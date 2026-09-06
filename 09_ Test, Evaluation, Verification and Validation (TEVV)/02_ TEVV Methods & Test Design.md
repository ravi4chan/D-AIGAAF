# D-AIGAAF — TEVV Methods & Test Design

## 1. Purpose

This document defines a structured approach for selecting Test, Evaluation, Verification and Validation (TEVV) methods and designing tests for Defence AI capabilities.

The objective is to ensure that the method used produces evidence appropriate to the requirement, risk, operational context, autonomy, and consequence of failure.

## 2. Core Principle

> **The test method should be capable of demonstrating the property being claimed under conditions relevant to the intended use.**

A technically valid test may still be inadequate if it does not represent the operational conditions or risks that matter.

## 3. Selecting the TEVV Method

The method should be selected based on:

- Requirement type.
- Risk.
- Consequence.
- Mission criticality.
- Autonomy.
- System complexity.
- Operational environment.
- Threat model.
- Human interaction.
- Available evidence.
- Acceptable uncertainty.

No single testing method is sufficient for every Defence AI capability.

## 4. TEVV Method Categories

Applicable methods may include:

### 4.1 Inspection

Examination of documentation, configuration, code, architecture, records, or controls.

### 4.2 Analysis

Use of analytical methods, simulations, statistical evaluation, or model analysis.

### 4.3 Demonstration

Observation that the system performs a defined function under specified conditions.

### 4.4 Test

Controlled execution of the system to generate measurable evidence.

### 4.5 Evaluation

Assessment of system characteristics, limitations, risks, or effectiveness against defined criteria.

### 4.6 Validation

Determination of whether the capability is suitable for its intended mission and operational context.

## 5. Test Design

A significant test should define:

- Objective.
- Requirement or risk addressed.
- System baseline.
- Test conditions.
- Inputs.
- Expected behaviour.
- Measurement method.
- Acceptance criteria.
- Safety controls.
- Data requirements.
- Personnel.
- Environment.
- Evidence to be retained.

## 6. Test Conditions

Test conditions should reflect the property being assessed.

Where relevant, testing should vary:

- Data quality.
- Environmental conditions.
- Sensor inputs.
- Communications.
- Workload.
- Operating temperature or resource constraints.
- Adversarial conditions.
- System configuration.
- User behaviour.

Testing should avoid assuming that a single representative condition adequately characterises system performance.

## 7. Baseline Control

The tested baseline should be uniquely identifiable.

At minimum, the test record should identify relevant:

- Model version.
- Software version.
- Hardware.
- Configuration.
- Data.
- Critical dependencies.
- Security settings.

Changes to the baseline should be controlled and assessed for their effect on test validity.

## 8. Statistical and Performance Evaluation

Where AI performance is measured statistically, evaluation should consider:

- Appropriate metrics.
- Sample size.
- Confidence or uncertainty.
- Class imbalance.
- Data representativeness.
- False positives.
- False negatives.
- Relevant operating thresholds.
- Performance variation.

A single aggregate accuracy value should not be treated as sufficient evidence where different error types have materially different consequences.

## 9. Robustness Testing

Robustness tests should examine performance when conditions deviate from expected inputs.

Examples include:

- Noise.
- Missing information.
- Sensor degradation.
- Distribution shift.
- Unexpected inputs.
- Environmental variation.
- Resource constraints.

The objective is to identify degradation behaviour and determine whether it remains within acceptable limits.

## 10. Adversarial Testing

Where applicable, test design should incorporate threats identified in the AI threat model.

Testing may assess:

- Input manipulation.
- Evasion.
- Poisoning.
- Prompt or instruction manipulation.
- Model exploitation.
- Dependency compromise.
- Configuration tampering.

Adversarial tests should be designed to generate useful evidence rather than simply demonstrate that an attack is theoretically possible.

## 11. Human-in-the-Loop Testing

Where humans interact with the capability, test design should include realistic human workflows.

Assessment may examine:

- Comprehension.
- Decision time.
- Workload.
- Trust calibration.
- Recognition of uncertainty.
- Automation bias.
- Recommendation acceptance/rejection.
- Intervention.
- Override.

The human and AI should be evaluated as an integrated operational system where their interaction materially affects outcomes.

## 12. Autonomous Behaviour Testing

For autonomous functions, tests should assess:

- Initiation conditions.
- Decision boundaries.
- Constraint compliance.
- Behaviour under uncertainty.
- Boundary conditions.
- Transition between autonomy states.
- Human intervention.
- Fail-safe response.
- Loss of required inputs.
- Loss of communications.

Testing should establish both intended behaviour and unacceptable behaviour.

## 13. Scenario-Based Testing

Scenario-based testing should be used where system behaviour depends heavily on context.

Scenarios should vary relevant combinations of:

**Mission × Environment × Data × Threat × Human Factors × Autonomy**

High-consequence scenarios should include plausible failure conditions rather than only successful mission outcomes.

## 14. Simulation

Simulation may be useful where live testing is:

- Unsafe.
- Impractical.
- Expensive.
- Rare-event limited.
- Environmentally constrained.

However, simulation evidence should be assessed for fidelity and relevance.

A simulation should not be treated as equivalent to operational evidence unless its assumptions and limitations support that conclusion.

## 15. Live and Operational Testing

Where appropriate, operational testing should expose the capability to representative real-world conditions.

Operational testing should assess:

- Mission effectiveness.
- Integration.
- Human interaction.
- Environmental robustness.
- Communications constraints.
- Operational workload.
- Security.
- Failure behaviour.

Safety and governance controls should remain in force during operational trials.

## 16. Negative Testing

TEVV should deliberately test conditions in which the system should:

- Refuse an action.
- Defer a recommendation.
- Indicate uncertainty.
- Escalate to a human.
- Enter a safer mode.
- Stop or suspend operation.

Negative testing is particularly important where inappropriate system behaviour could create significant consequences.

## 17. Boundary Testing

Test design should identify the limits of authorised operation.

Testing may establish:

- Maximum supported conditions.
- Minimum data quality.
- Maximum acceptable uncertainty.
- Resource limits.
- Environmental boundaries.
- Autonomy boundaries.
- Human response requirements.

Results should inform the operational envelope and authorisation conditions.

## 18. Repeatability and Reproducibility

Where practicable, important tests should be sufficiently documented to permit:

- Repeat execution.
- Independent review.
- Comparison across versions.
- Investigation of unexpected results.

Differences between repeated tests should be investigated when they could affect assurance conclusions.

## 19. Test Evidence

Evidence should include, as appropriate:

- Test plan.
- Test configuration.
- Inputs and datasets.
- Test procedures.
- Results.
- Logs.
- Measurements.
- Observations.
- Deviations.
- Failures.
- Limitations.
- Assessor conclusions.

Evidence should be linked to the relevant requirement and risk.

## 20. Core Principle

Effective TEVV test design connects the technical claim to the conditions under which that claim matters:

**Claim → Requirement → Risk → Test Method → Test Condition → Measurement → Result → Evidence → Conclusion**

The objective is not to produce more tests. It is to produce **credible evidence for the decisions that matter**.
