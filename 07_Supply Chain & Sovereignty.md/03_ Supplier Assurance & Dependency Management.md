# D-AIGAAF — Supplier Assurance & Dependency Management

## 1. Purpose

This document establishes requirements for assessing suppliers and managing dependencies that may materially affect the security, trustworthiness, availability, or operational continuity of Defence AI capabilities.

## 2. Supplier Assurance Objectives

Supplier assurance should establish reasonable confidence that suppliers:

- Have appropriate technical and security capabilities.
- Can identify and protect critical components.
- Maintain suitable development and change processes.
- Can provide relevant assurance evidence.
- Manage vulnerabilities and incidents responsibly.
- Protect the integrity of delivered components.
- Maintain agreed support and continuity arrangements.
- Notify relevant changes that could affect authorised operation.

Supplier assurance should be proportionate to the consequence and criticality of the capability.

## 3. Supplier Due Diligence

Before onboarding a supplier supporting a critical AI capability, assessment should consider:

- Corporate and technical capability
- Relevant security practices
- Development and assurance processes
- Supply-chain dependencies
- Ownership and control
- Subcontractors
- Update mechanisms
- Vulnerability management
- Incident response
- Business continuity
- Relevant legal and jurisdictional exposure
- Ability to provide technical evidence

The assessment should distinguish supplier claims from independently verified evidence where practical.

## 4. Critical Supplier Classification

Suppliers may be classified according to their effect on the capability:

| Level | Description |
|---|---|
| S1 — Routine | Limited effect if supplier fails or is compromised |
| S2 — Supporting | Supplier supports important but replaceable functions |
| S3 — Important | Supplier failure materially affects capability |
| S4 — Critical | Supplier supports a function essential to authorised operation |
| S5 — Strategic Critical | Supplier dependency may create severe or systemic consequences |

These categories are a D-AIGAAF working construct and should be adapted to applicable national and defence requirements.

## 5. Dependency Management

Each critical AI capability should maintain visibility of dependencies that could affect:

- Security
- Availability
- Integrity
- Mission effectiveness
- Safety
- Autonomy
- Data processing
- Model behaviour
- Maintenance
- Recovery

Dependencies should be recorded in appropriate capability, configuration, and assurance records.

## 6. Dependency Concentration

The organisation should identify excessive dependence on:

- One supplier
- One model provider
- One technology
- One infrastructure provider
- One geographic source
- One specialised component
- One update mechanism

Concentration risk should be assessed against the consequences of supplier or component failure.

## 7. Supplier Access and Privilege

Supplier access to operational AI environments should be:

- Explicitly authorised
- Limited to required functions
- Time bounded where practicable
- Monitored
- Logged
- Revoked when no longer required

Privileged supplier access should receive enhanced scrutiny.

Where remote access is used, the associated security and operational risks should be explicitly assessed.

## 8. Contractual Assurance Requirements

Where appropriate, contracts should establish requirements for:

- Security controls
- Vulnerability notification
- Incident notification
- Change notification
- Component provenance
- Software and model integrity
- Update controls
- Documentation
- Audit or assessment rights
- Support arrangements
- Data handling
- Subcontractor disclosure
- End-of-life notification
- Secure termination and transition

Contractual provisions should support, rather than replace, technical and operational assurance.

## 9. Supplier Changes

Suppliers should notify relevant authorities of material changes that could affect trust.

Examples include:

- Ownership changes
- Major subcontractor changes
- Critical dependency changes
- Significant architecture changes
- Model changes
- Update mechanism changes
- Hosting changes
- Material security incidents
- Loss of support
- Product retirement

Such changes should enter the D-AIGAAF change-impact process where applicable.

## 10. Dependency Failure Planning

Critical dependencies should have defined contingency arrangements where practicable.

Planning may include:

- Alternative suppliers
- Alternative components
- Local or offline capability
- Redundancy
- запас capability or запас components
- Graceful degradation
- Manual fallback
- Recovery procedures
- Emergency suspension

The selected approach should reflect mission consequence and operational environment.

## 11. End-of-Life and Supplier Withdrawal

The system owner should assess the consequences of:

- Supplier discontinuing support
- Product retirement
- Model retirement
- Loss of licensing
- Loss of infrastructure access
- Unavailable security updates
- Supplier insolvency

Critical capabilities should have a transition or retirement strategy before support becomes unavailable.

## 12. Supplier Incident Response

Supplier-reported incidents should be assessed for possible impact on deployed capabilities.

The response should determine:

- Which components are affected
- Which versions are affected
- Whether the deployed baseline is exposed
- Whether temporary restrictions are required
- Whether other systems are affected
- Whether revalidation is necessary

Supplier assurances should be considered alongside independent evidence where practicable.

## 13. Independent Assurance

For high-consequence or strategically critical dependencies, D-AIGAAF should seek the ability to obtain independent assurance through:

- Technical assessment
- Security testing
- Documentation review
- Independent verification
- Red-team or adversarial assessment
- Controlled evaluation

Proprietary status should not automatically eliminate the need to understand risks that could affect authorised operation.

## 14. Supplier Performance Monitoring

Supplier performance should be reviewed throughout the lifecycle.

Relevant indicators include:

- Security incidents
- Vulnerability response
- Delivery reliability
- Update quality
- Documentation quality
- Support responsiveness
- Change-notification compliance
- Assurance findings
- Repeated defects
- Material dependency changes

Poor performance should feed into supply-chain risk reassessment.

## 15. Core Principle

> **A supplier becomes part of the Defence AI trust boundary when its actions, components, access, or decisions can materially influence the security, behaviour, availability, or assurance of the capability.**

Supplier assurance should therefore continue throughout the lifecycle rather than end when procurement is complete.
