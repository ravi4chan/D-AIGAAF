# 04 — Fail-Safe and Safe-State Management

## 1. Purpose

This document defines governance requirements for the design, approval, testing, operation and recovery of fail-safe mechanisms and safe states for Defence AI capabilities.

The objective is to ensure that when continued AI operation cannot be safely justified, the capability can transition to a controlled condition that reduces foreseeable harm while preserving appropriate human authority.

---

## 2. Core Principle

> **Every Defence AI capability with material operational consequence shall have a defined and appropriately tested response for conditions in which continued operation is no longer justified. Fail-safe behaviour and safe states shall be proportionate to the capability, mission, environment, autonomy, human authority and foreseeable failure modes.**

---

## 3. Fail-Safe Governance Object

Fail-safe governance should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

The safe response should be derived from the actual operational context.

---

## 4. Fail-Safe Definition

For D-AIGAAF purposes, a fail-safe mechanism is a mechanism intended to move a capability toward a condition that reduces foreseeable unacceptable harm when normal or authorised operation cannot safely continue.

Fail-safe does not necessarily mean complete shutdown.

---

## 5. Safe-State Definition

A safe state is a defined system or operational condition in which:

- unacceptable risk is reduced;
- AI authority is appropriately restricted;
- human authority is preserved or restored where practicable;
- further harmful activity is prevented or limited;
- system status is observable;
- recovery or suspension can be managed.

---

## 6. Safe State Is Mission-Dependent

The appropriate safe state may differ according to:

- mission;
- function;
- consequence;
- autonomy;
- environment;
- human availability;
- communications;
- dependencies.

A universal safe-state definition should not be assumed.

---

## 7. Safe-State Categories

A capability may use one or more safe-state conditions such as:

- restricted function;
- reduced autonomy;
- human-controlled operation;
- paused operation;
- controlled termination;
- isolated operation;
- suspended operation.

The selected state should be explicitly authorised.

---

## 8. Fail-Safe versus Fail-Operational

The organisation should determine whether a function should:

### Fail Safe

Transition toward a condition that minimises foreseeable harm.

### Fail Operational

Continue operating in a degraded but controlled manner where continued operation remains justified.

The choice should be based on risk and mission consequence rather than convenience.

---

## 9. Fail-Safe Preconditions

Fail-safe behaviour should be defined before operational employment.

The design should establish:

- trigger conditions;
- response;
- authority;
- expected state;
- limitations;
- recovery;
- evidence requirements.

---

## 10. Fail-Safe Triggers

Potential triggers include:

- loss of human control;
- critical safety-control failure;
- unexpected autonomy;
- boundary violation;
- critical system error;
- material security compromise;
- unreliable inputs;
- unacceptable uncertainty;
- environmental excursion;
- critical dependency failure.

---

## 11. Trigger Thresholds

Triggers should be:

- defined;
- measurable where practicable;
- tested;
- observable;
- proportionate to consequence.

Thresholds should avoid excessive false triggering while preserving adequate protection.

---

## 12. Automatic Protective Mechanisms

Automated mechanisms may initiate protective responses where authorised.

Examples include:

- autonomy reduction;
- function restriction;
- pause;
- safe-state transition;
- controlled shutdown.

Automated protective mechanisms should not silently create new operational authority.

---

## 13. Human-Initiated Fail-Safe

Authorised humans should be able to initiate appropriate protective actions where required.

The mechanism should be:

- accessible;
- understandable;
- timely;
- protected against inappropriate activation;
- tested under realistic conditions.

---

## 14. Human Authority During Fail-Safe

The framework should define:

- who may activate;
- who may confirm;
- who may override;
- who may restore;
- who may suspend permanently.

Emergency authority should be clear before employment.

---

## 15. Intervention Hierarchy

Where practicable, protective responses may progress through:

**Restrict → Reduce Autonomy → Human Control → Pause/Override → Safe State → Suspend**

The appropriate response may skip levels where immediate risk requires it.

---

## 16. Fail-Safe Under Uncertainty

Where system state or risk cannot be established reliably, the organisation should consider whether uncertainty itself requires:

- increased human control;
- reduced autonomy;
- restriction;
- safe state;
- suspension.

Unknown conditions should not automatically be treated as benign.

---

## 17. Loss of Human Control

Fail-safe mechanisms should address situations where:

- human supervision is unavailable;
- intervention is ineffective;
- override fails;
- communication with the responsible human is lost;
- system behaviour cannot be sufficiently understood.

---

## 18. Unexpected Autonomy

Safe-state governance should address:

- unexpected autonomy;
- unauthorised autonomy;
- autonomy escalation;
- failure to transition to a lower authorised state;
- inability to terminate autonomous activity.

---

## 19. Boundary Protection

Fail-safe mechanisms should support protection against violations of:

- mission;
- geographic;
- temporal;
- functional;
- autonomy;
- environmental;
- data;
- configuration;
- human-authority boundaries.

---

## 20. Degraded and Disconnected Conditions

Fail-safe behaviour should remain appropriately defined when:

- communications are degraded;
- connectivity is lost;
- sensors are degraded;
- data is incomplete;
- navigation is unavailable;
- computing resources are constrained;
- external dependencies fail.

Fail-safe mechanisms should not rely on continuous connectivity unless that dependency is explicitly authorised and assured.

---

## 21. Adversarial Conditions

Where manipulation or hostile interference is suspected, fail-safe mechanisms should consider:

- trust degradation;
- corrupted inputs;
- compromised dependencies;
- abnormal system behaviour;
- loss of integrity.

Protective response should remain available even when the environment is adversarial.

---

## 22. Dependency Failure

Critical dependencies should have defined failure responses.

These may include:

- degraded operation;
- reduced autonomy;
- human control;
- isolation;
- safe state;
- suspension.

---

## 23. Fail-Safe and Security

Fail-safe mechanisms should themselves be protected against:

- unauthorised activation;
- unauthorised suppression;
- tampering;
- configuration manipulation;
- compromise.

A fail-safe mechanism that can be silently disabled cannot be treated as a reliable control.

---

## 24. Fail-Safe and Multi-AI Systems

For systems involving multiple AI components, safe-state design should consider:

- individual component failure;
- interaction failure;
- shared dependency failure;
- conflicting actions;
- inability of one system to control another.

The combined system should have a coherent protective response.

---

## 25. Safe-State Observability

Personnel should be able to determine, where practicable:

- whether safe state has been entered;
- why it was entered;
- what functions remain active;
- what authority remains;
- what recovery options exist.

Ambiguous system state may create additional risk.

---

## 26. Safe-State Integrity

The organisation should ensure that a safe state cannot inadvertently:

- increase autonomy;
- bypass human authority;
- create uncontrolled action;
- lose critical evidence;
- introduce a new unacceptable hazard.

Safe-state behaviour should be tested as a system state, not merely as an interface command.

---

## 27. Safe-State Testing

Testing should establish:

- trigger reliability;
- response correctness;
- transition time;
- human usability;
- failure behaviour;
- recovery behaviour;
- evidence generation.

Testing should include representative operational conditions.

---

## 28. Fail-Safe Testing Scenarios

Where appropriate, testing should include:

- normal conditions;
- degraded conditions;
- disconnected conditions;
- sensor failure;
- communication failure;
- power or computing degradation;
- unexpected autonomy;
- boundary violation;
- security compromise;
- human unavailability.

---

## 29. Fail-Safe Failure

Organisations should define what happens if the primary fail-safe mechanism fails.

Possible responses include:

- secondary protective mechanism;
- reduced functionality;
- manual control;
- isolation;
- suspension.

Critical capabilities should not rely on a single untested protective mechanism.

---

## 30. Recovery

Recovery from safe state should require defined conditions.

These may include:

- initiating condition resolved;
- system integrity established;
- configuration verified;
- human authority restored;
- necessary testing completed;
- assurance sufficient;
- authorisation valid.

---

## 31. No Automatic Recovery

Automatic return to unrestricted operation should not occur solely because a fail-safe trigger disappears where continued operation could remain unsafe or unauthorised.

Human or governance confirmation may be required.

---

## 32. Safe-State Exit

Safe-state exit criteria should define:

- who may authorise exit;
- required evidence;
- system checks;
- human-control confirmation;
- monitoring requirements;
- applicable restrictions.

---

## 33. Suspension as a Safe-State Outcome

Where risk cannot be adequately controlled, suspension should be available.

Suspension may remain necessary until:

- cause is understood sufficiently;
- corrective action is completed;
- assurance is restored;
- revalidation is completed;
- reauthorisation is obtained where required.

---

## 34. Fail-Safe and Assurance

Fail-safe performance should contribute to assurance evidence concerning:

- safety;
- human control;
- autonomy;
- resilience;
- security;
- operational readiness.

Failure of a material fail-safe control should be treated as an assurance concern.

---

## 35. Fail-Safe and Authorisation

Operational authorisation should specify, where appropriate:

- required fail-safe mechanisms;
- safe states;
- activation authority;
- recovery authority;
- restrictions;
- monitoring requirements.

---

## 36. Fail-Safe and Incident Management

Failure or unexpected activation of a material fail-safe mechanism should be assessed as a potential incident.

Records should capture:

- trigger;
- system response;
- human response;
- resulting state;
- outcome.

---

## 37. Fail-Safe and Continuous Assurance

Continuous assurance should monitor:

- fail-safe availability;
- test currency;
- intervention success;
- safe-state transitions;
- failed transitions;
- unexpected activations;
- recovery outcomes.

---

## 38. Maintenance and Configuration

Fail-safe mechanisms should remain part of controlled configuration management.

Changes should be assessed for impact on:

- trigger logic;
- response;
- safe state;
- intervention;
- recovery;
- assurance evidence.

---

## 39. Training

Relevant personnel should be trained to:

- recognise fail-safe conditions;
- understand safe states;
- initiate protective action;
- interpret system status;
- conduct human takeover;
- manage recovery;
- suspend operation.

---

## 40. Exercises

Exercises should validate:

- technical response;
- human response;
- authority;
- communication;
- degraded operation;
- recovery.

Exercise findings should feed into continuous improvement.

---

## 41. Fail-Safe Records

Material fail-safe records should include:

- mechanism;
- trigger;
- intended response;
- authority;
- test evidence;
- limitations;
- configuration;
- activation events;
- failures;
- recovery.

---

## 42. Governance Review

Fail-safe governance should be periodically reviewed for:

- effectiveness;
- false triggers;
- missed triggers;
- intervention failures;
- recovery failures;
- changing risks;
- changing autonomy;
- changing environments.

---

## 43. Governance Questions

The organisation should be able to answer:

1. What is the defined safe state?
2. Is the safe state mission-dependent?
3. What conditions trigger fail-safe behaviour?
4. Which responses are automatic?
5. Which responses require human action?
6. Who can activate fail-safe?
7. Who can restore operation?
8. What happens if fail-safe fails?
9. How does fail-safe operate when disconnected?
10. How is unexpected autonomy handled?
11. How are boundary violations handled?
12. How is fail-safe protected against tampering?
13. How are safe states tested?
14. What evidence demonstrates effectiveness?
15. When is automatic recovery prohibited?
16. How does fail-safe performance affect assurance?
17. When does fail-safe failure require revalidation or reauthorisation?

---

## 44. Core Rule

> **A Defence AI capability shall not rely on the assumption that normal operation will always continue. Its fail-safe and safe-state mechanisms shall be explicitly defined, authorised, tested and maintained so that material failures, loss of control, unexpected autonomy, security compromise or unacceptable uncertainty can result in a controlled reduction of risk. Restoration shall require sufficient evidence and authority; disappearance of the triggering condition shall not automatically restore unrestricted operation.**

---

## 45. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Incident Detection → Protective Response → Fail-Safe → Safe State → Investigation → Corrective Action → Verification → Assurance Update → Revalidation/Reauthorisation → Learning**
