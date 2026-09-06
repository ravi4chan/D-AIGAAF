# 33 Operational Authorisation Preconditions and Gating

## 1. Purpose

Operational authorisation should not be treated as a single administrative approval.

A Defence AI capability should pass defined governance gates before it can move from one stage of the authorisation lifecycle to another.

This document establishes preconditions and gating criteria for operational authority.

The objective is to ensure that:

- mandatory prerequisites are identifiable;
- evidence is available before consequential decisions;
- unresolved risks remain visible;
- authority is not granted prematurely;
- readiness is distinguished from assurance;
- deployment is distinguished from authorisation;
- employment is distinguished from deployment;
- failed gates produce defined outcomes; and
- exceptions do not silently bypass mandatory safeguards.

---

## 2. Core Principle

**A Defence AI capability shall not progress to a higher operational state or receive broader operational authority until the mandatory preconditions for that state have been demonstrated or explicitly addressed through an appropriately authorised governance decision.**

---

## 3. Gating Model

A working D-AIGAAF gating sequence is:

**Mission Defined → Requirements Defined → Risk Assessed → Controls Implemented → TEVV Completed → Environment Assessed → Assurance Determined → Authorisation Granted → Readiness Confirmed → Deployment Accepted → Employment Permitted → Continuous Monitoring**

Each gate should have defined entry criteria, evidence, decision authority and exit conditions.

---

## 4. Gate Definitions

Each gate should specify:

- objective;
- scope;
- mandatory requirements;
- evidence;
- responsible owner;
- decision authority;
- unresolved issues;
- conditions;
- permitted exceptions;
- decision outcome;
- record; and
- next gate.

---

## 5. Gate 1 — Mission and Use Case

Before assurance begins, the organisation should establish:

- mission need;
- intended purpose;
- use case;
- users;
- decisions supported;
- actions potentially affected;
- operational context;
- consequence;
- limitations;
- prohibited uses; and
- success criteria.

An undefined mission should not proceed to operational authorisation.

---

## 6. Gate 2 — Requirements

The organisation should establish requirements covering, as applicable:

- functionality;
- performance;
- reliability;
- robustness;
- security;
- human control;
- autonomy;
- environmental conditions;
- data;
- interoperability;
- fail-safe;
- monitoring;
- auditability; and
- lifecycle management.

Requirements should be traceable to mission need and risk.

---

## 7. Gate 3 — Risk and Autonomy

Before testing and authorisation, the organisation should determine:

- consequence;
- mission criticality;
- risk;
- proposed autonomy;
- human-control requirements;
- environmental complexity;
- dependencies;
- security concerns; and
- applicable risk treatment.

Higher consequence or autonomy should require proportionately stronger controls and assurance.

---

## 8. Gate 4 — Controls

Required controls should be implemented and verified.

Controls may address:

- system behaviour;
- access;
- configuration;
- data;
- security;
- human oversight;
- intervention;
- autonomy;
- environmental boundaries;
- fail-safe;
- monitoring;
- dependencies; and
- operational procedures.

Unimplemented mandatory controls should normally prevent progression.

---

## 9. Gate 5 — TEVV

TEVV should provide evidence relevant to the intended operational use.

Assessment should cover applicable dimensions including:

- technical performance;
- reliability and robustness;
- adversarial resilience;
- operational environment;
- human-AI interaction;
- security and integrity;
- autonomy and control; and
- mission effectiveness.

Testing should be appropriate to consequence and operational context.

---

## 10. Gate 6 — Operational Environment

The organisation should determine whether the capability has sufficient evidence for its intended environment.

Assessment should include relevant:

- physical conditions;
- sensors;
- communications;
- navigation;
- information;
- computing;
- human factors;
- electromagnetic conditions;
- adversarial conditions; and
- dependencies.

Untested conditions should remain visible as limitations.

---

## 11. Gate 7 — Assurance

Assurance should establish whether available evidence is sufficient to support the proposed operational decision.

The assurance determination should identify:

- demonstrated capabilities;
- limitations;
- unresolved risks;
- evidence gaps;
- contradictions;
- assumptions;
- uncertainty;
- configuration baseline; and
- recommended conditions.

Assurance should not simply restate developer claims.

---

## 12. Gate 8 — Operational Authorisation

Before operational authority is granted, the organisation should confirm:

- mission;
- use case;
- environment;
- autonomy;
- human authority;
- configuration;
- conditions;
- restrictions;
- residual risk;
- evidence;
- monitoring;
- fail-safe;
- dependencies;
- validity; and
- suspension/revocation triggers.

The authorisation decision should be attributable to the appropriate human authority.

---

## 13. Gate 9 — Operational Readiness

Authorisation does not guarantee current readiness.

Before employment, readiness should confirm:

- approved configuration;
- current evidence;
- suitable environment;
- available human authority;
- competent personnel;
- appropriate autonomy;
- security;
- data integrity;
- dependencies;
- monitoring;
- fail-safe; and
- mission conditions.

A capability may be authorised but not currently ready.

---

## 14. Gate 10 — Deployment

Deployment should confirm that the authorised capability is entering the intended operational setting.

Verification should include:

- configuration;
- environment;
- human authority;
- autonomy;
- security;
- data;
- dependencies;
- restrictions;
- monitoring; and
- handover.

Deployment should not expand authorisation.

---

## 15. Gate 11 — Operational Employment

Before active employment, the organisation should confirm:

- authorisation remains valid;
- readiness remains current;
- deployment is accepted;
- conditions are satisfied;
- human authority is available;
- autonomy is within authorised limits;
- environment remains within scope; and
- required monitoring is functioning.

If a mandatory precondition fails, employment should not begin or should move to an appropriately restricted state.

---

## 16. Mandatory versus Conditional Gates

Gates may contain:

### Mandatory Preconditions

Failure prevents progression unless an authorised governance mechanism explicitly permits otherwise.

### Conditional Preconditions

Progression may occur subject to defined conditions, controls and monitoring.

### Advisory Preconditions

Useful evidence or recommendations that do not independently prevent progression.

The distinction should be explicit.

---

## 17. Gate Status

A working status model may use:

- **G1 — Passed**
- **G2 — Passed with Conditions**
- **G3 — Evidence Pending**
- **G4 — Additional Assurance Required**
- **G5 — Failed**
- **G6 — Not Applicable**
- **G7 — Suspended**

A gate should not be represented as passed when mandatory evidence remains unavailable.

---

## 18. Gate Failure

Gate failure should trigger proportionate action.

Possible outcomes include:

- remediation;
- additional testing;
- additional controls;
- restricted scope;
- reduced autonomy;
- human-control requirement;
- return to an earlier lifecycle stage;
- suspension; or
- rejection.

Gate failure should not be hidden through administrative reclassification.

---

## 19. Conditional Gate Passage

Conditional passage should identify:

- unmet or partially met requirement;
- reason for conditional treatment;
- compensating control;
- authority;
- duration;
- monitoring;
- exit criteria; and
- consequences of non-compliance.

Conditions should be enforceable and recorded.

---

## 20. Evidence Sufficiency

Gate decisions should distinguish between:

- evidence available;
- evidence relevant;
- evidence current;
- evidence independently assessed;
- evidence applicable to the intended environment; and
- evidence sufficient for the decision.

A large volume of evidence does not necessarily constitute sufficient evidence.

---

## 21. Evidence Gaps

Evidence gaps should be recorded explicitly.

Examples include:

- untested environment;
- incomplete adversarial evaluation;
- limited autonomy testing;
- insufficient human-AI evaluation;
- unresolved security findings;
- incomplete dependency assurance;
- uncertain model behaviour;
- insufficient mission effectiveness evidence; or
- outdated results.

Material gaps should influence the gate outcome.

---

## 22. Assumptions

Gate decisions should identify material assumptions.

Examples include assumptions about:

- communications;
- sensors;
- data;
- human availability;
- operating environment;
- system configuration;
- supplier support;
- security;
- model behaviour; or
- mission conditions.

If an assumption becomes invalid, the affected gate should be reconsidered.

---

## 23. Gate Dependencies

Some gates depend on successful completion of earlier gates.

For example:

**Risk Assessment → TEVV Scope → TEVV Evidence → Assurance → Authorisation**

or:

**Authorisation → Readiness → Deployment → Employment**

Later-stage approval should not erase unresolved failures at an earlier mandatory gate.

---

## 24. Gate Overrides and Exceptions

Gate bypass should be exceptional.

Any authorised exception should specify:

- gate affected;
- requirement affected;
- reason;
- risk;
- compensating controls;
- authority;
- duration;
- monitoring;
- review; and
- closure criteria.

Non-derogable requirements should remain non-derogable.

---

## 25. Emergency Gating

Emergency situations may require accelerated governance.

Pre-authorised emergency procedures may permit defined protective actions where delay could create unacceptable harm.

Emergency action should:

- remain bounded;
- preserve human authority;
- avoid unnecessary mission expansion;
- be recorded;
- trigger post-event review; and
- lead to revalidation or reauthorisation where required.

---

## 26. Gate Decision Rights

Each gate should identify:

- decision owner;
- technical contributor;
- assurance contributor;
- operational authority;
- risk owner;
- security authority;
- OAIA where applicable; and
- escalation authority.

AI systems may provide evidence or recommendations but should not hold governance gate authority.

---

## 27. Gate Independence

Where consequence warrants, gate assessment should include sufficient independence from the team responsible for development or delivery.

Independence should be proportionate to:

- consequence;
- autonomy;
- mission criticality;
- organisational risk; and
- potential conflict of interest.

---

## 28. Gate Reassessment

A previously passed gate may require reassessment after:

- material change;
- incident;
- new threat;
- environmental change;
- autonomy change;
- security event;
- data drift;
- dependency failure;
- new evidence;
- legal/policy change; or
- significant performance deterioration.

A gate should remain valid only while its underlying assumptions and evidence remain applicable.

---

## 29. Gate Status and Operational Dashboard

Current gate status should be visible through appropriate governance dashboards.

The dashboard should show:

- current gate;
- gate status;
- owner;
- evidence status;
- conditions;
- outstanding actions;
- expiry/review;
- restrictions; and
- escalation status.

The dashboard informs governance; it does not itself grant authority.

---

## 30. Gate Records

A Gate Decision Record should include:

- capability;
- gate;
- scope;
- date/time;
- decision;
- authority;
- evidence;
- conditions;
- unresolved issues;
- assumptions;
- risk;
- required actions;
- review date; and
- linked authorisation or assurance records.

---

## 31. Gate Traceability

Gate decisions should be traceable through:

**Mission Need → Requirement → Risk → Control → Test → Evidence → Gate Decision → Authority → Operational State**

This provides a direct connection between governance requirements and operational authority.

---

## 32. Gate and Continuous Assurance

Continuous assurance should be capable of causing a previously passed gate to be reconsidered when evidence or conditions materially change.

The control loop is:

**Monitor → Detect Change → Reassess Gate → Restrict/Continue → Revalidate/Reauthorise**

---

## 33. Governance Questions

Responsible authorities should be able to determine:

1. What gate is the capability currently at?
2. What are the mandatory preconditions?
3. Which have been demonstrated?
4. What evidence supports each decision?
5. What remains uncertain?
6. Which assumptions underpin the gate?
7. Who owns the gate decision?
8. Who has authority to approve it?
9. Are there conditions?
10. Are there unresolved risks?
11. Has independent assurance been obtained where appropriate?
12. Does the gate depend on another unresolved gate?
13. What happens if the gate fails?
14. Can an exception be granted?
15. What requirements cannot be waived?
16. What events invalidate the gate?
17. When must the gate be reviewed?
18. Is the current operational state consistent with the gate status?
19. Is the gate decision traceable?
20. Does progression create any new or broader authority?

---

## 34. Core Rule

> **Operational progression for a Defence AI capability shall be governed through explicit preconditions and decision gates. No capability shall progress to a higher-risk operational state or broader authority merely because it is technically available or previously authorised. Mandatory evidence, risk treatment, human authority, configuration, environmental suitability, autonomy controls and other applicable safeguards shall be demonstrated or explicitly addressed through an appropriately authorised governance decision before progression.**
