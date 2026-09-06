# D-AIGAAF — Operational Environment Incident Management

## 1. Purpose

This document defines the governance approach for identifying, reporting, assessing and responding to incidents involving the operational environment of Defence AI capabilities.

The objective is to ensure that environmental incidents are treated as potential assurance events and that lessons from operational experience feed back into risk management, TEVV, authorisation and continuous assurance.

## 2. Core Principle

> **An operational environment incident is not only an event to be resolved; it may reveal that an assumption, boundary, control or assurance claim is incomplete.**

## 3. What Constitutes an Environmental Incident

An environmental incident may include:

- Unexpected environmental conditions affecting AI performance.
- Operation outside an authorised environmental envelope.
- Significant sensor degradation.
- Unexpected electromagnetic interference.
- Loss or degradation of communications.
- Loss or degradation of navigation or positioning.
- Critical data-quality or data-freshness failure.
- Unexpected interaction between environmental conditions and AI behaviour.
- Failure of environmental monitoring.
- Human-control degradation caused by environmental conditions.
- Environmental conditions contributing to unsafe or unintended system behaviour.

An environmental incident may occur without a cyberattack, software defect or hardware failure.

## 4. Incident Detection

Environmental incidents may be identified through:

- Operators.
- Supervisors.
- Operational AI Advisors.
- Automated monitoring.
- Technical personnel.
- Security personnel.
- Command authorities.
- Assurance activities.
- Post-operation review.

Personnel should have clear mechanisms for reporting suspected incidents.

## 5. Immediate Response

The immediate response should prioritise:

1. Protection of human life.
2. Prevention of further harm.
3. Restoration or preservation of human control.
4. Stabilisation of the AI capability.
5. Preservation of relevant evidence.
6. Notification of appropriate authorities.

Where required, pre-authorised fail-safe or fallback procedures should be used.

## 6. Environmental Boundary Breach

Operation outside an authorised environmental boundary should be treated as a significant assurance event where the boundary is safety-, mission- or autonomy-critical.

The response may include:

- Warning.
- Reduced capability.
- Reduced autonomy.
- Human confirmation.
- Fallback.
- Suspension.
- Incident investigation.

## 7. Incident Classification

A practical classification may consider:

### Severity

- Low.
- Moderate.
- High.
- Critical.

### Consequence

Potential effect on:

- Human life.
- Property.
- Mission outcome.
- System integrity.
- Information integrity.
- Human control.

### Assurance significance

- No material assurance impact.
- Potential assurance impact.
- Material assurance impact.
- Authorisation validity potentially affected.

## 8. Incident Assessment

The assessment should determine:

- What happened?
- What environmental condition contributed?
- What was expected?
- What actually occurred?
- Which assumptions were affected?
- How did the AI capability respond?
- How did humans respond?
- Was autonomy involved?
- Was the authorised boundary crossed?
- Was existing evidence sufficient?
- Was the event previously foreseeable?

## 9. Human and Command Considerations

Where an incident involves a consequential decision or action, the record should preserve sufficient information to establish:

- The relevant system state.
- The AI recommendation or action.
- The applicable authority.
- The human decision-maker.
- The human response.
- Any intervention or override.
- The basis for consequential decisions where practicable.

This supports accountability without assuming that the AI system itself is the legal or command authority.

## 10. Operational AI Advisor

Where an Operational AI Advisor is part of the governance model, the advisor may support incident interpretation by connecting:

**Environmental condition → AI behaviour → Mission implication → Risk → Recommended response**

The advisor should not replace the designated command or authorising authority.

## 11. Fail-Safe and Emergency Response

Where continued operation could create unacceptable harm, pre-authorised emergency procedures should permit immediate protective action.

Where circumstances permit, escalation may proceed through relevant:

**Developer / Technical Authority → System Manager → Operational AI Advisor → Command Authority**

This sequence should not delay emergency protective action when delay itself creates unacceptable risk.

## 12. Evidence Preservation

Relevant evidence should be preserved according to applicable policy and security requirements.

Examples include:

- System logs.
- Environmental indicators.
- Configuration state.
- Relevant data and metadata.
- AI outputs.
- Human actions.
- Autonomy state.
- Alerts.
- Communications relevant to the incident.
- Time sequence of events.

Evidence handling should maintain integrity and traceability.

## 13. Root Cause and Contributing Factors

Investigation should avoid assuming that the AI model alone caused the incident.

Contributing factors may include:

- Environment.
- Data.
- Sensors.
- Communications.
- Navigation.
- Human factors.
- System integration.
- Model behaviour.
- Autonomy design.
- Security.
- Supply chain.
- Operational procedures.
- Inadequate assumptions.
- Inadequate assurance.

## 14. Containment

Depending on risk, containment may include:

- Restricting the affected capability.
- Reducing autonomy.
- Increasing human supervision.
- Restricting environmental conditions.
- Disabling affected functions.
- Suspending operational use.
- Returning to a known safe configuration.

Containment should remain traceable to the identified risk.

## 15. Assurance Impact Assessment

Every material environmental incident should be assessed for possible impact on:

- Risk assessment.
- Environmental boundaries.
- TEVV evidence.
- Human-control assumptions.
- Autonomy authorisation.
- Security assurance.
- Mission effectiveness.
- Operational authorisation.

## 16. Revalidation and Reauthorisation

Revalidation should be considered when the incident indicates that existing evidence may no longer adequately support the capability.

Reauthorisation should be considered where the incident:

- Changes the risk profile.
- Invalidates material assumptions.
- Requires changed operating conditions.
- Requires a different autonomy level.
- Changes human authority arrangements.
- Demonstrates operation outside the authorised envelope.

## 17. Corrective and Preventive Actions

Actions may include:

- Technical correction.
- Environmental restriction.
- Monitoring enhancement.
- Additional training.
- Revised procedures.
- Additional TEVV.
- Risk reassessment.
- Autonomy reduction.
- Configuration change.
- Reauthorisation.
- Retirement where assurance cannot be restored.

## 18. Lessons Learned

Incident findings should feed into the wider framework.

Relevant outputs may update:

- Mission assumptions.
- Environmental profiles.
- Risk models.
- TEVV scenarios.
- Monitoring indicators.
- Fail-safe procedures.
- Training.
- Operational boundaries.
- Procurement requirements.
- Future system design.

## 19. Incident Closure

An incident should be closed only when the responsible authority is satisfied that:

- Immediate risk has been controlled.
- Required evidence has been preserved.
- Investigation is complete to the required level.
- Assurance implications have been assessed.
- Corrective actions are assigned.
- Revalidation or reauthorisation requirements are resolved or formally accepted.

## 20. Incident Records

The incident record should contain, as appropriate:

- Incident identifier.
- Date and context.
- Capability.
- Mission/use case.
- Environmental conditions.
- System state.
- Autonomy state.
- Human involvement.
- Consequence.
- Immediate response.
- Investigation findings.
- Assurance impact.
- Corrective actions.
- Authority decisions.
- Closure status.

## 21. Continuous Assurance

Environmental incidents should be treated as feedback into continuous assurance.

Repeated incidents may indicate:

- Inadequate environmental characterisation.
- Inadequate operating boundaries.
- Insufficient TEVV.
- Weak monitoring.
- Inadequate human controls.
- Unrecognised dependencies.
- Systemic governance deficiencies.

## 22. Governance Questions

Decision-makers should be able to answer:

1. What environmental condition contributed to the incident?
2. Was the capability within its authorised envelope?
3. What did the system do?
4. What did humans do?
5. Was meaningful human control maintained?
6. Did the incident expose an assurance gap?
7. Does existing evidence remain valid?
8. Is additional TEVV required?
9. Is revalidation or reauthorisation required?
10. What has been learned for future operational use?

## 23. Core Rule

> **Environmental incidents must be used to restore control, understand failure, strengthen assurance and prevent recurrence—not merely to return the system to service.**
