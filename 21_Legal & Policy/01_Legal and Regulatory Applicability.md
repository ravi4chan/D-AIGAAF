# 01-Legal and Regulatory Applicability

## Purpose
This document establishes the D-AIGAAF method for identifying, assessing, documenting, and maintaining legal and regulatory requirements applicable to a defence AI capability. Applicability is contextual and may change with mission, jurisdiction, lifecycle stage, data, suppliers, operational environment, autonomy, human authority, and intended use.

## Core Principle
**Legal applicability must be established for the specific AI capability, mission, environment, actors, data, and intended use before legal requirements can be translated into governance controls.**

## Applicability Chain
**Capability → Actor → Mission → Jurisdiction → Environment → Activity → Data → Consequence → Applicable Authority → Requirement → Governance Control → Evidence → Review**

## 1. Scope of Applicability Assessment
Consider, where relevant:
- AI capability, configuration and intended use
- Reasonably foreseeable and prohibited uses
- Lifecycle stage
- Responsible organisations and actors
- Geographic and extraterritorial jurisdiction
- Operational environment
- Data location, movement, classification and affected persons
- Suppliers, cloud and infrastructure providers
- Coalition and multinational arrangements
- Cross-border interfaces
- Autonomy and human decision authority
- Consequences of AI-supported decisions or actions
- Applicable international obligations

## 2. Sources of Requirements

### 2.1 Domestic Law
Potential sources include primary and subordinate legislation, data protection, cybersecurity, procurement, administrative, intellectual-property, employment, export-control, national-security and sector-specific requirements.

### 2.2 Defence and Government Requirements
Consider defence policy, departmental directives, service regulations, security instructions, information-classification rules, acquisition policy, safety requirements, operational directives and records requirements.

### 2.3 International Requirements
Where applicable, consider treaty obligations, international humanitarian law, international human rights law, international agreements, multinational arrangements, status-of-forces arrangements, data-sharing agreements and export-control regimes.

### 2.4 Contractual Requirements
Obligations may arise from procurement contracts, software and data licences, cloud agreements, support contracts, supplier commitments, coalition agreements and memoranda of understanding.

## 3. Applicability Assessment Method

### Step 1 — Identify the Capability
Record the capability, function, AI technique, system boundary, configuration, intended use, prohibited use and lifecycle stage.

### Step 2 — Identify the Actors
Identify capability owners, developers, acquirers, operators, commanders or decision authorities, suppliers, infrastructure providers, partner organisations and affected third parties.

### Step 3 — Identify the Activity
Determine whether the capability is being researched, developed, trained, tested, evaluated, acquired, integrated, deployed, operated, updated, shared, exported or retired.

### Step 4 — Identify Jurisdiction
Determine where the organisation is established, development occurs, data is processed, infrastructure is located, deployment occurs and operational effects arise. Consider extraterritorial, coalition and host-nation requirements.

### Step 5 — Identify the Legal Object
Determine whether a requirement attaches to the AI system, software, data, infrastructure, organisation, operator, decision, resulting action, affected person, supplier, transfer or transaction.

### Step 6 — Determine Applicability
Classify each potential source as:
- Applicable
- Applicable with conditions
- Potentially applicable
- Not applicable
- Uncertain / legal interpretation required

### Step 7 — Translate Requirements
Use the chain:
**Obligation → Governance Requirement → Control → Responsible Authority → Evidence**

## 4. Legal Applicability Register

| Source | Authority | Jurisdiction | Applicability | Requirement | D-AIGAAF Control | Owner | Evidence | Review Trigger |
|---|---|---|---|---|---|---|---|---|
| | | | | | | | | |

Distinguish:
- Binding legal requirements
- Binding internal policy
- Contractual obligations
- Standards adopted by policy or contract
- Voluntary standards
- Guidance
- Good practice

This prevents voluntary guidance from being represented as law and binding obligations from being treated as optional.

## 5. Defence Context
Explicitly assess national-security or defence exemptions, military-specific regimes, classified systems, intelligence activities, overseas deployment, coalition operations, armed conflict, emergency authorities, rules of engagement, command responsibility and host-nation requirements.

**An exemption from one regulatory requirement does not imply exemption from governance, security, safety, accountability, or other applicable obligations.**

## 6. Lifecycle Applicability

### Development
Consider data acquisition, intellectual property, security, research restrictions and supplier obligations.

### Testing and TEVV
Consider test data, human participants where relevant, operational trials, security, evidence retention and safety.

### Acquisition
Consider procurement, supplier disclosure, licensing, sovereignty, contractual requirements and export controls.

### Deployment and Employment
Consider operational authority, mission-specific law and policy, human decision-making, data processing, accountability and international obligations.

### Change
A new mission, jurisdiction, data source, supplier, autonomy level, tool, interface, affected population or deployment location may change applicability.

### Retirement
Consider records retention, data disposal, security, contractual closure, intellectual property and archival requirements.

## 7. Legal Uncertainty
Where uncertainty exists, record:
- Legal question
- Competing interpretations
- Relevant authority
- Legal advice
- Assumptions
- Operational consequence
- Interim control
- Decision authority
- Review trigger

Do not conceal uncertainty behind a simplistic compliant/non-compliant classification.

## 8. Conflicting Requirements
Where requirements conflict:
1. Identify each requirement.
2. Establish its authority and applicability.
3. Obtain competent legal interpretation.
4. Identify operational consequences.
5. Define approved controls or restrictions.
6. Record the decision and rationale.
7. Establish review triggers.

## 9. Relationship to Operational Authorisation
Legal review contributes to operational authorisation but does not replace it.

**Legally permissible ≠ Assured ≠ Operationally suitable ≠ Operationally authorised**

Likewise:

**Technical capability ≠ Legal authority ≠ Operational authority**

## 10. Evidence
Relevant evidence may include legal opinions, applicability assessments, policy interpretations, regulatory correspondence, contracts, licences, data-processing records, export approvals, information-sharing agreements, authorisation records and governance decisions.

Evidence should be current, traceable, protected, version-controlled and linked to the relevant capability and configuration.

## 11. Review Triggers
Review applicability after material changes including:
- New law, regulation, policy or directive
- Mission or jurisdiction change
- Operational-environment change
- Autonomy or human-authority change
- New data or supplier
- Infrastructure-location change
- New coalition partner
- New system interface
- Material model/software change
- Incident
- Legal challenge
- New authoritative interpretation

## 12. Roles and Responsibilities

### Legal / Policy Function
Interpret requirements, identify uncertainty, advise governance authorities and review material changes.

### Capability Owner
Provide accurate mission/system information, implement required controls and maintain evidence.

### Operational Authority
Ensure legal conditions are reflected in operational boundaries.

### Security / Data / Technical Functions
Translate relevant requirements into enforceable controls.

### Assurance Function
Assess whether evidence demonstrates implementation of applicable controls.

## 13. Minimum Applicability Record
Every consequential AI capability should record:
- Capability and mission
- Organisation and jurisdiction
- Lifecycle stage
- Applicable legal and policy sources
- Material obligations
- Legal uncertainties
- Required controls
- Responsible owners
- Evidence
- Review triggers
- Legal-review / approval status

## 14. Anti-Patterns
Avoid:
1. Treating every AI framework as legally binding.
2. Assuming defence use creates a complete legal exemption.
3. Conducting legal review only during procurement.
4. Treating supplier claims as legal analysis.
5. Assuming legal applicability remains unchanged after mission or jurisdiction changes.
6. Conflating legality with assurance.
7. Conflating legality with operational authorisation.
8. Ignoring contractual or licensing restrictions.
9. Ignoring cross-border data and infrastructure.
10. Recording “compliant” without identifying the requirement and evidence.

## 15. Governance Test
For every consequential AI capability, the organisation should be able to answer:

> **Which legal, regulatory, policy and contractual requirements apply to this specific capability, mission, jurisdiction and lifecycle stage; why do they apply; what controls implement them; what evidence demonstrates implementation; and what changes would require reassessment?**

If these questions cannot be answered, legal applicability has not been adequately established.

## D-AIGAAF Integration
Legal and regulatory applicability feeds the Golden Thread:

**Applicable Authority → Obligation → Requirement → Control → Evidence → Assurance → Operational Conditions → Authorisation → Monitoring → Change → Reassessment**

It connects particularly to Mission & Use Case, Risk & Autonomy, AI Lifecycle, Data & Information, AI Security, Supply Chain & Sovereignty, Human Authority, TEVV, Operational Environment, Operational Authorisation, Change & Reauthorisation, Audit & Evidence, Crosswalks, Acquisition & Procurement, Interoperability & Coalition, and Retirement & Decommissioning.

## Final Principle
**Legal and regulatory applicability is contextual and dynamic. It must follow the AI capability through changes in mission, jurisdiction, data, autonomy, suppliers, environment and operational use, while remaining traceable to specific governance controls and evidence.**
