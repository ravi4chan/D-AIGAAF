# 09-TEVV Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 09 — Testing, Evaluation, Verification & Validation (TEVV)**.

TEVV provides the evidence base for determining whether an AI capability:

- satisfies defined requirements;
- performs its intended mission function;
- remains within authorised boundaries;
- behaves acceptably under relevant conditions;
- is sufficiently robust and reliable;
- remains secure against relevant threats;
- supports meaningful human control;
- performs acceptably at its authorised autonomy level;
- produces evidence sufficient for assurance and operational authorisation.

The central principle is:

> **No consequential AI capability should be treated as assured merely because it works in development or performs well under nominal conditions. Its relevant behaviour must be demonstrated through proportionate, mission-relevant, adversarial and operationally representative TEVV.**

TEVV is therefore not a single test event. It is an evidence-generating process spanning the AI lifecycle.

---

# 2. TEVV Template Set

The recommended TEVV template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-09-001 | TEVV Governance Record |
| D-AIGAAF-T-09-002 | TEVV Strategy & Plan |
| D-AIGAAF-T-09-003 | TEVV Requirements Traceability Record |
| D-AIGAAF-T-09-004 | Test & Evaluation Design Record |
| D-AIGAAF-T-09-005 | Test Scenario & Test Case Record |
| D-AIGAAF-T-09-006 | Operational Environment Trial Record |
| D-AIGAAF-T-09-007 | Performance & Effectiveness Assessment |
| D-AIGAAF-T-09-008 | Reliability & Robustness Assessment |
| D-AIGAAF-T-09-009 | Human-AI Evaluation Record |
| D-AIGAAF-T-09-010 | Autonomy & Control Evaluation |
| D-AIGAAF-T-09-011 | Security & Adversarial Evaluation |
| D-AIGAAF-T-09-012 | Independent Evaluation & Review Record |
| D-AIGAAF-T-09-013 | TEVV Findings & Evidence Record |
| D-AIGAAF-T-09-014 | Operational Acceptance & Readiness Assessment |
| D-AIGAAF-T-09-015 | TEVV Evidence Package & Records Index |

---

# 3. Template 09-001 — TEVV Governance Record

## Purpose

Defines governance, responsibility and independence requirements for TEVV.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- TEVV authority
- Test authority
- Evaluation authority
- Validation authority
- Technical authority
- Operational authority
- Assurance authority
- Independent review authority
- Decision authority
- Required independence
- Review date

## Governance Questions

- Who defines TEVV requirements?
- Who designs the tests?
- Who conducts testing?
- Who evaluates results?
- Who validates mission suitability?
- Who challenges the evidence?
- Who accepts unresolved findings?
- Who determines whether evidence is sufficient for authorisation?

---

# 4. Template 09-002 — TEVV Strategy & Plan

## Purpose

Defines the overall TEVV approach for an AI capability.

## Required Sections

### Capability Scope

- capability;
- mission;
- use case;
- autonomy level;
- operating environment;
- intended users.

### TEVV Objectives

- requirement verification;
- technical evaluation;
- operational evaluation;
- security evaluation;
- human-AI evaluation;
- autonomy evaluation;
- mission effectiveness;
- robustness;
- reliability.

### Conditions

Define:

- normal;
- degraded;
- disconnected;
- adversarial;
- edge;
- stress;
- failure;
- recovery conditions.

### Evidence

Define:

- required evidence;
- evidence source;
- acceptance criteria;
- confidence requirements;
- independence requirements.

---

# 5. Template 09-003 — TEVV Requirements Traceability Record

## Purpose

Creates traceability between requirements and TEVV evidence.

## Traceability Chain

**Mission Need**
→ **Requirement**
→ **Control**
→ **Test**
→ **Result**
→ **Finding**
→ **Evidence**
→ **Assurance**
→ **Authorisation**

## Required Fields

- Requirement ID
- Requirement
- Source
- Criticality
- Test method
- Test ID
- Result
- Evidence
- Finding
- Acceptance criterion
- Status
- Owner

Every material requirement should have a defined method for determining whether it has been adequately demonstrated.

---

# 6. Template 09-004 — Test & Evaluation Design Record

## Purpose

Defines the design of an individual TEVV activity.

## Required Fields

- Test ID
- Objective
- Requirement
- Hypothesis
- Capability configuration
- Model version
- Data version
- Environment
- Inputs
- Expected behaviour
- Failure criteria
- Acceptance criteria
- Metrics
- Test method
- Test personnel
- Independence
- Safety controls
- Evidence requirements

The test design should be appropriate to the consequence of failure.

---

# 7. Template 09-005 — Test Scenario & Test Case Record

## Purpose

Defines repeatable test scenarios and cases.

## Scenario Categories

Consider:

- nominal;
- boundary;
- edge;
- rare;
- degraded;
- adversarial;
- ambiguous;
- incomplete information;
- conflicting information;
- unexpected input;
- system failure;
- human intervention;
- recovery.

## Required Fields

- Scenario ID
- Mission
- Environment
- Initial conditions
- Input
- AI function
- Human role
- Expected result
- Failure condition
- Intervention
- Outcome
- Evidence

---

# 8. Template 09-006 — Operational Environment Trial Record

## Purpose

Records testing in operationally representative environments.

## Environment Factors

Consider:

- terrain;
- weather;
- electromagnetic conditions;
- communications;
- network availability;
- sensor quality;
- data availability;
- adversarial activity;
- mission tempo;
- human workload;
- infrastructure;
- environmental uncertainty.

## Required Fields

- Trial ID
- Environment
- Configuration
- Conditions
- Scenario
- Participants
- Results
- Deviations
- Limitations
- Findings
- Evidence
- Acceptance

A capability demonstrated in a laboratory may not be demonstrated for its intended operational environment.

---

# 9. Template 09-007 — Performance & Effectiveness Assessment

## Purpose

Determines whether the AI capability achieves the required mission effect.

## Metrics

Metrics may include:

- accuracy;
- precision;
- recall;
- false positive rate;
- false negative rate;
- latency;
- availability;
- mission success;
- operator workload;
- intervention success;
- resource consumption.

Metrics should be selected according to mission consequence rather than convenience.

## Required Fields

- Metric
- Target
- Test result
- Confidence
- Operational relevance
- Threshold
- Finding
- Acceptance

High aggregate accuracy does not establish safety where rare high-consequence failures dominate risk.

---

# 10. Template 09-008 — Reliability & Robustness Assessment

## Purpose

Evaluates whether capability behaviour remains acceptable under variation and stress.

## Assessment Areas

- input variation;
- environmental variation;
- data quality;
- sensor degradation;
- distribution shift;
- edge cases;
- repeated operation;
- hardware variation;
- software faults;
- resource constraints;
- communication degradation.

## Required Fields

- Condition
- Expected behaviour
- Observed behaviour
- Failure rate
- Severity
- Recovery
- Control
- Residual risk
- Evidence

---

# 11. Template 09-009 — Human-AI Evaluation Record

## Purpose

Evaluates whether humans can use and govern the AI effectively.

## Assessment Areas

- comprehension;
- trust calibration;
- uncertainty interpretation;
- automation bias;
- workload;
- decision quality;
- intervention;
- override;
- response time;
- situational awareness;
- error recovery.

## Required Fields

- Human role
- Scenario
- AI output
- Human interpretation
- Human decision
- Response time
- Intervention
- Error
- Outcome
- Finding
- Evidence

Human-AI evaluation should examine actual behaviour, not simply whether an interface exists.

---

# 12. Template 09-010 — Autonomy & Control Evaluation

## Purpose

Determines whether AI behaviour remains within the authorised autonomy level.

## Assessment Areas

- autonomy classification;
- action authority;
- transition conditions;
- boundary adherence;
- constraint enforcement;
- human supervision;
- intervention;
- override;
- safe-state transition;
- unexpected autonomy.

## Required Fields

- Autonomy level
- Function
- Authorised behaviour
- Test condition
- Observed behaviour
- Boundary
- Deviation
- Consequence
- Control
- Evidence
- Finding

## Critical Question

> **Did the AI remain within the authority and behavioural boundaries explicitly authorised for the mission and environment?**

---

# 13. Template 09-011 — Security & Adversarial Evaluation

## Purpose

Evaluates resilience against relevant AI and conventional security threats.

## Threat Categories

Consider:

- adversarial inputs;
- data poisoning;
- model manipulation;
- prompt injection;
- instruction manipulation;
- tool abuse;
- retrieval manipulation;
- model extraction;
- supply-chain compromise;
- malicious updates;
- cyber attack;
- denial of service;
- sensor manipulation;
- spoofing.

## Required Fields

- Threat
- Attack method
- Target
- Preconditions
- Expected behaviour
- Observed behaviour
- Detection
- Mitigation
- Residual risk
- Evidence

Adversarial evaluation should reflect realistic threat capability and operational context.

---

# 14. Template 09-012 — Independent Evaluation & Review Record

## Purpose

Records independent challenge of TEVV evidence.

## Required Fields

- Review ID
- Capability
- Evidence reviewed
- Reviewer
- Independence basis
- Scope
- Findings
- Evidence limitations
- Confidence
- Recommendations
- Decision
- Follow-up

Independence should be proportionate to consequence and the importance of the decision supported by the evidence.

---

# 15. Template 09-013 — TEVV Findings & Evidence Record

## Purpose

Consolidates findings and supporting evidence from TEVV activities.

## Finding Categories

- pass;
- fail;
- partial;
- inconclusive;
- limitation;
- anomaly;
- nonconformity;
- evidence gap.

## Required Fields

- Finding ID
- Source test
- Requirement
- Finding
- Severity
- Evidence
- Confidence
- Impact
- Corrective action
- Owner
- Due date
- Verification
- Closure status

An inconclusive result should not automatically be treated as a pass.

---

# 16. Template 09-014 — Operational Acceptance & Readiness Assessment

## Purpose

Determines whether the AI capability has sufficient TEVV evidence to support the intended operational decision.

## Assessment Areas

- requirements;
- performance;
- robustness;
- reliability;
- security;
- human control;
- autonomy;
- environment;
- mission effectiveness;
- residual risk;
- evidence sufficiency.

## Required Fields

- Capability
- Mission
- Intended operating conditions
- TEVV status
- Open findings
- Evidence confidence
- Limitations
- Residual risk
- Conditions
- Recommendation
- Acceptance authority

### Important Distinction

**TEVV readiness ≠ operational authorisation.**

TEVV provides evidence. The appropriate authority decides whether that evidence supports authorisation.

---

# 17. Template 09-015 — TEVV Evidence Package & Records Index

## Purpose

Provides an authoritative index of TEVV evidence.

## Required Fields

- Evidence ID
- Test ID
- Requirement
- Evidence type
- Source
- Version
- Date
- Configuration
- Environment
- Integrity
- Owner
- Location
- Confidence
- Retention
- Authorisation relevance

The evidence package should permit reconstruction of what was tested, under which configuration and conditions, with what result.

---

# 18. TEVV Configuration Integrity

Every material TEVV activity should identify the configuration under test.

Record, where applicable:

- model version;
- model weights/version identifier;
- software version;
- firmware;
- hardware;
- dataset;
- prompts/instructions;
- system configuration;
- security controls;
- connected tools;
- external services;
- operating environment.

The governing principle is:

> **Evidence applies to what was actually tested, not merely to what was intended to be deployed.**

---

# 19. TEVV and the Operational Environment

Testing should be representative of the environment in which the capability is expected to operate.

A capability intended for:

- conventional operations;
- counter-insurgency;
- drone warfare;
- border operations;
- urban operations;
- contested electromagnetic environments;
- disconnected operations;

should not rely exclusively on benign laboratory testing.

Environmental realism should increase with mission consequence.

---

# 20. TEVV Under Degraded and Disconnected Conditions

Where operational use may occur without reliable communications or network connectivity, TEVV should examine:

- local processing;
- loss of external services;
- stale data;
- missing data;
- communication loss;
- delayed synchronisation;
- degraded sensors;
- manual fallback;
- autonomy transition;
- safe state;
- human intervention.

The question is not merely:

> Does the system work when connected?

It is:

> **Does the capability remain within authorised behaviour when the conditions assumed by its design are no longer available?**

---

# 21. TEVV and Uncertainty

TEVV should assess whether uncertainty is:

- measured;
- communicated;
- appropriately calibrated;
- understandable to the intended user;
- incorporated into decisions.

A system that produces accurate outputs but systematically communicates unjustified confidence may create unacceptable operational risk.

---

# 22. TEVV and Rare High-Consequence Failures

Average performance can conceal dangerous failure modes.

TEVV should therefore consider:

- tail risks;
- rare events;
- worst credible cases;
- cascading failures;
- correlated failures;
- adversarial cases;
- unexpected combinations of conditions.

For consequential capabilities:

> **The absence of observed failure is not equivalent to evidence that failure cannot occur.**

---

# 23. TEVV and Autonomy

Testing should evaluate transitions between autonomy states.

For example:

**A2**
→ **A3**
→ **A4**
→ **Safe State**

Test:

- entry conditions;
- exit conditions;
- authorisation;
- boundary enforcement;
- human awareness;
- intervention;
- transition timing;
- failure behaviour.

Autonomy must be demonstrated within the specific mission and environment for which it is authorised.

---

# 24. TEVV and Human Authority

TEVV should test whether designated personnel can actually exercise their authority.

This includes:

- receiving the relevant information;
- understanding AI uncertainty;
- recognising failure;
- rejecting recommendations;
- intervening;
- overriding;
- terminating;
- escalating;
- operating under time pressure.

A technically correct AI system can still create unacceptable risk if the human control mechanism fails.

---

# 25. TEVV Evidence Hierarchy

Evidence should be assessed according to relevance and strength.

A useful hierarchy is:

**Documented Claim**
→ **Supplier Evidence**
→ **Laboratory Test**
→ **Representative Test**
→ **Operational Trial**
→ **Adversarial Evaluation**
→ **Independent Evaluation**
→ **Operational Evidence**

No single evidence type is sufficient for every decision.

Evidence strength should be judged against:

- consequence;
- uncertainty;
- autonomy;
- environmental variability;
- adversarial exposure;
- decision significance.

---

# 26. TEVV Finding Disposition

Findings should be classified and handled explicitly.

Possible dispositions:

- accepted;
- corrected;
- mitigated;
- constrained;
- deferred;
- escalated;
- requires additional testing;
- requires revalidation;
- requires reauthorisation;
- capability rejected.

A finding should not be closed merely because the planned test has ended.

---

# 27. TEVV and Operational Authorisation

The relationship is:

**Requirements**
→ **TEVV**
→ **Evidence**
→ **Findings**
→ **Assurance**
→ **Risk Decision**
→ **Operational Authorisation**

TEVV does not itself grant operational authority.

Likewise:

> **Operational authorisation should not be granted on the basis of undocumented claims where proportionate TEVV evidence is reasonably required.**

---

# 28. TEVV Repetition and Revalidation

Testing should be repeated when material changes occur to:

- model;
- data;
- software;
- hardware;
- security controls;
- operating environment;
- mission;
- autonomy;
- human role;
- supplier dependency;
- operational constraints.

The extent of repeated testing should be based on change impact.

---

# 29. TEVV Evidence for Continuous Assurance

TEVV does not end at initial deployment.

Operational monitoring may generate evidence requiring:

- additional testing;
- regression testing;
- targeted adversarial testing;
- human-AI reassessment;
- environment testing;
- model evaluation;
- revalidation.

This creates a continuous loop:

**Operate**
→ **Monitor**
→ **Detect Change**
→ **Evaluate**
→ **Test**
→ **Revalidate**
→ **Reauthorise if Required**

---

# 30. Anti-Pattern — Benchmark Equals Assurance

D-AIGAAF rejects:

**High Benchmark Score**
→ **System Assured**
→ **Operationally Safe**

Benchmarks can provide useful evidence, but they may not capture:

- mission context;
- rare failures;
- adversarial conditions;
- operational environment;
- human behaviour;
- autonomy;
- system integration;
- security;
- supply-chain dependencies.

Benchmark performance should therefore be treated as one evidence component.

---

# 31. Anti-Pattern — Pass/Fail Without Context

A TEVV result should not be interpreted without knowing:

- what was tested;
- under which configuration;
- under which conditions;
- with which data;
- against which requirement;
- with what uncertainty;
- using which acceptance threshold.

A result without context can create false confidence.

---

# 32. Anti-Pattern — Testing the Model but Not the System

D-AIGAAF evaluates the operational capability, not only the underlying model.

The test scope may need to include:

**Data**
→ **Model**
→ **Software**
→ **Hardware**
→ **Sensors**
→ **Interfaces**
→ **Human**
→ **Network**
→ **Tools**
→ **Mission**
→ **Operational Environment**

System-level behaviour may differ materially from isolated model performance.

---

# 33. Final TEVV Principle

TEVV is the evidence engine connecting technical development to operational assurance.

The complete TEVV chain is:

**Requirement**
→ **Test Objective**
→ **Scenario**
→ **Configuration**
→ **Environment**
→ **Execution**
→ **Observation**
→ **Result**
→ **Finding**
→ **Evidence**
→ **Evaluation**
→ **Assurance**
→ **Authorisation**
→ **Operational Monitoring**
→ **Revalidation**

The governing principle is:

> **A consequential AI capability should be considered adequately evaluated only when evidence demonstrates, with appropriate confidence and independence, that the capability performs its intended function and remains within its authorised behavioural, security, autonomy and human-control boundaries under relevant operational conditions.**
