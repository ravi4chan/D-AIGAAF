# D-AIGAAF — Operational Environment Monitoring

## 1. Purpose

This document defines the governance approach for monitoring the operational environment of Defence AI capabilities after deployment and during authorised employment.

The objective is to detect material changes in environmental conditions, dependencies, system behaviour and operational context that could affect safety, security, mission effectiveness, human control or the validity of the operational authorisation.

## 2. Core Principle

> **Operational environment monitoring is a continuous assurance function, not merely an observation activity.**

A capability that remains unchanged technically may nevertheless become unsuitable if the environment in which it operates changes materially.

## 3. Monitoring Scope

Monitoring should consider, as applicable:

- Physical environment.
- Terrain and weather.
- Illumination and visibility.
- Sensor conditions.
- Electromagnetic environment.
- Communications.
- Navigation or positioning.
- Information environment.
- Data availability and freshness.
- Computing and power dependencies.
- Human operating conditions.
- Adversarial conditions.
- Mission context.
- External dependencies.

## 4. Environmental Baseline

Each authorised capability should have an appropriate environmental baseline describing:

- Assumed conditions.
- Demonstrated conditions.
- Known limitations.
- Critical dependencies.
- Environmental boundaries.
- Relevant indicators.
- Expected system behaviour.

Monitoring should identify material deviation from this baseline.

## 5. Environmental Indicators

Indicators should be selected according to mission and system risk.

Examples include:

- Sensor degradation.
- Communication loss or instability.
- Significant data-quality deterioration.
- Data staleness.
- Navigation uncertainty.
- Unexpected environmental conditions.
- Computing-resource degradation.
- Power limitations.
- Changes in human workload.
- Anomalous system behaviour.
- Adversarial interference indicators.

## 6. Monitoring Levels

Monitoring intensity should be proportionate to consequence and autonomy.

A governance model may distinguish:

### Routine monitoring

For normal operation within a well-understood environment.

### Enhanced monitoring

For elevated uncertainty, challenging conditions or higher-consequence use.

### Continuous or near-real-time monitoring

For highly consequential capabilities, autonomous functions or environments where rapid deterioration could create unacceptable risk.

## 7. Environmental Boundary Monitoring

The system or operating organisation should identify when conditions approach or cross authorised environmental boundaries.

Boundary monitoring should support:

- Warning.
- Escalation.
- Reduction of capability.
- Reduction of autonomy.
- Transition to fallback.
- Human intervention.
- Suspension where required.

## 8. Degraded and Disconnected Conditions

Monitoring should identify degradation in critical dependencies, including:

- Communications.
- Data.
- Sensors.
- Navigation.
- Computing.
- Power.
- Supporting systems.

Where monitoring becomes unavailable because of disconnection, the authorised fallback behaviour should remain defined.

## 9. Adversarial Environment Monitoring

Where relevant, monitoring should detect indicators of deliberate manipulation or disruption.

This may include:

- Unexpected input patterns.
- Sensor inconsistencies.
- Information anomalies.
- Communications disruption.
- Integrity failures.
- Unexpected model or system behaviour.

Environmental monitoring should complement, not replace, AI security monitoring.

## 10. Human Environment Monitoring

The human operating environment should also be monitored where it materially affects safe and effective use.

Relevant indicators may include:

- Excessive workload.
- Loss of situational awareness.
- Automation bias.
- Confusion regarding system recommendations.
- Difficulty exercising intervention or override.
- Insufficient staffing or competence.
- Excessive reliance on system outputs.

## 11. Monitoring and Uncertainty

Environmental monitoring should support explicit communication of uncertainty.

Where environmental conditions exceed the evidence base, the system or responsible personnel should not imply greater confidence than is justified.

The response may include:

- Confidence reduction.
- Warning.
- Request for human confirmation.
- Reduced autonomy.
- Fallback.
- Suspension.

## 12. Monitoring Thresholds

Where practical, predefined thresholds or decision criteria should be established for material environmental changes.

Thresholds should identify:

- Indicator.
- Normal range.
- Warning condition.
- Critical condition.
- Required response.
- Responsible authority.

Thresholds should be reviewed when operational experience demonstrates that they are inadequate.

## 13. Monitoring Responsibilities

Responsibilities should be explicitly assigned.

Depending on the capability, responsibilities may include:

- Operator.
- Supervisor.
- Operational AI Advisor.
- System owner.
- Technical authority.
- Security authority.
- Command authority.
- Assurance authority.

Monitoring responsibility should not be assumed merely because technical telemetry exists.

## 14. Response to Environmental Change

When a material environmental change is detected, the response should be proportionate to risk.

Possible responses include:

1. Continue with normal monitoring.
2. Issue an operator warning.
3. Increase human supervision.
4. Restrict system functionality.
5. Reduce autonomy.
6. Transition to a safe or fallback mode.
7. Suspend the affected capability.
8. Initiate incident or assurance procedures.

## 15. Monitoring Records

Material environmental observations should be recorded where required.

Records may include:

- Time and location/context.
- Environmental condition.
- Relevant indicators.
- System state.
- Autonomy state.
- Human response.
- System response.
- Decision taken.
- Outcome.
- Follow-up action.

Records should support later investigation and assurance.

## 16. Monitoring and Operational AI Advisor

The Operational AI Advisor may support interpretation of environmental monitoring by helping connect:

**Environmental condition → AI behaviour → Mission implication → Risk → Recommended response**

The advisor does not replace operational command authority.

## 17. Monitoring and Continuous Assurance

Environmental monitoring should feed the continuous assurance process.

Material findings should be evaluated for possible:

- Risk reassessment.
- TEVV activity.
- Configuration review.
- Change impact assessment.
- Revalidation.
- Reauthorisation.
- Operational restriction.

## 18. Environmental Change Management

Not every environmental change requires reauthorisation.

The organisation should assess whether the change:

- Remains within the authorised envelope.
- Changes material assumptions.
- Changes system risk.
- Affects autonomy.
- Introduces new dependencies.
- Invalidates existing evidence.

Material changes should trigger the appropriate governance process.

## 19. Monitoring During Initial Operational Use

Where appropriate, newly authorised capabilities should receive enhanced monitoring during early operational employment.

The objective is to identify:

- Differences between trial and operational conditions.
- Previously unknown failure modes.
- Unexpected human-AI interaction.
- Environmental effects not captured during TEVV.
- Emerging operational risks.

## 20. Monitoring Failure

Monitoring mechanisms themselves can fail.

The governance process should therefore establish:

- Monitoring dependencies.
- Monitoring failure indicators.
- Fallback arrangements.
- Human responsibilities.
- Escalation procedures.

Loss of monitoring capability should not silently be treated as normal operation when monitoring is an assurance condition.

## 21. Governance Questions

Decision-makers should be able to answer:

1. What environmental conditions are being monitored?
2. Which conditions are safety- or mission-critical?
3. What indicates that the capability is approaching an environmental boundary?
4. What happens when a boundary is crossed?
5. Who receives the warning?
6. Who can restrict or suspend the capability?
7. How does monitoring affect autonomy?
8. What happens if monitoring itself fails?
9. How are observations recorded?
10. What findings trigger revalidation or reauthorisation?

## 22. Core Rule

> **A Defence AI capability remains assured only while the conditions supporting its authorisation remain sufficiently understood, monitored and controlled.**
