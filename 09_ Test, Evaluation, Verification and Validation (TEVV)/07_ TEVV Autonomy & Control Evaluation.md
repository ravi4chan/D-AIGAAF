# D-AIGAAF — TEVV Autonomy & Control Evaluation

## 1. Purpose

This document defines how autonomy and human control should be evaluated as part of Testing, Evaluation, Verification and Validation (TEVV).

The objective is to establish whether the Defence AI capability behaves within its authorised autonomy boundaries and whether required human authority, supervision, intervention and override remain effective.

## 2. Core Principle

> **The autonomy level of a Defence AI capability must be demonstrated through observed behaviour, not inferred from design intent.**

A system should not be treated as operating at a lower autonomy level merely because a human is nominally present in the system.

## 3. Scope

Autonomy and control evaluation should consider:

- Actual system autonomy.
- Authorised autonomy.
- Human decision rights.
- Human supervision.
- Intervention.
- Override.
- Autonomy transitions.
- Operating boundaries.
- Constraint enforcement.
- Fail-safe behaviour.
- Loss of communications.
- Unexpected system behaviour.
- Recovery.

## 4. Authorised Autonomy

Before testing, the intended autonomy level should be explicitly defined.

D-AIGAAF uses the following working construct:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are D-AIGAAF working categories and should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

## 5. Autonomy Boundaries

Testing should establish whether the system remains within defined boundaries relating to:

- Mission.
- Environment.
- Function.
- Time.
- Data.
- Human authority.
- Consequence.
- Permitted actions.
- System state.

The system should not silently expand its effective autonomy beyond the authorised envelope.

## 6. Autonomy Behaviour

Evaluation should compare:

**Specified Autonomy → Implemented Autonomy → Observed Autonomy**

Any material difference should be investigated.

Testing should identify whether system behaviour changes under:

- Normal conditions.
- Degraded conditions.
- Unexpected inputs.
- Loss of communications.
- Sensor degradation.
- System faults.
- Security events.
- Human intervention.

## 7. Human Control

Where human control is required, testing should establish whether the human can:

- Understand system state.
- Recognise when intervention is necessary.
- Make an informed decision.
- Issue an intervention.
- Override the system.
- Confirm the resulting state.
- Resume or terminate operation.

Human control should be assessed under realistic time, workload and environmental conditions.

## 8. Human Decision Rights

Testing should verify that the system does not unintentionally transfer decision authority to the AI.

The evaluation should distinguish between:

- AI recommendation.
- Human decision.
- Human authorisation.
- AI execution.
- Autonomous action.

Where consequential action requires human authorisation, the evidence should demonstrate that the required authorisation actually occurs.

## 9. Autonomy Transitions

Systems capable of changing autonomy states should be tested for:

- Entry conditions.
- Exit conditions.
- Transition triggers.
- Human notification.
- Human approval where required.
- Safe transition behaviour.
- Recovery following interruption.

Unexpected or unauthorised transitions should be treated as significant findings.

## 10. Loss of Communications

Where communications are required for human supervision, testing should assess system behaviour following:

- Temporary communications loss.
- Extended communications loss.
- Intermittent connectivity.
- Delayed communications.
- Loss of the designated supervisor.

The authorised response should be demonstrated rather than assumed.

## 11. Constraint Enforcement

Autonomous functions should be tested against their defined constraints.

Testing may assess:

- Geographical or environmental constraints where applicable.
- Time constraints.
- Mission constraints.
- Action restrictions.
- Human approval requirements.
- Resource limits.
- Safety constraints.

The objective is to determine whether constraints are technically enforced and remain effective under degraded or adversarial conditions.

## 12. Fail-Safe Behaviour

Testing should establish whether the system enters the defined safer state when required.

Relevant conditions may include:

- Loss of required supervision.
- Critical sensor failure.
- Loss of communications.
- Detection of unsafe behaviour.
- Integrity failure.
- Unexpected system state.
- Exceeding authorised boundaries.

Fail-safe behaviour should be proportionate to the consequences of continued operation.

## 13. Override and Intervention

Override testing should assess:

- Availability of controls.
- Accessibility.
- Correct operation.
- Response time.
- Effectiveness.
- Resistance to accidental activation.
- Behaviour following override.
- Confirmation of system state.

An override mechanism should not be considered effective merely because it exists.

## 14. Unexpected Autonomy

Testing should deliberately seek evidence of behaviour outside expected autonomy boundaries.

Examples include:

- Unplanned actions.
- Unexpected sequencing.
- Persistent action after an intervention.
- Autonomous behaviour following loss of supervision.
- Actions based on invalid or stale information.
- Failure to enter the required safe state.

Unexpected autonomy should trigger appropriate investigation and risk assessment.

## 15. Autonomy Under Degraded Conditions

Where relevant, testing should combine autonomy with degraded conditions such as:

- Reduced communications.
- Sensor degradation.
- Data uncertainty.
- Infrastructure disruption.
- Increased human workload.
- Environmental variation.

The evaluation should establish whether autonomy remains bounded and predictable when normal assumptions fail.

## 16. Autonomy Under Adversarial Conditions

Where appropriate, testing should assess whether adversarial manipulation can:

- Increase effective autonomy.
- Bypass constraints.
- Prevent human intervention.
- Trigger unauthorised actions.
- Conceal changes in system state.
- Cause unsafe transitions.

Results should be assessed according to potential consequences.

## 17. Human-AI Interaction

Autonomy evaluation should include human factors such as:

- Automation bias.
- Situational awareness.
- Understanding of system state.
- Recognition of autonomy transitions.
- Trust calibration.
- Intervention readiness.
- Workload.

The human should remain capable of exercising the authority assigned to them.

## 18. Acceptance Criteria

Autonomy acceptance criteria should address:

- Compliance with authorised autonomy.
- Constraint enforcement.
- Human intervention.
- Override effectiveness.
- Transition behaviour.
- Fail-safe behaviour.
- Communication loss.
- Degraded operation.
- Recovery.
- Unexpected behaviour.

Criteria should become more stringent as consequence and autonomy increase.

## 19. Evidence

Evidence should include, where applicable:

- Authorised autonomy definition.
- Test scenarios.
- System configuration.
- Observed autonomy state.
- Human actions.
- System responses.
- Transition events.
- Intervention results.
- Fail-safe results.
- Deviations.
- Limitations.

Evidence should be traceable to the tested system baseline.

## 20. Findings

Findings should clearly distinguish:

- Correct autonomous behaviour.
- Incorrect autonomous behaviour.
- Boundary violation.
- Human-control failure.
- Intervention failure.
- Override failure.
- Unexpected transition.
- Evidence gap.
- Limitation.

Findings should be risk assessed in relation to mission consequence.

## 21. Relationship to Operational Authorisation

Autonomy TEVV provides evidence for determining whether the proposed autonomy level is acceptable.

The relationship is:

**Authorised Autonomy → Test Conditions → Observed Behaviour → Human Control → Assurance → Operational Authorisation**

Operational authorisation should specify the autonomy level and boundaries supported by the evidence.

## 22. Revalidation Triggers

Autonomy evaluation should be reconsidered when changes affect:

- Model behaviour.
- System architecture.
- Autonomy logic.
- Human interface.
- Sensors.
- Communications.
- Mission.
- Operating environment.
- Constraints.
- Human roles.
- Critical dependencies.

A change that alters effective autonomy should receive appropriate reassessment before continued employment.

## 23. Core Rule

> **If the system can take consequential action, TEVV must demonstrate not only what it is intended to do, but what it actually does when conditions change.**

The assurance objective is to establish that autonomy remains bounded, observable, controllable and consistent with the authority granted to the system.
