# D-AIGAAF — Supply Chain Change & Reauthorisation

## 1. Purpose

This document defines how material changes to suppliers, components, dependencies, or supply arrangements should be assessed to determine whether existing Defence AI assurance and operational authorisation remain valid.

## 2. Change Principle

A Defence AI capability should not be assumed to remain equivalent to its authorised baseline simply because its mission or user interface appears unchanged.

A change may affect:

- Security
- Model behaviour
- Data integrity
- Availability
- Mission effectiveness
- Autonomy
- Safety
- Operational dependencies
- Sovereignty
- Assurance evidence

## 3. Changes Requiring Assessment

Examples include:

- New supplier
- Supplier ownership change
- New subcontractor
- New model or model version
- Material software update
- New hardware
- New hosting environment
- New API or external service
- Change in data source
- Change in update mechanism
- Critical dependency replacement
- Loss of supplier support
- Newly identified vulnerability
- Material change in legal or jurisdictional exposure

## 4. Change Classification

Changes may be classified as:

| Category | Description |
|---|---|
| Minor | No credible material effect on authorised behaviour, security, or risk |
| Significant | Potential effect requiring targeted assessment or testing |
| Material | Credible effect on security, behaviour, autonomy, mission risk, or assurance |
| Critical | Change may invalidate existing assurance or operational authorisation |

These categories are working D-AIGAAF constructs and should be aligned with applicable organisational processes.

## 5. Change Impact Assessment

For each significant change, assess:

1. What has changed?
2. Why has it changed?
3. Which components or dependencies are affected?
4. Does the change affect the authorised baseline?
5. Could AI behaviour change?
6. Could security characteristics change?
7. Could autonomy or human control change?
8. Could mission effectiveness change?
9. Does existing assurance remain applicable?
10. Is additional TEVV required?
11. Is revalidation required?
12. Is reauthorisation required?

## 6. Supplier-Driven Updates

Supplier updates should not automatically be treated as operationally equivalent to the previously authorised version.

The system owner should establish:

- What changed
- Which versions are affected
- Expected behavioural impact
- Security impact
- Relevant testing
- Dependencies
- Rollback options
- Approval status

Updates affecting model behaviour or other consequential characteristics require heightened scrutiny.

## 7. Hidden or Opaque Changes

Particular caution is required where a change affects internal model layers, weights, parameters, retrieval behaviour, safety mechanisms, or other components whose effect cannot be fully understood from the external interface.

Where the effect of a material change cannot be confidently determined, the uncertainty should be reflected in the risk assessment and assurance decision.

Additional testing, revalidation, or reauthorisation may be required.

## 8. Revalidation

Revalidation should determine whether the changed capability continues to satisfy:

- Security requirements
- Mission requirements
- Operational constraints
- Autonomy boundaries
- Human-control requirements
- TEVV expectations
- Supply-chain controls
- Operational-authorisation conditions

The extent of revalidation should be proportionate to the change and risk.

## 9. Reauthorisation

Reauthorisation should be considered or required when a change materially affects:

- Capability
- Mission
- Risk
- Autonomy
- Human authority
- Operational environment
- Security
- Critical dependencies
- Assurance evidence

The authorising authority should determine whether the existing authorisation remains valid, requires modification, or must be withdrawn pending further assurance.

## 10. Emergency Changes

Emergency changes may be necessary to address:

- Active security compromise
- Critical vulnerability
- Immediate safety concern
- Severe operational failure
- Loss of critical dependency

Emergency procedures should define:

- Who can approve the change
- Permitted temporary scope
- Required evidence
- Duration
- Monitoring
- Post-change testing
- Retrospective review
- Reauthorisation requirements

Emergency status should not permanently bypass normal governance.

## 11. Rollback and Recovery

Where practicable, material changes should have a controlled rollback or recovery path.

This may require:

- Previous verified model
- Previous software baseline
- Known-good configuration
- Recovery data
- Alternative dependency
- Manual fallback

Rollback capability should itself be tested where the consequence warrants it.

## 12. Change Records

Each material change should maintain a traceable record containing:

- Change identifier
- Description
- Reason
- Affected components
- Previous baseline
- New baseline
- Risk assessment
- Testing
- Assurance findings
- Approval
- Deployment date
- Monitoring requirements
- Revalidation decision
- Reauthorisation decision

## 13. Continuous Monitoring After Change

Material changes should receive enhanced monitoring for an appropriate period after deployment.

Monitoring should consider:

- Unexpected model behaviour
- Performance changes
- Security anomalies
- Increased uncertainty
- New failure modes
- Changes in dependency behaviour
- Mission effects

Unexpected behaviour should trigger the applicable incident or reassessment process.

## 14. Core Principle

> **A Defence AI authorisation applies to an assessed capability and its defined conditions—not automatically to every future version of that capability.**

Supply-chain and technical changes must therefore remain connected to configuration management, assurance, risk assessment, revalidation, and operational reauthorisation.
