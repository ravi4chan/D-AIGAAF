# 02 — Incident Detection and Reporting

## 1. Purpose

This document defines how Defence AI incidents, anomalies and near misses are detected, recognised, reported and escalated under D-AIGAAF.

The objective is to ensure that material events are identified early enough to enable protective action, while preserving accurate information for subsequent investigation, assurance and governance.

---

## 2. Core Principle

> **Defence AI incidents shall be detectable through appropriate human, technical and organisational mechanisms. Reporting shall be timely, accurate, attributable and proportionate to consequence. Detection and reporting mechanisms shall support immediate protective action without requiring complete understanding of the event.**

---

## 3. Detection Objective

Detection should provide sufficient awareness to identify:

- unsafe behaviour;
- abnormal performance;
- loss of human control;
- unexpected autonomy;
- boundary violations;
- security compromise;
- environmental excursions;
- dependency failures;
- material uncertainty;
- conditions requiring intervention.

---

## 4. Detection Sources

Incidents may be detected through:

- operators;
- commanders;
- supervisors;
- technical personnel;
- AI monitoring;
- system alerts;
- automated safety mechanisms;
- security monitoring;
- audit;
- TEVV;
- assurance reviews;
- maintenance;
- user reports;
- external notifications.

No single detection mechanism should be assumed to identify every incident.

---

## 5. Human Detection

Personnel using or supervising Defence AI should be able to recognise:

- unexpected outputs;
- unsafe recommendations;
- abnormal behaviour;
- uncertainty;
- unexpected autonomy;
- loss of control;
- boundary violations;
- system degradation.

Human detection depends on appropriate competence, situational awareness and interface design.

---

## 6. Technical Detection

Technical mechanisms may monitor:

- system health;
- performance;
- output anomalies;
- confidence or uncertainty indicators;
- configuration;
- autonomy state;
- boundary conditions;
- security events;
- communications;
- dependencies.

Technical indicators should support human judgement rather than replace it.

---

## 7. Automated Detection

Automated detection may identify conditions requiring:

- alert;
- restriction;
- autonomy reduction;
- human intervention;
- safe state;
- suspension.

Automated protective action should be defined and tested within the authorised design.

---

## 8. Detection Coverage

Detection mechanisms should be assessed against:

- normal operation;
- degraded operation;
- disconnected operation;
- adversarial conditions;
- time-critical operation;
- high workload;
- limited human availability.

The organisation should identify known detection gaps.

---

## 9. Detection Thresholds

Detection thresholds should consider:

- consequence;
- likelihood;
- uncertainty;
- operating conditions;
- autonomy;
- human control;
- mission requirements.

Thresholds should be reviewed when experience demonstrates that they are ineffective.

---

## 10. Anomaly Detection

Anomalies may include:

- unexpected output;
- abnormal performance;
- unusual input;
- unexpected state transition;
- unusual resource use;
- inconsistent behaviour.

An anomaly should be recorded when it may have assurance or learning significance.

---

## 11. Incident Trigger

An event should be treated as a potential incident when:

- actual harm occurs;
- credible potential harm exists;
- human control is materially affected;
- autonomy behaves unexpectedly;
- a critical boundary is violated;
- a critical control fails;
- material security compromise is suspected;
- assurance assumptions may no longer hold.

---

## 12. Immediate Reporting versus Investigation

Reporting should not wait for:

- root cause;
- complete evidence;
- final severity;
- complete technical diagnosis.

Initial reporting should communicate what is known and what remains uncertain.

---

## 13. First Reporter

The framework should define who may report an incident.

Any person who observes a credible incident or significant anomaly should have an accessible reporting mechanism.

Reporting should not require the observer to determine technical cause.

---

## 14. No-Blame Reporting

Organisations should encourage reporting of:

- incidents;
- near misses;
- unexpected AI behaviour;
- uncertainty;
- control weaknesses;
- unsafe conditions.

The purpose is to improve safety, assurance and learning while maintaining appropriate accountability.

---

## 15. Reporting Channels

Reporting mechanisms may include:

- operational reporting;
- technical reporting;
- safety reporting;
- security reporting;
- assurance reporting;
- emergency escalation.

Channels should remain available during degraded or disconnected conditions where practicable.

---

## 16. Emergency Reporting

Critical events should have immediate escalation mechanisms.

Emergency reporting should prioritise:

1. protection;
2. human control;
3. containment;
4. notification;
5. evidence preservation.

Administrative reporting should not delay protective action.

---

## 17. Initial Incident Report

An initial report should capture, where known:

- incident ID;
- date/time;
- capability;
- mission;
- location or operating context as appropriate;
- configuration;
- autonomy state;
- human authority;
- observed event;
- immediate consequence;
- immediate action;
- current status;
- uncertainty;
- reporter.

---

## 18. Event Timeline

Where practicable, reporting should establish a preliminary timeline:

**Condition → AI Output/Behaviour → Human Observation → Decision → Action → Intervention → Result**

The timeline may be refined during investigation.

---

## 19. AI Contribution

Reports should distinguish:

- AI input;
- AI output;
- AI recommendation;
- AI action;
- human interpretation;
- human decision;
- human action.

This distinction supports accountability and investigation.

---

## 20. Human Action

Reports should identify material human actions such as:

- acceptance;
- rejection;
- modification;
- intervention;
- override;
- autonomy reduction;
- safe-state activation;
- suspension.

The purpose is reconstruction, not automatic attribution of blame.

---

## 21. Uncertainty in Reports

Reports should explicitly identify:

- confirmed facts;
- assumptions;
- unknowns;
- conflicting information;
- suspected causes.

Uncertainty should remain visible throughout the reporting process.

---

## 22. Initial Severity

The initial report should provide a preliminary severity classification where practicable.

Classification should remain subject to later review.

---

## 23. Escalation

Events should be escalated according to predefined thresholds.

Escalation factors may include:

- severity;
- consequence;
- human-control loss;
- autonomy;
- security;
- uncertainty;
- recurrence;
- operational exposure.

---

## 24. Escalation Authority

The organisation should define authorities responsible for:

- receiving reports;
- confirming classification;
- escalating severity;
- initiating protective action;
- notifying higher governance levels.

Emergency authorities should be clear before operational employment.

---

## 25. Notification

Notification should reach appropriate:

- operational authorities;
- safety authorities;
- security authorities;
- technical authorities;
- assurance authorities;
- authorisation authorities.

Notification should be proportionate and avoid unnecessary dissemination.

---

## 26. Security-Related Reporting

Where an incident may involve security compromise, the appropriate security reporting process should be initiated.

Security reporting should be coordinated with operational and safety reporting where AI behaviour or human control is affected.

---

## 27. Safety-Related Reporting

Safety-related incidents should be reported through applicable safety governance mechanisms.

A safety report should identify actual and potential consequence.

---

## 28. Boundary Violation Reporting

Material violations of:

- mission boundaries;
- autonomy boundaries;
- environmental boundaries;
- geographic boundaries;
- temporal boundaries;
- functional boundaries;
- human-authority boundaries;

should receive appropriate escalation.

---

## 29. Unexpected Autonomy Reporting

Unexpected autonomy events should capture:

- authorised autonomy;
- observed autonomy;
- transition;
- action;
- human awareness;
- intervention;
- outcome.

Such events should receive heightened assurance attention.

---

## 30. Loss of Human Control Reporting

Any material loss or degradation of human control should be reported promptly.

Reports should identify:

- control expected;
- control observed;
- duration;
- intervention capability;
- actual intervention;
- outcome.

---

## 31. Degraded and Disconnected Reporting

When normal reporting channels are unavailable, predefined alternative mechanisms should support:

- local recording;
- local notification;
- later synchronisation;
- preservation of evidence.

Connectivity loss should not erase incident accountability.

---

## 32. Multi-AI Reporting

Where multiple AI systems interact, reports should identify:

- participating systems;
- interfaces;
- sequence of interaction;
- shared dependencies;
- human involvement;
- combined operational effect.

---

## 33. Duplicate Reporting

Where an event is reported through multiple channels, the organisation should consolidate records while preserving original reports where necessary.

Duplicate reporting should not result in loss of evidence.

---

## 34. Reporting Quality

Reports should be assessed for:

- completeness;
- accuracy;
- timeliness;
- attribution;
- consistency;
- evidence linkage.

Incomplete reports should be supplemented rather than rejected when the event may be material.

---

## 35. Reporting Data Integrity

Incident reporting systems should protect against:

- unauthorised modification;
- deletion;
- corruption;
- inappropriate access.

Material changes should be traceable.

---

## 36. Reporting and Evidence Preservation

Reporting should initiate or support preservation of relevant evidence, including:

- logs;
- system state;
- configuration;
- AI outputs;
- inputs;
- decisions;
- actions;
- autonomy state;
- environmental conditions;
- security information.

---

## 37. Reporting and Assurance

Incident reports should feed into assessment of:

- assurance claims;
- evidence validity;
- risk;
- controls;
- operating boundaries;
- human control;
- autonomy.

---

## 38. Reporting and Authorisation

Material incidents should be visible to the authority responsible for determining whether employment may:

- continue;
- continue with restrictions;
- require additional assurance;
- require revalidation;
- require reauthorisation;
- be suspended.

---

## 39. Reporting and Continuous Monitoring

Incident detection and reporting should connect with continuous assurance indicators.

Repeated alerts or anomalies may indicate:

- performance drift;
- control weakness;
- changing environment;
- security degradation;
- emerging failure mode.

---

## 40. Reporting Metrics

Organisations may monitor:

- time to detect;
- time to report;
- time to escalate;
- reporting completeness;
- repeat incidents;
- near-miss reporting;
- unresolved reports;
- reporting gaps.

Metrics should improve detection rather than encourage suppression of reporting.

---

## 41. Reporting Review

The reporting process should periodically be reviewed for:

- missed incidents;
- delayed reporting;
- unclear escalation;
- reporting burden;
- false alarms;
- under-reporting;
- systemic detection gaps.

---

## 42. Governance Questions

The organisation should be able to answer:

1. How are incidents detected?
2. Who can report an incident?
3. What events require immediate reporting?
4. How are anomalies and near misses reported?
5. What technical monitoring supports detection?
6. What happens when communications are unavailable?
7. Who receives critical incident reports?
8. How are safety and security reporting coordinated?
9. How are unexpected autonomy events reported?
10. How is loss of human control reported?
11. How is uncertainty represented?
12. How are reports linked to evidence?
13. How are reports protected from unauthorised alteration?
14. How do reports affect assurance?
15. How do reports affect operational authorisation?
16. How is the effectiveness of detection and reporting measured?

---

## 43. Core Rule

> **Any person or mechanism that detects a credible Defence AI incident, significant anomaly or near miss shall be able to initiate reporting without waiting for complete diagnosis. Material events shall be escalated according to predefined criteria, immediate protective action shall take precedence where necessary, and reports shall preserve sufficient information to support investigation, assurance and governance decisions.**

---

## 44. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Detection → Reporting → Classification → Protective Response → Investigation → Corrective Action → Assurance Update → Revalidation/Reauthorisation → Learning**
