# D-AIGAAF — TEVV Evidence, Findings & Assurance

## 1. Purpose

This document defines how evidence generated through Testing, Evaluation, Verification and Validation (TEVV) is collected, assessed, recorded and translated into an assurance conclusion.

The objective is to ensure that operational decisions are based on sufficient, relevant, traceable and credible evidence.

## 2. Core Principle

> **A test result is evidence; assurance is the justified conclusion drawn from the totality of relevant evidence.**

Passing individual tests does not automatically establish that a Defence AI capability is safe, secure, effective or suitable for operational employment.

## 3. Evidence Requirements

TEVV evidence should be:

- Relevant to the intended use.
- Sufficient for the risk and consequence level.
- Traceable to requirements and test objectives.
- Reproducible where practicable.
- Credible and appropriately independent.
- Representative of intended operating conditions.
- Current for the assessed system baseline.
- Protected against unauthorised alteration.

## 4. Evidence Categories

Evidence may include:

- Test results.
- Evaluation reports.
- Verification records.
- Validation results.
- Simulation results.
- Operational trial results.
- Security assessments.
- Adversarial testing.
- Human-AI interaction assessments.
- Reliability and robustness measurements.
- Configuration records.
- Data quality and provenance records.
- Incident and failure records.
- Expert assessments.
- User feedback.

Different evidence types should be considered together rather than in isolation.

## 5. Traceability

Each significant finding should be traceable through the assurance chain:

**Requirement → Risk → Control → Test/Evaluation → Result → Finding → Assurance Conclusion**

Traceability should also connect evidence to the applicable:

- AI capability.
- Version/baseline.
- Configuration.
- Mission.
- Environment.
- Autonomy level.
- Test conditions.
- Date of assessment.

## 6. Evidence Quality

Evidence quality should consider:

### Relevance
Does the evidence address the actual requirement, risk or operational question?

### Adequacy
Is there enough evidence to support the conclusion?

### Reliability
Can the result be trusted and reproduced?

### Representativeness
Does the evidence reflect the intended operating environment?

### Currency
Does it remain applicable to the current system baseline?

### Independence
Was the assessment sufficiently independent for the consequence and risk involved?

## 7. Findings

TEVV findings should identify deviations, limitations, weaknesses, unexpected behaviour or areas requiring further evidence.

Findings should distinguish between:

- Confirmed failure.
- Partial compliance.
- Evidence gap.
- Limitation.
- Uncertainty.
- Observation.
- Improvement opportunity.

A finding should not be described as a system failure unless the evidence supports that conclusion.

## 8. Severity and Significance

Findings should be assessed according to their potential effect on:

- Human safety.
- Mission effectiveness.
- Human control.
- Security.
- Data integrity.
- Reliability.
- Legal or policy compliance.
- Operational authorisation conditions.

The significance of a finding should be considered in the context of the intended mission and autonomy level.

## 9. Evidence Gaps

An evidence gap exists where available evidence is insufficient to support a required conclusion.

Evidence gaps should be:

1. Identified.
2. Documented.
3. Risk assessed.
4. Assigned an owner.
5. Given a resolution path.
6. Tracked to closure or formally accepted.

Unresolved evidence gaps should be explicitly visible to the authorising authority.

## 10. Uncertainty

TEVV conclusions should communicate uncertainty where evidence is incomplete, variable or subject to limitations.

Uncertainty may arise from:

- Limited sample sizes.
- Environmental variability.
- Incomplete data.
- Unobserved failure modes.
- Distribution shift.
- Limited operational trials.
- Measurement limitations.
- Model opacity.

The absence of observed failure should not automatically be interpreted as evidence that failure cannot occur.

## 11. Assurance Levels

D-AIGAAF may use a graduated assurance concept:

- **Insufficient Assurance** — evidence does not support the required conclusion.
- **Limited Assurance** — evidence supports only restricted conclusions or conditions.
- **Conditional Assurance** — evidence supports employment subject to defined restrictions.
- **Substantial Assurance** — evidence provides strong support for the intended use within the assessed envelope.
- **High Assurance** — evidence provides a high degree of confidence appropriate to the consequence and autonomy level.

These labels are working framework constructs and should be mapped to applicable national, defence, legal or organisational terminology before formal adoption.

## 12. Assurance Decision

The assurance conclusion should state:

- What was assessed.
- Against which requirements.
- Under which conditions.
- What evidence was considered.
- What limitations remain.
- What risks remain.
- What controls are required.
- What conditions apply.
- Whether additional evidence is required.

An assurance conclusion should never imply broader validity than the evidence supports.

## 13. Conditional Assurance

Where evidence supports only restricted employment, the assurance record should specify the conditions.

Conditions may relate to:

- Mission.
- Environment.
- Autonomy.
- Human supervision.
- Data.
- Communications.
- System configuration.
- User competence.
- Monitoring.
- Fail-safe controls.

Conditions should be measurable or otherwise objectively assessable where practicable.

## 14. Independence and Review

The level of independent review should increase with:

- Consequence of failure.
- Mission criticality.
- Autonomy.
- System complexity.
- Novelty.
- Uncertainty.
- Supply-chain dependency.

High-consequence or highly autonomous capabilities should receive appropriately independent scrutiny before operational authorisation.

## 15. Assurance Record

The Defence AI Assurance Record should, where applicable, contain:

- Capability identifier.
- System baseline.
- Mission/use case.
- Applicable requirements.
- Risk profile.
- Autonomy level.
- TEVV scope.
- Evidence inventory.
- Test results.
- Findings.
- Evidence gaps.
- Limitations.
- Assurance conclusion.
- Conditions.
- Reviewer/assessor information.
- Date.
- Validity or review period.
- Required follow-up actions.

## 16. Relationship to Operational Authorisation

TEVV assurance provides evidence for operational authorisation; it does not itself constitute operational authorisation.

The relationship is:

**TEVV Evidence → Assurance Conclusion → Authorisation Decision**

The authorising authority remains responsible for determining whether the capability may be employed and under what conditions.

## 17. Revalidation Trigger

Previously established assurance should be reconsidered when material changes occur to:

- Model.
- Data.
- Software.
- Hardware.
- Sensors.
- Interfaces.
- Operating environment.
- Mission.
- Autonomy.
- Security posture.
- Critical dependencies.

Changes should be assessed to determine whether existing evidence remains valid.

## 18. Evidence Preservation

Evidence supporting important assurance decisions should be retained in a controlled manner.

Records should support:

- Audit.
- Investigation.
- Revalidation.
- Reauthorisation.
- Incident analysis.
- Lessons learned.
- Accountability.

Evidence integrity should be protected throughout its retention period.

## 19. Core Assurance Rule

> **The strength of the assurance conclusion should never exceed the strength and relevance of the evidence supporting it.**

D-AIGAAF therefore treats assurance as an evidence-based bridge between TEVV activity and operational authority.

## 20. Golden Thread

**Requirement → Risk → Test → Evidence → Finding → Assurance → Authority → Operational Condition → Continuous Monitoring**
