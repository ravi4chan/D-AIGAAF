# 07 Authorisation Suspension and Revocation

## 1. Purpose

This document defines the governance process for restricting, suspending or revoking operational authorisation for a Defence AI capability.

Suspension and revocation provide mechanisms to prevent continued operational employment when the basis for authorisation is no longer valid, when unacceptable risk emerges, or when required controls and conditions can no longer be relied upon.

---

## 2. Core Principle

**Operational authority shall remain conditional on continued satisfaction of the conditions, controls, evidence and assumptions on which that authority was granted.**

Suspension or revocation shall be treated as governance actions, not merely technical responses.

---

## 3. Distinction Between Restriction, Suspension and Revocation

### Restriction

Limits the authorised scope while allowing specified employment to continue.

Examples include:

- Reduced mission scope.
- Reduced autonomy.
- Restricted environment.
- Increased human supervision.
- Restricted configuration.
- Additional monitoring.

### Suspension

Temporarily removes operational authority while assessment, containment, investigation or corrective action is undertaken.

### Revocation

Formally withdraws operational authority.

Revocation may result from:

- Persistent unacceptable risk.
- Fundamental failure of assurance.
- Loss of required authority.
- Material loss of control.
- Unacceptable security compromise.
- Failure of mandatory conditions.
- Evidence that the capability is unsuitable for its authorised purpose.

Revocation does not necessarily mean immediate technical destruction or permanent retirement.

---

## 4. Suspension and Revocation Triggers

Potential triggers include:

- Serious AI-related incident.
- Loss of meaningful human control.
- Unexpected consequential behaviour.
- Material failure of fail-safe mechanisms.
- Operation outside authorised boundaries.
- Uncontrolled autonomy transition.
- Significant security compromise.
- Material model or configuration change without appropriate approval.
- Critical dependency failure.
- Significant data integrity failure.
- Evidence that key assumptions are invalid.
- Material degradation of performance.
- New evidence demonstrating unacceptable risk.
- Loss of required operational conditions.
- Breach of mandatory authorisation conditions.
- Legal or policy authority becoming invalid.
- Failure to complete required revalidation or reauthorisation.
- Repeated non-compliance.
- Inability to adequately monitor the capability.

A trigger does not necessarily require permanent revocation. The response should be proportionate to the nature and severity of the issue.

---

## 5. Immediate Protective Action

Where continued operation could create unacceptable harm, authorised personnel should be able to take immediate protective action.

This may include:

- Reducing autonomy.
- Removing the capability from a mission.
- Moving to a safe or degraded operating mode.
- Suspending selected functions.
- Disconnecting affected interfaces where appropriate.
- Invoking an approved fail-safe procedure.

Emergency protective actions should be defined in advance where reasonably foreseeable.

The need for immediate protective action should not be delayed by normal administrative approval processes when delay could materially increase harm.

Actions taken under emergency authority shall be recorded and subsequently reviewed.

---

## 6. Decision Authority

The authorisation governance model should define who may:

- Recommend restriction.
- Direct temporary protective action.
- Impose restriction.
- Suspend authority.
- Confirm suspension.
- Restore authority.
- Revoke authority.

Decision rights should reflect:

- Consequence.
- Mission criticality.
- Autonomy.
- Operational scope.
- Risk.
- Urgency.

The Authorising Authority retains responsibility for formal operational authorisation decisions unless authority has been explicitly delegated.

---

## 7. Emergency Suspension

Emergency suspension should be available where there is credible evidence that continued employment could create unacceptable risk.

The process should establish:

1. Immediate protective action.
2. Notification of relevant authorities.
3. Preservation of evidence.
4. Initial risk assessment.
5. Determination of affected scope.
6. Formal suspension decision where required.
7. Investigation and assurance assessment.
8. Corrective actions.
9. Decision on restoration, restriction or revocation.

Emergency suspension should be reversible where the underlying issue can be adequately addressed.

---

## 8. Scope of Suspension

Suspension may apply to:

- Entire capability.
- Specific model or version.
- Specific configuration.
- Specific mission.
- Specific use case.
- Specific autonomy level.
- Specific environment.
- Specific user group.
- Specific interface or function.

The suspension record should clearly identify what authority has been removed and what, if anything, remains authorised.

---

## 9. Conditions During Suspension

During suspension:

- Suspended functions shall not be treated as operationally authorised.
- Any permitted technical or investigative activity shall be clearly distinguished from operational employment.
- Relevant evidence shall be preserved.
- Changes should be controlled.
- Investigation and assurance activities should be documented.
- Restoration should require an explicit decision.

Suspension should not create ambiguity about operational authority.

---

## 10. Investigation and Assurance Response

Following suspension, the organisation should determine:

- What happened.
- When it happened.
- Which configuration was involved.
- Which mission and environment were involved.
- What the AI system did.
- What humans did.
- What controls operated or failed.
- Whether the event was foreseeable.
- Whether similar conditions could recur.
- Whether other capabilities are affected.

The investigation should determine whether the original assurance basis remains valid.

Where necessary, additional TEVV, security assessment, environmental testing, human-control assessment or risk analysis should be undertaken.

---

## 11. Root Cause and Contributing Factors

Investigation should consider multiple possible causes, including:

- Model behaviour.
- Data.
- Software.
- Hardware.
- Integration.
- Configuration.
- Human factors.
- Operational environment.
- Communications.
- Security.
- Supply chain.
- Dependency failure.
- Governance failure.
- Inadequate assumptions or requirements.

The objective should be to identify systemic contributing factors rather than attributing the event solely to an individual or component.

---

## 12. Restoration of Authority

Suspended authority should not automatically return when an investigation is completed.

Restoration should require evidence that:

- The immediate issue is understood.
- Necessary corrective actions are complete or appropriately controlled.
- Residual risk is acceptable.
- Required testing has been completed.
- Configuration is controlled.
- Human authority remains effective.
- Fail-safe arrangements are adequate.
- Authorisation conditions remain appropriate.
- Required evidence is current.

The restoration decision should be recorded by the appropriate authority.

---

## 13. Restricted Restoration

Where full restoration is not justified, authority may be restored under restrictions.

Restrictions may include:

- Lower autonomy.
- Narrower mission scope.
- Restricted environments.
- Additional human supervision.
- Increased monitoring.
- Specific configuration constraints.
- Additional reporting.
- Time-limited authority.

Restricted restoration should have explicit review criteria.

---

## 14. Revalidation and Reauthorisation

Suspension should transition to formal revalidation or reauthorisation when the event indicates that the previous assurance or authorisation basis is no longer sufficient.

Examples include:

- Material model changes.
- New failure modes.
- Significant autonomy changes.
- Loss of human-control assumptions.
- Material environmental changes.
- New security threats.
- Major dependency changes.
- Significant changes to mission consequence.

Reauthorisation should follow the applicable D-AIGAAF decision process.

---

## 15. Revocation

Revocation should be considered where:

- The capability cannot be adequately controlled.
- Required assurance cannot be established.
- Residual risk remains unacceptable.
- Mandatory conditions cannot be satisfied.
- Operational authority is no longer legally or organisationally valid.
- The capability is fundamentally unsuitable for its authorised mission.
- Repeated failures demonstrate that continued authority is not justified.

Revocation should identify the effective scope and date.

---

## 16. Consequences of Revocation

Following revocation:

- Operational employment under the revoked authority shall cease.
- Affected authorisation records shall be updated.
- Relevant users and authorities shall be informed.
- Configuration and evidence shall be preserved where required.
- Dependencies and interfaces should be assessed.
- Any continued technical use shall require separate appropriate authority.
- Retirement or decommissioning should be considered where appropriate.

Revocation should be distinguishable from lifecycle retirement and decommissioning.

---

## 17. Notification and Escalation

Suspension or revocation should trigger notification appropriate to the level of risk.

Relevant stakeholders may include:

- Authorising Authority.
- Command/Operational Authority.
- Capability Owner.
- System Manager.
- Technical Authority.
- Assurance/TEVV Authority.
- Security Authority.
- Operational AI Advisor.
- Risk Owner.
- Relevant oversight bodies.

Notification requirements should be proportionate and defined by policy.

---

## 18. Evidence Preservation

Following a significant suspension or revocation event, relevant evidence should be preserved, including:

- System configuration.
- Model version/state where available.
- Logs.
- Inputs and outputs where permitted.
- Human decisions.
- Environmental conditions.
- Security events.
- Alerts.
- Monitoring records.
- Communications relevant to the event.
- Previous assurance evidence.
- Authorisation conditions.

Evidence preservation should respect applicable security, privacy, classification and legal requirements.

---

## 19. No Silent Restoration

A suspended capability shall not return to operational use merely because:

- The immediate problem appears to have disappeared.
- A software restart succeeds.
- A new operator takes over.
- The system passes a basic functional test.
- Operational demand increases.
- Time has elapsed.

Restoration requires an explicit governance decision supported by appropriate evidence.

---

## 20. Cross-Capability Impact

A significant event may reveal a systemic issue affecting other Defence AI capabilities.

The organisation should assess whether the event has implications for:

- Common models.
- Shared datasets.
- Common software.
- Common suppliers.
- Shared infrastructure.
- Common interfaces.
- Similar use cases.
- Similar autonomy mechanisms.
- Common operational environments.

Where necessary, other authorisations should be reviewed, restricted or suspended.

---

## 21. Review After Suspension or Revocation

A post-event governance review should consider:

- Whether the response was timely.
- Whether decision rights were clear.
- Whether warning indicators were available.
- Whether monitoring worked.
- Whether human intervention was effective.
- Whether fail-safe arrangements worked.
- Whether evidence was sufficient.
- Whether authorisation conditions were adequate.
- Whether similar risks remain elsewhere.
- What changes are required.

Lessons should feed into continuous assurance and the D-AIGAAF lifecycle.

---

## 22. Record Requirements

The suspension or revocation record should capture:

- Authorisation identifier.
- Capability and configuration.
- Trigger.
- Date and time.
- Mission and environment.
- Autonomy level.
- Immediate action.
- Decision authority.
- Scope of restriction or suspension.
- Evidence considered.
- Risk assessment.
- Investigation status.
- Corrective actions.
- Restoration criteria.
- Final decision.
- Rationale.
- Notifications.
- Follow-up review.

All material decisions should remain traceable.

---

## 23. Golden Thread

Suspension and revocation preserve the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

When evidence shows that the basis for authority has failed, operational authority must be capable of being restricted, suspended or revoked.

---

## 24. Core Rule

**When the conditions supporting operational authority can no longer be demonstrated, the organisation shall have a clear, timely and accountable mechanism to restrict, suspend or revoke that authority before unacceptable risk is allowed to persist.**

---

## 25. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03_Authorisation_Decision_Rights.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `05_Authorisation_Record.md`
- `06_Authorisation_Review_and_Renewal.md`
- `03 Risk & Autonomy`
- `06 AI Security`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
