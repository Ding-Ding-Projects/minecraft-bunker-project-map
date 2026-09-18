# Handoff

## Current state

- Repository: `Ding-Ding-Projects/minecraft-bunker-project-map`
- Integrated source: `firefighter-update`
- Current `main` commit: `56497514248ba52493d820ea4d83b9125e33d9c0`
- Verified remote `main`: `56497514248ba52493d820ea4d83b9125e33d9c0`
- Release and installer work: out of scope for this pass

The firefighter world snapshot is integrated into `main`. The contamination integration and
the existing local main history were retained as merge parents. The working directory is now
being restored to a documented, ordinary-language handoff after a recoverable documentation
deletion.

## Preservation commits and refs

| Ref or commit | Purpose | Verification |
| --- | --- | --- |
| `37c87741273b7d26d0ac995913f2bd399d7544db` | Firefighter world snapshot | `origin/firefighter-update` verified with `git ls-remote` |
| `93cf3dfdace9805dfbd599eb7f1f4cf300daa425` | Royalty render project metadata | `origin/royalty-update` verified with `git ls-remote` |
| `7422bb7d8c256be2aa343774b54f52ca3de0b7d8` | Contamination integration preservation | `origin/contamination-update-part-2` ancestry retained |
| `56497514248ba52493d820ea4d83b9125e33d9c0` | Integrated main history | `origin/main` verified with `git ls-remote` |

The recoverable deletion of this handoff and roadmap is being committed separately with a
bilingual public message. No stash entries were present in the inventory.

## Conflict resolution

The existing main reconciliation contained 598 unmerged index entries. The firefighter merge
contained 614 unmerged entries. Resolution retained both parent histories in merge commits.
Where both parents had a file, the incoming snapshot was selected. Where the incoming side
deleted a path, the existing main file was retained. Paths deleted by both parents were removed.
The final checks reported zero unmerged index entries and zero textual conflict-marker lines.

## Archive evidence

The verified external archive for this repository is:

`C:\Users\cntow\OneDrive\OakKayBackups\contamination-update-part-2\zips\contamination-update-part-2-20260918T170100Z.7z`

It is `8,367,914,924` bytes. A full `7z t` returned exit code `0`, with `1,967` files and
`146` folders. The archive listing contains `2,114` path entries, including the Git administrative
directory under `__git`. The archive is retained as the verified backstop before any removal.

## Retained items and exclusions

All existing linked working directories and branches are retained because task ownership and
redundancy were not proven for them. The royalty working directory contained user-owned project
metadata and was preserved in commit `93cf3dfdace9805dfbd599eb7f1f4cf300daa425`. No stash was
present. No safe redundant directory, branch, or stash was identified for removal.

Release publication, installer work, unrelated product changes, and ownership-uncertain cleanup
remain excluded.
