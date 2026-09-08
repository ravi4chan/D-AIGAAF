# 42 — Authorisation Lifecycle Integration

## 1. Purpose

This document defines how Operational Authorisation integrates with the wider D-AIGAAF governance lifecycle.

Operational authorisation is not an isolated approval activity. It is the formal governance point at which assurance, risk, mission need, human authority, operational environment, security, configuration and other lifecycle evidence are brought together to determine whether a Defence AI capability may be employed.

---

## 2. Core Principle

> **Operational authorisation shall integrate evidence and decisions from across the Defence AI lifecycle and shall remain connected to the capability's subsequent employment, monitoring, change, incident, revalidation and reauthorisation activities.**

Authorisation should therefore be treated as a lifecycle function rather than a one-time event.

---

## 3. Lifecycle Integration Model

D-AIGAAF uses the following lifecycle:

**Strategic Need → Mission Need → Requirements & Use Case → Risk & Autonomy → Acquisition/Development → Design & Integration → Configuration Baseline → TEVV → Operational Environment Assessment → Assurance → Operational Authorisation → Deployment → Operational Employment → Continuous Monitoring & Assurance → Change/Incident/Emerging Risk → Revalidation → Reauthorisation → Retirement & Decommissioning**

Operational Authorisation sits between **Assurance** and **Deployment**, while remaining connected to all subsequent lifecycle activities.

---

## 4. Authorisation Inputs

Operational authorisation should draw from:

- mission definition;
- use-case definition;
- operational context;
- mission constraints;
- risk assessment;
- autonomy assessment;
- human-control assessment;
- lifecycle records;
- data assurance;
- AI security;
- supply-chain assurance;
- TEVV;
- operational environment assessment;
- fail-safe arrangements;
- operational readiness;
- legal and policy requirements;
- residual-risk acceptance;
- operational lessons.

The authorising authority should not be required to reconstruct this information from disconnected sources.

---

## 5. Authorisation as a Lifecycle Gate

Operational authorisation acts as a governance gate between assurance and operational use.

The basic transition is:

**Assurance Established → Authority Considered → Authorisation Granted → Readiness Confirmed → Deployment → Employment**

A capability should not bypass authorisation merely because it has successfully completed technical testing.

---

## 6. Upstream Traceability

Every material authorisation decision should be traceable backwards to:

**Mission Need → Requirements → Risk → Controls → Testing → Evidence → Assurance**

This allows the organisation to determine why the capability exists, what risks were identified, what controls were established and what evidence supports operational use.

---

## 7. Downstream Traceability

Authorisation should also remain traceable forward through:

**Authority → Conditions → Deployment → Employment → Monitoring → Incident/Change → Revalidation/Reauthorisation**

This ensures that the organisation can determine whether actual operational use remains consistent with the original authorisation basis.

---

## 8. Lifecycle State Relationship

D-AIGAAF distinguishes major lifecycle and operational states.

A capability may be:

- Under Development;
- Under Assurance;
- Assured;
- Authorised;
- Ready;
- Deployed;
- In Employment;
- Restricted;
- Suspended;
- Under Revalidation;
- Under Reauthorisation;
- Retired;
- Decommissioned.

These states should not be conflated.

For example:

**Assured ≠ Authorised**

**Authorised ≠ Ready**

**Ready ≠ Deployed**

**Deployed ≠ Currently Permitted for Every Use**

---

## 9. Requirements-to-Authority Traceability

Operational authorisation should verify that the capability being authorised remains consistent with the requirements for which it was developed or acquired.

Material divergence between:

- original requirements;
- actual capability;
- operational use;
- authorised mission;

should trigger appropriate review.

---

## 10. Risk-to-Authority Traceability

The authorisation decision should demonstrate that identified risks have been:

- assessed;
- treated;
- accepted where appropriate;
- assigned to responsible owners;
- connected to operational conditions.

A change in risk may therefore affect the validity of the authorisation.

---

## 11. Assurance-to-Authority Traceability

Assurance evidence should identify:

- what was tested;
- under which conditions;
- with which configuration;
- what was demonstrated;
- what remained uncertain;
- what limitations apply.

The authorisation should rely only on evidence relevant to the authority being granted.

---

## 12. Configuration-to-Authority Traceability

Operational authority should be connected to the configuration on which assurance was established.

Where material, this includes:

- model;
- model state;
- software;
- hardware;
- interfaces;
- safety controls;
- security controls;
- data;
- dependencies.

A material configuration change may invalidate part or all of the authorisation basis.

---

## 13. Environment-to-Authority Traceability

The authorisation should specify the environment within which the evidence applies.

This includes, where relevant:

- physical environment;
- sensor environment;
- communications;
- navigation;
- electromagnetic conditions;
- degraded conditions;
- adversarial conditions;
- human operating conditions.

Environmental expansion should therefore be treated as a potential change to authority.

---

## 14. Autonomy-to-Authority Traceability

The authorised autonomy level should be directly linked to:

- risk;
- human control;
- TEVV;
- operational conditions;
- system configuration;
- authorisation decision.

An increase in autonomy should not be treated as an ordinary configuration change where it materially changes operational consequence or human-control requirements.

---

## 15. Human Authority Integration

Operational authorisation should identify:

- authorising authority;
- operational authority;
- operator;
- supervisor;
- risk owner;
- technical authority;
- assurance authority;
- security authority;
- Operational AI Advisor (OAIA).

Decision rights should remain clear throughout the lifecycle.

---

## 16. Data Lifecycle Integration

Authorisation should consider whether the data supporting the AI capability remains appropriate.

Relevant lifecycle events include:

- new data sources;
- data quality changes;
- distribution drift;
- data poisoning;
- provenance changes;
- information-sharing changes;
- material data updates.

Material data changes may require additional assurance or revalidation.

---

## 17. Security Lifecycle Integration

Authorisation should remain connected to the AI security lifecycle.

Material events include:

- new threats;
- vulnerabilities;
- compromise;
- unauthorised modification;
- adversarial behaviour;
- dependency compromise;
- security-control changes.

A material security event may require restriction or suspension before reauthorisation.

---

## 18. Supply Chain Integration

Authorisation should consider changes to:

- suppliers;
- model providers;
- software components;
- hardware;
- external services;
- critical dependencies;
- update mechanisms.

The capability should not silently inherit authority following a material supply-chain change.

---

## 19. TEVV Integration

TEVV should provide evidence supporting the proposed operational authority.

Authorisation should consider whether:

- testing represents the intended mission;
- environmental conditions are represented;
- autonomy has been evaluated;
- human control has been evaluated;
- security has been evaluated;
- mission effectiveness has been demonstrated.

New evidence should be incorporated when it materially changes the assurance position.

---

## 20. Operational Readiness Integration

Authorisation and readiness are distinct.

**Authorisation:** Permission to employ within defined boundaries.

**Readiness:** Confirmation that the capability is currently prepared to enter employment under those boundaries.

A capability may remain authorised while temporarily not ready.

Readiness failure should not automatically imply permanent revocation of authority.

---

## 21. Deployment Integration

Deployment is a controlled lifecycle transition.

Before deployment, the organisation should verify:

- authorisation;
- readiness;
- configuration;
- environment;
- human authority;
- autonomy;
- security;
- dependencies;
- required safeguards.

Deployment should not expand authority beyond the authorisation record.

---

## 22. Operational Employment Integration

During employment, the capability remains subject to:

- authorisation boundaries;
- conditions;
- human authority;
- monitoring;
- incident management;
- operational state management;
- autonomy controls;
- security controls.

Actual employment should generate evidence for continuous assurance.

---

## 23. Continuous Assurance Integration

Operational monitoring should continuously evaluate whether the authorisation basis remains valid.

Monitoring should include:

- performance;
- effectiveness;
- AI behaviour;
- uncertainty;
- autonomy;
- human control;
- environment;
- security;
- data;
- dependencies;
- incidents.

The resulting feedback should inform governance decisions.

---

## 24. Change Integration

Material changes should flow through:

**Change Identification → Impact Assessment → Assurance → Revalidation/Reauthorisation**

Changes may affect:

- model;
- software;
- hardware;
- data;
- environment;
- mission;
- autonomy;
- human authority;
- security;
- dependencies.

No material change should silently inherit existing authority.

---

## 25. Incident Integration

Operational incidents should feed back into the authorisation lifecycle.

An incident may require:

- immediate protective action;
- restriction;
- suspension;
- investigation;
- additional assurance;
- change control;
- revalidation;
- reauthorisation.

Incident closure should not automatically restore authority.

---

## 26. Revalidation Integration

Revalidation determines whether existing assurance remains applicable after change, incident or emerging evidence.

Possible outcomes include:

- existing assurance remains valid;
- assurance remains valid with conditions;
- additional assurance required;
- reauthorisation required;
- authority restricted;
- authority suspended.

---

## 27. Reauthorisation Integration

Reauthorisation should occur where the basis for authority has materially changed.

Triggers may include:

- new mission;
- new environment;
- increased autonomy;
- material configuration change;
- material security change;
- significant data change;
- material dependency change;
- significant incident;
- changed legal or policy requirements.

Reauthorisation should reassess the complete operational authority rather than merely updating an administrative record.

---

## 28. Retirement and Decommissioning Integration

When a capability is retired:

- operational authority should be formally ended;
- active authorisations should be closed or withdrawn;
- records should be preserved;
- dependencies should be addressed;
- access should be controlled;
- remaining operational instances should be identified;
- transition to decommissioning should be documented.

Retirement should prevent unintended continuation of operational authority.

---

## 29. Lifecycle Records

The following records should remain connected where applicable:

1. **Defence AI Capability Register (DAICR)**
2. **Defence AI Assurance Record (DAAR)**
3. **Operational Authorisation Record**
4. **Operational Record**
5. Risk Records
6. TEVV Evidence
7. Configuration Records
8. Incident Records
9. Change Records
10. Revalidation/Reauthorisation Records

Together these provide lifecycle traceability.

---

## 30. Lifecycle Integration Failure

A governance failure may occur where:

- assurance is disconnected from authorisation;
- authorisation is disconnected from configuration;
- deployment occurs without current readiness;
- employment exceeds authorised scope;
- incidents do not affect assurance;
- changes bypass revalidation;
- operational lessons do not reach governance;
- retirement leaves active authority unresolved.

Such failures should be treated as governance and assurance concerns.

---

## 31. Lifecycle Integration Review

Periodic governance review should determine whether:

- lifecycle records remain connected;
- authority reflects current capability;
- evidence remains current;
- configuration remains controlled;
- operational experience is feeding assurance;
- changes trigger appropriate governance;
- retirement and decommissioning are controlled.

---

## 32. Golden Thread

Lifecycle integration preserves the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Revalidation/Reauthorisation**

The Golden Thread should remain traceable throughout the entire lifecycle.

---

## 33. Governance Questions

The organisation should be able to answer:

1. Where does operational authorisation sit within the AI lifecycle?
2. What evidence feeds the authorisation decision?
3. How is authorisation connected to configuration?
4. How is authorisation connected to operational environment?
5. How is autonomy connected to authority?
6. How does operational experience affect continued authority?
7. What happens after an incident?
8. What happens after a material change?
9. How does revalidation connect to reauthorisation?
10. How is authority formally ended at retirement?

---

## 34. Core Rule

> **Operational authorisation shall remain integrated with the complete Defence AI lifecycle. Evidence and decisions from mission definition, risk, development or acquisition, data, security, supply chain, TEVV, operational environment, human authority, readiness and configuration shall inform authorisation, while operational employment, monitoring, incidents, changes and emerging evidence shall continuously inform revalidation and reauthorisation. No lifecycle transition shall silently create, expand or preserve operational authority beyond its defined and currently supported basis.**
