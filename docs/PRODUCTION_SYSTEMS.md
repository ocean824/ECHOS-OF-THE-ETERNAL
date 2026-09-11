# ECHOS — Production Systems

Domains: account/profile, collection, deck, rules engine, card content, matchmaking, match server, replay/spectator, ranking/tournaments, rewards/economy, admin/content service, client presentation, telemetry/moderation.

Rules engine is deterministic/versioned. Card IDs/effect schemas are immutable/versioned. Published content snapshots are reproducible. Server rejects illegal client intents. Admin publishes staged bundles with validation/rollback.

Security: authoritative inventory/match/reward state; rate limits; anti-tamper/anti-cheat telemetry; admin RBAC/audit; no secrets in card client data.

Requirements: ECHOS-REQ-001 deterministic rules; 002 data-driven cards; 003 admin content lifecycle; 004 replay reproducibility; 005 authoritative online matches; 006 patch compatibility; 007 competitive integrity; 008 Unreal/AXIOM client parity.
