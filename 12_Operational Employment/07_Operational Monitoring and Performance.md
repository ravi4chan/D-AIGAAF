# 07 — Operational Monitoring and Performance

## 1. Purpose

This document defines governance requirements for monitoring Defence AI during actual operational employment.

The objective is to ensure that system performance, AI behaviour, operational conditions, human interaction, uncertainty, autonomy, security and mission effectiveness remain within the conditions under which the capability is authorised.

Operational monitoring is a core component of continuous assurance. It does not replace TEVV, operational authorisation, incident management or revalidation.

---

## 2. Core Principle

> **A Defence AI capability shall be continuously monitored during operational employment to detect material changes in performance, behaviour, uncertainty, operating conditions, human control, autonomy, security and mission effectiveness. Monitoring shall support timely intervention and shall provide evidence for continued employment, restriction, suspension, revalidation or reauthorisation.**

---

## 3. Monitoring Objective

Operational monitoring should answer:

- Is the AI operating as expected?
- Is performance within authorised limits?
- Are operating conditions still within the assessed envelope?
- Is uncertainty increasing?
- Is human control effective?
- Is autonomy behaving as authorised?
- Are dependencies functioning?
- Are security controls holding?
- Is mission effectiveness being achieved?
- Has anything changed that could invalidate existing assurance?

---

## 4. Monitoring Scope

Monitoring should be proportionate to:

- mission consequence;
- AI role;
- autonomy;
- operational environment;
- human authority;
- system complexity;
- dependency criticality;
- known failure modes;
- threat exposure.

Monitoring should consider both the AI capability and the operational context in which it is being used.

---

## 5. Monitoring Object

The operational monitoring object is:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions**

A change in any material element may affect the interpretation of observed performance.

---

## 6. Monitoring Categories

Operational monitoring may include:

1. system availability;
2. AI performance;
3. output quality;
4. uncertainty;
5. data and information quality;
6. environmental conditions;
7. autonomy;
8. human interaction;
9. security;
10. dependencies;
11. mission effectiveness;
12. incidents and anomalies;
13. configuration and change;
14. intervention events.

---

## 7. Performance Monitoring

Performance should be assessed against predefined measures appropriate to the use case.

Measures may include:

- accuracy;
- precision;
- recall;
- false-positive rate;
- false-negative rate;
- latency;
- availability;
- reliability;
- robustness;
- calibration;
- confidence quality;
- failure frequency.

Metrics should not be interpreted without considering mission context and consequence.

---

## 8. Operational Performance versus Laboratory Performance

Performance demonstrated during testing may not equal performance during employment.

Operational monitoring should therefore account for:

- environmental differences;
- data distribution changes;
- adversarial conditions;
- sensor quality;
- communications;
- workload;
- human interaction;
- system dependencies.

Operational evidence should feed back into assurance.

---

## 9. AI Output Monitoring

Monitoring should identify material changes in:

- output quality;
- confidence;
- uncertainty;
- consistency;
- recommendation quality;
- false positives;
- false negatives;
- unsupported outputs;
- anomalous behaviour.

Material output degradation should trigger the predefined response.

---

## 10. Uncertainty Monitoring

Uncertainty should be monitored as an operational variable.

Indicators may include:

- increased uncertainty;
- missing information;
- conflicting information;
- low-quality inputs;
- out-of-distribution conditions;
- unexplained confidence changes;
- disagreement with trusted sources.

Where uncertainty exceeds defined thresholds, human review or operational restriction may be required.

---

## 11. Data and Information Monitoring

Operational monitoring should consider:

- data availability;
- data integrity;
- timeliness;
- provenance;
- consistency;
- sensor health;
- information gaps;
- distribution changes.

Data anomalies should be assessed for their potential effect on AI outputs and mission decisions.

---

## 12. Environmental Monitoring

The operational environment should be monitored for changes in:

- physical conditions;
- terrain;
- weather;
- illumination;
- electromagnetic conditions;
- communications;
- navigation;
- sensor availability;
- information conditions;
- adversarial activity.

Material environmental change should trigger the applicable response defined in Module 10.

---

## 13. Autonomy Monitoring

The active autonomy state should remain observable to authorised personnel.

Monitoring should identify:

- current autonomy;
- authorised autonomy;
- unexpected transitions;
- autonomy reduction;
- attempted boundary expansion;
- autonomous actions;
- loss of human control.

Technical capability should never be interpreted as permission to increase autonomy.

---

## 14. Human-Control Monitoring

Monitoring should consider whether responsible personnel retain meaningful control.

Indicators may include:

- workload;
- response time;
- intervention availability;
- alert burden;
- situational awareness;
- operator disagreement;
- inability to understand outputs;
- inability to intervene.

A technically functioning system may still become operationally unsuitable if effective human control is degraded.

---

## 15. Human-AI Interaction

Monitoring should identify:

- excessive reliance on AI;
- automation bias;
- repeated rejection of AI recommendations;
- repeated acceptance without meaningful review;
- operator confusion;
- interface failures;
- unclear authority.

Material patterns should inform training, system design, operational restrictions or assurance review.

---

## 16. Security Monitoring

Operational monitoring should include relevant indicators of:

- unauthorised access;
- model or software integrity;
- data manipulation;
- interface compromise;
- abnormal system behaviour;
- dependency compromise;
- malicious inputs;
- security control failure.

Security events should be coordinated with the AI security incident process.

---

## 17. Dependency Monitoring

Critical dependencies should be monitored where failure could affect operational authority or safety.

Examples include:

- communications;
- navigation;
- sensors;
- computing;
- power;
- external information;
- software services;
- supporting systems.

Dependency failure should not result in uncontrolled continuation of AI activity.

---

## 18. Mission Effectiveness Monitoring

Monitoring should determine whether the AI capability continues to contribute to its authorised mission purpose.

Consider:

- mission success criteria;
- operational utility;
- decision quality;
- timeliness;
- human workload;
- unintended effects;
- opportunity costs;
- failure consequences.

A technically accurate AI system may still be operationally ineffective.

---

## 19. Monitoring Thresholds

Each material indicator should have defined thresholds where practical.

A simple model is:

### Green — Within Expected Conditions

Continue employment with normal monitoring.

### Amber — Deviation

Increase monitoring, verify conditions or apply restrictions.

### Red — Material Concern

Initiate protective action, which may include autonomy reduction, human control, safe state or suspension.

---

## 20. Threshold Design

Thresholds should consider:

- mission consequence;
- baseline performance;
- acceptable variance;
- uncertainty;
- time sensitivity;
- reversibility;
- intervention capability.

Thresholds should avoid creating a false impression of precision where uncertainty is significant.

---

## 21. Monitoring Frequency

Monitoring frequency should be proportionate to:

- consequence;
- autonomy;
- operational tempo;
- system volatility;
- environmental variability;
- known failure modes.

Some indicators may require continuous observation, while others may be reviewed periodically.

---

## 22. Event-Driven Monitoring

Monitoring should become more intensive following:

- unexpected outputs;
- intervention;
- autonomy transition;
- environmental change;
- security event;
- dependency failure;
- significant performance degradation;
- human-control concern;
- mission change.

---

## 23. Anomaly Detection

Anomalies should be identified against an appropriate baseline.

An anomaly does not automatically mean system failure.

It should trigger:

**Detect → Assess → Verify → Respond**

The assessment should consider whether the anomaly is:

- expected;
- explainable;
- benign;
- operationally significant;
- potentially unsafe;
- indicative of broader degradation.

---

## 24. Performance Drift

Operational monitoring should identify material performance drift.

Potential causes include:

- changing data;
- environmental change;
- sensor degradation;
- adversarial activity;
- software changes;
- model changes;
- dependency changes;
- unexpected human interaction.

Material drift should feed into the change and revalidation process.

---

## 25. Out-of-Distribution Conditions

Where inputs differ materially from assessed conditions, the organisation should determine whether the AI remains suitable.

Possible responses include:

- continue with monitoring;
- restrict functionality;
- increase human review;
- reduce autonomy;
- transition to safe state;
- suspend employment.

---

## 26. Monitoring and Intervention

Monitoring should connect directly to intervention mechanisms.

A general protective sequence is:

**Detect → Verify → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The applicable response should be defined before operational employment where practicable.

---

## 27. Monitoring and Operational Boundaries

Monitoring should identify conditions approaching or crossing:

- mission boundaries;
- geographic boundaries;
- temporal boundaries;
- functional boundaries;
- autonomy boundaries;
- environmental boundaries;
- configuration boundaries;
- human-authority boundaries.

Boundary uncertainty should itself be treated as an operational concern.

---

## 28. Monitoring under Degraded Conditions

Monitoring should continue, to the extent practicable, during:

- communications degradation;
- disconnected operations;
- sensor degradation;
- navigation uncertainty;
- computing degradation;
- power limitations;
- information degradation.

Where monitoring becomes insufficient to support safe employment, restrictions should apply.

---

## 29. Monitoring under Adversarial Conditions

Monitoring should consider whether observed changes could result from deliberate manipulation.

Indicators may include:

- unusual input patterns;
- unexpected sensor disagreement;
- abnormal confidence;
- inconsistent outputs;
- suspicious system behaviour;
- integrity failures.

Relevant observations should be shared with the applicable security and incident processes.

---

## 30. Multi-AI Monitoring

Where multiple AI systems interact, monitoring should consider:

- individual performance;
- interaction effects;
- dependency chains;
- cascading failures;
- conflicting recommendations;
- combined autonomy;
- shared data or interfaces.

System-of-systems behaviour may differ from the behaviour of individual AI components.

---

## 31. Configuration Monitoring

Operational monitoring should confirm the deployed configuration remains consistent with the authorised configuration.

Material differences may include:

- model version;
- software version;
- data source;
- parameters;
- rules;
- interfaces;
- hardware;
- connected dependencies.

Unapproved material configuration change should trigger the applicable change-control process.

---

## 32. Monitoring and Human Decision-Making

Monitoring information should be presented in a form that supports timely human judgement.

Where appropriate, personnel should be able to understand:

- current system status;
- current autonomy;
- relevant uncertainty;
- important anomalies;
- environmental status;
- intervention availability;
- operational restrictions.

Monitoring should improve situational awareness rather than create additional confusion.

---

## 33. Alerts

Alerts should be:

- meaningful;
- prioritised;
- actionable;
- proportionate;
- understandable.

Excessive alerts can reduce human attention and should be treated as a human-factors concern.

---

## 34. Escalation

Material monitoring findings should have defined escalation routes.

Escalation may involve:

- operator;
- supervisor;
- operational commander;
- OAIA;
- technical authority;
- security authority;
- safety authority;
- governance body.

Escalation thresholds should reflect consequence and urgency.

---

## 35. Monitoring Records

Material monitoring should generate records sufficient to reconstruct relevant operational conditions.

Records may include:

- timestamp;
- capability;
- configuration;
- mission;
- environment;
- autonomy;
- performance indicators;
- uncertainty;
- alerts;
- interventions;
- anomalies;
- decisions;
- actions;
- outcomes.

Records should remain subject to applicable information-security and retention requirements.

---

## 36. Monitoring Evidence

Monitoring evidence should support:

- continued employment;
- restriction;
- incident assessment;
- performance analysis;
- assurance review;
- revalidation;
- reauthorisation.

Evidence should be traceable to the relevant capability, mission, environment and configuration.

---

## 37. Monitoring and Continuous Assurance

Operational monitoring provides evidence for continuous assurance.

The assurance cycle is:

**Monitor → Detect Change → Assess Impact → Act → Verify → Update Assurance**

Monitoring should therefore be integrated with Modules 13, 14 and 15.

---

## 38. Monitoring and Change

A monitoring finding may indicate that:

- no change is required;
- enhanced controls are required;
- operational restrictions are required;
- additional testing is required;
- revalidation is required;
- reauthorisation is required;
- employment must be suspended.

The decision should be proportionate to the materiality of the finding.

---

## 39. Monitoring and Incident Management

A monitoring anomaly becomes an incident where it meets the organisation's defined incident criteria.

Material incidents should trigger:

- protective response;
- evidence preservation;
- assessment;
- investigation;
- corrective action;
- assurance review;
- lessons learned.

---

## 40. Monitoring Governance Review

Operational monitoring arrangements should themselves be reviewed periodically.

Review should consider:

- whether indicators remain relevant;
- whether thresholds remain appropriate;
- whether alerts are effective;
- whether monitoring detects known failure modes;
- whether new failure modes have emerged;
- whether human workload remains acceptable;
- whether evidence remains sufficient.

---

## 41. Monitoring Competence

Personnel responsible for monitoring should understand:

- system purpose;
- expected behaviour;
- key performance indicators;
- uncertainty;
- known limitations;
- autonomy;
- operational boundaries;
- intervention procedures;
- escalation requirements.

---

## 42. Monitoring Dashboard

Where technically appropriate, an operational monitoring view should provide an integrated picture of:

| Area | Example Status |
|---|---|
| Mission | Normal / Restricted |
| System | Normal / Degraded |
| Performance | Within limits / Degraded |
| Uncertainty | Normal / Elevated |
| Environment | Within envelope / Boundary |
| Autonomy | Authorised / Reduced / Anomalous |
| Human Control | Effective / Concern |
| Security | Normal / Concern |
| Dependencies | Available / Degraded |
| Intervention | Available / Failed |
| Authorisation | Valid / Restricted / Suspended |

The dashboard should support judgement rather than replace it.

---

## 43. Governance Questions

The organisation should be able to answer:

1. What must be monitored during employment?
2. Which indicators are safety or mission critical?
3. What are the monitoring baselines?
4. What thresholds trigger action?
5. Who receives alerts?
6. Who can restrict employment?
7. How is autonomy monitored?
8. How is human control monitored?
9. How are uncertainty and anomalies detected?
10. How are degraded and disconnected conditions handled?
11. How are security indicators incorporated?
12. How are dependencies monitored?
13. How are material findings recorded?
14. When does monitoring trigger incident management?
15. When does monitoring trigger revalidation or reauthorisation?

---

## 44. Core Rule

> **Operational monitoring shall provide sufficient and timely information to determine whether a Defence AI capability remains within its authorised mission, environment, autonomy, human authority, configuration and conditions. Material degradation, uncertainty, boundary change, loss of human control, security concern or mission-effectiveness failure shall trigger proportionate assessment and, where required, intervention, restriction, suspension, revalidation or reauthorisation.**

---

## 45. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Autonomy → Employment → Monitoring → Performance → Intervention → Incident/Change → Learning → Revalidation/Reauthorisation**
