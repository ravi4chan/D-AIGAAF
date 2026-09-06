# D-AIGAAF — TEVV Governance Model

## 1. Purpose

This document establishes the governance model for **Test, Evaluation, Verification and Validation (TEVV)** of Defence AI capabilities.

TEVV provides evidence that an AI capability is suitable for its intended mission, operating environment, risk level, autonomy level, and authorised conditions.

## 2. Core Principle

> **A Defence AI capability should not be operationally authorised solely because it works in development or laboratory conditions. It should demonstrate sufficient evidence of performance, robustness, security, safety, human control, and mission suitability in the conditions for which it is intended to operate.**

## 3. TEVV Objectives

TEVV should establish, as applicable:

- Whether requirements have been satisfied.
- Whether the system performs as intended.
- Whether performance remains reliable under relevant conditions.
- Whether known limitations are understood.
- Whether security controls are effective.
- Whether human control is meaningful.
- Whether autonomy remains within authorised boundaries.
- Whether the capability is suitable for its intended mission.
- Whether residual risk is acceptable.
- Whether sufficient evidence exists for operational authorisation.

## 4. Eight TEVV Dimensions

D-AIGAAF uses eight primary TEVV dimensions:

1. **Technical Performance**
2. **Reliability & Robustness**
3. **Adversarial Resilience**
4. **Operational Environment**
5. **Human-AI Interaction**
6. **Security & Integrity**
7. **Autonomy & Control**
8. **Mission Effectiveness**

These dimensions should be applied proportionately to the use case.

## 5. Technical Performance

Assessment should determine whether the capability meets defined technical requirements.

Depending on the system, this may include:

- Accuracy.
- Precision and recall.
- Detection performance.
- Classification performance.
- Latency.
- Availability.
- Throughput.
- Resource consumption.
- Relevant error rates.

Metrics should be selected according to mission purpose rather than treated as universally applicable.

## 6. Reliability & Robustness

Testing should assess behaviour when conditions differ from ideal development conditions.

Relevant factors may include:

- Noisy or incomplete data.
- Sensor degradation.
- Environmental variation.
- Missing inputs.
- Unexpected inputs.
- Hardware limitations.
- Software faults.
- Repeated operation.
- Distribution shift.

The objective is to understand not only average performance but also failure behaviour.

## 7. Adversarial Resilience

Where relevant, TEVV should assess resilience against deliberate attempts to manipulate or degrade AI performance.

This may include:

- Adversarial inputs.
- Data manipulation.
- Prompt or input manipulation.
- Model exploitation.
- Evasion.
- Data poisoning.
- Dependency compromise.
- Deliberate degradation of supporting information.

Testing should be appropriate to the threat model and security classification of the system.

## 8. Operational Environment

AI should be evaluated in environments representative of intended employment.

Relevant conditions may include:

- Intermittent or absent communications.
- Limited connectivity.
- Degraded sensors.
- High or low environmental extremes.
- Electromagnetic interference.
- Cyber disruption.
- Limited computing resources.
- Variable terrain or operating conditions.
- Adversarial conditions.

The objective is to establish whether the system remains within acceptable performance and risk boundaries outside ideal conditions.

## 9. Human-AI Interaction

TEVV should evaluate whether personnel can use the system safely and effectively.

Assessment may include:

- Understanding of outputs.
- Interpretation of uncertainty.
- Automation bias.
- Workload.
- Alert behaviour.
- Decision time.
- Ability to reject recommendations.
- Ability to intervene.
- Override effectiveness.
- Situational awareness.

Human performance is therefore part of system assurance, not an external consideration.

## 10. Security & Integrity

Testing should assess whether the capability and its supporting components preserve:

- Confidentiality where required.
- Integrity.
- Availability.
- Authentication and access control.
- Software integrity.
- Model integrity.
- Data integrity.
- Configuration integrity.
- Supply-chain integrity.

Security testing should be connected to the applicable AI threat model.

## 11. Autonomy & Control

For capabilities involving autonomous or semi-autonomous functions, TEVV should establish:

- Actual autonomy behaviour.
- Compliance with authorised boundaries.
- Correct operation of constraints.
- Transition behaviour.
- Human intervention effectiveness.
- Fail-safe behaviour.
- Response to loss of required inputs.
- Response to degraded conditions.
- Behaviour when operating assumptions fail.

Autonomy should be tested as actually implemented, not inferred from design documentation.

## 12. Mission Effectiveness

Technical performance does not automatically establish mission effectiveness.

Assessment should consider whether the AI capability contributes meaningfully to the intended mission outcome, including:

- Operational utility.
- Decision quality.
- Timeliness.
- Reliability of mission outputs.
- Human workload.
- Integration with existing processes.
- Consequences of failure.
- Performance under realistic mission conditions.

## 13. Verification and Validation

**Verification** should establish whether the system was built according to specified requirements.

**Validation** should establish whether the resulting capability is appropriate for its intended use and operational context.

Both should be maintained because technical conformance alone does not demonstrate operational suitability.

## 14. Independence

The degree of independence in TEVV should be proportionate to risk.

Higher-consequence systems should receive greater separation between:

- Development.
- Testing.
- Assurance.
- Operational authorisation.

Where complete independence is impractical, the limitation should be identified and managed.

## 15. Evidence-Based Assurance

TEVV should produce objective evidence rather than relying primarily on assertions.

Evidence may include:

- Test results.
- Evaluation reports.
- Validation results.
- Scenario results.
- Security assessments.
- Human factors assessments.
- Operational trials.
- Failure analysis.
- Configuration records.
- Known limitations.

Evidence should be traceable to requirements and risks.

## 16. Failure-Oriented Testing

Testing should not focus only on successful operation.

Where justified by risk, TEVV should deliberately examine:

- Incorrect outputs.
- False positives and false negatives.
- Unexpected inputs.
- Uncertainty.
- System degradation.
- Boundary conditions.
- Adversarial behaviour.
- Loss of supporting services.
- Human intervention.
- Fail-safe activation.

Understanding failure behaviour is essential for responsible operational authorisation.

## 17. TEVV and Operational Authorisation

TEVV evidence should inform the operational-authorisation decision.

The authorising authority should be able to determine:

- What was tested.
- Under what conditions.
- What passed.
- What failed.
- What remains uncertain.
- What limitations remain.
- What residual risk remains.
- Whether the evidence supports the proposed mission and autonomy.

## 18. Revalidation After Change

Material changes may invalidate previous TEVV evidence.

Revalidation should therefore consider:

- What changed.
- Which evidence remains applicable.
- Which tests must be repeated.
- Whether new failure modes are possible.
- Whether autonomy or human-control characteristics changed.
- Whether operational authorisation remains valid.

## 19. TEVV Records

The TEVV record should identify, as appropriate:

- Requirement.
- Risk.
- Test or evaluation objective.
- Method.
- Test environment.
- System baseline.
- Data/configuration used.
- Result.
- Limitation.
- Evidence reference.
- Assessor.
- Date.
- Disposition.

## 20. Core Principle

D-AIGAAF treats TEVV as a continuous assurance activity rather than a single gate before deployment.

The intended relationship is:

**Requirements → Risk → Test & Evaluation → Evidence → Assurance → Operational Authorisation → Monitoring → Revalidation**

A capability should remain subject to TEVV throughout its operational lifecycle when changes, incidents, emerging risks, or new operating conditions could affect the validity of existing evidence.
