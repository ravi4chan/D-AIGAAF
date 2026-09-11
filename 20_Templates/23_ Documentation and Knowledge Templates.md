# 23-Documentation and Knowledge Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 23 — Documentation & Knowledge**.

Documentation and knowledge management provide the institutional memory required to understand, govern, assure, operate, change and retire AI capabilities.

For consequential AI, documentation is not merely a record of what was built. It should enable authorised people to understand:

- what the capability is;
- why it exists;
- how it works at an appropriate level;
- what assumptions it makes;
- what risks it creates;
- what evidence supports it;
- what authority applies;
- what limitations exist;
- what changes have occurred;
- what lessons have been learned.

The central principle is:

> **Critical AI governance knowledge should be sufficiently accurate, current, traceable, accessible to authorised personnel and resilient to organisational or personnel change.**

The knowledge lifecycle is:

**Create → Classify → Validate → Approve → Publish → Use → Maintain → Review → Update → Archive / Retire**

---

# 2. Template Set

The recommended Documentation & Knowledge template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-23-001 | Documentation & Knowledge Governance Record |
| D-AIGAAF-T-23-002 | AI Capability Documentation Record |
| D-AIGAAF-T-23-003 | AI System Description & Intended Use Record |
| D-AIGAAF-T-23-004 | Assumptions, Limitations & Uncertainty Record |
| D-AIGAAF-T-23-005 | AI Knowledge & Evidence Index |
| D-AIGAAF-T-23-006 | Decision & Rationale Record |
| D-AIGAAF-T-23-007 | Configuration & Version Documentation Record |
| D-AIGAAF-T-23-008 | Operational Knowledge & Lessons Record |
| D-AIGAAF-T-23-009 | Documentation Change, Review & Retention Record |
| D-AIGAAF-T-23-010 | Knowledge Governance Review & Improvement Record |

---

# 3. Template 23-001 — Documentation & Knowledge Governance Record

## Purpose

Defines governance responsibilities for AI documentation and institutional knowledge.

## Required Fields

- Capability ID
- Mission / Use Case
- Documentation owner
- Knowledge owner
- System owner
- Records authority
- Security / classification authority
- Operational owner
- Assurance authority
- Approval authority
- Review authority
- Retention authority
- Review date

## Governance Questions

- What documentation is mandatory?
- Who owns each document?
- Who validates technical accuracy?
- Who approves operational documentation?
- Who controls classification?
- Who ensures documents remain current?
- How are obsolete documents controlled?
- How is institutional knowledge preserved?

---

# 4. Template 23-002 — AI Capability Documentation Record

## Purpose

Provides a master record of documentation associated with an AI capability.

## Required Fields

- Capability
- Mission
- Use Case
- Document ID
- Document type
- Version
- Owner
- Status
- Classification
- Related configuration
- Related evidence
- Related authorisation
- Effective date
- Review date
- Retention requirement

## Documentation Categories

Consider:

- governance;
- mission;
- requirements;
- risk;
- model;
- data;
- security;
- TEVV;
- environment;
- authorisation;
- employment;
- incidents;
- change;
- audit;
- workforce;
- architecture;
- procurement;
- interoperability;
- retirement.

---

# 5. Template 23-003 — AI System Description & Intended Use Record

## Purpose

Provides a controlled description of what the AI capability is intended to do and the boundaries within which it may be used.

## Required Fields

- Capability name
- Purpose
- Intended users
- Mission
- Use cases
- Inputs
- Outputs
- Decision / action supported
- Autonomy level
- Human role
- Operational environment
- Dependencies
- Constraints
- Prohibited uses
- Limitations
- Authorisation reference

## Principle

Documentation should clearly distinguish:

**Intended Use**

from

**Possible Use**

from

**Authorised Use**

Technical capability alone does not establish authorised use.

---

# 6. Intended Use and Mission Context

The description should explain:

- operational problem;
- decision supported;
- consequence;
- mission objective;
- operating conditions;
- expected human role;
- assumptions.

A generic product description is insufficient for a consequential defence capability.

The relevant question is:

> **What does this AI do in this mission, for this user, under these conditions, with what authority?**

---

# 7. Template 23-004 — Assumptions, Limitations & Uncertainty Record

## Purpose

Captures assumptions and known limitations that could affect safe and authorised use.

## Categories

Consider:

- data;
- model;
- environment;
- communications;
- sensors;
- human;
- infrastructure;
- supplier;
- security;
- autonomy;
- interoperability.

## Required Fields

- Assumption / limitation
- Source
- Condition
- Consequence if false
- Evidence
- Confidence
- Control
- Monitoring indicator
- Escalation
- Review date

---

# 8. Unknowns and Uncertainty

Documentation should distinguish:

- known;
- reasonably inferred;
- uncertain;
- disputed;
- unknown.

The absence of information should not be concealed by overly confident language.

Where uncertainty could affect a consequential decision, it should be visible to the appropriate authority.

---

# 9. Template 23-005 — AI Knowledge & Evidence Index

## Purpose

Provides a structured index linking important knowledge to evidence and governance decisions.

## Required Fields

- Knowledge item
- Source
- Evidence ID
- Capability
- Configuration
- Mission
- Risk
- Decision
- Authority
- Review date
- Confidence
- Owner

## Traceability

The index should support relationships such as:

**Requirement**
→ **Control**
→ **Evidence**
→ **Decision**
→ **Authorisation**

and:

**Incident**
→ **Finding**
→ **Lesson**
→ **Change**
→ **Revalidation**

---

# 10. Knowledge Criticality

Not all documentation has equal importance.

Classify knowledge according to consequence.

### Critical

Loss or corruption could materially affect safe operation, authorisation or incident response.

### Important

Loss could materially reduce governance or operational effectiveness.

### Routine

Loss creates administrative inconvenience but limited governance impact.

Critical knowledge should receive stronger:

- access control;
- integrity protection;
- backup;
- continuity;
- review;
- retention.

---

# 11. Template 23-006 — Decision & Rationale Record

## Purpose

Records significant governance decisions and the reasoning behind them.

## Required Fields

- Decision ID
- Capability
- Mission
- Decision
- Decision maker
- Authority
- Date
- Evidence
- Risk
- Alternatives considered
- Assumptions
- Uncertainty
- Conditions
- Dissent / challenge
- Rationale
- Review trigger

## Decision Principle

A consequential decision should be reconstructable without relying entirely on the memory of one individual.

---

# 12. Decision Traceability

Where material, maintain:

**Decision**
→ **Authority**
→ **Evidence**
→ **Risk**
→ **Conditions**
→ **Alternative**
→ **Rationale**
→ **Outcome**

This supports:

- accountability;
- audit;
- incident investigation;
- lessons learned;
- future reassessment.

---

# 13. Template 23-007 — Configuration & Version Documentation Record

## Purpose

Maintains documentation of the configuration relevant to governance and assurance.

## Required Fields

- Configuration ID
- Model
- Model version / identifier
- Software
- Hardware
- Data
- Instructions
- Tools
- APIs
- Security controls
- Infrastructure
- Dependencies
- Effective date
- Owner
- Integrity evidence

## Principle

Documentation should make it possible to determine what configuration was subject to:

- testing;
- assurance;
- authorisation;
- employment.

---

# 14. Configuration Documentation and Evidence

A document should not merely state:

> “Version 4 is deployed.”

Where material, it should establish what Version 4 actually comprises.

Configuration documentation may therefore need to connect:

**Model**
+ **Software**
+ **Data**
+ **Instructions**
+ **Tools**
+ **Infrastructure**
+ **Security Controls**

This supports reproducibility and investigation.

---

# 15. Template 23-008 — Operational Knowledge & Lessons Record

## Purpose

Captures knowledge generated through operational use, exercises, incidents and experience.

## Required Fields

- Lesson ID
- Capability
- Mission
- Event
- Observation
- What happened
- Why it mattered
- Evidence
- Risk implication
- Lesson
- Recommended change
- Owner
- Implementation
- Verification
- Date reviewed

## Sources

Consider:

- operations;
- exercises;
- incidents;
- near misses;
- audits;
- TEVV;
- operator feedback;
- supplier events;
- change events.

---

# 16. Lessons Should Change the System

A lesson should not end as a statement.

Where appropriate:

**Lesson**
→ **Risk**
→ **Control Change**
→ **Training Change**
→ **Technical Change**
→ **Policy Change**
→ **Revalidation**
→ **Reauthorisation**

This converts experience into governance improvement.

---

# 17. Template 23-009 — Documentation Change, Review & Retention Record

## Purpose

Controls documentation changes and ensures obsolete information is appropriately managed.

## Change Triggers

Consider:

- capability change;
- model update;
- software change;
- mission change;
- environment change;
- incident;
- audit finding;
- policy change;
- legal change;
- supplier change;
- new evidence.

## Required Fields

- Document
- Previous version
- New version
- Change
- Reason
- Impact
- Reviewer
- Approver
- Effective date
- Superseded version
- Retention
- Archive location

---

# 18. Document Currency

A document may become inaccurate because the capability changed even when the document itself was never formally amended.

Therefore review should consider:

**Is the document current relative to the actual system and operating context?**

not merely:

**Was the document recently edited?**

---

# 19. Documentation Classification

AI documentation may contain sensitive information.

Consider classification and handling requirements for:

- model architecture;
- vulnerabilities;
- security controls;
- operational procedures;
- mission information;
- data;
- supplier information;
- technical weaknesses.

Documentation should be accessible to those who need it while protected from unauthorised access.

---

# 20. Documentation and Security

Documentation can itself become an attack surface.

Protect against:

- unauthorised modification;
- deletion;
- disclosure;
- stale information;
- malicious insertion;
- conflicting versions.

Critical records should have appropriate:

- access control;
- integrity protection;
- versioning;
- backup;
- audit trail.

---

# 21. Documentation and Knowledge Continuity

Critical AI knowledge should not depend on one person.

Where appropriate, use:

- documented procedures;
- role-based access;
- knowledge repositories;
- alternate personnel;
- cross-training;
- decision records;
- configuration records.

This is particularly important for:

- system owners;
- AI specialists;
- security personnel;
- authorisation authorities;
- operational experts.

---

# 22. Documentation and Workforce

Documentation should support personnel in performing their actual responsibilities.

For operators, documentation may need to cover:

- intended use;
- limitations;
- uncertainty;
- warnings;
- autonomy;
- intervention;
- fail-safe;
- escalation.

For governance personnel, it may need to cover:

- risk;
- evidence;
- assurance;
- authorisation;
- change;
- incidents.

Documentation should be role appropriate.

---

# 23. Documentation and Human Control

Documentation should not create the illusion of human control.

It should help personnel understand:

- what the AI can do;
- what it cannot do;
- what it is authorised to do;
- when human approval is required;
- how to intervene;
- how to stop or restrict it;
- what to do when behaviour is unexpected.

---

# 24. Documentation and AI Security

Security documentation should provide sufficient information to govern:

- attack surface;
- trust boundaries;
- privileges;
- dependencies;
- known vulnerabilities;
- model integrity;
- data integrity;
- security monitoring;
- incident response.

Sensitive information should be appropriately protected.

---

# 25. Documentation and Operational Authorisation

Authorisation decisions should reference controlled documentation for:

- capability;
- configuration;
- mission;
- environment;
- autonomy;
- human authority;
- conditions;
- evidence.

If the documentation supporting authorisation is materially outdated, the validity of the authorisation basis should be reassessed.

---

# 26. Documentation and Change Management

A material change should trigger documentation review.

This may include:

- architecture documentation;
- risk records;
- TEVV evidence;
- operating procedures;
- training material;
- authorisation records;
- security documentation.

Change management should therefore include a documentation impact assessment.

---

# 27. Documentation and Incidents

Incident investigation may depend on historical records.

Preserve, where relevant:

- configuration;
- logs;
- AI outputs;
- inputs;
- decisions;
- authority;
- instructions;
- environmental state;
- security events.

Historical records should not be overwritten by subsequent updates.

---

# 28. Knowledge Retrieval

Knowledge should be organised so authorised personnel can find relevant information without excessive effort.

Useful indexing dimensions include:

- capability;
- mission;
- configuration;
- date;
- risk;
- authority;
- evidence;
- incident;
- change.

The objective is **decision-useful knowledge**, not a document warehouse.

---

# 29. Documentation Quality Criteria

Important documentation should be:

- accurate;
- clear;
- complete enough for purpose;
- current;
- traceable;
- internally consistent;
- appropriately classified;
- accessible to authorised users;
- reviewable;
- version controlled.

For high-consequence capabilities, documentation should be subject to stronger quality controls.

---

# 30. Anti-Pattern — Documentation for Documentation's Sake

D-AIGAAF rejects documentation that exists solely to demonstrate that a process was performed.

Documentation should enable:

- understanding;
- decision-making;
- control;
- assurance;
- accountability;
- continuity;
- learning.

If a document does not support one of these purposes, its necessity should be questioned.

---

# 31. Anti-Pattern — Latest Document Wins

The newest document is not necessarily the correct document.

Governance should establish:

- approved version;
- effective date;
- applicable configuration;
- superseded versions;
- authority.

A newer draft should not silently replace an approved record.

---

# 32. Anti-Pattern — Undocumented Tribal Knowledge

Critical governance knowledge should not exist only as:

- informal conversations;
- individual memory;
- private notes;
- supplier statements;
- undocumented workarounds.

Material knowledge should be captured in controlled records where appropriate.

---

# 33. Anti-Pattern — Documented Assumption Becomes Fact

Recording an assumption does not validate it.

Documentation should distinguish:

**Assumption**
from
**Evidence**
from
**Validated Fact**

When assumptions materially affect risk or authorisation, they should be monitored and reassessed.

---

# 34. Documentation and AI Explainability

Documentation should provide the level of explanation necessary for the intended audience and decision.

This may include:

- purpose;
- inputs;
- outputs;
- limitations;
- uncertainty;
- decision logic at an appropriate level;
- human responsibilities.

D-AIGAAF does not assume that complete disclosure of every internal model mechanism is always necessary or feasible.

The objective is **decision-relevant understanding**.

---

# 35. Documentation and External Suppliers

Supplier documentation should be incorporated into the governance knowledge base where relevant.

However:

**Supplier Documentation**
does not automatically equal
**Organisation-Validated Knowledge**

Important supplier claims may require:

- verification;
- independent assessment;
- contextual interpretation.

---

# 36. Knowledge Review

Knowledge governance should periodically ask:

1. Is critical information current?
2. Can authorised personnel find it?
3. Is the correct configuration documented?
4. Are assumptions still valid?
5. Are limitations understood?
6. Are decisions traceable?
7. Are lessons being incorporated?
8. Are obsolete records controlled?
9. Are sensitive records protected?
10. Could the organisation operate if key personnel became unavailable?

---

# 37. Template 23-010 — Knowledge Governance Review & Improvement Record

## Purpose

Provides periodic review of documentation and institutional knowledge.

## Required Fields

- Review ID
- Scope
- Documents reviewed
- Knowledge gaps
- Currency findings
- Security findings
- Traceability findings
- Workforce continuity findings
- Improvement actions
- Owner
- Due date
- Verification
- Governance decision

## Review Outcomes

- adequate;
- improvement required;
- material knowledge gap;
- critical documentation weakness;
- immediate corrective action.

---

# 38. Knowledge and Maturity

Documentation maturity should progress from:

**Stored**
→ **Controlled**
→ **Traceable**
→ **Integrated**
→ **Decision-Useful**
→ **Learning-Enabled**

The highest maturity is not maximum documentation volume.

It is the ability to reliably provide the right knowledge to the right authority at the right time.

---

# 39. Knowledge and Audit

Audit should be able to determine:

- what was known;
- when it was known;
- who knew it;
- what evidence supported it;
- what decision was made;
- under what authority;
- what configuration applied.

This creates institutional accountability.

---

# 40. Knowledge and Continuous Assurance

Continuous assurance depends upon current knowledge of:

- system state;
- configuration;
- performance;
- risk;
- security;
- human control;
- environment;
- dependencies.

Poor knowledge management can therefore become an assurance weakness.

---

# 41. Documentation Golden Thread Integration

Documentation connects the D-AIGAAF Golden Thread through controlled knowledge:

**Mission Need**
→ **Requirements**
→ **Risk**
→ **Controls**
→ **Testing**
→ **Evidence**
→ **Assurance**
→ **Authority**
→ **Conditions**
→ **Boundaries**
→ **Employment**
→ **Monitoring**
→ **Change / Incident**
→ **Learning**
→ **Revalidation / Reauthorisation**
→ **Records**
→ **Institutional Knowledge**

The purpose is to preserve the reasoning and evidence behind governance decisions throughout the lifecycle.

---

# 42. Final Documentation & Knowledge Principle

D-AIGAAF treats documentation and knowledge as operational governance infrastructure.

The governing principle is:

> **Critical AI governance knowledge should remain accurate, current, traceable, appropriately protected and accessible to authorised personnel throughout the capability lifecycle, with sufficient documentation to reconstruct important requirements, configurations, assumptions, decisions, evidence, authorisations, incidents and lessons without relying solely on individual memory or supplier assertion.**
