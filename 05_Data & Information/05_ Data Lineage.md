# D-AIGAAF — Data Lineage

## 1. Purpose

This document defines the governance and assurance approach for maintaining traceability of data as it moves through the AI lifecycle.

Data lineage establishes the relationship between:

**Source Data → Data Processing → Derived Data → Dataset → AI Use → AI Output**

The purpose is to enable the organisation to determine what data contributed to an AI capability or decision, how that data was transformed, and whether those transformations remain authorised and trustworthy.

---

## 2. Core Principle

> **For consequential AI, material data transformations must be traceable sufficiently to establish how source information became the data used by the AI capability.**

Data lineage is therefore an assurance mechanism, not merely a documentation exercise.

---

## 3. Scope

This document applies to:

- source datasets
- data ingestion
- preprocessing
- filtering
- cleaning
- transformation
- aggregation
- annotation
- feature engineering
- dataset creation
- model inputs
- operational data pipelines
- data exchange
- derived information
- AI outputs where input traceability is required
- third-party and supplier data
- synthetic and simulated data

---

## 4. Data Lineage Objectives

Lineage should enable the organisation to establish:

1. where data originated
2. who or what introduced it
3. how it was collected
4. how it was transformed
5. what systems processed it
6. which datasets were derived from it
7. which AI systems consumed it
8. which outputs depended on it
9. whether transformations were authorised
10. whether material changes can be reconstructed

---

## 5. Lineage Chain

A practical lineage chain is:

**Source → Collection → Ingestion → Validation → Processing → Transformation → Storage → Dataset → Model/System Input → AI Processing → Output**

For consequential decisions, the chain should extend where feasible to:

**AI Output → Human Assessment → Human Decision → Authorised Action → Outcome**

---

## 6. Lineage Levels

A working lineage model may include:

### L0 — Unknown

Origin and transformation history cannot be established.

### L1 — Source Identified

Primary source is known, but processing history is incomplete.

### L2 — Basic Traceability

Major processing and transformation stages are recorded.

### L3 — Controlled Lineage

Material transformations, versions and dependencies are recorded and governed.

### L4 — Strong Lineage

End-to-end lineage supports reconstruction of material data flows and AI dependencies.

### L5 — High-Assurance Lineage

Lineage is independently verifiable and sufficiently detailed for highly consequential use.

These are D-AIGAAF working constructs and should be mapped to applicable organisational and defence requirements before formal adoption.

---

## 7. Source Identification

Each material source should have a unique identifier where practical.

Source records may include:

- source ID
- owner
- origin
- collection method
- date/time
- geographic or operational context
- classification/handling requirements
- integrity status
- access conditions
- quality information
- provenance information

---

## 8. Collection Lineage

Collection records should establish:

- what was collected
- when it was collected
- how it was collected
- by which system or process
- under what authorised purpose
- relevant collection conditions
- applicable limitations

Where collection conditions affect AI behaviour, they should form part of the assurance evidence.

---

## 9. Ingestion Lineage

Ingestion records should identify:

- source
- receiving system
- ingestion time
- ingestion method
- validation performed
- transformations introduced
- errors detected
- rejected or modified records

The objective is to distinguish source data from the version actually accepted into an AI data pipeline.

---

## 10. Processing Lineage

Processing may include:

- cleaning
- filtering
- normalisation
- deduplication
- formatting
- conversion
- aggregation
- interpolation
- imputation

Each material processing step should be identifiable and reproducible where feasible.

---

## 11. Transformation Lineage

Transformations can materially affect AI behaviour.

Examples include:

- coordinate conversion
- unit conversion
- image processing
- text processing
- feature extraction
- compression
- resampling
- aggregation
- anonymisation or redaction
- data balancing

Material transformations should be documented with sufficient information to understand their potential impact.

---

## 12. Versioning

Lineage should be connected to version control.

Relevant objects may include:

- source version
- dataset version
- transformation version
- pipeline version
- annotation version
- model version
- configuration version
- system version

This allows the organisation to establish which data state supported a particular assurance claim.

---

## 13. Dataset Lineage

A dataset should be traceable to its constituent sources and transformations.

Where practical, record:

**Dataset ID → Source IDs → Processing Steps → Transformation Versions → Validation Results**

This should support reconstruction of the dataset's material composition.

---

## 14. Training Data Lineage

Training data lineage should establish:

- source datasets
- dataset versions
- preprocessing
- filtering
- annotation
- augmentation
- synthetic data
- sampling
- balancing
- exclusions
- final training dataset

Training-data lineage should remain associated with the relevant model version.

---

## 15. Validation and Test Data Lineage

Validation and test data should have independent lineage records.

Lineage should help demonstrate:

- source independence where required
- transformation history
- dataset version
- contamination controls
- sampling approach
- relevant representativeness
- evaluation configuration

This is particularly important where performance results support operational authorisation.

---

## 16. Synthetic Data Lineage

Synthetic data should record:

- generation method
- generating system
- source/reference data
- generation parameters
- generation date
- validation method
- intended use
- known limitations

Synthetic data should remain distinguishable from real-world observations throughout the lineage chain.

---

## 17. Annotation Lineage

For labelled datasets, lineage should identify:

- source data
- annotation process
- annotation guidance
- annotator or annotation system where appropriate
- annotation version
- quality checks
- corrections
- disputed cases

Material annotation changes should result in a new controlled dataset version where appropriate.

---

## 18. Third-Party Data Lineage

Supplier and third-party data should have sufficient lineage to establish:

- provider
- source
- acquisition method
- version
- transformations
- contractual restrictions
- classification/handling conditions
- known limitations
- dependencies

Where third-party lineage is incomplete, the limitation should be reflected in risk and assurance.

---

## 19. Operational Data Lineage

Operational data lineage should support understanding of:

- data source
- collection time
- processing path
- transformation
- system consumption
- output dependency

For high-consequence decisions, sufficient records should exist to reconstruct the relevant information path subject to applicable security and retention requirements.

---

## 20. AI Input Lineage

Where technically feasible, consequential AI inputs should be traceable to the data or information used to generate the output.

The objective is to support:

**Input → Processing → Output**

rather than merely recording the final AI answer.

This enables post-event analysis of whether an output was affected by:

- incorrect data
- stale information
- conflicting sources
- missing information
- processing errors
- unexpected transformations

---

## 21. Output Lineage

Where required by risk and mission context, outputs should be linked to:

- input data
- model version
- system configuration
- relevant processing state
- timestamp
- operating conditions

Output lineage should support investigation without implying that every AI output can always be explained causally.

---

## 22. Human Decision Lineage

For consequential decisions, the broader chain may be:

**Data Source → Data Used → AI Output → Human Assessment → Human Decision → Authorised Action → Outcome**

This does not transfer responsibility from the human decision maker to the AI system.

Instead, it supports reconstruction of the circumstances surrounding the decision.

---

## 23. Lineage and Provenance

Provenance answers:

**Where did the data come from?**

Lineage answers:

**How did the data move and change through the system?**

They are closely related but distinct.

A system may know the original source while lacking sufficient information about subsequent transformations.

Conversely, a detailed processing log is of limited value if the original source cannot be established.

---

## 24. Lineage and Data Quality

Lineage supports data-quality assessment by identifying where quality may have changed.

Potential points of degradation include:

- ingestion
- conversion
- filtering
- aggregation
- compression
- annotation
- transformation
- transmission
- storage

Quality assessments should therefore be associated with relevant lineage stages where material.

---

## 25. Lineage and Data Integrity

Lineage records should themselves be protected against unauthorised modification.

Controls may include:

- access control
- version control
- audit logging
- integrity verification
- controlled change
- immutable or protected records where appropriate

If lineage can be silently altered, confidence in reconstruction is reduced.

---

## 26. Lineage and Classification / Handling

Lineage information may itself reveal sensitive information about:

- data sources
- system relationships
- collection processes
- operational dependencies
- suppliers
- infrastructure

Lineage records should therefore receive appropriate classification and handling controls.

The need for traceability does not override applicable security requirements.

---

## 27. Lineage and AI Security

AI security should consider attacks or failures that disrupt lineage.

Examples include:

- unauthorised data substitution
- pipeline manipulation
- deletion of transformation records
- source spoofing
- metadata tampering
- hidden processing changes

Loss of lineage can reduce the ability to detect or investigate AI security incidents.

---

## 28. Lineage and Supply Chain

For externally developed AI systems and data pipelines, lineage should extend to material supplier dependencies where feasible.

Relevant dependencies may include:

- data providers
- model providers
- preprocessing components
- external services
- software libraries
- model weights
- update mechanisms

The organisation should understand which dependencies can materially alter AI behaviour.

---

## 29. Lineage and TEVV

TEVV evidence should identify the relevant data lineage supporting the test.

This allows evaluators to determine:

- what data was tested
- which version was tested
- how it was processed
- whether the data was representative
- whether results remain applicable after changes

A test result without adequate lineage may have limited reproducibility and assurance value.

---

## 30. Lineage and Operational Authorisation

Operational authorisation should be based on an understood configuration.

Where data lineage is material to the assurance case, authorisation should identify:

- approved data sources
- approved pipelines
- material transformations
- relevant versions
- known lineage limitations
- monitoring requirements

Material changes to these elements may require reassessment.

---

## 31. Lineage and Change Management

Changes should be assessed when they affect the established lineage.

Examples include:

- new source
- removed source
- new processing stage
- changed transformation
- new data pipeline
- changed supplier
- changed dataset composition
- changed annotation
- changed model dependency

The impact of the change should determine whether revalidation or reauthorisation is required.

---

## 32. Lineage and Incident Investigation

Following an AI or data incident, lineage should help answer:

1. What data was involved?
2. Where did it originate?
3. What transformations occurred?
4. Which system consumed it?
5. Which model/configuration was active?
6. Which output or decision may have been affected?
7. Were other systems or datasets affected?
8. What controls failed?
9. Is previous assurance still valid?

---

## 33. Lineage Monitoring

Where technically feasible, monitoring should detect:

- unexpected source changes
- pipeline changes
- missing lineage records
- unapproved transformations
- unexpected dependencies
- version mismatches
- unexplained data paths

Material lineage anomalies should trigger investigation.

---

## 34. Lineage Assessment Method

A practical assessment can follow:

1. Identify the mission and AI use.
2. Identify material data dependencies.
3. Identify sources.
4. Map the data flow.
5. Record material transformations.
6. Establish version relationships.
7. Assess lineage completeness.
8. Identify gaps.
9. Assess operational consequence.
10. Apply controls.
11. Test reconstruction.
12. Record evidence.
13. Monitor material changes.

---

## 35. Lineage Completeness

A working completeness scale may be:

### LC0 — Unknown

Material lineage cannot be established.

### LC1 — Partial

Source or major processing stages are known, but significant gaps remain.

### LC2 — Substantial

Most material sources and transformations are traceable.

### LC3 — Controlled

Material lineage is versioned, governed and auditable.

### LC4 — End-to-End

Relevant data flows can be reconstructed from source through AI use.

These are D-AIGAAF working constructs and should be mapped to applicable organisational requirements before formal adoption.

---

## 36. Data Lineage Record

A Data Lineage Record should include:

| Field | Description |
|---|---|
| Lineage ID | Unique identifier |
| Data Asset ID | Data being traced |
| Source | Origin |
| Collection | Collection details |
| Processing | Processing stages |
| Transformations | Material transformations |
| Versions | Relevant versions |
| Dataset | Resulting dataset |
| AI System | Consuming system |
| Model | Relevant model version |
| Output | Relevant output where required |
| Dependencies | External dependencies |
| Integrity | Integrity controls |
| Limitations | Known gaps |
| Evidence | Supporting evidence |
| Owner | Accountable owner |
| Review Date | Review date |

---

## 37. Reconstruction Test

For higher-consequence capabilities, lineage should be tested through reconstruction exercises.

A reconstruction test should determine whether an authorised reviewer can establish, within the available records:

**What data → From where → Through what transformations → Into which AI configuration → Producing what relevant output**

The test should record:

- reconstruction scope
- records used
- gaps
- elapsed effort/time
- result
- corrective actions

---

## 38. Common Failure Modes

- Recording source names but not transformations.
- Losing dataset version information.
- Changing preprocessing without updating lineage.
- Treating lineage as a documentation-only activity.
- Failing to connect lineage to model versions.
- Mixing training and evaluation lineage.
- Losing operational input records.
- Allowing third-party data to enter without adequate traceability.
- Failing to protect lineage records.
- Assuming provenance automatically provides complete lineage.
- Retaining outputs without retaining sufficient input/configuration context.
- Being unable to reconstruct the data path after an incident.

---

## 39. Core Rules

1. **Material data flows should be traceable.**
2. **Source identification alone is not sufficient; material transformations must also be understood.**
3. **Lineage should be linked to dataset, model and system versions.**
4. **Training, validation and test data should maintain distinct lineage where required.**
5. **Synthetic and third-party data should remain identifiable through the lineage chain.**
6. **Material transformations should be governed and documented.**
7. **Lineage records should be protected against unauthorised modification.**
8. **Operationally consequential data paths should support reconstruction where feasible.**
9. **Material lineage changes require impact assessment.**
10. **Lineage gaps should be visible in risk and assurance.**
11. **Lineage evidence should support TEVV, incident investigation and operational authorisation.**
12. **Lineage must remain connected to the D-AIGAAF Golden Thread.**

---

## 40. Golden Thread

Data lineage contributes to:

**Mission Need → Requirements → Data Dependency → Source → Processing → Transformation → Dataset → AI System → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Incident / Change → Revalidation → Reauthorisation**

The objective is to establish:

**Where the data came from → How it changed → Where it was used → What AI behaviour or decision it supported → Whether the relevant evidence remains valid**

---

## 41. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **02 Mission & Use Case**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Governance**
- **05 Data & Information — Data Provenance**
- **05 Data & Information — Data Quality**
- **05 Data & Information — Data Representativeness**
- **06 AI Security**
- **07 Supply Chain & Sovereignty**
- **09 TEVV**
- **11 Operational Authorisation**
- **13 Continuous Assurance**
- **14 Incident & Fail-Safe**
- **15 Change & Reauthorisation**
- **16 Audit & Evidence**
- **24 Architecture & Technical Controls**

---

## 42. Summary

Data lineage provides the traceability needed to connect source information to AI use and, where required, consequential decisions.

The central chain is:

**Source → Processing → Transformation → Dataset → AI Input → AI Output → Human Decision → Outcome**

For consequential defence AI, the governing question is:

> **Can the organisation reconstruct how material data moved and changed from its source to the AI capability, and determine whether that lineage remains authorised and trustworthy?**

Where the answer is no, the limitation should be reflected in **risk, assurance, operational restrictions and—where necessary—revalidation or reauthorisation**.
