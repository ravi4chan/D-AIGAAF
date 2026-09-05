# Risk Treatment

## Purpose

The D-AIGAAF Risk Treatment framework defines how identified AI-related risks are addressed before and during operational employment.

Risk treatment converts the assessed risk position into specific actions, controls, operating conditions and authority decisions.

The central principle is:

> **Risk should be treated at the capability, mission and operational-context level, not merely at the model level.**

The treatment process is:

```text
Risk Identified
      ↓
Risk Assessed
      ↓
Treatment Options
      ↓
Controls Selected
      ↓
Controls Implemented
      ↓
Control Effectiveness Evidenced
      ↓
Residual Risk Assessed
      ↓
Risk Accepted / Rejected
      ↓
Operational Authority Decision
      ↓
Continuous Monitoring
```

---

## 1. Purpose of Risk Treatment

Risk treatment should:

- reduce unacceptable risk;
- prevent foreseeable failure;
- preserve human authority;
- constrain autonomy;
- protect mission effectiveness;
- protect personnel and infrastructure;
- preserve information integrity;
- strengthen security;
- manage uncertainty;
- establish appropriate operating conditions;
- support informed risk acceptance;
- provide evidence for operational authorisation.

Risk treatment should not be limited to documenting risks.

---

## 2. Treatment Principle

D-AIGAAF treats risk through a combination of:

- avoidance;
- reduction;
- control;
- sharing or transfer where appropriate;
- acceptance;
- monitoring.

No single treatment approach is universally appropriate.

The selected treatment should reflect:

**Consequence × Mission Criticality × Autonomy × Environment × Human Control × Threat × Uncertainty**

---

## 3. Risk Treatment Hierarchy

A preferred treatment hierarchy is:

```text
1. Avoid
   ↓
2. Eliminate or Reduce the Risk at Source
   ↓
3. Constrain Capability
   ↓
4. Add Preventive Controls
   ↓
5. Add Detective Controls
   ↓
6. Add Corrective / Recovery Controls
   ↓
7. Establish Human Controls
   ↓
8. Establish Operational Conditions
   ↓
9. Accept Residual Risk
   ↓
10. Continuously Monitor
```

The hierarchy should not prevent emergency measures or other controls where operational circumstances require them.

---

## 4. Risk Avoidance

Risk avoidance means changing or discontinuing the proposed use so that the unacceptable risk is no longer incurred.

Examples include:

- not deploying the capability for a high-consequence use case;
- removing autonomous action;
- excluding an unsafe environment;
- prohibiting use with unreliable data;
- replacing the AI capability with a lower-risk alternative;
- restricting the capability to advisory use.

Avoidance should be considered before attempting to manage risks that cannot reasonably be controlled.

---

## 5. Risk Reduction

Risk reduction lowers either:

- the probability of an adverse outcome;
- the consequence of an adverse outcome;
- or both.

Examples include:

- improving model performance;
- improving data quality;
- reducing autonomy;
- adding independent verification;
- improving operator training;
- increasing monitoring;
- narrowing the operational envelope;
- introducing redundancy;
- improving resilience;
- improving recovery mechanisms.

Risk reduction should be supported by evidence wherever practical.

---

## 6. Risk Controls

Controls are measures designed to prevent, detect, contain, correct or govern risk.

D-AIGAAF groups controls into four broad categories.

### 6.1 Preventive Controls

Designed to prevent undesirable behaviour.

Examples:

- access controls;
- least-authority permissions;
- input validation;
- model constraints;
- geographic boundaries;
- autonomy limits;
- approved-use restrictions;
- configuration controls.

### 6.2 Detective Controls

Designed to identify abnormal conditions.

Examples:

- anomaly detection;
- behaviour monitoring;
- integrity checks;
- audit logging;
- performance monitoring;
- boundary monitoring;
- human review.

### 6.3 Corrective Controls

Designed to contain or recover from an adverse condition.

Examples:

- autonomy reduction;
- controlled degradation;
- human intervention;
- isolation;
- suspension;
- recovery procedures;
- fail-safe.

### 6.4 Governance Controls

Designed to ensure appropriate authority and accountability.

Examples:

- approval;
- risk acceptance;
- operational authorisation;
- independent assurance;
- configuration management;
- review requirements;
- audit;
- reauthorisation.

---

## 7. Control Design

Each material risk should have one or more controls appropriate to its nature.

Control design should consider:

- risk being addressed;
- control objective;
- control owner;
- implementation mechanism;
- operating conditions;
- dependencies;
- human role;
- autonomy;
- expected effectiveness;
- verification method;
- evidence required;
- monitoring;
- failure condition;
- response if the control fails.

A control that exists only on paper should not be treated as an effective control.

---

## 8. Defence in Depth

High-consequence AI-enabled capabilities should not depend on a single control.

Where appropriate, protection should exist across multiple layers:

```text
Model
 ↓
Software
 ↓
System
 ↓
Data
 ↓
Interface
 ↓
Human
 ↓
Operational Procedure
 ↓
Command Authority
 ↓
Monitoring
 ↓
Fail-Safe
```

The objective is to prevent a single failure from producing an unacceptable outcome.

---

## 9. Least Authority

AI-enabled capabilities should receive only the permissions and authority necessary for the approved mission and use case.

Least-authority controls may include:

- limited data access;
- limited system access;
- limited geographic scope;
- limited temporal scope;
- limited autonomy;
- limited action authority;
- limited interfaces;
- limited permissions.

Authority should not expand merely because a technical capability exists.

---

## 10. Autonomy as a Risk Treatment

Reducing autonomy can be an effective risk treatment.

Examples include:

- A4 → A3;
- A3 → A2;
- autonomous action → human confirmation;
- continuous autonomy → bounded autonomy;
- broad autonomy → mission-specific autonomy.

Autonomy reduction should be considered when:

- uncertainty increases;
- human control deteriorates;
- communications become unreliable;
- information integrity is uncertain;
- the environment moves outside validated conditions;
- threat conditions change;
- system performance degrades.

Autonomy reduction is a control, not necessarily a permanent design decision.

---

## 11. Human Control as a Risk Treatment

Human control can reduce risk where the human has:

- appropriate authority;
- sufficient information;
- relevant competence;
- enough decision time;
- meaningful ability to intervene;
- appropriate independence;
- clear accountability.

However:

> **Adding a human to a process does not automatically create meaningful human control.**

The effectiveness of human control must be assessed and evidenced.

---

## 12. Operational Constraints as Controls

Operational constraints can be used to reduce risk.

Examples include:

- approved mission types;
- defined geographic areas;
- environmental restrictions;
- restricted operating periods;
- approved information sources;
- minimum communications conditions;
- minimum sensor conditions;
- maximum workload conditions;
- minimum human staffing;
- defined autonomy limits.

Constraints should be enforceable where technically practicable.

---

## 13. Controlled Degradation

A capability should have defined degraded operating modes where continued operation remains useful and safe.

Possible responses include:

```text
Full Capability
      ↓
Reduced Capability
      ↓
Reduced Autonomy
      ↓
Human-Only / Advisory Mode
      ↓
Restricted Operation
      ↓
Suspension
      ↓
Fail-Safe
```

Controlled degradation should be tested rather than assumed.

---

## 14. Fail-Safe

Fail-safe should provide a final protective mechanism when normal controls are insufficient.

A fail-safe may:

- stop a consequential function;
- reduce autonomy;
- transfer control;
- isolate the system;
- place the system in a defined safe state;
- prevent further unauthorised action.

Fail-safe should not be treated as the primary risk treatment.

It is a last-resort mechanism within a broader defence-in-depth strategy.

---

## 15. Risk Transfer or Sharing

Some risks may be shared or transferred through:

- supplier contractual obligations;
- service agreements;
- insurance where applicable;
- external assurance;
- infrastructure providers;
- specialist technical support.

However:

> **Transfer of responsibility does not automatically transfer operational accountability.**

The operational authority remains responsible for decisions within its delegated authority.

Supplier assurance does not replace independent assurance.

---

## 16. Residual Risk

After controls are implemented, the remaining risk is residual risk.

The relationship is:

```text
Inherent Risk
      ↓
Risk Treatment
      ↓
Controls
      ↓
Control Effectiveness
      ↓
Residual Risk
```

Residual risk should be assessed against:

- mission consequence;
- mission criticality;
- autonomy;
- environment;
- human control;
- security;
- information integrity;
- uncertainty;
- dependencies;
- operational boundaries.

Residual risk must be explicitly understood before acceptance.

---

## 17. Control Effectiveness

A control should be considered effective only to the extent that evidence demonstrates it works under relevant conditions.

Possible evidence includes:

- testing;
- verification;
- validation;
- evaluation;
- red-team activity;
- operational trials;
- monitoring data;
- incident history;
- independent assessment.

Control effectiveness may be:

- Effective;
- Effective With Conditions;
- Partially Effective;
- Ineffective;
- Not Assessed;
- Not Applicable.

---

## 18. Control Failure

Risk treatment should consider what happens when a control fails.

For each critical control, identify:

- failure mode;
- detection method;
- consequence;
- fallback control;
- human response;
- autonomy response;
- safe state;
- escalation authority;
- evidence requirement.

Critical controls should not rely on undocumented assumptions.

---

## 19. Risk Treatment for Uncertainty

Uncertainty should be treated as an operational risk factor.

Treatment may include:

- additional testing;
- additional information;
- independent verification;
- human review;
- reduced autonomy;
- narrower operational boundaries;
- increased monitoring;
- delayed deployment;
- additional assurance.

A system should not conceal uncertainty through confident outputs.

> **Uncertainty is information and should be communicated where it can affect a consequential decision.**

---

## 20. Risk Treatment for Information Integrity

Where information may be manipulated, incomplete or unreliable, controls may include:

- data provenance;
- integrity checks;
- source validation;
- independent sources;
- sensor cross-checking;
- anomaly detection;
- human verification;
- confidence/uncertainty indicators;
- restricted autonomy.

Information degradation should be considered in the operational environment rather than only in laboratory testing.

---

## 21. Risk Treatment for Security

Security controls may include:

- identity and access management;
- least privilege;
- secure configuration;
- network segmentation;
- integrity monitoring;
- software assurance;
- dependency management;
- supply-chain controls;
- adversarial testing;
- incident response;
- isolation mechanisms.

Security treatment should consider both external compromise and non-adversarial system behaviour.

---

## 22. Risk Treatment for Dependencies

Where a capability depends on external or supporting systems, treatment may include:

- redundancy;
- alternative dependencies;
- local processing;
- graceful degradation;
- dependency monitoring;
- contingency procedures;
- reduced autonomy;
- controlled shutdown.

Critical dependencies should be identified before operational authorisation.

---

## 23. Risk Treatment for Communications Loss

For capabilities that may operate without continuous communications, treatment should define:

- permitted autonomy during communications loss;
- duration of autonomous operation;
- restricted functions;
- human-control alternatives;
- recovery conditions;
- safe-state conditions.

Communications-denied scenarios should be included in relevant TEVV.

---

## 24. Risk Treatment for Environmental Change

A capability may perform differently when environmental conditions change.

Treatment may include:

- environmental operating limits;
- additional sensors;
- environmental monitoring;
- degraded modes;
- reduced autonomy;
- mission restrictions;
- additional testing;
- suspension outside the validated envelope.

Relevant conditions may include:

- terrain;
- weather;
- visibility;
- altitude;
- temperature;
- electromagnetic conditions;
- infrastructure availability;
- communications conditions.

The framework remains generic and does not prescribe mission-specific environmental thresholds.

---

## 25. Risk Treatment for Human Factors

Human-related risks may be treated through:

- training;
- competence requirements;
- interface improvements;
- workload management;
- decision-time requirements;
- independent review;
- automation-bias mitigation;
- clear authority;
- recording of significant decisions;
- operational procedures.

Human controls should be tested under realistic workload and time pressure where relevant.

---

## 26. Risk Treatment for Supply Chain

Supply-chain risks may be treated through:

- provenance requirements;
- supplier assurance;
- independent verification;
- software/component inventories;
- dependency mapping;
- update controls;
- configuration management;
- contractual controls;
- alternative suppliers;
- substitutability;
- support-continuity planning.

Critical suppliers should not become invisible dependencies.

---

## 27. Risk Treatment for Change

Changes should be assessed according to their potential effect on behaviour and operational risk.

Potentially material changes include:

- model changes;
- training changes;
- software changes;
- sensor changes;
- data changes;
- configuration changes;
- autonomy changes;
- interface changes;
- dependency changes;
- environmental changes;
- mission changes.

Minor changes may be handled through controlled processes where evidence demonstrates that behaviour and operational risk remain materially unchanged.

Material changes may require:

**Reassessment → Revalidation → Reauthorisation**

---

## 28. Risk Treatment During Operations

Risk treatment does not end at deployment.

Operational monitoring should identify:

- emerging risks;
- control degradation;
- changed environmental conditions;
- unexpected behaviour;
- new threats;
- new dependencies;
- human-control degradation;
- changes in mission;
- changes in performance;
- incidents.

Operational risk treatment may require immediate:

- restriction;
- reduced autonomy;
- increased human control;
- suspension;
- fail-safe;
- emergency protective action.

---

## 29. Emergency Risk Treatment

Emergency conditions may require rapid action.

Where delay could create unacceptable harm, pre-authorised emergency controls should permit appropriately empowered personnel to:

- reduce autonomy;
- suspend a capability;
- isolate a system;
- activate fail-safe;
- take other protective measures within established authority.

Emergency action should be:

- legally and organisationally grounded;
- predefined where practicable;
- proportionate;
- recorded;
- reviewed afterwards.

Emergency procedures should not become a mechanism for bypassing normal governance.

---

## 30. Risk Treatment Record

Each material risk treatment should be recorded.

A D-AIGAAF Risk Treatment Record should include:

| Field | Description |
|---|---|
| Risk ID | Unique risk identifier |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Risk Statement | Description of risk |
| Inherent Risk | Risk before treatment |
| Treatment Decision | Avoid / Reduce / Control / Transfer / Accept / Monitor |
| Treatment Rationale | Reason for selected approach |
| Control ID | Linked control |
| Control Description | Treatment measure |
| Control Type | Preventive / Detective / Corrective / Governance |
| Owner | Control owner |
| Implementation | How control is implemented |
| Dependencies | Supporting dependencies |
| Evidence | Evidence of effectiveness |
| Effectiveness | Assessed effectiveness |
| Residual Risk | Risk after treatment |
| Risk Acceptance | Acceptance decision |
| Authority | Authorised risk owner |
| Monitoring | Ongoing monitoring |
| Trigger | Reassessment trigger |
| Review Date | Next review |
| Status | Current status |

---

## 31. Risk Acceptance

Risk acceptance should occur only after reasonable treatment options have been considered.

The decision should identify:

- residual risk;
- rationale;
- authority;
- limitations;
- conditions;
- evidence;
- review period;
- reassessment triggers.

Risk acceptance is not equivalent to operational authorisation.

> **A risk may be accepted within the appropriate authority while the capability remains unauthorised for operational employment.**

---

## 32. Relationship to Operational Authorisation

Risk treatment supports operational authorisation by establishing:

- controls;
- operating conditions;
- residual risk;
- evidence;
- limitations;
- human-control requirements;
- autonomy restrictions;
- monitoring requirements.

Operational authorisation should consider whether the residual risk is acceptable **for the specific mission, environment, autonomy and human authority involved**.

---

## 33. Relationship to Assurance

Risk treatment determines what must be demonstrated.

The chain is:

**Risk → Treatment → Control → Test → Evidence → Assurance**

A control without evidence may remain an assurance gap.

Assurance should therefore evaluate whether the selected controls:

- exist;
- operate as intended;
- remain effective;
- are appropriate to the risk;
- work under relevant conditions.

---

## 34. Risk Treatment and the Operational AI Advisor

The OAIA may advise on:

- operational implications of risk treatments;
- feasibility of controls;
- autonomy reduction;
- human-control arrangements;
- environmental restrictions;
- degraded modes;
- operational trade-offs;
- interpretation of technical evidence.

The OAIA does not independently accept operational risk unless explicitly empowered under applicable governance.

**OAIA advises; authorised authority decides.**

---

## 35. Monitoring Risk Treatment

Controls should be monitored for:

- continued effectiveness;
- degradation;
- circumvention;
- unexpected interactions;
- changing threat conditions;
- changing operational conditions;
- dependency changes;
- configuration changes.

Monitoring should generate evidence that can feed:

**Risk Review → Assurance Review → Operational Authority**

---

## 36. Reassessment Triggers

Risk treatment should be reconsidered when:

- mission changes;
- use case changes;
- consequence changes;
- autonomy changes;
- environment changes;
- human-control conditions change;
- threats change;
- dependencies change;
- model/software changes;
- control effectiveness declines;
- incidents occur;
- assumptions are invalidated;
- legal or policy requirements change;
- evidence becomes outdated.

---

## 37. Failure Modes

D-AIGAAF should guard against:

- treating risk treatment as paperwork;
- accepting risk without considering alternatives;
- relying on one control;
- assuming controls are effective without evidence;
- treating human presence as a control;
- reducing autonomy without verifying the resulting behaviour;
- treating fail-safe as the primary control;
- ignoring dependency risk;
- ignoring environmental degradation;
- ignoring information integrity;
- ignoring supply-chain risk;
- transferring accountability to suppliers;
- allowing emergency procedures to bypass governance routinely;
- failing to reassess after material changes;
- allowing controls to become obsolete.

---

## 38. Golden Thread

Risk treatment must remain traceable through:

**Mission Need → Use Case → Risk → Treatment → Controls → Testing → Evidence → Assurance → Risk Acceptance → Authority → Employment → Monitoring → Change / Incident → Reassessment**

Every material control should be traceable back to the risk it addresses.

Every material residual risk should be traceable forward to the authority that accepted it and the conditions under which that acceptance remains valid.

---

## 39. Core Rules

1. **Risk treatment must address the capability in its mission context, not merely the model.**
2. **Avoidance should be considered before attempting to control unacceptable risk.**
3. **Controls should be proportionate to consequence, autonomy and operational exposure.**
4. **High-consequence systems should use defence in depth.**
5. **AI should receive only the authority necessary for the approved mission and use case.**
6. **Autonomy reduction is an important risk treatment where conditions deteriorate.**
7. **Human control is effective only when it is real, informed, timely and technically possible.**
8. **Controls must be evidenced rather than assumed effective.**
9. **Fail-safe is a last-resort protective mechanism.**
10. **Technical recovery does not automatically eliminate residual operational risk.**
11. **Supplier responsibility does not automatically transfer operational accountability.**
12. **Uncertainty should be treated as information relevant to risk.**
13. **Risk treatment must continue throughout operational employment.**
14. **Material changes require reassessment and may require revalidation and reauthorisation.**
15. **Risk acceptance does not itself grant operational authority.**
16. **Operational authority remains with the appropriately empowered human authority.**

---

## 40. Summary Model

```text
IDENTIFY RISK
      ↓
ASSESS INHERENT RISK
      ↓
CONSIDER AVOIDANCE
      ↓
SELECT TREATMENT
      ↓
DESIGN CONTROLS
      ↓
IMPLEMENT CONTROLS
      ↓
TEST CONTROL EFFECTIVENESS
      ↓
ASSESS RESIDUAL RISK
      ↓
ACCEPT / REJECT / FURTHER TREAT
      ↓
ASSURANCE
      ↓
OPERATIONAL AUTHORISATION
      ↓
EMPLOY
      ↓
MONITOR
      ↓
REASSESS
      ↓
REAUTHORISE / RESTRICT / SUSPEND / RETIRE
```

The objective is not to eliminate every risk.

The objective is to ensure that **material risks are identified, deliberately treated, evidenced, accepted only by appropriate authority, and continuously reassessed throughout the AI capability lifecycle.**
