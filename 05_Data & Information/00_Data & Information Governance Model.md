# D-AIGAAF — Data & Information Governance Model

## 1. Purpose

This document defines the governance model for data and information used, generated, exchanged, stored, transformed, or relied upon by defence AI capabilities.

The purpose is to ensure that data and information remain sufficiently **trustworthy, traceable, protected, relevant, and fit for purpose** throughout the AI lifecycle.

Data governance is an assurance concern because weaknesses in data can directly affect AI behaviour, operational decisions, human judgement, safety, security, and mission outcomes.

---

## 2. Core Principle

> **An AI capability cannot be more trustworthy than the data and information on which its consequential behaviour depends.**

Data must therefore be governed as a controlled lifecycle asset rather than treated as an interchangeable technical input.

The level of data governance and assurance should increase with:

**Consequence × Mission Criticality × Data Dependence × Exposure × Autonomy**

---

## 3. Scope

This model applies to:

- training, validation and test data
- operational and sensor-derived data
- intelligence and information inputs
- reference and geospatial data
- human-generated and synthetic data
- labelled and annotated data
- prompts, instructions and contextual inputs where they influence AI behaviour
- data exchanged between systems
- AI outputs used as information inputs to other systems
- operational logs and audit records
- supplier and third-party data
- data used during simulation and TEVV

It applies across development, acquisition, integration, deployment, employment, monitoring, change, revalidation, reauthorisation and retirement.

---

## 4. Data Governance Objectives

D-AIGAAF data governance should establish reasonable assurance that data is:

1. **Relevant** — appropriate to the mission and intended AI function.
2. **Accurate** — sufficiently correct for its intended use.
3. **Complete** — sufficiently complete for the decision or task.
4. **Representative** — reflects relevant operational conditions.
5. **Timely** — sufficiently current for the operational context.
6. **Traceable** — provenance and lineage can be established.
7. **Understandable** — meaning, limitations and context are documented.
8. **Secure** — protected against unauthorised access or manipulation.
9. **Integrity-preserved** — unauthorised alteration can be detected.
10. **Available** — accessible when required within authorised conditions.
11. **Controlled** — ownership, access and permitted uses are defined.
12. **Assurable** — sufficient evidence exists to support assurance claims.

---

## 5. Data Governance Architecture

Data governance operates through connected layers.

### 5.1 Strategic Layer

Defines:

- data governance policy
- organisational responsibilities
- sovereignty requirements
- information-sharing principles
- assurance expectations

### 5.2 Mission Layer

Defines:

- why the data is required
- what mission decision or function it supports
- operational relevance
- acceptable limitations
- consequence of erroneous or misleading data

### 5.3 Data Layer

Controls:

- sources
- provenance
- lineage
- quality
- representativeness
- classification and handling
- access
- integrity
- retention
- transformation
- versioning

### 5.4 AI Layer

Assesses how data affects:

- model behaviour
- training
- validation
- testing
- uncertainty
- robustness
- bias and error
- model performance
- distribution shift

### 5.5 Operational Layer

Controls:

- operational data ingestion
- sensor and information feeds
- freshness
- degraded-data conditions
- availability
- information integrity
- human interpretation

### 5.6 Assurance Layer

Provides evidence that:

- data is fit for intended purpose
- known limitations are understood
- controls operate as intended
- data-related risks are managed
- changes remain traceable

---

## 6. Data Governance Roles

### Data Owner

Responsible for:

- defining purpose and permitted use
- establishing ownership and accountability
- approving appropriate access and use
- identifying material data risks

### Data Steward

Responsible for:

- day-to-day data quality and management
- metadata and lineage
- validation
- issue identification
- controlled data changes

### AI System Owner

Responsible for understanding:

- which data the capability depends upon
- how data affects system behaviour
- operational data dependencies
- data-related limitations and risks

### AI Developer / Model Owner

Responsible for:

- documenting data used in model development
- demonstrating appropriate data handling
- identifying material data limitations
- maintaining reproducibility and traceability

### Operational AI Advisor (OAIA)

Provides operational and AI-informed judgement on:

- suitability of data for the mission context
- significance of data limitations
- operational implications of data drift
- whether data-related changes require escalation

### Assurance / TEVV Function

Independently assesses, where appropriate:

- data quality
- provenance
- representativeness
- robustness
- data-related failure modes
- evidence sufficiency

### Operational Authorising Authority

Determines whether data-related residual risk is acceptable within the proposed operational authorisation.

---

## 7. Data Governance Across the AI Lifecycle

Data governance should follow the same lifecycle discipline as the AI capability.

**Identify → Acquire → Validate → Prepare → Use → Monitor → Change → Revalidate → Retain / Dispose**

### Strategic Need

Identify the information required to support the capability.

### Requirements

Specify data requirements, including quality, timeliness, provenance and operational coverage.

### Development

Control training, validation and test data.

### Integration

Verify data interfaces, transformations and dependencies.

### TEVV

Test whether data conditions support intended performance and robustness.

### Deployment

Verify that operational data sources and controls match the authorised configuration.

### Employment

Monitor data quality, freshness, integrity and operational suitability.

### Change

Assess whether changes to data sources, pipelines or distributions affect assurance.

### Revalidation

Reassess data-dependent claims when material changes or new evidence arise.

### Retirement

Determine what data must be retained, transferred, archived or disposed of.

---

## 8. Mission-to-Data Traceability

Every consequential AI capability should be able to establish a traceable relationship between mission need and relevant data.

The core chain is:

**Mission Need → Decision / Function → AI Capability → Data Dependency → Data Source → Data Transformation → AI Output → Human Decision → Action → Outcome**

Where practical, this should be represented through unique identifiers.

---

## 9. Data Fitness for Purpose

Data quality should not be assessed only in abstract technical terms.

A dataset may be technically clean but operationally unsuitable.

Fitness for purpose should consider:

- intended mission
- operating environment
- decision consequence
- temporal relevance
- geographic or contextual coverage
- sensor characteristics
- adversarial conditions
- expected data availability
- human interpretation
- model dependence
- uncertainty
- known gaps

The governing question is:

> **Is this data sufficiently fit for the intended use under the conditions in which the AI capability is authorised?**

---

## 10. Data Quality Dimensions

| Dimension | Governance Question |
|---|---|
| Accuracy | Is the information sufficiently correct? |
| Completeness | Are important observations or fields missing? |
| Consistency | Do related sources agree where they should? |
| Timeliness | Is the information current enough? |
| Validity | Does the data conform to expected rules and meaning? |
| Uniqueness | Are duplicates creating misleading effects? |
| Relevance | Does the data support the intended mission? |
| Representativeness | Does it cover relevant operational conditions? |
| Integrity | Can unauthorised alteration be detected? |
| Provenance | Can the source and history be established? |

Not every dimension has equal importance for every use case. Assessment should be risk-proportional.

---

## 11. Data Provenance and Lineage

For consequential data, the organisation should be able to establish, to a reasonable degree:

- source
- collection method
- collection time
- responsible organisation
- transformations
- labelling or annotation
- processing steps
- version
- transfer history
- storage location
- downstream use

Where provenance cannot be established, the limitation should be recorded and reflected in risk and assurance decisions.

---

## 12. Data Representativeness

AI capabilities should not be validated solely against convenient or historically available datasets.

Representativeness should consider conditions relevant to the authorised use, including:

- environmental variation
- sensor variation
- geographic variation
- temporal variation
- operational variation
- expected adversarial conditions
- degraded conditions
- unusual or edge cases
- relevant data scarcity

Absence of representative data should be treated as an assurance limitation rather than silently treated as evidence of capability.

---

## 13. Data and Operational Environment

Data behaviour can change when the operational environment changes.

Relevant factors may include:

- sensor degradation
- weather
- terrain
- lighting
- electromagnetic conditions
- communications availability
- data latency
- bandwidth limitations
- disconnected operation
- adversarial interference
- changes in patterns of activity
- unexpected data sources

Where conditions fall outside the validated data envelope, the limitation should be identified and the appropriate operational restriction or escalation applied.

---

## 14. Data Integrity

Data integrity controls should address:

- unauthorised modification
- corruption
- accidental alteration
- malicious manipulation
- pipeline failures
- inconsistent versions
- compromised sources
- data injection
- integrity failures during transfer

For high-consequence applications, the organisation should be able to determine whether information used by the AI capability has been altered or corrupted.

---

## 15. Data Security

Data governance must operate alongside AI Security.

Controls may include:

- identity and access management
- least-privilege access
- segregation
- encryption where appropriate
- secure transfer
- source validation
- integrity monitoring
- privileged-access controls
- supply-chain controls
- incident response

Security controls should not prevent legitimate operational access where availability is mission-critical. Trade-offs should be explicitly assessed.

---

## 16. Data and Information Integrity

AI systems may consume information that is technically valid but operationally misleading.

Information integrity therefore includes assessment of:

- source reliability
- context
- timeliness
- conflicting information
- stale information
- manipulated information
- missing context
- misleading correlations
- uncertainty
- provenance

AI outputs should not automatically inherit the credibility of their inputs.

Where input information is uncertain or contested, the AI capability should preserve or communicate that uncertainty where technically and operationally feasible.

---

## 17. Data Uncertainty

Data uncertainty should be identified where it could materially affect an AI output.

Examples include:

- incomplete observations
- conflicting sources
- stale information
- uncertain labels
- ambiguous classifications
- sensor limitations
- missing metadata
- insufficient operational coverage

The system should avoid presenting uncertain information as established fact.

Data uncertainty should flow into:

**Data Assessment → Model/System Behaviour → AI Output → Human Decision**

---

## 18. Data Drift

Operational data can change over time.

Relevant forms include:

- statistical distribution drift
- concept drift
- sensor drift
- source drift
- environmental drift
- operational-pattern drift
- adversarial adaptation

Material drift should trigger assessment of whether:

- performance remains valid
- risk has changed
- operational restrictions are required
- revalidation is necessary
- reauthorisation is necessary

---

## 19. Data Poisoning and Manipulation

Where AI depends on externally generated or operationally collected data, deliberate manipulation may affect system behaviour.

Governance should consider:

- malicious data injection
- compromised data sources
- manipulated labels
- contaminated training data
- adversarial examples
- compromised update pipelines
- falsified operational information

Controls should include appropriate prevention, detection, investigation and recovery mechanisms.

Detailed technical countermeasures belong in **06 AI Security** and **24 Architecture & Technical Controls**.

---

## 20. Data Changes

Changes to data may affect AI behaviour even when the model itself is unchanged.

Examples include:

- new data sources
- changed sensors
- changed labelling rules
- changed preprocessing
- changed data pipelines
- changed collection conditions
- changed reference datasets
- changed operational distributions

A material data change should therefore be subject to:

**Change Identification → Impact Assessment → Testing / Evaluation → Assurance Decision → Revalidation / Reauthorisation where required**

---

## 21. Data Dependencies

AI capabilities should maintain visibility of critical data dependencies.

Dependencies may include:

- internal databases
- external information sources
- sensors
- mapping or reference services
- communications systems
- third-party datasets
- cloud or hosted services
- software pipelines
- human-generated inputs

Critical dependencies should be recorded in the capability and configuration records.

---

## 22. Data Availability and Degraded Conditions

Operational AI should not assume that ideal data availability will always exist.

Where relevant, assurance should address:

- missing data
- delayed data
- intermittent feeds
- degraded sensors
- communications loss
- disconnected operation
- conflicting sources
- reduced bandwidth
- incomplete information

The capability should have defined behaviour for material degradation.

Possible responses include:

- continue with reduced confidence
- request additional information
- reduce autonomy
- restrict functionality
- transfer to human-only decision making
- enter a safe state
- suspend operation

---

## 23. Data Sharing and Exchange

Data sharing should define:

- purpose
- authority
- permitted users
- permitted uses
- provenance
- classification and handling requirements
- security controls
- integrity requirements
- retention requirements
- downstream responsibilities

Receiving data from a trusted organisation does not remove the recipient's responsibility to assess whether it is fit for the intended AI use.

---

## 24. Third-Party and Supplier Data

Supplier-provided data should be assessed for:

- provenance
- ownership
- licensing and permitted use
- collection methods
- quality
- representativeness
- security
- integrity
- update mechanisms
- dependencies
- known limitations

Where supplier claims cannot be independently verified, that limitation should be reflected in assurance confidence.

---

## 25. Data Retention and Disposal

Retention should be based on:

- operational need
- assurance requirements
- auditability
- incident investigation
- legal and policy requirements
- lessons learned
- security considerations
- applicable information-handling obligations

Disposal should be controlled and verifiable where residual copies could create security, operational or governance risk.

---

## 26. Data Governance and TEVV

TEVV should examine whether data supports the intended assurance claims.

Relevant questions include:

- Was the test data representative?
- Was data leakage controlled?
- Were important edge cases included?
- Were adversarial conditions assessed?
- Were operational data limitations reproduced?
- Were data transformations controlled?
- Can results be reproduced?
- Do test results remain valid after data changes?

Evidence should record significant limitations rather than presenting benchmark performance without context.

---

## 27. Data Governance and Operational Authorisation

Operational authorisation should consider whether data conditions are sufficiently understood for the intended mission.

Authorisation may include conditions relating to:

- approved data sources
- permitted data types
- minimum data quality
- freshness requirements
- required provenance
- operational coverage
- degraded-data behaviour
- data integrity controls
- monitoring thresholds
- restrictions on use

A capability may be technically functional but not operationally authorised if its required data conditions cannot be assured.

---

## 28. Data Governance and Human Authority

Humans remain responsible for decisions within the authority assigned to them.

Data governance should support human judgement by making relevant limitations visible.

Where AI recommendations depend on questionable, incomplete or conflicting information, the human decision maker should be able to:

- understand that limitation
- challenge the recommendation
- seek additional information
- reject or override the recommendation
- record the basis for a consequential decision where required

---

## 29. Data Governance and the OAIA

The Operational AI Advisor provides a bridge between technical data characteristics and operational decision-making.

The OAIA may advise on:

- whether data conditions match the authorised mission
- significance of data limitations
- operational implications of data drift
- whether data-related anomalies require escalation
- whether degraded data should change autonomy or employment conditions
- whether revalidation or reauthorisation should be considered

The OAIA does not replace technical assurance, command authority, or formal risk acceptance.

---

## 30. Data Assurance Levels

A working assurance approach may use:

### D1 — Basic

Limited consequence and low dependence on sensitive or dynamic data.

### D2 — Controlled

Defined data sources, quality controls and traceability.

### D3 — Assured

Representative evidence, controlled provenance, integrity and operational validation.

### D4 — High Assurance

Strong evidence across operational environments, adversarial conditions, integrity, provenance, monitoring and change control.

### D5 — Critical Assurance

Highest level of evidence and independent scrutiny for highly consequential AI use.

These levels are a D-AIGAAF working construct and should be mapped to applicable national, defence, legal and organisational requirements before formal adoption.

---

## 31. Data Risk Assessment

Data risks should be assessed in the context of:

**Consequence × Mission Criticality × Data Dependence × Exposure × Uncertainty**

Examples include:

- incorrect data
- incomplete data
- stale data
- manipulated data
- unrepresentative data
- unavailable data
- unknown provenance
- conflicting data
- data leakage
- data poisoning
- excessive dependence on a single source

Data risks should feed the broader **03 Risk & Autonomy** process.

---

## 32. Data Governance Decision Gates

### G1 — Data Need

Is the required data identified?

### G2 — Data Suitability

Is the data sufficiently fit for purpose?

### G3 — Data Assurance

Is sufficient evidence available to support intended use?

### G4 — Operational Data Readiness

Are operational data sources and dependencies ready?

### G5 — Continued Validity

Does operational evidence indicate that data assumptions remain valid?

### G6 — Change Decision

Has a material data change occurred?

### G7 — Revalidation

Does new evidence require revalidation?

### G8 — Retirement / Disposal

Have data dependencies and retention obligations been appropriately closed?

---

## 33. Data Records

Relevant records should include:

- Data Asset Record
- Data Source Record
- Data Provenance Record
- Data Lineage Record
- Data Quality Assessment
- Data Representativeness Assessment
- Data Validation Record
- Data Integrity Record
- Data Access Record
- Data Change Record
- Data Incident Record
- Data Assurance Record

These records should connect to the wider lifecycle records defined in **04 AI Lifecycle**.

---

## 34. Evidence Requirements

Evidence should be sufficient to establish, as applicable:

- what data was used
- where it came from
- how it was transformed
- who controlled it
- what limitations existed
- how quality was assessed
- how representative it was
- how integrity was protected
- what changes occurred
- how data affected assurance claims
- whether operational conditions remain within the validated envelope

Evidence quality should be explicitly assessed.

---

## 35. Failure Modes

Common data governance failures include:

- treating data as a purely technical concern
- assuming clean data is representative data
- failing to record provenance
- relying on unverified supplier data
- ignoring operational data drift
- testing only on convenient datasets
- ignoring degraded data conditions
- treating conflicting information as resolved
- failing to detect data manipulation
- changing data pipelines without reassessment
- assuming model validation remains valid after material data changes
- allowing AI outputs to conceal input uncertainty
- losing traceability between operational data and consequential decisions

---

## 36. Core Rules

1. **Data must be governed according to mission consequence and risk.**
2. **Data provenance should be established wherever practicable.**
3. **Data quality must be assessed in operational context.**
4. **Representativeness is an assurance concern, not merely a statistical concern.**
5. **Operational data conditions must be included in TEVV where they can affect performance.**
6. **Material data changes must trigger impact assessment.**
7. **Data uncertainty should not be concealed by AI outputs.**
8. **Critical data dependencies must be visible.**
9. **Data integrity is part of AI security and operational assurance.**
10. **Third-party data does not transfer accountability for its operational use.**
11. **Data-related limitations must be visible to appropriate human decision makers.**
12. **Data governance evidence must connect to the Golden Thread.**

---

## 37. Golden Thread

Data governance contributes to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Dependencies → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement → Decommissioning**

The objective is to ensure that the organisation can explain not merely **what data an AI system used**, but **why that data was considered sufficiently trustworthy for the authorised mission and what happened when its conditions changed**.

---

## 38. Relationship to Other D-AIGAAF Sections

This model should be read with:

- **00 Framework** — overall architecture and Golden Thread
- **02 Mission & Use Case** — mission purpose and operational context
- **03 Risk & Autonomy** — data-related risk and autonomy implications
- **04 AI Lifecycle** — lifecycle governance and records
- **06 AI Security** — protection against data compromise and manipulation
- **07 Supply Chain & Sovereignty** — third-party data and provenance
- **08 Human Authority** — human interpretation and decision accountability
- **09 TEVV** — evidence regarding data-dependent performance
- **10 Operational Environment** — environmental data conditions
- **11 Operational Authorisation** — authorised data conditions
- **13 Continuous Assurance** — monitoring data drift and integrity
- **14 Incident & Fail-Safe** — response to data-related incidents
- **15 Change & Reauthorisation** — material data changes
- **16 Audit & Evidence** — evidence and traceability
- **24 Architecture & Technical Controls** — technical data controls
- **25 Documentation & Knowledge** — data documentation
- **26 Retirement & Decommissioning** — data closure and disposition

---

## 39. Summary Model

D-AIGAAF treats data and information as an assurance-critical dependency.

The model can be summarised as:

**Purpose → Source → Provenance → Quality → Representativeness → Integrity → Security → Operational Fit → AI Behaviour → Human Decision → Mission Outcome**

For consequential AI capabilities, the central governance question is:

> **Can we demonstrate that the information influencing this AI capability is sufficiently trustworthy, understood and controlled for the mission and conditions under which the capability is authorised?**

If that question cannot be answered with appropriate evidence, the limitation should be reflected in risk, assurance and operational authority.
