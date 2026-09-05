# Lifecycle Governance

## Summary

Lifecycle Governance establishes the governance controls, responsibilities, decision rights and evidence requirements that apply throughout the lifecycle of a defence AI capability.

D-AIGAAF treats governance as a continuous function from initial need through retirement. Governance must remain connected to mission purpose, risk, autonomy, assurance, human authority, operational employment and change.

The central principle is:

**No lifecycle stage operates outside governance.**

---

## 1. Purpose

Lifecycle Governance provides a common governance structure for managing AI-enabled defence capabilities across:

- strategic planning;
- requirements;
- development;
- acquisition;
- integration;
- testing and evaluation;
- assurance;
- operational authorisation;
- deployment;
- operational employment;
- monitoring;
- change;
- revalidation;
- reauthorisation;
- retirement.

It ensures that responsibility and authority remain clear as the capability moves between lifecycle stages.

---

## 2. Core Principle

AI governance is not a single approval event.

A capability may be technically functional while still being:

- inadequately understood;
- insufficiently tested;
- insufficiently assured;
- outside its authorised environment;
- subject to unresolved risk;
- operating with inadequate human control; or
- affected by changes that invalidate previous evidence.

Lifecycle governance therefore requires decisions to be made at appropriate stages and supported by evidence.

---

## 3. Governance Objectives

Lifecycle Governance should ensure that:

1. mission need remains the basis for capability development;
2. requirements remain traceable to mission objectives;
3. risk and autonomy are assessed throughout the lifecycle;
4. responsibilities and decision rights are explicit;
5. evidence supports material lifecycle decisions;
6. operational authority is separated from technical development authority;
7. human authority remains identifiable;
8. configuration remains traceable;
9. material changes trigger appropriate reassessment;
10. incidents can trigger restriction, suspension or reauthorisation;
11. assurance remains current;
12. retirement and decommissioning are controlled.

---

## 4. Lifecycle Governance Structure

Governance should operate through complementary layers rather than a single committee.

### Strategic Governance

Provides direction and establishes:

- strategic objectives;
- policy alignment;
- organisational priorities;
- risk tolerance;
- resource priorities;
- sovereignty considerations.

### Capability Governance

Oversees the AI-enabled capability across its lifecycle.

Responsibilities may include:

- capability planning;
- requirements;
- acquisition/development;
- lifecycle status;
- configuration;
- sustainment;
- change governance.

### Risk & Assurance Governance

Provides independent or appropriately separated challenge concerning:

- risk;
- autonomy;
- human control;
- TEVV;
- security;
- operational environment;
- assurance evidence;
- residual risk.

### Operational Governance

Determines whether and how an assured capability may be employed within an authorised operational context.

### Change Governance

Determines whether changes require:

- routine acceptance;
- additional testing;
- risk reassessment;
- revalidation;
- reauthorisation;
- restriction;
- suspension.

### Retirement Governance

Controls:

- withdrawal;
- archival;
- access removal;
- data disposition;
- dependency removal;
- evidence retention;
- decommissioning.

---

## 5. Lifecycle Accountability

Each capability should have clearly identified accountability across the lifecycle.

Typical responsibilities include:

| Role | Primary Responsibility |
|---|---|
| Capability Owner | Overall capability lifecycle |
| Mission Owner | Mission need and operational suitability |
| System Owner | Integrated system performance and sustainment |
| AI/Model Owner | Model lifecycle and technical behaviour |
| Data Owner | Data governance and provenance |
| Security Authority | Security and integrity controls |
| Safety/Assurance Authority | Safety, assurance and evidence challenge |
| Test & Evaluation Authority | TEVV planning and evidence |
| Operational AI Advisor (OAIA) | Bridge between operational and AI expertise |
| Command/Operational Authority | Operational employment authority |
| Configuration Authority | Configuration and baseline control |
| Change Authority | Change significance and approval |
| Legal/Policy Authority | Applicable legal and policy requirements |
| Audit/Review Authority | Independent review and traceability |

Organisations may combine roles where appropriate, but high-consequence decisions should maintain appropriate separation of duties and independence.

---

## 6. Separation of Responsibilities

D-AIGAAF distinguishes between:

**Development → Testing → Assurance → Risk Acceptance → Operational Authorisation → Employment**

These functions should not automatically be controlled by the same individual or organisation.

The purpose of separation is to reduce conflicts of interest and ensure that technical confidence does not become operational permission without appropriate review.

A developer may state that a capability works.

A test organisation may provide evidence of performance.

An assurance authority may judge whether the evidence supports defined claims.

A risk authority may accept defined residual risk.

An operational authority may authorise employment.

These are related but distinct decisions.

---

## 7. Lifecycle Decision Rights

Every material lifecycle decision should identify:

- decision;
- decision authority;
- required evidence;
- required consultation;
- conditions;
- validity period;
- escalation route;
- review trigger.

Examples include:

| Decision | Typical Authority |
|---|---|
| Approve mission need | Appropriate capability authority |
| Approve use case | Mission/capability authority |
| Approve requirements | Requirements authority |
| Accept development baseline | Capability/system authority |
| Approve TEVV plan | Appropriate T&E authority |
| Accept assurance findings | Assurance authority |
| Accept residual risk | Empowered risk authority |
| Authorise operational employment | Appropriate operational authority |
| Approve material change | Designated change authority |
| Require revalidation | Assurance/change authority |
| Amend operational authorisation | Operational authorising authority |
| Suspend capability | Authorised operational/governance authority |
| Retire capability | Capability authority |

The exact authority structure should be determined by applicable organisational, legal, policy and command arrangements.

---

## 8. Lifecycle Stage Reviews

Each major lifecycle stage should have an appropriate review.

A review should determine:

- whether entry criteria are satisfied;
- whether evidence is adequate;
- whether assumptions remain valid;
- whether risks are understood;
- whether controls are effective;
- whether required decisions have been made;
- whether the capability may progress;
- whether additional work is required.

Possible review outcomes:

- Proceed;
- Proceed with Conditions;
- Hold;
- Rework;
- Restrict;
- Escalate;
- Reject;
- Return to Earlier Stage.

---

## 9. Entry and Exit Criteria

Every major lifecycle stage should have defined entry and exit criteria.

### Entry Criteria

May include:

- required prior-stage outputs;
- identified accountable owner;
- approved scope;
- available resources;
- known dependencies;
- required governance approvals.

### Exit Criteria

May include:

- required evidence completed;
- identified risks assessed;
- controls implemented;
- unresolved limitations documented;
- required authority decision recorded;
- next-stage conditions established.

A capability should not progress merely because a schedule or programme milestone has been reached.

---

## 10. Evidence-Based Governance

Governance decisions should be supported by evidence proportionate to consequence and risk.

Evidence may include:

- requirements;
- test results;
- evaluation results;
- validation evidence;
- configuration records;
- risk assessments;
- assurance judgements;
- operational observations;
- incident records;
- monitoring data;
- security assessments;
- human-control assessments;
- supplier information;
- change assessments.

Evidence should identify:

- source;
- date;
- configuration;
- environment;
- test conditions;
- limitations;
- confidence;
- applicability.

---

## 11. Governance of Assumptions

Lifecycle decisions often depend on assumptions.

Examples include assumptions about:

- operating environment;
- data quality;
- communications;
- sensor availability;
- user competence;
- human response time;
- supplier behaviour;
- system dependencies;
- threat conditions.

Material assumptions should be:

1. recorded;
2. assigned an owner;
3. tested where practicable;
4. monitored;
5. reviewed when conditions change.

An assumption that is no longer valid may invalidate part of the assurance basis.

---

## 12. Governance of Configuration

Lifecycle governance must maintain traceability between:

**Authorised Configuration ↔ Tested Configuration ↔ Deployed Configuration ↔ Operational Configuration**

Configuration governance should cover:

- model versions;
- software;
- hardware;
- data;
- sensors;
- interfaces;
- dependencies;
- security configuration;
- autonomy configuration;
- operating parameters;
- relevant procedures.

Uncontrolled configuration drift can invalidate assurance and operational authority.

---

## 13. Governance of Change

Change should be classified according to its potential effect on:

- system behaviour;
- risk;
- autonomy;
- human control;
- security;
- mission effectiveness;
- operational environment;
- dependencies;
- assurance evidence.

Possible change classes:

### Routine Change

No material effect on authorised behaviour or assurance basis.

### Controlled Change

Potentially relevant change requiring targeted assessment or testing.

### Material Change

Change capable of materially affecting behaviour, risk, autonomy, human control or assurance.

### Critical Change

Change requiring immediate restriction, suspension or urgent reassessment because the existing assurance or authority basis may no longer be valid.

Change classification should be evidence-based rather than determined solely by the size or type of technical modification.

---

## 14. Governance of Incidents

Incidents should be treated as lifecycle governance events.

Relevant incidents may include:

- unexpected AI behaviour;
- significant performance degradation;
- boundary violation;
- loss of effective human control;
- security compromise;
- information-integrity failure;
- unsafe autonomy transition;
- loss-of-control event;
- significant mission failure.

Incident governance should determine:

- immediate protective action;
- capability restriction;
- evidence preservation;
- root-cause investigation;
- risk reassessment;
- assurance impact;
- revalidation requirements;
- reauthorisation requirements.

---

## 15. Governance of Human Authority

Lifecycle governance must establish who has authority to:

- approve use;
- approve autonomy;
- intervene;
- override;
- suspend;
- reduce autonomy;
- invoke pre-authorised fail-safe mechanisms;
- resume operations;
- accept residual risk;
- authorise continued employment.

The principle remains:

**AI Output ≠ Human Decision ≠ Command Authority**

The Operational AI Advisor provides informed technical-operational advice but does not replace the authorised decision maker.

---

## 16. Governance of Autonomy

Autonomy governance should address:

- intended autonomy;
- actual autonomy;
- assessed autonomy;
- assured autonomy;
- authorised autonomy;
- autonomy transitions;
- autonomy constraints;
- human control;
- loss of control;
- recovery.

The progression is:

**Technical Capability → Actual Behaviour → Assessed Autonomy → Assured Autonomy → Authorised Autonomy**

Technical ability to perform an action does not itself create authority to perform that action.

---

## 17. Governance of Operational Authorisation

Operational authorisation should remain explicitly bounded by:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Governance should define:

- authorising authority;
- evidence basis;
- conditions;
- limitations;
- operational envelope;
- configuration;
- validity period;
- monitoring requirements;
- suspension triggers;
- revocation triggers;
- reauthorisation requirements.

Operational authorisation should not be treated as permanent permission.

---

## 18. Governance of Continuous Assurance

After deployment, governance should ensure that assurance remains current.

Review should be triggered by:

- material changes;
- incidents;
- new threats;
- environmental changes;
- performance degradation;
- newly discovered failure modes;
- supplier changes;
- dependency changes;
- changes in law or policy;
- changes in mission;
- changes in autonomy;
- evidence becoming outdated.

The objective is not to repeat every test continuously, but to determine whether the existing assurance basis remains valid.

---

## 19. Governance Escalation

A governance escalation path should exist for situations where:

- risk exceeds tolerance;
- evidence is insufficient;
- human control is ineffective;
- autonomy exceeds authorised boundaries;
- assurance confidence falls;
- configuration cannot be verified;
- significant unexpected behaviour occurs;
- an incident may invalidate authorisation.

A conceptual escalation path is:

**User/Operator → System Owner → OAIA → Assurance/Risk Authority → Operational Authority → Higher Governance Authority**

The exact path should be defined by applicable organisational arrangements.

Emergency protective action may be pre-authorised where delay could create unacceptable harm. Such action should be narrow, recorded and subject to subsequent review.

---

## 20. Governance Records

Lifecycle governance should maintain traceable records including:

- governance decisions;
- approvals;
- decision authorities;
- conditions;
- dissent or challenge;
- evidence references;
- assumptions;
- risk decisions;
- configuration decisions;
- change classifications;
- incident decisions;
- assurance decisions;
- authorisation decisions;
- review outcomes.

Records should allow reconstruction of why a material decision was made.

---

## 21. Governance Review and Challenge

High-consequence AI capabilities should be subject to appropriate independent challenge.

Challenge may examine:

- whether requirements are realistic;
- whether testing is sufficient;
- whether evidence supports claims;
- whether uncertainty is adequately understood;
- whether human control is meaningful;
- whether autonomy is appropriately bounded;
- whether residual risk is acceptable;
- whether operational authorisation is justified.

Challenge is not intended to prevent innovation. It is intended to prevent unsupported confidence from becoming operational authority.

---

## 22. Lifecycle Governance Failure Modes

Common failures include:

- unclear ownership;
- overlapping or conflicting authorities;
- development authority becoming operational authority;
- inadequate separation of assurance and acceptance;
- approval without sufficient evidence;
- schedule-driven progression;
- uncontrolled configuration;
- undocumented assumptions;
- weak change governance;
- treating incidents as isolated technical problems;
- failure to reassess autonomy;
- stale assurance evidence;
- unclear suspension authority;
- unclear emergency authority;
- failure to record decisions;
- retirement without controlled decommissioning.

---

## 23. Core Rules

1. **Governance applies across the entire AI lifecycle.**
2. **Every material decision must have an identifiable authority.**
3. **Technical capability does not create operational authority.**
4. **Governance decisions should be evidence-based.**
5. **High-consequence decisions require proportionate challenge and independence.**
6. **Configuration must remain traceable.**
7. **Material assumptions must be recorded and monitored.**
8. **Material changes require impact assessment.**
9. **Incidents can trigger reassessment even without technical changes.**
10. **Operational authorisation is bounded, conditional and reviewable.**
11. **Human authority must remain explicit.**
12. **The OAIA advises; the authorised authority decides.**
13. **Assurance must remain current throughout operational employment.**
14. **Suspension and revocation mechanisms must be defined before deployment.**
15. **Retirement and decommissioning require governance.**

---

## 24. Golden Thread

Lifecycle Governance maintains the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Governance is the mechanism that keeps this chain connected and ensures that authority does not become detached from evidence, risk and operational context.

---

## 25. Relationship to Other D-AIGAAF Sections

This document provides governance controls for the AI lifecycle and connects directly with:

- **01 Strategy & Governance** — organisational governance and decision rights.
- **02 Mission & Use Case** — mission definition and operational context.
- **03 Risk & Autonomy** — risk, autonomy, human control and constraints.
- **04 AI Lifecycle** — lifecycle stages and transition controls.
- **06 AI Security** — security governance and integrity.
- **08 Human Authority** — human decision rights and accountability.
- **09 TEVV** — evidence generation and evaluation.
- **11 Operational Authorisation** — formal employment authority.
- **13 Continuous Assurance** — post-deployment assurance.
- **15 Change & Reauthorisation** — material change and authority renewal.
- **16 Audit & Evidence** — lifecycle traceability.
- **26 Retirement & Decommissioning** — controlled withdrawal.

---

## 26. Summary Model

```text
Lifecycle Stage
      ↓
Entry Criteria
      ↓
Assigned Responsibility
      ↓
Evidence & Risk Review
      ↓
Governance Decision
      ↓
Conditions / Authority
      ↓
Lifecycle Progression
      ↓
Monitoring
      ↓
Change / Incident / New Evidence
      ↓
Reassessment
      ↓
Revalidation / Reauthorisation
```

Lifecycle Governance ensures that a defence AI capability remains **traceable, accountable, evidence-based and appropriately authorised throughout its entire lifecycle**.
