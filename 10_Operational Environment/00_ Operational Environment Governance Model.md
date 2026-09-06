# D-AIGAAF — Operational Environment Governance Model

## 1. Purpose

This document establishes the governance model for assessing and controlling the operational environment in which a Defence AI capability is intended to operate.

The objective is to ensure that AI assurance and operational authorisation are based not only on laboratory performance, but on demonstrated behaviour under relevant operational conditions.

## 2. Core Principle

> **An AI capability is not operationally assured merely because it performs successfully in a controlled test environment. Its behaviour must be understood within the environments in which it may actually be employed.**

Operational environment is therefore a core assurance and authorisation consideration.

## 3. Scope

Operational environment assessment should consider, as applicable:

- Physical environment.
- Electromagnetic environment.
- Information environment.
- Communication availability.
- Sensor conditions.
- Navigation and positioning conditions.
- Weather and atmospheric conditions.
- Terrain and infrastructure.
- Human operating conditions.
- Cyber and adversarial conditions.
- Resource constraints.
- Degraded and disconnected conditions.

D-AIGAAF remains generic and unclassified and does not prescribe specific military operating procedures.

## 4. Operational Environment Definition

Before deployment, the intended operational environment should be explicitly defined.

The definition should identify:

- Where the capability may operate.
- Under what environmental conditions.
- With which supporting systems.
- With what connectivity assumptions.
- With what human roles.
- Against what reasonably foreseeable disturbances and threats.

Unstated environmental assumptions should be treated as assurance gaps where they could materially affect system behaviour.

## 5. Environment Characterisation

The organisation should identify environmental characteristics that may influence:

- Data quality.
- Sensor performance.
- Model performance.
- Communications.
- Decision latency.
- Human understanding.
- Autonomy.
- Safety.
- Security.
- Mission effectiveness.

Characterisation should be proportionate to mission consequence and system criticality.

## 6. Environmental Variability

Assessment should account for meaningful variation rather than relying on a single representative condition.

Relevant variability may include:

- Different weather conditions.
- Different terrain or physical settings.
- Changing illumination.
- Sensor degradation.
- Intermittent communications.
- Different information availability.
- Changing operational tempo.
- Different levels of human workload.

Where environmental variation can materially change AI behaviour, it should be incorporated into TEVV and operational monitoring.

## 7. Degraded Environment

Defence AI capabilities should be assessed for foreseeable degraded conditions.

Examples include:

- Loss or reduction of communications.
- Reduced sensor availability.
- Missing or corrupted data.
- Increased latency.
- Reduced computing resources.
- Navigation uncertainty.
- Partial system failure.

The system should have defined behaviour for conditions outside its normal operating assumptions.

## 8. Disconnected Operation

Where a capability may operate without continuous connectivity, the governance process should establish:

- What functions remain available.
- What information becomes unavailable.
- How uncertainty changes.
- What decisions are prohibited or restricted.
- How synchronisation is restored.
- How stale information is identified.

Connectivity assumptions should never be treated as permanent unless they are justified by the intended operating context.

## 9. Adversarial Environment

Operational environment assessment should consider foreseeable attempts to manipulate or degrade AI-dependent functions.

This may include:

- Deceptive inputs.
- Manipulated information.
- Unexpected data conditions.
- Cyber compromise.
- Sensor interference.
- Deliberate disruption.

The assessment should focus on resilience, detection, graceful degradation and preservation of human authority.

## 10. Human Operating Environment

The environment includes the people who operate, supervise, interpret or act upon AI outputs.

Assessment should consider:

- Workload.
- Training.
- Time pressure.
- Interface usability.
- Decision authority.
- Alert fatigue.
- Automation bias.
- Situational awareness.
- Ability to challenge AI recommendations.
- Ability to intervene or override.

Human performance should be considered alongside technical performance.

## 11. Environmental Boundaries

The authorised operating envelope should define relevant environmental boundaries.

Where a system moves outside those boundaries, predefined responses may include:

- Continued operation with restrictions.
- Increased human supervision.
- Reduced autonomy.
- Safe degradation.
- Transition to a fallback mode.
- Suspension of the affected function.

The appropriate response should depend on risk and mission context.

## 12. Environmental Uncertainty

Not all operational conditions can be predicted in advance.

The framework should therefore distinguish between:

- Known conditions.
- Tested conditions.
- Reasonably foreseeable conditions.
- Untested conditions.
- Conditions outside the authorised envelope.

Unknown or insufficiently tested conditions should not automatically be treated as equivalent to demonstrated conditions.

## 13. Environment-Specific TEVV

TEVV should demonstrate performance under conditions relevant to the intended operating environment.

Evidence should address, as appropriate:

- Accuracy.
- Reliability.
- Robustness.
- Security.
- Human-AI interaction.
- Autonomy.
- Mission effectiveness.
- Failure and degradation behaviour.

The required depth of testing should increase with consequence and autonomy.

## 14. Environmental Baseline

A baseline should be established describing the environmental assumptions supporting authorisation.

The baseline may include:

- Environmental conditions.
- Sensor assumptions.
- Connectivity assumptions.
- Supporting infrastructure.
- Human roles.
- External dependencies.
- Known limitations.

Material changes to the baseline should be assessed through change management.

## 15. Operational Environment Monitoring

Where environmental conditions can materially affect system behaviour, relevant indicators should be monitored during employment.

Monitoring may identify:

- Environmental drift.
- Performance degradation.
- Unexpected operating conditions.
- Increased uncertainty.
- Loss of supporting dependencies.
- Emergence of previously untested conditions.

Significant deviations should be linked to operational controls and escalation procedures.

## 16. Environment and Autonomy

Permitted autonomy should depend partly on environmental predictability and controllability.

As environmental uncertainty increases, the organisation should consider whether to:

- Increase human involvement.
- Reduce autonomy.
- Restrict system functions.
- Require additional confirmation.
- Suspend consequential actions.

Autonomy should therefore be treated as conditional rather than purely a technical system characteristic.

## 17. Environment and Mission Risk

The same AI capability may have different risk profiles in different environments.

Risk assessment should therefore consider:

**Capability × Mission × Environment × Autonomy × Human Authority**

A capability authorised in one environment should not automatically be assumed to be authorised in another.

## 18. Operational Trials

Where practicable, operational trials should expose the capability to representative conditions before authorisation.

Trials should seek evidence about:

- Realistic performance.
- Human interaction.
- System dependencies.
- Degradation behaviour.
- Environmental limitations.
- Unexpected failure modes.

Operational trials should complement, not replace, controlled technical testing.

## 19. Environmental Failure and Degradation

The system should have defined responses when environmental conditions exceed demonstrated capability.

Responses should be proportionate to consequence and may include:

- Warning.
- Increased supervision.
- Reduced functionality.
- Reduced autonomy.
- Safe-state transition.
- Suspension.
- Fail-safe action.

## 20. Evidence and Authorisation

Operational environment evidence should form part of the assurance package supporting operational authorisation.

The authorisation record should identify relevant environmental limitations and conditions where these materially affect safe and effective employment.

## 21. Change and Reauthorisation

Changes to the operational environment, or discovery of previously unknown environmental effects, may trigger:

- Risk reassessment.
- Additional TEVV.
- Change impact assessment.
- Revalidation.
- Restriction of employment.
- Reauthorisation.

The response should be proportionate to the significance of the change.

## 22. Core Governance Questions

Before authorisation, decision-makers should be able to answer:

1. Where is the capability authorised to operate?
2. Under what conditions has it been tested?
3. Which conditions remain untested?
4. What assumptions does the capability depend upon?
5. What happens when those assumptions fail?
6. How does environmental uncertainty affect autonomy?
7. What human intervention remains available?
8. What monitoring detects environmental degradation?
9. What conditions trigger restriction, suspension or reauthorisation?

## 23. Core Rule

> **Operational authorisation should be bounded by demonstrated capability, understood environmental conditions and clearly defined responses to uncertainty and degradation.**
