# Use Case Definition

## 1. Purpose

A Use Case Definition translates the broader Mission Need into a specific, bounded description of how an AI capability is intended to be used.

It defines the operational situation, users, inputs, outputs, human decisions, system actions, constraints and expected outcomes.

A clear use case is necessary to determine whether the AI capability has been:

- appropriately designed;
- adequately tested;
- sufficiently assured;
- properly authorised;
- employed within its approved boundaries.

---

## 2. Core Principle

The governing sequence is:

**Mission → Use Case → Requirements → Risk → Assurance → Authority**

The same AI capability may support multiple use cases.

Each materially different use case should be assessed independently because changes in mission, environment, users, autonomy or consequence can change the risk and assurance requirements.

---

## 3. Use Case Identification

Each consequential use case should have a unique identifier.

A Use Case Definition should identify:

- Use Case ID;
- capability;
- mission;
- operational owner;
- intended users;
- purpose;
- status;
- version;
- date of approval or review.

---

## 4. Use Case Objective

The use case should state the specific operational objective.

It should answer:

> What is the AI expected to help a human or system accomplish?

The objective should be sufficiently specific to support requirements and mission-level evaluation.

---

## 5. Actors and Participants

The use case should identify relevant actors.

These may include:

- operational commander;
- decision-maker;
- system operator;
- analyst;
- Operational AI Advisor;
- AI system;
- connected systems;
- data providers;
- supporting technical personnel.

The use case should clearly distinguish human actors from AI-enabled functions.

---

## 6. AI Role

The use case should explicitly define the AI's role.

Examples include:

- information retrieval;
- classification;
- detection;
- prediction;
- analysis;
- recommendation;
- prioritisation;
- planning;
- control;
- autonomous execution.

The AI role should not be inferred solely from the system's technical capabilities.

---

## 7. Human Role

The use case should specify what humans are expected to do.

This may include:

- provide inputs;
- review AI outputs;
- interpret recommendations;
- approve actions;
- reject recommendations;
- modify decisions;
- supervise system behaviour;
- intervene during abnormal conditions;
- activate fail-safe procedures.

Human involvement should be described in terms of actual authority and control, not merely physical presence.

---

## 8. AI Output and Human Decision

The use case should identify the relationship between:

**AI Output → Human Assessment → Human Decision → Operational Action**

Where an AI recommendation is generated, the use case should identify:

- who receives it;
- who assesses it;
- who may accept or reject it;
- what evidence is available;
- what authority is required;
- whether the decision is recorded.

An AI recommendation does not automatically constitute an operational decision.

---

## 9. Autonomy

The use case should identify the authorised autonomy level.

A working D-AIGAAF construct is:

| Level | Description |
|---|---|
| A0 | No meaningful AI decision-making |
| A1 | Information or observation |
| A2 | Analysis or recommendation |
| A3 | Recommendation or action requiring explicit human authorisation |
| A4 | Execution of predefined actions under human supervision |
| A5 | Independent consequential decision or action |

This taxonomy is a working framework construct and should be validated against established terminology before formal implementation.

The use case should not assume that an AI capability is authorised to operate at the highest technically possible autonomy.

---

## 10. Operational Environment

The use case should identify where and under what conditions the capability will operate.

Relevant conditions may include:

- location;
- terrain;
- weather;
- visibility;
- communications;
- connectivity;
- sensor availability;
- computing resources;
- power;
- electromagnetic conditions;
- adversarial activity;
- data availability;
- human availability.

Performance claims should be tied to the environments in which they have been demonstrated.

---

## 11. Preconditions

Preconditions identify what must be true before the use case begins.

Examples include:

- required data is available;
- sensors are functioning;
- system integrity has been verified;
- authorised users are present;
- communications are available where required;
- required human authority is available;
- system configuration matches the authorised baseline;
- required safeguards are active.

Failure of a critical precondition should prevent or restrict execution where appropriate.

---

## 12. Inputs

The use case should identify relevant inputs.

Inputs may include:

- sensor data;
- imagery;
- text;
- maps;
- telemetry;
- intelligence;
- environmental information;
- operational plans;
- user instructions;
- system status;
- external data.

Input provenance, quality and integrity should be considered where they can affect operational outcomes.

---

## 13. Outputs

The use case should define expected outputs.

These may include:

- alerts;
- classifications;
- assessments;
- recommendations;
- predictions;
- prioritised information;
- plans;
- system commands;
- autonomous actions.

The use case should distinguish between informational outputs and outputs capable of directly affecting the physical or operational environment.

---

## 14. Normal Flow

The normal flow should describe the expected sequence.

A generic example is:

1. Mission requirement is identified.
2. Authorised user initiates the use case.
3. Required inputs are obtained.
4. AI processes the inputs.
5. AI produces an output or recommendation.
6. Human reviews or interprets the output where required.
7. Authorised decision-maker determines the appropriate action.
8. Action is executed.
9. Outcome is recorded where required.
10. Relevant performance and assurance information is captured.

The exact flow will depend on the use case and autonomy level.

---

## 15. Alternative Flows

The use case should identify foreseeable alternative conditions.

Examples include:

- incomplete data;
- conflicting inputs;
- unavailable sensor;
- degraded communications;
- unexpected environmental conditions;
- AI uncertainty;
- human disagreement;
- system performance degradation;
- loss of external dependency.

Each significant alternative flow should define the expected system and human response.

---

## 16. Exception and Failure Conditions

The use case should identify conditions under which normal operation should stop, degrade or escalate.

Examples include:

- unacceptable uncertainty;
- unexpected model behaviour;
- security compromise;
- loss of system integrity;
- loss of communications;
- loss of human control;
- operation outside the authorised envelope;
- critical sensor failure;
- material configuration change.

The response may include:

- controlled degradation;
- transition to a safe state;
- suspension;
- fail-safe activation;
- human intervention;
- escalation;
- incident reporting.

---

## 17. Uncertainty

The use case should define how uncertainty is presented and handled.

AI systems should not present uncertain outputs as established facts where uncertainty is operationally relevant.

Where practical, the system should communicate:

- confidence or uncertainty;
- missing information;
- conflicting information;
- known limitations;
- conditions outside demonstrated performance.

Uncertainty should become an input to human decision-making rather than being hidden.

---

## 18. Human Override

Where human override exists, the use case should specify:

- who may override;
- what may be overridden;
- when override is available;
- how override is executed;
- whether override requires confirmation;
- whether override is recorded;
- what happens after override.

For consequential systems, override mechanisms should be tested under realistic operational conditions.

---

## 19. Fail-Safe and Controlled Degradation

The use case should define expected behaviour when normal operation cannot safely continue.

Possible responses include:

- stop operation;
- revert to a safe state;
- reduce autonomy;
- transfer control to a human;
- isolate affected functions;
- continue only with restricted functionality.

Emergency protective action may be permitted under pre-authorised procedures where delay could create unacceptable harm.

---

## 20. Communications and Connectivity

The use case should explicitly identify communications dependencies.

It should state whether the capability can:

- operate with continuous connectivity;
- operate intermittently connected;
- operate offline;
- operate with degraded communications;
- continue safely following loss of connectivity.

If loss of communications changes the system's authority or behaviour, this must be reflected in the operational envelope and authorisation conditions.

---

## 21. Security and Adversarial Conditions

The use case should consider foreseeable adversarial conditions.

These may include:

- manipulated inputs;
- spoofed information;
- adversarial examples;
- malicious instructions;
- compromised data;
- compromised dependencies;
- unauthorised system access;
- attempts to manipulate system behaviour.

Security assumptions should be explicitly documented and tested where relevant.

---

## 22. Operational Boundaries

Each use case should define what the AI is **not** authorised to do.

Boundaries may include:

- missions;
- geographic areas;
- users;
- data sources;
- autonomy levels;
- actions;
- target categories;
- operating conditions;
- system interfaces;
- time periods.

A capability must not silently expand its authority because a technically possible function exists.

---

## 23. Foreseeable Misuse

The use case should identify foreseeable ways in which users or other systems might employ the capability incorrectly.

Examples include:

- using outputs outside the intended mission;
- treating recommendations as commands;
- using unsupported data;
- operating beyond tested conditions;
- bypassing required human review;
- using an outdated model;
- continuing operation after a material change;
- transferring the capability to another mission without assessment.

Controls should be established where foreseeable misuse could create material risk.

---

## 24. Success Criteria

The use case should define operational success.

Success criteria should consider:

- mission effectiveness;
- accuracy or reliability where relevant;
- timeliness;
- human decision quality;
- resilience;
- availability;
- acceptable false-positive and false-negative consequences;
- safe behaviour under abnormal conditions.

Success should not be defined solely by model-level technical metrics.

---

## 25. Evidence Requirements

The use case should identify what evidence is required to demonstrate suitability.

Evidence may include:

- laboratory testing;
- representative environment testing;
- adversarial testing;
- human factors evaluation;
- operational trials;
- security testing;
- mission-level evaluation;
- failure and recovery testing.

Evidence should be traceable to requirements and assurance claims.

---

## 26. Use Case Change

A use case should be reviewed when there is a material change to:

- mission;
- environment;
- users;
- data;
- autonomy;
- system behaviour;
- interfaces;
- dependencies;
- consequence;
- human authority.

A change to the use case may require revalidation, reauthorisation or both.

---

## 27. Use Case Record

A consequential AI capability should maintain a Use Case Record containing, as applicable:

- Use Case ID;
- mission;
- objective;
- actors;
- AI role;
- human role;
- autonomy;
- environment;
- preconditions;
- inputs;
- outputs;
- normal flow;
- alternative flows;
- failure conditions;
- uncertainty handling;
- human override;
- fail-safe;
- communications dependencies;
- security assumptions;
- operational boundaries;
- foreseeable misuse;
- success criteria;
- evidence requirements;
- version and change history.

---

## 28. Minimum Use Case Requirements

Before detailed operational assurance, a consequential use case should have:

1. A defined mission objective.
2. Identified human and AI roles.
3. Explicit autonomy.
4. Defined operational environment.
5. Defined inputs and outputs.
6. Defined normal and abnormal operating flows.
7. Defined human authority and override.
8. Defined failure and fail-safe behaviour.
9. Identified communications and critical dependencies.
10. Identified security and adversarial assumptions.
11. Defined operational boundaries.
12. Defined success criteria.
13. Defined evidence requirements.
14. A controlled version and change history.

---

## 29. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread.md`
- `01 Strategy & Governance`
- `02 Mission & Use Case/Mission_Definition.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `06 AI Security`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `12 Operational Employment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`

The use case provides the operational context required to connect mission requirements to risk, controls, testing, evidence, assurance and authority.

---

## 30. Summary

A mission explains **why** an AI capability is required.

A use case explains **how, where, by whom and under what conditions** it will be used.

The essential chain is:

**Mission → Use Case → Requirements → Risk → Controls → Testing → Evidence → Assurance → Authority**

A use case is therefore not merely a software-design document. It is an operational boundary that helps determine what the AI may do, what humans must control, what must be tested and what authority is required.
