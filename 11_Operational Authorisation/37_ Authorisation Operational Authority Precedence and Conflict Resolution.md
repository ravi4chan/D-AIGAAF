# 37 — Authorisation Operational Authority Precedence and Conflict Resolution

## 1. Purpose

This document defines how D-AIGAAF resolves conflicts between operational authorisation, mission requirements, risk controls, system behaviour, human decisions, technical constraints, environmental conditions, policies, dependencies and other sources of authority.

Defence AI capabilities may operate within complex organisations where multiple instructions, controls and conditions can exist simultaneously. Without a defined precedence model, conflicting instructions may create ambiguity about what the AI system, operator or commander is permitted or required to do.

This document establishes principles for resolving such conflicts while preserving human authority, safety, legality, traceability and operational control.

---

## 2. Core Principle

> **Where requirements, instructions, conditions or authorities conflict, the conflict shall be identified and resolved through defined governance and decision rights. No lower-level technical instruction, AI output, system state or operational convenience shall silently override a higher-level authorisation boundary or mandatory control.**

Conflict shall not be interpreted as permission to expand AI authority.

---

## 3. Authority Precedence Model

D-AIGAAF establishes the following conceptual precedence hierarchy:

1. Applicable Law and Binding Legal Requirements
2. Binding National, Defence and Organisational Policy
3. Formal Operational Authorisation
4. Authorisation Conditions, Restrictions and Boundaries
5. Operational Command and Mission Direction
6. Approved Rules, Procedures and Operating Constraints
7. Human Operator and Supervisor Decisions Within Their Authority
8. Technical System Controls and Safety Mechanisms
9. AI Recommendations and System Outputs
10. Automated Optimisation or Convenience

This is a governance model, not a substitute for applicable national law, military doctrine or organisational command arrangements.

Where applicable law or binding policy establishes a different mandatory hierarchy, that requirement takes precedence.

---

## 4. Authorisation Does Not Override Law or Policy

An operational authorisation shall not be interpreted as permission to:

- violate applicable law;
- bypass binding policy;
- ignore mandatory safety requirements;
- circumvent security controls;
- exceed the authority of the approving organisation;
- create authority that the approving authority does not possess.

Operational authorisation exists within the wider legal and governance framework.

---

## 5. Authorisation Conditions Have Operational Effect

Conditions and restrictions attached to an authorisation form part of the authority granted.

Where an instruction conflicts with a mandatory authorisation condition, the conflict shall be recognised and escalated unless the person issuing the instruction has lawful authority to modify or replace the authorisation.

An operator should not be expected to resolve a material authority conflict through personal interpretation alone.

---

## 6. Mission Direction versus AI Authority

Mission requirements may change during operations.

A commander may alter mission priorities within their lawful authority, but such a change does not automatically expand the AI capability's authorised:

- mission;
- function;
- environment;
- autonomy;
- human authority;
- configuration;
- data access;
- dependency scope;
- consequence level.

Where mission direction exceeds the established AI authorisation, the capability shall remain within its existing authority until the appropriate governance decision is made.

---

## 7. Human Decision versus AI Recommendation

AI output is advisory unless a specific autonomy level has been authorised.

A human decision-maker may:

- accept an AI recommendation;
- reject it;
- modify it;
- defer it;
- seek additional information;
- request another assessment;
- direct a different action within their authority.

AI disagreement with a human decision does not create AI authority to override that decision unless such authority has been explicitly and appropriately authorised.

---

## 8. Technical Controls versus Human Authority

Technical safeguards may impose stricter limitations than an operational authorisation.

For example, a system may prevent an action because:

- a safety condition has failed;
- an environmental boundary has been exceeded;
- a required dependency is unavailable;
- security integrity is uncertain;
- an autonomy transition has not been approved;
- a fail-safe condition has been triggered.

A human authority should not assume that technical capability can be used simply because operational authority exists.

Where technical controls prevent an authorised action, the issue should be investigated and resolved through the appropriate technical and operational authority.

Technical controls should not be bypassed merely to restore operational convenience.

---

## 9. Fail-Safe Precedence

When a fail-safe or protective mechanism is triggered because continued operation may create unacceptable risk, the protective state should take precedence over normal operational continuation.

The response should normally follow:

**Detect → Alert → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

Where immediate protective action is necessary to prevent unacceptable harm, pre-authorised emergency procedures may permit immediate intervention.

Subsequent governance review should determine whether the capability may be restored.

---

## 10. Loss of Human Authority

If required human authority becomes unavailable, uncertain or ineffective, the capability shall not automatically assume additional authority.

Examples include:

- loss of communications;
- loss of operator;
- loss of supervisor;
- unclear command succession;
- excessive human workload;
- inability to intervene;
- loss of situational awareness.

The capability should move to the predefined state appropriate to the authorised continuity and contingency arrangements.

---

## 11. Autonomy Conflict

A conflict exists where the system's actual or proposed behaviour exceeds the authorised autonomy level.

Examples include:

- A2 system attempting an action;
- A3 system acting without required human authorisation;
- A4 system operating without required supervision;
- unexpected transition toward higher autonomy;
- automated chaining of actions that effectively creates higher autonomy.

Such behaviour shall be treated as an authority and potentially safety event.

The response should include appropriate restriction, autonomy reduction, human control, safe-state transition or suspension.

---

## 12. Environment Conflict

Where operational conditions exceed the demonstrated or authorised environment, the system shall not assume that continued operation remains authorised.

Examples include:

- severe weather;
- unexpected terrain;
- sensor degradation;
- navigation uncertainty;
- communications loss;
- electromagnetic disruption;
- adversarial conditions;
- computing degradation.

The appropriate response should follow predefined environmental boundaries and transition criteria.

---

## 13. Configuration Conflict

Operational authority applies to the configuration identified in the authorisation basis.

A conflict may arise where:

- system version differs from the authorised baseline;
- model state has changed;
- software has been updated;
- hardware has changed;
- safety controls differ;
- interfaces have changed;
- data configuration is materially different.

The capability shall not rely on functional similarity to establish continued authority.

Material configuration uncertainty should trigger the appropriate change-control, assurance, revalidation or reauthorisation process.

---

## 14. Data and Information Conflict

Conflicts may occur where information sources disagree or where data integrity is uncertain.

The system and operators should distinguish between:

- confirmed information;
- conflicting information;
- uncertain information;
- stale information;
- incomplete information;
- unverified information.

AI systems should not present unresolved conflicts as certainty.

Where conflicting information materially affects a consequential decision, the issue should be escalated or additional verification obtained where practicable.

---

## 15. Multiple Human Authorities

Multiple commanders, supervisors, technical authorities or organisational authorities may sometimes provide apparently conflicting instructions.

The organisation should define:

- command hierarchy;
- operational decision rights;
- technical decision rights;
- security authority;
- risk authority;
- authorisation authority;
- escalation authority.

An AI system should not independently determine which human authority has precedence where that hierarchy is unclear.

The conflict should be resolved through the established human chain of authority.

---

## 16. Technical Authority versus Operational Authority

Technical authority and operational authority are distinct.

### Technical Authority

May determine:

- technical suitability;
- configuration;
- maintenance;
- system integrity;
- technical constraints;
- technical recovery.

### Operational Authority

May determine:

- mission employment;
- operational priority;
- authorised use;
- human decision rights;
- operational restrictions.

Neither authority should silently assume the responsibilities of the other.

Where technical and operational views conflict, the matter should be escalated according to defined governance arrangements.

---

## 17. Security Authority versus Operational Continuity

Security controls may conflict with immediate operational requirements.

A security authority may require:

- isolation;
- access restriction;
- disconnection;
- suspension;
- configuration lockdown;
- additional verification.

Operational command may have an urgent mission requirement.

Neither side should resolve the conflict through unilateral circumvention of the other's authority.

The organisation should define emergency decision rights and protective procedures in advance.

Security compromise should generally increase governance restrictions rather than create additional AI authority.

---

## 18. Risk Acceptance versus Authorisation

Risk acceptance does not automatically create operational authorisation.

A risk owner may accept a defined residual risk within their authority, but that acceptance does not:

- expand the authorised mission;
- increase autonomy;
- remove mandatory controls;
- override legal requirements;
- replace required assurance;
- create authority for an unauthorised configuration.

Risk acceptance and operational authorisation should remain traceably connected but distinct decisions.

---

## 19. Emergency Conflict Resolution

Emergency conditions may require rapid decisions.

The objective should be:

1. Protect human life and assets;
2. Preserve human authority;
3. Prevent uncontrolled AI behaviour;
4. Apply predefined protective measures;
5. Move to the safest practicable authorised state;
6. Escalate unresolved authority conflicts;
7. Preserve evidence;
8. Review the event after immediate danger has passed.

Emergency conditions should not be used as a general mechanism for bypassing governance.

---

## 20. Conflict Resolution Process

When a material conflict is identified:

### Step 1 — Detect

Identify the conflicting requirements, instructions or authorities.

### Step 2 — Classify

Determine whether the conflict concerns:

- law/policy;
- mission;
- authorisation;
- risk;
- autonomy;
- human authority;
- technical controls;
- security;
- environment;
- configuration;
- data;
- dependencies.

### Step 3 — Establish Authority

Identify which human authority has decision rights over the issue.

### Step 4 — Apply Precedence

Apply the applicable authority hierarchy and mandatory controls.

### Step 5 — Assess Consequence

Determine whether delay, continuation or resolution may create material risk.

### Step 6 — Protect

Apply predefined restrictions, autonomy reduction, human control, safe state or suspension where required.

### Step 7 — Decide

Make and record the authorised human decision.

### Step 8 — Verify

Confirm that the resulting system state and operational activity conform to the decision.

### Step 9 — Record

Capture the conflict, decision, authority, rationale and outcome.

### Step 10 — Learn

Determine whether the conflict indicates a weakness requiring changes to authorisation, procedures, system design or governance.

---

## 21. AI Behaviour During Conflict

AI systems should be designed and governed so that conflicting instructions do not result in uncontrolled behaviour.

Where material conflict is detected, the system should, where technically feasible:

- identify the conflict;
- communicate the uncertainty;
- avoid silently selecting a higher-risk interpretation;
- preserve applicable safety constraints;
- defer to authorised human decision-making;
- move toward the predefined safe or restricted state when required.

The system should not conceal the existence of conflicting instructions.

---

## 22. Conflicting AI Outputs

Where multiple AI systems produce conflicting recommendations:

- neither recommendation automatically takes precedence;
- source, provenance and confidence should be considered;
- disagreement should be visible to the human decision-maker;
- consequential action should remain subject to the applicable human authority;
- material disagreement should be recorded where relevant.

An aggregation mechanism should not conceal material disagreement.

---

## 23. Multi-AI Authority Conflict

Where one AI system provides information or recommendations to another AI system, the receiving system should not treat the upstream AI as an authority merely because it is technically connected.

The authority chain must remain human-defined.

For consequential multi-AI arrangements, the organisation should identify:

- originating system;
- receiving system;
- information flow;
- authority boundary;
- human decision rights;
- autonomy level;
- escalation mechanism.

---

## 24. Conflict During Degraded or Disconnected Operations

When communications or central governance systems are unavailable:

- previously defined authority remains applicable;
- predefined local procedures should govern;
- autonomy should not expand by default;
- human authority should be preserved where practicable;
- minimum required records should be maintained;
- decisions should be reconciled after connectivity is restored.

Disconnection does not invalidate existing authority automatically, but neither does it create new authority.

---

## 25. Conflict and Operational Boundaries

If resolving a conflict would require crossing an operational boundary, the capability should remain within its existing boundary unless an appropriately authorised decision changes that boundary.

A commander may make a new operational decision within their authority, but the AI capability's authority must be separately considered where the proposed change materially affects its approved scope.

---

## 26. Conflict and Change Control

A recurring conflict may indicate that the existing authorisation is no longer suitable.

Examples include:

- repeated mission-authority conflicts;
- recurring autonomy ambiguity;
- repeated security-versus-operation conflicts;
- frequent environment boundary disputes;
- unclear human decision rights;
- recurring technical-control overrides.

Such patterns should trigger governance review and, where necessary:

- amendment;
- additional assurance;
- revalidation;
- reauthorisation;
- restriction;
- suspension.

---

## 27. Conflict Register

A controlled **Authorisation Conflict Register** should record material conflicts.

Suggested fields:

| Field | Description |
|---|---|
| Conflict ID | Unique identifier |
| Date/Time | When conflict occurred |
| Capability | AI capability involved |
| Mission | Relevant mission/use case |
| Conflict Type | Category of conflict |
| Conflicting Authorities | Authorities or requirements involved |
| Initial State | System/operational state |
| Risk | Potential consequence |
| Immediate Action | Protective action taken |
| Decision Authority | Human authority resolving conflict |
| Decision | Resolution |
| Rationale | Basis for decision |
| Outcome | Result |
| Evidence | Supporting records |
| Follow-up | Required governance action |
| Status | Open/Closed |

---

## 28. Non-Delegable Conflict Decisions

Certain conflicts may be too consequential to delegate below the designated authority.

Examples may include:

- material increase in autonomy;
- expansion of consequential mission scope;
- acceptance of materially increased residual risk;
- overriding mandatory safety controls;
- restoration following serious loss of control;
- continuation after major security compromise;
- reauthorisation following material failure.

The applicable organisation should define which decisions require retained authority.

---

## 29. Governance Review

Material conflicts should be reviewed periodically to identify systemic weaknesses.

Review should consider:

- frequency;
- severity;
- recurring patterns;
- authority ambiguity;
- system design;
- human factors;
- procedures;
- training;
- technical controls;
- authorisation conditions;
- assurance evidence.

The objective is not merely to resolve individual conflicts but to reduce the likelihood of recurrence.

---

## 30. Golden Thread

Conflict resolution should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Conflict/Incident → Change → Revalidation/Reauthorisation**

This ensures that recurring authority conflicts can result in improvements to the underlying governance and assurance basis.

---

## 31. Governance Questions

Before operational employment, the organisation should be able to answer:

1. What happens when two instructions conflict?
2. Which authority has precedence?
3. Can an AI recommendation override a human decision?
4. Can technical controls override operational direction?
5. Who resolves technical versus operational disagreement?
6. What happens when security requirements conflict with mission urgency?
7. What happens when human authority is unavailable?
8. What happens when the AI's actual autonomy exceeds its authorised autonomy?
9. What happens when environmental conditions invalidate an assumption?
10. Who resolves conflicting AI outputs?
11. Which decisions cannot be delegated?
12. How are conflicts recorded and reviewed?

---

## 32. Core Rule

> **Material conflicts affecting Defence AI operational authority shall be identified, attributable and resolved through defined human decision rights and an explicit precedence model. AI outputs, technical capability, operational urgency or system connectivity shall not silently override legal requirements, mandatory controls, authorisation boundaries or established human authority. Where conflict cannot be safely resolved, the capability shall move toward an appropriately restricted, human-controlled, safe or suspended state until controlled authority is restored.**
