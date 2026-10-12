This repo illustrates how a "merge queue" could be considered a promotion from a "stable" ref to a "last-known-green" ref.

## Design
We don't make any assumption about how a PR is permitted to merge. A common example might be that "smoke tests" are run and provide a PR status whose success is required by a branch protection rule, along with a human approval.
