# D-AIGAAF — Supply Chain Risk Assessment

## 1. Purpose

This document defines a structured approach for identifying, assessing, treating, and monitoring supply-chain risks associated with Defence AI capabilities.

The assessment should determine whether dependencies could adversely affect security, availability, integrity, mission effectiveness, safety, autonomy, or operational sovereignty.

## 2. Assessment Scope

The assessment should consider the full supply chain supporting the AI capability, including:

- Models
- Training and operational data
- Software
- Hardware
- Infrastructure
- Sensors
- APIs and external services
- Open-source components
- Cloud or hosted services
- Suppliers
- Subcontractors
- Maintenance and support arrangements
- Update mechanisms

## 3. Risk Factors

Supply-chain risk assessment should consider:

### 3.1 Provenance Risk
Can the origin and development history of the component be established?

### 3.2 Integrity Risk
Could the component be modified, substituted, or compromised without detection?

### 3.3 Dependency Risk
Would failure of the supplier or component materially affect the capability?

### 3.4 Jurisdictional Risk
Could legal, regulatory, political, or jurisdictional factors affect access, control, or continuity?

### 3.5 Update Risk
Could updates materially alter system behaviour or security characteristics?

### 3.6 Support Risk
Could loss of supplier support prevent secure operation, maintenance, or remediation?

### 3.7 Concentration Risk
Does excessive dependence on one supplier, technology, platform, or geographic source create systemic vulnerability?

### 3.8 Assurance Risk
Can the component be sufficiently tested, inspected, monitored, and independently assessed?

## 4. Risk Assessment Questions

For each critical dependency, assess:

1. What is the component?
2. Who developed or supplies it?
3. Who controls its updates?
4. Where is it hosted, developed, or maintained?
5. What other components does it depend upon?
6. What happens if it becomes unavailable?
7. What happens if its integrity is compromised?
8. Can its behaviour be independently assessed?
9. Can it be replaced or isolated?
10. What evidence supports trust in it?

## 5. Risk Rating

Supply-chain risks should be evaluated using the broader D-AIGAAF risk methodology.

Relevant factors include:

- Consequence
- Mission criticality
- Threat exposure
- Autonomy
- Dependency criticality
- Detectability
- Recoverability
- Availability of alternatives

A dependency supporting a high-consequence autonomous function should receive substantially greater scrutiny than a dependency supporting low-risk informational use.

## 6. Critical Dependency Categories

| Category | Description |
|---|---|
| C1 — Non-Critical | Failure has limited operational effect |
| C2 — Supporting | Failure degrades capability but does not normally prevent mission execution |
| C3 — Important | Failure materially affects mission effectiveness |
| C4 — Critical | Failure may prevent authorised operation or create significant risk |
| C5 — Strategic Critical | Compromise or loss may create severe or systemic consequences |

These categories are a D-AIGAAF working construct and should be adapted to applicable national and defence requirements.

## 7. Risk Treatment

Identified supply-chain risks may be treated through:

- Avoidance
- Reduction
- Isolation
- Diversification
- Substitution
- Additional assurance
- Contractual controls
- Technical controls
- Monitoring
- Contingency planning
- Explicit risk acceptance

Risk treatment should address the actual dependency rather than simply documenting it.

## 8. Mitigation Hierarchy

Where practical, preference should be given to:

**Eliminate unnecessary dependency → Reduce dependency → Control dependency → Monitor dependency → Accept residual dependency risk**

Risk acceptance should be undertaken by the authority appropriate to the consequence.

## 9. Residual Risk

Residual supply-chain risk should be documented when:

- A critical dependency cannot be replaced
- Independent verification is limited
- Supplier control cannot be fully established
- Alternative components are unavailable
- Continuity depends on an external service
- Material uncertainty remains

Residual risk should remain visible within the Defence AI Assurance Record and Operational Authorisation.

## 10. Monitoring

Supply-chain risk should be continuously monitored for:

- Supplier changes
- Ownership changes
- New vulnerabilities
- Component changes
- New dependencies
- Update changes
- Loss of support
- Security incidents
- Changes in jurisdictional exposure
- Changes in availability
- Changes in mission dependence

## 11. Trigger for Reassessment

A reassessment should occur when a change could materially affect the trustworthiness or operational dependency of the capability.

Examples include:

- New model
- Major software update
- New hosting provider
- New critical component
- Supplier acquisition or ownership change
- Critical vulnerability
- Significant supply disruption
- Change in mission
- Increase in autonomy

Material changes should enter the D-AIGAAF change-impact and reauthorisation process.

## 12. Evidence

The assessment should maintain evidence such as:

- Supplier records
- Component inventories
- Dependency maps
- Provenance information
- Security assessments
- Vulnerability information
- Contractual controls
- Continuity assessments
- Substitutability analysis
- Test and assurance results
- Risk decisions

## 13. Core Principle

> **A supply-chain dependency becomes a Defence AI risk when failure, compromise, manipulation, or loss of control could materially affect the authorised capability.**

Supply-chain risk should therefore be assessed as an operational risk, not merely as a procurement or vendor-management issue.
