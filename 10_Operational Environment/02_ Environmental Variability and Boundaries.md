# D-AIGAAF — Environmental Variability and Boundaries

## 1. Purpose

This document establishes how environmental variability and operational boundaries should be defined, assessed and controlled for Defence AI capabilities.

The objective is to ensure that a capability is not treated as equally assured across conditions that may materially change its behaviour.

## 2. Core Principle

> **Operational assurance applies within demonstrated and authorised boundaries, not automatically across every conceivable environment.**

## 3. Environmental Variability

Environmental variability refers to changes in operating conditions that may influence AI inputs, system behaviour, human interaction or mission outcomes.

Relevant variability may include:

- Physical conditions.
- Weather.
- Terrain.
- Illumination.
- Sensor quality.
- Information availability.
- Communication conditions.
- Navigation confidence.
- Computing resources.
- Human workload.
- Adversarial activity.

The relevant variables should be determined for each capability.

## 4. Environmental Operating Envelope

Each capability should have an identified environmental operating envelope.

The envelope should describe:

- Conditions within which operation is demonstrated.
- Conditions requiring additional controls.
- Conditions where operation is restricted.
- Conditions where operation is prohibited or suspended.

The envelope should be proportionate to mission consequence and autonomy.

## 5. Environmental Zones

A practical governance model may distinguish:

| Zone | Meaning | Typical Governance Response |
|---|---|---|
| Green | Demonstrated and authorised conditions | Normal authorised operation |
| Amber | Degraded or boundary conditions | Additional controls or supervision |
| Red | Outside demonstrated/authorised conditions | Restriction, suspension or fallback |

These labels are a governance construct and should be adapted to the adopting organisation's terminology.

## 6. Nominal Conditions

Nominal conditions are conditions under which the capability is expected to operate routinely.

Evidence should establish that:

- Performance is acceptable.
- Known limitations are understood.
- Dependencies are available.
- Human controls function as intended.

Nominal performance should not be assumed to represent performance under degraded conditions.

## 7. Challenging Conditions

Challenging conditions are conditions that remain within the intended operating concept but may stress system performance.

Examples may include:

- Reduced visibility.
- Increased sensor noise.
- Intermittent communications.
- Increased information latency.
- Higher human workload.
- Reduced computing resources.

Such conditions should be included in TEVV where they could materially affect mission risk.

## 8. Boundary Conditions

Boundary conditions represent the limits of demonstrated or authorised operation.

For each material boundary, the organisation should identify:

- The variable involved.
- The relevant threshold or qualitative limit.
- Evidence supporting the boundary.
- Expected system behaviour near the boundary.
- Required human controls.
- Response when the boundary is exceeded.

## 9. Outside-Envelope Conditions

Conditions outside the authorised envelope should not automatically result in continued normal operation.

Predefined responses should be considered, including:

- Warning.
- Increased human supervision.
- Reduced functionality.
- Reduced autonomy.
- Fallback mode.
- Safe-state transition.
- Suspension.

The response should be based on risk and consequence.

## 10. Environmental Combinations

Environmental risks may arise from combinations of conditions rather than a single variable.

For example:

**Reduced visibility + degraded sensors + communication loss**

may create a substantially different risk profile from any individual condition.

TEVV should therefore consider important combinations where system behaviour may be non-linear or difficult to predict.

## 11. Environmental Transitions

AI capabilities may move between environmental states during operation.

The governance model should define how the system responds when transitioning between:

- Nominal and degraded conditions.
- Connected and disconnected states.
- High and low sensor confidence.
- Normal and constrained computing conditions.
- Expected and unexpected environmental states.

Transitions should be considered in autonomy and fail-safe design.

## 12. Detecting Boundary Crossings

Where technically feasible, the system should detect conditions that indicate it may be approaching or exceeding an authorised boundary.

Indicators may include:

- Reduced confidence.
- Sensor-quality degradation.
- Loss of required inputs.
- Communication degradation.
- Navigation uncertainty.
- Processing constraints.
- Unexpected data patterns.

Detection should lead to an appropriate predefined response.

## 13. Uncertainty at Boundaries

System uncertainty should generally increase the governance concern associated with boundary conditions.

The capability should communicate relevant uncertainty to human decision-makers rather than presenting degraded outputs with unjustified confidence.

## 14. Environmental Boundary and Autonomy

Autonomy should not remain fixed merely because the underlying software is unchanged.

Where environmental uncertainty increases, the authorised autonomy level may need to:

- Remain unchanged if evidence supports it.
- Move to a more supervised mode.
- Reduce consequential functions.
- Require additional human confirmation.
- Transition to a safe or fallback state.

## 15. Environmental Boundary and Mission

A capability may have different acceptable environmental boundaries for different missions.

Therefore:

**Capability × Mission × Environment**

should be considered together when defining operational limits.

An environment authorised for one use case should not automatically be treated as authorised for another.

## 16. Environmental Boundary Evidence

Each significant boundary should be supported by appropriate evidence.

Evidence may include:

- Laboratory testing.
- Simulation.
- Field testing.
- Operational trials.
- Historical operational data.
- Human factors evaluation.
- Reliability assessment.
- Security evaluation.

The evidence should identify the system baseline and relevant test conditions.

## 17. Conservative Treatment of Unknowns

Where environmental effects are poorly understood, the framework should favour explicit uncertainty over unsupported assumptions.

Unknown conditions may require:

- Additional testing.
- Temporary restrictions.
- Increased supervision.
- Reduced autonomy.
- Additional monitoring.

## 18. Monitoring During Employment

Environmental indicators relevant to authorised boundaries should be monitored where practicable.

Monitoring should support:

- Early detection of degradation.
- Human awareness.
- Automated safeguards where appropriate.
- Escalation.
- Suspension decisions.
- Post-operation analysis.

## 19. Change Management

Environmental boundaries should be reviewed when:

- The mission changes.
- The operating environment changes.
- Threat conditions change materially.
- Sensors or supporting systems change.
- The AI model or software changes.
- New failure modes are discovered.
- Operational evidence contradicts previous assumptions.

Material changes should enter the D-AIGAAF change and reauthorisation process.

## 20. Documentation

The environmental boundary record should capture, as appropriate:

- Capability.
- Mission.
- Environment.
- Boundary.
- Evidence.
- Assumptions.
- Limitations.
- Required controls.
- Human authority.
- Autonomy implications.
- Monitoring requirements.
- Boundary-crossing response.
- Review date.

## 21. Governance Review

The environmental envelope should be reviewed by appropriate operational, technical, assurance and authority stakeholders.

The review should establish that:

1. Relevant variability has been considered.
2. Important boundaries are identified.
3. Evidence supports the boundaries.
4. Boundary-crossing responses are defined.
5. Human authority remains effective.
6. Autonomy remains appropriate.
7. Residual uncertainty is understood.

## 22. Core Rule

> **Environmental boundaries should be explicit, evidence-based and linked to operational controls, human authority and autonomy.**
