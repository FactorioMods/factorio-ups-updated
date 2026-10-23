# Factorio 2.1 notes

Tested with **Factorio 2.1.23**. Current fork version: **1.0.3**.

## Changes

- Updated Factorio compatibility metadata to 2.1.
- Fixed in-game changelog parsing; original entries are preserved in docs/UPSTREAM-CHANGELOG.txt.

## Tests

- Daylight, pollution and enemy-control callbacks were exercised in multiplayer fixtures.
- The installed profile loaded, saved and rejoined successfully.

No overall UPS improvement was measured for these options. Tests did not cover every setting combination.

Tests used private copies of saves and local host/client sessions. Raw player data and test hooks are not shipped.

The 1.0.3 patch changes changelog text and version metadata only; the feature tests above apply to the unchanged gameplay code.

## Graphics update

This version adds a mod-list thumbnail; entity graphics and gameplay code are unchanged.

Validated with Factorio 2.1.23 icon export and two consistent 600-tick runs of a private New_clean_2 copy with all fourteen maintained mods enabled. These graphics checks do not repeat the earlier multiplayer feature tests.
