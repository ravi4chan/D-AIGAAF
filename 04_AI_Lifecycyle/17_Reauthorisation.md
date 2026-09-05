# Reauthorisation

## Summary

Reauthorisation determines whether a defence AI capability that has undergone revalidation, or otherwise experienced a material change in its assurance or operational conditions, should continue to receive operational authority.

Reauthorisation is an **authority decision**, not a technical test and not a substitute for assurance.

The core principle is:

**A capability should operate only under an operational authorisation that remains valid for its current capability, configuration, mission, environment, autonomy and human-authority conditions.**

The core chain is:

**Revalidation / Trigger → Assurance Review → Authorisation Review → Decision → Updated Conditions → Controlled Employment → Continuous Assurance**

---

## 1. Purpose

Reauthorisation provides a controlled mechanism to:

- confirm continued operational authority;
- amend existing authorisation conditions;
- impose restrictions;
- increase or reduce authorised autonomy;
- respond to changed risk;
- respond to changed mission or environment;
- suspend authority where evidence is insufficient;
- formally renew authority after a defined review period.

---

## 2. Core Principle

Operational authority is conditional and time-bound.

A previous authorisation should not be treated as permanent permission to use an AI capability regardless of changes.

The authorisation relationship is:

**AI Capability × Configuration × Mission × Environment × Autonomy × Human Authority**

A material change to any of these may require review of existing authority.

---

## 3. Reauthorisation vs Revalidation

These functions must remain distinct.

### Revalidation

Determines whether evidence continues to support the capability's requirements, performance, safety, security and operational suitability.

### Reauthorisation

Determines whether the responsible authority permits the capability to operate under defined conditions.

Revalidation produces evidence.

Reauthorisation produces authority.

Neither function should be treated as automatically replacing the other.

---

## 4. When Reauthorisation Is Required

Reauthorisation may be required following:

- material model or system changes;
- significant changes in data;
- changes in mission;
- changes in operational environment;
- changes in autonomy;
- changes in human authority;
- significant safety or security events;
- material performance degradation;
- new failure modes;
- changed threat conditions;
- changed legal or policy requirements;
- expiry of an authorisation period;
- significant change in dependencies;
- major changes in operating assumptions.

---

## 5. Authorisation Review

The review should establish whether the current authorisation remains appropriate.

It should consider:

- current capability;
- current configuration;
- current assurance evidence;
- current risk;
- current mission;
- current environment;
- current autonomy;
- human authority;
- known limitations;
- operational restrictions;
- monitoring;
- incident history;
- unresolved findings.

---

## 6. Authorisation Preconditions

Before reauthorisation, the responsible authority should have access to sufficient information on:

- capability identity;
- configuration baseline;
- mission and use case;
- operating environment;
- risk assessment;
- autonomy assessment;
- human authority;
- TEVV evidence;
- assurance findings;
- known limitations;
- fail-safe and recovery;
- security controls;
- monitoring arrangements;
- incident history;
- outstanding corrective actions.

---

## 7. Authorisation Evidence Package

The reauthorisation package should provide a concise decision basis.

It should identify:

1. what is being authorised;
2. what has changed;
3. what evidence was generated;
4. what risks remain;
5. what conditions apply;
6. what autonomy is permitted;
7. who holds decision authority;
8. when the authority expires or is reviewed;
9. what events trigger suspension or further review.

---

## 8. Configuration

The authorisation must identify the configuration to which it applies.

Relevant elements may include:

- model version;
- model weights where applicable;
- software;
- hardware;
- firmware;
- data dependencies;
- system parameters;
- interfaces;
- security controls;
- safety controls;
- supporting services.

The principle is:

**Authorised Configuration = Deployed Configuration**

Unapproved configuration changes should not automatically inherit the existing authorisation.

---

## 9. Mission Scope

Authorisation should identify the mission or use case for which operation is permitted.

The same AI capability may require different authority for:

- information support;
- planning;
- intelligence analysis;
- logistics;
- resource allocation;
- targeting support;
- autonomous functions.

A capability authorised for one mission should not automatically be considered authorised for another.

---

## 10. Environmental Scope

Authorisation should identify the operating conditions for which evidence is sufficient.

Relevant conditions may include:

- terrain;
- weather;
- communications;
- sensor availability;
- infrastructure;
- data availability;
- adversarial conditions;
- degraded or disconnected operation.

Operating outside the validated envelope may require restriction, additional evidence or renewed authority.

---

## 11. Autonomy Scope

Authorisation should explicitly state the permitted autonomy.

A working D-AIGAAF construct is:

- **A0 — No Meaningful AI Decision**
- **A1 — Information / Observation**
- **A2 — Analysis / Recommendation**
- **A3 — Human-Authorised Action**
- **A4 — Supervised Autonomous Action**
- **A5 — Independent Consequential Autonomy**

These are working framework categories and should be mapped to applicable national, defence, legal, doctrinal and international terminology before formal adoption.

Increasing autonomy should generally require stronger evidence and clearer authority.

---

## 12. Human Authority

The authorisation should define:

- who may use the capability;
- who may accept AI recommendations;
- who may reject or bypass recommendations;
- who may change operating conditions;
- who may suspend the capability;
- who may authorise emergency protective action;
- who holds final consequential decision authority.

AI output does not itself constitute operational authority.

---

## 13. Operational AI Advisor

For higher-consequence capabilities, an **Operational AI Advisor (OAIA)** may support the authorising and command chain.

The OAIA provides operationally relevant AI judgement on:

- capability limitations;
- AI behaviour;
- uncertainty;
- risk;
- autonomy;
- operating conditions;
- assurance evidence;
- observed deviations.

The OAIA supports command authority but does not replace the legally or organisationally designated authorising authority.

---

## 14. Authorisation Conditions

An authorisation may contain conditions covering:

- mission;
- environment;
- autonomy;
- human supervision;
- operating envelope;
- performance thresholds;
- safety controls;
- security controls;
- data requirements;
- monitoring;
- fail-safe;
- reporting;
- incident response;
- configuration;
- training;
- review frequency.

Conditions should be specific enough to be operationally enforceable.

---

## 15. Conditional Authorisation

Where evidence supports limited use but not unrestricted use, authority may be granted conditionally.

Examples include:

- reduced autonomy;
- additional human supervision;
- restricted mission scope;
- restricted environment;
- enhanced monitoring;
- additional operator qualifications;
- time-limited authority.

Conditional authorisation should not be used to obscure material evidence gaps.

---

## 16. Risk Acceptance

Residual risk should be explicitly identified.

The authorising authority should understand:

- what risks remain;
- why they remain;
- what controls mitigate them;
- what evidence supports the controls;
- what consequences could result if controls fail.

Risk acceptance and operational authorisation should remain identifiable decisions even where made within the same governance process.

---

## 17. Evidence Confidence

Authorisation decisions should account for evidence quality.

Consider:

- relevance;
- recency;
- independence;
- test coverage;
- operational representativeness;
- limitations;
- unresolved findings;
- uncertainty.

Weak evidence should not be represented as strong assurance.

---

## 18. Known Limitations

The authorisation should identify material limitations, including where applicable:

- known failure modes;
- unsupported environments;
- data limitations;
- performance boundaries;
- uncertainty;
- degraded-mode limitations;
- autonomy limitations;
- human-factor limitations;
- security assumptions.

Limitations should be visible to relevant decision-makers and users.

---

## 19. Fail-Safe and Suspension

The authorisation should establish conditions under which the capability must be:

- restricted;
- placed into a safer mode;
- disconnected;
- suspended;
- terminated.

The fail-safe mechanism is a last-resort control.

Where circumstances permit, issues should be assessed through the appropriate chain involving:

**Developer / Technical Owner → AI System Manager → OAIA → Command / Authorising Authority**

Where delay could create unacceptable harm, pre-authorised emergency protective procedures may permit immediate protective action, followed by notification and review.

---

## 20. Incident Impact

A significant incident may invalidate or weaken the basis of an existing authorisation.

Examples include:

- unexpected consequential behaviour;
- safety control failure;
- security compromise;
- material performance degradation;
- loss of human control;
- unauthorised autonomy;
- unexplained system behaviour.

The capability may require restriction or suspension pending assessment.

---

## 21. Changes in Mission or Environment

A capability may remain technically unchanged while the operational context changes.

A new mission or environment can therefore create a new authorisation question.

The principle is:

**Same AI does not necessarily mean same authority.**

---

## 22. Changes in Autonomy

A change from recommendation to action, or from supervised to more independent action, should receive heightened authorisation scrutiny.

The authorisation should clearly distinguish:

- what the AI may observe;
- what it may analyse;
- what it may recommend;
- what it may execute;
- what requires human approval;
- what it is prohibited from doing.

---

## 23. Changes in Human Authority

If human supervision, approval, override or intervention changes, the authorisation basis should be reassessed.

Reduced human control may materially increase operational risk even when model performance remains unchanged.

---

## 24. Supply-Chain Changes

Changes to suppliers, dependencies or externally controlled components should be assessed where they may affect:

- model behaviour;
- security;
- data;
- integrity;
- availability;
- autonomy;
- assurance.

The authorisation should identify critical dependencies where necessary.

---

## 25. Authorisation Decision States

A working status model is:

### Proposed

Reauthorisation package is being prepared.

### Under Review

Evidence and authority are being assessed.

### Conditionally Authorised

Operation is permitted subject to explicit restrictions.

### Operationally Authorised

Operation is permitted within the defined authorisation envelope.

### Restricted

Authority remains but with reduced scope or additional controls.

### Suspended

Operational authority is temporarily withdrawn.

### Revoked

Authority is withdrawn pending further decision.

### Retired

The capability is no longer authorised for operational use.

---

## 26. Reauthorisation Decision

The decision should explicitly state:

- capability;
- configuration;
- mission;
- environment;
- autonomy;
- human authority;
- evidence basis;
- residual risk;
- limitations;
- conditions;
- monitoring;
- validity period;
- review date;
- suspension triggers;
- authorising authority.

---

## 27. Validity Period

Authorisation should have an appropriate review period.

The period should reflect:

- consequence;
- autonomy;
- change frequency;
- operational volatility;
- evidence confidence;
- mission criticality;
- threat environment.

Higher-risk capabilities may require more frequent review.

---

## 28. Suspension Triggers

Predefined suspension or urgent review triggers may include:

- critical safety failure;
- loss of human control;
- significant security compromise;
- unexplained consequential behaviour;
- material configuration deviation;
- unauthorised autonomy;
- performance outside approved thresholds;
- invalidated assumptions;
- significant change in mission or environment.

---

## 29. Emergency Authority

Emergency procedures should be predefined for situations where immediate action is necessary to prevent unacceptable harm.

Emergency authority should specify:

- who may act;
- what protective actions are permitted;
- duration;
- notification requirements;
- documentation;
- retrospective review.

Emergency authority should not become a mechanism for bypassing normal governance.

---

## 30. Reauthorisation and Monitoring

Authorisation should be linked to continuous assurance.

Monitoring should determine whether:

- authorised conditions remain satisfied;
- performance remains within thresholds;
- configuration remains unchanged;
- autonomy remains within limits;
- assumptions remain valid;
- incidents or emerging risks require action.

The authorisation should define what monitoring results require escalation.

---

## 31. Reauthorisation and Configuration Control

The authorisation should reference a specific configuration baseline.

The control relationship is:

**Approved Baseline → Revalidated Baseline → Authorised Baseline → Deployed Configuration**

A configuration that cannot be reliably identified should not be treated as reliably authorised.

---

## 32. Restrictions

Restrictions should be explicit, measurable and enforceable.

Possible restrictions include:

- mission limitations;
- environmental limitations;
- autonomy limits;
- user restrictions;
- data restrictions;
- operating-time restrictions;
- supervision requirements;
- geographic or system boundaries;
- mandatory monitoring.

---

## 33. Authorisation Handover

Where authority changes between organisational levels, the receiving authority should have access to:

- current authorisation;
- evidence basis;
- conditions;
- limitations;
- risk;
- monitoring status;
- incidents;
- configuration.

Authority should not depend on undocumented institutional knowledge.

---

## 34. Record of Authorisation

An Operational Authorisation Record should include:

| Field | Description |
|---|---|
| Authorisation ID | Unique identifier |
| Capability ID | AI capability |
| Configuration | Authorised baseline |
| Mission | Approved mission/use case |
| Environment | Approved environment |
| Autonomy | Permitted autonomy |
| Human Authority | Decision and supervision structure |
| Evidence | Assurance basis |
| Risk | Accepted residual risk |
| Limitations | Known limitations |
| Conditions | Operational conditions |
| Monitoring | Required monitoring |
| Suspension Triggers | Conditions for restriction/suspension |
| Valid From | Start date |
| Valid Until | Expiry/review date |
| Authorising Authority | Responsible authority |
| Decision | Authorisation status |
| Review | Required review |

---

## 35. Decision Accountability

The framework should preserve a clear distinction between:

**AI Output → Human Decision → Authorised Action → Outcome**

Where consequential action occurs, records should support determination of:

- who received the AI output;
- what information was available;
- what configuration was active;
- what authority existed;
- what decision was made;
- what action followed.

This supports accountability without assuming that AI itself holds legal or command authority.

---

## 36. Reauthorisation Failure

Reauthorisation should not be granted where:

- evidence is materially insufficient;
- risk exceeds acceptable authority;
- human control is inadequate;
- configuration cannot be verified;
- mission suitability is not demonstrated;
- safety or security controls are inadequate;
- autonomy exceeds authorised limits.

Possible outcomes include:

- restriction;
- suspension;
- rollback;
- additional TEVV;
- reduced autonomy;
- further revalidation;
- retirement.

---

## 37. Independent Challenge

High-consequence reauthorisation should include independent challenge where practical.

Challenge should examine:

- evidence sufficiency;
- assumptions;
- residual risk;
- limitations;
- autonomy;
- human control;
- operational suitability.

The purpose is to reduce confirmation bias and prevent authority from becoming a procedural rubber stamp.

---

## 38. Reauthorisation Review Board

Organisations may establish a review mechanism appropriate to their governance structure.

Relevant participants may include:

- operational authority;
- AI system owner;
- risk representative;
- assurance/TEVV representative;
- security representative;
- safety representative;
- legal/policy representative;
- OAIA;
- other domain specialists as required.

The composition should reflect consequence and autonomy.

---

## 39. Reauthorisation After Incident

After a significant incident:

**Incident → Containment → Investigation → Assurance Review → Revalidation → Reauthorisation Decision**

Continued operation should be based on explicit authority rather than assumption.

---

## 40. Reauthorisation After Material Change

For material changes:

**Change → Change Impact Assessment → Revalidation → Assurance Review → Reauthorisation**

This prevents technical change approval from being confused with renewed operational permission.

---

## 41. Reauthorisation and Continuous Assurance

Reauthorisation is one point in a continuing authority cycle:

**Authorise → Employ → Monitor → Detect Change / Incident → Revalidate → Reauthorise**

Operational authority therefore remains conditional on continuing assurance.

---

## 42. Core Rules

1. **Operational authorisation is conditional, not permanent.**
2. **Reauthorisation is an authority decision, not a testing activity.**
3. **Revalidation provides evidence; reauthorisation determines permission.**
4. **Authorisation must identify the capability and configuration to which it applies.**
5. **Mission and environment must be explicitly bounded.**
6. **Permitted autonomy must be explicit.**
7. **Human authority must remain identifiable.**
8. **Residual risk must be visible to the authorising authority.**
9. **Known limitations must be documented.**
10. **Material incidents or changes may invalidate existing authority.**
11. **High-consequence authorisation should receive independent challenge where practical.**
12. **Emergency authority should be predefined and subject to retrospective review.**
13. **Restrictions must be explicit and enforceable.**
14. **Monitoring must be linked to suspension and review triggers.**
15. **Unauthorised configuration changes must not automatically inherit existing authority.**
16. **AI output does not itself constitute operational authority.**
17. **The authorisation chain must preserve accountability for consequential decisions and actions.**
18. **Authorisation must remain connected to continuous assurance.**

---

## 43. Golden Thread

Reauthorisation maintains the Golden Thread:

**Mission Need → Risk → Requirements → Capability → Change / Incident → TEVV → Evidence → Revalidation → Assurance → Authority → Employment → Monitoring → Reauthorisation**

---

## 44. Relationship to Other D-AIGAAF Sections

This document connects directly with:

- **01 Strategy & Governance** — establishes authority and governance.
- **02 Mission & Use Case** — defines mission boundaries.
- **03 Risk & Autonomy** — provides risk and autonomy assessments.
- **04 AI Lifecycle** — provides lifecycle context.
- **08 Human Authority** — defines human decision rights and control.
- **09 TEVV** — provides evidence.
- **10 Operational Environment** — defines validated environments.
- **11 Operational Authorisation** — provides the primary authorisation framework and authority model.
- **12 Operational Employment** — governs actual use.
- **13 Performance Monitoring** — provides continuing operational evidence.
- **14 Model & System Updates** — identifies changes requiring review.
- **15 Change Impact Assessment** — determines impact and revalidation need.
- **16 Revalidation** — establishes whether assurance remains valid.
- **20 Templates** — supports standardised records and decision documentation.
- **21 Legal & Policy** — ensures authority aligns with applicable law and policy.

---

## 45. Summary Model

```text
Revalidation / Trigger
        ↓
Assurance Review
        ↓
Risk / Autonomy / Human Authority Review
        ↓
Authorisation Review
        ↓
┌─────────────────────────────────────┐
│ Authorised                           │
│ Conditionally Authorised             │
│ Restricted                           │
│ Suspended                            │
│ Revoked / Retired                    │
└─────────────────────────────────────┘
        ↓
Updated Conditions / Baseline
        ↓
Controlled Employment
        ↓
Continuous Monitoring
        ↓
Change / Incident / Review
        ↓
Revalidation / Reauthorisation
```

Reauthorisation ensures that operational permission remains tied to the capability, evidence, risk, mission, environment, autonomy and human authority that actually exist.
