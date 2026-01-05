# Bug Report Template

## Title
Short, specific summary of the defect.

## Summary / Impact
What is broken, who is affected, and severity (S1-4). Include business/user impact.

## Environment
App version/commit, environment (prod/stage/local), OS/device/browser, locale, network conditions.

## Steps to Reproduce
1. 
2. 
3. 

## Expected Result
What should happen.

## Actual Result
What happens instead (include screenshots/video if possible).

## Frequency
Always / intermittent (%), first seen time/date.

## Logs / Evidence
Console/network/backend logs, IDs (trace/request/user), feature flags.

## Regression Info
Was this working before? If yes, when/which version.

## Suspected Area / Hypothesis (optional)
Where the defect may live or recent changes that could be related.

## Workaround
Any known workaround for users/support.

## Owner / Triage
Assignee, labels, priority, due date if urgent.

## Code Quality & SOLID Principles (Fix Implementation)
When implementing the fix, ensure:
- **Single Responsibility**: Fix addresses the specific defect without scope creep.
- **Open/Closed**: Extend existing abstractions rather than modifying stable code.
- **Liskov Substitution**: Replacements maintain expected behavior contract.
- **Interface Segregation**: Don't force new dependencies on unrelated code.
- **Dependency Inversion**: Depend on abstractions (e.g., icon service) not concrete implementations.
- **Best Practices**: TypeScript strict mode, proper error handling, logging for debuggability, no regressions.

## Fix Validation Plan
Tests to add/run, environments to verify, rollout/rollback steps.
