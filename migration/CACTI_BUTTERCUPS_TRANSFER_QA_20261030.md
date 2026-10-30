# Cacti & Buttercups — existing source and public learner QA (October 30, 2026)

**Migration source integrity: PASS.** Verified all **543** rows from the original transfer manifest against staging Git tree `8c331c6820389894d5a36c6e3b357c235cc26d2d`, with **543/543 exact source blob hashes**, zero missing and zero mismatches. Manifest's original hub snapshot: `515387cbc23b8bf8931141ead9c44c92a7793699`.

| Item | Verified count |
|---|---:|
| Assigned families | 14 |
| Original species | 107 |
| Source text / credit files | 349 |
| Source original photo files | 194 |
| Published species JSON files | 107 |
| Published hosted existing photos | 37 |
| Species with published images | 25 |
| Held source photo metadata references | 181 of 218 |

The public learner data index matches the installed published species JSON files; its gallery index photo total matches the actual published media file count as inspected October 30, 2026. No new photo collection, species edits, source-photo deletion, or legacy hub mutation occurred.

This checkpoint adds a read-only local + live Pages verification script. The script verifies each publication file, associated photo Git blob SHA, rights metadata and photo credits. **Do not claim the end-to-end live URL test has passed until its workflow run is successful.**

Important distinction: historical held photo bytes are in a publicly readable Git repository and may require later provenance remediation; the Pages rights-filter itself does not restrict source/history access. Existing source archival preservation is complete separately from future photo licensing and field-ready anatomy improvements. Old text-only workflow failures are safety blocks, not missing source data. Future species writes route to this family's staging branch, the original hub stays read-only, and automations stay paused.
