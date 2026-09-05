# Operational Assumptions

## 1. Purpose

Operational Assumptions identifies assumptions on which an AI use case, risk assessment, assurance position or operational authorisation depends.

The purpose is to make assumptions explicit, testable and reviewable rather than allowing them to become hidden dependencies.

---

## 2. Core Principle

An assumption that materially affects AI behaviour, risk, human control or operational authority must be visible.

> **An unverified assumption should not be treated as established operational fact.**

Assumptions may be acceptable at one lifecycle stage but require validation before progression to a higher-consequence stage.

---

## 3. Scope

Operational assumptions may relate to:

- mission;
- environment;
- data;
- sensors;
- communications;
- infrastructure;
- personnel;
- human authority;
- autonomy;
- security;
- dependencies;
- system configuration;
- supplier support;
- legal and policy conditions;
- operational procedures.

---

## 4. Types of Assumptions

### 4.1 Mission Assumptions

Examples:

- mission objective remains unchanged;
- intended users remain defined;
- AI remains limited to the stated mission;
- mission alternatives remain available where required.

### 4.2 Environmental Assumptions

Examples:

- expected terrain is within defined conditions;
- weather remains within tested limits;
- environmental conditions do not materially exceed validated boundaries.

### 4.3 Information Assumptions

Examples:

- required data will be available;
- data provenance can be established;
- information quality remains within defined limits;
- critical inputs are not materially corrupted.

### 4.4 Communications Assumptions

Examples:

- required communications are available;
- latency remains within acceptable limits;
- loss of communications can be detected;
- the system has an appropriate degraded mode.

### 4.5 Human Assumptions

Examples:

- users possess required competency;
- sufficient personnel are available;
- workload remains manageable;
- human intervention remains practical.

### 4.6 Technical Assumptions

Examples:

- hardware remains within validated configuration;
- critical software dependencies remain available;
- interfaces behave as specified;
- computing resources remain sufficient.

### 4.7 Security Assumptions

Examples:

- security controls remain effective;
- privileged access remains controlled;
- system integrity can be monitored;
- critical dependencies have not been compromised.

### 4.8 Authority Assumptions

Examples:

- designated decision-makers remain available;
- delegated authority remains valid;
- escalation channels remain functional;
- required human approval can be obtained.

### 4.9 Supply-Chain Assumptions

Examples:

- suppliers maintain declared controls;
- software and model provenance remains known;
- updates are controlled;
- critical components are not silently replaced.

---

## 5. Assumption vs Requirement

An assumption describes a condition believed to be true.

A requirement establishes a condition that must be satisfied.

For example:

**Assumption:** Communications will normally be available.

**Requirement:** The system must safely degrade when communications are unavailable.

Assumptions should therefore not substitute for controls or requirements where the consequence of failure is material.

---

## 6. Assumption vs Constraint

A constraint limits what the system or mission can do.

An assumption describes a condition expected to exist.

An assumption may become a constraint when failure to satisfy it materially limits safe or authorised operation.

---

## 7. Assumption Classification

Each material assumption should be classified, where appropriate, as:

- **Verified** — supported by evidence.
- **Partially Verified** — supported within defined conditions.
- **Unverified** — not yet sufficiently demonstrated.
- **Invalidated** — evidence indicates the assumption is no longer reliable.
- **Conditional** — valid only under specified conditions.
- **Accepted Residual Uncertainty** — not fully verified but explicitly considered and accepted by the appropriate authority.

---

## 8. Materiality

An assumption is material when its failure could affect:

- mission effectiveness;
- safety;
- security;
- human control;
- autonomy;
- operational boundaries;
- risk;
- assurance;
- operational authorisation;
- legal or policy compliance.

Material assumptions require stronger management than routine planning assumptions.

---

## 9. Assumption Register

Each consequential use case should maintain an assumption register.

Suggested fields:

| Field | Description |
|---|---|
| Assumption ID | Unique identifier |
| Category | Mission, environment, data, human, technical, etc. |
| Assumption | Statement of expected condition |
| Rationale | Why the assumption is made |
| Materiality | Impact if false |
| Evidence | Supporting evidence |
| Verification Method | How it will be tested |
| Owner | Responsible person/organisation |
| Status | Verified, conditional, etc. |
| Expiry/Review | When it must be reassessed |
| Failure Impact | Consequence if invalidated |
| Linked Risk | Related risk |
| Linked Control | Related control |
| Authorisation Impact | Potential effect on authority |

---

## 10. Assumptions and Risk

Assumptions are risk variables.

If an assumption fails, the risk position may change.

The relationship is:

**Assumption → Condition → Risk → Control → Evidence → Assurance → Authority**

Important assumptions should therefore be linked to the relevant risk record.

---

## 11. Assumptions and Assurance

Assurance should consider whether material assumptions have been demonstrated.

Where an assurance claim depends on an assumption, the evidence should identify:

- the assumption;
- the conditions under which it was tested;
- evidence supporting it;
- limitations;
- remaining uncertainty.

An assurance claim should not be stronger than the assumptions supporting it.

---

## 12. Assumptions and TEVV

Material assumptions should be converted into testable conditions where practical.

Examples:

- communications availability → communications-loss testing;
- sensor reliability → degraded-sensor testing;
- human response time → human-in-the-loop evaluation;
- environmental suitability → representative environmental testing;
- data quality → data integrity and quality evaluation.

This converts hidden uncertainty into explicit evidence requirements.

---

## 13. Assumptions and Human Control

Some assumptions directly affect meaningful human control.

Examples include assumptions that:

- a human will see the recommendation;
- the human will have enough time to intervene;
- communications will permit intervention;
- the human will understand system limitations;
- an override mechanism will remain available.

If these assumptions fail, human presence may remain while meaningful control is lost.

---

## 14. Assumptions and Autonomy

Autonomy may depend on assumptions about:

- communications;
- sensor availability;
- human supervision;
- system reliability;
- environmental conditions;
- mission consequence.

A higher autonomy level should not be treated as valid merely because it was technically demonstrated under more favourable assumptions.

---

## 15. Assumptions and Operational Boundaries

Each material assumption should be associated with the relevant operational boundary where possible.

For example:

**Assumption:** GPS-quality positioning remains within validated limits.

**Boundary:** Navigation use is restricted outside those limits unless separately assessed.

The failure of an assumption may therefore trigger a boundary condition or out-of-bounds state.

---

## 16. Assumptions and Dependencies

Assumptions frequently depend on external systems or organisations.

Examples include:

- communications networks;
- cloud or external services;
- satellite services;
- power;
- navigation;
- data providers;
- suppliers;
- maintenance organisations.

Critical dependencies should be identified explicitly.

---

## 17. Assumptions and Security

Security assumptions should be treated cautiously.

Examples include:

- trusted software;
- uncompromised credentials;
- secure update mechanisms;
- reliable identity management;
- uncompromised data;
- trusted suppliers.

Where compromise could materially affect mission safety or authority, the assumption should have a corresponding detection or response mechanism.

---

## 18. Assumption Failure

When a material assumption becomes false or uncertain, the organisation should determine whether to:

- continue operation;
- apply additional controls;
- reduce autonomy;
- restrict the operational envelope;
- transfer control to a human;
- suspend the capability;
- invoke fail-safe procedures;
- reassess risk;
- initiate revalidation;
- initiate reauthorisation.

The response should be proportionate to consequence.

---

## 19. Assumption Monitoring

Material assumptions should be monitored during operational employment where feasible.

Monitoring may use:

- system telemetry;
- environmental data;
- data-quality indicators;
- communications status;
- security alerts;
- human workload indicators;
- dependency status;
- operational reports.

The purpose is to detect when the conditions supporting the authorised use case no longer hold.

---

## 20. Assumption Expiry

Some assumptions should have an explicit review or expiry condition.

Review may be triggered by:

- passage of time;
- system change;
- mission change;
- new threat;
- new operational environment;
- incident;
- supplier change;
- policy change;
- new evidence.

An assumption should not remain valid indefinitely merely because it was once accepted.

---

## 21. Assumption Confidence

Confidence in an assumption should reflect the strength and relevance of available evidence.

Evidence should be assessed for:

- relevance;
- recency;
- representativeness;
- independence;
- reproducibility;
- operational applicability.

Strong evidence from a laboratory environment may not establish an assumption for an extreme operational environment.

---

## 22. Unknown Assumptions

D-AIGAAF should recognise that not all assumptions can be identified in advance.

Operational experience, incidents, testing and monitoring may reveal previously unrecognised dependencies or conditions.

These should be captured and incorporated into:

- risk;
- assurance;
- TEVV;
- operational boundaries;
- controls;
- future authorisation decisions.

---

## 23. Assumption Escalation

Escalation should occur when:

- a critical assumption is invalidated;
- multiple assumptions fail simultaneously;
- an assumption becomes materially uncertain;
- evidence no longer supports the assumption;
- operational conditions depart from the assumed environment;
- the consequence of assumption failure increases.

Escalation authority should be predefined.

---

## 24. Operational Assumptions Record

The Operational Assumptions Record should contain, as applicable:

- use case identifier;
- assumption identifier;
- assumption statement;
- category;
- rationale;
- materiality;
- evidence;
- verification status;
- owner;
- linked risk;
- linked control;
- linked boundary;
- monitoring method;
- failure condition;
- response;
- review date;
- authorisation implications.

---

## 25. Minimum Operational Assumption Requirements

For consequential AI use cases:

1. Material assumptions should be explicitly documented.
2. Assumptions should be distinguished from requirements and constraints.
3. Material assumptions should be linked to risk.
4. Important assumptions should have an identified owner.
5. Material assumptions should be supported by evidence where practical.
6. Critical assumptions should be converted into TEVV conditions where possible.
7. Assumptions affecting human control should be explicitly assessed.
8. Assumptions affecting autonomy should be explicitly assessed.
9. Critical dependencies should be identified.
10. Material assumptions should be monitored where feasible.
11. Failure of critical assumptions should have a defined response.
12. Invalidated assumptions should trigger appropriate reassessment.
13. Assumption changes should be traceable.
14. Assumptions should not silently become permanent operating conditions.

---

## 26. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Golden Thread`
- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Operational_Scenarios.md`
- `02 Mission & Use Case/Operational_Boundaries.md`
- `02 Mission & Use Case/Mission_Threat_Context.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `05 Data & Information`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `10 Operational Environment`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`

Operational assumptions provide an explicit bridge between what the organisation expects to be true and what must actually be demonstrated before authority is granted.

---

## 27. Summary

Operational assumptions make hidden dependencies visible.

They ensure that D-AIGAAF does not treat uncertain conditions as established facts and provides a mechanism for testing, monitoring and escalating when assumptions cease to hold.

The central principle is:

> **If a material assumption supports risk, assurance or operational authority, it must be explicit, traceable and subject to verification or controlled acceptance.**
