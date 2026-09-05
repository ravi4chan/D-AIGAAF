# Loss of Control

## Purpose

The D-AIGAAF Loss of Control framework defines how to identify, assess, prevent, detect, contain and respond to situations in which an AI-enabled capability no longer behaves within its intended, assured or authorised operational boundaries.

Loss of control is treated as a distinct risk because an AI capability may remain technically functional while becoming operationally unsafe, unreliable, compromised or outside the authority granted to it.

The central principle is:

> **An AI capability must remain within its authorised operational envelope, and loss of control must have predefined detection, containment and recovery mechanisms.**

---

## 1. What Is Loss of Control?

For D-AIGAAF, loss of control occurs when an AI-enabled capability:

- behaves outside its intended behaviour;
- exceeds its authorised autonomy;
- operates outside its authorised boundaries;
- cannot be effectively directed or stopped by authorised humans;
- produces consequential actions without required authority;
- continues operating when required safeguards have failed;
- becomes materially compromised;
- behaves unpredictably in a consequential context;
- loses the ability to transition to a safe or controlled state.

Loss of control may be:

- technical;
- operational;
- human;
- environmental;
- security-related;
- governance-related;
- or a combination of these.

---

## 2. Loss of Control Is Not the Same as System Failure

A system can fail without losing control.

For example:

**System Failure**
→ system stops operating as designed.

**Loss of Control**
→ system continues operating, but its behaviour can no longer be reliably constrained, understood, directed or stopped within the authorised framework.

A loss-of-control condition may therefore be more consequential than ordinary technical failure.

---

## 3. Core Control Chain

D-AIGAAF uses the following control chain:

```text
Prevent
  ↓
Detect
  ↓
Assess
  ↓
Contain
  ↓
Reduce Autonomy
  ↓
Restore Human Control
  ↓
Safe State / Fail-Safe
  ↓
Recover
  ↓
Reassess
  ↓
Reauthorise
```

Not every incident will require every stage.

The response should be proportionate to consequence, urgency and operational conditions.

---

## 4. Sources of Loss of Control

Loss of control can originate from multiple sources.

### 4.1 Technical

- software failure;
- model failure;
- unexpected model behaviour;
- faulty decision logic;
- interface failure;
- configuration error;
- actuator failure;
- integration failure.

### 4.2 Information

- corrupted data;
- manipulated inputs;
- stale information;
- contradictory information;
- sensor failure;
- spoofed information;
- incomplete information.

### 4.3 Communications

- communications loss;
- intermittent connectivity;
- delayed communications;
- compromised communications;
- loss of command links.

### 4.4 Human

- operator error;
- misunderstanding;
- excessive workload;
- fatigue;
- inadequate competence;
- automation bias;
- delayed intervention;
- unclear authority.

### 4.5 Security

- cyber compromise;
- adversarial manipulation;
- malicious instructions;
- compromised dependencies;
- insider threat;
- supply-chain compromise.

### 4.6 Operational

- unexpected environmental conditions;
- mission change;
- rapid change in circumstances;
- operation outside validated conditions;
- dependency loss;
- unexpected interaction with another system.

### 4.7 Governance

- unclear authority;
- unauthorised use;
- authority drift;
- undocumented configuration;
- expired authorisation;
- failure to act on known risk.

---

## 5. Levels of Loss of Control

A working classification may be used to distinguish severity.

### L1 — Control Degradation

Human or system control remains effective but is becoming less reliable.

Examples:

- increased uncertainty;
- declining performance;
- degraded communications;
- increased operator workload.

### L2 — Material Control Impairment

Normal control mechanisms are impaired and additional controls are required.

Examples:

- unreliable human intervention;
- significant sensor degradation;
- loss of important dependencies;
- abnormal AI behaviour.

### L3 — Loss of Effective Control

The authorised human cannot reliably direct, constrain or stop the system as required.

Examples:

- autonomous behaviour outside expected conditions;
- failed intervention mechanism;
- unexpected consequential actions.

### L4 — Critical Loss of Control

The system can create severe or potentially catastrophic consequences while effective control is unavailable.

Examples may include:

- uncontrolled consequential action;
- persistent operation outside authorised boundaries;
- compromised system with consequential authority;
- inability to reach a safe state.

These levels are a working D-AIGAAF construct and should be calibrated to the specific capability and mission.

---

## 6. Control State

Operational systems should have a defined control state.

A possible state model is:

**Controlled → Degraded → Restricted → Emergency → Safe State → Recovered → Revalidated → Reauthorised**

The exact state model may vary by capability.

The important requirement is that each state has defined:

- permitted actions;
- autonomy;
- human authority;
- monitoring;
- transition conditions;
- response requirements.

---

## 7. Detection

Loss of control should be detected through multiple mechanisms where appropriate.

Detection may include:

- behavioural monitoring;
- boundary monitoring;
- anomaly detection;
- system-health monitoring;
- sensor integrity checks;
- data integrity checks;
- configuration monitoring;
- communications monitoring;
- human observation;
- independent verification;
- security monitoring;
- performance monitoring.

Detection mechanisms should be tested under representative conditions.

---

## 8. Indicators of Loss of Control

Potential indicators include:

- unexpected decisions;
- unexpected actions;
- repeated boundary violations;
- unexplained changes in behaviour;
- unexplained changes in output distribution;
- inability to explain material system state;
- unexpected autonomy increase;
- failure to respond to authorised intervention;
- abnormal interaction with connected systems;
- continued operation after a stop command;
- failure to enter a defined safe state;
- significant divergence from validated behaviour;
- compromised configuration;
- security anomalies.

A single indicator may not prove loss of control, but it may trigger increased scrutiny or reduced autonomy.

---

## 9. Detection Thresholds

Each capability should define appropriate thresholds for escalation.

Examples include:

```text
Normal
   ↓
Warning Threshold
   ↓
Enhanced Monitoring
   ↓
Restriction Threshold
   ↓
Reduced Autonomy
   ↓
Suspension / Safe State Threshold
```

Thresholds should be based on:

- consequence;
- mission criticality;
- autonomy;
- system behaviour;
- operational environment;
- available intervention time.

Higher-consequence systems should generally have less tolerance for undetected or unexplained abnormal behaviour.

---

## 10. Loss of Human Control

Human control may be lost even when the system itself continues functioning.

Examples include:

- human cannot understand the output in time;
- human cannot communicate with the system;
- human cannot override the action;
- intervention is too slow;
- the system acts faster than the human decision cycle;
- human authority is unclear;
- the human is overloaded;
- the system provides misleading confidence;
- the human is unable to distinguish system error from genuine information.

Human-control degradation should therefore be treated as a potential loss-of-control condition.

---

## 11. Autonomous Escalation

A particularly important risk is unintended escalation of autonomy.

The system should not independently:

- expand its mission;
- expand its geographic scope;
- expand its target or object set;
- increase its decision authority;
- increase its action authority;
- remove human approval requirements;
- disable safeguards;
- alter its own operating boundaries.

> **AI must not self-expand its authority.**

Any material increase in autonomy must have a defined authority basis and control mechanism.

---

## 12. Boundary Violation

A capability may lose operational control by crossing an authorised boundary.

Relevant boundaries include:

- mission;
- use case;
- geography;
- environment;
- data;
- communications;
- autonomy;
- time;
- configuration;
- dependency;
- security;
- human authority;
- permitted actions.

Boundary violations should generate an appropriate response based on consequence.

Possible responses include:

- warning;
- human review;
- reduced autonomy;
- controlled degradation;
- restriction;
- suspension;
- fail-safe;
- emergency protective action.

---

## 13. Communications Loss

Communications loss is particularly important for systems capable of autonomous operation.

Assessment should determine:

- whether autonomy continues;
- how long autonomy may continue;
- what actions remain permitted;
- whether autonomy automatically reduces;
- whether the system can return to human control;
- what happens if communications cannot be restored;
- whether the system transitions to a safe state.

A system should not rely on an assumption that communications will always remain available if the mission can encounter communications denial or disruption.

---

## 14. Information Loss or Manipulation

Loss of reliable information can create loss of control.

Examples include:

- sensor failure;
- spoofing;
- manipulated data;
- conflicting information;
- missing information;
- stale information;
- corrupted data.

Where information integrity becomes uncertain, the capability should have defined responses.

These may include:

- increased scrutiny;
- reduced autonomy;
- use of independent information;
- controlled degradation;
- suspension;
- safe state.

---

## 15. Adversarial Loss of Control

An adversary may attempt to cause loss of control by manipulating:

- inputs;
- sensors;
- communications;
- data;
- software;
- models;
- dependencies;
- operators;
- system interfaces.

Assessment should consider whether adversarial activity can cause:

- unsafe outputs;
- incorrect decisions;
- unauthorised actions;
- autonomy escalation;
- loss of human control;
- failure of safety mechanisms.

Adversarial conditions should form part of TEVV for relevant capabilities.

---

## 16. AI Turning Against Own Forces

D-AIGAAF should explicitly consider the possibility of harmful AI behaviour **without requiring an external attacker**.

The risk assessment should consider whether unexpected system behaviour could:

- misidentify friendly entities;
- misclassify information;
- act against authorised interests;
- interact dangerously with connected systems;
- misuse available permissions;
- trigger unintended actions;
- create cascading effects;
- compromise own infrastructure;
- continue harmful behaviour after human intervention is attempted.

This is a loss-of-control and system-assurance question, not only a cyber-security question.

---

## 17. Response Hierarchy

Where abnormal behaviour is detected, the response should generally seek to preserve control while avoiding unnecessary escalation.

A possible hierarchy is:

1. **Observe**
2. **Warn**
3. **Increase human scrutiny**
4. **Verify independently**
5. **Reduce autonomy**
6. **Restrict operation**
7. **Transfer to human control**
8. **Isolate**
9. **Suspend**
10. **Fail-safe**
11. **Emergency protective action**

The appropriate response depends on the time available, consequence and operational conditions.

---

## 18. Fail-Safe as Last Resort

Fail-safe should be treated as a last-resort protective mechanism.

Before reaching fail-safe, where time and conditions permit, the issue may be assessed through an escalation path such as:

**Developer / Technical Support → AI System Manager → OAIA → Operational Command Authority**

The purpose is to determine the appropriate technical and operational response.

However:

> **Where delay could create unacceptable harm, pre-authorised emergency procedures should permit immediate protective action.**

Emergency action should be followed by appropriate reporting, investigation and reassessment.

---

## 19. Safe State

A safe state is a predefined system condition intended to minimise unacceptable consequences when normal operation cannot safely continue.

A safe state may involve:

- cessation of consequential actions;
- reduced autonomy;
- controlled degradation;
- isolation;
- transfer to human control;
- termination of selected functions;
- preservation of evidence.

The safe state must be defined for the particular system.

There is no universal safe state applicable to every AI-enabled capability.

---

## 20. Recovery

Recovery should not mean simply restarting the system.

Recovery should include, where appropriate:

1. establish control;
2. determine system state;
3. preserve relevant evidence;
4. identify cause or contributing factors;
5. verify configuration;
6. assess security;
7. assess dependencies;
8. assess mission conditions;
9. reassess risk;
10. determine whether revalidation is required;
11. determine whether authority remains valid;
12. obtain reauthorisation where required.

> **Technical recovery does not automatically restore operational authority.**

---

## 21. Post-Incident Assessment

Following a significant loss-of-control event, assess:

- what happened;
- when it happened;
- what the system did;
- what the human did;
- what the AI contributed;
- what information was available;
- what authority existed;
- what controls were active;
- which controls failed;
- whether boundaries were violated;
- whether assumptions remained valid;
- whether dependencies failed;
- whether security was compromised;
- what consequences occurred;
- whether the behaviour was foreseeable;
- whether existing evidence remains valid.

---

## 22. Loss-of-Control Record

A D-AIGAAF Loss-of-Control Record should contain:

| Field | Description |
|---|---|
| Incident ID | Unique identifier |
| Capability | AI-enabled capability |
| Mission | Supported mission |
| Use Case | Relevant use case |
| Time | Event time |
| Location / Context | Operational context |
| Autonomy | Active autonomy level |
| Human Control | Human-control state |
| Trigger | Initial trigger |
| Indicators | Detected indicators |
| Control Level | L1–L4 |
| Boundary | Relevant boundary |
| System State | State before/during event |
| AI Behaviour | Observed AI behaviour |
| Human Action | Human response |
| Automated Action | System action |
| Communications | Communications status |
| Information | Information condition |
| Dependencies | Dependency condition |
| Security | Security status |
| Response | Actions taken |
| Fail-Safe | Whether activated |
| Consequence | Actual/potential consequence |
| Evidence | Preserved evidence |
| Root / Contributing Causes | Findings |
| Controls Failed | Failed controls |
| Corrective Actions | Required improvements |
| Risk Impact | Updated risk position |
| Assurance Impact | Updated assurance position |
| Authority Impact | Authorisation implications |
| Revalidation | Required activity |
| Reauthorisation | Required activity |
| Status | Current status |

---

## 23. Escalation Authority

Authority for responding to loss of control should be explicitly defined before operational employment.

This may include authority to:

- reduce autonomy;
- restrict operation;
- transfer control;
- isolate systems;
- suspend capability;
- activate fail-safe;
- initiate emergency protective action;
- terminate a mission-specific function.

Emergency authority should be pre-defined wherever practicable.

---

## 24. Operational AI Advisor Role

The OAIA may support loss-of-control response by:

- interpreting AI behaviour;
- identifying likely technical limitations;
- assessing whether behaviour is within the known envelope;
- advising on autonomy reduction;
- advising on system limitations;
- supporting commanders during technical uncertainty;
- identifying whether additional technical expertise is required;
- supporting post-event analysis.

The OAIA does not replace operational command authority.

**OAIA advises; authorised operational authority decides.**

Emergency procedures may permit immediate protective action where delay creates unacceptable risk.

---

## 25. Monitoring for Loss of Control

Continuous monitoring should consider:

- behavioural anomalies;
- boundary violations;
- autonomy changes;
- human-control degradation;
- communications status;
- information integrity;
- dependency health;
- security indicators;
- performance degradation;
- unexpected system interactions;
- fail-safe activation.

Monitoring should be proportionate to consequence and autonomy.

---

## 26. Testing Loss of Control

Relevant systems should be tested for:

- failure detection;
- abnormal behaviour detection;
- intervention;
- override;
- autonomy reduction;
- communications loss;
- sensor degradation;
- information manipulation;
- dependency loss;
- boundary violation;
- fail-safe activation;
- safe-state transition;
- recovery;
- evidence preservation.

Testing should occur under conditions representative of intended operational use.

---

## 27. Assurance Requirements

Loss-of-control assurance should establish:

- what failure conditions have been considered;
- what loss-of-control conditions have been tested;
- whether intervention works;
- whether safeguards can fail;
- whether the system can reach a safe state;
- whether humans can regain control;
- how quickly control can be restored;
- what evidence supports these claims.

For high-consequence autonomy, evidence should include adversarial and degraded-condition testing where relevant.

---

## 28. Relationship to Risk

Loss of control should be explicitly represented in the risk assessment.

The relationship is:

**Autonomy + Consequence + Human Control + Boundary Exposure → Loss-of-Control Risk**

Controls may include:

- constrained autonomy;
- least authority;
- human intervention;
- monitoring;
- independent verification;
- boundary enforcement;
- fail-safe;
- controlled degradation;
- isolation;
- suspension.

Residual loss-of-control risk must be considered before operational authorisation.

---

## 29. Relationship to Operational Authorisation

Operational authorisation should define:

- maximum autonomy;
- operational boundaries;
- human authority;
- intervention requirements;
- monitoring;
- loss-of-control triggers;
- response procedures;
- suspension conditions;
- fail-safe conditions;
- reauthorisation requirements.

A capability should not receive operational authority without an adequate understanding of how control could be lost and how that condition will be managed.

---

## 30. Reauthorisation After Loss of Control

A significant loss-of-control event should trigger review of:

- risk;
- autonomy;
- human control;
- controls;
- evidence;
- operational boundaries;
- configuration;
- dependencies;
- security;
- assumptions;
- authorisation conditions.

Depending on severity, the capability may be:

**Continued → Restricted → Suspended → Revalidated → Reauthorised**

Previous authorisation should not be assumed to remain valid where the event materially changes the assurance position.

---

## 31. Failure Modes

D-AIGAAF should guard against:

- treating loss of control as ordinary system failure;
- assuming humans can always intervene;
- assuming communications will always be available;
- relying on a single control mechanism;
- allowing silent autonomy escalation;
- failing to define safe states;
- treating fail-safe as a substitute for assurance;
- restarting a system without reassessment;
- restoring technical operation without restoring authority;
- failing to preserve evidence;
- ignoring adversarial causes;
- ignoring non-adversarial harmful behaviour;
- failing to assess cascading effects;
- allowing emergency procedures to become normal operating procedures;
- failing to reassess after a significant event.

---

## 32. Golden Thread

Loss of control should remain traceable through:

**Mission Need → Use Case → Risk → Autonomy → Human Control → Boundaries → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Loss of Control → Incident → Reassessment → Revalidation → Reauthorisation**

This provides a traceable link between:

- the original mission need;
- the autonomy granted;
- the controls established;
- the evidence supporting those controls;
- the event that caused control degradation or loss;
- the corrective action;
- the resulting authority decision.

---

## 33. Core Rules

1. **Loss of control is a distinct operational risk.**
2. **A functioning system can still be outside human or operational control.**
3. **Loss-of-control conditions must be identified before operational employment.**
4. **Human intervention must be technically and operationally effective.**
5. **AI must not expand its own authority.**
6. **Boundary violations require predefined responses.**
7. **Communications loss and information degradation must be assessed where relevant.**
8. **Adversarial and non-adversarial loss-of-control scenarios must be considered.**
9. **Fail-safe is a last-resort protective mechanism.**
10. **Emergency protective action may be pre-authorised where delay could create unacceptable harm.**
11. **Technical recovery does not automatically restore operational authority.**
12. **Significant loss-of-control events should trigger risk and assurance reassessment.**
13. **Relevant evidence must be preserved after incidents.**
14. **Previous authorisation does not automatically survive a material loss-of-control event.**
15. **Operational authority remains with the appropriately authorised human authority.**

---

## 34. Summary Model

```text
NORMAL OPERATION
       ↓
DETECTION OF ABNORMAL CONDITION
       ↓
ASSESS CONTROL STATE
       ↓
WARNING / ENHANCED SCRUTINY
       ↓
VERIFY
       ↓
REDUCE AUTONOMY
       ↓
RESTORE HUMAN CONTROL
       ↓
RESTRICT / ISOLATE / SUSPEND
       ↓
FAIL-SAFE / EMERGENCY PROTECTIVE ACTION
       ↓
PRESERVE EVIDENCE
       ↓
INVESTIGATE
       ↓
REASSESS RISK
       ↓
REASSESS AUTONOMY + HUMAN CONTROL
       ↓
REVALIDATE / TEVV AS REQUIRED
       ↓
REAUTHORISE OR RETIRE
```

The objective is not to assume that loss of control can be eliminated.

The objective is to ensure that **loss of control is anticipated, detectable, containable, recoverable where possible, and governed by explicit human authority.**
