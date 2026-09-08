# 46 — Authorisation for Consequential Autonomy and Weapons Systems

## 1. Purpose

This document defines governance requirements for Defence AI capabilities that can influence or perform actions with consequential effects, including AI-enabled or autonomous weapons systems.

The purpose is not to prescribe operational tactics or classified procedures. It establishes a generic governance model for determining when, where and under what human authority consequential autonomy may be permitted.

---

## 2. Core Principle

> **A Defence AI system shall not acquire authority to perform consequential actions merely because it is technically capable of performing them. Consequential autonomy shall require explicit, bounded and proportionate operational authorisation, supported by evidence of control, reliability, security, environmental suitability and meaningful human authority.**

---

## 3. Consequential Autonomy

For D-AIGAAF purposes, consequential autonomy refers to AI-enabled activity where the system can materially influence or perform an action that may affect:

- human life;
- physical safety;
- critical infrastructure;
- significant property;
- mission-critical outcomes;
- other materially consequential interests.

The precise legal and doctrinal definition should be determined by the adopting organisation.

---

## 4. Autonomy Model

D-AIGAAF uses the following working model:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These categories are governance constructs, not universal legal definitions.

They should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

---

## 5. Autonomy Is Not Authority

The framework distinguishes:

**Capability** — what the system can technically do.

**Autonomy** — how independently the system can perform or initiate functions.

**Authority** — what the organisation has formally permitted the system to do.

A system may possess technical capability that exceeds its authorised operational authority.

---

## 6. Weapons-System Context

Where AI is incorporated into a weapons system or other consequential platform, authorisation should address the combined system rather than the AI model in isolation.

The assessment should consider:

**AI Component × Platform × Human Authority × Mission × Environment × Autonomy**

The combined behaviour, interfaces and control arrangements should be understood sufficiently for the proposed use.

---

## 7. Human Authority

The organisation should identify:

- authorising authority;
- operational authority;
- responsible commander or decision-maker;
- operator;
- supervisor;
- technical authority;
- assurance authority;
- security authority;
- risk owner;
- escalation authority.

Human accountability should remain identifiable even when autonomous functions are authorised.

---

## 8. Meaningful Human Control

Where human control is required, the organisation should establish that humans can realistically:

- understand the relevant system output;
- understand material uncertainty;
- assess the operational context;
- determine whether employment remains appropriate;
- intervene where required;
- restrict or stop the capability;
- respond to unexpected behaviour;
- escalate concerns.

Formal presence of a human should not be treated as sufficient evidence of meaningful control.

---

## 9. Human Decision Authority

For human-authorised consequential actions, the authorisation should identify:

- what decision the human must make;
- what information is available;
- what AI contribution is permitted;
- what the human may reject or modify;
- what uncertainty must be considered;
- what authority the human possesses;
- what actions remain prohibited.

The human should not be reduced to a procedural confirmation step.

---

## 10. Autonomous Action Authority

Where autonomous action is authorised, the authorisation should explicitly define:

- permitted function;
- permitted mission;
- permitted environment;
- autonomy level;
- operating boundaries;
- human supervision requirements;
- intervention conditions;
- prohibited actions;
- fail-safe behaviour;
- monitoring;
- suspension triggers.

Autonomous authority should be no broader than necessary for the authorised purpose.

---

## 11. Scope of Autonomy

Autonomy should be bounded across:

- mission;
- geography;
- time;
- environment;
- function;
- target or object category where applicable;
- configuration;
- data;
- interfaces;
- dependencies;
- consequence;
- human authority.

These boundaries should be documented and, where practicable, technically enforced.

---

## 12. Autonomy Transitions

Transitions between autonomy states should be governed.

Examples include:

**Human Control → Assisted Operation → Supervised Autonomy → Reduced Autonomy → Human Control → Safe State**

A system should not silently transition to a higher autonomy state because of:

- communications loss;
- operator absence;
- degraded sensors;
- software failure;
- environmental change;
- mission urgency;
- dependency failure.

Any permitted transition should have predefined conditions and authority.

---

## 13. Loss of Human Control

The organisation should define what constitutes loss or material degradation of human control.

Indicators may include:

- inability to understand system behaviour;
- inability to intervene;
- inability to communicate required instructions;
- excessive human workload;
- loss of situational awareness;
- unexpected autonomy;
- failed override;
- uncertain system state.

Loss of required human control should trigger proportionate protective action.

---

## 14. Fail-Safe and Safe State

Consequential autonomous systems should have credible mechanisms for:

- intervention;
- autonomy reduction;
- controlled termination;
- safe-state transition;
- suspension.

Fail-safe mechanisms should be tested under representative conditions.

The organisation should define what happens when a fail-safe cannot be confirmed to function as intended.

---

## 15. Emergency Protective Action

Emergency conditions may require immediate protective action.

Pre-authorised procedures should define who may:

- restrict autonomy;
- transition to human control;
- place the system in a safe state;
- suspend operation;
- invoke other approved protective measures.

Where delay could create unacceptable harm, appropriately pre-authorised emergency action may occur without waiting for the full normal escalation chain.

Emergency action should remain bounded and recorded.

---

## 16. Weapons-System Safety

Where AI contributes to weapons-system functions, assurance should address:

- system boundaries;
- control logic;
- sensor inputs;
- data integrity;
- environmental limitations;
- human-control mechanisms;
- autonomy transitions;
- fail-safe behaviour;
- cybersecurity;
- configuration integrity;
- unexpected behaviour.

The framework should not assume that satisfactory AI model performance alone establishes safety of the integrated system.

---

## 17. Identification and Consequence

Before authorisation, the organisation should determine:

- what or whom the system may affect;
- what types of actions it may support or perform;
- the maximum foreseeable consequence;
- what uncertainty exists;
- what human authority applies;
- what controls limit unacceptable outcomes.

The assessment should include foreseeable unintended effects.

---

## 18. Uncertainty and Identification

Where consequential action depends on AI-generated identification, classification or inference, the authorisation should establish:

- acceptable uncertainty;
- information requirements;
- relevant confidence or uncertainty indicators;
- conditions requiring human review;
- conditions requiring rejection;
- escalation requirements.

The system should not conceal material uncertainty or present uncertain outputs as established facts.

---

## 19. Environmental Boundaries

Consequential autonomy should be authorised only for environments supported by sufficient evidence.

Environmental considerations may include:

- terrain;
- weather;
- illumination;
- sensor conditions;
- communications;
- navigation;
- electromagnetic conditions;
- adversarial interference;
- information availability;
- human operating conditions.

Operation outside the demonstrated envelope should trigger predefined restrictions or additional assurance.

---

## 20. Degraded and Disconnected Operations

The authorisation should define behaviour under:

- communication degradation;
- complete communication loss;
- sensor degradation;
- navigation uncertainty;
- degraded computing;
- data unavailability;
- dependency failure.

Loss of connectivity should not automatically increase autonomy unless that behaviour has been specifically assessed and authorised.

---

## 21. Adversarial Conditions

Consequential autonomous systems should be assessed against plausible attempts to:

- deceive sensors;
- manipulate inputs;
- corrupt data;
- interfere with communications;
- manipulate interfaces;
- compromise software or models;
- induce unsafe behaviour.

Adversarial evaluation should be proportionate to consequence and autonomy.

---

## 22. Own-Force and Friendly-System Risk

Governance should consider the possibility of erroneous or unintended effects on:

- own personnel;
- friendly forces;
- cooperating systems;
- civilian persons or assets;
- protected infrastructure;
- other authorised systems.

The authorisation should define applicable controls and boundaries for such risks.

---

## 23. Multi-AI and System-of-Systems Autonomy

Where multiple AI systems interact, individually authorised systems should not automatically gain combined autonomous authority.

Assessment should consider:

- recommendation chaining;
- automated decision chains;
- conflicting outputs;
- shared data;
- shared dependencies;
- cascading failures;
- emergent behaviour;
- combined autonomy.

Material combined behaviour should be assessed as part of the authorisation basis.

---

## 24. Configuration and Model Integrity

Consequential autonomy should be linked to an approved configuration baseline.

Material changes to:

- model weights;
- model architecture;
- training or fine-tuning;
- software;
- autonomy logic;
- safety mechanisms;
- sensors;
- interfaces;
- data;
- security controls;

should undergo appropriate change assessment.

Material behavioural changes should require revalidation or reauthorisation as applicable.

---

## 25. Testing and TEVV

Consequential autonomous systems should undergo proportionate TEVV across:

1. Technical Performance;
2. Reliability and Robustness;
3. Adversarial Resilience;
4. Operational Environment;
5. Human-AI Interaction;
6. Security and Integrity;
7. Autonomy and Control;
8. Mission Effectiveness.

Testing should include relevant boundary and failure conditions.

---

## 26. Operational Trials

Where practicable, operational trials should evaluate:

- realistic environmental conditions;
- human workload;
- communications degradation;
- sensor limitations;
- autonomy transitions;
- intervention;
- fail-safe behaviour;
- uncertainty communication;
- system interactions;
- unexpected behaviour.

Trials should generate evidence relevant to the specific proposed authority.

---

## 27. Independent Challenge

High-consequence autonomy should receive independent review proportionate to risk.

Reviewers should be able to challenge:

- autonomy claims;
- evidence;
- assumptions;
- safety mechanisms;
- human-control claims;
- environmental suitability;
- security;
- risk acceptance;
- proposed boundaries.

---

## 28. Operational Boundaries

The authorisation should explicitly identify:

**Permitted → Restricted → Prohibited**

functions or behaviours.

Technical capability should never be treated as operational permission.

Boundary violations should trigger defined responses.

---

## 29. Monitoring During Employment

Monitoring should assess:

- system behaviour;
- autonomy state;
- uncertainty;
- performance;
- environmental conditions;
- human control;
- security;
- data integrity;
- dependencies;
- boundary conditions;
- incidents.

Monitoring thresholds should be defined before employment.

---

## 30. Protective Response

A consequential autonomous capability should have predefined response states:

**Continue → Monitor Closely → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The response should be proportionate to consequence and urgency.

---

## 31. Suspension Triggers

Potential triggers include:

- loss of human control;
- unexpected consequential behaviour;
- failed fail-safe;
- serious security compromise;
- material configuration uncertainty;
- environmental conditions outside the authorised envelope;
- unacceptable performance;
- boundary violation;
- critical dependency failure;
- material evidence contradicting the authorisation basis.

---

## 32. Risk Acceptance

Residual risk should be explicitly assessed and accepted by an appropriately authorised human authority.

Risk acceptance should identify:

- known risks;
- uncertainty;
- controls;
- limitations;
- residual risk;
- monitoring;
- acceptance authority;
- review triggers.

Risk acceptance does not create authority beyond the approved operational scope.

---

## 33. Decision and Action Traceability

For consequential AI use, the organisation should preserve, where feasible:

**Operational Context → AI Contribution → Human Assessment or Authorised Autonomous Process → Authority → Decision → Action → Outcome**

For autonomous actions, records should identify the applicable:

- authorisation;
- autonomy state;
- configuration;
- operating conditions;
- relevant AI/system contribution;
- human authority that authorised the autonomous mode.

---

## 34. Operational AI Advisor

The OAIA may support command and authorising authorities by explaining:

- AI capability;
- limitations;
- uncertainty;
- autonomy;
- evidence;
- operational suitability;
- emerging behaviour.

The OAIA advises; the designated human authority authorises.

---

## 35. Legal and Policy Compliance

Consequential autonomous systems shall be governed consistently with:

- applicable law;
- national policy;
- defence policy;
- applicable rules and directives;
- relevant international obligations;
- organisational authorisation requirements.

D-AIGAAF does not replace legal review or establish legal permission.

---

## 36. Training and Competence

Personnel involved in consequential autonomy should understand:

- system capabilities;
- limitations;
- autonomy states;
- human-control requirements;
- uncertainty;
- operational boundaries;
- intervention;
- fail-safe procedures;
- escalation;
- incident reporting.

Competence should be demonstrated before assuming consequential authority.

---

## 37. Reauthorisation

Reauthorisation should be considered when there is material change to:

- mission;
- environment;
- autonomy;
- system behaviour;
- configuration;
- human-control arrangements;
- security;
- dependencies;
- consequence;
- evidence.

Previous successful employment does not automatically establish authority for a materially different use.

---

## 38. Governance Questions

Before authorising consequential autonomy, the organisation should be able to answer:

1. What consequential action can the system perform or influence?
2. What is the maximum foreseeable consequence?
3. What autonomy level is requested?
4. Who holds operational authority?
5. What human control remains?
6. What prevents unauthorised action?
7. What happens when the system is uncertain?
8. What happens when communications fail?
9. What happens when the environment changes?
10. What happens when the system behaves unexpectedly?
11. Can the system be restricted, controlled or placed in a safe state?
12. What evidence demonstrates the required performance?
13. What independent challenge has occurred?
14. Who accepts residual risk?
15. What triggers suspension or reauthorisation?
16. Can consequential activity be reconstructed afterwards?

---

## 39. Golden Thread

Consequential autonomy should remain connected to:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Autonomy → Employment → Monitoring → Incident/Change → Revalidation/Reauthorisation**

---

## 40. Core Rule

> **Consequential autonomous Defence AI, including AI-enabled weapons systems, shall operate only under explicit, bounded and appropriately authorised human governance. The organisation shall establish the permitted autonomy, mission, environment, human authority, configuration, boundaries, safeguards, monitoring and emergency controls before operational employment. The greater the potential consequence and autonomy, the stronger the required evidence, independent challenge, human-control arrangements and assurance. Technical capability shall never be interpreted as operational permission, and material loss of control, unexpected behaviour, uncertainty, boundary violation or compromise of the authorisation basis shall trigger proportionate restriction, reduced autonomy, human control, safe-state transition or suspension.**
