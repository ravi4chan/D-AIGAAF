# Autonomy Constraints

## Purpose

The D-AIGAAF Autonomy Constraints framework defines the controls and limitations that prevent an AI-enabled capability from exercising autonomy beyond its assessed and authorised operational envelope.

The central principle is:

> **Autonomy must be constrained by explicit technical, operational, environmental, human and governance controls so that capability cannot silently become authority.**

Autonomy constraints convert the authorised boundary into enforceable operating conditions.

---

## 1. Core Model

```text
Mission
   ↓
Risk & Consequence
   ↓
Autonomy Assessment
   ↓
Autonomy Boundary
   ↓
Constraints
   ↓
Controls
   ↓
Testing & Evidence
   ↓
Assurance
   ↓
Operational Authorisation
   ↓
Employment & Monitoring
```

Constraints should be established before operational employment and continuously monitored thereafter.

---

## 2. Definition

An autonomy constraint is a technical, procedural, operational or governance mechanism that limits:

- what the system may decide;
- what it may recommend;
- what it may execute;
- when it may operate;
- where it may operate;
- under what conditions it may operate;
- how long it may operate;
- what data it may use;
- what authority it may exercise;
- how it may adapt;
- how it may recover;
- how it may escalate.

---

## 3. Constraint Hierarchy

Constraints should generally be considered in layers:

1. Mission constraints
2. Legal and policy constraints
3. Operational constraints
4. Human-authority constraints
5. Technical constraints
6. Data constraints
7. Environmental constraints
8. Security constraints
9. Temporal constraints
10. Recovery and fail-safe constraints

A robust design should avoid reliance on a single constraint.

---

## 4. Capability Constraint

The system should expose only the functions required for the authorised mission.

Unnecessary capability increases:

- attack surface;
- misuse potential;
- uncertainty;
- operational complexity;
- authority ambiguity.

Where practical, unused capabilities should be disabled, isolated or otherwise constrained.

---

## 5. Mission Constraint

The system should operate only within the approved mission and use case.

Constraints should prevent or detect:

- mission expansion;
- objective substitution;
- unauthorised tasking;
- unauthorised reuse;
- scope escalation.

A capability authorised for one mission should not automatically be considered authorised for another.

---

## 6. Action Constraint

The system should have an explicit action set.

This should distinguish:

### Permitted Actions

Actions the system is authorised to perform.

### Conditional Actions

Actions permitted only when defined conditions are satisfied.

### Human-Approval Actions

Actions requiring explicit human approval.

### Prohibited Actions

Actions the system must not perform.

The action set should be linked to the operational authorisation.

---

## 7. Decision Constraint

Decision autonomy should be constrained independently from action autonomy.

For example, a system may be authorised to:

- analyse information;
- identify patterns;
- provide recommendations;

while not being authorised to independently execute consequential actions.

This distinction should remain explicit throughout system design and operational employment.

---

## 8. Consequence Constraint

Autonomy should be constrained according to potential consequence.

Higher-consequence functions should generally require:

- stronger evidence;
- stronger human control;
- narrower operating conditions;
- greater monitoring;
- stronger intervention mechanisms;
- higher authority.

The constraint should reflect the worst credible consequence rather than only the expected outcome.

---

## 9. Human Authority Constraint

The system should operate within clearly defined human authority.

Controls should identify:

- who may authorise operation;
- who may approve consequential actions;
- who may change autonomy;
- who may suspend operation;
- who may invoke emergency procedures;
- who may restore operation.

Technical permissions should not be allowed to substitute for legitimate human authority.

---

## 10. Human-in-the-Loop Constraint

Where human approval is required, the system should enforce an actual approval gate rather than merely display a recommendation.

The design should establish:

- approval mechanism;
- decision time;
- required information;
- authority verification;
- intervention capability;
- audit record.

A nominal human role is not sufficient if the human cannot meaningfully influence the outcome.

---

## 11. Human-on-the-Loop Constraint

Where supervised autonomy is authorised, the supervising human should have:

- situational awareness;
- sufficient information;
- sufficient time;
- intervention capability;
- authority to intervene;
- ability to understand system state.

The workload created by supervision should be assessed.

---

## 12. Temporal Constraint

Autonomy may be limited by:

- maximum operating duration;
- maximum autonomous period;
- approval validity;
- review interval;
- mission expiry;
- inactivity period.

Automatic expiry may be used where appropriate to prevent indefinite operation.

---

## 13. Geographic Constraint

Where relevant, geographic constraints may include:

- approved areas;
- exclusion areas;
- boundary warnings;
- automatic restriction;
- transition to reduced autonomy;
- suspension outside the authorised area.

Geographic constraints should be assessed for degraded positioning and information conditions.

---

## 14. Environmental Constraint

The capability should have defined operating conditions.

These may include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic environment;
- infrastructure;
- sensor availability;
- communications;
- information quality.

When conditions move outside the validated envelope, predefined restrictions should apply.

---

## 15. Sensor Constraint

Sensor-dependent autonomy should be constrained by:

- required sensors;
- minimum sensor quality;
- sensor integrity;
- sensor availability;
- redundancy;
- sensor disagreement;
- sensor degradation.

Loss of a critical sensor should trigger predefined behaviour.

---

## 16. Data Constraint

Data constraints should define:

- permitted sources;
- permitted data types;
- data freshness;
- data quality;
- provenance;
- integrity requirements;
- access permissions.

The system should not silently substitute unvalidated data sources when required information is unavailable.

---

## 17. Information-Integrity Constraint

The system should account for the possibility that information may be:

- incomplete;
- incorrect;
- manipulated;
- stale;
- conflicting;
- misleading.

Where confidence falls below the validated threshold, the system should communicate uncertainty and, where appropriate, reduce autonomy.

---

## 18. Communications Constraint

The system should define behaviour for:

```text
Normal Communications
        ↓
Degraded Communications
        ↓
Intermittent Communications
        ↓
Communications Loss
```

Possible constraints include:

- reduced autonomy;
- restricted action set;
- mandatory human confirmation when available;
- controlled continuation;
- safe state;
- suspension.

Communications loss should never silently create additional authority.

---

## 19. Information-Access Constraint

Access to external information or services should be explicitly controlled.

The system should not assume that:

- internet access is always available;
- external services are trustworthy;
- external information is current;
- external dependencies are authorised.

Operational use without external connectivity should be assessed separately where relevant.

---

## 20. Security Constraint

Security controls should constrain:

- access;
- privileges;
- interfaces;
- dependencies;
- update mechanisms;
- administrative functions;
- external connections.

Security controls should prevent unauthorised users or components from increasing autonomy or authority.

---

## 21. Supply-Chain Constraint

Critical dependencies should be identified and controlled.

Relevant constraints include:

- approved suppliers;
- component provenance;
- model provenance;
- software provenance;
- dependency versions;
- update authority;
- signing and integrity;
- change notification.

A third-party component capable of materially changing system behaviour should be subject to appropriate assurance.

---

## 22. Configuration Constraint

Autonomy should be tied to an approved configuration baseline.

Relevant controls may cover:

- model version;
- software version;
- hardware;
- sensors;
- data;
- permissions;
- autonomy settings;
- dependencies.

Unauthorised configuration changes should be detectable and, where practical, prevented.

---

## 23. Update Constraint

Updates should be classified according to their effect on system behaviour.

A change that does not materially affect behaviour may follow a lighter process.

A change that may affect:

- decision behaviour;
- autonomy;
- safety;
- security;
- human control;
- boundary enforcement;

should receive appropriate revalidation, assurance and potentially reauthorisation.

Opaque changes to model behaviour should not be treated as automatically insignificant.

---

## 24. Adaptation Constraint

Adaptive behaviour should be bounded.

The system should define:

- what may adapt;
- what may not adapt;
- permitted adaptation range;
- monitoring;
- rollback;
- human notification;
- reassessment criteria.

Adaptation must not silently expand the authorised operational envelope.

---

## 25. Learning Constraint

Where a system can learn or update from operational data, governance should establish:

- whether learning is permitted during operation;
- approved data sources;
- learning limits;
- validation requirements;
- rollback mechanisms;
- authority for activating learned behaviour.

A system should not acquire new consequential behaviour merely because new data becomes available.

---

## 26. Escalation Constraint

The system must not independently increase:

- mission scope;
- autonomy;
- permissions;
- consequence;
- geographic area;
- access privileges;
- operational authority.

Escalation should require appropriate human authority or a narrowly defined pre-authorised protective mechanism.

---

## 27. Resource Constraint

Autonomy may be constrained by available:

- computing;
- energy;
- communications;
- storage;
- sensor capacity;
- human attention;
- external dependencies.

Resource degradation should have predefined effects on autonomy where relevant.

---

## 28. Dependency Constraint

Critical dependencies should have defined operating limits.

These may include:

- communications;
- positioning;
- external data;
- software libraries;
- cloud or remote services;
- authentication;
- timing services;
- supporting infrastructure.

Loss or degradation of a critical dependency should trigger the defined response.

---

## 29. Rate Constraint

Where appropriate, systems may be constrained by:

- action frequency;
- decision frequency;
- number of simultaneous actions;
- rate of adaptation;
- rate of resource consumption.

Rate constraints can limit cascading effects and reduce the consequences of erroneous or unstable behaviour.

---

## 30. Scope Constraint

The scope of autonomous operation should be explicitly bounded.

Scope may cover:

- mission;
- task;
- geographic area;
- objects or entities;
- systems;
- time;
- data;
- resources;
- actions.

A system should not infer broader authority from a broad technical capability.

---

## 31. Interface Constraint

Interfaces should expose only the permissions required for authorised operation.

Controls may include:

- least privilege;
- role-based access;
- approval gates;
- command validation;
- interface isolation;
- privilege separation.

An AI system should not receive unrestricted access merely because it technically supports a function.

---

## 32. Command and Approval Constraint

Where human approval is required, the system should verify:

- identity;
- authority;
- command validity;
- relevant context;
- approval state.

The system should maintain sufficient records to establish who authorised a significant action.

---

## 33. Override Constraint

Override mechanisms should be:

- accessible to authorised personnel;
- protected from unauthorised activation;
- tested;
- monitored;
- effective under relevant degraded conditions.

An override that exists only on paper does not provide meaningful control.

---

## 34. Fail-Safe Constraint

Fail-safe should establish a defined lower-authority state.

It should specify:

- functions that stop;
- functions that continue;
- remaining permissions;
- human authority;
- recovery requirements;
- evidence preservation.

Fail-safe is a last-resort protective control and does not replace proper assurance.

---

## 35. Degraded-Mode Constraint

The system should define multiple operating states where appropriate.

For example:

```text
FULL OPERATION
      ↓
LIMITED OPERATION
      ↓
ADVISORY
      ↓
RESTRICTED
      ↓
SUSPENDED
      ↓
SAFE STATE
```

Each state should have defined permissions and authority.

---

## 36. Constraint Enforcement

Constraints may be implemented through:

### Technical Controls

- software policies;
- permissions;
- access controls;
- interface restrictions;
- automated checks;
- configuration controls;
- geographic controls.

### Procedural Controls

- operating procedures;
- approval processes;
- supervision;
- training;
- checklists.

### Governance Controls

- policy;
- delegated authority;
- operational authorisation;
- review;
- audit.

The preferred approach is defence in depth.

---

## 37. Constraint Independence

Where consequence is high, critical constraints should not depend entirely on the same component whose behaviour they are intended to constrain.

Independent or separately controlled mechanisms may provide greater assurance.

This principle should be applied proportionately to risk and system architecture.

---

## 38. Constraint Monitoring

Monitoring should identify:

- constraint activation;
- constraint failures;
- attempted violations;
- repeated constraint triggers;
- unexpected permission use;
- unexpected autonomy;
- boundary proximity;
- degraded conditions.

Monitoring should support timely intervention.

---

## 39. Constraint Violation

A constraint violation occurs when the system or operator causes operation outside an established constraint.

Possible responses include:

```text
Detect
  ↓
Alert
  ↓
Assess
  ↓
Reduce Autonomy
  ↓
Restrict / Isolate
  ↓
Suspend / Safe State
  ↓
Investigate
  ↓
Reassess
```

Response severity should reflect consequence and urgency.

---

## 40. Constraint Failure

A constraint can fail without the system actually crossing the boundary.

Examples include:

- a monitoring control stops working;
- an override becomes unavailable;
- a permission check fails;
- a sensor required for a constraint becomes unreliable;
- a geographic control loses confidence.

Constraint failure should itself be treated as a risk condition.

---

## 41. Constraint Testing

Constraints should be tested under:

- normal conditions;
- degraded conditions;
- communications loss;
- sensor failure;
- information uncertainty;
- adversarial conditions;
- human workload;
- unexpected inputs;
- configuration changes;
- recovery conditions.

Testing should demonstrate that constraints actually limit behaviour.

---

## 42. Constraint Assurance

Assurance should establish:

- constraints are correctly defined;
- constraints correspond to operational authorisation;
- constraints are enforceable;
- constraint failures are detectable;
- humans can intervene;
- degraded modes operate correctly;
- fail-safe operates correctly;
- evidence remains valid.

---

## 43. Constraint and Risk

Constraints are a principal mechanism for reducing residual risk.

The relationship is:

**Inherent Risk → Constraints → Controls → Residual Risk**

Constraint design should focus particularly on:

- consequence;
- autonomy;
- human control;
- environmental uncertainty;
- information integrity;
- security;
- dependencies;
- loss of control.

---

## 44. Constraint and Operational Authorisation

Operational authorisation should explicitly reference material constraints.

The authorisation should establish:

- authorised autonomy;
- operating envelope;
- action permissions;
- human authority;
- environmental conditions;
- communication conditions;
- data requirements;
- adaptation restrictions;
- escalation restrictions;
- fail-safe requirements.

A constraint outside the authorisation is not automatically an authorised constraint.

---

## 45. Constraint and Risk Acceptance

Risk acceptance should consider whether the constraints relied upon are:

- implemented;
- tested;
- effective;
- monitored;
- within their validated assumptions.

If a critical constraint fails, the accepted residual-risk position may no longer remain valid.

---

## 46. Operational AI Advisor

The OAIA may advise on:

- operational necessity of constraints;
- practicality of restrictions;
- trade-offs between autonomy and mission effectiveness;
- human-control requirements;
- degraded-mode behaviour;
- consequences of constraint failure.

The OAIA does not independently approve the removal or relaxation of operational constraints.

**OAIA advises; authorised authority decides.**

---

## 47. Constraint Review

Constraints should be reviewed when:

- mission changes;
- use case changes;
- autonomy changes;
- environment changes;
- configuration changes;
- system performance changes;
- threats change;
- dependencies change;
- incidents occur;
- new evidence becomes available.

---

## 48. Relaxation of Constraints

Relaxing a constraint can increase risk.

A proposed relaxation should consider:

**Changed Constraint → Changed Exposure → Risk Assessment → Evidence → Assurance → Authority Decision**

Critical constraints should not be removed solely for convenience or performance optimisation.

---

## 49. Constraint Record

A D-AIGAAF Autonomy Constraint Record should include:

| Field | Description |
|---|---|
| Constraint ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Relevant mission |
| Use Case | Relevant use case |
| Constraint Type | Technical / Operational / Human / Governance |
| Description | Constraint definition |
| Trigger | Activation condition |
| Permitted State | Allowed operating state |
| Prohibited State | Prohibited condition |
| Enforcement | Enforcement mechanism |
| Authority | Responsible authority |
| Human Control | Human-control requirement |
| Dependencies | Relevant dependencies |
| Evidence | Supporting evidence |
| Test Status | Test result |
| Assurance | Assurance status |
| Monitoring | Monitoring requirement |
| Failure Response | Response to failure |
| Violation Response | Response to violation |
| Configuration | Applicable baseline |
| Review Date | Review date |
| Status | Current status |

---

## 50. Constraint Status

A constraint may be classified as:

- **Defined**
- **Implemented**
- **Tested**
- **Assured**
- **Conditionally Assured**
- **Failed**
- **Suspended**
- **Under Review**
- **Retired**

---

## 51. Reauthorisation

Reauthorisation should be considered when:

- critical constraints change;
- constraints are removed;
- constraint enforcement changes;
- autonomy increases;
- operating conditions expand;
- evidence becomes invalid;
- constraint failures materially change risk.

The governing sequence is:

**Change → Risk Assessment → TEVV → Assurance → Risk Acceptance → Reauthorisation**

---

## 52. Golden Thread

Autonomy constraints should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy Assessment → Human Control → Autonomy Boundary → Constraint Definition → Controls → Testing → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Constraint Failure / Change → Reassessment → Reauthorisation**

The record should allow an authorised reviewer to answer:

> **What prevented the AI system from exercising authority beyond its authorised autonomy, and what evidence demonstrates that those constraints work?**

---

## 53. Core Rules

1. **Autonomy must be constrained by explicit limits.**
2. **Technical capability must not silently become operational authority.**
3. **Mission, action, consequence, environmental and human-authority constraints should be explicit where relevant.**
4. **Higher-consequence autonomy requires stronger constraints.**
5. **Human approval must be technically meaningful where required.**
6. **The system must not independently expand mission, scope, permissions or authority.**
7. **Communications and information degradation must have predefined constraint responses where relevant.**
8. **Adaptive behaviour must remain within defined limits.**
9. **Critical constraints should be technically enforced where practicable.**
10. **High-consequence constraints should use defence in depth.**
11. **Constraint failure is itself a risk condition.**
12. **Constraints must be tested, not merely documented.**
13. **Constraint effectiveness must be monitored during operational employment.**
14. **Risk acceptance depends on the continued effectiveness of critical constraints.**
15. **Material constraint changes may require revalidation and reauthorisation.**
16. **Fail-safe is a last-resort constraint and does not replace assurance.**
17. **OAIA advises; authorised authority decides.**

---

## 54. Summary Model

```text
AUTHORised AUTONOMY
        ↓
DEFINED BOUNDARIES
        ↓
AUTONOMY CONSTRAINTS
        ↓
TECHNICAL + PROCEDURAL + GOVERNANCE CONTROLS
        ↓
TESTING
        ↓
EVIDENCE
        ↓
ASSURANCE
        ↓
OPERATIONAL AUTHORISATION
        ↓
EMPLOYMENT
        ↓
MONITORING
        ↓
CONSTRAINT FAILURE / CHANGE
        ↓
RISK REASSESSMENT
        ↓
REVALIDATION / REAUTHORISATION
```

The objective is to ensure that **AI autonomy remains deliberately constrained, technically bounded where practicable, operationally governed and continuously reassessed as conditions change.**
