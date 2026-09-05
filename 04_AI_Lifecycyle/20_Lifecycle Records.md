# Lifecycle Records

## Summary

Lifecycle records provide the authoritative evidence trail for a defence AI capability from initial need through development, assurance, authorisation, operational employment, change, revalidation, reauthorisation, retirement and decommissioning.

The core principle is:

**If a consequential AI capability cannot be reconstructed from reliable lifecycle records, its governance and assurance cannot be reliably demonstrated.**

The core chain is:

**Decision → Record → Evidence → Traceability → Review → Accountability**

---

## 1. Purpose

Lifecycle records provide a controlled mechanism to:

- establish what decisions were made;
- identify who made or approved them;
- preserve evidence supporting those decisions;
- reconstruct capability configuration;
- demonstrate compliance with requirements;
- support assurance and operational authorisation;
- investigate incidents;
- support audit;
- preserve lessons learned;
- establish historical accountability.

---

## 2. Scope

Lifecycle records should cover, as applicable:

- strategic need;
- mission need;
- requirements;
- use case;
- risk;
- autonomy;
- data;
- model development;
- acquisition;
- system integration;
- configuration;
- TEVV;
- operational environment;
- deployment readiness;
- operational deployment;
- operational employment;
- monitoring;
- incidents;
- changes;
- revalidation;
- reauthorisation;
- retirement;
- decommissioning.

---

## 3. Record-Keeping Principle

Records should be:

- attributable;
- authentic;
- complete;
- accurate;
- timely;
- traceable;
- protected from unauthorised alteration;
- accessible to authorised reviewers;
- retained for an appropriate period.

The level of record-keeping should be proportionate to consequence, autonomy and risk.

---

## 4. Lifecycle Record Architecture

D-AIGAAF should maintain connected records rather than isolated documents.

The principal record relationships are:

**Capability Register → Requirements → Risk → Configuration → TEVV → Assurance → Authorisation → Employment → Monitoring → Change → Revalidation → Reauthorisation → Retirement → Decommissioning**

---

## 5. Core Records

D-AIGAAF identifies four principal record families.

### 5.1 Defence AI Capability Register (DAICR)

Records what AI capabilities exist.

### 5.2 Defence AI Assurance Record (DAAR)

Records what evidence exists and what that evidence demonstrates.

### 5.3 Defence AI Operational Authorisation Record

Records why and under what conditions operational use is authorised.

### 5.4 Operational Record

Records what actually occurred during operational employment.

These records should be linked rather than maintained as unrelated repositories.

---

## 6. Capability Register

The Defence AI Capability Register should identify:

- capability ID;
- capability name;
- owner;
- mission/use case;
- system;
- model;
- configuration;
- lifecycle status;
- risk level;
- autonomy;
- authorisation status;
- assurance status;
- environment;
- dependencies;
- review status.

---

## 7. Requirements Records

Requirements records should preserve:

- mission need;
- use case;
- requirements;
- assumptions;
- constraints;
- acceptance criteria;
- traceability;
- requirement changes.

Requirements should remain linked to the capability they govern.

---

## 8. Risk Records

Risk records should preserve:

- identified risks;
- consequence;
- likelihood;
- mission criticality;
- autonomy;
- human control;
- environment;
- controls;
- residual risk;
- risk acceptance;
- review history.

Risk records should show how risk changed over the lifecycle.

---

## 9. Data Records

Where relevant, record:

- data source;
- provenance;
- ownership;
- collection context;
- transformation;
- labelling;
- quality;
- representativeness;
- limitations;
- version;
- validation;
- security controls.

Data records should support reproducibility and assurance.

---

## 10. Model Records

Model records may include:

- model identity;
- architecture;
- version;
- weights or equivalent identifiers;
- training information;
- evaluation;
- limitations;
- dependencies;
- configuration;
- change history;
- provenance.

Sensitive implementation details should be protected according to applicable policy.

---

## 11. Acquisition Records

Acquisition records should preserve:

- supplier;
- contractual requirements;
- technical claims;
- assurance commitments;
- provenance;
- dependencies;
- support arrangements;
- update obligations;
- security requirements;
- acceptance decisions.

---

## 12. Configuration Records

Configuration records should establish:

**What Was Approved → What Was Tested → What Was Deployed → What Was Operated**

They should identify relevant:

- models;
- software;
- hardware;
- firmware;
- data;
- parameters;
- interfaces;
- dependencies;
- security controls.

---

## 13. TEVV Records

TEVV records should preserve:

- test objectives;
- requirements;
- configuration;
- environment;
- methodology;
- test cases;
- results;
- failures;
- limitations;
- evaluator;
- date;
- evidence location;
- conclusions.

A result should not be interpreted without its test context.

---

## 14. Assurance Records

The Defence AI Assurance Record should connect evidence to claims.

For each significant assurance claim, record:

- assurance claim;
- supporting evidence;
- evidence quality;
- limitations;
- assumptions;
- reviewer;
- conclusion;
- unresolved gaps.

---

## 15. Operational Environment Records

Where operational environment affects assurance, record:

- environment characteristics;
- assumptions;
- constraints;
- test conditions;
- observed conditions;
- limitations;
- deviations.

This prevents evidence from being detached from the conditions under which it was generated.

---

## 16. Deployment Records

Deployment records should establish:

- authorised capability;
- approved configuration;
- deployment environment;
- deployment date;
- responsible personnel;
- verification;
- deviations;
- acceptance;
- handover.

The record should demonstrate:

**Approved Baseline = Deployed Baseline**

---

## 17. Operational Employment Records

Operational records should capture information necessary to reconstruct consequential use.

Where appropriate:

- user;
- capability;
- configuration;
- mission/use case;
- relevant inputs;
- AI output;
- uncertainty;
- human decision;
- action;
- outcome;
- exception;
- intervention;
- override.

The objective is not to record every trivial interaction, but to preserve sufficient evidence for consequential decisions and events.

---

## 18. Decision Traceability

For consequential decisions, records should support the chain:

**Who → Used Which Capability → In Which Configuration → Received What Information → AI Output → Human Decision → Action → Outcome**

This is particularly important where AI contributes to decisions affecting:

- human life;
- safety;
- critical infrastructure;
- major resources;
- operational continuity.

---

## 19. Human Decision Records

Where AI informs a consequential decision, records should distinguish:

- AI-generated information;
- human interpretation;
- human decision;
- authorised action.

Where practicable, the record should also support documentation of why a material AI recommendation was rejected, modified or bypassed.

---

## 20. Autonomy Records

Records should identify:

- authorised autonomy;
- observed autonomy;
- autonomy transitions;
- human supervision;
- intervention;
- override;
- termination;
- exceptions.

Unexpected autonomy should trigger appropriate incident or assurance processes.

---

## 21. Monitoring Records

Monitoring records should preserve:

- performance;
- reliability;
- robustness;
- uncertainty;
- data drift;
- environment;
- configuration;
- security;
- safety;
- autonomy;
- mission effectiveness;
- alerts;
- interventions.

Monitoring data should be linked to the relevant configuration and period.

---

## 22. Incident Records

Incident records should include, as appropriate:

- incident ID;
- date/time;
- capability;
- configuration;
- environment;
- observed behaviour;
- AI output;
- human response;
- action;
- consequence;
- containment;
- investigation;
- corrective action;
- revalidation;
- authorisation impact.

---

## 23. Change Records

Change records should establish:

- what changed;
- why it changed;
- who approved it;
- configuration before;
- configuration after;
- impact assessment;
- testing;
- evidence;
- risk impact;
- revalidation requirement;
- authorisation impact.

---

## 24. Revalidation Records

Revalidation records should preserve:

- trigger;
- scope;
- affected evidence;
- testing;
- findings;
- limitations;
- updated risk;
- validation outcome;
- configuration;
- authorisation impact.

---

## 25. Reauthorisation Records

Reauthorisation records should preserve:

- authorisation decision;
- authority;
- capability;
- configuration;
- mission;
- environment;
- autonomy;
- human authority;
- evidence;
- residual risk;
- conditions;
- limitations;
- validity period;
- suspension triggers.

---

## 26. Retirement Records

Retirement records should establish:

- retirement reason;
- authority;
- effective date;
- final configuration;
- final authorisation;
- transition;
- residual risk;
- records retained;
- decommissioning requirements.

---

## 27. Decommissioning Records

Decommissioning records should establish:

- assets;
- dependencies;
- access closure;
- interfaces;
- model disposition;
- data disposition;
- infrastructure disposition;
- supplier closure;
- verification;
- exceptions;
- residual risk.

---

## 28. Record Relationships

Every significant record should reference relevant identifiers.

Example:

```text
Capability ID
    ↓
Use Case ID
    ↓
Requirement ID
    ↓
Risk ID
    ↓
Configuration ID
    ↓
Test / Evidence ID
    ↓
Assurance Claim ID
    ↓
Authorisation ID
    ↓
Operational Event ID
    ↓
Change / Incident ID
    ↓
Revalidation ID
    ↓
Reauthorisation ID
    ↓
Retirement ID
    ↓
Decommissioning ID
```

---

## 29. Version Control

Records should preserve meaningful versions.

Version control should apply to:

- requirements;
- risk assessments;
- models;
- configurations;
- test plans;
- assurance conclusions;
- authorisations;
- operating procedures.

Historical versions should not be silently overwritten.

---

## 30. Immutable Historical Evidence

Where appropriate, critical records should have controls that make unauthorised alteration detectable.

Examples may include:

- controlled repositories;
- cryptographic integrity mechanisms;
- signed approvals;
- access logs;
- version histories.

The implementation should reflect organisational security and technical requirements.

---

## 31. Metadata

Records should contain sufficient metadata to establish:

- creator;
- approver;
- date/time;
- version;
- capability;
- configuration;
- environment;
- classification or handling requirements where applicable;
- related records.

---

## 32. Access Control

Access should follow the principle of least privilege.

Different roles may require access to:

- operational records;
- technical records;
- assurance evidence;
- security information;
- authorisation decisions;
- audit records.

Sensitive information should not be broadly accessible merely because it forms part of a lifecycle record.

---

## 33. Record Integrity

Integrity controls should protect against:

- unauthorised modification;
- deletion;
- corruption;
- loss;
- misattribution;
- version confusion.

Record integrity is itself part of assurance.

---

## 34. Record Availability

Critical records should remain available to authorised personnel when needed for:

- operational decisions;
- assurance;
- incident response;
- audit;
- investigation;
- reauthorisation.

Availability requirements should account for disconnected or degraded operating conditions where relevant.

---

## 35. Record Retention

Retention periods should be defined according to:

- legal requirements;
- policy;
- operational need;
- risk;
- investigation requirements;
- audit requirements;
- historical value.

Retention should not be indefinite by default.

---

## 36. Record Disposal

When retention expires:

- disposal should be authorised;
- applicable holds should be checked;
- data should be securely disposed of;
- disposal should itself be recorded.

---

## 37. Legal and Investigation Hold

Records relevant to:

- investigations;
- audits;
- legal proceedings;
- safety reviews;
- security incidents;

should be preserved until the relevant hold is formally released.

---

## 38. Evidence Sufficiency

Lifecycle records should support an evidence question:

**Can an independent reviewer determine what happened, why it happened, under what authority, and what evidence supported the decision?**

If not, the record system may be inadequate for the consequence of the capability.

---

## 39. Audit Trail

The audit trail should allow review of:

- decisions;
- approvals;
- configuration changes;
- access;
- testing;
- incidents;
- authorisation;
- operational use;
- retirement.

Auditability should increase with consequence and autonomy.

---

## 40. Independent Review

For high-consequence capabilities, records should support independent review without relying solely on the original development or operational team.

Reviewers should be able to access sufficient evidence to challenge:

- assumptions;
- conclusions;
- risk acceptance;
- authorisation;
- operational suitability.

---

## 41. Operational Record Granularity

Record depth should be proportionate.

### Low Consequence

Periodic or event-based records may be sufficient.

### Moderate Consequence

More detailed configuration, decision and monitoring records may be required.

### High Consequence

Records should support reconstruction of significant AI-assisted decisions, actions and outcomes.

---

## 42. Data Minimisation

Record-keeping should not become uncontrolled data collection.

Capture only information necessary to support:

- accountability;
- assurance;
- safety;
- security;
- audit;
- operational learning;
- legal requirements.

---

## 43. Privacy and Sensitive Information

Where records contain personal or otherwise sensitive information:

- access should be controlled;
- collection should be justified;
- retention should be appropriate;
- disclosure should be governed.

---

## 44. Records During Disconnected Operation

Where a capability operates without reliable communications, records should support:

- local logging;
- secure time/order information;
- later synchronisation;
- integrity verification;
- conflict resolution.

The absence of connectivity should not automatically eliminate accountability.

---

## 45. Records During Degraded Operation

Where systems operate in degraded conditions, record mechanisms should fail safely.

Where full logging is unavailable:

- minimum required records should be preserved;
- the limitation should be recorded;
- later reconciliation should occur where feasible.

---

## 46. Record Synchronisation

Distributed systems may produce records across multiple locations.

Synchronisation should preserve:

- ordering;
- provenance;
- integrity;
- source;
- configuration;
- time context.

Conflicting records should not be silently merged.

---

## 47. Record Searchability

Records should be searchable by relevant identifiers such as:

- capability;
- mission;
- configuration;
- event;
- incident;
- authorisation;
- date;
- user;
- test;
- change.

Searchability directly affects the ability to conduct assurance and investigation.

---

## 48. Record Ownership

Each major record type should have an identified owner responsible for:

- accuracy;
- access;
- retention;
- integrity;
- review;
- disposal.

Ownership should not be ambiguous between technical, operational and assurance functions.

---

## 49. Record Review

Records should be periodically reviewed for:

- completeness;
- integrity;
- accessibility;
- relevance;
- retention;
- unresolved gaps.

High-consequence capabilities should receive stronger record governance.

---

## 50. Lifecycle Record Gaps

Record gaps should be treated as governance findings where they affect:

- assurance;
- accountability;
- safety;
- security;
- authorisation.

A missing record may represent missing evidence rather than merely missing paperwork.

---

## 51. Common Failure Modes

### 51.1 Treating Documentation as Administrative Overhead

Lifecycle records are part of assurance and accountability.

### 51.2 Recording Only the Final Decision

The evidence and reasoning supporting the decision may be equally important.

### 51.3 Overwriting Historical Versions

Historical configuration and decisions may be required for investigation.

### 51.4 Logging Everything Without Purpose

Excessive records can reduce usability and create unnecessary exposure.

### 51.5 Ignoring Disconnected Operation

Record systems must account for environments where connectivity is unavailable.

### 51.6 Separating Records From Configuration

A decision cannot be reliably reconstructed if the configuration is unknown.

### 51.7 Losing Records During Retirement

Retirement and decommissioning should include evidence preservation.

---

## 52. Core Rules

1. **Every consequential AI capability should have a traceable lifecycle record.**
2. **Records must establish what was decided, by whom, when and on what evidence.**
3. **Capability, configuration, evidence and authority must remain linked.**
4. **Historical versions must not be silently overwritten.**
5. **Critical records should have appropriate integrity protection.**
6. **Record access should be proportionate and controlled.**
7. **Operational records should support reconstruction of consequential AI-assisted decisions and actions.**
8. **Record depth should increase with consequence and autonomy.**
9. **Disconnected and degraded operation must be considered in record design.**
10. **Incident, assurance and legal evidence must be preserved when required.**
11. **Record gaps affecting assurance or accountability should be treated as governance findings.**
12. **Record retention should have defined purpose and duration.**
13. **Disposal should be authorised and recorded.**
14. **Records should support independent review where required.**
15. **Lifecycle records are part of the assurance system, not merely administrative documentation.**

---

## 53. Golden Thread

Lifecycle records preserve the complete Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement → Decommissioning**

---

## 54. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **00 Framework** — provides the overall lifecycle and Golden Thread.
- **01 Strategy & Governance** — establishes record ownership and decision rights.
- **02 Mission & Use Case** — provides mission and use-case records.
- **03 Risk & Autonomy** — provides risk and autonomy evidence.
- **04 AI Lifecycle** — governs lifecycle record creation and closure.
- **05 Data & Information** — governs data provenance and records.
- **06 AI Security** — governs record security and integrity.
- **07 Supply Chain & Sovereignty** — preserves supplier and provenance records.
- **08 Human Authority** — records human decisions and authority.
- **09 TEVV** — preserves testing and evaluation evidence.
- **11 Operational Authorisation** — preserves operational authority decisions.
- **12 Operational Employment** — provides operational records.
- **13 Continuous Assurance** — provides monitoring evidence.
- **14 Incident & Fail-Safe** — provides incident and emergency records.
- **15 Change & Reauthorisation** — provides change and authority history.
- **16 Audit & Evidence** — establishes audit and evidence requirements.
- **18 Retirement** — provides retirement records.
- **19 Decommissioning** — provides final closure records.
- **25 Documentation & Knowledge** — governs documentation and knowledge management.

---

## 55. Summary Model

```text
Mission / Need
      ↓
Requirements / Risk
      ↓
Capability / Configuration
      ↓
TEVV / Evidence
      ↓
Assurance
      ↓
Authorisation
      ↓
Operational Employment
      ↓
Monitoring / Incidents
      ↓
Change / Revalidation
      ↓
Reauthorisation
      ↓
Retirement
      ↓
Decommissioning
      ↓
Historical Record
```

Lifecycle records provide the evidence backbone that allows D-AIGAAF to demonstrate not only that an AI capability existed, but **what it was, what it was authorised to do, what evidence supported that authority, how it was actually used, what changed, and how its lifecycle ended.**
