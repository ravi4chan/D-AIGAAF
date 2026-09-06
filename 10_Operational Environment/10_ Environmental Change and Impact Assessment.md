# D-AIGAAF — Environmental Change and Impact Assessment

## 1. Purpose

This document defines the process for assessing whether a change in the operational environment could materially affect the assurance, safety, security, mission effectiveness or authorised use of a Defence AI capability.

The objective is to distinguish routine environmental variation from changes that require additional assurance, restriction, revalidation or reauthorisation.

## 2. Core Principle

> **A change in the environment can change the risk of an otherwise unchanged AI capability.**

Environmental change should therefore be assessed independently from software or model change.

## 3. Sources of Environmental Change

Environmental changes may arise from:

- Terrain or physical conditions.
- Weather and illumination.
- Sensor conditions.
- Electromagnetic conditions.
- Communications availability.
- Navigation or positioning conditions.
- Information availability or integrity.
- Data characteristics.
- Computing or power availability.
- Human operating conditions.
- Adversarial activity.
- Mission changes.
- Changes to supporting systems or external dependencies.

## 4. Materiality

Not every environmental change requires formal reauthorisation.

The assessment should determine whether a change is material based on its potential effect on:

- Mission outcome.
- Human safety.
- Property or infrastructure.
- AI performance.
- Reliability.
- Security.
- Human control.
- Autonomy.
- System dependencies.
- Existing assurance evidence.
- Operational boundaries.

## 5. Environmental Change Classification

A practical classification may be:

### Minor

A change that remains within the demonstrated operating envelope and does not materially affect risk or system behaviour.

### Significant

A change that introduces increased uncertainty, changes assumptions or may affect performance or control, but can potentially be managed through additional controls or evidence.

### Material

A change that may invalidate existing evidence, alter risk materially, affect autonomy or human control, or move operation beyond the authorised environmental envelope.

## 6. Impact Assessment

The assessment should consider:

**Environmental Change → Affected Assumption → System Effect → Mission Effect → Risk Change → Control → Evidence Requirement → Governance Decision**

This provides a traceable connection between the environmental change and the resulting governance action.

## 7. Environmental Assumptions

The assessment should identify whether the change affects assumptions used during:

- Requirements definition.
- Development.
- TEVV.
- Operational trials.
- Environmental assessment.
- Risk assessment.
- Operational authorisation.

An assumption that is no longer valid should not remain embedded in the assurance case.

## 8. AI Performance Impact

The assessment should consider whether environmental change may affect:

- Accuracy.
- Reliability.
- Robustness.
- Detection or classification.
- Prediction.
- Data interpretation.
- Response time.
- Decision-support quality.
- Uncertainty estimation.

Where performance may change materially, additional evidence should be obtained.

## 9. Human and Autonomy Impact

Environmental changes should be assessed for their effect on:

- Human workload.
- Situational awareness.
- Intervention time.
- Operator understanding.
- Human oversight.
- Autonomy boundaries.
- Ability to intervene or override.

A condition that reduces effective human control may require reduced autonomy or suspension even when technical performance remains acceptable.

## 10. Degraded and Disconnected Impact

The assessment should consider whether the change affects:

- Communications.
- Data freshness.
- Local processing.
- Sensor availability.
- Navigation.
- External dependencies.
- Recovery or resynchronisation.

Where degradation changes system behaviour, the applicable degraded operating mode should be reviewed.

## 11. Adversarial Impact

Environmental changes may also increase exposure to deliberate manipulation or disruption.

The assessment should consider whether the changed environment:

- Increases attack opportunities.
- Reduces detection capability.
- Weakens information integrity.
- Changes sensor reliability.
- Increases uncertainty.
- Affects human decision-making.

## 12. Evidence Review

Existing evidence should be mapped against the changed environment.

Evidence may be:

- Directly applicable.
- Partially applicable.
- Indirectly informative.
- No longer sufficient.

The assessment should identify evidence gaps rather than assuming that previous testing remains valid.

## 13. Additional Assurance

Depending on materiality, additional assurance may include:

- Analysis.
- Simulation.
- Laboratory testing.
- Environmental testing.
- Operational trials.
- Human factors assessment.
- Security assessment.
- Adversarial evaluation.
- Autonomy evaluation.
- Independent review.

The method should be proportionate to the consequence and uncertainty involved.

## 14. Operational Restrictions

Where additional evidence is not immediately available, temporary controls may include:

- Reduced operating envelope.
- Reduced autonomy.
- Increased human supervision.
- Restricted mission use.
- Additional confirmation requirements.
- Increased monitoring.
- Geographic or environmental restrictions.
- Temporary suspension.

Restrictions should be explicit and recorded.

## 15. Decision Outcomes

An environmental change assessment may result in:

1. **No further action** — change remains within authorised conditions.
2. **Continue with enhanced controls** — additional monitoring or restrictions required.
3. **Additional assurance required** — testing or evaluation required.
4. **Revalidation required** — existing assurance must be revisited.
5. **Reauthorisation required** — operational authority must reconsider the authorised conditions.
6. **Suspension** — continued operation is not justified until assurance is restored.

## 16. Relationship to Operational Authorisation

The assessment should determine whether the environmental change remains within the existing authorisation.

If not, the capability should not simply continue under the assumption that the previous authorisation remains valid.

## 17. Emergency Conditions

Where an environmental change occurs unexpectedly and immediate action is required, pre-authorised emergency procedures may permit protective action.

Such procedures should define:

- Permitted actions.
- Responsible personnel.
- Autonomy limits.
- Fail-safe behaviour.
- Recording requirements.
- Subsequent review.

Emergency procedures should not become a substitute for normal assurance.

## 18. Documentation

The environmental change record should document, as appropriate:

- Description of change.
- Date and context.
- Affected environment.
- Affected assumptions.
- Impact assessment.
- Risk implications.
- Existing evidence.
- Evidence gaps.
- Controls.
- Restrictions.
- Decision.
- Responsible authority.
- Review requirements.

## 19. Continuous Assurance

Environmental change assessment should feed the continuous assurance system.

Recurring environmental changes may indicate that:

- The operating envelope is too narrow.
- Monitoring thresholds require adjustment.
- TEVV needs expansion.
- Risk assumptions need revision.
- Operational restrictions need refinement.

## 20. Governance Questions

Decision-makers should be able to answer:

1. What changed?
2. Which environmental assumptions are affected?
3. Does the change alter AI behaviour or performance?
4. Does it affect human control?
5. Does it affect autonomy?
6. Does it change mission risk?
7. Is existing evidence still applicable?
8. Are additional controls sufficient?
9. Is revalidation required?
10. Is reauthorisation required?

## 21. Core Rule

> **Environmental change must be treated as an assurance event whenever it can materially alter the relationship between the AI capability, its mission, its operating conditions and its authorised risk.**
