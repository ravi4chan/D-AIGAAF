# 05 Authorisation Record

## 1. Purpose

This document defines the structure and minimum content of the Defence AI Operational Authorisation Record.

The Authorisation Record is the controlled governance record that establishes what an AI capability is permitted to do, under whose authority, for which mission, in which environment, at what autonomy level and subject to which conditions.

It provides the authoritative link between assurance evidence and operational employment.

---

## 2. Core Principle

**No operational authority should exist without a corresponding, controlled and traceable authorisation record.**

The record shall represent the specific authority granted rather than a general statement that the AI system is "approved" or "safe".

---

## 3. Authorisation Object

The record shall describe the complete authorisation object:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

A separate record, amendment or reauthorisation should be used where material changes alter this combination.

---

## 4. Purpose of the Record

The Authorisation Record should allow an authorised person to determine:

1. What capability is authorised.
2. For what mission or use case.
3. In which environment.
4. At what autonomy level.
5. Under whose human authority.
6. With which configuration.
7. On what evidence.
8. Subject to what limitations and conditions.
9. With what residual risk.
10. Until when or under what review conditions.
11. What events would restrict, suspend or revoke the authority.

---

## 5. Minimum Record Information

The record should contain, as applicable:

- Authorisation identifier.
- Capability identifier.
- System and model identification.
- Capability owner.
- Mission and use case.
- Operational environment.
- Autonomy level.
- Human authority.
- Configuration baseline.
- Authorising authority.
- Assurance status.
- Evidence references.
- Residual-risk statement.
- Conditions and restrictions.
- Monitoring requirements.
- Fail-safe requirements.
- Critical dependencies.
- Validity period.
- Review triggers.
- Suspension triggers.
- Revocation triggers.
- Approval decision.
- Decision rationale.
- Date and version.
- Relevant amendments.

---

## 6. Authorisation Identifier

Each authorisation should have a unique identifier.

The identifier should allow the record to be associated with:

- Capability register.
- Assurance record.
- Risk assessment.
- TEVV evidence.
- Operational records.
- Change records.
- Incident records.
- Revalidation.
- Reauthorisation.
- Retirement and decommissioning records.

---

## 7. Capability Identification

The record shall identify the capability sufficiently to prevent ambiguity.

This may include:

- Capability name.
- System identifier.
- Model identifier.
- Model version.
- Software version.
- Hardware configuration.
- Relevant interfaces.
- Configuration baseline.
- Critical dependencies.

Where model behaviour can change without an obvious user-facing software version change, the relevant model state or equivalent controlled identifier should be recorded where practicable.

---

## 8. Mission and Use Case

The record shall identify:

- Mission.
- Use case.
- Operational objective.
- Intended users.
- Decisions or functions supported.
- Permitted functions.
- Prohibited functions.
- Consequence-sensitive limitations.

The mission scope should be sufficiently precise to prevent unintended expansion of operational authority.

---

## 9. Operational Environment

The record shall define the authorised operating envelope.

This may include:

- Physical conditions.
- Terrain and environmental conditions.
- Sensor conditions.
- Communication availability.
- Navigation conditions.
- Information environment.
- Electromagnetic conditions.
- Computing and power dependencies.
- Human operating conditions.
- Adversarial conditions.

The record should identify known environmental limitations and relevant boundary conditions.

---

## 10. Autonomy Level

The authorised autonomy level shall be explicitly recorded.

The record should state:

- Authorised autonomy level.
- Functions permitted at that level.
- Actions requiring human approval.
- Prohibited autonomous actions.
- Human supervision requirements.
- Conditions for autonomy transition.
- Conditions requiring reduction or termination of autonomy.

The D-AIGAAF working autonomy construct may be used:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These levels are working constructs and should be mapped to applicable national, defence, legal or doctrinal terminology before formal adoption.

---

## 11. Human Authority

The record shall identify:

- Authorised human authority.
- Operational commander or responsible authority.
- Operator or supervisory role.
- Human decision rights.
- Intervention and override authority.
- Escalation arrangements.
- Required competence.

Where an Operational AI Advisor (OAIA) is involved, the record may identify the OAIA role and advisory responsibilities.

The record shall not imply that the AI itself holds operational decision authority.

---

## 12. Assurance Basis

The record shall identify the assurance basis for the decision.

This should include references to:

- Requirements assessment.
- Risk assessment.
- Autonomy assessment.
- Human-control assessment.
- TEVV evidence.
- Security assessment.
- Data assurance.
- Supply-chain assessment.
- Operational environment assessment.
- Fail-safe assessment.
- Independent review where applicable.

The record should state any material evidence limitations.

---

## 13. Evidence References

Evidence should be referenced rather than copied into the authorisation record.

Each material evidence reference should identify, where appropriate:

- Evidence identifier.
- Evidence type.
- Configuration tested.
- Conditions tested.
- Date.
- Responsible organisation.
- Findings.
- Limitations.
- Relevance to authorisation.

The authorisation record should make it possible to trace a decision back through the Golden Thread.

---

## 14. Residual Risk

The record shall identify accepted residual risks.

For each material residual risk, it should record:

- Risk identifier.
- Risk description.
- Potential consequence.
- Existing controls.
- Remaining uncertainty.
- Risk owner.
- Acceptance authority.
- Conditions attached to acceptance.
- Review trigger.

Risk acceptance shall remain within the authority delegated by the adopting organisation.

---

## 15. Conditions and Restrictions

All mandatory conditions shall form part of the authorisation record.

These may include:

- Mission restrictions.
- Environmental restrictions.
- Autonomy restrictions.
- Human supervision requirements.
- Configuration restrictions.
- Data requirements.
- Security controls.
- Dependency requirements.
- Monitoring requirements.
- Duration limits.
- Training requirements.
- Prohibited uses.

Conditions should have identifiable owners and verification mechanisms where practicable.

---

## 16. Fail-Safe and Degraded Operation

The record shall identify applicable requirements for:

- Fail-safe behaviour.
- Loss of communications.
- Sensor degradation.
- Data degradation.
- Navigation degradation.
- Computing or power limitations.
- Loss of human supervision.
- Security incidents.
- Model anomalies.

Where emergency protective procedures are pre-authorised, the relevant authority and limits should be recorded.

---

## 17. Monitoring and Continuous Assurance

The record shall identify the monitoring arrangements required to maintain the basis of authorisation.

This may include:

- Performance indicators.
- Risk indicators.
- Environment indicators.
- Security indicators.
- Autonomy indicators.
- Human-control indicators.
- Thresholds.
- Escalation criteria.
- Reporting requirements.

Material changes in monitored conditions should trigger the applicable governance response.

---

## 18. Validity and Review

The record should identify:

- Effective date.
- Validity period where applicable.
- Scheduled review date.
- Mandatory review triggers.
- Conditions for continuation.
- Revalidation requirements.
- Reauthorisation requirements.

A validity period does not override mandatory review following a material change or incident.

---

## 19. Suspension Triggers

The record shall identify events that may require restriction or suspension, including:

- Significant AI incident.
- Loss of meaningful human control.
- Critical security concern.
- Material configuration uncertainty.
- Operation outside authorised boundaries.
- Failure of mandatory safeguards.
- Significant performance degradation.
- Loss of critical dependency.
- Evidence invalidating a key assumption.
- Material change without required assessment.

---

## 20. Revocation Triggers

The record should identify circumstances under which operational authority may be revoked, including:

- The assurance basis is no longer valid.
- Mandatory requirements cannot be satisfied.
- Material risks cannot be adequately controlled.
- Critical evidence is invalidated.
- Repeated serious incidents occur.
- Legal or policy authority is withdrawn.
- The capability is permanently withdrawn or retired.

Revocation removes operational authority. It does not necessarily mean immediate technical decommissioning.

---

## 21. Decision and Rationale

The record shall state the authorisation decision, such as:

- Operationally Authorised.
- Conditionally Authorised.
- Restricted.
- Suspended.
- Revoked.
- Not Authorised.

The decision should include a concise rationale explaining why the authority is justified within the defined context.

---

## 22. Approval and Accountability

The record shall identify:

- Authorising authority.
- Supporting authorities where applicable.
- Decision date.
- Approval status.
- Delegation basis where applicable.
- Accountability for the decision.

Where multiple authorities contribute to the decision, their responsibilities should remain distinguishable.

---

## 23. Amendments

Changes to an authorisation record shall be controlled.

Each amendment should identify:

- Amendment identifier.
- Date.
- Change description.
- Reason.
- Affected authorisation element.
- Change classification.
- Assessment performed.
- Whether revalidation was required.
- Whether reauthorisation was required.
- Approving authority.

Material amendments should not be implemented through informal editing.

---

## 24. Authorisation States

The record should support the D-AIGAAF authorisation lifecycle:

**Proposed → Under Assurance → Conditionally Authorised → Operationally Authorised → Restricted → Suspended → Revoked / Retired**

Movement between states shall be authorised by the appropriate decision authority.

---

## 25. Record Integrity and Access

The Authorisation Record shall be:

- Controlled.
- Versioned.
- Protected from unauthorised modification.
- Accessible to authorised personnel.
- Retained according to applicable records policy.
- Traceable to supporting evidence.
- Linked to relevant operational and assurance records.

Where appropriate, changes should be auditable.

---

## 26. Relationship with Other Records

The Authorisation Record should link to the principal D-AIGAAF records:

1. **Defence AI Capability Register (DAICR)** — what capabilities exist.
2. **Defence AI Assurance Record (DAAR)** — what evidence exists and what it demonstrates.
3. **Operational Authorisation Record** — what employment is authorised and under what conditions.
4. **Operational Record** — what actually occurred during employment.

This separation prevents capability existence, assurance and operational authority from being conflated.

---

## 27. Golden Thread

The Authorisation Record provides the formal bridge between assurance and operational authority:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Every material authorisation decision should be traceable through this chain.

---

## 28. Minimum Record Quality Test

Before an authorisation is issued, an independent reviewer should be able to determine from the record:

- What is authorised?
- Why is it authorised?
- For which mission?
- Under which conditions?
- At what autonomy?
- Under whose authority?
- Against which configuration?
- Based on what evidence?
- With what residual risk?
- What limitations apply?
- What monitoring is required?
- What would cause the authority to change?

If these questions cannot be answered, the authorisation record should be considered incomplete.

---

## 29. Core Rule

**The Authorisation Record is the authoritative statement of operational permission. If an action, mission, environment, autonomy level or configuration is outside the record, it should not be treated as authorised without an appropriate governance decision.**

---

## 30. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03_Authorisation_Decision_Rights.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
