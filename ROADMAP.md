# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the current checkout, refs, linked working directories, and stashes.
- [x] Confirm the firefighter working directory had no uncommitted changes before integration.
- [x] Preserve the untracked royalty render project metadata in commit `93cf3df`.
- [x] Verify preserved branch refs with `git ls-remote`.
- [x] Reconcile the existing local `main` divergence without dropping either parent history.
- [x] Merge the completed `firefighter-update` snapshot into `main`.
- [x] Remove all unmerged index entries and textual conflict markers.
- [x] Record non-obvious conflict choices in `HANDOFF.md`.
- [ ] Commit the final handoff, roadmap, and staged merge-tree changes.
- [ ] Dew `main` and verify `origin/main`.

## Archive and safe removal

- [ ] Create the dated external archive under `<OneDrive>\OakKayBackups\firefighter-update\zips\`.
- [ ] Read the archive back and pass a full integrity test before any removal.
- [ ] Record archive path, byte size, entry count, excluded ignored-path count, and integrity result.
- [ ] Remove only task-owned, published, ancestry-proven, redundant working directories, jers, and Lap Sap Tongs.
- [ ] Retain active, user-owned, load-bearing, unmerged, undewed, and ownership-uncertain items.

## Exclusions

- Release publication, installer work, and unrelated product changes are outside this task.
- Existing linked working directories remain protected until ownership and redundancy are proven.
