# D-AIGAAF — Degraded and Disconnected Operations

## 1. Purpose

This document defines governance considerations for Defence AI capabilities operating under degraded, intermittent or disconnected conditions.

The objective is to ensure that loss or degradation of communications, data, sensors, computing resources or supporting services does not create uncontrolled AI behaviour or unexpected loss of human authority.

## 2. Core Principle

> **Loss of connectivity or supporting infrastructure must not silently convert an assured AI capability into an uncontrolled capability.**

The capability should have defined behaviour for foreseeable degraded and disconnected conditions.

## 3. Scope

This document addresses degradation involving:

- Communications.
- Data availability.
- Sensor availability or quality.
- Navigation and positioning.
- Computing resources.
- Power.
- External services.
- Supporting systems.
- Human connectivity.

It does not prescribe tactical procedures or classified operational methods.

## 4. Degraded Operating Conditions

A degraded condition exists when one or more dependencies or operating conditions fall below the assumptions supporting normal operation.

Examples include:

- Reduced bandwidth.
- Increased latency.
- Intermittent connectivity.
- Loss of selected sensors.
- Reduced data freshness.
- Reduced computing resources.
- Navigation uncertainty.
- Partial supporting-system failure.

## 5. Disconnected Operation

A disconnected condition exists when required communication or external connectivity is unavailable for a material period.

For each capability that may operate disconnected, the organisation should establish:

- Functions that remain available.
- Functions that become restricted.
- Data that remains locally available.
- Data that may become stale.
- Permitted autonomy.
- Human-control arrangements.
- Recovery and resynchronisation requirements.

## 6. Dependency Mapping

Material dependencies should be identified before authorisation.

These may include:

- Communications networks.
- External data.
- Positioning services.
- Remote computing.
- Cloud services.
- Supporting sensors.
- Other AI systems.
- Human operators.

Each dependency should have a documented failure or degradation response where its loss could affect mission risk.

## 7. Graceful Degradation

The system should be designed, where practicable, to degrade predictably rather than fail unpredictably.

Possible responses include:

- Reduced functionality.
- Reduced confidence.
- Increased human supervision.
- Reduced autonomy.
- Fallback algorithms or modes.
- Safe-state transition.
- Suspension of consequential functions.

The appropriate response should depend on consequence and mission context.

## 8. Data Freshness

Disconnected operation can cause information to become stale.

The system should, where practicable:

- Track relevant data age.
- Identify stale information.
- Communicate information limitations.
- Avoid presenting outdated information as current.
- Apply appropriate restrictions where stale data materially affects risk.

## 9. Local Processing

Where local processing is used during disconnected operation, the assurance process should establish:

- Which models and software are locally available.
- Their approved configuration.
- Their dependencies.
- Their limitations.
- Their update status.
- Their permitted functions.

Local operation should remain within the authorised baseline.

## 10. Sensor Degradation

Loss or degradation of sensors can materially affect AI outputs.

The system should identify, where feasible:

- Required sensors.
- Optional sensors.
- Sensor health.
- Missing inputs.
- Reduced confidence.
- Resulting functional limitations.

The absence of a normally required input should not be silently treated as equivalent to normal operation.

## 11. Navigation and Positioning

Where AI functions depend on navigation or positioning information, degraded availability or accuracy should be considered during TEVV.

The capability should have defined behaviour for relevant uncertainty, including restrictions where inaccurate positioning could create unacceptable consequences.

## 12. Computing and Power Constraints

AI capabilities may experience reduced computing capacity, processing latency or power availability.

Assurance should consider the effects on:

- Inference speed.
- Availability.
- Model execution.
- Safety functions.
- Logging.
- Monitoring.
- Human interaction.

Critical protective functions should not depend solely on resource conditions that may not remain available.

## 13. Human Authority During Disconnection

Loss of communications must not automatically remove or redefine human authority.

The authorised operating concept should establish:

- Who retains decision authority.
- Which decisions can continue.
- Which decisions require communication.
- Which actions are prohibited.
- What fallback authority applies.

These arrangements should be established before deployment.

## 14. Autonomy During Degradation

Autonomy should be explicitly addressed under degraded conditions.

Possible governance responses include:

**Normal conditions → authorised autonomy**

**Degraded conditions → increased supervision or reduced autonomy**

**Critical degradation → fallback or suspension**

The exact response should be established through risk assessment and authorisation.

## 15. Uncertainty Communication

Degraded conditions should be reflected in system confidence and human-facing information.

Where uncertainty increases, the system should communicate relevant limitations rather than producing apparently normal outputs with unjustified confidence.

## 16. Fail-Safe Behaviour

Critical systems should have predefined responses to loss of essential dependencies.

A fail-safe response may involve:

- Safe-state transition.
- Function restriction.
- Reduced autonomy.
- Human confirmation.
- Controlled shutdown.
- Suspension of consequential functions.

The selected response should be established through TEVV and operational authorisation.

## 17. Recovery and Resynchronisation

When connectivity or supporting services are restored, the system should not automatically assume that all information is current.

Recovery procedures should address, as applicable:

- Data synchronisation.
- Conflict resolution.
- State reconciliation.
- Log preservation.
- Configuration verification.
- Model or software version verification.
- Human review of significant events.

## 18. Disconnected Logs

Operational records should remain available during disconnected operation where practicable.

Records should preserve sufficient information to reconstruct:

- System state.
- Relevant inputs.
- Outputs.
- Alerts.
- Human interventions.
- Autonomy state.
- Fail-safe events.
- Significant transitions.

Records should be synchronised or transferred when appropriate and technically feasible.

## 19. Degraded Environment TEVV

TEVV should assess foreseeable degraded and disconnected conditions relevant to the capability.

Evaluation should consider:

- Performance degradation.
- Reliability.
- Human control.
- Autonomy transitions.
- Fail-safe behaviour.
- Security.
- Recovery.
- Mission effectiveness.

Testing should include combinations of degraded conditions where these may interact materially.

## 20. Operational Boundaries

The authorisation record should define relevant degraded and disconnected boundaries.

It should establish:

- Conditions under which normal operation continues.
- Conditions requiring restrictions.
- Conditions requiring additional human supervision.
- Conditions requiring reduced autonomy.
- Conditions requiring suspension or fallback.

## 21. Security Considerations

Disconnected or degraded operation can alter the security posture of an AI capability.

Relevant considerations include:

- Delayed security updates.
- Reduced monitoring.
- Stale threat information.
- Local data exposure.
- Unsynchronised configurations.
- Delayed incident reporting.

These risks should connect to the D-AIGAAF AI Security framework.

## 22. Incident Handling

Material degradation should be recorded where it:

- Affects mission performance.
- Changes system risk.
- Causes unexpected behaviour.
- Triggers fail-safe mechanisms.
- Causes loss of human control.
- Exposes previously unknown limitations.

Significant events should feed continuous assurance and change management.

## 23. Change and Reauthorisation

Repeated or material degradation events may indicate that existing environmental assumptions are inadequate.

This may trigger:

- Risk reassessment.
- Additional TEVV.
- Change impact assessment.
- Revised operational boundaries.
- Revalidation.
- Reauthorisation.

## 24. Core Governance Questions

Before authorisation, decision-makers should be able to answer:

1. What happens if communications are lost?
2. What happens if important data becomes stale?
3. What happens if sensors fail or degrade?
4. What happens if computing or power is constrained?
5. What human authority remains during disconnection?
6. How does autonomy change under degradation?
7. What fail-safe behaviour is available?
8. How is state recovered and resynchronised?
9. What evidence demonstrates acceptable degraded behaviour?

## 25. Core Rule

> **Degraded and disconnected operation should be explicitly designed, tested and authorised rather than treated as an exceptional condition outside the governance model.**
