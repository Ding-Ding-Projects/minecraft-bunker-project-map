# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the current checkout, branches, linked worktrees, and stashes.
- [x] Confirm the starting checkout has no uncommitted files, unmerged index entries, or conflict markers.
- [x] Record the preservation and integration plan in `HANDOFF.md`.
- [ ] Commit and publish the preservation record on `contamination-update-part-1`.
- [ ] Merge the completed update into `main` while preserving both histories.
- [ ] Publish `main` and verify the remote ref.
- [ ] Create and verify the external archive before any cleanup.
- [ ] Review cleanup candidates and retain anything active, user-owned, load-bearing, unmerged, undewed, or ownership-uncertain.

## Explicit scope boundary

- Release work, installer work, and unrelated product changes are deliberately out of scope for this pass.
