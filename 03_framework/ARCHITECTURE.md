# Architecture

**Status:** Layer separation accepted. Detailed implementation choices are proposed.

## Separation of concerns

| Layer | Question | Owns | Must not do |
| --- | --- | --- | --- |
| Foundation | Why? | Mission, ethical commitments, scope | Present normative commitments as scientific findings |
| Education | What and how? | Content principles, developmental guidance, activities, evidence | Let data format dictate educational priorities |
| Framework | How is it represented and maintained? | Schemas, templates, identifiers, validation, tools | Define what constitutes a worthy person |
| Governance | Who decides and how? | Editorial review, contributions, change control | Substitute popularity for evidence or rights |

## Flow of decisions

Foundation principles govern educational choices. Educational content explains goals, rationale and experiences. The framework represents and validates this content. Governance reviews changes across all layers.

## Architectural guardrails

1. Parents can use content without running code.
2. Human-readable explanations take priority; structured metadata is added where useful.
3. Substantial educational choices explain purpose, developmental fit, approach, evidence, trade-offs and observation.
4. No identifying child data belongs in this public repository.
5. Local extensions cannot silently override universal guidance.
6. Normative values, empirical claims and practical suggestions must be distinguishable.
7. Technical convenience must not determine educational priorities.
8. Do not build tooling before there is a demonstrated need.

## Deferred decisions

Formal schemas, stable identifier formats, localization structure, evidence classification, assessment rubrics, licenses and release versioning remain subject to review.
