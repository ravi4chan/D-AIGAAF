# 00-Templates Governance and Template Architecture

## 1. Purpose

This document defines the governance architecture for the D-AIGAAF template library.

The templates in Module 20 translate D-AIGAAF requirements into practical, reusable working documents and records.

They are intended to support:

- governance;
- mission definition;
- risk assessment;
- lifecycle management;
- data governance;
- AI security;
- human authority;
- TEVV;
- operational environment assessment;
- operational authorisation;
- operational employment;
- continuous assurance;
- incident management;
- change and reauthorisation;
- audit and evidence;
- workforce management;
- procurement;
- interoperability;
- architecture;
- documentation;
- retirement.

Templates are implementation aids. They do not replace judgement, policy, legal interpretation, technical assessment, operational authority or assurance.

## 2. Template Design Principle

Every template should answer five questions:

1. **What decision, assessment or record is this template supporting?**
2. **Who is responsible for completing it?**
3. **What evidence is required?**
4. **Who reviews or approves it?**
5. **How does it connect to the D-AIGAAF Golden Thread?**

A template should therefore be treated as a governance instrument, not merely as a form.

## 3. Template Architecture

Module 20 should provide reusable templates corresponding to the major governance activities in D-AIGAAF.

A recommended structure is:

| Serial | Template Area |
|---:|---|
| 00 | Template Governance and Architecture |
| 01 | Strategy and Governance Templates |
| 02 | Mission and Use Case Templates |
| 03 | Risk and Autonomy Templates |
| 04 | AI Lifecycle Templates |
| 05 | Data and Information Templates |
| 06 | AI Security Templates |
| 07 | Supply Chain and Sovereignty Templates |
| 08 | Human Authority Templates |
| 09 | TEVV Templates |
| 10 | Operational Environment Templates |
| 11 | Operational Authorisation Templates |
| 12 | Operational Employment Templates |
| 13 | Continuous Assurance Templates |
| 14 | Incident and Fail-Safe Templates |
| 15 | Change and Reauthorisation Templates |
| 16 | Audit and Evidence Templates |
| 17 | Workforce Templates |
| 18 | Maturity Assessment Templates |
| 19 | Crosswalk Templates |
| 20 | Acquisition and Procurement Templates |
| 21 | Interoperability and Coalition Templates |
| 22 | Architecture and Technical Control Templates |
| 23 | Documentation and Knowledge Templates |
| 24 | Retirement and Decommissioning Templates |
| 25 | Implementation and Programme Templates |

This structure may be expanded or consolidated during implementation without changing the underlying D-AIGAAF architecture.

## 4. Template Categories

Templates should be classified into four broad categories.

### 4.1 Planning Templates

Used before or during capability development.

Examples:

- mission definition;
- use-case definition;
- requirements;
- risk assessment;
- TEVV plan;
- security plan;
- implementation plan.

### 4.2 Decision Templates

Used to support governance decisions.

Examples:

- risk acceptance;
- autonomy approval;
- operational readiness;
- operational authorisation;
- change approval;
- reauthorisation.

### 4.3 Evidence Templates

Used to create structured records.

Examples:

- test record;
- assurance record;
- incident record;
- audit finding;
- training record;
- configuration record.

### 4.4 Monitoring Templates

Used after deployment.

Examples:

- performance monitoring;
- assurance review;
- incident monitoring;
- change monitoring;
- lessons learned;
- continuous improvement.

## 5. Minimum Template Metadata

Every D-AIGAAF template should contain, where applicable:

| Field | Purpose |
|---|---|
| Template ID | Unique identifier |
| Template Name | Official name |
| D-AIGAAF Module | Primary module |
| Version | Template version |
| Classification | Information classification |
| Owner | Responsible authority |
| Approver | Approval authority |
| Effective Date | Date of use |
| Review Date | Scheduled review |
| Related Documents | Connected records |
| Related Controls | D-AIGAAF controls |
| Related Risks | Relevant risks |
| Related Authorisation | Relevant authority |
| Retention | Record retention requirement |

The exact metadata should be adapted to the organisation's records-management regime.

## 6. Template Identification

A consistent naming convention should be used.

Recommended pattern:

`D-AIGAAF-T-[MODULE]-[NUMBER]-[SHORT NAME]`

Example:

`D-AIGAAF-T-11-001-Operational-Authorisation`

The identifier should remain stable even when the template wording changes.

## 7. Template Status

Each template should have a controlled status:

- Draft;
- Under Review;
- Approved;
- Active;
- Superseded;
- Retired.

Only approved and active versions should normally be used for formal governance activity.

## 8. Template Versus Record

A critical distinction must be maintained.

### Template

The reusable structure.

### Completed Template

A populated governance record.

### Evidence

Information demonstrating that a requirement or control has been implemented or performed.

A completed template may itself constitute evidence, but it is not automatically sufficient evidence.

## 9. Template-to-Control Relationship

Templates should be linked to D-AIGAAF controls.

Example:

**Requirement**

Human intervention capability shall be defined.

**Control**

Human intervention and override mechanisms are established.

**Template**

Human Authority and Intervention Assessment.

**Evidence**

Completed assessment + test results + approval record.

**Assurance**

Independent or designated review.

This creates traceability from governance requirement to operational evidence.

## 10. Template-to-Golden-Thread Relationship

Templates should support the D-AIGAAF Golden Thread:

**Mission Need**
→ **Risk**
→ **Requirements**
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

A template that cannot be connected to a meaningful governance activity should be reconsidered.

## 11. Required Sections for Decision Templates

Decision-oriented templates should normally contain:

1. Decision required.
2. Decision owner.
3. Relevant capability.
4. Mission/use case.
5. Applicable environment.
6. Risk position.
7. Autonomy level.
8. Human authority.
9. Evidence.
10. Assurance position.
11. Options.
12. Constraints.
13. Residual risk.
14. Recommendation.
15. Decision.
16. Conditions.
17. Review/reconsideration trigger.
18. Record of approval.

## 12. Required Sections for Assessment Templates

Assessment templates should normally contain:

- scope;
- objective;
- assessment criteria;
- evidence reviewed;
- methodology;
- findings;
- limitations;
- uncertainty;
- risk implications;
- corrective actions;
- conclusion;
- reviewer;
- date;
- approval.

## 13. Evidence and Traceability

Templates should provide fields for traceability wherever practical.

Examples:

- requirement ID;
- risk ID;
- control ID;
- test ID;
- finding ID;
- incident ID;
- change ID;
- authorisation ID;
- configuration baseline;
- evidence reference.

This allows governance records to be connected without repeatedly reproducing the same information.

## 14. Uncertainty

Templates should not force artificial certainty.

Where relevant, they should include:

- confidence level;
- known limitations;
- unknowns;
- assumptions;
- unresolved findings;
- evidence gaps;
- disagreement;
- dissenting assessment.

For high-consequence AI, the absence of evidence should remain visible rather than being converted into an implicit positive conclusion.

## 15. Human Accountability

Decision templates should identify the human authority responsible for consequential decisions.

Where applicable, record:

- decision maker;
- delegated authority;
- technical adviser;
- operational adviser;
- assurance authority;
- legal/policy adviser;
- security authority.

The AI system itself should not be represented as the holder of human legal or command authority unless an applicable governance regime explicitly establishes such authority.

## 16. Autonomy

Where AI autonomy is relevant, templates should record the applicable D-AIGAAF autonomy level:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

The selected level should be justified by the actual system behaviour and mission context.

## 17. Operational Conditions

Templates supporting authorisation or employment should capture conditions such as:

- geographic boundaries;
- temporal boundaries;
- mission boundaries;
- target/object boundaries where applicable;
- data boundaries;
- connectivity requirements;
- environmental constraints;
- human supervision;
- intervention requirements;
- prohibited uses;
- escalation conditions;
- fail-safe requirements.

## 18. Template Quality Criteria

Before approval, a template should be checked for:

### Relevance
Does it support a real governance activity?

### Completeness
Are material decisions and evidence covered?

### Usability
Can personnel realistically complete it?

### Traceability
Can entries be linked to requirements and evidence?

### Authority
Are approval and accountability clear?

### Security
Does it handle sensitive information appropriately?

### Auditability
Can an independent reviewer understand what occurred?

### Maintainability
Can it be updated without unnecessary redesign?

## 19. Avoiding Template Proliferation

D-AIGAAF should avoid creating a separate form for every minor activity.

Where several activities share a governance objective, a modular template should be preferred.

For example, a common **Assessment Record** may support:

- security assessment;
- environment assessment;
- human-control assessment;
- data assurance assessment.

Optional sections can be activated according to context.

This reduces administrative burden while preserving governance depth.

## 20. Mandatory Versus Optional Fields

Templates should distinguish:

**Mandatory**

Required for all applicable uses.

**Conditional**

Required only when a specified condition applies.

**Optional**

Useful supporting information.

Example:

**Autonomy Level**

Conditional when AI can influence or initiate consequential action.

**Human Intervention Authority**

Mandatory for A3–A5 capabilities.

**Coalition Interoperability Assessment**

Conditional where coalition interoperability is relevant.

## 21. Template Tailoring

Templates may be tailored for:

- organisation;
- service;
- mission;
- AI capability;
- classification;
- risk level;
- autonomy;
- operational environment.

However, tailoring should not remove controls that are mandatory under applicable law, policy or authorisation conditions.

Material tailoring should be documented.

## 22. Classification and Information Handling

Templates may contain sensitive information.

Users should follow the applicable information-classification and handling regime.

Templates should therefore avoid embedding assumptions about classification markings that may vary between organisations.

Where appropriate, the template should provide a field for:

- classification;
- handling caveats;
- releasability;
- dissemination restrictions.

## 23. Approval and Electronic Records

Templates may be implemented as:

- Markdown;
- Word documents;
- spreadsheets;
- forms;
- workflow systems;
- databases;
- governance platforms.

The format is secondary to the governance function.

Electronic workflows should preserve:

- identity;
- authority;
- timestamp;
- version;
- decision;
- evidence;
- audit trail.

## 24. Template Change Management

Changes to an approved template should be controlled.

The process should include:

**Change Request**
→ Impact Assessment
→ Review
→ Approval
→ Version Update
→ Publication
→ User Notification
→ Transition
→ Record Retention

Changes affecting governance meaning or required evidence should receive appropriate governance review.

## 25. Template Retirement

A template may be retired when:

- its governance activity no longer exists;
- it is replaced;
- its requirements are incorporated elsewhere;
- the underlying framework changes.

Retirement should preserve historical completed records according to applicable retention requirements.

## 26. Template Library Governance

The template library should maintain:

- master versions;
- ownership;
- approval status;
- change history;
- relationships to D-AIGAAF modules;
- dependencies;
- review dates;
- superseded versions.

Users should be able to determine which version was authorised for use at a particular point in time.

## 27. Recommended Template Dependency Model

Templates should be linked rather than treated as isolated documents.

Example:

**Mission Definition**
→ **Use Case**
→ **Risk Assessment**
→ **Requirements**
→ **TEVV Plan**
→ **Security Assessment**
→ **Operational Environment Assessment**
→ **Authorisation Package**
→ **Employment Record**
→ **Continuous Assurance**
→ **Incident / Change Record**
→ **Reauthorisation**

This provides a practical document-level representation of the D-AIGAAF lifecycle.

## 28. Template Evidence Hierarchy

Where appropriate, evidence should be prioritised according to strength.

A practical hierarchy is:

1. Direct operational evidence.
2. Independent test/evaluation evidence.
3. Controlled test evidence.
4. Verified technical evidence.
5. Approved documentation.
6. Process records.
7. Self-attestation.
8. Unsupported assertion.

The hierarchy is contextual and should not be treated as a universal scoring rule.

## 29. Template Review Questions

Before using a template, the responsible authority should ask:

- Does this template support the actual decision or activity?
- Is the applicable D-AIGAAF requirement clear?
- Are responsibilities clear?
- Are mandatory fields identified?
- Is sufficient evidence captured?
- Is uncertainty visible?
- Is human authority identified?
- Are relevant risks captured?
- Is the record traceable?
- Can the resulting record support audit or assurance?
- Does completion meaningfully affect governance?

## 30. Anti-Compliance-Theatre Principle

Templates must not become evidence of governance merely because they have been completed.

A completed form does not prove:

- that the control works;
- that the risk is acceptable;
- that the AI is safe;
- that the system is secure;
- that operational conditions are satisfied;
- that the capability is authorised.

Therefore:

> **D-AIGAAF templates document governance; they do not substitute for governance.**

## 31. Relationship to External Frameworks

Templates should support the integrated crosswalk methodology in Module 19.

External requirements should follow:

**External Source**
→ **Applicability**
→ **Requirement**
→ **D-AIGAAF Control**
→ **Template / Record**
→ **Evidence**
→ **Assurance**
→ **Authorisation**

This allows one template to support multiple compatible external requirements without creating duplicate administrative processes.

## 32. Minimum Template Governance Checklist

Before a template is placed into active use:

- [ ] Purpose defined.
- [ ] D-AIGAAF module identified.
- [ ] Owner assigned.
- [ ] Approver assigned.
- [ ] Version assigned.
- [ ] Applicability defined.
- [ ] Mandatory fields identified.
- [ ] Conditional fields identified.
- [ ] Evidence requirements defined.
- [ ] Traceability fields included.
- [ ] Human authority identified where relevant.
- [ ] Security/classification considerations addressed.
- [ ] Review cycle defined.
- [ ] Change process defined.
- [ ] Supersession process defined.
- [ ] Records-retention requirements considered.

## 33. Final Principle

The D-AIGAAF template library should make the framework **implementable without making it bureaucratic**.

The desired outcome is a connected set of practical instruments that enable organisations to move from:

**Principle**
→ **Requirement**
→ **Control**
→ **Action**
→ **Evidence**
→ **Assurance**
→ **Decision**
→ **Operational Authority**
→ **Continuous Governance**

Templates are therefore the operational interface between the D-AIGAAF architecture and the people who must implement, assure, authorise and govern defence AI.
