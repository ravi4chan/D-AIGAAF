# 07-Supply Chain and Sovereignty Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 07 — Supply Chain & Sovereignty**.

These templates provide practical instruments for governing the organisations, technologies, data, models, software, hardware, services and dependencies that contribute to a defence AI capability.

The central principle is:

> **An organisation cannot fully govern an AI capability if it cannot understand, control and assure the critical external dependencies through which that capability is developed, supplied, updated, operated or sustained.**

Supply-chain governance should consider not only procurement risk, but also:

- provenance;
- strategic dependency;
- foreign dependency;
- concentration risk;
- supplier access;
- update authority;
- software dependencies;
- model dependencies;
- data dependencies;
- infrastructure dependencies;
- continuity;
- substitution;
- sovereignty;
- security;
- exit capability.

---

# 2. Template Set

The recommended Supply Chain & Sovereignty template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-07-001 | Supply Chain Governance Record |
| D-AIGAAF-T-07-002 | AI Supply Chain Register |
| D-AIGAAF-T-07-003 | Supplier Risk Assessment |
| D-AIGAAF-T-07-004 | AI Component Provenance Record |
| D-AIGAAF-T-07-005 | Supplier Assurance Assessment |
| D-AIGAAF-T-07-006 | Third-Party Dependency Assessment |
| D-AIGAAF-T-07-007 | Strategic Dependency Assessment |
| D-AIGAAF-T-07-008 | Sovereignty Assessment |
| D-AIGAAF-T-07-009 | Supplier Access & Privilege Assessment |
| D-AIGAAF-T-07-010 | Supplier Change & Update Assessment |
| D-AIGAAF-T-07-011 | Supply Chain Security Assessment |
| D-AIGAAF-T-07-012 | Supply Chain Continuity Assessment |
| D-AIGAAF-T-07-013 | Substitution & Exit Assessment |
| D-AIGAAF-T-07-014 | Supplier Incident Record |
| D-AIGAAF-T-07-015 | Supply Chain Exception Record |
| D-AIGAAF-T-07-016 | Supply Chain Governance Review |

---

# 3. Template 07-001 — Supply Chain Governance Record

## Purpose

Defines governance responsibility for supply-chain risks associated with an AI capability.

## Required Fields

- Capability ID
- Mission ID
- Use Case ID
- Supply-chain owner
- Procurement authority
- Security authority
- Technical authority
- Risk owner
- Assurance authority
- Operational authority
- Authorisation authority
- Critical suppliers
- Review date

## Governance Questions

- Who owns supplier risk?
- Who approves material dependencies?
- Who can accept supplier-related risk?
- Who can require supplier remediation?
- Who can suspend use of a supplier component?
- Who can approve a supplier change?

---

# 4. Template 07-002 — AI Supply Chain Register

## Purpose

Provides an authoritative inventory of components and suppliers supporting the AI capability.

## Component Categories

Include, where applicable:

- foundation models;
- specialised models;
- software;
- libraries;
- datasets;
- hardware;
- chips;
- sensors;
- firmware;
- cloud services;
- APIs;
- platforms;
- tools;
- security services;
- support services;
- maintenance services.

## Required Fields

- Component ID
- Component
- Supplier
- Subsupplier
- Country/jurisdiction
- Function
- Criticality
- Dependency
- Security status
- Assurance status
- Contract
- Update mechanism
- Alternative
- Review date

---

# 5. Template 07-003 — Supplier Risk Assessment

## Purpose

Assesses risks associated with a supplier.

## Assessment Areas

- financial;
- technical;
- security;
- geopolitical;
- legal;
- regulatory;
- continuity;
- concentration;
- ownership;
- personnel access;
- intellectual property;
- data access;
- update control;
- strategic dependency.

## Required Fields

- Supplier
- Risk
- Likelihood
- Consequence
- Existing controls
- Residual risk
- Treatment
- Owner
- Review date

Risk assessment should consider both the supplier and the specific capability being supplied.

---

# 6. Template 07-004 — AI Component Provenance Record

## Purpose

Records the origin and chain of custody of material AI components.

## Components

Consider:

- model;
- model weights;
- datasets;
- software;
- libraries;
- firmware;
- hardware;
- configuration;
- tools.

## Required Fields

- Component ID
- Component
- Original source
- Supplier
- Version
- Build/source information
- Dependencies
- Modifications
- Verification
- Integrity evidence
- Provenance confidence

The organisation should be able to establish what it is actually operating.

---

# 7. Template 07-005 — Supplier Assurance Assessment

## Purpose

Assesses evidence provided by suppliers regarding the security, reliability and governance of their products or services.

## Evidence Areas

- technical documentation;
- security controls;
- testing;
- certifications;
- assurance reports;
- vulnerability management;
- development practices;
- supply-chain controls;
- incident history;
- update governance.

## Required Fields

- Supplier
- Evidence
- Scope
- Date
- Independence
- Limitations
- Findings
- Confidence
- Residual risk
- Acceptance

Supplier assertions should not automatically be treated as independent assurance.

---

# 8. Template 07-006 — Third-Party Dependency Assessment

## Purpose

Identifies dependencies on third parties that could affect mission performance or governance.

## Dependency Categories

- model provider;
- data provider;
- cloud provider;
- network provider;
- software supplier;
- hardware supplier;
- specialist service;
- external API;
- security service;
- maintenance provider.

## Required Fields

- Dependency
- Provider
- Function
- Criticality
- Failure consequence
- Availability
- Alternative
- Recovery
- Monitoring
- Contractual control
- Owner

---

# 9. Template 07-007 — Strategic Dependency Assessment

## Purpose

Assesses whether a dependency creates significant strategic or operational vulnerability.

## Factors

Consider:

- single-source dependency;
- foreign dependency;
- concentration;
- lack of substitutes;
- proprietary interfaces;
- supplier control over updates;
- supplier access to sensitive information;
- export restrictions;
- geopolitical risk;
- sanctions;
- supply disruption;
- technology lock-in.

## Required Fields

- Dependency
- Strategic importance
- Dependency level
- Vulnerability
- Consequence
- Mitigation
- Alternative
- Time to substitute
- Owner

---

# 10. Template 07-008 — Sovereignty Assessment

## Purpose

Assesses sovereignty considerations associated with the AI capability.

## Assessment Areas

### Technology

- critical hardware;
- software;
- model dependence;
- intellectual property.

### Data

- data location;
- data control;
- data jurisdiction;
- external access.

### Infrastructure

- cloud;
- networks;
- compute;
- hosting.

### Operations

- external support;
- external maintenance;
- update authority.

### Strategic

- foreign dependence;
- continuity;
- ability to operate independently;
- ability to replace critical components.

## Required Fields

- Sovereignty issue
- Dependency
- Jurisdiction
- Consequence
- Mitigation
- Residual concern
- Authority

Sovereignty is context-dependent and should not be reduced to country-of-origin alone.

---

# 11. Template 07-009 — Supplier Access & Privilege Assessment

## Purpose

Assesses supplier access to AI systems, data, infrastructure and operational environments.

## Access Categories

- remote access;
- maintenance access;
- administrative access;
- development access;
- data access;
- model access;
- support access.

## Required Fields

- Supplier
- Identity
- Role
- Access
- Privilege
- Purpose
- Duration
- Approval
- Monitoring
- Revocation mechanism

Supplier access should follow least-privilege principles.

---

# 12. Template 07-010 — Supplier Change & Update Assessment

## Purpose

Determines the impact of supplier-provided changes.

## Change Categories

- model update;
- software update;
- security patch;
- firmware update;
- hardware replacement;
- dataset update;
- API change;
- tool change;
- configuration change.

## Assessment

Determine impact on:

- mission;
- risk;
- security;
- autonomy;
- performance;
- dependencies;
- TEVV;
- assurance;
- authorisation.

Supplier-controlled updates should not bypass D-AIGAAF change governance.

---

# 13. Template 07-011 — Supply Chain Security Assessment

## Purpose

Assesses security threats introduced through the supply chain.

## Threats

Consider:

- malicious components;
- compromised software;
- compromised models;
- malicious datasets;
- counterfeit hardware;
- backdoors;
- compromised update mechanisms;
- insider threats;
- supplier compromise;
- dependency vulnerabilities.

## Required Fields

- Threat
- Component
- Attack path
- Likelihood
- Consequence
- Control
- Detection
- Response
- Residual risk

---

# 14. Template 07-012 — Supply Chain Continuity Assessment

## Purpose

Assesses whether critical AI capabilities can continue operating if a supplier or dependency becomes unavailable.

## Scenarios

Consider:

- supplier failure;
- geopolitical disruption;
- export restrictions;
- sanctions;
- cyber attack;
- network outage;
- cloud outage;
- component shortage;
- supplier withdrawal;
- support termination.

## Required Fields

- Dependency
- Failure scenario
- Mission impact
- Duration tolerance
- Alternative
- Stock / reserve
- Recovery time
- Degraded mode
- Owner

---

# 15. Template 07-013 — Substitution & Exit Assessment

## Purpose

Determines whether critical AI components can be replaced or removed without unacceptable mission or governance consequences.

## Assessment Areas

- alternative supplier;
- alternative model;
- alternative hardware;
- data portability;
- interface portability;
- intellectual property;
- migration effort;
- revalidation requirement;
- reauthorisation requirement;
- time to substitute.

## Required Fields

- Component
- Current supplier
- Alternative
- Substitution difficulty
- Cost
- Time
- Risk
- TEVV impact
- Authorisation impact

---

# 16. Template 07-014 — Supplier Incident Record

## Purpose

Records incidents involving suppliers or externally sourced components.

## Incident Categories

- supplier compromise;
- data breach;
- malicious update;
- model compromise;
- vulnerability;
- service outage;
- unauthorised access;
- provenance failure;
- contractual failure;
- security disclosure.

## Required Fields

- Incident ID
- Supplier
- Component
- Detection
- Impact
- Immediate action
- Containment
- Evidence
- Supplier response
- Risk reassessment
- Revalidation
- Reauthorisation
- Closure

---

# 17. Template 07-015 — Supply Chain Exception Record

## Purpose

Records approved deviations from supply-chain requirements.

## Required Fields

- Exception ID
- Requirement
- Supplier/component
- Deviation
- Reason
- Risk
- Compensating control
- Duration
- Approval authority
- Monitoring
- Expiry
- Review

Exceptions should be explicit, risk-assessed and time-bounded where possible.

---

# 18. Template 07-016 — Supply Chain Governance Review

## Purpose

Provides periodic review of supply-chain and sovereignty risk.

## Review Areas

- critical suppliers;
- strategic dependencies;
- supplier assurance;
- security;
- geopolitical changes;
- ownership changes;
- contracts;
- update mechanisms;
- continuity;
- alternatives;
- incidents;
- exceptions;
- sovereignty.

## Review Questions

1. Have critical suppliers changed?
2. Has ownership changed?
3. Have geopolitical risks changed?
4. Has supplier access changed?
5. Has the supply chain become more concentrated?
6. Are alternatives still viable?
7. Have supplier updates changed system behaviour?
8. Are supplier assurance claims still current?
9. Can the capability continue if a supplier becomes unavailable?
10. Does the authorisation remain valid?

---

# 19. Critical Dependency Model

D-AIGAAF recommends identifying dependencies according to their ability to affect mission continuity.

### Tier 1 — Mission Critical

Failure could directly prevent or seriously compromise the authorised mission.

### Tier 2 — Significant

Failure could materially degrade capability.

### Tier 3 — Supporting

Failure has manageable impact.

### Tier 4 — Non-Critical

Failure has limited operational consequence.

Criticality should be reassessed when the mission, architecture or operating environment changes.

---

# 20. Supplier Assurance Is Not Delegated Accountability

A supplier may provide:

- documentation;
- test reports;
- certifications;
- security assessments;
- model cards;
- assurance statements.

These can contribute to D-AIGAAF evidence.

However:

> **Supplier assurance does not automatically transfer accountability for the customer's operational use of the AI capability.**

The organisation must assess whether supplier evidence is:

- relevant;
- sufficient;
- current;
- independent where required;
- applicable to the actual configuration;
- applicable to the intended mission.

---

# 21. Model and Software Supply Chain

AI supply-chain assessment should include conventional software dependencies and AI-specific components.

Consider:

**Hardware**
→ **Firmware**
→ **Operating System**
→ **Libraries**
→ **Application**
→ **Model Runtime**
→ **Model**
→ **Data**
→ **Tools**
→ **Operational System**

A vulnerability at any relevant layer may affect the final capability.

---

# 22. Foundation Model Dependency

Where a defence capability depends on an external foundation model, record:

- provider;
- model version;
- hosting location;
- update policy;
- access controls;
- training-data limitations where known;
- model behaviour changes;
- service dependency;
- outage consequences;
- jurisdiction;
- data exposure;
- substitution options.

Uncontrolled provider updates should be treated as potential lifecycle changes.

---

# 23. Cloud and External Service Dependency

Where cloud or external services are used, assess:

- connectivity;
- availability;
- jurisdiction;
- data access;
- security;
- service continuity;
- vendor lock-in;
- outage behaviour;
- disconnected operation;
- recovery;
- alternative infrastructure.

Where mission conditions require disconnected operation, reliance on continuously available external services should be explicitly assessed.

---

# 24. Sovereignty and Operational Independence

Sovereignty assessment should address whether the organisation retains sufficient control over:

- critical data;
- critical models;
- critical infrastructure;
- critical software;
- updates;
- operational configuration;
- security;
- sustainment.

The objective is not necessarily complete domestic ownership.

The objective is understanding and managing dependencies that could undermine mission continuity, security or strategic freedom of action.

---

# 25. Supply Chain and Authorisation

Critical supply-chain dependencies should be reflected in operational authorisation.

Authorisation conditions may include:

- approved suppliers;
- approved model versions;
- approved hosting;
- approved data sources;
- approved update mechanisms;
- prohibited substitutions;
- notification requirements;
- revalidation triggers.

A material supplier or component change may require reauthorisation.

---

# 26. Supply Chain and Autonomy

Supply-chain risk can affect autonomy.

Examples:

- external service outage;
- model update;
- compromised dependency;
- loss of data source;
- degraded compute;
- unavailable human support.

If such dependencies affect the AI's ability to remain within its authorised behaviour, the system may need to:

- reduce autonomy;
- restrict functionality;
- require human confirmation;
- transition to a safe state.

---

# 27. Supply Chain Evidence Package

For a consequential AI capability, the supply-chain evidence package should normally contain:

- supply-chain register;
- supplier risk assessments;
- provenance;
- supplier assurance;
- dependency assessment;
- strategic dependency assessment;
- sovereignty assessment;
- supplier access assessment;
- update/change assessment;
- security assessment;
- continuity assessment;
- substitution/exit assessment;
- incident records;
- exceptions;
- governance reviews.

---

# 28. Review Questions

Before approving a critical AI capability, reviewers should ask:

1. Who supplies the critical components?
2. Who owns those suppliers?
3. Where are they located?
4. What jurisdictions apply?
5. What can suppliers access?
6. Who controls updates?
7. Can the supplier change the capability without customer approval?
8. Can the organisation verify the model and software being used?
9. What happens if the supplier becomes unavailable?
10. Is there a credible alternative?
11. How long would substitution take?
12. Would substitution require new TEVV?
13. Would substitution require reauthorisation?
14. Are strategic dependencies acceptable?
15. Can the capability operate under degraded or disconnected conditions?

---

# 29. Anti-Pattern — Procurement Equals Assurance

D-AIGAAF rejects:

**Contract Award**
→ **Supplier Trusted**
→ **Capability Assured**

Procurement is only one governance mechanism.

The correct sequence is:

**Requirement**
→ **Supplier Selection**
→ **Due Diligence**
→ **Contractual Controls**
→ **Technical Verification**
→ **TEVV**
→ **Assurance**
→ **Authorisation**
→ **Continuous Supplier Monitoring**

---

# 30. Anti-Pattern — Country of Origin as the Only Sovereignty Test

Sovereignty should not be reduced to:

**Foreign = Unsafe**

or:

**Domestic = Safe**

A domestic supplier can create:

- concentration risk;
- proprietary lock-in;
- weak continuity;
- poor security;
- inadequate assurance.

An external supplier may be acceptable where risks are understood and appropriately controlled.

The relevant question is:

> **Does the dependency create an unacceptable loss of control, resilience, security or strategic freedom of action?**

---

# 31. Final Supply Chain & Sovereignty Principle

D-AIGAAF treats supply-chain governance as an integral part of AI governance.

The governing principle is:

> **An AI capability should not be considered adequately governed until its critical external dependencies, provenance, supplier access, update mechanisms, strategic dependencies, continuity risks and substitution options are understood and appropriately controlled.**

The complete supply-chain chain is:

**Source**
→ **Supplier**
→ **Component**
→ **Dependency**
→ **Threat**
→ **Risk**
→ **Control**
→ **Assurance**
→ **Continuity**
→ **Operational Authorisation**
→ **Monitoring**
→ **Change**
→ **Revalidation**
→ **Reauthorisation**

This ensures that an AI capability remains governable even when important parts of its technology, data or sustainment ecosystem are outside the organisation's direct control.
