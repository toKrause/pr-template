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

Please read, understand and follow [this guidance](https://github.com/toKrause/pr-template/blob/main/CONTIBUTING.md#describing-the-featureproblem).

- [ ] I've made a conscious effort to make it as easy as possible for reviewers to understand the problem and the solution.

### The boring part II: Ticket and PR metadata, target branch

Please read, understand and follow [this guidance](https://github.com/toKrause/pr-template/blob/main/CONTIBUTING.md#ticket-and-pr-metadata-target-branch-for-a-bugfix).

- [ ] I chose an appropriate target branch and added all relevant versions to the Jira ticket.

### The core part: The bugfix

Please read, understand and follow [this guidance](https://github.com/toKrause/pr-template/blob/main/CONTIBUTING.md#development-of-a-bugfix).

- [ ] I fixed the bug with the bare minimum of changes and without preventable breaking changes.

<!-- If breaking changes were necesary, please add a concice description and justification -->
<!-- Otherwise, please remove this section -->
**About those unpreventable braking changes:**  ...

### The tedious part: Testing

Please read, understand and follow [this guidance](https://github.com/toKrause/pr-template/blob/main/CONTIBUTING.md#testing-of-a-bugfix).

- [ ] I've made reasonable efforts to add automated tests.
- [ ] I tested the bugfix myself and can confirm that the solution works.

<!-- If changes were necesary, please add a concice description and justification -->
<!-- Otherwise, please remove this section -->
**About those unpreventable changes:**  ...
