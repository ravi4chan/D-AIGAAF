# 04 — Change TEVV & Verification

## 1. Purpose

This document defines how changes to Defence AI capabilities are tested, evaluated, verified and validated before and after implementation.

The objective is to establish evidence that the changed capability continues to satisfy applicable requirements, controls, assurance claims and authorised conditions.

---

## 2. Core Principle

> **Testing after change shall be proportionate to the potential effect of the change and shall provide evidence relevant to the configuration, mission, environment, autonomy and human-authority conditions under which the capability is intended to operate.**

---

## 3. Scope

Change-related TEVV may apply to:

- models;
- data;
- software;
- hardware;
- configuration;
- interfaces;
- sensors;
- communications;
- dependencies;
- security controls;
- autonomy;
- human-AI interaction;
- operational procedures.

---

## 4. TEVV Object

The changed capability should be evaluated against:

**Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions × Dependencies**

---

## 5. TEVV Planning

Before implementation or operational use, the organisation should determine:

- what changed;
- what could be affected;
- which claims require evidence;
- which tests are required;
- acceptance criteria;
- required independence;
- required operational conditions.

---

## 6. Test Scope

Testing should be based on change impact rather than change size.

Potential scope includes:

- functional testing;
- performance testing;
- robustness testing;
- safety testing;
- security testing;
- human-AI testing;
- autonomy testing;
- environmental testing;
- integration testing;
- regression testing.

---

## 7. Requirements Traceability

Tests should trace to relevant:

- requirements;
- risks;
- controls;
- assurance claims;
- acceptance criteria.

This preserves the Golden Thread between change and evidence.

---

## 8. Configuration Control

The configuration tested must be uniquely identified.

Records should include, as applicable:

- model version;
- software version;
- hardware;
- data;
- parameters;
- interfaces;
- dependencies.

---

## 9. Baseline Testing

Where practical, the previous authorised baseline should provide a comparison point.

Comparison may identify:

- performance change;
- behavioural change;
- new failure modes;
- improved capability;
- degraded capability;
- changed uncertainty.

---

## 10. Functional Verification

Verification should establish that the changed functionality:

- operates as intended;
- satisfies specified requirements;
- does not introduce unintended functions;
- remains within authorised boundaries.

---

## 11. Performance Evaluation

Performance should be assessed against relevant:

- thresholds;
- benchmarks;
- mission criteria;
- uncertainty measures;
- operating conditions.

Performance improvements should not be assumed to imply unchanged risk.

---

## 12. Regression Testing

Regression testing should determine whether existing functionality or controls have been adversely affected.

Regression scope should reflect:

- change dependencies;
- criticality;
- interaction effects;
- prior failure modes.

---

## 13. Safety Evaluation

Where relevant, evaluate whether the change affects:

- hazards;
- safety controls;
- fail-safe behaviour;
- safe-state transitions;
- human intervention;
- consequences of failure.

---

## 14. Security Evaluation

Security TEVV may include assessment of:

- attack surface;
- integrity;
- interfaces;
- authentication;
- access controls;
- model security;
- data security;
- dependencies;
- adversarial behaviour.

---

## 15. Human-AI Evaluation

Where human interaction changes, assess:

- comprehension;
- situational awareness;
- workload;
- decision quality;
- automation bias;
- intervention;
- override;
- timing.

---

## 16. Autonomy Evaluation

Where autonomy changes, assess:

- authorised autonomy level;
- transitions;
- boundary compliance;
- autonomous behaviour;
- intervention;
- override;
- safe-state behaviour.

Any increase in consequential autonomy should receive appropriate testing before operational use.

---

## 17. Environmental Evaluation

Where environmental applicability may change, test relevant:

- normal conditions;
- boundary conditions;
- degraded conditions;
- disconnected conditions;
- adversarial conditions;
- sensor conditions;
- communications conditions.

---

## 18. Integration Testing

Changes should be evaluated within the relevant system context where interactions may affect behaviour.

Integration testing may include:

- interfaces;
- sensors;
- communications;
- human interfaces;
- other AI systems;
- external dependencies.

---

## 19. Dependency Testing

Where dependencies change, evaluate:

- failure behaviour;
- availability;
- integrity;
- fallback;
- continuity;
- interoperability.

---

## 20. Boundary Testing

Testing should include relevant operational boundaries.

This may identify:

- performance degradation;
- unsafe transitions;
- unexpected autonomy;
- control failure;
- environmental limitations.

---

## 21. Adversarial Testing

Where appropriate, evaluate changed capability against credible adversarial conditions.

Testing may address:

- manipulated inputs;
- abnormal inputs;
- sensor deception;
- data integrity issues;
- interface manipulation;
- model-targeted attacks.

Testing should remain appropriate to the risk and authorised scope.

---

## 22. Uncertainty Evaluation

Testing should assess whether the change affects:

- confidence;
- uncertainty estimates;
- calibration;
- detection of insufficient information;
- communication of limitations.

A changed capability should not conceal increased uncertainty.

---

## 23. Failure and Recovery Testing

Where relevant, evaluate:

- failure detection;
- intervention;
- autonomy reduction;
- safe state;
- recovery;
- rollback;
- restoration.

---

## 24. Human-Control Verification

Verification should establish that authorised personnel can practically:

- understand relevant outputs;
- supervise the system;
- intervene;
- override;
- reduce autonomy;
- suspend operation.

---

## 25. Evidence Quality

Change-related evidence should be assessed for:

- relevance;
- integrity;
- accuracy;
- completeness;
- representativeness;
- reproducibility;
- independence;
- currency.

---

## 26. Test Results

Results should identify:

- test objective;
- configuration;
- conditions;
- method;
- expected result;
- observed result;
- deviations;
- uncertainty;
- conclusion.

---

## 27. Findings

Findings may be classified as:

- conforming;
- observation;
- minor;
- significant;
- critical.

Findings affecting safety, human control, autonomy, security or authorised boundaries should receive appropriate escalation.

---

## 28. Failed Tests

A failed test should not be concealed by aggregate results.

The organisation should determine:

- cause;
- consequence;
- affected claims;
- risk;
- required corrective action;
- retest requirements.

---

## 29. Contradictory Evidence

Evidence that contradicts an existing assurance claim should be explicitly recorded.

Contradictory evidence may require:

- additional testing;
- assurance reassessment;
- restriction;
- revalidation;
- reauthorisation.

---

## 30. Test Independence

Testing independence should be proportionate to:

- consequence;
- change significance;
- autonomy;
- uncertainty;
- security;
- systemic significance.

---

## 31. Operationally Relevant Testing

Laboratory results should not automatically substitute for operational evidence where behaviour depends on:

- environment;
- human interaction;
- communications;
- sensors;
- adversarial conditions;
- mission context.

---

## 32. Acceptance Criteria

Acceptance criteria should be defined before final evaluation where practical.

They should address:

- requirements;
- risk;
- controls;
- assurance claims;
- operational conditions.

---

## 33. TEVV Decision

The TEVV conclusion may be:

- verified;
- verified with conditions;
- partially verified;
- insufficiently verified;
- not verified.

---

## 34. Revalidation Decision

Where existing assurance is affected, the TEVV results should inform the revalidation decision.

TEVV demonstrates evidence; it does not itself grant operational authority.

---

## 35. Reauthorisation Decision

Where the changed basis affects operational authority, TEVV evidence should be provided to the relevant authorisation process.

Reauthorisation remains a governance decision.

---

## 36. Post-Deployment Verification

Where appropriate, verification should continue after operational entry to determine whether real-world behaviour remains consistent with test evidence.

---

## 37. Enhanced Monitoring

Changes with residual uncertainty may require:

- enhanced monitoring;
- additional review;
- restricted employment;
- shorter review intervals;
- defined escalation thresholds.

---

## 38. Change-Related Incidents

If testing or operational use reveals an incident, the incident process defined in Module 14 should apply.

The findings should feed back into change governance.

---

## 39. TEVV Records

Records should preserve:

- test plan;
- configuration;
- data;
- methods;
- results;
- evidence;
- findings;
- approvals;
- deviations;
- conclusions.

---

## 40. Governance Questions

The organisation should be able to answer:

1. What changed?
2. What could the change affect?
3. Which requirements require testing?
4. Which assurance claims require evidence?
5. What configuration was tested?
6. Was regression testing required?
7. Were human-control effects assessed?
8. Were autonomy effects assessed?
9. Were environmental effects assessed?
10. Were security effects assessed?
11. Were dependencies assessed?
12. Were relevant boundaries tested?
13. What uncertainty remains?
14. Were contradictory results identified?
15. Is additional revalidation required?
16. Is reauthorisation required?
17. What post-change monitoring is required?

---

## 41. Core Rule

> **A changed Defence AI capability shall not be treated as adequately verified merely because the modification has been technically implemented. The organisation shall establish evidence appropriate to the change and its potential operational consequences.**

---

## 42. Golden Thread

**Mission Need → Risk → Requirements → Controls → Authorised Baseline → Change → Impact Assessment → TEVV Planning → Testing → Evidence → Findings → Verification → Assurance → Revalidation → Reauthorisation → Operational Employment → Monitoring → Learning**
