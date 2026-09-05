# TEVV Lifecycle

## Summary

TEVV Lifecycle governs the planning, execution, evidence generation and progression of Testing, Evaluation and Validation throughout the defence AI lifecycle.

D-AIGAAF treats TEVV as a progressive evidence process rather than a single final test event.

The core chain is:

**Requirements → TEVV Planning → Test → Verification → Validation → Evaluation → Evidence → Assurance → Operational Authorisation**

---

## 1. Purpose

The TEVV Lifecycle establishes controls to determine whether an AI capability:

- satisfies defined requirements;
- performs reliably;
- remains robust under relevant conditions;
- behaves within defined boundaries;
- supports the intended mission;
- preserves human authority;
- operates within its authorised autonomy;
- maintains safety and security;
- provides sufficient evidence for assurance and operational authorisation.

---

## 2. Core Principle

**TEVV is evidence generation, not a certificate of correctness.**

No single test can establish that an AI capability is safe, secure, reliable or operationally effective under all possible conditions.

TEVV should therefore build evidence progressively and explicitly identify:

- what was tested;
- what was not tested;
- what the evidence demonstrates;
- what assumptions remain;
- what limitations remain;
- what risks remain.

---

## 3. TEVV Scope

TEVV may cover:

- data;
- models;
- software;
- hardware;
- integrated systems;
- human-AI interaction;
- security;
- safety;
- autonomy;
- operational environment;
- mission effectiveness.

The scope should reflect the approved mission and use case.

---

## 4. TEVV Planning

TEVV planning should begin with approved requirements.

Each material requirement should identify an appropriate evidence method, such as:

- test;
- inspection;
- analysis;
- demonstration;
- simulation;
- evaluation;
- operational assessment.

The plan should identify:

- objective;
- method;
- conditions;
- metrics;
- acceptance criteria;
- configuration;
- responsible party;
- evidence requirements.

---

## 5. TEVV Traceability

The Golden Thread for TEVV is:

**Requirement → Test/Evaluation Objective → Method → Configuration → Result → Evidence → Assurance Claim**

This should remain traceable throughout the lifecycle.

---

## 6. Test

Testing establishes whether the system behaves as expected under defined test conditions.

Testing may address:

- functional performance;
- interfaces;
- latency;
- reliability;
- failure handling;
- safety mechanisms;
- security controls;
- autonomy controls.

A successful test does not by itself establish mission effectiveness.

---

## 7. Verification

Verification asks:

**Did we build the system according to the specified requirements?**

Verification may examine:

- implementation;
- interfaces;
- configuration;
- requirements compliance;
- technical specifications;
- safety mechanisms;
- security controls.

Verification should be traceable to the applicable requirement.

---

## 8. Validation

Validation asks:

**Does the capability satisfy its intended operational need?**

Validation should consider:

- mission context;
- intended users;
- operational environment;
- human interaction;
- operational constraints;
- mission outcomes.

Validation should not rely solely on laboratory performance.

---

## 9. Evaluation

Evaluation interprets evidence to determine:

- effectiveness;
- limitations;
- uncertainty;
- residual risk;
- operational relevance;
- suitability for intended use.

Evaluation is broader than pass/fail testing.

---

## 10. TEVV Independence

The degree of independence should increase with:

- consequence;
- mission criticality;
- autonomy;
- uncertainty;
- operational exposure.

For higher-consequence capabilities, independent evaluation should be considered where practicable.

---

## 11. TEVV Configuration Control

Every material TEVV activity should identify the configuration under test.

This may include:

- model version;
- model weights;
- software;
- hardware;
- dataset;
- interfaces;
- parameters;
- dependencies;
- safety controls;
- security controls.

Evidence should not be detached from the configuration that produced it.

---

## 12. Progressive TEVV

D-AIGAAF uses a progressive evidence model:

1. Laboratory
2. Controlled Environment
3. Representative Environment
4. Adversarial / Red-Team
5. Operational Environment
6. Mission-Level Evaluation
7. Operational Authorisation

Progression should be based on evidence and risk rather than calendar milestones alone.

---

## 13. Laboratory Testing

Laboratory testing may establish:

- baseline functionality;
- repeatability;
- initial performance;
- basic failure behaviour;
- interface correctness;
- technical constraints.

Laboratory testing should not be treated as sufficient evidence for operational deployment where the operational environment differs materially.

---

## 14. Controlled Environment Testing

Controlled testing introduces representative but managed conditions.

It may examine:

- environmental variation;
- sensor variation;
- data degradation;
- communications conditions;
- user interaction;
- system integration.

---

## 15. Representative Environment Testing

Testing should increasingly reflect the conditions expected during actual employment.

Relevant variations may include:

- terrain;
- weather;
- lighting;
- sensor characteristics;
- data availability;
- communications;
- operational tempo;
- user behaviour.

The exact conditions should be derived from the mission and operational context.

---

## 16. Adversarial Testing

Where relevant, TEVV should assess deliberate attempts to cause:

- incorrect outputs;
- degraded performance;
- unsafe behaviour;
- loss of control;
- security compromise;
- information manipulation.

Adversarial testing should reflect credible threats and realistic attack surfaces.

---

## 17. Red-Team Assessment

Red-team activities may challenge:

- assumptions;
- operating boundaries;
- safety controls;
- security controls;
- human authority;
- autonomy;
- model robustness;
- system integration.

The objective is to discover credible failure pathways before operational use.

---

## 18. Operational Environment Testing

Before operational authorisation, evidence should establish that the capability has been assessed under relevant operational conditions.

This may include:

- environmental conditions;
- sensor configurations;
- degraded communications;
- data limitations;
- resource constraints;
- human interaction;
- adversarial conditions.

The required scope depends on mission consequence and autonomy.

---

## 19. Mission-Level Evaluation

Mission-level evaluation asks whether the AI-enabled capability contributes to the intended mission outcome.

Assessment may consider:

- mission effectiveness;
- decision quality;
- timeliness;
- workload;
- human understanding;
- false alarms;
- missed events;
- operational consequences.

A model can perform technically well while reducing overall mission effectiveness if integrated or used poorly.

---

## 20. Performance

Performance assessment should use metrics appropriate to the mission.

Potential metrics include:

- accuracy;
- precision;
- recall;
- false-positive rate;
- false-negative rate;
- latency;
- availability;
- reliability;
- calibration;
- uncertainty quality.

Metrics should be interpreted in operational context.

---

## 21. Reliability

Reliability assessment should examine whether performance remains stable over:

- repeated operation;
- changing conditions;
- extended operation;
- system degradation;
- component failure;
- expected operational variation.

Reliability requirements should be proportionate to consequence.

---

## 22. Robustness

Robustness testing should examine behaviour under relevant variation and degradation.

Examples include:

- noisy inputs;
- incomplete data;
- unusual inputs;
- sensor degradation;
- communications degradation;
- environmental variation;
- distribution shift.

---

## 23. Uncertainty Evaluation

Where uncertainty is relevant, TEVV should assess whether the system:

- identifies uncertain cases;
- avoids unjustified confidence;
- abstains where appropriate;
- communicates limitations;
- escalates when required.

A confidence score should not automatically be interpreted as calibrated probability.

---

## 24. Human-AI Evaluation

TEVV should assess how users interact with AI outputs.

Consider:

- comprehension;
- trust;
- over-reliance;
- under-reliance;
- workload;
- override behaviour;
- interpretation of uncertainty;
- response to incorrect recommendations.

Human factors can materially change operational risk.

---

## 25. Human Authority Evaluation

Where human authority is required, testing should establish that:

- authorised personnel can intervene;
- override mechanisms function;
- authority boundaries are clear;
- actions cannot bypass required approval;
- users understand the distinction between recommendation and action.

---

## 26. Autonomy Evaluation

Autonomous functions should be evaluated against the authorised autonomy level.

Assessment may include:

- activation conditions;
- decision boundaries;
- action boundaries;
- supervision;
- intervention;
- transition between autonomy states;
- loss of communication;
- degraded conditions;
- termination.

Autonomy demonstrated during testing should not exceed the authority granted for operational employment without separate approval.

---

## 27. Safety Evaluation

Safety evaluation may examine:

- failure modes;
- safe defaults;
- constraints;
- interlocks;
- fail-safe behaviour;
- degradation;
- recovery;
- emergency shutdown;
- human intervention.

Safety mechanisms should be tested under realistic failure conditions.

---

## 28. Security Evaluation

Security assessment may examine:

- unauthorised access;
- model modification;
- data poisoning;
- malicious inputs;
- interface vulnerabilities;
- compromised dependencies;
- supply-chain risks;
- logging and monitoring.

Security testing should reflect the system's operational exposure.

---

## 29. Information Integrity Evaluation

Where decisions depend on information from multiple sources, TEVV should consider:

- source reliability;
- conflicting information;
- stale information;
- corrupted information;
- missing information;
- manipulated information.

The system should not create unwarranted confidence from unreliable inputs.

---

## 30. Fail-Safe Evaluation

Fail-safe mechanisms should be tested for:

- activation;
- reliability;
- response time;
- safe state;
- containment;
- recovery;
- human authority;
- auditability.

For high-consequence capabilities, fail-safe behaviour should be treated as a testable requirement.

---

## 31. Edge Cases

TEVV should include relevant edge cases, particularly those that are:

- rare;
- difficult to observe;
- difficult to reproduce;
- consequential if mishandled.

Statistical rarity should not automatically justify exclusion where consequences are severe.

---

## 32. Distribution Shift

TEVV should assess the effect of differences between:

**Development Data → Evaluation Data → Operational Data**

Material shifts may require:

- additional testing;
- risk reassessment;
- model adaptation;
- operational restrictions;
- revalidation;
- reauthorisation.

---

## 33. Negative Testing

TEVV should not focus only on expected successful operation.

Negative testing should assess:

- invalid inputs;
- missing inputs;
- contradictory inputs;
- degraded components;
- unavailable dependencies;
- unexpected sequences;
- unsafe requests;
- boundary conditions.

---

## 34. Stress Testing

Stress testing may examine:

- high workload;
- high data volume;
- degraded resources;
- repeated requests;
- latency;
- extended operation;
- component failures.

Stress conditions should reflect credible operational limits.

---

## 35. Simulation

Simulation may support:

- rare-event assessment;
- scenario generation;
- edge-case testing;
- large-scale evaluation;
- controlled comparison.

Simulation results should be assessed for realism and transferability.

Simulation should complement, not automatically replace, representative real-world evaluation.

---

## 36. Test Data Management

TEVV data should be:

- controlled;
- versioned;
- traceable;
- protected from contamination;
- appropriately representative;
- retained according to applicable requirements.

Test data should be linked to the configuration and TEVV activity.

---

## 37. Evidence Quality

Evidence should be:

- relevant;
- sufficient;
- reliable;
- traceable;
- reproducible where practicable;
- configuration-specific;
- appropriately independent.

Evidence volume should not substitute for evidence quality.

---

## 38. Limitations

Every TEVV programme should explicitly identify:

- untested conditions;
- excluded scenarios;
- evidence gaps;
- known limitations;
- uncertainty;
- assumptions.

A TEVV report should distinguish:

**Demonstrated → Partially Demonstrated → Not Demonstrated → Unknown**

---

## 39. Evidence Confidence

Evidence confidence should consider:

- test quality;
- representativeness;
- independence;
- repeatability;
- configuration control;
- coverage;
- data quality;
- uncertainty.

High confidence should require stronger evidence than simple test completion.

---

## 40. TEVV Exit Criteria

Before progression to assurance or operational authorisation, the responsible authority should establish that:

- required TEVV activities are complete to the applicable stage;
- configuration is controlled;
- requirements are traceable;
- material performance is measured;
- relevant failure modes are assessed;
- robustness is evaluated;
- uncertainty is understood;
- human authority is assessed;
- autonomy is assessed where applicable;
- safety and security are evaluated;
- operational environment is represented appropriately;
- evidence gaps are documented;
- residual risks are identified.

---

## 41. TEVV Record

A TEVV Record should include, as applicable:

| Field | Description |
|---|---|
| TEVV ID | Unique activity identifier |
| Capability | AI capability |
| Configuration | Configuration under test |
| Requirement | Related requirement |
| Objective | TEVV objective |
| Method | Test/evaluation method |
| Environment | Test environment |
| Data | Test dataset/version |
| Metrics | Measures used |
| Results | Results obtained |
| Limitations | Evidence limitations |
| Failure Modes | Relevant failures |
| Human Factors | Human-AI findings |
| Autonomy | Autonomy findings |
| Safety | Safety findings |
| Security | Security findings |
| Evidence | Supporting evidence |
| Independence | Independence level |
| Conclusion | Assessment conclusion |
| Status | TEVV status |

---

## 42. TEVV Status

A working status model is:

- Planned
- In Preparation
- In Progress
- Completed
- Partially Demonstrated
- Demonstrated
- Evidence Gap
- Failed
- Requires Reassessment

Status should not be interpreted independently of the underlying evidence.

---

## 43. Core Rules

1. **TEVV must begin with requirements and mission context.**
2. **Testing, verification, validation and evaluation are related but distinct activities.**
3. **TEVV evidence must be linked to the configuration tested.**
4. **Laboratory performance does not establish operational suitability.**
5. **Representative and degraded conditions should be tested where relevant.**
6. **Adversarial assessment should be proportionate to threat and consequence.**
7. **Human-AI interaction and human authority are part of system assurance.**
8. **Autonomy must be evaluated against its authorised boundaries.**
9. **Uncertainty and evidence gaps must be explicitly documented.**
10. **Rare but consequential cases require appropriate attention.**
11. **Simulation should complement rather than automatically replace real-world evidence.**
12. **Evidence quality matters more than evidence volume.**
13. **Material changes may invalidate previously generated evidence.**
14. **TEVV results support assurance and authorisation but do not themselves grant operational authority.**

---

## 44. Golden Thread

TEVV Lifecycle maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 45. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — establishes testable requirements.
- **03 Risk & Autonomy** — determines TEVV depth based on consequence and autonomy.
- **03 AI Development** — generates development evidence.
- **04 AI Acquisition** — establishes supplier evidence and acceptance requirements.
- **05 Data Preparation** — governs TEVV data.
- **06 Model Development** — supports model-level evaluation.
- **07 System Integration** — supports integrated-system testing.
- **08 Configuration Management** — links evidence to configuration.
- **10 Operational Environment** — defines representative conditions.
- **11 Operational Authorisation** — uses TEVV evidence for authorisation.
- **13 Continuous Assurance** — continues evidence generation during employment.
- **15 Change & Reauthorisation** — determines when new TEVV is required.
- **16 Audit & Evidence** — preserves TEVV records.
- **24 Architecture & Technical Controls** — supports technical testing and controls.

---

## 46. Summary Model

```text
Requirements
      ↓
TEVV Planning
      ↓
Laboratory
      ↓
Controlled Environment
      ↓
Representative Environment
      ↓
Adversarial / Red-Team
      ↓
Operational Environment
      ↓
Mission-Level Evaluation
      ↓
Evidence Assessment
      ↓
Assurance
      ↓
Operational Authorisation
      ↓
Operational Monitoring
      ↓
Change / Incident
      ↓
Targeted TEVV
      ↓
Revalidation / Reauthorisation
```

The TEVV Lifecycle converts technical and operational testing into structured evidence that supports assurance and informed operational authority.
