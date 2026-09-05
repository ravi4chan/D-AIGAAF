# Data Assurance and Lifecycle

## 1. Purpose

This document defines how D-AIGAAF assures data throughout its lifecycle, from identification and acquisition through operational use, monitoring, change, retention, and disposal.

The objective is to ensure that data remains sufficiently trustworthy, controlled, fit for purpose, and traceable for the AI capability and mission for which it is used.

## 2. Core Principle

> **Data assurance is a continuous lifecycle activity; data that was acceptable at one point in time is not automatically acceptable for continued or changed operational use.**

Data assurance should therefore remain connected to AI assurance, operational risk, and operational authorisation throughout the lifecycle.

## 3. Scope

This document covers:

- data assurance planning;
- data lifecycle controls;
- data validation;
- data quality and integrity;
- provenance and lineage;
- representativeness;
- operational monitoring;
- data incidents;
- data sharing;
- retention;
- disposal;
- lifecycle records;
- data changes;
- revalidation and reauthorisation.

## 4. Data Lifecycle

The D-AIGAAF data lifecycle is:

**Identify → Acquire → Validate → Prepare → Use → Monitor → Change → Revalidate → Retain / Dispose**

The lifecycle should be applied proportionately to the consequence and sensitivity of the data and its dependence within the AI capability.

## 5. Data Assurance Objectives

Data assurance should establish that data is:

- appropriate for its intended purpose;
- sufficiently accurate;
- sufficiently complete;
- sufficiently representative;
- traceable to its source;
- protected against unauthorised alteration;
- handled according to applicable restrictions;
- available when required;
- monitored for material change;
- governed throughout its lifecycle.

Not every objective requires the same level of control for every dataset.

## 6. Data Assurance Planning

For consequential AI capabilities, a Data Assurance Plan should identify:

- critical data assets;
- data owners and stewards;
- intended uses;
- data dependencies;
- required quality characteristics;
- provenance requirements;
- representativeness requirements;
- integrity controls;
- monitoring requirements;
- change thresholds;
- incident triggers;
- retention requirements;
- evidence requirements.

The plan should align with the AI system's assurance and operational-authorisation requirements.

## 7. Data Validation

Before material use, data should be assessed against appropriate criteria.

Validation may include:

- schema and format checks;
- completeness checks;
- consistency checks;
- source verification;
- integrity verification;
- duplicate detection;
- anomaly detection;
- provenance checks;
- representativeness assessment;
- domain-expert review.

Validation should be proportionate to the consequence of incorrect or misleading AI outputs.

## 8. Data Acceptance

A data asset should have an explicit status appropriate to its intended use.

A practical working model is:

- **Proposed** — identified but not yet assessed;
- **Under Validation** — assessment in progress;
- **Accepted** — suitable for the defined purpose;
- **Conditionally Accepted** — usable subject to stated limitations;
- **Restricted** — use limited pending corrective action;
- **Rejected** — unsuitable for the intended purpose;
- **Retired** — no longer approved for use.

Acceptance for one purpose does not automatically establish acceptance for another.

## 9. Fitness for Purpose

Data fitness should be assessed against:

**Purpose → Mission → Consequence → Required Data Characteristics → Evidence**

A dataset may be technically valid while being operationally unsuitable.

Examples include data that is:

- too old for the intended decision;
- insufficiently representative;
- collected under different conditions;
- missing important classes or events;
- unsuitable for the authorised environment;
- subject to unresolved provenance uncertainty.

## 10. Data Monitoring

Operational monitoring should consider changes that could affect AI behaviour.

Depending on the capability, monitoring may include:

- data quality;
- data completeness;
- source availability;
- distribution changes;
- integrity indicators;
- anomaly rates;
- missing-data patterns;
- sensor characteristics;
- data-source changes;
- operational outcomes.

Monitoring should generate actionable thresholds rather than simply collecting metrics.

## 11. Data Assurance Status

A working status model is:

**Normal → Watch → Alert → Restricted → Suspended → Revalidation Required**

The meaning and trigger conditions should be defined for each consequential capability.

A status change should result in an appropriate response rather than becoming a passive reporting event.

## 12. Data Incidents

A data incident is any event that may materially affect the confidentiality, integrity, availability, provenance, quality, representativeness, or authorised use of data.

Examples include:

- unauthorised modification;
- corrupted data;
- compromised source;
- loss of provenance;
- suspected poisoning;
- unexpected distribution shift;
- unauthorised access;
- incorrect labelling;
- data leakage;
- loss of critical data;
- use outside authorised purpose.

Data incidents should be connected to the relevant AI incident and operational risk processes.

## 13. Data Incident Response

A general response pathway is:

**Detect → Contain → Assess → Inform → Decide → Recover → Revalidate → Reauthorise if Required**

Where continued AI use could create unacceptable risk, predefined restrictions or suspension should be available.

Emergency procedures should permit immediate protective action where delay could create unacceptable harm.

## 14. Data Sharing

Data sharing should consider:

- authority to share;
- intended purpose;
- recipient eligibility;
- classification and handling restrictions;
- integrity requirements;
- provenance;
- onward-use controls;
- retention requirements;
- security requirements;
- accountability.

Technical ability to transfer data does not establish authority to share it.

## 15. External and Third-Party Data

External data should receive assurance proportionate to its operational importance.

The assessment should consider:

- source reliability;
- provenance;
- acquisition conditions;
- integrity;
- quality;
- representativeness;
- legal or contractual restrictions;
- dependency risk;
- update mechanisms;
- ability to independently verify material claims.

Critical external data dependencies should be visible in the AI system's assurance record.

## 16. Data Retention

Retention should be based on:

- operational need;
- assurance requirements;
- investigation requirements;
- legal and policy obligations;
- security requirements;
- privacy requirements where applicable;
- historical traceability needs;
- storage and access risks.

Retention should not mean indefinite storage of all data.

For consequential AI systems, sufficient records should remain available to support reconstruction of important decisions and assurance conclusions, subject to applicable restrictions.

## 17. Data Disposal

Disposal should be controlled and documented where the data is consequential, sensitive, or required for assurance.

Disposal processes should address:

- authorised disposal;
- verification;
- applicable copies and replicas;
- backups where relevant;
- derived datasets;
- associated metadata;
- provenance records;
- retention obligations.

Disposal of operational data should not unintentionally destroy evidence required for an active investigation or assurance activity.

## 18. Data Change Management

Material changes to data should be assessed before continued use.

Changes may include:

- new sources;
- changed source systems;
- changed collection methods;
- changed preprocessing;
- changed labels;
- changed schemas;
- changed distributions;
- new synthetic-data generation;
- changed data dependencies.

A working change classification is:

- **Class 0 — Administrative:** No meaningful effect on data meaning or AI behaviour.
- **Class 1 — Minor:** Limited effect with no expected material operational impact.
- **Class 2 — Controlled:** Potentially meaningful effect requiring documented assessment.
- **Class 3 — Material:** Likely effect on AI behaviour or assurance; revalidation normally required.
- **Class 4 — Critical:** Significant potential effect on operational risk; use may require restriction, suspension, and reauthorisation.

## 19. Data Revalidation

Revalidation should be considered when:

- data changes materially;
- distribution drift exceeds thresholds;
- a new operational environment is introduced;
- a new sensor or source is introduced;
- a significant incident occurs;
- data assumptions are found to be incorrect;
- model behaviour changes in ways attributable to data;
- assurance evidence becomes outdated.

The required depth of revalidation should depend on the nature and consequence of the change.

## 20. Data and Operational Authorisation

Operational authorisation should consider whether critical data dependencies are:

- identified;
- sufficiently assured;
- controlled;
- representative of the authorised environment;
- monitored;
- subject to defined change thresholds;
- supported by adequate evidence.

Where data assurance materially deteriorates, the conditions of operational authorisation may need to change.

## 21. Data Assurance Record

A Data Assurance Record should contain, where appropriate:

| Field | Description |
|---|---|
| Data Asset ID | Unique identifier |
| Purpose | Intended use |
| Owner | Accountable owner |
| Steward | Data steward |
| Classification / Restrictions | Applicable handling controls |
| Provenance Status | Source and lineage confidence |
| Quality Status | Current quality assessment |
| Representativeness Status | Current coverage assessment |
| Integrity Status | Current integrity assessment |
| Assurance Level | Current assurance level |
| Dependencies | Relevant systems and sources |
| Monitoring | Active controls and indicators |
| Change History | Material changes |
| Incidents | Relevant data incidents |
| Retention | Approved retention requirement |
| Disposal Status | Current lifecycle state |
| Evidence | Supporting assurance records |
| Approval | Responsible authority |

## 22. Assurance Levels

A working five-level data assurance scale may be used:

- **D1 — Basic:** Limited assurance and low dependency.
- **D2 — Controlled:** Core governance and validation established.
- **D3 — Assured:** Quality, provenance, integrity and representativeness adequately demonstrated.
- **D4 — Operationally Assured:** Data assurance demonstrated for the authorised operational context.
- **D5 — High-Consequence Assurance:** Strong continuous assurance appropriate to highly consequential AI use.

These are D-AIGAAF working constructs and should be mapped to established organisational terminology before formal adoption.

## 23. Evidence

Data assurance evidence may include:

- validation results;
- quality assessments;
- provenance records;
- lineage records;
- distribution analyses;
- drift reports;
- integrity checks;
- incident reports;
- change assessments;
- revalidation results;
- approvals;
- monitoring records;
- audit records.

Evidence should be sufficiently traceable to support independent review and operational accountability.

## 24. Golden Thread

Data assurance should connect to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Dependency → Data Controls → Validation → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation**

This ensures that data governance is connected to operational consequences rather than operating as an isolated technical process.

## 25. Common Failure Modes

Common weaknesses include:

- treating data assurance as a one-time activity;
- accepting data without a clearly defined purpose;
- failing to monitor operational data;
- losing provenance during transformations;
- ignoring data drift;
- allowing uncontrolled updates;
- retaining data without governance;
- disposing of evidence required for investigation;
- failing to reassess external data;
- failing to connect data incidents to AI and operational risk;
- assuming technically accessible data is authorised for use.

## 26. Core Rules

1. Govern data throughout its lifecycle.
2. Define fitness for purpose against the mission and operational context.
3. Validate data before consequential use.
4. Maintain provenance, lineage, quality and integrity controls.
5. Monitor data for material change after deployment.
6. Establish clear data assurance states and response thresholds.
7. Treat material data changes as potential assurance events.
8. Connect data incidents to AI and operational risk management.
9. Retain sufficient evidence for accountability and investigation.
10. Revalidate and reauthorise where data changes materially affect operational assurance.

## 27. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **03 Risk & Autonomy** — consequence and uncertainty;
- **04 AI Lifecycle** — lifecycle controls and change;
- **05 Data & Information** — governance, quality, provenance and representativeness;
- **06 AI Security** — integrity, access and data compromise;
- **07 Supply Chain & Sovereignty** — external data dependencies;
- **09 TEVV** — evidence and validation;
- **11 Operational Authorisation** — data conditions supporting authority;
- **13 Continuous Assurance** — ongoing data monitoring;
- **14 Incident & Fail-Safe** — response to data-related incidents;
- **15 Change & Reauthorisation** — material data changes;
- **16 Audit & Evidence** — records and traceability;
- **26 Retirement & Decommissioning** — final data disposition.

## 28. Summary

The key question is:

> **Can the organisation demonstrate that the data supporting the AI capability remains fit for its authorised purpose throughout its lifecycle, and can it detect, respond to, and evidence changes that could affect operational risk?**

If not, the resulting uncertainty must be reflected in assurance, operational constraints, and authorisation decisions.
