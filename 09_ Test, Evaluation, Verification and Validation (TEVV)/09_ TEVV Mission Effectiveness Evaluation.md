# D-AIGAAF — TEVV Mission Effectiveness Evaluation

## 1. Purpose

This document defines how Defence AI capabilities should be evaluated for mission effectiveness as part of Testing, Evaluation, Verification and Validation (TEVV).

The objective is to establish whether the capability delivers meaningful and measurable operational value for its approved mission, rather than merely demonstrating technical model performance.

## 2. Core Principle

> **A Defence AI capability is effective only when its technical performance translates into an acceptable improvement in mission outcomes within authorised risk and control boundaries.**

A model can perform well on technical metrics while providing little, no, or negative operational value.

## 3. Scope

Mission effectiveness evaluation should consider:

- Mission objectives.
- Operational outcomes.
- Decision quality.
- Timeliness.
- Reliability.
- Human-AI interaction.
- Resource use.
- Mission constraints.
- Consequences of errors.
- Environmental conditions.
- Autonomy.
- Operational limitations.

## 4. Mission Objectives

Evaluation should begin with clearly defined mission objectives.

Objectives should identify:

- What the capability is intended to achieve.
- Who uses it.
- Which decisions or functions it supports.
- What constitutes success.
- What constitutes unacceptable failure.
- Applicable operational constraints.

Mission objectives should be traceable to the approved use case.

## 5. Measures of Effectiveness

Measures of Effectiveness (MoE) should assess whether the capability achieves the intended mission outcome.

Examples may include:

- Improvement in decision quality.
- Reduction in decision time.
- Improved detection or identification outcomes.
- Improved resource allocation.
- Reduction in avoidable workload.
- Improved situational awareness.
- Increased mission resilience.

MoEs should be defined before significant evaluation begins.

## 6. Measures of Performance

Measures of Performance (MoP) describe how well the system performs its assigned function.

Examples may include:

- Accuracy.
- Precision.
- Recall.
- Latency.
- Availability.
- Reliability.
- Error rate.
- Processing capacity.

MoPs should support, but not replace, mission-level effectiveness assessment.

## 7. Technical-to-Mission Traceability

Evaluation should establish the relationship:

**Technical Performance → Human Use → Decision/Action → Mission Effect → Operational Risk**

A strong technical result should not be treated as mission success unless the causal relationship is supported by evidence.

## 8. Baseline Comparison

Where practicable, mission effectiveness should be compared against an appropriate baseline.

The baseline may represent:

- Existing human-only processes.
- Existing non-AI systems.
- Previous system versions.
- Alternative technical approaches.
- Other approved methods.

The comparison should account for differences in resources, workload, conditions and constraints.

## 9. Human Contribution

Where AI supports human decision-making, evaluation should determine the contribution of the combined human-AI system.

Assessment may consider:

- Human-only performance.
- AI-only technical performance where meaningful.
- Human-AI team performance.
- Decision time.
- Error rates.
- Workload.
- Appropriate reliance.
- Ability to challenge AI outputs.

The objective is to establish whether AI assistance creates a net operational benefit.

## 10. Decision Quality

For decision-support applications, evaluation should assess:

- Accuracy of the final decision.
- Quality of available information.
- Recognition of uncertainty.
- Consideration of alternatives.
- Timeliness.
- Human accountability.
- Consequences of incorrect decisions.

The AI recommendation and human decision should remain distinguishable where human authority is required.

## 11. Mission Timeliness

A technically accurate result may still be operationally ineffective if it arrives too late.

Evaluation should therefore consider:

- Processing time.
- Communication delay.
- Human review time.
- Decision time.
- Action time.
- End-to-end mission latency.

Timeliness requirements should reflect the decision context.

## 12. Consequence of Error

Mission effectiveness should be assessed together with the consequence of incorrect AI behaviour.

Evaluation should consider:

- False positives.
- False negatives.
- Delayed decisions.
- Missed information.
- Incorrect recommendations.
- Unintended actions.
- Loss of human control.

A single aggregate accuracy measure may conceal mission-critical failure modes.

## 13. Operational Conditions

Mission effectiveness should be evaluated under representative conditions defined for the use case.

Where relevant, this may include:

- Environmental variation.
- Degraded communications.
- Sensor variation.
- Incomplete information.
- Adversarial conditions.
- Increased workload.
- Resource constraints.

Results should identify the conditions under which the claimed mission benefit remains valid.

## 14. Mission-Level Failure Modes

Evaluation should identify situations where AI assistance could reduce mission effectiveness.

Examples include:

- Incorrect prioritisation.
- Misleading recommendations.
- Excessive confidence.
- Delayed alerts.
- Information overload.
- Automation bias.
- Failure to communicate uncertainty.
- Unanticipated system behaviour.

These findings should feed into risk treatment and operational controls.

## 15. Autonomy and Mission Effectiveness

Where autonomy is involved, evaluation should assess whether increased autonomy actually improves mission outcomes without creating unacceptable risk.

Assessment should consider:

- Mission benefit.
- Response time.
- Human workload.
- Predictability.
- Control.
- Failure consequences.
- Environmental limits.

Higher autonomy should not be justified solely because it increases speed or efficiency.

## 16. Resource Effectiveness

Mission evaluation may consider whether the capability improves the use of:

- Personnel.
- Time.
- Computing resources.
- Energy.
- Communications.
- Sensors.
- Other mission resources.

Resource savings should not be treated as mission benefit if they create unacceptable safety, security or control risks.

## 17. Acceptance Criteria

Mission effectiveness acceptance criteria should define:

- Required mission outcomes.
- Minimum performance.
- Maximum acceptable degradation.
- Timeliness requirements.
- Human-control requirements.
- Environmental boundaries.
- Error tolerances.
- Safety and security conditions.

Criteria should be proportionate to mission consequence.

## 18. Evaluation Scenarios

Scenarios should include, where relevant:

- Normal mission conditions.
- Representative variation.
- Degraded conditions.
- Ambiguous situations.
- Incorrect AI recommendations.
- High-uncertainty situations.
- Human-AI disagreement.
- System failure.
- Communications loss.
- Adversarial conditions.

Scenario selection should be risk-informed.

## 19. Evidence

Mission effectiveness evidence may include:

- Operational trial results.
- Simulation results.
- User assessments.
- Decision-quality measurements.
- Mission outcome data.
- Performance measurements.
- Human factors results.
- Reliability results.
- Security findings.
- Incident data.

Evidence should identify the conditions and system baseline under which the result was obtained.

## 20. Limitations and Generalisation

Evaluation results should clearly state:

- Conditions tested.
- Conditions not tested.
- Assumptions.
- Data limitations.
- Known uncertainties.
- Known failure modes.
- Boundaries of applicability.

Evidence from one mission or environment should not automatically be generalised to another.

## 21. Relationship to Assurance

Mission effectiveness is one of the eight D-AIGAAF TEVV dimensions:

1. Technical Performance.
2. Reliability & Robustness.
3. Adversarial Resilience.
4. Operational Environment.
5. Human-AI Interaction.
6. Security & Integrity.
7. Autonomy & Control.
8. Mission Effectiveness.

Mission effectiveness should therefore be considered alongside the other assurance dimensions rather than treated as a standalone performance claim.

## 22. Relationship to Operational Authorisation

Mission effectiveness evidence contributes to determining whether the capability provides sufficient operational value to justify its proposed employment.

The relationship is:

**Mission Need → Effectiveness Requirement → Evaluation → Evidence → Mission Outcome → Risk/Benefit Assessment → Assurance → Authorisation**

Where evidence shows insufficient mission benefit, deployment or continued employment should be reconsidered even where technical performance is acceptable.

## 23. Continuous Evaluation

Mission effectiveness should continue to be assessed after deployment where practicable.

Monitoring should consider:

- Changes in mission conditions.
- Changes in user behaviour.
- Performance degradation.
- Emerging failure modes.
- Changing threat conditions.
- Changes in operational value.

A capability that was effective at authorisation may become less effective as its environment or mission changes.

## 24. Revalidation Triggers

Mission effectiveness should be reassessed following material changes to:

- Mission.
- Use case.
- Operating environment.
- Model.
- Data.
- System architecture.
- Autonomy.
- Human roles.
- Critical dependencies.

Significant changes in observed mission outcomes should also trigger review.

## 25. Core Rule

> **Mission effectiveness must demonstrate operational value, not merely technical capability.**

The final evaluation question is:

> **“Does this Defence AI capability improve the approved mission outcome sufficiently, reliably and safely to justify its authorised employment?”**
