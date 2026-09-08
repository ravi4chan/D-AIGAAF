# 07 — Assurance Change, Revalidation and Reauthorisation

## 1. Purpose

This document defines how D-AIGAAF manages changes that may affect continuing assurance and determines when revalidation or reauthorisation is required.

The objective is to prevent a previously assured and authorised Defence AI capability from being treated as automatically suitable after material changes to its technology, mission, environment, autonomy, human authority, configuration, dependencies, threat conditions or operating assumptions.

---

## 2. Core Principle

> **A material change shall not be assumed to preserve existing assurance or operational authority. Changes shall be assessed for their effect on risk, evidence, controls, assurance claims and authorisation. Where existing evidence is no longer sufficient, the capability shall undergo proportionate revalidation and, where the authorised basis has materially changed, reauthorisation before continued unrestricted employment.**

---

## 3. Change Object

Change assessment should consider:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

A change in any material element may affect assurance.

---

## 4. Types of Change

Changes may involve:

- model;
- software;
- hardware;
- data;
- configuration;
- interfaces;
- system integration;
- mission;
- environment;
- autonomy;
- human authority;
- dependencies;
- suppliers;
- threat conditions;
- legal or policy requirements.

---

## 5. Change Classification

A practical classification is:

### Minor Change

No material effect on assurance claims, risk, operational boundaries or authorisation is expected.

### Significant Change

Potential effect on assurance exists and requires documented assessment.

### Material Change

The change may alter risk, capability, mission, environment, autonomy, human authority, evidence or authorisation sufficiently to require revalidation and/or reauthorisation.

---

## 6. Change Assessment

Every potentially material change should be assessed for impact on:

- requirements;
- risks;
- controls;
- evidence;
- performance;
- human control;
- autonomy;
- environment;
- security;
- dependencies;
- mission effectiveness;
- authorisation.

---

## 7. Change Triggers

A change assessment may be triggered by:

- model update;
- software update;
- data change;
- hardware replacement;
- configuration change;
- new interface;
- supplier change;
- mission change;
- environmental change;
- autonomy change;
- human-role change;
- new threat;
- incident;
- performance drift;
- assurance finding.

---

## 8. Change Impact on Assurance Claims

The organisation should identify which assurance claims may be affected.

For each affected claim, determine whether existing evidence remains:

- valid;
- partially applicable;
- outdated;
- insufficient;
- contradicted.

---

## 9. Change Impact on Risk

The assessment should determine whether the change:

- creates a new risk;
- increases an existing risk;
- reduces a risk;
- changes risk controls;
- changes residual risk;
- changes risk acceptance.

Risk changes should be linked to the appropriate authority.

---

## 10. Change Impact on Human Control

Changes should be assessed for effects on:

- decision rights;
- workload;
- interface;
- intervention;
- override;
- situational awareness;
- competence;
- automation bias.

A technically minor change may be assurance-significant if it changes human interaction.

---

## 11. Change Impact on Autonomy

Changes should be assessed for effects on:

- autonomy state;
- autonomy transitions;
- autonomous actions;
- boundaries;
- intervention;
- human authority.

Any expansion of autonomy should receive heightened scrutiny.

---

## 12. Change Impact on Environment

Changes should be assessed for effects on:

- operating envelope;
- environmental assumptions;
- sensors;
- communications;
- navigation;
- information conditions;
- degraded operation;
- adversarial conditions.

---

## 13. Change Impact on Security

Changes should be assessed for:

- new vulnerabilities;
- altered attack surface;
- model integrity;
- software integrity;
- data integrity;
- interface security;
- dependency security.

---

## 14. Change Impact on Dependencies

Changes should identify whether:

- new dependencies are introduced;
- critical dependencies change;
- resilience changes;
- supplier exposure changes;
- failure modes change.

---

## 15. Change Impact on Evidence

The organisation should determine:

- which evidence remains valid;
- which evidence must be supplemented;
- which evidence must be regenerated;
- whether new testing is required.

Evidence should not be assumed to transfer automatically across materially different configurations.

---

## 16. Revalidation

Revalidation is the process of establishing that specified assurance claims remain valid following a relevant change or new evidence.

Revalidation should be proportionate to the affected claim.

---

## 17. Revalidation Triggers

Revalidation may be required following:

- material model change;
- significant software change;
- material data change;
- changed operating environment;
- new autonomy;
- intervention failure;
- significant performance drift;
- major security finding;
- changed human role;
- new mission;
- significant incident.

---

## 18. Revalidation Scope

Revalidation may be:

### Focused

Limited to the affected requirement or assurance claim.

### Domain-Based

Covers affected domains such as security, autonomy or human control.

### End-to-End

Reassesses the complete operational capability where interactions are significant.

---

## 19. Revalidation Evidence

Evidence may include:

- regression testing;
- targeted TEVV;
- operational testing;
- security testing;
- human-factors assessment;
- autonomy evaluation;
- environmental testing;
- dependency testing;
- operational evidence.

---

## 20. Revalidation Outcome

Possible outcomes include:

- claim remains valid;
- claim remains valid with conditions;
- additional controls required;
- additional evidence required;
- restrictions required;
- claim not demonstrated;
- reauthorisation required;
- employment suspended.

---

## 21. Reauthorisation

Reauthorisation is the formal governance decision to continue, amend, restrict or renew operational authority after a material change or review.

Reauthorisation should consider:

- assurance;
- risk;
- mission;
- environment;
- autonomy;
- human authority;
- configuration;
- conditions;
- operational boundaries.

---

## 22. Revalidation versus Reauthorisation

The distinction is:

**Revalidation → Does the assurance claim remain supported?**

**Reauthorisation → Is continued or changed operational authority approved?**

Revalidation does not itself create operational authority.

Reauthorisation should not be granted without sufficient assurance for the changed basis.

---

## 23. Change and Existing Authorisation

An existing authorisation should be treated as applying only to its defined scope.

A capability should not automatically be considered authorised for:

- a new mission;
- a new environment;
- higher autonomy;
- changed human authority;
- materially changed configuration;
- materially changed consequences.

---

## 24. Emergency Changes

Emergency changes may be required to:

- address safety;
- mitigate security threats;
- restore essential functionality;
- correct critical defects.

Emergency change procedures should define:

- authority;
- scope;
- safeguards;
- documentation;
- testing;
- post-change assessment;
- revalidation;
- reauthorisation.

---

## 25. Emergency Change Principle

Emergency action should reduce risk and restore controlled operation.

It should not be used as a general mechanism for bypassing governance requirements.

---

## 26. Temporary Changes

Temporary changes should have:

- defined purpose;
- authorised duration;
- scope;
- controls;
- monitoring;
- expiry;
- restoration conditions.

Temporary status should not become permanent through administrative inertia.

---

## 27. Configuration Baseline

The organisation should maintain an approved configuration baseline.

Changes should be traceable to:

- approved request;
- authority;
- implementation;
- testing;
- resulting configuration;
- assurance assessment.

---

## 28. Model Change

Model changes should consider:

- architecture;
- weights;
- training data;
- fine-tuning;
- prompting or control logic;
- performance;
- uncertainty;
- failure modes;
- security;
- autonomy;
- human interaction.

A change to hidden model behaviour may require substantial revalidation even where the user-facing interface appears unchanged.

---

## 29. Data Change

Material data changes may include:

- new source;
- new distribution;
- changed quality;
- changed provenance;
- new operational population;
- altered labels;
- changed preprocessing.

The impact on model performance and assurance should be assessed.

---

## 30. Mission Change

A mission change should be assessed for effects on:

- purpose;
- consequence;
- users;
- operating conditions;
- decisions;
- actions;
- autonomy;
- human authority.

A technically unchanged AI may require new assurance for a materially different mission.

---

## 31. Environment Change

A change in environment should be assessed against the demonstrated operating envelope.

Where the capability enters previously untested conditions, additional assurance may be required.

---

## 32. Autonomy Change

An increase or material change in autonomy should receive heightened assurance scrutiny.

The assessment should address:

- risk;
- human control;
- intervention;
- boundary;
- performance;
- failure behaviour;
- safe state.

---

## 33. Human Authority Change

Changes to who may:

- approve;
- supervise;
- intervene;
- override;
- suspend;
- restore;

should be assessed for assurance impact.

---

## 34. Dependency Change

New or changed dependencies should be assessed for:

- availability;
- integrity;
- security;
- resilience;
- failure behaviour;
- operational authority implications.

---

## 35. Change Review

Material changes should receive appropriate review before implementation or continued employment.

Review should confirm:

- impact assessment;
- evidence plan;
- testing;
- authority;
- conditions;
- rollback or recovery.

---

## 36. Independent Challenge

Material changes should receive independent challenge where proportionate to:

- consequence;
- uncertainty;
- autonomy;
- complexity;
- assurance impact.

---

## 37. Change Findings

Findings may include:

- insufficient evidence;
- invalidated assumption;
- increased risk;
- ineffective control;
- unexpected behaviour;
- inadequate testing.

Findings should enter the corrective-action process.

---

## 38. Change Records

A material change record should include:

- change ID;
- description;
- reason;
- affected capability;
- affected configuration;
- affected mission;
- affected environment;
- risk impact;
- assurance impact;
- testing;
- decision;
- authority;
- implementation date;
- resulting status.

---

## 39. Revalidation Records

Revalidation records should establish:

- claims assessed;
- evidence;
- methods;
- findings;
- limitations;
- conclusion;
- responsible authority.

---

## 40. Reauthorisation Records

Reauthorisation records should identify:

- previous authority;
- changed basis;
- assurance conclusion;
- risk position;
- new conditions;
- new boundaries;
- autonomy;
- human authority;
- validity;
- approving authority.

---

## 41. Change Monitoring

Following a material change, enhanced monitoring may be required to verify that real-world behaviour remains consistent with revalidation evidence.

This is particularly important for:

- model changes;
- autonomy changes;
- environmental changes;
- major software changes.

---

## 42. Change Rollback

Where a change produces unacceptable effects, the organisation should have controlled mechanisms to:

- stop deployment;
- restrict functionality;
- restore a previous configuration where safe and authorised;
- enter safe state;
- suspend employment.

Rollback should not be assumed to restore assurance automatically.

---

## 43. Change and Lessons Learned

Change-related findings should feed into:

- requirements;
- development;
- TEVV;
- monitoring;
- procurement;
- training;
- authorisation;
- future change-control procedures.

---

## 44. Governance Questions

The organisation should be able to answer:

1. What constitutes a material change?
2. Who performs change-impact assessment?
3. Which assurance claims are affected?
4. Which evidence remains valid?
5. When is revalidation required?
6. When is reauthorisation required?
7. How are model changes assessed?
8. How are data changes assessed?
9. How are autonomy changes assessed?
10. How are human-authority changes assessed?
11. How are emergency changes governed?
12. How are temporary changes controlled?
13. Who independently challenges material changes?
14. How are changes recorded?
15. How is post-change behaviour monitored?

---

## 45. Core Rule

> **Material change shall trigger an explicit assessment of its effect on assurance, risk and operational authority. Existing evidence and authorisation shall not automatically be assumed to apply to a materially changed capability, mission, environment, autonomy, human authority, configuration or dependency. Revalidation shall establish whether assurance claims remain supported, while reauthorisation shall determine whether continued or changed operational authority is permitted.**

---

## 46. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Change → Impact Assessment → Revalidation → Reauthorisation → Employment → Monitoring → Learning**
