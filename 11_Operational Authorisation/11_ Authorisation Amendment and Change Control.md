# 11 Authorisation Amendment and Change Control

## 1. Purpose

This document defines how changes to an existing Defence AI operational authorisation are identified, assessed, approved, recorded and controlled.

The objective is to prevent material changes to a capability or its operating context from being introduced under an authorisation that was granted on a different assurance basis.

---

## 2. Core Principle

**An operational authorisation applies to an identified capability, configuration, mission, environment, autonomy level, human authority and set of conditions. Material change to any of these may require amendment, revalidation or reauthorisation.**

---

## 3. What Constitutes a Change

Changes may affect:

- AI model.
- Model state or weights.
- Software.
- Hardware.
- Configuration.
- Data.
- Interfaces.
- Security controls.
- Critical dependencies.
- Mission.
- Use case.
- Operational environment.
- Autonomy.
- Human authority.
- Operating procedures.
- Authorisation conditions.

Changes may be technical, operational, organisational, environmental or regulatory.

---

## 4. Change Classification

A practical D-AIGAAF classification is:

### C1 — Administrative / Non-Material

No meaningful effect on capability, risk, assurance or operational authority.

Examples may include:

- Formatting.
- Administrative contact changes.
- Non-substantive record corrections.

### C2 — Minor Controlled Change

Limited effect with no material change to the assurance basis.

May require:

- Documentation update.
- Targeted testing.
- Configuration record update.

### C3 — Significant Change

Potentially meaningful effect on performance, risk, environment, human control, security or assurance.

May require:

- Additional TEVV.
- Risk reassessment.
- Revalidation.

### C4 — Material Change

Changes the basis on which operational authority was granted.

Normally requires:

- Formal revalidation.
- Updated assurance evidence.
- Reauthorisation.

These categories are working D-AIGAAF constructs and should be aligned with organisational terminology.

---

## 5. Change Identification

Changes should be identified through:

- Configuration management.
- Software release processes.
- Model management.
- Data governance.
- Security monitoring.
- Supply-chain monitoring.
- Operational monitoring.
- Incident management.
- Environmental monitoring.
- User feedback.
- Governance review.

No material change should rely solely on informal notification.

---

## 6. Change Request

A change request should identify:

- Change identifier.
- Capability.
- Current authorisation.
- Current configuration.
- Proposed change.
- Reason.
- Expected effect.
- Mission.
- Environment.
- Autonomy.
- Human authority.
- Risk.
- Assurance implications.
- Security implications.
- Dependency implications.
- Testing required.
- Proposed implementation.
- Rollback approach.
- Approval authority.

---

## 7. Initial Change Assessment

Every potentially material change should receive an initial assessment to determine:

1. What is changing?
2. Why is it changing?
3. Which assumptions are affected?
4. Which risks are affected?
5. Which controls are affected?
6. Which evidence is affected?
7. Does existing TEVV remain valid?
8. Does human control change?
9. Does autonomy change?
10. Does operational scope change?
11. Does the authorisation remain valid?

---

## 8. Impact Domains

Change assessment should consider at least:

- Mission impact.
- Risk impact.
- Autonomy impact.
- Human-control impact.
- Environmental impact.
- Data impact.
- Security impact.
- Supply-chain impact.
- Performance impact.
- Fail-safe impact.
- Dependency impact.
- Legal/policy impact.
- Assurance impact.

---

## 9. Hidden and Opaque Model Changes

Particular attention should be given to changes affecting internal model behaviour that may not be directly observable.

Examples include:

- Model weights.
- Fine-tuning.
- Retraining.
- Reinforcement learning.
- Model architecture.
- Safety mechanisms.
- Decision logic.
- Prompting or orchestration layers where they materially affect behaviour.

A change should not be classified as non-material merely because the external interface appears unchanged.

---

## 10. Change to Autonomy

Any increase in authorised autonomy should receive heightened scrutiny.

Assessment should consider:

- New decision authority.
- Human supervision.
- Intervention capability.
- Consequence.
- Failure modes.
- Boundary behaviour.
- Environmental assumptions.
- Security.
- Fail-safe behaviour.
- TEVV evidence.

A higher autonomy level should not be introduced through routine configuration management alone.

---

## 11. Change to Human Authority

Changes affecting:

- Operators.
- Supervisors.
- Decision rights.
- Override.
- Intervention.
- Escalation.
- Accountability.

should be assessed for their effect on meaningful human control.

Where the responsible authority changes, the Authorisation Record should be updated.

---

## 12. Change to Mission

A mission change should be assessed for:

- New objectives.
- New consequences.
- New users.
- New operating conditions.
- New decision contexts.
- New prohibited or restricted activities.

A capability authorised for one mission should not automatically be treated as authorised for another.

---

## 13. Change to Operational Environment

Environmental changes may include:

- Terrain.
- Weather.
- Illumination.
- Sensor conditions.
- Communications.
- Electromagnetic conditions.
- Information conditions.
- Computing availability.
- Adversarial conditions.

Material environmental changes should trigger assessment against the authorised operating envelope.

---

## 14. Change to Data

Changes to data may affect:

- Provenance.
- Quality.
- Representativeness.
- Timeliness.
- Distribution.
- Integrity.
- Bias.
- Drift.
- Adversarial exposure.

Material data changes should be assessed for their effect on model performance and assurance evidence.

---

## 15. Security-Driven Change

Security findings may require changes to:

- Access controls.
- Interfaces.
- Software.
- Model protection.
- Data handling.
- Network architecture.
- Monitoring.
- Isolation mechanisms.

Security-driven changes should be assessed for both security and operational-authorisation implications.

---

## 16. Dependency and Supply-Chain Change

Changes to critical suppliers or dependencies should be assessed for:

- Trust.
- Provenance.
- Availability.
- Integrity.
- Support.
- Resilience.
- Strategic dependency.
- Continuity.

A supplier update should not automatically be considered operationally equivalent to the previously authorised component.

---

## 17. Change Impact on Assurance Evidence

The change process should identify whether existing evidence remains:

- Valid.
- Relevant.
- Representative.
- Configuration-consistent.
- Sufficient.

Evidence affected by a material change should not continue to be presented as if it demonstrated the unchanged system.

---

## 18. Testing and TEVV

Testing requirements should be determined by the change impact.

Possible responses include:

- No additional testing.
- Targeted testing.
- Regression testing.
- Security testing.
- Adversarial testing.
- Human-AI evaluation.
- Autonomy evaluation.
- Environmental testing.
- Mission-effectiveness evaluation.
- Full or expanded TEVV.

Testing should address the changed risk, not merely confirm that the system starts and functions.

---

## 19. Rollback

Material changes should have a defined rollback or recovery approach where practicable.

Rollback planning should consider:

- Previous authorised configuration.
- Dependencies.
- Data compatibility.
- Human procedures.
- Security controls.
- Operational conditions.
- Recovery time.
- Authority required to restore the previous configuration.

Rollback should not itself be assumed to restore authorisation if the surrounding operational context has changed.

---

## 20. Approval Categories

Following change assessment, the change may be:

- Approved as non-material.
- Approved with additional controls.
- Approved after targeted testing.
- Sent for revalidation.
- Sent for reauthorisation.
- Deferred.
- Rejected.
- Implemented only under restricted authority.
- Implemented only under an approved exception.

The approval decision should be recorded.

---

## 21. Amendment of Authorisation

Where a change does not invalidate the authorisation but modifies its conditions or scope, the authorisation may be formally amended.

The amendment should identify:

- Original authorisation.
- Change.
- Impact assessment.
- Evidence.
- New conditions.
- New restrictions.
- Effective date.
- Approval authority.
- Revised review date where applicable.

The amended record should preserve the history of the original decision.

---

## 22. Revalidation Trigger

Revalidation should be considered where the change may affect:

- Performance.
- Risk.
- Human control.
- Autonomy.
- Environment.
- Security.
- Data.
- Critical dependencies.
- Fail-safe behaviour.
- Assurance assumptions.

Revalidation should establish whether existing assurance remains valid.

---

## 23. Reauthorisation Trigger

Reauthorisation should normally be required where a material change alters the basis of operational authority.

Examples include:

- Material increase in autonomy.
- New mission.
- Materially different environment.
- Material change in consequence.
- Fundamental model change.
- Major system architecture change.
- Significant human-control change.
- Material assurance failure.

The decision should be made through the formal authorisation process.

---

## 24. Emergency Changes

Emergency changes may be implemented where delay could create unacceptable harm and appropriate emergency authority exists.

Emergency changes should:

- Have a defined purpose.
- Be authorised.
- Be controlled.
- Be recorded.
- Be tested where practicable.
- Be reviewed after implementation.
- Trigger revalidation or reauthorisation where required.

Emergency status should not permanently exempt the change from normal governance.

---

## 25. Change Freeze

A temporary change freeze may be imposed where:

- An incident is under investigation.
- Assurance evidence is materially uncertain.
- A security compromise is suspected.
- Configuration integrity is uncertain.
- A systemic issue is identified.

Change freeze decisions should identify their scope and termination conditions.

---

## 26. Configuration Traceability

Every operational configuration should be traceable to:

**Change → Assessment → Testing → Evidence → Assurance → Authorisation**

This ensures that the organisation can determine why a particular configuration was considered operationally acceptable.

---

## 27. Change Register

A Change Register should capture:

- Change identifier.
- Capability.
- Authorisation identifier.
- Current baseline.
- Proposed baseline.
- Change classification.
- Impact assessment.
- Testing.
- Evidence.
- Approval.
- Implementation date.
- Rollback status.
- Post-change monitoring.
- Revalidation/reauthorisation decision.
- Closure.

---

## 28. Post-Change Monitoring

Following implementation, monitoring should assess:

- Expected performance.
- Unexpected behaviour.
- Risk indicators.
- Security indicators.
- Human-control indicators.
- Autonomy behaviour.
- Environmental interaction.
- Dependency performance.
- User feedback.

Material unexpected behaviour should trigger the applicable incident or authorisation process.

---

## 29. Change Closure

A change should be formally closed when:

- Implementation is complete.
- Evidence is available.
- Required testing is complete.
- Configuration is recorded.
- Authorisation status is updated.
- Conditions are updated.
- Monitoring requirements are established.
- Outstanding actions are assigned.

---

## 30. Governance Review

Organisations should periodically review change patterns to identify:

- Repeated exceptions.
- Recurring emergency changes.
- Uncontrolled configuration drift.
- Supplier-driven changes.
- Frequent model updates.
- Systemic assurance gaps.

Repeated changes of the same type may indicate that the underlying lifecycle or governance process requires improvement.

---

## 31. Golden Thread

Change control preserves the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

No material change should break the traceability between the capability and the authority under which it operates.

---

## 32. Core Rule

**A Defence AI capability shall not inherit operational authority merely because a changed system remains functionally similar to its predecessor. The organisation shall determine whether the change preserves, modifies or invalidates the assurance basis and authorisation on which operational use depends.**

---

## 33. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `01_Authorisation_Requirements.md`
- `02_Authorisation_Assessment.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `05_Authorisation_Record.md`
- `06_Authorisation_Review_and_Renewal.md`
- `08_Authorisation_Validity_and_Scope.md`
- `09_Authorisation_Emergency_and_Contingency.md`
- `10_Authorisation_Exceptions_and_Derogations.md`
- `04 AI Lifecycle`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `09 TEVV`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
