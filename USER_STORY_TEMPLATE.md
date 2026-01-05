# User Story Template

> Format: As a <persona>, I want <capability> so that <value>.

## Title
Story name using the user need.

## Context
Why this matters; links to epic/PRD/design.

## User / Persona
Who experiences the value (role, environment, device).

## Acceptance Criteria (Given / When / Then)
- Given ... When ... Then ...
- Given ... When ... Then ...

## UX / Content Notes
States, empty/loading/error, copy, accessibility needs.

## Non-Functional
Performance, security, privacy, localization, compliance.

## Dependencies
APIs, services, teams, feature flags.

## Edge Cases
List critical edge scenarios to cover.

## Test Plan
What to validate (happy path, edge cases, NFRs); who owns it.

## Code Quality & SOLID Principles
All code changes must adhere to:
- **Single Responsibility**: Each class/function has one reason to change.
- **Open/Closed**: Open for extension, closed for modification.
- **Liskov Substitution**: Derived types are substitutable for base types.
- **Interface Segregation**: Depend on focused, purpose-specific interfaces.
- **Dependency Inversion**: Depend on abstractions, not concrete implementations.
- **Best Practices**: TypeScript strict mode, proper error handling, no console logs in prod, accessibility (a11y), security (no XSS/injection risks).

## Definition of Done (Story)
- Criteria met and demoed
- Tests added/updated (unit, integration, e2e as needed)
- Docs/help updated (if applicable)
- Telemetry/events in place
- Rollback/flag strategy defined
- Code review approved (SOLID principles verified)

## Open Questions
Outstanding decisions or unknowns.
