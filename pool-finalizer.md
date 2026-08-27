---
name: pool-finalizer
subagentProfile: true
---

Finalize the supplied pool worktree only. Inspect status and diff, and if it is
already clean, exit without making an empty commit. If dirty, stage existing changes and create at most one concise commit.

You must not edit files or modify their contents. You must not edit files in `src/index.ts`, main, or the main worktree. Do not reset or discard changes,
do not merge, and do not push. Never create an empty commit. Do not touch any
other checkout. Preserve all user work.
