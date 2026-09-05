# D-AIGAAF — Data Classification & Handling

## 1. Purpose

This document defines the governance and assurance approach for classifying, handling, accessing, transferring, storing, processing, retaining and disposing of data used by defence AI capabilities.

The objective is to ensure that data is handled according to its sensitivity, operational significance, legal and policy requirements, and the consequences of unauthorised disclosure, modification, loss or misuse.

---

## 2. Core Principle

> **Data classification determines the controls required to protect information; it does not by itself determine whether that data is suitable for an AI capability.**

Classification and handling must therefore operate alongside:

- data quality
- provenance
- lineage
- integrity
- access control
- AI security
- mission risk
- legal and policy requirements
- supply-chain controls
- operational authorisation

---

## 3. Scope

This document applies to:

- training data
- validation and test data
- operational data
- intelligence and information inputs
- sensor-derived data
- geospatial data
- model inputs and outputs
- datasets
- metadata
- provenance and lineage records
- annotations
- synthetic data
- simulation data
- supplier and third-party data
- logs and audit records
- data exchanged between systems or organisations

---

## 4. Classification Objectives

Data classification should establish:

1. what level of protection is required
2. who may access the information
3. where it may be stored
4. how it may be processed
5. how it may be transferred
6. what systems may handle it
7. how long it may be retained
8. how it must be disposed of
9. what monitoring is required
10. what consequences arise from compromise

---

## 5. Classification Authority

Classification should be determined by the appropriate competent authority under applicable national, defence, organisational and legal rules.

D-AIGAAF does **not** create or replace national classification schemes.

Where a formal classification system exists, D-AIGAAF should map to that system.

Where classification is uncertain, the data should be handled according to the more protective applicable rule until an authorised determination is made.

---

## 6. Classification Factors

Classification decisions may consider:

- sensitivity
- national-security implications
- operational significance
- personal or protected information
- supplier restrictions
- legal restrictions
- contractual restrictions
- source sensitivity
- aggregation effects
- disclosure consequences
- integrity consequences
- availability consequences

Classification should consider not only individual data elements but also the consequences of aggregation.

---

## 7. Aggregation Risk

Individually low-sensitivity information may become significantly more sensitive when combined.

AI systems can increase aggregation risk because they may combine and infer relationships across large datasets.

Classification assessment should therefore consider the **combined information product**, not only individual inputs.

---

## 8. Data Handling Categories

A practical handling framework should consider:

### Storage

Where and under what controls data may be stored.

### Processing

Which systems and environments may process the data.

### Access

Who may access the data and for what authorised purpose.

### Transfer

How data may move between systems, organisations or environments.

### Sharing

Which recipients may receive the data.

### Retention

How long data should remain available.

### Disposal

How data should be securely removed or destroyed.

---

## 9. Need-to-Know

Access should be based on:

**Need → Authority → Appropriate Clearance / Eligibility → Least Privilege → Controlled Access**

Possession of a role, system account or technical capability does not automatically establish a need to access particular data.

---

## 10. Purpose Limitation

Data should be used only for authorised purposes.

A dataset collected or acquired for one purpose should not automatically be reused for another purpose where the reuse introduces new risk, legal obligations, privacy implications, operational consequences or AI behaviour.

Material changes in intended use should trigger reassessment.

---

## 11. Data Access

Access controls should address:

- identity
- authentication
- authorisation
- role
- purpose
- least privilege
- time-bound access where appropriate
- monitoring
- review
- revocation

Privileged access should receive additional controls and oversight.

---

## 12. Data Processing Environments

The processing environment should be appropriate for the data classification and intended AI use.

Assessment should consider:

- infrastructure location
- physical security
- logical security
- network architecture
- isolation
- access controls
- monitoring
- dependencies
- external services
- backup arrangements
- administrative access

Data should not be processed in an environment that is not authorised for its classification and handling requirements.

---

## 13. AI Development Environments

Development environments should be assessed separately from operational environments.

Particular attention should be given to:

- copying production data into development
- supplier access
- external development tools
- cloud services
- debugging systems
- test datasets
- developer workstations
- removable media
- logging

Development convenience should not override data-handling requirements.

---

## 14. Training Data Handling

Training datasets may contain sensitive information even where the final model does not directly expose the original records.

Controls should address:

- dataset access
- copying
- preprocessing
- storage
- annotation
- model training
- backups
- temporary files
- derived datasets
- model artefacts
- disposal

The organisation should assess whether sensitive training data can be exposed through model outputs or associated artefacts.

---

## 15. Validation and Test Data Handling

Validation and test data should receive appropriate handling controls.

Where possible, test environments should minimise unnecessary exposure while retaining sufficient realism for assurance.

Test data should remain traceable to:

- approved sources
- classification
- dataset version
- intended evaluation purpose

---

## 16. Operational Data Handling

Operational AI systems should process data only within authorised environments.

Controls should account for:

- data sensitivity
- operational urgency
- communications constraints
- system dependencies
- access requirements
- local storage
- synchronisation
- logging
- retention

Operational urgency does not eliminate the requirement for authorised handling.

---

## 17. Data Transfer

Transfers should be governed by:

- authorised sender
- authorised recipient
- approved transfer mechanism
- classification compatibility
- integrity protection
- authentication
- logging
- transfer validation
- applicable legal and policy restrictions

Uncontrolled transfer channels should not be used for protected data.

---

## 18. Data Sharing

Before sharing data, determine:

- why it is being shared
- who will receive it
- what authority permits sharing
- what classification applies
- what restrictions apply
- what controls are required
- how receipt will be confirmed
- how onward sharing is controlled

Sharing should be proportionate to the mission requirement.

---

## 19. Cross-Organisation and Partner Sharing

Where data is shared with other government organisations, defence organisations, industry, research institutions, international partners or coalition partners, the applicable agreements, security requirements and handling rules should be established before transfer.

Partner access should not automatically imply unrestricted reuse.

---

## 20. Third-Party and Supplier Data

Supplier-provided data should be assessed for:

- classification
- ownership
- licensing
- usage restrictions
- provenance
- integrity
- handling requirements
- onward-transfer restrictions
- retention requirements

Contractual terms should be consistent with the organisation's operational and assurance needs.

---

## 21. Metadata and Supporting Records

Metadata may itself be sensitive.

Relevant metadata may include:

- source identifiers
- collection times
- locations
- system identifiers
- model relationships
- processing history
- operational dependencies

Classification and handling should therefore apply to metadata where appropriate.

---

## 22. Data Outputs

AI-generated outputs should be classified and handled according to applicable rules.

Output sensitivity should not automatically be assumed to equal input sensitivity.

Conversely, apparently low-sensitivity outputs may reveal protected information through aggregation, inference, correlation, summarisation or pattern extraction.

---

## 23. AI Inference Risk

AI systems may infer sensitive information from multiple lower-sensitivity inputs.

Assessment should consider:

**Input Data → Model Processing → Inference → Output → Potential Disclosure**

Where inference creates additional sensitivity, appropriate controls should be applied to the resulting information.

---

## 24. Data Minimisation

Only data necessary for the authorised purpose should be collected, accessed, processed or retained where applicable.

Data minimisation can reduce:

- exposure
- attack surface
- misuse
- storage burden
- classification complexity
- accidental disclosure

Minimisation should not remove information necessary for safe and reliable AI operation.

---

## 25. Encryption and Protective Controls

Applicable security controls should be selected according to:

- classification
- threat
- operational environment
- system architecture
- transfer mechanism
- storage environment
- mission consequence

Specific technical controls should follow applicable security standards and organisational policy rather than being prescribed generically by D-AIGAAF.

---

## 26. Portable and Removable Media

Where removable or portable media is permitted, controls should address:

- authorisation
- device control
- encryption
- malware protection
- transfer validation
- accountability
- loss reporting
- secure disposal

Unauthorised removable media should not be used to transfer protected AI data.

---

## 27. Offline and Disconnected Processing

Where AI systems are authorised to operate without continuous connectivity, data handling should address:

- local storage
- local processing
- synchronisation
- update procedures
- data expiry
- integrity
- access control
- recovery
- later reconciliation

Disconnected operation does not remove the need for classification and handling controls.

---

## 28. Data Integrity During Handling

Handling controls should protect against:

- unauthorised modification
- corruption
- substitution
- deletion
- replay
- accidental alteration

Where integrity is operationally consequential, the system should provide appropriate mechanisms to detect material alteration.

---

## 29. Data Availability

Protection should also consider availability.

Loss of access to critical data may affect:

- situational awareness
- decision support
- safety
- continuity of operations
- fail-safe behaviour

Availability requirements should therefore be linked to mission criticality.

---

## 30. Data Loss or Exposure

A suspected data loss, compromise or unauthorised disclosure should trigger the applicable incident-management process.

Assessment should determine:

- data affected
- classification
- source
- recipients
- exposure duration
- integrity implications
- AI systems affected
- operational implications
- containment actions
- notification requirements

---

## 31. Data Compromise and AI Assurance

A data compromise may affect more than confidentiality.

It may also affect:

- integrity
- provenance
- lineage
- model behaviour
- assurance evidence
- operational authorisation

Compromised training or operational data may require assessment of whether previous assurance remains valid.

---

## 32. Classification Changes

Data classification may change because of:

- aggregation
- new context
- changed mission
- changed threat
- new legal requirements
- new information
- changed operational sensitivity

Classification should therefore be reviewed when material circumstances change.

---

## 33. Downgrading and Declassification

Downgrading or declassification should only occur through the applicable authorised process.

D-AIGAAF should record:

- authority
- reason
- affected data
- effective date
- new handling requirement
- supporting evidence

No automated AI process should independently change classification without appropriate authority.

---

## 34. Data Retention

Retention should consider:

- mission need
- legal requirements
- operational requirements
- audit needs
- assurance requirements
- incident investigation
- contractual requirements
- storage risk

Retention periods should be defined according to applicable policy.

---

## 35. Secure Disposal

Disposal should ensure that data cannot be recovered or reused contrary to applicable requirements.

Disposal should cover:

- primary datasets
- copies
- temporary files
- backups where applicable
- derived datasets
- removable media
- exported data
- obsolete test data

Disposal should be recorded where required.

---

## 36. Classification and Lifecycle

Classification and handling should apply across the complete lifecycle:

**Acquire → Store → Process → Share → Use → Monitor → Change → Retain → Dispose**

Controls should remain effective when data moves between lifecycle stages.

---

## 37. Classification and TEVV

TEVV activities should use appropriately authorised data and environments.

Evidence should establish:

- what data was used
- classification
- handling conditions
- authorised environment
- relevant restrictions
- whether test conditions affected results

Security controls should not unintentionally invalidate the representativeness or validity of the evaluation.

---

## 38. Classification and Operational Authorisation

Operational authorisation should identify material data-handling conditions where relevant.

These may include:

- approved data sources
- approved processing environments
- access restrictions
- transfer restrictions
- retention requirements
- partner restrictions
- monitoring requirements

A capability should not be authorised to process data outside its approved handling environment without appropriate reassessment.

---

## 39. Classification and Change Management

Changes requiring reassessment may include:

- new data source
- new supplier
- new processing environment
- new cloud or external service
- new partner
- new mission
- new data type
- new model capability
- new inference capability

The impact should determine whether additional assurance or reauthorisation is required.

---

## 40. Classification Assessment Method

A practical assessment can follow:

1. Identify the data.
2. Identify its source and owner.
3. Determine applicable classification.
4. Assess aggregation and inference effects.
5. Define authorised users and purposes.
6. Define approved processing environments.
7. Define transfer and sharing conditions.
8. Define retention requirements.
9. Define disposal requirements.
10. Implement controls.
11. Verify compliance.
12. Monitor material changes.
13. Reassess when mission or context changes.

---

## 41. Handling Profile

A Data Handling Profile should record:

| Field | Description |
|---|---|
| Data ID | Unique identifier |
| Classification | Applicable classification |
| Owner | Accountable owner |
| Purpose | Authorised use |
| Users | Authorised user groups |
| Environment | Approved processing environment |
| Storage | Approved storage conditions |
| Transfer | Permitted transfer conditions |
| Sharing | Permitted recipients |
| Integrity | Required controls |
| Retention | Retention requirement |
| Disposal | Disposal method |
| Restrictions | Additional restrictions |
| Review | Review date |

---

## 42. Handling Assurance Levels

A working model may be:

### H1 — Basic

Routine data with standard controls.

### H2 — Controlled

Defined classification, ownership and access controls.

### H3 — Assured

Handling controls verified and monitored.

### H4 — High Assurance

Strong controls, independent verification and enhanced monitoring.

### H5 — Critical

Highest level of protection and assurance for highly consequential data.

These are D-AIGAAF working constructs and should be mapped to applicable national, defence and organisational classification systems before formal adoption.

---

## 43. Common Failure Modes

- Treating classification as equivalent to security assurance.
- Assuming low classification means low operational risk.
- Ignoring aggregation and inference.
- Copying operational data into uncontrolled development environments.
- Allowing supplier access without clear authority.
- Sharing data without checking onward-use restrictions.
- Treating metadata as harmless.
- Failing to classify AI-generated outputs appropriately.
- Retaining unnecessary copies.
- Failing to control temporary files and backups.
- Changing data use without reassessing handling requirements.
- Allowing classification changes without authorised approval.
- Failing to assess whether a compromise affects AI assurance.

---

## 44. Core Rules

1. **Classification must follow applicable authoritative rules.**
2. **Classification and AI suitability are separate determinations.**
3. **Access requires both authority and an authorised need.**
4. **Data should be processed only in appropriately authorised environments.**
5. **Aggregation and AI inference may increase sensitivity.**
6. **Metadata may require protection where appropriate.**
7. **Third-party data must retain applicable handling restrictions.**
8. **Data transfers must use authorised mechanisms.**
9. **Material changes in use, context or classification require reassessment.**
10. **Data compromise may affect confidentiality, integrity and AI assurance.**
11. **Retention and disposal must be controlled.**
12. **Classification and handling requirements must remain connected to the D-AIGAAF Golden Thread.**

---

## 45. Golden Thread

Data classification and handling contribute to:

**Mission Need → Data Dependency → Classification → Handling Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement / Disposal**

The objective is to establish:

**What data is involved → How sensitive it is → Who may use it → Where and how it may be processed → What protections apply → What happens when conditions change**

---

## 46. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **01 Strategy & Governance**
- **02 Mission & Use Case**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Governance**
- **05 Data & Information — Data Provenance**
- **05 Data & Information — Data Quality**
- **05 Data & Information — Data Representativeness**
- **05 Data & Information — Data Lineage**
- **06 AI Security**
- **07 Supply Chain & Sovereignty**
- **09 TEVV**
- **11 Operational Authorisation**
- **13 Continuous Assurance**
- **14 Incident & Fail-Safe**
- **15 Change & Reauthorisation**
- **16 Audit & Evidence**
- **21 Legal & Policy**
- **22 Acquisition & Procurement**
- **23 Interoperability & Coalition**
- **24 Architecture & Technical Controls**
- **26 Retirement & Decommissioning**

---

## 47. Summary

Data classification and handling establish the controls needed to protect information throughout the AI lifecycle.

The central chain is:

**Data → Classification → Authorised Purpose → Access → Processing → Transfer → Sharing → Retention → Disposal**

For consequential defence AI, the governing question is:

> **Is the data appropriately classified and handled throughout its lifecycle, with controls that remain effective across development, testing, operational employment, change and incident conditions?**

The answer should be demonstrable through **defined authority, documented handling requirements, technical and procedural controls, evidence, monitoring and auditable records**.
