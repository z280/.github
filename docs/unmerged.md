# Unmerged branches — .github

Remote branches with commits that are not on `main`, as of 2026-10-08.
Written during the 2026-10-08 branch cleanup: every branch whose work was already on
`main` (merged PR, or an ancestor of `main`) was deleted, and its tip SHA logged so it can be
restored. What is left here was **not** deleted because it holds work that is not on
`main`. Each one needs a decision: merge it, open a PR, or delete it.

This is a snapshot; it goes stale as branches change. Re-check with
`git fetch --prune && git log origin/main..origin/<branch>`.

**None.** Every remote branch other than `main` is fully on `main`.

