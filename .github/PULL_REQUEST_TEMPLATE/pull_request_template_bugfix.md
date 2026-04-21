# ![bug](https://github.com/toKrause/pr-template/blob/main/.github/bug.png?raw=true) Bugfix

This PR fixes a bug.

<!-- Please create a ticket and replace XXXX  with the ticket number in the following link -->
[Link to Jira](https://mycore.atlassian.net/browse/MCR-XXXX).

<!-- An important question: Does this PR require any other pending PRs to be merged first? -->
<!-- If so, please replace XXXX with the corresponding PR numbers in the following links -->
<!-- If so, please also add the label 'relies-on-other-pr' -->
<!-- Otherwise, please remove this section -->
**Relies on https://github.com/toKrause/pr-template/pull/XXXX.**  
**Relies on https://github.com/toKrause/pr-template/pull/XXXX.**  
**Relies on https://github.com/toKrause/pr-template/pull/XXXX.**  

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

[ ] I've made a conscious effort to make it reviewers as easy as possible to unserstand the problem and the solution.

### The boring part II: Ticket and PR metadata, target branch

**If the problem has not been part of a release:**
 
- DO NOT CREATE A NEW TICKET: Reuse the ticket number of th PR that introduced the bug
- The PR should have the same target branch as the offending PR 
- The ticket should have *Affects version*: `????`
- The ticket should have *Fix version*: `????`

**If the problem has already been released:**

- The PR should have the oldest feasible target branch that includes the problem (say, `20XX.12.x`)
- Tag ticket should have *Affects version*: All unreleased versions from `20XX.12.x` up to, but not including, `main`
- Tag ticket should have *Fix version*: All unreleased versions from `20XX.12.x` up to, and including, `main`

[ ] I chose an appropriate target branch and added all relevant versions to the ticket. 






