# Handoff

## Scope and current state

- Repository: `Ding-Ding-Projects/minecraft-bunker-project-map`
- Primary checkout: `C:\Users\cntow\Documents\GitHub\hospital-update`
- Preservation branch: `hospital-update`
- Starting commit: `13e7a791a2644d2da8d3d73580f313bbc569788b`
- Starting state: clean, with no unmerged index entries, conflict markers, or stashes.
- Fetch completed before mutation. The repository has one primary checkout and nine linked checkouts.
- No installer, release, or unrelated product work was run.

## Preservation and integration evidence

- `hospital-update` remains clean and matches `origin/hospital-update` at `13e7a791a2644d2da8d3d73580f313bbc569788b`.
- `contamination-update-part-1` is clean and dewed at `886651180af6fd4cdc2afcf8a752de01b83f1e05`.
- `contamination-update-part-2` is clean and dewed at `90542430a3d644817866677a81f93e4e2fded08b`.
- `royalty-update` is clean and dewed at `93cf3dfdace9805dfbd599eb7f1f4cf300daa425`.
- The existing main integration produced `c5482385f8c546defc58f96badca18725ca9491b`, with parents `515c55d` and `7422bb7`.
- The firefighter integration produced `114613e2d5ee9514f3d5f4e5d6cf2a9d96fc1525`, with parents `c5482385f8c546defc58badca18725ca9491b` and `37c8774`. Both merge parents remain in history.
- Main is not yet dewed after those integrations. The main checkout currently contains staged region-file changes from a concurrent writer and is therefore retained and not rewritten.

## Non-obvious conflict resolutions

- The contamination integration retained both parent histories and resolved world-file conflicts without conflict markers.
- The firefighter integration selected the incoming snapshot where both sides supplied a path. Two delete/modify paths had no incoming blob, `world/region/r.5.-5.mca` and `world/stats/5101778e-024b-4702-8be2-bd287d9bb3ed.json`; the current main-side deletion was retained. The firefighter parent still preserves the incoming history.
- No unmerged index entries or conflict markers remain in the committed merge results. The active staged region changes in the main checkout are a separate concurrent state and must not be discarded.

## Retained work and cleanup boundary

- All active linked checkouts, user-owned or ownership-uncertain branches, load-bearing branches, and the concurrently modified main checkout are retained.
- `storage-update`, `the-renovation-update`, and `the-security-update` have no linked checkout and remain retained because ownership and cleanup safety are not proven.
- No Lap Sap Tongs were present at inventory time.
- No branch, linked checkout, or file was removed. Mat Day removal awaits a verified external archive, a stable clean main checkout, remote ancestry proof, and exact ownership proof.

## Next safe actions

1. Commit and dew this preservation handoff on `hospital-update`, then verify its hui ref with `git ls-remote`.
2. Wait for the concurrent main writer to settle, inspect its final staged state, and preserve it before any further integration.
3. Refresh `HANDOFF.md` and `ROADMAP.md` on main, resolve any remaining conflicts, dew main, and verify the hui ref.
4. Create and read back the required dated archive in `<OneDrive>/OakKayBackups/minecraft-bunker-project-map/zips/` before any Mat Day removal.
5. Remove only proven redundant task-owned items. Keep everything else dewed and documented.
