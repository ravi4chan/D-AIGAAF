# 07 — Corrective Action, Recovery and Restoration

## 1. Purpose

This document defines how Defence AI capabilities recover from incidents, implement corrective action and restore controlled operation under D-AIGAAF.

The objective is to ensure that restoration follows evidence-based confirmation that the initiating condition has been addressed, required safeguards are effective, assurance is sufficient and operational authority remains valid.

---

## 2. Core Principle

> **Corrective action shall address the underlying cause or control weakness identified through incident investigation. Recovery and restoration shall be evidence-based and shall not return a Defence AI capability to unrestricted operation merely because the immediate incident condition has disappeared. Material restoration shall require confirmation that risk, controls, assurance and operational authority remain acceptable.**

---

## 3. Recovery Object

Recovery should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

Recovery should address both the affected capability and the conditions that allowed the incident to occur.

---

## 4. Recovery Objectives

Recovery should seek to:

- contain remaining risk;
- restore safe and controlled operation;
- correct identified weaknesses;
- restore human control;
- verify system integrity;
- preserve assurance;
- establish whether authority remains valid;
- prevent recurrence.

---

## 5. Corrective Action

Corrective action is action taken to address an identified incident cause, contributing factor or control weakness.

It may involve:

- model changes;
- software changes;
- data changes;
- configuration;
- security controls;
- human controls;
- procedures;
- training;
- monitoring;
- fail-safe;
- operational restrictions.

---

## 6. Preventive Action

Preventive action addresses conditions that could produce similar incidents in the future.

Preventive measures may include:

- new controls;
- additional testing;
- revised requirements;
- monitoring improvements;
- boundary changes;
- training;
- supplier controls.

---

## 7. Immediate Corrective Action

Immediate action may be required to:

- stop harmful behaviour;
- reduce autonomy;
- restrict functionality;
- restore human control;
- isolate affected components;
- enter safe state;
- suspend employment.

Immediate action should not wait for complete root-cause analysis.

---

## 8. Root-Cause Linkage

Corrective actions should be linked to:

- incident findings;
- root cause;
- contributing factors;
- affected controls;
- assurance claims.

Actions should address causes rather than only visible symptoms.

---

## 9. Corrective Action Priority

Priority should consider:

- consequence;
- recurrence;
- residual risk;
- assurance impact;
- exposure;
- systemic significance;
- urgency.

High-consequence weaknesses should receive appropriate priority even where incidents are rare.

---

## 10. Corrective Action Ownership

Each material action should have:

- accountable owner;
- defined scope;
- expected outcome;
- due date;
- verification method;
- status.

---

## 11. Corrective Action Status

A practical lifecycle is:

**Identified → Assessed → Assigned → Planned → Implemented → Verification Pending → Verified → Closed**

Administrative closure should not replace effectiveness verification.

---

## 12. Compensating Controls

Where permanent correction cannot be implemented immediately, temporary compensating controls may be used.

Examples include:

- reduced autonomy;
- increased human supervision;
- restricted mission;
- restricted environment;
- enhanced monitoring;
- limited functionality.

Compensating controls should have defined duration and review.

---

## 13. Risk Reassessment

After corrective action, risk should be reassessed to determine whether:

- risk has reduced;
- residual risk remains acceptable;
- new risk has been introduced;
- risk acceptance has changed.

---

## 14. Assurance Reassessment

Corrective action should be assessed for its effect on:

- assurance claims;
- evidence;
- confidence;
- operating boundaries;
- human-control assurance;
- autonomy assurance;
- security assurance.

---

## 15. Verification

Corrective action should be verified using proportionate evidence.

Verification may include:

- inspection;
- testing;
- regression testing;
- targeted TEVV;
- security evaluation;
- human-factors assessment;
- operational evaluation;
- monitoring.

---

## 16. Regression Testing

Where changes affect a previously assured capability, regression testing should establish that corrective action has not introduced unacceptable effects elsewhere.

Testing should consider relevant:

- functions;
- interfaces;
- dependencies;
- autonomy;
- human-control mechanisms.

---

## 17. Corrective Action Failure

Where corrective action does not achieve its intended outcome:

- the action should remain open;
- risk should be reassessed;
- additional controls should be considered;
- further testing may be required;
- suspension may be necessary.

Repeated failed corrective actions should be treated as a potential systemic issue.

---

## 18. Configuration Control

All corrective changes should be incorporated into controlled configuration management.

The organisation should establish:

- previous configuration;
- changed configuration;
- authority;
- implementation;
- testing;
- resulting baseline.

---

## 19. Model Remediation

Where the incident involves AI/model behaviour, remediation may include:

- model change;
- data change;
- retraining;
- fine-tuning;
- additional safeguards;
- output filtering;
- function restriction.

Model remediation should not be assumed effective without appropriate evidence.

---

## 20. Data Remediation

Where data contributed to an incident, remediation may include:

- source correction;
- provenance improvement;
- quality controls;
- validation;
- preprocessing changes;
- additional monitoring.

The impact on existing model and assurance evidence should be assessed.

---

## 21. Human-Control Remediation

Where human control contributed to the incident, actions may include:

- interface changes;
- revised authority;
- additional training;
- workload reduction;
- improved alerts;
- intervention improvements;
- autonomy reduction.

---

## 22. Autonomy Remediation

Where autonomy contributed to the incident, actions may include:

- reduced autonomy;
- revised transition rules;
- tighter boundaries;
- improved monitoring;
- additional intervention;
- revised authorisation conditions.

---

## 23. Security Remediation

Security-related corrective action may include:

- vulnerability remediation;
- configuration hardening;
- credential or access changes;
- integrity controls;
- dependency changes;
- additional monitoring.

Security remediation should be coordinated with operational assurance.

---

## 24. Environmental Remediation

Where environmental conditions contributed, action may include:

- narrowing the operating envelope;
- additional environmental controls;
- improved sensing;
- additional testing;
- revised monitoring;
- mission restrictions.

---

## 25. Dependency Remediation

Where dependencies contributed, action may include:

- redundancy;
- alternative dependency;
- degraded-mode capability;
- supplier action;
- monitoring;
- dependency restrictions.

---

## 26. Recovery Readiness

Before restoration, the responsible authority should confirm:

- incident is contained;
- required corrective actions are complete or adequately controlled;
- configuration is known;
- system integrity is established;
- human control is effective;
- fail-safe mechanisms are available;
- assurance is sufficient;
- authorisation remains applicable.

---

## 27. Restoration Levels

Restoration may occur progressively:

### Restricted Restoration

Limited function under enhanced controls.

### Conditional Restoration

Operation under defined conditions and monitoring.

### Full Authorised Restoration

Return to the previously authorised scope where evidence supports it.

The restoration level should match the available assurance.

---

## 28. No Automatic Full Restoration

A capability should not automatically return to its previous unrestricted state after an incident.

The post-incident evidence may justify:

- narrower boundaries;
- lower autonomy;
- additional human supervision;
- enhanced monitoring;
- revalidation;
- reauthorisation.

---

## 29. Restoration Authority

The organisation should define who may approve:

- restricted restoration;
- conditional restoration;
- full restoration;
- suspension continuation;
- return from suspension.

Authority should be based on consequence and governance level.

---

## 30. Revalidation Trigger

Corrective changes may require revalidation where they affect:

- assurance claims;
- model behaviour;
- configuration;
- autonomy;
- human control;
- environment;
- security;
- mission effectiveness.

---

## 31. Reauthorisation Trigger

Reauthorisation may be required where corrective action changes the authorised basis, including:

- mission;
- environment;
- autonomy;
- human authority;
- operational boundaries;
- conditions;
- risk acceptance.

---

## 32. Enhanced Monitoring

Restored capabilities may require enhanced monitoring to verify that:

- corrected behaviour persists;
- new anomalies do not emerge;
- controls remain effective;
- human control remains effective;
- performance remains within expected bounds.

---

## 33. Restoration Period

Where appropriate, restoration may include a defined observation period before unrestricted employment.

The period should have:

- objectives;
- indicators;
- thresholds;
- authority;
- exit criteria.

---

## 34. Restoration Failure

If unacceptable behaviour recurs during restoration:

- protective response should be initiated;
- restoration should be reassessed;
- corrective action should reopen where necessary;
- revalidation or suspension should be considered.

---

## 35. Evidence of Recovery

Recovery evidence may include:

- test results;
- inspection;
- configuration verification;
- security assessment;
- human-control evaluation;
- operational monitoring;
- incident trend analysis.

---

## 36. Corrective Action and Lessons

Corrective actions should produce lessons about:

- control effectiveness;
- detection;
- response;
- root cause;
- testing;
- governance.

Lessons should feed into continuous improvement.

---

## 37. Systemic Corrective Action

Where an incident indicates an organisational weakness, corrective action should extend beyond the affected capability.

Possible actions include:

- policy change;
- common control;
- revised standards;
- portfolio-wide testing;
- workforce training;
- supplier requirements.

---

## 38. Supplier Corrective Action

Where a supplier contributes to an incident, corrective action may include:

- supplier investigation;
- remediation;
- additional assurance;
- contract action;
- dependency restriction;
- replacement.

---

## 39. Documentation

Material corrective actions should document:

- incident;
- finding;
- cause;
- action;
- owner;
- implementation;
- verification;
- residual risk;
- assurance impact;
- restoration decision.

---

## 40. Governance Review

Material recovery and restoration decisions should be reviewed where proportionate to:

- consequence;
- uncertainty;
- autonomy;
- security;
- systemic significance.

---

## 41. Closure

An incident should not be considered fully resolved merely because the system is restored.

Resolution should include:

- corrective action;
- verification;
- assurance assessment;
- authority decision;
- lessons.

---

## 42. Governance Questions

The organisation should be able to answer:

1. How are corrective actions derived from investigation findings?
2. Who owns corrective action?
3. How is corrective-action effectiveness verified?
4. What compensating controls are available?
5. How are failed corrective actions handled?
6. How are model and data remediation assessed?
7. How are human-control weaknesses corrected?
8. How are autonomy-related weaknesses corrected?
9. How are security and dependency issues addressed?
10. What evidence is required before restoration?
11. When is restricted restoration appropriate?
12. When is revalidation required?
13. When is reauthorisation required?
14. Who can approve restoration?
15. How is restored operation monitored?
16. How are systemic lessons transferred across capabilities?

---

## 43. Core Rule

> **Recovery shall restore controlled operation, not merely technical functionality. Corrective action shall address underlying causes and be verified for effectiveness. Restoration shall be proportionate to the available assurance and may require restrictions, enhanced monitoring, revalidation or reauthorisation. A capability shall not return automatically to its previous operational state solely because the immediate incident has ended.**

---

## 44. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Incident → Investigation → Findings → Corrective Action → Verification → Recovery → Restoration → Assurance Reassessment → Revalidation/Reauthorisation → Learning**
