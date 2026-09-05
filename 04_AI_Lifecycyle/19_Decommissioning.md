# Decommissioning

## Summary

Decommissioning governs the controlled technical, physical and administrative closure of a retired AI capability.

It ensures that an AI capability cannot continue to operate unintentionally after retirement and that its models, software, infrastructure, interfaces, credentials, data dependencies and supporting services are appropriately removed, disabled, archived or transferred.

The core principle is:

**A retired AI capability is not fully closed until its operational authority, technical execution paths and supporting dependencies have been deliberately addressed.**

The core chain is:

**Retirement → Decommissioning Planning → Dependency Mapping → Access Closure → Technical Disablement → Data / Model Disposition → Verification → Record Closure**

---

## 1. Purpose

Decommissioning provides controls to:

- permanently or appropriately disable an AI capability;
- prevent unintended continued operation;
- remove obsolete access and dependencies;
- manage models, data and infrastructure;
- preserve required records;
- close supplier relationships;
- manage residual risk;
- demonstrate that closure has actually occurred.

---

## 2. Retirement vs Decommissioning

These concepts are related but distinct.

### Retirement

Ends authorised operational use.

### Decommissioning

Removes, disables, transfers or permanently closes the technical and supporting elements of the capability.

The lifecycle relationship is:

**Operational Authority Ends → Capability Retired → Technical Closure → Decommissioned**

A retired capability may remain temporarily available for controlled non-operational purposes before final decommissioning.

---

## 3. Decommissioning Triggers

Decommissioning may follow:

- formal retirement;
- replacement by another capability;
- permanent loss of mission need;
- technology obsolescence;
- unacceptable risk;
- security concerns;
- supplier termination;
- infrastructure closure;
- inability to maintain assurance.

---

## 4. Decommissioning Planning

A decommissioning plan should identify:

- capability;
- final configuration;
- systems;
- infrastructure;
- models;
- software;
- hardware;
- data;
- interfaces;
- credentials;
- suppliers;
- users;
- records;
- dependencies;
- retention requirements;
- disposal requirements;
- responsible authorities.

---

## 5. Complete Asset Inventory

Before closure, identify all relevant components.

This may include:

- models;
- model weights;
- software;
- firmware;
- hardware;
- sensors;
- edge devices;
- servers;
- storage;
- APIs;
- databases;
- logs;
- monitoring systems;
- interfaces;
- supporting services;
- development environments;
- test environments.

Unknown components create decommissioning risk.

---

## 6. Dependency Mapping

Identify systems and services that:

- depend on the AI capability;
- provide data to it;
- receive outputs from it;
- authenticate it;
- monitor it;
- update it;
- maintain it.

Each dependency should have a disposition:

- remove;
- disable;
- transfer;
- replace;
- retain with explicit purpose.

---

## 7. Operational Closure

Confirm that:

- operational authority has ended;
- users have been informed;
- operational workflows no longer rely on the capability;
- active missions have transitioned;
- fallback procedures are complete.

Decommissioning should not unexpectedly disrupt critical operational functions.

---

## 8. Access Closure

Review and close:

- user accounts;
- administrator accounts;
- service accounts;
- API credentials;
- certificates;
- tokens;
- privileged access;
- supplier access;
- remote-management access.

Access should be revoked, transferred or retained only where justified.

---

## 9. Interface Closure

Identify and address:

- network interfaces;
- APIs;
- data feeds;
- system integrations;
- automated triggers;
- message queues;
- control interfaces.

An interface that remains active can create an unintended path to continued operation.

---

## 10. Model Disposition

Models may be:

- destroyed;
- securely archived;
- transferred;
- retained for research;
- retained for audit or investigation.

The disposition should comply with applicable security, legal, records-management and policy requirements.

---

## 11. Model Integrity During Retention

Where models are retained:

- integrity should be protected;
- access should be controlled;
- purpose should be documented;
- operational use should be prohibited unless separately authorised;
- provenance and version should remain identifiable.

Archived does not mean operationally authorised.

---

## 12. Data Disposition

Data may require:

- retention;
- archival;
- migration;
- transfer;
- deletion;
- secure destruction.

Decisions should account for:

- legal requirements;
- security classification where applicable;
- records-management rules;
- contractual requirements;
- investigative requirements;
- future assurance needs.

---

## 13. Evidence Preservation

Before disposal, preserve required:

- assurance evidence;
- TEVV results;
- configuration records;
- authorisations;
- incident records;
- monitoring history;
- change history;
- retirement records.

Evidence preservation should support historical reconstruction.

---

## 14. Infrastructure Closure

Infrastructure should be:

- removed;
- repurposed;
- transferred;
- securely sanitised;
- isolated.

This may include:

- compute;
- storage;
- networking;
- edge devices;
- supporting services.

---

## 15. Hardware Disposition

For physical equipment, establish whether it will be:

- reused;
- transferred;
- stored;
- sanitised;
- physically destroyed.

Disposition should account for data-bearing components and embedded software.

---

## 16. Software Closure

Remove or disable:

- applications;
- services;
- scheduled processes;
- containers;
- packages;
- deployment pipelines;
- automated update mechanisms.

Unused software components should not remain capable of restarting the capability unintentionally.

---

## 17. Configuration Closure

The final operational configuration should be preserved as a historical record where required.

Decommissioning should establish:

**Final Approved Configuration → Final Deployed Configuration → Closure State**

---

## 18. Automated Processes

Check for and disable:

- scheduled inference;
- automated retraining;
- model refresh;
- data ingestion;
- automated deployment;
- monitoring triggers;
- automated actions.

Automation can cause unintended operation after apparent retirement.

---

## 19. Monitoring Closure

Monitoring systems should confirm closure where appropriate.

They may verify:

- no continued inference;
- no active connections;
- no unauthorised access;
- no automated execution;
- no unexpected data flows.

Monitoring should remain active long enough to provide reasonable confidence in closure.

---

## 20. Security Closure

Security closure should address:

- credentials;
- keys;
- certificates;
- privileged accounts;
- remote access;
- supplier access;
- update channels;
- external connections.

The objective is to eliminate unnecessary attack paths created by the retired capability.

---

## 21. Safety Closure

Where AI was connected to physical or consequential functions, confirm:

- automated actions are disabled;
- control has transferred appropriately;
- safety interlocks remain effective;
- fallback systems are functioning;
- residual automated behaviour is not possible.

---

## 22. Supplier Closure

For externally provided capabilities, address:

- contracts;
- subscriptions;
- support;
- licences;
- hosted environments;
- supplier access;
- data return;
- data deletion;
- intellectual property;
- retained components.

Supplier closure should be verified rather than assumed.

---

## 23. Supply-Chain Closure

Critical dependencies should be identified and either:

- removed;
- transferred;
- retained under explicit governance.

This includes components capable of modifying:

- models;
- software;
- data;
- configuration;
- infrastructure.

---

## 24. Replacement and Migration

Where a replacement capability exists, migration should verify:

- required data transfer;
- interface replacement;
- user transition;
- mission continuity;
- assurance of the replacement;
- removal of obsolete dependencies.

The replacement must not inherit the retired capability's technical access automatically.

---

## 25. Legacy System Risk

Legacy systems may continue to reference or attempt to access the decommissioned capability.

Testing should establish that:

- obsolete integrations are removed;
- fallback behaviour is understood;
- failed connections do not create unsafe conditions;
- no hidden dependency remains.

---

## 26. Decommissioning Verification

Decommissioning must be verified.

Verification may include:

- access tests;
- interface checks;
- service discovery;
- configuration inspection;
- dependency checks;
- security validation;
- operational confirmation.

The objective is to demonstrate:

**Intended Closure = Actual Closure**

---

## 27. Independent Verification

For high-consequence capabilities, independent verification should be considered.

The verifier should not rely solely on statements from the team responsible for decommissioning.

Independence should increase with:

- consequence;
- system complexity;
- number of dependencies;
- security sensitivity;
- operational criticality.

---

## 28. Residual Access

After closure, review for:

- dormant accounts;
- retained credentials;
- forgotten APIs;
- legacy interfaces;
- supplier access;
- copies of models;
- development instances;
- test environments.

Residual access should have a documented owner and purpose or be removed.

---

## 29. Retained Copies

Models, software or datasets may exist in:

- backups;
- archives;
- development systems;
- test systems;
- disaster-recovery systems;
- supplier environments.

The disposition of retained copies should be known and governed.

---

## 30. Backup and Disaster Recovery

Decommissioning should address:

- backups;
- snapshots;
- disaster-recovery copies;
- replicated data;
- archived configurations.

Where immediate deletion is not possible, retention controls and expiry requirements should be defined.

---

## 31. Legal and Records Requirements

Decommissioning must account for applicable requirements relating to:

- records retention;
- investigations;
- legal proceedings;
- contractual obligations;
- data protection;
- security;
- intellectual property.

Technical destruction should not occur before mandatory records are preserved.

---

## 32. Incident and Investigation Hold

If the capability is subject to an active:

- incident investigation;
- security investigation;
- safety review;
- audit;
- legal proceeding;

relevant assets and evidence should be protected from destruction until authorised for disposal.

---

## 33. Environmental and Physical Disposal

Where hardware is physically disposed of, applicable organisational and environmental requirements should be followed.

Data-bearing components should receive appropriate sanitisation or destruction.

---

## 34. Decommissioning Status

A working status model is:

### Planned

Decommissioning approved and planned.

### In Progress

Closure activities underway.

### Technically Disabled

Operational execution paths have been disabled.

### Pending Verification

Closure has occurred but final verification remains.

### Decommissioned

Closure has been verified.

### Archived

Relevant artefacts remain retained under controlled non-operational governance.

---

## 35. Decommissioning Record

A Decommissioning Record should include:

| Field | Description |
|---|---|
| Decommissioning ID | Unique identifier |
| Capability ID | AI capability |
| Retirement ID | Related retirement decision |
| Final Configuration | Final operational baseline |
| Assets | Components in scope |
| Dependencies | Connected systems/services |
| Access | Accounts/credentials closed |
| Interfaces | Connections removed |
| Model | Disposition |
| Data | Retention/disposal |
| Infrastructure | Disposition |
| Supplier | Closure status |
| Evidence | Records preserved |
| Verification | Closure verification |
| Residual Risk | Remaining risk |
| Exceptions | Outstanding matters |
| Authority | Responsible authority |
| Date | Completion date |
| Status | Decommissioning status |

---

## 36. Exceptions

Any component that cannot be immediately removed should have:

- documented reason;
- owner;
- security controls;
- purpose;
- retention period;
- review date.

Exceptions should not become permanent unmanaged legacy components.

---

## 37. Emergency Decommissioning

Emergency decommissioning may be required where continued operation presents unacceptable risk.

Immediate protective measures may include:

- disabling execution;
- disconnecting interfaces;
- revoking access;
- isolating infrastructure.

Formal documentation and verification should follow as soon as practicable.

---

## 38. Decommissioning and Accountability

Records should preserve the lifecycle history:

**Capability → Configuration → Authorisation → Employment → Monitoring → Incident / Change → Retirement → Decommissioning**

This enables future investigation and lessons learned.

---

## 39. Lessons Learned

Decommissioning findings should feed:

- lifecycle governance;
- acquisition requirements;
- architecture;
- security controls;
- configuration management;
- assurance;
- future procurement;
- workforce training.

---

## 40. Closure Criteria

Decommissioning should not be declared complete until, as applicable:

- operational authority has ended;
- active use has ceased;
- critical dependencies are closed or transferred;
- access has been addressed;
- interfaces are closed;
- automated execution is disabled;
- data/model disposition is complete;
- required records are preserved;
- residual risks have owners;
- closure has been independently verified where required.

---

## 41. Common Failure Modes

### 41.1 Declaring Decommissioning After Shutdown Alone

Technical shutdown does not prove complete closure.

### 41.2 Leaving Credentials Active

Dormant credentials can preserve access.

### 41.3 Ignoring Backups

Archived copies may continue to contain models, data or credentials.

### 41.4 Ignoring Dependencies

Other systems may still depend on the capability.

### 41.5 Destroying Evidence

Historical evidence may be required after operational retirement.

### 41.6 Assuming Supplier Closure

External services may remain active unless explicitly terminated and verified.

### 41.7 Leaving Automated Processes Running

Scheduled jobs or update mechanisms can restart components unexpectedly.

---

## 42. Core Rules

1. **Decommissioning must establish that operational execution paths have been closed.**
2. **Retirement and decommissioning must remain distinct decisions.**
3. **All significant assets and dependencies must be identified before closure.**
4. **Access, credentials and interfaces must be addressed explicitly.**
5. **Automated processes must be identified and disabled or transferred.**
6. **Models and data must have documented disposition.**
7. **Required assurance and incident evidence must be preserved.**
8. **Backups and retained copies must be included in disposition planning.**
9. **Safety must be preserved during technical closure.**
10. **Supplier access and hosted services must be explicitly closed or transferred.**
11. **High-consequence decommissioning should receive independent verification where practical.**
12. **Residual risks and exceptions must have owners.**
13. **Closure must be demonstrated rather than assumed.**
14. **Replacement capabilities must be independently governed.**
15. **Decommissioning records must preserve sufficient lifecycle traceability.**

---

## 43. Golden Thread

Decommissioning closes the lifecycle:

**Mission Need → Risk → Requirements → Capability → Assurance → Authority → Employment → Monitoring → Change / Incident → Revalidation → Reauthorisation → Retirement → Decommissioning**

---

## 44. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **04 AI Lifecycle** — defines the final lifecycle stage.
- **05 Data & Information** — governs data disposition.
- **06 AI Security** — governs security closure.
- **07 Supply Chain & Sovereignty** — governs supplier and dependency closure.
- **08 Human Authority** — governs responsibility during closure.
- **11 Operational Authorisation** — confirms operational authority has ended.
- **12 Operational Employment** — confirms operational use has ceased.
- **13 Continuous Assurance** — supports closure monitoring.
- **14 Incident & Fail-Safe** — addresses emergency closure and incidents.
- **16 Audit & Evidence** — preserves historical evidence.
- **18 Retirement** — provides the preceding retirement decision.
- **26 Retirement & Decommissioning** — provides the broader governance domain for end-of-life management.
- **27 Implementation** — supports organisational implementation.

---

## 45. Summary Model

```text
Retirement
    ↓
Decommissioning Plan
    ↓
Asset & Dependency Mapping
    ↓
Operational Closure
    ↓
Access / Credential Closure
    ↓
Interface Closure
    ↓
Model / Data / Infrastructure Disposition
    ↓
Automated Process Closure
    ↓
Security & Safety Verification
    ↓
Independent Verification Where Required
    ↓
Residual Risk Closure / Transfer
    ↓
Decommissioned
    ↓
Records Retained as Required
```

Decommissioning ensures that the end of an AI capability is as controlled, traceable and assurance-driven as its development and operational deployment.
