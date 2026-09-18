# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the current checkout, refs, linked working directories, and stashes.
- [x] Preserve recoverable changes and half-finished work in factual bilingual commits.
- [x] Verify preservation refs with `git ls-remote` where each ref was published.
- [x] Reconcile the existing local `main` history without dropping either parent history.
- [x] Merge the firefighter and contamination world snapshots into the integrated line.
- [x] Resolve all unmerged index entries and textual conflict markers.
- [x] Record non-obvious conflict choices in `HANDOFF.md`.
- [ ] Commit this combined handoff and roadmap after the merge resolution.
- [ ] Publish `main` and verify the exact remote ref.

## Archive and safe removal

- [x] Create and verify the dated external archive under `<OneDrive>\OakKayBackups\contamination-update-part-2\zips\`.
- [x] Record the valid archive path, byte size, entry count, and integrity result in `HANDOFF.md`.
- [x] Confirm that no safe, task-owned, proven-redundant checkout, ref, or stash is available for removal.
- [x] Retain active, user-owned, load-bearing, unmerged, unpublished, and ownership-uncertain work.

## Exclusions

- Release publication, installer work, and unrelated product changes are outside this task.
- Existing linked working directories remain protected until ownership and redundancy are proven.
- Invalid partial archive outputs remain identified as failed evidence and are not used as backups.
