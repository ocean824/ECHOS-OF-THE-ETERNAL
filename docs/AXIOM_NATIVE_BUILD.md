# ECHOS — AXIOM Native Build

The card rules/content service is engine-neutral from the beginning. AXIOM client consumes the same versioned rules/content protocol as Unreal.

AXIOM requirements: deterministic card simulation library/service binding, UI/card rendering, animation/VFX, networking, account/match services, replay/spectator hooks, asset/content delivery and profiler.

Migration is primarily client/presentation replacement, not rules rewrite. Golden match transcripts and replay hashes must produce identical outcomes across supported clients for the same rules version/seed/commands.

PYRAMID may provide identity/social/tournament/store integrations behind platform adapters; canonical collection/match ownership remains ECHOS services.
