# Use Case Approval Criteria

## 1. Purpose

Use Case Approval Criteria define the minimum conditions that should be satisfied before an AI use case progresses from definition into the next stage of the D-AIGAAF lifecycle.

They provide a structured basis for determining whether a proposed use case is sufficiently defined, bounded and understood to proceed to risk assessment, development, TEVV, assurance or operational authorisation.

Approval at this stage does **not** constitute operational authorisation.

---

## 2. Core Principle

A use case should not progress merely because an AI solution is technically available.

The governing sequence is:

**Mission Need → Use Case Definition → Approval Criteria → Risk & Autonomy → Development/TEVV → Assurance → Operational Authorisation**

Approval should establish that the use case is sufficiently clear and controlled for the proposed lifecycle stage.

---

## 3. Approval vs Authorisation

The framework distinguishes:

**Use Case Approval**

from

**Assurance**

from

**Operational Authorisation**

Use case approval confirms that the proposed use is sufficiently defined and legitimate to proceed.

Assurance establishes what evidence demonstrates about the capability.

Operational authorisation establishes whether, where and under what conditions the capability may actually be employed.

Approval must not be interpreted as operational permission.

---

## 4. Approval Scope

Approval criteria should be applied proportionately to the proposed use case.

The assessment should consider:

- mission consequence;
- autonomy;
- mission criticality;
- operational environment;
- human control;
- security exposure;
- information sensitivity;
- potential for loss of control;
- foreseeable misuse;
- dependency risk.

Higher-consequence or higher-autonomy use cases should require stronger review.

---

## 5. Mission Need

Before approval, the use case should demonstrate:

- a legitimate mission need;
- a defined mission objective;
- a clear operational problem;
- a reason for considering AI;
- an identified mission owner.

The use case should not be justified solely by the availability of a technology.

---

## 6. Use Case Definition

The use case should clearly define:

- objective;
- actors;
- AI role;
- human role;
- inputs;
- outputs;
- normal flow;
- alternative flows;
- failure conditions;
- operational environment;
- constraints;
- autonomy;
- human override;
- foreseeable misuse.

Ambiguity in these areas should remain visible rather than being assumed away.

---

## 7. Decision Context

Where AI supports a consequential decision, the use case should identify:

- decision or activity supported;
- decision objective;
- authorised human decision-maker;
- AI contribution;
- human contribution;
- available information;
- decision time;
- consequence;
- alternatives;
- escalation arrangements.

The distinction between **AI output, human decision and command authority** should be explicit.

---

## 8. Operational Context

The proposed operating context should be sufficiently defined to identify material conditions.

Consider:

- geography;
- terrain;
- weather;
- sensor conditions;
- communications;
- computing;
- data availability;
- human workload;
- adversarial conditions;
- legal and policy context;
- critical dependencies.

A use case should not be approved on assumptions that are materially unknown.

---

## 9. Operational Boundaries

The proposed use case should identify its initial operational boundaries.

These should include, where relevant:

- mission;
- environment;
- data;
- communications;
- users;
- autonomy;
- configuration;
- permitted actions;
- prohibited actions.

The boundaries should be sufficiently clear to support risk assessment.

---

## 10. Mission Constraints

Material constraints should be identified.

These may include:

- operational;
- environmental;
- information;
- communications;
- computing;
- sensor;
- human;
- time;
- security;
- legal/policy;
- resource;
- supply-chain;
- interoperability;
- autonomy;
- safety constraints.

Unresolved constraints should be recorded as conditions or gaps.

---

## 11. Initial Risk Profile

An initial risk profile should be established before progression into later lifecycle stages.

It should consider:

- consequence;
- autonomy;
- mission criticality;
- environment;
- human control;
- information integrity;
- security;
- loss of control;
- reliability;
- availability;
- supply chain;
- dependencies;
- foreseeable misuse;
- uncertainty.

The initial profile should identify major risk drivers rather than attempting false numerical precision.

---

## 12. Autonomy

The proposed autonomy level should be explicitly identified.

The assessment should establish:

- what the AI can technically do;
- what it is intended to do;
- what autonomy is proposed;
- what autonomy is prohibited;
- what human intervention is expected.

Technical capability beyond the proposed autonomy level should not automatically become part of the approved use case.

---

## 13. Human Authority

The proposed human authority structure should be clear.

This should identify, where applicable:

- operational authority;
- decision authority;
- risk acceptance authority;
- technical authority;
- suspension authority;
- emergency authority;
- OAIA involvement.

Authority should derive from legitimate organisational, legal and policy arrangements.

---

## 14. Human Control

Where human control is required, the use case should demonstrate a credible mechanism for:

- review;
- rejection;
- override;
- suspension;
- termination;
- escalation.

The assessment should consider whether intervention remains practical under realistic workload, communications and environmental conditions.

---

## 15. Success Criteria

Mission-level success criteria should be defined.

These should address, where relevant:

- mission effectiveness;
- technical performance;
- accuracy;
- timeliness;
- reliability;
- robustness;
- human decision quality;
- safety;
- security;
- uncertainty communication;
- human control;
- resilience.

Technical metrics alone should not constitute approval evidence.

---

## 16. Operational Scenarios

Representative scenarios should be identified.

At minimum, consideration should be given to:

- normal operation;
- degraded conditions;
- information degradation;
- communications loss;
- human workload;
- failure;
- recovery;
- adversarial conditions where relevant;
- high-consequence conditions where applicable.

Scenarios provide the basis for later TEVV and should be traceable to the use case.

---

## 17. Foreseeable Misuse

The approval assessment should identify reasonably foreseeable misuse.

This may include:

- use outside the mission;
- use outside the authorised environment;
- use by unauthorised personnel;
- excessive reliance on AI recommendations;
- use with unsuitable data;
- use beyond authorised autonomy.

Controls should be identified where foreseeable misuse could create material risk.

---

## 18. Security and Integrity

The use case should identify relevant security considerations.

These may include:

- data integrity;
- model integrity;
- system integrity;
- access control;
- authentication;
- adversarial manipulation;
- cyber attack;
- supply-chain compromise;
- critical dependencies.

Security requirements should be proportionate to consequence and exposure.

---

## 19. Fail-Safe and Controlled Degradation

The proposed use case should identify how serious failure will be handled.

Possible responses include:

- warning;
- controlled degradation;
- transfer to human control;
- isolation;
- suspension;
- fail-safe;
- shutdown.

Where delay could create unacceptable harm, pre-authorised emergency protective procedures may permit immediate intervention.

---

## 20. Evidence Plan

Before approval, the use case should have an initial evidence plan identifying:

- what claims will need to be demonstrated;
- what tests or evaluations may be required;
- what operational scenarios are relevant;
- what human factors evidence is required;
- what security testing is required;
- what evidence gaps currently exist.

The evidence plan may evolve as the system becomes better understood.

---

## 21. Configuration and Dependencies

The proposed capability should identify known:

- system components;
- model dependencies;
- software dependencies;
- hardware dependencies;
- data dependencies;
- communications dependencies;
- external services.

Where a configuration baseline does not yet exist, this should be recorded rather than implied.

---

## 22. Legal and Policy Alignment

The use case should be checked against applicable:

- law;
- government policy;
- defence policy;
- doctrine;
- directives;
- organisational rules;
- applicable standards.

D-AIGAAF does not create legal authority.

A use case should not progress on the assumption that framework approval overrides existing legal or policy requirements.

---

## 23. Accountability

The use case should have clearly identified accountability.

At minimum, appropriate responsibility should exist for:

- mission ownership;
- system management;
- risk;
- assurance;
- operational authority;
- security;
- data;
- evidence.

Accountability should not be transferred to the AI system.

---

## 24. OAIA Assessment

For use cases involving significant AI complexity, autonomy or consequence, consideration should be given to assigning an Operational AI Advisor.

The assessment may determine:

- whether an OAIA is required;
- what competency is required;
- when the OAIA participates;
- escalation responsibilities;
- relationship with command authority.

The OAIA advises; authorised human authority decides.

---

## 25. Approval Conditions

Approval may be:

- unconditional for progression to the next lifecycle stage;
- conditional on specified actions;
- restricted to a defined scope;
- deferred pending additional information;
- rejected.

Conditions should be explicit, recorded and reviewable.

---

## 26. Approval Decision

The approval decision should record:

- use case identifier;
- decision;
- approving authority;
- date;
- conditions;
- unresolved issues;
- required actions;
- next lifecycle stage;
- review date;
- relevant evidence.

The decision should be traceable.

---

## 27. Approval Criteria Matrix

| Criterion | Minimum Expectation | Status |
|---|---|---|
| Mission Need | Legitimate and defined |  |
| Use Case | Clearly bounded |  |
| Decision Context | Human authority identified |  |
| Operational Context | Material conditions identified |  |
| Constraints | Major constraints identified |  |
| Risk | Initial risk profile completed |  |
| Autonomy | Proposed autonomy explicit |  |
| Human Control | Required control identified |  |
| Success Criteria | Mission-level criteria defined |  |
| Scenarios | Representative scenarios identified |  |
| Security | Major security risks identified |  |
| Fail-Safe | Failure response considered |  |
| Evidence | Initial evidence plan defined |  |
| Dependencies | Critical dependencies identified |  |
| Legal/Policy | Alignment assessed |  |
| Accountability | Responsible authorities identified |  |
| Records | Required records established |  |

---

## 28. Approval Outcomes

### Approved

The use case satisfies the applicable criteria and may proceed to the authorised next lifecycle stage.

### Conditionally Approved

The use case may proceed subject to explicit conditions.

### Deferred

The use case requires additional information, analysis or clarification before progression.

### Rejected

The proposed use case does not satisfy the applicable criteria or is not appropriate to progress.

### Restricted

Progression is limited to a defined scope, environment, autonomy level or activity.

---

## 29. Review Triggers

Approval should be reconsidered when:

- mission changes;
- use case changes;
- consequence changes;
- autonomy changes;
- operational environment changes;
- human control changes;
- new threats emerge;
- system behaviour changes;
- critical dependencies change;
- significant incidents occur;
- policy or legal requirements change.

Approval should not be treated as permanently valid when the underlying use case has materially changed.

---

## 30. Approval Record

A controlled Use Case Approval Record should contain, as applicable:

- use case identifier;
- mission;
- decision context;
- operational context;
- constraints;
- initial risk profile;
- autonomy;
- human authority;
- success criteria;
- operational scenarios;
- security assessment;
- fail-safe arrangements;
- evidence plan;
- dependencies;
- legal/policy assessment;
- accountability assignments;
- OAIA assessment;
- approval decision;
- conditions;
- approving authority;
- review triggers;
- review date.

---

## 31. Minimum Approval Requirements

A consequential AI use case should not progress without:

1. A defined and legitimate mission need.
2. A sufficiently bounded use case.
3. A defined decision context where applicable.
4. Identified operational conditions.
5. Identified material constraints.
6. An initial risk profile.
7. Explicit proposed autonomy.
8. Identified human authority.
9. Defined human control requirements.
10. Mission-level success criteria.
11. Representative operational scenarios.
12. Initial security and integrity assessment.
13. Defined failure and fail-safe considerations.
14. An initial evidence plan.
15. Identified critical dependencies.
16. Legal and policy alignment assessment.
17. Explicit accountability.
18. A recorded approval decision.

---

## 32. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread`
- `01 Strategy & Governance`
- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `02 Mission & Use Case/Use_Case_Register.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Mission_Decision_Context.md`
- `02 Mission & Use Case/Operational_Boundaries.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `08 Human Authority`
- `09 TEVV`
- `11 Operational Authorisation`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

This module provides the decision point between defining a use case and progressing it through the wider D-AIGAAF lifecycle.

---

## 33. Summary

Use Case Approval Criteria prevent technically attractive AI applications from progressing without a sufficiently defined mission, decision context, risk position, human authority and operational boundary.

Approval establishes that a use case is sufficiently understood and controlled to proceed.

It does not establish that the AI capability is safe, assured or operationally authorised.

The central principle is:

> **A consequential AI use case should progress only when its purpose, boundaries, risks, human authority, evidence needs and failure conditions are sufficiently defined for the next lifecycle stage.**
