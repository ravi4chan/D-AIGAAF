# 03 — Evidence Collection and Integrity

## 1. Purpose

This document defines how audit evidence is identified, requested, collected, verified, protected, assessed, and preserved within D-AIGAAF.

It establishes requirements for ensuring that evidence supporting audit conclusions is relevant, sufficient, reliable, authentic, appropriately current, and traceable.

Detailed audit testing and findings are addressed in `04_Audit_Testing_and_Findings.md`. Detailed records and retention requirements are addressed in `08_Audit_Records_Traceability_and_Retention.md`.

---

## 2. Evidence Principle

Audit conclusions should be based on evidence appropriate to the claim or criterion being assessed.

The fundamental chain is:

**Criterion → Control → Claim → Evidence → Assessment → Conclusion**

Evidence demonstrating that a control exists does not necessarily demonstrate that the control operates effectively.

---

## 3. Evidence Definition

Audit evidence is information used to support:

- assessment of criteria;
- assessment of control design;
- assessment of implementation;
- assessment of operation;
- assessment of effectiveness;
- identification of findings;
- formation of audit conclusions.

Evidence may be documentary, technical, operational, human, physical, or digital.

---

## 4. Evidence Sources

Potential evidence includes:

### Governance Evidence
- policies;
- procedures;
- approvals;
- committee records;
- risk assessments;
- authorisations;
- decision records.

### Technical Evidence
- system configurations;
- model or software versions;
- logs;
- test results;
- performance measurements;
- security records.

### Operational Evidence
- employment records;
- monitoring data;
- intervention records;
- incident records;
- operational observations;
- lessons learned.

### Human Evidence
- interviews;
- competence records;
- training records;
- role assignments;
- decision records.

### Supplier Evidence
- contractual records;
- supplier assessments;
- provenance information;
- assurance reports;
- dependency records.

---

## 5. Evidence Planning

Evidence requirements should be identified during audit planning.

The evidence plan should consider:

- audit objective;
- criteria;
- control objectives;
- risk;
- audit scope;
- time period;
- configuration;
- environment;
- autonomy;
- human authority;
- dependencies;
- expected decision use.

Evidence requirements should be proportionate to consequence.

---

## 6. Evidence Request

Evidence requests should identify, as appropriate:

- requested item;
- purpose;
- relevant criterion;
- applicable period;
- required configuration or version;
- responsible provider;
- required format;
- deadline;
- handling requirements.

Requests should be sufficiently specific to minimise ambiguity.

---

## 7. Evidence Acquisition

Evidence may be acquired through:

- controlled document provision;
- system access;
- observation;
- interviews;
- sampling;
- system-generated records;
- technical extraction;
- independent sources;
- supplier submissions;
- authorised operational records.

The acquisition method should be recorded where material to evidence reliability.

---

## 8. Evidence Provenance

Evidence provenance describes where evidence came from and how it was obtained.

Where relevant, provenance should capture:

- source;
- owner;
- collection method;
- date and time;
- applicable system;
- configuration or version;
- environment;
- transformation or processing;
- person or system responsible for extraction.

Provenance should support later reconstruction.

---

## 9. Evidence Authenticity

Evidence authenticity concerns whether evidence is what it is represented to be.

Where appropriate, auditors should consider:

- source identity;
- system of origin;
- timestamps;
- digital signatures;
- access records;
- version identifiers;
- independent corroboration;
- chain of custody.

Verification should be proportionate to risk and consequence.

---

## 10. Evidence Integrity

Evidence integrity concerns protection against inappropriate alteration, corruption, deletion, substitution, or manipulation.

Controls may include:

- access restrictions;
- protected storage;
- version control;
- integrity mechanisms where appropriate;
- audit trails;
- controlled transfer;
- checksums or hashes where appropriate;
- segregation of duties.

---

## 11. Chain of Custody

For material evidence, a chain of custody may be required.

It should establish:

**Collected → Transferred → Stored → Accessed → Analysed → Reported → Retained/Disposed**

Material custody events and responsible parties should be identifiable.

---

## 12. Evidence Identification

Evidence should be uniquely identifiable where practical.

Identification may include:

- evidence ID;
- source;
- record name;
- version;
- date;
- configuration;
- collection event;
- related audit;
- related criterion.

---

## 13. Evidence Classification

Evidence may be classified according to applicable handling requirements, such as:

- public;
- organisational;
- restricted;
- sensitive;
- operationally sensitive;
- legally protected.

Audit governance does not require unnecessary disclosure of sensitive operational information.

---

## 14. Evidence Relevance

Evidence is relevant when it directly or materially informs the criterion, control, risk, or claim being assessed.

Evidence should not be included merely because it is available.

---

## 15. Evidence Sufficiency

Evidence is sufficient when there is enough appropriate information to support the intended conclusion.

Sufficiency should consider:

- consequence;
- risk;
- complexity;
- control significance;
- evidence quality;
- independence;
- population;
- sampling;
- contradictory information.

---

## 16. Evidence Reliability

Reliability concerns the degree to which evidence can reasonably be depended upon.

Factors may include:

- source reliability;
- independence;
- directness;
- consistency;
- collection method;
- integrity;
- corroboration;
- susceptibility to manipulation.

---

## 17. Direct and Indirect Evidence

### Direct Evidence

Evidence that directly demonstrates the relevant condition.

Examples include:

- system records;
- configuration state;
- observed control operation;
- authorised decision record.

### Indirect Evidence

Evidence that supports a conclusion through inference or corroboration.

Examples include:

- management representations;
- related monitoring trends;
- secondary records.

Indirect evidence should not automatically be treated as equivalent to direct evidence.

---

## 18. Corroboration

Important conclusions should be corroborated where appropriate.

Corroboration may compare:

- system logs with operational records;
- authorisation records with configuration;
- test results with deployment state;
- interview statements with documentary evidence;
- supplier claims with independent records.

Material discrepancies should be investigated.

---

## 19. Management Representations

Management representations may provide context or identify evidence sources.

They should not automatically substitute for evidence where independent verification is reasonably available.

Where a material conclusion relies substantially on representation, the limitation should be recorded.

---

## 20. Evidence Currency

Evidence should be sufficiently current for the decision it supports.

Currency should consider:

- model changes;
- software updates;
- hardware changes;
- data changes;
- configuration changes;
- environmental changes;
- threat changes;
- policy changes;
- operational experience.

Old evidence may remain useful for historical questions but may not support current operational claims.

---

## 21. Configuration Traceability

Where audit conclusions concern an AI capability, evidence should be traceable to the relevant configuration where practical.

This may include:

- model version;
- software version;
- hardware configuration;
- data version;
- policy configuration;
- interface version;
- autonomy configuration;
- dependency versions.

Evidence from an unverified configuration should be treated cautiously.

---

## 22. Temporal Traceability

Evidence should be associated with an appropriate point or period in time.

This is particularly important for:

- recurring controls;
- incidents;
- changes;
- operational employment;
- monitoring;
- authorisation conditions;
- performance;
- security events.

---

## 23. Environmental Context

Where relevant, evidence should identify the operational environment in which it was generated.

Relevant context may include:

- nominal conditions;
- degraded conditions;
- disconnected conditions;
- adversarial conditions;
- communications state;
- sensor conditions;
- human workload;
- dependency status.

Evidence demonstrated under one environment should not automatically be generalised to all environments.

---

## 24. Human-Generated Evidence

Interviews, observations, and human decisions can provide valuable evidence.

Auditors should consider:

- role of the individual;
- competence;
- proximity to the activity;
- contemporaneity;
- consistency with other evidence;
- potential bias;
- ability to independently verify the statement.

---

## 25. System-Generated Evidence

System-generated records may include:

- logs;
- alerts;
- configuration records;
- performance metrics;
- access records;
- autonomy-state records;
- intervention records;
- incident records.

Reliability depends on whether the underlying system generating the evidence is itself appropriately configured, protected, and governed.

---

## 26. AI-Generated Evidence

Where AI-generated outputs are used as audit evidence, they should not be treated as inherently authoritative.

The audit should consider:

- source;
- generation method;
- model/version;
- input context where material;
- validation;
- corroboration;
- uncertainty;
- potential confabulation or error.

AI-generated information should generally be independently verified before supporting a material audit conclusion.

---

## 27. Evidence Transformation

Evidence may be transformed through:

- extraction;
- filtering;
- aggregation;
- conversion;
- analysis;
- anonymisation;
- redaction.

Material transformations should be documented sufficiently to connect the audit evidence to the original source.

---

## 28. Evidence Sampling

Where complete population review is impractical, sampling may be used.

Sampling should consider:

- audit objective;
- population;
- risk;
- consequence;
- expected variability;
- previous findings;
- unusual cases;
- recent changes.

Sampling limitations should be recorded.

---

## 29. Evidence Completeness

Evidence completeness concerns whether material information required to support the audit conclusion has been obtained.

Potential gaps include:

- missing records;
- unavailable historical data;
- omitted exceptions;
- incomplete system logs;
- missing change records;
- absent configuration information.

Known gaps should remain visible in the audit record.

---

## 30. Evidence Gaps

An evidence gap exists where available information is insufficient to support the intended assessment.

Possible responses include:

- obtain additional evidence;
- perform additional testing;
- narrow the conclusion;
- record an evidence limitation;
- raise a finding where appropriate;
- escalate where consequence warrants.

Evidence gaps should not be silently filled through assumptions.

---

## 31. Contradictory Evidence

Where evidence conflicts, auditors should:

1. identify the conflict;
2. assess source reliability;
3. investigate the difference;
4. seek corroboration;
5. document the outcome;
6. reflect unresolved uncertainty in the conclusion.

Contradictory evidence may itself indicate a governance or control weakness.

---

## 32. Negative Evidence

Evidence indicating that a control failed, a condition was breached, or an expected outcome did not occur should be retained and considered.

Negative evidence should not be discarded merely because it conflicts with the expected governance narrative.

---

## 33. Evidence Security

Evidence should be protected against:

- unauthorised access;
- alteration;
- deletion;
- disclosure;
- loss;
- inappropriate copying;
- unauthorised transfer.

Security requirements should reflect evidence sensitivity and consequence.

---

## 34. Evidence Access

Access should follow applicable least-privilege and need-to-know principles.

Access restrictions should not prevent authorised auditors from obtaining sufficient information to perform the audit.

Material access restrictions should be recorded.

---

## 35. Evidence Retention

Evidence should be retained for the period required by:

- applicable law;
- organisational policy;
- contractual requirements;
- audit requirements;
- operational requirements;
- applicable investigation or legal holds.

Detailed retention requirements are addressed in `08_Audit_Records_Traceability_and_Retention.md`.

---

## 36. Evidence Disposal

When evidence reaches the end of its approved retention period, disposal should follow applicable requirements.

Disposal should consider:

- sensitivity;
- legal holds;
- operational need;
- audit traceability;
- security;
- privacy;
- contractual requirements.

---

## 37. Evidence Quality Assessment

Material evidence should be assessed against relevant characteristics:

| Characteristic | Question |
|---|---|
| Relevance | Does it address the criterion or claim? |
| Sufficiency | Is there enough to support the conclusion? |
| Reliability | Can it reasonably be depended upon? |
| Integrity | Has it remained protected from inappropriate alteration? |
| Authenticity | Is it what it claims to be? |
| Currency | Is it sufficiently current? |
| Provenance | Can its origin be established? |
| Traceability | Can it be linked to the relevant system, event, or decision? |
| Independence | Is it sufficiently independent for its intended use? |

---

## 38. Evidence Status

D-AIGAAF may classify evidence as:

- **Demonstrated**
- **Partially Demonstrated**
- **Indirectly Supported**
- **Untested**
- **Contradicted**
- **Unavailable**
- **Insufficient**

Evidence status should not be confused with the overall control assessment.

---

## 39. Evidence and Assurance Confidence

Evidence contributes to assurance confidence based on:

- quality;
- coverage;
- relevance;
- currency;
- representativeness;
- independence;
- consistency.

A large evidence volume may still produce low confidence if evidence is stale, biased, poorly representative, or contradictory.

---

## 40. Evidence Register

For material audits, an evidence register should be maintained where appropriate.

| Evidence ID | Criterion | Source | Date | Configuration | Type | Status | Integrity | Assessment Use |
|---|---|---|---|---|---|---|---|---|

The register should support traceability from audit conclusion back to source evidence.

---

## 41. Evidence Handling During Audit

Auditors should:

- preserve original evidence where practicable;
- distinguish originals from working copies;
- record material transformations;
- control access;
- avoid unnecessary modification;
- preserve relevant metadata;
- document significant evidence decisions.

---

## 42. Sensitive Operational Information

D-AIGAAF is intended as a generic and unclassified governance framework.

Audit evidence may nevertheless contain sensitive information.

The framework therefore requires appropriate protection and controlled handling without requiring sensitive operational details to be embedded in the public framework itself.

---

## 43. Evidence Integrity Failure

Where evidence may have been altered, lost, corrupted, fabricated, or otherwise compromised, auditors should:

- preserve available evidence;
- identify the integrity concern;
- assess impact on conclusions;
- seek alternative or corroborating evidence;
- escalate where material;
- consider incident or investigation processes where applicable.

An integrity concern affecting critical evidence may invalidate a related audit conclusion.

---

## 44. Evidence Collection Review

Before conclusions are finalised, the audit team should review whether evidence is:

- sufficient;
- appropriate;
- traceable;
- current;
- internally consistent;
- relevant to the criteria;
- adequate for the intended conclusion.

Material evidence gaps should remain visible.

---

## 45. Integration with D-AIGAAF

Evidence collection and integrity should integrate with:

- Module 04 — AI Lifecycle;
- Module 05 — Data & Information;
- Module 06 — AI Security;
- Module 09 — TEVV;
- Module 10 — Operational Environment;
- Module 11 — Operational Authorisation;
- Module 12 — Operational Employment;
- Module 13 — Continuous Assurance;
- Module 14 — Incident & Fail-Safe;
- Module 15 — Change & Reauthorisation.

Evidence should remain traceable across these governance domains where it supports common claims.

---

## 46. Evidence Governance Model

D-AIGAAF uses:

**Identify → Request → Collect → Authenticate → Protect → Assess → Corroborate → Trace → Preserve → Use → Review → Retain/Dispose**

This lifecycle provides a controlled basis for evidence used in audit conclusions.

---

## 47. Core Rule

**Evidence is not merely information collected during an audit. It is the foundation on which governance conclusions are justified. D-AIGAAF requires material evidence to be relevant, sufficient, reliable, appropriately current, traceable, and protected against inappropriate alteration or loss. Where evidence is incomplete, contradictory, stale, or compromised, the limitation must remain visible and the strength of the audit conclusion must be adjusted accordingly.**

---

## 48. Golden Thread

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Boundaries → Employment → Monitoring → Change/Incident → Learning → Revalidation/Reauthorisation → Audit Planning → Criteria → Evidence Collection → Testing → Findings → Corrective Action → Verification**
