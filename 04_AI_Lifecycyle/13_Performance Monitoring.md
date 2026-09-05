# Performance Monitoring

## Summary

Performance Monitoring governs the continuous observation of an AI capability after deployment and during operational employment.

Its purpose is to determine whether the capability continues to perform within its authorised performance envelope, whether assumptions remain valid, and whether emerging degradation, drift, incidents or new risks require intervention.

The core chain is:

**Baseline → Monitor → Detect → Assess → Escalate → Act → Revalidate / Reauthorise**

Performance monitoring is not limited to accuracy. In defence environments, operational suitability may also depend on reliability, robustness, uncertainty, data quality, latency, availability, human interaction, autonomy, safety, security and mission effectiveness.

---

## 1. Purpose

Performance Monitoring establishes controls to:

- detect material performance degradation;
- identify distribution shift;
- monitor reliability and robustness;
- detect changes in uncertainty;
- identify data-quality problems;
- monitor human-AI interaction;
- monitor authorised autonomy;
- identify safety or security concerns;
- provide evidence for continuous assurance;
- trigger appropriate intervention.

---

## 2. Core Principle

**An AI capability that was acceptable at deployment is not automatically acceptable indefinitely.**

Operational performance must remain observable and comparable with the evidence and assumptions supporting its authorisation.

---

## 3. Scope

Monitoring may cover:

- model performance;
- system performance;
- data;
- environment;
- human interaction;
- autonomy;
- safety;
- security;
- configuration;
- mission effectiveness;
- incidents;
- near misses.

The depth and frequency of monitoring should be proportionate to:

**Consequence × Mission Criticality × Autonomy × Operational Exposure**

---

## 4. Performance Baseline

Monitoring should use an approved baseline established during assurance.

The baseline may contain:

- expected performance;
- acceptable variation;
- known limitations;
- uncertainty characteristics;
- operating envelope;
- environmental assumptions;
- failure modes;
- availability requirements;
- latency requirements;
- safety thresholds;
- autonomy constraints.

---

## 5. What Should Be Monitored

A performance monitoring programme should consider at least:

1. Technical Performance
2. Reliability
3. Robustness
4. Data Quality
5. Uncertainty
6. Operational Environment
7. Human-AI Interaction
8. Autonomy
9. Safety
10. Security
11. Mission Effectiveness
12. Configuration Integrity

---

## 6. Technical Performance

Depending on the capability, monitoring may include:

- accuracy;
- precision;
- recall;
- false-positive rate;
- false-negative rate;
- classification performance;
- detection performance;
- prediction error;
- ranking quality;
- response quality;
- latency.

Metrics should be relevant to the actual operational task rather than selected only because they are easy to measure.

---

## 7. Reliability

Reliability monitoring may include:

- system availability;
- service interruptions;
- processing failures;
- repeated errors;
- crashes;
- timeout rates;
- recovery performance;
- component failures.

Repeated low-level failures may indicate a higher-level operational risk.

---

## 8. Robustness

Monitoring should identify whether performance changes under:

- environmental variation;
- sensor variation;
- degraded data;
- communications disruption;
- unusual inputs;
- changing operating conditions;
- adversarial conditions.

Robustness should be considered against the authorised operating envelope.

---

## 9. Data Quality

Operational data should be monitored for:

- completeness;
- accuracy;
- freshness;
- consistency;
- provenance;
- unexpected distributions;
- missing fields;
- corrupted inputs;
- anomalous patterns.

Data degradation may appear as model degradation even when the model itself has not changed.

---

## 10. Distribution Shift

Distribution shift occurs when operational inputs differ materially from those represented during development or assurance.

Potential indicators include:

- changing input distributions;
- new sensor characteristics;
- changing environmental conditions;
- new operational patterns;
- previously unseen conditions;
- changing adversarial behaviour.

Material distribution shift should trigger assessment rather than automatic continued use.

---

## 11. Uncertainty Monitoring

Systems should monitor whether uncertainty behaves consistently with assurance expectations.

Potential indicators include:

- excessive confidence;
- confidence collapse;
- unexpected certainty under degraded inputs;
- increased abstention;
- disagreement between model outputs and independent evidence.

High-confidence incorrect outputs should receive particular attention in high-consequence applications.

---

## 12. Confabulation and Unsupported Output

For systems capable of generating natural-language or other inferential outputs, monitoring should consider:

- unsupported claims;
- fabricated information;
- incorrect attribution;
- loss of source traceability;
- inconsistent reasoning;
- inappropriate certainty.

Where relevant, monitoring should verify that the system distinguishes information from inference.

---

## 13. Human-AI Interaction

Monitoring may include:

- frequency of human overrides;
- rejection of recommendations;
- repeated user corrections;
- automation bias indicators;
- user misunderstanding;
- excessive reliance;
- failure to review outputs;
- workload effects.

Human interaction can be an indicator of system performance and operational risk.

---

## 14. Human Override

Human overrides should not automatically be treated as system failures.

They may indicate:

- appropriate human judgement;
- model limitations;
- changing context;
- inadequate system design;
- poor user understanding;
- inappropriate AI recommendations.

Patterns in overrides should be analysed rather than interpreted in isolation.

---

## 15. Autonomy Monitoring

Where autonomous functions are authorised, monitoring should include:

- actual autonomy level;
- autonomy transitions;
- intervention frequency;
- unexpected actions;
- failed interventions;
- boundary violations;
- termination events.

Observed behaviour should remain consistent with the authorised autonomy level.

---

## 16. Safety Monitoring

Safety monitoring should identify:

- unsafe outputs;
- unsafe recommendations;
- loss of human control;
- failed safeguards;
- unexpected actions;
- unintended effects;
- near misses.

Near misses should be treated as valuable assurance evidence.

---

## 17. Security Monitoring

Monitoring should consider:

- unauthorised access;
- model integrity;
- data integrity;
- abnormal inputs;
- suspicious behaviour;
- dependency changes;
- compromised components;
- anomalous system activity.

Security monitoring should connect with the applicable AI Security and incident processes.

---

## 18. Configuration Monitoring

The deployed capability should be monitored against its authorised configuration baseline.

Potential changes include:

- model;
- model weights;
- software;
- firmware;
- parameters;
- data sources;
- interfaces;
- dependencies;
- safety controls;
- security controls.

Unknown configuration changes should be treated as potentially significant.

---

## 19. Operational Environment

Monitoring should assess whether the actual environment remains within the conditions supporting assurance.

Relevant factors may include:

- terrain;
- weather;
- sensor conditions;
- communications;
- data availability;
- infrastructure;
- adversarial conditions;
- compute availability.

Environmental change may require reassessment even when the model has not changed.

---

## 20. Mission Effectiveness

Monitoring should ultimately assess whether the AI capability continues to support its intended mission.

Possible indicators include:

- mission-relevant outcomes;
- decision quality;
- timeliness;
- resource efficiency;
- reliability;
- user confidence;
- operational limitations.

Technical performance should not be treated as a complete substitute for mission effectiveness.

---

## 21. Monitoring Frequency

Monitoring frequency should be risk-based.

Possible categories include:

### Continuous

For high-consequence or highly autonomous functions where real-time observation is necessary.

### Frequent

For capabilities where material degradation can develop rapidly.

### Periodic

For lower-risk capabilities where performance changes more slowly.

### Event-Driven

Triggered by incidents, changes, unusual behaviour or environmental shifts.

---

## 22. Monitoring Thresholds

Thresholds should be defined where practical.

Examples include:

- performance degradation;
- increased error rates;
- increased uncertainty;
- increased abstention;
- reduced availability;
- configuration deviation;
- safety events;
- security anomalies;
- autonomy anomalies.

Thresholds should correspond to meaningful operational consequences.

---

## 23. Warning Levels

A working monitoring model is:

### Normal

Performance remains within expected bounds.

### Watch

Early indication of potential degradation.

### Alert

Material deviation requiring assessment.

### Restricted

Operational use limited while assessment occurs.

### Suspended

Operational use stopped pending resolution.

### Reauthorisation Required

Existing authorisation may no longer be sufficient.

---

## 24. Anomaly Detection

Anomalies should be assessed in context.

A single unusual event may not demonstrate systemic degradation.

Conversely, repeated small deviations may indicate an emerging problem.

Monitoring should therefore consider:

- magnitude;
- frequency;
- persistence;
- operational consequence;
- correlation with environmental change;
- correlation with configuration change.

---

## 25. Monitoring and the Operating Envelope

Monitoring should distinguish between:

- performance inside the authorised envelope;
- performance near the boundary;
- performance outside the envelope.

Operation outside the envelope should not be normalised simply because the system continues to produce outputs.

---

## 26. Degraded Performance

When material degradation is detected, possible responses include:

- increased human supervision;
- restricted use;
- reduced autonomy;
- degraded mode;
- additional verification;
- technical investigation;
- suspension;
- revalidation;
- reauthorisation.

The response should be proportionate to risk.

---

## 27. Performance Drift

Performance drift may result from:

- changing data;
- changing environment;
- changing users;
- changing adversarial behaviour;
- system degradation;
- dependency changes;
- model updates.

Monitoring should seek to distinguish these causes where practical.

---

## 28. Model Drift vs System Drift

Performance degradation may arise from:

### Model Drift

The model's behaviour changes relative to expected performance.

### Data Drift

Operational inputs change.

### System Drift

The wider integrated system changes.

### Environment Drift

The operational environment changes.

### Mission Drift

The system is increasingly used for purposes different from those originally authorised.

The response should address the actual source of the problem.

---

## 29. Mission Drift

Mission drift occurs when a capability gradually becomes used for purposes beyond the original authorised use case.

Indicators may include:

- new users;
- new missions;
- new decisions;
- new data sources;
- new environments;
- increased autonomy.

Mission drift should trigger governance review.

---

## 30. Monitoring Autonomy Expansion

Where users discover that the system can technically perform functions beyond its authorised autonomy, those functions should not be enabled informally.

Capability discovery should not become unauthorised autonomy expansion.

---

## 31. Operational AI Advisor

The **Operational AI Advisor (OAIA)** may support interpretation of monitoring results.

The OAIA may help determine:

- whether behaviour is expected;
- whether environmental factors explain degradation;
- whether the issue is technical or operational;
- whether additional testing is required;
- whether restrictions should be imposed;
- whether reauthorisation may be necessary.

The OAIA does not replace formal technical assurance or command authority.

---

## 32. Escalation

Monitoring findings should be escalated according to consequence.

A working path is:

**Monitoring → System Manager → OAIA / Technical Authority → Assurance Authority → Operational Authority**

Critical safety or security events should follow applicable emergency procedures.

---

## 33. Monitoring Evidence

Monitoring should produce evidence that can support:

- continued assurance;
- incident investigation;
- risk reassessment;
- performance analysis;
- revalidation;
- reauthorisation;
- audit.

Evidence should be linked to the relevant capability and configuration.

---

## 34. Monitoring Data Integrity

Monitoring itself must be trustworthy.

Monitoring records should be protected against:

- unauthorised alteration;
- deletion;
- incomplete collection;
- incorrect timestamps;
- loss of configuration context.

A monitoring system that cannot be trusted weakens the assurance chain.

---

## 35. False Alarms

Excessive false alarms can create operational fatigue.

Monitoring thresholds should therefore balance:

- sensitivity;
- specificity;
- consequence;
- workload;
- response capacity.

High-consequence systems may appropriately tolerate greater alert sensitivity.

---

## 36. Monitoring and Fail-Safe

Where monitoring detects behaviour that could create unacceptable harm, predefined protective responses should be available.

These may include:

- restricting functionality;
- reducing autonomy;
- switching to degraded mode;
- requiring additional human approval;
- suspending operation;
- activating fail-safe.

Emergency protective action should follow pre-authorised procedures.

---

## 37. Monitoring After Incidents

Following an incident, monitoring should be enhanced where appropriate.

The enhanced period may examine:

- recurrence;
- related failure modes;
- configuration stability;
- user behaviour;
- environmental triggers;
- effectiveness of corrective actions.

---

## 38. Monitoring After Changes

Following a material change, monitoring should verify that:

- expected behaviour remains valid;
- no new failure modes emerge;
- performance remains within the approved baseline;
- operational assumptions remain valid.

Material changes may require formal revalidation and reauthorisation.

---

## 39. Monitoring Across Environments

Where a capability is authorised across multiple operational environments, performance should be assessed separately where necessary.

A system performing acceptably in one environment should not automatically be assumed to perform equally well in another.

---

## 40. Monitoring Across Autonomy Levels

Performance evidence should be interpreted against the actual autonomy level.

A model suitable for:

**A2 — Analysis / Recommendation**

is not automatically suitable for:

**A4 — Supervised Autonomous Action**

Increasing autonomy increases the consequences of performance failure and should increase assurance requirements.

---

## 41. Monitoring and Risk

Monitoring should feed the risk process.

Potential changes may affect:

- likelihood;
- consequence;
- mission criticality;
- autonomy;
- human control;
- residual risk.

Material risk changes may require risk acceptance to be revisited.

---

## 42. Monitoring and Operational Authorisation

Operational authorisation should define, where appropriate:

- performance expectations;
- monitoring requirements;
- thresholds;
- reporting;
- suspension triggers;
- review frequency.

Monitoring therefore becomes part of maintaining the validity of operational authority.

---

## 43. Continuous Assurance

Performance monitoring is a major input to continuous assurance.

The assurance cycle is:

**Authorised Baseline → Operational Monitoring → Evidence → Risk Assessment → Assurance Review → Continued Use / Restriction / Revalidation / Reauthorisation**

---

## 44. Monitoring Record

A Performance Monitoring Record should include, as applicable:

| Field | Description |
|---|---|
| Capability ID | AI capability identifier |
| Configuration | Configuration being monitored |
| Mission | Authorised mission |
| Environment | Relevant environment |
| Autonomy | Active autonomy level |
| Metric | Performance metric |
| Baseline | Approved expectation |
| Observation | Observed performance |
| Threshold | Applicable threshold |
| Trend | Performance trend |
| Uncertainty | Relevant uncertainty |
| Data Quality | Data condition |
| Incident | Related incident |
| Action | Response taken |
| Authority | Responsible authority |
| Evidence | Supporting evidence |
| Date | Observation/review date |
| Status | Current monitoring status |

---

## 45. Monitoring Review

Periodic review should assess:

- trends;
- recurring anomalies;
- changes;
- incidents;
- near misses;
- environmental effects;
- human interaction;
- autonomy behaviour;
- mission effectiveness;
- continuing suitability.

The review should distinguish isolated events from systemic degradation.

---

## 46. Revalidation Triggers

Monitoring should trigger consideration of revalidation when:

- material performance degradation occurs;
- distribution shift becomes significant;
- new environments emerge;
- material configuration changes occur;
- new data sources are introduced;
- autonomy changes;
- significant incidents occur;
- safety assumptions become invalid;
- mission use changes.

---

## 47. Reauthorisation Triggers

Reauthorisation should be considered when monitoring demonstrates that the existing operational authority may no longer adequately describe:

- capability;
- mission;
- environment;
- autonomy;
- human authority;
- risk;
- operating envelope.

---

## 48. Retirement Signals

Monitoring may identify that a capability should be considered for retirement when:

- performance cannot be restored;
- assurance evidence becomes inadequate;
- dependencies become unsustainable;
- security risks cannot be adequately controlled;
- mission need disappears;
- replacement capability provides materially better assurance.

---

## 49. Core Rules

1. **Operational performance must remain observable throughout the AI lifecycle.**
2. **Monitoring must be based on an approved performance and risk baseline.**
3. **Performance monitoring must consider more than model accuracy.**
4. **Data, environment and system changes can produce degradation without a model update.**
5. **Meaningful uncertainty and confidence behaviour should be monitored.**
6. **Human overrides and user behaviour are important assurance signals.**
7. **Autonomy behaviour must be monitored against the authorised level.**
8. **Configuration integrity must be monitored continuously or at a risk-appropriate frequency.**
9. **Near misses should be treated as assurance evidence.**
10. **Material deviations should trigger assessment and appropriate escalation.**
11. **Monitoring thresholds should be linked to operational consequences.**
12. **Monitoring evidence must itself be protected and trustworthy.**
13. **Material degradation may require restriction, suspension, revalidation or reauthorisation.**
14. **Continuous monitoring does not replace formal assurance or operational authority.**

---

## 50. Golden Thread

Performance Monitoring maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Authority → Deployment → Employment → Monitoring → Risk Change → Revalidation → Reauthorisation**

---

## 51. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **03 Risk & Autonomy** — provides risk and autonomy thresholds.
- **08 Human Authority** — establishes human control and override.
- **09 TEVV** — provides the performance baseline and evidence.
- **10 Operational Environment** — defines environmental conditions.
- **11 Operational Authorisation** — defines authorised performance and monitoring conditions.
- **12 Operational Employment** — provides operational usage context.
- **13 Continuous Assurance** — uses monitoring evidence for continued assurance.
- **14 Incident & Fail-Safe** — governs abnormal behaviour and protective action.
- **15 Change & Reauthorisation** — governs response to material changes.
- **16 Audit & Evidence** — preserves monitoring evidence.
- **24 Architecture & Technical Controls** — supports monitoring infrastructure.

---

## 52. Summary Model

```text
Approved Baseline
        ↓
Operational Monitoring
        ↓
Performance / Data / Environment / Human / Autonomy Signals
        ↓
Anomaly Detection
        ↓
Risk Assessment
        ↓
Normal / Watch / Alert
        ↓
Continue / Restrict / Degrade / Suspend
        ↓
Technical & Operational Investigation
        ↓
Revalidation
        ↓
Reauthorisation
        ↓
Updated Baseline
        ↓
Continuous Monitoring
```

Performance Monitoring ensures that operational trust in an AI capability remains evidence-based rather than being treated as permanent once initial authorisation has been granted.
