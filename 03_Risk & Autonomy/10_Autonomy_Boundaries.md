# Autonomy Boundaries

## Purpose

The D-AIGAAF Autonomy Boundaries framework defines the limits within which an AI-enabled capability may exercise decision or action autonomy.

The central principle is:

> **Technical capability does not create operational authority. Autonomy must be explicitly bounded, tested, assured and authorised for the specific mission and conditions in which it will be employed.**

The core relationship is:

```text
Technical Capability
        ↓
Tested Autonomy
        ↓
Assured Autonomy
        ↓
Authorised Autonomy
        ↓
Operational Employment
        ↓
Continuous Monitoring
```

---

## 1. Definition

An autonomy boundary is a defined limit on what an AI-enabled capability may decide, recommend, initiate, execute, modify or continue without additional human authority.

An autonomy boundary may constrain:

- decisions;
- actions;
- time;
- geography;
- mission scope;
- objects or entities;
- data;
- systems;
- environmental conditions;
- adaptation;
- escalation;
- recovery;
- interfaces;
- human authority.

---

## 2. Capability Is Not Authority

A system may technically be capable of performing an action without being authorised to perform that action.

Therefore:

**Technical Capability ≠ Operational Authority**

Similarly:

**AI Output ≠ Human Decision ≠ Command Authority**

Autonomy must be separately established through:

**Capability → Testing → Assurance → Authorisation**

---

## 3. Autonomy Levels

D-AIGAAF uses the following working autonomy scale:

| Level | Description |
|---|---|
| A0 | No Meaningful AI Decision |
| A1 | Information / Observation |
| A2 | Analysis / Recommendation |
| A3 | Human-Authorised Action |
| A4 | Supervised Autonomous Action |
| A5 | Independent Consequential Autonomy |

These are D-AIGAAF working constructs and should be mapped to applicable national, defence, legal and doctrinal terminology before formal adoption.

An autonomy level alone does not determine whether a capability is authorised.

---

## 4. Multi-Dimensional Autonomy

Autonomy should not be represented by a single label alone.

Relevant dimensions include:

### Decision Autonomy

How independently the system determines an output, recommendation or decision.

### Action Autonomy

How independently the system executes an action.

### Temporal Autonomy

How long the system may operate without human intervention.

### Scope Autonomy

How broadly the system may operate within the mission.

### Adaptation Autonomy

Whether the system can modify its behaviour in response to changing conditions.

### Escalation Autonomy

Whether the system can initiate actions that increase mission consequence or authority.

### Recovery Autonomy

Whether the system can independently respond to failures or abnormal conditions.

### Authority Autonomy

What permissions the system can exercise without additional human approval.

---

## 5. Autonomy Boundary Dimensions

Each material capability should consider boundaries across:

- mission;
- use case;
- geography;
- environment;
- time;
- data;
- sensors;
- communications;
- human authority;
- decision type;
- action type;
- autonomy level;
- system configuration;
- dependencies;
- security;
- adaptation;
- escalation;
- recovery.

---

## 6. Mission Boundary

The capability should operate only for the approved mission and use case.

The system should not independently:

- change the mission;
- create a new mission;
- pursue a different objective;
- expand mission scope;
- reinterpret authority beyond the approved purpose.

A technically possible alternative use does not automatically become an authorised use.

---

## 7. Geographic Boundary

Where relevant, autonomy may be restricted to defined geographic areas.

Controls may include:

- approved operating areas;
- exclusion areas;
- boundary alerts;
- automatic restriction;
- transition to reduced autonomy;
- human review.

Geographic boundaries should be assessed for reliability under degraded positioning or information conditions.

---

## 8. Environmental Boundary

Autonomy may depend on environmental conditions.

Relevant conditions may include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic environment;
- infrastructure;
- communications;
- sensor availability;
- information quality.

If conditions move outside the validated envelope, the capability should have predefined behaviour.

Possible responses include:

- warning;
- increased human supervision;
- reduced autonomy;
- controlled degradation;
- restriction;
- suspension;
- fail-safe.

---

## 9. Temporal Boundary

Autonomy may be limited by time.

Controls may specify:

- maximum autonomous duration;
- authorised operating period;
- review intervals;
- expiry of mission authority;
- automatic transition to human control;
- suspension after a defined period without confirmation.

Temporal limits are particularly relevant where operational conditions can change rapidly.

---

## 10. Data Boundary

The system should have defined limits on:

- data sources;
- data types;
- data age;
- data quality;
- data sensitivity;
- permitted data combinations.

The capability should not assume that all available information is valid merely because it is technically accessible.

---

## 11. Sensor Boundary

Sensor-dependent autonomy should account for:

- sensor availability;
- sensor integrity;
- sensor quality;
- conflicting sensors;
- sensor degradation;
- loss of independent sources.

Where sensor reliability becomes inadequate, autonomy may need to reduce.

---

## 12. Communications Boundary

Autonomy should define what happens when communications:

- are available;
- become degraded;
- are delayed;
- are lost;
- are compromised.

The system should have predefined behaviour for communications loss.

Possible responses include:

- continue within narrow limits;
- reduce autonomy;
- return to human control;
- restrict operation;
- enter a safe state.

---

## 13. Human Authority Boundary

Autonomy must explicitly define which decisions remain with humans.

This should identify:

- decision authority;
- action authority;
- approval requirements;
- intervention authority;
- emergency authority;
- suspension authority;
- escalation authority.

Human authority should be explicit rather than inferred from system design.

---

## 14. Consequence Boundary

Higher-consequence actions should generally have stronger autonomy constraints.

The assessment should consider:

- potential loss of life;
- serious harm;
- property damage;
- mission failure;
- strategic consequences;
- critical infrastructure;
- cascading effects.

Autonomy should be matched to consequence.

> **The more consequential the action, the stronger the evidence and authority required for autonomous execution.**

---

## 15. Decision-Type Boundary

Different decisions may require different autonomy levels.

For example:

```text
Information Collection
        ↓
Analysis
        ↓
Recommendation
        ↓
Planning
        ↓
Human-Authorised Action
        ↓
Supervised Autonomous Action
        ↓
Independent Consequential Action
```

A capability authorised for analysis should not automatically be authorised for action.

---

## 16. Action Boundary

Where a system can execute actions, the authorised action set should be explicit.

The boundary should identify:

- permitted actions;
- prohibited actions;
- conditions for action;
- required human approval;
- maximum consequence;
- escalation restrictions;
- recovery requirements.

A system should not infer additional action authority from available interfaces or permissions.

---

## 17. Escalation Boundary

The system should not independently escalate its authority or mission consequence.

It should not independently:

- increase autonomy;
- expand mission scope;
- broaden geographic scope;
- access additional authority;
- remove approval requirements;
- disable safeguards;
- create new objectives.

Any material escalation should require an authorised human decision or explicitly pre-authorised emergency mechanism.

---

## 18. Adaptation Boundary

Adaptive systems require particular attention.

The governance process should determine:

- what the system may adapt;
- what it may not adapt;
- whether adaptation affects behaviour;
- whether adaptation is reversible;
- whether adaptation can change autonomy;
- whether adaptation can affect safety or security;
- whether human approval is required.

Self-modification or behaviour-changing adaptation should not silently expand the authorised operational envelope.

---

## 19. Recovery Boundary

Recovery autonomy should also be bounded.

A system may be permitted to:

- restore non-consequential functions;
- switch to a degraded mode;
- use approved redundancy;
- re-establish communications;
- return to a defined safe state.

Recovery should not automatically grant new mission or action authority.

---

## 20. Authority Boundary

Authority should be explicitly represented as:

```text
Technical Capability
        ↓
Permitted Function
        ↓
Tested Boundary
        ↓
Assured Boundary
        ↓
Authorised Boundary
```

The authorised boundary should be narrower than or equal to the assured boundary.

A capability should not be authorised beyond what the evidence supports.

---

## 21. Boundary Enforcement

Where technically practicable, boundaries should be enforced through system controls rather than relying solely on instructions.

Possible mechanisms include:

- access control;
- permissions;
- policy enforcement;
- geographic restrictions;
- autonomy controls;
- interface restrictions;
- configuration controls;
- data restrictions;
- approval gates;
- monitoring;
- automatic degradation.

The strongest controls combine technical and procedural mechanisms.

---

## 22. Boundary Monitoring

Operational monitoring should identify:

- boundary proximity;
- boundary crossings;
- attempted boundary violations;
- unexpected scope expansion;
- unexpected autonomy;
- unexpected actions;
- configuration changes.

Boundary monitoring should generate records sufficient to reconstruct significant events.

---

## 23. Boundary Violation

A boundary violation occurs when the system or its operator causes the capability to operate outside an authorised limit.

Responses may include:

- warning;
- human review;
- reduced autonomy;
- restriction;
- isolation;
- suspension;
- fail-safe;
- incident review.

The response should be proportionate to consequence and urgency.

---

## 24. Boundary Degradation

A boundary may become unreliable without an obvious violation.

Examples include:

- degraded navigation;
- uncertain location;
- unreliable sensors;
- changing environmental conditions;
- uncertain information;
- loss of communications;
- degraded monitoring.

Where boundary confidence decreases, the capability may need to move to a more restrictive operating state.

---

## 25. Human Override

Human override should be:

- technically possible where required;
- within the authority of the designated human;
- timely;
- tested;
- monitored;
- protected from accidental activation;
- protected from unauthorised use.

The ability to issue an override command is not sufficient if the system cannot reliably execute it.

---

## 26. Fail-Safe Boundary

The fail-safe state should itself be defined as an autonomy boundary.

It should establish:

- what functions stop;
- what functions continue;
- what authority remains;
- whether human control is required;
- how recovery occurs;
- what evidence is preserved.

Fail-safe should be treated as a last-resort protective mechanism.

---

## 27. Degraded-Mode Boundary

A capability may have multiple operating states:

```text
FULL AUTONOMY
      ↓
LIMITED AUTONOMY
      ↓
ADVISORY / HUMAN-CONTROLLED
      ↓
RESTRICTED
      ↓
SUSPENDED
      ↓
SAFE STATE
```

Each state should define its own:

- permitted functions;
- autonomy;
- human authority;
- environmental limits;
- monitoring;
- transition criteria.

---

## 28. Boundary Transitions

Transitions between autonomy states should be governed.

Transitions may be:

- human initiated;
- system initiated under pre-authorised rules;
- automatically triggered by defined safety conditions.

System-initiated transitions should not increase authority without explicit authorisation.

A system may be permitted to automatically reduce autonomy as a protective measure where this has been pre-authorised.

---

## 29. Emergency Boundary

Emergency procedures may establish pre-authorised actions for urgent protective situations.

These should define:

- trigger;
- authorised actor or mechanism;
- permitted action;
- maximum authority;
- time limit;
- reporting;
- review.

Emergency authority should be narrow and purpose-specific.

---

## 30. Boundary Testing

Autonomy boundaries should be tested under:

- normal conditions;
- degraded conditions;
- communications loss;
- information degradation;
- adversarial conditions;
- human workload;
- sensor failure;
- dependency loss;
- unexpected inputs;
- configuration changes.

Testing should determine whether the system remains within its authorised envelope.

---

## 31. Boundary Assurance

Assurance should establish:

- boundaries are clearly defined;
- boundaries are technically or procedurally enforceable;
- boundary controls operate;
- boundary violations are detectable;
- humans can intervene where required;
- degraded modes work;
- fail-safe works;
- evidence supports the authorised autonomy.

---

## 32. Boundary and Risk

Autonomy boundaries are a risk treatment.

The relationship is:

**Consequence + Autonomy + Environment + Human Control → Boundary Requirements**

Narrower boundaries can reduce:

- consequence exposure;
- uncertainty;
- autonomy risk;
- environmental risk;
- dependency risk;
- human-control burden.

---

## 33. Boundary and Operational Authorisation

Operational authorisation should specify the authorised autonomy boundary.

At minimum:

**Capability × Mission × Environment × Autonomy × Human Authority**

The authorised boundary should include:

- permitted autonomy;
- prohibited autonomy;
- permitted actions;
- prohibited actions;
- operating conditions;
- human approval requirements;
- intervention requirements;
- monitoring;
- suspension triggers.

---

## 34. Boundary and Risk Acceptance

Risk acceptance should apply only within defined boundaries.

Acceptance of risk at A2 does not automatically accept risk at A4.

Acceptance in one environment does not automatically accept risk in another.

Acceptance for one mission does not automatically extend to another.

---

## 35. Boundary and Operational AI Advisor

The OAIA may advise on:

- operational meaning of autonomy boundaries;
- feasibility of restrictions;
- consequences of boundary changes;
- degraded-mode transitions;
- human-control requirements;
- environmental limitations;
- operational trade-offs.

The OAIA does not create or independently expand operational authority.

**OAIA advises; authorised authority decides.**

---

## 36. Configuration

Autonomy boundaries should be tied to the assessed configuration.

Relevant elements may include:

- model;
- software;
- hardware;
- sensors;
- data;
- interfaces;
- autonomy settings;
- permissions;
- dependencies.

Material configuration changes may require boundary reassessment.

---

## 37. Change Management

Changes should be assessed for their potential effect on autonomy.

Material changes may include:

- new model;
- model update;
- software update;
- new sensor;
- new interface;
- new dependency;
- changed data;
- changed autonomy setting;
- changed mission;
- changed environment.

Behaviour determines change significance.

---

## 38. Reauthorisation

A material change to an autonomy boundary may require:

**Risk Reassessment → TEVV → Assurance → Risk Acceptance → Reauthorisation**

Previous authority should not automatically extend to a materially changed autonomy configuration.

---

## 39. Boundary Record

A D-AIGAAF Autonomy Boundary Record should include:

| Field | Description |
|---|---|
| Boundary ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Configuration | Assessed configuration |
| Autonomy Level | A0–A5 |
| Decision Authority | Permitted decision autonomy |
| Action Authority | Permitted action autonomy |
| Temporal Limit | Maximum duration |
| Geographic Limit | Geographic boundary |
| Environmental Limit | Environmental boundary |
| Data Limit | Approved data boundary |
| Communications | Required communications conditions |
| Human Authority | Human decision/action authority |
| Intervention | Intervention requirements |
| Adaptation | Permitted adaptation |
| Escalation | Escalation restrictions |
| Recovery | Recovery authority |
| Fail-Safe | Safe-state conditions |
| Monitoring | Monitoring requirements |
| Violation Response | Boundary-violation response |
| Evidence | Supporting evidence |
| Assurance | Assurance status |
| Risk Acceptance | Linked acceptance |
| Operational Authorisation | Linked authority |
| Review Date | Review date |
| Status | Current status |

---

## 40. Failure Modes

D-AIGAAF should guard against:

- treating technical capability as authority;
- defining autonomy only as a single label;
- failing to define action boundaries;
- allowing mission expansion;
- allowing geographic expansion;
- allowing silent autonomy escalation;
- allowing self-modification to expand authority;
- assuming communications are always available;
- failing to define degraded modes;
- relying only on procedural boundaries;
- failing to test boundary enforcement;
- allowing human override that does not work in practice;
- treating fail-safe as sufficient assurance;
- extending one authorisation to another mission;
- extending one environment's authority to another;
- allowing material changes without boundary reassessment.

---

## 41. Golden Thread

Autonomy boundaries should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy Assessment → Human Control → Boundary Definition → Controls → Testing → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Boundary Violation / Change → Reassessment → Reauthorisation**

The record should make it possible to answer:

> **What was the system technically capable of doing, what was tested and assured, what autonomy was actually authorised, and what boundaries constrained that authority?**

---

## 42. Core Rules

1. **Technical capability does not create operational authority.**
2. **Autonomy must be explicitly defined and bounded.**
3. **Autonomy should be assessed across multiple dimensions.**
4. **Authorised autonomy must not exceed the assured autonomy supported by evidence.**
5. **Autonomy must be matched to consequence.**
6. **Mission, geographic, environmental, temporal and action boundaries should be explicit where relevant.**
7. **AI must not independently expand its authority or mission.**
8. **Boundary enforcement should use technical controls where practicable.**
9. **Human override must be real, timely and tested where required.**
10. **Communications loss and degraded information must have predefined autonomy responses where relevant.**
11. **Degraded modes should have defined autonomy and authority states.**
12. **Fail-safe should be defined as a last-resort protective boundary.**
13. **Boundary violations should generate an appropriate response and record.**
14. **Material changes may require boundary reassessment and reauthorisation.**
15. **Risk acceptance applies only within defined boundaries.**
16. **Operational authority remains with appropriately empowered human authority.**
17. **OAIA advises; authorised authority decides.**

---

## 43. Summary Model

```text
TECHNICAL CAPABILITY
        ↓
ACTUAL AUTONOMY
        ↓
AUTONOMY ASSESSMENT
        ↓
DEFINE BOUNDARIES
        ↓
TEST BOUNDARIES
        ↓
ASSURE BOUNDARIES
        ↓
ACCEPT RESIDUAL RISK
        ↓
AUTHORISE AUTONOMY
        ↓
OPERATIONAL EMPLOYMENT
        ↓
MONITOR
        ↓
BOUNDARY CHANGE / VIOLATION
        ↓
REASSESS
        ↓
REVALIDATE
        ↓
REAUTHORISE / RESTRICT / SUSPEND
```

The objective is to ensure that **AI autonomy remains bounded by explicit mission, operational, technical and human-authority limits, and that no increase in technical capability silently becomes an increase in operational authority.**
