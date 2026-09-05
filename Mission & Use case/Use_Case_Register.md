# Use Case Register

## 1. Purpose

The Use Case Register provides a controlled inventory of AI use cases governed under D-AIGAAF.

It establishes visibility of:

- what AI is being used for;
- where it is used;
- who is responsible;
- what level of autonomy is involved;
- what risks apply;
- what assurance exists;
- what operational authority has been granted.

The register supports governance, risk management, assurance, authorisation, audit and continuous monitoring.

---

## 2. Core Principle

No consequential AI use case should exist outside the governance system.

The register should provide a traceable relationship:

**Mission → Use Case → Risk → Assurance → Authorisation → Employment**

Registration does not itself constitute approval or operational authorisation.

---

## 3. Scope

The register should cover AI use cases across the capability lifecycle, including:

- proposed use cases;
- use cases under development;
- use cases undergoing TEVV;
- authorised use cases;
- restricted use cases;
- suspended use cases;
- retired use cases.

The level of information recorded should be proportionate to mission consequence and autonomy.

---

## 4. Use Case Identification

Each use case should have a unique identifier.

A suitable identifier should remain stable throughout the lifecycle even if:

- the system changes;
- the model is updated;
- the responsible organisation changes;
- the deployment location changes.

Changes should be recorded through versioning rather than creating unnecessary duplicate identities.

---

## 5. Minimum Register Fields

Each use case record should identify, where applicable:

| Field | Description |
|---|---|
| Use Case ID | Unique identifier |
| Use Case Name | Concise operational description |
| Mission | Supported mission |
| Capability | AI-enabled capability |
| AI Role | Function performed by AI |
| Human Role | Human responsibility and authority |
| Autonomy | Authorised or proposed autonomy level |
| Mission Criticality | Mission consequence classification |
| Consequence | Potential consequence of failure |
| Operational Environment | Intended operating conditions |
| Risk Profile | Current risk assessment |
| Assurance Status | Current assurance position |
| Authorisation Status | Current operational authority |
| Owner | Accountable capability/use-case owner |
| System Manager | Responsible technical authority |
| Operational Authority | Relevant operational decision authority |
| OAIA | Assigned Operational AI Advisor, where applicable |
| Baseline | Approved configuration/baseline |
| Dependencies | Critical dependencies |
| Limitations | Known limitations |
| Fail-Safe | Applicable fail-safe arrangements |
| Review Date | Next scheduled review |
| Change Status | Current change/revalidation position |

---

## 6. Use Case Status

A use case should have a controlled lifecycle status.

A suggested status model is:

**Proposed → Defined → Under Development → Under TEVV → Under Assurance → Conditionally Authorised → Operationally Authorised → Restricted → Suspended → Retired**

Status should reflect the actual governance position.

A system being technically available does not mean that its use case is operationally authorised.

---

## 7. Relationship With the AI Capability Register

The Use Case Register should be linked to the Defence AI Capability Register (DAICR).

One AI capability may support:

- one use case;
- multiple use cases;
- different missions;
- different environments;
- different autonomy levels.

Therefore:

**Capability ≠ Use Case**

A capability may be authorised for one use case while remaining unauthorised for another.

---

## 8. Mission Linkage

Every consequential use case should link to a defined mission need.

The register should identify:

- mission objective;
- supported operational activity;
- mission criticality;
- mission owner.

A use case without a legitimate mission purpose should not progress to operational authorisation.

---

## 9. Risk Linkage

Each consequential use case should have a current risk profile.

The register should link to relevant assessments covering:

- consequence;
- autonomy;
- mission criticality;
- environment;
- human control;
- information integrity;
- security;
- uncertainty;
- availability;
- supply chain;
- dependencies;
- foreseeable misuse.

Risk status should be updated when material conditions change.

---

## 10. Assurance Linkage

The register should identify the current assurance position.

This may include:

- assurance status;
- applicable assurance claims;
- evidence repository;
- outstanding evidence gaps;
- limitations;
- unresolved findings;
- last assurance review.

Assurance status should not be interpreted as operational authority.

---

## 11. Authorisation Linkage

Where operational use is permitted, the register should link to the applicable Operational Authorisation record.

The authorisation should define, as applicable:

- mission;
- environment;
- autonomy;
- operational envelope;
- human authority;
- conditions;
- limitations;
- validity period;
- suspension triggers;
- revocation triggers;
- reauthorisation requirements.

The register should make the current authorisation state immediately visible.

---

## 12. Human Authority

The register should identify the human authorities associated with the use case.

This may include:

- operational authority;
- decision authority;
- risk acceptance authority;
- technical authority;
- assurance authority;
- OAIA.

Roles should not be inferred merely from organisational ownership.

---

## 13. Operational AI Advisor

Where the use case requires an Operational AI Advisor, the register should record:

- assigned advisor;
- role and authority;
- relevant competency;
- scope of responsibility;
- escalation route.

The OAIA provides an operational bridge between AI technical expertise and command decision-making.

The OAIA advises; authorised human authority decides.

---

## 14. Autonomy

The register should record the proposed and authorised autonomy level separately where necessary.

For example:

| Attribute | Example |
|---|---|
| Proposed Autonomy | A3 |
| Tested Autonomy | A3 |
| Authorised Autonomy | A2 |
| Reason for Difference | Evidence limitation |

This prevents tested capability from being mistaken for authorised capability.

---

## 15. Operational Environment

The register should identify the environments in which the use case is authorised or intended to operate.

Relevant dimensions may include:

- geographic conditions;
- terrain;
- weather;
- sensor conditions;
- communications;
- computing availability;
- data availability;
- adversarial conditions;
- human workload.

Authorisation in one environment should not automatically imply authorisation in another.

---

## 16. Critical Dependencies

The register should identify dependencies that could materially affect the use case.

Examples include:

- communications;
- cloud or remote infrastructure;
- positioning;
- external data;
- sensors;
- third-party models;
- software libraries;
- hardware;
- authentication infrastructure;
- power;
- human operators.

Critical dependency failure should have a defined operational response.

---

## 17. Configuration and Baseline

The register should identify the configuration baseline associated with the use case.

This may include:

- model version;
- software version;
- hardware configuration;
- data version;
- system configuration;
- critical dependencies.

The baseline establishes what was actually assured and authorised.

---

## 18. Change Management

Changes to a registered use case should be assessed for significance.

Potential triggers include:

- model updates;
- software changes;
- data changes;
- new dependencies;
- changes in autonomy;
- new operating environments;
- changes in mission;
- changes in human control;
- security changes;
- changes in system behaviour.

A change should not preserve operational authority automatically.

---

## 19. Incident and Fail-Safe Status

The register should provide visibility of significant incidents.

Relevant information may include:

- incident identifier;
- date;
- affected use case;
- nature of incident;
- operational impact;
- current status;
- containment;
- investigation status;
- revalidation requirement.

A significant incident may change the assurance and authorisation position.

---

## 20. Review Triggers

A use case should be reviewed when:

- scheduled review is due;
- mission changes;
- risk changes materially;
- autonomy changes;
- operating environment changes;
- significant incident occurs;
- security threat changes;
- critical dependency changes;
- model or system behaviour changes;
- policy or legal requirements change;
- evidence becomes obsolete.

---

## 21. Register Governance

The Use Case Register should have:

- a designated owner;
- defined data responsibilities;
- controlled access;
- version history;
- audit trail;
- review process;
- change control.

The register itself is a governance record.

---

## 22. Access and Classification

The register should contain only the information necessary for governance and operational control.

Sensitive operational details should be protected according to applicable information-security and classification requirements.

D-AIGAAF does not require the public repository to contain classified operational information.

The public framework should remain generic and unclassified.

---

## 23. Minimum Register Views

Different stakeholders may require different views of the register.

### Governance View

Focuses on:

- ownership;
- status;
- risk;
- assurance;
- authorisation;
- review dates.

### Operational View

Focuses on:

- authorised mission;
- operating environment;
- autonomy;
- human authority;
- limitations;
- fail-safe conditions.

### Assurance View

Focuses on:

- evidence;
- assurance claims;
- test status;
- evidence gaps;
- limitations;
- revalidation requirements.

### Security View

Focuses on:

- threats;
- vulnerabilities;
- dependencies;
- security status;
- incidents;
- resilience.

---

## 24. Register Quality

A useful register should be:

- accurate;
- current;
- traceable;
- complete for its intended purpose;
- independently reviewable;
- linked to authoritative records.

A stale register can create governance risk by giving decision-makers an incorrect view of what is authorised.

---

## 25. Example Register Structure

| ID | Mission | Use Case | Autonomy | Risk | Assurance | Authorisation | Owner | Review |
|---|---|---|---|---|---|---|---|---|
| UC-001 | Defined mission | Defined use | A2 | Current | Assured | Authorised | Assigned | Date |
| UC-002 | Defined mission | Defined use | A3 | Current | Conditional | Restricted | Assigned | Date |
| UC-003 | Defined mission | Defined use | A4 | Current | Under TEVV | Not authorised | Assigned | Date |

The values are illustrative only.

---

## 26. Register and Golden Thread

The Use Case Register provides a central navigation point across the Golden Thread.

For each consequential use case, it should be possible to trace:

**Mission → Use Case → Constraints → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authorisation → Employment → Monitoring → Change**

Missing links should be treated as governance or assurance gaps.

---

## 27. Minimum Use Case Register Requirements

A D-AIGAAF implementation should:

1. Maintain a controlled inventory of consequential AI use cases.
2. Assign a unique identifier to each use case.
3. Link each use case to a mission need.
4. Record the AI and human roles.
5. Record proposed, tested and authorised autonomy where relevant.
6. Record mission criticality and consequence.
7. Identify authorised operational environments.
8. Link to the current risk profile.
9. Link to assurance evidence and status.
10. Link to operational authorisation where applicable.
11. Identify accountable owners and authorities.
12. Record critical dependencies.
13. Identify the configuration baseline.
14. Record known limitations.
15. Record significant incidents and change status.
16. Maintain review dates and triggers.
17. Preserve an auditable history of changes.
18. Protect sensitive information appropriately.

---

## 28. Relationship With D-AIGAAF

This module connects directly with:

- `00 Framework/Reference Model`
- `00 Framework/Golden Thread`
- `01 Strategy & Governance`
- `02 Mission & Use Case/Mission_Definition.md`
- `02 Mission & Use Case/Use_Case_Definition.md`
- `02 Mission & Use Case/Operational_Context.md`
- `02 Mission & Use Case/Mission_Constraints.md`
- `02 Mission & Use Case/Use_Case_Risk_Profile.md`
- `02 Mission & Use Case/Mission_Success_Criteria.md`
- `03 Risk & Autonomy`
- `04 AI Lifecycle`
- `09 TEVV`
- `11 Operational Authorisation`
- `13 Continuous Assurance`
- `14 Incident & Fail-Safe`
- `15 Change & Reauthorisation`
- `16 Audit & Evidence`

The register acts as an index connecting governance records across the framework.

---

## 29. Summary

The Use Case Register provides controlled visibility of where, why and how AI is being used.

Its central purpose is not administration.

It is to prevent consequential AI use from becoming invisible, ambiguous or detached from its:

- mission;
- risk;
- assurance;
- human authority;
- operational authorisation;
- configuration;
- limitations;
- continuous monitoring.

The central principle is:

> **If a consequential AI use case cannot be clearly identified, traced and assigned to an accountable authority, it should not be treated as operationally governed.**
