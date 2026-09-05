# AI Development

## Summary

AI Development defines the controlled process for creating, adapting, configuring and improving AI components that form part of a defence AI capability.

D-AIGAAF treats development as more than model training. The development lifecycle includes the model, data, software, infrastructure, interfaces, dependencies, security controls, human interaction and configuration required for the capability to operate as intended.

Development must remain connected to:

**Mission Need → Requirements → Risk → Design → Development → TEVV → Evidence → Assurance → Operational Authorisation**

A technically successful model is not, by itself, an operationally authorised defence capability.

---

## 1. Purpose

The AI Development process establishes controls for developing AI components in a manner that supports:

- mission requirements;
- safety;
- security;
- reliability;
- robustness;
- human control;
- autonomy constraints;
- auditability;
- reproducibility;
- traceability;
- TEVV;
- operational assurance.

It applies to:

- new AI models;
- adapted models;
- fine-tuned models;
- machine-learning components;
- AI-enabled software;
- model configurations;
- significant model behaviour changes.

---

## 2. Core Principle

Development should be governed by requirements and evidence rather than by technical capability alone.

The development process should answer:

1. What mission need is being addressed?
2. What requirements must be satisfied?
3. What risks must be controlled?
4. What behaviour is intended?
5. What behaviour is prohibited?
6. What autonomy is technically possible?
7. What autonomy is intended and permitted?
8. What evidence must be generated?
9. How will changes be controlled?
10. How will the resulting capability be assured and authorised?

---

## 3. Development Scope

Development governance should consider the complete AI component and its dependencies.

Depending on the capability, this may include:

- model architecture;
- model weights;
- training algorithms;
- training data;
- validation data;
- test data;
- prompts or system instructions where relevant;
- preprocessing;
- post-processing;
- inference software;
- hardware acceleration;
- APIs;
- external services;
- libraries;
- operating environment;
- monitoring;
- security controls;
- human interfaces;
- autonomy controls.

A model should not be assessed in isolation when integration can materially affect behaviour.

---

## 4. Development Lifecycle

A controlled development lifecycle may include:

**Requirement → Design → Data → Development → Training/Adaptation → Evaluation → Integration → Testing → Configuration Baseline → Assurance**

Development should operate iteratively where appropriate, but each material iteration should remain traceable.

---

## 5. Development Planning

Before development begins, the development team should establish a controlled plan covering:

- objectives;
- applicable requirements;
- intended use;
- prohibited use;
- risk profile;
- autonomy expectations;
- data strategy;
- development methods;
- security controls;
- testing strategy;
- evaluation criteria;
- documentation;
- configuration management;
- change management;
- supplier dependencies;
- evidence generation.

Development planning should identify which decisions require approval before proceeding.

---

## 6. Requirements Traceability

Development activities should remain traceable to the approved requirements baseline.

A useful chain is:

**Requirement → Design Decision → Implementation → Test → Evidence**

Traceability should identify:

- requirement affected;
- design decision;
- implementation component;
- test method;
- evidence;
- responsible owner;
- configuration/version.

This allows later reviewers to determine why a particular design or implementation exists.

---

## 7. AI Design

AI design should consider both intended capability and foreseeable failure.

Design decisions may address:

- model architecture;
- input/output structure;
- decision logic;
- confidence and uncertainty;
- human interaction;
- autonomy boundaries;
- safeguards;
- monitoring;
- fail-safe behaviour;
- recovery;
- security;
- data handling;
- interfaces;
- dependencies.

Design should explicitly consider what happens when the model cannot reliably perform its intended function.

---

## 8. Data for Development

Development data should be governed according to its intended purpose.

Consider:

- provenance;
- quality;
- relevance;
- representativeness;
- completeness;
- timeliness;
- integrity;
- labelling quality;
- bias;
- contamination;
- duplication;
- distribution shift;
- legal and policy constraints;
- security requirements.

Training, validation and test data should be appropriately separated to reduce misleading performance estimates.

---

## 9. Data Provenance

Material development datasets should have sufficient provenance to establish:

- source;
- collection method;
- date or period;
- transformation;
- labelling;
- ownership;
- permitted use;
- version;
- known limitations.

Where provenance is uncertain, the limitation should be documented and considered in risk and assurance.

---

## 10. Model Development

Model development activities may include:

- architecture selection;
- training;
- fine-tuning;
- parameter optimisation;
- retrieval configuration;
- prompt/system-instruction development;
- reinforcement or preference optimisation;
- model compression;
- quantisation;
- adaptation;
- integration of supporting models.

Each material development stage should remain reproducible to the extent practicable.

---

## 11. Development Reproducibility

Development should maintain sufficient records to reproduce or explain material results.

Records may include:

- code version;
- model version;
- training configuration;
- dataset version;
- hyperparameters;
- random seeds where relevant;
- compute environment;
- dependency versions;
- evaluation configuration;
- relevant prompts or instructions;
- changes between iterations.

Perfect reproducibility may not always be technically possible, but material sources of variation should be understood and documented.

---

## 12. Model Behaviour Assessment

Development should evaluate more than aggregate performance.

Consider:

- expected behaviour;
- unexpected behaviour;
- edge cases;
- failure modes;
- uncertainty;
- sensitivity to input changes;
- distribution shift;
- degraded information;
- adversarial inputs;
- conflicting information;
- missing information;
- boundary conditions.

The objective is to understand how the system behaves across relevant conditions, not merely its average benchmark performance.

---

## 13. Uncertainty and Abstention

Where the AI cannot reliably determine an answer or recommendation, development should support appropriate uncertainty behaviour.

Possible mechanisms include:

- confidence indicators;
- uncertainty estimates;
- abstention;
- clarification requests;
- human escalation;
- reduced autonomy;
- safe-state transition.

The system should not be optimised solely for producing an answer if the correct behaviour under uncertainty is to decline, defer or escalate.

---

## 14. Robustness Development

Robustness should be considered during development rather than added only after the model is complete.

Development may examine:

- noisy inputs;
- missing data;
- sensor variation;
- environmental changes;
- unusual inputs;
- adversarial inputs;
- distribution shift;
- degraded communications;
- degraded computing;
- conflicting information.

Robustness claims should ultimately be supported by appropriate testing and evaluation.

---

## 15. Human-AI Interaction Development

Where humans rely on AI outputs, development should consider:

- information presentation;
- uncertainty communication;
- alerting;
- explanation where appropriate;
- cognitive workload;
- automation bias;
- over-reliance;
- decision latency;
- override;
- intervention;
- escalation.

A technically accurate output can still create operational risk if the interface causes users to misunderstand or over-trust it.

---

## 16. Autonomy Development

Development should explicitly identify:

- technically possible autonomy;
- intended autonomy;
- permitted autonomy;
- prohibited autonomy;
- autonomy transitions;
- autonomy constraints;
- recovery behaviour.

The distinction remains:

**Technical Capability ≠ Authorised Autonomy**

Development teams should not assume that because a system can execute an action, that action is permitted operationally.

---

## 17. Safety-by-Design

Safety controls should be incorporated into the development process.

Depending on the capability, this may include:

- constrained outputs;
- action limits;
- permission checks;
- human approval;
- rate limits;
- boundary enforcement;
- fail-safe behaviour;
- degraded modes;
- recovery mechanisms;
- monitoring;
- independent safeguards.

Safety controls should be designed so that failure of one control does not automatically remove all meaningful protection where defence in depth is required.

---

## 18. Security-by-Design

Security should be incorporated throughout development.

Consider:

- model integrity;
- code integrity;
- dependency security;
- access control;
- authentication;
- secrets management;
- interface security;
- data protection;
- update mechanisms;
- logging;
- monitoring;
- vulnerability management;
- supply-chain provenance.

Security controls should be evaluated against both external compromise and unintended system behaviour.

---

## 19. Development Environment

Development environments should be controlled according to the sensitivity and consequence of the capability.

Controls may include:

- access management;
- source-control protection;
- dependency management;
- build integrity;
- environment isolation;
- secure storage;
- audit logging;
- controlled artefact repositories;
- reproducible builds where appropriate.

Development infrastructure should not introduce uncontrolled changes into the operational configuration.

---

## 20. Dependency Management

Development should identify dependencies capable of affecting behaviour.

Dependencies may include:

- libraries;
- frameworks;
- operating systems;
- hardware;
- model APIs;
- external services;
- data sources;
- retrieval systems;
- identity systems;
- cloud or infrastructure services.

Material dependencies should be recorded in the configuration and supply-chain baseline.

---

## 21. Development Testing

Testing should occur throughout development.

It may include:

- unit testing;
- integration testing;
- regression testing;
- performance testing;
- robustness testing;
- security testing;
- adversarial testing;
- human-AI interaction testing;
- autonomy testing;
- failure and recovery testing.

Development testing does not replace formal TEVV.

---

## 22. Evaluation During Development

Development evaluations should progressively determine whether the capability remains aligned with requirements.

Evaluation should consider:

- performance;
- limitations;
- uncertainty;
- failure modes;
- robustness;
- security;
- human control;
- autonomy;
- mission relevance.

Poor evaluation results should trigger development changes, requirement review or risk reassessment as appropriate.

---

## 23. Model and System Boundaries

Development should define clear boundaries around what the AI is responsible for.

Examples include:

- input boundaries;
- output boundaries;
- decision boundaries;
- action boundaries;
- adaptation boundaries;
- temporal boundaries;
- environmental boundaries;
- authority boundaries.

These boundaries should be consistent with the requirements and risk assessment.

---

## 24. Development of Fail-Safe and Recovery

Failure behaviour should be deliberately developed and tested.

The system should have defined responses to conditions such as:

- model failure;
- unexpected output;
- loss of communications;
- sensor degradation;
- information-integrity failure;
- security event;
- loss of human control;
- autonomy boundary violation.

A conceptual response is:

**Detect → Assess → Contain → Reduce Autonomy → Restore Human Control → Safe State/Fail-Safe → Recover**

Emergency protective action may be pre-authorised for narrowly defined conditions where delay could create unacceptable harm.

---

## 25. Development Change Control

Material development changes should be recorded and assessed.

Changes may include:

- model architecture;
- weights;
- training data;
- training method;
- software;
- dependencies;
- prompts or system instructions;
- inference parameters;
- safety controls;
- autonomy controls;
- interfaces.

Change significance should be determined by its potential effect on behaviour, risk, autonomy, human control and assurance.

---

## 26. Version and Configuration Control

Each material development output should have controlled identification.

This may include:

- model identifier;
- model version;
- code version;
- dataset version;
- dependency versions;
- configuration;
- build identifier;
- evaluation version;
- security configuration.

The tested configuration must remain traceable to the configuration proposed for assurance and operational use.

---

## 27. Development Documentation

Development documentation should be sufficient to support later:

- testing;
- evaluation;
- assurance;
- audit;
- troubleshooting;
- incident investigation;
- change assessment;
- revalidation.

Documentation should describe both successful development outcomes and significant known limitations.

---

## 28. Development Evidence

Development evidence may include:

- design records;
- source-control records;
- dataset records;
- training records;
- evaluation results;
- test results;
- security assessments;
- robustness assessments;
- autonomy assessments;
- human-control assessments;
- configuration records;
- change records.

Evidence should identify the configuration and conditions under which it was generated.

---

## 29. Development Exit Criteria

Before a development baseline is released for formal TEVV, the responsible authority should determine that:

- applicable requirements are identified;
- development is sufficiently complete;
- material dependencies are known;
- configuration is controlled;
- significant risks are documented;
- known limitations are documented;
- required development tests are completed;
- evidence is available;
- security controls are in place;
- autonomy boundaries are identified;
- human-control mechanisms are implemented;
- fail-safe and recovery behaviour is defined;
- the configuration is suitable for formal TEVV.

Development completion does not itself imply operational readiness.

---

## 30. Development and Operational Authority

Development organisations should not assume authority to determine operational employment.

The lifecycle separation is:

**Develop → Test → Evaluate → Assure → Accept Risk → Authorise → Employ**

Operational authority remains with the appropriately empowered authority.

---

## 31. Operational AI Advisor

The Operational AI Advisor (OAIA) may contribute during development by helping connect:

- operational requirements;
- AI behaviour;
- risk;
- autonomy;
- human control;
- environmental conditions;
- TEVV needs.

The OAIA should help identify where technical development assumptions may not reflect operational reality.

The OAIA advises.

**The authorised governance or operational authority decides.**

---

## 32. Development Failure Modes

Common failures include:

- developing technology without a clear mission need;
- optimising benchmark performance while ignoring operational performance;
- training on unrepresentative data;
- inadequate data provenance;
- insufficient separation of training and test data;
- ignoring uncertainty;
- ignoring edge cases;
- developing autonomy without defining authority;
- treating safety as a late-stage feature;
- uncontrolled dependencies;
- weak configuration control;
- undocumented model changes;
- insufficient robustness testing;
- assuming human control without testing it;
- failing to preserve development evidence;
- treating development completion as operational readiness.

---

## 33. AI Development Record

A development record should include, as applicable:

| Field | Description |
|---|---|
| Capability ID | Unique capability identifier |
| Development Objective | Intended development outcome |
| Related Mission | Mission need/use case |
| Requirements | Applicable requirements |
| Model | Model identifier/version |
| Data | Dataset identifiers/versions |
| Code | Code/build version |
| Dependencies | Material dependencies |
| Development Method | Training/adaptation method |
| Environment | Development environment |
| Security Controls | Applicable controls |
| Autonomy | Relevant autonomy characteristics |
| Human Control | Relevant human-control mechanisms |
| Tests | Development tests performed |
| Evaluation | Evaluation results |
| Limitations | Known limitations |
| Changes | Material changes |
| Evidence | Evidence references |
| Owner | Responsible authority |
| Status | Lifecycle status |

---

## 34. Core Rules

1. **Development must begin from an approved mission and requirements baseline.**
2. **The complete AI-enabled capability must be considered, not only the model.**
3. **Development must account for foreseeable failure and degraded conditions.**
4. **Data provenance and quality must be controlled.**
5. **Material development activities must remain traceable.**
6. **Actual system behaviour must be assessed rather than inferred from design intent.**
7. **Uncertainty should be explicitly considered during development.**
8. **Safety and security should be designed into the capability.**
9. **Autonomous technical capability does not create operational authority.**
10. **Material changes must be configuration controlled and assessed.**
11. **Development testing does not replace formal TEVV.**
12. **Development completion does not equal operational authorisation.**
13. **Evidence must remain traceable to the configuration that produced it.**
14. **Known limitations must be documented rather than hidden by aggregate performance metrics.**

---

## 35. Golden Thread

AI Development maintains the Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Development converts requirements and risk controls into an implemented capability that can subsequently be tested, assured and authorised.

---

## 36. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 Mission & Use Case** — establishes mission purpose and operational context.
- **03 Risk & Autonomy** — defines risk, autonomy, human control and constraints.
- **04 AI Lifecycle** — establishes lifecycle governance.
- **02 AI Requirements** — provides the development requirements baseline.
- **05 Data & Information** — governs development data.
- **06 AI Security** — establishes security controls.
- **07 Supply Chain & Sovereignty** — governs dependencies and provenance.
- **08 Human Authority** — defines human decision rights.
- **09 TEVV** — independently tests and evaluates the capability.
- **11 Operational Authorisation** — determines whether the capability may be employed.
- **13 Continuous Assurance** — monitors continued performance after deployment.
- **15 Change & Reauthorisation** — governs material changes after baseline.
- **16 Audit & Evidence** — preserves development traceability.

---

## 37. Summary Model

```text
Mission Need
      ↓
Requirements
      ↓
Risk & Autonomy
      ↓
Design
      ↓
Data
      ↓
Development
      ↓
Training / Adaptation
      ↓
Development Testing
      ↓
Integration
      ↓
Configuration Baseline
      ↓
Formal TEVV
      ↓
Evidence
      ↓
Assurance
      ↓
Operational Authorisation
```

AI Development produces an evidence-ready, controlled capability; it does not by itself grant authority for operational employment.
