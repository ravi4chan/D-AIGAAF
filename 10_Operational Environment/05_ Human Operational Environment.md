# D-AIGAAF — Human Operational Environment

## 1. Purpose

This document defines governance considerations for the human operating environment surrounding a Defence AI capability.

The objective is to ensure that AI assurance considers not only technical performance, but also the conditions under which people must understand, supervise, challenge, authorise, intervene in and act upon AI outputs.

## 2. Core Principle

> **A Defence AI system operates within a human decision environment; human performance and human authority are therefore part of operational assurance.**

## 3. Scope

The human operational environment includes:

- Commanders and decision-makers.
- AI operators.
- Supervisors.
- Technical personnel.
- Operational AI advisors.
- Maintainers.
- Support personnel.
- Other authorised users and affected stakeholders.

The relevant roles will vary by capability.

## 4. Human Roles

For each significant AI capability, relevant human roles and responsibilities should be identified.

These may include:

- Decision authority.
- AI operator.
- Supervisor.
- Technical support.
- System owner.
- Assurance authority.
- Operational AI advisor.

Roles should be clearly distinguished where different people hold different responsibilities.

## 5. Decision Authority

The governance model should identify who has authority to:

- Accept AI recommendations.
- Reject AI recommendations.
- Authorise consequential actions.
- Change autonomy settings where permitted.
- Intervene in system behaviour.
- Suspend operation.
- Invoke predefined fail-safe procedures.

Decision authority should remain attributable to an identifiable authorised role.

## 6. Human-AI Interaction

The system should be designed and evaluated around the actual interaction between people and AI.

Assessment should consider:

- Information presentation.
- Timing.
- Confidence communication.
- Alerts.
- Recommendations.
- Explanations or supporting rationale where appropriate.
- User actions.
- Override mechanisms.
- Failure notifications.

## 7. Meaningful Human Control

Where human control is required, the person exercising that control should have:

- Appropriate authority.
- Sufficient information.
- Adequate time where practicable.
- Ability to understand relevant AI limitations.
- Ability to reject or override AI recommendations.
- A viable mechanism for intervention.

A nominal human presence should not automatically be treated as meaningful control.

## 8. Human Workload

AI may reduce some workloads while increasing others.

Assessment should consider:

- Information volume.
- Alert frequency.
- Decision frequency.
- Time pressure.
- Task switching.
- Monitoring burden.
- Fatigue.
- Cognitive load.

Excessive workload may reduce the practical effectiveness of human oversight.

## 9. Automation Bias

Users may place excessive trust in AI recommendations, particularly when systems appear highly accurate or authoritative.

TEVV and operational design should consider:

- Uncritical acceptance.
- Reduced independent judgement.
- Over-reliance.
- Confirmation bias.
- Reduced vigilance.

Training and interface design should support appropriate use of AI rather than automatic acceptance.

## 10. AI Uncertainty

Where uncertainty is material, it should be communicated in a manner that supports human decision-making.

The system should avoid presenting:

- Speculation as fact.
- Missing information as complete information.
- Low-confidence outputs as high-confidence outputs.
- Unsupported conclusions with unjustified certainty.

Human users should understand the significance of uncertainty to the decision at hand.

## 11. Situational Awareness

AI should support appropriate situational awareness rather than create a narrow or misleading view of the operating environment.

Where relevant, users should be able to understand:

- Current system state.
- Relevant information sources.
- Important limitations.
- Significant uncertainty.
- Changes in operating conditions.
- Autonomy state.
- Alerts and anomalies.

## 12. Time-Critical Decisions

Some operational decisions may occur under severe time constraints.

The governance process should assess whether the available time permits:

- Human review.
- AI recommendation assessment.
- Confirmation.
- Intervention.
- Safe response.

Where meaningful human control cannot realistically be exercised within the available time, this should be explicitly reflected in risk and autonomy assessment.

## 13. Human Intervention

Intervention mechanisms should be:

- Accessible to authorised personnel.
- Understandable.
- Tested.
- Appropriate to the consequence of the system action.
- Available under relevant operating conditions where required.

The practical ability to intervene should be demonstrated rather than assumed.

## 14. Override

Where override is part of the authorised control model, TEVV should assess whether users can:

- Recognise the need for intervention.
- Exercise the override correctly.
- Understand the consequences.
- Confirm the resulting system state.

An override mechanism that exists technically but cannot be reliably used under operational conditions should not be treated as effective human control.

## 15. Operational AI Advisor

For high-consequence or technically complex AI capabilities, the organisation may designate an **Operational AI Advisor (OAIA)** or equivalent role.

The role can provide an interface between:

**Operational Command ↔ AI System / Developer / Technical Authority**

The advisor may help commanders understand:

- AI capabilities.
- Limitations.
- Confidence and uncertainty.
- Risk implications.
- Autonomy.
- System state.
- Appropriate escalation.

The OAIA should advise rather than replace the designated command authority.

## 16. Competence

Personnel exercising meaningful control should possess competence appropriate to their role.

Competence may include:

- Operational knowledge.
- AI literacy.
- Understanding of system limitations.
- Understanding of autonomy.
- Ability to interpret uncertainty.
- Knowledge of intervention procedures.
- Knowledge of applicable authority boundaries.

## 17. Training

Training should reflect realistic operational conditions.

Where relevant, training should include:

- Normal operation.
- Degraded operation.
- Unexpected AI behaviour.
- Loss of communications.
- Uncertainty.
- Human-AI disagreement.
- Override.
- Fail-safe procedures.
- Escalation.

Training should not assume ideal conditions.

## 18. Human-AI Disagreement

The framework should permit and record legitimate disagreement between humans and AI.

A human decision-maker should be able to reject or bypass an AI recommendation where authorised.

For consequential decisions, the governance process should support an appropriate record of:

- AI recommendation.
- Relevant uncertainty or limitations.
- Human decision.
- Reason for rejection or deviation where required.
- Resulting action.

The objective is accountability and learning, not discouraging justified human judgement.

## 19. Human Error

The system should be assessed for foreseeable human errors that could interact with AI behaviour.

Examples include:

- Misinterpretation.
- Incorrect configuration.
- Failure to notice alerts.
- Incorrect mode selection.
- Delayed intervention.
- Over-reliance.

Where reasonable controls can reduce such risks, they should be considered in system design and assurance.

## 20. Shift and Continuity Considerations

Where capabilities operate over extended periods, governance should consider:

- Handover.
- Fatigue.
- Personnel rotation.
- Continuity of situational awareness.
- Transfer of decision responsibility.
- Maintenance of relevant operational records.

Critical information should not depend solely on one individual's memory.

## 21. Human Environment and Autonomy

The authorised autonomy level should reflect the actual ability of humans to supervise and intervene.

Factors may include:

- Number of systems supervised.
- Decision frequency.
- Time available.
- Communication conditions.
- Human workload.
- Training.
- Interface quality.

Increasing autonomy should not be used to compensate for an environment in which effective human supervision is impractical without appropriate assurance.

## 22. Human Environment and Operational Boundaries

Environmental conditions may affect human control as well as technical performance.

For example, degraded communications, increased workload or reduced situational awareness may require:

- Additional supervision.
- Reduced autonomy.
- Restricted functions.
- Additional confirmation.
- Suspension.

## 23. Human Factors TEVV

TEVV should evaluate human-AI interaction under conditions representative of intended use.

Assessment may include:

- Decision quality.
- Workload.
- Response time.
- Situational awareness.
- Automation bias.
- Understanding of uncertainty.
- Intervention effectiveness.
- Override effectiveness.

## 24. Monitoring

Operational monitoring should identify indicators that human control may be degrading.

Possible indicators include:

- Excessive alerts.
- Repeated overrides.
- Frequent operator disagreement.
- Increasing workload.
- Missed interventions.
- Unexpected dependence on AI recommendations.

Such indicators should feed continuous assurance.

## 25. Incident and Learning

Significant human-AI interaction events should support organisational learning.

Review should consider whether:

- The interface contributed to the event.
- Training was sufficient.
- Authority was clear.
- AI uncertainty was communicated adequately.
- Human workload was excessive.
- Autonomy was appropriate.

## 26. Governance Questions

Before authorisation, decision-makers should be able to answer:

1. Who has decision authority?
2. Who operates and supervises the AI?
3. Is meaningful human control realistically achievable?
4. What information does the human need?
5. How is uncertainty communicated?
6. Can the human reject or override the AI?
7. What happens under time pressure?
8. What competence and training are required?
9. How does human workload affect assurance?
10. When should an Operational AI Advisor or equivalent role be used?

## 27. Core Rule

> **Human authority must be operationally real, technically supported and demonstrable under the conditions in which the AI capability is authorised to operate.**
