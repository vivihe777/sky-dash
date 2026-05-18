# Changelog

## v5.0 — 2026-05-18
### Added
- 2 new skins: Deep Sea Sprite (深海精灵, bioluminescent fish) + Fire Phoenix (烈焰凤凰, flame wings)
- Total 5 skins, all free/unlocked

### Fixed
- Skin card bird "穿模" (overflow) — canvas clip() constrains bird to card boundary

## v4.0 — 2026-05-18
### Changed
- Continuous gameplay: no between-level pause screens
- Difficulty auto-increases every 5 pipes via non-blocking level-up banner
- Removed levelComplete / win states; unified into single playing scene

## v3.0 — 2026-05-18
### Added
- Bezier-curve bird drawing for all 3 skins (no more circle stacking)
- Skin redesign: Classic Bird / Cyber Mech / Ghost Spirit — fully distinct silhouettes
- Proper `devicePixelRatio` canvas scaling (Retina / HiDPI support)
- READY state before gameplay (bird bobs, waiting for first tap)

### Fixed
- Immediate death bug on level start (gravity now only activates on first tap)
- Canvas blurriness on Retina screens

## v2.0 — 2026-05-18
### Added
- 3 skins with skin selection screen
- Level complete / Game over scenes
- Particle effects, screen shake, flash

## v1.0 — 2026-05-18
### Added
- Initial release: 10 levels, Flappy Bird mechanics, coin system
