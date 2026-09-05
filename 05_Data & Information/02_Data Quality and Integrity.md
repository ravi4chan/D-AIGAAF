# 02 Data Quality and Integrity

## 1. Purpose

This document establishes requirements for assessing, maintaining, monitoring, and assuring the quality and integrity of data used by defence AI capabilities.

It addresses whether data is sufficiently reliable for its authorised purpose and whether it can be protected from unintended or unauthorised alteration.

## 2. Core Principle

> **Data quality and integrity must be assessed against the mission, consequence, and operating conditions in which the AI capability is authorised to function.**

A dataset should not be considered suitable merely because it is large, technically valid, or historically successful.

## 3. Data Quality Dimensions

D-AIGAAF should consider the following dimensions:

| Dimension | Key question |
|---|---|
| Accuracy | Does the data correctly represent what it claims to represent? |
| Completeness | Are material values or observations missing? |
| Consistency | Are related records compatible with each other? |
| Validity | Does the data conform to required formats and rules? |
| Timeliness | Is the data sufficiently current for the intended decision? |
| Relevance | Does the data support the authorised purpose? |
| Representativeness | Does it reflect the intended operational domain? |
| Uniqueness | Are duplicate or conflicting records appropriately handled? |
| Provenance | Is the source sufficiently understood? |
| Integrity | Can unauthorised or unintended alteration be detected or prevented? |

Not every dimension will have equal importance for every AI capability.

## 4. Mission-Dependent Quality

Data quality thresholds should be derived from:

**Mission + Use Case + Consequence + Data Dependence + Operating Conditions**

A capability supporting low-consequence analysis may tolerate limitations that would be unacceptable for a high-consequence decision.

The organisation should therefore define **minimum acceptable data conditions** for each authorised use rather than applying a single universal quality threshold.

## 5. Accuracy

Accuracy should be assessed using methods appropriate to the type of data.

Assessment may include:

- Comparison with trusted reference information
- Cross-source verification
- Measurement uncertainty
- Error rates
- Annotation accuracy
- Sensor performance
- Temporal accuracy
- Geospatial accuracy
- Human verification

Known systematic errors should be documented rather than hidden by aggregate performance metrics.

## 6. Completeness

Completeness should consider whether missing information could materially affect AI behaviour or decisions.

The assessment should identify:

- Missing fields
- Missing observations
- Missing time periods
- Missing geographic areas
- Missing classes or events
- Missing edge cases
- Missing metadata
- Unknown or unavailable source information

Missing data should not automatically be treated as harmless.

## 7. Consistency and Validity

Data should be checked for:

- Conflicting values
- Incompatible formats
- Invalid ranges
- Broken relationships
- Duplicate records
- Timestamp inconsistencies
- Schema changes
- Unit mismatches
- Encoding problems

Where inconsistencies cannot be resolved, the uncertainty should be preserved and appropriately communicated.

## 8. Timeliness and Freshness

Timeliness should be determined by the mission.

The organisation should define, where appropriate:

- Maximum acceptable data age
- Refresh requirements
- Update frequency
- Synchronisation requirements
- Time-source dependencies
- Acceptable latency

Stale data may remain technically accurate while becoming operationally misleading.

## 9. Relevance and Fitness for Purpose

Data should be evaluated against the actual AI function.

The assessment should determine:

- Why the data is required
- Which system function depends upon it
- What decisions may rely upon it
- What assumptions are made about it
- What limitations exist
- Whether alternative or supplementary sources are required

Data should not be retained or used merely because it is available.

## 10. Data Integrity

Integrity concerns whether data remains complete, consistent, authentic, and unaltered except through authorised processes.

Controls should address:

- Unauthorised modification
- Accidental alteration
- Corruption
- Incomplete transfers
- Synchronisation failures
- Uncontrolled transformations
- Malicious manipulation
- Data poisoning
- Configuration errors

Integrity controls should extend across:

**Acquisition → Storage → Processing → Transfer → Training → Testing → Deployment → Operational Use**

## 11. Integrity Controls

Appropriate controls may include:

- Access control
- Authentication
- Authorised write permissions
- Cryptographic integrity mechanisms
- Checksums or hashes
- Version control
- Immutable or protected records
- Change logging
- Validation checks
- Separation of duties
- Backup and recovery
- Integrity monitoring

The exact control set should be proportionate to risk and applicable security requirements.

## 12. Data Validation

Validation should determine whether data meets defined requirements before it is used for a consequential purpose.

Validation may examine:

- Structure
- Values
- Sources
- Quality
- Integrity
- Provenance
- Representativeness
- Temporal relevance
- Environmental relevance
- Expected distributions
- Known failure conditions

Validation should be repeated when material conditions or data pipelines change.

## 13. Training, Validation and Test Data

Data quality requirements apply separately to:

- Training data
- Validation data
- Test data
- Operational data

The organisation should avoid assuming that strong training-data quality automatically establishes strong evaluation or operational assurance.

Potential concerns include:

- Data leakage
- Duplicate samples
- Biased sampling
- Unrepresentative test sets
- Contamination
- Label errors
- Distribution mismatch
- Insufficient edge cases

## 14. Data Quality in Operational Environments

Operational data may differ materially from development or test data.

Monitoring should consider:

- Environmental changes
- Sensor degradation
- Communications constraints
- Data latency
- Missing observations
- New patterns
- Adversarial manipulation
- Unexpected distributions
- Infrastructure degradation

Where operational data falls outside authorised assumptions, the AI capability should respond according to its approved degraded-mode or restriction procedures.

## 15. Quality and AI Uncertainty

Poor data quality can produce misleading AI outputs even when the model itself has not changed.

The system should, where technically feasible, communicate material uncertainty associated with:

- Missing information
- Conflicting sources
- Stale information
- Low-quality inputs
- Distribution shift
- Sensor limitations
- Unknown conditions

The objective is to avoid presenting an uncertain result with unjustified confidence.

## 16. Data Quality Monitoring

Quality should be monitored throughout operational employment where data materially affects system behaviour.

Possible monitoring indicators include:

- Error rates
- Missing-data rates
- Freshness
- Distribution changes
- Sensor health
- Validation failures
- Integrity alerts
- Source availability
- Annotation quality
- Out-of-range values

### Suggested Statuses

| Status | Meaning |
|---|---|
| Normal | Data remains within authorised conditions |
| Watch | Early indication of degradation |
| Alert | Material quality concern detected |
| Restricted | Use requires additional controls or limitations |
| Suspended | Data conditions are incompatible with authorised use |
| Revalidation Required | Existing assurance may no longer be valid |

## 17. Data Quality Risk

A working D-AIGAAF formulation is:

**Data Quality Risk = Consequence × Data Dependence × Data Uncertainty × Exposure**

Higher risk should generally result in stronger validation, monitoring, integrity controls, and human oversight.

The formula is a framework construct and is not intended to replace an organisation's approved risk methodology.

## 18. Quality Gaps

When data does not meet the required threshold, the organisation should determine whether to:

1. Improve the data
2. Supplement it with another source
3. Restrict the AI function
4. Increase human oversight
5. Increase uncertainty disclosure
6. Apply operational constraints
7. Conduct additional TEVV
8. Suspend the capability
9. Accept the residual risk through the appropriate authority

A quality gap should not be silently absorbed into system performance.

## 19. Data Quality Assurance Levels

D-AIGAAF may use the following working levels:

| Level | Description |
|---|---|
| Q1 | Limited understanding or evidence |
| Q2 | Basic quality controls established |
| Q3 | Controlled, measured, and traceable |
| Q4 | Strong evidence under representative conditions |
| Q5 | High confidence for the authorised purpose and operating conditions |

These are framework constructs and should be mapped to applicable organisational and national standards.

## 20. Change and Revalidation

Material changes that may affect data quality or integrity should trigger impact assessment.

Examples include:

- New sources
- Source removal
- Sensor changes
- Processing changes
- Schema changes
- New preprocessing methods
- Changes in labelling
- Significant distribution changes
- New external dependencies
- Changes in operating environment

Depending on impact, the change may require:

**Review → Validation → TEVV → Revalidation → Reauthorisation**

## 21. Data Quality Record

A Data Quality Record should capture, where applicable:

- Data Asset ID
- Intended use
- Quality requirements
- Quality metrics
- Validation methods
- Results
- Known limitations
- Integrity controls
- Monitoring indicators
- Current status
- Responsible owner
- Evidence references
- Material changes
- Review date

## 22. Evidence

Evidence should be sufficient to demonstrate that data quality and integrity requirements have been assessed.

Evidence may include:

- Validation results
- Quality metrics
- Reference comparisons
- Integrity checks
- Change logs
- Data-quality reports
- Monitoring records
- Test results
- Incident records
- TEVV findings
- Revalidation results

Evidence should remain traceable to the relevant dataset, system baseline, mission, and authorisation.

## 23. Common Failure Modes

Common failures include:

- Treating dataset size as a measure of quality
- Measuring technical quality without considering mission relevance
- Ignoring stale information
- Accepting missing data without consequence analysis
- Failing to detect systematic errors
- Assuming training data quality represents operational quality
- Failing to protect data from alteration
- Ignoring data poisoning
- Allowing uncontrolled transformations
- Failing to monitor operational degradation
- Hiding uncertainty behind aggregate metrics
- Continuing authorised use after critical data assumptions have failed

## 24. Core Rules

1. **Data quality must be assessed against intended use and mission consequence.**
2. **Material quality requirements must be defined before consequential use.**
3. **Accuracy, completeness, timeliness, relevance, and integrity must be assessed where material.**
4. **Data integrity must be protected throughout the lifecycle.**
5. **Critical quality limitations must be documented and communicated.**
6. **Operational data must be monitored where it materially affects AI behaviour.**
7. **Material quality or integrity changes require impact assessment.**
8. **Failure of critical data conditions may require restriction, suspension, or reauthorisation.**
9. **Quality evidence must remain traceable to the relevant AI capability and authorisation.**
10. **Good model performance does not compensate for unacceptable data quality.**

## 25. Golden Thread

Data Quality and Integrity contributes to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Data Dependencies → Quality & Integrity Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

The objective is to ensure that confidence in AI behaviour is supported by confidence in the quality and integrity of the information on which that behaviour depends.
