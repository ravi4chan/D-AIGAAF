# 01 — Audit Planning and Scope

## 1. Purpose

This document defines how D-AIGAAF audits are planned, scoped, approved, conducted, and controlled.

It establishes a consistent basis for determining:

- why an audit is required;
- what will be audited;
- what will not be audited;
- which criteria apply;
- what evidence is expected;
- who is responsible;
- how audit effort is prioritised;
- when escalation is required.

This document complements `00_Audit_and_Evidence_Governance_Model.md` and does not replace detailed requirements for criteria assessment, evidence collection, testing, reporting, corrective action, records, or learning.

---

## 2. Planning Principle

An audit should be designed around a defined governance question.

Examples include:

- Are required controls operating effectively?
- Are operational authorisation conditions being followed?
- Does evidence support a material governance claim?
- Has a significant change been governed correctly?
- Are human-control requirements being maintained?
- Are critical dependencies appropriately governed?
- Have previous findings been effectively remediated?

The audit objective should determine the scope, criteria, evidence, and testing approach.

---

## 3. Audit Initiation

An audit may be initiated through:

- the approved audit programme;
- risk assessment;
- management request;
- governance review;
- operational authorisation requirement;
- significant change;
- incident;
- repeated assurance weakness;
- previous audit finding;
- regulatory or policy requirement;
- supplier concern;
- emerging threat;
- material uncertainty.

The reason for initiation should be recorded.

---

## 4. Audit Objective

Each audit should have a clear objective describing the intended determination.

The objective should identify:

1. the governance question;
2. the audit object;
3. relevant risks or requirements;
4. expected decision use;
5. material limitations, where known.

Objectives should be specific enough to prevent uncontrolled expansion of scope.

---

## 5. Audit Object

The audit object should be explicitly defined.

It may be:

- an AI capability;
- a model or AI component;
- an AI-enabled system;
- a mission use case;
- an operational deployment;
- a governance process;
- a control domain;
- an organisational function;
- a supplier;
- a dependency;
- an authorisation;
- a portfolio;
- a specific event or decision.

Where an audit concerns an AI capability, the object should normally be considered in its operational context rather than as an isolated model.

---

## 6. Audit Scope

Scope should define the boundaries of the audit.

At minimum, scope should address relevant:

- systems;
- AI components;
- missions;
- use cases;
- lifecycle stages;
- operational environments;
- autonomy levels;
- human roles;
- organisational units;
- suppliers;
- dependencies;
- configurations;
- time periods;
- records;
- applicable requirements.

---

## 7. Scope Boundaries

The audit plan should explicitly state:

### Included

The systems, processes, decisions, controls, evidence, people, environments, and periods included in the audit.

### Excluded

Items intentionally excluded from examination.

### Conditional

Items that may be examined if evidence, risk, or findings indicate that expansion is necessary.

Explicit boundaries reduce ambiguity and prevent conclusions from being interpreted more broadly than justified.

---

## 8. Scope Limitations

Known limitations should be documented before or during planning.

Examples include:

- unavailable records;
- inaccessible systems;
- incomplete historical data;
- unavailable personnel;
- restricted evidence;
- limited operational observation;
- incomplete configuration history;
- supplier access limitations;
- time constraints;
- insufficient independent evidence.

Limitations should be considered when determining the strength and intended use of audit conclusions.

---

## 9. Audit Criteria

Criteria should be identified before substantive assessment begins.

Potential criteria sources include:

- D-AIGAAF requirements;
- organisational policies;
- approved procedures;
- laws and regulations;
- contractual requirements;
- technical standards;
- security requirements;
- operational authorisation conditions;
- mission constraints;
- governance decisions;
- approved risk treatments.

The criteria should be sufficiently clear to support consistent conclusions.

---

## 10. Criteria Hierarchy

Where multiple criteria apply, their relationship should be established.

A practical hierarchy is:

**Applicable Law / Binding Requirement**
↓
**Policy and Governance Requirement**
↓
**Authorisation Condition**
↓
**Approved Control**
↓
**Procedure / Implementation Requirement**
↓
**Evidence of Operation**

Where criteria conflict, the conflict should be escalated rather than silently resolved by the audit team.

---

## 11. Risk-Based Planning

Audit planning should consider the risk associated with the audit object.

Relevant factors include:

- consequence of failure;
- likelihood;
- autonomy;
- human-control dependency;
- mission criticality;
- safety significance;
- security exposure;
- environmental complexity;
- data dependency;
- supplier dependency;
- change frequency;
- novelty;
- previous incidents;
- previous findings;
- assurance gaps;
- evidence weakness.

Higher-consequence areas should generally receive greater audit attention.

---

## 12. Risk and Consequence

Audit priority should reflect the potential consequence of governance failure.

Particular attention should be given where failure could result in:

- loss of human control;
- unauthorised consequential action;
- significant safety impact;
- mission-critical failure;
- security compromise;
- significant misinformation;
- uncontrolled autonomy;
- critical dependency failure;
- breach of authorisation conditions.

The absence of previous incidents should not by itself justify reduced audit priority.

---

## 13. Autonomy Consideration

Audit planning should consider the authorised and observed autonomy level.

Higher autonomy may require greater scrutiny of:

- authority boundaries;
- human oversight;
- intervention;
- override;
- safe-state behaviour;
- autonomy transitions;
- uncertainty;
- failure handling;
- operational constraints;
- decision traceability.

Where observed autonomy differs from authorised autonomy, the issue should be treated as potentially significant.

---

## 14. Human Authority Consideration

Planning should identify the human roles relevant to the audit.

These may include:

- commanders;
- decision-makers;
- operators;
- supervisors;
- technical personnel;
- AI assurance personnel;
- maintainers;
- authorising authorities;
- independent reviewers.

Audit scope should consider whether human authority is:

- explicit;
- understood;
- competent;
- available;
- traceable;
- exercisable;
- proportionate to consequence.

---

## 15. Operational Environment Consideration

Where an AI capability is operationally deployed, the audit plan should consider the environments in which governance claims are expected to hold.

Relevant conditions may include:

- normal operations;
- degraded operations;
- disconnected operations;
- variable communications;
- sensor degradation;
- environmental variability;
- adversarial conditions;
- human workload;
- dependency disruption.

The audit should not assume that evidence from one environment automatically demonstrates governance effectiveness in another.

---

## 16. Change Consideration

Recent or planned changes should be identified during planning.

These may involve:

- models;
- software;
- hardware;
- data;
- configurations;
- interfaces;
- autonomy;
- mission;
- environment;
- suppliers;
- dependencies;
- security controls;
- human roles;
- policies.

Significant or material changes may justify targeted audit or expanded scope.

---

## 17. Incident Consideration

Relevant incidents should be reviewed during planning.

The audit team should consider:

- whether an incident affects the audit objective;
- whether previous controls failed;
- whether corrective actions were completed;
- whether similar conditions may exist elsewhere;
- whether the incident indicates a systemic weakness.

Incident investigation and immediate response remain governed by Module 14.

---

## 18. Previous Findings

Previous findings should inform planning.

The audit team should consider:

- open findings;
- overdue corrective actions;
- recurring findings;
- ineffective corrective actions;
- finding severity;
- systemic patterns;
- changes since the previous audit.

Repeated findings may justify increased audit scope or governance escalation.

---

## 19. Audit Frequency

Audit frequency should be proportionate to risk and governance significance.

Factors supporting more frequent review include:

- high consequence;
- high autonomy;
- frequent change;
- weak evidence;
- unresolved findings;
- incidents;
- immature controls;
- significant supplier dependency;
- rapidly changing threat environment.

Periodic scheduling should not prevent triggered audits when conditions warrant earlier examination.

---

## 20. Triggered Audits

A triggered audit may be initiated following:

- serious incident;
- unexpected autonomy;
- loss of human control;
- material change;
- repeated control failure;
- significant security event;
- major environmental change;
- supplier failure;
- evidence integrity concern;
- regulatory requirement;
- significant governance dispute.

The trigger and rationale should be recorded.

---

## 21. Audit Team

The audit plan should identify required competencies.

Depending on scope, these may include:

- audit methodology;
- AI and machine learning;
- cybersecurity;
- data governance;
- safety;
- human factors;
- operational context;
- autonomy;
- software and systems engineering;
- legal or regulatory requirements;
- procurement and supply chain.

Technical specialists may support the audit without compromising audit independence.

---

## 22. Independence Assessment

Before substantive audit work begins, the audit team should consider:

- conflicts of interest;
- previous involvement in the audited activity;
- reporting relationships;
- personal or organisational incentives;
- dependency on management assertions;
- ability to challenge conclusions.

Any material independence concern should be resolved or disclosed.

---

## 23. Audit Authority and Access

The audit should establish appropriate authority to obtain:

- relevant records;
- system information;
- configuration information;
- evidence;
- personnel access;
- supplier information where applicable;
- operational observations;
- previous assessments.

Access restrictions should be documented and reflected in the audit conclusion where material.

---

## 24. Audit Methodology

The audit plan should define the broad methodology.

Possible methods include:

- document review;
- interviews;
- observation;
- sampling;
- walkthroughs;
- configuration review;
- record examination;
- control testing;
- evidence tracing;
- technical assessment;
- process testing;
- independent corroboration.

The methodology should be proportionate to the objective and risk.

---

## 25. Sampling

Where the audit involves sampling, the basis for selection should be documented.

Sampling may consider:

- risk;
- consequence;
- population size;
- transaction frequency;
- autonomy;
- operational criticality;
- previous findings;
- unusual cases;
- recent changes.

Sampling limitations should be considered when interpreting conclusions.

---

## 26. Evidence Planning

The audit plan should identify expected evidence sources.

Examples include:

- policies;
- approvals;
- risk assessments;
- authorisations;
- configuration records;
- test results;
- monitoring records;
- logs;
- training records;
- incident records;
- change records;
- supplier evidence;
- operational records.

Evidence collection and integrity requirements are addressed in `03_Evidence_Collection_and_Integrity.md`.

---

## 27. Audit Work Programme

A work programme should translate the audit objective and scope into planned activities.

It may identify:

- audit criteria;
- control areas;
- evidence required;
- testing activities;
- responsible auditors;
- specialists;
- timing;
- dependencies;
- review points.

The work programme may be adjusted when evidence or findings materially change the audit risk.

---

## 28. Audit Planning Outputs

The planning stage should produce, as appropriate:

- audit objective;
- audit scope;
- exclusions;
- criteria;
- risk assessment;
- audit methodology;
- evidence plan;
- audit team;
- independence assessment;
- timetable;
- communication arrangements;
- escalation conditions;
- reporting expectations.

---

## 29. Entry Meeting

Where appropriate, an entry meeting should establish:

- audit purpose;
- scope;
- criteria;
- timetable;
- access arrangements;
- responsibilities;
- communication routes;
- evidence expectations;
- escalation process.

The entry meeting should not be used to negotiate away applicable audit criteria.

---

## 30. Scope Changes

Scope should be controlled.

Expansion may be justified where:

- new evidence reveals material risk;
- a finding affects another control;
- a systemic issue becomes apparent;
- the original scope cannot support the intended conclusion;
- an incident or change materially affects the audit.

Material scope changes should be documented and approved through the applicable audit governance process.

---

## 31. Scope Creep

Uncontrolled expansion should be avoided.

Scope creep can:

- weaken audit focus;
- consume resources;
- delay critical findings;
- create inconsistent conclusions;
- obscure accountability.

Where additional issues are identified but do not justify immediate scope expansion, they may be recorded for future audit consideration.

---

## 32. Audit Criteria and Scope Traceability

Each significant audit activity should be traceable to:

**Objective → Scope → Criterion → Control → Evidence → Test → Finding/Conclusion**

This prevents audit work from becoming disconnected from the question the audit was intended to answer.

---

## 33. Audit Planning Risk

The audit itself can fail if planning is inadequate.

Planning weaknesses include:

- vague objectives;
- excessive scope;
- insufficient criteria;
- weak evidence planning;
- inadequate technical competence;
- unmanaged conflicts;
- failure to consider autonomy;
- failure to consider operational context;
- failure to consider recent changes;
- excessive dependence on management assertions.

Planning quality should therefore be subject to appropriate review.

---

## 34. Approval of Audit Plan

The audit plan should be approved by the appropriate audit authority before substantive work begins, except where urgent circumstances require otherwise.

Approval should establish that:

- objective is clear;
- scope is appropriate;
- criteria are identified;
- resources are sufficient;
- independence is acceptable;
- major risks are considered.

Emergency audits may use abbreviated planning with retrospective documentation where necessary.

---

## 35. Communication During Audit

Communication should establish appropriate routes for:

- evidence requests;
- clarification;
- emerging findings;
- urgent risks;
- scope changes;
- disagreements;
- escalation.

Communication should not compromise auditor independence or permit findings to be suppressed.

---

## 36. Urgent Issues

Where audit activity identifies an immediate and credible risk to:

- human safety;
- human control;
- authorised autonomy;
- operational security;
- mission-critical operation;
- legal or policy compliance;

the issue should be escalated without waiting for completion of the audit.

Audit escalation does not replace immediate operational response requirements.

---

## 37. Audit Conclusion Boundaries

The audit conclusion should remain within the approved scope and available evidence.

The audit should not claim:

- universal compliance from limited samples;
- operational suitability from documentary evidence alone;
- effectiveness from control existence alone;
- current validity from stale evidence;
- independence where material conflicts existed.

The strength of the conclusion should match the strength of the evidence.

---

## 38. Planning Review

Before fieldwork or substantive testing, the audit plan should be reviewed for:

- objective clarity;
- scope completeness;
- criteria suitability;
- risk coverage;
- evidence sufficiency;
- team competence;
- independence;
- operational relevance;
- expected decision use.

Material deficiencies should be corrected before proceeding where practicable.

---

## 39. Relationship to Other Module 16 Documents

This document establishes planning and scope.

Detailed requirements are addressed separately:

- `02_Audit_Criteria_and_Control_Assessment.md` — criteria and control assessment;
- `03_Evidence_Collection_and_Integrity.md` — evidence collection and integrity;
- `04_Audit_Testing_and_Findings.md` — audit testing and findings;
- `05_Audit_Independence_and_Challenge.md` — independence and challenge;
- `06_Nonconformity_Corrective_Action_and_Follow_Up.md` — corrective action and follow-up;
- `07_Audit_Reporting_and_Governance_Assurance.md` — reporting;
- `08_Audit_Records_Traceability_and_Retention.md` — records;
- `09_Audit_Learning_and_Continuous_Improvement.md` — learning.

---

## 40. Relationship to the D-AIGAAF Lifecycle

Audit planning should use information generated by:

- risk and autonomy assessment;
- TEVV;
- operational environment assessment;
- operational authorisation;
- operational employment;
- continuous assurance;
- incident management;
- change and reauthorisation.

Audit findings should subsequently feed those governance processes where relevant.

---

## 41. Core Planning Model

D-AIGAAF uses the following planning sequence:

**Trigger / Programme → Objective → Audit Object → Risk → Scope → Criteria → Evidence Plan → Methodology → Team & Independence → Work Programme → Approval → Audit**

This sequence should provide a controlled foundation for objective and evidence-based audit.

---

## 42. Core Rule

**An audit should be planned around a clearly defined governance question, bounded scope, applicable criteria, relevant risk, appropriate evidence, and sufficient independence. The scope and strength of the audit conclusion must never exceed what the approved objective, available evidence, and audit methodology can justify.**

---

## 43. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation → Audit Planning → Audit → Findings → Corrective Action → Verification**
