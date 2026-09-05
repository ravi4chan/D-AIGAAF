# Data Representativeness and Drift

## 1. Purpose

This document defines how D-AIGAAF governs data representativeness, distribution shift, and data drift across the AI lifecycle.

The objective is to ensure that data remains sufficiently representative of the conditions for which an AI capability is developed, tested, assured, and operationally authorised.

## 2. Core Principle

> **AI performance demonstrated on historical or development data does not establish continued fitness for an operational environment whose data, conditions, or adversarial characteristics have changed.**

Representativeness is therefore an ongoing assurance concern rather than a one-time dataset property.

## 3. Scope

This document applies to:

- training data;
- validation and test data;
- operational input data;
- sensor data;
- human-generated data;
- synthetic data;
- environmental data;
- reference data;
- derived data;
- data distributions;
- changes in data sources;
- changes in operational conditions;
- adversarial manipulation of data.

## 4. Representativeness

Representativeness should be assessed against the intended mission and operational envelope.

Relevant dimensions may include:

- geography;
- terrain;
- climate and weather;
- season;
- time of day;
- sensor characteristics;
- platform characteristics;
- communication conditions;
- data availability;
- population or object characteristics;
- operational behaviour;
- adversarial conditions;
- degraded conditions;
- unusual or rare events.

Not every dimension will be relevant to every AI capability.

## 5. Operational Design Domain

Each AI capability should identify the operational conditions within which its data assumptions are expected to remain valid.

The relevant operational envelope may include:

**Mission → Environment → Data Sources → Conditions → Constraints → Expected Data Distribution**

Where an AI capability is used outside its assessed operational envelope, additional assurance or explicit authorisation should be required.

## 6. Data Coverage

Data coverage should consider whether the available datasets contain sufficient examples of:

- normal conditions;
- expected variation;
- boundary conditions;
- rare but consequential events;
- degraded conditions;
- adversarial conditions;
- known failure cases.

High aggregate dataset size does not necessarily imply adequate operational coverage.

## 7. Data Gaps

A data gap exists where relevant operational conditions are absent, insufficiently represented, or poorly understood.

Examples include:

- limited representation of unusual environments;
- insufficient examples of degraded sensors;
- limited data from changed equipment;
- sparse representation of rare events;
- insufficient adversarial examples;
- missing data for newly emerging conditions.

Data gaps should be recorded explicitly and considered during risk and assurance assessment.

## 8. Distribution Shift

Distribution shift occurs when the statistical or operational characteristics of input data differ from those represented during development or assurance.

Potential causes include:

- changes in environment;
- changes in sensors;
- changes in platforms;
- changes in operating procedures;
- changes in user behaviour;
- changes in external conditions;
- new adversarial tactics;
- changes in data collection;
- changes in data preprocessing;
- changes in mission context.

Distribution shift may occur without an obvious technical failure.

## 9. Data Drift

Data drift refers to meaningful changes in operational data over time.

D-AIGAAF should distinguish, where useful:

- **Feature Drift** — changes in input characteristics;
- **Label / Outcome Drift** — changes in observed outcomes;
- **Concept Drift** — changes in the relationship between inputs and outcomes;
- **Source Drift** — changes in originating data sources;
- **Context Drift** — changes in the operational circumstances surrounding the data.

These categories may overlap.

## 10. Drift Monitoring

Monitoring should be proportionate to mission consequence and data dependence.

Possible indicators include:

- changes in input distributions;
- missing-data rates;
- sensor characteristics;
- confidence patterns;
- anomaly rates;
- error rates;
- human override rates;
- unexpected output patterns;
- changes in operational outcomes;
- changes in data-source composition.

Monitoring should focus on changes that could affect authorised system behaviour.

## 11. Drift Status

A practical working status model is:

- **Normal** — no material change identified;
- **Watch** — emerging change requires observation;
- **Alert** — potentially material change identified;
- **Restricted** — operational use constrained pending assessment;
- **Suspended** — use temporarily stopped;
- **Revalidation Required** — evidence must be refreshed before continued authorised use.

These are working D-AIGAAF constructs.

## 12. Representativeness and Risk

A working relationship is:

**Data Representativeness Risk = Consequence × Data Dependence × Distribution Uncertainty × Exposure**

Higher risk should result in stronger monitoring, testing, human oversight, operational constraints, or revalidation.

## 13. Out-of-Distribution Conditions

An AI system may encounter inputs materially different from those represented during development or assurance.

The system should, where technically feasible:

- identify potential out-of-distribution conditions;
- communicate relevant uncertainty;
- avoid presenting unsupported confidence;
- invoke defined degraded or fail-safe behaviour;
- escalate to an appropriate human authority where required;
- record the event for later analysis.

An out-of-distribution input should not automatically be interpreted as a system failure; however, consequential use under materially unknown conditions requires appropriate controls.

## 14. Adversarial Data Conditions

Operational data may be deliberately manipulated.

Potential mechanisms include:

- deceptive inputs;
- spoofed or manipulated sensor information;
- poisoned datasets;
- maliciously modified reference data;
- corrupted metadata;
- manipulated labels;
- adversarial examples;
- compromised data sources.

Adversarial resilience should be assessed through the relevant TEVV and AI security processes.

## 15. Data Poisoning

Data poisoning involves deliberate or unauthorised manipulation intended to alter AI behaviour.

Controls should address, as appropriate:

- source authentication;
- access control;
- provenance;
- integrity verification;
- controlled ingestion;
- anomaly detection;
- dataset versioning;
- review of unexpected distribution changes;
- segregation of trusted and untrusted data.

Potential poisoning should trigger incident and assurance processes appropriate to its consequence.

## 16. Rare and High-Consequence Conditions

Rare events may be disproportionately important.

A dataset can be statistically representative overall while remaining inadequate for low-frequency, high-consequence conditions.

Assurance should therefore consider:

**Frequency ≠ Consequence**

Where rare conditions can produce severe outcomes, dedicated testing, simulation, expert review, synthetic data, or operational constraints may be required.

## 17. Environmental Variation

Where relevant, AI capabilities should be assessed across meaningful environmental variation.

Examples include:

- weather;
- visibility;
- terrain;
- lighting;
- temperature;
- altitude;
- electromagnetic conditions;
- communications availability;
- sensor degradation;
- platform variation.

The objective is not to test every conceivable condition, but to demonstrate sufficient robustness across the authorised operational envelope.

## 18. Data and Sensor Changes

Changes to sensors or collection systems can alter AI inputs without changing the AI model itself.

Examples include:

- new sensor hardware;
- changed sensor configuration;
- software updates;
- calibration changes;
- changed resolution;
- changed preprocessing;
- changed data formats;
- changed fusion methods.

Such changes should undergo impact assessment before operational employment where they could materially affect AI behaviour.

## 19. Data Drift and Human Authority

Human decision-makers should understand when AI outputs may be affected by distribution changes or data limitations.

Where significant drift is detected:

1. identify the change;
2. assess operational significance;
3. communicate relevant uncertainty;
4. apply predefined constraints;
5. escalate where required;
6. determine whether continued use remains authorised;
7. initiate revalidation where necessary.

The presence of a human operator does not eliminate the need to govern data drift.

## 20. Drift Response

A general response pathway is:

**Detect → Characterise → Assess Impact → Apply Controls → Decide Continued Use → Revalidate if Required → Reauthorise if Required**

The response should be proportionate to consequence and urgency.

## 21. Data Representativeness Record

Where appropriate, the record should include:

| Field | Description |
|---|---|
| Data Asset ID | Dataset or operational data identifier |
| Intended Use | Authorised purpose |
| Operational Envelope | Conditions represented |
| Coverage | Relevant data dimensions |
| Known Gaps | Important missing conditions |
| Baseline Distribution | Approved reference |
| Monitoring Indicators | Drift measures |
| Drift Thresholds | Defined trigger conditions |
| Current Status | Normal / Watch / Alert / Restricted / Suspended |
| Detected Changes | Material changes observed |
| Impact Assessment | Operational significance |
| Mitigations | Controls applied |
| Revalidation Status | Current assurance position |
| Evidence | Supporting records |

## 22. Assurance Levels

A working five-level representativeness assurance scale may be used:

- **R1 — Limited Representation:** Significant uncertainty about operational coverage.
- **R2 — Basic Representation:** Core expected conditions represented.
- **R3 — Operationally Representative:** Important authorised conditions adequately represented.
- **R4 — Demonstrated Robustness:** Variation, boundary and relevant degraded conditions assessed.
- **R5 — High-Consequence Assurance:** Strong evidence of representativeness and continued monitoring for consequential use.

These are D-AIGAAF working constructs and should be mapped to established organisational terminology before formal adoption.

## 23. Change and Reauthorisation

Material changes in data distribution should be treated as potential changes to the authorised AI capability.

Triggers may include:

- sustained distribution shift;
- significant new data sources;
- major environmental changes;
- new sensors;
- changed mission context;
- emerging adversarial behaviour;
- significant degradation in measured performance;
- previously unknown failure conditions.

Depending on impact:

**Monitor → Assess → Restrict → Revalidate → Reauthorise**

## 24. Common Failure Modes

Common weaknesses include:

- treating a large dataset as automatically representative;
- testing only average conditions;
- ignoring rare high-consequence cases;
- assuming historical data predicts future operational conditions;
- failing to monitor drift after deployment;
- treating sensor changes as unrelated to AI assurance;
- ignoring adversarial manipulation;
- failing to communicate uncertainty;
- continuing authorised use after material distribution change without assessment;
- relying solely on aggregate performance metrics.

## 25. Core Rules

1. Define representativeness against the authorised mission and operational envelope.
2. Identify important data gaps before authorisation.
3. Test meaningful environmental and operational variation.
4. Monitor for material distribution changes after deployment.
5. Treat adversarial data manipulation as an assurance and security concern.
6. Give special attention to rare, high-consequence conditions.
7. Make significant data uncertainty visible to human decision-makers.
8. Assess sensor and data-source changes for AI impact.
9. Restrict or suspend use where drift materially undermines assurance.
10. Revalidate and reauthorise when changes exceed defined thresholds.

## 26. Relationship to Other D-AIGAAF Domains

This document connects directly with:

- **03 Risk & Autonomy** — consequence, uncertainty and control;
- **04 AI Lifecycle** — testing, deployment, monitoring and change;
- **05 Data & Information** — governance, quality, provenance and lifecycle;
- **06 AI Security** — poisoning and adversarial data threats;
- **09 TEVV** — robustness and operational-environment testing;
- **10 Operational Environment** — environmental conditions and boundaries;
- **11 Operational Authorisation** — authorised operational envelope;
- **13 Continuous Assurance** — monitoring and drift detection;
- **14 Incident & Fail-Safe** — response to unsafe or degraded conditions;
- **15 Change & Reauthorisation** — material changes to data and operating conditions.

## 27. Summary

The key question is:

> **Is the data on which the AI capability depends still sufficiently representative of the conditions in which the capability is authorised to operate, and can the organisation detect when that assumption stops being valid?**

If not, the resulting uncertainty must be reflected in risk, assurance, operational constraints, and authorisation decisions.
