# Use Case Exit Criteria

## 1. Purpose

Use Case Exit Criteria define the conditions under which a D-AIGAAF use case should stop progressing, be restricted, suspended, retired or otherwise exit its current lifecycle state.

The purpose is to prevent an AI use case from continuing through development, assurance or operational employment when its mission need, risk position, evidence, authority or operational conditions no longer justify progression.

---

## 2. Core Principle

A use case should not continue merely because resources have already been invested in it.

> **Continued progression or employment requires continued legitimacy, evidence, control and appropriate authority.**

Exit criteria provide controlled stopping points throughout the lifecycle.

---

## 3. Exit vs Failure

An exit decision does not necessarily mean that the AI capability has technically failed.

A use case may exit because:

- the mission need no longer exists;
- the risk is unacceptable;
- required evidence cannot be obtained;
- human control is inadequate;
- the operational environment has changed;
- the capability is no longer required;
- a safer alternative exists;
- policy or legal conditions have changed;
- dependencies are no longer reliable;
- the capability has reached retirement.

---

## 4. Lifecycle Application

Exit criteria may apply at any stage:

**Proposed → Defined → Approved → Development → TEVV → Assurance → Authorisation → Employment → Review → Retirement**

The exit decision should be appropriate to the current lifecycle state.

---

## 5. Mission Need Exit

A use case should be considered for exit when:

- the original mission need no longer exists;
- the mission objective has changed materially;
- the AI solution no longer addresses the mission problem;
- another solution provides a materially better option;
- the mission has been discontinued.

The use case should not continue solely because the AI capability remains available.

---

## 6. Use Case Definition Exit

Progression should stop when material ambiguity remains regarding:

- intended use;
- users;
- AI role;
- human role;
- decision context;
- operational environment;
- boundaries;
- autonomy;
- foreseeable misuse.

The use case may return to definition rather than proceed with unresolved ambiguity.

---

## 7. Risk Exit Criteria

A use case should be restricted, suspended or exited when:

- residual risk exceeds approved tolerance;
- consequence increases materially;
- autonomy increases without appropriate assessment;
- human control becomes inadequate;
- loss-of-control risk becomes unacceptable;
- new threats materially alter the risk position;
- required controls are ineffective.

Risk acceptance should remain with the appropriately authorised authority.

---

## 8. Evidence Exit Criteria

Progression should stop or be restricted when:

- required evidence cannot be produced;
- evidence is not representative of the intended environment;
- evidence is materially outdated;
- critical test failures remain unresolved;
- assurance claims cannot be supported;
- evidence gaps are inconsistent with the proposed consequence or autonomy.

No authority should depend on evidence that does not adequately support the relevant claim.

---

## 9. TEVV Exit Criteria

A use case should not progress where TEVV demonstrates material unresolved problems involving:

- technical performance;
- reliability;
- robustness;
- adversarial resilience;
- human-AI interaction;
- security;
- autonomy;
- human control;
- mission effectiveness.

A failed test does not automatically require retirement, but it must be assessed for its effect on risk and authority.

---

## 10. Operational Context Exit

The use case should be restricted or exited when operating conditions move materially beyond the validated context.

Examples include:

- different geography;
- different terrain;
- extreme weather;
- degraded sensors;
- communications loss;
- degraded data;
- changed human workload;
- changed adversarial conditions;
- changed infrastructure.

Operation outside validated conditions should require an appropriate governance decision.

---

## 11. Boundary Exit Criteria

A use case should be restricted or suspended when:

- an operational boundary is exceeded;
- prohibited behaviour is observed;
- autonomy exceeds the authorised level;
- the capability performs an unauthorised action;
- human authority is bypassed;
- critical safeguards are unavailable.

Capability beyond the authorised boundary is not automatically authorised.

---

## 12. Human Control Exit Criteria

Operation should be reconsidered when:

- the authorised human cannot meaningfully intervene;
- intervention time becomes insufficient;
- the human cannot understand relevant system state;
- override mechanisms fail;
- workload prevents effective supervision;
- communications required for human control are unavailable.

Human presence should not be treated as sufficient where meaningful control has been lost.

---

## 13. Security Exit Criteria

Restriction or suspension should be considered when:

- system integrity is uncertain;
- model integrity is compromised;
- critical data integrity is uncertain;
- unauthorised access is detected;
- a critical dependency is compromised;
- adversarial manipulation is suspected;
- an update introduces unexplained behaviour.

Security incidents should be assessed for their effect on operational authority.

---

## 14. Loss-of-Control Exit Criteria

Immediate protective action may be required when the AI capability:

- behaves outside its authorised function;
- cannot be reliably interrupted;
- attempts unauthorised actions;
- affects systems outside its intended scope;
- continues operating after authority has been withdrawn;
- exhibits unexplained critical behaviour.

Pre-authorised emergency procedures may permit immediate protective action where delay could create unacceptable harm.

---

## 15. Dependency Exit Criteria

A use case should be restricted or suspended when a critical dependency:

- becomes unavailable;
- becomes unreliable;
- is compromised;
- is materially changed;
- can no longer support required human control;
- creates an unacceptable single point of failure.

Technical recovery does not automatically restore operational authority.

---

## 16. Threat Exit Criteria

The use case should be reassessed when:

- a new material threat is identified;
- threat severity increases;
- adversarial conditions exceed tested assumptions;
- the system is exposed to an unassessed attack pathway;
- threat intelligence changes relevant operational assumptions.

A significant threat change may require new TEVV, risk assessment or reauthorisation.

---

## 17. Legal and Policy Exit Criteria

Progression or employment should stop when:

- applicable law changes;
- policy changes materially;
- required authority expires;
- a legal or policy conflict is identified;
- an exception or waiver expires;
- the use case can no longer demonstrate required compliance.

D-AIGAAF cannot create authority that does not exist under applicable law or policy.

---

## 18. Change Exit Criteria

A use case should be reassessed following material changes to:

- model;
- software;
- hardware;
- data;
- configuration;
- dependencies;
- operating environment;
- mission;
- autonomy;
- human authority.

Behaviour, consequence and operational effect should determine change significance.

---

## 19. Incident Exit Criteria

An incident should trigger consideration of restriction, suspension or exit when it reveals:

- material safety failure;
- loss of control;
- unauthorised action;
- serious security compromise;
- significant human-AI failure;
- systemic reliability problem;
- previously unknown failure mode;
- evidence that assurance assumptions were incorrect.

The incident should feed back into risk, assurance and authorisation.

---

## 20. Workforce Exit Criteria

Employment or progression should be reconsidered when required competency is unavailable.

Examples include:

- insufficient trained operators;
- unavailable qualified decision-makers;
- loss of required AI expertise;
- inadequate maintenance capability;
- inability to support required assurance activities.

A technically capable system may still be operationally unsuitable without the required human capability.

---

## 21. Supply-Chain Exit Criteria

A use case should be reassessed when:

- critical supplier ownership changes;
- provenance becomes uncertain;
- a critical dependency becomes unavailable;
- supplier security is materially compromised;
- an uncontrolled update occurs;
- a critical component is replaced without appropriate assessment.

Supply-chain change may alter both assurance and operational authority.

---

## 22. Authorisation Exit Criteria

Operational authority should be restricted, suspended or revoked when:

- authorisation conditions are violated;
- validity expires;
- required evidence becomes invalid;
- risk exceeds accepted tolerance;
- operational boundaries are exceeded;
- human authority is unavailable;
- critical controls fail;
- significant change has not been assessed.

Authorisation should be treated as conditional, not permanent.

---

## 23. Voluntary Exit

A use case may be voluntarily exited when:

- mission value is insufficient;
- cost is disproportionate;
- safer alternatives exist;
- operational utility is inadequate;
- maintenance burden is excessive;
- strategic priorities change.

Voluntary exit should still be formally recorded.

---

## 24. Retirement Exit

A use case should enter retirement when:

- the mission need has ended;
- the capability is replaced;
- the system reaches end of service;
- required support is unavailable;
- risk is no longer acceptable;
- the capability is no longer economically or operationally justified.

Retirement should include removal of operational authority.

---

## 25. Exit Decision States

A controlled set of states may include:

- **Continue** — proceed under existing conditions.
- **Continue With Conditions** — proceed subject to defined controls.
- **Restrict** — reduce scope, autonomy or operating conditions.
- **Return for Reassessment** — return to an earlier lifecycle stage.
- **Suspend** — temporarily remove operational use.
- **Revoke** — terminate operational authority.
- **Retire** — permanently remove the use case from service.

These states should not be interpreted as universal organisational terminology.

---

## 26. Exit Decision Authority

Exit authority should be explicitly assigned.

Depending on the situation, authority may rest with:

- operational commander;
- authorising authority;
- system authority;
- security authority;
- incident authority;
- designated emergency authority.

Emergency protective action may be pre-authorised within defined limits.

---

## 27. Exit Conditions and Escalation

Exit criteria should specify when escalation is required.

Examples:

**Minor issue → local correction**

**Material issue → operational restriction**

**Major issue → suspension and reassessment**

**Critical issue → immediate protective action and authority review**

Escalation should be based on consequence and operational effect.

---

## 28. Exit Record

A Use Case Exit Record should contain:

- use case identifier;
- lifecycle state;
- exit trigger;
- observed condition;
- affected mission;
- affected boundaries;
- risk assessment;
- evidence;
- human authority;
- decision;
- restrictions;
- immediate actions;
- required reassessment;
- revalidation requirements;
- reauthorisation requirements;
- responsible authority;
- date and time;
- subsequent review.

---

## 29. Re-entry After Exit

Exit does not always mean permanent termination.

A suspended or restricted use case may re-enter the lifecycle when:

- the triggering issue is resolved;
- required evidence is restored;
- risk is reassessed;
- controls are verified;
- required TEVV is completed;
- authority is re-established.

Re-entry should not automatically restore the previous authority level.

---

## 30. Exit and Golden Thread

Every exit decision should remain traceable through:

**Mission → Use Case → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Exit/Reauthorisation**

The exit record should preserve the reasoning behind the decision.

---

## 31. Minimum Use Case Exit Requirements

For consequential AI use cases:

1. Exit criteria should be defined before operational employment.
2. Material mission changes should have defined exit or reassessment triggers.
3. Risk exceedance should have a defined response.
4. Evidence failure should have a defined response.
5. Operational boundary violations should have a defined response.
6. Loss of meaningful human control should have a defined response.
7. Security compromise should have a defined response.
8. Critical dependency failure should have a defined response.
9. Material threat changes should trigger reassessment.
10. Material system changes should trigger reassessment.
11. Incidents should be assessed for exit implications.
12. Authorisation expiry should be controlled.
13. Suspension and revocation authority should be explicit.
14. Emergency protective action should be pre-authorised where appropriate.
15. Exit decisions should be recorded and traceable.
16. Re-entry should require evidence and appropriate authority.
17. Retirement should remove operational authority.

---

## 32. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread`
- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Mission_Decision_Context.md`
- `02 Mission & Use Case/Operational_Boundaries.md`
- `02 Mission & Use Case/Operational_Assumptions.md`
- `02 Mission & Use Case/Mission_Threat_Context.md`
- `02 Mission & Use Case/Mission_Dependencies.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `06 AI Security`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `26 Retirement & Decommissioning`

Use Case Exit Criteria provides the controlled stopping and reassessment mechanism within the mission and use-case layer.

---

## 33. Summary

D-AIGAAF must define not only how an AI use case is allowed to progress, but also when it must stop.

Exit criteria provide controlled mechanisms for restriction, reassessment, suspension, revocation and retirement when mission need, risk, evidence, human control, security, dependencies, threats or authority materially change.

The central principle is:

> **An AI use case should continue only while its mission need, evidence, risk, operational boundaries, human authority and control conditions remain sufficient to justify continued progression or employment.**
