# ECHOS OF THE ETERNAL — Unreal Production Build

## Foundation
Narrative Pro 2 + Ultra Game Template 1.3 where useful for application shell/tutorial/PvE narrative. Card rules remain an independent deterministic domain.

## Fab
Card Creator Pro + Card Games Templates + Card Game Interface are prototype/presentation accelerators. Audit each before selecting ownership. Do not combine their rule engines blindly. Gacha System optional only for explicitly approved collection/reward presentation.

## Architecture
Shared pure rules package/service defines cards, zones, actions, timing, effects, RNG and match state. Unreal client renders and submits legal intents. Online authoritative server validates/resolves. Replays derive from initial state + ordered commands/events.

## Admin app
Separate web/desktop content application backed by versioned card/content service: create/edit/import art, define effects, validate, preview, sets/rarity, availability, limits, ban/restrict, stage/publish/rollback. Canva-origin card images/templates can be imported as source assets; canonical gameplay fields are structured data.

## Testing
Golden match transcripts, property/fuzz tests, deterministic replay hashes, illegal-action rejection, reconnect, timeout/concede, patch compatibility and client/server version gates.
