# 04 Authorisation Conditions and Restrictions

## 1. Purpose

This document defines how conditions and restrictions are established, documented, monitored and enforced as part of Defence AI operational authorisation.

Conditions and restrictions provide a mechanism to permit controlled operational use where unrestricted employment would not be justified by the available evidence, risk profile, autonomy, environment or human-control arrangements.

---

## 2. Core Principle

**Operational authorisation defines what an AI capability is permitted to do; conditions and restrictions define the boundaries within which that authority remains valid.**

A capability shall not be interpreted as having authority beyond its explicitly authorised conditions.

---

## 3. Why Conditions and Restrictions Matter

Operational AI capabilities may have:

- Known limitations.
- Uncertainty in specific environments.
- Restricted evidence coverage.
- Dependencies that require monitoring.
- Elevated risks at higher autonomy levels.
- Human-control constraints.
- Temporary assurance gaps.
- Mission-specific limitations.

Conditions allow risk to be managed without treating authorisation as a binary unrestricted approval.

---

## 4. Types of Conditions

Conditions may be applied to:

1. Mission
2. Environment
3. Autonomy
4. Human authority
5. Configuration
6. Data and information
7. Security
8. Dependencies
9. Monitoring
10. Duration
11. Personnel competence
12. Geographic or operational scope
13. Fail-safe arrangements
14. Reporting and escalation
15. Additional assurance

Conditions should be proportionate to the identified risk.

---

## 5. Mission Conditions

Mission-related conditions may define:

- Permitted missions.
- Permitted use cases.
- Specific decision-support functions.
- Prohibited uses.
- Consequence limits.
- Required human confirmation.
- Required escalation.
- Circumstances in which employment must cease.

An authorisation for one mission shall not automatically extend to materially different missions.

---

## 6. Environmental Conditions

Environmental conditions may define:

- Approved operating environments.
- Environmental boundaries.
- Weather or visibility limitations where relevant.
- Sensor limitations.
- Communication requirements.
- Navigation requirements.
- Information availability.
- Electromagnetic conditions.
- Computing or power dependencies.
- Adversarial conditions.

Use outside the authorised environmental envelope shall require an appropriate decision under the applicable governance process.

---

## 7. Autonomy Restrictions

Autonomy restrictions shall explicitly identify:

- Maximum authorised autonomy.
- Functions permitted at that autonomy level.
- Actions requiring human approval.
- Actions prohibited to the AI.
- Conditions for autonomy transition.
- Conditions requiring reduction of autonomy.
- Conditions requiring suspension or termination.

An increase in technical capability shall not automatically increase operational authority.

---

## 8. Human-Control Conditions

Where meaningful human control is required, conditions may specify:

- Minimum supervision level.
- Required operator competence.
- Human confirmation requirements.
- Intervention capability.
- Override availability.
- Maximum acceptable response time.
- Escalation requirements.
- Minimum situational awareness.
- Human workload limitations.

If required human control cannot be maintained, the relevant authority shall determine whether autonomy must be reduced or employment suspended.

---

## 9. Configuration Restrictions

Authorisation may be limited to a specific configuration baseline, including:

- Model version.
- Model state or weights where applicable.
- Software version.
- Hardware configuration.
- Data pipeline.
- Interfaces.
- Security controls.
- Autonomy settings.
- Human-machine interface.
- Critical dependencies.

Material changes outside the authorised baseline shall trigger change assessment.

---

## 10. Data and Information Conditions

Where AI performance depends materially on data or information, conditions may specify:

- Approved data sources.
- Minimum data quality.
- Required provenance.
- Information freshness.
- Source integrity.
- Permitted data handling.
- Access controls.
- Required validation.
- Conditions for degraded or incomplete data.

Where material information uncertainty exists, the system and human users should be able to recognise and appropriately manage that uncertainty.

---

## 11. Security Conditions

Security-related conditions may include:

- Required security controls.
- Access restrictions.
- Configuration protection.
- Monitoring requirements.
- Integrity verification.
- Approved interfaces.
- Dependency restrictions.
- Incident reporting.
- Additional security testing.

A material security condition shall be treated as part of the operational authority, not as an optional technical recommendation.

---

## 12. Supply-Chain and Dependency Conditions

Conditions may be imposed where operational assurance depends on:

- Specific suppliers.
- Critical software components.
- External services.
- Communications infrastructure.
- Navigation services.
- Data providers.
- Update mechanisms.
- Hardware dependencies.

The authorisation should define what happens if a critical dependency becomes unavailable, compromised, unreliable or materially changed.

---

## 13. Monitoring Conditions

Monitoring conditions should define:

- What must be monitored.
- Who is responsible.
- Monitoring frequency or trigger.
- Thresholds.
- Escalation criteria.
- Required records.
- Required response.
- Authority to restrict or suspend employment.

Monitoring should focus on changes that could invalidate the basis of authorisation.

---

## 14. Duration and Validity Conditions

Authorisation may be:

- Time-limited.
- Event-limited.
- Configuration-limited.
- Mission-limited.
- Environment-limited.
- Evidence-limited.

A validity period shall not be treated as proof that the capability remains suitable regardless of material changes.

Authorisation should remain subject to continuous assurance and defined review triggers.

---

## 15. Conditional Authorisation

Conditional authorisation may be appropriate where:

- Evidence is sufficient for a restricted use.
- Residual risk is understood and accepted.
- Additional safeguards compensate for identified limitations.
- Further evidence is being generated.
- The operational need justifies restricted employment.

The conditions shall be explicit enough to determine when the capability is within or outside its authority.

---

## 16. Restricted Authorisation

A restricted state may be used where the capability remains employable but its authorised scope must be reduced.

Restrictions may include:

- Lower autonomy.
- Narrower mission scope.
- Additional supervision.
- Reduced operating envelope.
- Additional monitoring.
- Limited duration.
- Specific configuration.
- Prohibited functions.

Restriction should be preferred over unrestricted employment where a defined reduction in scope can adequately manage the identified risk.

---

## 17. Prohibited Uses

The authorisation record should explicitly identify uses that are outside authority.

Examples of generic prohibited categories may include:

- Use outside the approved mission.
- Use outside the authorised environment.
- Use with an unauthorised configuration.
- Use beyond the authorised autonomy level.
- Use without required human authority.
- Use after a defined suspension trigger.
- Use where mandatory safeguards are unavailable.
- Use where critical assumptions are known to be invalid.

---

## 18. Entry Conditions

Before operational employment, applicable conditions should be verified.

Entry conditions may include:

- Approved configuration.
- Required personnel.
- Required training.
- Required human authority.
- Environmental suitability.
- Security controls.
- Data availability.
- Monitoring readiness.
- Fail-safe readiness.
- Dependency availability.
- Valid authorisation status.

Failure of a mandatory entry condition should prevent operational entry unless an approved exception process applies.

---

## 19. Boundary Conditions

The authorisation should identify conditions at which the capability approaches or reaches the edge of its authorised envelope.

Boundary indicators may relate to:

- Environmental degradation.
- Sensor performance.
- Communication availability.
- Data quality.
- System performance.
- Human workload.
- Autonomy behaviour.
- Security posture.
- Dependency availability.

Boundary conditions should trigger predefined responses where practicable.

---

## 20. Suspension Conditions

Suspension triggers may include:

- Material safety concern.
- Significant AI-related incident.
- Loss of required human control.
- Critical security compromise.
- Material configuration uncertainty.
- Operating outside the demonstrated envelope.
- Failure of critical safeguards.
- Significant degradation in mission performance.
- Loss of critical dependency.
- Evidence that invalidates a key assurance assumption.

Suspension should remain in effect until the responsible authority determines that continued employment is justified.

---

## 21. Revocation Conditions

Revocation may be appropriate where:

- The basis for authorisation is no longer valid.
- Material risks cannot be adequately controlled.
- Critical evidence is shown to be invalid.
- The capability cannot meet mandatory conditions.
- Repeated incidents demonstrate unacceptable behaviour.
- Governance or legal requirements cannot be satisfied.
- The capability has reached retirement or has been permanently withdrawn from authorised use.

Revocation removes operational authority. It does not necessarily require immediate technical destruction or retirement of the system.

---

## 22. Emergency Conditions

Emergency procedures may include pre-authorised protective actions where delay could create unacceptable harm.

Emergency conditions should define:

- Who may act.
- Triggering circumstances.
- Permitted protective action.
- Maximum scope.
- Required safeguards.
- Notification requirements.
- Post-event recording.
- Review requirements.

Emergency conditions shall not create unrestricted AI authority.

---

## 23. Condition Management

Each condition should have:

- Unique identifier.
- Description.
- Rationale.
- Risk addressed.
- Responsible owner.
- Verification method.
- Monitoring method.
- Effective date.
- Review date or trigger.
- Escalation requirement.
- Consequence of non-compliance.

Conditions should be maintained as controlled records.

---

## 24. Non-Compliance with Conditions

If a mandatory authorisation condition is breached:

1. The breach should be detected and recorded.
2. Immediate protective action should be taken where required.
3. Operational authority should be reassessed.
4. The appropriate authority should be notified.
5. Risk and assurance impact should be assessed.
6. Additional controls, restriction or suspension should be considered.
7. Revalidation or reauthorisation should be initiated where required.
8. Lessons learned should be captured.

Repeated or material breaches should trigger governance review.

---

## 25. Change to Conditions

Conditions should be reviewed when:

- Mission changes.
- Environment changes.
- Autonomy changes.
- Configuration changes.
- New evidence becomes available.
- A significant incident occurs.
- Threat conditions change.
- Human-control arrangements change.
- Critical dependencies change.
- New legal or policy requirements apply.

Conditions should not be informally relaxed to accommodate operational convenience.

---

## 26. Verification and Auditability

Conditions should be measurable or verifiable where practicable.

The organisation should be able to demonstrate:

- That conditions were communicated.
- That conditions were understood.
- That conditions were active.
- That compliance was monitored.
- That breaches were recorded.
- That corrective action was taken.

This evidence should form part of the operational assurance record.

---

## 27. Condition Hierarchy

Where multiple conditions apply, the most restrictive applicable requirement should govern unless a competent authority explicitly approves otherwise.

Conditions should be organised by:

**Mission → Environment → Autonomy → Human Authority → Configuration → Dependencies → Monitoring → Emergency/Suspension**

This helps prevent conflicting interpretations.

---

## 28. Golden Thread Integration

Conditions and restrictions provide the operational link between assurance evidence and authorised employment:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Each material condition should be traceable to the risk, requirement, evidence or assurance finding that justified it.

---

## 29. Core Rule

**An authorisation condition is part of the authority itself. If a mandatory condition cannot be satisfied, the capability is not operating within the basis on which it was authorised.**

---

## 30. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03_Authorisation_Decision_Rights.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
