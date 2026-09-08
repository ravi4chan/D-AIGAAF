# 04 — Operational Autonomy and Boundary Management

## 1. Purpose

This document defines how autonomy and operational boundaries are managed while a Defence AI capability is actively employed.

The objective is to ensure that the capability performs only those functions, actions and transitions that are permitted by its operational authorisation and current conditions.

---

## 2. Core Principle

> **Operational autonomy shall remain explicitly bounded, continuously observable and consistent with the authorised mission, environment, configuration, human authority and conditions. Technical capability shall never be interpreted as operational permission.**

---

## 3. Autonomy Model

D-AIGAAF uses the following working autonomy levels:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are working governance constructs and should be mapped to applicable national, defence, legal, doctrinal and international terminology.

---

## 4. Autonomy versus Authority

The framework distinguishes:

**Capability** — what the system can technically perform.

**Autonomy** — how independently the system performs a function.

**Authority** — what the organisation has permitted the system to perform.

A system may technically support a higher autonomy level without being authorised for that level.

---

## 5. Authorised Autonomy

For each employment, the organisation should establish:

- authorised autonomy;
- permitted functions;
- permitted actions;
- human supervision;
- intervention requirements;
- transition conditions;
- prohibited autonomy;
- monitoring;
- suspension triggers.

The active autonomy state should remain visible to relevant personnel.

---

## 6. Autonomy Boundaries

Autonomy should be bounded across:

- mission;
- function;
- environment;
- geography;
- time;
- configuration;
- data;
- dependencies;
- consequence;
- human authority.

A capability should not be allowed to expand these boundaries through its own behaviour.

---

## 7. Functional Boundaries

The organisation should distinguish between:

**Observe → Analyse → Recommend → Support Decision → Execute Authorised Action**

Movement from one functional category to another should require the authority established by the applicable authorisation.

---

## 8. Mission Boundaries

Autonomy should remain limited to the authorised mission.

A system should not automatically:

- begin a new mission;
- change mission objectives;
- expand mission scope;
- pursue an unrelated objective;
- continue after mission completion.

Mission changes should follow applicable governance.

---

## 9. Environmental Boundaries

Autonomy should operate only within the authorised environmental envelope.

Relevant conditions may include:

- terrain;
- weather;
- illumination;
- sensors;
- communications;
- navigation;
- electromagnetic conditions;
- information environment;
- adversarial conditions.

Material movement outside the demonstrated or authorised envelope should trigger the applicable response.

---

## 10. Geographic Boundaries

Where geographic restrictions apply, the system should operate only within defined limits.

Geographic boundaries should be:

- clearly specified;
- understood by responsible personnel;
- monitored where practicable;
- technically enforced where appropriate.

A system's ability to operate beyond a boundary does not create permission to do so.

---

## 11. Temporal Boundaries

Autonomy may be limited by:

- mission duration;
- authorisation validity;
- operating periods;
- specific phases of employment;
- temporary conditions.

Expiration of an authorisation or operating period should not be silently ignored.

---

## 12. Human-Authority Boundaries

The organisation should define which decisions remain with humans.

Where human authority is required, the AI should not:

- bypass the decision-maker;
- substitute its own authority;
- reinterpret human refusal as permission;
- create additional authority through automation.

---

## 13. Configuration Boundaries

Autonomy should be tied to an approved configuration.

Relevant configuration elements may include:

- model;
- model state;
- software;
- hardware;
- sensors;
- interfaces;
- safety mechanisms;
- security controls;
- data configuration.

Material changes should trigger the applicable change process.

---

## 14. Data Boundaries

Autonomy may depend on specific data sources.

The organisation should identify:

- required data;
- permitted data;
- data quality expectations;
- data integrity requirements;
- unavailable or degraded data conditions.

Loss or corruption of critical data should trigger appropriate reassessment.

---

## 15. Dependency Boundaries

Autonomy may depend on:

- communications;
- navigation;
- sensors;
- compute;
- power;
- external services;
- software;
- security infrastructure.

Critical dependency failure should not automatically increase autonomy.

---

## 16. Consequence Boundaries

Autonomy should be limited according to the consequences it may produce.

Higher-consequence actions should generally require:

- stronger evidence;
- stronger human authority;
- tighter boundaries;
- greater monitoring;
- stronger intervention capability.

---

## 17. Autonomy Transitions

Autonomy transitions should have:

- defined trigger;
- defined authority;
- defined conditions;
- defined limits;
- defined monitoring;
- defined failure response.

Examples include:

**A2 → A3**

**A3 → A4**

**A4 → A3**

**A4 → Safe State**

Transitions should not occur merely because the system is technically capable of making them.

---

## 18. Unexpected Autonomy Transition

An unexpected increase or change in autonomy should be treated as a material operational event.

Potential causes include:

- software error;
- configuration error;
- communications loss;
- dependency failure;
- unexpected system behaviour;
- human error;
- security compromise.

The organisation should apply the appropriate protective response.

---

## 19. Autonomy Reduction

Where risk increases, autonomy may be reduced:

**A4 → A3**

**A3 → A2**

**A2 → A1**

The objective is to restore an appropriate level of human control without necessarily terminating the entire capability.

---

## 20. Human Control

Human control should remain effective for the authorised autonomy level.

The organisation should assess:

- availability of responsible personnel;
- situational awareness;
- workload;
- communication;
- intervention;
- override;
- authority;
- competence.

A nominal human presence is insufficient if the human cannot realistically exercise control.

---

## 21. Intervention

Personnel should have defined mechanisms to:

- pause;
- restrict;
- reduce autonomy;
- assume human control;
- override where authorised;
- enter a safe state;
- suspend employment.

Intervention requirements should reflect consequence and autonomy.

---

## 22. Override

Where an override is provided, the organisation should define:

- who may use it;
- when it may be used;
- what it changes;
- what safeguards remain;
- what happens afterwards;
- what records are required.

Override capability should be tested under appropriate conditions.

---

## 23. Safe State

A safe state should represent a predefined condition intended to reduce unacceptable risk.

The organisation should define:

- entry conditions;
- system behaviour;
- authority;
- safeguards;
- recovery;
- restoration conditions.

The safe state should not be assumed to be identical for every AI capability.

---

## 24. Boundary Monitoring

Operational monitoring should identify:

- proximity to boundaries;
- boundary crossings;
- unusual autonomy;
- environmental changes;
- configuration changes;
- data degradation;
- dependency failures.

Boundary monitoring should provide sufficient warning where practicable.

---

## 25. Boundary Violation

A boundary violation may involve:

- unauthorised function;
- unauthorised mission;
- unauthorised autonomy;
- unauthorised environment;
- unauthorised geography;
- unauthorised configuration;
- unauthorised user;
- prohibited action.

Material violations should trigger investigation and appropriate protective action.

---

## 26. Boundary Uncertainty

Where personnel cannot determine whether the capability remains within an authorised boundary, the uncertainty should be treated as a governance concern.

The response may include:

**Verify → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

Uncertainty should not be interpreted as permission to continue unrestricted activity.

---

## 27. Degraded Operations

During degraded conditions, the organisation should reassess:

- current autonomy;
- available human control;
- environmental suitability;
- information quality;
- dependency status;
- boundary enforcement.

Degradation should not silently expand the authorised operating envelope.

---

## 28. Disconnected Operations

Where communications are unavailable:

- predefined autonomy rules should apply;
- human authority should remain bounded;
- permitted autonomous behaviour should remain within the authorisation;
- unplanned mission expansion should not occur;
- restoration should require controlled verification.

---

## 29. Adversarial Conditions

Adversarial activity may attempt to cause:

- unexpected autonomy;
- boundary crossing;
- misleading inputs;
- incorrect decisions;
- unsafe actions;
- loss of human control.

Monitoring and protective controls should address these risks proportionately.

---

## 30. Multi-AI Autonomy

Where multiple AI systems interact, autonomy should be assessed collectively where their interaction can materially affect outcomes.

Consider:

- automated recommendation chains;
- shared data;
- shared dependencies;
- cascading actions;
- combined autonomy;
- emergent behaviour.

Individually authorised systems should not acquire additional authority through interaction.

---

## 31. Human-AI Interaction

Personnel should understand the current autonomy state and what it means operationally.

Interfaces should make relevant information visible, including where appropriate:

- autonomy state;
- human authority;
- active restrictions;
- transition status;
- warnings;
- intervention options.

---

## 32. Autonomy and Uncertainty

Increasing uncertainty should generally result in increased human involvement where required by the authorisation.

Possible response:

**Normal → Increased Review → Reduced Autonomy → Human Control → Safe State**

The appropriate threshold should be defined before employment.

---

## 33. Autonomy and Environment

When environmental conditions approach or exceed defined boundaries, the organisation should determine whether to:

- continue;
- increase monitoring;
- restrict;
- reduce autonomy;
- move to human control;
- enter contingency;
- enter safe state;
- suspend.

---

## 34. Autonomy and Security

A material security concern may require:

- autonomy reduction;
- human control;
- restriction;
- safe state;
- suspension.

Security status should therefore remain connected to operational autonomy management.

---

## 35. Autonomy and Configuration Changes

Material changes to model or system behaviour should not automatically inherit the previous autonomy authority.

Changes affecting:

- model weights;
- architecture;
- training;
- fine-tuning;
- software;
- autonomy logic;
- safety mechanisms;

should undergo appropriate assessment.

---

## 36. Autonomy and Mission Change

A change in mission may alter:

- consequence;
- environment;
- human authority;
- operating conditions;
- required autonomy.

The same technical capability may therefore require a different authorisation for a different mission.

---

## 37. Autonomy Restrictions

Restrictions may include:

- lower autonomy;
- narrower mission;
- narrower environment;
- additional supervision;
- additional confirmation;
- reduced operating period;
- increased monitoring.

Restrictions should be communicated to affected personnel.

---

## 38. Suspension

Suspension should be considered where:

- human control is lost;
- autonomous behaviour becomes unexpected;
- boundaries cannot be enforced;
- security integrity is compromised;
- critical dependencies fail;
- material evidence contradicts safe operation.

Suspension should prevent unintended continuation.

---

## 39. Restoration

Restoration from restricted, safe or suspended states should require verification of:

- system condition;
- configuration;
- environment;
- human authority;
- autonomy;
- security;
- dependencies;
- applicable authorisation;
- readiness.

Technical recovery does not automatically restore operational authority.

---

## 40. Operational Records

Material autonomy events should be recorded where required, including:

- autonomy state;
- transition;
- trigger;
- authority;
- intervention;
- boundary event;
- relevant configuration;
- environment;
- outcome.

Records should support accountability and assurance.

---

## 41. Governance Questions

The organisation should be able to answer:

1. What autonomy level is currently active?
2. What functions are permitted at that level?
3. Who authorised the autonomy?
4. What human authority remains?
5. What conditions govern the autonomy?
6. What boundaries apply?
7. Can autonomy increase without human approval?
8. What triggers autonomy reduction?
9. What happens if communications fail?
10. What happens if the environment changes?
11. What happens if the AI behaves unexpectedly?
12. Can personnel intervene?
13. Can the capability enter a safe state?
14. Are autonomy transitions recorded?
15. What triggers revalidation or reauthorisation?

---

## 42. Golden Thread

Operational autonomy remains connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Autonomy → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation**

---

## 43. Core Rule

> **Operational autonomy shall remain within explicitly authorised mission, environmental, functional, geographic, temporal, configuration, data, dependency, consequence and human-authority boundaries. Autonomy transitions shall be predefined, observable and attributable, and shall not occur merely because the system is technically capable of performing a higher-risk function. Material loss of human control, uncertainty about boundaries, unexpected autonomy, environmental change, configuration change, security compromise or critical dependency failure shall trigger proportionate protective action, including restriction, autonomy reduction, human control, safe-state transition or suspension where required. Restoration of technical capability shall not by itself restore operational authority; the conditions supporting authorised autonomy shall first be verified.**
