# Mission Threat Context

## 1. Purpose

Mission Threat Context defines the threat conditions that may affect an AI capability, its mission, its information, its users and its operational authority.

The purpose is to ensure that AI governance considers not only ordinary operating conditions, but also deliberate attempts to deceive, manipulate, degrade, compromise or exploit the capability.

---

## 2. Core Principle

AI assurance must account for the threat environment in which the capability is expected to operate.

The relevant question is:

> **Can the AI capability remain sufficiently trustworthy when exposed to the threats and degraded conditions reasonably expected within its authorised operational context?**

Threat context is therefore part of mission context, risk, TEVV, security and operational authorisation.

---

## 3. Threat Context Scope

Mission threat context should consider threats to:

- data;
- sensors;
- communications;
- models;
- software;
- hardware;
- users;
- decision processes;
- operational authority;
- supply chains;
- supporting infrastructure;
- availability;
- integrity;
- confidentiality where relevant;
- human-AI interaction.

Threat assessment should remain appropriate to the intended use and classification of the system.

---

## 4. Threat Actors

Relevant threat actors may include:

- external adversaries;
- malicious insiders;
- compromised users;
- compromised suppliers;
- compromised infrastructure;
- automated or AI-enabled adversaries;
- opportunistic actors;
- accidental or unintentional actors.

The framework should not assume that every failure originates from an external attacker.

---

## 5. Threat Categories

Threats should be considered across several dimensions.

### 5.1 Data Manipulation

Examples include:

- corrupted inputs;
- misleading data;
- poisoned training data;
- altered metadata;
- fabricated information;
- stale information;
- incomplete information.

### 5.2 Sensor Manipulation

Examples include:

- spoofing;
- deception;
- sensor degradation;
- false signals;
- missing observations;
- environmental interference.

### 5.3 Communications Threats

Examples include:

- communications loss;
- interception;
- disruption;
- delay;
- bandwidth degradation;
- unreliable connectivity.

### 5.4 Model and Software Threats

Examples include:

- malicious modification;
- unauthorised model changes;
- compromised dependencies;
- hidden functionality;
- unsafe updates;
- configuration manipulation.

### 5.5 Cyber Threats

Relevant cyber threats should be considered according to the system architecture and mission.

These may include:

- unauthorised access;
- privilege escalation;
- manipulation;
- denial of service;
- persistence;
- compromise of supporting systems.

D-AIGAAF should align with applicable cybersecurity requirements rather than replacing them.

### 5.6 Human-AI Manipulation

Threats may target human users rather than the AI system directly.

Examples include:

- deceptive recommendations;
- manipulation of operator trust;
- automation bias;
- misleading confidence;
- excessive reliance on AI output;
- deliberate exploitation of human decision patterns.

---

## 6. Adversarial AI Threats

AI systems may be exposed to deliberate attempts to influence their behaviour.

Relevant considerations may include:

- adversarial inputs;
- prompt or input manipulation where applicable;
- data poisoning;
- model extraction;
- model manipulation;
- evasion;
- deceptive content;
- adversarial examples;
- attempts to induce unsafe behaviour.

The applicable threat set should depend on the AI architecture and use case.

---

## 7. Threats to Situational Awareness

AI may contribute to command situational awareness.

Threats should therefore consider whether an adversary could cause the system or its users to:

- miss relevant information;
- receive false information;
- misinterpret information;
- overestimate confidence;
- underestimate uncertainty;
- develop an incorrect operational picture.

The security of information supporting decisions is an operational concern, not merely a technical concern.

---

## 8. Threats to Human Authority

Threat context should consider attempts to undermine the intended human authority structure.

Examples include:

- AI recommendations being treated as commands;
- users bypassing required approval;
- unauthorised delegation;
- hidden automation;
- loss of meaningful human control;
- inability to override the system;
- authority being transferred implicitly to the AI.

AI capability must not silently expand its operational authority because of technical functionality.

---

## 9. Loss-of-Control Threats

A critical threat category is loss of control.

This may occur when an AI system:

- behaves outside its authorised boundaries;
- takes unauthorised actions;
- continues operating after authority has been withdrawn;
- cannot be reliably interrupted;
- modifies critical behaviour without authorisation;
- exploits unexpected system pathways;
- affects systems beyond its intended scope.

Loss of control should be assessed separately from ordinary technical failure.

---

## 10. Insider and Supply-Chain Threats

Threat context should consider the possibility that trusted components, personnel or suppliers may become compromised.

Relevant considerations include:

- supplier access;
- software dependencies;
- model provenance;
- update mechanisms;
- privileged accounts;
- third-party services;
- critical infrastructure dependencies;
- compromised development environments.

Provenance should support identification of components or actors capable of materially changing system behaviour.

---

## 11. Threats From Degraded Conditions

Not all threat conditions involve deliberate attack.

Mission threat context should also include:

- poor weather;
- sensor degradation;
- power limitations;
- communications loss;
- incomplete data;
- infrastructure failure;
- high workload;
- reduced staffing;
- geographic isolation;
- environmental extremes.

These conditions may interact with deliberate threats.

---

## 12. Threat Combinations

Threats should not always be assessed independently.

Important combinations may include:

**Adversarial Input + Poor Data + High Autonomy**

**Sensor Degradation + Communications Loss + High Human Workload**

**Cyber Compromise + Supply-Chain Dependency + Reduced Human Control**

**False Information + Time Pressure + High Mission Consequence**

Combined conditions may produce risks that are not apparent when each threat is considered separately.

---

## 13. Threat Severity

Threat significance should consider:

- likelihood or plausibility;
- potential consequence;
- detectability;
- persistence;
- reversibility;
- exposure;
- affected mission;
- affected authority;
- potential for cascading effects.

Threat severity should not be reduced to a single universal numerical formula without appropriate validation.

---

## 14. Threat Detection

The system and operational organisation should identify how relevant threats may be detected.

Detection mechanisms may include:

- integrity checks;
- anomaly detection;
- independent information sources;
- human review;
- system monitoring;
- security monitoring;
- provenance checks;
- behavioural monitoring;
- operational alerts.

Detection limitations should be explicitly documented.

---

## 15. Threat Response

Threat response should define appropriate actions.

Depending on severity and authority, these may include:

- warning;
- increased human scrutiny;
- reduced autonomy;
- controlled degradation;
- isolation;
- transfer to human control;
- suspension;
- fail-safe;
- emergency protective action.

Response authority must be explicitly assigned.

---

## 16. Threats and Autonomy

Threat conditions may change the acceptable autonomy level.

For example, an autonomy level acceptable under controlled conditions may not remain acceptable when:

- communications are unavailable;
- sensor confidence is degraded;
- adversarial manipulation is suspected;
- human intervention is delayed;
- mission consequence increases.

Operational authority should therefore be conditional on relevant threat conditions.

---

## 17. Threats and Human Control

Threat assessment should examine whether meaningful human control remains possible.

Questions include:

- Can the human understand the relevant system state?
- Can the human identify unreliable output?
- Can the human intervene?
- Can intervention occur within the required time?
- Can the system be suspended?
- Can the human operate without the AI if necessary?

Human presence alone should not be treated as sufficient control.

---

## 18. Threats and Uncertainty

Threat conditions can increase uncertainty.

The AI capability should distinguish, where technically feasible, between:

- reliable information;
- uncertain information;
- missing information;
- conflicting information;
- anomalous information.

The system should not convert significant uncertainty into unjustified confidence.

---

## 19. Threats and Mission Boundaries

Threat conditions may create pressure to operate outside the authorised envelope.

Examples include:

- expanding the mission because normal tools are unavailable;
- increasing autonomy because communications are lost;
- using unapproved data sources;
- bypassing human approval;
- continuing operation after a security compromise.

Such changes should be treated as changes in operational conditions, not as automatic authority.

---

## 20. Threat-Informed TEVV

Threat context should inform TEVV.

Testing and evaluation should consider relevant:

- adversarial inputs;
- degraded data;
- sensor manipulation;
- communications disruption;
- cyber conditions;
- human workload;
- loss-of-control conditions;
- recovery procedures.

Evidence should demonstrate performance and limitations under conditions representative of the intended threat environment.

---

## 21. Threat-Informed Assurance

Assurance should consider whether evidence adequately supports claims under the relevant threat conditions.

A capability should not be considered robust merely because it performs well in benign conditions.

Assurance should identify:

- tested threats;
- untested threats;
- known vulnerabilities;
- evidence gaps;
- residual uncertainty;
- compensating controls.

---

## 22. Threat-Informed Operational Authorisation

Operational authorisation should specify material threat conditions where relevant.

The authorisation may establish:

- permitted threat environment;
- required controls;
- autonomy restrictions;
- human control requirements;
- monitoring requirements;
- suspension triggers;
- fail-safe conditions;
- reauthorisation triggers.

A significant change in threat conditions may invalidate assumptions supporting the original authorisation.

---

## 23. Threat Escalation

Escalation should occur when:

- threat severity increases materially;
- a new threat is identified;
- a critical control fails;
- system behaviour changes;
- human control is degraded;
- loss of control becomes plausible;
- evidence is no longer representative;
- a security compromise is suspected.

Escalation should lead to an explicitly defined decision or action.

---

## 24. Emergency Conditions

Where a threat creates an immediate risk of unacceptable harm, pre-authorised emergency procedures may allow rapid protective action.

Emergency procedures should:

- define who may act;
- define what actions are permitted;
- define applicable conditions;
- minimise delay;
- preserve accountability;
- require subsequent recording and review.

Emergency action should not become a mechanism for bypassing normal governance routinely.

---

## 25. Threat Context Record

A Mission Threat Context Record should contain, as applicable:

- mission/use case identifier;
- operational environment;
- threat actors;
- threat categories;
- relevant threat scenarios;
- affected components;
- affected decisions;
- affected human authority;
- detection mechanisms;
- response mechanisms;
- autonomy implications;
- human-control implications;
- TEVV coverage;
- evidence gaps;
- residual threat;
- escalation triggers;
- suspension triggers;
- emergency procedures;
- review date.

---

## 26. Minimum Threat Context Requirements

For consequential AI use cases, the threat assessment should:

1. Identify relevant threat actors.
2. Identify material threats to data and information.
3. Identify relevant sensor threats.
4. Identify communications threats.
5. Identify applicable cyber and software threats.
6. Consider human-AI manipulation.
7. Assess loss-of-control threats.
8. Consider insider and supply-chain threats.
9. Include relevant degraded conditions.
10. Consider significant threat combinations.
11. Define detection and response mechanisms.
12. Assess implications for autonomy.
13. Assess implications for human control.
14. Inform TEVV and assurance.
15. Identify authorisation and suspension implications.
16. Record material assumptions and evidence gaps.

---

## 27. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread`
- `00 Framework/Principles`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Operational_Boundaries.md`
- `03 Risk & Autonomy`
- `05 Data & Information`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`

Threat context provides the threat-informed layer connecting mission conditions with security, risk, assurance and operational authority.

---

## 28. Summary

Mission Threat Context ensures that D-AIGAAF evaluates AI capabilities against the conditions in which they may actually be used, including deliberate adversarial action and degraded environments.

The framework should consider not only whether an AI system can fail, but whether an adversary, compromised dependency, degraded environment or human-AI interaction can cause it to produce unsafe or unauthorised outcomes.

The central principle is:

> **An AI capability should be authorised only to the extent that its behaviour, controls and human authority remain sufficiently trustworthy under the material threat conditions of its intended operational environment.**
