# 40 — Authorisation Operational Authority Review Board and Independent Challenge

## 1. Purpose

This document defines governance arrangements for formal review and independent challenge of Defence AI operational authorisation decisions.

The purpose is to ensure that high-consequence authorisation decisions are subject to appropriate scrutiny and are not based solely on the judgement of the capability owner, developer, operator or a single decision-maker.

Independent challenge should improve decision quality without transferring operational authority away from the designated authorising authority.

## 2. Core Principle

> **Operational authorisation decisions shall be subject to proportionate, competent and sufficiently independent review, with material assumptions, evidence gaps, risks, autonomy, human-control arrangements and proposed conditions capable of being challenged before authority is granted or maintained.**

Independent challenge does not replace the accountability of the authorising authority.

## 3. Review versus Authorisation

The **Review Board** provides structured scrutiny.

The **Authorising Authority** grants, conditions, restricts, suspends or revokes operational authority.

These functions should remain distinct.

A review board may recommend authorisation, conditional authorisation, restriction, additional assurance, revalidation, reauthorisation, suspension or refusal.

The final operational-authority decision remains with the designated human authority.

## 4. Objectives of Independent Challenge

Independent review should determine whether:

- the decision package is complete;
- the evidence is relevant and sufficient;
- assumptions are reasonable;
- material uncertainty is visible;
- risk has been appropriately assessed;
- autonomy is properly bounded;
- human control is credible;
- operational boundaries are enforceable;
- configuration is controlled;
- dependencies are understood;
- security risks are addressed;
- environmental conditions are represented;
- residual risk is attributable and accepted by the appropriate authority.

## 5. Proportionality

Review depth should increase with:

- consequence;
- mission criticality;
- autonomy;
- uncertainty;
- operational complexity;
- environmental variability;
- security exposure;
- dependency criticality;
- novelty;
- scope of employment.

Low-risk decision-support applications should not necessarily require the same review process as highly autonomous consequential capabilities.

## 6. Review Authority

The adopting organisation should define:

- who convenes the review;
- who may request a review;
- who must participate;
- who may challenge evidence;
- who may require additional assurance;
- who records the review;
- who makes the final authorisation decision.

Review authority should be independent enough to challenge the proposal credibly.

## 7. Review Board Composition

Membership should be appropriate to the capability and its risks.

Potential functions include:

- operational authority;
- AI governance;
- Operational AI Advisor (OAIA);
- technical authority;
- TEVV/assurance;
- security;
- risk management;
- legal/policy;
- data/information assurance;
- human factors;
- supply-chain/dependency assurance.

Not every review requires every function. Composition should be determined by consequence and risk.

## 8. Independence

Reviewers should be sufficiently independent from the activity being reviewed to provide meaningful challenge.

Potential conflicts include:

- reviewing one's own development work;
- approving one's own risk acceptance;
- evaluating one's own test results without independent scrutiny;
- reviewing a system where the reviewer has a material personal or organisational interest.

Where full independence is impracticable, the limitation should be disclosed and compensating controls applied.

## 9. Capability Owner Participation

The capability owner should provide evidence and answer questions concerning:

- intended purpose;
- system capability;
- limitations;
- configuration;
- dependencies;
- known incidents;
- performance;
- changes;
- operational experience.

Participation does not give the capability owner authority to approve their own operational employment where governance requires independent authorisation.

## 10. Developer Participation

Developers or system providers may explain:

- architecture;
- model behaviour;
- known limitations;
- update mechanisms;
- safety controls;
- security considerations;
- testing;
- unresolved technical issues.

They should not be treated as the sole authority on operational suitability.

Technical understanding is necessary but does not substitute for operational judgement.

## 11. Operational AI Advisor Role

The **Operational AI Advisor (OAIA)** provides a bridge between:

**Operational Mission ↔ AI Capability ↔ Risk ↔ Assurance ↔ Human Authority**

The OAIA may:

- explain AI limitations to command;
- challenge unrealistic assumptions;
- interpret assurance evidence in operational terms;
- identify autonomy and human-control concerns;
- support scenario-based review;
- identify gaps between technical evidence and operational requirements.

The OAIA is advisory unless separately assigned formal decision authority.

## 12. Review Inputs

The review should normally consider:

- Operational Authorisation Decision Package;
- Operational Authorisation Record;
- risk assessment;
- autonomy assessment;
- human-control assessment;
- TEVV evidence;
- operational environment assessment;
- security assessment;
- data assurance;
- supply-chain/dependency assessment;
- configuration baseline;
- fail-safe arrangements;
- operational boundaries;
- conditions and restrictions;
- residual-risk acceptance;
- monitoring plan;
- incidents and lessons;
- legal/policy assessment;
- change history;
- previous review findings.

## 13. Review Questions

The board should challenge the proposal using questions such as:

1. What exactly is being authorised?
2. What evidence supports the requested authority?
3. What evidence does not exist?
4. What assumptions are critical?
5. What could cause loss of human control?
6. What happens when the environment changes?
7. What happens when communications fail?
8. What happens when the AI is uncertain?
9. What happens when the AI behaves unexpectedly?
10. What prevents technical capability from becoming unauthorised authority?
11. What is the residual risk?
12. Who accepts that risk?
13. What conditions are mandatory?
14. What would trigger suspension?
15. What changes would require reauthorisation?

## 14. Evidence Challenge

Reviewers should challenge whether evidence:

- corresponds to the actual configuration;
- represents the proposed environment;
- represents the proposed mission;
- covers relevant edge cases;
- is sufficiently recent;
- is independently credible;
- addresses autonomy;
- addresses human control;
- addresses adversarial conditions;
- supports the specific operational claim being made.

Evidence from an unrelated configuration or environment should not automatically be treated as sufficient.

## 15. Assumption Challenge

Critical assumptions should be explicitly identified.

Examples include assumptions concerning:

- sensor availability;
- communications;
- navigation;
- data quality;
- operator competence;
- human supervision;
- environmental conditions;
- system performance;
- external dependencies.

The board should determine whether each assumption is:

- demonstrated;
- conditionally supported;
- uncertain;
- untested;
- contradicted.

## 16. Risk Challenge

Reviewers should examine whether:

- risks are complete enough for the decision;
- consequence has been properly assessed;
- autonomy-related risk has been considered;
- human-control risks are included;
- security risks are included;
- dependency risks are included;
- residual risk is explicit;
- controls are credible;
- risk acceptance authority is appropriate.

Risk should not be reduced merely because a control exists on paper.

## 17. Autonomy Challenge

For autonomous or semi-autonomous capabilities, reviewers should challenge:

- actual autonomy;
- authorised autonomy;
- autonomy transitions;
- supervision;
- intervention;
- override;
- fail-safe;
- unexpected autonomy;
- chained autonomy across systems;
- behaviour when human supervision is unavailable.

A system should not be considered adequately controlled merely because autonomy is described in documentation.

## 18. Human-Control Challenge

Review should assess whether humans can:

- understand relevant AI outputs;
- recognise uncertainty;
- maintain situational awareness;
- intervene;
- override;
- stop or restrict the capability;
- escalate concerns;
- make consequential decisions within available time.

The review should consider realistic operational workload rather than ideal staffing assumptions.

## 19. Operational Environment Challenge

Reviewers should challenge whether TEVV and assurance evidence adequately represent the proposed environment.

This may include:

- physical conditions;
- sensor conditions;
- communications;
- navigation;
- electromagnetic environment;
- degraded infrastructure;
- adversarial conditions;
- human factors.

Untested environmental conditions should be visible in the authorisation decision.

## 20. Security Challenge

Security review should consider:

- threat model;
- attack surface;
- model integrity;
- data integrity;
- supply-chain risks;
- unauthorised modification;
- adversarial manipulation;
- dependency compromise;
- detection and response;
- consequences of compromise.

Security assurance should remain connected to operational authority.

## 21. Decision Outcomes

The review may produce:

- **R1 — Support Authorisation**
- **R2 — Support Conditional Authorisation**
- **R3 — Restrict Proposed Authority**
- **R4 — Additional Assurance Required**
- **R5 — Revalidation Required**
- **R6 — Reauthorisation Required**
- **R7 — Suspension Recommended**
- **R8 — Authorisation Not Supported**

## 22. Dissenting Views

Material dissent should be recorded.

Examples include disagreement concerning:

- risk;
- evidence sufficiency;
- autonomy;
- human control;
- security;
- operational environment;
- legal or policy requirements;
- residual risk;
- authorisation scope.

Dissent should not automatically prevent a decision, but unresolved material dissent should be visible to the authorising authority.

## 23. Review Conditions

A review may impose requirements before authorisation, such as:

- additional testing;
- independent evaluation;
- restricted deployment;
- reduced autonomy;
- additional supervision;
- enhanced monitoring;
- configuration restrictions;
- environmental limitations;
- additional security controls;
- specific competence requirements.

Conditions should be measurable and verifiable where practicable.

## 24. Review and Emergency Decisions

Emergency operational decisions may not permit the full review process.

In such cases:

- predefined emergency authorities apply;
- immediate protective actions remain available;
- temporary restrictions may be imposed;
- evidence should be preserved;
- formal review should occur as soon as practicable.

Emergency action should not become permanent authority without appropriate review.

## 25. Review after Incident

A serious incident should trigger review where it may affect:

- risk;
- performance;
- autonomy;
- human control;
- security;
- environmental assumptions;
- configuration;
- dependencies;
- authorisation conditions.

The review should determine whether the existing authority remains valid.

## 26. Review after Material Change

The board should review material changes affecting:

- model;
- model state;
- software;
- hardware;
- configuration;
- data;
- mission;
- environment;
- autonomy;
- human authority;
- security;
- dependencies.

The review should determine whether the change requires amendment, additional assurance, revalidation, reauthorisation, restriction or suspension.

## 27. Review Frequency

Periodic review should be established according to:

- consequence;
- autonomy;
- risk;
- operational tempo;
- change frequency;
- evidence currency;
- incident history.

Higher-risk capabilities should generally receive more frequent or more trigger-sensitive review.

Periodic review should not replace event-triggered review.

## 28. Review Record

A controlled **Operational Authorisation Review Record** should include:

| Field | Description |
|---|---|
| Review ID | Unique identifier |
| Capability | AI capability |
| Mission | Mission/use case |
| Authority | Current authorisation |
| Review Trigger | Reason for review |
| Review Date | Date |
| Participants | Review functions |
| Evidence Reviewed | Evidence set |
| Key Findings | Material findings |
| Risks | Material risks |
| Conditions | Proposed conditions |
| Dissent | Material dissent |
| Recommendation | Review outcome |
| Required Actions | Follow-up |
| Decision Authority | Final authority |
| Decision | Final decision |
| Next Review | Next review |

## 29. Review Findings and Corrective Action

Findings should be classified according to significance.

Possible categories include:

- Observation;
- Improvement Required;
- Minor Non-Conformance;
- Significant Non-Conformance;
- Critical Governance Concern.

Material findings should have:

- owner;
- corrective action;
- target date;
- verification method;
- closure status.

Open critical findings should normally affect continued operational authority.

## 30. Independence and Authorisation Integrity

The review process should protect against:

- pressure to approve;
- schedule-driven assurance;
- commercial influence;
- organisational bias;
- confirmation bias;
- selective evidence;
- suppression of adverse findings.

The objective is not to prevent operational use, but to ensure that authority is based on a credible and defensible decision.

## 31. Relationship with Continuous Assurance

Review findings should feed:

- risk monitoring;
- TEVV;
- operational performance monitoring;
- incident management;
- change control;
- human-control assessment;
- autonomy assurance;
- environmental assessment;
- supply-chain assurance;
- revalidation;
- reauthorisation.

This creates the feedback loop:

**Review → Findings → Corrective Action → Evidence → Assurance → Authorisation**

## 32. Governance Questions

The adopting organisation should be able to answer:

1. Who independently challenges operational authorisation decisions?
2. How is reviewer independence established?
3. Which capabilities require formal review?
4. What evidence must be challenged?
5. Who may require additional assurance?
6. How are dissenting views handled?
7. What happens when a review identifies a critical concern?
8. How are review findings tracked to closure?
9. What triggers an extraordinary review?
10. How does review feed revalidation and reauthorisation?

## 33. Golden Thread

The review process should remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Review → Change/Incident → Revalidation/Reauthorisation**

This ensures that independent challenge strengthens the entire governance lifecycle rather than becoming an isolated approval activity.

## 34. Core Rule

> **Operational authorisation for Defence AI shall be subject to proportionate, competent and sufficiently independent challenge. Reviewers shall be able to question evidence, assumptions, risk, autonomy, human control, security, environmental suitability, dependencies, conditions and residual risk without transferring operational authority away from the designated human authorising authority. Material unresolved concerns shall be visible to the decision-maker and shall trigger proportionate additional assurance, restriction, revalidation, reauthorisation or suspension where required.**
