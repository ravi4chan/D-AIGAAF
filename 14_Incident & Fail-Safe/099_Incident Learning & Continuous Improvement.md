# 09 — Incident Learning & Continuous Improvement

## 1. Purpose

This document defines how lessons from Defence AI incidents, near misses, anomalies, investigations, corrective actions and operational experience are converted into sustained improvements across the AI lifecycle, governance system and operational assurance process.

The objective is to prevent lessons from remaining isolated within individual incident records.

---

## 2. Core Principle

> **Every material incident should produce learning proportionate to its significance, and validated lessons should be translated into changes to requirements, controls, testing, training, monitoring, authorisation and governance where necessary.**

---

## 3. Learning Objective

Incident learning should seek to understand:

- what happened;
- why it happened;
- what allowed it to happen;
- what prevented greater consequence;
- whether the issue is local or systemic;
- what should change;
- whether the change is effective.

---

## 4. Learning Sources

Relevant learning may originate from:

- incidents;
- near misses;
- anomalies;
- unexpected AI behaviour;
- loss of human control;
- autonomy events;
- security events;
- data issues;
- environmental events;
- degraded or disconnected operations;
- failed controls;
- TEVV findings;
- operational experience;
- exercises and trials;
- assurance reviews;
- audit findings.

---

## 5. Learning Lifecycle

The learning process should follow:

**Observe → Capture → Assess → Learn → Prioritise → Act → Verify → Institutionalise → Monitor**

Learning is therefore an assurance activity, not merely a reporting activity.

---

## 6. Immediate Learning Capture

Relevant information should be captured before evidence, context or operational knowledge is lost.

Initial capture should include:

- event;
- context;
- observed behaviour;
- consequences;
- immediate response;
- known uncertainty;
- preliminary lesson.

---

## 7. Investigation-Based Learning

Lessons should be informed by investigation findings rather than assumptions.

Investigation should identify:

- root causes;
- contributing factors;
- latent conditions;
- control weaknesses;
- human factors;
- environmental factors;
- security factors;
- dependency issues;
- governance weaknesses.

---

## 8. Lesson Validation

A proposed lesson should be validated before being treated as a general requirement.

Validation should consider:

- evidence;
- recurrence;
- causal relevance;
- operational applicability;
- alternative explanations;
- confidence.

---

## 9. Local Lessons

Some lessons may apply only to:

- one capability;
- one configuration;
- one mission;
- one environment;
- one operational procedure.

Local lessons should not automatically be generalised.

---

## 10. Cross-Capability Lessons

A lesson should be considered for wider application where it involves:

- common architecture;
- common model or supplier;
- common data source;
- common dependency;
- common control;
- common operational process.

---

## 11. Systemic Lessons

Systemic learning may reveal weaknesses in:

- governance;
- procurement;
- assurance;
- TEVV;
- human authority;
- security;
- data governance;
- autonomy controls;
- environmental assessment;
- authorisation.

Systemic lessons require organisational action rather than isolated corrective action.

---

## 12. Portfolio Learning

Where a lesson may affect multiple AI capabilities, the organisation should determine whether to:

- notify relevant capability owners;
- review related assurance claims;
- conduct targeted assessments;
- update common controls;
- initiate portfolio-wide review.

---

## 13. Requirements Update

Validated lessons may require changes to:

- mission requirements;
- AI requirements;
- safety requirements;
- security requirements;
- human-control requirements;
- autonomy requirements;
- environmental requirements;
- evidence requirements.

---

## 14. Control Improvement

Lessons should be translated into control improvements where existing controls were:

- absent;
- inadequate;
- ineffective;
- poorly implemented;
- bypassable;
- insufficiently monitored.

---

## 15. TEVV Improvement

Lessons should feed back into TEVV through:

- new test cases;
- new scenarios;
- boundary testing;
- adversarial testing;
- human-AI evaluation;
- autonomy testing;
- degraded-environment testing;
- regression testing.

---

## 16. Data and Model Learning

Where incidents involve data or model behaviour, lessons may require review of:

- data provenance;
- representativeness;
- data quality;
- data drift;
- model assumptions;
- model limitations;
- training data;
- evaluation datasets;
- monitoring indicators.

---

## 17. Human-Factor Learning

Lessons should consider:

- operator workload;
- training;
- competence;
- automation bias;
- situational awareness;
- interface design;
- decision timing;
- intervention capability;
- communication.

Human error should not automatically be treated as the sole cause where system design or governance contributed.

---

## 18. Autonomy Learning

Where autonomy is involved, lessons should examine:

- autonomy boundaries;
- transition conditions;
- unexpected transitions;
- intervention;
- override;
- safe-state behaviour;
- authority clarity;
- observability.

---

## 19. Environment Learning

Lessons may reveal that the assessed operating envelope was:

- incomplete;
- too broad;
- incorrectly characterised;
- insufficiently tested;
- inadequately monitored.

Environmental assumptions should be updated where evidence supports the change.

---

## 20. Security Learning

Security-related lessons should inform:

- threat models;
- security controls;
- adversarial testing;
- monitoring;
- incident response;
- supplier assurance;
- dependency management.

---

## 21. Dependency Learning

Where incidents involve external or internal dependencies, assess:

- dependency criticality;
- failure modes;
- fallback arrangements;
- supplier controls;
- continuity;
- resilience.

---

## 22. Human Authority Learning

Lessons should determine whether:

- decision rights were clear;
- authority was available;
- authority was exercised;
- intervention was practical;
- escalation worked;
- accountability was traceable.

---

## 23. Monitoring Improvement

Validated lessons may require changes to:

- indicators;
- thresholds;
- alerting;
- anomaly detection;
- environmental monitoring;
- human-control monitoring;
- autonomy monitoring;
- security monitoring.

---

## 24. Training and Exercises

Lessons should be incorporated into appropriate:

- operator training;
- commander training;
- technical training;
- governance training;
- exercises;
- simulations;
- emergency-response drills.

Training should reflect realistic failure and degraded conditions where appropriate.

---

## 25. Policy and Governance Improvement

Systemic lessons may require changes to:

- policy;
- governance processes;
- decision rights;
- approval criteria;
- authorisation conditions;
- assurance requirements;
- oversight arrangements.

---

## 26. Procurement and Supply Chain Learning

Relevant lessons should feed into:

- acquisition requirements;
- supplier assurance;
- contractual controls;
- provenance requirements;
- dependency management;
- change notification;
- continuity requirements.

---

## 27. Authorisation Learning

Lessons may require changes to:

- authorisation conditions;
- operating boundaries;
- autonomy limits;
- environmental restrictions;
- human-supervision requirements;
- review frequency.

Changes affecting the authorised basis should follow the reauthorisation process defined in Module 11.

---

## 28. Prioritisation

Lessons should be prioritised according to:

- consequence;
- likelihood;
- recurrence;
- uncertainty;
- systemic significance;
- affected capabilities;
- assurance impact.

---

## 29. Action Ownership

Each validated improvement should have:

- accountable owner;
- required action;
- priority;
- target date;
- dependencies;
- verification method;
- status.

---

## 30. Corrective versus Preventive Learning

Corrective learning addresses the identified failure.

Preventive learning addresses similar failures that may occur elsewhere.

Both should be considered where systemic risk exists.

---

## 31. Verification of Learning

A lesson should not be considered implemented merely because a document or procedure was changed.

Verification should establish that the intended improvement:

- exists;
- is implemented;
- operates effectively;
- produces the intended assurance effect.

---

## 32. Regression Testing

Where learning produces a technical or configuration change, regression testing should verify that the improvement does not introduce unacceptable new behaviour.

---

## 33. Assurance Update

Validated lessons should update relevant:

- assurance claims;
- evidence;
- confidence;
- risk assessments;
- controls;
- monitoring;
- evidence gaps.

This maintains the connection between learning and continuing assurance.

---

## 34. Revalidation

Revalidation should be considered where learning indicates that existing evidence no longer adequately supports an assurance claim.

---

## 35. Reauthorisation

Reauthorisation should be considered where validated learning changes:

- risk;
- mission;
- environment;
- autonomy;
- human authority;
- operating boundaries;
- authorisation conditions.

---

## 36. Knowledge Management

Lessons should be stored in a structured knowledge system that allows:

- retrieval;
- traceability;
- categorisation;
- trend analysis;
- cross-capability comparison;
- governance reporting.

---

## 37. Lesson Traceability

Each material lesson should be traceable from:

**Incident → Finding → Lesson → Action → Verification → Governance Change**

This prevents lessons from becoming disconnected observations.

---

## 38. Recurring Lessons

Repeated lessons should be treated as evidence that:

- corrective actions are ineffective;
- root causes remain unresolved;
- systemic controls are inadequate;
- governance processes require review.

---

## 39. Negative Learning

The organisation should also capture what **did not fail**.

Effective controls, successful interventions and recovery mechanisms may provide valuable evidence for:

- resilience;
- fail-safe design;
- human control;
- operational procedures.

---

## 40. Learning Quality

Lessons should be assessed for:

- evidence basis;
- clarity;
- causal validity;
- applicability;
- specificity;
- actionability;
- transferability.

---

## 41. Governance Review of Lessons

Material lessons should be reviewed by the appropriate governance authority to determine whether they require:

- local action;
- cross-capability action;
- policy change;
- portfolio review;
- revalidation;
- reauthorisation.

---

## 42. Continuous Improvement Metrics

Useful indicators may include:

- overdue corrective actions;
- recurring incidents;
- recurring findings;
- time from incident to lesson validation;
- time from lesson to implementation;
- verification success rate;
- systemic lessons identified;
- lessons transferred across capabilities.

Metrics should support improvement rather than encourage superficial closure.

---

## 43. Closure Criteria

A lesson should be considered closed only when:

- the lesson is validated;
- required actions are completed;
- implementation is verified;
- assurance implications are addressed;
- required governance changes are completed.

---

## 44. Governance Questions

The organisation should be able to answer:

1. How are lessons captured?
2. How are lessons validated?
3. How are local and systemic lessons distinguished?
4. How are lessons transferred across capabilities?
5. How are requirements and controls updated?
6. How are lessons incorporated into TEVV?
7. How are human and autonomy lessons addressed?
8. How are security and dependency lessons addressed?
9. How are training and exercises updated?
10. How are lessons linked to assurance?
11. When does learning trigger revalidation?
12. When does learning trigger reauthorisation?
13. How are actions owned and tracked?
14. How is implementation verified?
15. How are recurring lessons escalated?
16. How is organisational learning institutionalised?

---

## 45. Core Rule

> **The purpose of incident learning is not to document what happened; it is to improve the conditions under which Defence AI is designed, assured, authorised and employed. Validated lessons shall therefore flow back into the governance system and remain visible until the resulting improvement is implemented and verified.**

---

## 46. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Incident → Investigation → Findings → Learning → Requirements/Controls/TEVV/Training/Monitoring Updates → Verification → Assurance Update → Revalidation/Reauthorisation → Continuous Improvement**
