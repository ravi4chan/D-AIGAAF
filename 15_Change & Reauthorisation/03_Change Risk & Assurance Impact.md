# 03 — Change Risk & Assurance Impact

## 1. Purpose

This document defines how a proposed change is assessed for its effect on risk, assurance claims, evidence, controls and confidence in the continued safe and appropriate operation of a Defence AI capability.

---

## 2. Core Principle

> **A change shall be evaluated not only for what it changes technically, but for whether it changes the evidence, assumptions, controls or risk basis supporting operational confidence and authority.**

---

## 3. Scope

This assessment applies to changes affecting:

- models;
- data;
- software;
- hardware;
- configuration;
- interfaces;
- dependencies;
- security;
- environment;
- mission;
- autonomy;
- human authority.

---

## 4. Assessment Object

The assessment should consider:

**Change × Mission × Risk × Assurance × Human Authority × Autonomy × Environment × Security × Dependencies**

---

## 5. Risk Baseline

The existing risk position should be established before assessing the change.

This should include:

- identified risks;
- risk ratings;
- controls;
- residual risk;
- assumptions;
- risk acceptance;
- monitoring indicators.

---

## 6. Change Risk Identification

Determine whether the change:

- creates new hazards;
- changes existing hazards;
- alters consequences;
- alters likelihood;
- introduces new failure modes;
- changes uncertainty;
- affects existing controls.

---

## 7. Risk Interaction

A change may affect multiple risk domains simultaneously.

Consider interactions among:

- safety;
- security;
- human factors;
- autonomy;
- environment;
- mission;
- dependencies.

Individual low-impact changes should not conceal combined high-impact effects.

---

## 8. Risk Assumptions

Existing assumptions should be reviewed for continued validity.

An assumption that is invalidated by a change should not remain part of the risk basis.

---

## 9. Residual Risk

Determine whether residual risk after the change remains:

- acceptable;
- conditionally acceptable;
- unacceptable;
- uncertain.

Where uncertainty is material, further evidence should be obtained before unrestricted operation.

---

## 10. Risk Acceptance

Existing risk acceptance should be reassessed where:

- risk increases materially;
- consequences change;
- controls change;
- operating boundaries change;
- assurance confidence decreases.

Risk acceptance should not automatically transfer to a materially changed capability.

---

## 11. Assurance Baseline

The assurance baseline consists of the claims and evidence supporting confidence in the capability.

It should identify:

- assurance claims;
- supporting evidence;
- assumptions;
- limitations;
- confidence;
- applicable configuration.

---

## 12. Assurance Claim Identification

Identify claims affected by the change.

Examples include claims concerning:

- performance;
- robustness;
- reliability;
- security;
- human control;
- autonomy;
- environmental suitability;
- mission effectiveness.

---

## 13. Claim Validity

Each affected claim should be classified as:

- unchanged;
- still supported;
- conditionally supported;
- requiring additional evidence;
- unsupported;
- contradicted.

---

## 14. Evidence Applicability

Existing evidence should be assessed against the changed configuration.

Consider:

- configuration;
- scope;
- conditions;
- test environment;
- data;
- model version;
- dependencies.

---

## 15. Evidence Currency

Evidence may become less relevant as:

- models change;
- data changes;
- threats change;
- environments change;
- dependencies change.

Evidence currency should therefore be considered explicitly.

---

## 16. Evidence Coverage

Determine whether existing evidence still covers:

- expected operating conditions;
- boundary conditions;
- failure modes;
- autonomy states;
- human interactions;
- security conditions.

---

## 17. Evidence Representativeness

Assess whether previous test and operational evidence remains representative of the changed capability.

Where representativeness is uncertain, additional testing may be required.

---

## 18. Control Effectiveness

Determine whether controls remain:

- applicable;
- effective;
- observable;
- enforceable;
- sufficient.

A change may render an existing control ineffective even where the control itself was not modified.

---

## 19. Human-Control Impact

Assess whether the change affects:

- decision authority;
- situational awareness;
- operator workload;
- intervention;
- override;
- escalation;
- training;
- human-AI interaction.

---

## 20. Autonomy Impact

Determine whether the change affects:

- autonomy level;
- autonomy transitions;
- action authority;
- operating boundaries;
- intervention;
- safe-state behaviour.

Changes capable of increasing consequential autonomy require heightened scrutiny.

---

## 21. Environment Impact

Assess whether the change affects the capability's assessed suitability across:

- normal conditions;
- degraded conditions;
- disconnected conditions;
- adversarial conditions;
- sensor conditions;
- communication conditions.

---

## 22. Security Impact

Assess whether the change affects:

- attack surface;
- integrity;
- access;
- interfaces;
- model security;
- data security;
- supply chain;
- monitoring.

---

## 23. Dependency Impact

Assess whether changes to dependencies affect:

- availability;
- integrity;
- continuity;
- resilience;
- fallback;
- interoperability;
- supplier risk.

---

## 24. Mission-Effectiveness Impact

Determine whether the change affects:

- mission success criteria;
- decision quality;
- accuracy;
- reliability;
- timeliness;
- operational suitability.

---

## 25. Uncertainty

Uncertainty should be explicitly recorded.

Where the impact cannot be reliably determined, the organisation should consider:

- additional testing;
- restricted operation;
- enhanced monitoring;
- independent review;
- revalidation.

---

## 26. Assurance Confidence

Post-change confidence may be:

- High;
- Moderate;
- Low;
- Insufficient.

Confidence should reflect the quality and relevance of evidence supporting the changed configuration.

---

## 27. Assurance Debt

A change may create assurance debt when:

- required evidence is incomplete;
- testing is deferred;
- assumptions remain unresolved;
- controls require verification;
- monitoring is inadequate.

Assurance debt should remain visible until resolved or formally accepted.

---

## 28. Change Risk Matrix

A structured assessment may combine:

**Change Significance × Consequence × Uncertainty × Assurance Impact**

The highest credible concern should determine the required governance response.

---

## 29. Mitigation

Where risk or assurance is degraded, mitigation may include:

- additional controls;
- reduced autonomy;
- narrower mission;
- narrower environment;
- additional supervision;
- enhanced monitoring;
- additional testing.

---

## 30. Independent Challenge

Significant or material changes should receive proportionate independent challenge.

Challenge should examine:

- risk assumptions;
- assurance claims;
- evidence;
- controls;
- uncertainty;
- proposed decision.

---

## 31. Assessment Outcomes

Possible outcomes include:

- no material impact;
- proceed with existing assurance;
- proceed with conditions;
- additional assurance required;
- focused revalidation;
- full revalidation;
- reauthorisation;
- restriction;
- suspension.

---

## 32. Revalidation Trigger

Revalidation should be considered when the change affects the evidence supporting material assurance claims.

---

## 33. Reauthorisation Trigger

Reauthorisation should be considered when the change affects the authorised basis, including:

- mission;
- risk acceptance;
- environment;
- autonomy;
- human authority;
- boundaries;
- conditions.

---

## 34. Change Decision

The decision should clearly distinguish:

- technical assessment;
- risk assessment;
- assurance assessment;
- governance judgement;
- operational-authority decision.

---

## 35. Conditions

Where continued operation is permitted, conditions may include:

- restricted functionality;
- reduced autonomy;
- additional supervision;
- environmental restrictions;
- enhanced monitoring;
- defined review date.

---

## 36. Post-Change Assurance

After implementation, assurance should be monitored to determine whether:

- expected behaviour occurs;
- controls remain effective;
- risk remains acceptable;
- confidence is sustained;
- unexpected effects emerge.

---

## 37. Change-Induced Incident

If the change contributes to an incident, the incident process in Module 14 should apply.

The resulting findings should update the change-risk and assurance assessment.

---

## 38. Records

The assessment record should preserve:

- change;
- baseline;
- risks;
- assurance claims;
- evidence;
- uncertainty;
- controls;
- decision;
- authority;
- conditions;
- required follow-up.

---

## 39. Governance Review

Material change assessments should be reviewed periodically or when:

- new evidence emerges;
- risk changes;
- incidents occur;
- monitoring identifies unexpected behaviour;
- assumptions are invalidated.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What risks existed before the change?
2. What risks does the change introduce or modify?
3. Which assumptions changed?
4. Which assurance claims are affected?
5. Which evidence remains valid?
6. Is the evidence representative of the changed configuration?
7. Are controls still effective?
8. Has human control changed?
9. Has autonomy changed?
10. Has environmental suitability changed?
11. Have security or dependencies changed?
12. Has mission effectiveness changed?
13. What uncertainty remains?
14. Is assurance confidence sufficient?
15. Has assurance debt been created?
16. Is revalidation required?
17. Is reauthorisation required?
18. What restrictions or conditions apply?

---

## 41. Core Rule

> **No change should be considered adequately governed until its effect on risk, assurance claims, evidence, controls and operational authority has been explicitly assessed and the resulting decision has been recorded.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Baseline → Change → Risk Impact → Assurance Impact → Evidence Reassessment → Control Assessment → Decision → Revalidation/Reauthorisation → Employment → Monitoring → Learning**
