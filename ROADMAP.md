# Roadmap

## Preservation and integration

- [x] Inspect the primary checkout, all linked checkouts, branches, tags, and stashes.
- [x] Fetch all hui refs before mutation.
- [x] Confirm the primary checkout started clean with no unmerged index entries or conflict markers.
- [x] Preserve and verify the existing dewed preservation branches.
- [x] Resolve the contamination and firefighter merge conflicts while retaining both parent histories.
- [x] Record the two delete/modify conflict choices in `HANDOFF.md`.
- [ ] Commit and dew this handoff on `hospital-update` and verify the hui ref.
- [ ] Reconcile the concurrent staged main state without discarding user-owned work.
- [ ] Refresh the final handoff and roadmap on main.
- [ ] Dew main and verify the remote main ref with `git ls-remote`.

## Archive and Mat Day

- [ ] Create the dated external archive in the HuiDrive Oak Kay backup folder.
- [ ] Read back the archive, verify the Git administrative directory and expected tracked/untracked entries, and record byte size and entry count.
- [ ] Prove exact cleanup candidates are merged, dewed, and ancestors of dewed main.
- [ ] Remove only safe proven redundant branches, linked checkouts, and Lap Sap Tongs.
- [ ] Document every retained item and every exclusion.

## Explicit exclusions

- Release work, installer work, publication, and unrelated product changes are out of scope for this pass.
