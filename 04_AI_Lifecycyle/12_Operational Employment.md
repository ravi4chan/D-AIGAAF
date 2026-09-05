# Operational Employment

## Summary

Operational Employment governs how an authorised and deployed defence AI capability is used during actual operations.

It translates operational authorisation into disciplined day-to-day use while preserving mission boundaries, human authority, autonomy constraints, safety, security, accountability and continuous assurance.

The core principle is:

**An AI capability must be employed only for the purpose, mission, environment, configuration, autonomy and authority for which it has been authorised.**

The operational chain is:

**Authorisation → Deployment → Employment → Human Decision → Action → Monitoring → Outcome → Review**

---

## 1. Purpose

Operational Employment establishes controls for:

- using AI within its authorised mission;
- maintaining human authority;
- operating within defined environmental and technical boundaries;
- interpreting AI outputs appropriately;
- managing uncertainty;
- controlling autonomy;
- identifying abnormal behaviour;
- recording consequential decisions and actions;
- escalating incidents and emerging risks;
- maintaining continuous assurance.

---

## 2. Core Principle

**Operational employment is governed use, not unrestricted use.**

Deployment makes a capability available.

Operational authorisation establishes what is permitted.

Operational employment determines how that capability is actually used within those permissions.

---

## 3. Scope

Operational Employment may apply to AI supporting:

- command decision support;
- situational awareness;
- intelligence, surveillance and reconnaissance;
- information analysis;
- logistics;
- maintenance;
- planning;
- resource allocation;
- cyber or information functions;
- targeting support;
- autonomous or semi-autonomous functions where separately authorised.

The framework remains generic and does not prescribe specific operational tactics or classified procedures.

---

## 4. Employment Preconditions

Before operational use, personnel should confirm:

- valid operational authorisation;
- correct system configuration;
- appropriate mission;
- authorised environment;
- required data availability;
- required human authority;
- authorised autonomy level;
- applicable restrictions;
- system health;
- monitoring;
- fail-safe availability.

If a material precondition is absent, use should be restricted, suspended or escalated as appropriate.

---

## 5. Mission Alignment

AI should be used only for an approved mission or use case.

Users should be able to determine:

- what the AI is authorised to support;
- what decisions it may inform;
- what actions it may support;
- what it is prohibited from doing;
- what assumptions apply.

A technically capable system should not be treated as automatically authorised for every task it can perform.

---

## 6. Operational Context

Employment should account for the actual operating context.

Relevant factors may include:

- physical environment;
- weather;
- terrain;
- sensor conditions;
- communications;
- data availability;
- adversarial activity;
- system degradation;
- human workload;
- time pressure.

Material changes in context may alter the validity of previous assurance.

---

## 7. Operating Envelope

Each capability should have an understood operating envelope.

The envelope may define:

- environmental conditions;
- data conditions;
- sensor conditions;
- communications;
- latency;
- compute availability;
- supported missions;
- authorised autonomy;
- human supervision;
- known limitations.

Use outside the envelope should require defined authority or reassessment.

---

## 8. Human Authority

Human authority remains explicit for consequential decisions unless a higher autonomy level has been separately authorised.

Personnel should understand:

- who receives AI outputs;
- who interprets them;
- who makes decisions;
- who authorises actions;
- who can override the system;
- who can suspend operation;
- who can initiate emergency protective action.

AI output should not create ambiguity about accountability.

---

## 9. Human-AI Decision Relationship

The relationship should remain clear:

**AI Output ≠ Human Decision**

AI may:

- observe;
- classify;
- analyse;
- predict;
- recommend;
- prioritise;
- assist.

The authority to act remains governed by the authorised human-AI relationship.

---

## 10. AI Recommendations

Where AI provides recommendations, users should consider:

- confidence or uncertainty;
- supporting information;
- known limitations;
- operating conditions;
- conflicting evidence;
- data quality;
- whether the recommendation is within the intended use case.

Users should not treat confidence scores as a substitute for judgement.

---

## 11. Uncertainty

AI should communicate uncertainty where meaningful.

Operational users should be able to distinguish between:

- high-confidence output;
- uncertain output;
- insufficient information;
- out-of-distribution conditions;
- system error;
- unavailable functionality.

Where the system cannot reliably support a decision, it should be capable of abstaining or escalating where designed to do so.

---

## 12. Preventing Confabulation

For high-consequence applications, systems should minimise the risk of presenting unsupported information as fact.

Where appropriate, the system should:

- identify uncertainty;
- distinguish observation from inference;
- identify missing information;
- avoid fabricated information;
- preserve source traceability;
- allow human challenge.

A plausible answer is not necessarily a reliable answer.

---

## 13. Human Challenge

Users should be able to challenge AI outputs.

Challenge may include:

- requesting supporting information;
- comparing alternative evidence;
- seeking a second assessment;
- rejecting a recommendation;
- escalating to an OAIA or technical authority.

The system should not discourage appropriate human challenge.

---

## 14. Rejecting AI Recommendations

A human decision maker may reject or bypass an AI recommendation where authorised.

For consequential decisions, the framework should support recording:

- AI recommendation;
- relevant evidence;
- human decision;
- reason for rejection or override where required;
- resulting action;
- outcome.

This supports accountability, learning and future assurance.

---

## 15. Autonomy Management

Operational employment must remain within the authorised autonomy level.

Working autonomy construct:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are D-AIGAAF working categories and should be mapped to applicable national, defence, legal and doctrinal terminology before formal adoption.

---

## 16. Autonomy Transitions

Where a system can transition between autonomy levels, transitions should be:

- authorised;
- observable;
- controlled;
- logged;
- reversible where feasible.

Unexpected autonomy escalation should be treated as a significant event.

---

## 17. Autonomous Actions

Where autonomous action is authorised, operational personnel should understand:

- permitted actions;
- prohibited actions;
- operating boundaries;
- supervision;
- intervention;
- termination;
- fail-safe;
- recovery.

Autonomy must not silently expand during employment.

---

## 18. Situational Awareness

AI should support rather than undermine human situational awareness.

Commanders should understand, where applicable:

- what the system is observing;
- what it is not observing;
- what assumptions it is making;
- what uncertainty exists;
- where information is incomplete;
- whether system limitations could materially affect decisions.

AI-generated situational awareness should not be treated as complete situational awareness by default.

---

## 19. Adversarial Conditions

Employment should account for the possibility of:

- manipulated inputs;
- deceptive information;
- adversarial examples;
- spoofed sensors;
- compromised data;
- unexpected environmental conditions;
- malicious or misleading content.

The appropriate response may include restriction, human verification, degraded operation or suspension.

---

## 20. Degraded Conditions

AI may encounter:

- communications loss;
- sensor degradation;
- data gaps;
- reduced compute;
- infrastructure failure;
- environmental change.

The system should behave according to its authorised degraded-mode design.

Loss of connectivity or supporting infrastructure should not automatically result in unauthorised autonomy.

---

## 21. Offline Operation

Where offline operation is authorised, personnel should understand:

- available data;
- model limitations;
- update status;
- local dependencies;
- uncertainty;
- logging limitations;
- recovery procedures.

Offline capability should remain within its authorised role.

---

## 22. Safety During Employment

Operational users should monitor for:

- unexpected behaviour;
- unsafe recommendations;
- uncontrolled actions;
- loss of human control;
- abnormal system states;
- failure of safeguards.

Where required, the system should be restricted or suspended.

---

## 23. AI Against Own Forces or Infrastructure

Where an AI capability can influence consequential actions, assurance and operational controls should address the possibility of unintended effects against:

- own personnel;
- own systems;
- own infrastructure;
- authorised assets;
- friendly or protected entities.

This should be treated as a safety, security and control concern even when no external attacker is involved.

---

## 24. Fail-Safe

The fail-safe mechanism is a last-resort protective control.

Normal escalation should generally follow:

**User / Operator → System Manager → OAIA → Command Authority**

Where delay could create unacceptable harm, pre-authorised emergency procedures should permit immediate protective action.

All emergency use should be recorded and reviewed.

---

## 25. Incident Recognition

Operational personnel should be able to recognise:

- unexpected model behaviour;
- incorrect outputs;
- unexplained confidence;
- unsafe recommendations;
- autonomy anomalies;
- configuration deviations;
- security incidents;
- data integrity problems;
- repeated performance degradation.

Potentially significant incidents should be escalated promptly.

---

## 26. Incident Response

Operational response should consider:

1. protect people and critical assets;
2. prevent further unsafe or unauthorised behaviour;
3. preserve relevant evidence;
4. notify the appropriate authority;
5. determine whether the capability should be restricted or suspended;
6. initiate technical and operational investigation;
7. assess whether revalidation or reauthorisation is required.

---

## 27. Performance Monitoring

Operational performance should be monitored against the approved baseline.

Monitoring may include:

- accuracy;
- reliability;
- availability;
- latency;
- false positives;
- false negatives;
- uncertainty;
- abstention;
- human overrides;
- autonomous actions;
- environmental performance.

---

## 28. Distribution Shift

Performance may change when operational conditions differ from development or testing conditions.

Potential indicators include:

- changing data patterns;
- new sensor characteristics;
- changing environmental conditions;
- unexpected user behaviour;
- adversarial adaptation;
- degraded accuracy.

Material degradation should trigger investigation and potentially restriction or suspension.

---

## 29. Configuration Integrity

Operational users and system managers should ensure that the deployed configuration remains consistent with the authorised baseline.

Unexpected changes to:

- model;
- software;
- data;
- parameters;
- interfaces;
- dependencies;
- security controls

should be assessed under configuration and change management.

---

## 30. Supply Chain Awareness

Operational employment should retain visibility of critical dependencies where practical.

This may include:

- model provider;
- software dependencies;
- hardware;
- update mechanisms;
- externally supplied components;
- critical services.

Unknown or uncontrolled dependencies may create operational risk.

---

## 31. Operational Logging

For consequential AI-supported activities, records should support reconstruction of:

**Who → Which Capability → Which Configuration → What Information → AI Output → Human Decision → Action → Outcome**

The level of logging should be proportionate to consequence, autonomy and legal/policy requirements.

---

## 32. Accountability

Responsibility should not be assigned to the AI system itself.

Accountability should remain associated with the authorised human, organisational and technical authorities responsible for:

- approving use;
- operating the system;
- supervising autonomy;
- accepting risk;
- maintaining the capability;
- authorising consequential actions.

---

## 33. Operational AI Advisor

The **Operational AI Advisor (OAIA)** provides a bridge between operational command and technical AI expertise.

The OAIA may advise on:

- system limitations;
- uncertainty;
- model behaviour;
- operational suitability;
- emerging risks;
- autonomy;
- incidents;
- changes.

The OAIA does not replace the commander, operational authority, system owner or formal assurance authority.

---

## 34. Command Decision Support

For AI supporting command decisions, users should understand:

- the decision being supported;
- information available to the AI;
- information unavailable to the AI;
- assumptions;
- uncertainty;
- alternatives;
- consequences of error.

AI should strengthen command judgement rather than become an opaque substitute for it.

---

## 35. Targeting and Other High-Consequence Functions

Where AI supports functions involving significant risk to human life or property, additional controls should apply.

These may include:

- stronger evidence requirements;
- higher human-authority requirements;
- enhanced monitoring;
- stronger environmental validation;
- explicit autonomy restrictions;
- independent review;
- enhanced logging;
- defined suspension criteria.

The level of assurance should increase with consequence and autonomy.

---

## 36. Operational Restrictions

Restrictions should be clearly communicated.

Examples include:

- mission restrictions;
- geographic or environmental restrictions;
- autonomy restrictions;
- user restrictions;
- data restrictions;
- time restrictions;
- supervision requirements.

Restrictions should be treated as conditions of authorisation, not optional guidance.

---

## 37. Use Beyond Authorisation

If personnel identify a potentially useful application outside the authorised use case, they should not simply repurpose the system operationally.

The proposed use should enter the applicable:

**Use Case → Risk → Requirements → TEVV → Assurance → Authorisation**

process.

---

## 38. Temporary Operational Expansion

Temporary expansion of use may be permitted only where an applicable authority and process explicitly allow it.

The expansion should specify:

- purpose;
- duration;
- operating conditions;
- autonomy;
- human authority;
- additional controls;
- monitoring;
- review.

---

## 39. Operational Suspension

A capability may require suspension when:

- unsafe behaviour is detected;
- authorisation expires;
- configuration integrity is uncertain;
- security is compromised;
- performance materially degrades;
- operating conditions exceed the authorised envelope;
- human control is lost;
- material assumptions become invalid.

Suspension should remain available to the appropriate authority.

---

## 40. Reauthorisation Triggers

Operational employment should trigger review when there is:

- material model change;
- material software change;
- new mission;
- new environment;
- new data source;
- changed autonomy;
- significant incident;
- material performance degradation;
- new threat;
- changed legal or policy requirement.

---

## 41. Operational Learning

Operational experience should feed back into:

- requirements;
- risk assessments;
- TEVV;
- training;
- system design;
- configuration management;
- assurance;
- authorisation.

Operational employment therefore becomes an evidence source for the next assurance cycle.

---

## 42. Operational Review

Periodic review should assess:

- actual mission use;
- performance;
- incidents;
- near misses;
- human overrides;
- autonomy behaviour;
- environmental conditions;
- emerging risks;
- changes;
- user feedback;
- continuing suitability.

---

## 43. Operational Employment Record

An Operational Employment Record should include, where appropriate:

| Field | Description |
|---|---|
| Capability ID | AI capability identifier |
| Authorisation ID | Applicable operational authorisation |
| Mission | Mission/use case |
| Configuration | Configuration used |
| Environment | Operational environment |
| User | Responsible user/operator |
| Human Authority | Decision/action authority |
| Autonomy | Active autonomy level |
| AI Output | Relevant AI recommendation/output |
| Uncertainty | Relevant uncertainty |
| Human Decision | Decision made |
| Action | Resulting action |
| Outcome | Observed outcome |
| Override | Human override, if applicable |
| Incident | Relevant incident |
| Restriction | Applicable restriction |
| Time | Event timestamp |
| Evidence | Supporting records |

---

## 44. Employment Status

A working status model is:

### Authorised

Approved for operational employment.

### Active

Currently employed within approved conditions.

### Restricted

Employment limited by defined conditions.

### Degraded

Operating under an authorised degraded mode.

### Suspended

Operational use temporarily stopped.

### Revoked

Operational authority withdrawn.

### Retired

Capability removed from operational employment.

---

## 45. Employment Exit Criteria

An operational employment period or activity should conclude with:

- relevant records preserved;
- incidents reported;
- material deviations recorded;
- performance assessed where required;
- configuration confirmed;
- lessons captured;
- follow-up actions assigned.

---

## 46. Core Rules

1. **AI must be employed only within its authorised purpose and operating envelope.**
2. **Deployment does not automatically authorise every technically possible use.**
3. **Human authority must remain explicit for consequential decisions unless autonomy is separately authorised.**
4. **AI recommendations must not be treated as inherently correct.**
5. **Meaningful uncertainty must be communicated and considered.**
6. **Users must be able to challenge, reject or override AI outputs where authorised.**
7. **Autonomy must not silently expand during employment.**
8. **Unexpected behaviour must trigger appropriate escalation.**
9. **Loss of communications must not silently change the authorised role of the AI.**
10. **Safety, security and configuration controls remain active throughout employment.**
11. **Consequential decisions and actions should be reconstructable from operational records.**
12. **Material changes in mission, environment, configuration, autonomy or risk may require reauthorisation.**
13. **Operational experience must feed continuous assurance.**
14. **The AI system itself is not the accountable decision authority.**

---

## 47. Golden Thread

Operational Employment maintains the Golden Thread:

**Mission Need → Risk → Requirements → Data → Model → Integration → Configuration → Testing → Evidence → Assurance → Authority → Deployment → Employment → Decision → Action → Outcome → Monitoring → Change/Incident → Revalidation → Reauthorisation**

---

## 48. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **02 Mission & Use Case** — defines authorised mission and use.
- **03 Risk & Autonomy** — defines consequence, risk and autonomy conditions.
- **04 AI Lifecycle** — establishes lifecycle controls.
- **06 AI Security** — protects AI capability and operational integrity.
- **08 Human Authority** — defines human decision and control responsibilities.
- **09 TEVV** — establishes evidence supporting operational use.
- **10 Operational Environment** — defines environmental considerations.
- **11 Operational Authorisation** — establishes operational authority and conditions.
- **11 Operational Deployment** — establishes the deployed capability.
- **13 Continuous Assurance** — monitors continued suitability.
- **14 Incident & Fail-Safe** — governs incidents and protective action.
- **15 Change & Reauthorisation** — governs material changes.
- **16 Audit & Evidence** — preserves accountability records.
- **17 Workforce** — supports competence and training.
- **24 Architecture & Technical Controls** — supports operational technical controls.

---

## 49. Summary Model

```text
Operational Authorisation
        ↓
Operational Deployment
        ↓
Mission / Use Case
        ↓
AI Output / Recommendation
        ↓
Human Interpretation
        ↓
Human Decision / Authorised Autonomy
        ↓
Action
        ↓
Outcome
        ↓
Monitoring
        ↓
Incident / Change / Emerging Risk
        ↓
Revalidation
        ↓
Reauthorisation
```

Operational Employment is where governance becomes operational behaviour. Its purpose is to ensure that an AI capability remains within the boundaries under which it was trusted, while creating the evidence needed to determine whether that trust should continue.
