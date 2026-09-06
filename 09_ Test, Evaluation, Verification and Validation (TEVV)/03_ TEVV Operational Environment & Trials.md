# D-AIGAAF — TEVV Operational Environment & Trials

## 1. Purpose

This document defines how Defence AI capabilities should be evaluated in operationally representative environments and trials.

The objective is to establish whether a capability that performs under controlled conditions remains suitable when exposed to the environmental, technical, human, and operational conditions for which it is intended.

## 2. Core Principle

> **Operational suitability must be demonstrated in conditions sufficiently representative of intended employment.**

Laboratory performance is valuable evidence, but it does not by itself establish operational effectiveness, robustness, or safe employment.

## 3. Operational Environment

The operational environment should consider relevant:

- Terrain.
- Weather and environmental conditions.
- Sensor characteristics.
- Communications availability.
- Computing resources.
- Power constraints.
- Electromagnetic conditions.
- Cyber environment.
- Data availability and quality.
- Human workload.
- Mission tempo.
- Adversarial conditions.

The applicable environment should be defined for each use case.

## 4. Environment Characterisation

Before trials, the relevant operating environment should be documented sufficiently to establish:

- Expected conditions.
- Known variations.
- Degraded conditions.
- Boundary conditions.
- Threat conditions.
- Critical assumptions.
- Dependencies.
- Conditions that invalidate previous evidence.

This creates a reference against which trial results can be interpreted.

## 5. Representative Conditions

Trials should reproduce important operational characteristics where practicable.

Examples may include:

- Intermittent communications.
- Limited or delayed connectivity.
- Reduced sensor quality.
- Incomplete information.
- Environmental variation.
- Limited processing resources.
- Variable operator workload.
- Unexpected or ambiguous inputs.

The objective is not to reproduce every possible condition, but to expose the system to conditions that could materially affect its safety, security, or mission effectiveness.

## 6. Degraded Environment Testing

Where the capability is expected to operate in degraded environments, trials should assess behaviour following:

- Communications loss.
- Sensor degradation.
- Data loss.
- Processing limitations.
- Infrastructure disruption.
- Security events.
- Environmental extremes.

Testing should establish whether the capability:

- Continues within acceptable limits.
- Communicates degradation or uncertainty.
- Transitions to an appropriate state.
- Requests human intervention.
- Enters a defined safer mode.
- Stops where required.

## 7. Adversarial Environment

Where relevant, operational trials should include realistic adversarial conditions derived from the threat model.

These may include:

- Deliberately misleading information.
- Manipulated inputs.
- Adversarial environmental conditions.
- Cyber disruption.
- Attempts to interfere with supporting systems.
- Degraded or contested information environments.

The purpose is to assess resilience and identify conditions under which the capability should be restricted or withdrawn.

## 8. Human Performance During Trials

Operational trials should evaluate the complete human-AI system.

Assessment may include:

- User comprehension.
- Decision time.
- Workload.
- Situational awareness.
- Recognition of uncertainty.
- Reliance on AI recommendations.
- Rejection of incorrect recommendations.
- Intervention.
- Override.
- Response to system degradation.

A capability should not be considered operationally effective if its use creates unacceptable human performance risks.

## 9. Mission-Level Trials

Mission-level trials should assess whether the AI capability produces meaningful operational value.

Assessment may include:

- Decision quality.
- Timeliness.
- Mission effectiveness.
- Resource efficiency.
- Reliability.
- Integration with existing workflows.
- Human workload.
- Consequences of incorrect outputs.

Technical performance should therefore be connected to mission outcomes.

## 10. Autonomy Trials

For autonomous or semi-autonomous functions, trials should assess:

- Actual autonomy behaviour.
- Operating boundaries.
- Constraint compliance.
- Transition between autonomy states.
- Human supervision.
- Intervention and override.
- Fail-safe behaviour.
- Behaviour under degraded conditions.
- Behaviour when assumptions fail.

Autonomy should not be inferred solely from documentation or design intent.

## 11. Trial Safety and Governance

Operational trials should have defined:

- Trial authority.
- Scope.
- Objectives.
- Risk controls.
- Safety boundaries.
- Stop criteria.
- Personnel responsibilities.
- Data-handling requirements.
- Incident procedures.
- Post-trial review.

Trial conditions should not unintentionally create an operational deployment without appropriate authority.

## 12. Stop Criteria

Trials should define conditions requiring pause, termination, or transition to a safer state.

Examples include:

- Uncontrolled system behaviour.
- Critical safety issue.
- Security compromise.
- Unexpected autonomous behaviour.
- Significant performance degradation.
- Loss of required human control.
- Operation outside the approved trial envelope.

Stop criteria should be understood by relevant personnel before the trial begins.

## 13. Trial Data

Trial records should capture, where appropriate:

- Environment.
- Date and time.
- System baseline.
- Configuration.
- Data conditions.
- Scenario.
- Human participants or roles.
- AI outputs.
- Performance.
- Failures.
- Interventions.
- Deviations.
- Environmental conditions.
- Observations.

The data should support later analysis and assurance decisions.

## 14. Trial Limitations

Every operational trial has limitations.

The trial report should identify:

- Conditions not tested.
- Assumptions made.
- Data limitations.
- Unrepresentative conditions.
- Known uncertainties.
- Test constraints.
- Results that should not be generalised.

Uncertainty in the evidence should be carried into the assurance and authorisation process.

## 15. Scaling Evidence

Evidence should be assessed carefully when moving between environments.

For example:

**Laboratory → Simulation → Controlled Trial → Operational Trial → Operational Employment**

Successful performance at one stage should not automatically be treated as evidence sufficient for every subsequent stage.

The required evidence should increase as consequence, autonomy, and operational complexity increase.

## 16. Environmental Change

If the operational environment changes materially after authorisation, the system owner should assess whether existing TEVV evidence remains applicable.

Examples include:

- New sensors.
- New communications architecture.
- Different environmental conditions.
- New threat conditions.
- Different data sources.
- Changed mission tempo.
- Changed autonomy.

Material environmental changes may require additional testing, revalidation, or reauthorisation.

## 17. Post-Trial Review

Following significant trials, review should determine:

- Whether objectives were met.
- Whether acceptance criteria were satisfied.
- What unexpected behaviour occurred.
- Whether assumptions remained valid.
- What limitations remain.
- Whether additional testing is required.
- Whether assurance conclusions should change.
- Whether operational authorisation can proceed or continue.

## 18. Core Principle

Operational trials should answer a practical question:

> **“Can this Defence AI capability perform its intended function, within acceptable risk and control boundaries, under the conditions in which it is actually expected to operate?”**

The resulting evidence should connect:

**Operational Environment → Trial Conditions → System Behaviour → Human Response → Mission Outcome → Assurance Decision**
