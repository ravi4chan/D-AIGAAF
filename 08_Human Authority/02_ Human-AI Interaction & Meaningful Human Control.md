# D-AIGAAF — Human-AI Interaction & Meaningful Human Control

## 1. Purpose

This document defines the requirements for meaningful interaction between humans and Defence AI systems, particularly where AI outputs may influence consequential decisions or actions.

Meaningful human control requires more than placing a person somewhere in the decision loop. The human must have sufficient authority, information, competence, time, and ability to intervene for the assigned responsibility to be meaningful.

## 2. Core Principle

> **Human control is meaningful only when the responsible human can understand, assess, and appropriately influence the AI-supported decision or action within the conditions that matter.**

## 3. Elements of Meaningful Human Control

D-AIGAAF considers meaningful human control through six elements:

1. **Authority** — the human has legitimate authority to decide or intervene.
2. **Competence** — the human understands the relevant mission, AI capability, limitations, and risks.
3. **Information** — the human receives information necessary for an informed decision.
4. **Time** — sufficient time exists to exercise judgement or intervention.
5. **Intervention** — the human can influence, override, or stop the system where required.
6. **Accountability** — the decision and authority chain remain identifiable.

A failure in one or more elements may reduce the effectiveness of human control.

## 4. Human-AI Interaction Model

The preferred interaction pattern for consequential use cases is:

**Sense / Collect → AI Process → AI Output → Human Interpretation → Decision → Action → Feedback → Record**

The degree of human involvement should increase where consequence, uncertainty, autonomy, or mission criticality increases.

## 5. Appropriate AI Presentation

AI systems should communicate outputs in a manner that supports informed human judgement.

Where relevant, interfaces should provide:

- Recommendation or result.
- Relevant supporting information.
- Confidence or uncertainty.
- Important limitations.
- Data freshness or temporal context.
- Alerts and anomalies.
- Applicable operating constraints.
- Indication when conditions fall outside the validated envelope.

The objective is not to overwhelm the user with technical information but to provide information necessary for sound operational judgement.

## 6. Uncertainty

AI systems should explicitly communicate meaningful uncertainty.

They should avoid presenting uncertain outputs as established facts.

Where uncertainty is material to the decision, the human decision maker should be able to recognise:

- That uncertainty exists.
- Its significance.
- What may have caused it.
- Whether additional information is available.
- Whether the system is operating outside validated conditions.

## 7. Human Cognitive Factors

Human-AI interaction should account for risks including:

- Automation bias.
- Over-reliance on AI recommendations.
- Confirmation bias.
- Alert fatigue.
- Excessive workload.
- Misinterpretation of confidence scores.
- Loss of situational awareness.
- Complacency.
- Excessive trust in system reputation.

Assurance should evaluate whether the interface or workflow unintentionally encourages inappropriate reliance.

## 8. Situational Awareness

Defence AI should support, rather than degrade, human situational awareness.

Users should be able to distinguish where practical between:

- Observed information.
- AI-derived information.
- AI inference.
- AI recommendation.
- Human judgement.
- Authorised action.

This distinction becomes particularly important when information is incomplete, delayed, contradictory, or degraded.

## 9. Intervention Capability

Where human intervention is required, the system should provide a practical means to:

- Pause or stop AI activity.
- Reject recommendations.
- Override authorised actions where applicable.
- Change to a safer mode.
- Transfer control.
- Revert to manual procedures.

Intervention should be technically feasible within the response time relevant to the risk.

## 10. Human Control Under Autonomous Operation

Higher autonomy does not necessarily mean continuous human input.

For authorised autonomous functions, meaningful control may instead depend on:

- Clearly defined boundaries.
- Predefined operating conditions.
- Explicit constraints.
- Reliable monitoring.
- Predictable transition conditions.
- Effective intervention mechanisms.
- Defined responsibility.
- Tested fail-safe behaviour.

The required form of human control should therefore be matched to the autonomy level and consequence of failure.

## 11. Loss of Human Control

Loss of meaningful control may occur when:

- The human cannot understand the AI output sufficiently.
- The human lacks authority to intervene.
- Intervention is technically ineffective.
- The system acts faster than meaningful human response is possible.
- Communications are unavailable and no valid contingency exists.
- The AI operates outside its authorised conditions.
- Human workload prevents effective supervision.
- The system obscures uncertainty or limitations.

Such conditions should be treated as a risk requiring assessment and mitigation.

## 12. Degraded and Disconnected Environments

Human-AI interaction should be assessed under conditions such as:

- Limited or lost communications.
- Reduced sensor availability.
- Interference.
- Cyber disruption.
- Delayed information.
- Limited technical support.
- Reduced staffing.
- Environmental degradation.

The system should have defined behaviour when the conditions required for meaningful human control are no longer available.

## 13. Human Override

Override should not exist only as a theoretical feature.

Where override is required, assurance should establish:

- It can be initiated by authorised personnel.
- It functions under relevant operating conditions.
- It has an understood effect.
- It does not introduce unacceptable secondary risk.
- Personnel know when and how to use it.
- Override actions are recorded where required.

## 14. Human-AI Trust

Trust should be based on demonstrated evidence rather than assumptions.

Human users should understand:

- What the system is designed to do.
- What it has been validated to do.
- What it has not been validated to do.
- Known failure modes.
- Relevant uncertainty.
- Conditions requiring escalation or disengagement.

The objective is **calibrated trust** rather than maximum trust.

## 15. Testing Meaningful Human Control

TEVV should evaluate human-AI interaction using realistic scenarios, including:

- Correct AI recommendations.
- Incorrect recommendations.
- High-uncertainty outputs.
- Conflicting information.
- Unexpected system behaviour.
- Time pressure.
- Repeated alerts.
- Loss of communications.
- Loss of sensor inputs.
- Need for immediate intervention.

Testing should evaluate both technical intervention and actual human performance.

## 16. Evidence of Meaningful Control

Evidence may include:

- Human factors assessments.
- Interface testing.
- User training records.
- Intervention testing.
- Override testing.
- Scenario-based exercises.
- Incident records.
- Human-AI performance measurements.
- Operational observations.

Evidence should be linked to the applicable assurance and authorisation record.

## 17. Core Principle

Meaningful human control should not be reduced to the question:

> **“Is a human somewhere in the loop?”**

The relevant question is:

> **“Does the authorised human possess the authority, competence, information, time, and practical ability to exercise meaningful judgement and control?”**

If the answer is no, the governance model should reassess the use case, autonomy level, safeguards, or operational authorisation.
