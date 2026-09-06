# D-AIGAAF — Supply Chain & Sovereignty Governance Model

## 1. Purpose

This document establishes the governance approach for supply-chain assurance and technological sovereignty across the Defence AI lifecycle.

The objective is to ensure that Defence AI capabilities can be trusted, traced, maintained, secured, and governed despite dependence on developers, suppliers, third-party components, models, datasets, infrastructure, and external services.

## 2. Scope

Supply-chain and sovereignty considerations should apply to:

- Foundation and specialised AI models
- Training and operational data
- Software and libraries
- Hardware and compute infrastructure
- Sensors and supporting systems
- Cloud and hosted services
- APIs and external services
- Open-source components
- Commercial products
- Third-party datasets
- Model updates and patches
- System integrators and subcontractors
- Critical technical dependencies

## 3. Governance Objectives

D-AIGAAF should establish reasonable confidence that:

1. Critical components have identifiable provenance.
2. Suppliers and dependencies are appropriately assessed.
3. Material dependencies are visible to the system owner.
4. Unauthorised modification can be detected.
5. Critical updates are controlled and traceable.
6. Dependence on external parties is understood.
7. Security and assurance obligations extend through the supply chain.
8. The capability can remain governed throughout its authorised lifecycle.
9. Sovereignty risks are explicitly assessed rather than assumed away.

## 4. Supply-Chain Governance Principle

A Defence AI capability should not be treated as a standalone model.

The governed system includes:

**Model + Data + Software + Hardware + Infrastructure + Interfaces + Dependencies + Suppliers + People**

A weakness in any critical component may affect the trustworthiness of the overall capability.

## 5. Sovereignty Dimensions

For D-AIGAAF purposes, sovereignty should be considered across several dimensions:

| Dimension | Key Question |
|---|---|
| Technical | Can the system be understood, maintained, secured, and controlled? |
| Data | Who controls critical data and where is it processed? |
| Model | Who controls the model and its material updates? |
| Infrastructure | Who controls the computing and hosting environment? |
| Supply | Can critical components be obtained and sustained when required? |
| Operational | Can the capability be employed without unacceptable external dependency? |
| Legal | Are contractual and jurisdictional dependencies understood? |
| Assurance | Can the system be independently assessed when required? |

These dimensions should be assessed according to the mission and risk rather than interpreted as a requirement for complete domestic ownership of every component.

## 6. Critical Dependency Identification

Each AI capability should identify dependencies that could materially affect:

- AI behaviour
- Security
- Availability
- Mission effectiveness
- Safety
- Autonomy
- Data integrity
- Operational continuity
- Reauthorisation

Critical dependencies should be recorded in the capability's assurance and configuration records.

## 7. Supply-Chain Risk Assessment

Supply-chain risk assessment should consider:

- Supplier reliability
- Component provenance
- Dependency concentration
- Foreign jurisdictional exposure
- Update control
- Vendor access
- Lifecycle support
- Vulnerability exposure
- Subcontractor dependencies
- Ability to replace the component
- Consequences of supplier failure
- Ability to independently verify the component

Risk should be evaluated in the context of the authorised mission and operational environment.

## 8. Governance Responsibilities

Supply-chain governance should clearly assign responsibility for:

- Supplier assessment
- Component approval
- Dependency management
- Security assurance
- Contractual controls
- Configuration management
- Update approval
- Vulnerability response
- Continuity planning
- Risk acceptance
- Reauthorisation following material supply-chain changes

No critical dependency should exist without an identifiable accountable owner.

## 9. Supply-Chain Assurance

Supply-chain assurance should be integrated with:

- AI security
- Data governance
- Configuration management
- TEVV
- Operational authorisation
- Continuous assurance
- Acquisition and procurement
- Incident response

Evidence should demonstrate not only who supplied a component, but also whether the component remains trustworthy within the authorised system.

## 10. Material Supplier or Dependency Changes

Changes requiring assessment may include:

- New supplier
- Change of ownership
- Change of hosting location
- New critical dependency
- Material software update
- Material model update
- Change in update mechanism
- Change in subcontractor
- Newly identified vulnerability
- Loss of supplier support
- Change in legal or jurisdictional exposure

Material changes should trigger the applicable D-AIGAAF change-impact assessment and, where necessary, revalidation or reauthorisation.

## 11. Continuity and Substitutability

Critical AI capabilities should assess whether essential components can be:

- Replaced
- Restored
- Reconfigured
- Isolated
- Operated in degraded mode

Where a capability has a critical single point of dependency, that dependency should be explicitly documented and reflected in residual risk.

## 12. Core Principle

> **Trust in Defence AI depends not only on the behaviour of the AI system, but on confidence in the people, organisations, technologies, data, and dependencies that create and sustain it.**

Supply-chain and sovereignty governance should therefore remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**
