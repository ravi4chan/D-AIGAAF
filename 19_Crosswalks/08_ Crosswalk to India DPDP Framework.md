# 08-Crosswalk to India DPDP Framework

## 1. Purpose

This document establishes the relationship between D-AIGAAF — Defence AI Governance, Assurance & Operational Authorisation Framework and India's **Digital Personal Data Protection Act, 2023 (DPDP Act)** together with the **Digital Personal Data Protection Rules, 2025 (DPDP Rules)**.

The DPDP framework is treated as an important Indian **data-protection and privacy legal layer** within D-AIGAAF.

It is not treated as a complete AI governance framework.

The crosswalk therefore answers a specific question:

> **Where D-AIGAAF processes digital personal data, what data-protection governance requirements must be incorporated into the AI lifecycle, and where does D-AIGAAF require additional controls beyond data protection?**

The DPDP Act was enacted on 11 August 2023. The DPDP Rules, 2025 were notified on 13 November 2025, with phased commencement provisions. MeitY's current materials describe the Rules as establishing the implementation framework for the Act. citeturn0search3turn0search24turn0search27

## 2. Status and Legal Character

The DPDP Act is an Indian statute governing the processing of digital personal data.

The DPDP Rules provide detailed implementation requirements under the Act.

This creates an important distinction within D-AIGAAF:

- **IndiaAI Responsible AI principles** provide a responsible-AI policy reference.
- **IndiaAI Governance Guidelines** provide an evolving AI-governance policy layer.
- **DPDP Act and Rules** provide a legal data-protection layer where applicable.
- **D-AIGAAF** provides a broader defence AI governance and operational-authorisation architecture.

The DPDP framework should therefore be treated as a **legal requirement to be incorporated where applicable**, rather than as a substitute for AI governance.

## 3. Scope and Applicability

The DPDP Act establishes a framework for processing digital personal data and recognises both individual data-protection interests and the need for lawful processing. The Act defines concepts including Data Principal, Data Fiduciary, automated processing and certain legitimate uses. citeturn0search3turn0search26

D-AIGAAF implementation must therefore begin with a scope determination:

1. Is the information personal data?
2. Is it digital personal data?
3. Is it being processed within the scope of the Act?
4. Is the organisation acting in a relevant fiduciary or processing role?
5. Does an exemption or special legal provision apply?
6. Which DPDP provisions are currently in force for the relevant activity?
7. Are other legal, defence, security or contractual requirements also applicable?

The crosswalk must never assume that every defence dataset is automatically outside the DPDP framework or that every defence AI system automatically falls within it.

Applicability should be determined by the relevant legal facts and competent legal authority.

## 4. DPDP Governance Concepts

The DPDP framework establishes several important concepts relevant to AI governance, including:

- Data Principal;
- Data Fiduciary;
- processing of personal data;
- consent;
- certain legitimate uses;
- obligations of Data Fiduciaries;
- Significant Data Fiduciary obligations;
- rights of Data Principals;
- grievance redressal;
- processing of children's data;
- cross-border processing provisions;
- exemptions;
- Data Protection Board of India.

The Act's structure includes obligations of Data Fiduciaries, rights and duties of Data Principals, special provisions, exemptions and the Data Protection Board. citeturn0search28

D-AIGAAF should map these concepts into its data-governance and legal/policy processes rather than attempting to redefine them.

## 5. High-Level Crosswalk

| DPDP Area | D-AIGAAF Modules | D-AIGAAF Treatment |
|---|---|---|
| Purpose and lawful processing | 02 Mission & Use Case; 21 Legal & Policy | Establishes lawful and authorised purpose for data use |
| Data governance | 05 Data & Information | Governs ownership, handling, quality, integrity, provenance and lifecycle |
| Data Fiduciary accountability | 01 Strategy & Governance; 05 Data & Information | Maps legal accountability into organisational governance |
| Consent | 05 Data & Information; 21 Legal & Policy | Incorporates consent requirements where applicable |
| Certain legitimate uses | 21 Legal & Policy; 02 Mission & Use Case | Requires documented legal basis where applicable |
| Data Principal rights | 05 Data & Information; 21 Legal & Policy | Establishes processes to address applicable rights |
| Data security | 06 AI Security; 05 Data & Information | Extends data-security obligations into AI-specific security |
| Data retention / disposal | 05 Data & Information; 26 Retirement & Decommissioning | Aligns lifecycle retention and disposal with applicable requirements |
| Children's data | 05 Data & Information; 21 Legal & Policy | Applies additional controls where relevant |
| Significant Data Fiduciary obligations | 01 Governance; 05 Data; 06 Security; 16 Audit & Evidence | Integrates enhanced governance where applicable |
| Breach / incident response | 14 Incident & Fail-Safe; 06 AI Security | Connects personal-data incidents to AI incident governance |
| Cross-border data considerations | 05 Data; 07 Supply Chain & Sovereignty; 21 Legal & Policy | Assesses jurisdictional and dependency implications |
| Governance records | 16 Audit & Evidence; 25 Documentation & Knowledge | Maintains evidence of data-governance decisions |
| Data protection oversight | 01 Governance; 16 Audit & Evidence | Establishes internal accountability and review |

## 6. Data Purpose and Mission Definition

D-AIGAAF begins AI governance with mission and use-case definition.

Where personal data is involved, the organisation should explicitly document:

- why the data is required;
- what AI capability uses it;
- what processing is performed;
- who determines the purpose and means of processing;
- what outputs are produced;
- who can access the data;
- how long it is required;
- what dependencies exist;
- what legal basis applies;
- what restrictions apply.

This connects DPDP requirements with the D-AIGAAF principle:

> **Data should have a defined and authorised purpose within the AI lifecycle.**

Mission necessity should not be used as a substitute for legal assessment.

## 7. Data Minimisation and AI Design

Data protection and AI development can create tension where more data appears to improve model performance.

D-AIGAAF therefore requires organisations to consider whether the desired mission outcome can be achieved with:

- less personal data;
- less granular data;
- anonymised or otherwise appropriately transformed data;
- synthetic data where suitable;
- restricted access;
- shorter retention;
- narrower collection;
- alternative non-personal data.

The relevant design principle is:

> **Collecting or retaining more personal data is not automatically justified merely because it may improve an AI model.**

The trade-off should be documented and assessed under applicable law and mission requirements.

## 8. Data Quality, Integrity and Provenance

DPDP compliance does not by itself establish that data is suitable for AI.

D-AIGAAF therefore separates:

**Data protection**

from

**Data quality**

from

**Data integrity**

from

**Data provenance**

from

**Data representativeness**.

An organisation can lawfully process data while still using data that is:

- inaccurate;
- incomplete;
- biased;
- stale;
- manipulated;
- poorly sourced;
- unrepresentative;
- incorrectly labelled.

D-AIGAAF requires these AI-specific risks to be addressed through Module 05 and TEVV.

## 9. Data Principal Rights and AI Systems

Where applicable, rights provided by the DPDP framework must be considered in AI data flows.

This can affect:

- training datasets;
- validation datasets;
- operational datasets;
- user profiles;
- records containing personal information;
- AI-generated outputs containing personal data;
- data retention;
- correction or deletion processes;
- grievance processes.

Organisations should identify where personal-data rights interact with:

- model training;
- model retraining;
- data lineage;
- backups;
- derived datasets;
- embeddings;
- vector stores;
- logs;
- model outputs.

D-AIGAAF therefore treats data-rights implications as part of lifecycle governance rather than only a database-management issue.

## 10. Personal Data in Model Training

AI systems create particular challenges where personal data becomes embedded in models or derived artefacts.

D-AIGAAF requires assessment of:

- whether personal data is present in training data;
- whether its use is legally permitted;
- whether data is appropriately documented;
- whether provenance is known;
- whether retention is justified;
- whether model outputs could expose personal information;
- whether retraining or model updates alter the legal or risk position;
- whether downstream systems introduce additional processing.

The framework does not assume that removing the original database automatically removes every privacy risk from an AI system.

Model behaviour, generated outputs and associated artefacts should therefore be considered where relevant.

## 11. Security of Personal Data

The DPDP framework contains obligations concerning protection of personal data.

D-AIGAAF incorporates this through both:

- Module 05 — Data & Information; and
- Module 06 — AI Security.

The security assessment should consider:

- access control;
- authentication;
- authorisation;
- encryption where appropriate;
- data integrity;
- secure storage;
- secure transmission;
- logging;
- monitoring;
- privileged access;
- supply-chain dependencies;
- model access;
- output exposure;
- adversarial attacks.

AI-specific security can introduce additional risks, including:

- membership inference;
- model inversion;
- training-data extraction;
- prompt manipulation;
- insecure retrieval;
- compromised plugins/tools;
- excessive model permissions;
- data leakage through outputs.

These risks are beyond a simple privacy-policy assessment and require AI-security controls.

## 12. Data Breach and Incident Governance

Where a personal-data incident occurs, D-AIGAAF connects data-protection response to its broader incident architecture.

The incident process should support:

**Detection → Classification → Protective Response → Notification where legally required → Investigation → Containment → Recovery → Corrective Action → Assurance Review → Reauthorisation where required**

Relevant records should establish:

- what happened;
- what data was affected;
- what AI system was involved;
- what caused the event;
- what controls failed;
- what decisions were taken;
- what notifications were required;
- what corrective actions were implemented;
- whether previous assurance remains valid.

The AI incident process should therefore not replace the organisation's legal data-breach process.

It should integrate with it.

## 13. Significant Data Fiduciary Considerations

The DPDP Act provides additional obligations for a Significant Data Fiduciary.

Where an organisation or activity falls within that category, D-AIGAAF should incorporate applicable enhanced requirements into:

- governance;
- risk assessment;
- data protection;
- audit;
- monitoring;
- documentation;
- security;
- accountability.

The classification should be determined according to the Act and applicable Government notifications/rules rather than inferred solely from the importance of a defence AI system.

## 14. Children's Data

Where a D-AIGAAF-governed system processes data relating to children and the DPDP framework applies, additional legal requirements must be incorporated.

This can be particularly relevant for AI systems involving:

- recruitment or training platforms;
- educational systems;
- public-facing services;
- healthcare or welfare applications;
- social or behavioural datasets.

The framework should identify whether children's data is present and ensure that the applicable legal controls are reflected in:

- data collection;
- consent or lawful processing;
- processing restrictions;
- model development;
- retention;
- access;
- outputs.

## 15. Cross-Border Processing and Supply Chain

AI systems frequently involve:

- cloud providers;
- model providers;
- data processors;
- APIs;
- SaaS platforms;
- external datasets;
- international suppliers;
- multinational development teams.

D-AIGAAF therefore connects DPDP considerations with Module 07 — Supply Chain & Sovereignty.

The assessment should consider:

- where data is stored;
- where processing occurs;
- who can access it;
- what suppliers are involved;
- what jurisdictions apply;
- what contractual controls exist;
- what dependencies exist;
- what happens if a supplier changes its service or jurisdiction.

Cross-border processing should be assessed against the current legal position under the DPDP framework and any applicable Government requirements.

## 16. Retention and Disposal

Personal data should not automatically remain in AI environments indefinitely.

D-AIGAAF requires lifecycle consideration of:

- source data;
- training datasets;
- validation datasets;
- operational logs;
- user records;
- derived datasets;
- embeddings;
- vector stores;
- backups;
- model artefacts;
- archived records.

Retention should be linked to:

- legal requirements;
- mission necessity;
- assurance requirements;
- audit requirements;
- security requirements;
- contractual obligations.

When data is no longer legitimately required, appropriate disposal or other legally compliant treatment should be considered.

## 17. DPDP and AI Lifecycle

The DPDP framework should be considered at every relevant D-AIGAAF lifecycle stage.

| D-AIGAAF Stage | DPDP Consideration |
|---|---|
| Mission Need | Purpose and necessity for personal data |
| Requirements | Applicable legal and data-protection requirements |
| Data Preparation | Collection, lawful basis, quality and governance |
| Model Development | Training-data use and privacy risks |
| Integration | Access, data flows and third-party dependencies |
| TEVV | Appropriate use of personal data in testing |
| Deployment | Access, monitoring and operational data handling |
| Employment | Ongoing processing and user/data rights |
| Monitoring | Security, compliance and data-governance monitoring |
| Incident | Personal-data breach response |
| Change | Impact of model/data changes |
| Revalidation | Reassessment where processing materially changes |
| Retirement | Data retention, archival and disposal |
| Decommissioning | Removal or controlled retention of associated data |

## 18. DPDP and D-AIGAAF Golden Thread

The relationship can be expressed as:

**Mission Need**
→ establish why personal data is required

**Risk**
→ assess privacy, security and AI risks

**Requirements**
→ translate applicable DPDP obligations into requirements

**Controls**
→ data governance, access, security and lifecycle controls

**Testing**
→ verify controls and AI-specific privacy/security behaviour

**Evidence**
→ maintain records of processing, controls and decisions

**Assurance**
→ establish continuing confidence in data governance

**Authority**
→ identify accountable data and AI authorities

**Conditions**
→ define permissible processing

**Boundaries**
→ limit data access and use

**Employment**
→ govern operational processing

**Monitoring**
→ detect privacy, security and governance issues

**Incident / Change**
→ respond to breaches and changed processing

**Learning**
→ improve controls

**Revalidation / Reauthorisation**
→ reassess where material data or system changes occur

## 19. DPDP Is Not an AI Governance Framework

This distinction is fundamental.

The DPDP framework primarily addresses the governance of **digital personal data**.

It does not by itself establish:

- whether an AI model is reliable;
- whether an AI system is safe;
- whether an AI system is secure against adversarial attacks;
- whether autonomy is appropriate;
- whether a human has meaningful control;
- whether a model performs adequately in a military environment;
- whether a capability should receive operational authorisation;
- whether a weapon-related AI capability is appropriate for a mission;
- whether TEVV is sufficient.

D-AIGAAF therefore treats DPDP compliance as one component of a much broader governance architecture.

## 20. Defence-Specific Considerations

Defence organisations may process information under complex combinations of:

- personal-data law;
- security requirements;
- defence policy;
- operational requirements;
- contractual obligations;
- classification rules;
- records requirements;
- international arrangements.

D-AIGAAF therefore requires a **legal applicability assessment** rather than a blanket assumption that one framework overrides another.

Where a legal exemption applies, the organisation should document:

- the legal basis for the exemption;
- its scope;
- the activities covered;
- the responsible authority;
- any residual privacy or ethical controls that remain applicable.

A legal exemption should not automatically be interpreted as a removal of all responsible-data governance.

## 21. Evidence Expectations

Evidence supporting DPDP alignment may include:

- data inventories;
- processing records;
- data-flow diagrams;
- purpose statements;
- legal-basis assessments;
- consent records where applicable;
- access-control records;
- security assessments;
- data retention schedules;
- deletion/disposal records;
- supplier agreements;
- data-processing assessments;
- incident records;
- grievance records;
- audit reports;
- corrective actions;
- governance approvals.

D-AIGAAF should preserve sufficient evidence to reconstruct important data-governance decisions.

## 22. Relationship to Other Module 19 Crosswalks

Serial 08 is specifically the **Indian data-protection legal layer**.

It complements:

- **Serial 06 — IndiaAI Responsible AI Governance Framework:** responsible-AI principles;
- **Serial 07 — IndiaAI Governance Guidelines:** broader Indian AI-governance policy;
- **Serial 09 — Indian AI Policy and Standards:** wider Indian policy and standards ecosystem;
- **Serial 10 — Defence AI and Responsible AI Principles:** defence-specific responsible-AI principles;
- **Serial 11 — TEVV and AI Assurance Frameworks:** technical and assurance mechanisms;
- **Serial 12 — AI Security and Adversarial Frameworks:** AI-specific security;
- **Serial 13 — Integrated Crosswalk Method:** integration of all applicable frameworks.

## 23. Implementation Method

Organisations implementing D-AIGAAF should apply the following sequence:

### Step 1 — Identify data

Determine whether the AI system processes digital personal data.

### Step 2 — Determine applicability

Assess whether the DPDP Act and relevant provisions apply.

### Step 3 — Identify legal obligations

Map applicable provisions to the system and processing activity.

### Step 4 — Translate into requirements

Create explicit AI/data governance requirements.

### Step 5 — Implement controls

Apply data, security, access, lifecycle and accountability controls.

### Step 6 — Evaluate

Test whether controls function as intended.

### Step 7 — Record evidence

Maintain evidence of decisions and implementation.

### Step 8 — Monitor

Monitor processing, security, incidents and changes.

### Step 9 — Reassess

Reassess when data, model, supplier, mission or legal conditions change.

## 24. Limitations

This crosswalk does not constitute legal advice.

It does not claim:

- that every D-AIGAAF system is subject to the DPDP Act;
- that every defence system is exempt;
- that the DPDP Act provides complete AI governance;
- that DPDP compliance establishes AI safety;
- that DPDP compliance establishes operational authorisation;
- that this crosswalk substitutes for legal review; or
- that the current legal position will remain unchanged.

The latest official Government of India and MeitY materials should be consulted before formal compliance decisions.

## 25. Primary References

- **Digital Personal Data Protection Act, 2023**, India Code. The Act is Act No. 22 of 2023 and was enacted on 11 August 2023. citeturn0search3turn0search26
- **Digital Personal Data Protection Rules, 2025**, Ministry of Electronics and Information Technology. The Rules were notified in November 2025 and contain phased commencement provisions. citeturn0search0turn0search24
- **MeitY Annual Report 2025–26**, describing the DPDP Act and the 2025 Rules and their phased implementation. citeturn0search27
- Current MeitY Act and Policy materials concerning the DPDP framework. citeturn0search4

## 26. Final Crosswalk Position

The DPDP framework provides an essential Indian legal foundation for governing digital personal data.

D-AIGAAF incorporates that foundation while recognising that data protection is only one dimension of defence AI governance.

The resulting architecture is:

**Lawful Data Processing**
→ **Data Governance**
→ **Data Security**
→ **AI-Specific Privacy Risk**
→ **TEVV**
→ **Human Authority**
→ **Operational Governance**
→ **Continuous Assurance**

The governing principle is:

> **Personal-data compliance is necessary where applicable, but it is not sufficient to establish that an AI capability is safe, secure, reliable, authorised or operationally appropriate.**

D-AIGAAF therefore treats the DPDP framework as a distinct legal layer within the larger defence AI governance architecture.
