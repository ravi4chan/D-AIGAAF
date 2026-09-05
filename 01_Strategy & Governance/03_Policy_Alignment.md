# D-AIGAAF — Policy Alignment

**Document:** Policy Alignment  
**Framework:** D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework  
**Status:** Working Draft v0.1  
**Classification:** Generic / Unclassified

---

## 1. Purpose

This document defines how D-AIGAAF should align with applicable law, policy, doctrine, standards, organisational directives and existing AI governance frameworks.

D-AIGAAF is intended to operate as a **defence-specific operational governance layer**.

It does not replace:

- national law;
- international law;
- defence policy;
- military doctrine;
- service regulations;
- information-security policy;
- acquisition rules;
- safety regulations;
- existing AI governance frameworks;
- applicable technical standards.

Instead, D-AIGAAF provides a structured mechanism for translating those requirements into operational governance, assurance and authorisation decisions.

---

## 2. Policy Alignment Principle

The fundamental rule is:

> **D-AIGAAF authority cannot exceed the legal, policy and delegated authority of the organisation implementing it.**

Where a D-AIGAAF requirement conflicts with applicable law or higher-level policy, the higher-level requirement prevails.

Where existing policy is less specific than the operational problem, D-AIGAAF may provide additional governance controls without weakening the underlying legal or policy requirement.

---

## 3. Policy Hierarchy

An implementing organisation should establish the hierarchy applicable to its jurisdiction and institutional structure.

A conceptual hierarchy is:

```text
Applicable Law
      ↓
National / Government Policy
      ↓
Defence Policy
      ↓
Military Doctrine and Directives
      ↓
Service / Organisational Regulations
      ↓
Capability-Specific Policy
      ↓
D-AIGAAF Governance Requirements
      ↓
System / Mission Procedures
```

The exact hierarchy is organisation-specific.

D-AIGAAF should always operate within the highest applicable authority.

---

## 4. Types of External Requirements

Policy alignment should consider at least the following categories.

### 4.1 Legal Requirements

Includes applicable:

- national law;
- international law;
- treaty obligations;
- regulations;
- statutory requirements;
- rules governing the use of force;
- data and information law;
- procurement law;
- applicable liability regimes.

### 4.2 Government Policy

Includes:

- national AI policy;
- national security policy;
- defence policy;
- technology policy;
- data policy;
- cybersecurity policy;
- sovereign capability policy.

### 4.3 Military Doctrine

Includes:

- command doctrine;
- operational doctrine;
- rules governing authority;
- safety doctrine;
- force employment doctrine;
- service-specific doctrine.

### 4.4 Organisational Directives

Includes:

- internal governance policies;
- security procedures;
- acquisition procedures;
- risk-management requirements;
- safety procedures;
- information-management rules.

### 4.5 Standards and Frameworks

May include relevant:

- AI governance frameworks;
- risk-management frameworks;
- cybersecurity standards;
- software engineering standards;
- systems engineering standards;
- safety standards;
- testing and evaluation standards;
- quality-management standards.

---

## 5. D-AIGAAF as a Defence Operational Layer

Many existing AI governance frameworks address broad topics such as:

- responsible AI;
- risk management;
- trustworthy AI;
- privacy;
- cybersecurity;
- lifecycle governance;
- organisational accountability.

D-AIGAAF builds on these concepts but focuses specifically on the operational question:

> **Can this AI capability be trusted to perform this mission, under these conditions, at this level of autonomy, with this level of human authority?**

The framework therefore connects external requirements to:

**Mission → Risk → Assurance → Authority → Employment**

---

## 6. No Legal Authority by Framework Adoption

Adopting D-AIGAAF does not itself create:

- command authority;
- legal authority;
- authority to use force;
- authority to access information;
- authority to process restricted information;
- procurement authority;
- risk acceptance authority.

Those authorities must come from applicable law, policy, regulation or explicit delegation.

---

## 7. Policy-to-Control Translation

External requirements should be translated into operationally meaningful controls.

The conceptual chain is:

**External Requirement**
→ **D-AIGAAF Requirement**
→ **Control**
→ **Verification / Testing**
→ **Evidence**
→ **Assurance**
→ **Operational Condition**
→ **Authorisation**

This prevents policy statements from remaining disconnected from actual system behaviour and operational employment.

---

## 8. Policy Traceability

Every material policy requirement should be traceable to its implementation.

A Policy Traceability Record should identify:

- source;
- source authority;
- requirement;
- interpretation;
- D-AIGAAF control;
- responsible owner;
- verification method;
- evidence;
- applicable capability;
- applicable mission;
- review date.

Where a requirement cannot be implemented directly, the reason should be documented.

---

## 9. Policy Interpretation

Policy language may be ambiguous or open to interpretation.

Where interpretation materially affects:

- risk;
- authority;
- autonomy;
- human control;
- operational employment;
- accountability;

the interpretation should be documented.

The record should identify:

- the original requirement;
- the interpretation adopted;
- the basis for interpretation;
- the responsible legal or policy authority;
- any conditions or limitations.

---

## 10. Legal and Policy Review

Legal or policy review should be proportionate to consequence.

Enhanced review should be considered where AI capability:

- contributes to consequential decisions;
- supports or influences use-of-force decisions;
- operates with significant autonomy;
- processes sensitive information;
- affects protected persons or civilian populations;
- operates across jurisdictions;
- affects critical infrastructure;
- introduces novel forms of operational authority.

Legal and policy review should occur before operational authorisation where required.

---

## 11. Rules Governing Use of Force

Where an AI capability may contribute to decisions or actions involving the use of force, the implementing organisation must identify the applicable legal, policy and command requirements.

D-AIGAAF does not itself determine whether a particular use of force is lawful.

Instead, it requires the governance process to establish:

- applicable authority;
- decision rights;
- human control requirements;
- operational limitations;
- assurance requirements;
- escalation procedures;
- accountability;
- recording requirements.

The capability must not be treated as possessing authority simply because it can technically perform an action.

---

## 12. Human Authority and Policy Alignment

Policy alignment must address the human role explicitly.

The governance process should identify:

- who has decision authority;
- who may approve an AI recommendation;
- who may override the AI;
- who may suspend the system;
- who may authorise increased autonomy;
- who may accept residual risk;
- who must review incidents.

Where law or policy requires human judgement, D-AIGAAF should ensure that the system design and operational procedures preserve the required human authority.

---

## 13. Autonomy and Policy

Autonomy must be considered within the applicable legal and policy framework.

The fact that a system can technically operate autonomously does not establish that it may legally or operationally do so.

Before increasing autonomy, the implementing organisation should assess:

- applicable law;
- policy restrictions;
- command authority;
- consequence;
- human control;
- assurance evidence;
- operational environment;
- reversibility;
- fail-safe capability.

---

## 14. Data and Information Policy

AI capabilities may depend on large volumes of data and information.

Policy alignment should therefore consider:

- data ownership;
- access authority;
- classification;
- handling restrictions;
- retention;
- sharing;
- provenance;
- integrity;
- privacy where applicable;
- cross-border transfer;
- third-party access;
- deletion and disposal.

Data may be technically accessible while still being legally or operationally restricted.

---

## 15. Cybersecurity and AI Security Policy

D-AIGAAF should align AI security requirements with the organisation's existing cybersecurity governance.

Where AI-specific threats are not adequately addressed by existing controls, additional controls may be required.

Relevant areas include:

- model integrity;
- training-data integrity;
- adversarial manipulation;
- unauthorised model modification;
- supply-chain compromise;
- malicious inputs;
- model theft;
- prompt or interface manipulation where relevant;
- unauthorised autonomous behaviour;
- loss of control.

Existing cybersecurity compliance should not automatically be treated as sufficient AI security assurance.

---

## 16. Acquisition and Procurement Policy

Policy alignment should continue into acquisition.

Procurement requirements should address, where relevant:

- supplier transparency;
- provenance;
- audit rights;
- testing rights;
- access to relevant technical information;
- update controls;
- change notification;
- vulnerability disclosure;
- dependency management;
- data rights;
- model rights;
- security requirements;
- termination and transition;
- sovereign capability requirements.

A contract should not unintentionally prevent the organisation from independently assuring or controlling a consequential AI capability.

---

## 17. Supplier Policy and Accountability

Supplier involvement does not eliminate government or military accountability.

Where an external organisation develops or operates part of an AI capability:

- supplier responsibilities should be explicit;
- government responsibilities should remain explicit;
- critical dependencies should be identified;
- assurance responsibilities should be defined;
- change notification requirements should be established;
- incident reporting should be governed.

> **Supplier responsibility is not a substitute for operational accountability.**

---

## 18. Policy and Supply-Chain Sovereignty

Where policy requires sovereign or trusted capability, D-AIGAAF should identify dependencies that could materially affect:

- system behaviour;
- availability;
- security;
- update mechanisms;
- access to evidence;
- operational control;
- continuity of service.

Sovereignty should be assessed as a governance and risk issue rather than treated solely as an acquisition preference.

---

## 19. Policy Alignment With Existing AI Frameworks

D-AIGAAF should be designed to interoperate with established AI governance frameworks rather than require organisations to abandon them.

Potential areas of alignment include:

| Existing Framework Area | D-AIGAAF Application |
|---|---|
| AI risk management | Defence-specific operational risk |
| Responsible AI | Human authority and accountability |
| AI lifecycle governance | Defence AI lifecycle |
| Trustworthy AI | Operational assurance |
| Cybersecurity | AI security and resilience |
| Safety engineering | Consequence and fail-safe governance |
| Quality management | Evidence and configuration control |
| Systems engineering | Requirements and traceability |
| Testing and evaluation | Defence TEVV |
| Governance | Operational authorisation |

The exact mapping should be developed in `19 Crosswalks`.

---

## 20. No Framework Substitution

D-AIGAAF should not be presented as a replacement for established frameworks.

A mature implementation may use multiple frameworks simultaneously.

For example:

```text
Law / Policy
      +
Enterprise AI Governance
      +
Cybersecurity
      +
Safety / Systems Engineering
      +
D-AIGAAF
      ↓
Defence AI Operational Governance
```

The purpose is integration, not unnecessary duplication.

---

## 21. Policy Conflicts

Where requirements conflict, the conflict should be identified rather than resolved informally.

The governance process should determine:

1. which requirement has higher authority;
2. whether the requirements can be reconciled;
3. whether a formal exemption exists;
4. who has authority to approve the deviation;
5. what compensating controls are required;
6. how the decision is recorded.

No programme should quietly choose the least restrictive interpretation.

---

## 22. Policy Exceptions and Waivers

An implementing organisation may establish controlled mechanisms for exceptions or waivers.

A waiver should identify:

- requirement being waived;
- reason;
- duration;
- affected capability;
- risk introduced;
- compensating controls;
- approving authority;
- review date;
- expiry condition.

A waiver should not silently become permanent policy.

---

## 23. Policy Change Management

Changes in law, policy or doctrine can invalidate existing governance assumptions.

A policy change should therefore trigger assessment of affected:

- capabilities;
- risk assessments;
- controls;
- assurance claims;
- operational authorisations;
- procurement arrangements;
- training;
- procedures.

Where the change materially affects operational authority, reauthorisation may be required.

---

## 24. Policy Horizon Scanning

Organisations implementing D-AIGAAF should maintain awareness of relevant changes in:

- legislation;
- national AI policy;
- defence policy;
- international obligations;
- standards;
- technical guidance;
- cybersecurity requirements;
- procurement rules;
- operational doctrine.

Horizon scanning should focus on changes that could materially affect the governance or authorisation of existing capabilities.

---

## 25. Policy Evidence

Policy compliance should be supported by evidence.

Examples include:

- legal review;
- policy mapping;
- signed approvals;
- delegated authority records;
- technical controls;
- test results;
- assurance findings;
- training records;
- audit records;
- operational procedures.

A policy statement without evidence of implementation should not automatically be treated as a satisfied control.

---

## 26. Policy Alignment and the Golden Thread

Policy alignment contributes to the Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change / Incident → Reauthorisation**

External legal and policy requirements should be traceable into the relevant:

- requirements;
- controls;
- evidence;
- assurance claims;
- authorisation conditions.

This ensures that policy remains connected to operational behaviour.

---

## 27. Policy Alignment Records

A mature D-AIGAAF implementation should maintain, as appropriate:

### Policy Register

Identifies applicable laws, policies, directives and standards.

### Policy Traceability Record

Maps requirements to D-AIGAAF controls.

### Legal / Policy Assessment

Records relevant interpretation and conclusions.

### Exception / Waiver Record

Records approved deviations.

### Policy Change Record

Records changes affecting existing capabilities.

These records should connect to the DAICR, DAAR and DAOA where relevant.

---

## 28. Responsibilities

### Strategic / Policy Authority

- establishes applicable policy;
- approves strategic interpretations where required;
- defines policy boundaries.

### Legal / Policy Advisor

- interprets applicable requirements;
- identifies legal and policy constraints;
- advises governance authorities.

### Capability Owner

- ensures applicable requirements are incorporated into capability governance.

### System Owner

- implements applicable technical and procedural controls.

### Independent Assurance Function

- evaluates whether evidence demonstrates implementation.

### Operational Authority

- ensures operational employment remains within applicable authority.

### Audit / Evidence Function

- preserves traceability.

---

## 29. Policy Alignment Failure Modes

### Policy Blindness

Relevant legal or policy requirements are not identified.

### Policy-to-Control Gap

A requirement exists but has not been translated into an operational control.

### Compliance by Assertion

Compliance is claimed without evidence.

### Policy Drift

Operational practice gradually diverges from governing requirements.

### Informal Interpretation

Material policy interpretations are made without documentation.

### Conflicting Requirement Suppression

Conflicts between requirements are hidden rather than resolved.

### Waiver Normalisation

Temporary exceptions become permanent operating practice.

### Supplier Policy Gap

Contractual arrangements prevent effective assurance or control.

### Outdated Policy Basis

A capability continues operating under obsolete policy assumptions.

### Framework Substitution

Compliance with one framework is incorrectly assumed to satisfy all other applicable obligations.

---

## 30. Minimum Policy Alignment Requirements

Every consequential AI capability should have:

- identified applicable legal and policy requirements;
- named responsibility for policy alignment;
- documented material interpretations;
- traceable policy-to-control mapping;
- evidence of implementation;
- defined exception and waiver procedures;
- defined policy-change triggers;
- appropriate legal and policy review;
- linkage to operational authorisation.

---

## 31. Relationship With Other D-AIGAAF Modules

This document should be read with:

- `00 Framework/Reference Model.md`
- `00 Framework/Principles.md`
- `00 Framework/Terminology.md`
- `00 Framework/Lifecycle.md`
- `00 Framework/Golden Thread.md`
- `01 Strategy & Governance/Governance Model.md`
- `01 Strategy & Governance/Decision Rights.md`
- `01 Strategy & Governance/Risk Governance.md`

Detailed treatment is developed further in:

- `03 Risk & Autonomy`
- `06 AI Security`
- `07 Supply Chain & Sovereignty`
- `08 Human Authority`
- `09 TEVV`
- `11 Operational Authorisation`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`
- `19 Crosswalks`
- `21 Legal & Policy`
- `22 Acquisition & Procurement`

---

## 32. Implementation Principle

D-AIGAAF should remain legally and institutionally adaptable.

It should provide a common governance architecture without assuming that every country, military or organisation has identical:

- laws;
- command structures;
- policies;
- procurement systems;
- risk authorities;
- operational doctrines.

The framework should therefore define **governance functions and traceability requirements**, while allowing implementing organisations to populate the applicable legal and policy context.

---

## 33. Summary

Policy alignment ensures that D-AIGAAF remains subordinate to legitimate authority while translating external requirements into operational governance.

The core chain is:

**Law / Policy → Requirement → Control → Evidence → Assurance → Authority → Employment**

The governing principle is:

> **D-AIGAAF does not create authority. It makes existing authority, constraints and accountability visible and operationally traceable.**

A defence AI capability should therefore never be considered governed merely because a policy document exists.

The relevant requirements must be:

**Identified → interpreted → implemented → tested → evidenced → assured → authorised → monitored**

---

**Status:** Working Draft v0.1  
**Next review:** Following development of detailed `21 Legal & Policy` and `19 Crosswalks` modules.
