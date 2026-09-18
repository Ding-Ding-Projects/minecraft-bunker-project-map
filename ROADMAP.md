# Roadmap

## Preservation and integration

- [x] Fetch `origin` and inventory the checkout, refs, linked working directories, and stashes.
- [x] Preserve the royalty render project metadata in `93cf3dfdace9805dfbd599eb7f1f4cf300daa425`.
- [x] Reconcile the existing local `main` history without dropping either parent history.
- [x] Integrate the firefighter snapshot into `main`.
- [x] Resolve all unmerged index entries and textual conflict markers.
- [x] Record conflict choices and retained items in `HANDOFF.md`.
- [x] Publish `main` and verify `56497514248ba52493d820ea4d83b9125e33d9c0` with `git ls-remote`.
- [ ] Publish this refreshed handoff and roadmap commit, then verify its ref.

## Archive and safe removal

- [x] Verify the external archive with a full `7z t` integrity test.
- [x] Record archive size, entry count, and integrity result in `HANDOFF.md`.
- [x] Retain active, user-owned, load-bearing, unmerged, unpublished, and ownership-uncertain items.
- [x] Make no removal where task ownership and redundancy are not proven together.

## Exclusions

- Release publication, installer work, and unrelated product changes are outside this task.
