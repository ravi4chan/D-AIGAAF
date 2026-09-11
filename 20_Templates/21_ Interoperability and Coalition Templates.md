# 21-Interoperability and Coalition Templates

## 1. Purpose

This document defines the template set for **D-AIGAAF Module 21 — Interoperability & Coalition**.

Defence AI capabilities may operate across services, platforms, networks, command structures, national boundaries and coalition partners. Interoperability can therefore create both operational advantage and new governance risk.

An AI capability that is acceptable within one organisation may become unsafe or unauthorised when connected to:

- another AI;
- another command system;
- another nation;
- another data source;
- another autonomy framework;
- another operational environment.

The central principle is:

> **Interoperability must not silently transfer, expand or weaken AI authority, assurance, security, human control or operational boundaries.**

The core interoperability governance cycle is:

**Identify Interface → Define Trust Boundary → Establish Authority → Assess Dependency → Test Interoperability → Assure Behaviour → Authorise Connection → Monitor → Manage Change → Reassess**

---

# 2. Template Set

The recommended Interoperability & Coalition template set is:

| ID | Template |
|---|---|
| D-AIGAAF-T-21-001 | Interoperability & Coalition Governance Record |
| D-AIGAAF-T-21-002 | AI Interoperability & Interface Register |
| D-AIGAAF-T-21-003 | Coalition AI Trust & Authority Assessment |
| D-AIGAAF-T-21-004 | Cross-Organisation Data & Information Sharing Assessment |
| D-AIGAAF-T-21-005 | AI-to-AI Interaction & Dependency Assessment |
| D-AIGAAF-T-21-006 | Interoperability Security & Boundary Assessment |
| D-AIGAAF-T-21-007 | Coalition TEVV & Interoperability Test Record |
| D-AIGAAF-T-21-008 | Shared Human Authority & Decision Rights Record |
| D-AIGAAF-T-21-009 | Interoperability Change, Incident & Reauthorisation Record |
| D-AIGAAF-T-21-010 | Coalition Governance Review & Exit Record |

---

# 3. Template 21-001 — Interoperability & Coalition Governance Record

## Purpose

Defines governance arrangements for interoperable and coalition AI capabilities.

## Required Fields

- Capability ID
- Mission
- Participating organisation(s)
- Participating nation(s)
- Interoperability owner
- Operational authority
- Technical authority
- Security authority
- Data authority
- AI assurance authority
- Authorisation authority
- Coalition coordination authority
- Legal / policy authority
- Review date

## Governance Questions

- Who owns the capability?
- Who owns each interface?
- Who controls each data source?
- Who can authorise interaction?
- Who is accountable for consequential decisions?
- What happens when authorities disagree?
- Which organisation can suspend the connection?
- What happens if one partner changes its system?

---

# 4. Template 21-002 — AI Interoperability & Interface Register

## Purpose

Records all material interfaces through which an AI capability interacts with external systems or organisations.

## Interface Types

Consider:

- command and control;
- ISR;
- sensor;
- communications;
- logistics;
- targeting;
- cyber;
- electronic warfare;
- cloud;
- data exchange;
- AI model;
- AI agent;
- human-machine interface.

## Required Fields

- Interface ID
- Connected system
- Organisation
- Nation
- Data exchanged
- Commands exchanged
- AI dependency
- Security boundary
- Trust level
- Authority boundary
- Availability dependency
- Failure mode
- Owner
- Authorisation status

---

# 5. Interoperability Trust Boundary

Every material connection should establish:

**What is trusted?**

**What is not trusted?**

**What information can cross the boundary?**

**What commands can cross the boundary?**

**What authority can cross the boundary?**

**What happens when trust is degraded?**

Interoperability should never be interpreted as implicit trust.

---

# 6. Template 21-003 — Coalition AI Trust & Authority Assessment

## Purpose

Determines whether an interoperable or coalition capability can be trusted and used within defined authority boundaries.

## Assess

- organisation;
- mission;
- capability;
- data;
- model;
- security;
- provenance;
- assurance;
- human authority;
- autonomy;
- legal constraints;
- rules of engagement;
- national caveats.

## Required Fields

- Partner
- Capability
- Trust basis
- Evidence
- Limitations
- Authority granted
- Authority withheld
- Conditions
- Risk
- Review date

## Principle

Trust in a partner does not automatically establish trust in every AI capability supplied by that partner.

---

# 7. Authority Across Organisations

Coalition operations may involve multiple authorities.

D-AIGAAF should distinguish:

**National Authority**

from

**Coalition Authority**

from

**Operational Command Authority**

from

**Technical Authority**

from

**AI System Authority**

These must not be assumed to be interchangeable.

An AI system cannot acquire authority merely because it is connected to a coalition command network.

---

# 8. Template 21-004 — Cross-Organisation Data & Information Sharing Assessment

## Purpose

Assesses the governance implications of sharing information between organisations or nations.

## Assess

- data ownership;
- classification;
- releasability;
- provenance;
- integrity;
- quality;
- timeliness;
- jurisdiction;
- retention;
- access;
- downstream use;
- AI training / inference use.

## Required Fields

- Data asset
- Source
- Owner
- Classification
- Releasability
- Purpose
- Recipient
- Processing
- AI use
- Restrictions
- Integrity controls
- Retention
- Risk
- Approval

---

# 9. Data Provenance Across Coalitions

For consequential AI use, organisations should understand:

**Source**
→ **Collection**
→ **Transfer**
→ **Transformation**
→ **Storage**
→ **AI Processing**
→ **Output**
→ **Decision**

Where provenance becomes uncertain after transfer, the receiving organisation should account for the resulting assurance limitation.

---

# 10. Data Caveats

Coalition data may contain:

- national caveats;
- source restrictions;
- confidence levels;
- collection limitations;
- classification;
- geographic restrictions;
- time restrictions;
- purpose restrictions.

AI systems should not silently discard material caveats.

Where caveats affect the reliability or permitted use of AI outputs, they should remain available to the responsible human decision maker.

---

# 11. Template 21-005 — AI-to-AI Interaction & Dependency Assessment

## Purpose

Assesses risks arising when AI capabilities interact with other AI capabilities.

## Assess

- inputs;
- outputs;
- decision dependencies;
- instructions;
- authority;
- autonomy;
- confidence;
- failure propagation;
- feedback loops;
- emergent behaviour;
- tool access;
- security;
- monitoring.

## Required Fields

- AI system A
- AI system B
- Interaction
- Purpose
- Data flow
- Decision flow
- Authority flow
- Dependency
- Failure mode
- Control
- Test
- Evidence
- Residual risk
- Authorisation

## Core Principle

> **AI-to-AI interaction must not create an ungoverned chain of consequential authority.**

---

# 12. Cascading AI Risk

Interoperable AI can create:

**AI A**
→ recommendation

**AI B**
→ interprets recommendation

**AI C**
→ acts on output

The final action may therefore depend on multiple systems.

Governance should identify:

- origin of the decision;
- transformations;
- uncertainty;
- authority;
- accountability;
- intervention point.

---

# 13. Authority Non-Propagation

D-AIGAAF establishes:

> **Authority does not propagate merely because information or instructions propagate.**

An AI system receiving an instruction from another AI does not thereby receive authority to execute a consequential action.

Human-authorised boundaries must remain explicit at each relevant decision/action point.

---

# 14. Template 21-006 — Interoperability Security & Boundary Assessment

## Purpose

Assesses cybersecurity and AI-specific security risks introduced through interoperability.

## Assess

- network boundary;
- identity;
- authentication;
- authorisation;
- data exchange;
- APIs;
- model interfaces;
- tool permissions;
- remote access;
- logging;
- encryption;
- supply chain;
- adversarial manipulation;
- compromised partner systems.

## Required Fields

- Interface
- Threat
- Attack surface
- Trust boundary
- Control
- Test
- Residual risk
- Monitoring
- Incident response
- Owner

---

# 15. Coalition Security Principle

A partner system should be treated according to its assessed trust and security properties rather than its organisational identity alone.

Consider:

- compromised credentials;
- compromised infrastructure;
- malicious data;
- altered models;
- insider threat;
- supply-chain compromise;
- adversarial access.

Coalition status does not eliminate technical security requirements.

---

# 16. Template 21-007 — Coalition TEVV & Interoperability Test Record

## Purpose

Records testing of interoperable AI capabilities under representative conditions.

## Test Areas

Consider:

- functional interoperability;
- data integrity;
- timing;
- latency;
- degraded communications;
- failure propagation;
- security;
- human control;
- autonomy;
- command relationships;
- national caveats;
- fail-safe;
- recovery.

## Required Fields

- Test ID
- Capability
- Partners
- Configuration
- Environment
- Scenario
- Expected result
- Actual result
- Failure
- Evidence
- Confidence
- Acceptance criterion
- Finding
- Decision

---

# 17. Interoperability Testing

Testing should include more than:

**Can System A communicate with System B?**

It should also ask:

**What happens when communication is delayed?**

**What happens when data is wrong?**

**What happens when one system fails?**

**What happens when one partner withdraws?**

**What happens when autonomy states differ?**

**What happens when human authorities disagree?**

---

# 18. Degraded Coalition Operations

Coalition AI should be assessed for:

- loss of partner connectivity;
- intermittent communications;
- stale data;
- asymmetric information;
- partner system failure;
- degraded navigation;
- degraded sensor feeds;
- loss of external services.

The capability should have defined behaviour when interoperability assumptions no longer hold.

---

# 19. Template 21-008 — Shared Human Authority & Decision Rights Record

## Purpose

Defines human decision rights across organisations.

## Required Fields

- Decision / action
- Mission
- AI capability
- Organisation
- Human authority
- Decision rights
- Delegation
- Intervention
- Override
- Escalation
- National caveat
- Rules / restrictions
- Accountability
- Record owner

## Questions

- Who can approve the action?
- Who can reject it?
- Who can intervene?
- Who can suspend AI use?
- Who owns the risk?
- Who is accountable after the action?

---

# 20. Coalition Rules and National Caveats

Coalition AI operations may involve differing:

- laws;
- policies;
- rules of engagement;
- risk tolerances;
- data restrictions;
- autonomy policies;
- human-control requirements.

These differences should be explicitly represented.

The least restrictive partner's rules should not automatically become the coalition-wide operating rule.

---

# 21. Template 21-009 — Interoperability Change, Incident & Reauthorisation Record

## Purpose

Controls material changes and incidents affecting interoperable AI capabilities.

## Change Triggers

Consider:

- partner system update;
- model update;
- interface change;
- new data source;
- new network;
- new mission;
- changed command relationship;
- changed autonomy;
- changed national caveat;
- changed threat;
- changed security posture.

## Required Fields

- Event
- Partner
- Change / incident
- Impact
- Risk
- Configuration
- Evidence
- Immediate control
- TEVV
- Revalidation
- Reauthorisation
- Implementation
- Monitoring
- Closure

---

# 22. Interoperability Incident Response

A material interoperability incident may require:

**Detect**
→ **Contain**
→ **Protect**
→ **Disconnect / Restrict**
→ **Investigate**
→ **Assess Partner Impact**
→ **Revalidate**
→ **Reauthorise**
→ **Reconnect**

Disconnection itself should have defined authority and safe-state implications.

---

# 23. Template 21-010 — Coalition Governance Review & Exit Record

## Purpose

Reviews continuing suitability of coalition interoperability and provides controlled exit arrangements.

## Review Areas

- mission;
- partners;
- interfaces;
- data;
- trust;
- security;
- assurance;
- authority;
- incidents;
- changes;
- national caveats;
- dependencies;
- continuity.

## Exit Considerations

- disconnect authority;
- data return / deletion;
- credential revocation;
- interface removal;
- model / software dependency;
- shared infrastructure;
- operational continuity;
- records retention;
- incident obligations.

---

# 24. Coalition Interoperability and Mission Context

Interoperability should be authorised in relation to:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Partner Context**

The addition of a partner can materially alter the risk profile even when the AI capability itself has not changed.

---

# 25. Interoperability and Operational Environment

The environment should include coalition-specific factors such as:

- partner network;
- spectrum;
- command architecture;
- shared infrastructure;
- data availability;
- coalition procedures;
- language;
- operator training;
- rules of engagement.

A capability tested in a national environment may require additional assurance before coalition employment.

---

# 26. Interoperability and Supply Chain

Coalition operations can create additional dependencies:

- partner cloud;
- partner AI model;
- shared data service;
- foreign software;
- shared satellite service;
- external API;
- coalition infrastructure.

These dependencies should be captured in supply-chain and sovereignty assessments.

---

# 27. Interoperability and Human Control

Human control can become ambiguous when:

- multiple commanders are involved;
- AI recommendations cross national boundaries;
- decision rights are distributed;
- communications are delayed;
- different AI systems interact.

The responsible human should remain identifiable for consequential decisions.

---

# 28. Interoperability and Uncertainty

AI outputs crossing organisational boundaries should retain, where material:

- confidence;
- uncertainty;
- provenance;
- time;
- source;
- limitations;
- caveats.

Stripping these attributes during data exchange can increase decision risk.

---

# 29. Interoperability and Accountability

For consequential actions, records should permit reconstruction of:

**Source AI**
→ **Data**
→ **Transformation**
→ **Receiving AI**
→ **Human Decision**
→ **Authority**
→ **Action**
→ **Outcome**

This is particularly important where responsibility crosses organisational or national boundaries.

---

# 30. Coalition Governance Disagreement

Where participating authorities disagree about:

- risk;
- autonomy;
- data;
- mission;
- authorisation;
- legal constraints;

the disagreement should be recorded and escalated according to agreed governance arrangements.

AI should not resolve governance disagreement by defaulting to the most permissive instruction.

---

# 31. Anti-Pattern — Network Connectivity Equals Trust

D-AIGAAF rejects:

> “The system is on the coalition network, therefore it is trusted.”

Connectivity establishes a technical relationship.

It does not establish:

- assurance;
- authority;
- legal permission;
- operational suitability.

---

# 32. Anti-Pattern — Partner Assurance Transfers

A partner's assurance evidence may support assessment.

It does not automatically establish assurance for the receiving organisation's:

- mission;
- environment;
- configuration;
- human control;
- operational authority.

Context remains relevant.

---

# 33. Anti-Pattern — Interoperability as a Technical Problem Only

D-AIGAAF treats interoperability as a governance issue as well as a technical issue.

The complete question is:

> **Can the systems communicate safely, preserve required information and uncertainty, maintain authority boundaries, support human control, protect security, preserve accountability and operate within the agreed mission and coalition conditions?**

---

# 34. Anti-Pattern — AI-to-AI Authority Chain

D-AIGAAF rejects:

**AI A recommends**
→ **AI B approves**
→ **AI C acts**

as a substitute for explicit human authority where the action is consequential.

AI-to-AI interaction can transmit information or perform authorised functions, but it cannot independently create operational authority.

---

# 35. Coalition Interoperability Golden Thread

The interoperability module extends the D-AIGAAF Golden Thread:

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
→ **Partner Context**
→ **Interoperability**
→ **Employment**
→ **Monitoring**
→ **Change / Incident**
→ **Learning**
→ **Revalidation / Reauthorisation**

This ensures that interoperability remains governed as part of the operational system rather than treated as an isolated interface.

---

# 36. Final Interoperability & Coalition Principle

D-AIGAAF treats interoperability as a potential change to the governance and risk context of an AI capability.

The governing principle is:

> **Connecting an AI capability to another system, organisation or coalition must not silently expand its authority, alter its assurance basis, weaken human control, expose unacceptable security or supply-chain dependencies, or obscure accountability; interoperable use should therefore be explicitly bounded, tested, assured, authorised and continuously monitored in its actual coalition context.**
