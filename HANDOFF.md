# Handoff

## Current state

- Repository: `Ding-Ding-Projects/minecraft-bunker-project-map`
- Preservation branch: `contamination-update-part-1`
- Preservation commit: `886651180af6fd4cdc2afcf8a752de01b83f1e05`
- Merge commit: `515c55db48501d509368732789b33828b95a9c26`
- Common base: `c648a1a763ac9938188f558c8f9e7f94ac2e8d2a`
- Starting `main` commit: `2a9e9e117653bf98c07e8a046c5722bf445310b2`

The update contains the contamination-update-part-1 world snapshot, including tracked world
data and the Paper JAR files under `world/versions/`. Release and installer work is outside
this pass.

## Conflict resolution

The merge had an add/add conflict in `AGENTS.md`. The existing repository-specific prohibition
was retained first, followed by the incoming public vocabulary-discipline block. No text from
either block was discarded.

The merge tree also contained inherited conflict-marker text in 13 world JSON files and in
earlier versions of this handoff and roadmap. The JSON records were repaired by parsing both
sides, combining object keys recursively, retaining the greatest numeric progress counter,
retaining the later timestamp when two timestamps differed, and retaining both array values.
All repaired JSON files parse successfully, and a repository-wide marker scan is clean.

## Remote state

The preservation branch was published and verified at `886651180af6fd4cdc2afcf8a752de01b83f1e05`.
The `main` branch still needs its final publication and remote-reference verification.

## Archive and cleanup

No stash entries were present in the initial inventory. Before any removal, create and verify
the dated external archive under `<OneDrive>\OakKayBackups\contamination-update-part-1\zips\`.
The archive must include the Git administrative directory, all tracked files, and all
non-ignored untracked files. Record its path, byte size, entry count, and full integrity-test
result here.

All other local branches and linked working directories are retained because they are outside
this task's ownership boundary. The pre-existing untracked file
`world/worldlens.project.json` in `royalty-update` is also retained.

## Remaining actions

1. Validate every JSON file and the final marker scan.
2. Commit this corrective handoff, roadmap, and data repair.
3. Publish `main` and verify the exact remote reference with `git ls-remote`.
4. Create and verify the external archive.
5. Remove nothing unless ownership, publication, ancestry, and redundancy are all proven.
