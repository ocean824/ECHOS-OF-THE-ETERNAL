# ECHOS Master Blueprint

## Rules architecture
Deterministic engine separate from visuals/network. Data-driven CardDefinition/Set/Format/Deck/Match/Zone/Effect/Trigger/Target/Cost/Status. Server-authoritative online play. Replay/event log allows deterministic reconstruction where feasible.

## Content/admin
Admin app imports Ø's source card art/design references, renders canonical templates, validates text/assets, manages sets, limits/bans/rotations, balance patches, localization and publishing. Never require manual code edits to add ordinary cards.

## Unreal
Use Card Creator Pro/Card Games Templates/Card Game Interface selectively after mapping features to canonical rules. Do not let marketplace template rules define ECHOS. Narrative Pro/Ultra support meta shell/story where valuable.

## AXIOM
Same engine-neutral rules/data/event contracts implemented in AXIOM; golden match fixtures ensure parity.

## XYRA Gauntlet
Rules/property tests; illegal-state prevention; effect ordering; targeting; disconnect/reconnect; duplicate requests; cheating; deterministic replay; deck legality; patch migration; admin permissions; matchmaking/ranked integrity; UI clarity/accessibility.

## Delivery
Rules spec → deterministic simulator → card schema/admin → local match → AI → deck builder → network authority → ranked/tournament → content ops → AXIOM parity.