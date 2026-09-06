# D-AIGAAF — Operational Environment Exit Criteria

## 1. Purpose

This document defines criteria for determining when a Defence AI capability should cease, suspend or transition out of authorised operation because the environmental conditions supporting its use are no longer acceptable.

The objective is to ensure that operational entry criteria are matched by explicit and enforceable exit conditions.

## 2. Core Principle

> **A capability authorised for an environment must have clearly defined conditions under which continued operation is no longer justified.**

Exit criteria are an essential part of operational assurance and should be established before operational employment.

## 3. Exit Conditions

Exit may be triggered when:

- The authorised environmental envelope is exceeded.
- Critical environmental assumptions become invalid.
- Human control is materially degraded.
- Critical dependencies fail.
- Environmental monitoring becomes unavailable.
- AI performance degrades beyond acceptable limits.
- Adversarial conditions exceed the demonstrated envelope.
- A significant incident occurs.
- New information indicates unacceptable risk.
- Required safeguards or fail-safe mechanisms become unavailable.

## 4. Types of Exit

### Planned exit

A normal transition from operational use at the completion of a mission, activity or authorised period.

### Conditional exit

A transition required when specified environmental or operational thresholds are reached.

### Emergency exit

An immediate protective response when continued operation could create unacceptable harm.

### Authorisation-driven exit

A suspension or cessation directed by the relevant authority following a governance, assurance or risk decision.

## 5. Environmental Boundary Exit

Where operation approaches or crosses an authorised environmental boundary, predefined responses should apply.

These may include:

- Warning.
- Increased human supervision.
- Reduced functionality.
- Reduced autonomy.
- Transition to fallback.
- Suspension.
- Termination of the affected function.

## 6. Degraded and Disconnected Exit

Where critical communications, data, sensors, navigation, computing or other dependencies degrade beyond authorised conditions, the capability should transition according to predefined rules.

The response should preserve:

- Human authority.
- Safety.
- System integrity.
- Recoverability.
- Traceability.

Loss of connectivity should not create uncontrolled autonomy.

## 7. Adversarial Exit

Where environmental conditions indicate significant manipulation, disruption or uncertainty beyond the authorised envelope, the capability should apply appropriate restrictions or exit procedures.

The response should consider:

- Reduced autonomy.
- Increased human verification.
- Fallback.
- Suspension.
- Incident response.

## 8. Human-Control Exit

Exit should be considered when humans can no longer exercise the level of control required by the authorisation.

Examples include:

- Insufficient intervention time.
- Loss of situational awareness.
- Excessive workload.
- Inability to interpret critical system outputs.
- Failure of authorised override.
- Loss of competent supervision.

## 9. Autonomy Exit

Where authorised autonomy depends on particular environmental conditions, failure of those conditions should trigger the appropriate autonomy response.

Possible responses include:

- Lower autonomy level.
- Return to advisory mode.
- Human confirmation requirement.
- Safe fallback.
- Suspension.

Autonomy should not continue simply because the underlying system remains technically functional.

## 10. Fail-Safe and Fallback

Exit procedures should identify the applicable fail-safe or fallback state.

The selected state should be:

- Defined in advance.
- Tested where practicable.
- Appropriate to the mission.
- Compatible with human authority.
- Proportionate to the risk.

Emergency protective action should be available where delay could create unacceptable harm.

## 11. Monitoring-Based Exit

Monitoring systems should support detection of conditions requiring exit.

Relevant indicators may include:

- Environmental thresholds.
- Sensor integrity.
- Data quality.
- Data freshness.
- Communications status.
- Navigation uncertainty.
- System performance.
- Human-control indicators.
- Adversarial indicators.

## 12. Authority to Initiate Exit

Authority to initiate exit should be explicit.

Depending on the capability, authority may be assigned to:

- Operator.
- Supervisor.
- Technical authority.
- Operational AI Advisor within its advisory role.
- Command authority.
- System owner.
- Designated safety authority.

The framework should distinguish between authority to **initiate protective action** and authority to **make or approve consequential operational decisions**.

## 13. Immediate Protective Action

Where immediate protective action is necessary, predefined procedures should permit appropriate personnel or system safeguards to act without waiting for the complete governance chain.

This emergency mechanism should be:

- Limited.
- Pre-authorised.
- Recorded.
- Reviewed after the event.

## 14. Exit Decision Record

Where practicable, the record should identify:

- Capability.
- Mission/use case.
- Environmental condition.
- Trigger.
- System state.
- Autonomy state.
- Human decision or intervention.
- Action taken.
- Authority.
- Time.
- Outcome.

## 15. Recovery After Exit

Exit does not automatically imply permanent loss of authorisation.

Recovery should require assessment of:

- Cause of exit.
- Current environmental conditions.
- System state.
- Human readiness.
- Dependencies.
- Residual risk.
- Existing assurance evidence.

Where necessary, additional testing or review should precede resumed operation.

## 16. Re-entry

Re-entry should occur only when the applicable conditions for operation are restored or a new authorised condition has been established.

Depending on the event, re-entry may require:

- Operator confirmation.
- Technical checks.
- Environmental reassessment.
- Additional TEVV.
- Revalidation.
- Reauthorisation.

## 17. Incident and Lessons Integration

Material exits should be evaluated as potential incidents or assurance events.

The organisation should determine whether the event reveals:

- An inadequate boundary.
- An inadequate monitoring threshold.
- An unexpected failure mode.
- An insufficient human-control arrangement.
- An incorrect autonomy assumption.
- An assurance gap.

## 18. Exit Criteria Register

A capability should maintain an appropriate register of material exit criteria.

| Field | Description |
|---|---|
| Exit ID | Unique identifier |
| Trigger | Condition causing exit |
| Environment | Relevant environmental condition |
| Threshold | Applicable boundary |
| Response | Required action |
| Autonomy response | Required autonomy transition |
| Human role | Required human action |
| Authority | Responsible authority |
| Fallback | Applicable safe state |
| Recording | Required evidence |
| Recovery | Re-entry requirements |

## 19. Relationship to Operational Authorisation

Exit criteria should form part of the operational authorisation package.

An authorisation should specify not only:

**Where and how the capability may operate**

but also:

**When and why it must stop, restrict itself or transition to a safer state.**

## 20. Relationship to Continuous Assurance

Exit events should feed into continuous assurance.

Repeated or unexpected exits may indicate that:

- Environmental boundaries are poorly defined.
- Monitoring is inadequate.
- The operating envelope is too broad.
- The capability is unsuitable for the environment.
- Additional assurance is required.

## 21. Governance Questions

Decision-makers should be able to answer:

1. What environmental conditions require exit?
2. Are those conditions detectable?
3. Who can initiate protective action?
4. What happens when a boundary is crossed?
5. What happens if communications are lost?
6. What happens if human control is degraded?
7. What happens to autonomy?
8. What fail-safe or fallback state applies?
9. What evidence is recorded?
10. What is required before re-entry?

## 22. Core Rule

> **Every authorised Defence AI capability should have explicit, testable and operationally enforceable conditions for reducing capability, transitioning to a safer state or exiting operation.**
