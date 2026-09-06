# D-AIGAAF — TEVV Reliability & Robustness Evaluation

## 1. Purpose

This document defines how the reliability and robustness of Defence AI capabilities should be evaluated through Testing, Evaluation, Verification and Validation (TEVV).

The objective is to establish whether the capability performs consistently and remains within acceptable behavioural and operational boundaries when conditions vary, degrade or depart from expected assumptions.

## 2. Core Principle

> **A Defence AI capability should be reliable not only under expected conditions, but sufficiently robust to foreseeable variation and degradation within its authorised operating envelope.**

Reliability and robustness should be evaluated in relation to mission consequence, system criticality and autonomy.

## 3. Scope

Evaluation should consider:

- Functional reliability.
- Performance consistency.
- Robustness to environmental variation.
- Sensor variation.
- Data variation.
- Communications degradation.
- Hardware and software faults.
- Resource constraints.
- Unexpected inputs.
- Recovery behaviour.
- Long-duration operation.
- Interaction with dependent systems.

## 4. Reliability

Reliability concerns whether the system performs its intended function consistently over time and under specified conditions.

Assessment may include:

- Failure frequency.
- Availability.
- Repeatability.
- Error rates.
- Recovery behaviour.
- Performance degradation.
- Component failures.
- Software faults.
- Dependency failures.

Reliability measures should be appropriate to the system and mission.

## 5. Robustness

Robustness concerns whether the system remains within acceptable behavioural limits when conditions vary or assumptions are stressed.

Relevant variations may include:

- Environmental conditions.
- Sensor characteristics.
- Data quality.
- Input distributions.
- Communications.
- Computing resources.
- User behaviour.
- Mission tempo.

Robustness should not be interpreted as unlimited resilience.

## 6. Requirements and Acceptance Criteria

Reliability and robustness requirements should be established before testing.

Criteria may define:

- Required performance.
- Maximum acceptable error.
- Availability.
- Recovery time.
- Degradation limits.
- Safe-state requirements.
- Conditions requiring human intervention.

Requirements should be traceable to mission needs and risk assessments.

## 7. Environmental Robustness

Where relevant, testing should assess performance across expected environmental variation.

Examples include:

- Weather variation.
- Lighting variation.
- Terrain variation.
- Temperature variation.
- Sensor obstruction.
- Background changes.
- Electromagnetic conditions.

The tested conditions should reflect the intended operational environment.

## 8. Data Robustness

Testing should assess the effect of:

- Missing data.
- Incomplete data.
- Noisy data.
- Stale data.
- Distribution changes.
- Unexpected data formats.
- Reduced data availability.

The system should communicate meaningful degradation rather than silently producing misleading results.

## 9. Sensor Robustness

Where AI depends on sensors, testing should consider:

- Sensor degradation.
- Sensor failure.
- Calibration variation.
- Occlusion.
- Conflicting sensor information.
- Reduced resolution or quality.
- Temporary loss of sensor inputs.

The system should behave predictably when critical sensing assumptions fail.

## 10. Communications Robustness

Where connectivity is required, testing should assess:

- Intermittent communications.
- Latency.
- Packet or message loss.
- Temporary disconnection.
- Extended loss of connectivity.
- Recovery following reconnection.

The system should transition according to its authorised degraded-mode behaviour.

## 11. Resource Robustness

Where relevant, testing should assess operation under constrained:

- Processing capacity.
- Memory.
- Power.
- Storage.
- Network resources.

Resource constraints should not cause uncontrolled or unexplained system behaviour.

## 12. Fault Injection

Fault-injection testing may be used to evaluate behaviour when selected components or dependencies fail.

Potential fault categories include:

- Sensor failure.
- Software failure.
- Communications failure.
- Data-source failure.
- Supporting-service failure.
- Hardware failure.

Testing should establish detection, containment, degradation and recovery behaviour.

## 13. Long-Duration Operation

Where mission duration makes it relevant, testing should assess performance over extended periods.

Evaluation may consider:

- Performance drift.
- Resource consumption.
- Accumulated errors.
- Memory or storage effects.
- Repeated decision cycles.
- Human fatigue.
- System recovery.

Long-duration testing should reflect realistic operational use where practicable.

## 14. Recovery and Restart

Testing should establish behaviour following:

- Controlled restart.
- Unexpected restart.
- Power interruption.
- Communications restoration.
- Recovery from degraded mode.
- Recovery following fault conditions.

The system should return to a known and appropriate state before resuming consequential functions.

## 15. Graceful Degradation

Where full performance cannot be maintained, the system should degrade in a predictable manner.

Evaluation should establish whether it:

- Detects degradation.
- Communicates reduced capability.
- Reduces functionality where required.
- Reduces autonomy where required.
- Requests human intervention.
- Enters a defined safe state.

Graceful degradation is particularly important where failure could affect human life or mission-critical functions.

## 16. Boundary Testing

Testing should identify performance boundaries by progressively varying relevant conditions.

The objective is to determine:

- Where performance begins to degrade.
- Where requirements are no longer satisfied.
- Where human intervention becomes necessary.
- Where operation should stop.

Known boundaries should be incorporated into operational constraints and authorisation conditions.

## 17. Unexpected Inputs and Edge Conditions

Testing should include credible edge conditions that may not be fully represented in development data.

These may include:

- Rare inputs.
- Ambiguous inputs.
- Conflicting information.
- Unusual combinations.
- Unexpected environmental conditions.
- Inputs outside normal distributions.

The objective is not to prove that every possible edge case has been tested, but to identify important failure boundaries and appropriate responses.

## 18. Reliability Under Adversarial Conditions

Where applicable, reliability and robustness should be assessed alongside security and adversarial testing.

This may include conditions that intentionally:

- Reduce data quality.
- Disrupt communications.
- Stress system resources.
- Manipulate inputs.
- Create conflicting information.

Results should be considered together with the threat model and AI security assessment.

## 19. Evidence

Evidence may include:

- Test results.
- Failure records.
- Performance measurements.
- Fault-injection results.
- Recovery measurements.
- Environmental trials.
- Long-duration results.
- Boundary measurements.
- Logs.
- Configuration information.

Evidence should identify the tested baseline and conditions.

## 20. Findings and Limitations

Findings should document:

- Observed failures.
- Performance degradation.
- Unreliable behaviour.
- Boundary conditions.
- Recovery limitations.
- Unvalidated assumptions.
- Evidence gaps.

Known limitations should be carried into the assurance and operational authorisation process.

## 21. Relationship to Operational Authorisation

Reliability and robustness evidence contributes to determining whether a capability can operate safely and effectively within its proposed operational envelope.

The relationship is:

**Requirement → Reliability/Robustness Test → Observed Behaviour → Boundary → Risk → Control → Assurance → Authorisation Condition**

Operational limits identified during testing should be reflected in authorisation conditions where relevant.

## 22. Revalidation Triggers

Reassessment should be considered following material changes to:

- Model.
- Data.
- Software.
- Hardware.
- Sensors.
- Dependencies.
- Operating environment.
- Mission.
- Autonomy.
- Resource requirements.

Emerging evidence of reliability degradation should also trigger appropriate review.

## 23. Core Rule

> **Reliability establishes consistency; robustness establishes acceptable behaviour when conditions vary. Both must be demonstrated within the intended operational envelope.**

D-AIGAAF therefore treats reliability and robustness as continuing assurance properties rather than one-time certification outcomes.
