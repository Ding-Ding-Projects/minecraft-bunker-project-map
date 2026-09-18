# Roadmap

## Preservation and integration

- [x] Inventory the primary checkout, linked checkouts, refs, stashes, and current working state.
- [x] Fetch the hui and verify the current preservation ref.
- [x] Merge `origin/main` into `contamination-update-part-2` without dropping either side.
- [x] Verify that the merge has no unmerged index entries or conflict markers.
- [ ] Commit and verify the refreshed handoff and roadmap on the preservation branch.
- [ ] Dew the preservation branch and verify its remote ref with `git ls-remote`.
- [ ] Integrate the completed work into `main` and verify the dewed main ref.

## Archive and safe removal

- [ ] Create the required dated external archive under `<OneDrive>\OakKayBackups\contamination-update-part-2\zips\`.
- [ ] Read the archive back and record its path, byte size, entry count, and verification result in `HANDOFF.md`.
- [ ] Remove only safe, task-owned, proven-redundant checkouts, refs, and stashes.
- [ ] Retain active, user-owned, load-bearing, unmerged, undewed, and ownership-uncertain work.

## Exclusions

- Release publication, installer work, and unrelated product changes are outside this task.
- Pre-existing linked checkouts are not cleanup candidates unless ownership and ancestry are proven for this task.
- The untracked `world/worldlens.project.json` in `royalty-update` remains untouched.
