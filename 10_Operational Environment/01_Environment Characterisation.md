# D-AIGAAF — Environment Characterisation

## 1. Purpose

This document defines a structured approach for characterising the operational environment relevant to a Defence AI capability.

The objective is to establish sufficient understanding of environmental conditions, variability, dependencies and constraints to support risk assessment, TEVV and operational authorisation.

## 2. Core Principle

> **Environmental assumptions that can materially affect AI behaviour should be identified, characterised and tested rather than left implicit.**

## 3. Scope

Environment characterisation should consider factors relevant to the specific capability and mission, including:

- Physical conditions.
- Terrain and infrastructure.
- Weather and atmospheric conditions.
- Illumination and visibility.
- Sensor conditions.
- Electromagnetic conditions.
- Communication availability.
- Navigation and positioning.
- Information availability and quality.
- Computing and power constraints.
- Human operating conditions.
- Cyber and adversarial conditions.
- External system dependencies.

Not every factor will be relevant to every capability.

## 4. Environment Categories

D-AIGAAF may categorise environmental factors into:

| Category | Examples |
|---|---|
| Physical | Terrain, infrastructure, obstacles |
| Atmospheric | Weather, temperature, precipitation, visibility |
| Sensor | Noise, occlusion, degradation, calibration |
| Electromagnetic | Interference, disruption, signal availability |
| Information | Missing, delayed, inconsistent or misleading information |
| Communications | Connected, intermittent, degraded or disconnected |
| Navigation | Availability, accuracy and uncertainty |
| Computing | Processing, memory, power and latency constraints |
| Human | Workload, time pressure, training and decision context |
| Adversarial | Manipulation, deception, disruption and attack |
| Dependency | External services, systems, data or infrastructure |

## 5. Intended Operating Environment

For each capability, the intended operating environment should be explicitly documented.

It should describe:

- Expected operating conditions.
- Expected environmental variability.
- Supporting infrastructure.
- External dependencies.
- Connectivity assumptions.
- Human roles.
- Relevant constraints.
- Conditions outside the intended envelope.

## 6. Environmental Variables

Environmental variables should be identified where changes could influence:

- AI inputs.
- Model performance.
- System reliability.
- Detection or classification accuracy.
- Decision quality.
- Human interpretation.
- Autonomy.
- Safety.
- Security.
- Mission effectiveness.

The level of detail should be proportionate to risk.

## 7. Environmental Variability

Characterisation should account for meaningful variation rather than relying solely on average or ideal conditions.

Where relevant, consider:

- Best-case conditions.
- Nominal conditions.
- Challenging conditions.
- Degraded conditions.
- Boundary conditions.
- Conditions outside the authorised envelope.

The objective is not to test every possible environment, but to understand the conditions that could materially change system behaviour.

## 8. Environmental Dependencies

Dependencies should be documented where capability performance relies upon:

- Communications.
- Positioning services.
- External data.
- Cloud or remote services.
- Power availability.
- Supporting sensors.
- Other software or systems.
- Human operators or supervisors.

Each material dependency should have an identified failure or degradation response.

## 9. Environmental Assumptions

Environmental assumptions should be explicitly recorded.

Examples include assumptions concerning:

- Sensor availability.
- Data freshness.
- Connectivity.
- Navigation accuracy.
- Environmental visibility.
- Computing resources.
- Human availability.

Assumptions that are unverified or weakly supported should be identified as assurance concerns.

## 10. Representative Conditions

TEVV should use representative environmental conditions appropriate to the intended mission.

Representative conditions should reflect the characteristics most likely to affect:

- System performance.
- Reliability.
- Security.
- Human control.
- Autonomy.
- Mission effectiveness.

Where representative conditions cannot be reproduced fully, limitations should be documented.

## 11. Boundary Conditions

Boundary conditions are conditions near the limits of demonstrated system capability.

These should be identified and assessed because small changes may cause disproportionate degradation.

Examples include:

- Reduced visibility.
- Increasing sensor noise.
- Increasing communication latency.
- Reduced positioning confidence.
- Reduced computing availability.
- Increased information uncertainty.

## 12. Unknown and Untested Conditions

Conditions that have not been sufficiently evaluated should be explicitly identified.

An untested condition should not automatically be interpreted as:

- Safe.
- Unsafe.
- Equivalent to a tested condition.

Instead, its uncertainty should inform risk assessment and operational restrictions.

## 13. Environmental Threats

Environmental threats should be considered where they can affect AI behaviour.

These may include:

- Deliberate deception.
- Manipulated inputs.
- Sensor interference.
- Communications disruption.
- Cyber compromise.
- Unexpected environmental phenomena.

Threat characterisation should connect with the D-AIGAAF AI Security and Risk & Autonomy sections.

## 14. Human Environment

The operational environment includes the human decision environment.

Characterisation should consider:

- Number and role of personnel.
- Decision authority.
- Workload.
- Time available for review.
- Training and AI literacy.
- Interface conditions.
- Ability to challenge recommendations.
- Ability to intervene.
- Consequences of automation bias or over-reliance.

## 15. Environment and Data

Environmental conditions can change the quality and distribution of AI inputs.

Assessment should consider:

- Missing data.
- Delayed data.
- Noisy data.
- Distribution shifts.
- Sensor degradation.
- Unexpected inputs.
- Data outside the development domain.

These factors should connect with the D-AIGAAF Data & Information controls.

## 16. Environment and Autonomy

Environmental predictability should influence autonomy decisions.

Where environmental uncertainty increases, the organisation should consider:

- Additional human confirmation.
- Reduced autonomy.
- Restricted functions.
- Increased monitoring.
- Transition to a fallback mode.
- Suspension of consequential functions.

## 17. Environment Profile

A capability should have an environment profile describing:

**Environment → Conditions → Dependencies → Risks → Controls → Evidence → Authorised Boundaries**

The profile should be maintained as a controlled lifecycle record.

## 18. Characterisation Evidence

Evidence supporting environment characterisation may include:

- Technical tests.
- Simulations.
- Operational trials.
- Historical performance data.
- Environmental measurements.
- Human factors evaluations.
- Security evaluations.
- Reliability assessments.

Evidence should be traceable to the capability baseline and conditions under which it was obtained.

## 19. Environmental Change

Changes to the operating environment should be assessed where they could materially affect system behaviour.

Triggers may include:

- New operating conditions.
- New dependencies.
- Changed infrastructure.
- Changed threat conditions.
- Significant changes in information availability.
- Newly observed failure modes.

Such changes may trigger change impact assessment, revalidation or reauthorisation.

## 20. Governance Review

Environment characterisation should be reviewed by appropriate technical, operational, assurance and authority stakeholders.

The review should establish whether:

- Relevant environmental factors have been identified.
- Important assumptions are explicit.
- Dependencies are understood.
- Evidence is sufficient.
- Environmental boundaries are clear.
- Degradation responses are defined.
- Remaining uncertainty is acceptable.

## 21. Core Questions

Before operational authorisation, decision-makers should be able to answer:

1. What environments has the capability been designed for?
2. What environments has it actually been tested in?
3. Which environmental variables materially affect performance?
4. What dependencies must remain available?
5. What conditions are outside the authorised envelope?
6. What happens when environmental assumptions fail?
7. How does environmental uncertainty affect human control and autonomy?
8. What evidence supports the environmental boundaries?

## 22. Core Rule

> **The operational environment should be treated as part of the system's assurance context, not merely as background information.**
