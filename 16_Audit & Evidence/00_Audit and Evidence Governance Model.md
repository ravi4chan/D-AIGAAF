# 00 — Audit and Evidence Governance Model

## 1. Purpose

This document establishes the governance model for audit and evidence within D-AIGAAF.

It defines how an organisation independently examines whether AI governance arrangements, controls, decisions, evidence, authorisations, and operational practices remain compliant, effective, traceable, and accountable.

This document establishes the architecture for audit and evidence governance. Detailed audit planning, criteria assessment, evidence collection, testing, corrective action, reporting, records management, and learning are addressed in subsequent documents within Module 16.

---

## 2. Scope

The audit and evidence governance model applies across the AI lifecycle and operational governance system, including:

- strategy and governance;
- mission and use-case definition;
- risk and autonomy management;
- AI lifecycle activities;
- data and information governance;
- AI security;
- supply-chain and sovereignty controls;
- human authority;
- TEVV;
- operational environment;
- operational authorisation;
- operational employment;
- continuous assurance;
- incident and fail-safe management;
- change and reauthorisation;
- audit and evidence itself.

The model applies to AI capabilities, supporting systems, governance processes, people, suppliers, dependencies, records, and decisions where they contribute to an authorised AI capability.

---

## 3. Audit Purpose

Audit provides an independent and structured means of determining whether:

1. applicable requirements are identified and understood;
2. governance arrangements are operating as intended;
3. required controls exist and are implemented;
4. decisions and authorities are properly established;
5. evidence supports material governance claims;
6. operational practices remain within authorised boundaries;
7. identified risks are being governed;
8. exceptions and nonconformities are controlled;
9. corrective actions are effective;
10. accountability and traceability can be demonstrated.

Audit is therefore more than a documentation check.

A system may possess extensive documentation while still having ineffective controls. Conversely, an effective practice may lack sufficient evidence to demonstrate that it is consistently performed.

D-AIGAAF treats both control effectiveness and demonstrability as governance concerns.

---

## 4. Audit Principles

Audits should be governed by the following principles.

### 4.1 Independence

Audit activity should be sufficiently independent from the activity being audited to support objective conclusions.

### 4.2 Objectivity

Conclusions should be based on defined criteria and evidence rather than preference, assumption, or organisational status.

### 4.3 Risk-Based Prioritisation

Audit effort should reflect consequence, risk, autonomy, complexity, change, incidents, dependencies, and previous findings.

### 4.4 Evidence-Based Conclusions

Material conclusions should be supported by appropriate evidence.

### 4.5 Traceability

Audit conclusions should be traceable to criteria, evidence, findings, decisions, and responsible authorities.

### 4.6 Proportionality

Audit depth should be proportionate to the consequences and governance significance of the AI capability.

### 4.7 Timeliness

Evidence and audit conclusions should remain sufficiently current for the decision they support.

### 4.8 Challenge

Audit should provide constructive challenge rather than merely confirm management assertions.

### 4.9 Transparency of Limitations

Audit conclusions should identify material evidence gaps, uncertainty, scope limitations, and unresolved issues.

### 4.10 Accountability

Audit should preserve clear responsibility for findings, decisions, remediation, and acceptance of residual risk.

---

## 5. Audit Object

The audit object is the defined subject against which criteria are assessed.

Depending on purpose, an audit object may include:

- an AI capability;
- an AI-enabled system;
- a mission use case;
- an operational deployment;
- a governance process;
- an organisational function;
- a supplier or dependency;
- an authorisation;
- a control set;
- a lifecycle stage;
- a portfolio or programme;
- a specific decision or event.

The audit object should be explicitly identified before audit activity begins.

---

## 6. Auditable System

For D-AIGAAF purposes, the auditable system is broader than the AI model.

It may include:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Governance × Dependencies**

Audit should therefore consider the interactions between technical capability and the surrounding governance system.

A technically functioning model does not by itself demonstrate that the overall AI capability is governed appropriately.

---

## 7. Audit Universe

The audit universe is the population of governance areas, AI capabilities, processes, systems, suppliers, decisions, and operational activities that may be subject to audit.

The audit universe should be maintained so that the organisation can:

- identify what can be audited;
- assess relative significance;
- identify coverage gaps;
- prioritise audit resources;
- track recurring findings;
- identify systemic weaknesses;
- support an auditable governance programme.

The audit universe should be periodically reviewed as the AI portfolio, mission environment, threats, regulations, technology, and organisational responsibilities change.

---

## 8. Audit Programme

The audit programme establishes planned audit activity over an appropriate period.

It should consider:

- consequence of failure;
- risk level;
- autonomy level;
- operational criticality;
- mission importance;
- complexity;
- novelty;
- material changes;
- incidents;
- previous audit findings;
- assurance gaps;
- supplier dependencies;
- security concerns;
- regulatory or policy obligations;
- time since previous audit;
- evidence maturity.

Audit frequency should not be determined solely by calendar intervals.

---

## 9. Risk-Based Audit Prioritisation

Audit priority should increase where there is greater potential for:

- loss of human control;
- consequential or harmful action;
- significant mission failure;
- safety impact;
- security compromise;
- misleading or unreliable outputs;
- unauthorised autonomy;
- critical dependency failure;
- inadequate evidence;
- governance bypass;
- material configuration drift;
- repeated incidents or findings.

Risk-based prioritisation should also account for uncertainty.

A low observed incident rate should not automatically be interpreted as low risk where evidence coverage is weak.

---

## 10. Audit Criteria

Audit criteria define what is being assessed.

Criteria may originate from:

- D-AIGAAF requirements;
- organisational policy;
- applicable law;
- regulatory obligations;
- operational authorisation conditions;
- contractual requirements;
- technical standards;
- security requirements;
- mission constraints;
- approved procedures;
- documented controls;
- governance decisions.

Criteria should be sufficiently specific to support consistent assessment.

Detailed criteria and control assessment are addressed in `02_Audit_Criteria_and_Control_Assessment.md`.

---

## 11. Compliance

Compliance asks whether an applicable requirement has been met.

Examples include:

- required approval exists;
- required assessment was completed;
- required record was maintained;
- authorised conditions were followed;
- mandated control was implemented.

Compliance is necessary but not sufficient for effective governance.

A control can formally exist while failing to achieve its intended purpose.

---

## 12. Control Effectiveness

Control effectiveness asks whether a control is:

1. appropriately designed;
2. implemented;
3. operating as intended;
4. producing the intended governance effect.

Audit should distinguish between:

**Control exists → Control implemented → Control operates → Control is effective**

Evidence supporting only the first step should not automatically establish effectiveness.

---

## 13. Assurance

Assurance concerns justified confidence that governance claims remain supported.

Audit contributes to assurance but does not replace continuous assurance, TEVV, operational monitoring, or management responsibility.

A useful distinction is:

- **Compliance:** Was the requirement met?
- **Control effectiveness:** Does the control work?
- **Assurance:** How well justified is our confidence?
- **Authorisation:** Is the capability permitted to operate?
- **Operational readiness:** Is it ready for the intended use?

These are related but distinct determinations.

---

## 14. Evidence Governance

Evidence is the basis through which audit conclusions can be substantiated.

Evidence governance should address:

- relevance;
- sufficiency;
- reliability;
- integrity;
- authenticity;
- provenance;
- traceability;
- currency;
- completeness;
- independence;
- protection from alteration or loss.

Evidence should be evaluated in relation to the claim or criterion it is intended to support.

More evidence does not necessarily mean stronger evidence.

---

## 15. Evidence and Governance Claims

Audit should trace material claims through a structured chain:

**Requirement → Control → Claim → Evidence → Assessment → Finding/Conclusion → Decision**

Where evidence does not adequately support a claim, the limitation should be recorded rather than inferred away.

Negative, contradictory, incomplete, or stale evidence should remain visible to decision-makers.

---

## 16. Evidence Integrity

Evidence supporting consequential governance decisions should have appropriate integrity controls.

Depending on context, these may include:

- controlled records;
- timestamps;
- version identifiers;
- configuration identifiers;
- provenance;
- access controls;
- audit trails;
- change history;
- retention controls;
- evidence ownership;
- integrity verification.

Evidence integrity requirements should be proportionate to consequence and risk.

---

## 17. Audit Independence

Audit independence should be protected through appropriate organisational arrangements.

Independence considerations may include:

- separation from the activity being audited;
- avoidance of conflicts of interest;
- appropriate reporting lines;
- access to relevant evidence;
- authority to challenge management assertions;
- protection from inappropriate influence;
- escalation routes for unresolved disagreements.

Independence does not mean isolation from operational knowledge.

Auditors require sufficient technical, operational, governance, and AI literacy to understand the subject being examined.

Detailed independence and challenge arrangements are addressed in `05_Audit_Independence_and_Challenge.md`.

---

## 18. Audit Lifecycle

D-AIGAAF uses the following high-level audit lifecycle:

**Plan → Define Criteria → Collect Evidence → Test → Find → Challenge → Correct → Verify → Report → Learn**

Each stage should produce appropriate records.

The lifecycle should remain connected to the wider D-AIGAAF lifecycle rather than operate as an isolated compliance activity.

---

## 19. Audit Planning

Audit planning should establish:

- audit objective;
- audit object;
- scope;
- criteria;
- relevant risks;
- stakeholders;
- evidence requirements;
- sampling approach where applicable;
- independence arrangements;
- timetable;
- reporting expectations;
- escalation conditions.

Detailed planning requirements are addressed in `01_Audit_Planning_and_Scope.md`.

---

## 20. Audit Scope

Scope should clearly define:

- what is included;
- what is excluded;
- time period;
- systems and processes;
- configurations or versions;
- operational environments;
- missions or use cases;
- organisational units;
- suppliers and dependencies;
- evidence sources.

Scope limitations should be explicitly recorded.

An audit conclusion should not imply coverage beyond the approved scope.

---

## 21. Audit Evidence Model

Evidence may include:

### Governance Evidence
- policies;
- approvals;
- committee records;
- decision records;
- risk assessments;
- authorisations.

### Technical Evidence
- configurations;
- test results;
- system logs;
- performance records;
- security assessments;
- model or software version records.

### Operational Evidence
- employment records;
- monitoring records;
- incidents;
- intervention records;
- operational observations;
- lessons learned.

### Human and Organisational Evidence
- competence records;
- training;
- role assignments;
- decision records;
- workload or human-factors assessments.

### Supplier and Dependency Evidence
- supplier assessments;
- contractual controls;
- provenance records;
- dependency assessments;
- continuity evidence.

Evidence should be assessed according to its intended purpose rather than by category alone.

---

## 22. Audit Findings

Audit findings identify conditions where evidence indicates that:

- a requirement is not met;
- a control is ineffective;
- a governance process is incomplete;
- evidence is insufficient;
- an authorisation condition has been breached;
- a material risk is inadequately controlled;
- a systemic weakness exists.

Findings should be evidence-based and sufficiently specific to support corrective action.

Detailed testing and findings are addressed in `04_Audit_Testing_and_Findings.md`.

---

## 23. Nonconformity

A nonconformity is a demonstrated failure to satisfy an applicable requirement or approved condition.

Nonconformities should be distinguished from:

- observations;
- improvement opportunities;
- evidence gaps;
- control weaknesses;
- risks;
- incidents.

Classification should be based on defined criteria and consequence.

---

## 24. Finding Severity

Finding significance should consider:

- consequence;
- likelihood;
- scope;
- recurrence;
- duration;
- control weakness;
- autonomy;
- human-control implications;
- operational exposure;
- security implications;
- authorisation implications;
- systemic impact.

A minor documentation issue should not be treated identically to a failure that could permit unauthorised consequential autonomy.

---

## 25. Corrective Action

Findings should lead to proportionate corrective action.

Corrective action should address:

- the identified condition;
- immediate containment where required;
- root or contributing causes;
- responsible owner;
- required action;
- target completion;
- verification method;
- closure authority.

Corrective action is not complete merely because an action was performed.

Effectiveness should be verified.

Detailed arrangements are addressed in `06_Nonconformity_Corrective_Action_and_Follow_Up.md`.

---

## 26. Audit Reporting

Audit reporting should provide decision-makers with:

- audit objective;
- scope;
- criteria;
- methodology;
- evidence limitations;
- findings;
- severity;
- overall conclusion;
- unresolved issues;
- corrective actions;
- escalation requirements.

Reports should clearly distinguish verified facts from interpretation and professional judgement.

Detailed reporting governance is addressed in `07_Audit_Reporting_and_Governance_Assurance.md`.

---

## 27. Escalation

Audit findings should be escalated where they may affect:

- human safety;
- human control;
- authorised autonomy;
- operational authorisation;
- mission-critical performance;
- security;
- legal or policy compliance;
- critical dependencies;
- systemic governance integrity.

Escalation thresholds should be predefined where practical.

Urgent findings should not wait for the normal audit reporting cycle.

---

## 28. Relationship with Operational Authorisation

Audit does not itself grant operational authority.

Audit may, however, identify evidence that:

- supports continued authorisation;
- indicates conditions are not being met;
- requires additional controls;
- triggers review;
- requires revalidation;
- supports restriction;
- supports suspension;
- requires reauthorisation.

The authorising authority remains responsible for the operational authorisation decision.

---

## 29. Relationship with TEVV

TEVV provides technical and operational test, evaluation, verification, and validation evidence.

Audit examines whether:

- required TEVV was conducted;
- applicable requirements were addressed;
- evidence is appropriately governed;
- findings were handled;
- decisions based on TEVV evidence were properly governed.

Audit should not duplicate technical testing without a defined audit purpose.

---

## 30. Relationship with Continuous Assurance

Continuous assurance provides continuing confidence through monitoring, evidence, review, and corrective action.

Audit provides periodic or triggered independent examination.

Audit findings should feed continuous assurance where they reveal weaknesses in:

- controls;
- evidence;
- indicators;
- assumptions;
- human control;
- autonomy;
- environment;
- security;
- dependencies.

Continuous assurance should also inform audit prioritisation.

---

## 31. Relationship with Incidents

Incidents may trigger:

- focused audit;
- control review;
- evidence examination;
- independent challenge;
- revalidation;
- reauthorisation review.

Audit findings may also identify conditions that increase incident likelihood.

Module 14 governs incident response; Module 16 governs the audit perspective on governance effectiveness and accountability.

---

## 32. Relationship with Change and Reauthorisation

Material changes may trigger targeted or expanded audit.

Audit may examine whether:

- the change was properly classified;
- configuration remained controlled;
- required testing occurred;
- revalidation was performed;
- reauthorisation was obtained where required;
- implementation remained within approved conditions.

Audit should therefore provide an independent check on change governance without replacing the change process itself.

---

## 33. Governance Assurance

At governance level, audit should enable leadership to understand:

- whether required governance exists;
- whether controls are operating;
- where evidence is weak;
- where findings are concentrated;
- whether corrective actions are effective;
- whether systemic weaknesses exist;
- whether governance confidence is justified.

Governance assurance should not rely only on aggregate audit scores.

Critical findings, unresolved evidence gaps, and high-consequence control failures should remain visible.

---

## 34. Audit Coverage

Audit coverage should be monitored across:

- lifecycle stages;
- AI capabilities;
- missions;
- autonomy levels;
- environments;
- organisational units;
- suppliers;
- control domains;
- high-consequence use cases.

Coverage gaps should be treated as governance information.

No audit coverage does not mean no risk.

---

## 35. Systemic Findings

Multiple findings may indicate a common underlying weakness.

Examples include:

- repeated incomplete evidence;
- recurring configuration drift;
- repeated failures to reauthorise after change;
- inadequate human-control records;
- recurring uncertainty disclosure failures;
- repeated supplier assurance weaknesses.

Such patterns should be analysed at governance level rather than treated only as individual findings.

---

## 36. Audit Evidence and the Golden Thread

Audit should be able to trace relevant governance evidence through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation**

The audit function should test whether this chain is:

- complete;
- coherent;
- current;
- internally consistent;
- supported by evidence;
- traceable;
- accountable.

A broken Golden Thread is itself a governance concern.

---

## 37. Audit Records

Audit records should preserve sufficient information to reconstruct:

- what was audited;
- why it was audited;
- against what criteria;
- what evidence was considered;
- what testing was performed;
- what findings were identified;
- what judgements were made;
- who made material decisions;
- what corrective actions followed;
- how closure was verified.

Detailed records and retention requirements are addressed in `08_Audit_Records_Traceability_and_Retention.md`.

---

## 38. Audit Governance Roles

Roles should be explicitly assigned for:

- audit programme ownership;
- audit approval;
- audit execution;
- technical subject-matter support;
- evidence provision;
- finding ownership;
- corrective action;
- verification;
- escalation;
- governance review;
- audit quality assurance.

Responsibility for remediation should remain with the accountable process or capability owner.

Auditors should not become the owners of the controls they audit.

---

## 39. Audit Quality

The audit function should itself be subject to appropriate quality controls.

These may include:

- consistent methodology;
- reviewer oversight;
- competency requirements;
- conflict-of-interest checks;
- quality review;
- evidence sufficiency checks;
- conclusion review;
- periodic assessment of audit effectiveness.

Audit should be capable of demonstrating that its own conclusions are credible.

---

## 40. Evidence Limitations

Audit conclusions should explicitly identify material limitations such as:

- inaccessible evidence;
- incomplete records;
- insufficient sample coverage;
- stale evidence;
- configuration uncertainty;
- unavailable operational data;
- conflicting evidence;
- dependence on management assertions;
- insufficient independence;
- untested conditions.

Absence of evidence should not automatically be interpreted as evidence of compliance.

---

## 41. Decision Use of Audit Results

Audit results may inform:

- operational authorisation;
- risk acceptance;
- control improvement;
- deployment decisions;
- autonomy restrictions;
- security decisions;
- supplier management;
- revalidation;
- reauthorisation;
- incident response;
- governance priorities;
- resource allocation.

Audit results should not be used outside their scope without considering their limitations and currency.

---

## 42. Core Audit Governance Model

D-AIGAAF therefore establishes the following model:

**Governance Requirements**
↓
**Audit Universe**
↓
**Risk-Based Audit Programme**
↓
**Defined Criteria and Scope**
↓
**Evidence and Testing**
↓
**Findings and Conclusions**
↓
**Challenge and Independence**
↓
**Corrective Action**
↓
**Verification**
↓
**Governance Reporting**
↓
**Learning and Continuous Improvement**

This model connects independent examination with the broader AI governance lifecycle.

---

## 43. Integration with D-AIGAAF

Module 16 should integrate with:

- **Module 03 — Risk & Autonomy:** audit risk treatment, residual risk, autonomy boundaries, and risk acceptance.
- **Module 09 — TEVV:** audit of test governance and evidence.
- **Module 10 — Operational Environment:** audit of environmental assumptions and readiness.
- **Module 11 — Operational Authorisation:** audit of authorisation conditions and decision governance.
- **Module 12 — Operational Employment:** audit of actual operational use.
- **Module 13 — Continuous Assurance:** audit findings as independent assurance inputs.
- **Module 14 — Incident & Fail-Safe:** incident-triggered audit and governance examination.
- **Module 15 — Change & Reauthorisation:** audit of change governance and reauthorisation controls.

No module should be interpreted in isolation where an audit conclusion depends on another governance domain.

---

## 44. Governance Outcome

A mature audit and evidence governance system should allow the organisation to answer:

1. What requirement are we assessing?
2. What control is intended to satisfy it?
3. What evidence demonstrates operation?
4. How reliable and current is that evidence?
5. Was the control effective?
6. What weaknesses were identified?
7. Who is accountable?
8. What corrective action is required?
9. Was the corrective action effective?
10. Does the finding affect assurance, risk, authority, autonomy, or operational use?
11. Does it require escalation, revalidation, or reauthorisation?
12. What has been learned?

---

## 45. Core Rule

**An AI capability should not be considered well governed merely because policies, controls, or approvals exist. D-AIGAAF requires governance to be demonstrable through independent examination, reliable evidence, effective controls, traceable decisions, accountable corrective action, and continuing learning.**

Audit provides independent challenge; it does not replace management responsibility, TEVV, continuous assurance, incident governance, or operational authorisation.

---

## 46. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation → Audit**

Audit provides an independent examination across this thread to determine whether governance claims remain supported and accountable.
