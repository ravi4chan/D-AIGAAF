# 39 — Authorisation Operational Authority Decision Logging and Record Integrity

## 1. Purpose

This document defines requirements for recording and protecting material operational authority decisions involving Defence AI capabilities.

The purpose is to ensure that decisions affecting AI operational authority can be:

- identified;
- attributed to the responsible human authority;
- reconstructed;
- understood in context;
- connected to the applicable authorisation;
- linked to relevant AI contributions;
- supported by evidence;
- protected against unauthorised alteration;
- reviewed after incidents or disputes.

Decision logging is a governance control and an accountability mechanism. It is not intended to record every insignificant system event.

---

## 2. Core Principle

> **Material decisions affecting Defence AI operational authority shall be recorded with sufficient context, attribution, integrity and traceability to reconstruct who decided what, on what basis, under which authority and with what outcome.**

The existence of a log does not by itself establish that a decision was lawful, authorised or correct.

---

## 3. Decision Logging versus Operational Logging

D-AIGAAF distinguishes between:

### Decision Logging

Records material human or authorised autonomous decisions affecting operational authority, mission, autonomy, risk, restrictions or consequential activity.

### Operational Logging

Records relevant system and operational activity during employment.

### Audit Evidence

Provides evidence supporting assurance, compliance, investigation and governance review.

These records should remain connected but should not be unnecessarily duplicated.

---

## 4. Decisions Requiring Recording

Material decisions should be logged where they affect:

- operational authorisation;
- mission scope;
- operational boundaries;
- autonomy;
- human authority;
- risk acceptance;
- restrictions;
- suspension;
- restoration;
- deployment;
- operational employment;
- consequential action;
- emergency response;
- fail-safe activation;
- override;
- material configuration;
- security response;
- revalidation;
- reauthorisation.

The level of logging should be proportionate to consequence.

---

## 5. Decision Context

A decision record should contain sufficient context to understand the situation at the time of decision.

Where applicable, this includes:

- date and time;
- mission;
- operational state;
- environment;
- capability;
- configuration;
- autonomy level;
- human authority;
- relevant conditions;
- material risk;
- relevant AI output;
- available information;
- uncertainty;
- triggering event.

The record should avoid unnecessary collection of information that is not required for accountability or assurance.

---

## 6. Human Decision Attribution

Every material human decision should identify the responsible decision-maker or authority.

The record should establish:

- identity or role identifier;
- organisational authority;
- decision rights;
- delegation status where applicable;
- time of decision;
- decision scope.

Where authority was delegated, the delegation should be traceable to the applicable delegation record.

---

## 7. AI Contribution

Where AI materially contributed to a consequential decision, the record should identify, where technically and operationally feasible:

- AI capability;
- model/system version;
- relevant configuration;
- material output or recommendation;
- confidence or uncertainty information;
- important input context;
- time of output;
- relevant system state.

The objective is not to imply that AI made the human decision.

The record should distinguish:

**AI Contribution → Human Assessment → Human Decision → Action**

---

## 8. Human Assessment

Where a human reviewed an AI recommendation, the record should capture sufficient information to establish the nature of that review.

Depending on consequence, this may include:

- accepted;
- rejected;
- modified;
- deferred;
- overridden;
- independently verified;
- escalated.

Where a consequential AI recommendation is rejected or bypassed, the organisation should retain sufficient rationale to support later review where practicable.

---

## 9. Autonomous Decision Logging

Where autonomous action has been separately authorised, the record should identify:

- authorised autonomy level;
- relevant trigger;
- system state;
- action;
- applicable rule or condition;
- human supervision status;
- intervention opportunity;
- outcome.

Autonomous activity should remain attributable to the human authority that authorised the relevant autonomy and operational conditions.

---

## 10. Decision and Action Chain

For consequential use, D-AIGAAF uses the traceability chain:

**Context → AI Contribution → Human Assessment → Authority → Decision → Action → Outcome**

The level of detail should be proportionate to the consequence and operational feasibility.

This chain supports:

- accountability;
- investigation;
- audit;
- assurance;
- lessons learned;
- revalidation;
- reauthorisation.

---

## 11. Decision Integrity

Decision records should be protected against:

- unauthorised alteration;
- deletion;
- corruption;
- manipulation;
- loss;
- retrospective fabrication.

Appropriate integrity controls may include:

- access control;
- authentication;
- time synchronisation;
- versioning;
- tamper-evident mechanisms;
- controlled amendments;
- backup;
- integrity verification.

Technical mechanisms should be proportionate to the sensitivity and consequence of the records.

---

## 12. Time and Sequence Integrity

Where decisions occur in rapid succession, reliable sequencing is important.

The organisation should establish, where practicable:

- consistent time sources;
- event ordering;
- system and human timestamps;
- synchronisation status;
- handling of uncertain timestamps.

Where precise sequencing cannot be established, that limitation should be recorded rather than inferred as certainty.

---

## 13. Configuration Traceability

A consequential decision record should be connected to the configuration under which the decision occurred.

Where material, record:

- model version;
- model state;
- software version;
- hardware;
- relevant configuration;
- safety controls;
- security controls;
- interface state;
- dependency versions.

This enables later determination of whether the behaviour was associated with the authorised configuration.

---

## 14. Authority Traceability

Each material decision should be traceable to:

- applicable authorisation;
- authorisation conditions;
- relevant operational authority;
- delegation;
- applicable restrictions;
- emergency authority where applicable.

The record should make it possible to determine whether the decision was within the authority available at the time.

---

## 15. Uncertainty and Missing Information

Decision records should preserve material uncertainty.

Examples include:

- incomplete sensor information;
- conflicting information;
- uncertain AI output;
- uncertain environment;
- uncertain system state;
- uncertain communications;
- uncertain human authority.

A later review should be able to distinguish between:

**Known at the time**

and

**Known only after the event**

This prevents hindsight from being mistaken for information available to the original decision-maker.

---

## 16. Decision Logging During Degraded Operations

Where normal recording infrastructure is unavailable:

- minimum viable records should be maintained where practicable;
- local logging may be used;
- manual records may be used where appropriate;
- authority and decision time should be captured;
- records should be reconciled after restoration.

Loss of central logging should not create additional operational authority.

---

## 17. Decision Logging During Disconnected Operations

Where connectivity is unavailable:

- authorised local logging arrangements should apply;
- critical decisions should remain attributable;
- local records should be protected;
- later synchronisation should preserve original event timing;
- conflicts between local and central records should be resolved through controlled reconciliation.

Restored connectivity should not permit silent alteration of historical records.

---

## 18. Emergency Decision Logging

Emergency actions may occur faster than normal documentation allows.

In such cases:

1. Take the necessary pre-authorised protective action;
2. Record the minimum practicable decision information;
3. Preserve system and operational evidence;
4. Record the responsible authority;
5. Complete the record as soon as practicable;
6. Conduct post-event review.

Emergency conditions should not be used to eliminate accountability.

---

## 19. Override and Intervention Records

Where a human overrides, interrupts or modifies AI behaviour, the record should identify:

- system state;
- AI action or recommendation;
- human intervention;
- authority for intervention;
- reason where material;
- resulting state;
- outcome.

Repeated interventions may indicate a weakness in:

- model performance;
- human-AI interaction;
- autonomy design;
- operating procedures;
- authorisation conditions.

Such patterns should feed continuous assurance.

---

## 20. Fail-Safe Activation Records

Where a fail-safe or safe-state mechanism is activated, the record should capture where practicable:

- trigger;
- system state;
- human involvement;
- protective action;
- resulting state;
- operational impact;
- recovery action.

A fail-safe activation should be treated as evidence relevant to continued assurance, even where it successfully prevented harm.

---

## 21. Decision Disputes

Where material disagreement exists between:

- operator and supervisor;
- commander and technical authority;
- operational and security authority;
- human and AI recommendation;
- multiple human authorities;

the material disagreement should be recorded where relevant.

The record should distinguish:

- disagreement;
- decision;
- authority;
- unresolved concern;
- final outcome.

Disagreement does not itself create operational permission.

---

## 22. Decision Record Corrections

Corrections should preserve the original record.

A correction process should identify:

- original entry;
- correction;
- reason;
- person making correction;
- authority;
- date/time.

Records should not be silently rewritten to reflect later understanding.

---

## 23. Decision Record Retention

Retention should be proportionate to:

- consequence;
- legal requirements;
- operational significance;
- investigation requirements;
- assurance needs;
- audit requirements;
- organisational policy.

Records required for ongoing assurance or unresolved investigations should not be destroyed merely because an authorisation has expired.

---

## 24. Privacy and Data Minimisation

Decision logging should collect only information necessary for:

- accountability;
- safety;
- assurance;
- security;
- investigation;
- legal compliance;
- governance.

Where personal information is recorded, appropriate controls should apply.

Accountability requirements should not become a justification for indiscriminate data collection.

---

## 25. Decision Record Access

Access should be controlled according to:

- role;
- need;
- sensitivity;
- operational requirements;
- legal requirements.

Access should itself be appropriately auditable where required.

The objective is to balance:

**Accountability ↔ Security ↔ Privacy ↔ Operational Need**

---

## 26. Decision Record Review

Material decision records should be reviewed when:

- an incident occurs;
- a dispute arises;
- a boundary is crossed;
- performance degrades;
- security concerns emerge;
- authorisation is reconsidered;
- revalidation is required;
- reauthorisation is required.

Review should determine whether:

- authority was valid;
- decision rights were followed;
- evidence was sufficient;
- uncertainty was understood;
- controls operated as intended;
- the outcome indicates a systemic governance issue.

---

## 27. Decision Logging and Continuous Assurance

Decision records provide evidence for:

- performance monitoring;
- risk monitoring;
- human-control assessment;
- autonomy assurance;
- incident investigation;
- lessons learned;
- change impact assessment;
- revalidation;
- reauthorisation.

Decision logging therefore forms part of the continuous assurance feedback loop:

**Employment → Decision → Outcome → Evidence → Review → Learning → Change → Revalidation/Reauthorisation**

---

## 28. Decision Logging and Audit

Auditors and reviewers should be able to determine, where records are available:

1. What happened?
2. What information was available?
3. What did the AI contribute?
4. Who held authority?
5. What decision was made?
6. Why was it made?
7. What action followed?
8. What was the outcome?
9. Was the action within the authorisation?
10. What evidence supports the reconstruction?

A record should not imply certainty where the available evidence cannot support it.

---

## 29. Decision Log Register

A controlled **Operational Authority Decision Log** should include, where applicable:

| Field | Description |
|---|---|
| Decision ID | Unique identifier |
| Date/Time | Decision time |
| Capability | AI capability |
| Mission | Mission/use case |
| Operational State | Current state |
| Configuration | Applicable baseline |
| Autonomy | Applicable level |
| AI Contribution | Recommendation/output |
| Uncertainty | Material uncertainty |
| Human Authority | Decision-maker |
| Authority Basis | Authorisation/delegation |
| Decision | Decision made |
| Rationale | Material reasoning |
| Action | Resulting action |
| Outcome | Result |
| Intervention | Override/intervention if any |
| Evidence | Supporting records |
| Follow-up | Required action |
| Status | Open/Closed |

---

## 30. Minimum Record for Consequential Decisions

For decisions with potential material effect on human life, safety, property or mission outcomes, the minimum record should, where practicable, establish:

- operational context;
- AI contribution;
- human authority;
- applicable authorisation;
- decision;
- action;
- outcome;
- relevant configuration;
- material uncertainty;
- significant intervention or override.

The level of detail should reflect the operational consequences and available technical capability.

---

## 31. Record Reconciliation

Where multiple systems independently record the same event, records should be reconciled when necessary.

Potential sources may include:

- AI system logs;
- platform logs;
- operator records;
- command records;
- security records;
- communications records;
- sensor records;
- incident records.

Differences should be identified rather than silently normalised.

---

## 32. Record Integrity Failure

A material inability to establish reliable decision records may itself become an assurance concern.

Examples include:

- missing consequential records;
- unexplained timestamp conflicts;
- unauthorised modification;
- loss of configuration information;
- inability to identify decision authority;
- inability to reconstruct AI contribution.

Depending on consequence, this may trigger:

- additional investigation;
- restriction;
- additional assurance;
- revalidation;
- reauthorisation;
- suspension.

---

## 33. Governance Questions

Before operational employment, the organisation should be able to answer:

1. Which AI-supported decisions must be recorded?
2. Who is responsible for the decision record?
3. How is human authority established?
4. How is AI contribution distinguished from human decision-making?
5. Can the decision be reconstructed later?
6. How is uncertainty captured?
7. How are configuration and authorisation linked to the decision?
8. What happens when normal logging is unavailable?
9. How are emergency decisions recorded?
10. How are corrections controlled?
11. How are records protected against manipulation?
12. When does a record-integrity failure affect operational authority?

---

## 34. Golden Thread

Decision logging should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Decision → Action → Outcome → Monitoring → Change/Incident → Revalidation/Reauthorisation**

This ensures that consequential decisions become usable evidence for assurance, accountability and organisational learning.

---

## 35. Core Rule

> **Material Defence AI operational authority and consequential decision-making shall be recorded with sufficient context, attribution, authority linkage, AI contribution, configuration, uncertainty and outcome information to support reliable reconstruction and accountability. Records shall be protected against unauthorised alteration and preserved according to applicable requirements. Where decision-record integrity is materially compromised, the organisation shall assess the resulting assurance and operational-authority implications and apply proportionate corrective action.**
