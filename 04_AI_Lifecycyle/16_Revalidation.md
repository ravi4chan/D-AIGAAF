# Revalidation

## Summary

Revalidation determines whether an AI capability continues to satisfy the evidence, requirements, risk controls and operational conditions established for its authorised use after a material change or significant operational event.

Revalidation is not simply repeating the original tests. It is a focused determination of whether the existing assurance case remains valid for the capability as it now exists.

The core principle is:

**When material change or new evidence creates doubt about the validity of previous assurance, the capability must be revalidated before continued use at the affected level of consequence or autonomy.**

The core chain is:

**Trigger → Scope Assessment → Evidence Review → Targeted / Full TEVV → Assurance Decision → Reauthorisation Decision → Updated Baseline**

---

## 1. Purpose

Revalidation establishes controls to:

- determine whether previous assurance remains applicable;
- identify evidence invalidated by change or new conditions;
- conduct appropriate additional testing;
- reassess risk and autonomy;
- confirm continued operational suitability;
- support a decision on continued authorisation.

---

## 2. Core Principle

**Previous validation belongs to a specific capability, configuration, mission and operating context.**

A capability should not be assumed to remain validated when any material part of that relationship changes.

The relevant relationship is:

**Capability × Configuration × Mission × Environment × Autonomy × Human Authority**

---

## 3. Scope

Revalidation may be triggered by:

- model changes;
- model weight changes;
- retraining;
- fine-tuning;
- significant data changes;
- software changes;
- hardware changes;
- dependency changes;
- sensor changes;
- communications changes;
- autonomy changes;
- new missions;
- new environments;
- significant incidents;
- material performance degradation;
- emerging threats;
- changed assumptions;
- changes in legal or policy requirements.

---

## 4. Revalidation vs Reauthorisation

These functions are related but distinct.

### Revalidation

Determines whether the capability continues to satisfy applicable requirements and whether existing evidence remains valid.

### Reauthorisation

Determines whether the capability is permitted to operate under defined conditions.

A capability may require:

- revalidation without reauthorisation;
- both revalidation and reauthorisation;
- neither, where a documented assessment establishes that existing evidence remains valid.

---

## 5. Revalidation Triggers

A revalidation assessment should be initiated when:

- a material change occurs;
- a new operational environment is introduced;
- mission purpose changes;
- autonomy changes;
- human authority changes;
- performance materially degrades;
- a significant incident occurs;
- a major security or safety issue is identified;
- assumptions underlying assurance become invalid;
- new evidence indicates a previously unknown failure mode.

---

## 6. Trigger Assessment

Not every event requires full revalidation.

The initial assessment should determine:

- what changed;
- what evidence may be affected;
- whether risk changed;
- whether the operating envelope changed;
- whether previous validation remains applicable.

The result should be documented.

---

## 7. Revalidation Scope

Revalidation should be proportionate to the affected assurance.

Possible scope:

### Targeted Revalidation

Focused on specific changed components, requirements or failure modes.

### Partial Revalidation

Covers multiple affected assurance domains.

### Full Revalidation

Reassesses the capability across the major assurance dimensions.

---

## 8. Evidence Review

Existing evidence should be reviewed for continued applicability.

Consider:

- configuration;
- test environment;
- data;
- model;
- system integration;
- operating environment;
- mission;
- autonomy;
- human authority;
- safety;
- security.

Evidence should be explicitly linked to the current capability.

---

## 9. Evidence Validity

Previous evidence may become invalid or less persuasive when:

- configuration changes;
- operating conditions change;
- data distributions change;
- mission changes;
- autonomy increases;
- failure modes change;
- assumptions are no longer true.

Evidence should not be discarded automatically, but its applicability must be justified.

---

## 10. Requirements Review

Revalidation should confirm that the current capability still satisfies applicable requirements.

Review may cover:

- functional requirements;
- performance requirements;
- robustness;
- safety;
- security;
- human authority;
- autonomy;
- interoperability;
- environmental requirements;
- auditability.

Changed requirements may require a new assurance baseline.

---

## 11. Risk Reassessment

Revalidation should reassess risk where the change or event may affect:

- consequence;
- likelihood;
- mission criticality;
- exposure;
- autonomy;
- human control;
- uncertainty.

The updated risk should be compared with the risk accepted under the existing authorisation.

---

## 12. Autonomy Reassessment

Where autonomy changes or behaviour may have changed, reassess:

- actual autonomy;
- authorised autonomy;
- autonomy transitions;
- action boundaries;
- supervision;
- intervention;
- termination;
- fail-safe.

Higher autonomy should generally require stronger evidence.

---

## 13. Human Authority Reassessment

Confirm that:

- human roles remain clear;
- decision authority remains appropriate;
- override remains available where required;
- suspension authority remains effective;
- users understand changed behaviour.

Changes to human authority should receive explicit review.

---

## 14. Performance Revalidation

Revalidation may include:

- benchmark comparison;
- regression testing;
- operational scenario testing;
- robustness testing;
- uncertainty testing;
- edge-case testing;
- stress testing.

Testing should focus on areas affected by the change while retaining sufficient coverage of critical existing behaviour.

---

## 15. Operational Environment Revalidation

Where environment changes, evidence should establish suitability for the new conditions.

Relevant factors may include:

- terrain;
- weather;
- sensor characteristics;
- communications;
- data availability;
- infrastructure;
- adversarial conditions.

Performance in one environment should not automatically be treated as evidence for another.

---

## 16. Data Revalidation

Data-dependent systems should assess:

- source changes;
- distribution changes;
- data quality;
- provenance;
- preprocessing;
- labels;
- leakage;
- adversarial manipulation.

Operational data should remain appropriate to the validated use.

---

## 17. Model Revalidation

Model-related revalidation may assess:

- architecture;
- weights;
- training;
- fine-tuning;
- inference;
- prompts;
- system instructions;
- tool use;
- output behaviour.

Where internal changes are difficult to interpret, observed behaviour should be tested empirically.

---

## 18. System Revalidation

System-level revalidation should consider interactions between:

- model;
- software;
- hardware;
- sensors;
- communications;
- data;
- users;
- interfaces;
- dependencies.

A validated model does not automatically imply a revalidated system.

---

## 19. Human-AI Revalidation

Assess whether changes affect:

- interpretation of outputs;
- uncertainty presentation;
- alerting;
- workload;
- decision time;
- automation bias;
- user understanding;
- override behaviour.

Human performance is part of the assurance case where the system depends on human judgement.

---

## 20. Safety Revalidation

Safety evidence should be reconsidered when changes affect:

- safeguards;
- interlocks;
- action constraints;
- fail-safe;
- human approval;
- degraded modes;
- recovery;
- termination.

High-consequence functions should receive heightened attention.

---

## 21. Security Revalidation

Security revalidation may assess:

- model integrity;
- data integrity;
- access control;
- dependencies;
- interfaces;
- attack surface;
- update mechanisms;
- monitoring.

Security changes should be evaluated for both technical and operational consequences.

---

## 22. Information Integrity Revalidation

For systems producing information used in consequential decisions, assess:

- source traceability;
- provenance;
- confidence;
- uncertainty;
- unsupported outputs;
- data authenticity;
- output integrity.

A change that affects information integrity can materially affect operational trust.

---

## 23. Adversarial Revalidation

Where relevant, revalidation should consider:

- manipulated inputs;
- adversarial examples;
- spoofing;
- deceptive data;
- malicious content;
- changing adversarial behaviour.

Testing should reflect the threat assumptions relevant to the authorised use.

---

## 24. TEVV Strategy

Revalidation should use an evidence strategy proportionate to the trigger.

Possible progression:

**Targeted Test → Regression Test → Representative Test → Adversarial Test → Operational Environment Test → Mission-Level Evaluation**

Not every revalidation requires every stage.

---

## 25. Independent Review

For high-consequence capabilities, revalidation should include independent review where practical.

Independence should increase with:

- consequence;
- autonomy;
- uncertainty;
- scope of change;
- weakness of existing evidence.

---

## 26. Revalidation Acceptance Criteria

Acceptance criteria should be defined before testing where practical.

They may include:

- required performance;
- acceptable error;
- robustness;
- uncertainty behaviour;
- safety;
- security;
- human control;
- autonomy;
- mission effectiveness.

---

## 27. Negative Testing

Revalidation should not focus only on expected successful behaviour.

Where appropriate, testing should include:

- failure conditions;
- edge cases;
- abnormal inputs;
- degraded conditions;
- contradictory information;
- unexpected environmental conditions;
- loss of supporting services.

---

## 28. Regression Testing

Critical previously validated behaviours should be retested where a change could affect them.

Historical failure modes should remain part of the regression set where relevant.

---

## 29. Uncertainty and Abstention

Revalidation should assess whether the capability:

- communicates uncertainty appropriately;
- abstains when information is inadequate;
- avoids unjustified confidence;
- behaves predictably near operating boundaries.

A system that becomes more confident without becoming more reliable may represent increased risk.

---

## 30. Mission Effectiveness

Revalidation should determine whether the changed capability still supports the intended mission.

Technical improvement does not automatically demonstrate mission improvement.

---

## 31. Revalidation Outcomes

A working outcome model is:

### Validated

Evidence supports continued use under existing conditions.

### Conditionally Validated

Use permitted subject to defined restrictions.

### Partially Validated

Some functions or environments remain validated while others require further evidence.

### Not Validated

Evidence is insufficient for continued use under the affected conditions.

### Validation Withdrawn

Existing validation is no longer relied upon pending reassessment.

---

## 32. Conditional Revalidation

Conditional validation may be appropriate where:

- evidence is sufficient for limited use;
- specific environments remain unvalidated;
- autonomy must be reduced;
- additional human supervision is required;
- enhanced monitoring is necessary.

Conditions should be explicit and time-bounded where appropriate.

---

## 33. Revalidation and Operational Authorisation

Following revalidation, the responsible authority should determine whether:

- existing authorisation remains valid;
- authorisation conditions require amendment;
- restrictions are necessary;
- new authorisation is required;
- use must remain suspended.

Revalidation provides evidence; operational authority provides permission.

---

## 34. Revalidation and Configuration

A successfully revalidated configuration should become an identifiable approved baseline.

The relationship should be:

**Revalidated Configuration → Assurance Evidence → Authorised Configuration**

---

## 35. Post-Revalidation Monitoring

Following revalidation, enhanced monitoring may be appropriate to confirm that:

- expected behaviour occurs operationally;
- no new failure modes emerge;
- assumptions remain valid;
- performance remains within the approved envelope.

---

## 36. Revalidation Record

A Revalidation Record should include, as applicable:

| Field | Description |
|---|---|
| Revalidation ID | Unique identifier |
| Capability ID | AI capability |
| Trigger | Reason for revalidation |
| Current Baseline | Existing configuration |
| Changed Baseline | Changed configuration |
| Scope | Revalidation scope |
| Requirements | Affected requirements |
| Risk | Updated risk |
| Autonomy | Updated autonomy assessment |
| Environment | Relevant environment |
| Tests | Tests performed |
| Evidence | Evidence generated |
| Findings | Key findings |
| Limitations | Remaining limitations |
| Conditions | Restrictions/conditions |
| Independent Review | Review status |
| Outcome | Validation outcome |
| Authorisation Impact | Effect on authority |
| Configuration | Approved baseline |
| Monitoring | Post-validation monitoring |
| Authority | Responsible authority |
| Date | Decision date |

---

## 37. Revalidation Decision

The final decision should state:

- what was revalidated;
- what evidence supports the decision;
- what limitations remain;
- what conditions apply;
- whether authorisation remains valid;
- whether reauthorisation is required.

---

## 38. Suspension During Revalidation

Where risk is uncertain and consequences are significant, the capability may be:

- suspended;
- restricted;
- operated at lower autonomy;
- operated under enhanced supervision.

The decision should be proportionate to the uncertainty and potential harm.

---

## 39. Emergency Revalidation

Emergency revalidation may use an accelerated evidence process where delay creates unacceptable risk.

It should still establish:

- minimum evidence;
- responsible authority;
- temporary restrictions;
- monitoring;
- residual uncertainty;
- retrospective full review where required.

---

## 40. Revalidation Failure

Revalidation may fail when:

- performance no longer meets requirements;
- safety evidence is insufficient;
- security assumptions fail;
- human control is inadequate;
- autonomy exceeds acceptable limits;
- mission effectiveness is not demonstrated;
- evidence cannot establish acceptable risk.

Possible outcomes include restriction, rollback, suspension or retirement.

---

## 41. Operational Learning

Revalidation findings should feed into:

- risk assessment;
- requirements;
- model development;
- system design;
- TEVV;
- training;
- monitoring;
- change management;
- operational authorisation.

---

## 42. Revalidation Closure

Revalidation is complete when:

- scope is addressed;
- required evidence is generated;
- findings are documented;
- limitations are recorded;
- risk is reassessed;
- configuration is established;
- required authorisation decisions are completed;
- monitoring requirements are defined.

---

## 43. Common Failure Modes

### 43.1 Repeating the Original Test Suite Blindly

Revalidation should focus on what changed while protecting critical previously validated behaviour.

### 43.2 Treating Revalidation as Reauthorisation

Evidence and authority are separate functions.

### 43.3 Assuming Old Evidence Automatically Transfers

Applicability must be demonstrated.

### 43.4 Testing Only the Model

System, human and operational effects may be equally important.

### 43.5 Ignoring New Environments

A new environment can invalidate existing evidence.

### 43.6 Ignoring Autonomy Changes

A change in autonomy can substantially alter consequence.

### 43.7 Ignoring Human Factors

Changed outputs or interfaces can change human decisions.

### 43.8 Ignoring Uncertainty

Improved average performance does not eliminate uncertainty at operational boundaries.

---

## 44. Core Rules

1. **Revalidation is required when material change or new evidence may invalidate previous assurance.**
2. **Revalidation assesses the current capability, not merely the changed component.**
3. **Existing evidence must be shown to remain applicable.**
4. **Revalidation scope should be proportionate to consequence, autonomy and change impact.**
5. **Critical previously validated behaviours should remain protected through regression testing.**
6. **New environments and missions require explicit assessment.**
7. **Changes to autonomy or human authority require heightened scrutiny.**
8. **Safety and security evidence must be reconsidered when affected by change.**
9. **Negative and degraded-condition testing should be used where appropriate.**
10. **Uncertainty and abstention behaviour should be reassessed where relevant.**
11. **High-consequence revalidation should include independent review where practical.**
12. **Revalidation provides evidence; operational authorisation provides permission.**
13. **Conditional validation should have explicit conditions and monitoring.**
14. **Revalidated configurations must be uniquely identified and controlled.**
15. **Revalidation findings must feed continuous assurance and future lifecycle decisions.**

---

## 45. Golden Thread

Revalidation maintains the Golden Thread:

**Mission Need → Risk → Requirements → Capability → Change / Trigger → Impact → TEVV → Evidence → Revalidation → Assurance → Authority → Deployment → Employment → Monitoring**

---

## 46. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **03 Risk & Autonomy** — reassesses risk and autonomy.
- **04 AI Lifecycle** — provides lifecycle revalidation control.
- **08 Human Authority** — validates continuing human control.
- **09 TEVV** — provides testing and evaluation evidence.
- **10 Operational Environment** — validates environmental suitability.
- **11 Operational Authorisation** — determines authority after revalidation.
- **12 Operational Employment** — provides operational evidence and context.
- **13 Performance Monitoring** — supplies degradation and trend evidence.
- **14 Model & System Updates** — identifies material changes.
- **15 Change Impact Assessment** — determines revalidation scope.
- **16 Reauthorisation** — governs renewed operational authority.
- **24 Architecture & Technical Controls** — supports technical verification.

---

## 47. Summary Model

```text
Trigger
   ↓
Scope Assessment
   ↓
Review Existing Evidence
   ↓
Identify Evidence Gaps
   ↓
Risk / Autonomy Reassessment
   ↓
Targeted / Partial / Full TEVV
   ↓
Revalidation Decision
   ↓
Validated / Conditional / Partial / Not Validated
   ↓
Reauthorisation Decision
   ↓
Updated Configuration Baseline
   ↓
Post-Revalidation Monitoring
```

Revalidation prevents historical assurance from being treated as permanent evidence after the capability, mission, environment, autonomy or risk has materially changed.
