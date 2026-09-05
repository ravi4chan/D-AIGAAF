# D-AIGAAF — Data Representativeness

## 1. Purpose

This document defines the governance and assurance approach for determining whether data adequately represents the conditions, populations, environments, behaviours and operational situations for which a defence AI capability is intended to be used.

Representativeness is not the same as dataset size or statistical diversity. The question is whether the data provides sufficient coverage of the **relevant operational domain** to support the intended AI behaviour and assurance claims.

---

## 2. Core Principle

> **An AI capability should not be considered adequately assured merely because it performs well on available data; the data must represent the conditions under which the capability is intended to operate.**

A dataset may be accurate and internally consistent while still being poorly representative of the operational environment.

---

## 3. Scope

This document applies to:

- training data
- validation and test data
- operational data
- sensor data
- geospatial data
- intelligence and information datasets
- labelled datasets
- synthetic data
- third-party datasets
- simulation data
- environmental data
- edge-case and rare-event data
- data used for TEVV and operational assurance

---

## 4. Representativeness Objectives

Representativeness assessment should establish whether relevant variation is adequately covered across:

1. mission context
2. operational environment
3. geography
4. time
5. environmental conditions
6. sensor characteristics
7. information quality
8. operating conditions
9. adversarial conditions
10. human interaction
11. relevant classes and events
12. expected and unexpected conditions

Coverage should be assessed against the intended operational domain rather than against arbitrary dataset targets.

---

## 5. Operational Domain

The first step is to define the **Operational Domain of Applicability (ODA)**.

The ODA should describe, where relevant:

- mission
- users
- environment
- geography
- time horizon
- available information
- sensor conditions
- communication conditions
- expected threats
- operational constraints
- human involvement
- authorised autonomy
- known exclusions

The dataset should then be assessed against this domain.

---

## 6. Representativeness Dimensions

| Dimension | Question |
|---|---|
| Geographic | Does data cover relevant geographic conditions? |
| Temporal | Does data cover relevant periods and changes over time? |
| Environmental | Does data reflect relevant environmental conditions? |
| Operational | Does data reflect intended operational situations? |
| Sensor | Does data cover relevant sensor types and characteristics? |
| Information | Does data reflect expected information quality and availability? |
| Class | Are relevant categories sufficiently represented? |
| Behavioural | Are relevant behaviours and interactions represented? |
| Adversarial | Are relevant hostile or deceptive conditions represented? |
| Edge Case | Are important rare or unusual conditions represented? |
| Human | Does data reflect relevant human-AI interaction? |
| Degraded | Does data include realistic degraded conditions? |

Not every dimension will have equal importance for every AI capability.

---

## 7. Mission-Driven Coverage

Representativeness requirements should originate from the mission.

The chain should be:

**Mission → Use Case → Operational Domain → Relevant Conditions → Data Requirements → Coverage Assessment**

A dataset should not be declared representative simply because it is large or diverse in unrelated dimensions.

---

## 8. Geographic Representativeness

Where geography affects AI performance, assessment may consider:

- terrain
- elevation
- climate
- built environment
- vegetation
- infrastructure
- spatial density
- geographic distribution
- relevant boundary conditions

Geographic coverage should reflect the authorised operational domain.

A model trained primarily in one environment may not generalise safely to another.

---

## 9. Temporal Representativeness

Data should account for changes over time.

Relevant factors include:

- seasonal variation
- day/night conditions
- weather cycles
- operational changes
- infrastructure changes
- population or activity changes
- sensor upgrades
- evolving adversarial behaviour
- changes in information sources

Historical data may remain useful while becoming less representative of current conditions.

---

## 10. Environmental Representativeness

Where applicable, data should cover relevant environmental conditions.

Examples include:

- clear and poor visibility
- different lighting conditions
- precipitation
- dust
- smoke
- temperature variation
- atmospheric effects
- terrain variation
- high-altitude conditions
- maritime or water environments
- dense urban environments
- remote or sparse environments

The purpose is not to reproduce every possible condition, but to establish sufficient coverage of conditions that could materially affect mission performance.

---

## 11. Sensor Representativeness

Sensor-dependent AI should account for variation in:

- sensor type
- sensor quality
- resolution
- calibration
- field of view
- noise
- degradation
- positioning
- processing pipelines
- software versions

Testing only with ideal or laboratory-quality sensor inputs may overstate operational performance.

---

## 12. Operational Representativeness

Data should reflect the situations in which the AI capability will actually be used.

Assessment may consider:

- mission tempo
- information availability
- human workload
- decision timelines
- operational constraints
- incomplete information
- concurrent events
- unexpected inputs
- system dependencies

Operational representativeness should be considered in conjunction with operational environment testing.

---

## 13. Class and Event Coverage

Where AI distinguishes between classes, objects, events or conditions, the dataset should contain sufficient examples of relevant categories.

Assessment should identify:

- common classes
- uncommon classes
- rare classes
- ambiguous classes
- classes that are operationally consequential
- classes that may be easily confused

Class frequency alone should not determine importance.

A rare event may require disproportionate attention if its consequences are high.

---

## 14. Edge Cases

Edge cases are conditions that occur infrequently but may materially affect AI behaviour.

Examples may include:

- unusual environmental conditions
- atypical sensor inputs
- ambiguous observations
- unexpected combinations of features
- incomplete information
- unusual human behaviour
- novel operating conditions

Important edge cases should be deliberately sought rather than assumed to be captured by random sampling.

---

## 15. Rare but Consequential Events

Representativeness should account for the difference between:

**Frequency** and **Consequence**.

A low-frequency event can still be a high-priority assurance concern.

The assessment should therefore consider:

**Event Frequency × Consequence × AI Dependence**

This helps identify conditions requiring additional testing, simulation, expert review or controlled data generation.

---

## 16. Adversarial Representativeness

Where an AI capability may operate in an adversarial environment, data should account for relevant attempts to:

- deceive
- manipulate
- obscure
- corrupt
- confuse
- exploit known weaknesses
- create misleading patterns

Adversarial representativeness should be coordinated with:

- AI Security
- TEVV
- Risk & Autonomy
- Operational Environment
- Incident & Fail-Safe

---

## 17. Degraded Conditions

AI systems should not be evaluated only under nominal conditions.

Where operationally relevant, data should include realistic degradation such as:

- missing inputs
- noisy inputs
- stale information
- reduced sensor quality
- intermittent connectivity
- incomplete observations
- conflicting sources
- delayed information

The objective is to determine whether the system remains within authorised behaviour when data quality deteriorates.

---

## 18. Communication-Constrained Conditions

Where AI may operate without continuous connectivity, representativeness should consider:

- disconnected operation
- delayed synchronisation
- intermittent communications
- locally available information
- incomplete updates
- delayed external data

AI behaviour should be evaluated against the information actually available under the authorised operating conditions.

---

## 19. Human-AI Representativeness

For decision-support systems, data and evaluation should reflect realistic human interaction.

Relevant factors may include:

- time pressure
- information overload
- competing recommendations
- uncertainty
- human disagreement
- varying user expertise
- confirmation bias
- automation bias
- rejection of AI recommendations

Where appropriate, the system should be assessed not only on prediction accuracy but also on whether it supports sound human judgement.

---

## 20. Representativeness of Training Data

Training data should be assessed against the intended ODA.

Potential gaps should be identified before development or deployment decisions.

Where material gaps exist, possible responses include:

- collect additional real-world data
- improve sampling
- use controlled synthetic data
- use simulation
- expand environmental coverage
- add edge cases
- restrict intended use
- reduce authorised autonomy
- require additional human oversight

---

## 21. Representativeness of Validation and Test Data

Validation and test data should independently represent the conditions relevant to the assurance claim.

Assessment should consider:

- separation from training data
- geographic coverage
- temporal coverage
- environmental conditions
- operational conditions
- edge cases
- adversarial conditions
- degraded conditions
- human interaction

A model should not be considered robust merely because it performs well on a narrow test set.

---

## 22. Avoiding Distribution Leakage

Representativeness assessment should identify cases where training and test data are too similar.

Potential issues include:

- duplicate observations
- near-duplicate observations
- same-source leakage
- temporal leakage
- geographic leakage
- repeated scenarios
- synthetic variants of training data

Such leakage can create artificially high performance.

---

## 23. Distribution Shift

The operational distribution may differ from the development distribution.

Potential causes include:

- new environments
- new sensors
- changing weather
- new operational patterns
- changing adversarial behaviour
- new information sources
- changes in user behaviour
- infrastructure changes

The system should have mechanisms to detect material distribution changes where feasible.

---

## 24. Representativeness and Generalisation

Good performance on one dataset does not establish generalisation.

Assurance should distinguish:

**Performance on Known Data**

from:

**Performance Across the Authorised Operational Domain**

The second is the more relevant question for operational authorisation.

---

## 25. Representativeness and Uncertainty

Representativeness gaps should increase uncertainty.

Where the system encounters conditions outside validated coverage, it should, where technically feasible:

- reduce confidence
- identify uncertainty
- abstain
- request additional information
- escalate to a human
- restrict functionality

Unknown conditions should not automatically be treated as normal conditions.

---

## 26. Representativeness and Autonomy

Permitted autonomy should reflect confidence in data coverage.

A practical relationship is:

**Lower Representativeness → Higher Uncertainty → Greater Human Oversight → Lower Permitted Autonomy**

This relationship should be explicitly tested and authorised where applicable.

---

## 27. Representativeness and TEVV

TEVV should demonstrate that the evaluation dataset adequately supports the intended assurance claim.

Evidence should include:

- coverage definition
- coverage analysis
- known gaps
- edge-case assessment
- degraded-condition testing
- adversarial testing
- operational environment testing
- performance across relevant conditions
- uncertainty behaviour

Representativeness should be treated as an assurance property, not merely a data-management activity.

---

## 28. Representativeness and Operational Authorisation

Operational authorisation should define the conditions for which evidence supports employment.

Where material representativeness gaps remain, authorisation may:

- restrict mission scope
- restrict environment
- restrict users
- restrict autonomy
- require additional human oversight
- impose monitoring
- require additional testing
- prohibit specific use conditions

The authorised operational envelope should not exceed the validated evidence base without appropriate reassessment.

---

## 29. Representativeness and Change Management

Material changes may invalidate previous representativeness assumptions.

Examples include:

- new geographic area
- new environment
- new sensor
- new mission
- new user group
- new data source
- major model update
- new adversarial conditions
- significant distribution shift

Such changes should trigger a Change Impact Assessment.

---

## 30. Representativeness Assessment Method

A practical assessment can follow:

1. Define the mission.
2. Define the intended use.
3. Define the Operational Domain of Applicability.
4. Identify relevant operating conditions.
5. Identify consequential edge cases.
6. Map available data against those conditions.
7. Identify coverage gaps.
8. Assess the operational significance of each gap.
9. Determine mitigations.
10. Test under representative and degraded conditions.
11. Document evidence and limitations.
12. Establish operational restrictions where required.
13. Monitor for distribution changes after deployment.

---

## 31. Coverage Gap Classification

A working classification may be:

### R0 — No Material Gap

Available evidence adequately covers the relevant domain.

### R1 — Minor Gap

Limited coverage gap with low expected operational consequence.

### R2 — Controlled Gap

Material gap with defined mitigation and monitoring.

### R3 — Significant Gap

Gap may materially affect mission performance or assurance.

### R4 — Critical Gap

Insufficient evidence for the intended consequential use.

R-levels are D-AIGAAF working constructs and should be mapped to applicable organisational and defence requirements before formal adoption.

---

## 32. Representativeness Record

A Representativeness Record should include:

| Field | Description |
|---|---|
| Record ID | Unique identifier |
| AI Capability ID | Capability assessed |
| Mission | Intended mission |
| Use Case | Intended use |
| ODA | Operational Domain of Applicability |
| Dimensions | Dimensions assessed |
| Coverage | Available coverage |
| Gaps | Identified gaps |
| Consequence | Potential impact |
| Mitigation | Controls or restrictions |
| Evidence | Supporting evidence |
| Status | Current assessment |
| Owner | Accountable authority |
| Review Date | Next review |

---

## 33. Evidence Sources

Evidence may include:

- dataset coverage analysis
- geographic sampling
- temporal analysis
- environmental testing
- sensor variation testing
- simulation
- controlled trials
- red-team testing
- operational evaluation
- expert review
- historical comparison
- distribution analysis
- field observations

Evidence should identify both what it demonstrates and what it does not demonstrate.

---

## 34. Common Failure Modes

- Assuming a large dataset is representative.
- Confusing statistical diversity with operational coverage.
- Testing only under ideal conditions.
- Ignoring rare but consequential events.
- Ignoring geographic or environmental differences.
- Using historical data without assessing temporal relevance.
- Training and testing on highly similar data.
- Treating synthetic data as automatically representative.
- Ignoring adversarial conditions.
- Ignoring degraded sensor or communication conditions.
- Expanding an AI capability into a new environment without reassessment.
- Assuming high test accuracy proves operational generalisation.
- Failing to communicate representativeness gaps to human decision makers.

---

## 35. Core Rules

1. **Representativeness must be defined against the intended operational domain.**
2. **Dataset size is not evidence of operational representativeness.**
3. **Relevant geographic, temporal, environmental and operational variation should be assessed.**
4. **Rare but consequential events require explicit consideration.**
5. **Degraded and adversarial conditions should be included where relevant.**
6. **Training, validation and test data should be assessed for meaningful coverage.**
7. **Material representativeness gaps must be visible in assurance and operational risk.**
8. **Unknown or poorly represented conditions should increase uncertainty rather than false confidence.**
9. **Permitted autonomy should reflect confidence in validated data coverage.**
10. **Changes to the operational domain require representativeness reassessment.**
11. **Operational authorisation should not exceed the evidence-supported domain.**
12. **Representativeness evidence must remain connected to the D-AIGAAF Golden Thread.**

---

## 36. Golden Thread

Representativeness contributes to:

**Mission Need → Use Case → Operational Domain → Data Requirements → Coverage → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change → Revalidation → Reauthorisation**

The objective is to establish:

**What conditions the AI is expected to encounter → What conditions the evidence actually covers → What gaps remain → What those gaps mean for risk, uncertainty, human authority and operational employment**

---

## 37. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **02 Mission & Use Case**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Quality**
- **05 Data & Information — Data Provenance**
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

## 38. Summary

Representativeness is the bridge between **data quality** and **operational reality**.

The central chain is:

**Operational Domain → Relevant Conditions → Data Coverage → Coverage Gaps → Testing → Evidence → Risk → Operational Restrictions → Authority**

For consequential defence AI, the governing question is:

> **Does the evidence base adequately represent the environments, conditions, information characteristics and situations in which the AI capability is authorised to operate?**

If not, the gap should be reflected in **uncertainty, assurance, human oversight, autonomy limits, operational restrictions and—where necessary—additional testing, revalidation or reauthorisation**.
