# Deployment Readiness

## Summary

Deployment Readiness establishes the formal assessment required before a defence AI capability moves from development, integration and assurance into operational deployment.

The purpose is to determine whether the capability is sufficiently mature, controlled, assured and authorised for its intended operational use.

The core decision is:

**Is the capability ready to be deployed in the specific configuration, mission, environment, autonomy and human-authority conditions for which approval is sought?**

Deployment readiness does not itself grant operational authority. It establishes whether the capability is ready to enter the operational authorisation decision.

---

## 1. Purpose

Deployment Readiness provides a structured gate between:

**Development / TEVV / Assurance → Operational Authorisation → Deployment**

It should establish that:

- required evidence exists;
- material risks are understood;
- configuration is controlled;
- operational boundaries are defined;
- human authority is established;
- autonomy is understood;
- safety and security controls are in place;
- deployment conditions are achievable;
- limitations are known;
- residual risk is identified.

---

## 2. Core Principle

**A technically complete system is not necessarily deployment-ready.**

Readiness depends on the relationship between:

**Capability × Mission × Environment × Autonomy × Human Authority × Evidence × Risk**

A capability may be suitable for one mission or environment and unsuitable for another.

---

## 3. Deployment Readiness Scope

Assessment should consider, as applicable:

- mission need;
- use case;
- requirements;
- risk;
- autonomy;
- data;
- model;
- system integration;
- configuration;
- TEVV;
- operational environment;
- security;
- safety;
- human authority;
- workforce;
- logistics;
- sustainment;
- incident response;
- fail-safe;
- operational authorisation.

---

## 4. Readiness Inputs

Deployment readiness should use evidence from:

- requirements;
- risk assessments;
- autonomy assessments;
- data preparation;
- model development;
- system integration;
- configuration management;
- TEVV;
- security assessment;
- safety assessment;
- operational environment assessment;
- human-AI assessment;
- supply-chain assessment;
- legal/policy review.

---

## 5. Readiness Criteria

The responsible authority should define measurable readiness criteria.

Typical criteria include:

- required functionality demonstrated;
- required performance demonstrated;
- relevant robustness demonstrated;
- material failure modes understood;
- safety mechanisms tested;
- security controls implemented;
- configuration verified;
- human authority established;
- autonomy boundaries established;
- operating envelope defined;
- monitoring established;
- incident procedures established;
- evidence gaps documented.

---

## 6. Configuration Readiness

The deployment configuration must be identifiable.

It should include, where applicable:

- model;
- model version;
- weights;
- software;
- hardware;
- data;
- interfaces;
- dependencies;
- parameters;
- safety controls;
- security controls.

Deployment should not proceed against an undefined or uncontrolled configuration.

---

## 7. Configuration Verification

Before deployment:

**Approved Configuration = Deployment Configuration**

Verification should confirm that the configuration intended for operational use corresponds to the configuration assessed through the applicable assurance process.

Material discrepancies should trigger assessment.

---

## 8. TEVV Readiness

The required TEVV stage should be complete for the intended deployment.

Evidence should establish, to the required degree:

- performance;
- reliability;
- robustness;
- security;
- safety;
- uncertainty;
- human interaction;
- autonomy;
- mission effectiveness.

Unresolved evidence gaps should be explicitly considered in the readiness decision.

---

## 9. Operational Environment Readiness

The deployment environment should be assessed against the assumptions used during development and TEVV.

Consider:

- terrain;
- weather;
- lighting;
- sensors;
- communications;
- compute;
- data availability;
- operational tempo;
- user competence;
- adversarial conditions.

Where the deployment environment differs materially from tested conditions, readiness should be reassessed.

---

## 10. Operating Envelope

The deployment should have a defined operating envelope.

The envelope may specify:

- permitted missions;
- permitted environments;
- supported sensors;
- communications assumptions;
- data conditions;
- resource constraints;
- autonomy;
- human supervision;
- prohibited uses;
- performance boundaries.

The system should not be treated as authorised outside its approved envelope.

---

## 11. Human Authority Readiness

Before deployment, the organisation should establish:

- who receives AI outputs;
- who may rely on them;
- who may approve consequential actions;
- who may override the AI;
- who may suspend the capability;
- who may activate emergency procedures;
- who owns operational accountability.

The distinction between:

**AI Recommendation → Human Decision → Authorised Action**

should remain clear unless a different autonomy level has been separately authorised.

---

## 12. Operational AI Advisor

For capabilities with significant AI complexity or operational consequence, deployment readiness should establish access to an appropriately competent **Operational AI Advisor (OAIA)** where required.

The OAIA may bridge:

- commanders;
- system owners;
- developers;
- assurance personnel;
- technical specialists.

The OAIA should help interpret:

- AI limitations;
- uncertainty;
- model behaviour;
- operational boundaries;
- emerging risks;
- material changes.

The OAIA does not replace command authority or technical accountability.

---

## 13. Autonomy Readiness

Where autonomous functions exist, readiness should confirm:

- authorised autonomy level;
- activation conditions;
- operating boundaries;
- supervision;
- intervention;
- transition mechanisms;
- fail-safe;
- termination;
- degraded behaviour.

The capability should not operate at a higher effective autonomy than has been assessed and authorised.

---

## 14. Safety Readiness

Safety readiness should confirm that:

- material hazards are identified;
- controls are implemented;
- fail-safe mechanisms exist;
- emergency procedures are defined;
- intervention mechanisms function;
- degraded states are understood;
- safety evidence is available.

Safety readiness should be demonstrated, not inferred from design intent.

---

## 15. Security Readiness

Security readiness should address:

- system access;
- model integrity;
- data integrity;
- dependencies;
- interfaces;
- credentials;
- update mechanisms;
- monitoring;
- incident response.

Material security deficiencies should affect the deployment decision.

---

## 16. Information Integrity Readiness

Where the AI capability depends on information from multiple sources, readiness should consider:

- source reliability;
- data freshness;
- conflicting information;
- missing information;
- degraded information;
- potential manipulation.

The system should communicate material uncertainty or information limitations where relevant.

---

## 17. Workforce Readiness

Personnel should have appropriate competence for the intended use.

Training may cover:

- system operation;
- AI limitations;
- uncertainty;
- appropriate reliance;
- prohibited uses;
- human authority;
- override;
- fail-safe;
- incident reporting;
- configuration awareness.

Users should understand that AI output is not automatically authoritative.

---

## 18. Sustainment Readiness

Deployment readiness should consider:

- maintenance;
- software support;
- model support;
- data updates;
- hardware support;
- security patching;
- technical assistance;
- training;
- configuration management.

A capability should not be deployed if it cannot reasonably be maintained within its authorised conditions.

---

## 19. Incident Readiness

Before deployment, procedures should exist for:

- reporting failures;
- reporting unsafe behaviour;
- reporting security incidents;
- preserving evidence;
- restricting use;
- suspending the capability;
- escalation;
- investigation;
- recovery.

Incident procedures should identify responsible authorities.

---

## 20. Fail-Safe Readiness

Where consequential harm is possible, readiness should establish that fail-safe mechanisms are:

- available;
- accessible to authorised personnel;
- tested;
- auditable;
- appropriate to the system.

Normal escalation should support informed action through:

**Developer → AI System Manager → OAIA → Command Authority**

Where delay could create unacceptable harm, pre-authorised emergency procedures should allow immediate protective action.

---

## 21. Deployment Monitoring

Monitoring should be established before deployment.

Depending on the use case, it may monitor:

- performance;
- error rates;
- uncertainty;
- distribution shift;
- system health;
- configuration;
- security;
- human overrides;
- autonomous actions;
- incidents.

Monitoring requirements should reflect consequence and autonomy.

---

## 22. Evidence Gaps

Deployment readiness should explicitly identify:

- missing evidence;
- untested conditions;
- unresolved assumptions;
- known limitations;
- residual risks.

An evidence gap should not be hidden by an overall readiness label.

Where deployment proceeds with known gaps, the applicable authority should explicitly understand and accept the associated risk.

---

## 23. Residual Risk

Readiness assessment should distinguish between:

- inherent risk;
- treated risk;
- residual risk;
- accepted risk.

Residual risk should be evaluated against the authority permitted to accept it.

Technical teams should not implicitly accept operational risk merely by declaring a system technically ready.

---

## 24. Readiness Decision

A working readiness model is:

### Ready

Evidence and controls satisfy applicable criteria.

### Conditionally Ready

Deployment may proceed only under specified restrictions or conditions.

### Not Ready

Material evidence, control or risk issues remain.

### Suspended

Previously established readiness is no longer valid due to a material change, incident or emerging risk.

---

## 25. Conditional Readiness

Conditions may address:

- restricted missions;
- restricted environments;
- lower autonomy;
- additional human supervision;
- additional monitoring;
- limited user groups;
- reduced operational exposure;
- additional testing;
- shorter review periods.

Conditions should be explicit and enforceable.

---

## 26. Deployment Readiness Review

The review should include appropriate representatives from:

- capability owner;
- operational authority;
- AI/system owner;
- development;
- TEVV;
- security;
- safety;
- legal/policy where required;
- OAIA where applicable.

The composition should be proportionate to consequence and autonomy.

---

## 27. Independence and Challenge

Readiness review should provide meaningful challenge to:

- developer claims;
- test results;
- assumptions;
- limitations;
- risk assessments;
- operational suitability.

For higher-consequence systems, greater independence should be expected.

---

## 28. Deployment Checklist

A deployment readiness checklist may include:

| Area | Readiness Question |
|---|---|
| Mission | Is the intended use approved? |
| Requirements | Are material requirements satisfied? |
| Risk | Is residual risk understood? |
| Model | Is the model controlled? |
| Data | Is data suitable and traceable? |
| Integration | Is the system integrated and tested? |
| Configuration | Is the deployment baseline verified? |
| TEVV | Is sufficient evidence available? |
| Environment | Is the intended environment represented? |
| Human Authority | Is decision authority clear? |
| Autonomy | Is autonomy assessed and bounded? |
| Safety | Are safety controls tested? |
| Security | Are security controls adequate? |
| Monitoring | Is continuous monitoring established? |
| Incident | Are response procedures ready? |
| Workforce | Are users trained? |
| Sustainment | Can the capability be maintained? |
| Authorisation | Is the capability ready for authorisation? |

---

## 29. Deployment Readiness Record

A Deployment Readiness Record should include, as applicable:

| Field | Description |
|---|---|
| Capability ID | Unique capability identifier |
| Mission | Intended mission/use case |
| Configuration | Deployment configuration |
| Environment | Intended operational environment |
| Autonomy | Intended/assessed autonomy |
| Human Authority | Decision/action authority |
| TEVV Status | Current evidence status |
| Safety | Safety readiness |
| Security | Security readiness |
| Workforce | Training/readiness |
| Monitoring | Monitoring arrangements |
| Incident | Incident arrangements |
| Limitations | Known limitations |
| Evidence Gaps | Remaining gaps |
| Residual Risk | Remaining risk |
| Conditions | Restrictions or conditions |
| Reviewer | Review authority |
| Decision | Ready / Conditional / Not Ready / Suspended |
| Date | Review date |
| Evidence | Supporting evidence |

---

## 30. Readiness and Operational Authorisation

Deployment readiness should lead into operational authorisation:

**Readiness → Authorisation Decision → Deployment**

Readiness does not replace authorisation.

Operational authorisation should determine:

- whether employment is permitted;
- for which mission;
- in which environment;
- at which autonomy;
- under which human authority;
- subject to which restrictions.

---

## 31. Deployment Readiness Exit Criteria

Deployment readiness is complete when:

- the intended mission is defined;
- deployment configuration is verified;
- required TEVV evidence is available;
- operational environment is assessed;
- human authority is established;
- autonomy is bounded;
- safety and security controls are ready;
- monitoring is established;
- incident procedures exist;
- workforce readiness is established;
- residual risk is identified;
- evidence gaps are documented;
- the capability is ready for an operational authorisation decision.

---

## 32. Core Rules

1. **Deployment readiness is a decision gate, not a deployment authority.**
2. **Readiness is specific to mission, environment, configuration, autonomy and human authority.**
3. **A technically complete system is not automatically operationally ready.**
4. **The deployment configuration must be verified against the assured configuration.**
5. **Material evidence gaps must be visible to the decision authority.**
6. **Residual operational risk must be accepted by an appropriate authority.**
7. **Human authority must be explicit before deployment.**
8. **Autonomy must not exceed the assessed and authorised level.**
9. **Safety and security controls must be operationally ready.**
10. **Monitoring and incident response must exist before deployment.**
11. **Conditional deployment must have explicit, enforceable conditions.**
12. **Material changes or incidents may invalidate deployment readiness.**
13. **Higher-consequence systems require stronger evidence and independent challenge.**
14. **Operational readiness should be reassessed when assumptions about the environment or system materially change.**

---

## 33. Golden Thread

Deployment Readiness maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Readiness → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 34. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — defines readiness requirements.
- **03 Risk & Autonomy** — determines readiness depth.
- **04 AI Acquisition** — supports supplier and acquisition readiness.
- **05 Data Preparation** — establishes data readiness.
- **06 Model Development** — establishes model readiness.
- **07 System Integration** — establishes integrated capability readiness.
- **08 Configuration Management** — verifies deployment configuration.
- **09 TEVV** — provides readiness evidence.
- **10 Operational Environment** — establishes environmental readiness.
- **11 Operational Authorisation** — makes the formal employment decision.
- **12 Operational Employment** — governs actual deployment and use.
- **13 Continuous Assurance** — monitors deployed capability.
- **14 Incident & Fail-Safe** — provides response mechanisms.
- **15 Change & Reauthorisation** — governs readiness after change.
- **16 Audit & Evidence** — preserves readiness evidence.
- **17 Workforce** — establishes user competency.
- **22 Acquisition & Procurement** — supports sustainment and contractual readiness.

---

## 35. Summary Model

```text
Mission / Use Case
       ↓
Requirements
       ↓
Risk & Autonomy
       ↓
Development / Acquisition
       ↓
Integration
       ↓
Configuration Baseline
       ↓
TEVV
       ↓
Operational Environment Assessment
       ↓
Safety / Security / Human Authority
       ↓
Monitoring / Incident Readiness
       ↓
Residual Risk
       ↓
Deployment Readiness Review
       ↓
Ready / Conditional / Not Ready / Suspended
       ↓
Operational Authorisation
       ↓
Deployment
```

Deployment Readiness establishes whether an AI-enabled capability has reached the required level of technical, operational and governance maturity to enter the formal operational authorisation process.
