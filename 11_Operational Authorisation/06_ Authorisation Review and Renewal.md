# 06 Authorisation Review and Renewal

## 1. Purpose

This document defines the process for reviewing and, where appropriate, renewing Defence AI operational authorisation.

Operational authorisation shall not be treated as permanently valid. Its continued validity depends on the capability, mission, environment, autonomy, human authority, evidence, risks and assumptions remaining consistent with the basis on which authority was granted.

---

## 2. Core Principle

**Renewal is a governance decision based on continued validity of the authorisation basis; it is not an automatic administrative extension.**

A renewal assessment should determine whether the capability remains suitable for its authorised context and whether any conditions, restrictions or assurance requirements need to change.

---

## 3. When Review Is Required

Authorisation should be reviewed:

- At a scheduled review date.
- Before expiry of a time-limited authorisation.
- Following a material system change.
- Following a material model or model-state change.
- Following a significant data change.
- Following a mission change.
- Following a material environmental change.
- Following an autonomy change.
- Following a human-control change.
- Following a significant security event.
- Following a material AI-related incident.
- When a critical dependency changes.
- When new evidence changes the assurance position.
- When a key assumption is shown to be invalid.
- When applicable legal, policy or doctrinal requirements change.

The authorisation record should define mandatory review triggers.

---

## 4. Review Objectives

A review should determine whether:

1. The authorised capability remains correctly identified.
2. The authorised mission remains valid.
3. The operating environment remains within the authorised envelope.
4. The authorised autonomy remains justified.
5. Human authority and meaningful control remain effective.
6. The configuration remains consistent with the assurance evidence.
7. Risk remains within accepted limits.
8. Security controls remain effective.
9. Critical dependencies remain acceptable.
10. TEVV evidence remains relevant and sufficiently current.
11. Fail-safe arrangements remain effective.
12. Monitoring indicates acceptable operational performance.
13. Authorisation conditions remain appropriate.
14. No event has invalidated the original authorisation decision.

---

## 5. Review Inputs

The review should consider:

- Current Authorisation Record.
- Previous assessment.
- Assurance Record.
- TEVV results.
- Operational performance.
- Incident records.
- Security events.
- Change records.
- Revalidation results.
- Risk assessments.
- Environmental monitoring.
- Human-control assessments.
- Data and information assurance.
- Supply-chain assessments.
- Lessons learned.
- Relevant legal and policy changes.

---

## 6. Review of Configuration

The review shall confirm whether the deployed configuration remains consistent with the authorised configuration.

This should include, where relevant:

- Model version.
- Model state or weights.
- Software.
- Hardware.
- Data pipeline.
- Interfaces.
- Security controls.
- Autonomy settings.
- Human-machine interface.
- Critical dependencies.

Any unexplained difference between the authorised and deployed configuration should be treated as an assurance issue.

---

## 7. Review of Mission and Use Case

The review should confirm that:

- The mission remains within the authorised scope.
- The use case remains materially unchanged.
- Intended users remain appropriate.
- Consequences remain within the assessed range.
- No new use has become embedded without assessment.
- Prohibited or out-of-scope uses remain understood.

Operational success should not itself be interpreted as evidence that broader use is authorised.

---

## 8. Review of Operating Environment

The review should assess whether:

- Environmental assumptions remain valid.
- The operating envelope remains appropriate.
- New environmental conditions have emerged.
- Degraded or disconnected operation remains adequately addressed.
- Adversarial conditions have changed.
- Sensor or information conditions have changed.
- Human operating conditions remain acceptable.

Material environmental changes should trigger the applicable change and revalidation process.

---

## 9. Review of Autonomy

The review shall determine whether the authorised autonomy level remains appropriate.

It should consider:

- Actual autonomy behaviour.
- Autonomy transitions.
- Human supervision.
- Intervention effectiveness.
- Override capability.
- Failure behaviour.
- Boundary behaviour.
- Changes to mission consequence.
- New evidence on autonomous behaviour.

Operational experience shall not be used to justify increased autonomy without an appropriate assessment and authorisation decision.

---

## 10. Review of Human Authority

The review should confirm that:

- Responsible human authorities remain identified.
- Decision rights remain clear.
- Operators remain competent.
- AI literacy remains adequate.
- Human supervision remains practicable.
- Workload remains acceptable.
- Intervention remains possible where required.
- Escalation arrangements remain effective.
- Accountability remains traceable.

Changes in organisational structure or personnel should be assessed where they affect decision authority.

---

## 11. Review of Risk

The current risk position should be compared with the original authorisation basis.

The review should consider:

- New risks.
- Changed consequence.
- Changed mission criticality.
- Changed autonomy.
- Changed environment.
- New threat information.
- Incident trends.
- Performance degradation.
- Dependency changes.
- Security findings.
- Residual-risk changes.

A capability should not be renewed solely because no major incident has occurred.

Absence of incidents is not equivalent to evidence of absence of risk.

---

## 12. Review of Assurance Evidence

The review should determine whether existing evidence remains:

- Relevant.
- Current.
- Configuration-consistent.
- Representative.
- Sufficient.
- Traceable.

Evidence should be reconsidered when:

- The system changes.
- The operating context changes.
- New failure modes emerge.
- New threats are identified.
- Previous assumptions are invalidated.

---

## 13. Review of Operational Performance

Operational monitoring should be reviewed for:

- Performance trends.
- Reliability.
- False positives and false negatives where applicable.
- Unexpected behaviour.
- Degradation.
- Human intervention frequency.
- Autonomy transitions.
- Boundary events.
- Security events.
- Environmental excursions.
- User-reported limitations.

Performance should be assessed against the authorised mission rather than against generic system benchmarks alone.

---

## 14. Review of Conditions and Restrictions

Each authorisation condition should be reviewed for:

- Continued relevance.
- Compliance.
- Effectiveness.
- Owner.
- Verification.
- Monitoring.
- Necessity.

Conditions may be:

- Retained.
- Modified.
- Strengthened.
- Removed where justified.
- Replaced by additional controls.

Conditions should not be relaxed merely because they are operationally inconvenient.

---

## 15. Review of Incidents and Lessons Learned

The review shall consider relevant incidents, near misses and lessons learned.

Particular attention should be given to:

- Recurring anomalies.
- Unanticipated failure modes.
- Human-AI interaction problems.
- Loss of control.
- Environmental boundary events.
- Security incidents.
- Data problems.
- Dependency failures.

Material lessons should be incorporated into requirements, controls, TEVV, training, monitoring or authorisation conditions as appropriate.

---

## 16. Review of Dependencies

The review should determine whether critical dependencies remain:

- Available.
- Trusted.
- Supported.
- Secure.
- Resilient.
- Within their assessed assumptions.

Material supplier or dependency changes should trigger the applicable supply-chain and change-management processes.

---

## 17. Renewal Decision Categories

A review may result in:

### R1 — Renew

Existing authorisation remains appropriate.

### R2 — Renew with Revised Conditions

Authorisation remains valid but conditions or restrictions should be changed.

### R3 — Additional Assurance Required

Further evidence is required before renewal.

### R4 — Revalidation Required

The basis of authorisation has changed sufficiently to require formal revalidation.

### R5 — Reauthorisation Required

A new operational authorisation decision is required.

### R6 — Restrict or Suspend

Current conditions or risks no longer justify continued unrestricted employment.

### R7 — Do Not Renew

The capability should not continue under the existing authorisation.

These are D-AIGAAF working decision categories and may be aligned with organisational terminology.

---

## 18. Administrative Renewal

Administrative renewal should be limited to cases where:

- The capability is unchanged.
- Mission is unchanged.
- Environment is unchanged.
- Autonomy is unchanged.
- Human authority is unchanged.
- Configuration remains controlled.
- No material risk or assurance issue has emerged.
- No mandatory review trigger has occurred.

Administrative renewal shall not be used to bypass substantive reassessment.

---

## 19. Renewal Evidence Package

A renewal package should contain, as applicable:

- Current Authorisation Record.
- Configuration confirmation.
- Updated risk assessment.
- Current TEVV evidence.
- Operational performance summary.
- Incident and lessons-learned review.
- Security status.
- Dependency status.
- Environmental assessment.
- Human-control assessment.
- Compliance with conditions.
- Open actions.
- Proposed changes.
- Renewal recommendation.

The depth of review shall be proportionate to risk and consequence.

---

## 20. Expiry and Lapse of Authority

Where authorisation has an explicit expiry date:

- The renewal process should begin sufficiently before expiry.
- Employment after expiry should not be assumed to remain authorised.
- Any required interim authority should be separately approved.
- Expiry should be recorded.
- Continued employment without valid authority should be treated as a governance issue.

Administrative delay should not automatically create an extension of operational authority.

---

## 21. Reauthorisation Triggered by Review

A review should transition to reauthorisation where there is a material change to:

- Mission.
- Environment.
- Autonomy.
- Human authority.
- Configuration.
- Risk.
- Critical dependency.
- Assurance basis.
- Legal or policy authority.

Reauthorisation should use the applicable D-AIGAAF assessment and decision process rather than simply renewing the previous record.

---

## 22. Independence of Review

Review independence shall be proportionate to risk.

For higher-consequence capabilities, review should include appropriate independent technical, operational, assurance or security input.

The capability owner should not be the sole authority determining whether the basis for continued operational authority remains valid.

---

## 23. Review Decision Record

The review record should capture:

- Authorisation identifier.
- Capability and configuration.
- Review date.
- Review trigger.
- Mission.
- Environment.
- Autonomy.
- Human authority.
- Evidence considered.
- Findings.
- Risk position.
- Incidents and lessons.
- Conditions reviewed.
- Open actions.
- Review outcome.
- Decision authority.
- Rationale.
- Next review date or trigger.

---

## 24. Continuity of Authority

Where renewal is pending, the organisation should clearly establish whether:

- Existing authority remains valid until a specified date.
- Employment is restricted during review.
- Specific activities are suspended.
- Additional controls are required.
- Temporary authority has been separately granted.

There shall be no ambiguity about whether operational employment remains authorised.

---

## 25. Golden Thread

Review and renewal preserve the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The review should determine whether the evidence and assumptions supporting the existing authority remain valid throughout this chain.

---

## 26. Core Rule

**Operational authorisation should be renewed only when there is sufficient evidence that the basis on which authority was granted remains valid, or after the capability has undergone the additional assurance and reauthorisation required by material change.**

---

## 27. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03_Authorisation_Decision_Rights.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `05_Authorisation_Record.md`
- `03 Risk & Autonomy`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
