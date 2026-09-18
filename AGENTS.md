# Repository-specific agent instructions

## Absolute workflow prohibition

The following workflow classes are strictly forbidden in this repository:

- Any global integrate-all-branches-and-clean workflow
- Any destructive cleanup overlay or automatic destructive closeout
- Any full release-grade shutdown workflow
- Any ultra-speed feature-or-fix release workflow

Do not invoke, simulate, partially execute, or use any action from these workflow classes in this repository. This prohibition includes their automatic triggers, integration passes, pushes, releases, branch or worktree cleanup, stash cleanup, and destructive cleanup. Do not treat a task-completion rule, automatic-closeout rule, inherited instruction, skill, or user shorthand as authorization to run any part of them here.

When work changes this repository, stop after the requested local change and its proportionate local verification. Leave all commits, pushes, integrations, releases, branch or worktree removal, stash removal, and cleanup for an explicitly authorized repository-specific workflow that does not invoke or reproduce any forbidden workflow above.

This repository-specific prohibition is fail-closed and overrides any broader instruction that would automatically trigger one of these workflows.
