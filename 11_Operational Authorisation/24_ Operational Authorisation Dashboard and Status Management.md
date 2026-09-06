# 24 Operational Authorisation Dashboard and Status Management

## 1. Purpose

Operational authorisation for Defence AI is not a one-time approval event. It is a controlled state that must remain visible, current and traceable throughout the capability lifecycle and operational period.

This document defines a governance approach for maintaining an operational authorisation status view across capabilities, missions, environments, autonomy levels, human authorities, conditions, evidence, incidents and changes.

The objective is to provide responsible authorities with a reliable view of:

- what is authorised;
- what is currently ready;
- what is deployed;
- what is being employed;
- what restrictions apply;
- what evidence supports authority;
- what conditions are changing; and
- what requires action.

---

## 2. Core Principle

Operational authorisation status should be **visible, current, evidence-based and unambiguous**.

A capability should not be treated as authorised merely because an approval exists somewhere in a document repository.

The current governance state should be capable of being determined from controlled records.

---

## 3. Status Object

The status view should connect:

**AI Capability × Mission × Environment × Autonomy × Human Authority × Configuration × Conditions**

This allows the organisation to distinguish between:

- capability-level status;
- mission-specific authority;
- environment-specific authority;
- autonomy-specific authority;
- current readiness;
- deployment status; and
- actual employment status.

---

## 4. Authorisation Status

The core operational authorisation states are:

| State | Meaning |
|---|---|
| **Proposed** | Operational authority is being considered. |
| **Under Assurance** | Required evidence and assessments are being developed or reviewed. |
| **Conditionally Authorised** | Operational use is permitted subject to defined conditions. |
| **Operationally Authorised** | Operational use is authorised within defined scope. |
| **Restricted** | Authority remains in force but with reduced scope or additional controls. |
| **Suspended** | Operational authority is temporarily inactive. |
| **Revoked** | Operational authority has been formally withdrawn. |
| **Retired** | The capability has reached the end of its authorised lifecycle. |

Status should never be inferred from technical availability.

---

## 5. Readiness Status

Authorisation status should be displayed separately from current readiness.

Readiness states are:

- **Ready**
- **Conditionally Ready**
- **Not Ready**
- **Temporarily Not Ready**
- **Suspended**

A capability may therefore be:

**Operationally Authorised + Not Ready**

or:

**Conditionally Authorised + Conditionally Ready**

This distinction is essential.

---

## 6. Deployment Status

Where deployment is relevant, the status view should also identify:

- Planned;
- Approved for Deployment;
- In Deployment;
- Operationally Deployed;
- Restricted Deployment;
- Deployment Halted; or
- Deployment Reversed.

Deployment status should not be interpreted as operational permission.

---

## 7. Employment Status

Where the capability is deployed, the current employment state may be:

- Not Employed;
- Active Employment;
- Restricted Employment;
- Degraded Employment;
- Contingency Employment;
- Suspended; or
- Terminated.

This provides a common operational picture across governance states.

---

## 8. Status Dimensions

A useful authorisation dashboard should include, as applicable:

### Authority
- authorisation status;
- authorising authority;
- validity period;
- conditions;
- restrictions;
- suspension triggers.

### Mission
- mission;
- use case;
- mission criticality;
- approved functions;
- prohibited functions.

### Environment
- authorised environment;
- current environment;
- operating-envelope status;
- degraded status;
- boundary status.

### Autonomy
- authorised autonomy;
- current autonomy;
- autonomy restrictions;
- transition status.

### Human Authority
- decision authority;
- supervisor;
- operator;
- Operational AI Advisor;
- human-control status.

### Configuration
- authorised baseline;
- deployed baseline;
- current configuration;
- material changes.

### Assurance
- assurance status;
- latest TEVV;
- evidence currency;
- unresolved findings;
- revalidation status.

### Security
- security status;
- open critical issues;
- relevant incidents;
- integrity status.

### Data
- data status;
- provenance;
- quality;
- drift;
- integrity concerns.

### Dependencies
- critical dependencies;
- availability;
- degradation;
- contingency status.

### Operations
- readiness;
- deployment;
- employment;
- incidents;
- interventions.

---

## 9. Status Indicators

A simple working status indicator may use:

| Indicator | Meaning |
|---|---|
| **Green** | Conditions and evidence remain within authorised expectations. |
| **Amber** | A condition requires attention, additional monitoring or a defined restriction. |
| **Red** | Operational authority or readiness may no longer be valid; immediate action or escalation is required. |
| **Grey** | Status is unavailable, not assessed or not applicable. |

Colour should not replace the underlying evidence or decision record.

---

## 10. Critical Status Conditions

The dashboard should highlight conditions capable of invalidating authority, including:

- expired authorisation;
- failed mandatory condition;
- material configuration change;
- significant performance degradation;
- loss of meaningful human control;
- unauthorised autonomy;
- critical security issue;
- critical data-integrity issue;
- critical dependency failure;
- environment outside the authorised envelope;
- unresolved serious incident;
- failed revalidation;
- overdue mandatory assurance activity; or
- inability to establish current status.

---

## 11. Evidence Currency

Status should indicate whether supporting evidence remains current.

Evidence may be classified as:

- Current;
- Approaching Review;
- Expired;
- Superseded;
- Invalidated;
- Under Reassessment; or
- Unavailable.

Evidence should not remain marked current solely because no new test has yet been performed.

---

## 12. Condition Management

Operational authorisation conditions should have explicit status.

For each condition, where applicable, identify:

- condition;
- responsible owner;
- verification method;
- current status;
- evidence;
- review date;
- consequence of failure;
- required response.

A failed mandatory condition should automatically trigger the applicable governance response.

---

## 13. Restriction Management

Restrictions should be visible and specific.

The status view should identify:

- restriction;
- reason;
- affected mission;
- affected environment;
- affected autonomy;
- duration;
- authority;
- verification requirement;
- removal criteria.

Restrictions should not be buried in supporting documentation where operational personnel need to know them.

---

## 14. Suspension Status

A suspended capability should clearly identify:

- suspension authority;
- effective date/time;
- reason;
- affected scope;
- prohibited employment;
- interim controls;
- investigation status;
- restoration criteria;
- revalidation requirements;
- reauthorisation requirements; and
- responsible authority.

Suspension should remain visible until formally lifted.

---

## 15. Expiry and Renewal

The status system should identify upcoming:

- authorisation expiry;
- review dates;
- assurance renewals;
- TEVV activities;
- evidence reviews;
- condition reviews;
- delegated authority expiry; and
- other governance deadlines.

An approaching expiry should create sufficient time for responsible authorities to act.

Expired authority should not be treated as active merely because renewal is expected.

---

## 16. Change Status

Material changes should be visible in the status view.

The record should identify:

- change identifier;
- change type;
- affected capability;
- affected configuration;
- impact assessment;
- assurance status;
- approval status;
- revalidation requirement;
- reauthorisation requirement;
- deployment status; and
- implementation status.

A pending material change should not be confused with an approved operational configuration.

---

## 17. Incident Status

The dashboard should identify material incidents affecting:

- capability;
- mission;
- environment;
- human control;
- autonomy;
- security;
- data;
- dependencies; or
- authorisation validity.

Where an incident may invalidate authority, this should be clearly escalated.

---

## 18. Dynamic Operational Status

During employment, status may change rapidly.

The status mechanism should support timely updates following:

- environmental change;
- performance degradation;
- loss of communications;
- loss of human supervision;
- autonomy transition;
- security event;
- data-integrity concern;
- dependency failure;
- unexpected AI behaviour;
- mission change; or
- incident.

The dashboard should distinguish between **current operational status** and **historical status**.

---

## 19. Status Ownership

Every material status should have a responsible owner.

Ownership may be assigned to:

- Authorising Authority;
- Command/Operational Authority;
- Capability Owner;
- System Manager;
- Technical Authority;
- Assurance/TEVV Authority;
- Security Authority;
- Risk Owner; or
- another formally designated role.

No critical status should depend on an undefined or assumed owner.

---

## 20. Status Update Authority

Not every role should be able to change an authorisation status.

The organisation should define:

- who may create status;
- who may modify status;
- who may approve status;
- who may suspend status;
- who may restore status;
- who may revoke authority; and
- who may view or audit status.

Technical system controls should enforce these rights where practicable.

---

## 21. Status Integrity

Operational status records should be protected against:

- unauthorised changes;
- deletion;
- stale information;
- contradictory records;
- misleading status indicators;
- configuration mismatch; and
- loss of audit history.

Changes should be attributable to an authorised person or controlled process.

---

## 22. Status History

The system should preserve a history of material status changes.

The history should establish:

- previous status;
- new status;
- date/time;
- authority;
- reason;
- evidence;
- conditions;
- related incident or change;
- resulting action.

This enables reconstruction of how operational authority evolved over time.

---

## 23. Status Escalation

Status conditions should trigger escalation where required.

Examples include:

**Green → Amber**
- emerging performance degradation;
- evidence nearing expiry;
- environmental boundary approach;
- increased uncertainty;
- dependency degradation.

**Amber → Red**
- mandatory condition failure;
- loss of meaningful human control;
- critical security event;
- unauthorised autonomy;
- material configuration discrepancy;
- environment outside authorised envelope;
- serious unresolved incident.

Escalation criteria should be defined before they are needed.

---

## 24. Dashboard and Decision-Making

The dashboard is a decision-support mechanism.

It should help responsible authorities answer:

- Is the capability authorised?
- Is it currently ready?
- Is it deployed?
- Is it being employed?
- Under what conditions?
- At what autonomy?
- Under whose authority?
- What restrictions apply?
- What evidence supports continued use?
- What has changed?
- What requires action?

The dashboard itself does not grant authority.

---

## 25. Offline and Disconnected Operation

Where operational conditions prevent access to a central status system, an approved local or offline representation should be available where practicable.

The local status should identify:

- current authorisation;
- restrictions;
- autonomy;
- human authority;
- configuration;
- readiness;
- contingency conditions;
- last verified status; and
- update/reconciliation requirements.

When connectivity is restored, local status changes should be reconciled into the authoritative record.

---

## 26. Status Reconciliation

Where multiple records or systems exist, the organisation should establish a source of authoritative status.

Potentially conflicting information should be resolved through defined governance rather than informal interpretation.

The principle should be:

**One authoritative operational status; multiple supporting evidence sources.**

---

## 27. Use During Operational Handover

During changes of command, shift changes or responsibility transfers, current status should form part of the handover.

The receiving authority should understand:

- authorisation;
- readiness;
- deployment;
- employment;
- restrictions;
- autonomy;
- human authority;
- incidents;
- changes;
- dependencies; and
- outstanding actions.

This reduces the risk of operational authority being lost through organisational transition.

---

## 28. Governance Review

The authorisation status system should itself be periodically reviewed for:

- accuracy;
- completeness;
- timeliness;
- usability;
- evidence linkage;
- ownership;
- access control;
- status integrity;
- escalation effectiveness; and
- alignment with actual operational conditions.

A governance dashboard that is inaccurate or stale can create operational risk.

---

## 29. Relationship to Continuous Assurance

Status management connects operational evidence to governance action:

**Monitoring → Status Change → Assessment → Risk → Assurance → Restriction/Suspension/Revalidation/Reauthorisation**

This creates a visible operational control loop.

---

## 30. Golden Thread

Operational authorisation status remains connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Reauthorisation**

The status view should provide a practical representation of this governance chain.

---

## 31. Governance Questions

Responsible authorities should be able to determine:

1. Is this capability authorised?
2. What exact mission is authorised?
3. What environment is authorised?
4. What autonomy is authorised?
5. Who holds human authority?
6. What configuration is authorised?
7. Is the capability currently ready?
8. Is it deployed?
9. Is it currently employed?
10. What conditions apply?
11. What restrictions apply?
12. Is supporting evidence current?
13. Are there unresolved incidents?
14. Have material changes occurred?
15. Are critical dependencies available?
16. Is security status acceptable?
17. Is data integrity acceptable?
18. Is the current environment within the authorised envelope?
19. What would cause restriction or suspension?
20. Who has authority to make the next governance decision?

---

## 32. Core Rule

> **Operational authorisation status shall be maintained as a current, controlled and evidence-linked governance state. Responsible authorities shall be able to determine what is authorised, what is ready, what is deployed, what is being employed, what restrictions apply and what conditions may invalidate authority. The status mechanism shall inform decisions but shall never itself create operational authority.**
