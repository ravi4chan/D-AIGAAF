# Use Case Risk Profile

## 1. Purpose

The Use Case Risk Profile provides an initial, use-case-specific view of the risks associated with employing an AI capability for a defined mission.

It connects the mission and use case to the broader D-AIGAAF risk process.

The profile is not a substitute for the formal risk assessment. It establishes the key risk drivers that must be examined before determining:

- required controls;
- assurance depth;
- human authority;
- autonomy;
- operational restrictions;
- authorisation conditions.

---

## 2. Core Principle

Risk belongs to the **AI capability in its intended use**, not simply to the underlying model.

The governing relationship is:

**Capability + Mission + Use Case + Context + Constraints → Risk**

The same model may therefore have materially different risk profiles across different use cases.

---

## 3. Risk Profile Scope

The profile should be specific to:

- AI capability;
- mission;
- use case;
- operational environment;
- authorised users;
- autonomy level;
- human authority;
- relevant dependencies.

A generic system-level risk statement should not automatically be treated as a use-case risk assessment.

---

## 4. Risk Dimensions

The use case should consider at least the following dimensions:

- consequence;
- autonomy;
- mission criticality;
- operational environment;
- human control;
- information integrity;
- security;
- supply-chain dependency;
- system reliability;
- uncertainty;
- availability;
- interoperability.

These dimensions should be assessed qualitatively or using an approved organisational methodology.

---

## 5. Consequence

The profile should identify the consequences that could arise from incorrect, unavailable, manipulated or uncontrolled AI behaviour.

Potential consequences include:

- incorrect information;
- poor prioritisation;
- mission delay;
- resource loss;
- equipment damage;
- injury;
- loss of life;
- compromise of sensitive information;
- critical infrastructure disruption;
- unintended escalation;
- strategic consequences.

Higher consequence generally requires stronger evidence, controls and human authority.

---

## 6. Autonomy

The risk profile should identify the AI's authorised autonomy.

A working construct is:

| Level | Description |
|---|---|
| A0 | No meaningful AI decision-making |
| A1 | Information or observation |
| A2 | Analysis or recommendation |
| A3 | Recommendation or action requiring explicit human authorisation |
| A4 | Predefined action under human supervision |
| A5 | Independent consequential decision or action |

This taxonomy is a working D-AIGAAF construct and should be validated against established terminology.

Higher autonomy generally increases the need to understand:

- system behaviour;
- failure modes;
- intervention mechanisms;
- operational boundaries;
- loss-of-control consequences.

---

## 7. Mission Criticality

The profile should identify how important the use case is to mission success.

A working construct is:

| Level | Description |
|---|---|
| M1 | Low operational significance |
| M2 | Routine operational support |
| M3 | Material mission effect |
| M4 | Significant mission, safety or critical-function effect |
| M5 | Critical to life, strategic decisions or catastrophic consequences |

The implementing organisation should calibrate these levels to its own risk methodology.

---

## 8. Operational Environment

The profile should identify whether the use case operates in:

- controlled conditions;
- routine field conditions;
- degraded conditions;
- contested conditions;
- adversarial conditions;
- disconnected or offline conditions;
- environmentally extreme conditions.

Risk may increase when conditions differ from those represented in training, testing or previous operational evidence.

---

## 9. Human Control

The profile should assess the degree of meaningful human control.

Consider:

- proximity of the human decision-maker;
- time available to intervene;
- information available to the human;
- ability to understand the AI output;
- ability to reject or override;
- reliability of communications;
- availability of trained personnel;
- consequences of delayed intervention.

A nominal human-in-the-loop arrangement may provide little practical control if intervention is unrealistic.

---

## 10. Information Risk

The profile should consider:

- data quality;
- data completeness;
- data provenance;
- data integrity;
- data latency;
- conflicting information;
- sensor limitations;
- data drift;
- manipulated inputs.

An accurate model can still generate an operationally harmful result when the information presented to it is incorrect or compromised.

---

## 11. Security Risk

Security-related risks may include:

- unauthorised access;
- malicious inputs;
- data poisoning;
- adversarial manipulation;
- model compromise;
- software compromise;
- supply-chain compromise;
- unauthorised updates;
- loss of system integrity.

Security risk should be considered together with operational consequences rather than treated solely as an IT concern.

---

## 12. Loss-of-Control Risk

Where the AI can influence physical, operational or consequential activity, the profile should explicitly address loss of control.

Questions include:

- What actions can the system initiate?
- What happens if it behaves unexpectedly?
- Can it continue operating after communications loss?
- Can it affect other systems?
- Can human intervention be bypassed?
- Can it create cascading effects?
- What is the safest achievable state?

Loss-of-control risk should directly influence autonomy, controls, assurance and authorisation.

---

## 13. Reliability and Robustness

The profile should consider whether failures may occur because of:

- unfamiliar inputs;
- environmental changes;
- sensor degradation;
- software faults;
- hardware faults;
- data changes;
- model drift;
- unexpected interactions;
- system overload.

Reliability should be considered in the actual operating context rather than only under ideal conditions.

---

## 14. Uncertainty

Uncertainty should be treated as a risk-relevant characteristic.

The profile should identify:

- known uncertainty;
- uncertainty arising from missing information;
- uncertainty arising from unfamiliar conditions;
- uncertainty in model outputs;
- uncertainty about system limitations;
- unknown or poorly characterised behaviour.

A system that cannot reliably identify when it may be wrong presents a different risk profile from one that communicates meaningful uncertainty.

---

## 15. Availability Risk

The profile should assess the consequence of AI unavailability.

Consider:

- whether the mission can continue without AI;
- fallback procedures;
- human workload;
- alternative systems;
- dependency on communications;
- dependency on external services;
- recovery time.

A critical AI dependency may require greater resilience than a convenience capability.

---

## 16. Supply-Chain Risk

The profile should consider:

- developer;
- supplier;
- model provenance;
- critical dependencies;
- third-party components;
- update mechanisms;
- remote support;
- ownership changes;
- ability to independently verify changes;
- sovereignty considerations.

Supply-chain uncertainty may increase assurance requirements.

---

## 17. Dependency Risk

Critical dependencies may include:

- data;
- sensors;
- communications;
- positioning;
- power;
- compute;
- external services;
- specialist personnel;
- maintenance;
- software libraries.

The failure of a dependency should be assessed for its effect on mission performance and human control.

---

## 18. Risk of Misuse

The profile should consider foreseeable misuse.

Examples include:

- use outside the intended mission;
- use in an unsupported environment;
- operation at a higher autonomy level;
- treating recommendations as commands;
- bypassing human review;
- using outdated information;
- using an unapproved model version;
- continuing operation after a material change.

Misuse risks should inform controls and operational restrictions.

---

## 19. Risk of Mission Expansion

A system may gradually be used for purposes beyond its original use case.

Potential examples include:

- new missions;
- new geographic areas;
- new users;
- new data sources;
- new autonomy levels;
- new system interfaces.

Such expansion should not occur solely because the system is technically capable of supporting it.

Material mission expansion should trigger appropriate reassessment and, where required, reauthorisation.

---

## 20. Risk Treatment

Risk treatment should consider:

1. Avoid
2. Reduce
3. Control
4. Transfer where appropriate
5. Accept
6. Monitor

Not every risk should be accepted merely because mitigation exists.

Where residual risk remains above the authorised tolerance, the capability should not proceed without an appropriately empowered risk decision.

---

## 21. Risk Acceptance

Risk acceptance must be performed by an authority with appropriate delegated responsibility.

The authority should consider:

- mission importance;
- consequence;
- evidence;
- uncertainty;
- controls;
- residual risk;
- alternatives;
- operational conditions;
- human authority;
- applicable law and policy.

A technical team should not silently accept operational risk on behalf of command authority.

---

## 22. Risk Escalation

Risk should be escalated when:

- consequence increases;
- autonomy increases;
- human control decreases;
- evidence is insufficient;
- uncertainty becomes material;
- operating conditions change;
- a significant incident occurs;
- security integrity is questioned;
- a critical dependency changes;
- system behaviour changes materially.

Escalation thresholds should be defined by the implementing organisation.

---

## 23. Initial Risk Profile

A concise initial profile may use the following structure:

| Dimension | Assessment | Key Evidence / Rationale |
|---|---|---|
| Consequence | C1–C5 |  |
| Autonomy | A0–A5 |  |
| Mission Criticality | M1–M5 |  |
| Environment | E1–E5 |  |
| Human Control | H1–H5 |  |
| Information Integrity | Low/Medium/High/Critical |  |
| Security Risk | Low/Medium/High/Critical |  |
| Loss-of-Control Risk | Low/Medium/High/Critical |  |
| Availability Risk | Low/Medium/High/Critical |  |
| Supply-Chain Risk | Low/Medium/High/Critical |  |
| Uncertainty | Low/Medium/High/Critical |  |
| Critical Dependencies | Identified / Not Identified |  |

This is a profile structure, not a mandatory numerical scoring formula.

D-AIGAAF should avoid creating a universal risk score without sufficient validation and operational evidence.

---

## 24. Risk Profile and Assurance

The risk profile should help determine the required assurance depth.

A simplified relationship is:

**Higher Consequence + Higher Autonomy + Lower Human Control + More Adversarial Environment → Greater Assurance Need**

This relationship is directional rather than a universal mathematical rule.

Assurance requirements should be determined through an approved risk methodology.

---

## 25. Risk Profile and Operational Authorisation

The risk profile informs the operational authorisation case.

Authorisation should consider:

- identified risks;
- residual risk;
- risk acceptance authority;
- evidence;
- operating envelope;
- autonomy;
- human authority;
- controls;
- monitoring;
- suspension triggers.

The risk profile does not itself grant authority.

---

## 26. Risk Profile Review Triggers

The profile should be reviewed following:

- new mission;
- new use case;
- material system change;
- model update;
- new operational environment;
- increased autonomy;
- significant incident;
- new threat;
- significant data change;
- critical dependency change;
- evidence degradation;
- policy or legal change.

---

## 27. Use Case Risk Record

A consequential use case should maintain a record containing:

- use case identification;
- mission;
- consequence;
- autonomy;
- mission criticality;
- operational environment;
- human control;
- information risks;
- security risks;
- loss-of-control risks;
- reliability risks;
- uncertainty;
- availability;
- supply-chain dependencies;
- foreseeable misuse;
- risk treatments;
- residual risk;
- risk acceptance authority;
- escalation conditions;
- review triggers;
- linked evidence.

---

## 28. Minimum Use Case Risk Requirements

Before progressing to operational assurance, a consequential use case should have:

1. Identified major consequences of failure.
2. Defined the intended autonomy.
3. Assessed mission criticality.
4. Defined the relevant operational environment.
5. Assessed meaningful human control.
6. Identified information and data risks.
7. Identified security risks.
8. Assessed loss-of-control risk where applicable.
9. Identified reliability and availability risks.
10. Identified critical dependencies.
11. Considered foreseeable misuse.
12. Defined risk treatments.
13. Identified residual risk.
14. Identified the appropriate risk acceptance authority.
15. Defined review and escalation triggers.

---

## 29. Relationship With D-AIGAAF

This module connects directly with:

- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `03 Risk & Autonomy`
- `06 AI Security`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

It extends the Golden Thread:

**Mission → Use Case → Context → Constraints → Risk → Controls → Testing → Evidence → Assurance → Authority**

---

## 30. Summary

The Use Case Risk Profile provides the bridge between operational purpose and formal risk governance.

It makes visible the factors that determine whether an AI capability can be safely and appropriately employed:

**Consequence + Autonomy + Mission Criticality + Environment + Human Control + Information + Security + Uncertainty**

The central principle is:

> **Risk must be assessed against what the AI is actually being asked to do, under the conditions in which it will actually operate.**

A technically capable system is not automatically a low-risk system, and a low-risk system in one use case may become high-risk when its mission, environment, autonomy or human-control conditions change.
