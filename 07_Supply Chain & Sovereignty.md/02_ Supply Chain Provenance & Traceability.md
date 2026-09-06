# D-AIGAAF — Supply Chain Provenance & Traceability

## 1. Purpose

This document establishes requirements for maintaining sufficient provenance and traceability across the components and dependencies of a Defence AI capability.

The objective is to enable the responsible authority to understand where critical components came from, how they were changed, what they depend upon, and whether the deployed configuration remains consistent with the authorised baseline.

## 2. Scope

Provenance and traceability should cover, where relevant:

- AI models
- Training, validation, and operational data
- Software and libraries
- Hardware and firmware
- APIs and external services
- Infrastructure
- Security components
- Configuration
- Model and software updates
- Third-party and open-source dependencies
- Suppliers and subcontractors

## 3. Provenance Requirements

For each critical component, records should identify, where practicable:

- Component identity
- Version
- Origin
- Developer or supplier
- Date or release information
- Dependencies
- Modification history
- Verification status
- Approval status
- Applicable security or assurance evidence

The level of provenance required should be proportionate to the consequence and criticality of the component.

## 4. Model Provenance

Model provenance should establish confidence in the identity and history of the model used in an authorised capability.

Relevant records may include:

- Model name or identifier
- Version
- Developer
- Base model, where applicable
- Fine-tuning or adaptation history
- Relevant training sources
- Evaluation history
- Model changes
- Approval history
- Integrity verification
- Deployment history

Where complete provenance cannot be established, the resulting uncertainty should be explicitly recorded and risk assessed.

## 5. Data Provenance

Data provenance should support understanding of:

- Source
- Collection method
- Transformation
- Labelling or annotation
- Processing
- Validation
- Use
- Retention
- Modification

Provenance should enable investigation of material data-related failures or unexpected AI behaviour.

## 6. Software and Dependency Traceability

Software inventories should identify components that could materially affect AI behaviour or security.

This may include:

- Application software
- Libraries
- Frameworks
- Operating systems
- Drivers
- Firmware
- APIs
- Security components
- Open-source packages
- Third-party services

Where practicable, dependencies should be linked to known versions and their applicable assurance status.

## 7. Hardware and Infrastructure Traceability

Critical infrastructure should be identifiable sufficiently to support:

- Configuration management
- Security assessment
- Fault investigation
- Replacement
- Recovery
- Revalidation

Records may include hardware identity, firmware version, platform configuration, hosting environment, and relevant interfaces.

## 8. Change Traceability

Material changes should be traceable from:

**Original Baseline → Change → Assessment → Testing → Approval → Deployment → Monitoring**

The record should identify who authorised the change and what evidence supported the decision.

## 9. Configuration Traceability

The deployed configuration should be capable of being compared with the approved configuration baseline.

Differences should be:

- Detected
- Recorded
- Assessed
- Approved or corrected

Unauthorised deviations from a critical baseline should be treated as a security and assurance concern.

## 10. Supplier Traceability

For critical components, the supply chain should be traceable to an appropriate level of depth.

Assessment should consider:

- Primary supplier
- Relevant subcontractors
- Critical third-party components
- Development and maintenance responsibility
- Update responsibility
- Hosting responsibility
- Material ownership changes

The required depth should reflect risk and practical feasibility.

## 11. Traceability and Incident Response

Provenance records should support rapid investigation following:

- Security incidents
- Unexpected AI behaviour
- Model anomalies
- Data integrity concerns
- Vulnerability disclosures
- Supplier incidents
- Unauthorised configuration changes

The objective is to identify affected components, determine exposure, and support containment and recovery.

## 12. Traceability and Operational Authorisation

Operational authorisation should reference the relevant configuration and provenance baseline.

A capability should not be assumed to remain authorised if a critical component has changed without the required assessment.

Where a material change affects system behaviour, security, autonomy, or mission risk, the D-AIGAAF change-impact and reauthorisation process should apply.

## 13. Records and Evidence

Provenance records should be retained according to applicable security and records-management requirements.

The Defence AI Assurance Record should reference relevant evidence rather than requiring every technical artefact to be duplicated within it.

## 14. Provenance Limitations

The framework should explicitly record where provenance is:

- Incomplete
- Unverified
- Dependent on supplier declarations
- Technically difficult to establish
- Obscured by proprietary systems
- Affected by legacy components

Unknown provenance should be treated as uncertainty and incorporated into risk assessment.

## 15. Core Principle

> **A Defence AI capability should be traceable sufficiently to establish what it is, where its critical components came from, how they changed, and whether the deployed system remains the system that was assessed and authorised.**
