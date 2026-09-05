# Change Impact Assessment

## Summary

Change Impact Assessment determines how a proposed change to an AI capability could affect its mission, performance, risk, autonomy, safety, security, assurance and operational authorisation.

The assessment is the decision point between **identifying a change** and **deciding how much governance, testing and assurance the change requires**.

The core principle is:

**The governance response to a change should be proportionate to its potential operational impact, not merely to the size or complexity of the technical change.**

The core chain is:

**Change → Impact Identification → Risk Assessment → Classification → Testing → Revalidation / Reauthorisation Decision**

---

## 1. Purpose

Change Impact Assessment establishes a consistent process to:

- understand what a proposed change affects;
- identify new or changed risks;
- determine whether existing evidence remains valid;
- classify change materiality;
- define required testing and assurance;
- determine whether revalidation is required;
- determine whether reauthorisation is required.

---

## 2. Core Principle

**A change is material when it can materially alter the conditions under which the AI capability is trusted or authorised.**

Materiality should therefore be assessed across:

**Capability × Mission × Environment × Risk × Autonomy × Human Authority**

---

## 3. Scope

Impact assessment applies to changes involving:

- models;
- model weights;
- training;
- fine-tuning;
- data;
- software;
- firmware;
- hardware;
- sensors;
- interfaces;
- parameters;
- prompts or system instructions;
- dependencies;
- infrastructure;
- security;
- safety;
- autonomy;
- users;
- missions;
- environments.

---

## 4. Change Description

Every assessment should begin with a clear description of:

- what is changing;
- what is not changing;
- why it is changing;
- who proposed it;
- affected components;
- current baseline;
- proposed baseline;
- expected benefits;
- expected risks.

Ambiguous change descriptions should not be treated as low-risk by default.

---

## 5. Impact Domains

A change impact assessment should consider at least:

1. Mission
2. Requirements
3. Performance
4. Data
5. Model
6. System Integration
7. Configuration
8. Operational Environment
9. Human-AI Interaction
10. Human Authority
11. Autonomy
12. Safety
13. Security
14. Information Integrity
15. Interoperability
16. Supply Chain
17. Legal and Policy
18. Assurance
19. Operational Authorisation
20. Sustainment

---

## 6. Mission Impact

Assess whether the change affects:

- intended mission;
- mission success criteria;
- supported decisions;
- supported actions;
- mission criticality;
- operational users.

A change that introduces a new mission should normally be treated as more than a technical update.

---

## 7. Requirements Impact

Determine whether existing requirements remain valid.

Questions include:

- Does the change affect functional requirements?
- Does it affect performance requirements?
- Does it affect safety requirements?
- Does it affect autonomy requirements?
- Does it affect human-authority requirements?
- Does it introduce new requirements?

If requirements change, the requirements baseline should be updated before assurance is completed.

---

## 8. Performance Impact

Assess possible effects on:

- accuracy;
- precision;
- recall;
- false positives;
- false negatives;
- latency;
- availability;
- reliability;
- robustness;
- uncertainty;
- abstention.

A performance improvement in one area may introduce degradation elsewhere.

---

## 9. Data Impact

Assess whether the change affects:

- data sources;
- data distributions;
- labels;
- preprocessing;
- filtering;
- augmentation;
- synthetic data;
- data provenance;
- data quality;
- data access.

Data changes can alter model behaviour without changing model architecture.

---

## 10. Model Impact

Assess whether the change affects:

- architecture;
- weights;
- training;
- fine-tuning;
- inference;
- optimisation;
- prompts;
- system instructions;
- tool use;
- output generation.

Where internal behaviour cannot be reliably inferred, empirical evaluation should be used.

---

## 11. System Impact

Assess whether the change affects:

- interfaces;
- sensors;
- communications;
- compute;
- storage;
- software;
- hardware;
- dependencies;
- human-machine interface;
- safety mechanisms.

An unchanged model may still produce different operational behaviour when integrated into a changed system.

---

## 12. Configuration Impact

Determine whether the change creates a new configuration baseline.

The assessment should identify:

- changed components;
- unchanged components;
- dependencies;
- version relationships;
- rollback state.

The resulting configuration should remain uniquely identifiable.

---

## 13. Operational Environment Impact

Assess whether the change:

- expands the operating environment;
- changes environmental assumptions;
- changes sensor assumptions;
- changes communications assumptions;
- changes data conditions;
- changes infrastructure requirements.

A capability demonstrated in one environment should not automatically be considered assured in another.

---

## 14. Human-AI Interaction Impact

Assess effects on:

- user interface;
- workload;
- decision time;
- alerting;
- explanation;
- uncertainty presentation;
- user understanding;
- automation bias;
- override mechanisms.

Changes in presentation can materially affect human decisions even when underlying model performance is unchanged.

---

## 15. Human Authority Impact

Determine whether the change affects:

- who receives outputs;
- who interprets outputs;
- who approves actions;
- who can override;
- who can suspend;
- who can terminate.

Changes to authority relationships should receive explicit governance review.

---

## 16. Autonomy Impact

Assess whether the change affects:

- autonomy level;
- action boundaries;
- supervision;
- intervention;
- autonomy transitions;
- termination;
- fail-safe.

Any increase in consequential autonomy should receive heightened scrutiny.

---

## 17. Safety Impact

Assess effects on:

- safety constraints;
- interlocks;
- human approval;
- fail-safe;
- degraded modes;
- recovery;
- termination;
- unintended actions.

Changes that can increase potential harm should be treated as material unless evidence demonstrates otherwise.

---

## 18. Security Impact

Assess effects on:

- attack surface;
- access control;
- model integrity;
- data integrity;
- interfaces;
- dependencies;
- authentication;
- monitoring;
- logging.

Security changes should be assessed alongside functional effects.

---

## 19. Information Integrity Impact

Determine whether the change can affect:

- source traceability;
- data authenticity;
- output integrity;
- provenance;
- uncertainty;
- generated information.

For systems producing information used in consequential decisions, information integrity should be treated as a core impact domain.

---

## 20. Interoperability Impact

Assess whether the change affects:

- interfaces;
- data formats;
- protocols;
- dependent systems;
- coalition interoperability where applicable;
- backward compatibility.

Technical compatibility does not automatically demonstrate operational interoperability.

---

## 21. Supply Chain Impact

Assess whether the change introduces or modifies:

- suppliers;
- third-party software;
- external services;
- hardware;
- model providers;
- update mechanisms;
- critical dependencies.

Changes should preserve visibility of critical provenance.

---

## 22. Legal and Policy Impact

Assess whether the change affects:

- legal obligations;
- policy constraints;
- rules or directives;
- data governance;
- records requirements;
- procurement obligations;
- applicable operational restrictions.

A technical change may create new governance obligations.

---

## 23. Assurance Impact

The assessment should identify which previous evidence remains valid and which may no longer be sufficient.

Consider:

- previous test results;
- validation;
- evaluation;
- red-team evidence;
- operational evidence;
- safety evidence;
- security evidence;
- human factors evidence.

Evidence should not be assumed transferable without justification.

---

## 24. Operational Authorisation Impact

Determine whether the change affects the conditions of existing operational authorisation.

Ask whether it changes:

- capability;
- mission;
- environment;
- autonomy;
- human authority;
- operating envelope;
- risk;
- safety;
- security.

If material conditions change, reauthorisation should be considered.

---

## 25. Risk Impact

Assess whether the change alters:

- likelihood;
- consequence;
- mission criticality;
- human control;
- autonomy;
- exposure;
- residual risk.

A change that reduces one risk may increase another.

---

## 26. Risk Transfer

Changes should be assessed for risk transfer.

For example:

- improved speed may increase error;
- increased autonomy may reduce workload but increase consequence;
- improved accuracy may reduce one failure mode while introducing another;
- stronger security controls may reduce availability.

The assessment should consider the complete risk profile.

---

## 27. Dependency Impact

Changes should consider indirect effects from dependencies.

A change in one component may affect:

- model execution;
- data processing;
- timing;
- security;
- interfaces;
- safety;
- system availability.

Impact assessment should therefore include relevant dependencies rather than only the directly modified component.

---

## 28. Change Materiality

Materiality should consider:

- consequence;
- probability;
- uncertainty;
- autonomy;
- scope;
- reversibility;
- detectability;
- operational exposure;
- evidence strength.

A technically small change may be operationally material.

---

## 29. Working Impact Levels

A useful assessment model is:

### Low Impact

No meaningful effect expected on authorised behaviour, risk or operational conditions.

### Moderate Impact

Potential effect exists but can be addressed through targeted testing and controls.

### High Impact

Potential material effect on performance, risk, safety, security, autonomy or operating conditions.

### Critical Impact

Potential to invalidate major assurance assumptions or materially alter consequential behaviour or authority.

These are working D-AIGAAF categories and should be aligned with organisational governance before formal adoption.

---

## 30. Reversibility

Assess whether the change can be safely reversed.

Consider:

- rollback availability;
- dependency compatibility;
- data compatibility;
- operational disruption;
- recovery time.

Irreversible or difficult-to-reverse changes generally require stronger assurance.

---

## 31. Detectability

Assess whether harmful effects would be:

- immediately observable;
- detectable through monitoring;
- detectable only through detailed analysis;
- difficult to detect.

Changes with low detectability may require stronger pre-deployment testing.

---

## 32. Operational Exposure

Assess:

- frequency of use;
- number of users;
- mission criticality;
- affected systems;
- geographic/environmental scope;
- autonomy;
- potential consequence.

Higher exposure should generally increase assessment depth.

---

## 33. Evidence Confidence

The assessment should consider confidence in existing evidence.

Evidence confidence may be reduced by:

- outdated testing;
- changed environment;
- changed data;
- changed configuration;
- limited test coverage;
- unknown dependencies;
- significant uncertainty.

Weak evidence should not be treated as equivalent to strong evidence.

---

## 34. Change Classification Decision

The assessment should produce a recommended change class.

A working mapping is:

| Impact | Typical Response |
|---|---|
| Low | Configuration/documentation review |
| Moderate | Targeted testing and assurance review |
| High | Extended TEVV and formal revalidation |
| Critical | Full reassessment and likely reauthorisation |

The final decision should be made by the appropriate authority.

---

## 35. Testing Requirements

The assessment should define testing proportionate to impact.

Possible testing includes:

- regression testing;
- performance testing;
- robustness testing;
- adversarial testing;
- safety testing;
- security testing;
- human factors testing;
- autonomy testing;
- operational environment testing;
- mission-level evaluation.

---

## 36. Revalidation Decision

Revalidation should be required where existing evidence may no longer support the changed capability.

The decision should identify:

- evidence affected;
- additional testing;
- responsible authority;
- acceptance criteria;
- required configuration.

---

## 37. Reauthorisation Decision

Reauthorisation should be considered where the change affects the authorised relationship between:

**Capability × Mission × Environment × Autonomy × Human Authority**

The assessment should explicitly document why reauthorisation is or is not required.

---

## 38. Emergency Change Assessment

Emergency changes may require an accelerated impact assessment.

The assessment should still identify:

- affected components;
- expected risk;
- operational restrictions;
- testing available;
- residual uncertainty;
- approval authority;
- monitoring;
- rollback.

Emergency processes should be documented and retrospectively reviewed.

---

## 39. Supplier Change Assessment

Supplier-provided changes should be assessed using the same impact domains.

Supplier claims should be supported by evidence where possible.

The organisation should retain responsibility for determining whether the changed capability remains suitable for its intended operational use.

---

## 40. Change Impact Assessment Record

The record should include, as applicable:

| Field | Description |
|---|---|
| Change ID | Unique identifier |
| Capability ID | Affected capability |
| Current Configuration | Existing baseline |
| Proposed Configuration | New baseline |
| Change Description | What changes |
| Reason | Why change is proposed |
| Mission Impact | Effect on mission |
| Requirements Impact | Effect on requirements |
| Performance Impact | Effect on performance |
| Data Impact | Effect on data |
| Model Impact | Effect on model |
| System Impact | Effect on integration |
| Environment Impact | Effect on operating conditions |
| Human Impact | Effect on users and authority |
| Autonomy Impact | Effect on autonomy |
| Safety Impact | Effect on safety |
| Security Impact | Effect on security |
| Risk Impact | Effect on risk |
| Assurance Impact | Effect on existing evidence |
| Authorisation Impact | Effect on authority |
| Materiality | Impact classification |
| Testing | Required testing |
| Revalidation | Required? |
| Reauthorisation | Required? |
| Approver | Responsible authority |
| Decision | Final decision |
| Date | Assessment date |

---

## 41. Decision Record

The assessment should produce an explicit decision:

**Approve as Low Impact / Controlled Change / Revalidate / Reauthorise / Reject / Suspend**

The rationale should be recorded.

---

## 42. Independence and Challenge

For high-consequence changes, assessment should include independent review or challenge where practical.

The person proposing the change should not be the sole person deciding that the change is immaterial.

---

## 43. Monitoring After Change

The impact assessment should define any enhanced post-change monitoring required.

Monitoring may focus on:

- changed metrics;
- changed failure modes;
- uncertainty;
- user interaction;
- autonomy;
- safety;
- security;
- mission performance.

---

## 44. Change Closure

A change should not be considered closed until:

- implementation is verified;
- testing is complete;
- required assurance is complete;
- revalidation is complete where required;
- reauthorisation is complete where required;
- monitoring requirements are established;
- configuration baseline is updated;
- records are complete.

---

## 45. Common Failure Modes

### 45.1 Treating Every Software Update as Low Risk

A software change may affect model execution, safety or autonomy.

### 45.2 Focusing Only on the Changed Component

System-level behaviour can emerge from interactions between components.

### 45.3 Assuming Model Unchanged Means Risk Unchanged

Data, environment and integration can change operational behaviour.

### 45.4 Accepting Supplier Claims Without Assessment

External assurance does not automatically establish mission-specific suitability.

### 45.5 Ignoring Human Factors

Changes to interfaces and alerts can alter human decisions.

### 45.6 Ignoring Autonomy

Small technical changes can alter autonomous behaviour.

### 45.7 Reusing Old Evidence Without Justification

Evidence must be shown to remain applicable.

### 45.8 Treating Emergency Changes as Exempt

Emergency processes may be accelerated but should remain governed.

### 45.9 Failing to Record Rationale

Future reviewers need to understand why a change was classified as material or non-material.

---

## 46. Core Rules

1. **Every material change must undergo documented impact assessment.**
2. **Impact assessment must consider operational consequences, not only technical complexity.**
3. **Model, data, software, hardware, environment and human factors must be assessed together where relevant.**
4. **A change can be material even when the model itself is unchanged.**
5. **Changes affecting autonomy require explicit assessment.**
6. **Changes affecting human authority require explicit governance review.**
7. **Changes affecting safety or security require heightened scrutiny.**
8. **New missions and environments should be assessed as potential material changes.**
9. **Previous assurance evidence must be demonstrated to remain applicable.**
10. **Risk transfer must be considered, not only risk reduction.**
11. **Low detectability and low reversibility increase change risk.**
12. **High-consequence changes should receive independent challenge where practical.**
13. **Emergency changes may use accelerated procedures but must remain documented and reviewable.**
14. **The final change classification and rationale must be recorded.**
15. **Change closure requires configuration, assurance and authorisation records to be updated as applicable.**

---

## 47. Golden Thread

Change Impact Assessment maintains the Golden Thread:

**Mission Need → Risk → Requirements → Capability → Change → Impact → Testing → Evidence → Assurance → Authority → Deployment → Monitoring → Revalidation → Reauthorisation**

---

## 48. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **03 Risk & Autonomy** — provides risk and autonomy assessment.
- **04 AI Lifecycle** — governs lifecycle change.
- **06 AI Security** — assesses security impact.
- **07 Supply Chain & Sovereignty** — assesses supplier and dependency impact.
- **08 Human Authority** — assesses human-control implications.
- **09 TEVV** — defines evidence and testing.
- **10 Operational Environment** — assesses environmental impact.
- **11 Operational Authorisation** — determines impact on authority.
- **12 Operational Employment** — provides operational context.
- **13 Performance Monitoring** — identifies changes requiring assessment.
- **14 Model & System Updates** — initiates and controls changes.
- **16 Reauthorisation** — governs renewed operational authority.
- **24 Architecture & Technical Controls** — identifies technical dependencies and controls.

---

## 49. Summary Model

```text
Proposed Change
       ↓
Change Description
       ↓
Impact Domains
       ↓
Risk / Materiality Assessment
       ↓
Low / Moderate / High / Critical
       ↓
Testing Requirements
       ↓
Assurance Review
       ↓
Revalidation?
   ↙          ↘
 Yes           No
  ↓             ↓
Revalidate     Continue
  ↓
Reauthorisation?
   ↙          ↘
 Yes           No
  ↓             ↓
Reauthorise   Deploy / Monitor
        ↓
Configuration Update
        ↓
Post-Change Monitoring
        ↓
Change Closure
```

Change Impact Assessment is the mechanism that prevents apparently routine updates from bypassing the assurance and authority required when operational risk changes.
