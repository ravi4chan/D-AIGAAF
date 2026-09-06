# 08 Authorisation Validity and Scope

## 1. Purpose

This document defines how D-AIGAAF establishes, expresses and controls the validity and scope of an operational authorisation for a Defence AI capability.

Operational authority is contextual. An authorisation applies only to the capability, mission, environment, autonomy, human authority, configuration and conditions explicitly covered by the authorisation decision.

---

## 2. Core Principle

**An operational authorisation is valid only within its defined scope, for its defined period, configuration, conditions and operational context.**

Authority should not be interpreted more broadly than the evidence and decision supporting it.

---

## 3. Authorisation Scope

Every authorisation should define, as applicable:

- AI capability.
- Model and system version.
- Configuration baseline.
- Mission.
- Use case.
- Operational environment.
- Geographic or operational boundaries where relevant.
- Autonomy level.
- Human authority.
- User/operator population.
- Permitted functions.
- Prohibited functions.
- Dependencies.
- Conditions and restrictions.
- Validity period.
- Monitoring requirements.

The scope should be sufficiently precise to prevent ambiguity about what is authorised.

---

## 4. Authorisation Object

D-AIGAAF defines the operational authorisation object as:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

A material change to any of these dimensions should trigger an assessment of whether the existing authorisation remains valid.

---

## 5. Validity Period

An authorisation may be:

- Time-limited.
- Condition-limited.
- Event-limited.
- Mission-limited.
- Configuration-limited.
- Environment-limited.
- Combination-limited.

The validity period should be proportionate to:

- Risk.
- Consequence.
- Autonomy.
- Mission criticality.
- Rate of change.
- Assurance uncertainty.
- Operational environment variability.

Higher-consequence capabilities may require shorter review intervals or more frequent confirmation.

---

## 6. Scope Boundaries

The authorisation should establish clear boundaries around:

- What the AI may do.
- Where it may operate.
- Under what conditions it may operate.
- At what autonomy level it may operate.
- Who may use or supervise it.
- What configuration is authorised.
- What data and dependencies may be used.
- What actions require human approval.
- What actions are prohibited.

A capability outside these boundaries should not be treated as authorised by default.

---

## 7. Mission Scope

Mission scope should identify:

- Approved mission purpose.
- Approved use cases.
- Intended users.
- Operational objectives.
- Relevant mission constraints.
- Consequence assumptions.
- Prohibited or excluded uses.

Successful performance in one mission does not automatically establish authorisation for another mission.

---

## 8. Environmental Scope

Environmental scope should identify the conditions under which authority applies.

These may include:

- Physical environment.
- Terrain.
- Weather.
- Illumination.
- Sensor conditions.
- Information environment.
- Electromagnetic conditions.
- Communication availability.
- Computing availability.
- Human operating conditions.
- Adversarial conditions.

Operating outside the demonstrated or authorised environment should trigger the applicable boundary, restriction or reauthorisation process.

---

## 9. Autonomy Scope

The authorisation should explicitly identify the permitted autonomy level.

D-AIGAAF uses the following working construct:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are working D-AIGAAF constructs and should be mapped to applicable national, defence, legal and international terminology before formal adoption.

A capability authorised at one autonomy level shall not be assumed to be authorised at a higher level.

---

## 10. Human Authority Scope

The authorisation should define:

- Responsible decision authority.
- Supervisory authority.
- Operator responsibilities.
- Intervention authority.
- Override authority.
- Escalation authority.
- Emergency authority.
- Accountability arrangements.

Where human approval is a condition of authorisation, the requirement should be explicit and operationally practicable.

---

## 11. Configuration Scope

Authorisation should apply to a defined configuration baseline.

Relevant configuration elements may include:

- Model.
- Model state or weights.
- Software.
- Hardware.
- Interfaces.
- Data pipeline.
- Security controls.
- Autonomy settings.
- Human-machine interface.
- Critical dependencies.

A change outside the authorised baseline should be assessed before being treated as operationally authorised.

---

## 12. Data and Information Scope

Where material to the capability, authorisation should define assumptions or limits concerning:

- Data sources.
- Data quality.
- Data provenance.
- Data timeliness.
- Information integrity.
- Sensor inputs.
- External information dependencies.
- Data-processing arrangements.

Material changes to these factors may alter the assurance basis.

---

## 13. Dependency Scope

Authorisation should identify critical dependencies where their failure could affect operational authority.

Examples include:

- Communications.
- Navigation.
- Positioning.
- Computing infrastructure.
- External services.
- Software libraries.
- Model providers.
- Hardware components.
- Data providers.

Where a dependency is essential to safe or authorised operation, its availability and failure behaviour should be understood.

---

## 14. Prohibited Use

An authorisation should identify uses that are outside its authority.

Examples may include:

- Use for an unapproved mission.
- Use at an unauthorised autonomy level.
- Use outside the approved environment.
- Use with an unauthorised configuration.
- Use by unauthorised personnel.
- Use when mandatory conditions are not satisfied.
- Use following a suspension.
- Use following expiry.
- Use following revocation.

Prohibited use should remain prohibited unless an appropriate governance decision changes the authorisation.

---

## 15. Conditional Validity

An authorisation may remain valid only while specified conditions are satisfied.

Conditions may relate to:

- Human supervision.
- Environmental limits.
- Communications.
- Sensor availability.
- Data quality.
- Security status.
- Configuration.
- Operator competence.
- Monitoring.
- Fail-safe readiness.

Failure of a mandatory condition should trigger the response specified in the authorisation record.

---

## 16. Boundary Conditions

Boundary conditions identify circumstances where the capability approaches or exceeds its demonstrated operating envelope.

These may include:

- Increasing uncertainty.
- Degraded sensors.
- Loss of communications.
- Navigation uncertainty.
- Environmental change.
- Adversarial interference.
- Performance degradation.
- Human workload increase.

The system should have defined responses to relevant boundary conditions.

These may include:

**Continue → Increase Supervision → Reduce Autonomy → Restrict Function → Safe State → Suspend**

---

## 17. Geographic and Operational Boundaries

Where appropriate, an authorisation may define:

- Geographic area.
- Operational formation or organisation.
- Mission phase.
- Time window.
- Specific operational activity.
- Approved interface or network.
- Approved supporting system.

Geographic or operational scope should not be inferred where it has not been explicitly established.

---

## 18. Temporal Scope

Temporal limits may apply to:

- Mission phase.
- Operating window.
- Validity period.
- Specific event.
- Environmental condition.
- Temporary authorisation.
- Emergency authority.

Temporary authority should have a clear start, end or termination condition.

---

## 19. Scope Expansion

Expansion of scope should require assessment before implementation.

Potential scope expansion includes:

- New mission.
- New use case.
- New environment.
- Higher autonomy.
- New user population.
- New configuration.
- New data source.
- New critical dependency.
- Wider operational area.

The extent of assurance required should be proportionate to the materiality of the expansion.

---

## 20. Scope Reduction

Scope may be reduced to manage risk.

Reduction may include:

- Lower autonomy.
- Fewer functions.
- Narrower mission.
- Restricted environment.
- Fewer users.
- Additional supervision.
- Additional monitoring.
- Restricted configuration.

Scope reduction may be used as a risk treatment while preserving limited operational utility.

---

## 21. Interpretation of Ambiguity

Where there is uncertainty about whether an activity falls within the authorisation scope:

- The narrower interpretation should apply pending clarification.
- The activity should not be treated as authorised solely by implication.
- The responsible authority should determine the applicable scope.
- Where necessary, the authorisation should be amended or reissued.

Ambiguity should be treated as a governance weakness.

---

## 22. Authorisation Scope Matrix

A practical implementation should maintain a scope matrix covering at least:

| Dimension | Authorised | Boundary | Not Authorised |
|---|---|---|---|
| Mission | Defined mission | Conditional mission | Unapproved mission |
| Environment | Demonstrated environment | Boundary conditions | Outside envelope |
| Autonomy | Approved level | Restricted transition | Higher level |
| Human Authority | Defined authority | Escalation required | Unauthorised authority |
| Configuration | Approved baseline | Controlled change | Unapproved configuration |
| Data | Approved sources/conditions | Degraded quality | Unauthorised source |
| Dependencies | Assessed dependencies | Degraded dependency | Unapproved dependency |
| Time | Valid period | Expiry approaching | Expired authority |

This matrix should be linked to the Authorisation Record.

---

## 23. Scope and Continuous Assurance

Continuous monitoring should identify evidence that the capability may be moving outside its authorised scope.

Relevant indicators may include:

- Environmental boundary crossings.
- Autonomy changes.
- Configuration drift.
- Performance degradation.
- Human-control degradation.
- Security events.
- Dependency failures.
- Data drift.
- Repeated exceptions.

Detected scope violations should trigger the appropriate response.

---

## 24. Scope Violation

A scope violation occurs when operational employment occurs outside an applicable authorisation boundary.

Potential responses include:

- Immediate protective action.
- Restriction.
- Suspension.
- Incident investigation.
- Risk reassessment.
- Revalidation.
- Reauthorisation.
- Corrective action.

The response should be proportionate to consequence and severity.

---

## 25. Relationship with Renewal

Renewal confirms that the existing scope remains appropriate.

It should not silently expand:

- Mission.
- Environment.
- Autonomy.
- Human authority.
- Configuration.
- Operational area.

Material scope expansion should follow the applicable change and reauthorisation process.

---

## 26. Relationship with Change Management

Changes affecting the scope or basis of authority should be assessed under D-AIGAAF change management.

The change process should determine whether the change requires:

- No additional action.
- Updated documentation.
- Additional controls.
- Additional testing.
- Revalidation.
- Reauthorisation.
- Suspension pending assessment.

---

## 27. Authorisation Scope Record

The Authorisation Record should provide a clear statement of:

1. What is authorised.
2. For what mission.
3. In what environment.
4. At what autonomy level.
5. Under whose authority.
6. With what configuration.
7. Under what conditions.
8. For what period.
9. With what restrictions.
10. What is explicitly outside scope.

---

## 28. Golden Thread

Validity and scope preserve the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The scope of operational authority should remain traceable to the mission, risk, evidence and assurance basis supporting the decision.

---

## 29. Core Rule

**An AI capability is operationally authorised only within the specific mission, environment, autonomy, human authority, configuration, conditions and validity period for which sufficient assurance and formal authority have been established.**

---

## 30. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `03_Authorisation_Decision_Rights.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `05_Authorisation_Record.md`
- `06_Authorisation_Review_and_Renewal.md`
- `07_Authorisation_Suspension_and_Revocation.md`
- `03 Risk & Autonomy`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
