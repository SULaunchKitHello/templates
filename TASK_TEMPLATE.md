# Task / Tech Debt Template

## Title
Clear action-oriented name.

## Context / Problem
What needs to change and why now (include links to epic/story/bug if related).

## Goal / Outcome
What success looks like when the task is done.

## Scope
What is included; what is explicitly out of scope.

## Approach / Plan
Outline steps or options; call out decision points.

## Acceptance Criteria
Checklist of observable results (e.g., tests passing, metric changes, docs updated).

## Code Quality & SOLID Principles
For code-related tasks, ensure adherence to:
- **Single Responsibility**: Each class/function has one reason to change.
- **Open/Closed**: Open for extension, closed for modification.
- **Liskov Substitution**: Derived types are substitutable for base types.
- **Interface Segregation**: Depend on focused, purpose-specific interfaces.
- **Dependency Inversion**: Depend on abstractions, not concrete implementations.
- **Best Practices**: TypeScript strict mode, proper error handling, no console logs in prod, accessibility (a11y), security (no XSS/injection risks).

## Dependencies
Upstream/downstream work, access needs, scheduling constraints.

## Risk & Mitigation
Known risks and how to reduce them.

## Test & Validation Plan
Tests to add/run; environments to verify; rollback/flag strategy if applicable.

## Notes / Follow-ups
Docs to update, owners, follow-up tasks.
