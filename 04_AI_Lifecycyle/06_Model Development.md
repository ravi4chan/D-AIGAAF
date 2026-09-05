# Model Development

## Summary

Model Development governs the design, training, adaptation, evaluation and controlled baselining of AI models used within a defence AI capability.

The objective is not merely to produce a model with strong benchmark performance. The model must be developed against defined requirements, understood within its limitations, traceable to its data and configuration, and capable of generating evidence suitable for TEVV, assurance and operational authorisation.

The core chain is:

**Requirements → Model Design → Data → Training/Adaptation → Evaluation → Robustness Assessment → Configuration Baseline → TEVV → Assurance**

---

## 1. Purpose

Model Development establishes controls for:

- model design;
- training;
- fine-tuning and adaptation;
- evaluation;
- robustness;
- uncertainty;
- reproducibility;
- configuration;
- documentation;
- change control;
- evidence generation.

Controls should be proportionate to:

**Consequence + Mission Criticality + Autonomy + Operational Exposure**

---

## 2. Core Principle

A model that performs well in development is not automatically suitable for operational employment.

Model performance must be interpreted in relation to:

- intended use;
- operational environment;
- data;
- uncertainty;
- failure modes;
- human authority;
- autonomy;
- security;
- mission consequences.

---

## 3. Model Development Scope

Model development may include:

- model architecture selection;
- model training;
- fine-tuning;
- transfer learning;
- parameter adaptation;
- prompt or policy configuration where behaviourally significant;
- reinforcement or preference optimisation;
- model compression;
- quantisation;
- pruning;
- ensemble construction;
- post-training modification.

The applicable process should distinguish between:

- model changes;
- system changes;
- data changes;
- configuration changes.

---

## 4. Model Requirements

Model development should trace to approved requirements covering, as applicable:

- intended capability;
- performance;
- reliability;
- robustness;
- uncertainty;
- explainability;
- safety;
- security;
- autonomy;
- human control;
- latency;
- resource constraints;
- operational environment;
- interoperability;
- fail-safe behaviour.

Every material model requirement should have an identified means of verification, validation or evaluation.

---

## 5. Model Design

Model design should consider:

- intended task;
- input characteristics;
- output characteristics;
- operating constraints;
- computational requirements;
- expected failure modes;
- uncertainty;
- human interaction;
- integration dependencies;
- security threats;
- autonomy level.

Design choices that materially affect operational behaviour should be documented.

---

## 6. Model Architecture

Architecture selection should consider more than predictive performance.

Relevant factors may include:

- interpretability;
- reliability;
- robustness;
- computational requirements;
- updateability;
- attack surface;
- data dependency;
- reproducibility;
- monitoring requirements;
- failure containment.

For high-consequence applications, architectural simplicity may sometimes be preferable to marginal performance gains where it materially improves assurance or control.

---

## 7. Training Data

Model development should use controlled datasets whose:

- provenance;
- quality;
- intended use;
- version;
- preparation history;
- limitations

are sufficiently understood.

The model baseline should be traceable to the dataset versions used for material training or adaptation.

---

## 8. Training Process

Training processes should be controlled sufficiently to establish:

- training configuration;
- software environment;
- model version;
- data version;
- hyperparameters where material;
- randomisation or seed controls where relevant;
- compute environment where material;
- training objectives;
- stopping criteria;
- evaluation criteria.

The objective is reproducibility sufficient for the intended assurance level.

---

## 9. Training Reproducibility

Where practical, development should allow an independent party to understand or reproduce the material training process.

Reproducibility should consider:

- source code;
- dependencies;
- configuration;
- data version;
- training procedure;
- model initialisation;
- hardware/software environment.

Where exact reproduction is impractical, the limitation should be documented.

---

## 10. Model Evaluation During Development

Evaluation should occur throughout development rather than only at the end.

It may assess:

- accuracy;
- precision/recall;
- error rates;
- calibration;
- uncertainty;
- robustness;
- resource usage;
- latency;
- failure behaviour.

Evaluation should be aligned with the intended mission rather than relying solely on generic benchmarks.

---

## 11. Benchmark Performance

External or standard benchmarks may provide useful comparative evidence.

However:

**Benchmark Performance ≠ Mission Effectiveness**

Benchmark results should therefore be treated as supporting evidence rather than automatic evidence of operational suitability.

---

## 12. Error Analysis

Development should include structured analysis of model errors.

Analysis may identify:

- false positives;
- false negatives;
- systematic errors;
- environmental weaknesses;
- data-dependent failures;
- rare-event failures;
- uncertainty failures;
- unexpected behaviours.

Errors with significant operational consequences should receive increased scrutiny.

---

## 13. Robustness

Models should be assessed against relevant variation in:

- inputs;
- sensors;
- environments;
- operating conditions;
- data quality;
- degraded information;
- unexpected inputs.

Robustness requirements should be derived from the intended operational environment.

---

## 14. Adversarial Robustness

Where relevant, development should consider whether model behaviour can be manipulated through:

- crafted inputs;
- misleading information;
- data corruption;
- adversarial examples;
- poisoned data;
- prompt or instruction manipulation;
- malicious system interactions.

Adversarial testing should be proportionate to the threat and consequence.

---

## 15. Uncertainty

Models should provide meaningful uncertainty information where the use case requires it.

Uncertainty may be expressed through:

- confidence estimates;
- probability distributions;
- abstention;
- uncertainty bands;
- explicit "insufficient information" states;
- escalation to human review.

The system should not represent uncertain outputs as certain conclusions.

---

## 16. Abstention

Where appropriate, the model should be capable of declining to provide an answer or action when:

- input quality is insufficient;
- the situation is outside the validated operating domain;
- confidence is inadequate;
- required information is missing;
- conflicting evidence is detected;
- system integrity is uncertain.

Abstention should be treated as a designed capability rather than necessarily as a model failure.

---

## 17. Hallucination and Confabulation

For generative or reasoning systems, development should assess the risk of:

- fabricated facts;
- unsupported claims;
- invented sources;
- false confidence;
- inconsistent reasoning;
- inappropriate completion;
- misleading recommendations.

Where such systems support consequential decisions, controls should ensure that generated content is not treated as verified fact merely because it is fluent or confident.

---

## 18. Human-AI Interaction

Model development should consider how users:

- interpret outputs;
- perceive confidence;
- understand limitations;
- challenge recommendations;
- override outputs;
- respond to errors.

Interface design can materially affect operational risk even when the underlying model is unchanged.

---

## 19. Human Authority

The model should not implicitly acquire authority merely because it produces an output.

Unless separately authorised:

**AI remains advisory or decision-support.**

Where the model can initiate or execute consequential actions, the authorised autonomy level and human control mechanism must be explicitly defined and assessed.

---

## 20. Autonomy

Model development should support the authorised autonomy level.

The working D-AIGAAF construct is:

- **A0** — No Meaningful AI Decision
- **A1** — Information / Observation
- **A2** — Analysis / Recommendation
- **A3** — Human-Authorised Action
- **A4** — Supervised Autonomous Action
- **A5** — Independent Consequential Autonomy

These levels are a D-AIGAAF working construct and should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

---

## 21. Safety by Design

Where model failure can create consequential harm, development should consider:

- safe defaults;
- bounded outputs;
- action constraints;
- fail-safe states;
- degraded modes;
- recovery;
- human intervention;
- shutdown or isolation mechanisms.

Safety mechanisms should be tested rather than assumed to work.

---

## 22. Security by Design

Model development should consider:

- unauthorised model modification;
- malicious dependencies;
- compromised development environments;
- model extraction;
- model poisoning;
- unauthorised access;
- insecure interfaces;
- supply-chain compromise.

Security controls should extend across the development environment and model artefacts.

---

## 23. Model Integrity

Material model artefacts should be protected against:

- unauthorised modification;
- substitution;
- corruption;
- unapproved versions;
- configuration drift.

Where practicable, integrity mechanisms should allow the deployed model to be compared with the authorised baseline.

---

## 24. Model Explainability

The required degree of explainability should reflect the use case.

Potential evidence may include:

- feature importance;
- attribution;
- rationale or supporting evidence;
- decision traces;
- retrieved information;
- rule execution;
- confidence or uncertainty;
- known limitations.

For opaque models, the framework should not imply that an explanation is necessarily a faithful representation of internal reasoning.

---

## 25. Model Boundaries

Development should document what the model is intended to do and what it is not intended to do.

Boundaries may include:

- input domain;
- output domain;
- operating environment;
- mission;
- autonomy;
- data dependencies;
- geographic or temporal scope;
- known unsupported cases.

Boundary definition supports later operational authorisation.

---

## 26. Failure Modes

Model development should identify foreseeable failure modes.

Examples include:

- incorrect classification;
- missed detection;
- overconfidence;
- unstable outputs;
- unexpected generalisation;
- degraded performance;
- unsafe recommendations;
- inappropriate action;
- loss of uncertainty information;
- failure under distribution shift.

Failure modes should be linked to:

**Risk → Control → Test → Evidence → Authorisation Condition**

---

## 27. Model Stress Testing

Stress testing may examine:

- degraded inputs;
- noisy inputs;
- incomplete inputs;
- unusual inputs;
- conflicting information;
- resource constraints;
- latency;
- repeated queries;
- operational edge cases.

Stress testing should reflect realistic failure pathways.

---

## 28. Model Evaluation Across Environments

Where operationally relevant, models should be evaluated across representative variations such as:

- terrain;
- weather;
- lighting;
- sensor configuration;
- communications availability;
- data quality;
- operational tempo;
- adversarial conditions.

The precise environments should be derived from the approved mission and operational context.

---

## 29. Model and System Interaction

A model cannot always be evaluated independently of the system in which it operates.

Material interactions may exist between:

- model;
- software;
- sensors;
- data pipelines;
- communications;
- user interfaces;
- downstream systems;
- human operators.

System-level evaluation should therefore complement model-level evaluation.

---

## 30. Model Change

Model changes may include:

- new training data;
- new architecture;
- retraining;
- fine-tuning;
- parameter changes;
- quantisation;
- pruning;
- optimisation;
- safety-policy changes;
- prompt or instruction changes where behaviourally significant.

Each change should be assessed for behavioural impact.

---

## 31. Change Classification

A working classification is:

### Routine Change

No expected material effect on:

- behaviour;
- risk;
- autonomy;
- operational envelope.

May proceed through established change controls.

### Controlled Change

Potentially affects performance or configuration but remains within the validated envelope.

Requires targeted assessment.

### Material Change

May affect:

- model behaviour;
- risk;
- uncertainty;
- autonomy;
- mission effectiveness;
- operational environment.

Requires appropriate revalidation and assurance review.

### Critical Change

May materially alter consequential behaviour, autonomy or operational risk.

May require:

- expanded TEVV;
- independent assurance;
- reauthorisation;
- suspension until evidence is established.

---

## 32. Model Baseline

A controlled model baseline should identify, where applicable:

- model version;
- architecture;
- weights;
- training data;
- training configuration;
- software dependencies;
- runtime;
- interfaces;
- safety controls;
- security controls;
- evaluation results.

The baseline should be linked to the applicable assurance and authorisation records.

---

## 33. Model Documentation

Documentation should describe:

- intended purpose;
- architecture;
- training approach;
- data dependencies;
- performance;
- limitations;
- uncertainty;
- failure modes;
- operating boundaries;
- security considerations;
- autonomy;
- change history.

Documentation should be understandable to both technical assurance personnel and relevant operational decision-makers.

---

## 34. Independent Review

For higher-consequence capabilities, model development should be subject to review independent of the development team where practicable.

Review may examine:

- requirements;
- methods;
- data;
- evaluation;
- failure modes;
- evidence;
- assumptions;
- limitations;
- change history.

Independence should increase with consequence and autonomy.

---

## 35. Model Development Exit Criteria

Before a model proceeds to formal TEVV or operational readiness assessment, the responsible authority should establish that:

- requirements are traceable;
- model configuration is controlled;
- training data is identified;
- material development steps are documented;
- performance is evaluated;
- failure modes are assessed;
- uncertainty is considered;
- robustness is assessed where relevant;
- security controls are addressed;
- model boundaries are documented;
- dependencies are known;
- evidence is retained;
- material limitations are disclosed.

---

## 36. Model Development Record

A Model Development Record should include, as applicable:

| Field | Description |
|---|---|
| Model ID | Unique model identifier |
| Model Version | Controlled version |
| Purpose | Intended purpose |
| Mission | Related mission/use case |
| Architecture | Model architecture |
| Data Version | Training/development data |
| Training Method | Development method |
| Configuration | Material configuration |
| Performance | Development results |
| Robustness | Robustness results |
| Uncertainty | Uncertainty behaviour |
| Failure Modes | Known failure modes |
| Security | Security assessment |
| Autonomy | Applicable autonomy level |
| Boundaries | Intended operating boundaries |
| Dependencies | Material dependencies |
| Evidence | Supporting evidence |
| Change History | Material changes |
| Owner | Responsible authority |
| Status | Lifecycle status |

---

## 37. Core Rules

1. **Model development must trace to approved requirements.**
2. **Benchmark performance does not establish operational effectiveness.**
3. **Model behaviour must be evaluated under relevant operational conditions.**
4. **Material training configurations and model versions must be controlled.**
5. **Data-to-model traceability must be maintained.**
6. **Failure modes must be identified and assessed.**
7. **Uncertainty must not be hidden behind confident outputs.**
8. **Abstention should be available where appropriate.**
9. **Security and safety should be addressed during development, not added only after deployment.**
10. **Model changes must be assessed for behavioural impact.**
11. **Higher-consequence and higher-autonomy systems require stronger independent scrutiny.**
12. **A model does not acquire operational authority merely by producing a recommendation or action.**
13. **The authorised model baseline must remain identifiable throughout operational employment.**
14. **Model evidence must remain linked to the model version for which it was generated.**

---

## 38. Golden Thread

Model Development maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 39. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — defines model requirements.
- **03 AI Development** — provides broader development governance.
- **05 Data & Information** — governs data dependencies.
- **06 AI Security** — addresses model and development security.
- **07 Supply Chain & Sovereignty** — addresses model provenance and dependencies.
- **08 Human Authority** — governs human control and decision authority.
- **09 TEVV** — provides formal testing, evaluation and validation.
- **10 Operational Environment** — defines environmental conditions.
- **11 Operational Authorisation** — determines whether and under what conditions the model may be employed.
- **13 Continuous Assurance** — monitors operational behaviour.
- **15 Change & Reauthorisation** — governs material model changes.
- **16 Audit & Evidence** — preserves development evidence.

---

## 40. Summary Model

```text
Requirements
      ↓
Model Design
      ↓
Controlled Data
      ↓
Training / Adaptation
      ↓
Development Evaluation
      ↓
Error & Failure Analysis
      ↓
Robustness / Uncertainty Assessment
      ↓
Security & Safety Review
      ↓
Controlled Model Baseline
      ↓
TEVV
      ↓
Assurance
      ↓
Operational Authorisation
      ↓
Operational Monitoring
      ↓
Model Change
      ↓
Revalidation / Reauthorisation
```

Model Development converts requirements and controlled data into a traceable AI model baseline whose performance, limitations, risks and behavioural boundaries can be assessed before operational employment.
