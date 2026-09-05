# Operational Deployment

## Summary

Operational Deployment governs the controlled transition of an authorised defence AI capability into its intended operational environment.

Deployment is the point at which an assured and authorised capability becomes available for actual operational employment. The deployment process must therefore preserve the approved configuration, operational boundaries, human authority, autonomy limits, safety controls and security controls established during the preceding lifecycle stages.

The core chain is:

**Deployment Readiness → Operational Authorisation → Deployment Planning → Controlled Installation → Configuration Verification → Activation → Operational Handover → Monitoring**

---

## 1. Purpose

Operational Deployment establishes controls to ensure that:

- only authorised capabilities are deployed;
- the approved configuration is installed;
- deployment conditions match the authorisation;
- users and commanders understand applicable limitations;
- safety and security controls are active;
- monitoring is established;
- operational accountability is clear;
- deviations are identified and controlled.

---

## 2. Core Principle

**Authorisation to deploy is not authorisation to exceed the approved operational envelope.**

Deployment must preserve the relationship:

**Capability × Mission × Environment × Configuration × Autonomy × Human Authority**

Any material change to these elements may require reassessment or reauthorisation.

---

## 3. Deployment Scope

Operational Deployment may include:

- installation;
- configuration;
- integration into operational infrastructure;
- user provisioning;
- data-source connection;
- communications configuration;
- sensor connection;
- security configuration;
- safety configuration;
- activation;
- operational handover.

The scope should be defined by the authorised use case.

---

## 4. Deployment Preconditions

Before deployment, the responsible authority should confirm:

- operational authorisation is valid;
- deployment configuration is identified;
- deployment environment is within the authorised envelope;
- required TEVV evidence is available;
- safety controls are active;
- security controls are active;
- human authority is established;
- users are trained;
- monitoring is available;
- incident procedures are available;
- sustainment arrangements exist.

---

## 5. Authorised Configuration

Deployment should use the configuration associated with the applicable operational authorisation.

This may include:

- model version;
- model weights;
- software;
- hardware;
- firmware;
- data;
- interfaces;
- parameters;
- dependencies;
- safety controls;
- security controls.

---

## 6. Deployment Verification

Before activation, the deployed configuration should be verified.

The verification should establish:

**Approved Baseline = Installed Configuration**

Where material discrepancies exist:

- deployment should be paused;
- the discrepancy should be assessed;
- the appropriate authority should determine whether correction, additional testing or reauthorisation is required.

---

## 7. Environment Verification

The deployment environment should be checked against the conditions assumed during assurance.

Relevant factors may include:

- sensors;
- communications;
- compute;
- data availability;
- network conditions;
- physical environment;
- supporting infrastructure;
- user competence.

Material differences should be escalated before operational activation.

---

## 8. Data Connection

Where the capability depends on operational data, deployment should verify:

- authorised data sources;
- data pathways;
- source integrity;
- access controls;
- expected data format;
- data freshness;
- failure handling.

Unapproved data sources should not be connected merely because the system can technically consume them.

---

## 9. Communications

Deployment should establish expected behaviour under:

- normal communications;
- degraded communications;
- intermittent communications;
- communications loss.

Where the capability can operate without connectivity, the applicable offline behaviour should be understood and authorised.

---

## 10. Human Authority

Deployment should explicitly establish:

- operational user;
- supervising authority;
- decision authority;
- action authority;
- override authority;
- suspension authority;
- emergency authority.

The deployed system should not create ambiguity about who is responsible for a consequential decision or action.

---

## 11. Operational AI Advisor

Where required by the capability's risk or complexity, deployment should ensure access to an **Operational AI Advisor (OAIA)**.

The OAIA may support commanders and system owners by interpreting:

- AI limitations;
- uncertainty;
- operational boundaries;
- model behaviour;
- emerging risks;
- material changes.

The OAIA advises but does not replace command authority, technical ownership or formal assurance functions.

---

## 12. Autonomy Activation

If autonomous functionality exists, deployment should verify:

- authorised autonomy level;
- activation conditions;
- supervision;
- action boundaries;
- intervention;
- transition mechanisms;
- fail-safe;
- termination.

The capability should not activate an autonomy mode that has not been authorised.

---

## 13. Safe Activation

Activation should occur through a controlled process.

Before activation, confirm:

- system health;
- configuration;
- security status;
- safety status;
- data availability;
- communications status;
- monitoring;
- human authority;
- applicable restrictions.

---

## 14. Operational Handover

Handover from development or technical teams to operational users should establish:

- capability purpose;
- authorised use;
- limitations;
- operating envelope;
- configuration;
- autonomy;
- human authority;
- monitoring;
- incident procedures;
- fail-safe;
- escalation routes.

Handover should include acknowledgement by the receiving authority where appropriate.

---

## 15. User Readiness

Operational users should understand:

- what the system does;
- what it does not do;
- how to interpret outputs;
- how uncertainty is communicated;
- when not to rely on outputs;
- how to challenge recommendations;
- how to override or suspend the system;
- how to report incidents.

Training should be proportionate to consequence and autonomy.

---

## 16. Operational Restrictions

Deployment may be subject to restrictions such as:

- specific missions;
- specific environments;
- specific users;
- specific autonomy levels;
- specific operating periods;
- additional human supervision;
- limited data sources;
- increased monitoring.

Restrictions should be recorded and communicated to affected personnel.

---

## 17. Conditional Deployment

A capability may be deployed conditionally where the authorisation explicitly permits it.

Conditions should be:

- specific;
- measurable;
- operationally understandable;
- enforceable;
- monitored.

Failure to satisfy a condition should trigger appropriate escalation.

---

## 18. Safety Controls

Before activation, safety controls should be verified, including where applicable:

- action constraints;
- interlocks;
- human approval mechanisms;
- fail-safe;
- degraded modes;
- emergency shutdown;
- recovery.

Safety controls should remain available during operational employment.

---

## 19. Security Controls

Deployment should verify:

- access control;
- authentication;
- system integrity;
- model integrity;
- data integrity;
- approved interfaces;
- dependency status;
- logging;
- monitoring.

Security configuration should correspond to the authorised baseline.

---

## 20. Fail-Safe and Emergency Action

Where the capability can create consequential harm, the deployment process should confirm that fail-safe mechanisms are operational.

Normal escalation may follow:

**User / Operator → System Manager → OAIA → Command Authority**

Where delay could create unacceptable harm, pre-authorised emergency procedures should allow immediate protective action.

Emergency use of fail-safe mechanisms should be recorded and subsequently reviewed.

---

## 21. Monitoring Activation

Monitoring should begin before or at activation.

Depending on the capability, monitoring may include:

- system health;
- model performance;
- uncertainty;
- data quality;
- configuration;
- security;
- safety;
- human overrides;
- autonomous actions;
- incidents.

---

## 22. Operational Logging

Where appropriate, deployment should establish logging sufficient to reconstruct:

- system identity;
- model version;
- configuration;
- user;
- inputs;
- outputs;
- uncertainty;
- approvals;
- overrides;
- actions;
- incidents.

Logging requirements should be proportionate to consequence.

---

## 23. Accountability

For consequential AI-supported decisions or actions, deployment should support reconstruction of:

**Who → Which Capability → Which Configuration → What Information → AI Output → Human Decision → Action → Outcome**

The purpose is accountability and learning, not merely technical troubleshooting.

---

## 24. Deployment Deviations

A deviation may occur when:

- the environment differs from the authorisation;
- the configuration differs from the baseline;
- required controls are unavailable;
- communications assumptions fail;
- data sources change;
- users lack required competence;
- autonomy conditions change.

Material deviations should be escalated and may require restriction or suspension.

---

## 25. Deployment in Degraded Conditions

Where degraded deployment is authorised, the system should operate only within defined degraded conditions.

The deployment plan should establish:

- expected degradation;
- permitted functions;
- prohibited functions;
- human supervision;
- fail-safe;
- recovery;
- escalation.

---

## 26. Offline Operation

Where offline operation is authorised, deployment should verify:

- local dependencies;
- available data;
- model availability;
- system resources;
- logging;
- uncertainty behaviour;
- autonomy constraints;
- recovery after reconnection.

Loss of connectivity should not silently change the authorised role of the AI.

---

## 27. Operational Environment Confirmation

Following activation, the operational authority should confirm that:

- actual environment is within the authorised envelope;
- system performance is consistent with expectations;
- material assumptions remain valid;
- no unexpected behaviour is observed.

Unexpected material behaviour should trigger escalation.

---

## 28. Deployment Acceptance

Operational acceptance should establish that:

- the capability is installed;
- configuration is verified;
- required controls are active;
- users are ready;
- monitoring is active;
- restrictions are understood;
- operational authority has accepted the deployment.

Acceptance does not remove the requirement for continuous assurance.

---

## 29. Deployment Status

A working status model is:

### Planned

Deployment approved for preparation.

### Ready for Deployment

All preconditions satisfied.

### Deployed

Capability installed but not necessarily active.

### Operationally Active

Capability is being used under valid authorisation.

### Restricted

Use limited by defined conditions.

### Suspended

Operational use temporarily stopped.

### Withdrawn

Capability removed from operational service.

---

## 30. Deployment Incident

Deployment-related incidents may include:

- incorrect configuration;
- unauthorised activation;
- unexpected autonomy;
- security compromise;
- unsafe behaviour;
- incorrect data connection;
- unexpected performance;
- loss of human control.

Incidents should be handled under the applicable incident and fail-safe process.

---

## 31. Post-Deployment Review

After deployment, an initial review should assess:

- actual performance;
- user understanding;
- unexpected behaviours;
- environmental differences;
- data quality;
- configuration integrity;
- incidents;
- emerging risks.

The review should inform continuous assurance.

---

## 32. Deployment Change Control

Changes after deployment should remain subject to configuration and change management.

Potentially material changes include:

- model updates;
- software updates;
- new data sources;
- new sensors;
- new interfaces;
- changed autonomy;
- changed operating environment.

Material changes may require revalidation or reauthorisation before continued use.

---

## 33. Deployment Record

An Operational Deployment Record should include, as applicable:

| Field | Description |
|---|---|
| Capability ID | Unique capability identifier |
| Authorisation ID | Related operational authorisation |
| Configuration | Deployed configuration |
| Environment | Deployment environment |
| Data Sources | Connected data sources |
| Communications | Communications state |
| Autonomy | Active/authorised autonomy |
| Human Authority | Operational authority |
| Users | Authorised users |
| Restrictions | Deployment conditions |
| Safety | Safety controls |
| Security | Security controls |
| Monitoring | Monitoring status |
| Handover | Handover record |
| Acceptance | Operational acceptance |
| Deviations | Material deviations |
| Incidents | Deployment incidents |
| Date | Deployment date |
| Status | Current deployment status |

---

## 34. Deployment Exit Criteria

Operational Deployment is complete when:

- operational authorisation is valid;
- authorised configuration is verified;
- environment is within scope;
- required data connections are controlled;
- human authority is established;
- autonomy is correctly configured;
- safety and security controls are active;
- users are ready;
- monitoring is active;
- incident procedures are available;
- restrictions are understood;
- operational acceptance is recorded.

---

## 35. Core Rules

1. **Only an authorised capability should be operationally deployed.**
2. **Deployment must preserve the authorised configuration and operating envelope.**
3. **The deployed configuration must be verified before activation.**
4. **Human authority must be explicit at the point of deployment.**
5. **Autonomy must not exceed the authorised level.**
6. **Operational restrictions must be visible to affected users.**
7. **Safety and security controls must be active before consequential use.**
8. **Monitoring and incident response must be operational at deployment.**
9. **Material deviations from the authorised conditions must be escalated.**
10. **Offline and degraded behaviour must be consistent with the authorised role of the AI.**
11. **Deployment records must support reconstruction of consequential events.**
12. **Material post-deployment changes may require revalidation or reauthorisation.**
13. **Operational deployment does not end the assurance lifecycle.**

---

## 36. Golden Thread

Operational Deployment maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Readiness → Authority → Deployment → Employment → Monitoring → Change/Incident → Reauthorisation**

---

## 37. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 AI Requirements** — defines deployment requirements.
- **03 Risk & Autonomy** — establishes deployment risk and autonomy conditions.
- **05 Data Preparation** — controls operational data inputs.
- **06 Model Development** — establishes the approved model baseline.
- **07 System Integration** — establishes the integrated capability.
- **08 Configuration Management** — verifies deployment configuration.
- **09 TEVV** — provides deployment evidence.
- **10 Operational Environment** — establishes environmental assumptions.
- **11 Operational Authorisation** — provides the authority to deploy.
- **12 Operational Employment** — governs use after deployment.
- **13 Continuous Assurance** — monitors deployed capability.
- **14 Incident & Fail-Safe** — governs incident response and protective action.
- **15 Change & Reauthorisation** — governs post-deployment changes.
- **16 Audit & Evidence** — preserves deployment records.
- **17 Workforce** — establishes user readiness.
- **24 Architecture & Technical Controls** — supports deployment architecture and controls.

---

## 38. Summary Model

```text
Deployment Readiness
        ↓
Operational Authorisation
        ↓
Deployment Planning
        ↓
Configuration Verification
        ↓
Environment Verification
        ↓
Safety / Security Verification
        ↓
Human Authority / Autonomy Verification
        ↓
Controlled Activation
        ↓
Operational Handover
        ↓
Monitoring
        ↓
Operational Employment
        ↓
Incident / Change
        ↓
Revalidation / Reauthorisation
```

Operational Deployment converts an authorised AI capability into an operationally usable capability while preserving configuration, authority, safety, security and assurance controls.
