# Autonomy Transitions

## Purpose

The D-AIGAAF Autonomy Transitions framework defines how an AI-enabled capability moves between different levels or states of autonomy during its lifecycle and operational employment.

The central principle is:

> **Autonomy transitions are changes in operational authority and risk exposure and must therefore be explicitly defined, controlled, monitored and, where material, authorised.**

A transition may occur because of:

- mission conditions;
- environmental change;
- human direction;
- system performance;
- communications status;
- information quality;
- security conditions;
- detected faults;
- loss of control;
- predefined safety rules;
- emergency conditions;
- configuration or system changes.

---

## 1. Core Transition Model

```text
Authorised Autonomy
        ↓
Operating Condition
        ↓
Transition Trigger
        ↓
Transition Assessment
        ↓
Defined Transition
        ↓
New Autonomy State
        ↓
Monitoring
        ↓
Return / Escalate / Restrict / Suspend
```

A transition should never create authority that was not already authorised.

---

## 2. Autonomy Levels

D-AIGAAF uses the following working autonomy scale:

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

These are working constructs and should be mapped to applicable national, defence, legal and doctrinal terminology before formal adoption.

---

## 3. Autonomy State

Autonomy level and operational state should be treated separately.

For example, a system assessed as technically capable of A4 may currently be operating at A2 because of:

- degraded communications;
- poor information quality;
- environmental conditions;
- human workload;
- temporary restrictions;
- increased uncertainty.

Therefore:

**Technical Capability ≠ Current Autonomy State ≠ Authorised Autonomy**

---

## 4. Transition Types

Transitions may be:

1. Human-directed;
2. Pre-authorised automatic;
3. System-initiated protective;
4. Emergency;
5. Scheduled;
6. Condition-triggered;
7. Maintenance or configuration driven.

Any transition that increases operational consequence or authority requires particular scrutiny.

---

## 5. Upward Transitions

An upward transition increases autonomy or operational authority.

Examples include:

```text
A1 → A2
A2 → A3
A3 → A4
A4 → A5
```

An upward transition should require evidence that:

- the transition is permitted;
- the conditions for transition are satisfied;
- the new state has been assessed;
- required human authority is available;
- relevant controls are functioning;
- the new risk remains within accepted limits.

A system should not independently move to a materially higher autonomy level merely because it detects that it could do so.

---

## 6. Downward Transitions

A downward transition reduces autonomy or authority.

Examples include:

```text
A4 → A3
A3 → A2
A2 → A1
A1 → A0
```

Downward transitions can be used as risk controls when:

- uncertainty increases;
- environmental conditions degrade;
- communications are lost;
- sensors become unreliable;
- system performance deteriorates;
- human control becomes less effective;
- a security concern emerges.

Where pre-authorised, automatic reduction of autonomy may be an important protective control.

---

## 7. Human-Directed Transitions

A human with appropriate authority may direct an autonomy transition.

The transition should be:

- within delegated authority;
- clearly communicated;
- technically executable;
- recorded where material;
- consistent with the operational authorisation.

Human direction does not remove the requirement for the receiving autonomy state to remain within the authorised envelope.

---

## 8. Automatic Protective Transitions

A system may be authorised to automatically reduce autonomy when predefined conditions are met.

Examples include:

- loss of required communications;
- critical sensor degradation;
- unacceptable uncertainty;
- detected system fault;
- boundary proximity;
- security alert;
- failure of human-control conditions.

Automatic protective transitions should normally reduce rather than expand authority.

---

## 9. Condition-Triggered Transitions

A transition may be linked to measurable conditions.

The transition specification should define:

- trigger;
- threshold;
- detection method;
- current state;
- destination state;
- permitted actions during transition;
- human notification;
- recovery criteria.

Triggers should be validated during testing.

---

## 10. Environmental Transitions

Autonomy may need to change when the operational environment changes.

Relevant factors include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic conditions;
- communications;
- infrastructure;
- sensor conditions;
- information availability.

A capability should not assume that autonomy validated in one environment remains valid in another.

---

## 11. Information-Quality Transitions

Information quality can affect autonomy.

Indicators may include:

- stale information;
- conflicting information;
- missing information;
- uncertain source provenance;
- sensor disagreement;
- unexpected data distributions.

Where information quality falls below the validated threshold, the system may transition to:

- lower autonomy;
- human review;
- restricted operation;
- suspension.

---

## 12. Communications Transitions

The transition model should explicitly account for:

```text
Communications Available
        ↓
Degraded
        ↓
Intermittent
        ↓
Lost
```

Each state should have predefined autonomy behaviour.

Loss of communications should not automatically imply that the system may continue with unrestricted autonomy.

---

## 13. Human-Control Transitions

Autonomy should change if meaningful human control is no longer available.

Relevant conditions include:

- loss of required personnel;
- excessive workload;
- insufficient decision time;
- loss of situational awareness;
- inability to intervene;
- unclear authority;
- human-system interface failure.

Where human control is a condition of authorisation, loss of that condition may require immediate reduction in autonomy.

---

## 14. Security-Triggered Transitions

Security events may require an autonomy transition.

Examples include:

- suspected compromise;
- anomalous behaviour;
- integrity failure;
- unauthorised access;
- dependency compromise;
- unexpected system modification.

Possible responses include:

**Normal → Restricted → Reduced Autonomy → Isolated → Suspended → Safe State**

The appropriate response depends on consequence and evidence.

---

## 15. Loss-of-Control Transitions

Loss of control should trigger predefined transition behaviour.

The general model is:

```text
Controlled
   ↓
Degraded
   ↓
Restricted
   ↓
Emergency
   ↓
Safe State
   ↓
Recovered
   ↓
Revalidated
   ↓
Reauthorised
```

The system should not automatically return to a higher autonomy state simply because the immediate fault has disappeared.

---

## 16. Recovery Transitions

Recovery should be treated as a separate transition process.

Before returning to a higher autonomy state, the responsible authority should determine whether:

- the cause is understood;
- the system is stable;
- controls are functioning;
- human control is restored;
- relevant evidence remains valid;
- the operational environment remains within bounds;
- risk remains acceptable.

---

## 17. Escalation Restrictions

An autonomy transition must not become a mechanism for authority escalation.

The system should not independently transition to a state that:

- expands mission scope;
- increases consequence;
- removes human approval;
- accesses new authority;
- bypasses safeguards;
- changes operational objectives.

Any such transition should require explicit authorised human decision unless covered by a narrowly defined emergency mechanism.

---

## 18. Emergency Transitions

Emergency procedures may permit predefined protective transitions.

For example:

```text
Normal Operation
      ↓
Critical Condition
      ↓
Pre-authorised Protective Action
      ↓
Reduced Autonomy / Safe State
      ↓
Human Review
```

Emergency authority should be:

- narrowly defined;
- pre-authorised;
- time-limited;
- proportionate;
- recorded;
- subject to post-event review.

Where delay could create unacceptable harm, immediate protective action may be necessary under the applicable pre-authorised emergency procedure.

---

## 19. Transition Authority

Each material transition should identify who may:

- initiate;
- approve;
- supervise;
- cancel;
- override;
- review;
- restore.

Authority should correspond to the consequence of the resulting autonomy state.

---

## 20. Transition Preconditions

Before an upward transition, applicable preconditions should be satisfied.

These may include:

- mission remains unchanged;
- authorised operating area;
- environmental conditions;
- required sensors available;
- information quality acceptable;
- communications requirements satisfied;
- human authority available;
- intervention capability functional;
- system configuration valid;
- monitoring operational;
- risk within accepted limits.

---

## 21. Transition Postconditions

After a transition, the system should establish that:

- the intended state was reached;
- permissions match the new state;
- controls are active;
- monitoring is active;
- human operators understand the new state;
- relevant records were created;
- the system remains within its authorised envelope.

---

## 22. Transition Hysteresis

Where conditions fluctuate around a threshold, repeated rapid transitions may create instability.

Transition logic should therefore consider:

- minimum persistence period;
- confirmation criteria;
- minimum time between transitions;
- stable-state requirements;
- human confirmation where appropriate.

This is particularly relevant where frequent switching could increase human workload or operational uncertainty.

---

## 23. Human Awareness

Material autonomy transitions should be visible to the responsible human authority.

The interface should communicate, where relevant:

- current autonomy;
- previous autonomy;
- transition trigger;
- reason;
- new permissions;
- restrictions;
- required human action.

A hidden transition can undermine meaningful human control.

---

## 24. Transition Logging

Material transitions should be recorded.

The record should capture:

- timestamp;
- system;
- mission;
- previous state;
- new state;
- trigger;
- authority;
- relevant conditions;
- system configuration;
- human action;
- outcome;
- subsequent review.

Logs should support accountability and reconstruction of significant events.

---

## 25. Transition Testing

Transitions should be tested under:

- normal conditions;
- degraded conditions;
- communications loss;
- sensor failure;
- information uncertainty;
- adversarial conditions;
- human workload;
- system faults;
- boundary conditions;
- recovery scenarios.

Testing should establish both:

**Transition correctness**

and

**Transition safety**

---

## 26. Transition Assurance

Assurance should establish that:

- transition conditions are correctly detected;
- transitions occur as specified;
- prohibited transitions cannot occur;
- human authority is respected;
- protective transitions work;
- degraded states are stable;
- recovery works;
- transition records are reliable.

---

## 27. Transition and Risk

Autonomy transitions can materially change risk.

The relationship is:

**Transition → Changed Autonomy → Changed Exposure → Risk Reassessment**

A transition that increases consequence, autonomy or operational exposure may require additional assurance or authority.

---

## 28. Transition and Human Control

Human control should be reassessed whenever a transition changes:

- decision authority;
- action authority;
- intervention requirements;
- decision time;
- workload;
- information requirements.

A human who can supervise A3 may not necessarily be able to provide meaningful control at A4 under the same conditions.

---

## 29. Transition and Operational Authorisation

Operational authorisation should define permitted transitions.

It should specify:

- starting autonomy;
- permitted destination states;
- transition triggers;
- required human authority;
- prohibited transitions;
- environmental conditions;
- monitoring;
- suspension triggers.

A transition outside the authorised envelope should be treated as an authorisation issue, not merely a technical event.

---

## 30. Transition and Risk Acceptance

Risk acceptance should explicitly account for permitted autonomy transitions.

For example:

**Risk accepted at A2 ≠ automatic acceptance at A4**

Similarly:

**Risk accepted in Environment E1 ≠ automatic acceptance in Environment E5**

Transition permissions should therefore remain linked to the scope of the accepted risk.

---

## 31. Operational AI Advisor

The OAIA may advise on:

- operational implications of transitions;
- whether conditions justify a transition;
- human-control requirements;
- mission and environmental effects;
- risk implications;
- whether additional assurance is required.

The OAIA does not independently grant operational authority.

**OAIA advises; authorised authority decides.**

---

## 32. Configuration and Updates

A software, model or configuration update may alter transition behaviour.

Changes should be assessed for effects on:

- transition triggers;
- thresholds;
- autonomy states;
- permissions;
- safeguards;
- fail-safe behaviour;
- recovery behaviour.

If behaviour changes materially, appropriate TEVV, assurance and reauthorisation should follow.

---

## 33. Continuous Monitoring

Transition monitoring should identify:

- unexpected transitions;
- repeated transitions;
- failed transitions;
- delayed transitions;
- prohibited transitions;
- transition loops;
- unexplained state changes;
- transitions caused by unexpected conditions.

Unexpected transition behaviour should trigger investigation and, where necessary, restriction or suspension.

---

## 34. Transition Failure

Potential failure modes include:

- transition does not occur when required;
- transition occurs too late;
- transition occurs too early;
- transition reaches the wrong state;
- transition increases autonomy unexpectedly;
- human is not informed;
- override fails;
- transition logic oscillates;
- recovery restores excessive authority;
- transition occurs outside authorisation.

Transition failure should be treated as a risk and assurance issue.

---

## 35. Autonomy Transition Record

A D-AIGAAF Autonomy Transition Record should include:

| Field | Description |
|---|---|
| Transition ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Relevant mission |
| Use Case | Relevant use case |
| Previous State | Starting autonomy |
| New State | Destination autonomy |
| Trigger | Reason for transition |
| Conditions | Conditions observed |
| Authority | Responsible authority |
| Preconditions | Conditions required |
| Postconditions | Conditions confirmed |
| Human Control | Human-control status |
| Risk Status | Relevant risk position |
| Configuration | Applicable baseline |
| Evidence | Supporting evidence |
| Monitoring | Monitoring requirements |
| Recovery | Recovery criteria |
| Outcome | Transition result |
| Review | Review requirement |
| Status | Current status |

---

## 36. Transition Status

A transition may be classified as:

- **Authorised**
- **Conditionally Authorised**
- **Protective**
- **Emergency**
- **Restricted**
- **Failed**
- **Unexpected**
- **Unauthorised**
- **Under Review**

---

## 37. Reauthorisation

Reauthorisation may be required when:

- a new autonomy state is introduced;
- transition permissions materially change;
- transition behaviour changes;
- risk changes materially;
- mission changes;
- operating environment changes;
- human-control assumptions change;
- incidents invalidate existing evidence.

The governing sequence is:

**Change → Assessment → TEVV → Assurance → Risk Acceptance → Reauthorisation**

---

## 38. Golden Thread

Autonomy transitions should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy Assessment → Human Control → Boundary Definition → Transition Rules → Controls → Testing → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Transition Event → Reassessment → Reauthorisation**

The record should allow an auditor or authorised reviewer to determine:

> **Why did the system change autonomy, who or what triggered the change, what authority permitted it, what conditions existed, and what happened afterward?**

---

## 39. Core Rules

1. **Autonomy transitions are operationally significant events.**
2. **Technical capability does not authorise an autonomy transition.**
3. **Every material transition should have defined conditions and authority.**
4. **Upward autonomy transitions require stronger scrutiny than downward protective transitions.**
5. **Protective reduction of autonomy may be pre-authorised where appropriate.**
6. **The system must not independently escalate its mission or authority.**
7. **Environmental, information, communications and human-control changes may require autonomy reduction.**
8. **Emergency transitions should be narrow, pre-authorised and reviewable.**
9. **Material transitions should be visible to the responsible human authority.**
10. **Material transitions should be logged and reconstructable.**
11. **Transition logic must be tested under normal, degraded and adversarial conditions.**
12. **Recovery does not automatically restore higher autonomy.**
13. **Risk acceptance must cover the autonomy states and transitions actually authorised.**
14. **Material changes to transition behaviour may require revalidation and reauthorisation.**
15. **OAIA advises; authorised authority decides.**
16. **Unexpected or unauthorised transitions should trigger appropriate restriction, investigation and reassessment.**

---

## 40. Summary Model

```text
CURRENT AUTONOMY STATE
        ↓
OPERATING CONDITIONS
        ↓
TRIGGER DETECTED
        ↓
TRANSITION RULE
        ↓
AUTHORITY / PRE-AUTHORISED CONTROL
        ↓
NEW AUTONOMY STATE
        ↓
HUMAN AWARENESS
        ↓
MONITORING
        ↓
RECOVERY / FURTHER TRANSITION / RESTRICTION
        ↓
REASSESSMENT
        ↓
REAUTHORISATION WHERE REQUIRED
```

The objective is to ensure that **autonomy can change when operational conditions change, but the change itself remains bounded by explicit rules, evidence, human authority and continuous assurance.**
