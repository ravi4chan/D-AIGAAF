# Data Preparation

## Summary

Data Preparation governs the processes through which data is collected, selected, transformed, labelled, validated and prepared for use in developing, testing, evaluating or operating a defence AI capability.

D-AIGAAF treats data as a controlled lifecycle asset. Poor data quality, uncertain provenance, inappropriate representation or uncontrolled transformation can create risks that propagate into model behaviour and operational decisions.

The core chain is:

**Data Source → Provenance → Collection → Quality Assessment → Preparation → Labelling/Transformation → Validation → Controlled Dataset → Development/TEVV → Operational Use → Monitoring → Change/Reassessment**

---

## 1. Purpose

The Data Preparation process establishes controls for preparing data so that it is:

- relevant to the intended mission;
- sufficiently representative of intended conditions;
- appropriately labelled;
- traceable;
- sufficiently accurate;
- protected against inappropriate modification;
- suitable for its intended purpose;
- governed according to applicable legal, policy and security requirements.

---

## 2. Core Principle

AI performance is partly a function of the data on which the system is developed and evaluated.

Therefore:

**Data Quality ≠ Model Quality ≠ Operational Effectiveness**

High-quality data can support better model performance, but good training performance does not prove operational suitability.

Data preparation must consider the conditions under which the AI capability will actually operate.

---

## 3. Data Lifecycle Scope

Data preparation may include:

- source identification;
- collection;
- ingestion;
- filtering;
- cleaning;
- labelling;
- annotation;
- transformation;
- normalisation;
- augmentation;
- sampling;
- deduplication;
- quality assessment;
- dataset splitting;
- validation;
- versioning;
- storage;
- access control.

The applicable controls should be proportionate to the consequence and intended use of the AI capability.

---

## 4. Data Requirements

Data requirements should originate from:

- mission need;
- AI requirements;
- risk assessment;
- operational environment;
- model requirements;
- TEVV requirements;
- legal and policy obligations.

Requirements should establish, where applicable:

- acceptable quality;
- required coverage;
- representativeness;
- freshness;
- provenance;
- integrity;
- labelling accuracy;
- permitted use;
- retention;
- security.

---

## 5. Data Sources

Potential sources may include:

- operational sensors;
- simulations;
- synthetic data;
- public datasets;
- internal datasets;
- partner-provided datasets;
- commercially acquired datasets;
- generated data.

Each material source should be assessed for:

- provenance;
- reliability;
- relevance;
- quality;
- legal status;
- security classification or handling requirements where applicable;
- known limitations.

---

## 6. Data Provenance

Data provenance should establish, where practicable:

- source;
- origin;
- collection method;
- collection period;
- ownership;
- processing history;
- transformations;
- labelling history;
- version;
- permitted use;
- known limitations.

Provenance gaps should be recorded.

Where provenance cannot be established sufficiently for the intended use, the data should be subject to appropriate restriction or exclusion.

---

## 7. Data Quality

Data quality should be assessed against characteristics relevant to the use case.

These may include:

- accuracy;
- completeness;
- consistency;
- relevance;
- timeliness;
- integrity;
- uniqueness;
- representativeness.

Quality thresholds should be defined according to mission requirements rather than generic assumptions.

---

## 8. Data Representativeness

Data should reasonably represent the conditions under which the capability is expected to operate.

Consider variation in:

- environment;
- geography;
- terrain;
- weather;
- lighting;
- sensor type;
- sensor quality;
- data source;
- operational context;
- user behaviour;
- mission conditions;
- degraded conditions.

A dataset can be statistically large but operationally unrepresentative.

---

## 9. Data Coverage

Coverage should address relevant variation rather than merely dataset volume.

Assessment may consider:

- normal conditions;
- edge cases;
- rare but consequential cases;
- degraded conditions;
- missing information;
- unusual inputs;
- conflicting inputs;
- adversarial inputs;
- boundary conditions.

High-consequence cases should not be excluded simply because they are statistically uncommon.

---

## 10. Data Labelling

Where supervised or labelled data is used, labelling processes should define:

- label definitions;
- annotation instructions;
- annotator competence;
- quality checks;
- disagreement handling;
- adjudication;
- versioning;
- uncertainty in labels.

Material labelling uncertainty should be reflected in development and assurance.

---

## 11. Label Quality

Label quality should be assessed using appropriate methods.

These may include:

- independent review;
- sampling;
- inter-annotator agreement;
- adjudication;
- error analysis;
- consistency checks.

A label should not be treated as ground truth solely because it exists in a dataset.

---

## 12. Data Cleaning

Data cleaning may include:

- removing corrupted records;
- resolving duplicates;
- correcting formatting errors;
- addressing missing values;
- identifying inconsistent records;
- removing irrelevant information.

Cleaning rules should be documented because transformations can affect model behaviour.

---

## 13. Data Transformation

Transformations may include:

- normalisation;
- scaling;
- encoding;
- filtering;
- feature extraction;
- resizing;
- format conversion;
- aggregation.

Material transformations should be:

- documented;
- version controlled;
- reproducible where practicable;
- included in the dataset or pipeline baseline.

---

## 14. Data Augmentation

Data augmentation may be used to improve robustness where appropriate.

Examples include controlled variation of:

- image characteristics;
- noise;
- environmental conditions;
- data availability;
- sensor characteristics.

Augmentation should not create unrealistic data that causes the model to learn conditions that do not correspond to the intended operational environment.

---

## 15. Synthetic Data

Synthetic data may support:

- rare-event coverage;
- scenario generation;
- privacy or security constraints;
- robustness testing;
- augmentation;
- simulation.

Synthetic data should be assessed for:

- realism;
- representativeness;
- generation assumptions;
- artefacts;
- distribution differences;
- transferability to real operational conditions.

Synthetic data should not automatically be treated as equivalent to real-world data.

---

## 16. Training, Validation and Test Data

Where appropriate, datasets should be separated into:

- training data;
- validation data;
- test data.

Controls should reduce the risk of:

- data leakage;
- contamination;
- duplicate examples across splits;
- indirect exposure of test data;
- overfitting;
- misleading performance estimates.

The test set should remain sufficiently independent to provide meaningful evidence.

---

## 17. Data Leakage

Data leakage can produce artificially strong performance.

Potential sources include:

- duplicate records;
- shared identifiers;
- temporal leakage;
- information derived from future events;
- preprocessing performed across datasets;
- human annotation leakage;
- repeated scenarios;
- related samples across training and test sets.

Data preparation should actively assess for leakage.

---

## 18. Distribution Shift

Data preparation should consider the possibility that operational data differs from development data.

Potential differences may arise from:

- environment;
- geography;
- sensor configuration;
- user behaviour;
- adversarial adaptation;
- mission tempo;
- seasonal conditions;
- information quality;
- communications;
- infrastructure.

Such differences should be incorporated into testing and operational risk assessment.

---

## 19. Adversarial Data Considerations

Where relevant, data preparation should consider:

- manipulated inputs;
- misleading information;
- corrupted data;
- adversarial examples;
- spoofed information;
- malicious labelling;
- poisoned training data.

The objective is not to assume every input is hostile, but to understand how data integrity failures can affect system behaviour.

---

## 20. Data Integrity

Controls should protect data against:

- unauthorised modification;
- accidental alteration;
- corruption;
- deletion;
- substitution;
- contamination.

Integrity controls may include:

- access control;
- versioning;
- checksums or equivalent mechanisms;
- audit trails;
- controlled repositories;
- validation procedures.

---

## 21. Data Security

Data should be handled according to applicable:

- security requirements;
- classification or handling rules;
- access controls;
- retention rules;
- legal obligations;
- contractual requirements.

Data security should apply throughout:

**Collection → Preparation → Storage → Development → Testing → Deployment → Monitoring → Retention/Disposition**

---

## 22. Data Access

Access should be governed according to:

- role;
- mission need;
- data sensitivity;
- security requirements;
- legal requirements.

Access should be logged where appropriate and periodically reviewed.

---

## 23. Data Versioning

Material datasets should have controlled versions.

A dataset version should identify, where applicable:

- source data;
- transformation pipeline;
- labels;
- filtering;
- augmentation;
- quality checks;
- release date;
- responsible owner.

A model should remain traceable to the data used to develop and evaluate it.

---

## 24. Data Preparation Pipeline

A controlled preparation pipeline may follow:

**Source → Ingest → Validate → Clean → Label → Transform → Quality Check → Split → Version → Release**

Each material stage should have appropriate controls.

---

## 25. Data Validation

Before release for model development or TEVV, data should be assessed for:

- quality;
- integrity;
- representativeness;
- completeness;
- labelling;
- leakage;
- contamination;
- provenance;
- security;
- legal/policy compliance.

Validation should produce evidence rather than rely solely on process completion.

---

## 26. Data and Uncertainty

Data uncertainty should be explicitly considered.

Examples include:

- uncertain labels;
- incomplete records;
- conflicting sources;
- missing information;
- stale information;
- uncertain provenance;
- ambiguous observations.

The objective is to prevent uncertainty in data from being hidden by apparently precise model outputs.

---

## 27. Data and Operational Environment

Where AI is intended for operational use, preparation should consider the relationship between:

**Development Data → Evaluation Data → Operational Data**

Differences should be identified and assessed.

Operational data should not be assumed to remain statistically or operationally identical to development data.

---

## 28. Data for High-Consequence Use Cases

For high-consequence capabilities, additional scrutiny may be required for:

- rare events;
- edge cases;
- distribution shift;
- adversarial conditions;
- label uncertainty;
- data integrity;
- provenance;
- representative environments;
- failure scenarios.

The required evidence should scale with:

**Consequence + Autonomy + Uncertainty + Operational Exposure**

---

## 29. Data Change Management

Changes to data may affect model behaviour.

Changes may include:

- new sources;
- changed sensors;
- new labels;
- new preprocessing;
- changed sampling;
- changed augmentation;
- expanded geographic or environmental coverage;
- removal of data;
- correction of labels.

Material data changes should be assessed for effects on:

- model performance;
- robustness;
- bias;
- uncertainty;
- risk;
- assurance;
- operational authorisation.

---

## 30. Data Monitoring

Operational data should be monitored where appropriate for:

- distribution changes;
- quality degradation;
- missing data;
- unusual inputs;
- source changes;
- integrity issues;
- sensor changes;
- emerging conditions.

Material changes may trigger:

- enhanced monitoring;
- risk reassessment;
- targeted testing;
- revalidation;
- restriction;
- reauthorisation.

---

## 31. Data Retention and Disposition

Data retention should consider:

- operational requirements;
- legal obligations;
- security;
- auditability;
- incident investigation;
- assurance evidence;
- privacy;
- contractual requirements.

When data is no longer required, controlled disposition should be performed where applicable.

---

## 32. Data Preparation Evidence

Evidence may include:

- source records;
- provenance records;
- quality reports;
- labelling guidelines;
- annotation records;
- transformation pipelines;
- validation results;
- leakage assessments;
- representativeness assessments;
- dataset versions;
- security controls;
- approval records.

Evidence should remain linked to the dataset version used.

---

## 33. Data Preparation Exit Criteria

Before a dataset is released for material development or TEVV, the responsible authority should establish that:

- provenance is sufficiently understood;
- intended use is defined;
- data quality is assessed;
- material limitations are documented;
- labels are appropriately validated;
- transformations are controlled;
- leakage has been considered;
- relevant operational conditions are represented;
- security requirements are satisfied;
- applicable legal and policy requirements are addressed;
- dataset version is controlled;
- evidence is retained.

---

## 34. Data Preparation Record

A Data Preparation Record should include, as applicable:

| Field | Description |
|---|---|
| Dataset ID | Unique dataset identifier |
| Dataset Version | Controlled version |
| Purpose | Intended use |
| Related Mission | Mission/use case |
| Source | Data origin |
| Provenance | Origin and history |
| Collection Period | Relevant collection period |
| Quality | Quality assessment |
| Labels | Labelling method and quality |
| Transformations | Preparation/transformation steps |
| Augmentation | Augmentation methods |
| Split | Training/validation/test allocation |
| Leakage Assessment | Leakage checks |
| Representativeness | Coverage assessment |
| Security | Applicable controls |
| Legal/Policy | Applicable constraints |
| Limitations | Known limitations |
| Owner | Responsible authority |
| Evidence | Supporting evidence |
| Status | Lifecycle status |

---

## 35. Core Rules

1. **Data preparation must be driven by mission and AI requirements.**
2. **Data provenance must be sufficiently understood for its intended use.**
3. **Data quality must be assessed rather than assumed.**
4. **Large datasets are not automatically representative datasets.**
5. **Rare but consequential conditions must be considered where relevant.**
6. **Training, validation and test data should be appropriately controlled.**
7. **Data leakage and contamination must be actively considered.**
8. **Material transformations must be documented and version controlled.**
9. **Synthetic data is not automatically equivalent to operational data.**
10. **Data integrity and security must be protected throughout the lifecycle.**
11. **Data changes can change model behaviour and may require reassessment.**
12. **Operational data should be monitored for meaningful distribution and quality changes.**
13. **Data uncertainty should be visible to development, assurance and operational users where relevant.**
14. **Data evidence must remain traceable to the dataset version used.**

---

## 36. Golden Thread

Data Preparation maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Development → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Data preparation converts raw or acquired information into controlled datasets that can support development, evaluation and operational assurance.

---

## 37. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 Mission & Use Case** — defines operational purpose and context.
- **03 Risk & Autonomy** — identifies data-related risk and uncertainty.
- **02 AI Requirements** — defines data requirements.
- **03 AI Development** — uses prepared data for development.
- **05 Data & Information** — provides broader data governance.
- **06 AI Security** — protects data integrity and access.
- **07 Supply Chain & Sovereignty** — addresses external data sources and dependencies.
- **09 TEVV** — evaluates data-dependent performance.
- **10 Operational Environment** — assesses representativeness of operational conditions.
- **13 Continuous Assurance** — monitors operational data changes.
- **15 Change & Reauthorisation** — governs material data changes.
- **16 Audit & Evidence** — preserves dataset traceability.

---

## 38. Summary Model

```text
Mission Need
      ↓
Data Requirements
      ↓
Source Identification
      ↓
Provenance
      ↓
Collection / Acquisition
      ↓
Quality Assessment
      ↓
Cleaning / Labelling
      ↓
Transformation / Augmentation
      ↓
Validation
      ↓
Training / Validation / Test Split
      ↓
Controlled Dataset Version
      ↓
Development / TEVV
      ↓
Operational Data
      ↓
Monitoring
      ↓
Data Change / Distribution Shift
      ↓
Reassessment / Revalidation
```

Data preparation establishes the controlled foundation on which AI development, testing, assurance and operational confidence depend.
