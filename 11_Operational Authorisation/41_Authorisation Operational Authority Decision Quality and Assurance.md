# 41 — Authorisation Operational Authority Decision Quality and Assurance

## 1. Purpose

This document defines how D-AIGAAF assesses and improves the quality of operational authorisation decisions for Defence AI capabilities.

The objective is to ensure that authorisation decisions are not evaluated solely by their outcome, but also by the quality of the process, evidence, judgement, authority, uncertainty management and governance controls through which the decision was reached.

A technically successful mission does not necessarily demonstrate that the authorisation decision was well-founded.

---

## 2. Core Principle

> **The quality of an operational authorisation decision shall be assessed by the quality, sufficiency and traceability of the evidence, authority, reasoning, risk assessment and governance process supporting the decision—not solely by the eventual operational outcome.**

Decision quality should be continuously improved through review, evidence, incidents, lessons and independent challenge.

---

## 3. Decision Quality Dimensions

D-AIGAAF assesses authorisation decision quality across:

1. Decision clarity
2. Authority clarity
3. Evidence sufficiency
4. Evidence relevance
5. Risk understanding
6. Uncertainty management
7. Autonomy assessment
8. Human-control assessment
9. Environmental suitability
10. Security assurance
11. Configuration integrity
12. Boundary definition
13. Condition adequacy
14. Residual-risk acceptance
15. Independent challenge
16. Traceability
17. Monitoring and reviewability

The depth of assessment should be proportionate to consequence and risk.

---

## 4. Decision Clarity

A decision should clearly state:

- what is being authorised;
- for which mission;
- in which environment;
- at what autonomy level;
- under whose human authority;
- with which configuration;
- subject to which conditions;
- for what period;
- with what restrictions.

Ambiguous authority creates operational risk.

---

## 5. Authority Clarity

Decision quality depends on knowing:

- who requested authority;
- who assessed it;
- who reviewed it;
- who accepted residual risk;
- who authorised employment;
- who may restrict or suspend it;
- who may change the authority;
- who remains accountable.

Delegation should be explicit and traceable.

---

## 6. Evidence Sufficiency

Evidence should be sufficient for the specific authority being requested.

The assessment should consider:

- quantity;
- quality;
- relevance;
- operational representativeness;
- recency;
- independence;
- configuration applicability;
- environmental applicability.

More evidence is not necessarily better evidence.

The critical question is whether the evidence supports the operational claim being made.

---

## 7. Evidence Relevance

Evidence should correspond to:

**Capability × Mission × Environment × Autonomy × Human Authority**

Evidence from a different mission, configuration or environment should not automatically support the proposed authorisation.

Material differences should be identified and assessed.

---

## 8. Risk Understanding

Decision quality requires that material risks are:

- identified;
- assessed;
- treated;
- communicated;
- assigned to an owner;
- accepted by an appropriate authority where residual risk remains.

Risk should not be hidden within technical documentation.

---

## 9. Uncertainty Management

The decision-maker should understand what is:

- known;
- demonstrated;
- conditionally demonstrated;
- uncertain;
- untested;
- contradicted.

Material uncertainty should be visible before authority is granted.

AI-generated confidence should not be treated as a substitute for evidence.

---

## 10. Autonomy Assessment Quality

For capabilities involving autonomy, review should establish:

- actual autonomy;
- authorised autonomy;
- supervision;
- intervention;
- override;
- autonomy transitions;
- unexpected autonomy;
- consequences of loss of human supervision.

The assessment should consider effective autonomy, not merely the autonomy described by the system provider.

---

## 11. Human-Control Assessment Quality

The decision should consider whether human control is realistically achievable under operational conditions.

Relevant factors include:

- workload;
- time available;
- situational awareness;
- training;
- information quality;
- interface usability;
- intervention time;
- override effectiveness;
- communications;
- degraded operations.

A nominal human-in-the-loop arrangement is insufficient if the human cannot meaningfully understand or intervene.

---

## 12. Environmental Decision Quality

The decision should consider whether the proposed environment has been adequately assessed.

Particular attention should be given to:

- boundary conditions;
- degraded conditions;
- disconnected operations;
- adversarial conditions;
- sensor limitations;
- communications;
- navigation;
- electromagnetic conditions;
- human factors.

Untested conditions should be treated as decision-relevant uncertainty.

---

## 13. Security Decision Quality

Security considerations should include:

- threat model;
- attack surface;
- model integrity;
- data integrity;
- configuration integrity;
- dependency risks;
- adversarial manipulation;
- detection;
- response;
- consequences of compromise.

A system should not receive unrestricted operational authority where material security risks remain inadequately controlled.

---

## 14. Configuration Decision Quality

The decision should be tied to a defined configuration baseline.

The assessment should establish whether:

- the tested configuration matches the authorised configuration;
- model state is known;
- software is controlled;
- hardware is identified;
- safety controls are present;
- security controls are present;
- dependencies are consistent.

Material configuration uncertainty should affect the decision.

---

## 15. Boundary Decision Quality

Operational boundaries should be:

- explicit;
- understandable;
- measurable where practicable;
- enforceable;
- monitored;
- supported by evidence.

A boundary that cannot be understood or enforced may not provide meaningful governance.

---

## 16. Condition Quality

Authorisation conditions should be:

- necessary;
- clear;
- achievable;
- measurable where practicable;
- assigned to an accountable owner;
- monitored;
- linked to risk.

Conditions should not be used as vague statements to compensate for missing evidence.

---

## 17. Residual-Risk Decision Quality

Risk acceptance should identify:

- residual risk;
- uncertainty;
- controls;
- risk owner;
- acceptance authority;
- conditions;
- consequences if assumptions fail.

The decision-maker should not accept risk that is outside their authority.

---

## 18. Independent Challenge

Material authorisation decisions should receive proportionate independent challenge.

The reviewer should be able to question:

- evidence;
- assumptions;
- risk;
- autonomy;
- human control;
- security;
- environmental suitability;
- conditions;
- residual risk.

Independent challenge should be substantive rather than a procedural signature.

---

## 19. Decision Traceability

A high-quality decision should be reconstructable through:

**Mission → Risk → Evidence → Assurance → Authority → Conditions → Decision → Employment → Outcome**

The organisation should be able to determine why authority was granted and what information supported it.

---

## 20. Decision Bias

The review process should consider potential sources of bias, including:

- confirmation bias;
- automation bias;
- schedule pressure;
- sunk-cost bias;
- organisational pressure;
- commercial influence;
- availability bias;
- overconfidence;
- familiarity with the system;
- previous successful performance.

A successful history should not automatically justify broader authority.

---

## 21. Outcome versus Decision Quality

D-AIGAAF distinguishes:

**Good Decision + Good Outcome**

**Good Decision + Poor Outcome**

**Poor Decision + Good Outcome**

**Poor Decision + Poor Outcome**

A poor outcome does not necessarily mean the original decision was unreasonable.

A good outcome does not prove that the decision was adequately justified.

This distinction is important for learning and accountability.

---

## 22. Decision Quality Indicators

Possible indicators include:

- proportion of decisions with complete evidence packages;
- proportion with independent review;
- number of unresolved material evidence gaps;
- number of authorisation disputes;
- number of post-authorisation corrections;
- number of boundary violations;
- number of unexpected autonomy events;
- number of emergency interventions;
- number of authorisations requiring early restriction;
- number of incidents revealing previously unidentified risks.

Indicators should be used for learning rather than creating incentives to suppress reporting.

---

## 23. Decision Quality Review

Decision-quality review should occur:

- periodically;
- after significant incidents;
- after material disputes;
- after unexpected AI behaviour;
- following major changes;
- during revalidation;
- during reauthorisation.

Review should examine both the decision and the process that produced it.

---

## 24. Post-Decision Review

Where appropriate, review should ask:

1. Was the decision within authority?
2. Was the evidence sufficient?
3. Were material limitations disclosed?
4. Were uncertainties understood?
5. Was risk appropriately assessed?
6. Was human control realistic?
7. Were conditions adequate?
8. Were operational boundaries clear?
9. Did actual conditions match assumptions?
10. Did the decision produce information requiring governance change?

---

## 25. Decision Quality after Incidents

Following a significant incident, the organisation should avoid assuming that the incident alone proves poor decision-making.

The review should distinguish:

- information available before the decision;
- information available during employment;
- information discovered after the incident;
- previously foreseeable risks;
- genuinely novel behaviour.

This supports fair and evidence-based accountability.

---

## 26. Corrective Action

Decision-quality findings may require:

- additional training;
- improved decision templates;
- stronger evidence requirements;
- additional independent review;
- revised thresholds;
- revised conditions;
- improved human-AI interfaces;
- stronger monitoring;
- additional TEVV;
- changes to authorisation procedures;
- revalidation;
- reauthorisation.

Corrective action should address root causes rather than only individual decision errors.

---

## 27. Decision Quality and Continuous Assurance

Decision-quality findings should feed the continuous assurance cycle:

**Decision → Employment → Evidence → Outcome → Review → Learning → Control Improvement → Revalidation/Reauthorisation**

This allows operational experience to strengthen future authorisation decisions.

---

## 28. Decision Quality Register

A controlled **Authorisation Decision Quality Register** may include:

| Field | Description |
|---|---|
| Review ID | Unique identifier |
| Authorisation | Related authority |
| Decision | Decision reviewed |
| Review Trigger | Reason for review |
| Evidence Quality | Assessment |
| Risk Quality | Assessment |
| Authority Quality | Assessment |
| Human Control | Assessment |
| Autonomy | Assessment |
| Boundary Quality | Assessment |
| Independent Challenge | Assessment |
| Findings | Material findings |
| Corrective Action | Required action |
| Outcome | Review result |
| Revalidation | Required/not required |
| Reauthorisation | Required/not required |
| Status | Open/Closed |

---

## 29. Decision Quality Rating

D-AIGAAF may use a working rating:

### DQ1 — Strong

Decision is well-supported, traceable, proportionate and independently challenged.

### DQ2 — Adequate with Conditions

Decision is supportable but contains identified limitations or conditions.

### DQ3 — Improvement Required

Material weaknesses exist but authority may remain subject to corrective action.

### DQ4 — Insufficient

Decision basis is materially inadequate.

### DQ5 — Unreliable

Material evidence, authority or process failures prevent confidence in the decision basis.

These are working D-AIGAAF constructs and should be adapted to the adopting organisation.

---

## 30. Governance Questions

The organisation should be able to answer:

1. How do we know an authorisation decision was well-founded?
2. Was the evidence relevant to the actual operational context?
3. Were uncertainties visible?
4. Was human control realistically achievable?
5. Was the autonomy assessment accurate?
6. Were operational boundaries enforceable?
7. Was residual risk accepted by the correct authority?
8. Was independent challenge meaningful?
9. Can the decision be reconstructed later?
10. What did the outcome teach us about the quality of the original decision?

---

## 31. Golden Thread

Decision quality should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Decision Review → Learning → Change → Revalidation/Reauthorisation**

This ensures that decision quality becomes part of continuous assurance rather than a one-time administrative assessment.

---

## 32. Core Rule

> **D-AIGAAF shall assess the quality of Defence AI operational authorisation decisions by examining the evidence, authority, reasoning, risk assessment, uncertainty, autonomy, human control, boundaries, conditions and independent challenge supporting the decision, rather than judging the decision solely by its eventual outcome. Decision-quality findings shall feed continuous assurance and, where material, corrective action, revalidation, reauthorisation, restriction or suspension.**
