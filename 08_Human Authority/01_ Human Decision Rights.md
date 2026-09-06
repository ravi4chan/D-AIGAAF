# D-AIGAAF — Human Decision Rights

## 1. Purpose

This document defines how decision rights should be assigned when Defence AI systems provide information, recommendations, decisions, or actions that may have operational, legal, safety, security, or human consequences.

The objective is to ensure that authority is explicit, proportionate to risk, and traceable.

## 2. Core Principle

> **Consequential authority must remain explicitly assigned to an authorised human or legally established authority unless a defined level of autonomy has been separately authorised.**

Technical capability does not constitute decision authority.

## 3. Decision Rights Framework

D-AIGAAF should distinguish between the following rights:

- **Request** — initiate use of the AI capability.
- **Interpret** — assess AI output in operational context.
- **Decide** — make the consequential decision.
- **Approve** — authorise a proposed action.
- **Execute** — carry out the action.
- **Override** — reject or supersede an AI recommendation or action.
- **Suspend** — temporarily stop AI-supported activity.
- **Revoke** — withdraw authority for continued employment.
- **Accept Risk** — formally accept defined residual risk.
- **Reauthorise** — approve continued employment following material change or review.

These rights should not automatically reside with the same person or organisation.

## 4. Decision Authority by AI Role

A typical allocation may include:

| Role | Primary decision rights |
|---|---|
| Command Authority | Mission decisions, consequential operational decisions, risk acceptance |
| Operational AI Advisor | AI interpretation and operational advice |
| System Owner | Capability management, configuration, lifecycle decisions |
| AI Developer / Technical Team | Technical decisions within delegated authority |
| Operator / User | Employment within authorised boundaries |
| Assurance Authority | Assurance judgement and evidence sufficiency |
| Authorising Authority | Operational authorisation, restriction, suspension, revocation |

Organisations should adapt this allocation to their legal and command structures.

## 5. Consequential Decisions

Additional controls should apply where AI-supported decisions may:

- Cause loss of human life.
- Cause significant physical harm.
- Affect protected persons or sensitive populations.
- Employ force.
- Affect critical infrastructure.
- Cause significant property damage.
- Create major operational consequences.
- Trigger irreversible or difficult-to-reverse actions.

The higher the consequence, the stronger the requirement for clearly assigned human authority, assurance, and oversight.

## 6. AI Recommendation vs Human Decision

A distinction should be maintained between:

**AI Output → Human Assessment → Human Decision → Authorised Action**

An AI recommendation should not be treated as a decision merely because it is presented with a confidence score, ranking, classification, or recommended course of action.

The responsible human should have sufficient information and authority to determine whether the recommendation is appropriate.

## 7. Acceptance and Rejection

Where human decision-making is required, authorised personnel should be able to:

- Accept an AI recommendation.
- Reject it.
- Modify it.
- Seek additional information.
- Request human or technical review.
- Defer action where operationally feasible.

The framework should avoid creating incentives for personnel to automatically follow AI recommendations merely because the system is considered authoritative.

## 8. Recording Decision Rationale

For defined high-consequence use cases, records should capture, where appropriate:

- AI recommendation or output.
- Relevant system version/baseline.
- Material uncertainty or limitations.
- Human decision.
- Whether the recommendation was accepted or rejected.
- Reason for material deviation from the recommendation.
- Applicable authority.
- Resulting action.

The level of recording should be proportionate to risk and operational feasibility.

## 9. Operational AI Advisor Decision Boundary

The Operational AI Advisor should advise rather than silently assume command authority.

The OAIA may:

- Explain AI behaviour and limitations.
- Assess whether use remains within authorised conditions.
- Recommend additional safeguards.
- Recommend suspension or escalation.
- Advise on uncertainty and failure modes.

The OAIA should not independently exercise command authority unless separately authorised under the applicable organisational structure.

## 10. Autonomous Decision Rights

Where autonomous behaviour is authorised, the decision rights should explicitly identify:

- What the AI may decide.
- What the AI may not decide.
- Permitted operating conditions.
- Permitted autonomy level.
- Human supervision requirements.
- Intervention mechanisms.
- Time and geographic boundaries where relevant.
- Conditions requiring transition to a safer mode.
- Conditions requiring suspension.

Autonomy should therefore be treated as **delegated and bounded authority**, not unrestricted authority.

## 11. Override Rights

Override authority should be defined before deployment.

The framework should establish:

- Who can override.
- What can be overridden.
- How override is initiated.
- Whether override is immediate.
- What happens after override.
- What records are created.
- When technical or command review is required.

Override mechanisms should be tested as part of assurance.

## 12. Suspension and Revocation

Suspension authority should be available when:

- AI behaviour becomes unreliable.
- Security is compromised.
- Critical assumptions no longer hold.
- Operating conditions exceed the authorised envelope.
- A serious incident occurs.
- Material uncertainty emerges.
- Required dependencies become unavailable.
- Assurance evidence is invalidated.

Revocation should be considered where continued use is no longer justified under the authorised risk posture.

## 13. Degraded Communications and Authority

Decision rights should remain understandable when normal communications or technical support are unavailable.

The governance model should define:

- Delegated authority.
- Local decision boundaries.
- Emergency procedures.
- Fail-safe conditions.
- Manual fallback.
- Post-event reporting and review.

Loss of connectivity should not unintentionally create unrestricted AI authority.

## 14. Commander and AI Recommendations

Where an AI recommendation is rejected, the commander or authorised decision maker should be able to justify the decision when required by policy, law, or the risk level of the use case.

Equally, personnel should not be penalised merely for rejecting an AI recommendation when they have exercised legitimate judgement within their authority.

This creates accountability in both directions:

**Do not blindly follow AI.  
Do not disregard AI without reason where reliance is expected.**

## 15. Decision Rights Matrix

Each consequential use case should maintain a decision-rights matrix identifying:

| Decision | AI role | Human role | Authority | Evidence/record |
|---|---|---|---|---|
| Information generation | Assist | Review as required | Defined | System record |
| Recommendation | Generate | Interpret/decide | Defined | Recommendation + decision |
| Consequential action | Execute only if authorised | Approve/supervise as required | Explicit | Action record |
| Override | Support | Authorised human | Defined | Override record |
| Suspension | Detect/recommend | Authorised human | Defined | Suspension record |
| Reauthorisation | Provide evidence | Authorising authority | Formal | Authorisation record |

The exact allocation should be established for each use case.

## 16. Core Principle

Decision rights should be:

- **Explicit**
- **Proportionate**
- **Competence-based**
- **Traceable**
- **Reversible where practicable**
- **Consistent with law and policy**
- **Aligned with the authorised autonomy level**

The central governance question is not simply:

> **“Can the AI make this decision?”**

It is:

> **“Who is authorised to make this decision, under what conditions, with what evidence, and with what accountability?”**
