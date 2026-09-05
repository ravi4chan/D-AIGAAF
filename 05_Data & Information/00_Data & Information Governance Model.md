# 00 Data & Information Governance Model

## 1. Purpose

The **Data & Information Governance Model** establishes the overarching governance approach for data and information used, produced, processed, exchanged, or relied upon by defence AI capabilities.

It defines how data-related considerations connect to:

- Mission need and operational context
- AI requirements and system design
- Risk and autonomy
- AI security and information assurance
- Testing, Evaluation, Verification and Validation (TEVV)
- Human authority and decision-making
- Operational authorisation
- Continuous assurance
- Change, incident response, and reauthorisation
- Retirement and decommissioning

This model is generic and unclassified. It does not replace applicable national classification systems, defence policies, legal requirements, information-security controls, or service-specific doctrine.

## 2. Core Principle

> **An AI capability cannot be more trustworthy than the data and information on which its consequential behaviour depends.**

Data governance is therefore not limited to protecting information. It must establish whether data is:

- Appropriate for the intended mission
- Sufficiently accurate and complete
- Representative of the operational domain
- Traceable to an identifiable source
- Protected against unauthorised access or manipulation
- Handled according to its sensitivity and restrictions
- Suitable for the conditions in which the AI capability will operate
- Monitored for degradation, drift, and emerging risk

## 3. Scope

This model applies to data and information across the AI lifecycle, including:

- Training data
- Validation and test data
- Operational data
- Sensor and machine-generated data
- Human-generated data
- Intelligence and situational-awareness inputs
- Geospatial and temporal information
- Labels and annotations
- Synthetic data
- External and third-party data
- Supplier-provided datasets and models
- Data exchanged with partners or coalition entities
- AI inputs, outputs, logs, and decision-support information
- Metadata and audit information
- Data used during degraded or disconnected operations

The framework should distinguish between governance of **data** and governance of **information derived from data**, while recognising that both can affect operational decisions.

## 4. Governance Objectives

D-AIGAAF data governance should provide reasonable assurance of:

| Objective | Governance question |
|---|---|
| Relevance | Is the data relevant to the authorised mission and function? |
| Accuracy | Is the data sufficiently accurate for its intended use? |
| Completeness | Are material gaps known and acceptable? |
| Representativeness | Does the data reflect the intended operational domain? |
| Timeliness | Is the information sufficiently current for the decision? |
| Provenance | Can the source and history of the data be established? |
| Lineage | Can material transformations be reconstructed? |
| Integrity | Can unauthorised or unintended alteration be detected or prevented? |
| Security | Is the data appropriately protected? |
| Availability | Is required data available under authorised operating conditions? |
| Control | Are ownership, access, use, and disposal responsibilities explicit? |
| Assurance | Is there sufficient evidence to support the intended AI use? |

## 5. Governance Layers

### Strategic Layer

Establishes organisational policy, priorities, authorities, standards, and risk appetite.

### Mission Layer

Determines what data is necessary for the mission, what decisions depend on it, and what limitations are operationally acceptable.

### Data Layer

Controls data acquisition, ownership, provenance, quality, representativeness, classification, access, integrity, retention, and disposal.

### AI Layer

Determines how data is used by models and AI-enabled systems, including training, evaluation, inference, and system updates.

### Operational Layer

Assesses whether data remains suitable under actual operating conditions, including degraded, adversarial, intermittent, or disconnected environments.

### Assurance Layer

Maintains evidence that data-related assumptions, controls, limitations, and risks remain understood and acceptable.

## 6. Roles and Accountability

### Data Owner

Accountable for the authorised purpose, use, sensitivity, and governance of a data asset.

### Data Steward

Responsible for day-to-day management, quality controls, metadata, lineage, and issue management.

### AI System Owner / Model Owner

Responsible for understanding how the AI capability depends on data and ensuring material data assumptions are reflected in system assurance.

### AI Developer

Responsible for implementing approved data requirements and documenting material data transformations and dependencies.

### Operational AI Advisor (OAIA)

Provides operationally informed advice on whether data limitations, uncertainty, provenance, quality, or environmental mismatch could affect operational employment.

### Assurance / TEVV Authority

Evaluates evidence concerning data suitability, limitations, robustness, and performance.

### Operational Authorising Authority

Determines whether data-related risks and limitations are acceptable within the proposed operational authorisation.

### Users / Operators

Remain responsible for applying authorised procedures and recognising relevant AI and data limitations.

No single technical role should automatically possess all development, assurance, risk-acceptance, and operational-authorisation responsibilities.

## 7. Data Lifecycle

Data governance should follow the complete lifecycle:

**Identify → Acquire → Validate → Prepare → Use → Monitor → Change → Revalidate → Retain / Dispose**

### Identify

Determine what information is required and why.

### Acquire

Establish lawful, authorised, and controlled sources.

### Validate

Assess provenance, quality, representativeness, integrity, and suitability.

### Prepare

Apply approved processing, cleaning, transformation, labelling, and formatting.

### Use

Control access and use according to authorised purpose and operating conditions.

### Monitor

Detect quality degradation, drift, integrity problems, anomalies, and emerging risks.

### Change

Assess material changes to data sources, transformations, datasets, or dependencies.

### Revalidate

Reassess assurance where changes may affect AI behaviour or operational risk.

### Retain / Dispose

Maintain records for the required period and securely dispose of data when authorised.

## 8. Mission-to-Data Traceability

The framework should establish a traceable relationship between mission requirements and data dependencies:

**Mission Need → Decision / Function → AI Capability → Data Dependency → Data Source → Data Transformation → AI Output → Human Decision → Action → Outcome**

This Golden Thread allows an organisation to determine:

- Which data supports a consequential function
- Which systems and sources the AI depends upon
- What assumptions have been made about that data
- What limitations exist
- What controls protect the data
- What evidence supports its use
- What happens if the data becomes unavailable, degraded, manipulated, or unreliable

## 9. Fitness for Purpose

Data should not be classified simply as "good" or "bad".

Its suitability depends on:

**Purpose + Mission + Consequence + Operating Conditions**

Data that is adequate for one use may be inadequate for another.

For example, data may be suitable for broad situational awareness but unsuitable for a higher-consequence decision requiring greater precision, timeliness, provenance, or environmental representativeness.

Therefore, data quality thresholds should be linked to the authorised use rather than defined only through generic technical metrics.

## 10. Data Assurance Considerations

For consequential AI capabilities, governance should consider:

1. **Provenance** — where did the data originate?
2. **Lineage** — how was it transformed?
3. **Quality** — is it sufficiently accurate and complete?
4. **Representativeness** — does it cover the intended operational domain?
5. **Integrity** — can alteration or corruption be detected?
6. **Classification and handling** — is it appropriately protected?
7. **Access** — who or what can use it?
8. **Timeliness** — is it current enough?
9. **Uncertainty** — what is unknown or unreliable?
10. **Drift** — has the data distribution or environment changed?
11. **Adversarial exposure** — could the data be deliberately manipulated?
12. **Dependencies** — does the capability depend on external sources or services?
13. **Availability** — what happens when required data is unavailable?
14. **Human interpretation** — can users understand important limitations?

## 11. Data and Operational Environment

Data assurance must consider the environment in which the AI capability is authorised to operate.

Relevant conditions may include:

- Geographic variation
- Weather and environmental conditions
- Sensor degradation
- Communications constraints
- Intermittent connectivity
- Navigation or positioning uncertainty
- Electronic interference
- Adversarial manipulation
- Unusual or previously unseen conditions
- Limited access to supporting information
- Degraded infrastructure

The organisation should not assume that data conditions during development or testing will remain identical during operational employment.

## 12. Data and AI Uncertainty

AI systems should not present unreliable data as established fact.

Where material uncertainty exists, the system should communicate it in a manner appropriate to the user and mission.

Relevant uncertainty may arise from:

- Incomplete data
- Conflicting sources
- Stale information
- Poor provenance
- Distribution shift
- Sensor limitations
- Sparse observations
- Unknown operating conditions
- Model limitations

Where uncertainty materially affects a consequential decision, it should become part of the assurance and operational-authorisation record.

## 13. Data Risk

A working D-AIGAAF data-risk formulation is:

**Data Risk = Consequence × Data Dependence × Data Uncertainty × Exposure**

This is a governance construct rather than a mandatory numerical formula.

Higher data risk should generally require:

- Stronger controls
- Better provenance
- Greater representativeness
- More extensive validation
- More rigorous TEVV
- Stronger monitoring
- Tighter operational constraints
- Greater human oversight
- Higher assurance before authorisation

## 14. Data Decision Gates

| Gate | Decision |
|---|---|
| G1 | Is the required data identified? |
| G2 | Is the source authorised and sufficiently understood? |
| G3 | Is the data suitable for the intended purpose? |
| G4 | Are provenance, quality, representativeness, and integrity acceptable? |
| G5 | Are classification and access controls adequate? |
| G6 | Does TEVV adequately test material data assumptions? |
| G7 | Are data limitations acceptable for operational authorisation? |
| G8 | Are monitoring, change, incident, retention, and disposal controls established? |

A capability should not proceed solely because data is available.

## 15. Data Assurance Levels

D-AIGAAF may use working assurance levels to communicate confidence:

| Level | Meaning |
|---|---|
| D1 | Minimal understanding or assurance |
| D2 | Basic controls and limited evidence |
| D3 | Controlled and traceable |
| D4 | Strong evidence and operational relevance |
| D5 | High confidence for the authorised purpose and conditions |

These levels are framework constructs and should be mapped to applicable national, defence, legal, and organisational standards before formal adoption.

## 16. Evidence and Records

Material data decisions should generate evidence sufficient to support the Golden Thread.

Typical records include:

- Data Asset Record
- Data Governance Record
- Data Provenance Record
- Data Lineage Record
- Data Quality Record
- Representativeness Assessment
- Classification and Handling Profile
- Access Control Record
- Data Validation Evidence
- Data Assurance Record
- Data Incident Record
- Change Impact Assessment
- Retention and Disposal Record

Evidence should be version-controlled and linked to the relevant AI capability, system baseline, mission, and authorisation.

## 17. Data and Operational Authorisation

Operational authorisation should explicitly consider material data dependencies.

The authorisation record should identify, where applicable:

- Required data sources
- Data quality assumptions
- Representativeness limitations
- Provenance limitations
- Integrity requirements
- Availability requirements
- Classification and handling conditions
- Access constraints
- Degraded-data behaviour
- Known failure modes
- Monitoring requirements
- Suspension triggers
- Revalidation or reauthorisation triggers

An AI capability should not be considered authorised simply because its model has passed technical testing if critical data assumptions remain unverified.

## 18. Data Changes and Reauthorisation

Changes to data may affect AI behaviour even when the model itself has not changed.

Potentially material changes include:

- New data sources
- Removal of data sources
- Significant distribution changes
- Changes in labelling
- Changes in preprocessing
- Changes in sensor characteristics
- Changes in data access
- Changes in classification or handling
- Significant changes in operational environment
- New external dependencies

Material changes should trigger an impact assessment and, where necessary, revalidation or reauthorisation.

## 19. Failure Modes

Common governance failures include:

- Treating data availability as evidence of data suitability
- Assuming large datasets are automatically representative
- Losing source or transformation history
- Ignoring stale or degraded information
- Allowing technical access without purpose-based authority
- Treating classification as a substitute for data governance
- Failing to test data assumptions under representative conditions
- Ignoring third-party data dependencies
- Failing to monitor distribution shift
- Allowing changes to data pipelines without impact assessment
- Presenting uncertain information with excessive confidence
- Retaining unnecessary data without governance
- Failing to preserve evidence required to reconstruct consequential decisions

## 20. Core Rules

1. **Every consequential AI capability must have identifiable data dependencies.**
2. **Data must be governed according to its authorised purpose and mission context.**
3. **Technical access does not equal authority to use.**
4. **Material data transformations should be traceable.**
5. **Data quality must be assessed against intended use and consequence.**
6. **Representativeness must reflect the authorised operational domain.**
7. **Material uncertainty must be recognised and communicated.**
8. **Data integrity must be protected throughout the lifecycle.**
9. **Material changes to data or data pipelines require impact assessment.**
10. **Operational authorisation must account for critical data assumptions and limitations.**
11. **Data-related evidence must remain linked to the AI capability and its authorisation.**
12. **Data governance must continue throughout operational employment, not end at deployment.**

## 21. Golden Thread

Data governance contributes to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Dependencies → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

This ensures that data is treated as a component of operational trust rather than merely as a technical input to an AI model.

## 22. Relationship to Other D-AIGAAF Domains

This model connects directly with:

- **01 Strategy & Governance** — ownership, accountability, decision rights, and governance.
- **02 Mission & Use Case** — mission-specific data requirements and operational context.
- **03 Risk & Autonomy** — data-related contribution to consequence, uncertainty, and control risk.
- **04 AI Lifecycle** — data requirements, development, TEVV, deployment, change, and retirement.
- **06 AI Security** — protection against compromise, manipulation, poisoning, and unauthorised access.
- **07 Supply Chain & Sovereignty** — third-party sources, dependencies, provenance, and control.
- **08 Human Authority** — human interpretation and decision-making under uncertainty.
- **09 TEVV** — validation of data assumptions and operational representativeness.
- **10 Operational Environment** — environmental and degraded-condition data requirements.
- **11 Operational Authorisation** — data conditions and limitations attached to authority.
- **13 Continuous Assurance** — ongoing monitoring of data quality, drift, integrity, and emerging risk.
- **15 Change & Reauthorisation** — assessment of material data changes.
- **16 Audit & Evidence** — preservation of data governance evidence.

## 23. Summary

The central question is:

> **Can the organisation demonstrate who controls the data, why it is being used, whether it is fit for the authorised purpose, what limitations exist, and how those limitations affect operational risk and authority?**

If the answer is no, the data dependency should be treated as an unresolved assurance issue rather than assumed to be acceptable.
