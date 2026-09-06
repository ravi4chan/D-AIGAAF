# 22 Operational Decision and Action Traceability

## 1. Purpose

Operational decision and action traceability establishes a reliable record of how consequential decisions involving Defence AI were informed, reviewed, authorised and executed.

The purpose is not to attribute every operational decision to AI. It is to establish a reconstructable chain showing:

**Context → AI Contribution → Human Assessment → Authority → Decision → Action → Outcome**

This supports accountability, incident investigation, assurance, lessons learned, legal and policy review, and continuous improvement.

---

## 2. Core Principle

For consequential Defence AI use, the organisation should be able to determine:

- what the AI was asked to do;
- what information or inputs were available;
- what the AI produced;
- what uncertainty or limitations were communicated;
- who reviewed the output;
- who held decision authority;
- what decision was made;
- what action followed;
- what configuration and autonomy level were active;
- what conditions existed; and
- what outcome resulted.

Where complete reconstruction is technically impossible, the organisation should define proportionate traceability requirements based on consequence, autonomy, mission criticality and operational feasibility.

---

## 3. Traceability Object

Traceability should remain linked to:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

The traceability requirement should increase as the potential consequence of AI-supported decisions increases.

A low-consequence informational interaction may require limited records.

A high-consequence action should require substantially stronger traceability.

---

## 4. Decision and Action Categories

Operational activity may involve:

1. AI-generated information;
2. AI-assisted analysis;
3. AI-generated recommendation;
4. AI-supported human decision;
5. human-authorised AI action;
6. supervised autonomous action; or
7. independently executed consequential action where such autonomy has been separately authorised.

The record should make the nature of AI involvement clear.

---

## 5. Minimum Decision Chain

For consequential decisions, D-AIGAAF should seek to preserve the following chain:

**Operational Context → Input/Data → AI Processing → AI Output → Uncertainty/Limitations → Human Review → Human Authority → Decision → Action → Outcome**

The exact technical implementation may vary by system, but the governance objective should remain consistent.

---

## 6. Operational Context

Where proportionate and practicable, the record should establish:

- mission;
- use case;
- operational objective;
- environment;
- relevant operating conditions;
- system status;
- autonomy state;
- human authority;
- applicable restrictions;
- relevant time;
- configuration; and
- significant dependencies.

Context is necessary because an AI output cannot be meaningfully evaluated without understanding the circumstances in which it was produced.

---

## 7. AI Contribution

The record should identify the AI contribution where material.

This may include:

- information presented;
- analysis;
- recommendation;
- prediction;
- classification;
- proposed action;
- automated action;
- relevant confidence or uncertainty;
- warnings;
- system limitations; and
- significant system messages or status indicators.

The record should distinguish between what the AI produced and what a human subsequently decided.

---

## 8. Input and Data Traceability

Where technically and operationally practicable, material inputs should be traceable to their relevant sources.

This may include:

- source identifier;
- sensor or information source;
- data version;
- timestamp;
- provenance;
- relevant preprocessing;
- known data limitations;
- missing information; and
- data-integrity status.

Traceability should be proportionate to the importance of the input to the consequential decision.

---

## 9. Configuration Traceability

The system configuration relevant to a consequential decision should be identifiable.

This may include:

- model identifier;
- model version;
- software version;
- hardware configuration;
- configuration baseline;
- relevant rules or control settings;
- autonomy configuration;
- data/knowledge baseline where material;
- security configuration; and
- significant dependencies.

This allows an operational event to be connected to the exact capability state that existed at the time.

---

## 10. Human Review Traceability

Where human review is required, the record should identify:

- reviewing role;
- decision authority;
- review point;
- relevant information considered;
- AI recommendation or output;
- material uncertainty;
- human assessment;
- decision; and
- resulting action.

The purpose is to preserve meaningful human responsibility rather than merely recording that a person was technically present.

---

## 11. Human Decision Authority

For consequential actions, the organisation should be able to identify the human authority responsible for the decision.

The record should distinguish between:

- operator;
- supervisor;
- technical advisor;
- Operational AI Advisor;
- command/operational authority;
- risk owner; and
- authorising authority.

The person operating an interface is not necessarily the person holding authority for the consequential decision.

---

## 12. AI Recommendation Rejected or Bypassed

A human may reject, modify or bypass an AI recommendation.

Where consequential, the record should capture, where practicable:

- AI recommendation;
- human decision;
- responsible authority;
- principal reason for rejection or modification;
- conflicting information;
- uncertainty;
- resulting action; and
- outcome.

The purpose is not to create a presumption that AI recommendations should be followed.

Human disagreement with AI is an important part of meaningful human control and should support learning and assurance.

---

## 13. AI Recommendation Accepted

Where a consequential AI recommendation is accepted, the record should establish, where practicable:

- the relevant AI output;
- material uncertainty or limitations;
- human review;
- responsible authority;
- decision;
- action;
- configuration;
- autonomy level; and
- outcome.

The record should not imply that the AI itself held human decision authority unless the action occurred under a separately authorised autonomous mode.

---

## 14. Autonomous Actions

Where autonomous action is authorised, traceability should be proportionate to the consequence and autonomy level.

The record should seek to establish:

- authorised autonomy level;
- active autonomy state;
- conditions for autonomous action;
- triggering input;
- AI/system decision or action;
- relevant uncertainty or confidence;
- applicable constraints;
- human supervision status;
- intervention opportunities;
- action executed; and
- outcome.

Higher-consequence autonomous activity should require stronger evidence and reconstruction capability.

---

## 15. Consequential Actions

For actions that may materially affect:

- human life;
- physical safety;
- critical infrastructure;
- protected assets;
- significant property;
- mission outcomes; or
- other high-consequence interests,

the traceability requirements should be enhanced.

The organisation should seek to establish a reliable chain from the relevant AI contribution through human or authorised autonomous decision-making to the resulting action and outcome.

---

## 16. Uncertainty and Confidence

Where the AI communicates uncertainty, relevant uncertainty information should be retained where material to the decision.

This may include:

- confidence indicators;
- uncertainty estimates;
- warnings;
- competing hypotheses;
- missing information;
- known limitations; and
- system indications that the output may be unreliable.

A decision record should not present an AI output as more certain than it was at the time.

---

## 17. Temporal Traceability

Time is an important element of operational reconstruction.

Where relevant, records should preserve:

- input time;
- AI processing/output time;
- human review time;
- decision time;
- action time;
- intervention time; and
- outcome time.

Synchronisation requirements should be appropriate to the operational system and consequence of the decision.

---

## 18. Environment Traceability

The operational conditions surrounding a consequential decision should be recorded where relevant.

This may include:

- communications status;
- sensor condition;
- navigation status;
- information availability;
- environmental conditions;
- electromagnetic conditions;
- adversarial conditions;
- system degradation; and
- human operating conditions.

This allows later assessment of whether the decision occurred within the demonstrated and authorised operating envelope.

---

## 19. Autonomy Transition Traceability

Material transitions between autonomy states should be recorded.

Examples include:

- human-controlled to automated;
- automated to human-controlled;
- supervised to restricted;
- normal to degraded;
- degraded to safe state;
- normal to contingency; or
- suspension of autonomous functions.

The record should establish:

- previous state;
- new state;
- trigger;
- authority;
- time;
- reason; and
- resulting operational effect.

---

## 20. Intervention and Override Traceability

Material human interventions should be recorded where appropriate.

The record may include:

- trigger;
- intervention authority;
- action taken;
- system state;
- reason;
- result; and
- recovery status.

This provides evidence about whether meaningful human control was practically available and exercised.

---

## 21. Incident Traceability

Where an operational incident occurs, decision and action records should support reconstruction of:

**What was known → What AI produced → What humans understood → Who decided → What happened → What the outcome was**

Relevant evidence should be preserved in accordance with the Incident & Fail-Safe and Audit & Evidence modules.

---

## 22. Traceability and Privacy / Data Minimisation

Traceability should be balanced with appropriate information-security, privacy and data-minimisation requirements.

D-AIGAAF does not require indiscriminate retention of all information.

Organisations should define:

- what must be retained;
- why it is required;
- who may access it;
- how it is protected;
- retention periods;
- disposal requirements; and
- exceptional preservation requirements.

The objective is sufficient evidence for accountability and assurance without unnecessary collection.

---

## 23. Traceability Integrity

Decision and action records should be protected against:

- unauthorised modification;
- deletion;
- manipulation;
- incomplete capture;
- loss of sequence;
- misleading attribution; and
- configuration mismatch.

Where appropriate, technical controls should support:

- access control;
- integrity protection;
- timestamping;
- provenance;
- versioning;
- tamper evidence; and
- controlled retention.

---

## 24. Traceability Gaps

A traceability gap occurs where the available evidence cannot adequately establish a material part of the decision or action chain.

Examples include:

- missing AI output;
- unknown configuration;
- unidentified decision authority;
- missing human review evidence;
- unavailable environmental context;
- missing autonomy state;
- incomplete action record; or
- inconsistent timestamps.

Material traceability gaps should be assessed as assurance and governance risks.

A system should not be considered fully auditable merely because it generates extensive logs.

---

## 25. Traceability in Degraded and Disconnected Operations

Where communications or external services are unavailable, the system should use authorised local or deferred mechanisms for retaining material records where practicable.

Requirements should consider:

- local storage;
- synchronisation after connectivity restoration;
- data integrity;
- sequence preservation;
- storage capacity;
- protection of operational records; and
- fail-safe behaviour if recordkeeping itself becomes unavailable.

Loss of connectivity should not automatically eliminate accountability.

---

## 26. Operational Record

The Operational Record should link material employment activity to:

- Operational Authorisation Record;
- Readiness Record;
- Deployment Record;
- system configuration;
- assurance evidence;
- incidents;
- interventions;
- decisions; and
- outcomes.

This creates a connected evidence chain rather than isolated records.

---

## 27. Use in Accountability

Traceability should support identification of:

- who held authority;
- who made the consequential decision;
- what information was available;
- what role AI played;
- what controls applied;
- whether the action was authorised;
- whether conditions were satisfied; and
- whether deviations occurred.

Traceability should support accountability without automatically assigning blame to the person who happened to operate the system.

---

## 28. Use in Assurance and Learning

Decision and action records should feed into:

- TEVV;
- risk assessment;
- human-control assessment;
- autonomy assurance;
- security assurance;
- operational environment assessment;
- performance monitoring;
- incident investigation;
- lessons learned;
- authorisation review; and
- revalidation or reauthorisation.

Operational records therefore become evidence for future governance decisions.

---

## 29. Governance Questions

For consequential AI-supported decisions, responsible authorities should ask:

1. What mission was being conducted?
2. What AI capability was involved?
3. What configuration was active?
4. What information and inputs were available?
5. What did the AI produce?
6. What uncertainty or limitations were communicated?
7. What autonomy level was active?
8. Who reviewed the AI contribution?
9. Who held decision authority?
10. Was the decision within the authorisation?
11. What action occurred?
12. Was human intervention possible?
13. Was intervention exercised?
14. What environmental conditions existed?
15. Were any degraded or adversarial conditions present?
16. Were there any security or data-integrity concerns?
17. What was the outcome?
18. Can the decision be reconstructed?
19. Are there any material traceability gaps?
20. What assurance or governance action follows?

---

## 30. Core Rule

> **For consequential Defence AI use, the organisation shall maintain sufficient traceability to reconstruct the material chain from operational context and AI contribution through human or authorised autonomous decision-making to action and outcome. Traceability shall preserve human accountability, support meaningful human control, enable audit and investigation, and provide evidence for continuous assurance without implying that AI itself holds human authority unless such autonomy has been separately authorised.**
