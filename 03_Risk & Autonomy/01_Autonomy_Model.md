# Autonomy Model

## Purpose

The D-AIGAAF Autonomy Model provides a common framework for defining, assessing, controlling, assuring and authorising the degree of decision-making and action that an AI-enabled capability may perform.

**Autonomy is not an inherent permission of technology.** Technical capability and operational authority are separate questions.

Autonomy must therefore be explicitly defined, assessed against mission consequence and operational context, bounded by authorised conditions, supported by appropriate human authority, and continuously monitored.

---

## 1. Core Principle

> **Autonomy must be explicitly defined, matched to consequence, bounded by authority, and supported by evidence.**

A system capable of performing an action does not automatically have authority to perform that action.

The governing relationship is:

**Technical Capability → Tested Autonomy → Assured Autonomy → Authorised Autonomy**

Only the final stage establishes permitted operational employment.

---

## 2. What Autonomy Means in D-AIGAAF

For D-AIGAAF, autonomy describes the degree to which an AI-enabled capability can:

- observe or process information;
- generate assessments or recommendations;
- initiate decisions;
- select among actions;
- execute actions;
- continue operating without immediate human intervention;
- adapt its behaviour within defined limits; or
- perform consequential actions independently.

Autonomy should be assessed at the **system and mission level**, not solely at the model level.

A model may generate an output autonomously while the wider system remains subject to human authorisation. Conversely, an apparently simple system can create significant autonomy if its output directly triggers consequential action.

---

## 3. Working Autonomy Scale

D-AIGAAF uses the following working construct:

| Level | Name | General Description | Human Role |
|---|---|---|---|
| **A0** | No Meaningful AI Decision | AI has no meaningful role in a decision or action. | Human performs the decision/action. |
| **A1** | Information / Observation | AI detects, classifies, organises or presents information without independently recommending a consequential action. | Human interprets and decides. |
| **A2** | Analysis / Recommendation | AI analyses information and provides an assessment, prediction or recommendation. | Human evaluates and decides. |
| **A3** | Human-Authorised Action | AI may formulate or initiate a proposed consequential action, but execution requires explicit human authorisation. | Human provides affirmative authorisation. |
| **A4** | Supervised Autonomous Action | AI executes predefined actions within an authorised envelope while subject to human supervision and intervention. | Human supervises and retains defined intervention authority. |
| **A5** | Independent Consequential Autonomy | AI can independently make and execute consequential decisions or actions without immediate human authorisation. | Human authority is exercised through predefined boundaries, oversight and governance rather than case-by-case approval. |

This scale is a **D-AIGAAF working construct**, not a claim that these labels are universally accepted terminology. It should be mapped to applicable national, defence, legal, doctrinal and international terminology before operational adoption.

---

## 4. Autonomy Is Multi-Dimensional

A single autonomy level may not adequately describe a complex AI-enabled capability.

Assessment should consider at least:

### 4.1 Decision Autonomy
The degree to which AI can determine what decision should be made.

### 4.2 Action Autonomy
The degree to which AI can execute an action without human intervention.

### 4.3 Temporal Autonomy
How long the system can continue operating before requiring human review, confirmation or intervention.

### 4.4 Scope Autonomy
The range of objects, targets, users, systems, environments or actions over which the system can operate.

### 4.5 Adaptation Autonomy
The degree to which the system can modify its behaviour based on changing inputs or conditions.

### 4.6 Escalation Autonomy
Whether the system can move from lower-consequence activities toward higher-consequence decisions or actions.

### 4.7 Recovery Autonomy
The degree to which the system can detect and respond to failures, degraded conditions or abnormal behaviour without human direction.

### 4.8 Authority Autonomy
The practical ability of the system to cause an outcome without requiring additional human permission.

**Technical autonomy and operational authority are not equivalent.**

---

## 5. Autonomy and Human Authority

The core distinction is:

**AI Output ≠ Human Decision ≠ Command Authority**

An AI system may detect an object, assess a situation, recommend an action, select an option, initiate an action, or execute a predefined action.

None of these capabilities, by themselves, establish legal, organisational or command authority.

Human authority must remain explicitly defined.

For consequential decisions, D-AIGAAF should identify:

- who receives the AI output;
- who assesses it;
- who is authorised to decide;
- who is authorised to execute;
- what level of human confirmation is required;
- what information must be available to the human decision maker;
- what override authority exists;
- what happens if the human decision maker disagrees;
- what happens if the human is unavailable;
- how the decision and relevant AI contribution are recorded.

---

## 6. Meaningful Human Control

The presence of a human somewhere in the process does not automatically constitute meaningful human control.

Meaningful human control should consider whether the authorised human has:

1. **Information** — sufficient information to understand the relevant situation and AI output;
2. **Authority** — legitimate authority to approve, reject, modify or stop the action;
3. **Capability** — sufficient competence to understand the system and its limitations;
4. **Time** — sufficient time to exercise meaningful judgement;
5. **Independence** — ability to disagree with the AI recommendation;
6. **Intervention** — a technically viable means of intervention where required;
7. **Accountability** — clear responsibility for the resulting decision or action.

Human control that exists only formally but cannot operate effectively should not be treated as meaningful control.

---

## 7. Autonomy Must Be Matched to Consequence

The higher the potential consequence of an AI-enabled action, the stronger the justification, evidence, controls and human authority required for its autonomy.

Particular scrutiny should apply where autonomy could affect:

- human life;
- physical safety;
- use of force;
- critical infrastructure;
- strategic or operational command decisions;
- essential services;
- sensitive information;
- friendly-force safety;
- civilian safety;
- significant property or environmental consequences;
- irreversible or difficult-to-reverse outcomes.

A low-risk information-processing function may require relatively limited autonomy assurance.

A system capable of independently producing consequential physical effects requires substantially greater assurance and authority controls.

---

## 8. Autonomy and Operational Environment

Autonomy cannot be assessed independently of the environment in which it will operate.

Relevant conditions include:

- normal operating conditions;
- degraded communications;
- communications denial;
- degraded or conflicting sensor inputs;
- incomplete or corrupted information;
- adversarial conditions;
- electronic interference;
- cyber compromise;
- navigation degradation;
- unexpected environmental conditions;
- high human workload;
- rapidly changing situations;
- loss of supporting systems;
- loss of external services;
- operating without network connectivity.

An autonomy level demonstrated in a controlled environment should not automatically be assumed to remain safe or effective in a substantially different operational environment.

---

## 9. Autonomy and Loss of Control

Higher autonomy increases the importance of understanding how control can be lost.

Potential loss-of-control conditions include:

- unexpected system behaviour;
- incorrect or manipulated inputs;
- model or software failure;
- sensor failure;
- communication loss;
- corrupted configuration;
- compromised dependencies;
- unsafe adaptation;
- automation loops;
- failure of human intervention;
- inability to stop execution;
- autonomous escalation beyond intended boundaries.

D-AIGAAF treats **loss of control as an explicit risk dimension**, rather than assuming that human presence alone mitigates it.

---

## 10. Autonomy Boundaries

Every authorised autonomy level should have defined boundaries.

These may include:

- permitted missions;
- permitted use cases;
- geographic limits;
- environmental conditions;
- data sources;
- sensor requirements;
- communication requirements;
- permitted actions;
- prohibited actions;
- time limits;
- decision thresholds;
- human intervention requirements;
- system configuration;
- dependency requirements;
- security conditions;
- fail-safe conditions;
- escalation limits.

The system should not be treated as authorised merely because it remains technically capable of operating outside these boundaries.

---

## 11. Autonomy Transitions

AI systems may change autonomy during operation.

Examples include:

- A2 analysis moving to A3 human-authorised action;
- A3 moving to A4 under predefined conditions;
- A4 automatically reducing to A2 during degraded conditions;
- transition to a safe state following a fault;
- temporary reduction of autonomy after threat detection.

Each transition should have:

- a defined trigger;
- a defined authority;
- a defined operational condition;
- a defined maximum autonomy level;
- a defined human-control requirement;
- a defined response if the transition fails;
- appropriate logging.

> **Autonomy should never silently increase.**

---

## 12. Fail-Safe and Controlled Degradation

Fail-safe mechanisms should be designed as a last-resort protective measure.

Where an AI capability behaves unexpectedly or conditions exceed its authorised envelope, possible responses include:

1. warning;
2. increased human scrutiny;
3. reduced autonomy;
4. controlled degradation;
5. isolation;
6. transfer to human control;
7. suspension;
8. fail-safe action;
9. emergency protective action.

The appropriate response depends on mission consequence, timing and operational circumstances.

Where delay could create unacceptable harm, pre-authorised emergency procedures may permit immediate protective action.

---

## 13. Autonomy Evidence

An autonomy claim should be supported by evidence demonstrating that the system behaves as expected at the claimed level of autonomy.

Evidence should address, as applicable:

- decision performance;
- action performance;
- reliability;
- robustness;
- uncertainty;
- adversarial resilience;
- human-AI interaction;
- intervention effectiveness;
- boundary adherence;
- failure behaviour;
- recovery;
- communication loss;
- degraded conditions;
- security;
- configuration integrity;
- dependency failures;
- mission effectiveness.

Evidence should be representative of the intended operational environment.

---

## 14. Autonomy and Assurance

The assurance burden should increase with:

- higher autonomy;
- greater consequence;
- greater mission criticality;
- greater uncertainty;
- greater environmental complexity;
- greater adversarial exposure;
- reduced human intervention;
- increased duration of independent operation;
- increased scope of action;
- reduced reversibility of outcomes.

> **Greater autonomous authority requires stronger evidence that the system will remain within its intended operational envelope.**

---

## 15. Autonomy and Configuration

Autonomy depends on more than the underlying model.

Relevant configuration elements may include:

- model version;
- system software;
- prompts or control logic where material;
- rules and policies;
- sensors;
- data pipelines;
- decision logic;
- interfaces;
- connected systems;
- external services;
- safety controls;
- security controls;
- human-machine interfaces.

A change to any of these may alter effective autonomy.

Therefore:

**Configuration Change → Behaviour Assessment → Change Classification → Revalidation/TEVV as Required → Reauthorisation Where Required**

---

## 16. Autonomy and AI Updates

An update should not be assumed to preserve the previous autonomy authorisation.

Changes should be assessed according to their effect on system behaviour.

A change may be considered lower significance where evidence demonstrates that it does not materially affect:

- decision behaviour;
- action behaviour;
- operational boundaries;
- safety;
- security;
- human control;
- autonomy;
- mission performance.

Changes affecting model behaviour, hidden/model layers, decision logic, autonomy, safety controls or consequential outputs should trigger appropriate revalidation and potentially reauthorisation.

---

## 17. Autonomy Classification Questions

Before assigning an autonomy level, assess:

1. What decisions can the AI influence?
2. What actions can the AI initiate?
3. What actions can the AI execute?
4. Can the AI select among alternatives?
5. Can it act without immediate human approval?
6. How long can it operate independently?
7. What is the maximum scope of its action?
8. Can it adapt its behaviour?
9. Can it escalate its own authority?
10. Can a human intervene?
11. Is the intervention technically effective?
12. Is sufficient time available for intervention?
13. What happens if communications are lost?
14. What happens if sensors or data become unreliable?
15. What happens if the system behaves unexpectedly?
16. What happens if the system is compromised?
17. What happens if the authorised human is unavailable?
18. What is the worst credible consequence of autonomous behaviour?
19. What evidence supports the claimed autonomy?
20. Who authorised that autonomy?

---

## 18. Autonomy Decision Logic

```text
Identify AI Capability
        ↓
Identify Decisions and Actions
        ↓
Identify Human Role
        ↓
Determine Technical Autonomy
        ↓
Assess Consequence and Mission Criticality
        ↓
Assess Operational Environment
        ↓
Assess Human Control
        ↓
Assess Loss-of-Control Risk
        ↓
Define Autonomy Boundaries
        ↓
Determine Required Assurance
        ↓
Generate Evidence
        ↓
Determine Assured Autonomy
        ↓
Obtain Appropriate Operational Authority
        ↓
Authorise Specific Autonomy
        ↓
Monitor and Reassess
```

---

## 19. Autonomy Is Not Permanent

An authorised autonomy level should remain valid only while its underlying assumptions, evidence, configuration, environment and authority remain valid.

Reassessment should be considered following:

- material system changes;
- model updates;
- changes in mission;
- changes in use case;
- changes in operational environment;
- changes in threat conditions;
- changes in human staffing or competence;
- changes in dependencies;
- incidents;
- unexpected behaviour;
- evidence degradation;
- security compromise;
- changes in law, policy or doctrine;
- loss of required safeguards.

> **Previous authorisation does not automatically authorise future behaviour.**

---

## 20. Relationship to the D-AIGAAF Golden Thread

Autonomy should remain traceable through the D-AIGAAF Golden Thread:

**Mission Need → Use Case → Risk → Autonomy → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

This ensures that autonomy is connected to:

- why the capability exists;
- what it is permitted to do;
- what could go wrong;
- what evidence supports its use;
- who is accountable;
- where it may operate;
- when its authority must be reconsidered.

---

## 21. Key Failure Modes

D-AIGAAF should guard against:

- treating technical capability as operational authority;
- assuming human presence equals meaningful human control;
- assigning autonomy without consequence assessment;
- using a single autonomy label to hide important differences;
- allowing silent autonomy escalation;
- assuming autonomy remains safe across environments;
- ignoring communications-denied conditions;
- assuming fail-safe mechanisms always work;
- treating model-level performance as sufficient autonomy evidence;
- allowing updates without behaviour assessment;
- failing to define intervention authority;
- allowing AI to determine or expand its own authority;
- treating previous authorisation as permanent;
- failing to record consequential autonomous actions;
- confusing supervision with accountability.

---

## 22. Core Rule

> **AI may be technically capable of acting beyond its authorised autonomy. That capability does not constitute authority.**

D-AIGAAF therefore separates:

**Capability → Autonomy → Assurance → Authority → Employment**

The objective is not to maximise or minimise autonomy.

The objective is to ensure that **the level of autonomy employed is appropriate to the mission, consequence, environment, risk, human authority and available evidence.**
