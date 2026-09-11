# 13-Integrated D-AIGAAF Crosswalk and Alignment Method

## 1. Purpose

This document defines the **Integrated D-AIGAAF Crosswalk and Alignment Method**.

Its purpose is to provide a repeatable method for mapping external:

- laws;
- regulations;
- policies;
- principles;
- standards;
- frameworks;
- guidelines;
- assurance methods;
- security frameworks;
- defence doctrines;
- contractual requirements

to D-AIGAAF.

The objective is not to make D-AIGAAF dependent on any single external framework.

Instead, D-AIGAAF acts as the **integrating governance architecture** through which applicable external requirements can be identified, interpreted, mapped, implemented, evidenced and maintained.

The core method is:

**Identify → Classify → Scope → Map → Translate → Control → Evidence → Assure → Authorise → Monitor → Update**

## 2. Why an Integrated Crosswalk Method Is Required

AI governance is fragmented across multiple disciplines.

An organisation may simultaneously need to consider:

- AI governance;
- AI risk management;
- data protection;
- information security;
- AI safety;
- responsible AI;
- testing and evaluation;
- procurement;
- human rights;
- defence policy;
- operational requirements;
- sector regulation;
- national law;
- international standards.

These sources often overlap but are not identical.

A single external framework may provide excellent guidance in one area while saying little about another.

D-AIGAAF therefore uses an **integration model rather than a replacement model**.

The objective is:

> **Integrate relevant requirements without duplicating, confusing or weakening their original authority.**

## 3. D-AIGAAF as the Integration Layer

The D-AIGAAF architecture provides a common structure through which external requirements can be aligned.

The core relationship is:

**External Source**
→ **Applicable Requirement / Principle**
→ **D-AIGAAF Module**
→ **Control**
→ **Evidence**
→ **Assurance**
→ **Authority**
→ **Operational Condition**

This allows an organisation to answer:

1. What does the external source require?
2. Does it apply?
3. Where is it addressed in D-AIGAAF?
4. What control implements it?
5. What evidence demonstrates implementation?
6. Who assures it?
7. Who has authority to accept residual risk?
8. What operational conditions follow?

## 4. Types of External Sources

Every source should first be classified.

| Source | Typical Authority | Crosswalk Treatment |
|---|---|---|
| Law / Act | Binding | Mandatory where applicable |
| Regulation / Rule | Binding | Mandatory where applicable |
| Government Direction | Binding where applicable | Implement according to scope |
| Defence Directive | Binding within relevant organisation | Integrate into governance |
| Contractual Requirement | Binding between parties | Include in applicable controls |
| Standard | Normative / contractual / regulatory depending on use | Determine applicability |
| Framework | Guidance / best practice | Map relevant practices |
| Guideline | Policy guidance | Assess status and applicability |
| Principle | Normative objective | Translate into requirements |
| Expert Report | Advisory | Use as policy/reference input |
| Research | Informational | Use as supporting evidence |
| Industry Practice | Good practice | Consider where useful |

The source's authority must never be inferred merely from its title.

## 5. Step 1 — Identify

Identify all potentially relevant external sources.

The search should consider:

- jurisdiction;
- mission;
- sector;
- technology;
- data;
- security;
- procurement;
- human impact;
- autonomy;
- operational environment.

Sources should be recorded in an **External Requirements and Crosswalk Register**.

Minimum fields should include:

- source name;
- issuing authority;
- version;
- publication date;
- effective date;
- jurisdiction;
- source type;
- applicability status;
- owner.

## 6. Step 2 — Classify Authority

Determine the authority level of each source.

A practical classification is:

**L0 — Informational**

Research or background material.

**L1 — Advisory**

Non-binding guidance or good practice.

**L2 — Organisational Requirement**

Internal policy or mandatory organisational standard.

**L3 — Contractual Requirement**

Binding contractual requirement.

**L4 — Government / Defence Direction**

Applicable official requirement.

**L5 — Law / Regulation**

Binding legal requirement.

This classification is illustrative and should be adapted to the organisation's legal structure.

## 7. Step 3 — Determine Applicability

Not every requirement applies to every AI system.

Applicability should consider:

- organisation;
- jurisdiction;
- mission;
- use case;
- data;
- technology;
- system role;
- deployment location;
- affected persons;
- autonomy;
- supplier;
- operational environment.

The result should be one of:

- Applicable;
- Partially Applicable;
- Not Applicable;
- Under Assessment;
- Future / Emerging.

A decision of **Not Applicable** should be supported by documented reasoning where the source is potentially relevant.

## 8. Step 4 — Decompose the Source

External frameworks should be decomposed into manageable governance elements.

These may be:

- principles;
- requirements;
- controls;
- outcomes;
- procedures;
- evidence expectations;
- assurance expectations.

For example:

**Principle**
→ AI should be reliable.

**Requirement**
→ The system shall demonstrate reliability for its intended use.

**Control**
→ Conduct mission-representative reliability testing.

**Evidence**
→ Approved TEVV report.

This decomposition is essential for meaningful crosswalking.

## 9. Step 5 — Map to D-AIGAAF

Each external requirement should be mapped to one or more D-AIGAAF modules.

Example:

| External Requirement | D-AIGAAF Mapping |
|---|---|
| AI risk management | 03 Risk & Autonomy |
| Data governance | 05 Data & Information |
| AI security | 06 AI Security |
| Human oversight | 08 Human Authority |
| Testing | 09 TEVV |
| Environment | 10 Operational Environment |
| Authorisation | 11 Operational Authorisation |
| Operational use | 12 Operational Employment |
| Continuous monitoring | 13 Continuous Assurance |
| Incidents | 14 Incident & Fail-Safe |
| Change | 15 Change & Reauthorisation |
| Audit | 16 Audit & Evidence |
| Workforce | 17 Workforce |

Multiple mappings are expected where requirements cross governance domains.

## 10. Step 6 — Determine Mapping Type

Each mapping should be classified.

### Direct Alignment

D-AIGAAF already contains a substantially equivalent requirement.

### Partial Alignment

D-AIGAAF addresses part of the requirement.

### Extension

D-AIGAAF addresses the requirement and adds defence-specific controls.

### External Dependency

The requirement is intentionally left to another framework, policy or legal mechanism.

### Gap

D-AIGAAF does not currently address the requirement adequately.

### Conflict

Two applicable requirements appear inconsistent and require resolution.

This classification prevents a superficial “mapped = compliant” conclusion.

## 11. Step 7 — Translate Principles into Requirements

High-level principles should be converted into measurable requirements.

Example:

**Responsible AI**

→ The system shall operate within defined and approved conditions.

**Human oversight**

→ An appropriately authorised human shall retain defined decision and intervention authority.

**Explainability**

→ The system shall provide decision-relevant information sufficient for the authorised human to understand relevant outputs, limitations and uncertainty.

**Security**

→ The system shall be protected against identified AI-specific threats proportionate to mission consequence.

This translation creates operational value.

## 12. Step 8 — Map Requirements to Controls

Requirements should be linked to controls.

Example:

| Requirement | Control |
|---|---|
| Human oversight | Defined intervention authority |
| Reliability | Mission-representative testing |
| Data integrity | Provenance and integrity controls |
| Security | AI threat modelling and adversarial evaluation |
| Transparency | Lifecycle documentation |
| Accountability | Named decision authority |
| Change governance | Change-impact assessment |
| Operational safety | Fail-safe and safe-state mechanisms |

Controls should be:

- assigned;
- measurable;
- testable;
- auditable.

## 13. Step 9 — Define Evidence

Every significant control should have evidence.

Examples:

- policy;
- architecture;
- configuration;
- risk assessment;
- TEVV report;
- audit record;
- approval;
- authorisation;
- monitoring data;
- incident record;
- training record.

Evidence should demonstrate not only that a control exists, but where appropriate that it is effective.

The evidence chain is:

**Requirement → Control → Evidence → Finding → Assurance**

## 14. Step 10 — Assess Assurance

Evidence must be evaluated.

Assurance should consider:

- evidence quality;
- relevance;
- coverage;
- recency;
- independence;
- operational realism;
- residual risk;
- unresolved findings.

Assurance should communicate uncertainty.

D-AIGAAF rejects the assumption that:

**No evidence of failure = evidence of safety.**

## 15. Step 11 — Resolve Gaps

A crosswalk may identify gaps.

Gaps should be classified by:

- consequence;
- legal significance;
- operational importance;
- security significance;
- likelihood;
- urgency.

Possible treatments include:

- new control;
- strengthened control;
- additional testing;
- restricted employment;
- reduced autonomy;
- compensating control;
- additional monitoring;
- policy change;
- acceptance of residual risk where authorised.

## 16. Step 12 — Resolve Conflicts

External frameworks may contain different:

- terminology;
- thresholds;
- control expectations;
- assurance approaches;
- legal assumptions.

D-AIGAAF should not silently choose one.

Conflicts should be documented and resolved using:

1. Applicable law.
2. Binding government/defence requirements.
3. Contractual obligations.
4. Organisational policy.
5. Applicable standards.
6. Governance principles and good practice.

Where uncertainty remains, the issue should be escalated to the appropriate authority.

## 17. Step 13 — Determine the Strictest Applicable Requirement

Where multiple requirements apply, organisations should avoid selecting the weakest requirement simply because it is easier to satisfy.

A practical approach is:

> **Apply all mandatory requirements and adopt the stronger control where requirements are compatible and the risk warrants it.**

However, the strongest requirement should not automatically override a binding legal or operational requirement.

The final control position should be documented.

## 18. Step 14 — Connect Crosswalks to Authorisation

Crosswalks become operationally meaningful only when their results influence authorisation.

Before authorisation, the organisation should establish:

- applicable external requirements;
- identified gaps;
- evidence;
- residual risk;
- operating conditions;
- human authority;
- assurance status.

The authorisation authority should therefore receive a consolidated view of external-framework alignment.

## 19. Crosswalk Status Model

A practical status model is:

| Status | Meaning |
|---|---|
| Not Assessed | Requirement has not yet been reviewed |
| Applicable | Requirement applies |
| Mapped | D-AIGAAF location identified |
| Implemented | Control implemented |
| Evidence Available | Evidence exists |
| Assured | Evidence evaluated |
| Gap | Requirement not adequately addressed |
| Exception | Approved deviation |
| Not Applicable | Documented applicability decision |
| Superseded | Requirement/source no longer current |

These statuses should be maintained in the Crosswalk Register.

## 20. Integrated Crosswalk Register

D-AIGAAF recommends maintaining a master register.

Suggested fields:

| Field | Description |
|---|---|
| Crosswalk ID | Unique identifier |
| Source | External framework |
| Version | Source version |
| Requirement ID | Original requirement reference |
| Requirement Text | Relevant requirement |
| Authority | Legal/normative status |
| Applicability | Applicable / partial / N/A |
| D-AIGAAF Module | Mapped module |
| D-AIGAAF Control | Specific control |
| Evidence | Required evidence |
| Assurance | Assurance status |
| Gap | Identified deficiency |
| Risk | Related risk |
| Owner | Responsible role |
| Review Date | Next review |
| Status | Current implementation state |

## 21. One Requirement, Multiple Frameworks

The same D-AIGAAF control may satisfy multiple external requirements.

For example:

**Human Decision Rights**

may support:

- responsible-AI principles;
- defence AI principles;
- AI governance standards;
- operational safety requirements;
- assurance expectations.

D-AIGAAF should avoid creating five separate controls when one well-designed control can satisfy all five requirements.

This is a major benefit of an integrated crosswalk.

## 22. One Framework, Multiple D-AIGAAF Controls

Conversely, one external requirement may require multiple D-AIGAAF controls.

For example:

**AI reliability**

may require:

- risk assessment;
- requirements;
- data quality;
- TEVV;
- environment testing;
- human evaluation;
- continuous monitoring.

The crosswalk should therefore support **many-to-many relationships**.

## 23. Avoiding Double Counting

A common governance failure is double counting.

Example:

- ISO control;
- NIST practice;
- IndiaAI principle;
- NATO principle

may all describe substantially the same underlying objective.

D-AIGAAF should identify the **common control objective** rather than treating each source as a separate control burden.

The process is:

**Multiple External Requirements**
→ **Common Governance Objective**
→ **D-AIGAAF Control**
→ **Shared Evidence**

## 24. Avoiding False Equivalence

The opposite problem is assuming that similar words mean identical requirements.

For example:

- “human oversight”;
- “human control”;
- “human-in-the-loop”;
- “human accountability”

are not necessarily equivalent.

Similarly:

- testing;
- verification;
- validation;
- assurance;
- certification;
- authorisation

must remain distinct.

D-AIGAAF should preserve these distinctions when mapping frameworks.

## 25. Crosswalk Quality Criteria

A high-quality crosswalk should be:

### Accurate
The external requirement is represented correctly.

### Traceable
The source and exact reference can be identified.

### Complete
Material requirements are not selectively omitted.

### Contextual
Applicability is assessed for the actual system.

### Evidence-Based
Implementation can be demonstrated.

### Non-Duplicative
Equivalent controls are consolidated.

### Maintained
Changes in external sources are tracked.

### Authorisation-Relevant
Important gaps affect operational decisions.

## 26. Crosswalk Review

Crosswalks should be reviewed when:

- an external framework changes;
- a law changes;
- a new regulation is issued;
- a major standard is revised;
- the AI capability changes;
- mission changes;
- autonomy changes;
- operating environment changes;
- significant incidents occur.

The review should determine whether:

- requirements changed;
- applicability changed;
- controls changed;
- evidence remains valid;
- assurance remains valid;
- authorisation remains valid.

## 27. External Framework Change Management

An external framework update should enter D-AIGAAF change governance.

The sequence is:

**New Version**
→ Impact Assessment
→ Applicability Review
→ Crosswalk Update
→ Gap Assessment
→ Control Change
→ Evidence Update
→ Assurance Review
→ Revalidation
→ Reauthorisation where required

This prevents crosswalks from becoming static documents.

## 28. Crosswalk Governance

Ownership should be explicit.

A practical model includes:

- **Framework Owner:** maintains D-AIGAAF.
- **Legal/Policy Owner:** determines legal/policy applicability.
- **Control Owner:** implements controls.
- **Assurance Owner:** evaluates evidence.
- **Operational Authority:** determines operational acceptability.
- **Audit:** independently examines governance implementation.

No single person should necessarily perform all roles for high-consequence systems.

## 29. Defence AI Crosswalk Architecture

For defence AI, the integrated crosswalk should cover at least:

**Governance**
→ Strategy, accountability, decision rights

**Mission**
→ Purpose, use case, consequence

**Risk**
→ Risk and autonomy

**Lifecycle**
→ Development, acquisition, change

**Data**
→ Quality, provenance, integrity

**Security**
→ Cybersecurity, AI security, adversarial threats

**Human Authority**
→ Oversight, intervention, accountability

**TEVV**
→ Testing, evaluation, verification, validation

**Environment**
→ Operational conditions

**Authorisation**
→ Permission to employ

**Employment**
→ Actual operational use

**Assurance**
→ Continuing confidence

**Incident**
→ Failure and protective response

**Audit**
→ Independent examination

**Workforce**
→ Competence and capacity

## 30. The Integrated Golden Thread

The complete D-AIGAAF crosswalk method should connect:

**External Requirement**
→ Mission Need
→ Risk
→ Requirements
→ Controls
→ Testing
→ Evidence
→ Assurance
→ Human Authority
→ Conditions
→ Boundaries
→ Operational Authorisation
→ Employment
→ Monitoring
→ Incident / Change
→ Learning
→ Revalidation
→ Reauthorisation

This is the **Crosswalk Golden Thread**.

It ensures that external governance requirements ultimately connect to actual operational behaviour.

## 31. Example — Responsible AI Requirement

Consider the principle:

> AI should remain governable.

The integrated method becomes:

**External Principle**
→ Governability

**D-AIGAAF Requirement**
→ The capability shall remain within defined human-authority and autonomy boundaries.

**Controls**
→ autonomy constraints
→ intervention
→ override
→ safe state
→ monitoring

**TEVV**
→ autonomy-boundary testing

**Evidence**
→ test results and configuration records

**Assurance**
→ evaluation of governability

**Authority**
→ operational authorisation

**Employment**
→ authorised autonomy level

**Monitoring**
→ detection of unexpected autonomy

**Change**
→ reassessment following model/system change

This demonstrates how a principle becomes an operational control chain.

## 32. Example — Security Requirement

External requirement:

**AI system should be protected against adversarial threats.**

D-AIGAAF translation:

**Threat Model**
→ adversarial attack identification

**Risk**
→ mission consequence

**Requirement**
→ security controls

**Control**
→ adversarial input protection

**TEVV**
→ adversarial evaluation

**Evidence**
→ red-team results

**Assurance**
→ residual security risk

**Authorisation**
→ defined operating conditions

**Monitoring**
→ attack detection

**Incident**
→ protective response

**Revalidation**
→ reassessment after compromise

## 33. Example — Data Protection Requirement

External requirement:

**Personal data must be processed in accordance with applicable law.**

D-AIGAAF translation:

**Applicability**
→ determine whether DPDP or other law applies

**Requirement**
→ applicable legal obligations

**Control**
→ data governance

**Evidence**
→ processing records and controls

**Assurance**
→ review

**Monitoring**
→ data governance and security monitoring

**Incident**
→ breach response

**Change**
→ reassess following material processing changes

This demonstrates why legal requirements must be translated into operational controls rather than simply listed in a compliance register.

## 34. Integrated Compliance Position

D-AIGAAF should not make the statement:

> “We comply with NIST, ISO, NATO, IndiaAI and other frameworks.”

unless the organisation has separately assessed the precise claims.

A more defensible position is:

> **The organisation has mapped applicable requirements from identified external frameworks to D-AIGAAF controls, assessed applicability, implemented relevant controls, maintained evidence, evaluated assurance and recorded outstanding gaps or exceptions.**

This is more precise and auditable.

## 35. Conformity Versus Alignment

D-AIGAAF distinguishes:

### Alignment

The framework addresses a similar objective.

### Implementation

A corresponding control has been established.

### Evidence

Implementation is demonstrable.

### Assurance

Evidence has been evaluated.

### Conformity

The applicable requirements have been assessed against the relevant conformity criteria.

### Authorisation

An authorised authority permits specified operational use.

These terms should not be used interchangeably.

## 36. Crosswalk Maturity

Organisations can assess their crosswalk capability.

### Level 1 — Inventory

External frameworks are identified.

### Level 2 — Mapping

Requirements are mapped to D-AIGAAF.

### Level 3 — Control

Requirements are linked to controls.

### Level 4 — Evidence

Controls have traceable evidence.

### Level 5 — Assurance

Evidence is independently or systematically assessed.

### Level 6 — Integrated Governance

Crosswalks influence risk, authorisation, monitoring and change.

This maturity scale is illustrative and should not be confused with the formal D-AIGAAF Maturity Model in Module 18.

## 37. Crosswalk Dashboard

An organisation may maintain a dashboard showing:

- number of external frameworks;
- applicable requirements;
- mapped requirements;
- implemented controls;
- evidence completeness;
- assurance status;
- open gaps;
- approved exceptions;
- overdue reviews;
- changed requirements;
- authorisation-impacting issues.

The dashboard should support governance decisions rather than become a purely administrative metric.

## 38. Automation and Tool Support

Where appropriate, crosswalk management can be supported by digital tools.

Potential capabilities include:

- requirements databases;
- version tracking;
- control mapping;
- evidence repositories;
- automated change alerts;
- compliance dashboards;
- audit trails.

Automation should not replace human interpretation.

Legal applicability, risk significance and operational authority require appropriate human judgement.

## 39. Limitations

This method does not:

- declare legal compliance automatically;
- replace legal advice;
- replace TEVV;
- replace security testing;
- replace independent assurance;
- replace operational authorisation;
- guarantee equivalence between frameworks;
- eliminate conflicts between requirements;
- guarantee that every future framework will map cleanly to D-AIGAAF.

The method is a structured governance approach for integration and alignment.

## 40. Implementation Checklist

Before declaring a crosswalk complete, confirm:

- [ ] Source identified.
- [ ] Current version confirmed.
- [ ] Authority classified.
- [ ] Applicability assessed.
- [ ] Requirements decomposed.
- [ ] D-AIGAAF modules identified.
- [ ] Mapping type classified.
- [ ] Controls identified.
- [ ] Evidence defined.
- [ ] Assurance assessed.
- [ ] Gaps recorded.
- [ ] Exceptions approved where required.
- [ ] Operational implications assessed.
- [ ] Authorisation implications assessed.
- [ ] Review date assigned.
- [ ] Ownership assigned.
- [ ] Change-monitoring mechanism established.

## 41. Final Integrated Alignment Model

The complete method is:

### Layer 1 — External Sources

**Law → Regulation → Policy → Standards → Frameworks → Principles → Guidance**

### Layer 2 — Applicability

**Who → What → Where → When → Why**

### Layer 3 — D-AIGAAF Mapping

**Mission → Risk → Lifecycle → Data → Security → Human Authority → TEVV → Environment → Authorisation → Employment → Assurance**

### Layer 4 — Control

**Requirement → Control → Evidence**

### Layer 5 — Assurance

**Evidence → Evaluation → Findings → Residual Risk → Confidence**

### Layer 6 — Authority

**Assurance → Conditions → Boundaries → Operational Authorisation**

### Layer 7 — Continuous Governance

**Employment → Monitoring → Incident / Change → Learning → Revalidation → Reauthorisation**

## 42. Final Crosswalk Principle

D-AIGAAF should function as a **living integration architecture**, not as a static list of external frameworks.

Its central proposition is:

> **No external framework should be treated as a checkbox. Its applicable requirements must be translated into D-AIGAAF controls, supported by evidence, subjected to appropriate assurance, and connected to human authority and operational decisions.**

The ultimate objective is not to maximise the number of frameworks mapped.

It is to establish a defensible governance chain:

**Applicable Requirement**
→ **Risk**
→ **Control**
→ **Evidence**
→ **Assurance**
→ **Authority**
→ **Operational Condition**
→ **Employment**
→ **Continuous Assurance**

This is the mechanism by which D-AIGAAF integrates Indian law and policy, international standards, responsible-AI principles, defence AI frameworks, TEVV methodologies and AI-security frameworks into one coherent defence AI governance architecture.
