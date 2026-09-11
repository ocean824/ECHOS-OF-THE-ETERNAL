# ECHOS OF THE ETERNAL — Game Design Bible

## Identity
Strategic collectible card game with immediately legible rules, deep deck construction and tactical interaction. Preserve the card-game-first direction; do not turn the core product into a board/3D tactics game without Ø approval.

## Core loop
Acquire/unlock cards → construct deck → queue/challenge → draw/resource/action cycle → summon/play/react → resolve combat/effects → win condition → rewards/rank/progression → tune deck.

## Rules architecture
Rules are deterministic and server-authoritative for online play. Card definitions are data, not hard-coded per card. Effect system supports targets, costs, timing windows, triggers, replacement effects, statuses, zones, stack/chain resolution and deterministic RNG seeds where randomness exists.

## Content pipeline
Separate admin/content application is mandatory. Ø can create/import card art/templates, define cards/effects/rarity/sets/availability/limits/ban-restrict lists, validate, preview, stage, patch and publish without shipping a client code update for ordinary content changes.

## Unreal
Narrative Pro 2 + Ultra remain shared foundation where useful, but Card Creator Pro + Card Games Templates + Card Game Interface own card presentation/prototyping only after canonical rules contracts are defined. Do not let asset templates define game rules accidentally.

## Modes
Ranked/casual/private, tutorial/PvE challenges and tournament-ready architecture. Additional modes are data/config driven.

## Economy
Collection/crafting/reward/store architecture configurable; monetization cannot alter deterministic match rules. Gacha-style presentation/system may be used only where Ø intentionally configures it, not as a required progression mechanism.

## V1→V3
V1 proves complete rules engine, deck builder, online match, 100+ representative cards, admin app and patch pipeline. V2 expands sets/modes/ranking/tournaments/analytics. V3 supports mature competitive ecosystem, creator/content operations, spectator/replay and AXIOM-native client/runtime.
