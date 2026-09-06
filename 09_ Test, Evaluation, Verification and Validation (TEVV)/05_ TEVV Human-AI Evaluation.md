# D-AIGAAF — TEVV Human-AI Evaluation

## 1. Purpose

This document defines the evaluation of the human-AI system as part of Testing, Evaluation, Verification and Validation (TEVV).

The objective is to establish whether people can understand, supervise, challenge, intervene in and appropriately rely upon Defence AI capabilities within their authorised operational context.

## 2. Core Principle

> **A Defence AI capability is evaluated as a human-AI system, not as a model in isolation.**

Technical performance alone is insufficient where human judgement, supervision or intervention materially affects safe and effective employment.

## 3. Scope

Human-AI evaluation should consider:

- Human decision-making.
- AI recommendations and outputs.
- Human understanding of AI limitations.
- Communication of uncertainty.
- Workload.
- Situational awareness.
- Automation bias.
- Over-reliance and under-reliance.
- Intervention and override.
- Training and competence.
- Human authority.
- Time pressure.
- Mission consequences.

## 4. Human Role Definition

Before evaluation, the intended human role should be clearly defined.

Examples include:

- User.
- Operator.
- Supervisor.
- Decision maker.
- Mission commander.
- Technical support personnel.
- AI system manager.
- Operational AI Advisor.

The evaluation should verify that responsibilities and decision rights are understood in practice, not merely documented.

## 5. AI Output Comprehension

Users should be able to understand:

- What the AI is recommending or reporting.
- The relevant confidence or uncertainty.
- Important limitations.
- Whether the output is advisory or authorised to initiate action.
- What information materially influenced the output where such information is available.
- When human intervention is required.

The interface should not create a misleading impression of certainty or authority.

## 6. Uncertainty Communication

Where uncertainty is material, the system should communicate it in a form appropriate to the user and decision context.

Evaluation should assess whether users:

- Notice uncertainty.
- Understand its significance.
- Distinguish confidence from correctness.
- Adjust decisions appropriately.
- Seek additional information when necessary.

An uncertainty indicator that users consistently ignore or misunderstand should not be considered effective simply because it is technically present.

## 7. Automation Bias

TEVV should assess the possibility that users may accept AI outputs without sufficient independent judgement.

Testing may examine:

- Acceptance of incorrect recommendations.
- Influence of system confidence indicators.
- Behaviour when AI conflicts with human judgement.
- Effects of repeated correct outputs.
- Effects of time pressure.
- Differences between novice and experienced users.

Controls should be considered where automation bias could create unacceptable risk.

## 8. Appropriate Reliance

Evaluation should assess both:

- **Over-reliance** — accepting AI outputs when they should be challenged.
- **Under-reliance** — rejecting useful AI outputs without adequate basis.

The objective is not maximum trust or minimum trust.

The objective is **appropriately calibrated reliance**.

## 9. Human Decision Quality

Where AI supports consequential decisions, evaluation should consider whether AI assistance improves or degrades:

- Decision accuracy.
- Decision timeliness.
- Situational awareness.
- Identification of relevant risks.
- Consideration of alternatives.
- Recognition of uncertainty.
- Ability to justify the final decision.

The human decision should remain distinguishable from the AI recommendation.

## 10. Intervention and Override

Where human intervention is required, testing should establish whether the user can:

- Recognise the need to intervene.
- Access the required controls.
- Understand the consequence of intervention.
- Override or constrain the system.
- Complete the intervention within the required time.
- Confirm that the intended state has been achieved.

Controls that exist technically but cannot be used reliably under realistic conditions should not be treated as effective human control.

## 11. Loss of Communications

Where the capability may operate with limited or intermittent communications, evaluation should assess:

- Human awareness of communication loss.
- System behaviour during loss of connectivity.
- Availability of local controls.
- Continuity of required human authority.
- Transition to degraded or safer modes.
- Recovery following restoration of communications.

Where human oversight cannot be maintained, the authorised autonomy state should determine the permitted system behaviour.

## 12. Workload and Decision Tempo

Human-AI evaluation should consider workload under realistic operating conditions.

Assessment may include:

- Cognitive workload.
- Information overload.
- Number of simultaneous alerts.
- Decision frequency.
- Time available for review.
- Fatigue or sustained workload.
- Complexity of the user interface.

A system that requires unrealistic levels of human attention should not be considered adequately controlled.

## 13. Situational Awareness

The evaluation should determine whether AI assistance:

- Improves understanding of the operational situation.
- Highlights relevant information.
- Avoids obscuring important information.
- Communicates changes in system status.
- Enables users to recognise uncertainty and emerging risks.

AI should support, rather than unintentionally degrade, human situational awareness.

## 14. Human-AI Conflict

Where human judgement conflicts with AI output, trials should assess whether users can:

- Recognise the disagreement.
- Examine relevant evidence.
- Understand system limitations.
- Reject or accept the recommendation appropriately.
- Record or communicate the decision where required.

For consequential decisions, the framework should preserve clear human accountability.

## 15. Training and Competence

Evaluation should verify that intended users possess the knowledge and skills required to operate the human-AI system safely.

This may include:

- AI literacy.
- System-specific knowledge.
- Understanding of limitations.
- Interpretation of uncertainty.
- Intervention procedures.
- Fail-safe procedures.
- Incident reporting.
- Mission-specific decision responsibilities.

Competence requirements should be proportionate to consequence and autonomy.

## 16. Operational AI Advisor

Where appropriate, TEVV may evaluate the role of an Operational AI Advisor as an intermediate human function between command authority and AI developers/system owners.

The evaluation should establish whether the role effectively supports:

- Interpretation of AI behaviour.
- Understanding of technical limitations.
- Operational context.
- Risk assessment.
- Communication between technical and operational personnel.
- Escalation of unexpected behaviour.

The role should complement, not replace, the lawful decision authority of commanders or designated decision makers.

## 17. Evaluation Scenarios

Human-AI evaluation should include representative scenarios involving:

- Correct AI recommendations.
- Incorrect recommendations.
- Ambiguous information.
- Conflicting information.
- High uncertainty.
- System degradation.
- Loss of communications.
- Unexpected AI behaviour.
- Human-AI disagreement.
- Time-critical decisions.

Scenarios should be proportionate to the intended mission and risk.

## 18. Human Factors Findings

Findings should capture issues such as:

- Misunderstanding.
- Excessive workload.
- Poor interface design.
- Automation bias.
- Inadequate training.
- Delayed intervention.
- Unclear authority.
- Failure to recognise uncertainty.
- Loss of situational awareness.

Human factors findings should feed into system design, controls, training and authorisation decisions.

## 19. Acceptance Criteria

Human-AI acceptance criteria should be defined before significant trials.

Criteria may address:

- Decision performance.
- Intervention time.
- Error rates.
- User comprehension.
- Workload.
- Appropriate reliance.
- Uncertainty recognition.
- Override effectiveness.
- Situational awareness.
- Training proficiency.

Acceptance criteria should be linked to mission risk and operational consequences.

## 20. Evidence and Assurance

Human-AI evaluation evidence should be traceable to:

**Human Requirement → Risk → Evaluation Scenario → Human Behaviour → Outcome → Finding → Control/Recommendation → Assurance**

Evidence should identify the conditions under which conclusions apply.

## 21. Revalidation Triggers

Human-AI evaluation should be reconsidered when material changes occur to:

- User interface.
- AI behaviour.
- Autonomy level.
- Mission.
- User role.
- Decision authority.
- Operating environment.
- Workload.
- Communications.
- Training requirements.

A technically minor change may still require human-AI reassessment if it changes how people interact with the system.

## 22. Core Rule

> **Meaningful human control must be demonstrated through behaviour under realistic conditions, not inferred from the presence of a human somewhere in the system.**

The ultimate question is whether the human-AI system enables informed, timely and accountable human judgement within the authorised operational envelope.
