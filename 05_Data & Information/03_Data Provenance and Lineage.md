# Data Provenance and Lineage

## 1. Purpose

This document defines how D-AIGAAF governs the provenance and lineage of data used by defence AI capabilities.

The objective is to ensure that an organisation can determine:

- where data originated;
- who or what generated or supplied it;
- how it was acquired;
- what transformations were applied;
- where it has been used;
- what assumptions or limitations apply; and
- how changes in data may affect AI behaviour and operational risk.

## 2. Core Principle

> **Data used by consequential AI systems must be sufficiently traceable to support assurance, accountability, investigation, and operational decision-making.**

Data provenance establishes the history and origin of data.

Data lineage establishes how data moves, changes, combines, and contributes to an AI capability.

Neither requires that every byte of data be permanently retained. The level of traceability should be proportionate to mission consequence, data dependence, security requirements, and operational risk.

## 3. Scope

This document applies to data used across the AI lifecycle, including:

- training data;
- validation and test data;
- operational input data;
- reference and knowledge data;
- sensor-derived data;
- human-generated data;
- synthetic data;
- externally supplied data;
- third-party datasets;
- model-generated or transformed data;
- labels and annotations;
- derived features;
- embeddings and other representations;
- data used for monitoring and evaluation.

## 4. Provenance and Lineage Objectives

D-AIGAAF seeks to establish:

1. **Origin** — Where did the data come from?
2. **Authority** — Who was authorised to provide or collect it?
3. **Purpose** — Why was it collected or acquired?
4. **Transformation** — What happened to it before use?
5. **Context** — Under what conditions was it generated?
6. **Quality** — What quality controls were applied?
7. **Security** — What protections and handling restrictions apply?
8. **Use** — Which AI systems or processes depend on it?
9. **Change** — What has changed since previous use?
10. **Accountability** — Who is responsible for its governance?

## 5. Data Provenance

Provenance should capture, where applicable:

- source or originating system;
- data owner;
- data steward;
- collection or generation method;
- collection period;
- geographic or operational context at an appropriate level;
- acquisition authority;
- supplier or external source;
- applicable classification or handling restrictions;
- licensing or usage restrictions;
- known limitations;
- validation status;
- integrity status;
- relevant metadata;
- version or release identifier.

The required level of detail should be determined by risk and mission consequence.

## 6. Data Lineage

Lineage should provide a traceable representation of significant data transformations.

A typical lineage chain is:

**Source → Acquisition → Ingestion → Cleaning → Filtering → Labelling → Transformation → Dataset → Model/System Input → AI Output → Operational Decision**

The chain may contain additional stages where necessary.

Lineage should identify material transformations rather than attempting to document every routine technical operation.

## 7. Training Data Lineage

For training datasets, organisations should be able to determine, to an appropriate level:

- constituent datasets;
- source categories;
- major preprocessing steps;
- filtering rules;
- labelling methodology;
- synthetic-data generation;
- augmentation;
- deduplication;
- sampling;
- exclusions;
- version history;
- known data gaps;
- assumptions affecting representativeness.

Training-data lineage should support assessment of whether observed model behaviour can reasonably be related to the data used to develop the system.

## 8. Validation and Test Data Lineage

Validation and test data should have sufficient provenance to establish:

- how the dataset was constructed;
- whether it was independent of training data where independence is required;
- which operational conditions it represents;
- what scenarios are covered;
- what scenarios remain untested;
- whether data leakage or contamination risks exist;
- which version of the AI system was evaluated.

Test evidence without traceable test-data context may be insufficient for assurance.

## 9. Operational Data Lineage

Operational inputs should be traceable to the extent necessary to reconstruct consequential system behaviour.

Depending on the capability, this may include:

- input source;
- timestamp or temporal reference;
- relevant system state;
- preprocessing;
- filtering;
- fusion;
- confidence or uncertainty information;
- AI model/system version;
- output generated;
- human interaction;
- consequential action or decision.

Operational logging must remain proportionate to security, privacy, mission, and retention requirements.

## 10. Derived and Transformed Data

Derived data should not lose its relationship to the source data merely because it has been transformed.

Where material, records should identify:

**Source Data → Transformation → Derived Data**

Examples include:

- engineered features;
- aggregated datasets;
- synthetic datasets;
- translated or normalised data;
- embeddings;
- generated labels;
- fused sensor information;
- model-generated training material.

Where transformations materially alter interpretation, the transformation should be documented as part of the lineage record.

## 11. Synthetic Data

Synthetic data should be clearly identified.

Where synthetic data is used for development, testing, or training, provenance should record:

- generation method;
- generating system or model;
- generation assumptions;
- relevant parameters or configuration;
- validation approach;
- intended purpose;
- known limitations;
- relationship to real-world conditions.

Synthetic data should not automatically be treated as equivalent to operationally representative data.

## 12. Third-Party and External Data

External data should have sufficient provenance to establish:

- source organisation;
- acquisition route;
- applicable rights or restrictions;
- known collection methodology;
- version;
- integrity status;
- known limitations;
- dependencies on external systems;
- conditions of continued use.

Where provenance cannot be adequately established, the data should be treated as having elevated uncertainty.

## 13. Provenance Integrity

Provenance records themselves require protection.

Controls should address:

- unauthorised modification;
- deletion;
- loss of metadata;
- inconsistent versioning;
- undocumented transformations;
- broken lineage links;
- conflicting records;
- manipulation of provenance information.

For higher-consequence systems, provenance records should support tamper detection and controlled auditability.

## 14. Provenance and AI Assurance

Provenance contributes directly to assurance.

It should help answer:

- Was the AI system trained or tested on data appropriate to its authorised purpose?
- Can material data limitations be identified?
- Can unexpected behaviour be investigated?
- Can a changed dataset be distinguished from an approved baseline?
- Can evidence supporting an authorisation decision be reconstructed?

Weak provenance increases uncertainty and may require additional assurance measures.

## 15. Data Lineage and the Golden Thread

D-AIGAAF requires the ability to connect data lineage to the broader assurance chain:

**Mission Need → AI Requirement → Data Dependency → Data Source → Data Transformation → AI Behaviour → Human Decision → Operational Action → Outcome**

This connection is particularly important where data materially influences a consequential decision or action.

## 16. Provenance Gaps

A provenance gap exists when required information about the origin, transformation, or use of data cannot be established with sufficient confidence.

Examples include:

- unknown source;
- incomplete source history;
- undocumented preprocessing;
- missing version information;
- uncertain labelling origin;
- unclear third-party dependencies;
- broken lineage;
- inability to distinguish approved and modified datasets.

A provenance gap should be recorded as an assurance limitation rather than silently ignored.

## 17. Provenance Risk

A working provenance risk relationship is:

**Provenance Risk = Consequence × Data Dependence × Provenance Uncertainty × Exposure**

Higher provenance risk should result in stronger controls, greater testing, additional human review, or restrictions on operational use.

## 18. Change and Revalidation

Changes to data provenance or lineage should be assessed for operational significance.

Examples of potentially material changes include:

- new source populations;
- changed collection methods;
- significant preprocessing changes;
- new labelling methods;
- changed synthetic-data generation;
- new third-party dependencies;
- removal of critical data sources;
- significant changes in data distribution.

Material changes may require:

**Change Assessment → Impact Assessment → Revalidation → Reauthorisation**

## 19. Provenance Record

A Data Provenance Record should contain, where appropriate:

| Field | Description |
|---|---|
| Data Asset ID | Unique identifier |
| Dataset / Data Asset | Name and description |
| Owner | Accountable data owner |
| Steward | Operational data steward |
| Source | Originating source |
| Acquisition Method | How data was obtained |
| Collection Context | Relevant context |
| Version | Approved version |
| Transformations | Material processing steps |
| Dependencies | Systems or external sources |
| Restrictions | Applicable controls |
| Quality Status | Current quality assessment |
| Integrity Status | Current integrity assessment |
| Known Limitations | Relevant limitations |
| Downstream Use | AI systems/processes using the data |
| Change History | Material changes |
| Approval Status | Current governance status |

## 20. Assurance Levels

A working five-level provenance assurance scale may be used:

- **P1 — Minimal Traceability:** Basic source information available.
- **P2 — Documented Provenance:** Source, ownership, purpose, and version established.
- **P3 — Controlled Lineage:** Material transformations and dependencies traceable.
- **P4 — Assured Lineage:** Provenance and lineage independently verified to an appropriate level.
- **P5 — High-Consequence Traceability:** Strong end-to-end traceability supporting consequential operational assurance and investigation.

These are D-AIGAAF working constructs and should be adapted to the organisation's established assurance terminology.

## 21. Operational Authorisation Considerations

Operational authorisation should consider whether:

- critical data sources are known;
- provenance is sufficiently established;
- material transformations are documented;
- data dependencies are controlled;
- lineage supports investigation;
- provenance limitations have been assessed;
- changes can be detected and governed;
- evidence is adequate for the authorised mission and environment.

An AI capability should not receive unrestricted operational authority merely because its technical performance is satisfactory if critical data provenance remains materially uncertain.

## 22. Common Failure Modes

Common weaknesses include:

- treating dataset names as sufficient provenance;
- losing lineage during data transformation;
- using undocumented third-party datasets;
- failing to version datasets;
- assuming synthetic data represents operational reality;
- retaining model outputs without their input context;
- allowing uncontrolled data updates;
- separating data records from AI assurance records;
- failing to document known provenance gaps;
- treating provenance as a compliance exercise rather than an operational assurance mechanism.

## 23. Core Rules

1. Know the origin of consequential data.
2. Preserve material lineage through the AI lifecycle.
3. Record significant transformations.
4. Maintain dataset and data-asset version control.
5. Treat unknown provenance as uncertainty.
6. Link data provenance to AI assurance.
7. Assess material data changes before operational use.
8. Protect provenance records against unauthorised alteration.
9. Maintain sufficient traceability to support investigation and accountability.
10. Scale provenance requirements with consequence, dependence, uncertainty, and exposure.

## 24. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **05 Data & Information** — data governance, quality, representativeness, lifecycle;
- **04 AI Lifecycle** — development, testing, deployment, change and revalidation;
- **03 Risk & Autonomy** — data uncertainty and consequence;
- **06 AI Security** — integrity, access and tamper protection;
- **07 Supply Chain & Sovereignty** — external sources and dependencies;
- **09 TEVV** — evidence and test-data traceability;
- **11 Operational Authorisation** — evidence supporting authority;
- **13 Continuous Assurance** — monitoring for provenance and lineage changes;
- **15 Change & Reauthorisation** — governance of material data changes;
- **16 Audit & Evidence** — reconstruction and accountability.

## 25. Summary

The key question is:

> **Can the organisation trace consequential data from its origin through material transformations to its use by the AI system, and can it demonstrate that this lineage is sufficiently trustworthy for the authorised mission?**

If the answer is no, the resulting uncertainty must be visible in the assurance and operational-authorisation process.
