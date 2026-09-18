# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the current checkout, branches, linked working directories, and stashes.
- [x] Confirm the initial checkout had no uncommitted files or unresolved index entries.
- [x] Commit and publish the preservation record on `contamination-update-part-1`.
- [x] Merge the completed update into `main` while preserving both histories.
- [x] Resolve the `AGENTS.md` add/add conflict without dropping either public instruction block.
- [x] Repair inherited conflict-marker text in the affected world JSON records.
- [x] Validate repaired JSON records and confirm the repository-wide marker scan is clean.
- [ ] Commit and publish the corrective repair.
- [ ] Publish `main` and verify the exact remote reference.

## Archive and safe removal

- [ ] Create the required dated external archive under `<OneDrive>\OakKayBackups\contamination-update-part-1\zips\`.
- [ ] Read the archive back and record its path, byte size, entry count, and integrity-test result in `HANDOFF.md`.
- [ ] Remove only task-owned, published, ancestry-proven, redundant working directories, branches, and stashes.
- [ ] Retain active, user-owned, load-bearing, unmerged, unpublished, and ownership-uncertain work.

## Exclusions

- Release publication, installer work, and unrelated product changes are outside this task.
- Pre-existing linked working directories are not cleanup candidates unless ownership and ancestry are proven for this task.
- The untracked `world/worldlens.project.json` in `royalty-update` remains untouched.
