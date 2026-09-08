# 05 — Degraded, Disconnected and Contingency Employment

## 1. Purpose

This document defines governance requirements for Defence AI employment when normal operating conditions, communications, information, infrastructure, personnel, dependencies or system functions are degraded or unavailable.

The objective is to ensure that disruption does not create uncontrolled AI behaviour, expanded autonomy or ambiguous human authority.

---

## 2. Core Principle

> **Continuity of operations does not mean continuity of unrestricted AI authority. When normal conditions degrade, Defence AI shall operate only within predefined continuity conditions or transition to an appropriately restricted, human-controlled, safe or suspended state.**

---

## 3. Degraded Employment

Degraded employment occurs when one or more conditions supporting normal operation are impaired but the capability may remain usable within defined limits.

Examples include degradation of:

- communications;
- sensors;
- navigation;
- data;
- computing;
- power;
- external services;
- personnel availability;
- environmental conditions.

---

## 4. Disconnected Employment

Disconnected employment occurs when the capability cannot maintain expected communication with one or more required external systems, authorities or services.

Disconnection may be temporary or prolonged.

The applicable authorisation should define what functions remain permitted during disconnection.

---

## 5. Contingency Employment

Contingency employment is controlled operation under conditions materially different from normal operation but addressed by predefined procedures or authority.

Contingency arrangements should be established before employment wherever practicable.

---

## 6. Degradation Categories

Organisations may classify degradation across:

- communications;
- information/data;
- sensors;
- navigation;
- computing;
- power;
- security;
- external dependencies;
- human availability;
- environment.

Multiple simultaneous degradations should be assessed as a combined condition where they can materially affect risk or control.

---

## 7. Communications Degradation

Where communications degrade, personnel should determine:

- what communication remains available;
- which authorities remain reachable;
- what information becomes delayed;
- what autonomy remains authorised;
- what intervention remains possible;
- what contingency state applies.

Communication loss should not automatically increase AI authority.

---

## 8. Complete Communication Loss

Where communication is unavailable:

- predefined continuity rules should apply;
- existing authority remains bounded;
- authorised autonomous functions may continue only within their approved conditions;
- new missions should not be initiated unless specifically authorised;
- mission scope should not expand automatically;
- recovery should require controlled verification.

---

## 9. Information Degradation

Information degradation may involve:

- missing data;
- stale data;
- incomplete data;
- inconsistent data;
- corrupted data;
- delayed data.

Personnel should reassess whether AI outputs remain sufficiently reliable for the authorised use.

---

## 10. Sensor Degradation

Sensor degradation may affect:

- detection;
- classification;
- tracking;
- situational awareness;
- environmental understanding.

The system should not silently maintain normal confidence when critical sensing capability has materially degraded.

---

## 11. Navigation Degradation

Navigation uncertainty may affect the ability to remain within:

- geographic boundaries;
- environmental boundaries;
- mission boundaries.

Where location confidence becomes insufficient for the authorised function, predefined restriction or safe-state arrangements should apply.

---

## 12. Computing Degradation

Computing limitations may affect:

- processing;
- model performance;
- latency;
- monitoring;
- safety mechanisms;
- communication.

The organisation should define minimum computing conditions for continued authorised employment.

---

## 13. Power Degradation

Where power availability affects system performance or safety, the organisation should define:

- minimum operating conditions;
- graceful degradation;
- safe shutdown;
- recovery;
- restart verification.

Loss of power should not create uncontrolled continuation following restoration.

---

## 14. Dependency Failure

Critical dependency failures may involve:

- communications;
- navigation;
- sensors;
- data;
- compute;
- external services;
- security infrastructure.

The response should be proportionate to dependency criticality and operational consequence.

---

## 15. Human Availability

Degraded personnel availability may occur through:

- absence;
- workload;
- injury;
- communication failure;
- shift transition;
- organisational disruption.

Where required human authority or supervision is unavailable, the capability should move to the predefined restricted, reduced-autonomy, human-controlled or safe state.

---

## 16. Human Control During Degradation

The organisation should confirm whether humans can still:

- understand AI output;
- maintain situational awareness;
- intervene;
- override where authorised;
- communicate decisions;
- suspend employment;
- escalate concerns.

If required human control cannot be maintained, continued employment should be reassessed.

---

## 17. Autonomy During Degradation

Degradation should not automatically result in increased autonomy.

Where risk or uncertainty increases, the preferred response may be:

**Normal Autonomy → Reduced Autonomy → Human Control → Safe State**

Any autonomous operation during degraded conditions must have been appropriately assessed and authorised.

---

## 18. Contingency Autonomy

Where autonomous operation during degraded conditions is permitted, the authorisation should define:

- trigger;
- autonomy level;
- duration;
- mission;
- environment;
- boundaries;
- prohibited actions;
- human authority;
- monitoring;
- termination conditions.

---

## 19. Situational Awareness

Degraded conditions may reduce situational awareness.

Personnel should identify:

- known information;
- missing information;
- stale information;
- uncertain information;
- conflicting information;
- AI-derived information.

Reduced information should generally result in increased caution rather than increased confidence.

---

## 20. AI Uncertainty

During degraded operations, AI uncertainty may increase.

The system should communicate material uncertainty where practicable.

Personnel should consider whether uncertainty remains compatible with the authorised use.

---

## 21. Environmental Degradation

Environmental conditions may include:

- weather;
- terrain;
- illumination;
- electromagnetic conditions;
- information environment;
- adversarial interference.

Where conditions approach or exceed authorised limits, the organisation should apply predefined responses.

---

## 22. Adversarial Degradation

Adversarial activity may deliberately create:

- communication disruption;
- sensor deception;
- data corruption;
- navigation interference;
- misleading information;
- system compromise.

The organisation should distinguish accidental degradation from suspected deliberate manipulation where practicable.

---

## 23. Security Degradation

A suspected compromise of:

- model integrity;
- software;
- configuration;
- data;
- interfaces;
- dependencies;

may require immediate restriction or suspension.

Operational continuity should not override mandatory security controls.

---

## 24. Multi-Factor Degradation

Several individually tolerable failures may combine to create unacceptable risk.

Examples include:

**Communication Loss + Sensor Degradation**

**Navigation Uncertainty + Environmental Change**

**Data Degradation + Human Workload**

**Dependency Failure + Reduced Monitoring**

Combined effects should be assessed where they materially affect human control or operational risk.

---

## 25. Contingency States

D-AIGAAF may use:

- **C0 — Normal**
- **C1 — Degraded**
- **C2 — Disconnected**
- **C3 — Restricted**
- **C4 — Reduced Autonomy**
- **C5 — Human Control**
- **C6 — Safe State**
- **C7 — Suspended**

These are working governance states.

---

## 26. State Transition

Transitions should be:

- predefined where practicable;
- observable;
- attributable;
- bounded;
- recorded where required.

Unexpected transitions should be treated as material operational events.

---

## 27. Protective Response

Where degradation materially increases risk:

**Detect → Assess → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

Immediate protective action may be taken where required by the applicable emergency authority.

---

## 28. Graceful Degradation

Where possible, systems should degrade predictably rather than fail unpredictably.

Graceful degradation may include:

- reduced functionality;
- reduced autonomy;
- increased human supervision;
- reduced operating scope;
- safe-state transition.

Graceful degradation should be verified through appropriate testing.

---

## 29. Fail-Safe

The capability should have a defined response to critical loss of:

- human control;
- communications;
- sensing;
- navigation;
- data integrity;
- system integrity.

Fail-safe behaviour should be proportionate to consequence.

---

## 30. Emergency Protective Action

Where delay could create unacceptable harm, pre-authorised personnel may take immediate protective action.

Actions may include:

- reducing autonomy;
- restricting functions;
- assuming human control;
- entering safe state;
- suspending employment.

Emergency action should remain bounded and recorded.

---

## 31. Mission Continuity

Where degraded employment continues, the organisation should confirm:

- mission remains authorised;
- risk remains acceptable;
- required human authority remains available;
- current autonomy remains permitted;
- boundaries remain enforceable;
- dependencies remain adequate.

Mission urgency should not by itself justify uncontrolled continuation.

---

## 32. Mission Termination

Employment should terminate or transition to a safe state when:

- required human control is lost;
- authorised boundaries cannot be maintained;
- critical dependencies fail;
- uncertainty becomes unacceptable;
- security integrity cannot be established;
- environmental conditions exceed authorised limits;
- fail-safe requirements cannot be satisfied.

---

## 33. Recovery

Recovery should establish:

- cause of degradation;
- current system state;
- configuration;
- environment;
- security;
- data;
- dependencies;
- human authority;
- autonomy.

Recovery should be controlled rather than assumed successful.

---

## 34. Restoration

Technical restoration does not automatically restore operational authority.

Before returning to normal employment, verify:

- authorisation;
- readiness;
- configuration;
- environment;
- autonomy;
- human control;
- security;
- dependencies;
- monitoring.

---

## 35. Restart and Reinitialisation

Following a significant interruption, restart should verify:

- system identity;
- configuration;
- model state where relevant;
- data state;
- security status;
- autonomy state;
- safety mechanisms;
- operational boundaries.

Unexpected system state should trigger appropriate restriction or investigation.

---

## 36. Handover During Degradation

If operational responsibility changes during degraded conditions, the receiving authority should be informed of:

- current state;
- authorisation;
- autonomy;
- restrictions;
- system condition;
- environment;
- dependencies;
- incidents;
- recovery status.

---

## 37. Offline Governance

Where normal digital governance systems are unavailable, predefined offline mechanisms should support:

- authority verification;
- operational boundaries;
- emergency procedures;
- decision recording;
- handover;
- later reconciliation.

Offline governance should preserve accountability rather than create informal authority.

---

## 38. Decision Recording

Where normal systems are unavailable, material decisions should be recorded through available authorised means.

Records should later be reconciled with formal systems where required.

---

## 39. Training and Exercises

Personnel should regularly exercise:

- communication loss;
- sensor degradation;
- navigation uncertainty;
- dependency failure;
- loss of human control;
- security events;
- autonomy reduction;
- safe-state transition;
- suspension;
- recovery;
- restoration.

Exercises should generate lessons for continuous assurance.

---

## 40. Monitoring

Even under degraded conditions, monitor where practicable:

- system state;
- autonomy;
- human control;
- uncertainty;
- environment;
- security;
- dependencies;
- boundaries.

Loss of monitoring capability may itself trigger restriction.

---

## 41. Governance Questions

The organisation should be able to answer:

1. What degraded condition exists?
2. What functions remain reliable?
3. What information is missing or stale?
4. What autonomy remains authorised?
5. Who holds human authority?
6. Can human intervention still occur?
7. Are operational boundaries enforceable?
8. Which dependencies have failed?
9. What contingency state applies?
10. What triggers reduced autonomy?
11. What triggers human control?
12. What triggers safe state or suspension?
13. How are decisions recorded offline?
14. What must be verified before restoration?

---

## 42. Golden Thread

Degraded and contingency employment remains connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Degradation → Response → Recovery → Monitoring → Learning → Revalidation/Reauthorisation**

---

## 43. Core Rule

> **When communications, information, sensors, navigation, computing, power, personnel, security, dependencies or environmental conditions degrade, Defence AI employment shall remain within predefined continuity conditions and authorised boundaries. Degradation or disconnection shall not create implied or expanded AI authority, and loss of normal communication shall not by itself justify increased autonomy. Where human control, situational awareness, boundary enforcement, system integrity or critical dependencies become materially inadequate, the capability shall move toward restriction, reduced autonomy, human control, safe state or suspension as appropriate. Recovery and technical restoration shall not automatically restore operational authority; the authorisation, configuration, environment, autonomy, human-control, security and readiness basis shall first be verified.**
