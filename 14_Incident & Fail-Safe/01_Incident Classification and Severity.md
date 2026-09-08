# 01 — Incident Classification and Severity

## 1. Purpose

This document defines a consistent approach for identifying, classifying and assessing Defence AI incidents under D-AIGAAF.

The objective is to ensure that incidents are assessed according to actual and potential consequence, loss of control, uncertainty, recurrence and assurance impact rather than solely according to the immediate visible outcome.

---

## 2. Core Principle

> **Defence AI incidents shall be classified using consistent, evidence-based criteria that consider actual and potential consequence, human control, autonomy, safety, security, mission impact and assurance implications. Severity shall remain subject to reassessment as evidence develops.**

---

## 3. Incident Classification Object

Incident classification should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

The same technical event may have different significance in different operational contexts.

---

## 4. What Constitutes an Incident

An event or condition may be classified as an incident when it:

- causes actual harm;
- creates credible potential for significant harm;
- produces unsafe or unexpected AI behaviour;
- materially degrades performance;
- reduces human control;
- produces unauthorised autonomy;
- violates an operational boundary;
- compromises security or integrity;
- invalidates a material assurance assumption;
- requires emergency intervention;
- requires restriction, safe state or suspension.

---

## 5. Incident versus Anomaly

An **anomaly** is an unexpected observation that does not yet establish material operational impact.

An **incident** is an event or condition requiring formal assessment or response because actual or potential consequences are material.

An anomaly may become an incident as evidence develops.

---

## 6. Incident versus Near Miss

A **near miss** is an event where harmful or unacceptable consequences were avoided despite a credible pathway toward them.

Near misses should be captured because they may reveal weaknesses before harm occurs.

---

## 7. Incident Categories

Incidents may be classified into one or more categories:

| Category | Example Focus |
|---|---|
| Safety | Actual or potential harm |
| AI Behaviour | Unexpected or incorrect AI behaviour |
| Human Control | Loss or degradation of meaningful human control |
| Autonomy | Unexpected or unauthorised autonomous behaviour |
| Security | Compromise of AI, data or system integrity |
| Data/Information | Corruption, manipulation or material information failure |
| Environment | Operation outside demonstrated environmental conditions |
| Dependency | Failure of critical supporting dependency |
| Configuration | Unknown or unauthorised configuration |
| Human Factors | Material workload, interface or decision-making issue |
| Multi-AI | Harmful interaction between AI capabilities |

Multiple categories may apply.

---

## 8. Primary and Secondary Classification

Each material incident should have:

- primary category;
- secondary categories where applicable;
- severity;
- affected capability;
- affected mission;
- affected operational conditions.

Classification should describe the event without prematurely assigning cause.

---

## 9. Severity Assessment

Severity should consider:

- actual consequence;
- potential consequence;
- scope;
- duration;
- reversibility;
- loss of human control;
- autonomy;
- uncertainty;
- security implications;
- mission impact;
- recurrence;
- systemic implications.

---

## 10. Severity Levels

A practical five-level model is:

### Critical

An incident involving actual or credible potential for catastrophic consequence, loss of essential human control, uncontrolled consequential autonomy, critical security compromise or another condition requiring immediate protective action.

### High

An incident with significant actual or potential safety, security, mission, autonomy or assurance consequences.

### Moderate

A material but contained incident with limited consequence and effective control.

### Low

A limited event requiring assessment, corrective action or monitoring but with no significant consequence established.

### Observation

An unexpected event or condition with no material consequence established but with potential learning or assurance value.

---

## 11. Severity Is Not Consequence Alone

Severity should not be determined solely by observed harm.

A near miss with a credible high-consequence pathway may warrant a higher classification than an event where the same failure produced only a minor outcome because effective safeguards intervened.

---

## 12. Potential Consequence

Assessment should consider:

- credible worst-case outcome;
- reasonably foreseeable outcome;
- number of people or assets potentially affected;
- duration of exposure;
- ability to intervene;
- reversibility;
- uncertainty.

Potential consequence should be evidence-based and not speculative without justification.

---

## 13. Human-Control Factor

Severity should be increased where an incident involves:

- inability to understand AI behaviour sufficiently for safe control;
- inability to intervene;
- inability to override;
- unexpected autonomous action;
- delayed human response;
- loss of decision authority.

---

## 14. Autonomy Factor

Additional scrutiny should apply where an incident involves:

- unexpected autonomy;
- unauthorised autonomy;
- transition to a higher autonomy state;
- autonomous consequential action;
- failure to reduce autonomy;
- inability to return to an authorised state.

---

## 15. Security Factor

Security-related severity should consider whether an event affects:

- confidentiality;
- integrity;
- availability;
- model integrity;
- data integrity;
- configuration integrity;
- human control;
- operational authority.

A security event that affects AI behaviour or human control may have safety and operational consequences beyond the security domain.

---

## 16. Mission Impact

Mission impact may include:

- failure to perform the intended function;
- degraded mission effectiveness;
- misleading decision support;
- delayed action;
- inappropriate action;
- loss of situational awareness;
- disruption of critical support.

Mission impact should be assessed independently from technical performance.

---

## 17. Environmental Factor

Severity should consider whether the incident occurred:

- within the authorised operating envelope;
- near a defined boundary;
- in degraded conditions;
- in disconnected conditions;
- in adversarial conditions;
- outside the demonstrated envelope.

Operating outside the demonstrated envelope may itself have assurance significance even where no harm occurred.

---

## 18. Recurrence Factor

Severity and priority may increase where:

- the event has occurred previously;
- corrective action previously failed;
- the same failure appears across capabilities;
- the incident indicates a systemic weakness.

Repeated low-severity events should not be allowed to obscure a systemic problem.

---

## 19. Uncertainty Factor

Where material uncertainty exists about:

- what happened;
- system state;
- AI behaviour;
- human actions;
- consequence;
- security status;

the organisation should consider whether additional protective measures are required.

Uncertainty should not automatically be interpreted as evidence of safety.

---

## 20. Severity Matrix

A practical assessment may combine:

**Consequence × Likelihood/Plausibility × Control Effectiveness × Uncertainty**

The resulting classification should be subject to professional judgement and documented rationale.

---

## 21. Immediate Escalation Conditions

Immediate escalation should be considered where an incident involves:

- loss of human control;
- uncontrolled consequential autonomy;
- critical safety-control failure;
- critical boundary violation;
- suspected malicious manipulation;
- material compromise of system integrity;
- inability to establish a safe operating state.

---

## 22. Initial Classification

The initial classification should be based on information available at detection.

It should not delay necessary protective action.

---

## 23. Reclassification

Incident classification should be updated when material new evidence becomes available.

Reclassification may occur:

- upward;
- downward;
- across categories;
- from anomaly to incident;
- from incident to systemic issue.

Changes should be recorded.

---

## 24. Classification Authority

The organisation should define who may:

- assign initial classification;
- increase severity;
- reduce severity;
- declare a critical incident;
- close classification.

Emergency authority should be available where delay could increase harm.

---

## 25. Independence

Material incidents should receive independent review where proportionate to:

- consequence;
- uncertainty;
- autonomy;
- security implications;
- organisational significance.

---

## 26. Systemic Incident

An incident should be considered systemic where evidence indicates:

- common cause;
- common vulnerability;
- common control weakness;
- repeated failure across capabilities;
- governance process failure.

Systemic incidents should be escalated beyond the individual capability.

---

## 27. Multi-AI Incident Classification

Where multiple AI systems interact, classification should consider:

- each system's contribution;
- interaction effects;
- shared dependencies;
- emergent behaviour;
- human oversight;
- responsibility boundaries.

The classification should apply to the combined operational effect as well as individual components where necessary.

---

## 28. Classification and Protective Response

Classification should support, but not replace, immediate risk response.

The operational sequence is:

**Detect → Protect → Classify → Assess → Contain → Investigate**

Protective action may precede complete classification.

---

## 29. Classification and Assurance

Severity should inform assessment of:

- assurance claims;
- evidence validity;
- residual risk;
- control effectiveness;
- operating boundaries;
- human-control assurance;
- autonomy assurance.

---

## 30. Classification and Authorisation

Material incidents should be assessed for their effect on operational authorisation.

Possible outcomes include:

- continue;
- continue with restrictions;
- enhanced monitoring;
- additional assurance;
- revalidation;
- reauthorisation;
- suspension.

---

## 31. Classification and Reporting

Reporting thresholds should be linked to severity and consequence.

Critical and High incidents should normally receive enhanced reporting and escalation.

Reporting requirements should reflect applicable organisational and information-handling rules.

---

## 32. Incident Priority

Severity and response priority are related but distinct.

Priority should also consider:

- urgency;
- operational exposure;
- ability to contain;
- recurrence;
- ongoing harm;
- decision deadlines.

---

## 33. Incident Status

A practical status model is:

**Detected → Classified → Contained → Investigating → Corrective Action → Verification → Closed**

Status should remain visible for material incidents.

---

## 34. Classification Records

The incident classification record should include:

- incident ID;
- date/time;
- capability;
- mission;
- environment;
- configuration;
- autonomy;
- human authority;
- category;
- severity;
- evidence;
- rationale;
- uncertainty;
- escalation;
- reviewer;
- classification changes.

---

## 35. Classification Quality

Classification processes should be periodically reviewed for:

- consistency;
- under-reporting;
- over-classification;
- delayed escalation;
- recurring misclassification;
- systemic patterns.

---

## 36. Governance Questions

The organisation should be able to answer:

1. What constitutes an incident?
2. How are anomalies and near misses treated?
3. What incident categories are used?
4. How is severity determined?
5. How is potential consequence assessed?
6. How is loss of human control weighted?
7. How is unexpected autonomy treated?
8. How are security and safety impacts combined?
9. How is uncertainty handled?
10. Who can classify an incident?
11. Who can escalate or downgrade severity?
12. When is independent review required?
13. How are systemic incidents identified?
14. When does an incident affect assurance?
15. When does it affect operational authorisation?
16. How are classification changes recorded?

---

## 37. Core Rule

> **Incident classification shall support timely protection, proportionate escalation and evidence-based governance. Severity shall reflect actual and credible potential consequence, including loss of human control, autonomy, security, mission and assurance impacts. Classification shall remain reviewable and shall be updated when new evidence changes the understanding of the event.**

---

## 38. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Detection → Classification → Protective Response → Investigation → Corrective Action → Assurance Reassessment → Revalidation/Reauthorisation → Learning**
