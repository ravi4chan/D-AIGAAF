# 25 Operational Authorisation Continuity and Resilience

## 1. Purpose

Defence AI capabilities may be required to operate through disruption, degraded infrastructure, loss of communications, personnel changes, system failures, environmental changes and other conditions that challenge normal governance arrangements.

This document defines how operational authorisation should remain controlled during such disruptions.

The objective is to ensure that:

- operational authority remains identifiable;
- critical governance functions remain available;
- loss of supporting infrastructure does not create implied AI authority;
- continuity arrangements preserve human control;
- degraded operation remains within defined boundaries;
- authority can be transferred or restored in a controlled manner; and
- operational status and evidence can be reconciled after disruption.

---

## 2. Core Principle

**Continuity of operations shall not mean continuity of unrestricted AI authority.**

When governance infrastructure, communications, personnel or supporting systems are degraded, the organisation should preserve the minimum controls necessary to maintain authorised and accountable AI employment.

Where those controls cannot be maintained, the capability should move to an appropriately restricted, reduced-autonomy, human-controlled, safe or suspended state.

---

## 3. Continuity Object

Continuity planning should address:

**Authority × Human Control × Configuration × Evidence × Communication × Environment × Dependencies**

The continuity plan should identify which functions must remain available for the capability to continue operating safely and within its authorisation.

---

## 4. Critical Authorisation Functions

Continuity arrangements should consider the availability of:

- authorisation status;
- operational authority;
- human decision rights;
- autonomy restrictions;
- configuration baseline;
- mission boundaries;
- environmental boundaries;
- fail-safe mechanisms;
- monitoring;
- incident reporting;
- security controls;
- data integrity controls;
- critical dependencies;
- operational records; and
- escalation mechanisms.

Not every supporting service needs to remain continuously available, but critical governance controls should have defined fallback arrangements.

---

## 5. Continuity States

A working continuity model may use:

| State | Meaning |
|---|---|
| **Normal** | Full governance and supporting services are available. |
| **Degraded** | Some supporting functions are unavailable but essential controls remain available. |
| **Disconnected** | Normal communication or central services are unavailable. |
| **Contingency** | Predefined alternative governance arrangements are being used. |
| **Restricted** | AI employment is reduced to preserve control and assurance. |
| **Safe State** | The capability is placed in a controlled condition pending recovery. |
| **Suspended** | Operational authority is inactive. |

The applicable state should be recorded where practicable.

---

## 6. Minimum Viable Governance

For each operational capability, the organisation should identify a minimum set of governance functions that must remain available.

These may include:

- identifiable human authority;
- current authorisation boundaries;
- current autonomy restrictions;
- ability to intervene or override;
- fail-safe capability;
- minimum required situational information;
- configuration identification;
- essential monitoring;
- incident communication; and
- ability to terminate or restrict employment.

If minimum viable governance cannot be maintained, continued employment should be reassessed.

---

## 7. Communications Loss

Loss of communications should not automatically create additional AI authority.

The capability should have predefined behaviour for:

- loss of command link;
- loss of supervisory link;
- loss of external data;
- intermittent communication;
- delayed communication;
- loss of status synchronisation.

Possible responses include:

**Continue Within Boundary → Reduce Autonomy → Human Control → Contingency → Safe State → Suspend**

The appropriate response should be defined by the authorised use case and risk profile.

---

## 8. Loss of Central Governance Services

Where a central authorisation or monitoring service becomes unavailable, an approved local representation should be available where necessary.

The local representation should include, as applicable:

- authorisation identifier;
- authorised mission;
- authorised environment;
- autonomy level;
- human authority;
- configuration baseline;
- restrictions;
- validity;
- emergency procedures;
- last verified status; and
- reconciliation requirements.

A local copy should not be capable of silently extending authority beyond the approved record.

---

## 9. Personnel Continuity

Continuity planning should identify critical roles whose absence could affect authorised employment.

These may include:

- Authorising Authority;
- Command/Operational Authority;
- Risk Owner;
- Operational AI Advisor;
- System Manager;
- Technical Authority;
- Assurance/TEVV Authority;
- Security Authority; and
- qualified operators.

Succession or delegation arrangements should be established in advance where appropriate.

---

## 10. Delegation During Disruption

Emergency or contingency delegation should remain:

- explicit;
- bounded;
- competent;
- recorded where practicable;
- consistent with the delegator's authority; and
- subject to later review.

A disruption should not automatically transfer unrestricted authority to whoever is technically able to operate the system.

---

## 11. Human Control Continuity

Continuity arrangements should preserve meaningful human control appropriate to the authorised autonomy level.

The organisation should determine:

- who can supervise;
- who can intervene;
- who can override;
- who can reduce autonomy;
- who can place the system in a safe state;
- who can suspend employment; and
- who can restore employment.

Loss of the required human-control function should trigger the predefined response.

---

## 12. Configuration Continuity

Continuity arrangements should prevent configuration uncertainty.

Where practicable, personnel should be able to determine:

- approved system version;
- approved model version;
- approved configuration;
- approved data dependencies;
- applicable restrictions;
- emergency configuration;
- rollback configuration.

An unknown or unverifiable configuration should not automatically inherit the authority of a known authorised configuration.

---

## 13. Data and Information Continuity

Where AI depends on data or information services, continuity planning should identify:

- critical data sources;
- minimum data requirements;
- approved fallback sources;
- data-integrity checks;
- provenance requirements;
- stale-data risks;
- loss-of-data behaviour;
- degraded-data behaviour; and
- recovery and reconciliation procedures.

The system should not silently treat missing, stale or degraded information as equivalent to reliable information.

---

## 14. Dependency Continuity

Critical technical and organisational dependencies should be identified.

These may include:

- communications;
- navigation;
- sensors;
- compute;
- power;
- cloud or external services;
- identity and access services;
- data services;
- security services;
- software dependencies;
- specialist personnel; and
- supplier support.

For each critical dependency, the organisation should determine:

**Dependency → Failure Mode → Operational Impact → Control → Fallback → Recovery**

---

## 15. Environmental Continuity

Continuity arrangements should account for environmental changes that may occur during disruption.

These may include:

- weather;
- terrain;
- illumination;
- electromagnetic conditions;
- sensor availability;
- navigation conditions;
- communication conditions;
- adversarial activity; and
- human operational conditions.

A continuity plan should not assume that the environment remains unchanged simply because the mission remains unchanged.

---

## 16. Security Continuity

Security controls should remain effective during degraded or disconnected operation.

The organisation should define how to respond to:

- suspected compromise;
- loss of integrity;
- unauthorised access;
- malicious inputs;
- corrupted data;
- compromised dependencies;
- security-monitoring loss; and
- inability to verify system integrity.

Where security assurance becomes insufficient, operational authority may need to be restricted or suspended.

---

## 17. Safe-State and Fail-Safe Continuity

The capability should have a defined safe-state strategy appropriate to its function.

The safe-state concept should address:

- trigger conditions;
- responsible authority;
- automatic protective behaviour where authorised;
- human intervention;
- consequences of transition;
- recovery requirements;
- evidence preservation; and
- conditions for resuming employment.

The fail-safe mechanism should be treated as a governance control, not merely a technical feature.

---

## 18. Recovery

Recovery should restore controlled operational conditions rather than simply restore technical availability.

Recovery should verify, as applicable:

1. system integrity;
2. configuration;
3. data integrity;
4. dependencies;
5. environment;
6. human authority;
7. autonomy;
8. security;
9. monitoring;
10. assurance evidence;
11. authorisation status; and
12. readiness.

Technical recovery does not automatically mean operational readiness.

---

## 19. Reconstitution

Where disruption materially affects the assurance basis, the capability should undergo appropriate reconstitution before normal employment resumes.

Reconstitution may require:

- system checks;
- configuration verification;
- data validation;
- security assessment;
- environmental assessment;
- human-control checks;
- targeted TEVV;
- incident assessment;
- revalidation; or
- reauthorisation.

The depth should be proportionate to the disruption and resulting risk.

---

## 20. Restoration States

A capability may return through controlled states:

**Safe State → Restricted → Conditionally Ready → Ready → Operational Employment**

Skipping states should require a defined basis and appropriate authority.

Restoration should not be based solely on the absence of an obvious failure.

---

## 21. Post-Disruption Review

Material disruptions should be reviewed to determine:

- what failed;
- what remained available;
- whether authorised boundaries were maintained;
- whether human control was preserved;
- whether AI behaviour changed;
- whether assumptions remained valid;
- whether controls were effective;
- whether evidence remains valid;
- whether authorisation remains appropriate; and
- whether changes are required.

Lessons should feed back into continuous assurance.

---

## 22. Continuity and Dynamic Authority

During disruption, operational authority should continue to follow the defined authority model.

The sequence may be:

**Detect Change → Assess Impact → Maintain or Restrict Authority → Preserve Human Control → Recover → Verify → Restore**

Disruption should never be interpreted as an automatic expansion of autonomy.

---

## 23. Continuity of Records

Operational records should remain available or recoverable following disruption.

Where records cannot be synchronised in real time, controlled local recording should be used where practicable.

The record should preserve:

- decisions;
- AI contributions;
- authority;
- actions;
- interventions;
- status changes;
- incidents;
- configuration;
- conditions; and
- recovery actions.

Local records should be reconciled with authoritative systems when connectivity or normal services are restored.

---

## 24. Continuity Exercises

Continuity arrangements should be tested periodically.

Exercises should consider scenarios such as:

- communication loss;
- central-service failure;
- personnel unavailability;
- degraded sensors;
- data-service loss;
- security incident;
- dependency failure;
- environmental change;
- loss of human supervision; and
- simultaneous failures.

Exercises should test governance arrangements, not only technical recovery.

---

## 25. Continuity Evidence

Evidence should demonstrate that continuity arrangements have been:

- defined;
- approved;
- tested;
- understood by responsible personnel;
- technically supported;
- exercised;
- reviewed; and
- improved following lessons learned.

Evidence should be linked to the applicable authorisation and assurance records.

---

## 26. Continuity Responsibilities

The organisation should define responsibilities for:

- continuity planning;
- authority succession;
- technical recovery;
- human-control recovery;
- security response;
- assurance reassessment;
- operational readiness;
- authorisation restoration; and
- post-disruption review.

Responsibility should remain identifiable throughout the disruption.

---

## 27. Relationship to Authorisation

Continuity planning does not replace operational authorisation.

It provides controlled mechanisms for maintaining, restricting, suspending and restoring authorised employment when normal conditions are disrupted.

The relationship is:

**Authorisation → Continuity Conditions → Degradation Response → Recovery → Readiness → Continued or Restored Authority**

---

## 28. Golden Thread

Continuity remains connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Disruption/Incident → Recovery → Revalidation/Reauthorisation**

---

## 29. Governance Questions

Responsible authorities should be able to determine:

1. What governance functions are essential for continuity?
2. Who holds authority if the normal authority is unavailable?
3. What happens when communications are lost?
4. What happens when central governance services are unavailable?
5. What autonomy level applies during degradation?
6. Can meaningful human control be maintained?
7. What is the minimum viable governance state?
8. What dependencies are critical?
9. What configuration is authorised?
10. What happens when configuration cannot be verified?
11. What data and information remain trustworthy?
12. What triggers a safe state?
13. What triggers suspension?
14. What must be verified before recovery?
15. What evidence is required before normal employment resumes?
16. When is revalidation required?
17. When is reauthorisation required?
18. How are records preserved and reconciled?
19. Who decides that the capability is ready to resume?
20. Have continuity arrangements been exercised?

---

## 30. Core Rule

> **A Defence AI capability shall have defined continuity and resilience arrangements proportionate to its mission, consequence, autonomy and operational dependency. Disruption shall not create implied AI authority. Where normal governance functions are degraded, the capability shall operate only within predefined continuity conditions or move to an appropriately restricted, human-controlled, safe or suspended state. Restoration of technical capability shall not by itself restore operational authority; controlled verification of the assurance, human-control, configuration, environmental and authorisation basis shall precede restoration of normal employment.**
