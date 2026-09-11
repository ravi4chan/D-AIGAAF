# 02 — Audit Criteria and Control Assessment

## 1. Purpose

This document defines how D-AIGAAF audit criteria are established, interpreted, mapped to controls, and assessed.

It provides a structured basis for determining whether governance requirements are:

- applicable;
- adequately defined;
- translated into controls;
- implemented;
- operating as intended;
- effective for their intended purpose;
- supported by sufficient evidence.

This document complements `00_Audit_and_Evidence_Governance_Model.md` and `01_Audit_Planning_and_Scope.md`.

---

## 2. Assessment Principle

An audit should assess the relationship between requirements and controls rather than simply verify the presence of documents.

The basic chain is:

**Requirement → Control Objective → Control → Implementation → Evidence → Assessment → Conclusion**

A requirement should not be considered satisfied merely because a related policy, procedure, or system feature exists.

---

## 3. Audit Criteria

Audit criteria are the requirements or expectations against which the audit object is assessed.

Criteria may originate from:

- D-AIGAAF;
- applicable law;
- regulation;
- organisational policy;
- operational authorisation;
- contractual obligations;
- approved standards;
- technical requirements;
- mission constraints;
- risk treatment decisions;
- governance decisions.

Criteria should be identifiable and sufficiently precise to support objective assessment.

---

## 4. Criteria Applicability

Not every criterion applies to every AI capability.

Applicability should consider:

- mission;
- use case;
- consequence;
- autonomy;
- operational environment;
- human authority;
- data;
- security;
- lifecycle stage;
- supplier dependency;
- deployment status;
- applicable legal or policy obligations.

The basis for determining applicability should be recorded.

---

## 5. Criteria Hierarchy

Where multiple sources apply, criteria should be organised so that conflicts and dependencies are visible.

A practical structure is:

**Binding Requirement**
→ **Governance Requirement**
→ **Authorisation Condition**
→ **Control Objective**
→ **Control**
→ **Procedure**
→ **Evidence**

Where a lower-level control appears inconsistent with a higher-level requirement, the discrepancy should be escalated.

---

## 6. Requirement Interpretation

Criteria should be interpreted according to their intended governance purpose.

Interpretation should consider:

- wording;
- context;
- consequence;
- scope;
- applicable definitions;
- related requirements;
- operational conditions;
- approved exceptions.

Material ambiguity should be documented rather than silently resolved.

---

## 7. Control Objectives

A control objective describes what a control is intended to achieve.

Examples include:

- ensuring only authorised personnel can approve consequential use;
- preventing unauthorised autonomy;
- preserving evidence integrity;
- ensuring model changes are assessed;
- maintaining human intervention capability;
- ensuring operational boundaries are enforced;
- protecting critical AI dependencies.

Control objectives provide the bridge between requirements and implementation.

---

## 8. Control Definition

A control should describe the mechanism used to achieve the control objective.

Controls may be:

- preventive;
- detective;
- corrective;
- compensating;
- technical;
- procedural;
- organisational;
- human;
- contractual.

Controls may operate individually or as part of a control system.

---

## 9. Control Design

Control design assessment asks:

**If the control operates exactly as intended, is it reasonably capable of addressing the identified requirement or risk?**

Design assessment should consider:

- relevance;
- completeness;
- specificity;
- ownership;
- authority;
- timing;
- dependencies;
- failure modes;
- human factors;
- operational conditions.

A perfectly implemented but poorly designed control remains ineffective.

---

## 10. Control Implementation

Implementation assessment asks whether the designed control actually exists in the intended operating environment.

Examples include:

- required approval mechanisms are deployed;
- access controls are configured;
- procedures are established;
- human roles are assigned;
- monitoring mechanisms are operational;
- evidence records are generated;
- technical restrictions are implemented.

Documentation alone may not demonstrate implementation.

---

## 11. Control Operation

A control may exist and be implemented but fail to operate consistently.

Audit should examine whether:

- the control is actually used;
- required actions occur;
- responsibilities are understood;
- exceptions are handled;
- records are generated;
- failures are detected;
- escalation occurs where required.

Operating effectiveness should be assessed over an appropriate period where the control is recurring.

---

## 12. Control Effectiveness

Control effectiveness considers whether the control achieves its intended purpose in practice.

A useful progression is:

**Designed → Implemented → Operating → Effective**

Evidence should support the conclusion at the appropriate level.

---

## 13. Preventive Controls

Preventive controls aim to stop an undesirable condition before it occurs.

Examples include:

- authorisation gates;
- autonomy restrictions;
- access controls;
- configuration controls;
- deployment approval;
- prohibited-use restrictions;
- mandatory human approval.

Preventive controls are particularly important where consequences are severe and recovery may be difficult.

---

## 14. Detective Controls

Detective controls identify an undesirable condition after or while it occurs.

Examples include:

- monitoring;
- anomaly detection;
- audit logs;
- performance thresholds;
- security alerts;
- autonomy-state monitoring;
- incident reporting.

Detective controls should have defined response pathways.

Detection without an effective response may provide limited governance value.

---

## 15. Corrective Controls

Corrective controls reduce the effect of an identified failure.

Examples include:

- rollback;
- safe-state transition;
- suspension;
- corrective action;
- revalidation;
- reauthorisation;
- recovery procedures.

Corrective controls should be evaluated for timeliness and effectiveness.

---

## 16. Compensating Controls

A compensating control may be used where the preferred control cannot be implemented or temporarily cannot operate.

Compensating controls should:

- address the same or materially related risk;
- be explicitly approved;
- have defined scope;
- have an owner;
- have a defined duration where temporary;
- be supported by evidence;
- not create unacceptable residual risk.

---

## 17. Control Ownership

Every material control should have an accountable owner.

Ownership should identify responsibility for:

- design;
- implementation;
- operation;
- monitoring;
- maintenance;
- evidence;
- remediation.

Audit responsibility should remain distinct from control ownership.

---

## 18. Control Dependencies

Controls may depend on:

- people;
- software;
- hardware;
- data;
- communications;
- sensors;
- suppliers;
- identity systems;
- monitoring;
- other controls.

Audit should consider whether critical dependencies could undermine control effectiveness.

A control should not be considered effective merely because its immediate mechanism functions if a critical dependency can routinely defeat it.

---

## 19. Control Interaction

Individual controls may be effective only as part of a larger control system.

Examples include:

**Autonomy restriction + Human oversight + Intervention capability + Monitoring**

or:

**Change control + TEVV + Revalidation + Reauthorisation**

Audit should identify material control dependencies and interactions where relevant.

---

## 20. Control Failure Modes

Assessment should consider how controls may fail.

Potential failure modes include:

- control bypass;
- control unavailable;
- incorrect configuration;
- human non-compliance;
- automation failure;
- stale evidence;
- dependency failure;
- conflicting controls;
- excessive workload;
- unclear authority;
- degraded environment;
- adversarial manipulation.

Material failure modes should be reflected in findings or risk assessments where appropriate.

---

## 21. Control Mapping

Applicable requirements should be mapped to relevant controls.

A control mapping may use:

| Requirement | Control Objective | Control | Owner | Evidence | Assessment |
|---|---|---|---|---|---|
| Requirement A | Objective A | Control A | Owner A | Evidence A | Effective |
| Requirement B | Objective B | Control B | Owner B | Evidence B | Partial |
| Requirement C | Objective C | Control C | Owner C | Evidence C | Not demonstrated |

The mapping should remain traceable to the relevant D-AIGAAF governance domain.

---

## 22. One Requirement, Multiple Controls

A single requirement may depend on multiple controls.

For example:

**Requirement: Human authority must remain effective**

may require:

- defined decision rights;
- competent personnel;
- meaningful system information;
- intervention capability;
- override capability;
- autonomy monitoring;
- workload management;
- decision traceability.

Audit should assess whether the combined control system achieves the requirement.

---

## 23. One Control, Multiple Requirements

A single control may support multiple requirements.

For example, controlled configuration management may support:

- security;
- change management;
- TEVV;
- operational authorisation;
- auditability;
- continuous assurance.

Such relationships should be recorded where they materially affect assessment.

---

## 24. Evidence Expectations

Each material control should have identifiable evidence appropriate to its purpose.

Evidence may demonstrate:

- existence;
- implementation;
- operation;
- effectiveness;
- exception handling;
- corrective action.

Evidence should be assessed for:

- relevance;
- sufficiency;
- reliability;
- integrity;
- currency;
- provenance;
- traceability.

Detailed evidence collection requirements are addressed in `03_Evidence_Collection_and_Integrity.md`.

---

## 25. Management Assertions

Management statements may provide useful information but should not automatically be treated as independent evidence.

Where a material conclusion depends substantially on management assertion, the limitation should be identified.

Independent corroboration should be sought where proportionate to risk.

---

## 26. Testing Control Operation

Testing should determine whether the control operated as described.

Possible methods include:

- inspection;
- observation;
- inquiry;
- walkthrough;
- sampling;
- reperformance;
- configuration examination;
- log review;
- independent corroboration.

Testing should be appropriate to the nature of the control.

---

## 27. Sampling and Control Assessment

Where recurring controls are sampled, the audit should define:

- population;
- sample basis;
- selection method;
- period;
- criteria;
- exceptions;
- limitations.

Sampling results should not be extrapolated beyond what the methodology reasonably supports.

---

## 28. Exceptions

An exception is evidence that a control or requirement did not operate as expected.

Exceptions should be assessed for:

- isolated occurrence;
- recurrence;
- severity;
- duration;
- consequence;
- root cause;
- systemic significance.

Not every exception necessarily constitutes a formal nonconformity, but material exceptions should not be obscured.

---

## 29. Control Maturity

Where useful, control maturity may be assessed using stages such as:

1. **Absent** — no meaningful control exists.
2. **Defined** — control is documented.
3. **Implemented** — control exists in practice.
4. **Operating** — control operates consistently.
5. **Effective** — control achieves intended purpose.
6. **Adaptive** — control is monitored, improved, and responsive to change.

Maturity should not replace evidence-based control effectiveness assessment.

---

## 30. Control Assessment Outcomes

D-AIGAAF may use the following assessment outcomes:

- **Effective**
- **Largely Effective**
- **Partially Effective**
- **Ineffective**
- **Not Implemented**
- **Not Demonstrated**
- **Not Applicable**

The selected outcome should be supported by evidence and assessment rationale.

---

## 31. Not Demonstrated

A control may exist but still be classified as **Not Demonstrated** where evidence is insufficient to establish implementation or effectiveness.

This distinction is important.

Lack of evidence should not automatically be converted into a finding of complete control failure, but neither should it be treated as evidence that the control works.

---

## 32. Contradictory Evidence

Where evidence conflicts, the audit should not simply select the evidence supporting the preferred conclusion.

Conflicting evidence should be:

- identified;
- investigated;
- assessed for reliability;
- documented;
- reflected in the conclusion where unresolved.

Material contradiction may reduce assurance confidence or trigger further testing.

---

## 33. Control Effectiveness Under Stress

Where a control is expected to function in degraded, disconnected, adversarial, or otherwise challenging environments, audit should consider whether evidence demonstrates effectiveness under those conditions.

A control demonstrated only under nominal conditions should not automatically be considered effective across the full authorised operating envelope.

---

## 34. Human Controls

Human controls require specific consideration.

Audit should assess whether:

- the responsible person is identified;
- authority is understood;
- competence is adequate;
- relevant information is available;
- uncertainty is communicated;
- intervention is feasible;
- override is practicable;
- workload is manageable;
- decisions are traceable.

The mere presence of a human in the process does not demonstrate meaningful human control.

---

## 35. AI and Automated Controls

Automated controls should be assessed for:

- intended logic;
- configuration;
- coverage;
- failure modes;
- monitoring;
- override;
- dependency;
- update/change management.

Automation should not be assumed to be inherently more reliable than human control.

---

## 36. Control Effectiveness and Autonomy

For higher autonomy levels, audit should examine whether controls prevent capability from exceeding authorised autonomy.

Particular attention should be given to:

- autonomy state;
- transition conditions;
- boundaries;
- human authority;
- intervention;
- termination;
- monitoring;
- fail-safe behaviour.

Where observed autonomy exceeds authorised autonomy, immediate escalation may be required.

---

## 37. Control Effectiveness and Security

Security controls should be assessed not only for formal existence but for their ability to withstand relevant threats.

Assessment may consider:

- access control;
- integrity protection;
- adversarial inputs;
- supply-chain risk;
- configuration security;
- monitoring;
- incident response;
- recovery.

Security control assessment should remain aligned with Module 06.

---

## 38. Control Effectiveness and Change

Controls should be reassessed where changes may affect their operation.

Relevant changes include:

- AI model;
- data;
- software;
- hardware;
- configuration;
- interface;
- autonomy;
- environment;
- supplier;
- dependency.

A previously effective control may no longer be effective after a material change.

---

## 39. Control Effectiveness and Incidents

Incidents may provide evidence that a control failed, was bypassed, was insufficient, or was incorrectly designed.

Incident evidence should therefore inform control assessment where relevant.

The existence of an incident does not automatically establish that every related control was ineffective; the causal relationship should be assessed.

---

## 40. Control Assessment and Assurance

Control assessment contributes to assurance but does not independently establish overall assurance.

Overall assurance should consider:

- control effectiveness;
- evidence quality;
- residual risk;
- human control;
- autonomy;
- environment;
- security;
- dependencies;
- operational performance;
- recent change;
- incidents.

---

## 41. Findings from Control Assessment

A control assessment may produce:

- no finding;
- observation;
- improvement opportunity;
- control weakness;
- nonconformity;
- significant finding;
- critical finding.

Classification should be based on defined criteria and consequence.

Detailed finding requirements are addressed in `04_Audit_Testing_and_Findings.md`.

---

## 42. Control Assessment Review

Material control assessments should be subject to appropriate review.

Review should consider:

- evidence sufficiency;
- consistency;
- criteria interpretation;
- testing quality;
- independence;
- severity;
- conclusion logic.

Reviewer challenge should be documented where material disagreements occur.

---

## 43. Control Assessment Record

For material controls, the audit record should be capable of showing:

**Requirement → Applicability → Control Objective → Control → Owner → Implementation → Evidence → Testing → Effectiveness → Finding/Conclusion**

This provides the core traceability needed for governance assurance.

---

## 44. Integration with D-AIGAAF

Control assessment should draw on and feed:

- Module 03 — Risk & Autonomy;
- Module 04 — AI Lifecycle;
- Module 05 — Data & Information;
- Module 06 — AI Security;
- Module 07 — Supply Chain & Sovereignty;
- Module 08 — Human Authority;
- Module 09 — TEVV;
- Module 10 — Operational Environment;
- Module 11 — Operational Authorisation;
- Module 12 — Operational Employment;
- Module 13 — Continuous Assurance;
- Module 14 — Incident & Fail-Safe;
- Module 15 — Change & Reauthorisation.

---

## 45. Core Assessment Model

D-AIGAAF uses:

**Requirement → Applicability → Control Objective → Control Design → Implementation → Operation → Effectiveness → Evidence → Finding → Corrective Action**

The assessment should identify where in this chain the governance claim is supported or breaks down.

---

## 46. Core Rule

**A requirement is not demonstrated merely because a policy, control, approval, or system feature exists. D-AIGAAF requires audit to determine whether applicable requirements are translated into appropriately designed controls, implemented, operating, effective, and supported by sufficient and reliable evidence.**

---

## 47. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation → Audit Criteria → Control Assessment → Findings → Corrective Action → Verification**
