# Human Control Assessment

## Purpose

The D-AIGAAF Human Control Assessment provides a structured method for determining whether human authority and intervention remain **meaningful, effective and accountable** when an AI-enabled capability influences or performs consequential decisions or actions.

The assessment recognises that the presence of a human in an AI-enabled process does not, by itself, establish meaningful human control.

The central principle is:

> **Human control must be real, informed, timely, authorised, technically effective and accountable.**

---

## 1. Core Principle

D-AIGAAF distinguishes:

**AI Output ≠ Human Decision ≠ Command Authority**

An AI system may provide information, analysis or recommendations, but the authority to make consequential decisions remains with the appropriately authorised human authority unless a different level of autonomy has been explicitly authorised.

Human control must therefore be assessed in relation to:

- the decision;
- the action;
- the consequence;
- the autonomy level;
- the operational environment;
- the time available;
- the information available;
- the authority of the human;
- the ability to intervene;
- the accountability arrangements.

---

## 2. Objectives

The Human Control Assessment should determine:

- who has decision authority;
- who receives the AI output;
- whether the human understands the relevant AI output;
- whether the human understands material limitations and uncertainty;
- whether the human has sufficient information;
- whether the human has sufficient time;
- whether the human can disagree with the AI;
- whether the human can intervene;
- whether intervention is technically effective;
- whether intervention remains possible under degraded conditions;
- whether automation bias may affect judgement;
- whether responsibility and accountability are explicit;
- whether the human role remains meaningful at the authorised autonomy level.

---

## 3. Human Control Is More Than Human Presence

A human may technically be "in the loop" while exercising little meaningful control.

Examples include:

- the human receives an AI recommendation but lacks relevant information;
- the human is given insufficient time to evaluate the recommendation;
- the system makes intervention practically impossible;
- the human lacks authority to reject the action;
- the AI output is presented with unjustified confidence;
- the human does not understand system limitations;
- the human becomes dependent on automation;
- the human can intervene only after the consequential action has occurred.

Therefore:

> **Human involvement should be evaluated by the control actually exercised, not by the location of a human in the workflow.**

---

## 4. Human Control Dimensions

D-AIGAAF assesses meaningful human control across seven primary dimensions:

| Dimension | Core Question |
|---|---|
| **Information** | Does the human have sufficient information to understand the decision context and AI contribution? |
| **Authority** | Does the human have legitimate authority to approve, reject, modify or stop the action? |
| **Competence** | Does the human have sufficient operational and AI-related knowledge? |
| **Time** | Is there sufficient time for meaningful human judgement? |
| **Independence** | Can the human disagree with the AI without inappropriate pressure or automation bias? |
| **Intervention** | Can the human technically and practically intervene? |
| **Accountability** | Is responsibility for the resulting decision and action clearly assigned? |

All seven dimensions should be considered for consequential use cases.

---

## 5. Information

Meaningful control requires sufficient information.

The human should have access, as appropriate, to:

- relevant operational context;
- AI output;
- source information;
- confidence or uncertainty;
- material limitations;
- known failure modes;
- relevant dependencies;
- system status;
- environmental conditions;
- conflicting information;
- applicable boundaries;
- available alternatives.

The human should not be expected to exercise meaningful judgement from an isolated AI output.

---

## 6. Uncertainty Communication

AI systems supporting consequential decisions should communicate material uncertainty.

The human-control assessment should determine whether the system:

- distinguishes facts from predictions;
- identifies missing information;
- communicates confidence appropriately;
- identifies conflicting inputs;
- avoids unjustified certainty;
- indicates when an output is outside validated conditions;
- prompts additional human scrutiny where required.

A system that routinely presents uncertain outputs as certain can weaken meaningful human control even if a human remains formally responsible.

---

## 7. Human Authority

The assessment must identify the actual authority of each human participant.

Distinguish between:

- technical operator;
- system administrator;
- analyst;
- AI specialist;
- mission commander;
- operational authority;
- authorising authority;
- emergency authority.

A person may have technical access without having authority to make the corresponding operational decision.

Similarly, a person may hold command authority without having sufficient technical competence to assess an AI system.

D-AIGAAF therefore supports the use of the **Operational AI Advisor (OAIA)** where appropriate to bridge operational and AI expertise.

> **OAIA advises; authorised command authority decides.**

---

## 8. Human Competence

Human control is meaningful only if the responsible person has appropriate competence.

Competence may include:

### Operational Competence
Understanding:

- mission;
- environment;
- operational risks;
- decision consequences;
- applicable procedures.

### AI Competence
Understanding:

- system purpose;
- capabilities;
- limitations;
- uncertainty;
- failure modes;
- autonomy level;
- operational boundaries;
- relevant dependencies.

### Decision Competence
Ability to:

- assess AI recommendations;
- challenge AI outputs;
- consider alternatives;
- recognise automation bias;
- make decisions under uncertainty.

Competence requirements should be proportionate to consequence and autonomy.

---

## 9. Time and Decision Latency

Human control requires sufficient time to act.

Assessment should determine:

- how quickly the AI produces an output;
- how quickly the human must respond;
- how much time is required to understand the output;
- how much time is required to seek additional information;
- how much time remains to intervene;
- whether the human can stop the action before its consequences occur.

A nominal human approval step may not constitute meaningful control if the available time is too short for informed judgement.

---

## 10. Human Independence

Humans should retain the practical ability to disagree with AI.

Assess risks including:

- automation bias;
- excessive trust in system outputs;
- interface design that favours acceptance;
- repeated exposure to correct AI outputs creating over-reliance;
- institutional pressure to accept AI recommendations;
- lack of alternative information;
- lack of confidence to challenge technical systems.

The assessment should determine whether rejection or override is genuinely available.

---

## 11. Human Intervention

Where intervention is required, assess:

- whether an intervention mechanism exists;
- whether it is accessible;
- whether it works under normal conditions;
- whether it works under degraded conditions;
- how quickly it operates;
- whether intervention can prevent the consequential action;
- whether intervention can stop an action already in progress;
- what happens if the intervention mechanism fails.

An intervention mechanism that exists but cannot operate within the relevant decision timeframe should not be treated as effective control.

---

## 12. Human Override

For use cases requiring human override, define:

- who can override;
- what can be overridden;
- when override is available;
- how override is initiated;
- what happens after override;
- whether the AI can resume operation;
- who decides when autonomous operation may resume;
- how the override is recorded.

Significant human overrides should be recorded where appropriate.

The record should support later analysis of:

- why the AI recommendation was rejected;
- whether the AI was wrong;
- whether the human had better information;
- whether the system boundary was inadequate;
- whether the use case or assurance assumptions require revision.

---

## 13. Human Control Under Degraded Conditions

Human control should not be assessed only under ideal conditions.

Consider:

- communications loss;
- degraded sensors;
- poor information;
- high workload;
- fatigue;
- limited connectivity;
- rapidly changing situations;
- cyber incidents;
- electronic interference;
- loss of supporting systems;
- unexpected AI behaviour.

A human-control arrangement that works in a controlled environment may become ineffective under operational stress.

---

## 14. Human Control and Autonomy

Human control should be evaluated alongside autonomy.

| Autonomy | Typical Human Role | Control Concern |
|---|---|---|
| **A0** | Human performs decision/action | Minimal AI autonomy concern |
| **A1** | Human interprets information | Information quality and understanding |
| **A2** | Human evaluates recommendation | Automation bias and uncertainty |
| **A3** | Human explicitly authorises action | Time, authority and intervention |
| **A4** | Human supervises autonomous action | Situational awareness and effective intervention |
| **A5** | Human cannot approve each action in real time | Boundaries, predefined authority, monitoring and loss-of-control risk |

The higher the autonomy and consequence, the greater the need to demonstrate that the human-control model remains meaningful.

---

## 15. Human Control and Consequence

Human-control requirements should increase where consequences are severe.

Particular scrutiny should apply to systems that can affect:

- human life;
- physical safety;
- use of force;
- friendly-force safety;
- civilian safety;
- critical infrastructure;
- strategic decisions;
- major operational outcomes;
- irreversible actions.

A human-control arrangement suitable for low-consequence information processing may be inadequate for consequential autonomous action.

---

## 16. Human Control and Operational AI Advisor

The **Operational AI Advisor (OAIA)** provides a mechanism for bridging operational command expertise and AI technical understanding.

The OAIA may:

- explain system capabilities;
- explain limitations;
- interpret uncertainty;
- identify relevant failure modes;
- advise on autonomy;
- advise on operational boundaries;
- assess whether conditions remain within the known assurance envelope;
- identify when additional technical or assurance expertise is required;
- advise commanders when AI behaviour appears inconsistent with expectations.

The OAIA does not automatically acquire command authority by performing these functions.

> **Operational authority remains with the legally and organisationally empowered human authority.**

---

## 17. Human Decision Chain

For consequential use cases, the decision chain should be explicitly documented:

```text
Operational Situation
        ↓
Information / Sensors
        ↓
AI Processing
        ↓
AI Output / Recommendation
        ↓
Human Assessment
        ↓
Human Decision
        ↓
Authorised Action
        ↓
Operational Effect
        ↓
Record / Review
```

The assessment should identify where:

- AI can bypass human assessment;
- automation can trigger action;
- a human can intervene;
- authority changes;
- accountability becomes unclear.

---

## 18. Human Decision Accountability

The assessment should distinguish:

### Responsibility
Who is expected to perform a function?

### Authority
Who is empowered to make the decision?

### Accountability
Who is answerable for the decision or action?

These may belong to different roles but must not be ambiguous.

AI systems should not become a mechanism for obscuring who made a consequential decision.

---

## 19. Recording Human Decisions

For significant decisions, the system should support appropriate records of:

- relevant AI output;
- material uncertainty;
- human decision;
- acceptance or rejection;
- override;
- authorising person;
- time;
- relevant system configuration;
- operational conditions.

The objective is not to record every trivial interaction.

The objective is to preserve sufficient evidence to reconstruct consequential decisions and assess whether human control operated as intended.

---

## 20. AI Recommendation Rejection

A commander or authorised decision maker should be able to reject or bypass an AI recommendation.

Where appropriate, the record should capture:

- AI recommendation;
- human decision;
- reason for rejection or bypass;
- available supporting information;
- operational context;
- outcome.

The purpose is not to penalise disagreement with AI.

It is to preserve evidence for:

- accountability;
- learning;
- system improvement;
- risk reassessment;
- assurance;
- investigation of unexpected outcomes.

---

## 21. Automation Bias

Assessment should consider whether system design could cause humans to:

- accept recommendations without sufficient scrutiny;
- assume AI is more accurate than available human judgement;
- ignore contradictory information;
- defer to system outputs under workload;
- continue relying on the system after performance degradation.

Controls may include:

- appropriate interface design;
- uncertainty display;
- independent information;
- training;
- challenge procedures;
- mandatory review points;
- monitoring;
- scenario-based training.

---

## 22. Human Workload

Human control can fail when workload exceeds practical capacity.

Assess:

- number of AI outputs;
- number of simultaneous systems;
- alert frequency;
- decision frequency;
- complexity;
- fatigue;
- interruptions;
- cognitive load;
- number of systems requiring supervision;
- time available for review.

A human supervising many autonomous systems may technically remain "in control" while practically losing the ability to exercise meaningful control.

---

## 23. Human Control Failure Modes

D-AIGAAF should guard against:

- human presence being treated as sufficient;
- nominal approval replacing meaningful review;
- inadequate information;
- insufficient time;
- lack of authority;
- inadequate AI competence;
- automation bias;
- excessive workload;
- inability to override;
- ineffective intervention;
- intervention occurring too late;
- loss of communications removing human control;
- degraded conditions not being assessed;
- unclear accountability;
- AI recommendations being treated as commands;
- human disagreement not being recorded where appropriate;
- responsibility being shifted to the AI system.

---

## 24. Human Control Assessment Record

A D-AIGAAF Human Control Assessment Record should contain:

| Field | Description |
|---|---|
| Assessment ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Specific use case |
| Autonomy | Assessed/authorised autonomy |
| Decision | Consequential decision being supported |
| Action | Consequential action |
| Human Role | Human functions |
| Decision Authority | Person/role authorised to decide |
| Execution Authority | Person/system authorised to execute |
| Information | Information available to human |
| Uncertainty | Uncertainty communicated |
| Competence | Required human competence |
| Time | Available decision/intervention time |
| Independence | Ability to disagree |
| Intervention | Technical intervention capability |
| Override | Override mechanism |
| Workload | Human workload assessment |
| Environment | Conditions assessed |
| Degraded Conditions | Control under degraded conditions |
| OAIA | Relevant advisory role |
| Accountability | Accountability arrangement |
| Recording | Required records |
| Evidence | Supporting evidence |
| Limitations | Known limitations |
| Risk | Linked risk assessment |
| Status | Assessment outcome |
| Reviewer | Responsible assessor |
| Date | Assessment date |

---

## 25. Assessment Outcome

The Human Control Assessment should produce an explicit conclusion.

Possible outcomes:

### Effective
Human control is demonstrated to be meaningful under the assessed conditions.

### Effective With Conditions
Human control is effective only under specified constraints.

### Partially Effective
Some dimensions of human control are demonstrated, but material gaps remain.

### Ineffective
Human control is insufficient for the proposed autonomy or consequence.

### Not Assessable
Evidence is insufficient to determine whether meaningful human control exists.

### Restricted
A lower autonomy level or narrower operational envelope is required.

---

## 26. Evidence Requirements

Human control should be supported by evidence such as:

- human factors testing;
- usability testing;
- operator trials;
- commander/decision-maker exercises;
- workload assessment;
- intervention testing;
- override testing;
- degraded-condition testing;
- communications-loss testing;
- automation-bias assessment;
- training evaluation;
- scenario-based exercises;
- operational trials;
- incident and near-miss analysis.

Evidence should demonstrate not merely that a human can theoretically intervene, but that the human can exercise meaningful control under relevant conditions.

---

## 27. Continuous Monitoring

Human control should be monitored during operational employment.

Monitor for:

- increased workload;
- delayed intervention;
- repeated uncritical acceptance of AI outputs;
- increased override frequency;
- declining operator confidence;
- declining system trustworthiness;
- changes in staffing or competence;
- changes in decision tempo;
- degraded communications;
- changes in operating conditions;
- unexpected AI behaviour.

Material changes should trigger reassessment.

---

## 28. Reassessment Triggers

Reassessment should be considered following:

- changes in autonomy;
- model or system updates;
- changes in interface design;
- changes in mission;
- changes in use case;
- changes in operating environment;
- changes in decision tempo;
- changes in human staffing;
- changes in training or competence;
- incidents;
- unexpected behaviour;
- increased workload;
- security incidents;
- changes in authority arrangements;
- changes in legal or policy requirements.

Previous evidence should not automatically be assumed to remain valid after material changes.

---

## 29. Relationship to Risk and Assurance

Human control assessment feeds directly into risk:

**Autonomy + Consequence + Human Control → Risk**

It also informs assurance:

**Human-Control Claim → Test → Evidence → Assurance**

And operational authorisation:

**Assured Human Control → Authorised Autonomy → Operational Employment**

A material weakness in human control may require:

- additional controls;
- reduced autonomy;
- additional training;
- increased monitoring;
- restricted employment;
- suspension;
- revalidation;
- reauthorisation.

---

## 30. Golden Thread

Human control should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy → Human Control → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

The assessment should make it possible to answer:

> **Who was authorised to decide, what information did they have, what did the AI contribute, could they meaningfully disagree or intervene, and who remained accountable for the resulting action?**

---

## 31. Core Rules

1. **Human presence does not automatically constitute meaningful human control.**
2. **Human control must be informed, authorised, competent and timely.**
3. **The human must be able to disagree with AI where human judgement is required.**
4. **Intervention must be technically and operationally effective.**
5. **Human control must be assessed under degraded and adversarial conditions where relevant.**
6. **Automation bias must be considered.**
7. **Human workload must be assessed.**
8. **Decision authority and technical access are not the same thing.**
9. **AI recommendation is not command authority.**
10. **Consequential human decisions should be appropriately traceable.**
11. **Significant overrides should be recorded where appropriate.**
12. **OAIA provides advice; authorised human authority decides.**
13. **Human-control evidence must support the claimed autonomy level.**
14. **Material changes require reassessment.**
15. **Loss of meaningful human control may require reduced autonomy, restriction or suspension.**

---

## 32. Summary Model

```text
IDENTIFY DECISION
        ↓
IDENTIFY AI CONTRIBUTION
        ↓
IDENTIFY HUMAN ROLE
        ↓
ASSESS INFORMATION
        ↓
ASSESS AUTHORITY
        ↓
ASSESS COMPETENCE
        ↓
ASSESS TIME
        ↓
ASSESS INDEPENDENCE
        ↓
ASSESS INTERVENTION
        ↓
ASSESS ACCOUNTABILITY
        ↓
ASSESS WORKLOAD + AUTOMATION BIAS
        ↓
TEST UNDER RELEVANT CONDITIONS
        ↓
GENERATE EVIDENCE
        ↓
DETERMINE HUMAN-CONTROL POSITION
        ↓
LINK TO RISK + ASSURANCE
        ↓
INFORM AUTONOMY / AUTHORISATION
        ↓
MONITOR CONTINUOUSLY
```

The objective of the Human Control Assessment is not to require human intervention for every AI activity.

It is to ensure that **where human authority is relied upon, the human actually possesses the information, authority, competence, time, independence and means necessary to exercise meaningful control.**
