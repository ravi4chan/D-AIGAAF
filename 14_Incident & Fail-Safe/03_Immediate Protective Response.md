# 03 — Immediate Protective Response

## 1. Purpose

This document defines the governance requirements for immediate protective action when a Defence AI capability presents actual or potential unacceptable risk during development, testing, deployment or operational employment.

The objective is to ensure that responsible personnel and systems can rapidly reduce exposure to harm while maintaining appropriate human authority, evidence preservation and subsequent governance review.

---

## 2. Core Principle

> **When a Defence AI capability presents actual or potential unacceptable risk, immediate protective action shall take priority over continued AI operation. Protective responses shall be proportionate to the risk and may include restriction, autonomy reduction, human control, intervention, override, safe-state transition or suspension.**

---

## 3. Protective Response Object

Protective response should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

The appropriate response depends on the operational context and consequence.

---

## 4. Protective Response Objectives

Immediate response should seek to:

- protect people;
- protect critical assets;
- prevent further harmful behaviour;
- restore human control;
- prevent escalation;
- contain security compromise;
- preserve evidence;
- establish a controlled operating state.

---

## 5. Protective Response Hierarchy

A practical hierarchy is:

**Detect → Assess → Restrict → Reduce Autonomy → Human Control → Override/Pause → Safe State → Suspend**

The hierarchy is not necessarily sequential.

Immediate circumstances may require skipping directly to a higher protective level.

---

## 6. Immediate Protective Conditions

Protective action may be required when:

- unsafe AI behaviour is detected;
- human control is materially degraded;
- unexpected autonomy occurs;
- a critical boundary is violated;
- safety controls fail;
- security integrity is compromised;
- environmental conditions leave the demonstrated envelope;
- critical dependencies fail;
- uncertainty becomes incompatible with safe operation.

---

## 7. Proportionality

The response should consider:

- consequence;
- likelihood or plausibility;
- duration;
- reversibility;
- autonomy;
- human-control availability;
- uncertainty;
- mission context.

The objective is to reduce unacceptable risk without introducing greater unmanaged risk through the response itself.

---

## 8. Immediate Human Authority

The organisation should predefine who may initiate:

- functional restriction;
- autonomy reduction;
- human takeover;
- intervention;
- override;
- pause;
- safe state;
- suspension.

Authority should be clear before employment begins.

---

## 9. Emergency Authority

Emergency protective authority should permit timely action where delay could increase harm.

Emergency authority should be:

- explicit;
- trained;
- tested;
- documented;
- reviewable.

---

## 10. Restriction

Restriction may limit:

- functions;
- missions;
- environments;
- data sources;
- autonomy;
- users;
- operating duration;
- dependencies.

Restriction may be temporary or continuing depending on assurance findings.

---

## 11. Functional Restriction

Where possible, the organisation should be able to disable or restrict the affected function without unnecessarily disabling unrelated safe functions.

Functional isolation should itself be assessed for safety and security consequences.

---

## 12. Autonomy Reduction

Where risk increases, autonomy may be reduced to a lower authorised state.

A typical response is:

**A4 → A3 → A2 → A1 → A0**

The appropriate transition depends on the capability and its authorised operating model.

---

## 13. Human Control

Where continued operation remains justified but AI autonomy or reliability is uncertain, responsibility may be returned to authorised human control.

Human control should be effective, timely and supported by sufficient situational awareness.

---

## 14. Intervention

Intervention may include:

- pause;
- stop;
- override;
- manual takeover;
- function restriction;
- transition to safe state.

Intervention mechanisms should be designed around realistic operational conditions.

---

## 15. Override

Override should be available where required by:

- safety;
- loss of control;
- boundary violation;
- unexpected autonomy;
- unacceptable behaviour.

Override authority should be clearly defined and protected against inappropriate use.

---

## 16. Pause

A pause may be appropriate where:

- immediate action is not required;
- additional information is needed;
- human review is necessary;
- continued AI activity creates uncertainty.

A pause should not be treated as equivalent to safe termination unless the capability has been assessed accordingly.

---

## 17. Safe-State Transition

A safe state should reduce foreseeable risk to an acceptable level.

The safe state should be:

- defined;
- authorised;
- observable;
- tested;
- appropriate to the capability.

---

## 18. Suspension

Suspension should be available where:

- risk is unacceptable;
- assurance is insufficient;
- human control is lost;
- critical safeguards fail;
- authorisation conditions cannot be satisfied;
- security integrity is uncertain.

---

## 19. Protective Response Under Time Pressure

Where decisions are time-critical:

- predefined response criteria should guide action;
- intervention mechanisms should be accessible;
- human authority should be clear;
- unnecessary decision steps should be avoided.

The response should not depend on perfect diagnosis.

---

## 20. Protective Response Under Uncertainty

Where uncertainty is material, personnel should consider whether:

- additional verification is possible;
- human review should increase;
- autonomy should decrease;
- the function should be restricted;
- safe state should be entered.

Uncertainty should not be interpreted automatically as evidence that continued operation is safe.

---

## 21. Protective Response to Unexpected Autonomy

Where autonomy exceeds or differs from its authorised state:

1. establish awareness where practicable;
2. reduce autonomy;
3. restore human control;
4. restrict affected functions;
5. enter safe state or suspend if necessary;
6. preserve evidence;
7. initiate incident assessment.

---

## 22. Protective Response to Boundary Violation

Material boundary violations should trigger proportionate action.

Relevant boundaries include:

- mission;
- geographic;
- temporal;
- functional;
- autonomy;
- environmental;
- data;
- configuration;
- human authority.

---

## 23. Protective Response to Security Events

Where security compromise may affect AI behaviour or control:

- protect human authority;
- restrict affected functions;
- isolate where appropriate;
- preserve evidence;
- involve appropriate security authorities;
- reassess operational assurance.

---

## 24. Protective Response in Degraded Conditions

During:

- communications degradation;
- disconnected operation;
- sensor degradation;
- navigation degradation;
- computing limitations;
- power limitations;

the capability should follow predefined degraded-operation rules.

Loss of connectivity should not automatically increase autonomy.

---

## 25. Protective Response in Adversarial Conditions

Where deliberate manipulation or deception is suspected, the organisation should consider:

- increased human verification;
- reduced trust in affected inputs;
- function restriction;
- autonomy reduction;
- isolation;
- safe state;
- suspension.

---

## 26. Multi-Factor Protective Response

When multiple degradation factors occur simultaneously, the response should consider their combined effect.

Examples include:

- degraded communications + uncertain data;
- environmental degradation + reduced human availability;
- security event + autonomy anomaly.

Combined conditions may require stronger protective action than any single factor.

---

## 27. Human Factors

Protective mechanisms should account for:

- workload;
- stress;
- time pressure;
- training;
- interface usability;
- automation bias;
- situational awareness.

A theoretically available intervention is not sufficient if personnel cannot use it effectively.

---

## 28. Protective Response Failure

The organisation should plan for failure of:

- automated safeguards;
- intervention mechanisms;
- communications;
- sensors;
- human availability;
- safe-state mechanisms.

Fallback mechanisms should be proportionate to consequence.

---

## 29. Fail-Safe Interaction

Immediate protective response should connect with the fail-safe architecture defined in this module.

Where continued operation cannot be justified:

**Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

---

## 30. Evidence Preservation

Protective action should preserve, where practicable:

- system state;
- configuration;
- inputs;
- outputs;
- autonomy state;
- human actions;
- environmental conditions;
- alerts;
- logs.

Evidence preservation should not delay necessary protective action.

---

## 31. Protective Response Recording

Material protective actions should record:

- trigger;
- time;
- authority;
- action;
- system state;
- human involvement;
- resulting state;
- reason where required.

---

## 32. Protective Response and Authorisation

Protective action does not itself create new operational authority.

Any continuation after a material protective event should remain within applicable authorisation or require appropriate governance action.

---

## 33. Protective Response and Assurance

A protective event should be assessed for impact on:

- assurance claims;
- evidence;
- risk;
- controls;
- human control;
- autonomy;
- environment;
- security.

Repeated protective interventions may indicate declining assurance.

---

## 34. Restoration After Protective Action

Restoration should require confirmation that:

- the initiating condition is understood sufficiently;
- immediate risk is controlled;
- required controls are functioning;
- human authority is restored;
- configuration is known;
- applicable assurance remains sufficient;
- authorisation permits continuation.

---

## 35. No Automatic Restoration

A system should not automatically return to unrestricted operation merely because the triggering condition disappears.

Restoration may require:

- human confirmation;
- additional testing;
- enhanced monitoring;
- revalidation;
- reauthorisation.

---

## 36. Escalation

Protective events should be escalated where they indicate:

- critical risk;
- loss of human control;
- unexpected autonomy;
- repeated intervention;
- safety-control failure;
- security compromise;
- invalid assurance;
- systemic weakness.

---

## 37. Training and Exercises

Personnel should periodically exercise:

- incident recognition;
- autonomy reduction;
- intervention;
- override;
- safe-state activation;
- degraded operation;
- communications loss;
- restoration;
- suspension.

Exercises should assess both technical and human effectiveness.

---

## 38. Protective Response Testing

Protective mechanisms should be tested under representative conditions.

Testing should establish:

- response availability;
- response time;
- correct state transition;
- human usability;
- failure behaviour;
- recovery behaviour.

---

## 39. Protective Response Metrics

Useful indicators may include:

- time to detect;
- time to intervene;
- time to reduce autonomy;
- time to safe state;
- intervention success rate;
- failed intervention rate;
- repeated protective events;
- restoration time.

Metrics should support safety and learning rather than become targets that encourage unsafe behaviour.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What conditions trigger protective action?
2. Who can initiate immediate protective action?
3. What restriction mechanisms exist?
4. How is autonomy reduced?
5. How is human control restored?
6. Who can override or pause the system?
7. What constitutes a safe state?
8. When is suspension required?
9. How are time-critical situations handled?
10. How is uncertainty handled?
11. How are security events handled?
12. How are degraded and disconnected conditions handled?
13. What happens if intervention fails?
14. How are protective actions recorded?
15. How are protective mechanisms tested?
16. What is required before restoration?
17. How do protective events affect assurance and authorisation?

---

## 41. Core Rule

> **Protective response shall be designed and authorised before operational employment and shall remain effective under realistic operational conditions. When risk becomes unacceptable or human control cannot be maintained, the organisation shall be capable of rapidly restricting AI activity, reducing autonomy, restoring human control, entering a safe state or suspending operation.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Detection → Protective Response → Human Control → Safe State/Suspension → Investigation → Corrective Action → Assurance Reassessment → Revalidation/Reauthorisation → Learning**
