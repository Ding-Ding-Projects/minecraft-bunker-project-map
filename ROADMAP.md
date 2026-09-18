# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the current checkout, branches, linked worktrees, and stashes.
- [x] Confirm the starting checkout has no uncommitted files, unmerged index entries, or conflict markers.
- [x] Record the preservation and integration plan in `HANDOFF.md`.
- [x] Commit and publish the preservation record on `contamination-update-part-1`.
- [x] Resolve the `AGENTS.md` add/add conflict while preserving both public instruction blocks.
- [x] Merge the completed update into `main` while preserving both histories.
- [ ] Publish `main` and verify the remote ref.
- [ ] Create and verify the external archive before any cleanup.
- [ ] Review cleanup candidates and retain anything active, user-owned, load-bearing, unmerged, undewed, or ownership-uncertain.

## Explicit scope boundary

- Release work, installer work, and unrelated product changes are deliberately out of scope for this pass.
