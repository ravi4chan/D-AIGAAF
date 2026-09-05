# D-AIGAAF — Data Access Control

## 1. Purpose

This document defines the governance and assurance approach for controlling access to data used by defence AI capabilities.

Data access control ensures that people, systems and services can access data only when they have:

- appropriate authority
- an authorised purpose
- an established need
- appropriate eligibility
- the minimum privileges required

Access control must protect both the confidentiality and integrity of data while ensuring that authorised AI capabilities remain operationally effective.

---

## 2. Core Principle

> **Technical ability to access data does not constitute authority to use it.**

Access should be governed through:

**Need → Authority → Eligibility → Purpose → Least Privilege → Controlled Access → Monitoring → Review → Revocation**

---

## 3. Scope

This document applies to:

- training data
- validation and test data
- operational data
- intelligence and information
- sensor data
- geospatial data
- datasets
- model inputs
- model outputs
- metadata
- provenance and lineage records
- data repositories
- data pipelines
- AI development environments
- operational AI systems
- third-party and supplier access
- machine-to-machine access

---

## 4. Access Control Objectives

Access governance should establish that:

1. access is authorised
2. access is necessary
3. access is appropriate to the data classification
4. access is limited to the required scope
5. access is attributable to an identity or system
6. privileged access receives additional controls
7. access is monitored
8. access is periodically reviewed
9. inappropriate access can be revoked
10. access decisions are auditable

---

## 5. Access Decision Model

A practical access decision should consider:

**Who → What → Why → When → Where → Under What Authority → With What Privilege**

The decision should be based on the combined assessment rather than identity alone.

---

## 6. Identity

Each human or system accessing protected data should have an identifiable identity where technically and operationally feasible.

Identity controls should support:

- unique identification
- authentication
- accountability
- credential management
- lifecycle management
- revocation

Shared accounts should be avoided where they prevent meaningful attribution.

---

## 7. Authentication

Authentication strength should be proportionate to:

- data sensitivity
- mission consequence
- privilege level
- threat
- operational environment

Where appropriate, stronger authentication mechanisms should be required for privileged or high-consequence access.

---

## 8. Authorisation

Authorisation determines whether an identified entity is permitted to access a particular resource.

Authorisation should consider:

- role
- clearance or eligibility
- need-to-know
- purpose
- mission
- data classification
- environment
- time
- privilege
- applicable restrictions

---

## 9. Need-to-Know

Need-to-know should be established independently from general organisational membership.

A person may have appropriate credentials and still not have an authorised need to access particular data.

Need-to-know should be:

- purpose-specific
- current
- reviewable
- revocable

---

## 10. Purpose-Based Access

Where appropriate, access should be linked to an authorised purpose.

Examples include:

- development
- testing
- assurance
- operational employment
- incident investigation
- maintenance
- audit

Access granted for one purpose should not automatically permit another use.

---

## 11. Least Privilege

Access should provide only the permissions necessary to perform the authorised task.

Examples include:

- read-only access
- write access
- execute access
- administrative access
- export access
- sharing access
- deletion access

Higher privileges should require stronger justification and controls.

---

## 12. Separation of Duties

Critical activities should be separated where practical.

Examples may include separating:

- data ownership
- development
- testing
- assurance
- access administration
- risk acceptance
- operational authorisation
- operational employment

No individual should have unnecessary control over the complete assurance chain.

---

## 13. Privileged Access

Privileged access can materially affect:

- datasets
- pipelines
- models
- system configurations
- audit records
- security controls

Privileged accounts should therefore receive:

- enhanced authentication
- restricted use
- additional monitoring
- periodic review
- controlled elevation
- rapid revocation capability

---

## 14. Administrative Access

Administrative access should be distinct from routine user access where practical.

Administrative activities should be attributable and recorded.

Administrative access should not automatically provide unrestricted access to operational data.

---

## 15. Machine-to-Machine Access

AI systems and data pipelines may require automated access.

Machine identities should be governed similarly to human identities.

Controls should address:

- unique machine identity
- authorised service relationship
- permitted data scope
- credential management
- expiration
- monitoring
- revocation
- dependency changes

---

## 16. Application and API Access

Where data is accessed through applications or interfaces, access controls should apply to the interface as well as the underlying data.

Controls should consider:

- authenticated clients
- authorised operations
- data scope
- rate limits where appropriate
- logging
- service identity
- input validation
- output restrictions

---

## 17. Data Repository Access

Repositories should implement access controls appropriate to:

- classification
- data sensitivity
- mission consequence
- user role
- operational environment

Repositories should maintain records of material access where required.

---

## 18. Training Data Access

Training datasets should be accessible only to personnel and systems with an authorised development or assurance requirement.

Controls should address:

- read access
- modification
- export
- copying
- deletion
- annotation
- preprocessing
- backup access

Training-data access should remain consistent with its classification and handling requirements.

---

## 19. Validation and Test Data Access

Test data should be accessible only to authorised personnel and systems.

Where test integrity is important, access should prevent unauthorised modification or contamination.

Access to test datasets should be controlled separately from training-data modification privileges where practical.

---

## 20. Operational Data Access

Operational data may require stronger controls because of its potential mission consequence.

Access should account for:

- operational role
- current mission
- geographic or organisational scope
- data sensitivity
- time
- system state
- emergency conditions

Operational access should remain attributable.

---

## 21. Emergency Access

Operational circumstances may require exceptional access.

Emergency access should be:

- pre-defined where possible
- authorised
- time-limited
- monitored
- recorded
- reviewed afterwards

Emergency access should not become a permanent bypass of normal access controls.

---

## 22. Break-Glass Access

Where a break-glass mechanism is necessary, it should provide exceptional access while preserving accountability.

Controls should include:

- explicit activation
- justification
- limited duration
- enhanced logging
- post-event review
- automatic or administrative revocation

---

## 23. Access from Degraded Environments

Where AI systems operate in constrained environments, access controls should account for:

- intermittent connectivity
- offline operation
- delayed synchronisation
- local credentials
- temporary access
- recovery after reconnection

Security controls should remain effective without creating unsafe operational dependencies.

---

## 24. Offline Access

Offline access should be explicitly authorised where required.

Controls should address:

- local storage
- credential validity
- data expiry
- local access privileges
- synchronisation
- revocation limitations
- recovery

Offline access should not automatically imply unrestricted local authority.

---

## 25. Data Export

Export rights can create significant disclosure risk.

Export controls should consider:

- classification
- destination
- purpose
- recipient
- volume
- format
- authorisation
- logging

Where practical, export should be separately controlled from ordinary read access.

---

## 26. Data Sharing and Forwarding

Users should not assume that access rights include authority to share data.

Sharing should require appropriate:

- authority
- recipient validation
- classification compatibility
- purpose
- transfer mechanism
- logging

---

## 27. Supplier Access

Supplier and contractor access should be:

- explicitly authorised
- purpose-specific
- time-limited where appropriate
- least-privileged
- monitored
- contractually governed
- revocable

Supplier access should not exceed the organisation's operational requirement.

---

## 28. Third-Party Systems

Where external systems interact with protected data, the organisation should establish:

- approved connection
- data scope
- security requirements
- access authority
- ownership
- monitoring
- incident responsibilities
- termination conditions

External connectivity should be treated as a controlled dependency.

---

## 29. Access Control and Data Classification

Access permissions should reflect classification and handling requirements.

A higher classification or sensitivity should generally require stronger access controls.

However:

**Classification → Required Protection**

does not automatically mean:

**Classification → Authorised User**

Authorisation still requires need and purpose.

---

## 30. Access Control and Data Integrity

Access control should protect against unauthorised modification.

For critical data, permissions should distinguish between:

- viewing
- creating
- modifying
- approving
- deleting
- exporting

This supports both integrity and accountability.

---

## 31. Access Control and AI Security

Compromised access credentials can allow manipulation of:

- training data
- model inputs
- operational data
- configurations
- logs
- assurance evidence

Access control should therefore form part of the AI security architecture.

---

## 32. Access Control and Model Behaviour

Access to data may indirectly affect model behaviour.

Examples include:

- modifying training data
- changing reference datasets
- altering retrieval sources
- changing operational inputs
- modifying feedback data

Access governance should therefore protect not only information but also the conditions influencing AI behaviour.

---

## 33. Access Control and TEVV

TEVV environments should ensure that only authorised personnel can modify the evidence base.

Controls should distinguish, where appropriate, between:

- test execution
- test data modification
- result generation
- result approval
- assurance review

This reduces the risk that test evidence can be altered by the same party responsible for development.

---

## 34. Access Control and Operational Authorisation

Operational authorisation should establish material access conditions where necessary.

These may include:

- authorised user groups
- permitted systems
- data scope
- privilege level
- emergency access
- monitoring
- review requirements

Changes to material access conditions may require reassessment.

---

## 35. Access Reviews

Access should be reviewed periodically and when material circumstances change.

Review triggers may include:

- role change
- transfer
- retirement
- mission change
- data reclassification
- system change
- supplier change
- security incident
- prolonged inactivity

Unnecessary access should be removed promptly.

---

## 36. Access Revocation

Revocation should be possible when:

- authority expires
- need ends
- role changes
- credentials are compromised
- mission ends
- contract ends
- security conditions change
- access is misused

Revocation procedures should be tested for effectiveness.

---

## 37. Access Monitoring

Monitoring should identify:

- unusual access
- excessive access
- failed authentication
- privilege escalation
- bulk extraction
- unexpected geographic or system access
- access outside authorised periods
- unusual machine-to-machine activity

Monitoring should be proportionate to risk.

---

## 38. Access Anomalies

An access anomaly should be assessed to determine whether it represents:

- normal operational variation
- policy violation
- credential compromise
- insider misuse
- system error
- malicious activity

Material anomalies should enter the applicable incident-management process.

---

## 39. Access and Audit Records

Access records should support reconstruction of material access events.

Where appropriate, records should include:

- identity
- resource
- action
- timestamp
- authorisation context
- source system
- result

Retention should follow applicable policy.

---

## 40. Access Control Testing

Access controls should be tested periodically.

Testing may include:

- permission reviews
- access-control testing
- privilege escalation testing
- credential testing
- revocation testing
- emergency-access testing
- segregation-of-duties testing
- configuration review

High-consequence systems should receive stronger assurance.

---

## 41. Access Control Assessment Method

A practical assessment can follow:

1. Identify the data.
2. Identify its classification and sensitivity.
3. Identify authorised purposes.
4. Identify users and systems.
5. Establish authority and need-to-know.
6. Define least-privilege permissions.
7. Establish authentication requirements.
8. Establish privileged-access controls.
9. Define monitoring.
10. Define review and revocation.
11. Test access controls.
12. Record evidence.
13. Monitor material changes.

---

## 42. Access Control Assurance Levels

A working model may be:

### AC1 — Basic

Standard identity and access controls.

### AC2 — Controlled

Defined roles, permissions and access reviews.

### AC3 — Assured

Access controls tested and monitored.

### AC4 — High Assurance

Strong privileged-access controls, enhanced monitoring and independent verification.

### AC5 — Critical

Highest level of access-control assurance for highly consequential AI capabilities.

These are D-AIGAAF working constructs and should be mapped to applicable organisational, national and defence security requirements before formal adoption.

---

## 43. Access Control Record

An Access Control Record should include:

| Field | Description |
|---|---|
| Access ID | Unique identifier |
| Data Asset | Protected data |
| Classification | Applicable classification |
| Subject | Person/system identity |
| Purpose | Authorised purpose |
| Authority | Approval basis |
| Privilege | Granted permissions |
| Scope | Data/system scope |
| Duration | Access period |
| Monitoring | Monitoring requirements |
| Review | Review date |
| Revocation | Revocation conditions |
| Evidence | Supporting evidence |
| Owner | Accountable owner |

---

## 44. Common Failure Modes

- Assuming system access equals authority to use data.
- Granting broad access for convenience.
- Failing to distinguish read, write, export and delete permissions.
- Using shared accounts that prevent attribution.
- Leaving former users or suppliers with active access.
- Failing to review privileged accounts.
- Allowing development access to operational data without justification.
- Treating machine identities as less important than human identities.
- Allowing emergency access to become permanent.
- Failing to monitor unusual access.
- Allowing access to alter assurance evidence.
- Failing to assess access changes after a model or mission change.

---

## 45. Core Rules

1. **Access requires authority, need and an authorised purpose.**
2. **Technical capability does not constitute authority.**
3. **Least privilege should be the default.**
4. **Privileged access requires additional controls.**
5. **Human and machine identities should be attributable.**
6. **Access should remain consistent with data classification and handling requirements.**
7. **Export and sharing should receive explicit control.**
8. **Emergency access should remain temporary, accountable and reviewable.**
9. **Access should be monitored according to risk.**
10. **Unnecessary access should be revoked promptly.**
11. **Material access changes should be assessed for impact on AI security and assurance.**
12. **Access-control evidence must remain connected to the D-AIGAAF Golden Thread.**

---

## 46. Golden Thread

Data access control contributes to:

**Mission Need → Data Dependency → Classification → Authorised Purpose → Access Authority → Permissions → Controls → Monitoring → Evidence → Assurance → Authority → Employment → Incident / Change → Revalidation → Reauthorisation**

The objective is to establish:

**Who can access what → Why they can access it → What they can do → Under whose authority → For how long → How that access is monitored and revoked**

---

## 47. Relationship to Other D-AIGAAF Sections

This document should be read with:

- **00 Framework**
- **01 Strategy & Governance**
- **02 Mission & Use Case**
- **03 Risk & Autonomy**
- **04 AI Lifecycle**
- **05 Data & Information — Data Governance Model**
- **05 Data & Information — Data Governance**
- **05 Data & Information — Data Provenance**
- **05 Data & Information — Data Quality**
- **05 Data & Information — Data Representativeness**
- **05 Data & Information — Data Lineage**
- **05 Data & Information — Data Classification & Handling**
- **06 AI Security**
- **07 Supply Chain & Sovereignty**
- **08 Human Authority**
- **09 TEVV**
- **11 Operational Authorisation**
- **13 Continuous Assurance**
- **14 Incident & Fail-Safe**
- **15 Change & Reauthorisation**
- **16 Audit & Evidence**
- **21 Legal & Policy**
- **22 Acquisition & Procurement**
- **23 Interoperability & Coalition**
- **24 Architecture & Technical Controls**

---

## 48. Summary

Data access control establishes who or what may access data, for what purpose, with what authority and privilege, and under what monitoring and review conditions.

The central chain is:

**Need → Authority → Eligibility → Purpose → Least Privilege → Access → Monitoring → Review → Revocation**

For consequential defence AI, the governing question is:

> **Can the organisation demonstrate that every material access to AI-relevant data is appropriately authorised, purpose-bound, attributable, least-privileged, monitored and revocable?**

Where the answer is no, the deficiency should be reflected in **security risk, assurance, operational restrictions and—where necessary—revalidation or reauthorisation**.
