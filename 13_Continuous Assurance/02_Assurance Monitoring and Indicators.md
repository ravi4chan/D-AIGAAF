# 02 — Assurance Monitoring and Indicators

## 1. Purpose

This document defines the governance approach for selecting, maintaining and interpreting indicators used to monitor the continuing assurance of Defence AI capabilities.

Assurance monitoring converts operational, technical, human, environmental and security observations into structured signals that can identify emerging loss of confidence before or while it becomes a material governance issue.

---

## 2. Core Principle

> **Assurance indicators shall provide timely and meaningful signals about changes that could affect confidence in a Defence AI capability. Indicators shall be linked to assurance claims, interpreted in context and connected to predefined assessment and response mechanisms. No single indicator shall be treated as conclusive evidence of assurance or failure without appropriate assessment.**

---

## 3. Monitoring Objective

Assurance monitoring should identify:

- degradation;
- unexpected behaviour;
- emerging risk;
- invalidated assumptions;
- control weakness;
- environmental change;
- human-control concerns;
- autonomy concerns;
- security concerns;
- dependency failures;
- evidence gaps.

---

## 4. Indicator Hierarchy

Indicators may be structured as:

**Assurance Claim → Domain → Indicator → Threshold → Assessment → Action**

For example:

**Human-Control Assurance → Intervention Effectiveness → Intervention Success Rate → Defined Threshold → Assessment → Restriction or Review**

---

## 5. Indicator Categories

D-AIGAAF may use indicators covering:

1. mission performance;
2. technical performance;
3. AI output quality;
4. uncertainty;
5. data;
6. human control;
7. autonomy;
8. environment;
9. security;
10. dependencies;
11. incidents;
12. configuration;
13. assurance evidence;
14. corrective actions.

---

## 6. Leading and Lagging Indicators

### Leading Indicators

Signals that may indicate an emerging problem before a material failure occurs.

Examples:

- increasing uncertainty;
- rising anomaly frequency;
- declining data quality;
- increasing operator workload;
- growing intervention frequency.

### Lagging Indicators

Evidence of an event or outcome that has already occurred.

Examples:

- incidents;
- system failures;
- consequential errors;
- boundary violations;
- security compromises.

Both types are useful for continuous assurance.

---

## 7. Indicator Design

Each material indicator should have, where practical:

- definition;
- purpose;
- assurance claim;
- data source;
- measurement method;
- baseline;
- threshold;
- owner;
- review frequency;
- limitations;
- escalation route.

---

## 8. Indicator Baseline

A baseline establishes the expected operating range.

Baselines should account for:

- system configuration;
- mission;
- environment;
- autonomy;
- human interaction;
- operating tempo.

A single universal baseline may be inappropriate for materially different operational contexts.

---

## 9. Thresholds

Thresholds should identify when observed conditions require further assessment.

Possible levels:

### Green

Within expected range.

### Amber

Material deviation requiring increased attention or assessment.

### Red

Material concern requiring defined protective or governance action.

Thresholds should support judgement rather than create false precision.

---

## 10. Dynamic Thresholds

Where appropriate, thresholds may vary according to:

- mission consequence;
- autonomy;
- environment;
- operating tempo;
- system state;
- data quality;
- threat conditions.

Any dynamic thresholding should itself be governed and validated.

---

## 11. Indicator Context

An indicator should not be interpreted independently of its context.

For example, increased intervention frequency may indicate:

- system degradation;
- changing operational conditions;
- improved human vigilance;
- changed mission demands;
- inappropriate system configuration.

Assessment should determine the underlying cause.

---

## 12. Performance Indicators

Relevant indicators may include:

- accuracy;
- precision;
- recall;
- false positives;
- false negatives;
- latency;
- availability;
- failure rate;
- reliability;
- robustness;
- calibration.

The selected indicators should reflect the actual mission consequence of errors.

---

## 13. Uncertainty Indicators

Indicators may monitor:

- confidence distribution;
- uncertainty levels;
- information gaps;
- conflicting sources;
- out-of-distribution inputs;
- unexplained confidence changes;
- prediction instability.

Increasing uncertainty may require increased human review or restricted employment.

---

## 14. Data Indicators

Relevant data indicators may include:

- completeness;
- timeliness;
- integrity;
- provenance;
- distribution shift;
- missing data;
- sensor disagreement;
- data-quality anomalies.

Data indicators should be connected to the risks arising from degraded AI inputs.

---

## 15. Human-Control Indicators

Human-control assurance may monitor:

- intervention time;
- intervention success;
- override availability;
- workload;
- alert burden;
- decision time;
- operator disagreement;
- automation reliance;
- situational awareness concerns.

A technically available control that cannot be effectively exercised should be treated as a concern.

---

## 16. Autonomy Indicators

Autonomy indicators may include:

- active autonomy state;
- authorised autonomy state;
- unexpected transitions;
- autonomy reductions;
- boundary events;
- autonomous action frequency;
- human intervention frequency.

Unexpected autonomy behaviour should trigger appropriate assessment.

---

## 17. Environmental Indicators

Indicators may cover:

- environmental conditions;
- sensor availability;
- communications;
- navigation;
- electromagnetic conditions;
- information availability;
- conditions approaching operational boundaries.

Environmental indicators should connect to the operating envelope established in Module 10.

---

## 18. Security Indicators

Relevant security indicators may include:

- unauthorised access;
- integrity alerts;
- abnormal inputs;
- software anomalies;
- data manipulation;
- model integrity concerns;
- dependency compromise;
- failed security controls.

Security indicators should integrate with Module 06.

---

## 19. Dependency Indicators

Critical dependencies may require indicators for:

- availability;
- latency;
- integrity;
- failure;
- degradation;
- recovery.

A dependency indicator should reflect its effect on the AI capability rather than merely reporting technical status.

---

## 20. Incident Indicators

Useful indicators may include:

- incident frequency;
- incident severity;
- recurring incident types;
- unresolved incidents;
- time to containment;
- corrective-action status.

Incident frequency alone should not be treated as the complete measure of system safety.

---

## 21. Configuration Indicators

Monitoring should identify:

- unauthorised configuration change;
- model version change;
- software version change;
- data-source change;
- interface change;
- dependency change.

Material configuration change should enter the change-assessment process.

---

## 22. Evidence Currency Indicators

Assurance monitoring should identify ageing or weakening evidence.

Examples include:

- time since last relevant validation;
- percentage of current evidence;
- expired reviews;
- unresolved evidence gaps;
- unreviewed operational findings.

Evidence ageing does not automatically invalidate assurance but should trigger review where appropriate.

---

## 23. Assurance Debt Indicators

Assurance debt may be monitored through:

- open evidence gaps;
- overdue corrective actions;
- unresolved anomalies;
- pending testing;
- pending independent review;
- temporary compensating controls.

Increasing assurance debt may indicate declining confidence even when operational performance appears stable.

---

## 24. Indicator Correlation

Multiple indicators may provide stronger signals than any individual indicator.

Examples:

**Performance Degradation + Environmental Change**

may indicate environmental unsuitability.

**Increasing Uncertainty + Increasing Intervention**

may indicate declining AI usefulness.

**Security Alert + Output Anomaly**

may indicate possible integrity compromise.

Correlation should trigger assessment rather than automatic conclusions.

---

## 25. Indicator Trends

Trends may be more informative than individual observations.

The organisation should consider:

- direction;
- rate of change;
- persistence;
- recurrence;
- seasonality where relevant;
- operational context.

A gradual decline may be significant even if no individual measurement crosses a threshold.

---

## 26. Anomaly Indicators

An anomaly is an observation that differs materially from an expected baseline or pattern.

Anomaly assessment should determine whether it is:

- expected variation;
- measurement error;
- benign anomaly;
- operational concern;
- technical failure;
- security concern;
- evidence of changed conditions.

---

## 27. Composite Assurance Indicators

For mature governance, composite indicators may combine multiple dimensions.

For example:

**Assurance Health = f(Performance, Human Control, Autonomy, Environment, Security, Evidence, Incidents)**

Composite measures should remain transparent enough that decision-makers can understand the underlying factors.

---

## 28. Avoiding Aggregate Masking

Aggregate scores should not conceal a critical failure.

For example, strong technical performance should not compensate for:

- loss of human control;
- serious security compromise;
- invalid authorisation;
- critical boundary violation.

Critical domains may therefore require independent gating criteria.

---

## 29. Indicator Ownership

Each material indicator should have an accountable owner responsible for:

- data quality;
- interpretation;
- threshold maintenance;
- review;
- escalation;
- corrective action where applicable.

Ownership should be clearly documented.

---

## 30. Data Quality for Indicators

Indicator data should itself be subject to quality controls.

Consider:

- completeness;
- accuracy;
- timeliness;
- integrity;
- provenance;
- consistency.

Poor indicator data can create false assurance.

---

## 31. Monitoring Frequency

Frequency should be proportionate to:

- consequence;
- volatility;
- autonomy;
- operational tempo;
- threat;
- environmental variability.

Some indicators may require continuous monitoring, while others may be reviewed periodically.

---

## 32. Event-Driven Monitoring

Monitoring intensity should increase following:

- incidents;
- unexpected autonomy;
- significant intervention;
- security events;
- environmental excursions;
- major configuration changes;
- material performance degradation.

---

## 33. Escalation Thresholds

Indicators should connect to defined escalation routes.

Possible escalation sequence:

**Operator → Supervisor → Operational Authority → Technical/Security/Safety Authority → Governance Body**

The appropriate route depends on the nature and consequence of the finding.

---

## 34. Indicator Response

Possible responses include:

- continue monitoring;
- verify;
- increase monitoring;
- add controls;
- restrict functionality;
- reduce autonomy;
- require human control;
- initiate incident management;
- initiate revalidation;
- initiate reauthorisation;
- suspend employment.

---

## 35. Indicator Validation

Material indicators should be assessed to determine whether they actually provide useful signals.

Validation may consider:

- sensitivity;
- specificity;
- false alarms;
- missed events;
- stability;
- interpretability;
- operational usefulness.

---

## 36. Alert Fatigue

Excessive or low-value alerts may reduce the effectiveness of human monitoring.

The organisation should periodically review:

- alert frequency;
- priority;
- actionability;
- duplication;
- false alarms.

Alert design should support rather than undermine situational awareness.

---

## 37. Human Interpretation

Indicators should be presented with sufficient context for responsible personnel to understand:

- what changed;
- why it matters;
- how certain the observation is;
- what authority applies;
- what action may be required.

Indicators should not replace human judgement for consequential governance decisions.

---

## 38. Assurance Dashboard

A dashboard may provide a structured view of:

| Domain | Example Indicator | Status |
|---|---|---|
| Performance | Error rate | Green / Amber / Red |
| Uncertainty | Confidence degradation | Green / Amber / Red |
| Human Control | Intervention effectiveness | Green / Amber / Red |
| Autonomy | Unexpected transition | Green / Amber / Red |
| Environment | Envelope excursion | Green / Amber / Red |
| Security | Integrity alert | Green / Amber / Red |
| Dependencies | Critical failure | Green / Amber / Red |
| Incidents | Open material events | Green / Amber / Red |
| Evidence | Evidence currency | Green / Amber / Red |
| Assurance Debt | Open material gaps | Green / Amber / Red |

---

## 39. Indicator Review

Indicator sets should be periodically reviewed for:

- continued relevance;
- effectiveness;
- redundancy;
- missed failure modes;
- changed risks;
- changed technology;
- changed operational conditions.

New lessons may require new indicators.

---

## 40. Indicator Change Control

Changes to material indicators or thresholds should be governed.

Changes should consider whether they affect:

- assurance conclusions;
- escalation;
- operational restrictions;
- authorisation conditions;
- evidence comparability.

Material changes should be recorded.

---

## 41. Indicator Records

Records should preserve where appropriate:

- indicator definition;
- measurement;
- timestamp;
- baseline;
- threshold;
- context;
- status;
- assessment;
- action;
- reviewer.

Historical indicator data should remain available where required for trend analysis and assurance.

---

## 42. Governance Questions

The organisation should be able to answer:

1. Which indicators support each assurance claim?
2. Which indicators are leading and which are lagging?
3. What are the baselines?
4. What thresholds trigger action?
5. Who owns each indicator?
6. How is indicator data validated?
7. How are trends assessed?
8. How are correlated indicators interpreted?
9. Can aggregate scores hide critical failures?
10. How are human-control indicators measured?
11. How is autonomy monitored?
12. How are environmental and security indicators integrated?
13. What triggers escalation?
14. How are indicators reviewed and changed?
15. How does indicator evidence feed revalidation and reauthorisation?

---

## 43. Core Rule

> **Assurance indicators shall be explicitly linked to material assurance claims and shall provide meaningful signals of changes in performance, risk, human control, autonomy, environment, security, dependencies, incidents and evidence. Indicators shall be interpreted in context, protected against poor data quality and excessive aggregation, and connected to defined escalation and governance actions.**

---

## 44. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance Claim → Indicators → Monitoring → Assessment → Action → Verification → Revalidation/Reauthorisation → Learning**
