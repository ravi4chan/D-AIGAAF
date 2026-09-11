# 19-Crosswalk Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 19 — Crosswalk**.

Crosswalks provide a controlled method for relating D-AIGAAF requirements to external frameworks, standards, regulations, policies, principles and assurance schemes.

The purpose is not to claim that two frameworks are identical.

The purpose is to establish:

- applicability;
- correspondence;
- gaps;
- overlaps;
- implementation requirements;
- evidence requirements;
- assurance implications;
- governance implications.

The central principle is:

> **A crosswalk is an analytical mapping between requirements and controls; it is not, by itself, evidence of compliance, conformity, assurance or authorisation.**

The crosswalk lifecycle is:

**Identify Source → Establish Applicability → Interpret Requirement → Map → Classify Relationship → Identify Gap → Translate to Control → Identify Evidence → Assure → Review → Update**

---

# 2. Template Set

The recommended Crosswalk template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-19-001 | Crosswalk Governance Record |
| D-AIGAAF-T-19-002 | Framework / Standard Crosswalk Record |
| D-AIGAAF-T-19-003 | Requirement Mapping Record |
| D-AIGAAF-T-19-004 | Applicability & Scope Assessment |
| D-AIGAAF-T-19-005 | Gap, Overlap & Conflict Assessment |
| D-AIGAAF-T-19-006 | Crosswalk Evidence & Traceability Record |
| D-AIGAAF-T-19-007 | Crosswalk Implementation & Control Translation Record |
| D-AIGAAF-T-19-008 | Crosswalk Assurance & Conformity Assessment |
| D-AIGAAF-T-19-009 | Crosswalk Change & Version Review Record |
| D-AIGAAF-T-19-010 | Integrated Crosswalk & Governance Review |

---

# 3. Template 19-001 — Crosswalk Governance Record

## Purpose

Defines governance arrangements for creating, approving, maintaining and using D-AIGAAF crosswalks.

## Required Fields

- Crosswalk ID
- Source framework
- Source owner
- D-AIGAAF owner
- Subject-matter expert
- Legal / policy reviewer
- Assurance reviewer
- Approval authority
- Version
- Effective date
- Review date
- Change trigger

## Governance Questions

- Who owns the crosswalk?
- Who interprets ambiguous requirements?
- Who approves mappings?
- Who resolves conflicting interpretations?
- Who validates legal applicability?
- Who determines whether a mapping is sufficiently evidenced?
- Who controls revisions?

---

# 4. Template 19-002 — Framework / Standard Crosswalk Record

## Purpose

Provides the high-level record for mapping D-AIGAAF to an external source.

## Required Fields

- Source name
- Issuing organisation
- Version
- Publication date
- Jurisdiction
- Source type
- Authority level
- Applicability
- Relevant sections
- D-AIGAAF modules affected
- Mapping owner
- Status
- Review date

## Source Types

Consider:

- regulation;
- law;
- standard;
- framework;
- policy;
- guidance;
- principle set;
- assurance scheme;
- technical specification.

---

# 5. Source Authority Classification

Crosswalks should distinguish the authority of the source.

Possible classifications include:

### Binding

A legal or formally mandatory requirement applicable to the organisation.

### Contractual

A requirement created through an agreement or procurement condition.

### Policy

An organisational or governmental policy requirement.

### Standard

A recognised technical or management standard.

### Guidance

Recommended practice that may inform governance but is not inherently binding.

### Principle

A high-level normative expectation requiring interpretation into controls.

This distinction prevents voluntary guidance from being incorrectly represented as mandatory law.

---

# 6. Template 19-003 — Requirement Mapping Record

## Purpose

Maps an individual source requirement to D-AIGAAF.

## Required Fields

- Mapping ID
- Source
- Source section
- Requirement
- Requirement type
- Applicability
- D-AIGAAF module
- D-AIGAAF requirement
- Correspondence
- Implementation status
- Evidence
- Assurance status
- Gap
- Owner
- Review date

## Mapping Relationships

Use controlled classifications such as:

- Direct correspondence
- Substantially aligned
- Partially aligned
- Complementary
- Indirectly addressed
- Not addressed
- Not applicable
- Potential conflict
- Requires interpretation

---

# 7. Avoiding False Equivalence

Two requirements may appear similar without being equivalent.

For example:

**External Requirement**
→ requires transparency

**D-AIGAAF Control**
→ requires uncertainty and decision traceability

These may support the same objective but are not necessarily identical obligations.

Crosswalks should therefore explain:

- what is similar;
- what is different;
- what is additional;
- what remains unaddressed.

---

# 8. Template 19-004 — Applicability & Scope Assessment

## Purpose

Determines whether a source requirement actually applies to the capability or organisation.

## Required Fields

- Source
- Requirement
- Jurisdiction
- Organisation
- AI capability
- Mission
- Product / service
- Data
- Geography
- User population
- Trigger
- Applicability determination
- Rationale
- Legal / policy review
- Effective date

## Possible Outcomes

- Applicable
- Partially applicable
- Conditionally applicable
- Not applicable
- Applicability uncertain
- Requires legal interpretation

A crosswalk should not automatically map every external requirement to every AI capability.

---

# 9. Applicability Dimensions

Consider:

- jurisdiction;
- organisation;
- sector;
- mission;
- procurement status;
- deployment location;
- data category;
- system classification;
- risk category;
- intended use;
- supplier relationship;
- contractual obligations.

Applicability should be determined before detailed mapping.

---

# 10. Template 19-005 — Gap, Overlap & Conflict Assessment

## Purpose

Identifies differences between the source framework and D-AIGAAF.

## Required Fields

- Mapping ID
- Source requirement
- D-AIGAAF control
- Gap
- Overlap
- Conflict
- Consequence
- Risk
- Resolution
- Owner
- Due date

## Gap Types

- Requirement absent
- Requirement partially addressed
- Evidence absent
- Control ineffective
- Assurance absent
- Authority unclear
- Applicability unresolved
- Terminology mismatch
- Scope mismatch

---

# 11. Conflicting Requirements

Where frameworks appear to conflict:

1. identify the conflict;
2. determine source authority;
3. determine jurisdiction;
4. establish applicability;
5. identify the underlying objective;
6. seek authoritative interpretation where necessary;
7. document the resolution;
8. update the control set.

D-AIGAAF should not silently choose one framework over another.

---

# 12. Template 19-006 — Crosswalk Evidence & Traceability Record

## Purpose

Links crosswalk claims to supporting evidence.

## Required Fields

- Mapping ID
- Requirement
- D-AIGAAF control
- Evidence ID
- Evidence source
- Evidence date
- Configuration
- Applicability
- Test / assessment
- Assurance status
- Evidence limitations
- Reviewer
- Confidence

## Traceability Chain

**Source → Requirement → Applicability → D-AIGAAF Control → Evidence → Test → Assurance → Governance Decision**

This prevents a crosswalk from becoming a purely textual exercise.

---

# 13. Template 19-007 — Crosswalk Implementation & Control Translation Record

## Purpose

Translates external requirements into actionable D-AIGAAF controls where necessary.

## Required Fields

- Source requirement
- Interpretation
- D-AIGAAF control
- Responsible owner
- Process
- Technical control
- Evidence
- Training
- TEVV requirement
- Monitoring
- Authorisation implication
- Implementation status

The objective is:

**Requirement → Control → Evidence**

rather than:

**Requirement → Citation**

---

# 14. Control Translation

A source requirement may require translation across several D-AIGAAF layers.

Example:

**External requirement**
→ risk management expectation

may translate into:

**D-AIGAAF**
→ risk assessment  
→ risk treatment  
→ residual risk  
→ evidence  
→ assurance  
→ authorisation  
→ monitoring

Crosswalks should capture the actual governance mechanism rather than merely listing equivalent terminology.

---

# 15. Template 19-008 — Crosswalk Assurance & Conformity Assessment

## Purpose

Determines whether mapped controls are actually implemented and supported by evidence.

## Required Fields

- Requirement
- D-AIGAAF control
- Applicability
- Implementation status
- Evidence
- Test
- Finding
- Assurance conclusion
- Conformity conclusion
- Limitations
- Reviewer
- Date

## Important Distinctions

### Alignment

The concepts or objectives correspond.

### Implementation

The corresponding control has actually been established.

### Evidence

The implementation is supported by records or other evidence.

### Assurance

Evidence supports justified confidence.

### Conformity

The relevant conformity criteria have been met.

### Authorisation

An authorised authority has permitted operational use.

These states must not be collapsed into one claim.

---

# 16. Template 19-009 — Crosswalk Change & Version Review Record

## Purpose

Maintains crosswalk accuracy as source frameworks and D-AIGAAF evolve.

## Change Triggers

Consider:

- new regulation;
- amended law;
- revised standard;
- new framework version;
- new guidance;
- D-AIGAAF revision;
- new AI capability;
- new jurisdiction;
- changed mission;
- changed interpretation;
- audit finding;
- legal decision.

## Required Fields

- Crosswalk ID
- Previous version
- New version
- Source change
- D-AIGAAF change
- Impact
- Affected mappings
- Reassessment
- Approval
- Effective date

---

# 17. Crosswalk Currency

A crosswalk can become obsolete even when the D-AIGAAF framework itself has not changed.

External sources may change:

- terminology;
- requirements;
- scope;
- thresholds;
- definitions;
- jurisdiction;
- implementation guidance.

Therefore crosswalks should have:

- owner;
- version;
- review date;
- source version;
- change triggers.

---

# 18. Template 19-010 — Integrated Crosswalk & Governance Review

## Purpose

Provides portfolio-level review of all major D-AIGAAF crosswalks.

## Review Areas

- applicable frameworks;
- regulatory changes;
- mapping coverage;
- gaps;
- conflicts;
- evidence;
- assurance;
- implementation;
- recurring weaknesses;
- governance implications.

## Review Questions

1. Are all material sources identified?
2. Are applicability decisions documented?
3. Are mappings sufficiently precise?
4. Are gaps visible?
5. Are conflicts resolved?
6. Are claims supported by evidence?
7. Are external changes detected?
8. Are controls updated?
9. Are assurance implications understood?
10. Are authorisation decisions affected?

---

# 19. Crosswalk Matrix Structure

A useful master matrix may contain:

| Source | Requirement | Applicability | D-AIGAAF Control | Evidence | Assurance | Gap | Owner | Status |
|---|---|---|---|---|---|---|---|---|

For larger implementations, extend it with:

| Risk | TEVV | Human Authority | Authorisation | Monitoring | Change Trigger |
|---|---|---|---|---|---|

---

# 20. Crosswalk to D-AIGAAF Modules

A source requirement should be mapped to the most relevant D-AIGAAF control domain.

Possible domains include:

- Strategy & Governance
- Mission & Use Case
- Risk & Autonomy
- AI Lifecycle
- Data & Information
- AI Security
- Supply Chain & Sovereignty
- Human Authority
- TEVV
- Operational Environment
- Operational Authorisation
- Operational Employment
- Continuous Assurance
- Incident & Fail-Safe
- Change & Reauthorisation
- Audit & Evidence
- Workforce
- Maturity
- Acquisition
- Interoperability
- Architecture & Technical Controls
- Documentation & Knowledge
- Retirement & Decommissioning

A requirement may legitimately map to multiple modules.

---

# 21. Crosswalk and Legal Requirements

Legal or regulatory mappings should distinguish:

- legal obligation;
- regulatory requirement;
- policy expectation;
- technical standard;
- voluntary guidance.

Where legal interpretation is uncertain, the uncertainty should be recorded rather than converted into a definitive compliance statement.

D-AIGAAF is not intended to replace competent legal review.

---

# 22. Crosswalk and Defence AI Principles

Defence AI principles may include concepts such as:

- responsible use;
- human responsibility;
- accountability;
- traceability;
- reliability;
- safety;
- security;
- resilience;
- lawful use;
- appropriate human control.

Crosswalks should translate high-level principles into observable governance controls and evidence where possible.

---

# 23. Crosswalk and International Frameworks

D-AIGAAF may be mapped to multiple external frameworks simultaneously.

Examples include:

- AI governance frameworks;
- AI risk-management frameworks;
- information-security standards;
- AI management-system standards;
- privacy/data protection regimes;
- AI regulation;
- defence AI principles;
- TEVV frameworks;
- AI security frameworks.

The existence of a crosswalk does not mean that one framework satisfies every requirement of another.

---

# 24. Crosswalk and Procurement

External requirements may enter D-AIGAAF through procurement.

For example:

**Regulation / Standard**
→ Procurement Requirement
→ Supplier Obligation
→ Contractual Control
→ Evidence
→ Acceptance
→ Assurance
→ Operational Authorisation

Crosswalks should identify procurement implications where applicable.

---

# 25. Crosswalk and Technical Controls

Some requirements may need translation into technical controls.

Examples:

- access control;
- logging;
- model integrity;
- data provenance;
- auditability;
- monitoring;
- configuration management;
- security testing.

A crosswalk should identify the relevant technical implementation where the requirement depends upon it.

---

# 26. Crosswalk and Human Authority

External principles concerning human oversight should be mapped carefully.

The relevant D-AIGAAF questions include:

- Who has authority?
- What decisions can they make?
- What information do they receive?
- Can they intervene?
- Can they override?
- Do they have enough time?
- Are they competent?
- Is accountability traceable?

“Human oversight” should not automatically be treated as equivalent to meaningful human control.

---

# 27. Crosswalk and TEVV

Where an external requirement concerns:

- accuracy;
- robustness;
- safety;
- security;
- reliability;
- fairness;
- transparency;

the crosswalk should identify:

**Requirement → TEVV Method → Evidence → Acceptance Criterion**

This creates an operational link between external expectations and verification.

---

# 28. Crosswalk and Operational Authorisation

Crosswalk findings may affect authorisation when they identify:

- mandatory requirements not met;
- unresolved legal obligations;
- missing controls;
- insufficient evidence;
- material assurance gaps.

However:

> **A crosswalk does not itself grant operational authority.**

Authorisation remains a distinct governance decision.

---

# 29. Anti-Pattern — Keyword Mapping

D-AIGAAF rejects mapping based solely on similar words.

Example:

**“Oversight”**
does not necessarily equal
**“Meaningful Human Control.”**

Likewise:

**“Risk management”**
does not automatically demonstrate
**“Consequence-based operational risk governance.”**

Mappings should compare substance, scope and intended outcome.

---

# 30. Anti-Pattern — One-to-One Mapping Assumption

One external requirement may map to multiple D-AIGAAF controls.

One D-AIGAAF control may support multiple external requirements.

Therefore crosswalks should support:

**Many-to-Many Relationships**

rather than forcing artificial one-to-one mappings.

---

# 31. Anti-Pattern — Crosswalk as Compliance Certificate

A completed crosswalk does not prove compliance.

It only establishes a relationship between:

**Source Expectations**
and
**D-AIGAAF Controls**

Compliance requires applicability, implementation and evidence against the relevant authoritative criteria.

---

# 32. Anti-Pattern — Static Crosswalk

A crosswalk should not be treated as permanent.

It should be reviewed when:

- the source changes;
- D-AIGAAF changes;
- capability changes;
- legal interpretation changes;
- mission changes;
- jurisdiction changes.

---

# 33. Crosswalk Confidence

Where useful, record confidence in the mapping:

- High
- Moderate
- Low
- Uncertain

Confidence should reflect:

- clarity of source;
- clarity of applicability;
- quality of interpretation;
- strength of correspondence;
- evidence available.

---

# 34. Crosswalk Records

A mature crosswalk record should allow reconstruction of:

**Source**
→ **Version**
→ **Requirement**
→ **Applicability**
→ **Interpretation**
→ **D-AIGAAF Mapping**
→ **Control**
→ **Evidence**
→ **Assurance**
→ **Gap**
→ **Decision**
→ **Review**

This makes crosswalks auditable.

---

# 35. Integrated D-AIGAAF Crosswalk Method

For complex implementations, use the following master sequence:

**Identify**
→ identify relevant source

**Classify**
→ determine source authority and type

**Scope**
→ determine applicability

**Map**
→ establish D-AIGAAF correspondence

**Translate**
→ convert expectation into operational control

**Control**
→ implement governance / technical control

**Evidence**
→ identify and collect evidence

**Assure**
→ test and assess

**Authorise**
→ consider implications for operational authority

**Monitor**
→ monitor source and capability changes

**Update**
→ revise crosswalk and controls

---

# 36. Crosswalk Golden Thread Integration

Crosswalks connect external requirements to the D-AIGAAF Golden Thread:

**External Source**
→ **Authority**
→ **Applicability**
→ **Requirement / Expectation**
→ **D-AIGAAF Control**
→ **Evidence**
→ **TEVV / Assurance**
→ **Risk**
→ **Human Authority**
→ **Authorisation**
→ **Employment**
→ **Monitoring**
→ **Change**
→ **Review**

This ensures that external alignment can ultimately influence operational governance rather than remaining a documentation exercise.

---

# 37. Final Crosswalk Principle

D-AIGAAF treats crosswalks as controlled analytical instruments for translating external requirements into implementable governance.

The governing principle is:

> **A crosswalk should explain what an external requirement means, whether it applies, how it corresponds to D-AIGAAF, what controls implement it, what evidence supports implementation, what assurance exists, what gaps remain and whether any governance or authorisation decision is affected; it should never be presented as proof of compliance merely because a mapping exists.**
