# D-AIGAAF — Operational Environment Records and Evidence

## 1. Purpose

This document defines the records and evidence required to demonstrate that the operational environment of a Defence AI capability has been characterised, assessed, monitored and governed throughout its lifecycle.

The objective is to preserve a traceable connection between environmental conditions, assurance evidence, operational decisions and continued authorisation.

## 2. Core Principle

> **If an environmental assurance claim cannot be supported by traceable evidence, it should not be treated as a demonstrated operational fact.**

Records should support both current decision-making and later review, investigation and audit.

## 3. Environmental Evidence

Environmental evidence may demonstrate:

- Conditions in which the capability was evaluated.
- Conditions in which the capability was successfully operated.
- Known environmental limitations.
- Environmental dependencies.
- Human-control performance.
- Autonomy behaviour.
- Degraded or disconnected behaviour.
- Adversarial resilience.
- Monitoring effectiveness.
- Incident response.
- Continued suitability.

## 4. Evidence Sources

Evidence may originate from:

- Environmental characterisation.
- Laboratory testing.
- Simulation.
- Operational trials.
- TEVV.
- Monitoring.
- Operational employment.
- Incident investigation.
- Human factors evaluation.
- Security assessment.
- Independent review.
- Maintenance and support records.
- Operational lessons learned.

## 5. Environmental Evidence Record

An environmental evidence record should identify, as appropriate:

- Capability.
- Mission/use case.
- Environment.
- Conditions.
- Date and context.
- System configuration.
- Relevant dependencies.
- Test or observation method.
- Result.
- Limitations.
- Assumptions.
- Responsible authority.
- Evidence status.

## 6. Evidence Classification

Environmental evidence may be classified as:

### Demonstrated

Direct evidence supports the claim under relevant conditions.

### Partially demonstrated

Evidence exists but does not fully cover the intended condition or boundary.

### Indirectly supported

Evidence provides useful confidence but was not generated under the relevant operational conditions.

### Untested

No sufficient evidence exists.

### Contradicted

Available evidence indicates that the existing assurance claim may not be valid.

## 7. Traceability

Environmental evidence should be traceable to:

**Mission → Environment → Risk → Requirement → Control → Test/Observation → Result → Assurance Claim → Authorisation**

This supports the D-AIGAAF Golden Thread.

## 8. Configuration Context

Environmental evidence should identify the relevant system configuration where material.

This may include:

- Software baseline.
- Model version.
- Hardware configuration.
- Sensor configuration.
- Supporting system configuration.
- Relevant data or model baseline.
- Critical dependencies.

Evidence should not automatically be assumed to apply to materially different configurations.

## 9. Environmental Boundaries

Records should identify evidence supporting:

- Nominal conditions.
- Challenging conditions.
- Boundary conditions.
- Restricted conditions.
- Prohibited conditions.

Where a boundary is based on limited evidence, that limitation should be visible.

## 10. Degraded and Disconnected Evidence

Where relevant, records should demonstrate behaviour under:

- Communications degradation.
- Loss of connectivity.
- Data limitations.
- Sensor degradation.
- Navigation limitations.
- Computing constraints.
- Recovery and resynchronisation.

Evidence should show whether human control and safe fallback remain effective.

## 11. Adversarial Environmental Evidence

Where relevant, records should capture evidence from controlled assessment of:

- Information manipulation.
- Sensor interference.
- Communications disruption.
- Environmental deception.
- Integrity threats.
- Unexpected system behaviour.

Such records should be handled according to applicable security requirements.

## 12. Human Environment Evidence

Evidence should support claims concerning:

- Human understanding.
- Workload.
- Situational awareness.
- Uncertainty interpretation.
- Intervention.
- Override.
- Autonomy supervision.
- Decision traceability.

Human performance should be considered part of operational environmental assurance where it materially affects system risk.

## 13. Monitoring Records

Monitoring records should preserve material observations such as:

- Environmental indicators.
- Boundary warnings.
- Environmental deviations.
- System response.
- Human response.
- Autonomy transitions.
- Fallback events.
- Monitoring failures.

Records should be sufficiently structured to support trend analysis.

## 14. Incident Records

Environmental incidents should preserve relevant evidence concerning:

- Conditions.
- System state.
- Human actions.
- AI outputs or actions.
- Autonomy state.
- Boundary status.
- Consequence.
- Response.
- Investigation.
- Corrective action.

Evidence preservation should support accountability and learning.

## 15. Evidence Integrity

Environmental evidence should have appropriate controls for:

- Authenticity.
- Integrity.
- Traceability.
- Access control.
- Versioning.
- Retention.
- Change history.

The required level of protection should be proportionate to consequence and information sensitivity.

## 16. Evidence Currency

Evidence should be reviewed for continued applicability.

Currency may be affected by:

- Environmental change.
- System change.
- Model updates.
- Data changes.
- Mission changes.
- Dependency changes.
- New threats.
- Operational experience.

Old evidence should not automatically be treated as invalid, but its applicability should be assessed.

## 17. Evidence Gaps

Evidence gaps should be explicitly recorded.

Each significant gap should identify:

- Missing evidence.
- Reason for the gap.
- Associated risk.
- Interim control.
- Required action.
- Responsible owner.
- Target resolution.
- Authority accepting any residual risk.

## 18. Evidence and Operational Authorisation

Environmental evidence should provide part of the basis for operational authorisation.

The authorisation record should be able to identify:

- What environmental conditions were demonstrated.
- What conditions remain uncertain.
- What restrictions apply.
- What monitoring is required.
- What evidence supports continued operation.

## 19. Evidence and Reauthorisation

Material environmental findings should feed reauthorisation decisions.

Reauthorisation may be required when evidence demonstrates that:

- An environmental assumption was incorrect.
- The authorised envelope is inadequate.
- Human control is affected.
- Autonomy is no longer sufficiently supported.
- Mission risk has materially changed.

## 20. Evidence Retention

Records should be retained according to applicable organisational, legal, security and records-management requirements.

Retention should support:

- Operational accountability.
- Assurance review.
- Incident investigation.
- Audit.
- Lessons learned.
- Future capability development.

## 21. Environmental Evidence Register

Organisations should maintain an appropriate register of material environmental evidence.

A register may contain:

| Field | Description |
|---|---|
| Evidence ID | Unique identifier |
| Capability | AI capability |
| Mission | Intended mission/use case |
| Environment | Relevant environment |
| Condition | Tested or observed condition |
| Configuration | Relevant baseline |
| Method | Test, trial, monitoring or observation |
| Result | Outcome |
| Applicability | Scope of relevance |
| Limitations | Known limitations |
| Assurance claim | Claim supported |
| Status | Current evidence status |
| Owner | Responsible authority |
| Review date | Next review |

## 22. Evidence Ownership

Ownership should be assigned for:

- Evidence creation.
- Evidence validation.
- Evidence storage.
- Evidence review.
- Evidence retention.
- Evidence disposition.

Ownership does not necessarily mean the same person or organisation performs every activity.

## 23. Operational AI Advisor

Where an Operational AI Advisor exists, the advisor may use environmental records to help interpret:

- Current operating conditions.
- Historical evidence.
- Known limitations.
- Emerging risks.
- Implications for human control and autonomy.

The advisor should not independently convert evidence into operational authority.

## 24. Audit and Review

Environmental records should support independent examination of whether:

- Environmental assumptions were explicit.
- Evidence was sufficient.
- Boundaries were justified.
- Monitoring was performed.
- Incidents were recorded.
- Lessons were incorporated.
- Authorisation decisions were traceable.

## 25. Governance Questions

Decision-makers should be able to answer:

1. What evidence demonstrates environmental suitability?
2. Under what conditions was it generated?
3. Which configuration does it apply to?
4. What conditions remain untested?
5. What limitations are known?
6. Is the evidence still current?
7. Are environmental incidents reflected in the evidence base?
8. Can every material assurance claim be traced to evidence?
9. Who owns the evidence?
10. What evidence must be refreshed before continued or expanded authorisation?

## 26. Core Rule

> **Environmental evidence is the factual foundation for deciding where, when and under what conditions a Defence AI capability can be trusted to operate.**
