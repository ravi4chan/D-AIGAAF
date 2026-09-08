# 01 — Assurance Evidence and Confidence

## 1. Purpose

This document defines how D-AIGAAF establishes, evaluates, maintains and communicates evidence-based confidence in a Defence AI capability throughout its operational lifecycle.

The purpose is to ensure that assurance conclusions are supported by relevant, sufficient, traceable and appropriately current evidence rather than by assumptions, technical availability or historical test results alone.

---

## 2. Core Principle

> **Assurance confidence shall be based on evidence that is relevant to the capability, mission, environment, autonomy, human authority and conditions of use. Evidence shall be sufficient, traceable and appropriately current for the assurance claim it supports, and material uncertainty or evidence gaps shall remain visible to the responsible authority.**

---

## 3. Assurance Claim

An assurance claim is a documented statement about a condition that the organisation needs reasonable confidence to accept.

Examples include:

- the capability performs its intended function;
- the capability remains within defined performance limits;
- AI outputs are sufficiently reliable for their authorised purpose;
- uncertainty is appropriately communicated;
- human control remains effective;
- autonomy remains within authorised limits;
- security controls remain effective;
- the capability remains suitable for its operating environment.

---

## 4. Claim Hierarchy

Assurance claims may be structured as:

**Top-Level Assurance Claim → Domain Claims → Sub-Claims → Evidence**

For example:

**Top-Level Claim:** The capability remains suitable for authorised employment.

Possible domain claims:

- Mission suitability;
- Technical performance;
- Human-control effectiveness;
- Autonomy assurance;
- Environmental suitability;
- Security assurance;
- Dependency assurance.

---

## 5. Evidence Categories

Evidence may include:

1. requirements evidence;
2. design evidence;
3. development evidence;
4. acquisition evidence;
5. data evidence;
6. TEVV evidence;
7. security evidence;
8. operational monitoring;
9. operational records;
10. incident evidence;
11. human-factors evidence;
12. environmental evidence;
13. audit evidence;
14. lessons learned.

Different evidence types provide different levels of confidence.

---

## 6. Direct and Indirect Evidence

### Direct Evidence

Evidence that directly demonstrates the relevant claim under representative conditions.

### Indirect Evidence

Evidence that supports the claim through related observations but does not directly demonstrate it.

Indirect evidence may be useful but should not automatically be treated as equivalent to direct demonstration.

---

## 7. Evidence Status

D-AIGAAF may classify evidence as:

### Demonstrated

The evidence directly supports the claim under relevant conditions.

### Partially Demonstrated

The claim is supported under some but not all relevant conditions.

### Indirectly Supported

Related evidence provides support, but direct demonstration is limited.

### Untested

Insufficient evidence exists.

### Contradicted

Available evidence indicates that the claim may not remain valid.

---

## 8. Evidence Relevance

Evidence should be evaluated against the conditions under which it is being used.

Consider:

- mission;
- environment;
- autonomy;
- human authority;
- configuration;
- data;
- threat;
- dependencies;
- consequence.

Evidence from a materially different context may have limited applicability.

---

## 9. Evidence Sufficiency

Evidence sufficiency should consider:

- quantity;
- quality;
- coverage;
- representativeness;
- independence;
- consistency;
- reproducibility;
- traceability;
- uncertainty.

More evidence does not automatically mean stronger assurance.

---

## 10. Evidence Quality

Evidence should be assessed for:

- accuracy;
- reliability;
- integrity;
- provenance;
- methodological soundness;
- reproducibility;
- completeness;
- independence where required.

Evidence of uncertain quality should be clearly identified.

---

## 11. Evidence Coverage

Assurance evidence should cover relevant:

- operating conditions;
- use cases;
- failure modes;
- autonomy states;
- human interactions;
- environmental conditions;
- threat conditions;
- dependencies.

Uncovered areas should be visible as assurance gaps.

---

## 12. Representative Evidence

Evidence should be sufficiently representative of the conditions in which the capability may be employed.

Representation may concern:

- data;
- terrain;
- weather;
- sensors;
- users;
- mission conditions;
- adversarial conditions;
- degraded conditions.

A capability demonstrated only under ideal conditions may have limited operational assurance.

---

## 13. Evidence Currency

Evidence should be reviewed for continuing relevance following:

- model updates;
- software changes;
- hardware changes;
- data changes;
- environmental changes;
- threat changes;
- mission changes;
- autonomy changes;
- dependency changes;
- significant operational experience.

---

## 14. Evidence Age

The age of evidence should be considered relative to the rate at which the underlying capability or environment changes.

Older evidence may remain valid where the relevant conditions are stable.

The organisation should avoid treating evidence as either automatically valid or automatically expired solely because of elapsed time.

---

## 15. Evidence Traceability

Material evidence should be traceable to:

**Requirement → Risk → Control → Test/Evaluation → Evidence → Assurance Claim**

Where applicable, operational evidence should also trace through:

**Employment → Monitoring → Observation → Evidence → Assurance**

---

## 16. Evidence Independence

For consequential assurance claims, evidence should be independently generated or independently reviewed where appropriate.

Independence should be proportionate to:

- consequence;
- conflict-of-interest risk;
- complexity;
- organisational structure;
- assurance criticality.

---

## 17. Conflicting Evidence

Where evidence conflicts, the organisation should not simply select the most favourable result.

It should assess:

- evidence quality;
- methodology;
- conditions;
- statistical significance where relevant;
- operational relevance;
- possible failure modes.

The unresolved conflict should remain visible until appropriately resolved.

---

## 18. Negative Evidence

Evidence demonstrating failure, degradation or unexpected behaviour is important assurance evidence.

Examples include:

- failed tests;
- incidents;
- false positives;
- false negatives;
- intervention events;
- autonomy anomalies;
- environmental excursions;
- security failures.

Negative evidence should not be excluded merely because it reduces confidence.

---

## 19. Operational Evidence

Operational evidence may include:

- observed performance;
- user feedback;
- intervention frequency;
- anomaly frequency;
- environmental observations;
- mission outcomes;
- security events;
- system failures.

Operational evidence should be interpreted with appropriate context and controls.

---

## 20. Evidence from Incidents

Incident evidence should be assessed for its effect on assurance claims.

A single event may indicate:

- isolated failure;
- control failure;
- evidence gap;
- systemic weakness;
- changed operating conditions;
- invalid assurance assumption.

---

## 21. Evidence from Human Interaction

Where humans materially interact with AI, evidence should address:

- comprehension;
- workload;
- reliance;
- automation bias;
- intervention;
- override;
- disagreement;
- decision quality.

Technical performance alone does not establish human-control assurance.

---

## 22. Evidence from Autonomous Behaviour

Where autonomy is authorised, evidence should address:

- actual autonomy;
- expected autonomy;
- autonomy transitions;
- boundary adherence;
- intervention;
- failure behaviour;
- safe-state behaviour.

Evidence should establish whether autonomous behaviour remains within the demonstrated and authorised envelope.

---

## 23. Evidence under Degraded Conditions

Where degraded or disconnected employment is authorised, evidence should address relevant:

- communications loss;
- sensor degradation;
- data degradation;
- navigation uncertainty;
- computing limitations;
- dependency failure;
- human-control limitations.

Assurance should not assume that normal-condition evidence automatically applies.

---

## 24. Evidence under Adversarial Conditions

Where relevant, assurance evidence should address:

- adversarial inputs;
- data manipulation;
- sensor deception;
- model attacks;
- interface manipulation;
- security compromise;
- malicious dependencies.

The level of adversarial evidence should reflect consequence and threat.

---

## 25. Evidence and Uncertainty

Every significant assurance conclusion should identify material uncertainty.

Uncertainty may arise from:

- limited evidence;
- changing conditions;
- incomplete testing;
- conflicting results;
- unknown failure modes;
- insufficient operational experience.

Uncertainty should reduce unwarranted confidence rather than being hidden within an aggregate score.

---

## 26. Confidence

Assurance confidence represents the degree to which available evidence supports an assurance claim.

A useful qualitative scale is:

### High Confidence

Evidence is strong, relevant, current and sufficiently representative.

### Moderate Confidence

Evidence is generally supportive but has material limitations.

### Low Confidence

Evidence is limited, indirect, outdated or materially uncertain.

### Insufficient Confidence

Evidence does not support continued reliance on the claim.

---

## 27. Confidence versus Correctness

High assurance confidence does not guarantee that the underlying claim is objectively true.

Confidence reflects the strength of available evidence and assurance reasoning.

The organisation should therefore distinguish:

**Confidence in Evidence ≠ Certainty of Outcome**

---

## 28. Confidence versus Risk

Assurance confidence and risk acceptance are related but distinct.

A high-risk capability may require stronger evidence and greater assurance confidence.

Low assurance confidence should not be concealed by formally accepting high residual risk.

---

## 29. Confidence versus Authorisation

Assurance confidence does not create operational authority.

The distinction remains:

**Assured ≠ Authorised**

Authorisation is a governance decision based on assurance, risk, authority, mission, environment and applicable conditions.

---

## 30. Assurance Evidence Gaps

An evidence gap exists where required evidence is:

- absent;
- insufficient;
- outdated;
- non-representative;
- conflicting;
- unverifiable.

Evidence gaps should have:

- owner;
- significance;
- treatment;
- target resolution;
- responsible authority.

---

## 31. Assurance Debt

Assurance debt represents unresolved evidence or assurance limitations that remain while a capability continues under defined conditions.

Examples include:

- incomplete testing;
- ageing evidence;
- limited environmental coverage;
- unresolved anomalies;
- pending independent review.

Assurance debt should be visible to decision-makers.

---

## 32. Compensating Controls

Where evidence is incomplete but continued restricted use is justified, compensating controls may include:

- increased human review;
- reduced autonomy;
- restricted mission scope;
- restricted environment;
- increased monitoring;
- additional operator competence;
- additional testing.

Compensating controls should not permanently substitute for required assurance evidence where stronger evidence is reasonably necessary.

---

## 33. Evidence Escalation

Material evidence concerns should be escalated when they indicate:

- reduced confidence;
- invalidated assumptions;
- control failure;
- new risk;
- unexpected behaviour;
- material performance change.

Escalation should follow defined governance authority.

---

## 34. Assurance Confidence Assessment

An assurance assessment should consider:

**Evidence Strength + Evidence Relevance + Evidence Currency + Evidence Coverage + Evidence Independence + Uncertainty**

No single factor should automatically determine the conclusion.

---

## 35. Evidence Review

Evidence should be reviewed when:

- assurance triggers occur;
- significant incidents occur;
- material changes occur;
- evidence becomes questionable;
- operational experience contradicts assumptions;
- revalidation is initiated;
- reauthorisation is considered.

---

## 36. Assurance Package

For consequential capabilities, an assurance package may contain:

- assurance claims;
- requirements;
- risks;
- controls;
- TEVV evidence;
- operational evidence;
- environmental evidence;
- human-control evidence;
- security evidence;
- incidents;
- limitations;
- uncertainty;
- outstanding gaps;
- assurance conclusion.

---

## 37. Assurance Statement

The responsible authority should be able to state:

- what is being assured;
- under what conditions;
- based on what evidence;
- with what limitations;
- with what residual uncertainty;
- for how long the conclusion remains applicable;
- what would invalidate the conclusion.

---

## 38. Evidence Review Outcomes

Possible outcomes include:

- confidence maintained;
- confidence maintained with conditions;
- additional evidence required;
- additional monitoring required;
- additional controls required;
- revalidation required;
- reauthorisation required;
- employment restricted;
- employment suspended.

---

## 39. Evidence Records

Evidence records should identify where appropriate:

- evidence ID;
- claim supported;
- source;
- date;
- conditions;
- configuration;
- methodology;
- result;
- limitations;
- reviewer;
- status;
- retention requirement.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What assurance claims require evidence?
2. What evidence supports each claim?
3. Is the evidence direct or indirect?
4. Is the evidence representative?
5. Is it current?
6. Are there conflicting results?
7. Are negative findings included?
8. What material evidence gaps exist?
9. What assurance debt remains?
10. What uncertainty remains?
11. Who reviewed the evidence?
12. Is independent challenge required?
13. What conditions limit the conclusion?
14. What events would invalidate the assurance claim?
15. When must the evidence be reassessed?

---

## 41. Core Rule

> **Assurance confidence shall reflect the strength, relevance, currency, coverage, independence and limitations of available evidence. Material gaps, conflicts, negative findings and uncertainty shall remain visible and shall not be obscured by aggregate assurance ratings. Where evidence no longer supports an assurance claim, continued operational use shall be reconsidered through proportionate controls, restriction, revalidation, reauthorisation or suspension.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance Claim → Confidence → Authority → Conditions → Boundaries → Employment → Monitoring → Operational Evidence → Assurance Review → Action → Verification → Revalidation/Reauthorisation**
