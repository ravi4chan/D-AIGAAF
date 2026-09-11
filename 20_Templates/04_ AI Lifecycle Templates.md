# 04-AI Lifecycle Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 04 — AI Lifecycle**.

These templates provide structured governance records across the complete lifecycle of a defence AI capability, from identification of the need through development or acquisition, integration, testing, deployment, employment, monitoring, change, revalidation, reauthorisation, retirement and decommissioning.

The central principle is:

> **AI governance is a lifecycle activity. A capability is not governed adequately if controls apply only at development or deployment while material risks can emerge during integration, operation, update or retirement.**

The templates support:

- lifecycle governance;
- requirements;
- development;
- acquisition;
- data and model activities;
- integration;
- configuration;
- TEVV;
- deployment readiness;
- deployment;
- operational employment;
- performance monitoring;
- updates;
- change-impact assessment;
- revalidation;
- reauthorisation;
- retirement;
- decommissioning;
- lifecycle records.

---

# 2. Lifecycle Model

D-AIGAAF uses the following logical lifecycle:

**Need**
→ **Requirements**
→ **Development / Acquisition**
→ **Data / Model**
→ **Integration**
→ **Configuration**
→ **TEVV**
→ **Deployment Readiness**
→ **Deployment**
→ **Employment**
→ **Monitoring**
→ **Updates / Change**
→ **Revalidation**
→ **Reauthorisation**
→ **Retirement**
→ **Decommissioning**

The lifecycle is iterative.

Material findings, incidents, changes or environmental shifts may move a capability backward to an earlier lifecycle stage.

---

# 3. Template Set

The recommended AI Lifecycle template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-04-001 | AI Lifecycle Governance Record |
| D-AIGAAF-T-04-002 | AI Capability Lifecycle Plan |
| D-AIGAAF-T-04-003 | AI Requirements Specification |
| D-AIGAAF-T-04-004 | AI Development Record |
| D-AIGAAF-T-04-005 | AI Acquisition Record |
| D-AIGAAF-T-04-006 | Data and Model Preparation Record |
| D-AIGAAF-T-04-007 | Model Development Record |
| D-AIGAAF-T-04-008 | AI Integration Assessment |
| D-AIGAAF-T-04-009 | Configuration Baseline Record |
| D-AIGAAF-T-04-010 | Lifecycle TEVV Plan |
| D-AIGAAF-T-04-011 | Deployment Readiness Assessment |
| D-AIGAAF-T-04-012 | Deployment Record |
| D-AIGAAF-T-04-013 | Operational Employment Readiness Record |
| D-AIGAAF-T-04-014 | AI Performance Monitoring Record |
| D-AIGAAF-T-04-015 | AI Update Record |
| D-AIGAAF-T-04-016 | Lifecycle Change Impact Assessment |
| D-AIGAAF-T-04-017 | Revalidation Assessment |
| D-AIGAAF-T-04-018 | Reauthorisation Assessment |
| D-AIGAAF-T-04-019 | AI Retirement Assessment |
| D-AIGAAF-T-04-020 | AI Decommissioning Record |
| D-AIGAAF-T-04-021 | AI Lifecycle Record Index |

---

# 4. Template 04-001 — AI Lifecycle Governance Record

## Purpose

Establishes governance responsibility across the AI lifecycle.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Lifecycle stage
- Lifecycle owner
- Technical authority
- Security authority
- Risk owner
- Assurance authority
- Operational authority
- Authorisation authority
- Current status
- Current baseline
- Review date

## Governance Questions

- Who owns the capability?
- Who can approve movement between lifecycle stages?
- Who can stop the lifecycle?
- Who accepts risk?
- Who assures evidence?
- Who authorises operational employment?

---

# 5. Template 04-002 — AI Capability Lifecycle Plan

## Purpose

Defines the planned lifecycle activities, gates and decision points for an AI capability.

## Required Sections

### Capability

- purpose;
- mission;
- use case;
- scope.

### Lifecycle Stages

For each stage record:

- objective;
- entry criteria;
- activities;
- outputs;
- evidence;
- responsible authority;
- exit criteria.

### Lifecycle Gates

Examples:

- requirements approval;
- development approval;
- TEVV entry;
- deployment readiness;
- operational authorisation;
- revalidation;
- retirement.

---

# 6. Template 04-003 — AI Requirements Specification

## Purpose

Defines measurable requirements for the AI capability.

## Requirement Categories

- mission;
- functional;
- performance;
- safety;
- security;
- data;
- human control;
- autonomy;
- environmental;
- interoperability;
- assurance;
- legal/policy;
- operational.

## Required Fields

- Requirement ID
- Requirement
- Rationale
- Source
- Priority
- Acceptance criterion
- Verification method
- Validation method
- Owner
- Status

Requirements should be traceable to mission needs and later to TEVV evidence.

---

# 7. Template 04-004 — AI Development Record

## Purpose

Records governance and technical information relating to AI development.

## Required Fields

- Capability ID
- Development organisation
- Development objective
- Architecture
- Model/system components
- Development environment
- Data used
- Training approach
- Evaluation approach
- Known limitations
- Security controls
- Configuration
- Development findings
- Approvals
- Version

## Development Principles

Development records should make material design decisions traceable.

Where feasible, record:

- significant design alternatives;
- rejected approaches;
- assumptions;
- known failure modes;
- unresolved issues.

---

# 8. Template 04-005 — AI Acquisition Record

## Purpose

Records governance requirements when AI is acquired from an external supplier.

## Required Fields

- Capability
- Supplier
- Contract
- Acquisition route
- Intended use
- Supplier dependencies
- Model provenance
- Data provenance
- Security requirements
- TEVV requirements
- Documentation requirements
- Update arrangements
- Support arrangements
- Intellectual property constraints
- Sovereignty considerations
- Exit arrangements

## Acquisition Principle

Procurement should not transfer governance responsibility away from the organisation.

The acquiring organisation remains responsible for ensuring that the capability is appropriate for its authorised use.

---

# 9. Template 04-006 — Data and Model Preparation Record

## Purpose

Records preparation of data and model inputs used in the AI lifecycle.

## Required Fields

### Data

- source;
- provenance;
- ownership;
- quality;
- representativeness;
- restrictions;
- preprocessing;
- transformation.

### Model

- model source;
- version;
- base model;
- fine-tuning;
- training configuration;
- dependencies;
- known limitations.

### Assurance

- validation;
- integrity checks;
- data-quality findings;
- model-quality findings.

This template should interface with Module 05.

---

# 10. Template 04-007 — Model Development Record

## Purpose

Provides a structured record of material model-development decisions.

## Required Fields

- Model ID
- Model version
- Architecture
- Training objective
- Training data
- Fine-tuning data
- Evaluation data
- Hyperparameter/configuration record
- Known limitations
- Performance results
- Security considerations
- Bias/fairness considerations where applicable
- Robustness results
- Model release decision

## Change Sensitivity

Changes affecting:

- model weights;
- architecture;
- training data;
- prompts/system instructions;
- retrieval;
- tools;
- guardrails;
- inference configuration

should be considered for change-impact assessment.

---

# 11. Template 04-008 — AI Integration Assessment

## Purpose

Assesses the integration of AI into the operational system.

## Integration Areas

- hardware;
- software;
- sensors;
- data feeds;
- communications;
- command-and-control systems;
- human interfaces;
- external systems;
- other AI systems.

## Required Assessment

- integration dependencies;
- failure modes;
- interface risks;
- data-flow changes;
- authority implications;
- security implications;
- human-control implications;
- interoperability;
- degraded-mode behaviour.

A model that performs acceptably in isolation may behave differently after integration.

---

# 12. Template 04-009 — Configuration Baseline Record

## Purpose

Defines the approved configuration of the AI capability.

## Configuration Items

- model;
- model version;
- weights;
- software;
- firmware;
- hardware;
- sensors;
- data sources;
- prompts/system instructions;
- retrieval components;
- tools;
- policies;
- guardrails;
- thresholds;
- interfaces;
- network configuration.

## Required Fields

- Baseline ID
- Configuration item
- Version
- Hash/checksum where appropriate
- Owner
- Approval
- Effective date
- Change history

The baseline should be sufficient to identify what was actually assessed and authorised.

---

# 13. Template 04-010 — Lifecycle TEVV Plan

## Purpose

Defines TEVV activities across the lifecycle.

## Required Sections

- requirements;
- test objectives;
- evaluation objectives;
- verification criteria;
- validation criteria;
- scenarios;
- test environment;
- operational environment;
- degraded conditions;
- adversarial conditions;
- human factors;
- autonomy;
- security;
- mission effectiveness;
- evidence requirements;
- independence requirements.

The plan should be updated when material lifecycle changes occur.

---

# 14. Template 04-011 — Deployment Readiness Assessment

## Purpose

Determines whether a capability is ready to enter deployment.

## Assessment Areas

- mission requirements;
- risk;
- controls;
- security;
- data;
- configuration;
- TEVV;
- operational environment;
- human competence;
- support;
- contingency;
- fail-safe;
- documentation;
- training;
- authorisation prerequisites.

## Decision

- ready;
- ready with conditions;
- not ready.

Readiness does not itself constitute operational authorisation.

---

# 15. Template 04-012 — Deployment Record

## Purpose

Records the actual deployment of the authorised configuration.

## Required Fields

- Deployment ID
- Capability
- Configuration baseline
- Location
- Date/time
- Environment
- Responsible authority
- Deployment team
- Security status
- Verification performed
- Deployment findings
- Exceptions
- Rollback mechanism
- Approval

Deployment records should establish what version was placed into the operational environment.

---

# 16. Template 04-013 — Operational Employment Readiness Record

## Purpose

Confirms that personnel, systems and conditions are ready for actual operational employment.

## Assessment Areas

- authorisation status;
- authorised mission;
- authorised environment;
- autonomy;
- human authority;
- operator competence;
- supervision;
- intervention;
- communications;
- contingency;
- security;
- monitoring;
- support;
- current risk.

## Decision

- ready for employment;
- restricted employment;
- not ready.

---

# 17. Template 04-014 — AI Performance Monitoring Record

## Purpose

Records ongoing AI performance and governance indicators.

## Indicators

Monitor as appropriate:

- accuracy;
- reliability;
- availability;
- false positives;
- false negatives;
- drift;
- uncertainty;
- latency;
- intervention frequency;
- unexpected behaviour;
- security events;
- human-control issues;
- mission effectiveness.

## Required Fields

- Indicator
- Baseline
- Threshold
- Current result
- Trend
- Interpretation
- Action
- Owner
- Review date

Monitoring should consider whether conditions remain within the authorised envelope.

---

# 18. Template 04-015 — AI Update Record

## Purpose

Records updates to an AI capability.

## Update Categories

- model update;
- software update;
- security patch;
- data update;
- prompt/instruction update;
- configuration change;
- tool change;
- hardware update;
- interface change.

## Required Fields

- Update ID
- Change description
- Reason
- Version
- Components affected
- Risk assessment
- TEVV performed
- Evidence
- Approval
- Rollback plan
- Implementation date

Every material update should enter change governance.

---

# 19. Template 04-016 — Lifecycle Change Impact Assessment

## Purpose

Determines whether a proposed lifecycle change affects risk, assurance or authorisation.

## Impact Areas

Assess changes to:

- mission;
- use case;
- model;
- data;
- architecture;
- security;
- autonomy;
- human authority;
- operational environment;
- supplier;
- dependencies;
- interfaces;
- performance;
- legal/policy requirements.

## Decision

- routine change;
- controlled change;
- material change;
- emergency change;
- requires revalidation;
- requires reauthorisation.

---

# 20. Template 04-017 — Revalidation Assessment

## Purpose

Determines whether an AI capability remains valid for its intended mission and operational context after change or material new evidence.

## Required Fields

- Capability
- Current baseline
- Previous validation
- Change/event
- Impact assessment
- Tests repeated
- New evidence
- Operational scenarios
- Limitations
- Residual risk
- Validation conclusion
- Approval

Revalidation should be based on the changed risk and assurance profile, not merely on completion of a checklist.

---

# 21. Template 04-018 — Reauthorisation Assessment

## Purpose

Determines whether operational authority should continue, change, be restricted or be withdrawn.

## Trigger Examples

- material change;
- incident;
- new threat;
- environmental change;
- autonomy increase;
- significant degradation;
- new legal/policy requirement;
- assurance failure.

## Assessment

- current authorisation;
- changed conditions;
- evidence;
- risk;
- assurance;
- human authority;
- proposed conditions;
- proposed autonomy;
- monitoring.

## Decision

- continue;
- modify;
- restrict;
- suspend;
- withdraw.

---

# 22. Template 04-019 — AI Retirement Assessment

## Purpose

Determines whether a capability should be retired.

## Retirement Triggers

- mission completed;
- capability obsolete;
- unacceptable risk;
- replacement;
- support discontinued;
- security vulnerability;
- legal/policy change;
- inability to maintain assurance;
- strategic decision.

## Assessment Areas

- operational impact;
- replacement;
- dependencies;
- data;
- security;
- records;
- contractual obligations;
- residual risk.

---

# 23. Template 04-020 — AI Decommissioning Record

## Purpose

Records final removal of an AI capability from service.

## Required Fields

- Capability
- Final configuration
- Retirement authority
- Decommissioning date
- Systems removed
- Data disposition
- Model disposition
- Credentials/access removed
- Interfaces removed
- Supplier arrangements closed
- Records retained
- Security verification
- Residual dependencies
- Lessons learned
- Final approval

Decommissioning should confirm that the capability cannot continue to operate unintentionally.

---

# 24. Template 04-021 — AI Lifecycle Record Index

## Purpose

Provides a master index of lifecycle records.

## Required Fields

- Capability ID
- Lifecycle stage
- Record type
- Record ID
- Version
- Date
- Owner
- Approval
- Evidence location
- Related risk
- Related control
- Related test
- Related authorisation
- Retention requirement

The index should provide a navigable audit trail across the capability lifecycle.

---

# 25. Lifecycle Gate Model

D-AIGAAF should use lifecycle gates for consequential capabilities.

A practical model is:

### Gate 1 — Need

Is there a justified mission need?

### Gate 2 — Requirements

Are requirements sufficiently defined?

### Gate 3 — Development / Acquisition

Is the proposed solution governed appropriately?

### Gate 4 — TEVV

Is sufficient evidence available?

### Gate 5 — Deployment Readiness

Is the capability ready to enter the operational environment?

### Gate 6 — Operational Authorisation

Has authorised authority permitted operational use?

### Gate 7 — Employment

Are conditions satisfied for actual use?

### Gate 8 — Continuous Assurance

Does evidence remain sufficient?

### Gate 9 — Change / Revalidation

Has a material change been adequately assessed?

### Gate 10 — Retirement

Should the capability continue to exist?

A gate should be treated as a governance decision point, not merely a project-management milestone.

---

# 26. Lifecycle Evidence Chain

The lifecycle records should support:

**Need**
→ **Requirement**
→ **Design**
→ **Implementation**
→ **Configuration**
→ **TEVV**
→ **Evidence**
→ **Assurance**
→ **Readiness**
→ **Authorisation**
→ **Employment**
→ **Monitoring**
→ **Change**
→ **Revalidation**
→ **Reauthorisation**
→ **Retirement**

---

# 27. Lifecycle Baseline

At every material lifecycle stage, the organisation should be able to identify:

- what system existed;
- what model existed;
- what data/configuration was used;
- what environment was assessed;
- what evidence was available;
- what risks were known;
- what authority applied;
- what conditions were imposed.

This creates temporal traceability.

---

# 28. Lifecycle and Configuration Control

A key D-AIGAAF principle is:

> **No material governance decision should depend on an unknown system configuration.**

The organisation should therefore be able to associate:

**Authorisation**
→ **Configuration Baseline**
→ **TEVV Evidence**
→ **Operational Conditions**

If the operational system materially differs from the assessed configuration, the organisation should determine whether revalidation or reauthorisation is required.

---

# 29. Lifecycle and Autonomy

Changes in autonomy require particular scrutiny.

Examples:

- A2 → A3;
- A3 → A4;
- increased action scope;
- reduced human intervention;
- faster autonomous execution;
- expanded operating environment.

Such changes should trigger assessment of:

- risk;
- human authority;
- controls;
- TEVV;
- assurance;
- authorisation.

---

# 30. Lifecycle and Security

Security must persist across the lifecycle.

The organisation should reassess:

- new vulnerabilities;
- model attacks;
- data poisoning;
- supply-chain compromise;
- adversarial inputs;
- model manipulation;
- credential compromise;
- interface exposure;
- newly introduced dependencies.

Security is not a one-time pre-deployment activity.

---

# 31. Lifecycle and Operational Environment

A capability may remain technically unchanged while its operating environment changes.

Examples:

- new adversary;
- different terrain;
- new communications conditions;
- new electromagnetic environment;
- changed mission tempo;
- new sensor;
- changed data distribution.

Such changes may affect the validity of existing assurance.

Therefore:

**Unchanged AI + Changed Environment ≠ Automatically Unchanged Risk**

---

# 32. Lifecycle and Incidents

An incident should be capable of triggering lifecycle reassessment.

The sequence may be:

**Incident**
→ **Protect**
→ **Investigate**
→ **Risk Reassessment**
→ **Corrective Action**
→ **Revalidation**
→ **Reauthorisation**
→ **Return to Employment**

The exact response should depend on consequence and severity.

---

# 33. Lifecycle and Workforce

Lifecycle governance should identify the personnel required at each stage.

Consider:

- developers;
- data specialists;
- security specialists;
- testers/evaluators;
- assurance personnel;
- operators;
- commanders;
- maintainers;
- legal/policy specialists;
- procurement personnel.

No lifecycle stage should depend on unavailable competence.

---

# 34. Minimum Lifecycle Package

For a consequential AI capability, the lifecycle record should normally include:

- lifecycle governance;
- lifecycle plan;
- requirements;
- development/acquisition record;
- data/model records;
- integration assessment;
- configuration baseline;
- TEVV plan and evidence;
- deployment readiness;
- deployment record;
- operational readiness;
- monitoring;
- updates;
- change-impact assessments;
- revalidation;
- reauthorisation;
- retirement;
- decommissioning;
- lifecycle record index.

---

# 35. Lifecycle Review Questions

Before progressing a capability, reviewers should ask:

1. What lifecycle stage is the capability in?
2. What is the current approved configuration?
3. What requirements apply?
4. What risks are known?
5. What evidence exists?
6. What assumptions remain?
7. What has changed since the previous gate?
8. Is the operational environment still within scope?
9. Is human authority still appropriate?
10. Is autonomy unchanged?
11. Are security conditions unchanged?
12. Is the capability still supported?
13. Is revalidation required?
14. Is reauthorisation required?
15. Should the capability continue?

---

# 36. Anti-Pattern — Development-Centric Governance

D-AIGAAF rejects the model:

**Develop**
→ **Test**
→ **Deploy**
→ **Done**

The preferred model is:

**Need**
→ **Requirements**
→ **Development / Acquisition**
→ **TEVV**
→ **Authorisation**
→ **Employment**
→ **Continuous Assurance**
→ **Change**
→ **Revalidation**
→ **Reauthorisation**
→ **Retirement**

---

# 37. Anti-Pattern — “Patch Equals Safe”

A software or model update should not automatically be considered low risk.

A seemingly minor change may affect:

- hidden model behaviour;
- decision thresholds;
- security;
- data distribution;
- human interaction;
- autonomy;
- tool use;
- operational performance.

Change impact must therefore be assessed according to consequence, not merely the apparent size of the code change.

---

# 38. Final AI Lifecycle Principle

The AI lifecycle templates make D-AIGAAF operational across the complete existence of an AI capability.

The governing principle is:

> **An AI capability remains subject to governance for as long as it can create operational consequences—including during development, integration, deployment, employment, update, incident recovery, revalidation and retirement.**

The complete lifecycle chain is:

**Need**
→ **Requirements**
→ **Development / Acquisition**
→ **Data / Model**
→ **Integration**
→ **Configuration**
→ **TEVV**
→ **Deployment Readiness**
→ **Authorisation**
→ **Employment**
→ **Continuous Assurance**
→ **Change / Incident**
→ **Revalidation**
→ **Reauthorisation**
→ **Retirement**
→ **Decommissioning**

This ensures that governance follows the AI capability rather than stopping when the system is deployed.
