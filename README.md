# Mage Knight

A **local, static-web** remake of *Mage Knight Board Game*. Rules run in Rust (`mk-engine`) compiled to **WASM** in the browser — no game server required for normal play.

> **Fan remake · not affiliated with WizKids / NECA / Vlaada Chvátil.**  
> Game design & official artwork remain with their rights holders. This repository **does not ship** scanned proprietary art. Local art packs stay gitignored; missing textures use placeholders.

**Play locally:** see [Quick start](#quick-start).  
**Demo (GitHub Pages):** https://kyle-ip.github.io/mage-knight/ — engine + UI only; expect placeholder art unless you point `VITE_ASSETS_BASE_URL` at assets you host privately.

---

## Features

- Static WASM play (solo Dummy, hotseat 2–4)
- Rust rules authority via thin WASM / optional WebSocket adapters
- Setup: scenarios, expansions, hero muster, EN / 中文
- Autosave / continue (`localStorage`)
- Pause, settings (locale, motion, text scale), soft exit to menu
- Critical UI regression suite (Playwright)

---

## License & copyright

- **Code:** see [LICENSE](./LICENSE) (MIT).
- **Agent skills under `.cursor/skills/awesome-gamedev-agent-skills/`:** see that tree’s LICENSE / NOTICE.
- **Art / trademarks:** rights holders retain all rights. Do not redistribute proprietary board-game assets via this repo or public Pages builds.
