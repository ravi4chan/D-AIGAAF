# 00-Crosswalk Governance Framework

## 1. Purpose

The D-AIGAAF Crosswalk Governance Framework establishes the method for mapping D-AIGAAF against external AI governance, risk management, security, assurance, responsible AI, and regulatory frameworks.

The purpose of a crosswalk is to demonstrate relationships, identify alignment and gaps, support complementary implementation, and reduce unnecessary duplication.

A crosswalk is an analytical mapping tool. It is not a declaration of compliance, certification, equivalence, endorsement, or legal conformity.

## 2. Scope

This framework applies to crosswalks involving relevant external frameworks, standards, regulations, principles, guidance, and assurance methodologies.

The initial D-AIGAAF crosswalk programme includes:

- NIST AI Risk Management Framework;
- ISO/IEC 42001;
- ISO/IEC 23894;
- ISO/IEC 27001;
- EU AI Act;
- defence and responsible-AI principles;
- TEVV and AI assurance frameworks; and
- AI security and adversarial-AI frameworks.

Additional frameworks may be incorporated through controlled updates.

## 3. Why D-AIGAAF Requires Crosswalks

D-AIGAAF is designed specifically for defence AI governance and therefore addresses issues that may not be fully covered by general AI governance frameworks.

These include the interaction between:

**Mission → Consequence → Risk → Autonomy → Human Authority → Operational Environment → TEVV → Assurance → Operational Authorisation → Employment → Continuous Assurance**

External frameworks may provide strong controls or governance concepts for individual elements of this chain, while D-AIGAAF integrates them into a defence-specific lifecycle and operational-authority model.

Crosswalks therefore help show how D-AIGAAF relates to established practice without unnecessarily duplicating it.

## 4. Crosswalk Principles

All D-AIGAAF crosswalks should follow these principles.

### 4.1 No Implied Compliance

Mapping a D-AIGAAF control to an external requirement does not mean that implementation of D-AIGAAF automatically satisfies that requirement.

Compliance depends on the actual wording, applicability, implementation, evidence, jurisdiction, scope, and conformity-assessment requirements of the external instrument.

### 4.2 No False Equivalence

Conceptual similarity does not necessarily mean functional equivalence.

Where two frameworks address similar subjects differently, the crosswalk shall identify the difference rather than forcing a one-to-one mapping.

### 4.3 Version Control

Crosswalks shall identify the specific version, edition, publication date, or legal status of the external framework being mapped.

Material changes to an external framework should trigger review of the relevant crosswalk.

### 4.4 Evidence-Based Mapping

Mappings should be supported by the actual requirements, controls, principles, outcomes, or provisions of the external framework.

Interpretive statements should be distinguished from explicit requirements.

### 4.5 Context Sensitivity

Crosswalks shall consider the context in which the external framework is applied.

A control designed for enterprise IT governance may require additional interpretation when applied to autonomous or consequential defence AI operating in adversarial, degraded, or disconnected environments.

### 4.6 Defence-Specific Extension

Where D-AIGAAF goes beyond an external framework, the crosswalk should explicitly identify the extension.

Examples include:

- operational authorisation;
- explicit human decision authority;
- autonomy boundaries;
- mission-specific risk;
- degraded and disconnected operations;
- operational environment governance;
- fail-safe and safe-state requirements;
- reauthorisation following consequential change; and
- continuous operational assurance.

## 5. Crosswalk Relationship Types

Each mapping should use a defined relationship classification.

| Relationship | Meaning |
|---|---|
| Direct Alignment | D-AIGAAF addresses substantially the same governance objective or requirement. |
| Partial Alignment | D-AIGAAF addresses part of the external concept but not all aspects. |
| Complementary | D-AIGAAF and the external framework address related but distinct aspects. |
| Extension | D-AIGAAF adds defence-specific or operational requirements beyond the external framework. |
| Different Scope | The concepts overlap but operate at materially different levels or scopes. |
| Not Addressed | The external framework contains a relevant concept not sufficiently represented in D-AIGAAF. |
| D-AIGAAF Specific | D-AIGAAF contains a concept primarily introduced for its defence operational governance purpose. |
| Not Applicable | The external requirement or concept is not relevant to the defined D-AIGAAF assessment context. |

Mappings should avoid ambiguous labels such as simply "covered" unless the basis and extent of coverage are documented.

## 6. Crosswalk Layers

A mature crosswalk should consider multiple layers rather than only terminology.

### Layer 1 — Principle

Does D-AIGAAF reflect the underlying principle?

### Layer 2 — Governance Objective

Does D-AIGAAF establish a comparable governance objective?

### Layer 3 — Process

Does D-AIGAAF define a process for achieving the objective?

### Layer 4 — Control

Does D-AIGAAF establish a specific control or control expectation?

### Layer 5 — Evidence

Does D-AIGAAF define or require evidence demonstrating implementation?

### Layer 6 — Assurance

Does D-AIGAAF provide mechanisms to assess whether the control remains effective?

### Layer 7 — Operational Authority

Does D-AIGAAF connect the requirement to an explicit operational decision, condition, boundary, or authorisation?

This layered approach prevents superficial keyword matching from being mistaken for substantive alignment.

## 7. Core Crosswalk Fields

Each crosswalk should, where applicable, contain:

| Field | Description |
|---|---|
| External Framework | Name of the framework, standard, regulation, or guidance. |
| Version | Specific edition or version assessed. |
| External Reference | Clause, article, control, principle, or requirement identifier. |
| External Requirement | Concise description of the requirement. |
| D-AIGAAF Module | Relevant D-AIGAAF module. |
| D-AIGAAF Reference | Relevant file, section, principle, or control. |
| Relationship | Alignment classification. |
| Coverage | Extent and nature of coverage. |
| Defence Extension | Additional D-AIGAAF requirement where applicable. |
| Evidence | Expected evidence or implementation artefact. |
| Notes | Interpretive limitations or important context. |

The crosswalk should remain traceable to both sides of the mapping.

## 8. Crosswalk Levels

Crosswalks may be produced at several levels.

### Strategic Level

Maps major principles and governance objectives.

### Framework Level

Maps major domains or functions.

### Requirement Level

Maps specific requirements, clauses, controls, or provisions.

### Evidence Level

Maps expected evidence and implementation records.

### Operational Level

Maps external requirements to D-AIGAAF operational conditions, boundaries, controls, and authorisation decisions.

The appropriate level should depend on the intended use.

## 9. Governance of Crosswalks

Crosswalks shall be treated as controlled D-AIGAAF knowledge assets.

Governance should establish:

- ownership;
- version control;
- review frequency;
- authoritative sources;
- assessor or analyst competence;
- interpretation rules;
- change triggers;
- approval arrangements; and
- records of material assumptions.

Review should be triggered by significant changes to either D-AIGAAF or the external framework.

Potential triggers include:

- new editions;
- amendments;
- regulatory developments;
- revised guidance;
- significant judicial or policy developments;
- changes to D-AIGAAF modules;
- newly identified defence AI risks; or
- material changes in technology or operational practice.

## 10. Crosswalk Quality and Assurance

Crosswalks should be reviewed for:

- accuracy;
- completeness;
- consistency;
- source integrity;
- correct interpretation;
- version currency;
- appropriate relationship classification;
- absence of unsupported compliance claims; and
- visibility of material differences.

Where legal or regulatory interpretation is involved, the crosswalk should clearly distinguish governance analysis from formal legal advice.

Independent review should be considered for high-consequence or externally published crosswalks.

## 11. Using Crosswalks for Implementation

Crosswalks can support organisations that already use established frameworks.

A practical implementation pattern is:

**Existing Framework → Crosswalk → Identify D-AIGAAF Coverage → Identify Defence Extensions → Integrate Controls → Establish Evidence → Assure → Authorise Where Applicable**

This allows D-AIGAAF to function as an integrating defence governance layer rather than requiring organisations to discard existing governance systems.

For example, an organisation may retain an enterprise information-security management system while using D-AIGAAF to connect AI-specific security concerns to mission risk, human authority, operational environment, TEVV, authorisation, and employment.

## 12. Crosswalks and Compliance

Crosswalks may support compliance activities, but they do not establish compliance independently.

Compliance should be determined against the applicable authoritative instrument and its specific requirements.

The distinction is:

**Crosswalk = Relationship Mapping**

**Control Implementation = Practical Execution**

**Evidence = Demonstration**

**Conformity Assessment = Formal Evaluation Where Required**

**Compliance = Determination Against Applicable Requirements**

D-AIGAAF should never state or imply that "mapped" means "compliant."

## 13. Crosswalks and D-AIGAAF Maturity

Crosswalk capability may contribute to D-AIGAAF maturity, particularly within governance, policy alignment, audit, evidence, knowledge management, and continuous improvement.

However, possession of extensive crosswalks does not itself demonstrate high maturity.

A mature organisation demonstrates that crosswalks are:

- accurate;
- maintained;
- actively used;
- connected to implementation;
- reflected in evidence;
- reviewed when frameworks change; and
- integrated into governance decisions.

## 14. Crosswalks and Operational Authorisation

External framework alignment shall not independently create operational authority.

Operational authorisation remains governed by D-AIGAAF Module 11 and depends on the applicable combination of:

**AI Capability × Mission × Environment × Autonomy × Human Authority**

An AI capability may be strongly aligned with multiple external frameworks and still fail to satisfy the conditions required for operational authorisation.

Conversely, a capability may require additional defence-specific controls beyond what general AI governance frameworks address.

## 15. Crosswalks and the Golden Thread

Crosswalks should ultimately strengthen traceability across the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation → Workforce → Maturity → Continuous Improvement**

External frameworks may contribute at different points along this chain.

The crosswalk should identify where each framework contributes and where D-AIGAAF provides additional integration or defence-specific requirements.

## 16. Generic Crosswalk Template

A generic D-AIGAAF crosswalk should follow this structure:

| External Reference | External Requirement | D-AIGAAF Reference | Relationship | Coverage | Defence Extension | Evidence | Notes |
|---|---|---|---|---|---|---|---|
| [Reference] | [Requirement] | [Module/File] | [Classification] | [Description] | [If applicable] | [Evidence] | [Limitations] |

The template should be adapted where the external instrument uses a different structure, such as regulatory articles, principles, controls, outcomes, or lifecycle functions.

## 17. Crosswalk Maintenance

Every published crosswalk should have a controlled metadata record containing:

- external framework name;
- version or edition;
- publication date;
- crosswalk version;
- date assessed;
- assessment scope;
- responsible owner;
- reviewer;
- approval status;
- known limitations; and
- next review or change trigger.

A crosswalk should be marked as requiring review when its underlying framework changes materially.

## 18. Handling Ambiguity

Where an external requirement can reasonably be interpreted in multiple ways, the crosswalk shall:

1. identify the ambiguity;
2. state the interpretation used;
3. identify the source supporting that interpretation;
4. assess whether alternative interpretations change the mapping; and
5. flag the issue for appropriate review where necessary.

The objective is to preserve analytical integrity rather than create an artificially precise mapping.

## 19. Public and Open-Source Use

Because D-AIGAAF is intended as a generic, unclassified framework, published crosswalks should use publicly available and authoritative source material wherever practicable.

Crosswalks should avoid:

- classified information;
- operationally sensitive procedures;
- restricted military capabilities;
- sensitive vulnerabilities;
- non-public system details; or
- information that would unnecessarily expose security-sensitive implementation details.

The framework should remain useful to defence organisations, government entities, industry, academia, assurance providers, and policy communities without requiring disclosure of sensitive operational information.

## 20. Core Rule

> **A crosswalk demonstrates a reasoned relationship between D-AIGAAF and an external framework; it does not create equivalence, compliance, assurance, safety, readiness, or operational authority.**

The D-AIGAAF approach is therefore:

**Recognise Existing Frameworks → Map Concepts and Requirements → Identify Alignment → Identify Gaps → Identify Defence Extensions → Integrate Evidence and Controls → Maintain Currency → Assure → Improve**

This establishes Module 19 as an interoperability and alignment layer around D-AIGAAF while preserving the framework's central principle:

**Governance must ultimately connect mission consequence to accountable human authority, credible evidence, operational conditions, and continuing assurance.**
