# D-AIGAAF — Governance Model

**Document:** Governance Model  
**Framework:** D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework  
**Status:** Working Draft v0.1  
**Classification:** Generic / Unclassified

---

## 1. Purpose

This document defines the governance architecture for D-AIGAAF.

It establishes how authority, accountability, responsibility, assurance, operational decision-making and escalation are organised across the lifecycle of a defence AI capability.

The governance model is designed to ensure that:

> **No consequential AI capability is developed, authorised or employed without clear authority, defined accountability, appropriate evidence and a traceable decision process.**

This document complements the D-AIGAAF Reference Model, Principles, Terminology, Lifecycle and Golden Thread.

---

## 2. Governance Philosophy

D-AIGAAF treats governance as an operational control system rather than a purely administrative function.

Governance must answer five questions:

1. **Who has the authority to decide?**
2. **Who is accountable for the outcome?**
3. **Who is responsible for the technical capability?**
4. **Who independently assures the capability?**
5. **Who advises commanders on the implications of AI behaviour in the operational context?**

Governance must remain effective across the entire AI lifecycle, from strategic need through retirement.

Governance requirements should increase with:

- consequence;
- autonomy;
- mission criticality;
- environmental uncertainty;
- degree of human control;
- potential for loss of control;
- dependency on external or opaque components.

---

## 3. Governance Objectives

D-AIGAAF governance shall seek to:

- establish clear decision rights;
- preserve legitimate human authority;
- prevent unauthorised expansion of AI authority;
- maintain separation between system ownership and independent assurance;
- connect technical evidence with operational decisions;
- ensure legal and policy compliance;
- identify and manage conflicts of interest;
- provide escalation routes for uncertainty, failure and disagreement;
- maintain traceability of consequential decisions;
- support rapid intervention during operational incidents;
- ensure changes trigger appropriate reassessment;
- preserve accountability throughout the AI lifecycle.

---

## 4. Governance Architecture

D-AIGAAF uses a layered governance architecture.

### Tier 1 — Strategic and Policy Governance

Provides strategic direction, policy, legal boundaries and enterprise-level priorities.

Primary responsibilities:

- define strategic objectives;
- establish policy and legal boundaries;
- determine enterprise risk appetite;
- establish governance standards;
- allocate strategic resources;
- oversee major capability portfolios.

### Tier 2 — Capability Governance

Governs the AI capability as a programme or operational capability.

Primary responsibilities:

- define capability objectives;
- establish ownership;
- manage requirements;
- oversee acquisition or development;
- ensure appropriate assurance;
- manage capability-level risk;
- ensure operational authorisation is sought where required.

### Tier 3 — System and Technical Governance

Governs the technical system, model, data, infrastructure and dependencies.

Primary responsibilities:

- maintain configuration baselines;
- manage model and system changes;
- maintain provenance;
- manage technical risk;
- conduct or support TEVV;
- manage cybersecurity and AI security;
- document limitations and dependencies.

### Tier 4 — Assurance Governance

Provides independent assessment of whether evidence supports the relevant assurance claims.

Primary responsibilities:

- review evidence;
- challenge assumptions;
- assess residual risk;
- identify evidence gaps;
- assess test and evaluation adequacy;
- provide independent assurance findings.

Assurance should remain organisationally and functionally independent from the team whose performance or capability it is assessing.

### Tier 5 — Operational Governance

Connects the AI capability to its actual mission, environment and authorised operational use.

Primary responsibilities:

- determine whether the capability is suitable for the operational context;
- ensure employment remains within the authorised operational envelope;
- monitor operational performance;
- manage operational risk;
- escalate incidents and emerging risks;
- exercise human authority over consequential decisions.

---

## 5. Key Governance Roles

The following roles form the core D-AIGAAF governance construct.

### 5.1 Strategic / Policy Authority

Provides strategic direction and establishes policy and legal boundaries.

The authority:

- establishes applicable policy;
- defines strategic priorities;
- determines enterprise-level governance requirements;
- establishes acceptable risk boundaries;
- ensures alignment with applicable law and national policy.

The Strategic / Policy Authority does not automatically possess operational authority over every AI capability.

---

### 5.2 Capability Owner / Sponsor

Owns the capability from a programme and capability-management perspective.

Responsibilities include:

- defining capability objectives;
- securing resources;
- ensuring requirements are established;
- ensuring appropriate assurance is conducted;
- ensuring unresolved risks are visible;
- ensuring the capability progresses through required governance gates;
- ensuring retirement is properly managed.

The Capability Owner does not substitute for the operational authorising authority.

---

### 5.3 System Owner / AI System Manager

Responsible for the technical system and its lifecycle.

Responsibilities include:

- system configuration;
- model and component provenance;
- technical documentation;
- change management;
- supplier and dependency management;
- system security;
- technical performance;
- maintenance;
- incident investigation;
- implementation of corrective actions.

The System Owner is responsible for the system but does not independently authorise its operational employment.

---

### 5.4 Operational Commander / Operational Authority

Holds the authority to determine whether an AI capability may be employed for a defined mission within a defined operational context, subject to applicable policy and delegated authority.

Responsibilities include:

- understanding the authorised operational envelope;
- ensuring employment remains within authorised boundaries;
- considering mission-specific risks;
- making or approving consequential operational decisions;
- exercising human authority;
- recording significant overrides or deviations where required;
- suspending employment when conditions invalidate the authorisation.

Operational authority remains human unless a specific alternative authority arrangement has been explicitly established and authorised.

---

### 5.5 Operational AI Advisor (OAIA)

The OAIA is a proposed D-AIGAAF working construct intended to bridge operational command, AI technical expertise, assurance and system ownership.

The OAIA provides commanders with operationally relevant advice on:

- AI capabilities and limitations;
- model uncertainty;
- operational context;
- autonomy implications;
- known failure modes;
- adversarial risks;
- changes in system behaviour;
- assurance evidence;
- implications of operating outside the authorised envelope.

The OAIA does **not** replace command authority.

> **OAIA advises; authorised human authority decides.**

The OAIA may recommend restriction, suspension, reassessment or fail-safe action where evidence indicates unacceptable risk.

---

### 5.6 Independent Assurance Function

Provides independent assessment of assurance claims and evidence.

Responsibilities include:

- reviewing TEVV evidence;
- challenging assurance claims;
- assessing evidence sufficiency;
- identifying evidence gaps;
- assessing residual risk;
- confirming whether limitations are adequately documented;
- recommending further testing or reassessment.

The assurance function should not be the sole authorising authority for operational employment.

---

### 5.7 TEVV Function

Conducts or manages testing, evaluation, verification and validation activities.

Responsibilities include:

- defining test objectives;
- executing approved test activities;
- assessing technical and operational performance;
- conducting adversarial and robustness testing where appropriate;
- documenting results;
- preserving reproducibility and traceability;
- identifying limitations and failure conditions.

TEVV evidence supports assurance; it does not by itself constitute operational authorisation.

---

### 5.8 AI Security Function

Addresses security risks specific to AI systems and their dependencies.

Responsibilities include:

- adversarial robustness;
- model and data integrity;
- supply-chain threats;
- compromise detection;
- prompt or input manipulation where relevant;
- model extraction or misuse where relevant;
- unauthorised behavioural modification;
- loss-of-control risks;
- security incident response.

---

### 5.9 Data / Information Owner

Responsible for the governance of data and information used by or produced by the AI capability.

Responsibilities include:

- data provenance;
- integrity;
- access control;
- classification and handling requirements;
- quality and suitability;
- retention;
- information-sharing constraints;
- identification of material data limitations.

Data integrity is treated as an operational assurance concern, not merely an information-management concern.

---

### 5.10 Legal / Policy Advisor

Provides advice on:

- applicable law;
- policy;
- authorities;
- restrictions;
- accountability;
- applicable rules governing the intended use;
- implications of changes in mission or operational context.

Legal and policy advice informs governance decisions but does not automatically replace operational or command authority.

---

### 5.11 Acquisition / Supply Chain Authority

Ensures that procurement and supplier relationships preserve the ability to assure and control the capability.

Responsibilities include:

- supplier assurance;
- provenance;
- contractual requirements;
- critical dependencies;
- update controls;
- intellectual-property and access considerations;
- sovereign capability considerations;
- rights required for independent testing and assurance.

---

### 5.12 Audit / Evidence Function

Maintains governance evidence and supports traceability.

Responsibilities include:

- maintaining decision records;
- preserving evidence;
- maintaining version history;
- supporting audits;
- tracking governance decisions;
- identifying missing or inconsistent records.

---

## 6. Separation of Responsibilities

D-AIGAAF requires appropriate separation between:

**Development → System Ownership → TEVV → Independent Assurance → Operational Authorisation**

The same individual or organisation should not control all stages where doing so would create an unacceptable conflict of interest.

In particular:

- system ownership does not equal assurance;
- assurance does not equal authorisation;
- technical expertise does not equal command authority;
- legal advice does not equal operational command;
- AI recommendation does not equal human decision;
- supplier assurance does not replace independent assurance.

---

## 7. Decision Rights

| Decision | Primary Authority | Required Inputs |
|---|---|---|
| Strategic AI policy | Strategic / Policy Authority | Strategy, law, risk |
| Capability requirement | Capability Owner / Sponsor | Mission need, user requirements |
| System configuration | System Owner | Technical assessment, change controls |
| TEVV scope | TEVV Function | Requirements, risk, intended use |
| Assurance conclusion | Independent Assurance Function | TEVV evidence, operational evidence |
| Operational employment | Operational Authorising Authority | Mission, risk, assurance, environment |
| Material change approval | Change Authority / Authorising Authority | Change assessment, revalidation evidence |
| Emergency protective action | Pre-authorised operational authority | Immediate risk, fail-safe conditions |
| Suspension | Operational / Authorising Authority | Incident, emerging risk, loss of control |
| Reauthorisation | Authorising Authority | Updated assurance and risk position |
| Retirement | Capability Owner + Authorising Authority | Lifecycle status, residual obligations |

The precise allocation of authority must be defined by the organisation implementing D-AIGAAF.

---

## 8. Governance and Operational Authorisation

Operational authorisation is a governance decision that binds:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Governance must therefore ensure that an authorisation decision identifies:

- the capability;
- the intended mission;
- the operational environment;
- the authorised autonomy level;
- the operational envelope;
- human authority requirements;
- supporting evidence;
- known limitations;
- applicable fail-safe and degradation mechanisms;
- configuration baseline;
- critical dependencies;
- authorising authority;
- review period;
- suspension triggers;
- revocation triggers;
- reauthorisation requirements.

No general statement that an AI system is "approved" should be interpreted as unlimited operational authority.

---

## 9. Escalation Model

Issues should escalate according to consequence, uncertainty and urgency.

A normal escalation pathway may be:

**Operator → Operational Commander → OAIA → System Owner / AI System Manager → Independent Assurance / TEVV → Authorising Authority**

The pathway may operate in parallel where an issue has legal, security, safety or mission-critical implications.

Escalation should be triggered by conditions such as:

- unexpected system behaviour;
- significant uncertainty;
- performance outside validated conditions;
- operation outside the authorised envelope;
- material configuration change;
- security compromise;
- suspected loss of control;
- unacceptable degradation;
- previously unknown failure mode;
- significant disagreement between technical and operational assessments.

---

## 10. Emergency and Fail-Safe Governance

Fail-safe mechanisms must be governed before deployment.

The normal decision pathway should allow concerns to move through:

**Developer / Technical Team → System Manager → OAIA → Operational Command / Authorising Authority**

However, emergency procedures must recognise that delay can itself create unacceptable harm.

Therefore:

- pre-authorised emergency actions should be defined where appropriate;
- personnel must know the conditions under which those actions may be taken;
- emergency actions must be logged;
- the capability should enter an appropriate safe, restricted or suspended state where required;
- post-incident review must determine whether the assurance and authorisation position remains valid.

Emergency authority must not become a mechanism for routine bypass of governance.

---

## 11. Governance by Consequence and Autonomy

Governance intensity should be proportional to risk.

Higher governance requirements should generally apply where an AI capability:

- can contribute directly to lethal or irreversible outcomes;
- can independently initiate consequential actions;
- operates with limited or delayed human intervention;
- operates in highly degraded or adversarial environments;
- affects critical infrastructure;
- supports strategic decision-making;
- can materially alter its own behaviour or critical configuration;
- presents significant loss-of-control potential.

A low-risk administrative AI capability should not be subjected to the same governance burden as an autonomous system capable of consequential action.

---

## 12. Governance Gates

Governance should operate through lifecycle decision gates.

Indicative gates are:

- **G0 — Strategic Need**
- **G1 — Mission Need and Use Case**
- **G2 — Requirements and Risk**
- **G3 — Acquisition / Development**
- **G4 — Design and Integration**
- **G5 — Configuration Baseline**
- **G6 — TEVV**
- **G7 — Operational Environment Assessment**
- **G8 — Assurance**
- **G9 — Operational Authorisation**
- **G10 — Continuous Assurance / Reauthorisation**
- **G11 — Retirement**

A capability should not progress merely because a technical milestone has been completed.

Progression requires the relevant governance questions to be answered and recorded.

---

## 13. Governance Records

Governance decisions should produce durable evidence.

Core records include:

### Defence AI Capability Register (DAICR)

Records what AI capabilities exist and their governance status.

### Defence AI Assurance Record (DAAR)

Records assurance claims, supporting evidence, limitations, gaps and conclusions.

### Defence AI Operational Authorisation (DAOA)

Records why, where, how and under what conditions operational employment is authorised.

### Operational Record

Records significant operational use, decisions, overrides, incidents and outcomes.

Additional records may include:

- risk assessments;
- TEVV records;
- change records;
- incident records;
- revalidation records;
- reauthorisation records;
- retirement records.

---

## 14. Decision Traceability

Every consequential governance decision should be traceable to:

**Authority → Decision → Evidence → Risk → Conditions → Accountability**

The Golden Thread provides the wider lifecycle trace:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

A governance decision that cannot be reconstructed should be treated as an evidence and accountability weakness.

---

## 15. Conflict of Interest

Governance arrangements should identify and manage conflicts of interest.

Examples include:

- a supplier assessing its own system without independent challenge;
- a system owner determining that its own system is operationally authorised;
- a programme team suppressing evidence of known limitations;
- operational pressure overriding unresolved safety or security concerns without documented authority;
- an assurance function becoming financially or organisationally dependent on the outcome it assesses.

Where independence cannot be absolute, compensating controls should be established and documented.

---

## 16. Disagreement and Dissent

D-AIGAAF recognises that technical, operational, legal and assurance stakeholders may reach different conclusions.

Disagreement should not be hidden through informal consensus.

Material disagreements should be:

1. documented;
2. supported by evidence where possible;
3. escalated to the appropriate authority;
4. resolved through an explicit decision;
5. retained as part of the governance record where consequential.

A dissenting professional assessment should not automatically prevent a decision, but it should not disappear from the evidence base.

---

## 17. Continuous Governance

Governance does not end at operational authorisation.

The governance position must be reconsidered when:

- system behaviour changes;
- the model changes;
- data sources change materially;
- critical dependencies change;
- the operational environment changes;
- the mission changes;
- autonomy changes;
- new vulnerabilities emerge;
- incidents occur;
- new evidence changes the risk assessment;
- previously unknown failure modes are discovered.

This reflects the D-AIGAAF principle:

> **Change does not preserve authority automatically.**

---

## 18. Relationship Between Governance and Assurance

Governance determines **who decides and under what authority**.

Assurance determines **what the available evidence supports**.

Operational authorisation determines **whether the capability may be employed under specified conditions**.

These functions must remain conceptually distinct:

**Evidence → Assurance → Authority**

A strong assurance conclusion does not automatically authorise operational employment.

Likewise, operational authority should not be used as a substitute for missing assurance evidence.

---

## 19. Relationship With the Operational AI Advisor

The OAIA exists to reduce the gap between:

**AI Technical Understanding ↔ Operational Understanding ↔ Command Decision-Making**

The OAIA should help commanders understand:

- what the system can do;
- what it cannot reliably do;
- where uncertainty exists;
- where the evidence is weak;
- how operational context affects system performance;
- whether observed behaviour remains within the expected envelope;
- whether escalation, restriction or reassessment is warranted.

The OAIA remains an advisory role.

It does not create an additional layer of command authority unless an implementing organisation explicitly establishes such authority.

---

## 20. Governance Accountability Model

D-AIGAAF uses the following conceptual accountability chain:

**Strategic Authority**
→ establishes policy and strategic direction

**Capability Owner**
→ ensures the capability is developed and governed

**System Owner**
→ maintains the technical capability and configuration

**TEVV**
→ produces and documents evidence

**Independent Assurance**
→ evaluates whether evidence supports assurance claims

**OAIA**
→ translates AI and assurance implications into operational advice

**Operational Authority**
→ decides whether and how the capability may be employed

**Operators / Users**
→ employ the capability within authorised boundaries

**Audit / Evidence Function**
→ preserves traceability and organisational learning

No role should be assumed to inherit another role's authority merely because it possesses technical expertise or organisational seniority.

---

## 21. Minimum Governance Requirements

Every consequential D-AIGAAF capability should have, at minimum:

- a named capability owner;
- a named system owner;
- a defined operational authority;
- identified assurance responsibility;
- defined TEVV responsibility;
- identified AI security responsibility;
- identified legal/policy support;
- defined data/information responsibility;
- an operational AI advisory function where warranted by risk;
- documented escalation pathways;
- documented emergency procedures;
- defined authorisation boundaries;
- traceable governance records.

The precise organisational implementation may differ, but the underlying responsibilities should remain identifiable.

---

## 22. Governance Principles

This Governance Model operationalises principles established in `00 Framework/Principles.md`, including:

- Primacy of Command Authority
- No Authority Beyond Law and Policy
- No Silent Expansion of Authority
- Conditional Operational Authority
- No Authority Without Evidence
- Assurance Does Not Equal Authorisation
- Mission- and Context-Dependent Assurance
- Meaningful Human Control
- Traceable Human Authority
- Qualified Human Authority
- AI Must Not Displace Accountability
- Autonomy Must Be Explicitly Defined
- Autonomy Must Be Matched to Consequence
- AI Shall Not Self-Expand Its Authority
- Continuous Assurance
- Procurement Must Preserve Assurance
- Supplier Assurance Does Not Replace Independent Assurance
- Behaviour Determines Change Significance
- Change Does Not Preserve Authority Automatically
- Incident Changes the Assurance Position
- OAIA Advises; Authority Decides
- Accountability Must Be Explicit
- Governance Must Follow the Lifecycle
- Cross-Functional Governance

---

## 23. Relationship With Other D-AIGAAF Modules

This document provides the governance foundation for the numbered modules that follow.

It should be read with:

- `00 Framework/Reference Model.md`
- `00 Framework/Principles.md`
- `00 Framework/Terminology.md`
- `00 Framework/Lifecycle.md`
- `00 Framework/Golden Thread.md`

Governance requirements are implemented and elaborated through:

- `03 Risk & Autonomy`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
- `17 Workforce`
- `21 Legal & Policy`
- `22 Acquisition & Procurement`
- `23 Interoperability & Coalition`
- `27 Implementation`

The numbered modules are not intended to imply that governance occurs sequentially. Governance is continuous and cross-cutting.

---

## 24. Implementation Principle

D-AIGAAF is deliberately organisationally agnostic.

It does not prescribe a single military command structure, ministry structure, procurement model or institutional arrangement.

Instead, it specifies the **functions and decision rights that must be identifiable**.

An implementing organisation may combine or separate roles according to its structure, provided that:

- accountability remains clear;
- authority remains legitimate;
- assurance remains appropriately independent;
- operational decisions remain traceable;
- conflicts of interest are controlled;
- escalation remains effective.

---

## 25. Summary

The D-AIGAAF Governance Model establishes a simple proposition:

> **AI governance in defence is ultimately a question of authority, accountability and evidence.**

Technical excellence alone is insufficient.

A defence AI capability must have:

**A legitimate mission → a defined owner → defined authority → appropriate testing → independent assurance → explicit operational conditions → accountable human decision-making → continuous governance.**

The objective is not to eliminate operational risk.

The objective is to ensure that risk is:

- understood;
- evidenced;
- controlled;
- accepted by the appropriate authority;
- continuously reassessed;
- and never allowed to become invisible through organisational ambiguity.

---

**Status:** Working Draft v0.1  
**Next review:** Following development of Risk & Autonomy, Human Authority and Operational Authorisation modules.
