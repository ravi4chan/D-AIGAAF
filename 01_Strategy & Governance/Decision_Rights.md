# D-AIGAAF — Decision Rights

**Document:** Decision Rights  
**Framework:** D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework  
**Status:** Working Draft v0.1  
**Classification:** Generic / Unclassified

---

## 1. Purpose

This document defines the decision rights required to govern, assure, authorise and employ defence AI capabilities.

The purpose is to ensure that consequential decisions are:

- made by an appropriately authorised human or authority;
- based on relevant evidence;
- within defined legal and policy boundaries;
- traceable to the applicable risk and assurance position;
- assigned to a clearly accountable role.

Decision rights are distinct from organisational rank, technical expertise and administrative responsibility.

---

## 2. Core Principle

The central D-AIGAAF rule is:

> **Authority to perform a function does not automatically confer authority to make every decision associated with that function.**

For example:

- a developer may modify a model but cannot automatically authorise its operational use;
- a system owner may approve a technical configuration but cannot automatically accept operational risk;
- an assurance team may conclude that evidence supports an assurance claim but cannot automatically authorise employment;
- an OAIA may recommend restriction or suspension but does not automatically exercise command authority;
- an operator may use an authorised capability but cannot expand its authorised mission or autonomy.

---

## 3. Decision Rights Architecture

D-AIGAAF separates decision rights into seven broad categories:

1. **Strategic decisions**
2. **Capability decisions**
3. **Technical decisions**
4. **Assurance decisions**
5. **Operational authorisation decisions**
6. **Emergency and incident decisions**
7. **Lifecycle and change decisions**

The same organisation may hold multiple categories of authority, but the specific decision rights must remain explicit.

---

## 4. Strategic Decision Rights

### 4.1 Strategic AI Policy

The Strategic / Policy Authority may:

- establish enterprise AI policy;
- define strategic objectives;
- establish governance requirements;
- establish enterprise risk appetite;
- determine strategic priorities;
- approve major governance changes.

It should not be assumed to have authority over tactical employment of individual AI capabilities unless that authority is explicitly delegated.

### 4.2 Strategic Risk Acceptance

Strategic authorities may accept risks that fall within their delegated authority.

They should not accept risks that exceed:

- legal authority;
- policy boundaries;
- delegated powers;
- established risk appetite.

Where a risk exceeds delegated authority, it must be escalated.

---

## 5. Capability Decision Rights

### 5.1 Capability Definition

The Capability Owner / Sponsor may:

- define capability objectives;
- propose intended missions;
- establish programme priorities;
- approve capability requirements within delegated authority;
- allocate programme resources.

### 5.2 Capability Scope

Changes to the intended purpose of a capability must trigger assessment of:

- mission impact;
- risk;
- autonomy;
- assurance;
- operational authorisation.

A capability should not silently acquire additional missions merely because the underlying technical system can perform them.

---

## 6. Technical Decision Rights

### 6.1 System Configuration

The System Owner / AI System Manager may approve technical changes within the approved change-control process.

This includes:

- configuration changes;
- maintenance;
- approved software changes;
- approved data changes;
- infrastructure changes;
- dependency updates.

### 6.2 Model Changes

Model changes must be classified according to their potential effect on behaviour.

A change may be considered minor only where evidence demonstrates that it does not materially affect:

- model behaviour;
- performance;
- security;
- autonomy;
- operational envelope;
- mission effectiveness;
- known limitations.

Where a change may materially affect these areas, revalidation and potentially reauthorisation are required.

### 6.3 Technical Risk

The System Owner may identify, assess and mitigate technical risk.

The System Owner should not independently accept operational risk that exceeds their delegated authority.

---

## 7. TEVV Decision Rights

The TEVV function has decision rights over the conduct and integrity of approved testing and evaluation activities.

It may:

- define test procedures within approved scope;
- execute tests;
- reject invalid test results;
- identify test limitations;
- recommend additional testing;
- report failure to meet requirements.

TEVV should not modify evidence to obtain a desired governance outcome.

A test result that demonstrates poor performance remains valid evidence even when the result is inconvenient to the programme.

---

## 8. Assurance Decision Rights

The Independent Assurance Function may:

- assess whether evidence supports assurance claims;
- identify evidence gaps;
- challenge assumptions;
- assess residual risk;
- recommend additional evidence;
- issue an assurance conclusion within its remit.

The assurance function should have the authority to state:

- evidence is sufficient;
- evidence is insufficient;
- evidence is contradictory;
- uncertainty remains material;
- further testing is required.

### 8.1 Assurance Does Not Equal Authorisation

An assurance conclusion does not itself create operational authority.

The distinction is:

**TEVV → Evidence**

**Assurance → Interpretation of Evidence**

**Authorisation → Decision to Permit Operational Employment**

---

## 9. Operational Decision Rights

### 9.1 Operational Employment

The Operational Authorising Authority decides whether an AI capability may be employed:

- for a specified mission;
- in a specified environment;
- at a specified autonomy level;
- under specified human authority;
- within specified operational constraints.

### 9.2 Operational Restrictions

The Operational Authority may impose restrictions including:

- limiting mission scope;
- limiting geographical or environmental use;
- reducing autonomy;
- requiring additional human confirmation;
- restricting data sources;
- requiring additional monitoring;
- limiting duration of employment.

### 9.3 Operational Suspension

Where the capability no longer satisfies the conditions under which it was authorised, the appropriate operational authority may suspend employment.

Suspension may be triggered by:

- unexpected behaviour;
- material degradation;
- security compromise;
- loss of control;
- changed operational conditions;
- evidence of a previously unknown failure mode;
- material change in system configuration;
- inability to maintain required human control.

---

## 10. Human Authority

Human authority must be explicitly defined for consequential AI capabilities.

The responsible human must know:

- what the AI is authorised to do;
- what the human must approve;
- what the human may override;
- when intervention is mandatory;
- what conditions require suspension;
- who holds higher authority;
- how decisions are recorded.

Human presence alone is not sufficient.

> **Human presence ≠ human control.**

---

## 11. AI Recommendations and Human Decisions

An AI-generated recommendation does not become a command merely because:

- it is technically sophisticated;
- it is highly confident;
- it has historically performed well;
- multiple systems produce the same recommendation;
- the recommendation is presented through a military command interface.

The decision-maker remains responsible for exercising the authority assigned to them.

Where required by the applicable governance regime, significant decisions should record:

- the AI recommendation;
- relevant uncertainty;
- human decision;
- decision rationale;
- significant override or deviation.

---

## 12. Operational AI Advisor Decision Rights

The OAIA is an advisory role.

The OAIA may:

- interpret AI behaviour;
- explain technical limitations;
- advise on uncertainty;
- advise on operational risk;
- recommend restriction;
- recommend suspension;
- recommend further testing;
- recommend escalation;
- advise on whether observed conditions remain within the authorised envelope.

The OAIA does not automatically possess:

- command authority;
- legal authority;
- operational authorisation authority;
- authority to accept strategic risk.

Where an organisation assigns the OAIA additional authority, that authority must be explicitly defined.

---

## 13. Risk Acceptance Rights

Risk acceptance must correspond to the level and consequence of the risk.

A conceptual hierarchy is:

**Operator / User**
→ routine risks within authorised procedures

**Operational Commander**
→ operational risks within delegated authority

**Authorising Authority**
→ risks associated with operational authorisation

**Strategic / Enterprise Authority**
→ risks exceeding lower-level delegated authority

The exact hierarchy is organisation-specific.

No individual should accept a risk merely because they are the most senior person present if the decision exceeds their legal or delegated authority.

---

## 14. Autonomy Decision Rights

Autonomy must be explicitly authorised.

A capability may not increase its autonomy merely because:

- technical functionality exists;
- operators permit it informally;
- mission pressure increases;
- communications degrade;
- a software update enables additional functions.

Any increase in consequential autonomy should trigger appropriate assessment of:

- risk;
- human control;
- assurance evidence;
- operational environment;
- authorisation.

---

## 15. Decision Rights for Use Outside the Authorised Envelope

Use outside the authorised operational envelope should normally be prohibited unless an applicable emergency authority explicitly permits it.

Examples include:

- new mission;
- new environment;
- increased autonomy;
- new target or decision class;
- materially different data;
- degraded communications;
- materially changed threat environment.

Where emergency action is permitted, the decision must be recorded and followed by appropriate review.

---

## 16. Emergency Decision Rights

Emergency governance must balance two risks:

1. harm caused by the AI capability continuing to operate; and
2. harm caused by delaying intervention.

Pre-authorised emergency procedures should therefore define:

- who may act;
- under what conditions;
- what actions are permitted;
- what safe state should be entered;
- what must be recorded;
- who must be informed;
- when post-incident review is mandatory.

### 16.1 Immediate Protective Action

Where delay could create unacceptable harm, a designated authority may take immediate protective action within the pre-authorised emergency procedure.

This may include:

- reducing autonomy;
- restricting functions;
- isolating the system;
- placing the system in a safe state;
- suspending operational use;
- activating a fail-safe mechanism.

The action should subsequently be reviewed through the normal governance process.

---

## 17. Fail-Safe Decision Rights

Fail-safe mechanisms should have clearly defined activation authority.

The governance design should specify:

- who can activate the mechanism;
- whether activation is automatic, human-initiated or both;
- what triggers activation;
- what system state follows activation;
- whether operational authority is suspended;
- who can restore the capability;
- what evidence is required before restoration.

Restoration of a suspended capability should not be treated as an administrative reset.

It should be based on an updated assessment of the reason for suspension.

---

## 18. Incident Decision Rights

Following an incident, the responsible authority should determine whether to:

- continue operation;
- restrict operation;
- suspend operation;
- revoke authorisation;
- initiate investigation;
- require additional TEVV;
- require revalidation;
- require reauthorisation.

The decision should consider:

- severity;
- recurrence potential;
- uncertainty;
- affected operational conditions;
- whether the incident reveals a previously unknown failure mode;
- whether the underlying assurance case remains valid.

---

## 19. Change Decision Rights

Changes should be classified according to behaviour and operational effect, not merely according to administrative size.

A change authority should determine whether a change is:

### Minor Change

A change supported by evidence showing no material effect on the authorised capability.

### Significant Change

A change that may affect:

- model behaviour;
- mission effectiveness;
- security;
- autonomy;
- human control;
- operational envelope;
- risk;
- assurance.

Significant changes should trigger appropriate revalidation and potentially reauthorisation.

---

## 20. Reauthorisation Decision Rights

Reauthorisation is required when the existing authority no longer adequately reflects the capability, evidence or operational context.

Triggers may include:

- material system change;
- increased autonomy;
- new mission;
- new operational environment;
- significant incident;
- changed threat conditions;
- material assurance gap;
- expiry of authorisation;
- discovery of previously unknown limitations.

The authorising authority must decide whether the updated evidence supports continued or modified operational authority.

---

## 21. Revocation and Retirement

### Revocation

The appropriate authority may revoke operational authority when:

- the capability cannot meet required conditions;
- assurance is no longer adequate;
- critical controls fail;
- loss of control is suspected;
- legal or policy authority changes;
- continued employment presents unacceptable risk.

### Retirement

Retirement ends the capability's authorised operational status.

Retirement decisions should address:

- withdrawal of operational authority;
- removal or restriction of access;
- data and model disposition;
- retention of required evidence;
- contractual obligations;
- residual security risks;
- lessons learned.

> **Retirement must remove authority, not merely stop routine use.**

---

## 22. Decision Matrix

| Decision | Primary Decision Right | Assurance / Technical Input | Operational Input |
|---|---|---|---|
| Strategic AI policy | Strategic / Policy Authority | Advisory | Advisory |
| Capability objective | Capability Owner | Technical input | User input |
| System design | System Owner | TEVV input | Operational requirements |
| Technical configuration | System Owner | As required | As required |
| Test scope | TEVV Function | Assurance input | Operational requirements |
| Assurance conclusion | Independent Assurance | TEVV evidence | Operational evidence |
| Risk treatment | Appropriate risk authority | Assurance input | Operational input |
| Operational authorisation | Authorising Authority | Required | Required |
| Autonomy level | Authorising Authority | Required | Required |
| Operational restriction | Operational Authority | Advisory | Primary |
| Emergency protective action | Pre-authorised authority | Advisory where feasible | Primary |
| Fail-safe activation | Designated authority / mechanism | Technical input | Operational input |
| Material change classification | Change Authority | Technical + assurance | Operational input |
| Revalidation decision | Assurance / Authorising Authority | Required | Required |
| Reauthorisation | Authorising Authority | Required | Required |
| Suspension | Operational / Authorising Authority | Required where feasible | Primary |
| Revocation | Authorising Authority | Required | Required |
| Retirement | Capability + Authorising Authority | Required | Required |

---

## 23. Decision Escalation

A decision should escalate when:

- the decision exceeds delegated authority;
- consequence exceeds the decision-maker's risk acceptance level;
- evidence is insufficient;
- uncertainty is material;
- technical and operational assessments conflict;
- legal or policy interpretation is uncertain;
- the capability operates outside its authorised envelope;
- an incident changes the assurance position;
- a material change has occurred;
- loss of control is suspected.

Escalation should never be used simply to transfer accountability without transferring appropriate decision authority.

---

## 24. Decision Traceability

Every consequential decision should be reconstructable from:

**Decision Maker → Authority → Decision → Evidence → Risk → Conditions → Outcome**

Where relevant, the decision record should also identify:

- AI recommendation;
- human decision;
- reason for override;
- applicable authorisation;
- system configuration;
- operational environment;
- relevant warnings or uncertainty;
- subsequent outcome.

This provides the decision component of the D-AIGAAF Golden Thread.

---

## 25. No Silent Delegation

Decision authority must not be inferred from:

- organisational hierarchy alone;
- system access privileges;
- possession of a technical account;
- physical control of equipment;
- informal practice;
- previous authorisations;
- historical custom.

Delegation should be:

- explicit;
- documented;
- bounded;
- revocable;
- appropriate to the consequence of the decision.

---

## 26. Decision Rights and Accountability

Decision rights and accountability must remain aligned.

The framework distinguishes:

**Responsible** — performs the activity.

**Accountable** — owns the outcome or decision.

**Consulted** — provides relevant expertise.

**Informed** — must be notified.

A person may be responsible for an action without being accountable for a decision they were not authorised to make.

Conversely, an authority cannot delegate accountability simply by delegating execution.

---

## 27. Minimum Decision Rights Register

Each consequential AI capability should maintain a Decision Rights Register containing, at minimum:

- decision;
- decision authority;
- delegated authority;
- conditions;
- required evidence;
- required consultation;
- escalation threshold;
- recording requirement;
- review requirement.

The register should be linked to the relevant capability, risk assessment and operational authorisation.

---

## 28. Governance Failure Modes

D-AIGAAF identifies the following decision-rights failure modes:

### 28.1 Authority Ambiguity

No one knows who is authorised to decide.

### 28.2 Authority Overreach

A person exercises authority beyond their delegation.

### 28.3 Authority Gap

A consequential decision is required but no authority has been assigned.

### 28.4 Authority Drift

Informal practice gradually expands the scope of authority.

### 28.5 Authority by Technology

System permissions are mistaken for legitimate decision authority.

### 28.6 Authority by Seniority

Organisational seniority is assumed to override specific delegated authority.

### 28.7 Assurance-Authorisation Confusion

Assurance is incorrectly treated as operational approval.

### 28.8 AI Authority Confusion

An AI recommendation is treated as though it were a human command decision.

### 28.9 Emergency Normalisation

Emergency procedures become a routine method for bypassing governance.

### 28.10 Accountability Displacement

Responsibility for a consequential outcome is incorrectly attributed to the AI rather than the human and organisational authorities responsible for its deployment and use.

---

## 29. Relationship With the Golden Thread

Decision rights form a critical link in the Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

The **Authority** stage must identify:

- who decided;
- what they were authorised to decide;
- what evidence they relied upon;
- what conditions applied;
- what accountability they accepted.

This prevents operational authority from becoming disconnected from the evidence and risk that justified it.

---

## 30. Relationship With Other Modules

This document should be read with:

- `00 Framework/Reference Model.md`
- `00 Framework/Principles.md`
- `00 Framework/Terminology.md`
- `00 Framework/Lifecycle.md`
- `00 Framework/Golden Thread.md`
- `01 Strategy & Governance/Governance Model.md`

Detailed implementation is developed further in:

- `03 Risk & Autonomy`
- `08 Human Authority`
- `09 TEVV`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
- `21 Legal & Policy`
- `22 Acquisition & Procurement`

---

## 31. Summary

D-AIGAAF treats decision rights as a fundamental component of safe and accountable defence AI governance.

The core logic is:

> **The capability may inform a decision, but legitimate authority must determine who may make the decision, under what conditions, using what evidence, and with what accountability.**

The framework therefore seeks to ensure:

**Clear authority → appropriate evidence → bounded decision → traceable accountability → continuous review**

No consequential AI capability should rely on assumed, inherited or informal authority.

---

**Status:** Working Draft v0.1  
**Next review:** Following development of Risk & Autonomy, Human Authority and Operational Authorisation modules.
