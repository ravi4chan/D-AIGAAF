# 35 Operational Authorisation Communication, Notification and Escalation

## 1. Purpose

Operational authorisation depends on timely communication of decisions, conditions, restrictions, incidents, changes and emerging risks to the people who hold operational responsibility.

A technically valid authorisation can become ineffective if relevant authorities are unaware of changes that affect its basis.

This document defines governance for communication, notification and escalation associated with Defence AI operational authorisation.

The objective is to ensure that:

- relevant authorities receive material information in time;
- authorisation conditions are communicated clearly;
- changes in risk or system status are escalated;
- uncertainty and limitations are not hidden;
- degraded and disconnected operations have defined communication arrangements;
- notifications do not themselves create operational authority;
- escalation paths are explicit;
- acknowledgement and handover are traceable; and
- communication failures trigger defined protective responses.

---

## 2. Core Principle

**Information relevant to operational authority shall reach the appropriate human decision-maker in a timely, reliable and traceable manner. Failure to communicate a material change shall not be treated as evidence that the authorisation basis remains valid.**

---

## 3. Communication Object

Authorisation communication should cover:

**Authority → Conditions → Risk → Status → Change → Incident → Decision → Action → Outcome**

The required communication should be proportionate to consequence, autonomy, operational tempo and uncertainty.

---

## 4. Communication Categories

Communication may include:

- authorisation decisions;
- conditions and restrictions;
- readiness status;
- deployment status;
- employment status;
- autonomy status;
- configuration changes;
- environmental changes;
- risk changes;
- security events;
- data integrity concerns;
- incidents;
- suspension/revocation;
- restoration;
- expiry;
- renewal;
- revalidation;
- reauthorisation; and
- lessons learned.

---

## 5. Notification Authority

The organisation should identify who is responsible for:

- generating notification;
- verifying information;
- approving notification where required;
- receiving notification;
- acknowledging receipt;
- escalating unresolved matters; and
- maintaining records.

Responsibilities should be explicit.

---

## 6. Materiality

Not every event requires the same level of notification.

Materiality should consider:

- consequence;
- autonomy;
- mission criticality;
- human-control impact;
- security;
- environmental impact;
- configuration impact;
- dependency impact;
- operational scope; and
- potential effect on authorisation.

Material changes should receive proportionately stronger notification and escalation.

---

## 7. Notification Levels

A working model may use:

- **N1 — Routine Information**
- **N2 — Operational Attention**
- **N3 — Immediate Escalation**
- **N4 — Emergency Protective Notification**

The organisation should define response times and authorities appropriate to each level.

---

## 8. Authorisation Decision Communication

When operational authorisation is granted, relevant personnel should receive the information necessary to understand:

- authorised mission;
- use case;
- environment;
- autonomy;
- human authority;
- configuration;
- conditions;
- restrictions;
- prohibited uses;
- monitoring;
- fail-safe;
- validity; and
- suspension/revocation triggers.

A decision should not be considered operationally effective where required recipients cannot reasonably determine what authority exists.

---

## 9. Conditional Authorisation Communication

Conditions should be communicated in a manner that makes clear:

- what is permitted;
- what is conditional;
- what must be verified;
- who is responsible;
- what monitoring applies;
- what happens if the condition fails; and
- when the condition expires.

Ambiguous conditions create operational risk.

---

## 10. Restriction Communication

Restrictions should identify:

- affected capability;
- affected mission;
- affected environment;
- affected autonomy;
- affected users;
- effective time;
- authority;
- reason;
- required actions; and
- conditions for removal.

Restrictions should be visible to personnel who could otherwise initiate prohibited employment.

---

## 11. Suspension and Revocation Communication

Suspension or revocation should be communicated promptly to relevant operational, technical, assurance and security authorities.

The notification should identify:

- scope;
- effective point;
- reason;
- immediate actions;
- prohibited employment;
- evidence preservation requirements;
- investigation arrangements;
- restoration or reauthorisation requirements; and
- responsible authority.

---

## 12. Risk Escalation

Risk should be escalated when:

- residual risk increases;
- consequence changes;
- controls fail;
- uncertainty becomes material;
- human control is degraded;
- autonomy increases unexpectedly;
- security is compromised;
- environmental conditions change materially;
- critical dependencies fail; or
- evidence contradicts the authorisation basis.

Escalation should preserve existing boundaries while the matter is resolved.

---

## 13. AI Behaviour Escalation

Unexpected AI behaviour should be communicated according to its potential consequence.

Examples include:

- unexplained outputs;
- abnormal confidence;
- unexpected recommendations;
- repeated errors;
- unexpected autonomy transitions;
- unexplained actions;
- failure to follow constraints; or
- behaviour inconsistent with tested characteristics.

Where necessary, immediate protective action should precede full investigation.

---

## 14. Uncertainty Communication

Material uncertainty should be communicated to the responsible human authority.

Relevant uncertainty may concern:

- data;
- model output;
- environment;
- sensor information;
- system state;
- autonomy;
- security;
- dependencies; or
- mission context.

AI-generated confidence should not replace human understanding of uncertainty.

---

## 15. Human Authority Communication

Personnel should know:

- who currently holds operational authority;
- who may intervene;
- who may override;
- who may restrict;
- who may suspend;
- who may restore;
- who accepts risk; and
- who is responsible for escalation.

Authority ambiguity should be treated as a governance issue.

---

## 16. Autonomy Status Communication

Where autonomy is material, relevant personnel should be able to determine:

- authorised autonomy;
- current autonomy;
- permitted transitions;
- human supervision;
- intervention capability;
- autonomy restrictions; and
- conditions requiring reduction or termination of autonomy.

A mismatch between authorised and observed autonomy should trigger escalation.

---

## 17. Configuration Change Notification

Material configuration changes should be communicated before operational use where practicable.

Notification should identify:

- previous configuration;
- new configuration;
- change;
- reason;
- assurance status;
- authorisation impact;
- restrictions;
- testing;
- approval; and
- effective time.

Unauthorised configuration changes should be escalated.

---

## 18. Environmental Change Notification

Material environmental changes should be communicated when they may affect:

- system performance;
- sensors;
- communications;
- navigation;
- human control;
- autonomy;
- security;
- mission effectiveness; or
- operating boundaries.

The response may include increased monitoring, restriction, reduced autonomy, human control, safe state or suspension.

---

## 19. Security Notification

Security concerns affecting AI should be communicated to the appropriate security and operational authorities.

Examples include:

- suspected compromise;
- adversarial manipulation;
- data poisoning;
- model integrity concerns;
- unauthorised change;
- credential or access compromise;
- dependency compromise; or
- loss of security monitoring.

Security notification should be linked to operational response.

---

## 20. Dependency Failure Notification

Failure or degradation of critical dependencies should be communicated where it affects operational authority.

Dependencies may include:

- communications;
- navigation;
- sensors;
- compute;
- external services;
- data providers;
- security services;
- suppliers; or
- other AI systems.

The notification should identify operational impact and applicable fallback.

---

## 21. Degraded and Disconnected Operations

Where communications are degraded or unavailable, predefined local notification and escalation procedures should apply where practicable.

These should identify:

- local authority;
- permitted actions;
- escalation options;
- autonomy limits;
- protective procedures;
- evidence capture; and
- reconciliation after connectivity is restored.

Loss of communication should not create unrestricted AI authority.

---

## 22. Emergency Notification

Emergency notification should prioritise information necessary for immediate protective action.

It should communicate, where practicable:

- what happened;
- current system state;
- immediate risk;
- human-control status;
- autonomy;
- action taken;
- authority;
- required next action; and
- escalation status.

Detailed reporting may follow after immediate risk is controlled.

---

## 23. Escalation Path

A generic escalation path may be:

**Operator/User → System Manager → OAIA → Operational/Command Authority → Technical/Assurance/Security Authority → Authorising Authority**

The actual path should depend on the issue and organisational decision rights.

Emergency protective authority may bypass normal sequencing where delay could create unacceptable harm.

---

## 24. OAIA Role

The Operational AI Advisor may support communication by translating between:

- operational context;
- AI behaviour;
- system limitations;
- risk;
- assurance evidence;
- autonomy; and
- command decision requirements.

The OAIA should not become an informal substitute for the authorised decision-maker.

---

## 25. Communication Acknowledgement

Material notifications should have an acknowledgement mechanism where practicable.

Acknowledgement should establish that the recipient:

- received the notification;
- understood the required action;
- identified any inability to comply; and
- escalated unresolved issues where necessary.

Acknowledgement does not itself constitute authorisation.

---

## 26. Handover Communication

During transfer of operational authority, the outgoing authority should communicate:

- current authorisation;
- conditions;
- restrictions;
- readiness;
- configuration;
- autonomy;
- environment;
- incidents;
- risks;
- dependencies;
- current status; and
- outstanding actions.

The receiving authority should confirm sufficient understanding before assuming consequential responsibility.

---

## 27. Multi-Organisation Communication

Where responsibility crosses organisational boundaries, communication arrangements should identify:

- respective authorities;
- information responsibilities;
- notification triggers;
- escalation paths;
- security constraints;
- dependency responsibilities;
- incident responsibilities; and
- decision rights.

Inter-organisational communication should not create ambiguous authority.

---

## 28. Communication Failure

Failure to communicate a material event should itself be treated as a governance concern.

Possible responses include:

- retry;
- alternate communication;
- increased local supervision;
- restricted operation;
- reduced autonomy;
- safe state; or
- suspension.

The response should depend on consequence and the importance of the missing information.

---

## 29. Communication Integrity

Material authorisation information should be protected against:

- alteration;
- loss;
- unauthorised disclosure;
- spoofing;
- delayed delivery;
- ambiguity; and
- conflicting versions.

Personnel should be able to identify the authoritative version of an operational decision where practicable.

---

## 30. Conflicting Notifications

Where different authorities or systems provide conflicting information, the organisation should use defined reconciliation procedures.

Examples include:

- authorisation status conflict;
- autonomy status conflict;
- configuration status conflict;
- suspension notification conflict; or
- conflicting command direction.

Unresolved conflict should not be interpreted as permission for higher-risk activity.

---

## 31. Communication Records

Material communications should be recorded where appropriate.

Records may include:

- notification;
- sender;
- recipient;
- date/time;
- subject;
- authority;
- decision;
- acknowledgement;
- action required;
- escalation;
- outcome; and
- linked evidence.

Records should support later reconstruction of the decision process.

---

## 32. Communication and Auditability

Communication records should support reconstruction of:

**Event → Notification → Recipient → Authority → Decision → Action → Outcome**

This supports accountability, assurance, investigation and lessons learned.

---

## 33. Continuous Assurance

Communication failures, delayed notifications and repeated escalation events should feed into continuous assurance.

The organisation should assess whether they indicate:

- inadequate procedures;
- unclear authority;
- insufficient staffing;
- weak monitoring;
- poor system design;
- communication dependency;
- training deficiencies; or
- governance weaknesses.

---

## 34. Governance Review

Communication and escalation arrangements should be reviewed after:

- incidents;
- missed notifications;
- delayed escalation;
- authority disputes;
- communication failures;
- degraded operations;
- security events;
- significant changes; or
- lessons learned.

Exercises should test communication under time pressure and degraded conditions.

---

## 35. Communication Register

A controlled Communication and Escalation Register may contain:

- notification type;
- trigger;
- severity;
- sender;
- recipient;
- authority;
- required response;
- acknowledgement;
- escalation path;
- time requirement;
- record;
- status; and
- review date.

---

## 36. Golden Thread

Communication and escalation remain connected to the D-AIGAAF Golden Thread:

**Mission Need → Risk → Requirements → Controls → Testing → Evidence → Assurance → Authority → Conditions → Employment → Monitoring → Change/Incident → Notification → Decision → Action → Revalidation/Reauthorisation**

---

## 37. Governance Questions

Responsible authorities should be able to determine:

1. Who must be informed?
2. What information must be communicated?
3. How quickly must it be communicated?
4. What makes an event material?
5. Who owns notification?
6. Who receives it?
7. Who acknowledges it?
8. What happens if acknowledgement is not received?
9. What requires immediate escalation?
10. Who can order protective action?
11. Who holds operational authority?
12. Who accepts risk?
13. How is autonomy status communicated?
14. How are configuration changes communicated?
15. How are environmental and security changes communicated?
16. What happens when communications are degraded?
17. What happens when communications are unavailable?
18. How are conflicting instructions resolved?
19. Are communications traceable?
20. Can the organisation reconstruct who knew what, when, and what decision followed?

---

## 38. Core Rule

> **Material information affecting Defence AI operational authority, risk, autonomy, human control, configuration, environment, security, dependencies or operational status shall be communicated and escalated to the appropriate human authorities through defined and traceable arrangements. Communication failure, delayed notification or uncertainty about authority shall not create implied permission to continue higher-risk activity and shall trigger proportionate protective action where required.**
