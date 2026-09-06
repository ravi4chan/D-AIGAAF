# 36 — Authorisation Operational Authority Evidence and Decision Package

## 1. Purpose

This document defines the evidence and decision package required to support a Defence AI operational authorisation decision.

The purpose is to ensure that an authorising authority receives a coherent, decision-ready view of:

- the capability being considered;
- the intended mission and use case;
- the operational environment;
- the proposed autonomy;
- human authority and control;
- identified risks;
- assurance evidence;
- limitations and uncertainty;
- conditions and boundaries;
- residual risk;
- monitoring arrangements;
- dependencies;
- fail-safe and contingency arrangements;
- the recommendation and basis for the decision.

The decision package should allow an appropriately authorised human decision-maker to determine whether operational authority should be granted, conditioned, restricted, deferred or refused.

---

## 2. Core Principle

> **An operational authorisation decision shall be based on a coherent and traceable decision package that connects mission need, risk, assurance evidence, operational boundaries, human authority and residual risk to the authority being requested.**

A collection of disconnected test reports or technical documents should not by itself be treated as an adequate authorisation basis.

---

## 3. Decision Package versus Authorisation Record

The **Decision Package** and the **Operational Authorisation Record** serve different purposes.

### Decision Package

The decision package supports the decision.

It should answer:

- What is being proposed?
- Why is it needed?
- What can it do?
- Where and how will it be used?
- What could go wrong?
- What evidence demonstrates acceptable performance and control?
- What remains uncertain?
- What authority is being requested?
- What conditions and restrictions are proposed?
- Who accepts the residual risk?

### Operational Authorisation Record

The authorisation record records the resulting authority.

It should state:

- what was authorised;
- under what conditions;
- by whom;
- for what period;
- with what restrictions;
- based on what decision.

The decision package therefore provides the **basis for the decision**, while the authorisation record provides the **authoritative statement of the resulting permission**.

---

## 4. Authorisation Decision Object

The decision package should describe the complete authorisation object:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Where applicable, this should also include:

**Configuration × Data × Dependencies × Conditions × Validity**

A decision should not be made on the AI model or technical system in isolation when operational authority depends on the wider system and context.

---

## 5. Minimum Decision Package

A decision package should contain, as applicable:

1. Executive Decision Summary
2. Capability Description
3. Mission and Use Case
4. Operational Context
5. Proposed Operational Scope
6. Risk and Autonomy Assessment
7. Human Authority and Control Assessment
8. Operational Environment Assessment
9. TEVV and Assurance Evidence
10. Security Assessment
11. Data and Information Assessment
12. Supply Chain and Dependency Assessment
13. Configuration Baseline
14. Fail-Safe and Contingency Arrangements
15. Operational Boundaries and Prohibited Uses
16. Conditions and Restrictions
17. Residual Risk and Risk Acceptance
18. Monitoring and Continuous Assurance Plan
19. Incidents, Lessons and Previous Operational Experience
20. Legal and Policy Assessment
21. Evidence Gaps and Uncertainty
22. Proposed Authorisation Decision
23. Decision Authority and Approval
24. Review, Renewal and Reauthorisation Triggers

Not every capability requires identical evidence. The package should be proportionate to consequence, autonomy, mission criticality and operational risk.

---

## 6. Executive Decision Summary

The first section should allow the authorising authority to understand the decision without reviewing the complete technical evidence set.

It should state:

- capability;
- intended mission;
- proposed operating environment;
- proposed autonomy;
- human authority;
- principal risks;
- assurance conclusion;
- significant limitations;
- residual risk;
- proposed conditions;
- recommended decision;
- decision authority.

The summary should not conceal material uncertainty or unresolved evidence gaps.

---

## 7. Capability Description

The package should clearly identify:

- system name and identifier;
- AI components;
- model(s);
- software and hardware;
- relevant interfaces;
- major dependencies;
- system owner;
- technical authority;
- operational owner;
- configuration baseline.

The description should be sufficient for the authorising authority to understand what is being authorised without requiring detailed software-level knowledge.

---

## 8. Mission and Use Case

The package should define:

- mission need;
- operational objective;
- authorised use case;
- intended users;
- operational phase;
- expected AI contribution;
- consequential decisions or actions;
- success criteria;
- limitations;
- prohibited uses.

The proposed use should remain consistent with the approved mission and use-case definition.

---

## 9. Proposed Operational Scope

The package should explicitly define:

- geographic scope;
- environmental scope;
- user scope;
- functional scope;
- temporal scope;
- autonomy scope;
- configuration scope;
- data scope;
- dependency scope;
- consequence scope.

Scope should be expressed in operationally understandable terms.

---

## 10. Risk and Autonomy Assessment

The package should summarise:

- mission criticality;
- consequence;
- identified risks;
- autonomy level;
- autonomy transitions;
- loss-of-control scenarios;
- residual risk;
- risk treatment;
- risk owner;
- proposed risk acceptance authority.

Higher consequence and higher autonomy should normally require stronger evidence and more restrictive authority.

---

## 11. Human Authority and Control

The package should identify:

- responsible human authority;
- operator;
- supervisor;
- command authority;
- decision rights;
- intervention authority;
- override mechanisms;
- escalation routes;
- required competence;
- human workload considerations;
- conditions requiring human control.

It should demonstrate that meaningful human control is achievable within the proposed operating context.

---

## 12. Operational Environment Assessment

The package should describe the environment in which the capability is proposed to operate.

Relevant factors may include:

- terrain;
- weather;
- illumination;
- sensors;
- communications;
- navigation;
- electromagnetic conditions;
- computing availability;
- information conditions;
- adversarial conditions;
- human factors;
- critical dependencies.

The package should identify whether the proposed environment is:

- Demonstrated;
- Conditionally Demonstrated;
- Partially Demonstrated;
- Untested;
- Outside the established envelope.

---

## 13. TEVV and Assurance Evidence

The package should summarise evidence across applicable dimensions:

1. Technical Performance
2. Reliability and Robustness
3. Adversarial Resilience
4. Operational Environment
5. Human-AI Interaction
6. Security and Integrity
7. Autonomy and Control
8. Mission Effectiveness

For each material claim, the package should identify:

- evidence source;
- test or evaluation method;
- relevant conditions;
- result;
- limitations;
- evidence status;
- applicability to the proposed mission.

Evidence should demonstrate the capability under relevant operational conditions rather than merely under ideal laboratory conditions.

---

## 14. Security Assessment

The package should identify material AI security risks, including where relevant:

- adversarial manipulation;
- data poisoning;
- model compromise;
- unauthorised modification;
- interface compromise;
- dependency compromise;
- supply-chain risks;
- credential or access risks;
- loss of integrity;
- unexpected system behaviour following compromise.

Security limitations that could affect operational authority should be explicitly presented.

---

## 15. Data and Information Assessment

The package should identify:

- important data sources;
- provenance;
- lineage;
- quality;
- representativeness;
- integrity;
- uncertainty;
- known limitations;
- drift considerations;
- data dependencies;
- information-sharing constraints.

Material data limitations should be connected to their potential operational consequences.

---

## 16. Supply Chain and Dependency Assessment

The package should identify material dependencies capable of affecting:

- model behaviour;
- software;
- hardware;
- data;
- communications;
- navigation;
- compute;
- security;
- availability;
- continuity.

Where practical, the package should identify:

- provider;
- dependency;
- criticality;
- trust boundary;
- change mechanism;
- update mechanism;
- failure consequence;
- fallback arrangement.

---

## 17. Configuration Baseline

The decision package should identify the configuration for which assurance has been established.

This may include:

- model version;
- model state;
- software version;
- hardware;
- firmware;
- interfaces;
- safety controls;
- security controls;
- relevant settings;
- data version where material.

The authorisation should not silently extend to materially different configurations.

---

## 18. Fail-Safe and Contingency Arrangements

The package should demonstrate:

- safe-state behaviour;
- intervention mechanisms;
- autonomy reduction;
- human-control transition;
- communications-loss behaviour;
- degraded-operation behaviour;
- contingency procedures;
- suspension mechanisms;
- recovery arrangements.

Emergency procedures should preserve human authority and should not create unrestricted AI authority.

---

## 19. Operational Boundaries and Prohibited Uses

The package should explicitly identify:

- authorised functions;
- prohibited functions;
- operating envelope;
- autonomy limits;
- human-control requirements;
- geographic boundaries;
- environmental boundaries;
- configuration limits;
- dependency limits;
- consequence limits;
- suspension conditions.

Technical capability outside these boundaries should not be interpreted as operational permission.

---

## 20. Conditions and Restrictions

The package should propose conditions necessary for safe and controlled employment.

These may include:

- restricted mission;
- restricted environment;
- reduced autonomy;
- increased supervision;
- specific configuration;
- additional monitoring;
- competence requirements;
- dependency requirements;
- time limits;
- reporting requirements;
- confirmation before consequential action.

Each material condition should have an identifiable rationale.

---

## 21. Residual Risk and Risk Acceptance

The package should clearly state:

- significant identified risks;
- controls;
- remaining uncertainty;
- residual risk;
- risk owner;
- proposed risk acceptance authority;
- compensating controls;
- conditions of acceptance.

Risk acceptance should not be implied by silence or by technical approval.

---

## 22. Monitoring and Continuous Assurance

The package should define how continued validity will be assessed.

Monitoring should cover, where applicable:

- technical performance;
- AI behaviour;
- mission effectiveness;
- uncertainty;
- human-AI interaction;
- autonomy;
- environment;
- security;
- data;
- dependencies;
- incidents;
- assurance evidence currency.

The package should identify thresholds requiring:

**Continue → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

---

## 23. Incidents, Lessons and Operational Experience

Previous incidents, failures, near misses, lessons and operational observations relevant to the proposed authority should be disclosed.

The package should identify:

- incident;
- relevance;
- corrective action;
- residual concern;
- evidence of resolution;
- impact on authorisation.

Material adverse experience should not be omitted merely because the capability remains technically functional.

---

## 24. Legal and Policy Assessment

Where applicable, the package should identify:

- applicable law;
- policy requirements;
- organisational directives;
- relevant restrictions;
- unresolved legal or policy questions;
- required approvals.

The authorisation decision should not be presented as overriding applicable legal or policy requirements.

---

## 25. Evidence Gaps and Uncertainty

The package should explicitly identify:

- missing evidence;
- contradictory evidence;
- untested conditions;
- uncertain system behaviour;
- uncertain environmental assumptions;
- uncertain data characteristics;
- uncertain dependencies;
- limitations of testing;
- areas requiring further assurance.

A decision package should distinguish clearly between:

**Demonstrated**

**Conditionally Demonstrated**

**Partially Demonstrated**

**Untested**

**Contradicted**

Uncertainty should be visible to the decision-maker.

---

## 26. Authorisation Recommendation

The package should provide a clear recommendation.

Possible outcomes include:

1. **Operational Authorisation Recommended**
2. **Conditional Authorisation Recommended**
3. **Restricted Authorisation Recommended**
4. **Additional Assurance Required**
5. **Revalidation Required**
6. **Reauthorisation Required**
7. **Authorisation Not Recommended**
8. **Suspension or Withdrawal Recommended**

The recommendation should state the principal reasoning and material conditions.

---

## 27. Decision Authority

The package should identify:

- proposed authorising authority;
- delegated authority, if applicable;
- decision rights;
- risk acceptance authority;
- technical authority;
- assurance authority;
- security authority;
- operational authority;
- OAIA involvement;
- required concurrence or consultation.

The decision package should make clear which individual or authority is accountable for the operational authorisation decision.

---

## 28. Decision Record

The final decision should record:

- decision;
- date;
- authority;
- scope;
- conditions;
- restrictions;
- residual risk acceptance;
- dissenting or unresolved views where material;
- evidence relied upon;
- validity period;
- review date;
- suspension/revocation triggers.

The decision should be traceable to the submitted package and its evidence.

---

## 29. Evidence Precedence and Conflicting Evidence

Where evidence conflicts, the decision process should consider:

- evidence quality;
- independence;
- relevance;
- recency;
- operational representativeness;
- test conditions;
- statistical or methodological limitations;
- configuration applicability.

Conflicting evidence should not simply be averaged away.

Material unresolved contradiction should normally result in:

- additional assurance;
- restricted authority;
- revalidation;
- reauthorisation; or
- refusal of authority.

---

## 30. Decision Package Review

The decision package should undergo an appropriate review before submission.

Review should verify:

- completeness;
- consistency;
- evidence traceability;
- configuration consistency;
- risk consistency;
- autonomy consistency;
- human-authority consistency;
- scope consistency;
- conditions;
- unresolved issues.

Independent review should be used where proportionate to consequence and risk.

---

## 31. Package Currency

The decision package should remain current throughout the authorisation lifecycle.

It should be reconsidered following:

- material system change;
- model update;
- mission change;
- environment change;
- autonomy change;
- human-control change;
- security incident;
- material data change;
- dependency change;
- significant operational incident;
- new assurance evidence;
- changed legal or policy requirements.

A stale decision package should not be treated as evidence that the original authorisation basis remains valid.

---

## 32. Decision Package and the Golden Thread

The decision package should preserve traceability through the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Revalidation/Reauthorisation**

This allows the authorising authority to understand not only the proposed decision, but why the decision is justified.

---

## 33. Decision Readiness Questions

Before granting operational authority, the decision-maker should be able to answer:

1. What exactly am I being asked to authorise?
2. For which mission and use case?
3. In which environment?
4. At what autonomy level?
5. Under whose human authority?
6. What configuration has been assured?
7. What evidence demonstrates acceptable performance and control?
8. What remains unknown or uncertain?
9. What are the most consequential risks?
10. Who owns and accepts the residual risk?
11. What conditions and boundaries apply?
12. What happens if those conditions fail?
13. How will continued validity be monitored?
14. What changes would invalidate this decision?
15. What is the appropriate response to an incident or loss of control?
16. When must the capability be revalidated or reauthorised?

If these questions cannot be answered adequately, the authorisation decision should not proceed without appropriate additional assurance or governance action.

---

## 34. Core Rule

> **Operational authority shall be granted only on the basis of a coherent, proportionate and traceable decision package that demonstrates why the specific Defence AI capability is sufficiently understood, assured and controlled for the proposed mission, environment, autonomy and human-authority arrangements. The package shall make material risks, limitations, uncertainty, evidence gaps, conditions and residual risk visible to the accountable human decision-maker.**
