# Model & System Updates

## Summary

Model & System Updates governs changes made to an AI capability after development, deployment or operational employment.

Updates may be routine maintenance, security patches, data changes, model changes, infrastructure changes or modifications to system behaviour. Not every update requires full reauthorisation, but every update should be assessed for its potential effect on performance, risk, autonomy, safety, security and the conditions under which the capability was authorised.

The core principle is:

**A change that can alter AI behaviour, operational risk or authorised conditions must be identified, assessed and controlled before continued operational use.**

The core chain is:

**Proposed Change → Change Classification → Impact Assessment → Testing → Configuration Baseline → Revalidation → Reauthorisation if Required → Deployment → Monitoring**

---

## 1. Purpose

This document establishes controls for:

- identifying AI and system changes;
- assessing change impact;
- distinguishing minor from material changes;
- maintaining configuration integrity;
- determining testing requirements;
- determining when revalidation is required;
- determining when reauthorisation is required;
- preserving operational accountability.

---

## 2. Core Principle

**Technical change and behavioural change are not necessarily the same thing.**

A change that appears small from a software perspective may materially affect:

- model behaviour;
- uncertainty;
- autonomy;
- safety;
- security;
- mission effectiveness;
- human interaction.

Conversely, some maintenance changes may have no material effect on authorised behaviour.

Change classification must therefore be based on **operational impact**, not only engineering effort.

---

## 3. Scope

This process applies to changes involving:

- models;
- model weights;
- training or adaptation;
- software;
- firmware;
- hardware;
- data;
- prompts or system instructions;
- parameters;
- interfaces;
- sensors;
- communications;
- infrastructure;
- dependencies;
- security controls;
- safety controls;
- autonomy;
- operating environment.

---

## 4. Why AI Updates Require Special Governance

AI behaviour can depend on complex interactions between:

- model architecture;
- model weights;
- data;
- prompts;
- system instructions;
- tools;
- dependencies;
- environment;
- user inputs.

Therefore, an update that does not obviously change the external interface may still change system behaviour.

---

## 5. Change Categories

A working D-AIGAAF classification is:

### Class 0 — Administrative

Changes with no expected effect on AI behaviour, security, safety or operational conditions.

Examples:

- documentation formatting;
- non-functional metadata;
- administrative records.

### Class 1 — Minor

Changes with low expected operational impact and no material change to authorised behaviour.

Examples may include:

- non-functional maintenance;
- approved interface presentation changes;
- low-risk performance improvements with demonstrated equivalence.

### Class 2 — Controlled

Changes that could affect system performance or reliability and require targeted testing or review.

Examples:

- software dependency changes;
- infrastructure changes;
- data pipeline changes;
- performance optimisation.

### Class 3 — Material

Changes that may alter model behaviour, operational risk, autonomy, safety, security or mission effectiveness.

Examples:

- model updates;
- model weight changes;
- training changes;
- major data changes;
- autonomy changes;
- new sensors;
- new operational environments.

### Class 4 — Critical

Changes with potential for significant consequences or loss of previously established assurance.

Examples:

- changes affecting consequential autonomy;
- major changes to safety boundaries;
- changes following serious incidents;
- changes that invalidate key assurance assumptions.

Classifications should be adapted to the applicable organisational governance system.

---

## 6. Change Identification

Every change should have a unique record containing, as applicable:

- change identifier;
- capability identifier;
- current configuration;
- proposed configuration;
- change description;
- reason;
- originator;
- supplier;
- affected components;
- proposed deployment date;
- initial classification.

---

## 7. Change Sources

Changes may originate from:

- development teams;
- system owners;
- operators;
- users;
- security teams;
- assurance teams;
- suppliers;
- incidents;
- performance monitoring;
- mission requirements;
- regulatory or policy changes;
- technology refresh.

---

## 8. Change Impact Assessment

Each non-trivial change should assess potential effects on:

- mission;
- requirements;
- performance;
- reliability;
- robustness;
- uncertainty;
- data;
- human-AI interaction;
- human authority;
- autonomy;
- safety;
- security;
- information integrity;
- interoperability;
- operating environment;
- supply chain;
- legal or policy compliance;
- assurance evidence;
- operational authorisation.

---

## 9. Behavioural Impact

The assessment should ask:

- Could outputs change?
- Could confidence change?
- Could failure modes change?
- Could abstention behaviour change?
- Could user interaction change?
- Could autonomy behaviour change?
- Could the operating envelope change?
- Could previously tested assumptions become invalid?

If the answer is potentially yes, additional assurance should be considered.

---

## 10. Hidden Model Changes

Special attention should be given to changes where internal model behaviour is difficult to predict or independently inspect.

For example:

- model weight changes;
- retraining;
- fine-tuning;
- reinforcement learning;
- architecture changes;
- changes to hidden model layers.

Where output behaviour cannot be reliably inferred from the change description, empirical testing should be used to establish impact.

---

## 11. Data Changes

Data changes may include:

- new sources;
- changed distributions;
- new labels;
- changed preprocessing;
- changed augmentation;
- synthetic data;
- altered filtering;
- changed data pipelines.

Data changes should be assessed for effects on performance, bias, robustness, uncertainty and mission suitability.

---

## 12. Software Changes

Software changes should be assessed for their effect on:

- model execution;
- input processing;
- output processing;
- timing;
- safety controls;
- security controls;
- interfaces;
- logging;
- human interaction;
- autonomy.

A software update should not be considered automatically low risk merely because the model itself is unchanged.

---

## 13. Dependency Changes

Third-party dependencies may affect behaviour or security.

Changes should consider:

- libraries;
- frameworks;
- APIs;
- external services;
- operating systems;
- firmware;
- hardware accelerators.

Critical dependencies should remain identifiable.

---

## 14. Security Updates

Security patches should be applied according to security risk while preserving operational assurance.

Emergency security changes may require accelerated procedures.

Where possible, emergency changes should be:

- tested;
- documented;
- configuration-controlled;
- monitored after deployment;
- retrospectively reviewed.

---

## 15. Safety Changes

Changes affecting:

- safeguards;
- interlocks;
- fail-safe;
- action constraints;
- human approval;
- termination mechanisms

should receive heightened scrutiny.

Safety controls should not be weakened through routine update processes without appropriate authority.

---

## 16. Autonomy Changes

Any change that can affect autonomy should be explicitly identified.

Examples include:

- enabling new autonomous functions;
- changing supervision;
- changing action boundaries;
- changing transition logic;
- reducing human intervention;
- changing termination conditions.

Autonomy expansion should require appropriate assurance and operational authority.

---

## 17. Human Authority Changes

Changes affecting who can:

- approve;
- supervise;
- override;
- suspend;
- terminate;
- authorise action

should be treated as governance-relevant changes.

---

## 18. Environmental Changes

A system may require reassessment when an update enables or causes use in:

- a new environment;
- different sensor conditions;
- different communications conditions;
- different data conditions;
- a new mission context.

A new environment can represent a material change even when the model remains unchanged.

---

## 19. Mission Changes

Using an existing capability for a new mission may constitute a material change.

Mission changes should be assessed through:

**Mission → Risk → Requirements → TEVV → Assurance → Authorisation**

rather than being treated solely as a configuration change.

---

## 20. Supplier Updates

Supplier-provided updates should be subject to the same governance principles as internally developed changes.

Contracts and acquisition controls should provide visibility into:

- update content;
- affected components;
- known behavioural changes;
- security implications;
- testing evidence;
- dependencies;
- rollback options.

Supplier assurance does not replace organisational responsibility.

---

## 21. Change Equivalence

Where a change is proposed as non-material, the responsible authority should have evidence supporting that conclusion.

Equivalence may require:

- targeted testing;
- regression testing;
- performance comparison;
- security verification;
- configuration verification.

The burden should be proportionate to consequence.

---

## 22. Regression Testing

Regression testing should assess whether existing validated behaviour remains valid.

Testing may cover:

- known critical scenarios;
- historical failure modes;
- edge cases;
- safety controls;
- security controls;
- human interaction;
- autonomy;
- mission performance.

---

## 23. Revalidation

Revalidation should be considered when a change may invalidate previous evidence.

Potential triggers include:

- model changes;
- material data changes;
- material software changes;
- new operating environments;
- autonomy changes;
- significant performance changes;
- changes to safety controls.

---

## 24. Reauthorisation

Reauthorisation should be required where the change alters the conditions under which the capability was authorised.

Potential triggers include changes to:

- mission;
- environment;
- autonomy;
- human authority;
- operating envelope;
- consequence;
- residual risk;
- material system behaviour.

---

## 25. Change and Operational Authorisation

A valid operational authorisation should identify the configuration or configuration class to which it applies.

The relationship should remain:

**Authorised Configuration ↔ Authorised Capability ↔ Authorised Mission**

A change that breaks this relationship should trigger review.

---

## 26. Emergency Changes

Emergency changes may be necessary where delay creates unacceptable:

- safety risk;
- security risk;
- mission risk;
- system availability risk.

Emergency change procedures should define:

- who can approve;
- what evidence is required;
- permitted scope;
- temporary restrictions;
- monitoring;
- rollback;
- retrospective review.

Emergency procedures should not become a mechanism for avoiding normal governance.

---

## 27. Rollback

Material changes should have a rollback strategy where technically feasible.

Rollback should identify:

- previous approved configuration;
- dependencies;
- data compatibility;
- recovery procedure;
- responsible authority.

Rollback should itself be configuration-controlled.

---

## 28. Parallel Evaluation

Where practical, material updates may be evaluated against the existing approved configuration.

Comparison may consider:

- performance;
- reliability;
- robustness;
- uncertainty;
- safety;
- security;
- human interaction;
- autonomy;
- mission effectiveness.

This supports evidence-based change decisions.

---

## 29. Change Testing Environment

Testing should occur in environments appropriate to the change.

Progression may include:

**Development → Controlled Test → Representative Environment → Operational Environment**

The level of testing should correspond to consequence and change impact.

---

## 30. Change Evidence

The change record should preserve evidence showing:

- what changed;
- why it changed;
- who approved it;
- what was tested;
- what results were obtained;
- what risks changed;
- what assurance changed;
- whether revalidation occurred;
- whether reauthorisation occurred.

---

## 31. Change Approval

Change approval should be separated from change implementation where practical.

A working separation is:

**Propose → Assess → Test → Assure → Approve → Implement → Verify → Monitor**

The independence required should increase with consequence and materiality.

---

## 32. Deployment Verification After Change

After implementation:

**Approved Configuration = Deployed Configuration**

Verification should confirm that:

- intended update was installed;
- no unauthorised changes occurred;
- dependencies are correct;
- safety controls remain active;
- security controls remain active;
- monitoring is operational.

---

## 33. Post-Change Monitoring

Material updates should receive enhanced monitoring after deployment.

Monitoring should assess:

- expected performance;
- unexpected behaviour;
- uncertainty;
- incidents;
- user feedback;
- autonomy;
- safety;
- security.

The monitoring period should be proportionate to change risk.

---

## 34. Change Failure

A change should be considered unsuccessful when:

- expected performance is not achieved;
- new unacceptable failure modes emerge;
- assurance evidence is insufficient;
- safety is degraded;
- security is degraded;
- operational conditions are no longer satisfied.

The response may include restriction, rollback, suspension or reauthorisation.

---

## 35. Change-Induced Incidents

Where an incident follows a change, investigation should examine:

- change content;
- test coverage;
- assumptions;
- configuration;
- dependencies;
- deployment process;
- monitoring;
- human interaction.

The incident should feed back into change governance and assurance.

---

## 36. Continuous Learning

Operational evidence should inform future updates.

Sources may include:

- performance monitoring;
- incidents;
- near misses;
- user feedback;
- environmental changes;
- emerging threats;
- assurance findings.

Changes should therefore form part of a controlled learning cycle rather than an uncontrolled optimisation cycle.

---

## 37. Change Records

A Model & System Change Record should include, as applicable:

| Field | Description |
|---|---|
| Change ID | Unique change identifier |
| Capability ID | AI capability |
| Current Baseline | Existing approved configuration |
| Proposed Baseline | Proposed configuration |
| Change Description | What is changing |
| Reason | Why it is changing |
| Originator | Change initiator |
| Supplier | Relevant supplier |
| Classification | Change class |
| Impact | Impact assessment |
| Risk | Risk assessment |
| Testing | Tests performed |
| Evidence | Supporting evidence |
| Revalidation | Required/completed |
| Reauthorisation | Required/completed |
| Approval | Authorising decision |
| Deployment | Deployment record |
| Rollback | Rollback plan |
| Monitoring | Post-change monitoring |
| Outcome | Result |
| Status | Current status |

---

## 38. Change Status

A working status model is:

### Proposed

Change identified but not yet assessed.

### Under Assessment

Impact and risk being evaluated.

### Under Test

Change undergoing validation or verification.

### Assured

Evidence supports the proposed change.

### Approved

Change authorised for implementation.

### Deployed

Change implemented.

### Under Enhanced Monitoring

Post-change monitoring active.

### Accepted

Change demonstrated acceptable operational behaviour.

### Rejected

Change not approved.

### Rolled Back

Change reversed.

### Suspended

Use of the changed configuration suspended.

---

## 39. Change Review

Periodic review should examine:

- recurring changes;
- failed changes;
- emergency changes;
- supplier changes;
- incidents;
- revalidation rates;
- reauthorisation rates;
- configuration deviations.

Patterns may reveal weaknesses in lifecycle governance.

---

## 40. Change Governance Principles

1. **Every material AI change must be identified and assessed.**
2. **Change classification must consider operational impact, not only technical complexity.**
3. **Hidden model changes require empirical evidence where behaviour cannot be reliably inferred.**
4. **Model, data, software, hardware and dependency changes must be considered together.**
5. **Changes affecting autonomy require explicit assessment.**
6. **Changes affecting human authority require governance review.**
7. **Changes affecting safety or security require heightened scrutiny.**
8. **A new mission or environment may constitute a material change even without a model update.**
9. **Material changes may require revalidation and reauthorisation.**
10. **Emergency changes require defined authority, evidence, monitoring and retrospective review.**
11. **The deployed configuration must be verified after every controlled change.**
12. **Material changes should have rollback or equivalent recovery arrangements where feasible.**
13. **Post-change monitoring is part of change assurance.**
14. **Supplier updates remain subject to organisational governance.**
15. **Operational learning should inform controlled future updates.**

---

## 41. Golden Thread

Model & System Updates maintain the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Authority → Deployment → Employment → Monitoring → Change → Revalidation → Reauthorisation**

---

## 42. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **03 Risk & Autonomy** — assesses risk and autonomy impact.
- **04 AI Lifecycle** — provides lifecycle change controls.
- **06 AI Security** — governs security-related changes.
- **07 Supply Chain & Sovereignty** — governs supplier and dependency changes.
- **08 Human Authority** — assesses changes affecting human control.
- **09 TEVV** — determines testing and evidence requirements.
- **11 Operational Authorisation** — determines whether authority remains valid.
- **12 Operational Employment** — provides operational change context.
- **13 Performance Monitoring** — identifies changes and post-change effects.
- **15 Revalidation** — determines whether previous evidence remains valid.
- **16 Reauthorisation** — governs renewed operational authority.
- **22 Acquisition & Procurement** — governs supplier update obligations.
- **24 Architecture & Technical Controls** — supports technical change implementation.
- **26 Retirement & Decommissioning** — governs removal of obsolete configurations.

---

## 43. Summary Model

```text
Change Identified
        ↓
Change Classification
        ↓
Impact Assessment
        ↓
Risk Assessment
        ↓
Test / Verify / Evaluate
        ↓
Assurance Review
        ↓
Revalidation?
   ↙          ↘
 Yes           No
  ↓             ↓
Revalidate     Approve
  ↓             ↓
Reauthorise?   Implement
  ↓             ↓
Implement      Verify
        ↓
Post-Change Monitoring
        ↓
Accept / Restrict / Roll Back / Suspend
        ↓
Updated Approved Baseline
```

Model & System Updates ensure that AI capabilities do not evolve operationally faster than the governance, assurance and authority needed to trust those changes.
