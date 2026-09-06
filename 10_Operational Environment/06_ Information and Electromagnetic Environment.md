# D-AIGAAF — Information and Electromagnetic Environment

## 1. Purpose

This document defines governance considerations for the information and electromagnetic conditions that may affect a Defence AI capability.

The objective is to ensure that AI assurance accounts for the availability, integrity, timeliness and reliability of information and relevant electromagnetic conditions on which system performance and human decision-making may depend.

## 2. Core Principle

> **AI assurance depends on the conditions under which information is acquired, transmitted, received, processed and interpreted.**

Information and electromagnetic conditions should therefore be treated as part of the operational assurance context.

## 3. Scope

The information environment may include:

- Data sources.
- Sensor inputs.
- Operational information.
- External information.
- Communications.
- Data links.
- System interfaces.
- Human-provided information.
- Information latency and availability.

The electromagnetic environment may include conditions affecting:

- Communications.
- Sensors.
- Navigation or positioning.
- Electronic equipment.
- Supporting systems.

This document remains generic and unclassified and does not prescribe tactical electronic-warfare procedures.

## 4. Information Environment Characterisation

The intended information environment should identify:

- Required information sources.
- Information dependencies.
- Expected data quality.
- Expected data freshness.
- Information availability.
- Relevant information gaps.
- Interfaces and exchanges.
- Human information requirements.

Material assumptions should be explicitly documented.

## 5. Information Availability

The system should be assessed for conditions involving:

- Missing information.
- Delayed information.
- Intermittent information.
- Conflicting information.
- Incomplete information.
- Loss of selected information sources.

The system should not silently treat missing information as equivalent to confirmed information.

## 6. Information Integrity

Where information materially affects consequential AI outputs, assurance should consider whether information can be:

- Altered.
- Corrupted.
- Mislabelled.
- Duplicated.
- Misrouted.
- Injected from an unauthorised source.

Appropriate controls should support confidence in information integrity.

## 7. Information Timeliness

Information may lose operational value as it becomes stale.

Where relevant, the system should:

- Track information age.
- Identify stale information.
- Communicate relevant latency.
- Apply appropriate restrictions.
- Avoid presenting old information as current.

Timeliness requirements should be defined according to mission context.

## 8. Information Consistency

Conflicting information should be detected or appropriately surfaced where practicable.

The system should not necessarily resolve conflicting inputs by selecting one source without considering:

- Source reliability.
- Data freshness.
- Context.
- Confidence.
- Potential consequences.

Where conflict cannot be resolved reliably, uncertainty should be communicated.

## 9. Information Provenance

Material information should have traceable provenance where practicable.

Relevant information may include:

- Source.
- Collection or creation time.
- Transformation.
- Processing history.
- Version.
- Responsible system.

Provenance supports both assurance and post-event reconstruction.

## 10. Electromagnetic Environment

The electromagnetic environment may affect the availability or quality of:

- Communications.
- Sensor inputs.
- Navigation or positioning.
- Timing.
- Supporting electronic systems.

The relevant effects should be characterised for the capability rather than assumed to be negligible.

## 11. Electromagnetic Interference

Where electromagnetic interference could materially affect system behaviour, TEVV should assess:

- Detection.
- Performance degradation.
- Resilience.
- Human awareness.
- Fallback behaviour.

Testing should be conducted safely and within authorised technical and regulatory boundaries.

## 12. Communication Conditions

Communication conditions may range from:

**Normal → Degraded → Intermittent → Disconnected**

For each relevant state, the authorised operating concept should establish:

- Available functions.
- Information limitations.
- Human-control implications.
- Autonomy implications.
- Required response.

## 13. Information and Situational Awareness

AI-generated situational understanding should not be treated as inherently complete.

Human decision-makers should be able to understand, where relevant:

- What information the system used.
- What information may be missing.
- The confidence associated with important outputs.
- Significant contradictions.
- Environmental or communication limitations.

## 14. Data Fusion

Where multiple information sources are combined, assurance should consider:

- Source compatibility.
- Timing differences.
- Data quality.
- Conflicting observations.
- Correlated errors.
- Failure of individual sources.

Data fusion should not create an appearance of certainty that is unsupported by the underlying information.

## 15. Information Uncertainty

Uncertainty may arise from:

- Missing information.
- Conflicting information.
- Low-quality data.
- Delayed data.
- Unknown sources.
- Environmental degradation.
- Adversarial manipulation.

Material uncertainty should be communicated in a manner useful to the human decision-maker.

## 16. Electromagnetic Degradation and Autonomy

Where electromagnetic conditions can reduce confidence in AI inputs or supervisory communications, autonomy should be reassessed.

Potential responses include:

- Increased human supervision.
- Reduced autonomy.
- Restricted functions.
- Fallback operation.
- Suspension.

The response should be defined through risk assessment and operational authorisation.

## 17. Information Dependencies

Critical information dependencies should be documented in the capability baseline.

For each material dependency, identify:

- Purpose.
- Source.
- Required availability.
- Required integrity.
- Required timeliness.
- Failure effect.
- Fallback or mitigation.

## 18. Environment-Specific TEVV

TEVV should evaluate information and electromagnetic conditions relevant to intended use.

Assessment may consider:

- Data availability.
- Data integrity.
- Latency.
- Sensor degradation.
- Communication degradation.
- Information conflict.
- Navigation uncertainty.
- Human interpretation.
- Autonomy transitions.

## 19. Adversarial Considerations

Information and electromagnetic conditions may be deliberately manipulated or disrupted.

The assessment should connect with:

- D-AIGAAF AI Security.
- Adversarial operational environment.
- Supply-chain assurance.
- Incident management.

The focus should be on resilience and preservation of safe and accountable operation.

## 20. Operational Boundaries

Authorisation should identify material information and electromagnetic assumptions.

Where those assumptions are exceeded, predefined responses should apply.

Possible responses include:

- Warning.
- Increased supervision.
- Reduced functionality.
- Reduced autonomy.
- Fallback.
- Suspension.

## 21. Monitoring

Where technically and operationally appropriate, monitoring should identify:

- Information loss.
- Information latency.
- Data-quality degradation.
- Communication degradation.
- Sensor anomalies.
- Electromagnetic effects.
- Loss of critical dependencies.

Monitoring should support timely human awareness and appropriate system response.

## 22. Records

Significant information or electromagnetic degradation should be recorded where it affects:

- AI outputs.
- Mission performance.
- Human control.
- Autonomy.
- Safety.
- Security.

Records should support investigation and continuous assurance.

## 23. Change and Reauthorisation

Material changes to the information or electromagnetic environment may trigger:

- Risk reassessment.
- Additional TEVV.
- Change impact assessment.
- Revised operating boundaries.
- Revalidation.
- Reauthorisation.

## 24. Governance Questions

Before authorisation, decision-makers should be able to answer:

1. What information does the capability depend upon?
2. How reliable, timely and complete is that information?
3. What happens when information is missing or conflicting?
4. How is information provenance established?
5. Which electromagnetic conditions could affect performance?
6. What happens when communications degrade or fail?
7. How does uncertainty affect human decisions?
8. How does information degradation affect autonomy?
9. What monitoring detects material degradation?
10. What conditions trigger restriction, suspension or reauthorisation?

## 25. Core Rule

> **The assurance of Defence AI depends not only on the model, but also on the integrity, availability and conditions of the information environment through which the model perceives and supports decisions.**
