# D-AIGAAF — TEVV Security & Adversarial Evaluation

## 1. Purpose

This document defines how Defence AI capabilities should be evaluated for security, adversarial resilience and resistance to intentional or unintentional manipulation.

The objective is to establish whether the capability can maintain acceptable behaviour, integrity and control when exposed to realistic security threats within its authorised operational context.

## 2. Core Principle

> **Security assurance must demonstrate resilience against credible threats, not merely the absence of known vulnerabilities.**

Defence AI systems should be evaluated as complete socio-technical systems, including models, data, software, hardware, interfaces, dependencies and human users.

## 3. Scope

Security and adversarial TEVV should consider:

- Model security.
- Data security.
- Input integrity.
- Output integrity.
- Software and infrastructure security.
- Supply-chain dependencies.
- Access control.
- Communications.
- Cyber resilience.
- Adversarial manipulation.
- System misuse.
- Insider or privileged-user risks.
- Recovery and fail-safe behaviour.

## 4. Threat-Informed Evaluation

Security testing should be informed by the applicable threat model.

The evaluation should identify:

- Relevant threat actors or sources.
- Attack surfaces.
- Critical assets.
- Security assumptions.
- Potential attack paths.
- Expected consequences.
- Existing controls.
- Residual risks.

Testing should prioritise threats capable of materially affecting safety, mission effectiveness, human authority or system integrity.

## 5. AI-Specific Attack Surfaces

Evaluation should consider attack surfaces such as:

- Training data.
- Fine-tuning data.
- Model files.
- Model interfaces.
- Input pipelines.
- Retrieval or knowledge sources.
- APIs.
- Sensors.
- Communications.
- User interfaces.
- Software dependencies.
- Update mechanisms.
- Monitoring systems.
- Logging and audit infrastructure.

The applicable attack surface will depend on system architecture.

## 6. Adversarial Input Evaluation

Where relevant, testing should assess the effect of deliberately manipulated inputs.

Examples include:

- Altered data.
- Misleading observations.
- Unexpected input combinations.
- Malformed inputs.
- Ambiguous information.
- Inputs designed to exploit known model weaknesses.

The objective is to determine whether the system:

- Detects the condition.
- Maintains acceptable behaviour.
- Communicates uncertainty.
- Rejects unsafe inputs.
- Degrades safely.
- Requires human intervention where necessary.

## 7. Data Integrity Evaluation

Testing should assess whether unauthorised or corrupted data can materially alter system behaviour.

Assessment may include:

- Data modification.
- Data substitution.
- Corruption.
- Provenance failures.
- Unexpected data sources.
- Distribution changes.
- Integrity-control bypass.

Critical data should have appropriate integrity and provenance controls.

## 8. Model Integrity

Where technically applicable, evaluation should assess whether the deployed model corresponds to the authorised baseline.

Controls should support detection of:

- Unauthorised model changes.
- Unexpected model versions.
- Altered model artefacts.
- Configuration changes.
- Unapproved dependencies.

Model integrity should be connected to configuration management and operational authorisation.

## 9. Output Integrity

Security evaluation should consider whether outputs can be:

- Manipulated.
- Misrepresented.
- Altered in transit.
- Presented out of context.
- Attributed incorrectly to the AI.
- Used after their validity has expired.

For consequential applications, users should be able to distinguish authentic system outputs from unauthorised or altered information where practicable.

## 10. Cyber-Resilience

Where AI depends on digital infrastructure, testing should assess behaviour during:

- Service disruption.
- Network degradation.
- Loss of supporting services.
- Compromised dependencies.
- Resource exhaustion.
- Recovery.

The system should operate within defined resilience and degradation boundaries.

## 11. Security Under Degraded Conditions

Where relevant, evaluation should include combinations of:

- Reduced connectivity.
- Limited computing resources.
- Sensor degradation.
- Incomplete data.
- Cyber disruption.
- Increased human workload.

The objective is to establish whether security and safety controls remain effective when normal operating assumptions fail.

## 12. Adversarial Robustness

Testing should evaluate the capability's resistance to credible attempts to cause:

- Incorrect outputs.
- Unsafe recommendations.
- Loss of control.
- Unauthorised actions.
- Misclassification.
- Concealed degradation.
- Misleading confidence.
- Violation of operational constraints.

Results should be assessed against the consequences of failure rather than only technical attack success rates.

## 13. Security Control Verification

Security controls should be verified to establish whether they operate as intended.

Examples include:

- Authentication.
- Authorisation.
- Integrity checking.
- Secure configuration.
- Access restrictions.
- Logging.
- Monitoring.
- Update controls.
- Isolation.
- Fail-safe mechanisms.

A documented control should not be treated as effective without appropriate evidence.

## 14. Human Security Interaction

Security evaluation should assess whether users can recognise and respond to security-relevant system behaviour.

This may include:

- Security alerts.
- Unexpected outputs.
- Integrity warnings.
- Suspicious inputs.
- System degradation.
- Loss of trust indicators.

Users should know when to stop relying on the system and invoke established escalation or incident procedures.

## 15. Fail-Safe and Protective Behaviour

Where a security event could create unacceptable consequences, testing should establish whether the system can transition to an appropriate protective state.

Possible responses include:

- Restricting functionality.
- Reducing autonomy.
- Isolating affected components.
- Requiring human confirmation.
- Switching to a safer mode.
- Suspending operation.

Emergency procedures should be defined and tested in accordance with the authorised operational concept.

## 16. Security Incident Scenarios

Adversarial TEVV should include realistic incident scenarios where appropriate.

Scenarios may assess:

- Detection.
- Containment.
- Human decision-making.
- System response.
- Fail-safe behaviour.
- Recovery.
- Evidence preservation.
- Restoration of trusted operation.

Incident testing should connect directly to the AI security incident and response process.

## 17. Security Acceptance Criteria

Acceptance criteria should be defined before significant testing.

Criteria may address:

- Attack detection.
- Prevention or resistance.
- Integrity preservation.
- Safe degradation.
- Human intervention.
- Recovery.
- Logging.
- Attribution.
- Response time.
- Residual risk.

Criteria should reflect mission consequence and system criticality.

## 18. Findings and Risk Treatment

Security findings should be:

1. Recorded.
2. Risk assessed.
3. Assigned an owner.
4. Given a treatment decision.
5. Retested where appropriate.
6. Tracked to closure or formally accepted.

Critical unresolved findings should be visible to the relevant authorising authority.

## 19. Evidence

Security and adversarial TEVV evidence should include, where appropriate:

- Test plans.
- Threat scenarios.
- Test configurations.
- Attack conditions.
- Results.
- Logs.
- Observed system behaviour.
- Mitigations.
- Retest results.
- Residual limitations.

Evidence should be traceable to the applicable system baseline and threat model.

## 20. Relationship to Operational Authorisation

Security and adversarial evaluation contributes to the assurance basis for operational authorisation.

The relationship is:

**Threat Model → Security Requirement → Adversarial Test → Evidence → Finding → Risk Treatment → Assurance → Authorisation Condition**

Authorisation should not rely solely on a generic cybersecurity assessment where AI-specific behaviour introduces additional risks.

## 21. Revalidation Triggers

Security and adversarial evaluation should be reconsidered following material changes to:

- Model.
- Data.
- Software.
- Hardware.
- Interfaces.
- Dependencies.
- Sensors.
- Communications.
- Security controls.
- Operating environment.
- Autonomy.

New vulnerabilities or credible threat changes may also trigger reassessment.

## 22. Core Rule

> **A Defence AI capability should be trusted only within the security and adversarial conditions that have been adequately evaluated and authorised.**

Security assurance should therefore remain connected to the current threat environment, system baseline, operational context and authorised employment conditions.
