# Risk Monitoring

## Purpose

The D-AIGAAF Risk Monitoring framework defines how AI-related risks are continuously observed during the capability lifecycle and how changes in the risk position trigger action.

The central principle is:

> **Risk does not remain static after authorisation. AI risk must be monitored continuously and reassessed when the conditions supporting the original risk position change.**

The core cycle is:

```text
Risk Assessment
      ↓
Risk Treatment
      ↓
Risk Acceptance
      ↓
Operational Authorisation
      ↓
Operational Monitoring
      ↓
New Evidence / Change / Incident
      ↓
Risk Review
      ↓
Reassessment
      ↓
Revalidation / Reauthorisation
```

---

## 1. Purpose of Risk Monitoring

Risk monitoring should identify:

- changes in AI behaviour;
- changes in performance;
- emerging failure modes;
- control degradation;
- changes in autonomy;
- changes in human control;
- changes in operational environment;
- new threats;
- dependency failures;
- security events;
- information-quality degradation;
- incidents;
- material configuration changes;
- invalidated assumptions.

Monitoring provides the feedback necessary to maintain the Golden Thread throughout operational employment.

---

## 2. Risk Is Dynamic

A risk assessment represents a position at a particular point in time and under defined assumptions.

That position may change because of:

- system changes;
- mission changes;
- environmental changes;
- threat changes;
- human changes;
- dependency changes;
- new evidence;
- incidents;
- operational learning.

Therefore:

> **Operational authorisation should be treated as conditional and reviewable, not as permanent certification.**

---

## 3. What Should Be Monitored?

Monitoring should consider the entire AI-enabled capability rather than the model alone.

Relevant areas include:

- model behaviour;
- software;
- hardware;
- sensors;
- data;
- interfaces;
- communications;
- computing;
- human interaction;
- autonomy;
- operational environment;
- security;
- dependencies;
- supply chain;
- operational procedures;
- mission effectiveness.

---

## 4. Risk Monitoring Dimensions

Monitoring should consider the D-AIGAAF risk dimensions.

### Consequence

Has the potential consequence of failure changed?

### Mission Criticality

Has the importance of the capability to mission success changed?

### Autonomy

Has the system's actual or authorised autonomy changed?

### Environment

Are operating conditions still within the validated envelope?

### Human Control

Can authorised humans still understand, direct and intervene effectively?

### Information Integrity

Can information still be considered sufficiently reliable?

### Security

Has the threat or security exposure changed?

### Dependencies

Are critical dependencies still available, trusted and reliable?

### Uncertainty

Has new evidence reduced or increased uncertainty?

---

## 5. Monitoring Objectives

Monitoring should answer:

1. Is the capability behaving as expected?
2. Is it operating within authorised boundaries?
3. Are controls functioning?
4. Is human control effective?
5. Is autonomy remaining within its authorised level?
6. Are operational assumptions still valid?
7. Are dependencies available and trusted?
8. Has the threat environment changed?
9. Has residual risk changed?
10. Does existing assurance remain valid?

---

## 6. Monitoring Sources

Potential sources include:

- operational logs;
- system telemetry;
- audit records;
- incident reports;
- user feedback;
- commander observations;
- OAIA observations;
- maintenance records;
- security monitoring;
- performance metrics;
- TEVV results;
- red-team findings;
- configuration records;
- supplier notifications;
- vulnerability information;
- environmental information;
- operational lessons.

No single monitoring source should be assumed sufficient for high-consequence systems.

---

## 7. Operational Performance Monitoring

Performance monitoring should consider mission-relevant performance rather than only laboratory metrics.

Possible indicators include:

- accuracy;
- reliability;
- timeliness;
- availability;
- false-positive behaviour;
- false-negative behaviour;
- degradation;
- uncertainty;
- human override frequency;
- failure frequency;
- mission effectiveness.

Metrics should be interpreted in operational context.

A model can maintain benchmark performance while its mission effectiveness deteriorates because the operating environment has changed.

---

## 8. Behaviour Monitoring

Behaviour monitoring should identify material deviations from the assessed and authorised behaviour.

Potential indicators include:

- unexpected outputs;
- unexpected decisions;
- unexpected actions;
- changing output patterns;
- unexplained performance shifts;
- repeated errors;
- boundary violations;
- unexpected interactions;
- unexplained autonomy changes.

Behavioural monitoring should be proportionate to consequence and autonomy.

---

## 9. Autonomy Monitoring

Actual autonomy should be monitored against authorised autonomy.

Monitoring should identify:

- changes in autonomy configuration;
- unexpected autonomous actions;
- expansion of operational scope;
- changes in decision authority;
- changes in action authority;
- unexpected persistence of autonomy;
- failure to reduce autonomy under defined conditions.

> **Technical capability to act autonomously does not itself constitute operational authority to do so.**

---

## 10. Human-Control Monitoring

Monitoring should assess whether meaningful human control remains effective.

Indicators may include:

- intervention delays;
- failed interventions;
- increasing operator workload;
- increasing automation bias;
- inability to interpret outputs;
- inadequate decision time;
- unclear authority;
- increasing override rates;
- inability to regain control.

Human-control degradation may require reduced autonomy or restriction even when technical performance remains acceptable.

---

## 11. Uncertainty Monitoring

AI systems should communicate material uncertainty.

Monitoring should identify:

- changes in confidence;
- increased uncertainty;
- unexpected uncertainty;
- inconsistent outputs;
- out-of-distribution conditions;
- situations where the system lacks sufficient information.

A system should not conceal degraded reliability through confident outputs.

Where uncertainty becomes material, risk controls may require:

- human verification;
- independent information;
- reduced autonomy;
- restricted use;
- suspension.

---

## 12. Information Integrity Monitoring

Monitoring should consider:

- data quality;
- source reliability;
- sensor integrity;
- data freshness;
- data consistency;
- manipulation indicators;
- spoofing;
- missing data;
- contradictory information.

Information integrity degradation can increase mission risk even when the AI model itself has not changed.

---

## 13. Security Monitoring

Security monitoring should identify:

- unauthorised access;
- configuration changes;
- malicious inputs;
- anomalous system activity;
- dependency compromise;
- software vulnerabilities;
- supply-chain events;
- insider activity;
- adversarial manipulation.

Security events should feed risk reassessment where they may affect:

- behaviour;
- autonomy;
- human control;
- operational boundaries;
- mission effectiveness.

---

## 14. Dependency Monitoring

Material dependencies should be continuously assessed where appropriate.

Monitoring may cover:

- communications;
- sensors;
- navigation;
- computing;
- power;
- infrastructure;
- data;
- external services;
- suppliers;
- software components;
- other AI systems.

A dependency failure should trigger the predefined response for that capability.

---

## 15. Environment Monitoring

Monitoring should determine whether operating conditions remain within the validated environment.

Relevant factors may include:

- terrain;
- weather;
- visibility;
- altitude;
- electromagnetic conditions;
- communications;
- infrastructure;
- information conditions;
- adversarial conditions;
- mission tempo.

Moving outside the validated envelope should trigger an appropriate response.

---

## 16. Control Monitoring

Critical controls should be monitored for continued effectiveness.

Examples:

| Control | Monitoring |
|---|---|
| Autonomy limit | Configuration / behaviour monitoring |
| Human approval | Decision records |
| Data integrity | Integrity monitoring |
| Boundary enforcement | Boundary monitoring |
| Fail-safe | Health and test monitoring |
| Access control | Security logs |
| Configuration baseline | Configuration management |
| Communications dependency | Link monitoring |
| Sensor integrity | Sensor health monitoring |

Control monitoring should provide evidence rather than relying solely on declarations.

---

## 17. Monitoring Thresholds

Each capability should define appropriate thresholds.

A generic model is:

```text
Normal
  ↓
Early Warning
  ↓
Enhanced Monitoring
  ↓
Risk Review
  ↓
Restriction / Reduced Autonomy
  ↓
Suspension
  ↓
Fail-Safe / Emergency Protective Action
```

Thresholds should be based on:

- consequence;
- autonomy;
- mission criticality;
- human-control capability;
- operational exposure;
- time available for intervention.

---

## 18. Risk Indicators

Indicators may be:

### Leading Indicators

Signals that risk may be increasing before an incident occurs.

Examples:

- increasing uncertainty;
- rising error rates;
- increasing workload;
- deteriorating communications;
- declining sensor quality;
- repeated near misses.

### Lagging Indicators

Evidence that an adverse event has already occurred.

Examples:

- incidents;
- control failures;
- boundary violations;
- loss-of-control events;
- mission failures;
- security compromises.

Both types should inform risk review.

---

## 19. Risk Monitoring Status

A capability may use a simple monitoring status:

### Green — Stable

No material change identified.

### Amber — Increased Attention

Risk indicators have changed and require enhanced monitoring or review.

### Red — Material Risk Change

Risk position may no longer be valid and requires immediate action.

### Critical — Immediate Protective Action

Conditions may require restriction, suspension, fail-safe or emergency protective action.

These are working constructs and should be calibrated to the organisation's approved risk system.

---

## 20. Monitoring and Risk Appetite

Monitoring should identify when the observed risk approaches or exceeds established organisational risk tolerance.

Where applicable:

```text
Within Tolerance
      ↓
Approaching Tolerance
      ↓
Tolerance Exceeded
      ↓
Escalation
      ↓
Treatment / Restriction / Suspension
```

Risk tolerance does not remove the need for case-specific risk acceptance.

---

## 21. Monitoring and Operational Authorisation

Operational authorisation should specify relevant monitoring requirements.

These may include:

- monitored conditions;
- responsible personnel;
- thresholds;
- reporting requirements;
- escalation authority;
- review frequency;
- suspension criteria;
- reauthorisation triggers.

Monitoring therefore becomes part of the operational control environment.

---

## 22. Monitoring and the Operational AI Advisor

The OAIA may support monitoring by:

- interpreting emerging AI behaviour;
- identifying operational significance;
- assessing whether assumptions remain valid;
- advising commanders on changing AI limitations;
- identifying changes requiring technical review;
- advising on autonomy reduction;
- supporting incident assessment.

The OAIA remains advisory unless explicitly assigned another authority.

**OAIA advises; authorised authority decides.**

---

## 23. Monitoring and Incidents

An incident should not be treated solely as a historical event.

It may provide evidence that:

- assumptions were wrong;
- controls were ineffective;
- the model behaved unexpectedly;
- human control was weaker than expected;
- the environment was inadequately represented;
- the threat model was incomplete;
- dependencies were insufficiently understood.

Incident information should therefore feed:

**Incident Record → Risk Review → Assurance Review → Revalidation → Reauthorisation**

where material.

---

## 24. Monitoring and Change

Changes should be monitored across:

- model;
- software;
- hardware;
- data;
- configuration;
- autonomy;
- sensors;
- interfaces;
- dependencies;
- environment;
- mission.

The significance of a change should be determined by its potential effect on behaviour and operational risk.

---

## 25. Monitoring Supplier Changes

Suppliers may issue:

- software updates;
- model updates;
- security patches;
- dependency changes;
- configuration changes;
- component substitutions.

The organisation should assess whether the change affects:

- behaviour;
- performance;
- autonomy;
- security;
- dependencies;
- assurance;
- operational boundaries.

Supplier notification alone does not determine whether revalidation is required.

---

## 26. Monitoring Assumptions

Material operational assumptions should be monitored for continued validity.

Examples:

- communications availability;
- sensor reliability;
- data quality;
- environmental conditions;
- human staffing;
- supplier support;
- infrastructure availability.

If a material assumption is invalidated, the risk position should be reviewed.

---

## 27. Monitoring Unknowns

Operational experience should be used to discover previously unknown risks.

Sources include:

- incidents;
- near misses;
- user observations;
- unexpected behaviour;
- adversarial testing;
- operational trials;
- new threat information.

The objective is not merely to confirm existing assumptions but to identify what the framework did not previously know.

---

## 28. Risk Review Triggers

A formal risk review should be considered when:

- a threshold is exceeded;
- a material incident occurs;
- loss of control occurs;
- autonomy changes;
- human control degrades;
- environment changes;
- mission changes;
- security events occur;
- dependencies fail;
- assumptions are invalidated;
- control effectiveness declines;
- material new evidence becomes available.

---

## 29. Risk Monitoring Actions

Possible actions include:

- continue monitoring;
- increase monitoring;
- conduct risk review;
- increase human supervision;
- reduce autonomy;
- narrow the operational envelope;
- introduce additional controls;
- restrict employment;
- suspend employment;
- activate fail-safe;
- initiate reassessment;
- initiate revalidation;
- initiate reauthorisation.

The response should be proportionate to the risk.

---

## 30. Monitoring Records

A D-AIGAAF Risk Monitoring Record should include:

| Field | Description |
|---|---|
| Monitoring ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Risk ID | Linked risk |
| Monitoring Period | Observation period |
| Indicators | Indicators monitored |
| Thresholds | Relevant thresholds |
| Observations | Recorded observations |
| Performance | Performance status |
| Autonomy | Actual / authorised autonomy |
| Human Control | Human-control status |
| Environment | Operating conditions |
| Information | Information condition |
| Security | Security status |
| Dependencies | Dependency status |
| Controls | Control status |
| Incidents | Relevant incidents |
| Assumptions | Assumption status |
| Risk Position | Current risk assessment |
| Action | Action taken |
| Escalation | Escalation if required |
| Evidence | Supporting evidence |
| Reviewer | Responsible reviewer |
| Review Date | Date reviewed |
| Status | Current status |

---

## 31. Risk Monitoring Frequency

Monitoring frequency should be proportionate to:

- consequence;
- autonomy;
- mission criticality;
- operational tempo;
- environmental variability;
- threat exposure;
- rate of change.

Possible frequencies include:

- continuous;
- event-driven;
- periodic;
- mission-based;
- configuration-based.

High-consequence capabilities may require near-real-time monitoring of selected indicators.

---

## 32. Monitoring During Degraded Conditions

Monitoring should continue, where technically practicable, during:

- communications loss;
- degraded sensors;
- degraded information;
- high workload;
- adverse environmental conditions;
- adversarial conditions;
- infrastructure degradation.

The system should have predefined behaviour when monitoring itself becomes degraded.

---

## 33. Monitoring Failure

Monitoring mechanisms can themselves fail.

The framework should consider:

- loss of telemetry;
- missing logs;
- corrupted logs;
- monitoring-system compromise;
- delayed alerts;
- false alarms;
- undetected failures.

Critical monitoring failures may themselves be a reason to reduce autonomy or restrict operation.

---

## 34. Monitoring and Evidence

Operational monitoring produces assurance evidence.

Relevant records may include:

- operational performance;
- incidents;
- control performance;
- autonomy behaviour;
- environmental performance;
- human-control observations;
- security events;
- dependency events.

Operational evidence should feed future TEVV, assurance and risk assessment.

---

## 35. Monitoring and Continuous Assurance

Continuous assurance uses operational evidence to determine whether the original assurance position remains valid.

The chain is:

**Operational Monitoring → Evidence → Assurance Review → Risk Reassessment → Revalidation / Reauthorisation**

This prevents assurance from becoming a one-time certification exercise.

---

## 36. Monitoring and Reauthorisation

Material changes in the risk position may require:

- risk reassessment;
- additional TEVV;
- assurance review;
- changed operating conditions;
- reduced autonomy;
- suspension;
- reauthorisation.

Previous authorisation should not automatically continue when the evidence supporting it has materially changed.

---

## 37. Golden Thread

Risk monitoring maintains the feedback loop:

**Mission Need → Use Case → Risk → Treatment → Controls → Testing → Evidence → Assurance → Risk Acceptance → Operational Authorisation → Employment → Monitoring → Change / Incident → Reassessment → Revalidation → Reauthorisation**

The monitoring record should make it possible to identify how operational evidence changes the risk and authority position.

---

## 38. Failure Modes

D-AIGAAF should guard against:

- treating risk assessment as permanent;
- monitoring only model accuracy;
- ignoring operational conditions;
- monitoring only technical metrics;
- failing to monitor human control;
- failing to monitor autonomy;
- ignoring uncertainty;
- ignoring information integrity;
- ignoring dependencies;
- ignoring security indicators;
- relying on one monitoring source;
- setting thresholds without defined responses;
- allowing monitoring failures to go unnoticed;
- ignoring near misses;
- failing to feed incidents into risk assessment;
- allowing supplier updates to bypass change assessment;
- continuing authorisation after the evidence base has materially changed.

---

## 39. Core Rules

1. **Risk monitoring is a continuous lifecycle function.**
2. **Risk should be monitored at capability and mission level, not only model level.**
3. **Operational conditions can change risk without any software change.**
4. **Actual autonomy should be monitored against authorised autonomy.**
5. **Meaningful human control should be monitored during employment.**
6. **Material uncertainty should be visible and monitored.**
7. **Information integrity is part of operational risk monitoring.**
8. **Security and supply-chain events may change the risk position.**
9. **Critical controls require evidence of continued effectiveness.**
10. **Thresholds should have predefined responses.**
11. **Incidents and near misses should feed risk reassessment.**
12. **Invalidated assumptions should trigger review.**
13. **Monitoring failures can themselves create material risk.**
14. **Operational evidence should feed continuous assurance.**
15. **Material changes may require revalidation and reauthorisation.**
16. **Operational authorisation remains conditional on the risk position remaining valid.**

---

## 40. Summary Model

```text
AUTHORISATION
      ↓
OPERATIONAL EMPLOYMENT
      ↓
CONTINUOUS MONITORING
      ↓
OBSERVE:
Behaviour
Performance
Autonomy
Human Control
Environment
Information
Security
Dependencies
Controls
      ↓
ANY MATERIAL CHANGE?
      │
      ├── NO → CONTINUE MONITORING
      │
      └── YES
            ↓
       RISK REVIEW
            ↓
       REASSESSMENT
            ↓
     CONTROL / TEVV REVIEW
            ↓
         ASSURANCE
            ↓
   RESTRICT / SUSPEND / CONTINUE
            ↓
       REVALIDATION
            ↓
       REAUTHORISATION
```

The objective is to ensure that **the risk position supporting operational employment remains visible, current and evidence-based throughout the capability lifecycle, and that material changes trigger timely human review and appropriate action.**
