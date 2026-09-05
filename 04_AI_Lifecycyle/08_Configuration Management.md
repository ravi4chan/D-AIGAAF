# Configuration Management

## Summary

Configuration Management governs the identification, control, verification and traceability of the technical and operational configuration of a defence AI capability.

The objective is to ensure that the capability being developed, tested, assured and operationally employed is the capability that was actually approved.

The core chain is:

**Configuration Identification → Baseline → Change Control → Verification → Operational Release → Monitoring → Reconciliation**

---

## 1. Purpose

Configuration Management establishes controls for:

- identifying material system components;
- establishing approved baselines;
- controlling changes;
- detecting configuration drift;
- maintaining version traceability;
- verifying deployed configurations;
- supporting audit, assurance and incident investigation.

---

## 2. Core Principle

**An AI capability cannot be reliably assured if its configuration is unknown or uncontrolled.**

Configuration includes more than the model.

It may include:

- model;
- weights;
- software;
- firmware;
- hardware;
- data;
- interfaces;
- parameters;
- prompts or instructions where behaviourally significant;
- dependencies;
- security controls;
- safety controls;
- infrastructure;
- operating environment assumptions.

---

## 3. Configuration Scope

The configuration baseline should cover material elements that can affect:

- AI behaviour;
- performance;
- safety;
- security;
- autonomy;
- human authority;
- mission effectiveness;
- operational availability.

The scope should be proportionate to consequence and operational criticality.

---

## 4. Configuration Identification

Each material configuration item should have a unique identifier or equivalent traceable reference.

Configuration items may include:

- AI model;
- model version;
- model weights;
- dataset;
- software;
- firmware;
- hardware;
- operating system;
- libraries;
- APIs;
- interfaces;
- configuration parameters;
- security controls;
- safety mechanisms.

---

## 5. Baseline

An approved baseline establishes the known configuration against which the capability is:

- tested;
- evaluated;
- assured;
- authorised;
- monitored.

A baseline should be uniquely identifiable and reproducible to the extent practicable.

---

## 6. AI Configuration Baseline

For an AI-enabled capability, the baseline should identify, where applicable:

- model architecture;
- model version;
- model weights;
- training data version;
- validation/test data;
- software;
- runtime;
- dependencies;
- prompts/instructions;
- system parameters;
- interfaces;
- hardware;
- security configuration;
- safety configuration.

---

## 7. Configuration Relationships

Material configuration items should be linked.

For example:

**System → Software → Model → Data → Dependencies → Configuration Parameters**

This enables reconstruction of what was actually deployed.

---

## 8. Configuration and Assurance

Assurance evidence is meaningful only in relation to the configuration for which it was generated.

Therefore:

**Evidence → Configuration Baseline**

must remain traceable.

Evidence generated against one baseline should not automatically be assumed to apply to another.

---

## 9. Configuration and Operational Authorisation

Operational authorisation should identify the approved configuration or an appropriately bounded configuration range.

The capability should not be considered authorised merely because the system name remains unchanged.

A material configuration change may invalidate part or all of the existing authorisation.

---

## 10. Change Control

Changes should be assessed before implementation.

Change assessment should consider effects on:

- performance;
- reliability;
- robustness;
- uncertainty;
- safety;
- security;
- autonomy;
- human authority;
- mission effectiveness;
- operational environment;
- assurance;
- authorisation.

---

## 11. Change Classification

A working classification is:

### Routine

No expected material effect on approved behaviour or risk.

### Controlled

Potential effect exists but remains within established controls and validated boundaries.

### Material

May affect model behaviour, performance, risk, autonomy, safety, security or operational conditions.

Requires appropriate revalidation and assurance review.

### Critical

May materially change consequential behaviour, autonomy or operational risk.

May require:

- expanded TEVV;
- independent assurance;
- suspension;
- reauthorisation.

---

## 12. AI-Specific Changes

Configuration management should explicitly capture changes such as:

- model retraining;
- fine-tuning;
- model replacement;
- weight changes;
- new datasets;
- changed preprocessing;
- changed prompts;
- changed system instructions;
- changed inference parameters;
- new software libraries;
- changed hardware;
- changed sensors;
- changed interfaces.

A change that appears technically minor may still be behaviourally significant.

---

## 13. Hidden or Opaque Model Changes

For models whose internal behaviour cannot be readily inspected, configuration control becomes especially important.

Changes affecting:

- model weights;
- hidden layers;
- training process;
- safety policies;
- system instructions;
- behaviourally significant dependencies

should not be classified as minor solely because the external interface appears unchanged.

---

## 14. Configuration Verification

Before operational release, the actual configuration should be verified against the approved baseline.

Verification may include:

- version comparison;
- integrity checks;
- dependency verification;
- parameter comparison;
- hardware verification;
- software verification;
- model hash or equivalent integrity mechanism;
- configuration inspection.

---

## 15. Configuration Drift

Configuration drift occurs when the deployed capability differs from its approved baseline without appropriate control.

Potential causes include:

- automatic updates;
- software patches;
- dependency changes;
- hardware replacement;
- model updates;
- configuration changes;
- data pipeline changes;
- infrastructure changes.

Drift should be detected and assessed.

---

## 16. Automatic Updates

Automatic updates should be controlled where they can affect:

- AI behaviour;
- safety;
- security;
- autonomy;
- mission performance;
- operational authorisation.

A system should not silently move from an authorised configuration to an materially different configuration without appropriate governance.

---

## 17. Emergency Changes

Emergency changes may be required to:

- contain a safety issue;
- address a security compromise;
- restore critical functionality;
- prevent unacceptable harm.

Emergency change procedures should establish:

- who may approve the change;
- permitted scope;
- immediate controls;
- recording requirements;
- subsequent testing;
- assurance review;
- revalidation;
- reauthorisation where required.

---

## 18. Rollback

Where feasible, systems should support controlled rollback to a known approved configuration.

Rollback capability should be:

- documented;
- tested;
- access controlled;
- auditable.

Rollback should not automatically be assumed to be safe if dependencies or data have also changed.

---

## 19. Configuration Integrity

Configuration should be protected against:

- unauthorised modification;
- substitution;
- corruption;
- accidental changes;
- unapproved versions.

Integrity controls should be proportionate to consequence.

---

## 20. Configuration Access

Access to material configuration items should be controlled according to:

- role;
- mission need;
- security requirements;
- technical responsibility.

Configuration changes should be attributable to an authorised actor or process.

---

## 21. Configuration Records

Configuration records should identify:

- current baseline;
- previous baseline;
- change;
- reason;
- initiator;
- approver;
- assessment;
- testing;
- evidence;
- effective date;
- resulting status.

---

## 22. Configuration and Supply Chain

Material third-party components should be traceable.

Where applicable, identify:

- supplier;
- component;
- version;
- dependency;
- source;
- update mechanism;
- support status.

This supports supply-chain assurance and sovereignty assessment.

---

## 23. Configuration and Security

Configuration management should support security by identifying:

- exposed interfaces;
- security controls;
- credentials or key-management dependencies;
- software versions;
- vulnerable dependencies;
- monitoring mechanisms.

Security patches should be assessed for behavioural impact where relevant.

---

## 24. Configuration and Safety

Safety-critical configuration should be separately identifiable where appropriate.

Examples may include:

- action constraints;
- interlocks;
- fail-safe mechanisms;
- autonomy limits;
- human approval controls;
- emergency shutdown mechanisms.

Changes to these controls should receive appropriate scrutiny.

---

## 25. Configuration and Autonomy

Autonomy depends on system configuration.

Changes to:

- model;
- decision thresholds;
- action permissions;
- human supervision;
- interfaces;
- control logic

may alter effective autonomy.

Therefore, configuration changes should be assessed against the authorised autonomy level.

---

## 26. Configuration and Human Authority

Changes must not silently alter:

- who may approve an action;
- who may override the AI;
- who may suspend the system;
- who receives AI recommendations;
- which actions can be executed automatically.

Human authority should remain explicitly defined.

---

## 27. Configuration and Environment

A configuration may be authorised only for specified environments.

Environmental assumptions may include:

- communications;
- sensors;
- compute;
- data availability;
- network conditions;
- physical operating conditions.

Changes to the environment that invalidate these assumptions should be treated as configuration or operational changes where appropriate.

---

## 28. Deployment Verification

Before deployment, the responsible authority should verify:

**Approved Baseline = Intended Deployment = Actual Deployment**

Any discrepancy should be resolved or formally accepted through the appropriate authority.

---

## 29. Operational Configuration Monitoring

During employment, monitoring should identify:

- unexpected version changes;
- configuration drift;
- dependency changes;
- system modifications;
- integrity failures;
- unauthorised changes.

Material discrepancies should trigger appropriate response.

---

## 30. Incident Investigation

Configuration records should support reconstruction of:

- what system was used;
- which model was active;
- which software was installed;
- what data/configuration was used;
- which controls were enabled;
- what changed before the incident.

This is essential for accountability and root-cause analysis.

---

## 31. Configuration and Accountability

For consequential AI-supported decisions or actions, configuration management should support the question:

**What exact AI capability was operating when the decision or action occurred?**

This should be linked, where appropriate, to:

- user;
- decision;
- output;
- action;
- outcome.

---

## 32. Configuration Review

Baselines should be periodically reviewed to confirm:

- accuracy;
- completeness;
- continued applicability;
- security;
- dependency status;
- authorisation status.

Review frequency should reflect consequence and rate of change.

---

## 33. Configuration Retirement

When a capability is retired:

- configuration records should be preserved according to applicable requirements;
- access should be withdrawn;
- deployed instances should be identified;
- dependencies should be addressed;
- residual risks should be closed or transferred;
- decommissioning should be verified.

---

## 34. Configuration Management Exit Criteria

A configuration should be considered controlled when:

- material configuration items are identified;
- a baseline is established;
- versions are traceable;
- changes are controlled;
- integrity is protected;
- deployment can be verified;
- drift can be detected;
- evidence is linked to configuration;
- authorisation boundaries are defined;
- records are maintained.

---

## 35. Configuration Management Record

A Configuration Management Record should include, as applicable:

| Field | Description |
|---|---|
| Capability ID | Unique capability identifier |
| Baseline ID | Approved configuration baseline |
| Model | Model/version |
| Data | Relevant dataset version |
| Software | Software versions |
| Hardware | Hardware configuration |
| Dependencies | Material dependencies |
| Interfaces | Material interfaces |
| Parameters | Behaviourally significant parameters |
| Safety | Safety configuration |
| Security | Security configuration |
| Autonomy | Applicable autonomy configuration |
| Human Authority | Authority configuration |
| Change History | Material changes |
| Verification | Baseline verification |
| Evidence | Supporting evidence |
| Authorisation | Related operational authorisation |
| Owner | Responsible authority |
| Status | Current status |

---

## 36. Core Rules

1. **The authorised configuration must be identifiable.**
2. **AI configuration includes more than model weights.**
3. **Material components and dependencies must be traceable.**
4. **Assurance evidence must remain linked to the configuration tested.**
5. **Changes must be assessed for behavioural and operational impact.**
6. **Automatic updates must not bypass appropriate governance.**
7. **Configuration drift must be detectable.**
8. **Material safety, security, autonomy and human-authority changes require increased scrutiny.**
9. **Deployment should be verified against the approved baseline.**
10. **Configuration records must support incident reconstruction.**
11. **Emergency changes must remain subject to retrospective assurance and governance.**
12. **A capability with an unknown configuration should not be treated as fully assured.**
13. **Material configuration changes may require revalidation or reauthorisation.**

---

## 37. Golden Thread

Configuration Management maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 38. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — defines configuration requirements.
- **03 AI Development** — establishes development baselines.
- **04 AI Acquisition** — governs acquired components and dependencies.
- **05 Data Preparation** — controls dataset versions.
- **06 Model Development** — controls model versions and training configuration.
- **07 System Integration** — establishes integrated-system configuration.
- **06 AI Security** — protects configuration integrity.
- **07 Supply Chain & Sovereignty** — governs component provenance.
- **09 TEVV** — links evidence to tested configurations.
- **11 Operational Authorisation** — defines authorised configurations.
- **13 Continuous Assurance** — detects configuration drift.
- **15 Change & Reauthorisation** — governs material changes.
- **16 Audit & Evidence** — preserves configuration records.
- **24 Architecture & Technical Controls** — provides detailed technical configuration controls.

---

## 39. Summary Model

```text
Configuration Identification
          ↓
Configuration Baseline
          ↓
Verification
          ↓
TEVV / Assurance
          ↓
Operational Authorisation
          ↓
Deployment
          ↓
Configuration Monitoring
          ↓
Change Detection
          ↓
Impact Assessment
          ↓
Testing / Revalidation
          ↓
Reauthorisation
          ↓
Updated Baseline
```

Configuration Management ensures that the AI capability being operated remains identifiable, controlled and traceable throughout its lifecycle.
