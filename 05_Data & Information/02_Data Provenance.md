# D-AIGAAF — Data Provenance

## 1. Purpose

This document defines governance requirements for establishing, recording, assessing, and maintaining the provenance of data used by defence AI capabilities.

Data provenance provides evidence about **where data came from, how it was collected, how it was transformed, who controlled it, and how it reached the point of use**.

For consequential AI, provenance is an assurance requirement because unknown or unreliable data origins can undermine confidence in model behaviour, operational decisions, security, and mission outcomes.

---

## 2. Core Principle

> **For consequential AI use, the organisation should know enough about where data came from and how it changed to determine whether it can be trusted for the intended purpose.**

Provenance does not mean that every historical detail must always be recoverable. The required level of provenance should be proportionate to:

**Consequence × Data Dependence × Exposure × Assurance Need**

---

## 3. Scope

This document applies to provenance of:

- training data
- validation and test data
- operational data
- sensor-derived information
- intelligence and information inputs
- geospatial and reference data
- human-generated data
- synthetic data
- labelled and annotated datasets
- supplier-provided datasets
- data received from partner organisations
- transformed and derived datasets
- AI outputs reused as downstream inputs
- data retained for TEVV, assurance, audit, or investigation

---

## 4. Provenance Objectives

The provenance framework should enable the organisation to establish, where appropriate:

1. **Origin** — where the data came from.
2. **Source authority** — who or what was responsible for providing it.
3. **Collection context** — how and under what conditions it was obtained.
4. **Time** — when it was collected or generated.
5. **Transformation history** — what happened to the data before use.
6. **Custody** — who controlled or processed it.
7. **Version** — which version was used.
8. **Integrity** — whether unauthorised alteration can be detected.
9. **Permitted use** — whether it may lawfully and appropriately be used for the intended purpose.
10. **Downstream dependency** — which AI capabilities depend on it.

---

## 5. Provenance Model

A useful provenance chain is:

**Source → Collection → Ingestion → Processing → Transformation → Storage → Transfer → Dataset → AI Use → Output**

Each stage should preserve sufficient metadata to support the required level of traceability.

---

## 6. Source Identification

For material data, the source should be identified where practicable.

Source information may include:

- organisation
- system
- sensor
- database
- individual or authorised contributor
- external provider
- partner organisation
- synthetic-data generation process
- public or commercial source
- derived internal source

Where the source cannot be reliably established, the uncertainty should be recorded.

---

## 7. Source Trust

Provenance and trustworthiness are related but not identical.

Knowing where data came from does not automatically establish that it is accurate.

Source assessment may consider:

- reliability history
- collection methodology
- authority
- independence
- known limitations
- susceptibility to manipulation
- consistency with other sources
- security controls
- validation history

A well-documented source may still produce unreliable data.

---

## 8. Collection Context

Where material to intended use, provenance should capture the context in which data was collected.

Relevant information may include:

- collection method
- collection system
- collection conditions
- relevant environmental conditions
- sensor or instrument characteristics
- collection time
- geographic or contextual information
- preprocessing performed at collection
- known collection limitations

The purpose is to allow later assessment of whether the data represents the conditions for which the AI capability is intended.

---

## 9. Temporal Provenance

Time can materially affect data validity.

Where relevant, provenance should distinguish:

- collection time
- processing time
- publication time
- ingestion time
- AI-use time
- last update time

For dynamic operational data, stale information may create greater risk than technically inaccurate information.

---

## 10. Transformation History

Material transformations should be traceable.

Examples include:

- filtering
- cleaning
- normalisation
- conversion
- aggregation
- annotation
- labelling
- augmentation
- sampling
- feature extraction
- redaction
- compression
- format conversion

Transformations that can affect AI behaviour should be treated as configuration-relevant where appropriate.

---

## 11. Dataset Lineage

Derived datasets should maintain a relationship to their source datasets.

The lineage should allow reconstruction of:

**Source Dataset → Transformation → Derived Dataset → Model / System Use**

Where multiple sources contribute to a dataset, the relationship should be recorded to the extent necessary for assurance.

---

## 12. Provenance and Data Labelling

Labels and annotations can materially influence AI behaviour.

Provenance should consider:

- who created the labels
- how labels were generated
- labelling guidance
- annotation tools
- quality checks
- disagreement resolution
- subsequent corrections
- version history

Where automated or AI-assisted labelling is used, the provenance chain should identify that process.

---

## 13. Synthetic Data Provenance

Synthetic data should not be treated as provenance-free.

Where synthetic data is used, provenance should identify:

- generation method
- generating model or system
- source data or assumptions
- generation configuration
- generation date
- filtering or selection
- validation performed
- intended use
- known limitations

Synthetic data may introduce characteristics that differ from real operational data and should therefore be assessed for representativeness.

---

## 14. Supplier and Third-Party Provenance

Supplier-provided data should include, where available:

- original source
- collection method
- processing history
- transformation history
- ownership
- licensing or permitted use
- update process
- known limitations
- validation evidence
- dependencies

Where the supplier cannot provide sufficient provenance, the resulting uncertainty should be recorded.

Supplier confidentiality or intellectual-property restrictions should not automatically justify complete absence of provenance information for high-consequence use.

---

## 15. Data from Partner Organisations

Data received from another organisation should retain provenance relating to:

- originating organisation
- transferring organisation
- transfer date
- transfer mechanism
- applicable handling restrictions
- validation status
- known limitations

Trust in the sending organisation does not remove the receiving organisation's responsibility to assess fitness for purpose.

---

## 16. Provenance and Data Classification

Provenance information itself may require controlled handling.

The organisation should assess whether provenance metadata reveals:

- sensitive sources
- system relationships
- collection methods
- operational dependencies
- security-relevant information
- supplier-sensitive information

Provenance should therefore be sufficiently detailed for assurance without creating unnecessary exposure.

---

## 17. Provenance and Data Integrity

Provenance is useful only if the provenance record itself can be trusted.

Controls should address:

- unauthorised modification
- deletion
- insertion
- timestamp manipulation
- version substitution
- metadata corruption
- loss of lineage

For consequential systems, appropriate integrity mechanisms should allow material provenance changes to be detected.

---

## 18. Provenance and Access Control

Not every user needs access to all provenance information.

Access should be based on:

- role
- mission need
- data sensitivity
- assurance responsibility
- investigation requirements
- security requirements

However, access restrictions should not prevent authorised assurance, audit, or investigation functions from reconstructing relevant provenance.

---

## 19. Provenance and AI Training

For model development, provenance should support identification of:

- training dataset version
- source datasets
- transformations
- filtering
- labelling
- augmentation
- exclusions
- data-generation processes
- relevant data-quality assessments

The objective is reproducibility and defensibility of model-development evidence.

---

## 20. Provenance and Validation / Test Data

Validation and test datasets should be traceable to their source and preparation history.

This should support assessment of:

- whether test data was independent
- whether leakage occurred
- whether data was representative
- whether transformations were appropriate
- whether the test remains valid after data changes

A test result without adequate knowledge of the underlying data may have limited assurance value.

---

## 21. Provenance and Operational Data

For operational AI, provenance should support reconstruction of important information inputs.

Where feasible, the organisation should be able to determine:

**What information → From which source → At what time → In which form → Used by which capability → Produced what output**

The required level of recording should be proportionate to mission consequence and operational feasibility.

---

## 22. Provenance and Human Decisions

Where AI contributes to consequential human decisions, provenance can support reconstruction of the information basis for that decision.

The broader accountability chain is:

**Data Source → Data Used → AI Output → Human Assessment → Human Decision → Authorised Action → Outcome**

This does not imply that every decision must expose sensitive source details to every user. It requires that authorised review functions can establish an adequate evidence trail.

---

## 23. Provenance and Uncertainty

Provenance can itself be uncertain.

Examples include:

- unknown original source
- incomplete historical records
- unclear transformations
- uncertain timestamps
- undocumented manual changes
- supplier limitations

Such uncertainty should be explicitly represented rather than replaced with assumptions.

---

## 24. Provenance Confidence

A working provenance confidence scale may be:

### P0 — Unknown

Origin and history cannot be established sufficiently.

### P1 — Limited

Basic source information exists, but significant gaps remain.

### P2 — Traceable

Source and major processing stages are known.

### P3 — Strong

Source, processing, transformations and relevant custody are documented.

### P4 — High Confidence

Provenance is strongly evidenced, integrity-protected and sufficiently reproducible for high-consequence assurance.

These levels are a D-AIGAAF working construct and should be mapped to applicable organisational and national requirements before formal adoption.

---

## 25. Provenance Gaps

A provenance gap exists when required provenance information is:

- missing
- inconsistent
- unverifiable
- inaccessible
- corrupted
- outdated
- contradicted by other evidence

A provenance gap should be assessed for operational impact.

Possible responses include:

- accept with documented limitation
- restrict use
- seek additional evidence
- perform additional validation
- exclude affected data
- reduce autonomy
- suspend affected capability
- initiate revalidation

---

## 26. Provenance and Risk

Provenance risk should consider:

**Consequence × Data Dependence × Provenance Uncertainty × Exposure**

High provenance uncertainty should receive greater scrutiny when:

- the data strongly influences AI behaviour
- the AI supports consequential decisions
- autonomy is high
- operational conditions are adversarial
- data may have been manipulated
- the source is externally controlled

---

## 27. Provenance and TEVV

TEVV should consider whether provenance is sufficient to support the intended assurance claim.

Relevant questions include:

- Can the test dataset be reconstructed?
- Are source conditions known?
- Are transformations documented?
- Can test results be reproduced?
- Is the data independent of training data?
- Are provenance gaps material?
- Does operational data have comparable provenance?

Where provenance is inadequate, the assurance claim should reflect that limitation.

---

## 28. Provenance and Operational Authorisation

Operational authorisation may establish provenance-related conditions such as:

- approved data sources
- minimum provenance confidence
- prohibited unknown sources
- required source validation
- permitted third-party sources
- required integrity controls
- monitoring requirements
- escalation thresholds

A capability may be technically functional but unsuitable for authorised use if critical data provenance cannot be established.

---

## 29. Provenance and AI Security

Provenance should work with **06 AI Security** to identify:

- compromised sources
- manipulated datasets
- malicious substitutions
- poisoned training data
- compromised pipelines
- unauthorised transformations
- false provenance claims

Security controls should protect both data and the records describing its origin and history.

---

## 30. Provenance and Supply Chain

Provenance should extend beyond the immediate supplier.

For critical AI capabilities, the organisation should seek reasonable visibility into:

- originating data sources
- critical data processors
- transformations
- third-party datasets
- dependencies capable of changing data
- update mechanisms

Where complete visibility is not possible, the limitation should be recorded and reflected in supply-chain and assurance risk.

---

## 31. Provenance Change Management

Changes to provenance may occur when:

- data sources change
- suppliers change
- processing pipelines change
- labels are corrected
- datasets are merged
- records are migrated
- storage systems change
- data is reprocessed

Material provenance changes should trigger appropriate change-impact assessment.

---

## 32. Provenance Records

A Data Provenance Record should include, where applicable:

| Field | Description |
|---|---|
| Provenance ID | Unique identifier |
| Data Asset ID | Associated data asset |
| Source | Origin |
| Source Authority | Responsible entity |
| Collection Method | How obtained |
| Collection Time | When obtained |
| Processing | Processing history |
| Transformations | Material transformations |
| Custody | Responsible parties |
| Version | Data version |
| Integrity Status | Integrity evidence |
| Permitted Use | Approved use |
| Provenance Confidence | P0–P4 working level |
| Limitations | Known gaps |
| Dependencies | Systems/models using data |
| Review Date | Next review |

---

## 33. Provenance Evidence

Evidence may include:

- source records
- collection metadata
- system logs
- dataset manifests
- checksums or equivalent integrity mechanisms
- transformation records
- annotation records
- version histories
- transfer records
- supplier attestations
- validation reports
- independent verification

Evidence should be retained according to the consequence and assurance requirements of the capability.

---

## 34. Provenance Review

Provenance should be reviewed when:

- data changes
- source changes
- operational conditions change
- a data incident occurs
- a supplier changes
- a material anomaly is detected
- model behaviour changes unexpectedly
- assurance assumptions are challenged

Review may be periodic or event-driven.

---

## 35. Provenance During Incidents

When an AI-related incident occurs, provenance should support investigation of:

- which data was used
- where it came from
- whether it was altered
- what transformations occurred
- whether the source was compromised
- whether the data was within the validated envelope
- whether similar data remains in use

If provenance cannot be reconstructed, that limitation should itself be recorded as an incident or assurance finding where material.

---

## 36. Provenance During Retirement

Retirement should preserve provenance information required for:

- audit
- investigation
- lessons learned
- historical reconstruction
- legal or policy obligations
- assurance evidence

Decommissioning should not inadvertently destroy critical provenance records.

---

## 37. Common Failure Modes

- Treating source identification as sufficient provenance.
- Assuming trusted organisations always provide trustworthy data.
- Losing provenance during preprocessing.
- Merging datasets without preserving lineage.
- Using supplier data without understanding its origin.
- Treating synthetic data as equivalent to operational data.
- Failing to record label-generation processes.
- Allowing metadata to become separated from the dataset.
- Modifying data without updating provenance records.
- Storing provenance records without adequate integrity protection.
- Destroying provenance during system migration.
- Using data with material provenance gaps without recording the associated risk.

---

## 38. Core Rules

1. **Material data should have identifiable provenance wherever practicable.**
2. **Provenance does not automatically establish data accuracy or trustworthiness.**
3. **Material transformations should be traceable.**
4. **Derived datasets should retain links to their source data.**
5. **Synthetic data requires provenance and representativeness assessment.**
6. **Supplier data should have sufficient provenance for its intended consequence level.**
7. **Provenance records require appropriate integrity protection.**
8. **Unknown provenance should be treated as an explicit limitation.**
9. **Material provenance changes require impact assessment.**
10. **Operationally consequential AI decisions should have an appropriate information trail.**
11. **Provenance must remain connected to configuration and assurance evidence.**
12. **Critical provenance records should survive retirement where required for audit or investigation.**

---

## 39. Golden Thread

Provenance strengthens the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Source → Provenance → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement → Decommissioning**

The objective is to make the origin and history of consequential information sufficiently visible to support operational trust and accountability.

---

## 40. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Governance**
- **06 AI Security**
- **07 Supply Chain & Sovereignty**
- **08 Human Authority**
- **09 TEVV**
- **10 Operational Environment**
- **11 Operational Authorisation**
- **13 Continuous Assurance**
- **14 Incident & Fail-Safe**
- **15 Change & Reauthorisation**
- **16 Audit & Evidence**
- **24 Architecture & Technical Controls**
- **25 Documentation & Knowledge**
- **26 Retirement & Decommissioning**

---

## 41. Summary

Data provenance provides the evidence trail needed to understand the origin and evolution of information used by an AI capability.

The core chain is:

**Source → Collection → Transformation → Custody → Dataset → AI Use → Output → Decision**

For consequential defence AI, the governing question is:

> **Can the organisation establish enough of the data's origin and history to determine whether it is suitable, trustworthy and appropriately controlled for the authorised mission?**

Where the answer is uncertain, that uncertainty should flow into **risk, assurance, operational restrictions, and—where necessary—revalidation or reauthorisation**.
