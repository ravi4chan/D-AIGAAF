# 01 Data Governance

## 1. Purpose

Data Governance establishes ownership, accountability, permitted use, access, quality, protection, lifecycle controls, and assurance requirements for data used by defence AI capabilities.

It provides the governance foundation required to ensure that data remains controlled and fit for its authorised purpose throughout the AI lifecycle.

## 2. Core Principle

> **Data ownership and governance must remain explicit throughout the AI lifecycle; technical access to data does not constitute authority to use it.**

Data governance should establish who is accountable for the data, why it is being used, what controls apply, and how changes or failures are managed.

## 3. Governance Principles

D-AIGAAF data governance should follow these principles:

1. **Purpose limitation** — data should be collected and used for defined and authorised purposes.
2. **Accountability** — ownership and responsibility should be explicit.
3. **Proportionality** — controls should reflect sensitivity and consequence.
4. **Least privilege** — access should be limited to what is necessary.
5. **Traceability** — material data use and transformations should be reconstructable.
6. **Integrity** — unauthorised or unintended changes should be prevented or detectable.
7. **Transparency of limitations** — material weaknesses or uncertainty should be documented.
8. **Lifecycle control** — governance should continue from acquisition through disposal.
9. **Mission alignment** — data requirements should be derived from the authorised use.
10. **Assurance** — material data decisions should be supported by evidence.

## 4. Data Ownership and Accountability

Every material data asset should have an identifiable owner.

### Data Owner

The Data Owner is accountable for:

- Authorised purpose
- Permitted use
- Data sensitivity
- Governance requirements
- Access decisions
- Retention and disposal requirements
- Material data risks

### Data Steward

The Data Steward manages day-to-day governance, including:

- Metadata
- Quality monitoring
- Data issues
- Access administration
- Lineage information
- Lifecycle records

### AI System / Model Owner

The AI System or Model Owner should understand:

- Which data the capability depends upon
- Which data assumptions affect system behaviour
- Which data limitations affect assurance
- Which changes could require revalidation

### Operational AI Advisor (OAIA)

The Operational AI Advisor provides operational advice on whether data limitations, uncertainty, or environmental mismatch could affect employment of the AI capability.

### Assurance / TEVV Authority

Assesses whether available evidence supports the intended use of the data and the AI capability.

### Operational Authorising Authority

Determines whether material data-related risks are acceptable for the proposed operational use.

## 5. Data Asset Record

Each material data asset should have an appropriate record containing, where applicable:

| Field | Description |
|---|---|
| Data Asset ID | Unique identifier |
| Owner | Accountable data owner |
| Steward | Operational data manager |
| Purpose | Authorised purpose |
| Source | Origin of the data |
| Classification | Applicable classification/handling category |
| Access | Authorised users and systems |
| Quality | Known quality characteristics |
| Provenance | Source and acquisition history |
| Lineage | Material transformations |
| Representativeness | Known coverage and limitations |
| Retention | Retention requirement |
| Dependencies | External or system dependencies |
| Risks | Identified data risks |
| Assurance | Evidence and assurance status |
| Change History | Material changes |

## 6. Data Classification and Handling

Data should be classified and handled according to applicable national, defence, legal, contractual, and organisational requirements.

Classification should consider:

- Sensitivity
- National-security implications
- Operational significance
- Personal or protected information
- Supplier restrictions
- Legal restrictions
- Source sensitivity
- Aggregation risk
- Inference risk
- Consequences of disclosure, alteration, or loss

Classification alone does not establish that data is suitable for an AI use.

Data handling should cover:

- Storage
- Processing
- Access
- Transfer
- Sharing
- Export
- Retention
- Disposal

## 7. Access Governance

Data access should follow:

**Need → Authority → Eligibility → Purpose → Least Privilege → Controlled Access → Monitoring → Review → Revocation**

Access governance should address:

- Human users
- Privileged users
- Administrators
- Applications
- APIs
- Machine-to-machine access
- AI systems
- Development environments
- Testing environments
- Operational environments
- External suppliers
- Partner organisations

Emergency or break-glass access should be explicitly governed, logged, attributable, and reviewed.

## 8. Data Use Authorisation

Access to data and authority to use data are separate decisions.

A user or system may technically be able to access information without being authorised to use it for a particular AI function.

Data use should therefore be evaluated against:

**Identity + Authority + Purpose + Data Sensitivity + Mission Need + Operating Context**

Use outside the authorised purpose should require appropriate approval.

## 9. Data Quality Governance

Data quality should be assessed against the intended mission and use.

Relevant dimensions include:

- Accuracy
- Completeness
- Consistency
- Validity
- Timeliness
- Relevance
- Representativeness
- Uniqueness
- Provenance
- Integrity

Quality thresholds should increase where:

- Consequence is high
- Mission criticality is high
- AI dependence on the data is high
- Data uncertainty is high
- Operating conditions are degraded or adversarial

## 10. Provenance and Lineage

Material data should be sufficiently traceable to establish:

**Source → Collection → Processing → Transformation → Dataset → AI Use**

Governance should preserve enough information to determine:

- Where data originated
- Who or what supplied it
- When it was collected
- What transformations occurred
- Which dataset version was used
- Which AI capability consumed it

For consequential applications, this should support reconstruction of:

**Data Source → Data Used → AI Output → Human Assessment → Human Decision → Authorised Action → Outcome**

## 11. Data Integrity

Data integrity controls should protect against:

- Unauthorised modification
- Accidental alteration
- Corruption
- Incomplete transfer
- Synchronisation errors
- Malicious manipulation
- Data poisoning
- Uncontrolled processing changes

Integrity controls should operate across acquisition, storage, processing, transfer, training, testing, deployment, and operational use.

## 12. Data Representativeness

Data governance should consider whether the available data represents the conditions in which the AI capability is authorised to operate.

Relevant dimensions may include:

- Geography
- Time
- Environment
- Sensors
- Operational conditions
- Classes or events
- Human behaviour
- Adversarial conditions
- Edge cases
- Degraded conditions

Large datasets should not automatically be considered representative.

## 13. Data Sharing and Third-Party Data

External or shared data should have defined governance arrangements.

Before use, the organisation should understand, as appropriate:

- Source
- Ownership
- Authorised purpose
- Restrictions
- Provenance
- Quality
- Classification
- Security requirements
- Dependencies
- Change mechanisms
- Withdrawal or availability risks

Supplier or partner data should not be treated as inherently trustworthy merely because it comes from an external organisation.

## 14. Data Issues and Changes

Material data issues should be recorded, assessed, assigned, and resolved or accepted.

Examples include:

- Quality degradation
- Missing data
- Stale information
- Provenance gaps
- Integrity concerns
- Distribution changes
- New data sources
- Removed data sources
- Pipeline changes
- Classification changes
- Access changes
- New external dependencies

### Change Classes

| Class | Description | Typical governance response |
|---|---|---|
| Class 0 | Administrative | Record change |
| Class 1 | Minor | Local review |
| Class 2 | Controlled | Formal impact assessment |
| Class 3 | Material | Revalidation and assurance review |
| Class 4 | Critical | Consider suspension and reauthorisation |

These are working D-AIGAAF constructs and should be adapted to organisational requirements.

## 15. Data and AI Development

Development teams should document material assumptions about:

- Training data
- Validation data
- Test data
- Labels
- Preprocessing
- Feature engineering
- Data transformations
- Data exclusions
- Data limitations
- Synthetic data
- External datasets

Data assumptions that materially affect model performance should become part of TEVV evidence.

## 16. Data and Operational Employment

During operational employment, governance should address:

- Data availability
- Data quality
- Data freshness
- Data integrity
- Environmental relevance
- Degraded conditions
- Sensor limitations
- Communications constraints
- External dependencies
- User interpretation

If critical data assumptions no longer hold, the AI capability may require restriction, suspension, revalidation, or reauthorisation.

## 17. Data and Human Authority

Where AI supports consequential decisions, users should understand material data limitations.

The organisation should be able to determine:

**What data was available → What information the AI generated → What uncertainty existed → What the human decision-maker understood → What decision was made**

Where a commander or authorised decision-maker rejects or bypasses an AI recommendation, the governance system should support appropriate recording of the decision and relevant rationale without creating unnecessary administrative burden.

## 18. Data Risk

A working data-risk formulation is:

**Data Risk = Consequence × Data Dependence × Data Uncertainty × Exposure**

Higher data risk should generally require stronger:

- Governance
- Access controls
- Integrity controls
- Validation
- TEVV
- Monitoring
- Human oversight
- Operational restrictions
- Assurance evidence

## 19. Data Incidents

A data incident may include:

- Unauthorised access
- Unauthorised disclosure
- Data corruption
- Suspected manipulation
- Data poisoning
- Loss of provenance
- Material quality failure
- Loss of critical data availability
- Incorrect classification or handling
- Uncontrolled data sharing

Incident response should establish:

1. Detection
2. Containment
3. Assessment
4. Operational impact determination
5. Notification through authorised channels
6. Remediation
7. Revalidation where necessary
8. Reauthorisation where necessary
9. Record preservation
10. Lessons learned

## 20. Retention and Disposal

Data should be retained according to applicable requirements and the needs of:

- Operational accountability
- Assurance
- Audit
- Legal obligations
- Incident investigation
- AI lifecycle traceability

When disposal is authorised, it should be controlled, documented, and appropriate to the sensitivity of the information.

## 21. Operational Authorisation Conditions

Where data is material to an AI capability, operational authorisation should specify relevant data conditions.

These may include:

- Required data sources
- Minimum data quality
- Maximum acceptable latency
- Required integrity controls
- Required availability
- Approved operating environments
- Known data limitations
- Degraded-data behaviour
- Monitoring requirements
- Suspension triggers
- Revalidation triggers

Data conditions should be treated as part of the operational envelope where they materially affect system behaviour.

## 22. Records and Evidence

The organisation should retain evidence sufficient to demonstrate:

- Who owns the data
- Why it is being used
- Who authorised its use
- What controls apply
- What its limitations are
- What evidence supports its suitability
- What changes have occurred
- What incidents have occurred
- What decisions were taken in response

Records should remain linked to the relevant AI capability, system baseline, mission, and operational authorisation.

## 23. Common Failure Modes

Common governance failures include:

- Treating access as equivalent to authority
- Treating availability as equivalent to suitability
- Assuming ownership is obvious without recording it
- Ignoring provenance gaps
- Failing to maintain lineage
- Treating classification as sufficient governance
- Using data outside its authorised purpose
- Failing to account for data drift
- Assuming third-party data is trustworthy
- Allowing material pipeline changes without assessment
- Failing to record critical data limitations
- Ending governance at deployment
- Failing to connect data risks to operational authorisation

## 24. Core Rules

1. **Every material data asset must have accountable ownership.**
2. **Data use must have an authorised purpose.**
3. **Technical access does not constitute authority to use.**
4. **Data governance must continue throughout the AI lifecycle.**
5. **Material data dependencies must be traceable.**
6. **Data quality must be assessed against mission and consequence.**
7. **Classification and handling requirements must be explicitly governed.**
8. **Material data changes require impact assessment.**
9. **Critical data limitations must be reflected in assurance and authorisation.**
10. **Data incidents must be attributable, assessed, and recorded.**
11. **Data governance evidence must remain linked to the AI capability and its operational authority.**
12. **Where critical data assumptions fail, continued operation must not be treated as automatically authorised.**

## 25. Golden Thread

Data Governance contributes to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Dependencies → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

The objective is to ensure that data governance is directly connected to operational trust and not treated as a separate administrative activity.
