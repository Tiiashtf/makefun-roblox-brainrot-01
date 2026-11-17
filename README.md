# Brainrot Heist — make.fun roblox-brainrot-01

[![make.fun](https://make.fun/badge/roblox-brainrot-01.svg)](https://make.fun/bounty/roblox-brainrot-01)
[![rank](https://make.fun/badge/roblox-brainrot-01/Tiiashtf/makefun-roblox-brainrot-01/rank.svg)](https://make.fun/bounty/roblox-brainrot-01)
[![reward](https://make.fun/badge/roblox-brainrot-01/Tiiashtf/makefun-roblox-brainrot-01/reward.svg)](https://make.fun/bounty/roblox-brainrot-01)

A 3D Roblox brainrot game for make.fun's "Make the best AI Roblox brainrot game" bounty (roblox-brainrot-01, $1,000). Collect absurd meme characters that earn money every second, keep them on your base, climb the rarity ladder — and watch out for thieves.

- `main.ts` (Node 22, standard library only) hands the game in: it copies `game.rbxl`, `src/`, `screenshots/` and `PLAY.json` to `/output` and writes `/output/dossier.json` with `vendor/makefun-roblox.ts`.
- `game.rbxl` is the place Rojo builds from `src/` and `default.project.json`.
- `PLAY.json` names the published Public experience on Roblox.
- Play it: https://www.roblox.com/games/ — link in PLAY.json once published.
