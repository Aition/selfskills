# Product Requirement Quality Gates

Use these gates before presenting a requirement as delivery-ready.

## 1. Evidence integrity

- All relevant pages, screenshots, tables, annotations, and user corrections were inspected.
- Current-state evidence is not mistaken for target design.
- Provided facts, confirmed additions, and assumptions remain distinguishable.
- Later additions are not falsely presented as originating in the original document.
- Supplied answers are reused instead of being asked again.

## 2. Product value

- The affected user or operator and their need are identifiable.
- The requested change connects to a user or business outcome.
- Success has observable evidence when measurement is in scope.
- Features without a user, outcome, consumer, risk-control purpose, or acceptance path are removed.

## 3. Terminology and product model

- Each business object has one stable name.
- Similar concepts are explicitly separated, such as user source, promoted brand, publishing platform, and reward provider.
- Actors, entries, objects, identifiers, relations, and ownership are sufficient to explain the workflow.
- Field labels describe business meaning; buttons and placeholders describe actions.

## 4. Current-to-target delta

- Existing pages, fields, modules, and workflows are reconstructed from evidence.
- Retained capability is separated from required change.
- The requirement extends the real system instead of inventing an unrelated replacement.
- One-time migration or cleanup is separated from permanent product functionality.

## 5. Workflow closure

- Entry, configuration, validation, system decision, action, result, state, and downstream handling connect end to end.
- User-facing, operator-facing, and external-system paths agree.
- Every configuration field has an owner, stored value, consumer, and edit/disable rule where applicable.
- Every visible value has a backend or external source.
- Every new stored field has a visible, operational, decision, or reporting consumer.

## 6. State, exception, and history

- Primary and material exception paths are covered.
- Enable/disable behavior covers future selection, list visibility, and direct access where relevant.
- Retry, failure, stock, quota, and external dependency behavior are defined when the product flow needs them.
- Editing explains whether historical records change.
- Existing records are retained, migrated, backfilled, or rejected by an explicit rule when affected.

## 7. Scope discipline

- Every permanent function supports the primary journey, operational handling, attribution, risk control, or acceptance.
- Existing upload, tags, SEO, review, reward, permission, and reporting capabilities are reused where possible.
- Fixed choices do not create unnecessary management modules.
- Deterministic rules are not replaced by manual consoles without evidence.
- No dashboard, report, queue, adapter, permission layer, sorting, or category system exists without a real consumer.

## 8. Delivery readiness

- Dependencies and ownership boundaries that affect delivery are visible.
- Material risks and unresolved decisions are short and actionable.
- Acceptance criteria are observable and binary pass/fail.
- Each primary path has end-to-end acceptance evidence.
- Important field-to-display, configuration-to-decision, state, failure, and migration rules are testable.
- Acceptance criteria do not introduce behavior absent from the requirement.

## Verdict

Use one outcome:

- **Delivery-ready:** the product path, data/state relations, operational handling, and acceptance evidence are closed.
- **Ready with stated assumptions:** only small reversible assumptions remain and they are visible.
- **Decision required:** list only the few material decisions blocking a correct product requirement.
