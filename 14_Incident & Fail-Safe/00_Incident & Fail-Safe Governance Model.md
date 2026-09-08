# 00 — Incident & Fail-Safe Governance Model

## 1. Purpose

This document establishes the governance model for managing incidents, unsafe behaviour, loss of control, unexpected AI behaviour and fail-safe responses throughout the lifecycle and operational employment of Defence AI capabilities.

The objective is to ensure that incidents are detected, contained, investigated, learned from and used to restore or revise assurance without allowing operational continuity to override safety, security, human authority or governance requirements.

---

## 2. Core Principle

> **A Defence AI capability shall have defined, tested and proportionate mechanisms for detecting, containing and responding to incidents and unsafe conditions. When continued AI operation can no longer be justified, the capability shall transition to an appropriately restricted, human-controlled, safe or suspended state. Incident response shall preserve evidence, maintain accountability and feed material findings into assurance, revalidation, reauthorisation and continuous improvement.**

---

## 3. Scope

This module applies to incidents involving:

- AI behaviour;
- AI outputs;
- model or system failure;
- loss of human control;
- unexpected autonomy;
- boundary violations;
- safety-control failure;
- security compromise;
- data or information integrity;
- degraded or disconnected operation;
- environmental conditions;
- critical dependencies;
- human-AI interaction;
- configuration;
- multi-AI interaction.

---

## 4. Incident Governance Object

Incident governance should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

An incident may affect one or several elements simultaneously.

---

## 5. Incident Definition

For D-AIGAAF purposes, an incident is an event or condition that:

- causes or could cause unacceptable harm;
- materially degrades AI performance;
- causes unexpected or unsafe behaviour;
- compromises security or integrity;
- reduces human control;
- violates an operational boundary;
- invalidates an assurance assumption;
- requires intervention, restriction, safe-state transition or suspension.

Near misses and significant anomalies should also be considered for incident-learning purposes.

---

## 6. Incident Categories

Incidents may include:

### Safety Incidents
Events that create actual or potential harm.

### AI Behaviour Incidents
Unexpected, incorrect, unstable or unsafe AI behaviour.

### Human-Control Incidents
Loss or degradation of meaningful human control.

### Autonomy Incidents
Unexpected autonomy, transition or autonomous action.

### Security Incidents
Compromise or suspected compromise affecting AI security or integrity.

### Data and Information Incidents
Material corruption, manipulation, loss or misleading information.

### Environment Incidents
Operating conditions materially outside the demonstrated envelope.

### Dependency Incidents
Failure or compromise of critical supporting dependencies.

### Configuration Incidents
Use of an unauthorised, unknown or materially altered configuration.

---

## 7. Incident Severity

Severity should reflect consequence and potential consequence.

A practical model is:

| Severity | Meaning |
|---|---|
| Critical | Immediate or potentially catastrophic consequence or loss of essential control |
| High | Significant operational, safety, security or assurance impact |
| Moderate | Material but contained impact |
| Low | Limited impact requiring controlled assessment |
| Observation | No material impact established, but learning value exists |

Severity classification should be reassessed as evidence develops.

---

## 8. Incident Lifecycle

The incident lifecycle is:

**Detect → Protect → Assess → Contain → Control → Preserve Evidence → Investigate → Correct → Verify → Decide → Learn**

Immediate protection and containment take priority over administrative completeness.

---

## 9. Detection

Incidents may be detected through:

- human observation;
- AI monitoring;
- system alerts;
- security monitoring;
- operational reports;
- automated safety mechanisms;
- assurance reviews;
- TEVV;
- audits;
- user reports;
- anomaly detection.

Detection mechanisms should be proportionate to consequence.

---

## 10. Immediate Protective Response

Where an incident creates immediate unacceptable risk, predefined protective actions should be available.

These may include:

- increased human supervision;
- restriction of function;
- reduction of autonomy;
- transfer to human control;
- intervention;
- override;
- pause;
- safe state;
- suspension.

---

## 11. Protective Response Hierarchy

The preferred response should be proportionate to the risk:

**Detect → Verify where practicable → Restrict → Reduce Autonomy → Human Control → Override/Pause → Safe State → Suspend**

The sequence may be shortened when immediate action is necessary.

---

## 12. Human Authority

Incident response shall have clearly defined authority for:

- declaring an incident;
- directing immediate protective action;
- restricting AI;
- reducing autonomy;
- intervening;
- overriding;
- entering safe state;
- suspending employment;
- restoring operation.

Emergency protective authority should not depend on the normal decision cycle where delay could increase harm.

---

## 13. Fail-Safe Principle

A fail-safe mechanism should move the capability toward a condition that reduces foreseeable harm when continued operation cannot be safely justified.

Fail-safe behaviour should be:

- defined;
- authorised;
- tested;
- observable;
- recoverable where appropriate.

---

## 14. Fail-Safe Is Not One Universal State

The appropriate safe response depends on:

- mission;
- consequence;
- autonomy;
- environment;
- system function;
- human availability;
- dependencies.

A safe state for one capability may not be safe for another.

---

## 15. Fail-Safe versus Fail-Operational

The governance decision between fail-safe and fail-operational behaviour should be explicitly assessed.

Continued operation may be appropriate where:

- risks remain controlled;
- authority permits continuation;
- degraded behaviour is understood;
- human control remains effective.

Transition to safe or suspended state should occur where continued operation cannot be justified.

---

## 16. Loss of Human Control

Loss or material degradation of human control shall be treated as a potentially critical assurance condition.

Response may include:

- immediate autonomy reduction;
- human takeover;
- safe-state transition;
- suspension.

---

## 17. Unexpected Autonomy

Unexpected autonomy may include:

- unplanned autonomous action;
- unauthorised autonomy state;
- unexpected autonomy transition;
- inability to reduce autonomy;
- inability to intervene.

Such events should trigger immediate assessment of operational authority and assurance.

---

## 18. Boundary Violation

A boundary violation may involve:

- mission;
- geographic;
- temporal;
- functional;
- autonomy;
- environmental;
- data;
- configuration;
- human-authority boundaries.

Material boundary violations should trigger protective response and incident investigation.

---

## 19. Security and Safety Interaction

Security events may create safety consequences.

Incident response should therefore consider both:

**Security Impact + Operational/Safety Impact**

A security incident affecting AI behaviour, integrity or human control should not be treated solely as an IT event.

---

## 20. Degraded and Disconnected Conditions

Incident response should account for:

- loss of communications;
- degraded sensors;
- degraded data;
- navigation limitations;
- computing limitations;
- power loss;
- unavailable human support.

The absence of connectivity shall not eliminate fail-safe or human-authority requirements.

---

## 21. Incident Containment

Containment should seek to prevent:

- continued harmful behaviour;
- propagation;
- unsafe autonomy;
- further compromise;
- evidence destruction;
- uncontrolled interaction with other systems.

Containment actions should themselves remain within applicable authority.

---

## 22. Evidence Preservation

Material incidents should preserve relevant evidence, including where applicable:

- system state;
- configuration;
- AI outputs;
- inputs;
- decisions;
- actions;
- autonomy state;
- human interventions;
- alerts;
- logs;
- environmental conditions;
- security indicators;
- dependency state.

Evidence preservation should begin as early as practicable.

---

## 23. Investigation

Incident investigation should establish, to the extent practicable:

- what happened;
- when it happened;
- what the AI contributed;
- what humans did;
- what authority applied;
- what conditions existed;
- why controls did or did not work;
- what consequences occurred;
- what remains uncertain.

---

## 24. Root Cause

Investigation should distinguish:

- immediate cause;
- contributing factors;
- systemic cause;
- latent control weakness.

Root cause should not automatically be attributed to the model alone.

---

## 25. Human Factors

Incident investigation should examine:

- workload;
- training;
- interface;
- automation bias;
- situational awareness;
- decision time;
- intervention usability;
- human-AI disagreement.

Human factors should be analysed without assuming individual error is the sole cause.

---

## 26. AI Behaviour Analysis

Where relevant, investigation should assess:

- input conditions;
- output;
- uncertainty;
- model behaviour;
- failure mode;
- data conditions;
- distribution shift;
- system integration;
- configuration.

The analysis should distinguish known facts from hypotheses.

---

## 27. Incident Impact on Assurance

Every material incident should be assessed for impact on:

- assurance claims;
- evidence;
- risks;
- controls;
- operating boundaries;
- human control;
- autonomy;
- environment;
- security;
- authorisation.

---

## 28. Incident Impact on Authorisation

A material incident may require:

- continued employment;
- restricted employment;
- enhanced monitoring;
- additional controls;
- revalidation;
- reauthorisation;
- suspension;
- withdrawal of authority.

Incident occurrence does not automatically determine the outcome; the evidence and risk assessment do.

---

## 29. Corrective Action

Corrective actions should address the identified cause or control weakness.

Actions may concern:

- model;
- software;
- data;
- configuration;
- controls;
- training;
- procedures;
- monitoring;
- human interface;
- authorisation conditions.

---

## 30. Verification

Corrective action should be verified for effectiveness.

Where material, verification may require:

- targeted testing;
- regression testing;
- TEVV;
- operational evaluation;
- security testing;
- human-factors assessment.

Administrative completion alone should not close a material incident.

---

## 31. Restoration

Restoration should require confirmation that:

- immediate risk is controlled;
- necessary corrective actions are complete;
- required evidence exists;
- human control is effective;
- configuration is known;
- authorisation remains valid or has been renewed.

---

## 32. Suspension

Suspension should be available where:

- risk is unacceptable;
- control is lost;
- assurance is insufficient;
- critical evidence is unavailable;
- authorisation conditions cannot be met;
- material security compromise exists.

---

## 33. Incident Escalation

Escalation thresholds should consider:

- consequence;
- potential consequence;
- loss of human control;
- autonomy;
- security;
- uncertainty;
- recurrence;
- systemic impact.

---

## 34. Incident Communication

Incident communication should clearly distinguish:

- confirmed facts;
- suspected causes;
- uncertainty;
- immediate actions;
- operational restrictions;
- decisions required.

Communication should follow applicable information-handling and security requirements.

---

## 35. Multi-AI Incidents

Where multiple AI systems interact, investigation should consider:

- individual system behaviour;
- interaction effects;
- shared dependencies;
- conflicting outputs;
- emergent behaviour;
- responsibility boundaries.

One system's assurance should not automatically be treated as assurance of the combined system.

---

## 36. Incident Records

Material incident records should include:

- incident ID;
- date/time;
- capability;
- mission;
- environment;
- configuration;
- autonomy;
- human authority;
- description;
- severity;
- immediate action;
- evidence;
- investigation;
- findings;
- corrective action;
- verification;
- assurance impact;
- authorisation decision;
- closure.

---

## 37. Incident Closure

An incident should be closed only when:

- immediate risk is controlled;
- required investigation is complete;
- material evidence is preserved;
- corrective actions are addressed;
- assurance impact is determined;
- required authority decisions are recorded;
- lessons are captured.

Open residual risks should remain visible after closure.

---

## 38. Incident Learning

Material incidents should feed into:

- risk management;
- AI lifecycle;
- security;
- TEVV;
- operational environment;
- operational authorisation;
- operational employment;
- continuous assurance;
- training;
- future design.

---

## 39. Testing of Fail-Safe

Fail-safe mechanisms should be tested under representative conditions, including where appropriate:

- normal operation;
- degraded operation;
- disconnected operation;
- adversarial conditions;
- communication loss;
- human unavailability;
- component failure.

Testing should establish that the intended protective behaviour is achievable.

---

## 40. Fail-Safe Limitations

Organisations should document circumstances in which:

- fail-safe may not operate;
- safe-state assumptions may not hold;
- human intervention may be delayed;
- recovery may be unavailable.

Known limitations should be incorporated into risk and authorisation decisions.

---

## 41. Governance Review

The incident governance model should be periodically reviewed for:

- incident trends;
- recurring failure modes;
- response effectiveness;
- fail-safe performance;
- escalation effectiveness;
- evidence quality;
- systemic weaknesses.

---

## 42. Governance Questions

The organisation should be able to answer:

1. What constitutes a Defence AI incident?
2. How are incidents detected?
3. Who can declare an incident?
4. Who can initiate emergency protective action?
5. What fail-safe states are defined?
6. How is loss of human control handled?
7. How are unexpected autonomy events handled?
8. How are boundary violations handled?
9. How are security and safety incidents connected?
10. How is evidence preserved?
11. How is root cause determined?
12. How is human contribution assessed?
13. When does an incident affect assurance?
14. When does it trigger revalidation or reauthorisation?
15. Who can suspend or restore employment?
16. How are corrective actions verified?
17. How are lessons transferred across capabilities?
18. How are fail-safe mechanisms tested?

---

## 43. Core Rule

> **When a Defence AI capability behaves unexpectedly, loses control, violates a material boundary, experiences a critical failure or enters a condition in which continued operation cannot be justified, the organisation shall prioritise protection of people, mission-critical assets and controlled operation; preserve evidence; investigate the event; assess its impact on assurance and authority; and take proportionate corrective, revalidation, reauthorisation or suspension action.**

---

## 44. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Incident Detection → Protective Response → Evidence Preservation → Investigation → Corrective Action → Verification → Assurance Update → Revalidation/Reauthorisation → Learning**
