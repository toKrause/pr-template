# ![bug](https://github.com/toKrause/pr-template/blob/main/.github/bug.png?raw=true) Bugfix

This PR fixes a bug.

<!-- Please create a ticket and replace XXXX  with the ticket number in the following link -->
[Link to Jira](https://mycore.atlassian.net/browse/MCR-XXXX).

<!-- An important question: Does this PR require any other pending PRs to be merged first? -->
<!-- If so, please replace XXXX with the corresponding PR numbers in the following links -->
<!-- If so, please also add the label 'relies-on-other-pr' -->
<!-- Otherwise, please remove this section -->
**Relies on https://github.com/MyCoRe-Org/mycore/pull/XXXX.**  
**Relies on https://github.com/MyCoRe-Org/mycore/pull/XXXX.**  
**Relies on https://github.com/MyCoRe-Org/mycore/pull/XXXX.**

<!-- An important question: Does this PR require a complementary PR in MIR? -->
<!-- If so, please replace XXXX with the corresponding PR numbers in the following link -->
<!-- Otherwise, please remove this section -->
**To be merged in conjunction with https://github.com/MyCoRe-Org/mir/pull/XXXX.**

## Checklist before requesting a review

### The boring part I: Describing the problem

- The Jira ticket should have a title that concisely describes the problem
- The Jira ticket should have a concise description of the problem, including
  - Steps to reproduce the problem with appropriate
    - required preconditions, esp. version numbers
    - example configuration
    - example data
    - example output (particularly: error messages and stack traces)
    - screenshots (if it is a problem in the UI)
  - If not self-evident, a description of the problematic output/behavior
  - If not self-evident, a description of the expected output/behavior

<!-- -->
- [ ] I've made a conscious effort to make it as easy as possible for reviewers to understand the problem and the solution.

### The boring part II: Ticket and PR metadata, target branch

**If the problem has not been part of a release:**

- NO NEW TICKET: The PR should have the same ticket number as the offending PR
- The PR should have the same target branch as the offending PR
- The Jira ticket should have _Affects version_: `????`
- The Jira ticket should have _Fix version_: `????`

**If the problem has already been released:**

- The PR should have the oldest feasible target branch that includes the problem (say, `20XX.12.x`)
- The Jira ticket should have _Affects version_:  All unreleased versions from `20XX.12.x`, not including, `main`
- The Jira ticket should have _Fix version_: All unreleased versions from `20XX.12.x`, including `main`

<!-- -->
- [ ] I chose an appropriate target branch and added all relevant versions to the Jira ticket.

### The core part: The bugfix

- A bugfix should only fix the bug
- A bugfix should not change the _public API_ (unless absolutely necessary)
- A bugfix should not introduce breaking changes that require a migration (unless absolutely necessary)

<!-- -->
- [ ] I fixed the bug with the bare minimum of changes and without preventable breaking changes.

<!-- If breaking changes were necesary, please add a concice description and justification -->
<!-- Otherwise, please remove this section -->
**About those unpreventable braking changes:**  ...

### The tedious part: Testing

- A bugfix should not change existing tests (unless absolutely necessary)
- A bugfix should add a new test that to an existing test class (if such a test class exists)

<!-- -->
- [ ] I've made reasonable efforts to add automated tests.
- [ ] I tested the bugfix myself and can confirm that the solution works.

<!-- If changes were necesary, please add a concice description and justification -->
<!-- Otherwise, please remove this section -->
**About those preventable changes:**  ...
