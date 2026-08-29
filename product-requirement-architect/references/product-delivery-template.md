# Product Requirement Delivery Template

Use only sections that help the current decision or implementation. Do not force a full PRD.

```markdown
# [Requirement name]

## 1. Product goal

[Affected user/operation, problem, expected outcome, and success evidence in one short paragraph.]

## 2. Scope and terminology

- [Business term]: [exact meaning]
- [In scope]
- [Out of scope, only when it prevents likely overbuilding]

## 3. Current state and required change

| Area | Current behavior | Required change |
| --- | --- | --- |
| [Existing page/module/flow] | [Evidence-backed behavior] | [Minimum target delta] |

## 4. Core product workflow

```text
[Entry]
→ [Recognition/configuration]
→ [Decision/display/action]
→ [Result/status]
→ [Downstream handling/data]
```

## 5. User-facing changes

### [Page or journey]

- [Retained behavior]
- [Required change]
- [Visibility, interaction, and exception rule]

## 6. Operations and configuration

| Existing function | Required change | Consumer |
| --- | --- | --- |
| [Module/page/service] | [Minimum extension] | [Journey/rule/operation] |

### Configuration fields

| Field | Owner | Required | Stored value | Used by |
| --- | --- | --- | --- | --- |
| [Field] | [Role/system] | [Yes/No] | [ID/value/snapshot] | [Display/decision/report] |

## 7. Rules, states, and data

- [Eligibility or visibility rule]
- [State transition and failure handling]
- [Attribution or historical-data rule]
- [External dependency boundary]

## 8. Migration or launch work

- [One-time mapping/backfill/cleanup and verification; omit if none]

## 9. Acceptance criteria

- [Observable end-to-end pass/fail statement]
- [Field-to-display or configuration-to-decision statement]
- [State/error/history/migration statement]

## 10. Excluded work

- [Only plausible but unnecessary functionality]

## 11. Decisions required

- [Only material unresolved choices]
```

## Writing rules

- Prefer one sentence per rule.
- Use tables only for repeated comparable relationships.
- Do not repeat the same rule across the goal, workflow, function list, and acceptance criteria.
- Keep examples only when they disambiguate a business rule.
- Separate source-backed behavior from confirmed additions and assumptions when provenance matters.
- Do not include roadmap phases, technical architecture, personas, or metrics unless the request needs them.
