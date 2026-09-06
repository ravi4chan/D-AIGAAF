# D-AIGAAF — Human Oversight, Intervention & Override

## 1. Purpose

This document establishes requirements for human oversight, intervention, and override of Defence AI capabilities.

It ensures that where human control is required, it is technically practical, operationally meaningful, and supported by defined authority.

## 2. Core Principle

> **Human oversight must be an effective control, not merely the presence of a person in the decision chain.**

The required degree of oversight should be proportionate to consequence, mission criticality, autonomy, environmental uncertainty, and system reliability.

## 3. Oversight Model

Human oversight may occur at different stages:

- Before AI employment.
- During AI operation.
- When AI produces a recommendation.
- When defined thresholds or anomalies occur.
- Before consequential action.
- After an event.
- During periodic assurance review.

The appropriate model should be defined for each authorised use case.

## 4. Types of Oversight

D-AIGAAF may distinguish between:

### 4.1 Pre-Action Oversight

A human reviews and approves an AI recommendation or proposed action before execution.

### 4.2 Supervisory Oversight

A human supervises AI operation and can intervene when required.

### 4.3 Exception-Based Oversight

AI operates within authorised boundaries while human intervention is triggered by defined exceptions.

### 4.4 Post-Action Oversight

Human review occurs after authorised autonomous activity, with appropriate safeguards and records.

The selected model must remain consistent with the authorised autonomy level and consequence.

## 5. Intervention Authority

Before deployment, the framework should establish:

- Who may intervene.
- What actions they may take.
- Under what conditions intervention is required.
- Whether intervention is immediate.
- What technical mechanism enables intervention.
- What happens following intervention.
- Whether escalation is required.

Authority should be explicit rather than inferred from organisational hierarchy.

## 6. Override

Override is the authorised ability of a human to reject, interrupt, supersede, or otherwise constrain AI-supported behaviour.

Where override is required, it should be:

- Accessible to authorised personnel.
- Unambiguous.
- Tested.
- Reliable under relevant conditions.
- Appropriate to the time available for intervention.
- Protected against accidental activation.
- Recorded where required.

## 7. Emergency Intervention

Where delay could create unacceptable harm, predefined emergency procedures may allow immediate intervention, including:

- Suspension.
- Isolation.
- Transition to a safer operating mode.
- Transfer to manual control.
- Termination of AI-supported activity.

Emergency intervention should be followed by appropriate notification, investigation, and reassessment.

## 8. AI Fail-Safe

A fail-safe should provide a last-resort mechanism for placing an AI capability into a defined safe or controlled state.

The fail-safe should not be treated as a substitute for normal governance, testing, or monitoring.

Where practicable, response to a serious AI issue should follow an escalation path such as:

**Detection → Operator → System Manager → Operational AI Advisor → Command / Authorising Authority**

However, where delay could create unacceptable harm, pre-authorised emergency intervention should be available.

## 9. Intervention Under Degraded Conditions

Oversight and override should be tested under conditions including:

- Loss of communications.
- Reduced connectivity.
- Sensor degradation.
- Cyber disruption.
- Electronic interference.
- Power or infrastructure limitations.
- Reduced personnel availability.
- High workload.

A control that works only under ideal conditions should not be considered adequately assured for environments where those conditions cannot be guaranteed.

## 10. Intervention Timing

The required intervention time should be assessed against the consequence and speed of system action.

A human cannot provide meaningful real-time intervention if:

- The system acts faster than the human can reasonably respond.
- The human cannot receive the relevant information in time.
- The intervention mechanism introduces unacceptable delay.
- The operational environment prevents effective communication.

Where meaningful real-time intervention is impossible, the governance model should rely on appropriate pre-authorised constraints, bounded autonomy, monitoring, and fail-safe mechanisms.

## 11. Preventing Automation Bias

Oversight design should reduce the risk that personnel:

- Automatically accept AI recommendations.
- Assume AI outputs are correct.
- Ignore contradictory information.
- Avoid overriding the system because of perceived authority.
- Continue using the system after its assumptions have failed.

Training, interface design, procedures, and assurance should address these risks.

## 12. Intervention Triggers

Predefined intervention or escalation triggers may include:

- AI confidence or uncertainty outside defined limits.
- Detection of anomalous behaviour.
- Operating outside validated conditions.
- Unexpected input conditions.
- Security compromise.
- Significant performance degradation.
- Loss of required data.
- Loss of communications.
- Conflict between AI outputs and trusted information.
- Emergence of a new high-consequence failure mode.

Triggers should be tailored to the use case.

## 13. Override Testing

TEVV should establish that override mechanisms:

1. Can be initiated by authorised personnel.
2. Operate under relevant environmental conditions.
3. Produce the expected system response.
4. Do not create unacceptable secondary hazards.
5. Remain available when required.
6. Are understood by users.
7. Generate appropriate records.

Testing should include realistic failure and stress scenarios.

## 14. Post-Intervention Review

Significant interventions should be reviewed to determine:

- Why intervention occurred.
- Whether the trigger was appropriate.
- Whether the AI behaved as expected.
- Whether human oversight was effective.
- Whether the operating envelope was exceeded.
- Whether the system should remain authorised.
- Whether additional testing or modification is required.

A significant intervention may therefore trigger incident management, revalidation, or reauthorisation.

## 15. Evidence

Evidence supporting effective oversight may include:

- Intervention test results.
- Override test results.
- Scenario-based exercises.
- Human factors assessments.
- Training records.
- Operational logs.
- Incident records.
- Fail-safe validation.
- Monitoring results.

Evidence should be linked to the relevant assurance and operational-authorisation records.

## 16. Core Principle

D-AIGAAF distinguishes between **having an override mechanism** and **having meaningful human control**.

The relevant question is:

> **Can the authorised human recognise when intervention is required, exercise legitimate authority, and cause the required system response within the time and conditions that matter?**

If not, the capability, autonomy level, safeguards, or operational authorisation should be reconsidered.
