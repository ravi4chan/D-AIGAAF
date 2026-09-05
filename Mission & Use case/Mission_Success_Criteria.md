# Mission Success Criteria

## 1. Purpose

Mission Success Criteria define what constitutes acceptable operational performance for an AI-enabled capability within a specific mission and use case.

They translate the mission objective into observable outcomes that can be evaluated through testing, trials, operational evidence and continuous assurance.

Success should not be defined solely by model accuracy or technical performance.

---

## 2. Core Principle

The governing sequence is:

**Mission Objective → Success Criteria → Requirements → Testing → Evidence → Assurance**

A system may meet its technical specifications and still fail to achieve the intended operational outcome.

Mission success must therefore be evaluated at the level at which the capability creates operational value.

---

## 3. What Constitutes Mission Success

Mission success should describe whether the capability:

- performs its intended function;
- supports the intended operational decision or activity;
- performs within required time limits;
- remains sufficiently reliable;
- operates within its authorised environment;
- preserves required human authority;
- behaves acceptably under degraded conditions;
- communicates meaningful uncertainty;
- remains secure and controllable;
- produces an acceptable operational outcome.

---

## 4. Mission-Level vs Model-Level Performance

Model-level metrics may include:

- accuracy;
- precision;
- recall;
- latency;
- false-positive rate;
- false-negative rate;
- availability.

These metrics are useful but insufficient on their own.

Mission-level success may also depend on:

- decision quality;
- timeliness;
- operator workload;
- human understanding;
- resilience;
- operational effectiveness;
- consequences of errors;
- recovery from failure.

The framework therefore distinguishes:

**Technical Performance ≠ Mission Effectiveness**

---

## 5. Success Criterion Categories

Success criteria should consider, where applicable:

1. Mission effectiveness
2. Technical performance
3. Reliability
4. Robustness
5. Timeliness
6. Human-AI interaction
7. Human control
8. Security
9. Information integrity
10. Autonomy
11. Resilience
12. Safety
13. Availability
14. Recovery
15. Operational suitability

---

## 6. Mission Effectiveness

Mission effectiveness addresses whether the AI capability materially contributes to the intended mission objective.

Examples include:

- improved detection;
- improved prioritisation;
- improved planning;
- reduced decision time;
- improved resource allocation;
- improved situational awareness;
- reduced workload;
- improved mission outcomes.

The criterion should specify what improvement is expected and how it will be observed.

---

## 7. Accuracy and Error

Where accuracy is relevant, success criteria should define acceptable error characteristics.

Consider:

- false positives;
- false negatives;
- missed detections;
- incorrect classifications;
- incorrect recommendations;
- systematic errors;
- rare but high-consequence errors.

Average accuracy may conceal operationally unacceptable failure modes.

For high-consequence use cases, the consequences of particular error types should be considered separately.

---

## 8. Timeliness

An output may be technically correct but operationally useless if it arrives too late.

Success criteria should therefore consider:

- processing latency;
- decision latency;
- response time;
- update frequency;
- time available for human review;
- time between detection and required action.

Timeliness thresholds should be tied to the actual mission decision window.

---

## 9. Reliability

Reliability criteria should define expected performance over time.

Consider:

- failure frequency;
- uptime;
- repeatability;
- recovery;
- component failures;
- software faults;
- hardware faults;
- dependency failures.

Reliability expectations should reflect mission consequence.

---

## 10. Robustness

Robustness criteria should consider performance when conditions vary from the ideal.

Relevant variations may include:

- environmental conditions;
- sensor degradation;
- data quality;
- unfamiliar inputs;
- communications degradation;
- computing constraints;
- adversarial manipulation.

A capability should not be considered robust merely because it performs well under controlled conditions.

---

## 11. Human-AI Interaction

Success criteria should assess whether humans can use the AI effectively.

Consider:

- clarity of outputs;
- understandability;
- workload;
- alert burden;
- ability to identify uncertainty;
- ability to challenge recommendations;
- ability to override;
- decision time;
- operator error.

A technically strong system may still fail operationally if it degrades human decision-making.

---

## 12. Human Control

Where human authority is required, success criteria should establish whether meaningful control exists in practice.

This may include:

- ability to review;
- ability to reject;
- ability to override;
- ability to suspend;
- ability to terminate;
- time available for intervention;
- reliability of intervention mechanisms.

Human control should be tested under realistic operational conditions, including degraded communications and high workload where relevant.

---

## 13. Uncertainty Communication

Where uncertainty is operationally relevant, success criteria should include whether the system:

- identifies uncertainty;
- communicates relevant limitations;
- identifies missing information;
- distinguishes high-confidence from low-confidence outputs;
- avoids presenting uncertain conclusions as established facts.

A useful success criterion is not simply whether the AI is correct, but whether it appropriately signals when it may be wrong.

---

## 14. Security

Security-related success criteria may include:

- resistance to known attack methods;
- integrity of models and data;
- authentication;
- access control;
- secure updates;
- logging;
- detection of compromise;
- containment;
- recovery.

Security criteria should be linked to the consequences of successful compromise.

---

## 15. Information Integrity

Success criteria should consider whether the system remains dependable when information is:

- incomplete;
- stale;
- conflicting;
- degraded;
- manipulated;
- unavailable.

The system should behave appropriately when information quality falls below defined thresholds.

---

## 16. Autonomy

For autonomous or semi-autonomous systems, success criteria should address:

- adherence to authorised behaviour;
- compliance with boundaries;
- predictable behaviour;
- response to human intervention;
- behaviour following communications loss;
- behaviour under abnormal conditions;
- prevention of unauthorised actions.

Higher autonomy should generally require stronger evidence of predictable and bounded behaviour.

---

## 17. Safety

Safety criteria should identify unacceptable outcomes.

Depending on the use case, this may include:

- injury;
- loss of life;
- uncontrolled physical action;
- unsafe system state;
- damage to critical infrastructure;
- unsafe interaction with other systems.

Safety thresholds should be established before operational testing where practical.

---

## 18. Resilience

Resilience criteria should assess whether the capability can continue safely when supporting conditions degrade.

Consider:

- communications loss;
- sensor loss;
- power disruption;
- system faults;
- dependency failure;
- cyber attack;
- degraded data.

The desired outcome may be continued operation, reduced functionality, transfer to human control, controlled degradation or safe shutdown.

---

## 19. Availability and Continuity

Success criteria should define the availability required for the mission.

Consider:

- required availability;
- acceptable downtime;
- recovery time;
- fallback capability;
- manual alternatives;
- degraded modes.

A capability should not become an unrecognised single point of failure.

---

## 20. Recovery

Success criteria should include recovery where failure is foreseeable.

Recovery may include:

- restoration of normal function;
- rollback;
- transfer to a safe state;
- transfer to human control;
- system isolation;
- replacement;
- manual fallback.

Recovery performance should be tested where the consequences justify it.

---

## 21. Adversarial Performance

Where adversarial conditions are foreseeable, success criteria should include behaviour under deliberate attempts to degrade or manipulate the system.

Assessment may consider:

- manipulated inputs;
- deceptive information;
- adversarial examples;
- malicious instructions;
- compromised dependencies;
- cyber attacks;
- deliberate disruption.

The objective is not to claim immunity from attack.

The objective is to demonstrate acceptable resilience and controlled behaviour.

---

## 22. Operational Boundaries

Success criteria should establish whether the system remains within its authorised boundaries.

These may include:

- mission;
- geography;
- environment;
- autonomy;
- data;
- users;
- system interfaces;
- time;
- permitted actions.

Operating outside a defined boundary should be detectable and should produce the required response.

---

## 23. Failure Criteria

Mission evaluation should define conditions that constitute unacceptable failure.

Examples include:

- catastrophic error;
- repeated high-consequence errors;
- loss of human control;
- unauthorised action;
- unsafe degradation;
- inability to communicate critical uncertainty;
- compromise of system integrity;
- failure of required fail-safe mechanisms.

A system should not be declared successful merely because average performance is acceptable when a critical failure mode remains uncontrolled.

---

## 24. Thresholds and Tolerances

Each important criterion should define, where practical:

- target;
- minimum acceptable threshold;
- tolerance;
- measurement method;
- evidence source;
- consequences of failure.

Not every criterion requires a numerical threshold.

Some requirements may be binary or conditional.

---

## 25. Measurement Conditions

Success criteria should specify the conditions under which performance is measured.

These may include:

- representative environment;
- representative data;
- realistic workload;
- realistic human operators;
- degraded conditions;
- adversarial conditions;
- relevant system configuration.

Performance measured under unrealistic conditions should not automatically support operational claims.

---

## 26. Evidence

Each success criterion should map to evidence.

Possible evidence includes:

- test results;
- verification records;
- validation results;
- evaluation reports;
- operational trials;
- red-team results;
- human factors studies;
- incident data;
- operational monitoring.

The evidence should demonstrate the criterion rather than merely describe it.

---

## 27. Success Criteria and Assurance

Mission Success Criteria become assurance claims when supported by appropriate evidence.

The relationship is:

**Success Criterion → Requirement → Test/Evaluation → Evidence → Assurance Claim**

Unsupported success claims should not be treated as established assurance.

---

## 28. Success Criteria and Authorisation

Operational authorisation should consider whether required mission success criteria have been demonstrated.

Where criteria remain unmet, the authorisation decision should consider:

- restriction;
- additional controls;
- reduced autonomy;
- additional testing;
- limited deployment;
- suspension;
- non-authorisation.

A capability should not receive unrestricted authority solely because some success criteria are met.

---

## 29. Success Criteria and Continuous Assurance

Mission success should continue to be monitored after deployment.

Monitoring may identify:

- performance degradation;
- new failure modes;
- changing environmental conditions;
- data drift;
- increased error rates;
- human factors problems;
- new adversarial threats.

Material degradation should trigger the appropriate review or reauthorisation process.

---

## 30. Success Criteria Change

Success criteria may need revision when:

- mission objectives change;
- use case changes;
- operational environment changes;
- autonomy increases;
- consequence changes;
- new threats emerge;
- system behaviour changes;
- policy changes.

Changes to success criteria should remain traceable through the Golden Thread.

---

## 31. Mission Success Record

A consequential use case should maintain a Mission Success Record containing, as applicable:

- mission objective;
- success criterion;
- criterion category;
- target;
- minimum threshold;
- tolerance;
- measurement method;
- test conditions;
- evidence;
- result;
- limitations;
- responsible owner;
- review date;
- change history.

---

## 32. Example Success-Criteria Structure

| Criterion | Target | Minimum Acceptable | Conditions | Evidence | Status |
|---|---|---|---|---|---|
| Mission effectiveness | Defined outcome | Defined threshold | Representative mission | Evaluation |  |
| Accuracy | Defined performance | Defined threshold | Representative data | Test |  |
| Timeliness | Defined response | Maximum latency | Mission conditions | Test |  |
| Human control | Effective intervention | Defined response | Realistic workload | Evaluation |  |
| Robustness | Stable performance | Defined degradation limit | Degraded conditions | Test |  |
| Security | Defined resilience | No critical failure | Adversarial conditions | Red team |  |
| Fail-safe | Safe transition | Defined response | Failure scenario | Test |  |

The values should be determined for the specific use case.

---

## 33. Minimum Mission Success Requirements

Before operational authorisation, a consequential AI capability should have:

1. Defined mission-level success criteria.
2. Distinguished technical performance from mission effectiveness.
3. Defined important error conditions.
4. Defined relevant timeliness requirements.
5. Assessed reliability and robustness.
6. Assessed human-AI interaction.
7. Demonstrated meaningful human control where required.
8. Defined uncertainty communication requirements.
9. Assessed security and information integrity.
10. Defined autonomy-related success criteria.
11. Defined safety and resilience criteria.
12. Defined operational boundaries.
13. Defined unacceptable failure conditions.
14. Identified evidence required to demonstrate success.
15. Established monitoring and review triggers.

---

## 34. Relationship With D-AIGAAF

This module connects directly with:

- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

The module strengthens the Golden Thread:

**Mission → Use Case → Success Criteria → Requirements → Controls → Testing → Evidence → Assurance → Authority**

---

## 35. Summary

Mission Success Criteria define what "good enough" means for the actual mission.

They ensure that AI capabilities are evaluated not only on whether the model works, but on whether the overall capability:

- achieves the intended mission outcome;
- remains reliable and robust;
- preserves meaningful human authority;
- communicates uncertainty;
- remains secure;
- behaves safely under failure;
- performs within its authorised operational envelope.

The central principle is:

> **Operational success must be demonstrated at the level of the mission, not inferred solely from model performance.**
