# Contribution guide

## Describing the feature/problem

- The Jira ticket should have a title that concisely describes the feature/problem
- The Jira ticket should have a concise description of the feature/problem, including
    - Steps to use a feature / reproduce a problem with appropriate
        - required preconditions, esp. version numbers
        - example configuration
        - example data
        - example output (particularly: error messages and stack traces)
        - screenshots (if it is a feature/problem in the UI)
    - If not self-evident, a description of the unexpected output/behavior
    - If not self-evident, a description of the expected output/behavior

## Bugfixes

### Ticket and PR metadata, target branch for a Bugfix

**If the problem has not been part of a release:**

- NO NEW TICKET: The PR should have the same ticket number as the offending PR
- The PR should have the same target branch as the offending PR
- The Jira ticket should have _Affects version_: `????`
- The Jira ticket should have _Fix version_: `????`

**If the problem has already been released:**

- The PR should have the oldest feasible target branch that includes the problem (say, `20XX.12.x`)
- The Jira ticket should have _Affects version_:  All unreleased versions from `20XX.12.x`, not including, `main`
- The Jira ticket should have _Fix version_: All unreleased versions from `20XX.12.x`, including `main`

If you notice something that should be cleand-up or improved, please make a follow-up PR targeting main

### Development of a Bugfix

- A bugfix should only fix the bug
- A bugfix should make the bare minimum of changes
- A bugfix should not change the _public API_ (unless absolutely necessary)
- A bugfix should not introduce breaking changes that require a migration (unless absolutely necessary)

### Testing of a Bugfix

- A bugfix should not change existing tests (unless absolutely necessary)
- A bugfix should add a new test that to an existing test class (if such a test class exists)

## Testing

## Documentation