# Handoff

## Current state

- Repository: `Ding-Ding-Projects/minecraft-bunker-project-map`
- Working branch: `contamination-update-part-1`
- Starting commit: `e006dd9f5d919ffe4cb5008c73205073e54fec74`
- Common base with `main`: `c648a1a763ac9938188f558c8f9e7f94ac2e8d2a`
- Starting `main` tip: `2a9e9e117653bf98c07e8a046c5722bf445310b2`
- Starting state: clean, with no unmerged index entries and no conflict markers.

This branch carries the contamination-update-part-1 world snapshot. The snapshot includes
tracked world data and the three Paper JAR files under `world/versions/`. No unrelated release
work is part of this handoff.

## Integration decision

The branch and `main` both contain work after the common base. The completed branch will be
merged into `main` with a normal merge, preserving both lines in the resulting history. Any
conflict will be resolved by keeping the complete meaning of both sides, then checked for
remaining unmerged index entries and conflict markers.

## Verification plan

1. Fetch `origin` before changes.
2. Commit and publish this preservation documentation on the current branch.
3. Verify the branch ref with `git ls-remote`.
4. Merge the completed branch into `main`.
5. Update this handoff and `ROADMAP.md` with the final merge commit.
6. Publish `main` and verify its remote ref with `git ls-remote`.
7. Create and test the required external archive before any cleanup decision.

## Conflict record

No conflicts were present at handoff creation. If merge conflicts occur, record each path,
the choice made, and the validation used here before declaring the merge complete.

## Retained work

Other local branches and linked worktrees are outside this task's ownership boundary. They are
retained unless a later inventory proves a specific item is redundant, merged, published, and
safe to remove.
