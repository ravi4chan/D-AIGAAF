# 05-Data and Information Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 05 — Data & Information**.

These templates provide practical instruments for governing the data and information on which defence AI capabilities depend.

The framework treats data as a lifecycle-controlled operational asset rather than merely a technical input.

The central principle is:

> **AI assurance cannot exceed the quality, integrity, provenance, relevance and governance of the information on which the capability depends.**

The templates support:

- data governance;
- data ownership;
- data classification;
- data quality;
- integrity;
- provenance;
- lineage;
- representativeness;
- bias and coverage assessment;
- data drift;
- lifecycle management;
- data assurance;
- information dependencies;
- AI-specific data risks.

---

# 2. Template Set

The recommended Data & Information template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-05-001 | Data & Information Governance Record |
| D-AIGAAF-T-05-002 | Data Asset Register |
| D-AIGAAF-T-05-003 | Data Governance Assessment |
| D-AIGAAF-T-05-004 | Data Classification & Handling Record |
| D-AIGAAF-T-05-005 | Data Quality Assessment |
| D-AIGAAF-T-05-006 | Data Integrity Assessment |
| D-AIGAAF-T-05-007 | Data Provenance Record |
| D-AIGAAF-T-05-008 | Data Lineage Record |
| D-AIGAAF-T-05-009 | Data Representativeness Assessment |
| D-AIGAAF-T-05-010 | Data Bias & Coverage Assessment |
| D-AIGAAF-T-05-011 | Data Drift Assessment |
| D-AIGAAF-T-05-012 | Data Dependency Assessment |
| D-AIGAAF-T-05-013 | Data Assurance Record |
| D-AIGAAF-T-05-014 | Data Lifecycle Record |
| D-AIGAAF-T-05-015 | Data Change Assessment |
| D-AIGAAF-T-05-016 | Data Incident Record |
| D-AIGAAF-T-05-017 | AI Training Data Assessment |
| D-AIGAAF-T-05-018 | AI Input / Operational Data Assessment |
| D-AIGAAF-T-05-019 | Data Retention & Disposal Record |
| D-AIGAAF-T-05-020 | Data Governance Review Record |

---

# 3. Template 05-001 — Data & Information Governance Record

## Purpose

Defines governance responsibility for data and information used, generated or processed by an AI capability.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Data owner
- Data custodian
- Data steward
- Security authority
- Privacy/legal authority where applicable
- Technical owner
- Assurance owner
- Classification
- Applicable policy
- Review date

## Governance Questions

- Who owns the data?
- Who may access it?
- Who may modify it?
- Who is accountable for quality?
- What restrictions apply?
- What evidence demonstrates governance?

---

# 4. Template 05-002 — Data Asset Register

## Purpose

Provides a controlled inventory of important data assets associated with the AI capability.

## Required Fields

- Data Asset ID
- Data name
- Description
- Source
- Owner
- Custodian
- Purpose
- Data type
- Classification
- Sensitivity
- Geographic origin
- Collection method
- Frequency
- Retention
- Related model
- Related mission
- Related risk
- Review date

## Data Categories

Consider:

- training data;
- validation data;
- test data;
- operational inputs;
- sensor data;
- intelligence data;
- geospatial data;
- human-generated data;
- synthetic data;
- retrieved information;
- external data.

---

# 5. Template 05-003 — Data Governance Assessment

## Purpose

Assesses whether data is governed appropriately for its intended AI use.

## Assessment Areas

- ownership;
- purpose;
- access;
- security;
- privacy;
- provenance;
- quality;
- integrity;
- retention;
- disposal;
- lawful use;
- contractual restrictions;
- cross-border considerations;
- downstream use.

## Conclusion

- adequate;
- adequate with conditions;
- deficient;
- prohibited for intended use.

---

# 6. Template 05-004 — Data Classification & Handling Record

## Purpose

Defines the classification and handling requirements applicable to a data asset.

## Required Fields

- Data Asset ID
- Classification
- Sensitivity
- Handling restrictions
- Access groups
- Encryption requirements
- Storage requirements
- Transmission restrictions
- Releasability
- Retention
- Disposal
- Authority

The classification system should follow the organisation's applicable information-security regime.

---

# 7. Template 05-005 — Data Quality Assessment

## Purpose

Determines whether data quality is sufficient for the intended AI use.

## Quality Dimensions

Assess, as relevant:

- accuracy;
- completeness;
- consistency;
- timeliness;
- validity;
- uniqueness;
- relevance;
- reliability.

## Required Fields

- Data Asset ID
- Quality dimension
- Metric
- Target
- Observed value
- Threshold
- Finding
- Impact
- Corrective action
- Owner
- Review date

Data quality should be evaluated against the intended mission rather than against an abstract universal standard.

---

# 8. Template 05-006 — Data Integrity Assessment

## Purpose

Assesses whether data has remained accurate and protected against unauthorised or unintended alteration.

## Assessment Areas

- source integrity;
- transfer integrity;
- storage integrity;
- processing integrity;
- transformation integrity;
- access controls;
- audit trail;
- cryptographic controls where appropriate.

## Required Fields

- Data Asset ID
- Integrity requirement
- Control
- Verification method
- Evidence
- Finding
- Residual risk
- Owner

---

# 9. Template 05-007 — Data Provenance Record

## Purpose

Records the origin and history of a data asset.

## Required Fields

- Data Asset ID
- Original source
- Source authority
- Collection date
- Collection method
- Collector
- Processing steps
- Transformations
- Derivatives
- Ownership
- Restrictions
- Verification
- Provenance confidence

## Principle

The organisation should be able to determine, where reasonably possible:

**Where did this data come from?**

**Who or what generated it?**

**What happened to it before it entered the AI system?**

---

# 10. Template 05-008 — Data Lineage Record

## Purpose

Maps the flow of data through the AI lifecycle.

## Example Flow

**Source**
→ **Collection**
→ **Storage**
→ **Cleaning**
→ **Transformation**
→ **Training / Validation / Testing**
→ **Model**
→ **Operational Input**
→ **AI Output**
→ **Decision / Action**

## Required Fields

- Data element
- Source
- Processing stage
- Transformation
- Destination
- System
- Owner
- Integrity control
- Evidence

Lineage should identify material transformations that could affect AI behaviour.

---

# 11. Template 05-009 — Data Representativeness Assessment

## Purpose

Determines whether data adequately represents the intended operational environment and population of interest.

## Dimensions

Consider:

- geography;
- terrain;
- climate;
- season;
- time;
- sensor;
- platform;
- population;
- adversary behaviour;
- mission type;
- operating conditions.

## Required Fields

- Intended population/environment
- Dataset population/environment
- Coverage
- Missing areas
- Known bias
- Consequence
- Confidence
- Mitigation
- Residual limitation

A dataset may be statistically large while still being operationally unrepresentative.

---

# 12. Template 05-010 — Data Bias & Coverage Assessment

## Purpose

Identifies systematic coverage limitations or biases that could affect AI performance.

## Assessment Areas

- sampling;
- class imbalance;
- geographic bias;
- demographic bias where relevant;
- sensor bias;
- temporal bias;
- label bias;
- collection bias;
- adversarial bias;
- missing classes.

## Required Fields

- Bias / coverage issue
- Evidence
- Affected output
- Mission consequence
- Mitigation
- Residual uncertainty
- Owner
- Review trigger

Bias assessment should be contextual and mission-specific.

---

# 13. Template 05-011 — Data Drift Assessment

## Purpose

Determines whether operational data is changing sufficiently to affect AI performance or assurance.

## Drift Categories

- distribution drift;
- concept drift;
- sensor drift;
- environmental drift;
- adversarial drift;
- population change;
- mission change;
- source change.

## Required Fields

- Data Asset ID
- Baseline
- Current distribution
- Drift indicator
- Threshold
- Impact assessment
- Action
- Owner
- Review date

Material drift may trigger:

- additional testing;
- model update;
- restricted use;
- revalidation;
- reauthorisation.

---

# 14. Template 05-012 — Data Dependency Assessment

## Purpose

Identifies dependencies on external or internal data sources.

## Required Fields

- Dependency ID
- Data source
- Provider
- Criticality
- Availability
- Reliability
- Security
- Continuity
- Alternative source
- Failure consequence
- Monitoring
- Owner

## Critical Principle

A mission should not silently depend on a data source whose availability or integrity cannot be reasonably assured.

---

# 15. Template 05-013 — Data Assurance Record

## Purpose

Records the assurance assessment of data supporting an AI capability.

## Assessment Areas

- quality;
- integrity;
- provenance;
- lineage;
- representativeness;
- bias;
- drift;
- security;
- legal/policy status;
- operational relevance.

## Required Fields

- Data Asset ID
- Evidence
- Assessment method
- Findings
- Limitations
- Confidence
- Residual risk
- Assurance conclusion
- Reviewer
- Date

---

# 16. Template 05-014 — Data Lifecycle Record

## Purpose

Tracks data through its lifecycle.

## Lifecycle

**Collect**
→ **Acquire**
→ **Store**
→ **Process**
→ **Use**
→ **Share**
→ **Retain**
→ **Archive / Dispose**

Where applicable, also track:

- transformation;
- replication;
- export;
- derivative datasets.

## Required Fields

- Lifecycle stage
- Owner
- Control
- Evidence
- Retention requirement
- Transition date
- Approval

---

# 17. Template 05-015 — Data Change Assessment

## Purpose

Assesses whether a material change to data may affect AI performance, risk or assurance.

## Change Types

- new source;
- changed source;
- new collection method;
- preprocessing change;
- label change;
- dataset expansion;
- dataset reduction;
- geographic change;
- temporal change;
- synthetic-data introduction;
- operational distribution change.

## Impact Assessment

Determine impact on:

- model performance;
- mission;
- risk;
- security;
- human decisions;
- autonomy;
- assurance;
- authorisation.

---

# 18. Template 05-016 — Data Incident Record

## Purpose

Records incidents affecting data integrity, confidentiality, availability or suitability.

## Incident Categories

- unauthorised access;
- data loss;
- corruption;
- poisoning;
- manipulation;
- misclassification;
- provenance failure;
- privacy incident;
- incorrect data;
- unavailable source;
- compromised source.

## Required Fields

- Incident ID
- Data Asset
- Detection
- Impact
- Immediate action
- Evidence
- Root cause
- Containment
- Recovery
- Risk reassessment
- Revalidation requirement
- Reauthorisation requirement

---

# 19. Template 05-017 — AI Training Data Assessment

## Purpose

Assesses the suitability of data used to train, fine-tune or otherwise materially influence an AI model.

## Required Fields

- Model ID
- Dataset ID
- Purpose
- Source
- Provenance
- Rights / permissions
- Quality
- Representativeness
- Bias
- Security
- Data transformations
- Labelling
- Contamination considerations
- Validation
- Limitations
- Approval

## Special Considerations

Assess:

- data poisoning;
- hidden contamination;
- compromised datasets;
- inappropriate sources;
- sensitive information;
- adversarial examples;
- label manipulation.

---

# 20. Template 05-018 — AI Input / Operational Data Assessment

## Purpose

Assesses the data entering the AI system during actual operational employment.

## Required Fields

- Input source
- Data type
- Timeliness
- Quality
- Confidence
- Integrity
- Completeness
- Sensor/source reliability
- Environmental relevance
- Adversarial concerns
- Missing data
- Out-of-distribution indicators
- Human interpretation requirement
- Action if unsuitable

## Operational Rule

Where input data falls outside defined conditions, the system should:

- continue with known limitations;
- restrict output;
- request human confirmation;
- transition to a safe state;
- stop operation;

according to the authorised operating conditions.

---

# 21. Template 05-019 — Data Retention & Disposal Record

## Purpose

Records retention and disposal decisions for AI-related data.

## Required Fields

- Data Asset
- Purpose
- Retention requirement
- Retention period
- Legal/policy basis
- Archive requirement
- Disposal method
- Disposal authority
- Disposal date
- Verification
- Record reference

Disposal should not occur where retention is required for:

- legal obligations;
- operational records;
- audit;
- investigation;
- safety;
- assurance;
- lessons learned.

---

# 22. Template 05-020 — Data Governance Review Record

## Purpose

Provides periodic review of data governance effectiveness.

## Review Areas

- ownership;
- quality;
- integrity;
- provenance;
- lineage;
- representativeness;
- bias;
- drift;
- security;
- dependencies;
- incidents;
- retention;
- disposal;
- legal/policy requirements.

## Review Questions

1. Is the data still suitable for the mission?
2. Has its provenance changed?
3. Has operational distribution changed?
4. Has data drift occurred?
5. Have new threats emerged?
6. Are data dependencies reliable?
7. Are controls operating?
8. Is assurance still sufficient?
9. Has the data change affected authorisation?
10. Are additional controls or testing required?

---

# 23. Data-to-Model Traceability

For consequential AI, the organisation should be able to establish:

**Data Source**
→ **Dataset**
→ **Processing**
→ **Model Version**
→ **Configuration**
→ **TEVV Evidence**
→ **Authorisation**
→ **Operational Use**

This traceability becomes particularly important when investigating failures or unexpected behaviour.

---

# 24. Data-to-Decision Traceability

Where practical, operational records should support:

**Operational Input**
→ **AI Processing**
→ **AI Output**
→ **Human Interpretation**
→ **Decision**
→ **Action**

The level of traceability should be proportionate to mission consequence and applicable security/privacy constraints.

---

# 25. Data Quality and Mission Consequence

Data quality requirements should be consequence-based.

A minor quality issue may be acceptable for:

- low-consequence information support.

The same issue may be unacceptable for:

- safety-critical systems;
- targeting support;
- force protection;
- autonomous action.

Therefore:

> **Data quality thresholds should be derived from intended use and consequence, not selected independently of the mission.**

---

# 26. Data Security

Data governance should interface directly with Module 06.

Relevant risks include:

- unauthorised access;
- manipulation;
- poisoning;
- exfiltration;
- inference;
- corruption;
- denial of availability;
- supply-chain compromise.

Security controls should protect:

**Data at Rest**
→ **Data in Transit**
→ **Data in Processing**
→ **Data in Use**

as appropriate to the architecture.

---

# 27. Data and Privacy

Where personal or otherwise legally protected information is involved, the applicable legal and policy requirements must be assessed.

The organisation should consider:

- purpose;
- lawful basis;
- minimisation;
- access;
- retention;
- security;
- rights;
- disclosure;
- cross-border transfer;
- disposal.

D-AIGAAF does not assume that all defence data is exempt from applicable data-protection requirements.

Applicability must be determined for the specific processing activity and legal context.

---

# 28. Data and AI Security

Data used by AI systems can become an attack surface.

Potential threats include:

- poisoning;
- backdoors;
- malicious labels;
- manipulated retrieval sources;
- compromised sensors;
- falsified intelligence;
- adversarial inputs.

The data-security assessment should therefore consider both conventional information security and AI-specific attack paths.

---

# 29. Data and Operational Environment

The operational environment may change the meaning or reliability of data.

Examples include:

- weather;
- terrain;
- sensor changes;
- adversarial deception;
- communications degradation;
- new populations;
- new equipment;
- changed mission conditions.

Therefore:

**Data Assured in Environment A ≠ Automatically Assured in Environment B**

unless the assurance basis demonstrates that the difference is immaterial.

---

# 30. Data and Autonomy

Autonomy should depend partly on the quality and reliability of required inputs.

Where critical input data becomes:

- unavailable;
- stale;
- corrupted;
- uncertain;
- out-of-distribution;

the system may need to:

- reduce autonomy;
- request human confirmation;
- restrict action;
- transition to safe state.

These conditions should be defined before operational authorisation.

---

# 31. Data Evidence Package

For a consequential capability, the data evidence package should normally contain:

- data asset register;
- governance assessment;
- classification/handling;
- quality assessment;
- integrity assessment;
- provenance;
- lineage;
- representativeness;
- bias/coverage;
- drift;
- dependencies;
- assurance;
- lifecycle;
- change history;
- incidents;
- retention/disposal.

Additional evidence should be required according to mission and data risk.

---

# 32. Review Questions

Before approving data for a consequential AI use case, reviewers should ask:

1. Where did the data come from?
2. Can its provenance be demonstrated?
3. Has it been altered?
4. Is it sufficiently accurate?
5. Is it complete enough?
6. Does it represent the intended environment?
7. What important populations or conditions are missing?
8. What biases exist?
9. Has the distribution changed?
10. Could the data have been poisoned or manipulated?
11. What dependencies exist?
12. What legal or policy restrictions apply?
13. Is retention appropriate?
14. Is operational input quality monitored?
15. What happens when data becomes unreliable?

---

# 33. Anti-Pattern — More Data Equals Better AI

D-AIGAAF rejects the assumption:

**More Data → Automatically Better AI**

A larger dataset may contain:

- poor-quality data;
- irrelevant data;
- biased data;
- duplicated data;
- contaminated data;
- manipulated data;
- unrepresentative data.

The relevant question is:

> **Is the data sufficiently suitable, trustworthy and representative for the intended mission?**

---

# 34. Anti-Pattern — Training Data Is the Only Important Data

Training data is only one part of the data lifecycle.

Operational data can introduce new risks after deployment.

The governance chain must therefore include:

**Training Data**
→ **Validation / Test Data**
→ **Operational Inputs**
→ **Retrieved / External Information**
→ **Outputs**
→ **Feedback / Learning Data**

Each may require different controls.

---

# 35. Final Data & Information Principle

D-AIGAAF treats data governance as a foundational component of AI assurance.

The governing principle is:

> **An AI capability should not be considered trustworthy merely because its model performs well; confidence must also account for whether the information entering and influencing the system is sufficiently accurate, representative, traceable, secure, current and fit for the mission.**

The complete data governance chain is:

**Source**
→ **Provenance**
→ **Quality**
→ **Integrity**
→ **Representativeness**
→ **Processing**
→ **Model**
→ **Operational Input**
→ **AI Output**
→ **Decision**
→ **Monitoring**
→ **Drift / Change**
→ **Revalidation**

This ensures that data remains part of the governance lifecycle rather than becoming an invisible dependency beneath the AI system.
