# 20-Acquisition and Procurement Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 20 — Acquisition & Procurement**.

AI governance begins before an AI capability enters operational service. Acquisition and procurement decisions can determine whether the organisation can subsequently understand, control, secure, test, monitor, update, audit, revalidate and authorise the capability.

The central principle is:

> **An AI capability should not be acquired on the basis of technical performance alone; procurement should establish the rights, evidence, controls, dependencies and supplier obligations required for lifecycle governance and operational assurance.**

The acquisition lifecycle is:

**Need → Requirement → Market / Supplier Assessment → Solicitation → Evaluation → Contract → Acceptance → TEVV → Deployment → Assurance → Employment → Monitoring → Change → Reauthorisation → Exit**

---

# 2. Template Set

The recommended Acquisition & Procurement template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-20-001 | AI Acquisition & Procurement Governance Record |
| D-AIGAAF-T-20-002 | AI Acquisition Requirements Specification |
| D-AIGAAF-T-20-003 | Supplier / Solution Evaluation Record |
| D-AIGAAF-T-20-004 | Procurement Risk & Assurance Assessment |
| D-AIGAAF-T-20-005 | Supplier Due Diligence & Assurance Record |
| D-AIGAAF-T-20-006 | Contractual AI Governance Requirements Record |
| D-AIGAAF-T-20-007 | Acceptance, TEVV & Evidence Requirements Record |
| D-AIGAAF-T-20-008 | Supplier Change, Update & Notification Record |
| D-AIGAAF-T-20-009 | Acquisition Exception, Waiver & Risk Acceptance Record |
| D-AIGAAF-T-20-010 | Procurement Performance, Review & Exit Record |

---

# 3. Template 20-001 — AI Acquisition & Procurement Governance Record

## Purpose

Defines governance responsibilities for acquiring AI capabilities.

## Required Fields

- Acquisition ID
- Capability / programme
- Mission / use case
- Procurement authority
- Capability owner
- Operational authority
- Risk owner
- Security authority
- TEVV authority
- Legal / policy authority
- Commercial authority
- Supplier management authority
- Acceptance authority
- Review date

## Governance Questions

- Who owns the acquisition requirement?
- Who determines operational suitability?
- Who evaluates AI-specific risks?
- Who approves security requirements?
- Who determines evidence requirements?
- Who accepts supplier risk?
- Who authorises operational use?

---

# 4. Template 20-002 — AI Acquisition Requirements Specification

## Purpose

Defines governance, technical, operational and assurance requirements that suppliers must satisfy.

## Requirement Categories

### Mission

- intended use;
- mission objectives;
- operational constraints;
- success criteria.

### AI

- model capability;
- limitations;
- uncertainty;
- explainability / interpretability where required;
- autonomy.

### Security

- security architecture;
- access control;
- model integrity;
- logging;
- adversarial resilience.

### Data

- provenance;
- quality;
- lineage;
- retention;
- handling;
- data dependencies.

### Human Authority

- roles;
- oversight;
- intervention;
- override;
- accountability.

### TEVV

- testing;
- evaluation;
- evidence;
- independent assessment.

### Lifecycle

- updates;
- configuration;
- revalidation;
- reauthorisation;
- retirement.

---

# 5. Procurement Requirement Principle

Procurement requirements should answer:

> **What must the organisation be able to know, control, test, change, monitor and prove throughout the AI capability lifecycle?**

A supplier should not be evaluated solely on:

- benchmark score;
- price;
- technical specification;
- demonstration performance.

Those are inputs to the decision, not the complete governance basis.

---

# 6. Template 20-003 — Supplier / Solution Evaluation Record

## Purpose

Provides structured evaluation of candidate suppliers and solutions.

## Required Fields

- Supplier
- Solution
- Mission fit
- Technical capability
- AI risk
- Security
- Data
- Supply chain
- Human control
- TEVV
- Integration
- Operational environment
- Lifecycle support
- Cost
- Sovereignty
- Continuity
- Exit capability
- Overall assessment
- Recommendation

## Evaluation Principle

A solution should be assessed against the **complete lifecycle**, not only initial acquisition.

---

# 7. Supplier Evaluation Dimensions

Consider:

| Dimension | Key Question |
|---|---|
| Capability | Does it perform the intended function? |
| Assurance | Can its claims be independently assessed? |
| Security | Can it withstand relevant threats? |
| Transparency | Can the organisation understand material dependencies and limitations? |
| Control | Can behaviour and access be governed? |
| Change | Can updates be detected and controlled? |
| Sovereignty | Are strategic dependencies acceptable? |
| Continuity | Can the capability be sustained? |
| Exit | Can the organisation transition away? |

---

# 8. Template 20-004 — Procurement Risk & Assurance Assessment

## Purpose

Assesses risks created by acquiring a particular AI capability or supplier relationship.

## Risk Areas

Consider:

- mission failure;
- safety;
- autonomy;
- human control;
- cybersecurity;
- model risk;
- data risk;
- supplier dependency;
- foreign dependency;
- intellectual property;
- update risk;
- cloud dependency;
- availability;
- vendor lock-in;
- legal / regulatory;
- operational continuity.

## Required Fields

- Risk
- Cause
- Consequence
- Likelihood
- Existing control
- Supplier control
- Customer control
- Residual risk
- Evidence
- Risk owner
- Acceptance authority

---

# 9. Shared Responsibility

Procurement should explicitly distinguish:

**Supplier Responsibility**

from

**Customer / Defence Organisation Responsibility**

and

**Shared Responsibility**

For example:

| Area | Supplier | Customer | Shared |
|---|---:|---:|---:|
| Model development | ✓ | | |
| Mission configuration | | ✓ | |
| Operational employment | | ✓ | |
| Security integration | | | ✓ |
| TEVV | | | ✓ |
| Updates | ✓ | ✓ | ✓ |
| Operational authorisation | | ✓ | |
| Incident response | ✓ | ✓ | ✓ |

The exact allocation depends on the capability and contract.

---

# 10. Template 20-005 — Supplier Due Diligence & Assurance Record

## Purpose

Assesses whether a supplier can support the governance requirements of the capability.

## Due Diligence Areas

Consider:

- ownership;
- corporate structure;
- relevant jurisdictions;
- development practices;
- AI governance;
- security;
- data practices;
- model provenance;
- subcontractors;
- supply chain;
- update mechanisms;
- incident history;
- assurance practices;
- workforce competence;
- continuity;
- financial resilience.

## Required Fields

- Supplier
- Assessment area
- Evidence requested
- Evidence received
- Finding
- Risk
- Confidence
- Follow-up
- Decision

Supplier assurances should be independently evaluated where material.

---

# 11. Supplier Evidence

Potential evidence may include:

- architecture documentation;
- model documentation;
- security assessments;
- TEVV results;
- test reports;
- vulnerability information;
- data provenance;
- software bill of materials;
- model/component provenance;
- change records;
- incident history;
- assurance reports;
- certifications;
- independent assessments.

A supplier statement should not automatically be treated as independent assurance.

---

# 12. Template 20-006 — Contractual AI Governance Requirements Record

## Purpose

Translates D-AIGAAF requirements into contractual obligations.

## Contractual Areas

Consider requirements for:

- configuration disclosure;
- model identification;
- data provenance;
- security;
- vulnerability notification;
- incident notification;
- material change notification;
- update approval;
- TEVV cooperation;
- audit rights;
- evidence access;
- logging;
- subcontractor disclosure;
- supply chain visibility;
- continuity;
- exit assistance;
- deletion / return of data;
- intellectual property;
- liability;
- service levels.

## Required Fields

- Requirement
- Contract clause
- Supplier obligation
- Customer obligation
- Evidence
- Enforcement mechanism
- Owner
- Review date

---

# 13. Material Change Notification

Contracts should define what constitutes a material supplier change.

Examples:

- model replacement;
- model-weight changes;
- fine-tuning;
- major software update;
- new data source;
- new external service;
- changed hosting;
- changed jurisdiction;
- changed security architecture;
- changed tool permissions;
- changed autonomy behaviour.

Where material, changes should trigger D-AIGAAF change governance.

---

# 14. Template 20-007 — Acceptance, TEVV & Evidence Requirements Record

## Purpose

Defines what must be demonstrated before accepting an acquired AI capability.

## Required Fields

- Requirement
- Acceptance criterion
- Test method
- Evidence
- Configuration
- Environment
- Responsible authority
- Supplier involvement
- Independent review
- Finding
- Acceptance decision

## Acceptance Areas

Consider:

- mission performance;
- reliability;
- robustness;
- security;
- human control;
- autonomy;
- environmental performance;
- fail-safe;
- interoperability;
- maintainability;
- documentation;
- training;
- support.

---

# 15. Acceptance Is Not Operational Authorisation

D-AIGAAF distinguishes:

**Contract Award**
→ **Delivery**
→ **Acceptance**
→ **TEVV / Assurance**
→ **Operational Readiness**
→ **Operational Authorisation**
→ **Employment**

Acceptance of a product does not automatically authorise its operational use.

---

# 16. Template 20-008 — Supplier Change, Update & Notification Record

## Purpose

Controls supplier-originated changes during the lifecycle.

## Required Fields

- Supplier
- Capability
- Change
- Change category
- Previous state
- New state
- Notification date
- Impact
- Risk
- Evidence
- TEVV requirement
- Revalidation requirement
- Reauthorisation requirement
- Implementation decision

## Principle

External updates should not silently change the authorised configuration.

---

# 17. External Service Dependencies

For AI capabilities dependent on external services, assess:

- availability;
- latency;
- connectivity;
- jurisdiction;
- data transfer;
- service changes;
- model changes;
- rate limits;
- outage;
- vendor access;
- security;
- continuity.

A capability may have different operational risk when disconnected from its external dependency.

---

# 18. Template 20-009 — Acquisition Exception, Waiver & Risk Acceptance Record

## Purpose

Provides controlled governance for procurement exceptions.

## Required Fields

- Requirement
- Exception
- Reason
- Risk
- Consequence
- Compensating control
- Duration
- Authority
- Supplier impact
- Evidence
- Review date
- Exit condition

Exceptions should be:

- explicit;
- bounded;
- risk assessed;
- authorised;
- monitored;
- reviewed.

A procurement waiver should not silently become permanent operational acceptance.

---

# 19. Template 20-010 — Procurement Performance, Review & Exit Record

## Purpose

Reviews supplier performance and ensures that the organisation can safely sustain or exit the capability.

## Performance Areas

- mission performance;
- availability;
- security;
- incident response;
- update management;
- evidence quality;
- supplier responsiveness;
- contractual compliance;
- support;
- interoperability;
- continuity.

## Exit Assessment

Consider:

- alternative supplier;
- replacement capability;
- data migration;
- model migration;
- configuration transfer;
- knowledge transfer;
- contract termination;
- dependency removal;
- secure data disposal;
- credential revocation.

---

# 20. Acquisition and Sovereignty

Sovereignty should be assessed according to the actual strategic dependency.

Consider:

- model ownership;
- critical intellectual property;
- data location;
- compute dependency;
- cloud dependency;
- foreign legal exposure;
- supplier concentration;
- availability of substitutes;
- domestic support capability;
- crisis continuity.

Country of origin alone is not a sufficient sovereignty assessment.

---

# 21. Acquisition and Supply Chain

Procurement should establish visibility of critical dependencies.

Where relevant, identify:

**Supplier**
→ **Subsupplier**
→ **Component**
→ **Model**
→ **Data**
→ **Infrastructure**
→ **Service**
→ **Operational Capability**

Unknown critical dependencies should increase procurement and assurance risk.

---

# 22. Acquisition and AI Security

Procurement should consider security throughout the lifecycle.

Requirements may include:

- secure development;
- vulnerability management;
- access control;
- model integrity;
- supply-chain security;
- logging;
- incident notification;
- adversarial testing;
- secure update mechanisms;
- secure decommissioning.

Security requirements should be established before contract award where possible rather than discovered after deployment.

---

# 23. Acquisition and Human Authority

Procurement requirements should ensure that human-control mechanisms are technically and operationally supportable.

Consider:

- interface;
- alerting;
- uncertainty presentation;
- intervention;
- override;
- access control;
- audit logs;
- operator configuration;
- training;
- workload.

The supplier should not be able to define human authority merely through product defaults.

Operational authority remains with the authorised defence organisation.

---

# 24. Acquisition and TEVV

Procurement should establish rights to:

- test;
- inspect;
- evaluate;
- red-team;
- reproduce relevant results;
- access required evidence;
- conduct independent assessment where necessary.

A system that cannot be adequately evaluated may create an assurance limitation regardless of technical performance.

---

# 25. Acquisition and Configuration Management

The contract should establish sufficient information to identify the operational configuration.

Where material, maintain visibility of:

- model version;
- software;
- firmware;
- hardware;
- data;
- instructions;
- tools;
- APIs;
- external services;
- security controls.

This supports the D-AIGAAF principle:

> **No material governance decision should depend on an unknown system configuration.**

---

# 26. Acquisition and Continuous Assurance

Procurement should support assurance after delivery.

Relevant contractual mechanisms may include:

- ongoing evidence provision;
- performance reporting;
- vulnerability notification;
- incident notification;
- change notification;
- audit rights;
- periodic assessment;
- supplier reviews.

Acquisition should therefore be designed for the **whole AI lifecycle**, not just the purchase event.

---

# 27. Acquisition and Operational Environment

Supplier testing should be assessed for relevance to the intended operational environment.

A system demonstrated in:

**Controlled Laboratory Environment**

may not automatically be suitable for:

**Degraded / Disconnected / Adversarial Operational Environment**

Procurement requirements should specify relevant environmental assumptions where necessary.

---

# 28. Acquisition and Emergency Procurement

Urgent operational requirements may compress procurement timelines.

However, emergency procurement should still identify, as far as practicable:

- mission need;
- critical risks;
- minimum evidence;
- security requirements;
- human-control requirements;
- supplier dependencies;
- compensating controls;
- acceptance authority;
- post-acquisition TEVV;
- review conditions.

Speed should not eliminate the ability to understand what has been acquired.

---

# 29. Acquisition and Vendor Lock-In

Vendor lock-in can create strategic risk when the organisation cannot:

- change supplier;
- migrate data;
- migrate models;
- maintain operations;
- audit the capability;
- control updates;
- operate without proprietary infrastructure.

Exit requirements should therefore be considered during procurement rather than only at contract termination.

---

# 30. Acquisition and Intellectual Property

Procurement should distinguish rights concerning:

- model;
- weights;
- source code;
- configuration;
- prompts/instructions;
- training data;
- operational data;
- logs;
- evaluation results;
- derived artifacts.

The organisation should obtain sufficient rights to govern, assure, secure, investigate and safely retire the capability.

---

# 31. Acquisition and Incident Response

Contracts should define supplier responsibilities for significant AI incidents.

Consider:

- notification time;
- information provided;
- technical support;
- evidence preservation;
- forensic support;
- vulnerability disclosure;
- remediation;
- recovery;
- revalidation;
- reauthorisation.

Incident responsibility should not become ambiguous because multiple suppliers are involved.

---

# 32. Acquisition Governance Decision

Before procurement proceeds, the responsible authority should be able to answer:

1. Is the capability suitable for the mission?
2. Can its risks be understood?
3. Can it be adequately tested?
4. Can its configuration be controlled?
5. Can human authority be maintained?
6. Can security be assured?
7. Can supplier dependencies be governed?
8. Can material changes be detected?
9. Can the capability be sustained?
10. Can the organisation exit safely?

---

# 33. Anti-Pattern — Lowest Price / Highest Benchmark Wins

D-AIGAAF rejects acquisition decisions based solely on:

- lowest price;
- highest benchmark;
- most features;
- fastest delivery.

A technically superior system may be unsuitable if it cannot be:

- assured;
- secured;
- governed;
- controlled;
- maintained;
- audited;
- safely authorised.

---

# 34. Anti-Pattern — Procurement Ends at Delivery

AI governance does not end when the product is delivered.

The relevant lifecycle is:

**Acquire**
→ **Accept**
→ **Assure**
→ **Authorise**
→ **Employ**
→ **Monitor**
→ **Change**
→ **Reassess**
→ **Reauthorise**
→ **Retire**

Contracts should support this lifecycle.

---

# 35. Anti-Pattern — Supplier Assurance Transfers Accountability

Supplier evidence can support assurance.

It does not automatically transfer operational accountability to the supplier.

The organisation responsible for operational employment remains responsible for ensuring that its own:

- risk;
- authority;
- mission;
- environment;
- human control;
- authorisation

are appropriately governed.

---

# 36. Anti-Pattern — Black-Box Procurement

A system should not be treated as acceptable merely because:

> “The supplier says it works.”

Where consequence warrants it, the procuring organisation should seek sufficient visibility into:

- limitations;
- dependencies;
- configuration;
- evidence;
- security;
- change mechanisms;
- failure modes.

Commercial confidentiality may constrain disclosure, but it should not be allowed to create unacceptable governance blindness.

---

# 37. Acquisition Golden Thread Integration

Acquisition connects to the D-AIGAAF Golden Thread:

**Mission Need**
→ **Use Case**
→ **Requirements**
→ **Procurement Requirement**
→ **Supplier / Solution**
→ **Risk**
→ **Controls**
→ **TEVV**
→ **Evidence**
→ **Acceptance**
→ **Assurance**
→ **Operational Authorisation**
→ **Employment**
→ **Monitoring**
→ **Change**
→ **Revalidation / Reauthorisation**
→ **Retirement / Exit**

Procurement is therefore an early governance control rather than an administrative purchasing function.

---

# 38. Final Acquisition & Procurement Principle

D-AIGAAF treats acquisition as a lifecycle governance decision.

The governing principle is:

> **An AI capability should be procured only when the organisation can establish, to a degree proportionate to consequence and risk, the contractual, technical, operational and governance conditions necessary to understand, control, secure, test, assure, monitor, change and ultimately retire the capability; technical performance and commercial value alone are insufficient.**
