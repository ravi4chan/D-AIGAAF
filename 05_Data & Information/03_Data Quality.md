# D-AIGAAF — Data Quality

## 1. Purpose

This document defines the governance and assurance approach for assessing and managing the quality of data used by defence AI capabilities.

Data quality is not an abstract measure of whether a dataset is "good". It is a determination of whether data is **sufficiently accurate, complete, consistent, timely, relevant, representative, valid, traceable and reliable for its intended use and consequence level**.

---

## 2. Core Principle

> **Data quality must be judged against the mission and intended use, not against a generic definition of "clean data".**

A dataset may be technically well-formed and still be unsuitable for a consequential AI capability.

The required level of data quality should therefore increase with:

**Consequence × Mission Criticality × Data Dependence × Uncertainty**

---

## 3. Scope

This document applies to:

- training data
- validation and test data
- operational data
- sensor-derived data
- intelligence and information inputs
- geospatial and reference data
- labelled and annotated datasets
- synthetic data
- third-party data
- derived datasets
- data pipelines and transformations
- data used in TEVV
- operational logs where data quality affects assurance

---

## 4. Data Quality Objectives

Data quality governance should establish reasonable confidence that data:

1. is accurate enough for the intended purpose
2. is sufficiently complete
3. is internally consistent
4. conforms to expected definitions and formats
5. is sufficiently current
6. is relevant to the mission
7. represents relevant operating conditions
8. has sufficient provenance
9. retains integrity
10. has known limitations
11. remains fit for purpose after material change

---

## 5. Data Quality Dimensions

D-AIGAAF uses the following core dimensions.

| Dimension | Meaning | Key Question |
|---|---|---|
| Accuracy | Correctness of information | Is it sufficiently correct? |
| Completeness | Presence of required information | Is important information missing? |
| Consistency | Agreement across related records/sources | Are contradictions understood? |
| Validity | Conformance to defined rules | Is the data structurally and semantically valid? |
| Timeliness | Currency relative to use | Is it current enough? |
| Relevance | Suitability for intended purpose | Does it answer the right question? |
| Representativeness | Coverage of relevant conditions | Does it reflect the intended operational domain? |
| Uniqueness | Absence of problematic duplication | Are duplicates distorting results? |
| Provenance | Traceability to origin | Can its source and history be established? |
| Integrity | Protection against unauthorised change | Can manipulation or corruption be detected? |

Not every dimension has equal importance for every capability.

---

## 6. Quality Thresholds

Quality thresholds should be defined according to intended use.

For example:

- exploratory analysis may tolerate significant uncertainty
- administrative decision support may require moderate quality
- operational decision support may require stronger evidence
- high-consequence AI may require stringent quality and validation
- highly autonomous systems may require the highest confidence in relevant data conditions

A numerical quality score should not replace judgement about operational suitability.

---

## 7. Data Quality Requirements

Data requirements should be established during the AI requirements phase.

Requirements may specify:

- acceptable error rates
- minimum completeness
- required freshness
- source reliability
- geographic coverage
- environmental coverage
- sensor characteristics
- label accuracy
- permitted missing values
- expected data distributions
- integrity requirements
- provenance requirements
- degraded-data behaviour

These requirements should be traceable to mission needs and TEVV.

---

## 8. Accuracy

Accuracy concerns whether data corresponds sufficiently to reality or an accepted reference.

Assessment methods may include:

- comparison with authoritative references
- cross-source comparison
- sampling
- expert review
- sensor calibration
- independent verification
- historical consistency checks

Accuracy requirements should be proportional to consequence.

A small numerical error may be irrelevant for one application but operationally significant for another.

---

## 9. Completeness

Completeness concerns whether important information is missing.

Assessment should consider:

- missing fields
- missing observations
- missing time periods
- missing geographic areas
- missing classes
- missing edge cases
- incomplete sensor coverage
- missing contextual information

Missing information should not automatically be treated as a neutral value.

Where missingness can affect AI behaviour, the system should account for it explicitly.

---

## 10. Consistency

Consistency concerns whether related data agrees sufficiently.

Potential problems include:

- conflicting databases
- incompatible definitions
- inconsistent timestamps
- duplicate records
- different coordinate systems
- incompatible units
- conflicting labels
- contradictory information sources

Conflicts should be identified and handled rather than silently averaged or discarded without justification.

---

## 11. Validity

Validity concerns whether data conforms to expected structural and semantic rules.

Examples include:

- valid formats
- valid ranges
- correct units
- valid identifiers
- permitted categories
- valid relationships
- expected schema
- meaningful values

A dataset can be structurally valid while still being factually inaccurate.

Validity therefore does not replace accuracy assessment.

---

## 12. Timeliness

Timeliness depends on the mission.

Relevant factors include:

- collection time
- ingestion delay
- processing delay
- transmission delay
- update frequency
- operational tempo
- information decay

For dynamic environments, stale information may become misleading even if it was accurate when collected.

Timeliness requirements should therefore be explicit where operationally relevant.

---

## 13. Relevance

Data should be relevant to the decision or AI function.

Questions include:

- Does the data represent the problem being solved?
- Does it contain the information needed?
- Is it being used outside its intended purpose?
- Does the data remain relevant after a mission change?
- Are irrelevant correlations influencing model behaviour?

Large datasets are not necessarily better datasets.

---

## 14. Representativeness

Representativeness is addressed in greater detail in **04_Data_Representativeness.md**, but data-quality governance should ensure that relevant variation is considered.

This may include:

- environment
- geography
- season
- time
- sensor type
- operational conditions
- adversarial conditions
- degraded conditions
- unusual cases

High aggregate quality cannot compensate for systematic absence of important operating conditions.

---

## 15. Uniqueness and Duplication

Duplicate records can distort:

- model training
- evaluation results
- statistical analysis
- confidence estimates
- frequency calculations
- operational assessments

Quality controls should identify and appropriately handle duplication.

Duplicates should not be removed automatically where repeated observations are meaningful.

---

## 16. Data Quality and Provenance

Quality assessment should be connected to provenance.

For material datasets, assess:

**Source → Collection → Processing → Transformation → Dataset**

Unknown or weak provenance may reduce confidence even when other quality measures appear strong.

---

## 17. Data Quality and Labels

For supervised or labelled AI systems, label quality can directly affect model behaviour.

Assessment may include:

- label accuracy
- annotation consistency
- inter-annotator agreement
- labelling guidance
- ambiguous cases
- correction rates
- class imbalance
- automated labelling effects

Material labelling changes should be controlled and documented.

---

## 18. Data Quality and Synthetic Data

Synthetic data should be assessed for:

- realism
- relevance
- representativeness
- generation artefacts
- duplication
- distribution differences
- hidden assumptions
- relationship to real operational data

Synthetic data should not automatically be treated as equivalent to real-world observations.

---

## 19. Data Quality and Training

Training-data quality affects:

- learned representations
- model performance
- generalisation
- robustness
- bias
- uncertainty
- failure modes

Development teams should understand important limitations in the training data.

High training-data volume does not by itself demonstrate sufficient quality.

---

## 20. Data Quality and Validation / Test Data

Validation and test data should be assessed independently from training data.

Governance should examine:

- leakage
- duplication between training and test sets
- representativeness
- label quality
- environmental coverage
- edge cases
- adversarial conditions
- operational relevance

A test dataset that does not represent the intended operational domain may produce misleading assurance.

---

## 21. Data Quality and Operational Environment

Data quality should be assessed under conditions relevant to actual employment.

Relevant conditions may include:

- degraded sensors
- limited communications
- intermittent data
- high latency
- environmental variation
- unexpected information sources
- adversarial manipulation
- incomplete observations

The objective is not to guarantee perfect data but to establish how the AI capability behaves when data quality deteriorates.

---

## 22. Data Quality Degradation

Quality may deteriorate because of:

- source changes
- sensor degradation
- infrastructure failures
- environmental changes
- operational changes
- adversarial activity
- pipeline failures
- human error
- data drift

Material degradation should trigger assessment against established thresholds.

Possible responses include:

- continue with reduced confidence
- increase human oversight
- reduce autonomy
- restrict functionality
- request additional information
- transfer to human-only operation
- suspend operation

---

## 23. Data Quality Monitoring

Operational monitoring should track relevant quality indicators.

Examples include:

- missing-data rate
- error rate
- freshness
- source availability
- distribution changes
- sensor health
- label quality
- integrity anomalies
- conflicting-source frequency
- unexpected values

Monitoring frequency should be risk-proportional.

---

## 24. Data Quality Alerts

A working status model may include:

### Normal

Quality remains within approved thresholds.

### Watch

A trend indicates possible deterioration.

### Alert

A defined quality threshold has been breached.

### Restricted

The capability remains available under reduced conditions.

### Suspended

Quality conditions are no longer sufficient for authorised use.

### Revalidation Required

The evidence supporting previous assurance may no longer remain valid.

---

## 25. Data Quality and AI Uncertainty

Poor or uncertain input data should influence AI confidence where technically feasible.

The system should avoid creating false certainty from uncertain inputs.

Where appropriate, AI behaviour may include:

- confidence reduction
- uncertainty disclosure
- abstention
- request for additional information
- human escalation
- restricted output

Data quality and model confidence should not be treated as identical concepts.

---

## 26. Data Quality and Human Authority

Human decision makers should be informed of material data limitations where those limitations can affect consequential decisions.

The objective is to support informed judgement rather than merely present a model output.

A human decision maker should be able to understand, where appropriate:

- whether important data is missing
- whether sources conflict
- whether information is stale
- whether data falls outside validated conditions
- whether confidence is reduced

---

## 27. Data Quality and Autonomy

Autonomy should remain within conditions supported by available data quality.

For example, deterioration in critical data may require:

**Higher Uncertainty → Lower Permitted Autonomy → Greater Human Involvement**

This relationship should be explicitly designed, tested and authorised where applicable.

---

## 28. Data Quality and TEVV

TEVV should demonstrate that data quality supports the intended assurance claims.

Evidence should address:

- quality thresholds
- quality assessment methods
- representative conditions
- known limitations
- degraded-data performance
- robustness
- uncertainty
- data-related failure modes

Quality evidence should be linked to the relevant model and system configuration.

---

## 29. Data Quality and Operational Authorisation

Operational authorisation may establish data-quality conditions such as:

- approved data sources
- minimum accuracy
- minimum completeness
- maximum acceptable latency
- minimum freshness
- required integrity
- permitted degradation
- monitoring thresholds
- escalation requirements

Operating outside these conditions may require restriction, reassessment or suspension.

---

## 30. Data Quality and Change Management

Changes should be assessed when they may affect quality.

Examples include:

- new source
- new sensor
- changed collection method
- changed preprocessing
- changed labelling
- changed schema
- changed reference data
- changed data pipeline
- changed operational distribution

The response should be based on potential operational impact.

---

## 31. Data Quality Assessment Method

A practical assessment can follow:

1. Define intended use.
2. Identify required quality dimensions.
3. Establish thresholds.
4. Identify data sources.
5. Assess current quality.
6. Identify gaps and limitations.
7. Assess operational consequences.
8. Determine controls.
9. Test under relevant conditions.
10. Record evidence.
11. Approve, restrict, reject or remediate.
12. Monitor after approval.

---

## 32. Quality Gap Management

A quality gap exists when actual quality does not meet an established requirement.

Each material gap should record:

- gap ID
- affected data
- requirement
- actual condition
- consequence
- risk
- mitigation
- responsible owner
- temporary restriction, if any
- target resolution
- closure evidence

A gap should not be considered closed merely because the dataset was technically modified.

---

## 33. Data Quality Assurance Levels

A working scale may be:

### Q1 — Basic

Limited consequence; basic validation and quality controls.

### Q2 — Controlled

Defined sources, thresholds and documented quality checks.

### Q3 — Assured

Evidence demonstrates fitness for intended operational use.

### Q4 — High Assurance

Strong evidence across representative, degraded and adversarial conditions.

### Q5 — Critical Assurance

Highest level of evidence and independent scrutiny for highly consequential use.

These are D-AIGAAF working constructs and should be mapped to applicable organisational, national and defence requirements before formal adoption.

---

## 34. Data Quality Records

A Data Quality Record should include, where applicable:

| Field | Description |
|---|---|
| Quality ID | Unique identifier |
| Data Asset ID | Dataset assessed |
| Intended Use | Purpose |
| Quality Dimensions | Dimensions assessed |
| Requirements | Applicable thresholds |
| Assessment Method | How quality was measured |
| Results | Assessment results |
| Limitations | Known gaps |
| Risk | Associated risk |
| Controls | Mitigations |
| Evidence | Supporting evidence |
| Status | Current quality status |
| Owner | Accountable person/organisation |
| Review Date | Next review |

---

## 35. Evidence Requirements

Evidence may include:

- validation reports
- sampling results
- reference comparisons
- sensor calibration records
- quality metrics
- expert assessments
- label audits
- data profiling
- integrity checks
- distribution analysis
- operational monitoring
- TEVV results

Evidence should identify its scope and limitations.

---

## 36. Data Quality Incidents

A quality incident occurs when a material quality failure affects or may affect an AI capability.

Examples include:

- unexpected error rates
- widespread missing data
- stale operational information
- incorrect labels
- corrupted records
- source failures
- major distribution shifts
- previously unknown data gaps

Incident assessment should determine whether:

- AI behaviour was affected
- decisions may have been affected
- operational authority remains valid
- additional testing is required
- revalidation is required
- reauthorisation is required

---

## 37. Common Failure Modes

- Treating data cleanliness as proof of operational suitability.
- Using a single quality score to hide important weaknesses.
- Ignoring missing or conflicting information.
- Testing only on ideal data.
- Assuming training-data quality guarantees operational performance.
- Ignoring sensor and environmental degradation.
- Treating stale information as current.
- Failing to establish quality thresholds before testing.
- Changing data pipelines without quality reassessment.
- Ignoring label uncertainty.
- Treating synthetic data as equivalent to real-world data.
- Allowing poor data quality to remain invisible to human decision makers.

---

## 38. Core Rules

1. **Data quality must be assessed against intended use.**
2. **Quality thresholds should reflect consequence and mission criticality.**
3. **Accuracy alone is insufficient; completeness, timeliness, relevance and representativeness also matter.**
4. **Data quality limitations must be documented.**
5. **Critical data quality conditions should be tested in relevant operational environments.**
6. **Material quality degradation should trigger defined escalation.**
7. **Data quality should influence assurance and, where appropriate, permitted autonomy.**
8. **Quality evidence must remain linked to the relevant configuration.**
9. **Third-party data must meet the quality expectations of its intended use.**
10. **Material data-quality changes require impact assessment.**
11. **Poor or uncertain data should not be converted into false AI certainty.**
12. **Data quality evidence must connect to the D-AIGAAF Golden Thread.**

---

## 39. Golden Thread

Data quality contributes to:

**Mission Need → Risk → Requirements → Data Dependency → Quality Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement → Decommissioning**

The objective is to establish a defensible relationship between:

**What data is needed → What quality is required → What quality actually exists → What limitations remain → How those limitations affect AI behaviour and operational authority**

---

## 40. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **02 Mission & Use Case**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Governance**
- **05 Data & Information — Data Provenance**
- **04_Data_Representativeness.md**
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

---

## 41. Summary

Data quality is a mission-dependent assurance property.

The central chain is:

**Purpose → Requirement → Quality Assessment → Limitation → Risk → Control → Evidence → Operational Authority**

For consequential defence AI, the governing question is:

> **Is the data sufficiently accurate, complete, timely, relevant, representative, traceable and reliable for the mission and conditions under which the AI capability is authorised?**

If not, the deficiency should be visible in **risk, assurance, operational restrictions, human oversight and—where necessary—revalidation or reauthorisation**.
