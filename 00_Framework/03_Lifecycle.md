# D-AIGAAF Lifecycle

**Defence AI Governance, Assurance & Operational Authorisation Framework**

**Version:** 0.1  
**Status:** Working Draft  
**Classification:** Open / Unclassified

---

## 1. Purpose

This document defines the D-AIGAAF lifecycle for governing AI-enabled defence capabilities from initial need through retirement.

The lifecycle establishes the major stages through which an AI capability should pass and identifies the principal governance, risk, assurance and authority activities associated with each stage.

D-AIGAAF treats AI governance as a **lifecycle activity**, not as a one-time approval.

The lifecycle is therefore continuous:

**Need → Design → Evidence → Authority → Employment → Monitoring → Change → Reauthorisation → Retirement**

---

# 2. Lifecycle Philosophy

The lifecycle is based on five propositions:

1. **Governance begins before an AI system is acquired or developed.**
2. **Risk and assurance requirements are determined by mission, consequence, context, autonomy and human authority.**
3. **Operational authorisation is a decision based on evidence, risk and authority—not merely technical completion.**
4. **Deployment does not end assurance.**
5. **Changes, incidents and operational experience can alter the assurance and authorisation position.**

---

# 3. D-AIGAAF Lifecycle

The reference lifecycle is:

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

The lifecycle is **iterative rather than strictly linear**.

Activities may return to earlier stages whenever evidence, risk, requirements or operating conditions change.

---

# 4. Stage 1 — Strategic Need

## Purpose

Establish why an AI-enabled capability is being considered and what strategic or organisational problem it is intended to address.

## Key Questions

- What problem needs to be solved?
- Why is AI being considered?
- Is AI actually necessary?
- What strategic objective does the capability support?
- What would happen if the capability were not developed?

## Principal Outputs

- Strategic need statement
- Initial capability concept
- Initial strategic risk considerations
- Initial governance classification

---

# 5. Stage 2 — Mission Need

## Purpose

Translate strategic intent into a defined operational or organisational requirement.

## Key Questions

- What mission or function will the capability support?
- Who will use it?
- What decisions or actions could it influence?
- What happens if it fails?
- What level of human authority is required?

## Principal Outputs

- Mission statement
- Mission use case
- Initial consequence assessment
- Initial operational context
- Initial human-authority model

---

# 6. Stage 3 — Requirements & Use Case

## Purpose

Define what the AI capability must do and the conditions under which it is expected to perform.

Requirements should address more than technical accuracy.

They should consider:

- mission effectiveness;
- reliability;
- security;
- resilience;
- explainability or interpretability where relevant;
- uncertainty;
- human control;
- autonomy;
- environmental conditions;
- communications;
- data;
- interoperability; and
- operational constraints.

## Principal Outputs

- System requirements
- Operational requirements
- Use-case definition
- Operational envelope draft
- Initial assurance objectives

---

# 7. Stage 4 — Risk & Autonomy

## Purpose

Determine the risk profile of the intended capability and establish the proposed autonomy and authority boundaries.

D-AIGAAF considers risk through multiple dimensions, including:

- consequence;
- autonomy;
- mission criticality;
- operational environment; and
- human control.

## Key Questions

- What could go wrong?
- What could the system cause or influence?
- How serious could the consequences be?
- How much independent authority does the system have?
- How quickly can a human intervene?
- Under what environmental conditions will it operate?

## Principal Outputs

- Risk assessment
- Autonomy classification
- Human-control assessment
- Initial control requirements
- Assurance level/objectives
- Proposed authority boundary

---

# 8. Stage 5 — Acquisition / Development

## Purpose

Acquire or develop the capability while preserving the ability to assure, secure, monitor, modify and ultimately retire it.

Acquisition decisions should consider:

- supplier provenance;
- model provenance;
- critical dependencies;
- data;
- hardware and software;
- update mechanisms;
- access to testing;
- auditability;
- security;
- interoperability;
- sovereignty; and
- lifecycle support.

## Principal Outputs

- Acquisition or development plan
- Supplier assurance information
- Dependency register
- Security requirements
- Assurance requirements
- Contractual governance requirements

---

# 9. Stage 6 — Design & Integration

## Purpose

Develop or integrate the AI capability into the wider technical and operational system.

The focus is not only whether the AI model works, but whether the **integrated capability** behaves appropriately.

Assessment should consider:

- interfaces;
- data flows;
- sensors;
- communications;
- human-machine interaction;
- access and permissions;
- system dependencies;
- failure modes;
- safety mechanisms; and
- operational workflows.

## Principal Outputs

- Integrated system
- Architecture documentation
- Configuration information
- Control implementation
- Initial test results
- Updated risk assessment

---

# 10. Stage 7 — Configuration Baseline

## Purpose

Establish the specific version and configuration against which assurance and authorisation will be based.

The baseline should identify, as appropriate:

- model version;
- software version;
- hardware;
- data configuration;
- interfaces;
- critical dependencies;
- security configuration;
- relevant operating parameters.

The baseline creates a reference point for determining whether subsequent changes are material.

---

# 11. Stage 8 — TEVV

## Purpose

Generate evidence about technical performance, operational suitability and risk.

D-AIGAAF uses the following conceptual progression:

```text
Laboratory
    ↓
Controlled
    ↓
Representative
    ↓
Adversarial / Red Team
    ↓
Operational Environment
    ↓
Mission-Level Evaluation
```

TEVV should assess the capability against the conditions that matter to its intended use.

## Core TEVV Dimensions

1. Technical Performance
2. Reliability & Robustness
3. Adversarial Resilience
4. Operational Environment
5. Human-AI Interaction
6. Security & Integrity
7. Autonomy & Control
8. Mission Effectiveness

## Principal Outputs

- Test results
- Verification evidence
- Validation evidence
- Evaluation findings
- Limitations
- Failure modes
- Evidence gaps

---

# 12. Stage 9 — Operational Environment Assessment

## Purpose

Determine whether evidence generated under test conditions remains applicable to the intended operational environment.

The assessment should consider relevant conditions such as:

- physical environment;
- environmental extremes;
- degraded communications;
- limited infrastructure;
- sensor limitations;
- data availability;
- adversarial conditions;
- human workload;
- system dependencies; and
- operational tempo.

The objective is not to guarantee perfect performance in every possible condition.

The objective is to understand **where the capability can be trusted, where it degrades and where it should not be used.**

---

# 13. Stage 10 — Assurance

## Purpose

Determine whether the accumulated evidence supports justified confidence that the capability is suitable for its intended use, within known limitations.

Assurance should answer:

> **What does the evidence actually demonstrate?**

It should identify:

- demonstrated capabilities;
- known limitations;
- assumptions;
- unresolved uncertainties;
- residual risks;
- evidence gaps;
- conditions of confidence.

The primary record is the **Defence AI Assurance Record (DAAR)**.

---

# 14. Stage 11 — Operational Authorisation

## Purpose

Make the formal organisational decision on whether the capability may be operationally employed.

Operational authorisation considers:

- assurance evidence;
- residual risk;
- mission requirement;
- law and policy;
- operational context;
- autonomy;
- human authority;
- operational envelope; and
- organisational risk acceptance.

The primary record is the **Defence AI Operational Authorisation (DAOA)**.

Operational authorisation binds:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

---

# 15. Stage 12 — Deployment

## Purpose

Place the authorised capability into the intended operational environment without silently changing the conditions under which it was assured or authorised.

Deployment should confirm:

- authorised configuration;
- authorised environment;
- authorised interfaces;
- authorised users;
- authorised permissions;
- monitoring mechanisms;
- fail-safe mechanisms; and
- relevant support arrangements.

Deployment should not be treated as permission to expand the operational envelope.

---

# 16. Stage 13 — Operational Employment

## Purpose

Use the AI capability within its authorised operational envelope.

Operational employment should preserve:

- authorised mission;
- authorised autonomy;
- authorised human authority;
- configuration baseline;
- operating constraints;
- monitoring requirements.

Where the system provides recommendations, the recommendation should remain distinguishable from the authorised human decision.

---

# 17. Stage 14 — Continuous Monitoring & Assurance

## Purpose

Determine whether the assumptions supporting assurance and authorisation remain valid during operational use.

Monitoring may include:

- system performance;
- reliability;
- anomalous behaviour;
- security events;
- data integrity;
- environmental changes;
- human overrides;
- incidents;
- mission outcomes;
- configuration changes;
- emerging threats.

Operational experience should feed back into the assurance record.

---

# 18. Stage 15 — Change, Incident & Emerging Risk

Three events can trigger reassessment:

### Change

A modification to:

- model;
- software;
- data;
- hardware;
- integration;
- permissions;
- environment;
- autonomy; or
- operational use.

### Incident

An event involving:

- unexpected behaviour;
- unsafe output;
- security compromise;
- loss of control;
- mission-impacting failure;
- significant human override;
- other material deviation.

### Emerging Risk

A new threat, vulnerability, operational condition, technology dependency or understanding of system behaviour that changes the risk position.

---

# 19. Stage 16 — Revalidation

## Purpose

Determine whether the capability continues to satisfy its intended operational purpose following a material change, incident or emerging risk.

Revalidation may involve:

- targeted testing;
- regression testing;
- operational evaluation;
- renewed risk assessment;
- human-control assessment;
- security assessment;
- review of existing evidence.

Not every change requires complete revalidation.

The extent of reassessment should be proportionate to the potential effect of the change.

---

# 20. Stage 17 — Reauthorisation

## Purpose

Determine whether existing operational authority remains appropriate.

Reauthorisation may be required when:

- autonomy changes;
- mission changes;
- operational environment changes materially;
- consequence changes;
- human-control conditions change;
- significant system behaviour changes;
- significant incidents occur;
- assurance assumptions are invalidated;
- authorisation expires; or
- organisational policy requires renewed approval.

Possible outcomes include:

- continued authorisation;
- modified authorisation;
- restricted authorisation;
- suspension; or
- revocation.

---

# 21. Stage 18 — Retirement & Decommissioning

## Purpose

Formally terminate operational use and remove the capability's operational authority.

Retirement should consider:

- withdrawal of authorisation;
- removal of operational access;
- credentials and permissions;
- interfaces;
- deployed instances;
- model and system records;
- data;
- dependencies;
- supplier arrangements;
- audit records;
- lessons learned.

Retirement is complete only when the capability no longer possesses unintended operational authority.

---

# 22. Lifecycle Decision Gates

D-AIGAAF uses decision gates to prevent progression based solely on technical momentum.

| Gate | Decision |
|---|---|
| **G0** | Is there a justified need for the capability? |
| **G1** | Is the mission and use case sufficiently defined? |
| **G2** | Are risk, autonomy and human authority understood? |
| **G3** | Are requirements and controls sufficiently defined? |
| **G4** | Is the capability ready for meaningful TEVV? |
| **G5** | Does evidence support the intended operational claims? |
| **G6** | Is the capability suitable for operational authorisation? |
| **G7** | Is operational use within the authorised envelope? |
| **G8** | Has continued assurance been maintained? |
| **G9** | Does a change, incident or emerging risk require reassessment? |
| **G10** | Should authority be renewed, restricted, suspended or revoked? |
| **G11** | Has operational authority been formally terminated? |

---

# 23. Lifecycle Feedback Loops

D-AIGAAF deliberately includes feedback loops.

```text
Operational Employment
        ↓
Operational Experience
        ↓
Continuous Assurance
        ↓
Risk / Evidence / Lessons
        ↓
Requirements / Controls / TEVV
        ↓
Revalidation
        ↓
Reauthorisation
        ↓
Operational Employment
```

A second loop connects operational experience to future capability development:

```text
Operational Experience
        ↓
Lessons Learned
        ↓
Requirements
        ↓
Design / Development
        ↓
TEVV
        ↓
Assurance
        ↓
Authorisation
```

This ensures that governance evolves with actual experience.

---

# 24. Lifecycle Principle: No One-Time Certification

D-AIGAAF does not treat AI authorisation as equivalent to permanent certification.

An AI capability may change because of:

- software updates;
- model updates;
- data changes;
- integration changes;
- new threats;
- new environments;
- changed missions;
- changed autonomy;
- changed human-control conditions.

Therefore:

> **Authorisation is valid only while the assumptions, evidence and conditions supporting it remain sufficiently valid.**

---

# 25. Lifecycle Principle: Behaviour Determines Change Significance

A change should not be classified only by how large the technical modification appears.

The relevant question is:

> **Could this change materially alter behaviour, performance, authority, security, autonomy or operational risk?**

If yes, appropriate reassessment should occur.

---

# 26. Lifecycle Principle: Evidence Follows the Capability

Evidence should remain associated with the specific capability and configuration to which it applies.

A test result for one configuration should not automatically be assumed to validate another materially different configuration.

This principle supports:

- configuration control;
- traceability;
- auditability;
- change management;
- revalidation.

---

# 27. Lifecycle Principle: Operational Authority Is Conditional

Operational authorisation should always be interpreted in context.

```text
Authorisation
      =
Capability
+ Mission
+ Environment
+ Autonomy
+ Human Authority
+ Conditions
```

This is a conceptual relationship, not a mathematical formula.

---

# 28. Lifecycle Records

The lifecycle should maintain traceable records including, as appropriate:

- Strategic Need;
- Mission Need;
- Requirements;
- Risk Assessment;
- Autonomy Assessment;
- Configuration Baseline;
- TEVV Evidence;
- Defence AI Assurance Record (DAAR);
- Defence AI Operational Authorisation (DAOA);
- Operational Records;
- Incident Records;
- Change Records;
- Revalidation Records;
- Reauthorisation Records;
- Retirement Records.

---

# 29. Lifecycle and Repository Modules

The lifecycle provides the temporal structure.

The repository modules provide the functional structure.

They are therefore related but not identical.

For example:

- `03 Risk & Autonomy` applies primarily during risk determination but remains relevant throughout the lifecycle.
- `06 AI Security` applies across the entire lifecycle.
- `09 TEVV` becomes especially important before authorisation but may continue after deployment.
- `13 Continuous Assurance` becomes central after operational authorisation.
- `15 Change & Reauthorisation` is activated when changes or incidents alter the assurance position.
- `26 Retirement & Decommissioning` governs the end of operational authority.

Therefore, repository numbering does **not** imply lifecycle sequence.

---

# 30. Lifecycle Summary

The D-AIGAAF lifecycle can be reduced to:

```text
1. Define the Need
        ↓
2. Define the Mission
        ↓
3. Define the Use Case
        ↓
4. Understand Risk and Autonomy
        ↓
5. Build / Acquire
        ↓
6. Test and Evaluate
        ↓
7. Establish Evidence
        ↓
8. Assure
        ↓
9. Authorise
        ↓
10. Employ
        ↓
11. Monitor
        ↓
12. Learn
        ↓
13. Change / Reassess
        ↓
14. Reauthorise
        ↓
15. Retire
```

The central lifecycle rule is:

> **No consequential AI capability should move from technical capability to operational authority without an appropriate chain of requirements, risk assessment, evidence, assurance and authorised human decision.**

---

## Status

**D-AIGAAF Lifecycle v0.1**

Working lifecycle model for framework development.

The lifecycle should be refined as individual D-AIGAAF modules are developed and cross-referenced against established lifecycle, safety, security, AI governance and defence assurance practices.
