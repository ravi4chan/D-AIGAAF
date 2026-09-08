# 43 — Authorisation Portfolio Governance

## 1. Purpose

This document defines how an organisation governs a portfolio of Defence AI capabilities rather than treating each operational authorisation as an isolated decision.

Portfolio governance provides senior leadership with visibility of:

- what AI capabilities are authorised;
- where they are employed;
- what level of autonomy they have;
- their risk and consequence;
- assurance status;
- restrictions;
- dependencies;
- incidents;
- changes;
- upcoming reviews;
- systemic risks across multiple capabilities.

---

## 2. Core Principle

> **Defence AI operational authorisations shall be governed individually and collectively so that the organisation can identify cumulative risk, shared dependencies, systemic weaknesses, capability gaps and concentration of operational authority across its AI portfolio.**

A portfolio view does not replace individual operational authorisation.

---

## 3. Portfolio versus Individual Authorisation

Individual authorisation determines whether a specific capability may be employed within a defined scope.

Portfolio governance considers the wider collection of capabilities and asks:

- Are multiple systems creating common risks?
- Are critical dependencies concentrated?
- Are several capabilities relying on the same model or provider?
- Are similar risks recurring?
- Are assurance resources adequate?
- Are multiple autonomous systems interacting?
- Is operational authority becoming concentrated in a small number of systems or suppliers?

---

## 4. Portfolio Scope

The portfolio may include:

- AI models;
- AI-enabled software;
- AI-enabled platforms;
- decision-support systems;
- autonomous or semi-autonomous capabilities;
- AI-enabled sensors;
- AI-enabled logistics systems;
- command-support capabilities;
- externally provided AI services.

The exact scope should be defined by the adopting organisation.

---

## 5. Portfolio Register

A controlled **Defence AI Authorisation Portfolio Register** should provide a current view of authorised capabilities.

Suggested fields include:

| Field | Description |
|---|---|
| Capability ID | Unique identifier |
| Capability | AI capability |
| Owner | Capability owner |
| Mission | Authorised mission |
| Environment | Authorised environment |
| Autonomy | Authorised autonomy |
| Human Authority | Responsible authority |
| Risk | Current risk classification |
| Assurance | Assurance status |
| Authorisation | Current authority |
| Conditions | Major restrictions |
| Dependencies | Critical dependencies |
| Provider | Relevant provider |
| Status | Current state |
| Review | Next review |
| Incident | Significant recent issue |
| Change | Material pending change |

---

## 6. Portfolio Risk View

Portfolio governance should identify:

- high-consequence capabilities;
- high-autonomy capabilities;
- capabilities with similar failure modes;
- capabilities sharing dependencies;
- capabilities with significant residual risk;
- capabilities operating in degraded environments;
- capabilities with unresolved assurance concerns.

The portfolio should provide visibility of cumulative exposure.

---

## 7. Concentration Risk

Concentration risk may arise when multiple capabilities depend on the same:

- model;
- supplier;
- software component;
- cloud or compute service;
- data source;
- communications infrastructure;
- navigation service;
- security service;
- technical team.

A common dependency failure may therefore affect several independently authorised capabilities.

---

## 8. Shared Model Risk

Where multiple operational capabilities use the same underlying model or model family, portfolio governance should consider whether:

- a model update affects several systems;
- a discovered vulnerability affects multiple capabilities;
- a performance limitation is systemic;
- a common training-data issue exists;
- assurance evidence is being reused appropriately;
- a provider change affects multiple authorisations.

Individual authorisation should not prevent recognition of common systemic risk.

---

## 9. Shared Dependency Risk

Portfolio governance should identify critical shared dependencies and assess:

- dependency criticality;
- failure consequence;
- substitutability;
- recovery arrangements;
- concentration;
- supplier dependency;
- change control.

Where one dependency can affect multiple consequential capabilities, enhanced resilience may be required.

---

## 10. Cross-Capability Risk

The organisation should consider whether the interaction of multiple capabilities creates:

- cumulative risk;
- conflicting recommendations;
- shared failure modes;
- cascading failures;
- autonomy interactions;
- information integrity problems;
- common security exposure;
- loss of human situational awareness.

Individually acceptable risks may become material when capabilities interact.

---

## 11. Portfolio Autonomy Distribution

The portfolio should provide visibility of autonomy levels.

The D-AIGAAF working model is:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

The organisation should understand how much operational authority is concentrated at higher autonomy levels.

This is a D-AIGAAF working construct and should be mapped to applicable national, defence, legal, doctrinal and international terminology.

---

## 12. High-Consequence Portfolio

A separate portfolio view should identify capabilities with potential to materially affect:

- human life;
- physical safety;
- critical infrastructure;
- significant property;
- mission continuity;
- sensitive information.

Higher-consequence capabilities may require:

- stronger independent review;
- more frequent monitoring;
- enhanced assurance;
- tighter authorisation conditions;
- stronger contingency arrangements.

---

## 13. Portfolio Assurance View

Portfolio governance should assess:

- assurance status;
- evidence currency;
- unresolved findings;
- repeated incidents;
- revalidation requirements;
- reauthorisation requirements;
- testing capacity;
- independent evaluation capacity.

This can reveal systemic assurance gaps that are not obvious when systems are viewed individually.

---

## 14. Portfolio Security View

The organisation should identify common security exposure across capabilities.

This may include:

- shared software;
- common suppliers;
- shared infrastructure;
- common data sources;
- common model providers;
- shared interfaces;
- common credentials or identity services.

A security issue affecting one capability should be assessed for potential portfolio-wide impact.

---

## 15. Portfolio Configuration View

Portfolio governance should identify:

- current versions;
- pending updates;
- common model components;
- shared software;
- configuration drift;
- unsupported configurations.

Where a material change affects several capabilities, coordinated assessment may be required.

---

## 16. Portfolio Environment View

The organisation should understand where capabilities are authorised to operate.

This may identify:

- concentration of AI capability in particular environments;
- common environmental assumptions;
- shared degraded-operation requirements;
- common communications dependencies;
- common sensor dependencies.

This supports resilience planning.

---

## 17. Portfolio Human Authority View

Portfolio governance should identify:

- responsible authorising authorities;
- operational authorities;
- delegated authorities;
- OAIA coverage;
- technical authorities;
- assurance authorities.

The organisation should avoid situations where a small number of individuals hold excessive or poorly supported decision responsibility for many high-consequence AI capabilities.

---

## 18. Portfolio Incident View

Incidents should be assessed both individually and collectively.

A single incident may reveal:

- capability-specific weakness;
- common model weakness;
- common dependency weakness;
- systemic governance weakness;
- inadequate testing;
- inadequate human-control arrangements.

Portfolio governance should therefore determine whether lessons from one capability apply to others.

---

## 19. Portfolio Change Management

Material changes affecting multiple capabilities should be coordinated.

Examples include:

- common model updates;
- shared software updates;
- supplier changes;
- common data changes;
- infrastructure changes;
- security changes.

Portfolio-level impact assessment should determine whether multiple authorisations require:

- additional assurance;
- revalidation;
- reauthorisation;
- restriction;
- suspension.

---

## 20. Portfolio Suspension

Where a common systemic issue affects multiple capabilities, portfolio governance should consider whether:

- only one capability should be restricted;
- related capabilities require review;
- all affected capabilities require temporary restriction;
- a shared dependency should be isolated;
- portfolio-wide assurance is required.

Suspension should remain proportionate to the evidence and consequence.

---

## 21. Portfolio Resilience

Portfolio governance should assess resilience against:

- common-mode failure;
- supplier failure;
- model failure;
- infrastructure failure;
- communications disruption;
- security compromise;
- data integrity failure;
- personnel shortages.

Resilience should not depend solely on every individual capability functioning independently.

---

## 22. Portfolio Governance Review

Senior governance should periodically review:

- authorisation status;
- high-consequence systems;
- autonomy distribution;
- risk distribution;
- common dependencies;
- incidents;
- security concerns;
- evidence gaps;
- upcoming renewals;
- material changes;
- assurance capacity.

The review should identify systemic issues requiring organisational action.

---

## 23. Portfolio Decision Rights

Portfolio governance may determine:

- prioritisation of assurance resources;
- common governance requirements;
- systemic risk treatment;
- dependency resilience;
- review priorities;
- common controls;
- portfolio-wide restrictions where justified.

It should not silently replace the designated authority for an individual operational authorisation unless the organisation's governance structure explicitly grants that decision right.

---

## 24. Portfolio Metrics

Possible portfolio metrics include:

- number of authorised capabilities;
- number of restricted capabilities;
- number of suspended capabilities;
- autonomy distribution;
- high-consequence capability count;
- overdue reviews;
- unresolved assurance findings;
- significant incidents;
- repeated failure modes;
- common dependencies;
- supplier concentration;
- capabilities requiring revalidation;
- capabilities requiring reauthorisation.

Metrics should support decision-making rather than create incentives to suppress incidents or findings.

---

## 25. Portfolio Risk Aggregation

Risk aggregation should consider:

- common causes;
- common dependencies;
- correlated failure;
- shared environments;
- shared human authorities;
- shared data;
- shared infrastructure.

Simple addition of individual risk scores may not adequately represent portfolio risk.

---

## 26. Portfolio Knowledge Management

The organisation should maintain cross-capability knowledge concerning:

- incidents;
- near misses;
- common failure modes;
- assurance findings;
- successful controls;
- emerging threats;
- operational lessons;
- model limitations.

Lessons should be assessed for applicability across the portfolio.

---

## 27. Portfolio Governance and Individual Authority

Portfolio governance should preserve the distinction between:

**Portfolio Oversight**

and

**Operational Authority**

Portfolio-level decisions may establish common controls or restrictions, but individual operational authority should remain clearly attributable.

A portfolio dashboard should inform authority, not create authority.

---

## 28. Portfolio Review Triggers

An extraordinary portfolio review may be triggered by:

- systemic AI failure;
- major security incident;
- critical supplier compromise;
- common model vulnerability;
- significant new threat;
- major legal or policy change;
- widespread performance degradation;
- common dependency failure;
- repeated similar incidents.

---

## 29. Portfolio Records

The portfolio should maintain:

1. Defence AI Authorisation Portfolio Register;
2. Shared Dependency Register;
3. Common Model/Component Register;
4. Portfolio Risk Register;
5. Portfolio Assurance Status;
6. Significant Incident Register;
7. Material Change Register;
8. Review and Reauthorisation Schedule.

These records should remain linked to individual capability records.

---

## 30. Governance Questions

Senior leadership should be able to answer:

1. How many Defence AI capabilities are currently authorised?
2. Which have the highest consequence or autonomy?
3. Where is operational AI authority concentrated?
4. Which capabilities share critical dependencies?
5. Which capabilities share models or components?
6. Are there systemic assurance gaps?
7. Are incidents revealing common failure modes?
8. Which authorisations require upcoming review?
9. Could one failure affect multiple capabilities?
10. Is the overall portfolio resilient enough for its operational role?

---

## 31. Golden Thread

Portfolio governance should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Portfolio Review → Change/Incident → Revalidation/Reauthorisation**

This ensures that portfolio-level oversight remains connected to individual operational authority and lifecycle evidence.

---

## 32. Core Rule

> **Defence AI operational authorisations shall be governed both individually and as a portfolio. Portfolio governance shall identify cumulative and common-mode risks, shared models and dependencies, concentration of autonomy and authority, systemic assurance weaknesses, incidents and resilience concerns. Portfolio oversight shall inform and, where explicitly authorised, constrain individual operational authority, but shall not create ambiguous responsibility or allow a capability to acquire authority merely through inclusion in an approved portfolio.**
