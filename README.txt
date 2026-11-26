GAME COLLECTION V3 — Netlify-ready static website

Deploy: extract this ZIP and drag the extracted folder into your existing Netlify site deployment page. index.html must be at the folder root. No build command, API keys or database required.

Five collections, eleven playable games:
- 小医官 · 传太医 (fictional historical medicine simulation; not medical advice)
- 茶博士 · 茶馆小当家
- Moonspire Academy
- The Midnight Antidote — 10 chapters, 3 difficulty levels, checkpoints, house points, spell journal, memory trial, maze, moving Snitch, duels and three final endings.
- Game Arcade — Xiangqi (standard/blind), Go (9/13/19), Chess, Banqi, Sudoku, Minesweeper, Pinball. Local saves per game, local/computer modes where applicable, undo where available, theme, sound and results. The original upload's third-party online room API is not usable on standalone Netlify; online play is not enabled.

The three original simulations retain their original gameplay and add monthly quests and a coin-based energy purchase. Existing V2 save keys remain unchanged. Older Midnight Antidote saves are migrated when loaded; completed V2 runs without saved state must restart from chapter 1. Saves are device/browser/domain specific. Use the collection's Settings backup/restore to transfer them. No cloud synchronization.

Validation: JavaScript syntax checks, isolated Chromium mobile-viewport test of homepage and all simulation entry points, complete 10-chapter story route, all 7 arcade tabs, chess save/restore and undo. Live Netlify deployment, full board-game rules/AI quality, alternative story branches and physical devices not exhaustively verified.

V4: Hogwarts free-roam RPG expansion. Use Explore Hogwarts after choosing a house. Story moves are unaffected by free-roam. Map, character, equipment, companions, exams, real-time duel and race challenges, simulated House Cup and quests save with the story. Online multiplayer is not included. The V3.1 pinball redesign is retained.
