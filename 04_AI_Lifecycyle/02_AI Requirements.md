# AI Requirements

## Summary

AI Requirements define what a defence AI capability must achieve, the conditions under which it must achieve it, the constraints within which it may operate, and the evidence required to demonstrate compliance.

D-AIGAAF treats requirements as the bridge between **Mission Need** and **TEVV, Assurance and Operational Authorisation**.

A requirement should not merely describe what the system should do. For consequential AI, it should also define:

- where it may operate;
- how well it must perform;
- what it must not do;
- what human authority must remain;
- how uncertainty must be communicated;
- how failure and degradation must be handled;
- what evidence is required;
- how changes affect the requirement and assurance basis.

The core chain is:

**Mission Need → Use Case → Requirements → Design → Controls → TEVV → Evidence → Assurance → Operational Authorisation**

---

## 1. Purpose

The AI Requirements process establishes a controlled and traceable set of requirements for an AI-enabled defence capability.

It ensures that requirements:

- originate from an identified mission need;
- reflect the operational context;
- account for risk and autonomy;
- define measurable or assessable outcomes;
- establish operational boundaries;
- support human authority;
- address security and information integrity;
- can be tested and evaluated;
- remain traceable throughout the lifecycle.

---

## 2. Core Principle

Requirements must describe the **capability that must be demonstrated**, not merely the technology that is intended to be built.

A requirement such as:

> "The AI shall use machine learning to support commanders."

is insufficient because it does not define:

- the mission need;
- the decision context;
- expected performance;
- operational conditions;
- human authority;
- limitations;
- uncertainty;
- failure behaviour;
- evidence required for acceptance.

A stronger requirement defines the expected operational outcome and the conditions under which that outcome must be demonstrated.

---

## 3. Requirements Hierarchy

D-AIGAAF uses a requirements hierarchy to maintain traceability.

### Level 1 — Strategic Requirements

Define the strategic purpose and capability objective.

Examples:

- address an identified capability gap;
- improve decision support;
- improve situational awareness;
- reduce operational burden;
- improve logistics efficiency.

### Level 2 — Mission Requirements

Define what the capability must contribute to a specific mission.

Examples:

- provide timely information;
- identify relevant patterns;
- support a defined decision;
- operate within specified operational constraints.

### Level 3 — System Requirements

Define what the integrated AI-enabled system must do.

Examples:

- functional behaviour;
- performance;
- interfaces;
- availability;
- security;
- logging;
- human control.

### Level 4 — AI/Model Requirements

Define requirements specifically applicable to AI or model behaviour.

Examples:

- accuracy;
- robustness;
- uncertainty;
- explainability where required;
- adaptation constraints;
- output consistency;
- model integrity.

### Level 5 — Operational Requirements

Define conditions for actual employment.

Examples:

- environment;
- communications;
- human authority;
- autonomy;
- operating envelope;
- fail-safe behaviour;
- degraded modes.

### Level 6 — Assurance Requirements

Define the evidence needed to establish that requirements have been satisfied.

Examples:

- test coverage;
- evaluation scenarios;
- representative environments;
- adversarial testing;
- human-control assessment;
- autonomy assessment.

---

## 4. Requirements Categories

A complete AI requirements baseline should consider, as applicable:

1. Mission
2. Functional
3. Performance
4. Reliability
5. Robustness
6. Operational Environment
7. Human-AI Interaction
8. Human Authority
9. Autonomy
10. Safety
11. Security
12. Information Integrity
13. Data
14. Interoperability
15. Resilience
16. Availability
17. Auditability
18. Explainability and Uncertainty
19. Fail-Safe and Recovery
20. Configuration and Change
21. Supply Chain
22. Legal and Policy
23. Assurance and TEVV
24. Sustainment
25. Retirement and Decommissioning

Not every capability requires identical requirements. Requirements should be proportionate to mission consequence, risk and autonomy.

---

## 5. Mission Requirements

Mission requirements define the operational problem the AI capability is intended to address.

They should establish:

- mission objective;
- intended users;
- decision context;
- expected contribution;
- mission criticality;
- acceptable performance;
- operational constraints;
- consequences of failure;
- relationship to human decision making.

The mission requirement should remain traceable to the original Mission Need.

---

## 6. Functional Requirements

Functional requirements define what the capability must do.

Examples include:

- process specified information;
- identify specified patterns;
- generate recommendations;
- classify information;
- support prioritisation;
- detect anomalies;
- provide alerts;
- support planning;
- provide logistics forecasts.

Functional requirements should avoid prescribing a particular technology unless that technology is itself necessary to meet the requirement.

---

## 7. Performance Requirements

Performance requirements define how well the capability must perform.

They may address:

- accuracy;
- precision;
- recall;
- false-positive rate;
- false-negative rate;
- latency;
- throughput;
- availability;
- reliability;
- detection performance;
- classification performance;
- decision-support usefulness.

Performance requirements should specify the relevant conditions under which performance must be demonstrated.

A performance number without its test conditions can be misleading.

---

## 8. Operational Environment Requirements

AI performance must be considered within the environments in which the capability may actually be used.

Requirements may address:

- terrain;
- weather;
- lighting;
- temperature;
- altitude;
- sensor variation;
- data quality;
- communications availability;
- computing limitations;
- infrastructure availability;
- adversarial conditions;
- information degradation;
- mission tempo.

The requirement should distinguish between:

**Intended Environment → Tested Environment → Assured Environment → Authorised Environment**

These should not automatically be assumed to be identical.

---

## 9. Robustness Requirements

Robustness requirements define acceptable behaviour when conditions differ from ideal operating conditions.

They may address:

- noisy data;
- incomplete data;
- sensor degradation;
- distribution shift;
- environmental variation;
- missing inputs;
- unexpected inputs;
- degraded computing;
- intermittent communications.

The system should have defined behaviour when it cannot reliably satisfy a requirement.

This may include:

- degraded output;
- explicit uncertainty;
- request for human review;
- reduced autonomy;
- safe state;
- temporary suspension.

---

## 10. Uncertainty Requirements

AI systems should not be required merely to produce answers.

They should also be required to communicate when confidence is insufficient.

Requirements may specify:

- uncertainty representation;
- confidence information;
- threshold behaviour;
- abstention;
- escalation;
- human review;
- handling of ambiguous inputs;
- distinction between known and unknown conditions.

The objective is to reduce the risk of confident but incorrect outputs.

Where uncertainty cannot be reliably quantified, the limitation should be explicitly documented and incorporated into assurance and operational constraints.

---

## 11. Human Authority Requirements

Human authority requirements define where human judgement, approval or intervention is mandatory.

They should establish:

- who may make the decision;
- what information the human must receive;
- when human approval is required;
- intervention time;
- override capability;
- escalation;
- accountability;
- required competence.

The core distinction is:

**AI Output ≠ Human Decision ≠ Command Authority**

An AI recommendation must not be treated as command authority merely because it is technically generated or operationally useful.

---

## 12. Autonomy Requirements

Autonomy requirements should define:

- intended autonomy;
- permitted actions;
- prohibited actions;
- human approval requirements;
- autonomy boundaries;
- autonomy transitions;
- adaptation limits;
- escalation limits;
- recovery behaviour.

Technical capability and authorised autonomy must remain separate.

The lifecycle relationship is:

**Technical Capability → Actual Behaviour → Assessed Autonomy → Assured Autonomy → Authorised Autonomy**

Requirements should therefore be written so that autonomy can be tested rather than inferred from system design descriptions.

---

## 13. Safety Requirements

Safety requirements should address foreseeable consequences of:

- incorrect output;
- unexpected behaviour;
- system failure;
- loss of control;
- unsafe autonomy transition;
- human misunderstanding;
- degraded operation;
- interface failure;
- dependency failure.

Where appropriate, requirements should define:

- protective states;
- intervention mechanisms;
- recovery procedures;
- fail-safe behaviour;
- degraded modes;
- safe shutdown.

Fail-safe mechanisms should be treated as protective controls and not as a substitute for prevention, monitoring or human control.

---

## 14. Security Requirements

Security requirements should address the AI capability as a complete system.

They may include:

- model integrity;
- software integrity;
- hardware integrity;
- authentication;
- access control;
- interface security;
- data protection;
- dependency security;
- supply-chain provenance;
- update security;
- logging;
- monitoring;
- vulnerability management.

Requirements should consider both external compromise and unintended or uncontrolled system behaviour.

---

## 15. Information Integrity Requirements

AI decisions depend on the information presented to the system.

Requirements may therefore address:

- data provenance;
- source reliability;
- data integrity;
- data freshness;
- conflicting information;
- missing information;
- manipulated information;
- sensor integrity;
- information confidence.

The system should not silently treat uncertain or compromised information as reliable.

---

## 16. Data Requirements

Data requirements should address, where applicable:

- source;
- provenance;
- quality;
- relevance;
- representativeness;
- completeness;
- timeliness;
- integrity;
- access controls;
- retention;
- permitted use;
- privacy and legal constraints;
- versioning;
- change management.

For machine-learning systems, requirements should also consider the relationship between training, validation, testing and operational data.

---

## 17. Interoperability Requirements

Where AI operates within a larger defence ecosystem, requirements should address interoperability with:

- sensors;
- information systems;
- command systems;
- communications;
- logistics systems;
- identity and access systems;
- external services;
- coalition or partner systems where applicable.

Interoperability requirements should address not only data exchange but also:

- meaning;
- timing;
- integrity;
- authority;
- failure behaviour.

---

## 18. Resilience and Availability Requirements

Requirements should define expected behaviour when supporting infrastructure is degraded.

Consider:

- loss of communications;
- reduced bandwidth;
- computing limitations;
- sensor loss;
- power interruption;
- dependency failure;
- infrastructure disruption.

The system should have defined behaviour for:

**Normal → Degraded → Restricted → Safe State → Recovery**

Where the mission permits continued operation under degraded conditions, those conditions should be explicitly tested and authorised.

---

## 19. Auditability Requirements

Consequential AI systems should generate sufficient records to reconstruct material decisions and events.

Requirements may address:

- AI output;
- relevant input information;
- system version;
- model version;
- configuration;
- time;
- user/operator;
- human decision;
- authorised action;
- autonomy state;
- override;
- exception;
- incident;
- system status.

Auditability requirements should balance operational utility, security, privacy, data protection and retention obligations.

---

## 20. Fail-Safe and Recovery Requirements

Requirements should define how the system behaves when normal operation cannot be maintained.

They should address:

- fault detection;
- loss of control;
- unexpected behaviour;
- communications failure;
- information degradation;
- security events;
- autonomy boundary violations;
- recovery;
- human intervention;
- safe state.

A conceptual response chain is:

**Detect → Assess → Contain → Reduce Autonomy → Restore Human Control → Safe State/Fail-Safe → Recover → Reassess**

Emergency protective action may be pre-authorised where delay could create unacceptable harm. Such authority should be narrow, clearly defined and subsequently recorded and reviewed.

---

## 21. Supply-Chain Requirements

Requirements should address provenance and control of critical components.

Consider:

- model origin;
- developer identity;
- software components;
- hardware components;
- third-party libraries;
- external services;
- data sources;
- dependencies;
- update mechanisms;
- supplier access;
- vulnerability disclosure;
- component traceability.

Where a dependency can materially alter system behaviour, it should form part of the assurance and configuration baseline.

---

## 22. Legal and Policy Requirements

AI requirements must incorporate applicable:

- law;
- regulation;
- defence policy;
- organisational policy;
- rules and directives;
- information-handling requirements;
- procurement requirements;
- applicable international obligations.

Legal and policy requirements should be translated into testable or reviewable controls wherever practicable.

---

## 23. Requirements for Testing and Evaluation

Every consequential requirement should have a corresponding means of verification, validation, testing or evaluation.

A requirements record should identify:

| Requirement | Verification / Evidence Method |
|---|---|
| Functional behaviour | Test |
| Performance | Quantitative evaluation |
| Robustness | Scenario testing |
| Security | Security assessment / testing |
| Human control | Human-control assessment |
| Autonomy | Autonomy assessment |
| Operational environment | Representative environment testing |
| Mission effectiveness | Mission-level evaluation |
| Fail-safe | Failure and recovery testing |
| Auditability | Record inspection / test |

A requirement that cannot be meaningfully assessed should be reviewed.

---

## 24. Requirements Traceability

Requirements should remain traceable across the lifecycle.

The minimum conceptual chain is:

**Mission Need → Requirement → Design Element → Control → Test → Evidence → Assurance Claim → Authorisation Condition**

Traceability should allow an assessor to determine:

- why a requirement exists;
- how it was implemented;
- how it was tested;
- what evidence supports it;
- whether the requirement remains satisfied;
- what happens if the requirement changes.

---

## 25. Requirements Baseline

A controlled requirements baseline should identify:

- requirement identifier;
- requirement statement;
- source;
- rationale;
- priority;
- applicability;
- acceptance criteria;
- verification method;
- responsible owner;
- dependencies;
- related risks;
- related controls;
- related autonomy constraints;
- status;
- version;
- change history.

The baseline should be configuration controlled.

---

## 26. Requirement Quality

A useful AI requirement should be:

- clear;
- necessary;
- unambiguous;
- feasible;
- measurable or assessable;
- testable;
- traceable;
- consistent;
- bounded;
- risk-informed.

Requirements should avoid unnecessary technology-specific language when an outcome-based requirement is more appropriate.

---

## 27. Requirement Prioritisation

Requirements may be prioritised according to:

- mission criticality;
- consequence;
- safety;
- security;
- human authority;
- autonomy;
- operational dependency;
- legal necessity;
- interoperability;
- assurance importance.

High-consequence requirements should receive proportionate verification and independent challenge.

---

## 28. Requirements and Risk

Requirements should reflect identified risks.

The relationship is:

**Risk → Requirement → Control → Test → Evidence**

For example, if a risk involves loss of human control, requirements may need to specify:

- intervention time;
- override capability;
- human awareness;
- autonomy limits;
- transition behaviour;
- monitoring;
- recovery.

Requirements should therefore be derived from risk rather than developed independently of it.

---

## 29. Requirements and Operational Authorisation

Operational authorisation should be based on satisfaction of the requirements relevant to the proposed employment.

Not all requirements necessarily need to be fully satisfied for every lifecycle state. A capability may be:

- under development;
- under test;
- conditionally authorised;
- restricted;
- operationally authorised.

Any requirement deviation should be:

- documented;
- risk assessed;
- subject to appropriate authority;
- reflected in operational conditions;
- monitored where relevant.

---

## 30. Requirements Change Management

Requirements may change because of:

- mission changes;
- new threats;
- operational lessons;
- technology changes;
- new environments;
- incidents;
- legal or policy changes;
- changes in risk;
- changes in autonomy;
- changes in human-control arrangements.

Requirement changes should be assessed for effects on:

- design;
- testing;
- evidence;
- assurance;
- risk;
- operational authorisation.

Material requirement changes may require revalidation or reauthorisation.

---

## 31. Requirements Failure Modes

Common failures include:

- technology-driven requirements;
- vague mission objectives;
- requirements that cannot be tested;
- performance requirements without operating conditions;
- ignoring uncertainty;
- failing to define prohibited behaviour;
- treating autonomy as an implementation detail;
- omitting human authority;
- ignoring degraded environments;
- ignoring communications loss;
- failing to define failure and recovery behaviour;
- weak traceability;
- uncontrolled requirement changes;
- accepting deviations without risk assessment;
- allowing technical acceptance to substitute for operational requirements.

---

## 32. AI Requirements Record

A requirements record should include, as applicable:

| Field | Description |
|---|---|
| Requirement ID | Unique identifier |
| Requirement | Controlled requirement statement |
| Source | Mission, policy, risk, legal or other source |
| Rationale | Why the requirement exists |
| Category | Functional, performance, safety, etc. |
| Priority | Relative importance |
| Acceptance Criteria | Conditions for satisfaction |
| Verification Method | Test, inspection, analysis, evaluation, etc. |
| Related Risk | Risk addressed |
| Related Control | Control implementing requirement |
| Autonomy Relevance | Effect on autonomy |
| Human Authority | Required human role |
| Environment | Applicable conditions |
| Dependencies | Relevant dependencies |
| Owner | Responsible organisation/person |
| Status | Current lifecycle status |
| Version | Baseline/version |
| Change History | Requirement evolution |

---

## 33. Core Rules

1. **Every requirement should trace to a legitimate need, obligation or risk.**
2. **Requirements must describe outcomes and conditions, not merely technology.**
3. **Consequential requirements must be testable or otherwise objectively assessable.**
4. **Performance requirements must specify relevant operating conditions.**
5. **Human authority must be explicitly represented where consequential decisions are involved.**
6. **Autonomy requirements must define permitted, conditional and prohibited behaviour.**
7. **Uncertainty and degraded behaviour should be addressed explicitly.**
8. **Security and information integrity are lifecycle requirements, not post-development additions.**
9. **Requirements must remain configuration controlled.**
10. **Requirement changes must be assessed for effects on risk, assurance and authority.**
11. **A requirement deviation does not automatically become acceptable merely because the system works.**
12. **Operational authorisation should be traceable to the requirements and evidence supporting it.**

---

## 34. Golden Thread

AI Requirements maintain the Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The requirements baseline is the point at which mission intent is converted into criteria that can subsequently be tested, evidenced, assured and authorised.

---

## 35. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 Mission & Use Case** — provides mission context and use-case boundaries.
- **03 Risk & Autonomy** — provides risk, autonomy and human-control considerations.
- **04 AI Lifecycle** — governs requirements throughout the lifecycle.
- **05 Data & Information** — provides data and information requirements.
- **06 AI Security** — provides security and integrity requirements.
- **07 Supply Chain & Sovereignty** — provides provenance and dependency requirements.
- **08 Human Authority** — defines human decision and authority requirements.
- **09 TEVV** — verifies and evaluates requirements.
- **10 Operational Environment** — establishes environmental requirements.
- **11 Operational Authorisation** — uses requirements and evidence to define authorised employment.
- **13 Continuous Assurance** — monitors continued satisfaction of material requirements.
- **15 Change & Reauthorisation** — assesses requirement changes and their authority implications.
- **16 Audit & Evidence** — preserves requirement traceability.
- **20 Templates** — provides controlled records and forms.

---

## 36. Summary Model

```text
Mission Need
      ↓
Use Case
      ↓
Risk & Autonomy
      ↓
Requirements
      ↓
Design / Acquisition
      ↓
Controls
      ↓
TEVV
      ↓
Evidence
      ↓
Assurance
      ↓
Risk Acceptance
      ↓
Operational Authorisation
      ↓
Employment
      ↓
Monitoring
      ↓
Requirement / Mission / Risk Change
      ↓
Revalidation / Reauthorisation
```

Requirements provide the controlled bridge between **what the mission needs** and **what must be demonstrated before the capability receives operational authority**.
