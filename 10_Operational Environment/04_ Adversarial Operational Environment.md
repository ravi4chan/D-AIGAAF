# D-AIGAAF — Adversarial Operational Environment

## 1. Purpose

This document defines governance considerations for Defence AI capabilities operating in environments where deliberate attempts may be made to deceive, manipulate, disrupt or compromise the information, systems or conditions on which AI behaviour depends.

The objective is to ensure that adversarial conditions are incorporated into risk assessment, TEVV, operational controls and continuous assurance.

## 2. Core Principle

> **A Defence AI capability should be assured not only against accidental degradation, but also against reasonably foreseeable deliberate attempts to influence or disrupt its behaviour.**

## 3. Scope

The adversarial operational environment may include threats to:

- Data.
- Sensors.
- Communications.
- Navigation.
- Software.
- Models.
- Interfaces.
- Supporting systems.
- Human decision-making.
- Operational information.

This document remains generic and unclassified and does not prescribe tactical methods for conducting attacks or counter-attacks.

## 4. Adversarial Environment Characterisation

The intended operating environment should identify reasonably foreseeable adversarial conditions that could materially affect:

- AI inputs.
- AI outputs.
- System availability.
- System integrity.
- Human understanding.
- Autonomy.
- Mission effectiveness.
- Safety.

The assessment should be proportionate to mission consequence and system criticality.

## 5. Threat Categories

Adversarial conditions may include:

| Category | Potential Effect |
|---|---|
| Data manipulation | Incorrect or misleading AI outputs |
| Input deception | Misclassification or erroneous inference |
| Sensor interference | Reduced perception or confidence |
| Communication disruption | Loss of information or coordination |
| Navigation interference | Increased positioning uncertainty |
| Software compromise | Unauthorised system behaviour |
| Model compromise | Altered or degraded model behaviour |
| Interface manipulation | Misleading human interpretation |
| Information manipulation | Incorrect situational understanding |

The table is illustrative rather than exhaustive.

## 6. Adversarial Assumptions

Relevant assumptions should be documented explicitly.

These may include assumptions concerning:

- Trustworthiness of data.
- Sensor integrity.
- Communications.
- External information.
- Software dependencies.
- Model provenance.
- Human interpretation.

Assumptions that cannot be adequately supported should inform risk treatment and operational restrictions.

## 7. Adversarial Inputs

AI capabilities should be evaluated against inputs that differ materially from expected operating conditions.

The objective is to determine whether the system:

- Detects abnormal inputs.
- Communicates uncertainty.
- Degrades predictably.
- Rejects or restricts unsafe outputs where appropriate.
- Preserves human authority.

Testing should be conducted in controlled environments consistent with applicable safety and security requirements.

## 8. Data Integrity

Where AI decisions depend on external or operational data, assurance should consider whether that data can be:

- Manipulated.
- Corrupted.
- Delayed.
- Duplicated.
- Removed.
- Mislabelled.

Controls should address the resulting integrity and decision risks.

## 9. Sensor and Perception Resilience

AI systems relying on sensors should be evaluated for foreseeable degradation and deception affecting those sensors.

Assessment should consider:

- Reduced signal quality.
- Conflicting sensor information.
- Missing observations.
- Unexpected observations.
- Sensor failure.
- Sensor compromise.

The system should not represent uncertain perception as reliable fact.

## 10. Communications Threats

Communication disruption may affect both AI performance and human control.

The governance model should address:

- Loss of connectivity.
- Intermittent communication.
- Increased latency.
- Incorrect or delayed information.
- Loss of supervisory links.

Relevant responses should be linked to the degraded and disconnected operating model.

## 11. Model and Software Integrity

The organisation should maintain confidence that the deployed AI model and supporting software correspond to the authorised baseline.

Controls should support:

- Configuration integrity.
- Version control.
- Provenance.
- Change detection.
- Controlled updates.
- Revalidation after material changes.

Unexpected model or software changes should be treated as potential assurance events.

## 12. Human Decision-Making Under Adversarial Conditions

Adversarial environments may deliberately exploit human limitations.

Assessment should consider:

- Automation bias.
- Excessive trust in AI outputs.
- Misleading confidence.
- Alert overload.
- Time pressure.
- Conflicting information.
- Reduced situational awareness.

Human decision-makers should retain the ability to question, reject and override AI recommendations where authorised.

## 13. Situational Awareness

AI should support rather than unnecessarily undermine human situational awareness.

Where AI outputs materially influence consequential decisions, users should have sufficient information to understand:

- What the system is reporting.
- How certain it is.
- What relevant limitations apply.
- What information may be missing.
- Whether the system is operating within its authorised envelope.

## 14. Uncertainty and Anomaly Detection

Where practicable, systems should identify conditions indicating:

- Unexpected inputs.
- Distribution shifts.
- Sensor inconsistency.
- Model uncertainty.
- Abnormal system behaviour.
- Environmental conditions outside the tested domain.

Detection should trigger an appropriate predefined response.

## 15. Adversarial TEVV

TEVV should evaluate relevant adversarial conditions appropriate to the capability.

Evaluation may include:

- Input robustness.
- Data integrity.
- Sensor resilience.
- System integrity.
- Cyber resilience.
- Human-AI interaction.
- Autonomy behaviour.
- Degraded operation.
- Recovery behaviour.

The evaluation should focus on assurance outcomes rather than merely demonstrating resistance to a fixed set of tests.

## 16. Red Teaming

Independent or appropriately separated adversarial evaluation may be used to identify weaknesses that conventional testing does not reveal.

Red-team activities should be:

- Authorised.
- Controlled.
- Documented.
- Traceable.
- Conducted within applicable safety and security constraints.

Findings should feed risk treatment and assurance.

## 17. Operational Boundaries

Where adversarial conditions exceed demonstrated resilience, operational restrictions should be defined.

Possible responses include:

- Increased human supervision.
- Reduced autonomy.
- Restricted functions.
- Fallback operation.
- Suspension.
- Fail-safe transition.

## 18. Adversarial Environment and Autonomy

Autonomy should be evaluated in relation to adversarial uncertainty.

Greater uncertainty about the integrity of inputs, system state or environment may require:

- Greater human involvement.
- Reduced autonomy.
- Additional confirmation.
- More restrictive operating conditions.

Autonomy should therefore remain conditional on the integrity and predictability of the operating environment.

## 19. Continuous Monitoring

Adversarial conditions may evolve after authorisation.

Continuous assurance should monitor for:

- New attack patterns.
- Unexpected system behaviour.
- Changes in threat conditions.
- Repeated anomalies.
- Degradation in resilience.
- Newly identified dependencies.

New evidence should be incorporated into risk and authorisation decisions.

## 20. Incident Response

Material adversarial events should be recorded and investigated.

Relevant records may include:

- Event time.
- System baseline.
- Environmental conditions.
- Relevant inputs.
- AI outputs.
- Human actions.
- Autonomy state.
- Security alerts.
- Fail-safe actions.
- Recovery actions.

Records should support accountability and future assurance.

## 21. Supply Chain Relationship

Adversarial risk can originate through system components or dependencies.

The assessment should connect with:

- Supplier assurance.
- Component provenance.
- Software integrity.
- Model provenance.
- Dependency management.
- Change control.

## 22. Revalidation and Reauthorisation

Significant adversarial findings may trigger:

- Risk reassessment.
- Additional TEVV.
- Corrective controls.
- Restricted employment.
- Revalidation.
- Reauthorisation.

Repeated unexplained anomalies should not be normalised merely because the system continues to function.

## 23. Governance Questions

Before authorisation, decision-makers should be able to answer:

1. What adversarial conditions are reasonably foreseeable?
2. Which inputs or dependencies could be manipulated?
3. How does the system detect abnormal conditions?
4. How is uncertainty communicated?
5. What happens when integrity cannot be established?
6. How does adversarial uncertainty affect autonomy?
7. What human controls remain available?
8. What evidence demonstrates resilience?
9. What events trigger restriction, suspension or reauthorisation?

## 24. Core Rule

> **Adversarial resilience should be demonstrated, monitored and governed as part of operational assurance—not treated solely as a cybersecurity concern.**
