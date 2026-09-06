# 20 Operational Employment Governance

## 1. Purpose

Operational employment is the controlled use of a Defence AI capability within the mission, environment, autonomy, human authority, configuration and conditions established by its operational authorisation.

This document defines governance requirements for actual employment after deployment and operational acceptance.

Operational employment is where the assumptions, controls and assurance basis established during the earlier stages of D-AIGAAF are exposed to real operational conditions. It therefore requires continuous human authority, monitoring, traceability and the ability to intervene when conditions change.

---

## 2. Core Principle

A Defence AI capability shall be employed only:

- for an authorised mission and use case;
- within the authorised operational environment;
- at the authorised autonomy level;
- under defined human authority;
- using an authorised configuration;
- subject to applicable conditions and restrictions;
- within established data and dependency boundaries;
- with required security controls;
- with functioning monitoring and escalation mechanisms; and
- with appropriate fail-safe and intervention arrangements.

Operational effectiveness shall not override governance requirements.

---

## 3. Employment Object

Operational employment remains governed by:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

Any material change to one or more of these dimensions should trigger assessment under the applicable change, incident, revalidation or reauthorisation process.

---

## 4. Employment States

D-AIGAAF defines the following working employment states:

| State | Meaning |
|---|---|
| **Not Employed** | The capability is authorised but is not currently being used. |
| **Active Employment** | The capability is performing its authorised functions. |
| **Restricted Employment** | The capability is operating under additional restrictions or reduced scope. |
| **Degraded Employment** | The capability is operating under an authorised degraded condition. |
| **Contingency Employment** | The capability is operating under a predefined contingency arrangement. |
| **Suspended** | Employment has been stopped pending resolution of a governance, safety, security, assurance or operational issue. |
| **Terminated** | The specific employment activity has ended. |

Employment state should be known to responsible personnel and recorded where material.

---

## 5. Employment Boundaries

Personnel responsible for operational use should understand:

- authorised mission;
- permitted functions;
- prohibited functions;
- geographic or operational boundaries;
- temporal limits;
- authorised autonomy;
- human approval requirements;
- supervision requirements;
- environmental limits;
- data limitations;
- dependency requirements;
- escalation conditions;
- intervention requirements; and
- termination or safe-state conditions.

The ability of an AI system to perform an action technically shall not be treated as evidence that the action is authorised.

---

## 6. Human Authority During Employment

Human authority shall remain identifiable throughout operational employment.

The responsible human authority should be able to determine:

- what the AI capability is being used for;
- what decisions or actions it may support;
- what level of autonomy is active;
- what limitations apply;
- when intervention is required;
- when employment should be restricted or stopped; and
- who is accountable for consequential operational decisions.

AI may support human decision-making, but shall not silently acquire authority through technical capability, automation or operator assumption.

---

## 7. Operational AI Advisor

Where designated, the **Operational AI Advisor (OAIA)** should provide an informed bridge between operational command, system management, technical personnel and AI assurance functions.

The OAIA may assist with:

- interpreting AI outputs;
- understanding limitations and uncertainty;
- assessing operational implications;
- advising on autonomy;
- identifying potential boundary violations;
- assessing unexpected behaviour;
- advising on degraded or adversarial conditions;
- supporting incident escalation; and
- translating operational observations into assurance requirements.

The OAIA does not automatically replace the command or authorising authority unless formally assigned the relevant decision rights.

---

## 8. AI Output and Decision Use

Operational users should distinguish between:

- observation;
- information;
- analysis;
- recommendation;
- prediction;
- proposed action; and
- authorised action.

The system should make the nature of its output sufficiently clear for the user to understand whether it is informing a decision or initiating an authorised action.

Where appropriate, AI outputs should communicate:

- uncertainty;
- confidence or reliability indicators;
- relevant limitations;
- data limitations;
- missing information;
- conflicting information; and
- conditions under which the output may be unreliable.

The system should not present unsupported conclusions with unjustified certainty.

---

## 9. Human Review of Consequential Decisions

Where AI contributes to consequential decisions, the required level of human review should reflect:

- potential consequence;
- mission criticality;
- autonomy level;
- uncertainty;
- environmental conditions;
- reliability of supporting information;
- reversibility of the action; and
- ability to intervene after the decision.

Higher-consequence decisions should require stronger human authority and assurance controls.

---

## 10. Human Disagreement with AI

Operational users may disagree with an AI recommendation or output.

Where a consequential AI recommendation is rejected or bypassed, the governance system should, where practicable, capture:

- the relevant AI recommendation;
- the decision taken;
- the responsible human authority;
- the principal reason for rejection or bypass;
- relevant uncertainty or conflicting information; and
- any resulting operational consequence.

The purpose is not to discourage disagreement with AI. It is to preserve decision traceability and support learning, accountability and future assurance.

---

## 11. Situational Awareness

AI should support, not degrade, human situational awareness.

Operational use should consider whether:

- users understand what the AI is observing or analysing;
- relevant uncertainty is visible;
- important information is omitted or filtered;
- automation creates excessive trust;
- users become dependent on AI recommendations;
- system limitations are understood; and
- the AI output remains consistent with available operational information.

A technically accurate output can still create operational risk if presented without sufficient context.

---

## 12. Monitoring During Employment

Operational monitoring should consider, as appropriate:

### Technical
- performance;
- availability;
- latency;
- error rates;
- system health;
- configuration integrity.

### AI Behaviour
- anomalous outputs;
- unexpected recommendations;
- unexplained behavioural changes;
- confidence or uncertainty changes;
- distribution shifts.

### Operational
- mission effectiveness;
- boundary conditions;
- human workload;
- decision quality;
- autonomy transitions.

### Security
- suspicious inputs;
- integrity failures;
- attempted manipulation;
- unauthorised access;
- abnormal system behaviour.

### Environment
- sensor degradation;
- communications loss;
- navigation uncertainty;
- environmental changes;
- adversarial conditions.

Monitoring should support timely protective action rather than merely generate post-event records.

---

## 13. Degraded and Disconnected Employment

Where authorised, the capability may continue operating under degraded or disconnected conditions.

The authorised degraded mode should define:

- permitted functions;
- autonomy restrictions;
- human-control requirements;
- available information;
- known limitations;
- transition thresholds;
- fail-safe behaviour;
- recovery requirements; and
- conditions for suspension.

Loss of communications, data or external services shall not automatically create additional authority for the AI.

Where the approved operating envelope is exceeded, the capability should transition to the defined restricted, contingency or safe state.

---

## 14. Adversarial Conditions

Operational employment should account for the possibility of:

- misleading inputs;
- manipulated data;
- sensor deception;
- communication disruption;
- navigation uncertainty;
- compromised dependencies;
- malicious interaction;
- abnormal system behaviour; and
- attempts to influence AI outputs or decisions.

Where adversarial conditions materially alter the risk profile, the responsible authority should apply the relevant operational restrictions, incident response, reassessment or suspension process.

---

## 15. Autonomy Management During Employment

Autonomy should remain within its authorised boundary.

Operational monitoring should detect:

- unintended autonomy;
- unexpected transitions;
- attempts to exceed authorised functions;
- failure of supervision;
- loss of intervention capability;
- divergence between configured and observed behaviour.

Where autonomy cannot be reliably maintained, the capability should move to the defined lower-autonomy, human-control, restricted or safe state.

Higher autonomy should never emerge merely because human supervision has become unavailable.

---

## 16. Operational Intervention

Intervention should be possible where required by the authorised risk and autonomy model.

Intervention mechanisms should be:

- understood by responsible personnel;
- accessible when required;
- tested;
- protected against unauthorised use;
- appropriate to the operational context; and
- capable of producing a predictable result to the extent reasonably practicable.

Intervention may include:

- reducing autonomy;
- restricting functions;
- requiring human confirmation;
- entering a safe state;
- stopping a specific function; or
- suspending employment.

---

## 17. Fail-Safe and Protective Action

Where AI behaviour creates unacceptable or potentially unacceptable risk, pre-defined protective actions should be available.

These may include:

**Continue → Restrict → Reduce Autonomy → Human Control → Safe State → Suspend**

The appropriate response should depend on:

- severity;
- immediacy;
- reversibility;
- available human control;
- system condition;
- environmental conditions; and
- potential consequences of delay.

Emergency protective action may be taken under pre-authorised procedures where delay could create unacceptable harm. Such action should be recorded and reviewed subsequently.

---

## 18. Incident Identification

An operational AI incident may include:

- unexpected consequential behaviour;
- incorrect or misleading output with material impact;
- loss of human control;
- autonomy boundary violation;
- fail-safe failure;
- security compromise;
- data-integrity failure;
- significant performance degradation;
- operation outside the authorised environment;
- unauthorised configuration change;
- critical dependency failure; or
- any event that materially questions the basis of operational authority.

Not every AI error is necessarily an incident. Classification should consider consequence, recurrence, risk and impact on the assurance basis.

---

## 19. Incident Response During Employment

Where a material incident occurs:

1. Protect people, assets and operational authority.
2. Apply the appropriate immediate control.
3. Restrict, reduce autonomy or suspend employment where necessary.
4. Preserve relevant evidence.
5. Notify responsible authorities.
6. Assess impact on the authorisation basis.
7. Investigate the cause.
8. Determine corrective and preventive action.
9. Establish whether revalidation or reauthorisation is required.
10. Record lessons learned.

Incident response should prioritise control and safety before attribution or fault analysis.

---

## 20. Change During Employment

Material changes during operational employment should not be introduced solely because they appear operationally beneficial.

Changes affecting:

- model behaviour;
- software;
- configuration;
- data;
- autonomy;
- mission;
- environment;
- human authority;
- security;
- dependencies; or
- operating procedures

should be assessed under the D-AIGAAF change-control process.

Emergency changes should follow defined emergency governance and should not create uncontrolled expansion of operational authority.

---

## 21. Operational Employment Records

Material operational activity should generate an Operational Record containing, where applicable:

- capability identifier;
- authorisation identifier;
- mission/use case;
- deployment and employment period;
- configuration;
- autonomy level;
- responsible human authority;
- significant AI outputs or actions;
- relevant human decisions;
- significant interventions;
- environmental conditions;
- degraded or disconnected periods;
- security events;
- incidents;
- restrictions;
- changes;
- outcomes; and
- relevant supporting evidence.

Records should be proportionate to consequence, autonomy and mission criticality.

---

## 22. Traceability of Consequential Actions

For actions or decisions with significant consequences, D-AIGAAF should support reconstruction of:

**AI Input/Context → AI Output/Recommendation → Human Review/Authority → Decision → Action → Outcome**

Where technically and operationally practicable, the record should establish:

- what information was available;
- what the AI produced;
- what uncertainty was communicated;
- who reviewed the output;
- who authorised the consequential action;
- what action occurred; and
- what happened afterwards.

This is essential for accountability, incident investigation and assurance learning.

---

## 23. Termination of Employment

At the end of an operational employment period, the responsible authority should confirm:

- the capability has ceased the authorised activity;
- no unintended autonomous activity continues;
- temporary restrictions or configurations are closed or documented;
- relevant data and records are preserved;
- incidents are recorded;
- outstanding issues are transferred;
- the configuration status is known; and
- lessons learned are captured where appropriate.

Termination of employment does not necessarily terminate the underlying operational authorisation.

---

## 24. Continuous Assurance Feedback

Operational employment should feed evidence back into:

- risk assessment;
- autonomy assessment;
- TEVV;
- operational environment assessment;
- human-control assessment;
- security assurance;
- data governance;
- supply-chain assurance;
- operational authorisation; and
- future capability development.

The cycle is:

**Employment → Observation → Evidence → Assessment → Learning → Control Change → Revalidation/Reauthorisation**

Operational experience should therefore become an assurance input rather than remaining isolated within operational reporting.

---

## 25. Relationship to Operational Authorisation

Operational employment shall remain within the authority established by the Operational Authorisation Record.

The following distinctions apply:

| Stage | Question |
|---|---|
| **Assurance** | Is the capability sufficiently understood and evidenced? |
| **Authorisation** | Is this use permitted? |
| **Readiness** | Is the capability currently ready? |
| **Deployment** | Has the authorised capability entered the operational setting? |
| **Employment** | How is the capability actually being used? |
| **Continuous Assurance** | Does the basis for continued use remain valid? |

Operational employment cannot expand the scope of authorisation through practice or precedent.

---

## 26. Golden Thread

Operational employment remains part of the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Readiness → Deployment → Employment → Monitoring → Change/Incident → Reauthorisation**

This provides traceability from the original mission need through actual operational use and subsequent governance decisions.

---

## 27. Governance Questions

Before and during operational employment, responsible authorities should be able to answer:

1. What authorised mission is the AI supporting?
2. What functions are permitted?
3. What autonomy level is active?
4. Who holds human decision authority?
5. What configuration is operating?
6. Is the configuration within the authorised baseline?
7. Is the environment within the authorised envelope?
8. What data and information are being relied upon?
9. Are critical dependencies available?
10. Is human supervision functioning?
11. Is the AI communicating meaningful uncertainty?
12. Are monitoring mechanisms active?
13. Has any consequential behaviour occurred outside expectations?
14. Has autonomy changed unexpectedly?
15. Are intervention and fail-safe mechanisms available?
16. Has any material incident occurred?
17. Has any material change occurred?
18. Does the capability remain within its authorisation?
19. What would require restriction or suspension?
20. Can the operational activity be reconstructed from available records?

---

## 28. Core Rule

> **Operational employment shall remain within the mission, environment, autonomy, human authority, configuration and conditions established by operational authorisation. Continuous monitoring, human authority, intervention capability and traceable operational records shall ensure that the capability does not silently move beyond the basis on which its use was authorised.**
