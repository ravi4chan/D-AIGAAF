# Mission Definition

## 1. Purpose

Mission definition establishes why an AI capability is required, what operational problem it is intended to address, and the boundaries within which it may be used.

A clear mission definition is the starting point for determining:

- operational requirements;
- mission criticality;
- risk;
- appropriate autonomy;
- required assurance;
- human authority;
- operational environment;
- authorisation conditions.

AI governance should begin with the mission rather than with the technology.

---

## 2. Core Principle

The governing sequence is:

**Mission Need → Use Case → Requirements → Risk → Assurance → Authority**

An AI capability should not receive operational authority merely because the underlying technology is technically capable.

The relevant question is:

> **What mission problem is this AI capability intended to solve, and what happens if it is wrong?**

---

## 3. Mission Need

A Mission Need identifies the operational problem or opportunity that requires a capability.

A Mission Need should describe:

- the operational problem;
- why existing approaches are insufficient;
- the desired operational outcome;
- affected personnel or assets;
- relevant constraints;
- expected consequences of failure;
- urgency;
- strategic or operational importance.

The Mission Need should be stated independently of a particular AI solution wherever possible.

For example:

**Weak:**  
"Deploy an AI model to detect objects."

**Stronger:**  
"Improve the timely identification of relevant objects within a defined surveillance area under specified environmental and information constraints."

This prevents technology from defining the mission unnecessarily.

---

## 4. Mission Objective

Each AI-enabled capability should have an explicit mission objective.

The objective should identify:

- what outcome is required;
- who or what benefits from the capability;
- the operational decision or activity supported;
- the expected performance;
- the conditions under which the objective applies.

Mission objectives should be measurable where practical.

---

## 5. Mission Criticality

Mission criticality describes the operational importance of the AI capability.

A working construct may include:

| Level | Description |
|---|---|
| M1 | Convenience or low operational significance |
| M2 | Supports routine operational activity |
| M3 | Material effect on mission performance |
| M4 | Significant effect on operational success, safety or critical functions |
| M5 | Critical to life, strategic decisions, essential infrastructure or other catastrophic consequences |

These levels are a framework construct and should be calibrated by the implementing organisation.

Mission criticality should influence the required level of assurance and operational control.

---

## 6. Mission Context

AI performance cannot be evaluated independently of its operational context.

Mission context should identify, where applicable:

- geographic setting;
- operational purpose;
- friendly and opposing conditions;
- environmental conditions;
- available infrastructure;
- communications;
- sensor availability;
- data availability;
- time constraints;
- human resources;
- applicable rules and policy;
- dependencies;
- expected adversarial conditions.

The same AI system may have different risk and assurance requirements in different missions.

---

## 7. Operational Environment

The mission definition should identify the environments in which the capability is expected to operate.

Examples may include:

- controlled environments;
- routine field environments;
- contested environments;
- degraded communications environments;
- disconnected or offline environments;
- high-altitude environments;
- mountainous environments;
- desert environments;
- jungle environments;
- maritime or amphibious environments;
- dense urban environments;
- disaster or humanitarian environments;
- adversarial or deceptive environments.

The list is illustrative, not exhaustive.

An AI capability should not automatically be assumed to be suitable for an environment merely because it performs successfully in another environment.

---

## 8. Mission Constraints

Mission definition should capture constraints that may affect AI performance or authority.

Examples include:

- limited communications;
- intermittent connectivity;
- limited computing resources;
- restricted power;
- sensor degradation;
- incomplete information;
- time pressure;
- environmental extremes;
- electromagnetic interference;
- adversarial manipulation;
- limited human availability;
- legal or policy constraints.

Constraints should become inputs to requirements, testing and assurance.

---

## 9. Mission Stakeholders

The mission definition should identify relevant stakeholders.

These may include:

- operational commanders;
- end users;
- system owners;
- capability owners;
- AI developers;
- AI security personnel;
- TEVV personnel;
- assurance authorities;
- legal and policy advisers;
- data owners;
- acquisition authorities;
- affected personnel or organisations.

Stakeholder identification should make accountability and consultation requirements visible.

---

## 10. Supported Operational Decision or Activity

The mission definition should identify exactly what the AI capability supports.

Examples include:

- situational awareness;
- information fusion;
- intelligence analysis;
- logistics planning;
- maintenance;
- route planning;
- resource allocation;
- threat assessment;
- targeting support;
- command decision support;
- autonomous system control.

The framework should distinguish between:

**AI Output → Human Interpretation → Human Decision → Operational Action**

These are not automatically the same thing.

---

## 11. Consequence of Error

The mission definition should explicitly consider what happens if the AI is wrong.

Potential consequences include:

- inconvenience;
- resource wastage;
- mission delay;
- incorrect prioritisation;
- loss of operational advantage;
- equipment damage;
- injury;
- death;
- compromise of sensitive information;
- damage to critical infrastructure;
- escalation of conflict;
- strategic or political consequences.

The severity of possible consequences should influence risk, assurance and authority requirements.

---

## 12. Consequence of Non-Availability

The framework should also consider what happens if the AI capability becomes unavailable.

Possible consequences include:

- reduced efficiency;
- delayed decision-making;
- degraded situational awareness;
- loss of a critical capability;
- increased human workload;
- increased operational risk.

A capability that becomes a critical dependency may require additional resilience and continuity measures.

---

## 13. Consequence of Loss of Control

For AI-enabled systems with autonomous or semi-autonomous behaviour, the mission definition should consider the consequences of loss of control.

Questions should include:

- What can the system do?
- What could it do incorrectly?
- What happens if human intervention is delayed?
- What happens if communications are lost?
- What happens if the system behaves outside its expected operating envelope?
- Can it affect people, equipment, infrastructure or other systems?
- Can its behaviour create cascading effects?

Loss-of-control consequences should feed directly into risk and autonomy assessment.

---

## 14. Mission Boundaries

Every mission should have explicit boundaries.

These may include:

- geographic boundaries;
- temporal boundaries;
- environmental boundaries;
- information boundaries;
- system boundaries;
- functional boundaries;
- autonomy boundaries;
- human-authority boundaries;
- legal and policy boundaries.

A capability authorised for one mission should not automatically be assumed to be authorised for another.

---

## 15. Intended Use

The intended use should describe what the capability is expected to do.

It should identify:

- users;
- tasks;
- inputs;
- outputs;
- decision points;
- operating conditions;
- expected human interaction;
- expected system behaviour;
- limitations.

Intended use should be sufficiently specific to support meaningful testing and assurance.

---

## 16. Foreseeable Misuse

Mission definition should also consider reasonably foreseeable misuse.

Examples include:

- use outside the authorised mission;
- use with unsupported data;
- use in an untested environment;
- use at a higher autonomy level;
- use after a material system change;
- use despite known limitations;
- treating AI recommendations as authoritative decisions;
- extending the system to a new mission without reauthorisation.

Foreseeable misuse should be considered during risk assessment and operational design.

---

## 17. Mission Dependencies

Mission definition should identify dependencies that could affect operational performance.

Dependencies may include:

- data sources;
- sensors;
- communications;
- positioning;
- power;
- cloud or edge infrastructure;
- external services;
- third-party models;
- software libraries;
- human operators;
- specialist personnel;
- maintenance;
- supplier support.

Critical dependencies should be visible in the capability and assurance records.

---

## 18. Mission Alternatives

AI should not automatically be treated as the only solution.

The mission analysis should consider:

- existing human processes;
- conventional technology;
- non-AI automation;
- alternative AI approaches;
- combinations of human and AI capabilities;
- whether the mission should be performed at all.

This supports proportionality and prevents unnecessary introduction of AI into high-consequence activities.

---

## 19. Mission-Level Performance

Performance requirements should be defined at the mission level rather than relying exclusively on model-level metrics.

For example, high model accuracy does not necessarily demonstrate:

- operational effectiveness;
- resilience under degraded conditions;
- appropriate human decision-making;
- acceptable false-positive consequences;
- acceptable false-negative consequences;
- suitability for the intended mission.

Mission effectiveness must therefore be assessed as part of the broader TEVV and assurance process.

---

## 20. Mission Change

A change in mission may change the assurance and authorisation position.

Examples include:

- new geographic area;
- new user group;
- new mission objective;
- higher consequence;
- new operational environment;
- increased autonomy;
- new data source;
- new system dependency.

A capability should be reassessed when mission change materially affects its risk or operational behaviour.

---

## 21. Mission Definition Record

Each consequential AI capability should maintain a Mission Definition Record containing, as applicable:

- Mission Need;
- Mission Objective;
- Mission Criticality;
- Operational Context;
- Operational Environment;
- Mission Constraints;
- Stakeholders;
- Supported Decision or Activity;
- Consequences of Error;
- Consequences of Non-Availability;
- Loss-of-Control Consequences;
- Mission Boundaries;
- Intended Use;
- Foreseeable Misuse;
- Dependencies;
- Alternatives Considered;
- Mission-Level Performance Requirements;
- Applicable Legal and Policy Constraints.

---

## 22. Minimum Mission Definition Requirements

Before progressing to detailed risk and assurance activities, a consequential AI capability should have:

1. A clearly stated Mission Need.
2. A defined Mission Objective.
3. A defined operational context.
4. Identified operational environments.
5. Defined mission boundaries.
6. Identified supported decisions or activities.
7. Identified consequences of error.
8. Considered consequences of non-availability.
9. Considered loss-of-control consequences where applicable.
10. Identified critical dependencies.
11. Identified intended use and foreseeable misuse.
12. Defined appropriate mission-level performance expectations.
13. Identified applicable legal and policy constraints.

---

## 23. Relationship With D-AIGAAF

Mission Definition is an input to:

- `00 Framework/Golden Thread.md`
- `01 Strategy & Governance`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `15 Change & Reauthorisation`

The Golden Thread begins with:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority**

Mission Definition provides the first substantive link in that chain.

---

## 24. Summary

D-AIGAAF begins with the mission, not the model.

A capability should be understood in terms of:

**Why it exists → What it is intended to do → Where it will operate → What decisions it supports → What happens if it is wrong → What authority it may require**

A technically capable AI system is not necessarily an operationally suitable AI capability.

Mission definition establishes the context required to determine whether it is suitable, trustworthy and appropriate for operational use.
