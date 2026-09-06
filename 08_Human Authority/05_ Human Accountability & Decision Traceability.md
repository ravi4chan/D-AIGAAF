# D-AIGAAF — Human Accountability & Decision Traceability

## 1. Purpose

This document establishes requirements for maintaining accountability and traceability for human decisions involving Defence AI capabilities.

The objective is to preserve a defensible chain connecting AI output, human judgement, authority, action, and outcome.

## 2. Core Principle

> **For consequential AI-supported activity, it should be possible to establish what the AI provided, who exercised authority, what decision was made, and under which authorised conditions.**

Traceability should support accountability without creating unnecessary administrative or operational burden.

## 3. Accountability Chain

Where relevant, D-AIGAAF should maintain a traceable chain:

**Mission → AI Capability → Input / Context → AI Output → Human Assessment → Authority → Decision → Action → Outcome → Review**

The degree of traceability should be proportionate to consequence and applicable legal, policy, and operational requirements.

## 4. Attribution of Responsibility

AI should not be treated as a substitute for legally or organisationally established responsibility.

Records should distinguish between:

- AI-generated information.
- AI-generated recommendation.
- Human interpretation.
- Human decision.
- Authorised autonomous action.
- Human intervention or override.
- System execution.

This distinction helps avoid ambiguity about who or what performed each part of the decision process.

## 5. Consequential Decisions

Enhanced traceability should apply to decisions that may:

- Affect human life or safety.
- Employ force.
- Cause significant physical harm.
- Affect critical infrastructure.
- Create significant property or mission consequences.
- Trigger high-consequence autonomous actions.
- Materially alter operational risk.

The required record should be defined in advance for each such use case.

## 6. Minimum Decision Record

Where required, a decision record should capture:

- Date and time.
- Mission or use-case identifier.
- AI capability identifier.
- Relevant system/model baseline.
- Operational context.
- AI output or recommendation.
- Material uncertainty or limitation.
- Human decision maker.
- Applicable authority.
- Decision taken.
- Whether AI recommendation was accepted, modified, or rejected.
- Action resulting from the decision.
- Relevant intervention or override.
- Outcome or immediate consequence.

Not every field will be required for every use case.

## 7. Decision Rationale

For defined high-consequence decisions, the responsible human should record sufficient rationale to explain the decision where required.

Where an AI recommendation is rejected or materially modified, the rationale may be particularly important for later review.

The purpose is not to require exhaustive written justification for every routine decision, but to preserve meaningful accountability where consequences warrant it.

## 8. Autonomous Actions

Where autonomous action is authorised, traceability should establish:

- Which capability acted.
- Which authorised autonomy level applied.
- Which baseline was deployed.
- What conditions triggered the action.
- What constraints applied.
- What action was taken.
- What human authority authorised that autonomy.
- Whether any human intervention occurred.

Autonomous execution therefore remains linked to prior human authority and defined operational boundaries.

## 9. System and Configuration Traceability

Decision records should, where practicable, identify the relevant:

- Model version.
- Software version.
- Hardware configuration.
- Data or information source.
- Critical dependency.
- Configuration baseline.
- Applicable operational-authorisation status.

This is particularly important when capabilities change over time.

## 10. Time Synchronisation

Where multiple systems contribute to a consequential decision, appropriate time synchronisation should be maintained where technically and operationally feasible.

Accurate temporal records can help establish:

- What information was available.
- When AI generated an output.
- When a human reviewed it.
- When a decision was made.
- When an action occurred.

## 11. Data Integrity and Record Protection

Decision records should be protected against:

- Unauthorised modification.
- Deletion.
- Loss.
- Tampering.
- Inappropriate access.

Where appropriate, systems should provide mechanisms to demonstrate record integrity.

## 12. Privacy and Information Protection

Accountability records should follow applicable requirements for:

- Personal information.
- Operational information.
- Security-sensitive information.
- Access control.
- Retention.
- Disclosure.

Traceability should not become a justification for collecting information that is unnecessary for governance or accountability.

## 13. When Records Are Incomplete

Operational conditions may prevent complete recording.

Examples include:

- Communications loss.
- System failure.
- Power interruption.
- Emergency action.
- Damaged equipment.
- Degraded infrastructure.

Where records are incomplete, the gap should itself be identified and assessed where the consequence warrants it.

## 14. Review and Investigation

Decision records should support:

- Incident investigation.
- Assurance review.
- Audit.
- Lessons learned.
- Revalidation.
- Reauthorisation.
- Legal or policy review where applicable.

Investigations should consider both human and system factors rather than automatically attributing failure to either the human or AI.

## 15. Accountability After AI Failure

An AI failure should not automatically establish human fault.

Review should consider:

- Whether the system was operating within its authorised envelope.
- Whether known limitations were communicated.
- Whether required safeguards were functioning.
- Whether the human had sufficient information and time.
- Whether procedures were followed.
- Whether organisational controls were adequate.
- Whether the system behaved unexpectedly.

Accountability should therefore be evidence-based.

## 16. Commander Decision and AI Recommendation

Where appropriate, the framework should preserve whether the commander or authorised decision maker:

- Accepted the recommendation.
- Rejected it.
- Modified it.
- Requested additional information.
- Escalated the decision.
- Suspended AI-supported activity.

This supports both operational learning and responsible use of AI.

## 17. Evidence Linkage

Decision records should connect, where applicable, to:

- Assurance evidence.
- Risk assessment.
- TEVV results.
- Operational authorisation.
- Incident records.
- Change records.
- Revalidation decisions.
- Reauthorisation decisions.

This creates a continuous evidence chain rather than isolated records.

## 18. Core Principle

Accountability in Defence AI should answer five questions:

1. **What did the AI provide or do?**
2. **What did the human know?**
3. **Who had authority?**
4. **What decision or action followed?**
5. **Under what authorised conditions did it occur?**

The resulting traceability should be sufficient to support responsible governance, operational learning, assurance, and review.
