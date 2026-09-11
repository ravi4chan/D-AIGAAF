# 02-Mission and Use Case Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 02 — Mission & Use Case**.

These templates establish the operational purpose and boundaries of an AI capability before risk, assurance and authorisation decisions are made.

The central principle is:

> **An AI capability cannot be adequately governed without first defining what mission it is intended to support, what decision or action it influences, under what conditions it will operate, and what outcomes are acceptable.**

The templates support:

- mission definition;
- use-case definition;
- operational context;
- mission constraints;
- consequence assessment;
- success criteria;
- use-case registration;
- operational scenarios;
- decision context;
- operational boundaries;
- approval;
- threat context;
- assumptions;
- dependencies;
- exit criteria.

---

# 2. Template Set

The recommended Mission & Use Case template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-02-001 | Mission Definition |
| D-AIGAAF-T-02-002 | AI Use Case Definition |
| D-AIGAAF-T-02-003 | Operational Context Assessment |
| D-AIGAAF-T-02-004 | Mission Constraints Record |
| D-AIGAAF-T-02-005 | Use Case Risk Profile |
| D-AIGAAF-T-02-006 | Mission Success Criteria |
| D-AIGAAF-T-02-007 | AI Use Case Register |
| D-AIGAAF-T-02-008 | Operational Scenario Record |
| D-AIGAAF-T-02-009 | Mission Decision Context |
| D-AIGAAF-T-02-010 | Operational Boundaries Record |
| D-AIGAAF-T-02-011 | Use Case Approval Record |
| D-AIGAAF-T-02-012 | Mission Threat Context |
| D-AIGAAF-T-02-013 | Operational Assumptions Register |
| D-AIGAAF-T-02-014 | Mission Dependencies Register |
| D-AIGAAF-T-02-015 | Use Case Exit Criteria Record |

---

# 3. Template 02-001 — Mission Definition

## Purpose

Defines the mission that the AI capability is intended to support.

## Required Fields

### Mission Identity

- Mission ID
- Mission name
- Mission owner
- Organisation
- Version
- Date
- Classification

### Mission Purpose

- mission objective;
- operational problem;
- desired outcome;
- affected operational function.

### Operational Context

Record:

- force context;
- geographic context;
- temporal context;
- operational environment;
- relevant actors;
- information environment.

### AI Role

Describe:

- what AI does;
- what AI does not do;
- decisions influenced;
- actions potentially influenced;
- human responsibilities.

### Consequences

Identify potential consequences involving:

- human life;
- force protection;
- civilians;
- property;
- mission success;
- security;
- sovereignty;
- reputation;
- legal obligations.

### Approval

- mission owner;
- approving authority;
- conditions;
- review date.

---

# 4. Template 02-002 — AI Use Case Definition

## Purpose

Defines the specific AI use case within the approved mission.

## Required Fields

- Use Case ID
- Mission ID
- Use Case Name
- AI capability
- Intended users
- Intended beneficiaries
- Intended outputs
- Inputs
- Decision/action influenced
- Operational setting
- Expected frequency
- Autonomy level
- Human role
- Prohibited uses
- Success criteria
- Exit criteria

## AI Function

Clearly state whether the AI:

- observes;
- classifies;
- detects;
- predicts;
- recommends;
- prioritises;
- plans;
- controls;
- initiates action.

The description should reflect actual system behaviour rather than marketing terminology.

---

# 5. Template 02-003 — Operational Context Assessment

## Purpose

Documents the environment in which the use case is expected to operate.

## Context Dimensions

### Physical

- terrain;
- weather;
- visibility;
- mobility;
- infrastructure.

### Information

- data availability;
- data quality;
- latency;
- uncertainty;
- source reliability.

### Communications

- connected;
- intermittent;
- degraded;
- disconnected.

### Adversarial

- deception;
- spoofing;
- jamming;
- cyber attack;
- manipulation;
- hostile observation.

### Human

- operator workload;
- competence;
- fatigue;
- command structure;
- time pressure.

### Operational

- mission tempo;
- consequence of delay;
- consequence of error;
- rules/constraints;
- escalation requirements.

---

# 6. Template 02-004 — Mission Constraints Record

## Purpose

Records constraints within which the AI use case may operate.

## Constraint Categories

### Mission

- mission objectives;
- prohibited activities;
- operational priorities.

### Legal / Policy

- applicable law;
- rules;
- directives;
- policy constraints.

### Technical

- system limitations;
- connectivity;
- compute;
- sensor limitations;
- interface constraints.

### Human

- supervision;
- intervention;
- competence;
- workload.

### Security

- information restrictions;
- adversarial conditions;
- cyber constraints.

### Environmental

- terrain;
- weather;
- electromagnetic conditions;
- infrastructure.

### Autonomy

- maximum autonomy;
- transition conditions;
- prohibited autonomy.

Every material constraint should have an owner and a verification method where practical.

---

# 7. Template 02-005 — Use Case Risk Profile

## Purpose

Provides an initial mission-specific risk profile.

This is not a replacement for the formal risk assessment in Module 03.

## Required Fields

- Use Case ID
- Hazard
- Threat
- Failure mode
- Consequence
- Likelihood
- Exposure
- Detectability
- Existing safeguards
- Initial risk
- Key uncertainty
- Risk owner
- Escalation requirement

## Consequence Categories

Consider:

- death or injury;
- civilian harm;
- mission failure;
- fratricide;
- infrastructure damage;
- information compromise;
- loss of control;
- strategic consequences.

---

# 8. Template 02-006 — Mission Success Criteria

## Purpose

Defines how mission effectiveness will be judged.

Success criteria should be measurable where practical.

## Categories

### Mission Effectiveness

- accuracy;
- timeliness;
- coverage;
- availability;
- mission outcome.

### Safety

- unacceptable events;
- intervention performance;
- safe-state performance.

### Human

- operator understanding;
- workload;
- decision quality;
- intervention effectiveness.

### Security

- resilience;
- adversarial performance;
- compromise tolerance.

### Operational

- performance in realistic environments;
- degraded operation;
- communication loss;
- environmental variation.

### Governance

- compliance with conditions;
- traceability;
- assurance requirements.

Success criteria should be linked to TEVV requirements.

---

# 9. Template 02-007 — AI Use Case Register

## Purpose

Provides a controlled inventory of approved and proposed AI use cases.

## Required Fields

- Use Case ID
- Mission
- Capability
- Owner
- Lifecycle status
- Risk category
- Autonomy level
- Operational environment
- Authorisation status
- Security status
- TEVV status
- Assurance status
- Current deployment status
- Review date

## Status Options

- Proposed;
- Under Assessment;
- Approved for Development;
- Under Development;
- Under TEVV;
- Authorised;
- Operational;
- Suspended;
- Retired.

A capability should not be considered operationally authorised merely because it appears in the register.

---

# 10. Template 02-008 — Operational Scenario Record

## Purpose

Defines representative and stress scenarios for the AI use case.

## Scenario Fields

- Scenario ID
- Mission
- Use case
- Environment
- Starting conditions
- AI state
- Human state
- Information state
- Communications state
- Threat conditions
- Expected AI behaviour
- Expected human behaviour
- Decision points
- Intervention points
- Failure conditions
- Safe-state expectation
- Success criteria

## Scenario Categories

Include, where applicable:

- normal;
- edge case;
- degraded;
- disconnected;
- adversarial;
- high-tempo;
- unexpected input;
- loss of sensor;
- loss of communications;
- human intervention;
- AI failure;
- recovery.

Scenarios should feed TEVV and operational authorisation.

---

# 11. Template 02-009 — Mission Decision Context

## Purpose

Defines the decision environment surrounding AI outputs.

## Required Fields

### Decision

- Decision ID
- Decision type
- Consequence
- Time available
- Decision authority

### AI Contribution

- AI output;
- confidence/uncertainty;
- evidence;
- limitations;
- recommendation;
- alternative outputs.

### Human Context

- operator competence;
- situational awareness;
- workload;
- available information;
- ability to challenge AI;
- ability to intervene.

### Decision Conditions

- minimum information;
- prohibited conditions;
- escalation conditions;
- intervention threshold.

The template should make clear whether AI is:

- informational;
- advisory;
- decision-supporting;
- action-enabling;
- action-executing.

---

# 12. Template 02-010 — Operational Boundaries Record

## Purpose

Defines the explicit limits within which the AI capability may operate.

## Boundary Categories

### Geographic

- authorised area;
- excluded area;
- boundary enforcement.

### Temporal

- authorised period;
- expiry;
- time-dependent restrictions.

### Mission

- approved mission;
- prohibited missions;
- mission transition rules.

### Functional

- permitted functions;
- prohibited functions;
- output limitations.

### Autonomy

- approved autonomy level;
- maximum autonomy;
- transition conditions.

### Human Authority

- supervising authority;
- intervention authority;
- override authority;
- suspension authority.

### Environmental

- permitted conditions;
- prohibited conditions;
- degraded-operation limits.

Boundaries should be technically enforceable where feasible and otherwise supported by procedural controls.

---

# 13. Template 02-011 — Use Case Approval Record

## Purpose

Records the decision to approve a use case for the next defined stage.

## Required Sections

### Proposal

- use case;
- mission;
- intended benefit;
- operational role.

### Assessment

- risk;
- legal/policy;
- security;
- data;
- human factors;
- environment;
- assurance.

### Decision

- approved;
- approved with conditions;
- deferred;
- rejected.

### Conditions

Record:

- restrictions;
- required controls;
- required testing;
- autonomy limitations;
- review triggers.

### Authority

- decision maker;
- authority basis;
- date;
- review date.

Approval for development must not be confused with operational authorisation.

---

# 14. Template 02-012 — Mission Threat Context

## Purpose

Records threats that may affect the mission or AI capability.

## Threat Categories

- adversary;
- cyber;
- deception;
- spoofing;
- data poisoning;
- sensor manipulation;
- communication disruption;
- electromagnetic interference;
- insider;
- supply chain;
- environmental;
- AI-specific threats.

## Required Fields

- Threat ID
- Threat actor/source
- Threat description
- Target
- Mechanism
- Likelihood
- Consequence
- Indicators
- Existing controls
- Residual concern
- Related risk
- Monitoring requirement

Threat context should feed Modules 03, 06, 10, 13 and 14.

---

# 15. Template 02-013 — Operational Assumptions Register

## Purpose

Records assumptions on which mission and use-case decisions depend.

## Required Fields

- Assumption ID
- Assumption
- Basis
- Owner
- Importance
- Dependency
- Verification method
- Verification status
- Consequence if false
- Related risk
- Review trigger

Examples:

- communications remain available;
- sensor quality remains within limits;
- operator is available;
- training data remains representative;
- environmental conditions remain within tested bounds.

## Critical Principle

An assumption that materially affects safety or mission success should not remain unverified indefinitely.

---

# 16. Template 02-014 — Mission Dependencies Register

## Purpose

Identifies dependencies required for successful AI employment.

## Dependency Categories

### Technical

- sensors;
- compute;
- software;
- models;
- interfaces.

### Data

- data sources;
- data feeds;
- external repositories.

### Communications

- networks;
- links;
- timing;
- positioning.

### Human

- operators;
- maintainers;
- technical specialists;
- command authorities.

### External

- suppliers;
- cloud services;
- external AI models;
- partner systems.

### Infrastructure

- power;
- facilities;
- environmental support.

## Required Fields

- Dependency ID
- Dependency
- Owner
- Criticality
- Failure consequence
- Alternative
- Recovery mechanism
- Monitoring requirement
- Related risk
- Review date

---

# 17. Template 02-015 — Use Case Exit Criteria Record

## Purpose

Defines conditions under which a use case should cease, be suspended, be redesigned or transition to another lifecycle state.

## Exit Conditions

Examples include:

- mission objective completed;
- capability no longer required;
- unacceptable residual risk;
- repeated performance failure;
- loss of assurance;
- security compromise;
- operating environment outside authorised conditions;
- loss of required human authority;
- technology obsolescence;
- legal/policy change;
- unacceptable dependency;
- inability to maintain required evidence.

## Decision

- continue;
- restrict;
- suspend;
- redesign;
- retire.

## Authority

Record:

- decision maker;
- evidence;
- rationale;
- conditions;
- follow-up actions.

---

# 18. Mission-to-Use-Case Traceability

Every significant AI use case should be traceable:

**Mission**
→ **Operational Problem**
→ **Use Case**
→ **AI Function**
→ **Decision / Action**
→ **Consequence**
→ **Risk**
→ **Required Controls**
→ **TEVV**
→ **Authorisation**
→ **Employment**

This prevents technology from becoming the starting point for governance.

---

# 19. Consequence-First Definition

Use-case templates should identify consequences before determining acceptable autonomy.

The sequence should be:

**What can the AI do?**
→ **What decision/action can it influence?**
→ **What can happen if it is wrong?**
→ **Who or what can be affected?**
→ **How quickly can harm occur?**
→ **Can a human detect and intervene?**
→ **What autonomy is therefore acceptable?**

This is especially important where AI can influence actions involving human life or significant property.

---

# 20. Mission Context and Autonomy

Autonomy should never be selected solely because a system is technically capable of it.

The appropriate autonomy level should consider:

- mission consequence;
- time available for human decision;
- reliability;
- uncertainty;
- environment;
- adversarial conditions;
- human ability to supervise;
- intervention latency;
- failure consequences.

The governing relationship is:

**Mission Consequence + Operational Context + AI Capability + Human Authority**
→ **Acceptable Autonomy**

---

# 21. Degraded and Disconnected Operations

Where applicable, mission templates must explicitly address:

- loss of communications;
- loss of external data;
- degraded sensors;
- degraded positioning;
- loss of cloud/external services;
- limited computing;
- delayed human communication.

The use case should specify whether it:

- continues;
- transitions to restricted mode;
- requires human confirmation;
- enters a safe state;
- terminates.

This decision should be tested before operational authorisation where the condition is foreseeable.

---

# 22. Human Authority

Mission templates should identify the human responsible for consequential decisions.

Where AI influences a consequential action, record:

- who receives the AI output;
- who interprets it;
- who may accept/reject it;
- who may intervene;
- who may suspend the capability;
- who accepts relevant residual risk;
- who has final operational authority.

Human authority must be explicit rather than inferred from organisational hierarchy.

---

# 23. Uncertainty and AI Outputs

Use-case definitions should identify what uncertainty matters operationally.

Where relevant, capture:

- confidence;
- uncertainty;
- known limitations;
- data limitations;
- model limitations;
- out-of-distribution conditions;
- ambiguity;
- unavailable information.

AI outputs should not be treated as authoritative merely because they are expressed with numerical confidence.

---

# 24. Relationship to TEVV

Mission templates should provide the foundation for TEVV.

The relationship is:

**Mission Success Criteria**
→ **Operational Scenarios**
→ **Performance Requirements**
→ **Test Conditions**
→ **Evaluation**
→ **Validation**
→ **Operational Acceptance**

If mission conditions are poorly defined, TEVV may demonstrate technical performance without demonstrating mission suitability.

---

# 25. Relationship to Operational Authorisation

The Mission & Use Case package should provide inputs to Module 11.

The authorisation authority should be able to determine:

- what mission is authorised;
- what use case is authorised;
- where it may operate;
- under what conditions;
- at what autonomy;
- under whose authority;
- with what restrictions.

The core authorisation object remains:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

---

# 26. Mission Package Minimum Evidence

For a consequential AI use case, the minimum package should normally contain:

- mission definition;
- use-case definition;
- operational context;
- constraints;
- risk profile;
- success criteria;
- scenarios;
- decision context;
- operational boundaries;
- approval;
- threat context;
- assumptions;
- dependencies;
- exit criteria.

Additional documentation should be required according to risk and mission consequence.

---

# 27. Quality Review

Before a use case proceeds, reviewers should ask:

1. Is the mission clearly defined?
2. Is the operational problem genuine?
3. Is AI actually necessary or beneficial?
4. Is the AI role precisely defined?
5. Are consequential decisions/actions identified?
6. Are affected people and assets identified?
7. Are operating conditions realistic?
8. Are assumptions explicit?
9. Are dependencies understood?
10. Are degraded conditions considered?
11. Is human authority clear?
12. Is autonomy justified?
13. Can success be measured?
14. Can failure be detected?
15. Are exit conditions defined?

---

# 28. Anti-Pattern — Technology-First Governance

D-AIGAAF should avoid:

**Available AI Technology**
→ **Find a Mission**

The preferred sequence is:

**Mission Need**
→ **Operational Problem**
→ **Use Case**
→ **Need for AI**
→ **AI Capability**
→ **Risk**
→ **Controls**
→ **TEVV**
→ **Authorisation**

This reduces the risk of deploying AI merely because the technology is available.

---

# 29. Anti-Pattern — Capability Equals Permission

The ability of an AI system to perform an action does not establish permission to perform it.

Therefore:

**Technical Capability ≠ Operational Authority**

and:

**Model Performance ≠ Mission Authorisation**

and:

**Successful Testing ≠ Permission for Operational Employment**

---

# 30. Final Mission & Use Case Principle

The Mission & Use Case templates establish the operational meaning of an AI capability.

The governing principle is:

> **Govern the AI capability in the context in which its outputs and actions can create consequences—not in isolation from the mission, people, environment and authority structure in which it operates.**

The complete chain is:

**Mission Need**
→ **Operational Problem**
→ **Use Case**
→ **Decision / Action**
→ **Consequence**
→ **Risk**
→ **Requirements**
→ **Controls**
→ **TEVV**
→ **Assurance**
→ **Human Authority**
→ **Operational Authorisation**
→ **Employment**
→ **Monitoring**

A well-defined use case is therefore the foundation on which the remainder of D-AIGAAF can operate.
