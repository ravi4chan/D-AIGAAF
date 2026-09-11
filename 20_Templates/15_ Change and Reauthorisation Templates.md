# 15-Change and Reauthorisation Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 15 — Change & Reauthorisation**.

AI capabilities can change without an obvious change to their external interface. Changes to models, data, software, hardware, configuration, suppliers, operating environments, missions, autonomy or human roles can alter risk and assurance.

This module provides mechanisms to ensure that material changes are:

- identified;
- classified;
- assessed;
- controlled;
- tested;
- verified;
- revalidated;
- reauthorised where required;
- implemented under controlled conditions;
- monitored after implementation.

The central principle is:

> **A change is a governance event whenever it could alter the capability's risk, behaviour, security, human control, autonomy, operational environment or assurance basis.**

The core lifecycle is:

**Identify Change → Classify → Assess Impact → Control Configuration → Test / Verify → Revalidate → Reauthorise → Implement → Monitor → Learn**

---

# 2. Template Set

The recommended Change & Reauthorisation template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-15-001 | Change & Reauthorisation Governance Record |
| D-AIGAAF-T-15-002 | AI Change Classification Record |
| D-AIGAAF-T-15-003 | Configuration Baseline Record |
| D-AIGAAF-T-15-004 | Change Risk & Assurance Impact Assessment |
| D-AIGAAF-T-15-005 | Change TEVV & Verification Plan |
| D-AIGAAF-T-15-006 | Revalidation Assessment |
| D-AIGAAF-T-15-007 | Reauthorisation Assessment |
| D-AIGAAF-T-15-008 | Emergency / Temporary Change Record |
| D-AIGAAF-T-15-009 | Change Implementation, Rollback & Monitoring Record |
| D-AIGAAF-T-15-010 | Change Records & Governance Review |

---

# 3. Template 15-001 — Change & Reauthorisation Governance Record

## Purpose

Defines responsibility for controlling changes and determining whether revalidation or reauthorisation is required.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Change owner
- Configuration authority
- Technical authority
- Risk owner
- TEVV authority
- Security authority
- Operational authority
- Assurance authority
- Authorisation authority
- Emergency change authority
- Review date

## Governance Questions

- Who can propose a change?
- Who can approve it?
- Who assesses impact?
- Who determines required TEVV?
- Who decides whether revalidation is necessary?
- Who decides whether reauthorisation is necessary?
- Who can approve emergency changes?
- Who can roll back a change?

---

# 4. Template 15-002 — AI Change Classification Record

## Purpose

Classifies a proposed change according to its potential effect.

## Change Categories

Consider:

- administrative;
- documentation;
- configuration;
- software;
- firmware;
- hardware;
- data;
- model;
- prompts/instructions;
- tools;
- security controls;
- supplier;
- infrastructure;
- mission;
- environment;
- autonomy;
- human role.

## Classification

### Minor

No credible material effect on risk, behaviour, security, human control or authorisation.

### Significant

Potential material effect requiring assessment and proportionate verification.

### Major

Material effect likely to require substantial TEVV, revalidation or reauthorisation.

### Critical

Potential to invalidate the existing assurance or authorisation basis.

## Required Fields

- Change ID
- Change
- Category
- Classification
- Rationale
- Initial risk
- Authority
- Required assessment

---

# 5. Template 15-003 — Configuration Baseline Record

## Purpose

Establishes the approved configuration against which changes are assessed.

## Record

Where applicable:

- model;
- model version/weights identifier;
- software;
- firmware;
- hardware;
- data;
- prompts/instructions;
- tools;
- APIs;
- external services;
- security controls;
- network;
- infrastructure;
- system parameters.

## Required Fields

- Baseline ID
- Component
- Version
- Source
- Integrity evidence
- Approval
- Effective date
- Owner

No material change should be introduced without updating the configuration record.

---

# 6. Template 15-004 — Change Risk & Assurance Impact Assessment

## Purpose

Determines how a proposed change could affect risk and assurance.

## Assess

- mission;
- performance;
- reliability;
- robustness;
- security;
- data;
- autonomy;
- human control;
- environment;
- supply chain;
- workforce;
- legal/policy requirements;
- TEVV evidence;
- operational authorisation.

## Required Fields

- Change
- Impact domain
- Existing state
- Proposed state
- Risk impact
- Assurance impact
- Evidence
- Control
- Residual risk
- Revalidation requirement
- Reauthorisation requirement

---

# 7. Template 15-005 — Change TEVV & Verification Plan

## Purpose

Defines testing required before implementing a material change.

## Test Areas

Consider:

- functional performance;
- regression;
- security;
- adversarial resilience;
- data;
- human-AI interaction;
- autonomy;
- environmental performance;
- integration;
- fail-safe;
- mission effectiveness.

## Required Fields

- Change ID
- Test objective
- Requirement
- Test method
- Configuration
- Environment
- Acceptance criteria
- Evidence
- Responsible authority
- Independence
- Decision threshold

Testing should be proportional to the change and consequence.

---

# 8. Template 15-006 — Revalidation Assessment

## Purpose

Determines whether existing assurance remains valid following a change or other material event.

## Assess

- previous assurance basis;
- change;
- new evidence;
- risk;
- performance;
- security;
- human control;
- autonomy;
- environment;
- dependencies;
- limitations.

## Required Fields

- Capability
- Existing assurance
- Change/event
- Impact
- New evidence
- Remaining uncertainty
- Residual risk
- Revalidation decision
- Conditions
- Authority

Possible decisions:

- existing validation remains valid;
- targeted revalidation;
- partial revalidation;
- full revalidation;
- assurance insufficient.

---

# 9. Template 15-007 — Reauthorisation Assessment

## Purpose

Determines whether operational authorisation must be renewed, amended or withdrawn after a material change.

## Required Fields

- Existing authorisation
- Change
- Mission
- Environment
- Autonomy
- Human authority
- Evidence
- Risk
- Conditions
- Reauthorisation decision
- Authority
- Effective date
- Validity

Possible outcomes:

- continue existing authorisation;
- amend conditions;
- restrict scope;
- reduce autonomy;
- reauthorise;
- suspend;
- withdraw.

---

# 10. Template 15-008 — Emergency / Temporary Change Record

## Purpose

Provides controlled governance for changes required urgently.

## Required Fields

- Change ID
- Emergency justification
- Capability
- Mission
- Change
- Immediate risk
- Evidence available
- Missing evidence
- Compensating controls
- Authority
- Duration
- Monitoring
- Rollback
- Post-change TEVV
- Revalidation
- Reauthorisation

Emergency conditions should not eliminate accountability or create indefinite authority.

---

# 11. Template 15-009 — Change Implementation, Rollback & Monitoring Record

## Purpose

Controls implementation and verifies the outcome after change.

## Required Fields

- Change ID
- Approved configuration
- Implementation time
- Implementing authority
- Verification
- Initial performance
- Security status
- Human-control status
- Autonomy status
- Environmental status
- Rollback trigger
- Rollback procedure
- Monitoring period
- Final status

## Rollback Conditions

Define conditions requiring:

- rollback;
- restriction;
- safe state;
- suspension;
- incident response.

---

# 12. Template 15-010 — Change Records & Governance Review

## Purpose

Provides periodic review of changes and their governance outcomes.

## Review Areas

- change volume;
- change classifications;
- failed changes;
- emergency changes;
- rollback events;
- revalidation;
- reauthorisation;
- incidents;
- configuration integrity;
- supplier changes;
- recurring weaknesses.

## Review Questions

1. Are changes being correctly classified?
2. Are material changes being detected?
3. Are configuration baselines accurate?
4. Is TEVV proportionate?
5. Are revalidation decisions justified?
6. Are reauthorisation triggers being recognised?
7. Are emergency changes controlled?
8. Are rollback mechanisms effective?
9. Have changes caused incidents?
10. Are recurring change patterns indicating architectural or governance weaknesses?

---

# 13. Change Taxonomy

D-AIGAAF recommends considering changes across the entire capability ecosystem.

### Model

- model version;
- weights;
- architecture;
- fine-tuning;
- guardrails.

### Data

- training data;
- validation data;
- operational data;
- retrieval sources;
- data pipelines.

### Software

- application;
- libraries;
- runtime;
- operating system;
- APIs.

### Hardware

- processors;
- sensors;
- storage;
- communications;
- power.

### Instructions and Tools

- system instructions;
- prompts;
- tool permissions;
- agent workflows.

### Environment

- geography;
- mission;
- threat;
- communications;
- electromagnetic conditions.

### Human

- operator;
- supervisor;
- staffing;
- authority;
- training.

### Supply Chain

- supplier;
- cloud;
- external model;
- external service;
- dependency.

---

# 14. Change Impact Is Not Proportional to Code Size

A small change can create a large governance effect.

Examples:

- changing a threshold;
- changing an instruction;
- changing a data source;
- enabling a new tool;
- changing a model endpoint;
- modifying an autonomy constraint.

Conversely, a large technical change may have limited operational impact if appropriately isolated.

Therefore:

> **Change classification should be based on potential consequence and impact, not simply on engineering effort or lines of code.**

---

# 15. Configuration Integrity

A change cannot be reliably governed if the baseline is unknown.

The organisation should be able to answer:

- What model is running?
- What software is running?
- What data is being used?
- What instructions apply?
- What tools are enabled?
- What hardware is present?
- What security controls are active?
- What external services are connected?

Unknown configuration should increase assurance uncertainty.

---

# 16. Change and Risk

The key question is:

> **Could this change alter the probability, consequence or controllability of a harmful outcome?**

Consider changes affecting:

- output quality;
- uncertainty;
- failure modes;
- autonomy;
- human intervention;
- attack surface;
- mission dependence;
- environmental robustness.

If yes, risk assessment should be revisited.

---

# 17. Change and TEVV

TEVV should be selected according to impact.

Possible responses:

**Low impact**
→ verification

**Moderate impact**
→ targeted testing

**High impact**
→ regression + targeted TEVV

**Major impact**
→ comprehensive TEVV

**Critical impact**
→ full reassessment before operational use

These are governance patterns rather than rigid mandatory categories.

---

# 18. Change and Human Control

Changes may affect:

- interface;
- alerts;
- confidence display;
- timing;
- recommendations;
- intervention;
- override;
- workload.

Therefore a technically successful change may still require human-control reassessment.

---

# 19. Change and Autonomy

Changes may unintentionally affect autonomy.

Examples:

- altered agent workflow;
- new tool permission;
- changed instruction;
- modified threshold;
- changed planner;
- new model;
- changed system integration.

A change should therefore be assessed for:

- actual autonomy;
- authorised autonomy;
- transitions;
- boundary adherence;
- intervention.

---

# 20. Change and Security

Security impact should consider:

- attack surface;
- dependencies;
- privileges;
- data access;
- model integrity;
- update mechanisms;
- external connectivity;
- vulnerabilities.

Security changes can create either increased protection or new attack paths.

Both should be assessed.

---

# 21. Change and Operational Environment

A capability can change risk without any software modification.

Examples:

**New Geography**
→ new environmental conditions

**New Adversary**
→ new threat model

**New Mission**
→ new consequence

**New Communications Conditions**
→ new human-control assumptions

**New Operator Population**
→ new human factors

These should be treated as potential changes to the authorised system context.

---

# 22. Change and Supply Chain

Supplier-controlled changes may include:

- model updates;
- API changes;
- cloud infrastructure changes;
- security patches;
- firmware;
- data updates.

Contracts should provide sufficient visibility to determine whether supplier changes trigger D-AIGAAF change governance.

Uncontrolled external updates create assurance uncertainty.

---

# 23. Emergency Changes

Emergency changes may be necessary, but should still establish:

- legitimate authority;
- scope;
- duration;
- risk;
- compensating controls;
- monitoring;
- rollback;
- post-change assessment.

The principle is:

> **Emergency conditions may change the speed of governance, but should not eliminate governance.**

---

# 24. Rollback

Rollback should be considered during change planning.

Define:

- rollback trigger;
- rollback authority;
- rollback configuration;
- rollback procedure;
- expected system state;
- verification;
- post-rollback monitoring.

Rollback should not be assumed to restore the previous assurance state if the change has already altered data, dependencies, security or the operating environment.

---

# 25. Change and Revalidation

Revalidation asks:

> **Does the previous evidence still support the capability after the change?**

Revalidation may be:

- targeted;
- partial;
- comprehensive.

The decision should be evidence-based.

---

# 26. Change and Reauthorisation

Reauthorisation asks:

> **Does the previous operational authority remain justified after the change?**

A capability can be technically revalidated while still requiring a new authorisation decision because:

- autonomy changed;
- mission changed;
- environment changed;
- risk changed;
- human authority changed.

---

# 27. Change Monitoring

Post-change monitoring should verify:

- expected behaviour;
- performance;
- security;
- human control;
- autonomy;
- environmental fit;
- incidents;
- unexpected effects.

Monitoring should be heightened after material changes where appropriate.

---

# 28. Change Records

The change record should allow reconstruction of:

**Previous State**
→ **Change**
→ **Reason**
→ **Impact Assessment**
→ **Testing**
→ **Evidence**
→ **Revalidation**
→ **Reauthorisation**
→ **Implementation**
→ **Outcome**

This supports auditability and future incident investigation.

---

# 29. Anti-Pattern — Patch = No Governance Impact

D-AIGAAF rejects:

> “It was only a patch.”

A patch can affect:

- model behaviour;
- security;
- dependencies;
- interfaces;
- performance;
- autonomy;
- human control.

The relevant question is its potential impact, not its label.

---

# 30. Anti-Pattern — Same Version Number = Same Behaviour

A version identifier alone does not prove behavioural equivalence.

Changes may arise through:

- external APIs;
- model providers;
- data;
- configuration;
- tools;
- infrastructure;
- system prompts;
- runtime dependencies.

Configuration assurance must therefore be broader than a single version number.

---

# 31. Anti-Pattern — Reauthorisation as Automatic Renewal

Reauthorisation should not become:

**Old Authorisation**
→ **Time Passed**
→ **New Date**

Instead:

**Existing Authority**
→ **Current Evidence**
→ **Current Risk**
→ **Current Conditions**
→ **Current Capability**
→ **Decision**

---

# 32. Final Change & Reauthorisation Principle

D-AIGAAF treats change as an integral part of AI governance.

The complete chain is:

**Identify Change**
→ **Classify**
→ **Assess Impact**
→ **Control Configuration**
→ **Test / Verify**
→ **Revalidate**
→ **Reauthorise**
→ **Implement**
→ **Monitor**
→ **Learn**

The governing principle is:

> **No material change to an AI capability, its data, model, software, hardware, configuration, autonomy, mission, environment, human-control arrangements or critical dependencies should be allowed to silently invalidate the evidence, assurance or operational authority on which its use depends.**
