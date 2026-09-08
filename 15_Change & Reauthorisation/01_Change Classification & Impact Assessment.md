# 01 — Change Classification & Impact Assessment

## 1. Purpose

This document defines the method for classifying changes to Defence AI capabilities and assessing their potential effect on risk, assurance, operational authority and authorised employment.

The objective is to ensure that governance effort is proportionate to the significance of the change.

---

## 2. Core Principle

> **Change classification shall be based on potential operational effect, not merely on the technical size or location of the change.**

A small technical change may have a material operational effect, while a large administrative change may have little or no effect on the authorised basis.

---

## 3. Scope

This process applies to changes involving:

- models;
- software;
- hardware;
- data;
- configuration;
- interfaces;
- sensors;
- communications;
- dependencies;
- environment;
- mission;
- autonomy;
- human authority;
- security;
- operational procedures.

---

## 4. Change Object

The change should be assessed against:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

---

## 5. Change Identification

The change owner should document:

- what is changing;
- why it is changing;
- affected components;
- affected configuration;
- expected benefits;
- known risks;
- dependencies;
- intended operational scope.

---

## 6. Baseline Comparison

The proposed state should be compared with the authorised baseline.

The comparison should identify:

- functional differences;
- behavioural differences;
- performance differences;
- interface differences;
- dependency differences;
- environmental differences;
- human-interaction differences.

---

## 7. Classification Categories

D-AIGAAF uses three primary change categories:

### Minor

No material effect is reasonably expected on risk, assurance, human control, autonomy, authorised boundaries or mission effectiveness.

### Significant

A meaningful effect is possible and additional assessment, testing or controls may be required.

### Material

The change may alter the basis of assurance, risk acceptance, operational authority or authorised conditions.

---

## 8. Classification is Not Permanent

A change classification may be revised when new evidence becomes available.

For example:

**Minor → Significant → Material**

The highest justified classification should govern the change.

---

## 9. Impact Assessment

The assessment should consider:

- mission;
- risk;
- requirements;
- controls;
- evidence;
- assurance;
- human control;
- autonomy;
- environment;
- security;
- dependencies;
- mission effectiveness.

---

## 10. Mission Impact

Determine whether the change affects:

- mission purpose;
- mission objectives;
- decision context;
- success criteria;
- operational timing;
- mission constraints.

A change that alters what the AI is expected to accomplish may require higher-level governance.

---

## 11. Risk Impact

Assess whether the change:

- introduces new risks;
- increases existing risks;
- changes consequences;
- changes likelihood;
- changes uncertainty;
- changes residual risk.

---

## 12. Assurance Impact

Identify affected assurance claims.

For each claim determine whether existing evidence remains:

- applicable;
- current;
- representative;
- sufficient;
- configuration-specific.

---

## 13. Evidence Impact

Existing evidence should be mapped to the changed configuration.

Evidence should not automatically transfer simply because:

- the same supplier is used;
- the same model family is used;
- the same software platform is used;
- the change appears small.

---

## 14. Human-Control Impact

Assess whether the change affects:

- decision rights;
- operator understanding;
- situational awareness;
- workload;
- intervention;
- override;
- escalation;
- training requirements.

---

## 15. Autonomy Impact

Determine whether the change affects:

- autonomy level;
- autonomy transitions;
- decision authority;
- action boundaries;
- intervention requirements;
- safe-state behaviour;
- observability.

Any change that increases consequential autonomy should receive explicit governance scrutiny.

---

## 16. Environmental Impact

Assess whether the change affects the capability's suitability for:

- authorised terrain;
- weather;
- sensor conditions;
- communications conditions;
- degraded operation;
- disconnected operation;
- adversarial conditions.

---

## 17. Security Impact

Assess changes to:

- attack surface;
- interfaces;
- software;
- model integrity;
- data;
- access controls;
- dependencies;
- supply chain;
- monitoring.

---

## 18. Dependency Impact

Determine whether the change introduces or modifies dependencies on:

- external services;
- communications;
- navigation;
- sensors;
- data sources;
- suppliers;
- other AI systems;
- computing resources.

---

## 19. Mission-Effectiveness Impact

Assess whether the change may alter:

- accuracy;
- reliability;
- timeliness;
- availability;
- robustness;
- decision quality;
- operational suitability.

---

## 20. Control Impact

Determine whether existing controls remain:

- applicable;
- effective;
- testable;
- observable;
- enforceable.

New risks may require new controls.

---

## 21. Boundary Impact

Assess whether the change affects:

- authorised mission boundaries;
- operating envelope;
- autonomy boundaries;
- prohibited uses;
- human-authority boundaries;
- environmental restrictions.

---

## 22. Configuration Impact

Determine whether the change creates:

- a new configuration;
- a new version;
- a modified baseline;
- a new dependency set;
- a new operational parameter set.

The resulting configuration must remain uniquely identifiable.

---

## 23. Cumulative Changes

Multiple individually minor changes may collectively become significant or material.

The organisation should therefore consider:

- change history;
- cumulative effects;
- interaction effects;
- repeated modifications;
- configuration drift.

---

## 24. Uncertainty

Where impact cannot be determined confidently, uncertainty should increase governance scrutiny rather than reduce it.

Unknown impact should not automatically be treated as low impact.

---

## 25. Change Dependencies

The assessment should identify changes that are dependent on one another.

A change may require another change to:

- data;
- software;
- hardware;
- security;
- training;
- operating procedures;
- infrastructure.

---

## 26. Impact Categories

A practical assessment can classify impact as:

- None;
- Low;
- Moderate;
- High;
- Critical.

Impact should be assessed independently across relevant domains.

---

## 27. Overall Change Significance

Overall significance should consider the highest credible impact across:

**Risk + Assurance + Human Control + Autonomy + Environment + Security + Dependencies + Mission**

A high-consequence impact in one domain should not be masked by low impact in others.

---

## 28. Assessment Outcomes

The assessment may conclude:

- no further governance action;
- additional controls;
- additional testing;
- focused assurance review;
- revalidation;
- reauthorisation;
- restricted implementation;
- suspension pending assessment.

---

## 29. Revalidation Trigger

Revalidation should be considered where:

- assurance evidence is affected;
- assumptions change;
- performance changes;
- controls change;
- environmental applicability changes;
- human-control effectiveness may change.

---

## 30. Reauthorisation Trigger

Reauthorisation should be considered where the change affects the authorised basis, including:

- mission;
- risk acceptance;
- environment;
- autonomy;
- human authority;
- operating boundaries;
- authorisation conditions.

---

## 31. Independent Review

Significant and material changes should receive proportionate independent challenge.

The review should examine:

- classification;
- assumptions;
- impact assessment;
- evidence;
- controls;
- proposed governance action.

---

## 32. Change Decision Authority

Decision authority should be determined by:

- change significance;
- consequence;
- autonomy;
- affected scope;
- assurance impact;
- risk.

Implementation responsibility does not automatically confer approval authority.

---

## 33. Change Conditions

Approval may be subject to:

- additional testing;
- restricted mission;
- restricted environment;
- reduced autonomy;
- additional supervision;
- enhanced monitoring;
- defined review period.

---

## 34. Change Record

The assessment record should contain:

- change identifier;
- baseline;
- proposed state;
- classification;
- impact assessment;
- affected claims;
- evidence;
- risk;
- controls;
- decision;
- authority;
- conditions.

---

## 35. Traceability

The change should be traceable through:

**Change → Classification → Impact → Controls → Evidence → Decision → Verification → Revalidation/Reauthorisation**

---

## 36. Governance Questions

The organisation should be able to answer:

1. What changed?
2. What was the authorised baseline?
3. Why was the change required?
4. How was the change classified?
5. What operational effects were considered?
6. Which risks changed?
7. Which assurance claims changed?
8. Which evidence remains valid?
9. Are human-control arrangements affected?
10. Is autonomy affected?
11. Is the operating environment affected?
12. Are security or dependencies affected?
13. Are cumulative changes relevant?
14. Is revalidation required?
15. Is reauthorisation required?
16. Who approved the change?
17. What conditions apply?

---

## 37. Core Rule

> **Change significance shall be determined by potential effect on the authorised and assured operational capability, not by technical effort, organisational ownership or the apparent size of the modification.**

---

## 38. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Baseline → Change → Classification → Impact Assessment → Decision → Verification → Revalidation/Reauthorisation → Employment → Monitoring → Learning**
