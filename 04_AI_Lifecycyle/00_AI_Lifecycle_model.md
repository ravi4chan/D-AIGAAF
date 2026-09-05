# AI Lifecycle Model

## Summary

The AI Lifecycle Model defines the controlled lifecycle through which a defence AI capability moves from an initial strategic or mission need to retirement and decommissioning.

D-AIGAAF treats the lifecycle as a continuous governance and assurance process rather than a one-time development activity. Risk, autonomy, human authority, security, assurance, operational context and evidence must remain connected throughout the lifecycle.

The lifecycle is:

**Strategic Need → Mission Need → Requirements & Use Case → Risk & Autonomy → Acquisition/Development → Design & Integration → Configuration Baseline → TEVV → Operational Environment Assessment → Assurance → Operational Authorisation → Deployment → Operational Employment → Continuous Monitoring & Assurance → Change/Incident/Emerging Risk → Revalidation → Reauthorisation → Retirement & Decommissioning**

---

## 1. Purpose

The AI Lifecycle Model establishes a common structure for governing an AI-enabled defence capability from conception through retirement.

It provides:

- lifecycle stages
- decision points
- required governance activities
- assurance expectations
- evidence requirements
- authority transitions
- change and reauthorisation triggers
- retirement and decommissioning considerations

The model applies to AI-enabled capabilities regardless of whether they are developed internally, acquired from industry, integrated from external components, or adapted from existing systems.

---

## 2. Core Principle

AI governance must continue for as long as the capability can affect defence decisions, operations, information, resources, personnel or other consequential outcomes.

An AI capability is therefore not considered governed merely because:

- the model has been tested;
- the system has been accepted by a technical organisation;
- procurement has been completed;
- an initial authorisation has been granted; or
- the system is already deployed.

Governance must continue through operational employment, updates, incidents, changing threats, changing environments and retirement.

---

## 3. Lifecycle Stages

### Stage 1 — Strategic Need

Identify the strategic, institutional or capability need that may justify an AI-enabled solution.

Consider:

- strategic objective
- capability gap
- expected benefit
- alternatives to AI
- strategic dependencies
- legal and policy context
- sovereignty considerations
- potential consequence of failure
- long-term sustainment implications

**Key output:** Strategic Need Statement.

---

### Stage 2 — Mission Need

Translate the strategic need into a defined mission or operational requirement.

Consider:

- mission objective
- users and decision authorities
- operational context
- mission criticality
- expected AI contribution
- consequences of failure
- human authority
- operational constraints
- environmental conditions

**Key output:** Mission Definition and initial Use Case.

---

### Stage 3 — Requirements & Use Case

Define what the capability is expected to do and, equally importantly, what it is not permitted to do.

Requirements should address:

- functional performance
- operational performance
- reliability
- robustness
- security
- information integrity
- human control
- autonomy
- interoperability
- environmental conditions
- communications conditions
- fail-safe and recovery behaviour
- auditability
- evidence requirements

The use case should establish the intended decision and action boundaries before development or acquisition progresses too far.

**Key output:** Approved Use Case and Requirements Baseline.

---

### Stage 4 — Risk & Autonomy

Assess the capability before committing it to development, acquisition or operational use.

Consider:

- consequence
- mission criticality
- autonomy
- operational environment
- human control
- information integrity
- security
- dependencies
- supply-chain risk
- uncertainty
- foreseeable misuse
- loss-of-control scenarios

Autonomy must be assessed separately from technical capability and operational authority.

**Key output:** Initial Risk Profile and Autonomy Assessment.

---

### Stage 5 — Acquisition / Development

Develop or acquire the AI-enabled capability under defined requirements, controls and governance conditions.

Consider:

- supplier provenance
- model and component dependencies
- data sources
- intellectual property and licensing
- security requirements
- sovereignty requirements
- development practices
- documentation
- configuration management
- testing obligations
- update mechanisms
- support and sustainment arrangements

Acquisition approval must not be treated as operational authorisation.

**Key output:** Development/Acquisition Baseline and Assurance Plan.

---

### Stage 6 — Design & Integration

Integrate the AI model with the wider system and operational ecosystem.

The assessment must cover the full AI-enabled capability, including where applicable:

- model
- software
- hardware
- sensors
- data
- interfaces
- communications
- computing infrastructure
- users
- external services
- dependencies
- security controls
- safety controls

Integration can materially change system behaviour. A model that performs acceptably in isolation may behave differently once integrated into a larger system.

**Key output:** Integrated System Baseline.

---

### Stage 7 — Configuration Baseline

Establish the specific configuration that will be tested and subsequently considered for assurance.

Record, as applicable:

- model version
- software version
- hardware configuration
- data and data versions
- prompts or configuration parameters where relevant
- sensors
- interfaces
- external services
- dependencies
- security configuration
- autonomy configuration
- operating procedures
- human-control arrangements

The baseline provides traceability between the tested system and the system later proposed for operational employment.

**Key output:** Controlled Configuration Baseline.

---

### Stage 8 — Testing, Evaluation, Verification & Validation

Conduct progressive TEVV appropriate to consequence, autonomy, uncertainty and operational exposure.

Evidence should progress where appropriate through:

**Lab → Controlled → Representative → Adversarial/Red-Team → Operational Environment → Mission-Level Evaluation**

Assess at least:

1. Technical Performance
2. Reliability & Robustness
3. Adversarial Resilience
4. Operational Environment
5. Human-AI Interaction
6. Security & Integrity
7. Autonomy & Control
8. Mission Effectiveness

Testing must examine both expected and credible adverse conditions.

**Key output:** TEVV Evidence Package.

---

### Stage 9 — Operational Environment Assessment

Determine whether the capability remains effective and controllable in the environments in which it is proposed to operate.

Consider variation in:

- terrain
- weather
- lighting
- sensors
- data quality
- communications
- computing availability
- electromagnetic conditions
- adversarial activity
- human workload
- mission tempo
- infrastructure
- information integrity

A capability should not be considered operationally ready solely because it performed well in controlled conditions.

**Key output:** Operational Environment Assessment.

---

### Stage 10 — Assurance

Convert evidence into an assurance judgement.

Assurance should establish:

- what claims are supported;
- what claims are not supported;
- known limitations;
- known failure modes;
- uncertainty;
- residual risk;
- autonomy boundaries;
- human-control effectiveness;
- operational constraints;
- evidence gaps;
- required conditions.

Assurance is an evidence-based judgement. It is not a statement that the AI is universally safe or reliable.

**Key output:** Defence AI Assurance Record (DAAR).

---

### Stage 11 — Operational Authorisation

Determine whether the specific AI capability may be employed for the defined mission, environment and autonomy.

Operational authorisation binds:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

The authorisation should define:

- authorised capability
- authorised mission/use case
- operational envelope
- authorised autonomy
- human authority
- constraints
- evidence basis
- known limitations
- fail-safe/degradation arrangements
- configuration baseline
- dependencies
- validity/review period
- suspension/revocation triggers

**Key output:** Defence AI Operational Authorisation (DAOA).

---

### Stage 12 — Deployment

Deploy the authorised configuration into the approved operational environment.

Deployment controls should verify:

- configuration integrity
- identity and provenance
- approved version
- dependencies
- security controls
- operational constraints
- human authority arrangements
- monitoring capability
- fail-safe mechanisms
- documentation and training

Deployment outside the authorised envelope requires appropriate review.

**Key output:** Deployment Record.

---

### Stage 13 — Operational Employment

Employ the capability within its authorised mission, environment, autonomy and human-authority boundaries.

During employment:

- monitor system behaviour;
- monitor operational performance;
- monitor uncertainty;
- maintain human authority;
- record consequential decisions and actions;
- monitor autonomy transitions;
- detect boundary violations;
- maintain configuration traceability;
- record significant deviations and incidents.

AI output does not itself constitute command authority.

**Key output:** Operational Records and Monitoring Evidence.

---

### Stage 14 — Continuous Monitoring & Assurance

Assurance continues after deployment.

Monitor:

- performance
- reliability
- robustness
- uncertainty
- autonomy
- human control
- security
- information integrity
- dependencies
- environment
- emerging threats
- user feedback
- supplier changes
- configuration changes
- incidents
- previously unknown failure modes

Monitoring should identify when the original assurance basis may no longer remain valid.

**Key output:** Continuous Assurance Evidence.

---

### Stage 15 — Change, Incident & Emerging Risk

Treat significant change, incidents and newly discovered risks as potential lifecycle events.

Triggers may include:

- model updates
- software updates
- hardware changes
- data changes
- dependency changes
- supplier changes
- autonomy changes
- new operational environments
- new threats
- security vulnerabilities
- significant performance degradation
- loss-of-control events
- unexpected behaviour
- changes in law or policy
- newly identified failure modes

Not every change requires full reauthorisation. Significance should be determined by its effect on behaviour, risk, autonomy, assurance and the authorised operational envelope.

**Key output:** Change/Incident Assessment.

---

### Stage 16 — Revalidation

Determine whether previous validation and assurance evidence remains applicable.

Revalidation should answer:

- Has intended operational performance changed?
- Has system behaviour changed?
- Has the operational context changed?
- Have assumptions changed?
- Have risks changed?
- Are previous test results still representative?
- Are human-control arrangements still effective?
- Has autonomy changed?
- Are existing controls still effective?

**Key output:** Revalidation Decision and updated evidence.

---

### Stage 17 — Reauthorisation

Where changes materially affect the authorised capability, obtain a new or amended operational authorisation.

Reauthorisation may be required following:

- material model behaviour changes;
- material autonomy changes;
- significant environmental changes;
- significant risk changes;
- major incidents;
- loss of control;
- major dependency changes;
- invalidated assurance evidence;
- changes in legal or policy requirements.

Possible outcomes include:

- continue authorisation;
- amend conditions;
- reduce autonomy;
- restrict mission scope;
- restrict environment;
- suspend;
- revoke;
- retire.

**Key output:** Updated Operational Authorisation.

---

### Stage 18 — Retirement & Decommissioning

Retirement should be governed as deliberately as deployment.

Consider:

- operational withdrawal
- data retention and disposition
- model and software archival
- credential and access revocation
- dependency removal
- supplier termination
- infrastructure disposal
- residual security risks
- records and evidence retention
- lessons learned
- replacement capability
- legal and policy obligations

A retired capability should not remain unintentionally accessible or operational.

**Key output:** Retirement and Decommissioning Record.

---

## 4. Lifecycle Decision Gates

D-AIGAAF uses decision gates to prevent progression based solely on technical development status.

Illustrative gates include:

| Gate | Key Question | Typical Evidence |
|---|---|---|
| G1 | Is there a justified mission need? | Strategic/Mission Need |
| G2 | Is the use case sufficiently defined? | Requirements and Use Case |
| G3 | Are risks and autonomy understood sufficiently to proceed? | Risk & Autonomy Assessment |
| G4 | Is the integrated capability ready for formal TEVV? | Configuration Baseline |
| G5 | Does evidence support the claimed capability? | TEVV Evidence |
| G6 | Does evidence support operational use in the intended environment? | Operational Environment Assessment |
| G7 | Is the residual risk understood and appropriately accepted? | Risk Acceptance |
| G8 | Is operational employment authorised? | DAOA |
| G9 | Does continued employment remain within the assurance basis? | Continuous Assurance |
| G10 | Does change require revalidation or reauthorisation? | Change/Incident Assessment |
| G11 | Can the capability be safely retired? | Decommissioning Record |

---

## 5. Lifecycle Traceability

Each material lifecycle decision should remain traceable to the Golden Thread:

**Mission Need → Use Case → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

This traceability should allow an authorised reviewer to determine:

- why the capability exists;
- what it is authorised to do;
- what evidence supports that authority;
- what limitations apply;
- who holds decision authority;
- what happened during employment;
- what changed;
- whether reauthorisation is required.

---

## 6. Operational AI Advisor

The Operational AI Advisor (OAIA) provides a bridge between operational command authority and technical AI expertise.

The OAIA may support lifecycle decisions involving:

- use-case definition;
- risk assessment;
- autonomy;
- human control;
- TEVV interpretation;
- operational limitations;
- change significance;
- incident assessment;
- revalidation;
- reauthorisation.

The OAIA advises.

**The appropriately authorised command or governance authority decides.**

The OAIA does not replace command authority, technical assurance authorities, legal authorities or other mandated governance bodies.

---

## 7. Lifecycle Records

The lifecycle should maintain traceable records, including as applicable:

- Strategic Need Statement
- Mission Definition
- Use Case Record
- Requirements Baseline
- Risk Assessment Record
- Autonomy Assessment Record
- Human Control Assessment
- Configuration Baseline
- TEVV Evidence Package
- Operational Environment Assessment
- Defence AI Assurance Record (DAAR)
- Risk Acceptance Record
- Defence AI Operational Authorisation (DAOA)
- Deployment Record
- Operational Record
- Continuous Assurance Record
- Change/Incident Record
- Revalidation Record
- Reauthorisation Record
- Retirement and Decommissioning Record

---

## 8. Lifecycle Status Model

A capability may move through the following conceptual states:

**Proposed → Defined → Under Development/Acquisition → Under TEVV → Under Assurance → Conditionally Authorised → Operationally Authorised → Operational → Restricted → Suspended → Revalidating → Reauthorised → Retired**

Status should reflect governance and authority, not merely technical development maturity.

---

## 9. Lifecycle Failure Modes

Common lifecycle failures include:

- starting with technology rather than mission need;
- defining a use case too narrowly;
- assessing the model but not the full system;
- treating technical acceptance as operational authorisation;
- testing only in benign conditions;
- ignoring communications degradation;
- assuming human control without testing it;
- failing to assess actual autonomy;
- losing configuration traceability;
- treating updates as automatically minor;
- allowing supplier changes without reassessment;
- allowing assurance evidence to become stale;
- failing to record operational deviations;
- failing to reassess after incidents;
- retaining authority after the assurance basis has been invalidated;
- treating retirement as an administrative event only.

---

## 10. Core Rules

1. **Mission need precedes technology selection.**
2. **The full AI-enabled capability must be governed, not only the model.**
3. **Technical capability does not equal operational authority.**
4. **Autonomy must be assessed from actual behaviour.**
5. **Assurance must be proportionate to consequence, autonomy, uncertainty and exposure.**
6. **Operational environment is part of the assurance case.**
7. **Human authority must remain explicit and testable.**
8. **Configuration traceability is essential to assurance.**
9. **Material change can invalidate previous assurance.**
10. **Incidents can invalidate assurance even without configuration change.**
11. **Operational authorisation is bounded and time/context dependent.**
12. **Continuous monitoring is part of the lifecycle, not an optional post-deployment activity.**
13. **Revalidation and reauthorisation must occur when the assurance basis materially changes.**
14. **Retirement and decommissioning are governed lifecycle stages.**

---

## 11. Summary Model

```text
Strategic Need
      ↓
Mission Need
      ↓
Requirements & Use Case
      ↓
Risk & Autonomy
      ↓
Acquisition / Development
      ↓
Design & Integration
      ↓
Configuration Baseline
      ↓
TEVV
      ↓
Operational Environment Assessment
      ↓
Assurance
      ↓
Risk Acceptance
      ↓
Operational Authorisation
      ↓
Deployment
      ↓
Operational Employment
      ↓
Continuous Monitoring & Assurance
      ↓
Change / Incident / Emerging Risk
      ↓
Revalidation
      ↓
Reauthorisation
      ↓
Retirement & Decommissioning
```

The lifecycle is continuous because operational evidence can change the risk, assurance or authority position at any point.

---

## 12. Relationship to Other D-AIGAAF Sections

This model provides the lifecycle backbone for:

- **Risk & Autonomy** — defines how risk and autonomy are assessed throughout the lifecycle.
- **AI Lifecycle** — defines development, integration, testing, deployment, change and retirement controls.
- **Data & Information** — governs data quality, provenance and information integrity.
- **AI Security** — protects models, systems, interfaces and dependencies.
- **Human Authority** — establishes decision rights and human control.
- **TEVV** — produces evidence supporting assurance.
- **Operational Environment** — determines whether capability remains effective in intended conditions.
- **Operational Authorisation** — establishes permission for defined employment.
- **Continuous Assurance** — maintains confidence after deployment.
- **Incident & Fail-Safe** — governs abnormal conditions and loss of control.
- **Change & Reauthorisation** — determines when the assurance and authority basis must be revisited.
- **Audit & Evidence** — preserves traceability throughout the lifecycle.
- **Retirement & Decommissioning** — governs controlled withdrawal.

---

## 13. Golden Thread

The AI Lifecycle Model maintains the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Employment → Monitoring → Change/Incident → Reauthorisation**

Every material lifecycle decision should be traceable through this chain.
