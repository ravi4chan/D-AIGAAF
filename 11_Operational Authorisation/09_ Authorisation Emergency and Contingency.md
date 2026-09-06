# 09 Authorisation Emergency and Contingency

## 1. Purpose

This document defines governance for emergency and contingency situations in which a Defence AI capability encounters conditions that were not fully anticipated within its normal operational authorisation.

The purpose is to enable timely protective action while preserving human authority, operational accountability, safety, security and traceability.

---

## 2. Core Principle

**Emergency conditions may justify accelerated protective action, but they do not create unrestricted AI authority.**

Emergency procedures should preserve the distinction between:

- AI-generated information or recommendations.
- Human decisions.
- Pre-authorised automated protective actions.
- Formal operational authorisation.

---

## 3. Emergency Conditions

Emergency conditions may arise from:

- Unexpected AI behaviour.
- Loss of human control.
- Loss of communications.
- Sensor failure.
- Navigation uncertainty.
- Cybersecurity events.
- Data integrity failure.
- Environmental conditions outside the authorised envelope.
- Critical dependency failure.
- Unanticipated mission conditions.
- Fail-safe activation.
- Significant system degradation.
- Loss of required human supervision.

The organisation should define foreseeable emergency categories in advance.

---

## 4. Emergency Authority

Emergency authority should be explicitly defined before operational employment.

It should specify:

- Who may act.
- What actions may be taken.
- Under what conditions.
- For how long.
- What limitations apply.
- When escalation is required.
- What must be recorded.

Emergency authority should be as narrow as practicable.

---

## 5. Protective Action

Where delay could create unacceptable harm, authorised personnel may take immediate protective action consistent with established procedures.

Possible actions include:

- Stop or suspend a function.
- Reduce autonomy.
- Transition to a safer operating mode.
- Transfer control to a human.
- Restrict mission scope.
- Isolate an affected component.
- Invoke an approved fail-safe.
- Withdraw the capability from the operational context.

The specific protective response should depend on the capability and risk.

---

## 6. Pre-Authorised Emergency Actions

Some emergency responses may be pre-authorised where:

- The condition is reasonably foreseeable.
- The response is clearly defined.
- The response has been assessed.
- The action has a bounded purpose.
- Human authority and accountability remain clear.

Pre-authorisation should not be interpreted as permission for the AI to determine its own emergency authority.

---

## 7. AI Behaviour During Emergencies

Unless a higher autonomy level has been explicitly authorised, the AI should remain within its approved role during an emergency.

AI should not independently:

- Expand its mission.
- Increase its autonomy.
- Create new objectives.
- Override human authority.
- Extend its operational scope.
- Change critical configuration.
- Establish new permissions.

Emergency conditions should trigger defined governance and technical responses rather than self-expansion of authority.

---

## 8. Human Decision Authority

Where consequential action remains subject to human authority:

- The responsible human decision maker should remain identifiable.
- The decision should be made using available information.
- Material uncertainty should be communicated.
- The AI recommendation should remain distinguishable from the human decision.
- The decision and rationale should be recorded where practicable.

Where normal communications are unavailable, previously defined local authority arrangements should apply.

---

## 9. Loss of Communications

Where communication with higher authority is lost, the capability should follow its approved degraded/disconnected operating procedure.

This may include:

- Continue within predefined limits.
- Reduce autonomy.
- Transition to a safe state.
- Await restoration.
- Execute a pre-authorised contingency action.

Loss of communications should not automatically create expanded AI authority.

---

## 10. Loss of Human Supervision

Where required human supervision becomes unavailable:

- The system should follow its approved contingency behaviour.
- Autonomy should not increase unless explicitly authorised.
- The capability should transition to a defined safe or restricted state where required.
- Restoration of human supervision should follow defined procedures.

The acceptable response depends on the authorised autonomy level and consequence.

---

## 11. Environmental Emergency

Where environmental conditions move outside the authorised envelope:

- Boundary detection should occur where practicable.
- The capability should apply the approved response.
- Autonomy may need to be reduced.
- Human authority should be notified where communications permit.
- Continued operation should require appropriate authority.

Environmental emergency procedures should be tested during TEVV where reasonably foreseeable.

---

## 12. Security Emergency

A suspected compromise may require immediate protective action.

Possible actions include:

- Restricting affected functions.
- Reducing autonomy.
- Isolating affected components.
- Suspending operational employment.
- Preserving evidence.
- Initiating incident response.
- Escalating to the appropriate security authority.

Security response should not be dependent on completing the normal authorisation cycle before immediate containment.

---

## 13. AI Fail-Safe

Fail-safe mechanisms should provide a controlled means of limiting or stopping unsafe or unauthorised behaviour.

A fail-safe may involve:

- Function suspension.
- Autonomy reduction.
- Human takeover.
- Safe-state transition.
- Interface isolation.
- System shutdown.

Fail-safe activation criteria should be defined and tested.

A fail-safe should be treated as a protective control, not as a substitute for sound system design, assurance or operational governance.

---

## 14. AI Kill-Switch Concept

For capabilities where continued operation could create unacceptable harm, an appropriately designed emergency stop or equivalent protective mechanism should be available.

The mechanism should be:

- Clearly defined.
- Authorised.
- Accessible to appropriate personnel.
- Tested.
- Protected against unauthorised activation.
- Protected against failure where practicable.
- Supported by recovery procedures.

The specific technical implementation should depend on the capability.

---

## 15. Escalation During an Emergency

Where time permits, the escalation path should support rapid coordination between:

**Operator → System Manager → Operational AI Advisor → Operational/Command Authority → Authorising Authority**

The exact structure may vary by organisation.

Where delay could materially increase harm, pre-authorised protective action should take precedence over normal escalation sequencing.

---

## 16. Operational AI Advisor

Where an Operational AI Advisor (OAIA) role exists, the OAIA may help commanders and operational authorities interpret:

- AI behaviour.
- Model limitations.
- Uncertainty.
- Confidence or reliability indicators.
- Likely technical causes.
- Available technical responses.
- Implications of changing autonomy or configuration.

The OAIA should advise rather than silently assume operational command authority unless separately designated under applicable organisational arrangements.

---

## 17. Emergency Use of AI Recommendations

During emergencies, AI recommendations may become particularly influential.

Human decision makers should remain alert to:

- Automation bias.
- Time pressure.
- Incomplete information.
- False confidence.
- Model uncertainty.
- Conflicting information.
- Changing environmental conditions.

The system should communicate material uncertainty where practicable.

---

## 18. Contingency Modes

A capability may define approved contingency modes such as:

### C1 — Continue

Continue within existing authorised boundaries.

### C2 — Restricted Operation

Continue with reduced scope or increased controls.

### C3 — Reduced Autonomy

Move to a lower authorised autonomy level.

### C4 — Human Control

Transfer relevant decisions or functions to human control.

### C5 — Safe State

Move to a predefined safe or controlled state.

### C6 — Suspend

Cease operational employment pending assessment.

These are D-AIGAAF working categories and may be adapted to organisational terminology.

---

## 19. Contingency Decision Matrix

A practical implementation should establish a contingency matrix:

| Condition | Initial Response | Authority | Follow-up |
|---|---|---|---|
| Minor degradation | Continue/monitor | Defined operational authority | Record |
| Significant degradation | Restrict/reduce autonomy | Operational authority | Assess |
| Loss of required human control | Safe state/suspend | Defined emergency authority | Investigate |
| Security compromise | Isolate/restrict/suspend | Security + operational authority | Incident response |
| Outside environmental envelope | Restrict/safe state | Operational authority | Reassess |
| Critical dependency failure | Contingency mode/suspend | Defined authority | Dependency assessment |
| Unexplained consequential behaviour | Protective action/suspend | Emergency authority | Investigation |

The matrix should be tailored to the capability.

---

## 20. Emergency Configuration Changes

Emergency technical changes should be controlled.

Where an emergency change is unavoidable:

- The change should have a defined purpose.
- The responsible authority should be identifiable.
- The change should be recorded.
- The resulting configuration should be identified.
- Appropriate testing should be conducted where practicable.
- Post-event review should determine whether revalidation or reauthorisation is required.

Emergency conditions should not become a route for uncontrolled configuration changes.

---

## 21. Evidence and Records

Emergency actions should be recorded to the extent practicable.

Relevant records may include:

- Time and circumstances.
- Capability and configuration.
- Mission.
- Environment.
- AI outputs.
- Human decisions.
- Protective actions.
- Autonomy state.
- Alerts.
- Communications status.
- Security events.
- Fail-safe activation.
- Authority exercised.
- Outcome.

If complete recording is impossible during the emergency, records should be reconstructed as soon as practicable.

---

## 22. Post-Emergency Review

Following an emergency, the organisation should assess:

- What happened.
- Whether the contingency procedure worked.
- Whether the AI behaved as expected.
- Whether human authority remained effective.
- Whether fail-safe mechanisms worked.
- Whether the operating environment contributed.
- Whether security contributed.
- Whether assumptions remain valid.
- Whether the authorisation remains appropriate.

The review should determine whether:

- No action is required.
- Additional controls are required.
- Restrictions should remain.
- Additional TEVV is required.
- Revalidation is required.
- Reauthorisation is required.
- Suspension should continue.
- Revocation should be considered.

---

## 23. Emergency Authority Does Not Equal Mission Expansion

Emergency conditions should not be used to justify:

- New missions.
- Unapproved autonomy.
- Unauthorised targets or actions.
- New users.
- Unassessed environments.
- Unapproved system changes.

Where circumstances require a materially different use, the applicable authority and assurance process should be followed as soon as practicable.

---

## 24. Training and Exercises

Emergency and contingency procedures should be incorporated into appropriate:

- Operator training.
- Command training.
- AI literacy training.
- Technical training.
- Security exercises.
- TEVV.
- Operational exercises.

Exercises should test both technical behaviour and human decision-making under degraded conditions.

---

## 25. Governance of Emergency Procedures

Emergency procedures should be periodically reviewed against:

- Incidents.
- Near misses.
- Lessons learned.
- System changes.
- Threat changes.
- Environmental changes.
- Operational experience.
- New assurance evidence.

Procedures should remain consistent with the current authorisation basis.

---

## 26. Golden Thread

Emergency governance preserves the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Emergency action is therefore treated as part of controlled operational governance rather than as an exception outside the framework.

---

## 27. Core Rule

**When an emergency occurs, the objective is not to give AI more authority; it is to preserve human authority, limit unacceptable behaviour, protect people and assets, and restore a controlled operational state as quickly as practicable.**

---

## 28. Related D-AIGAAF Modules

This document should be read with:

- `00_Operational_Authorisation_Governance_Model.md`
- `03_Authorisation_Decision_Rights.md`
- `04_Authorisation_Conditions_and_Restrictions.md`
- `05_Authorisation_Record.md`
- `07_Authorisation_Suspension_and_Revocation.md`
- `08_Authorisation_Validity_and_Scope.md`
- `03 Risk & Autonomy`
- `06 AI Security`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
