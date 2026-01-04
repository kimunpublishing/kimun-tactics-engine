# Kimün Tactics Engine

![Kimün Tactics Engine](kimun/branding/kimun_tactics_logo.png)

**Kimün Tactics Engine** is an **offline-first tactical card game engine**
developed as an **independent derivative edition** based on the OpenDuelyst
codebase, originally created by Counterplay Games and released in 2016.

This project is maintained by **Kimün Games (Kimün Publishing Universe)** and
serves as the foundation for a standalone, community-driven tactical card
battler, designed for modern desktop distribution (Windows + Linux), with a
focus on local play, accessibility, and long-term extensibility.

> ⚠️ This is an **unofficial derivative project**.  
> It is **not affiliated with or endorsed by Counterplay Games or Bandai Namco
> Entertainment**.

---

## About this Repository

This repository originates from **OpenDuelyst**, which preserves the state of
the original Duelyst game as it existed prior to the official server shutdown
in 2020.

The original project made the full source code and assets available under the
**Creative Commons Zero v1.0 Universal (CC0)** license, effectively dedicating
them to the public domain.

Kimün Tactics Engine builds upon that foundation with the following goals:

- Remove mandatory online dependencies for players
- Enable **offline-first gameplay**
- Provide a clean base for new original content
- Establish a legally clear separation between CC0 upstream code and Kimün
  Games original contributions

---

## Project Status

🚧 **Early Development / Work in Progress**

Current focus:
- Baseline build verification
- Offline-first refactor (no Firebase required for players)
- Rebranding and removal of legacy product marks
- Preparation for itch.io distribution

Target platforms:
- Windows
- Linux

---

## Gameplay Overview

Kimün Tactics Engine is a **grid-based, turn-based tactical card game engine**
where players summon units, cast spells, and maneuver across a battlefield
with the objective of defeating the opposing general.

In its current state (baseline upstream behavior):
- The game is playable by hosting a local server
- There is **no public server available**
- All factions and cards are unlocked for local play
- Players start with bonus in-game resources for deck building

These systems are subject to change as part of the offline-first refactor.

---

## Quick Start (Developers)

> ⚠️ **Note:** Player-facing offline builds are a project goal.  
> The current development baseline still reflects upstream requirements.

Running the engine locally currently requires:
- A free Google Firebase account
- Docker (for local services)
- Node.js

For detailed setup instructions, see:
📄 [`docs/QUICKSTART.md`](docs/QUICKSTART.md)

---

## Mobile Platforms

The engine can currently be played in modern mobile browsers (Chrome / Safari)
using a Progressive Web App approach.

Use the browser’s **“Add to Home Screen”** feature to launch the game in a
fullscreen, app-like mode.

Native mobile builds are **out of scope** for the current roadmap.

---

## Issues & Bug Reports

If you encounter a bug or technical issue:

1. Check existing issues first:
   https://github.com/kimunpublishing/kimun-tactics-engine/issues
2. If not reported, open a new issue with the appropriate label:
   - `bug`
   - `enhancement`

Please include:
- Platform (OS)
- Steps to reproduce
- Logs or screenshots when possible

---

## Contributing

Contributions are welcome.

If you are interested in contributing:
- Please read the contributor guidelines:
  📄 [`docs/CONTRIBUTING.md`](docs/CONTRIBUTING.md)
- Follow existing coding conventions
- Keep Kimün-specific additions clearly separated from upstream-derived code

### Localization

The engine currently includes:
- English
- German

To contribute a new language:
1. Copy the `app/localization/locales/en` directory
2. Translate the strings
3. Submit a Pull Request

---

## Legal & Licensing

### Upstream Code
- Base project: **OpenDuelyst**
- License: **Creative Commons Zero v1.0 Universal (CC0)**
- Original development: Counterplay Games and contributors

### Kimün Games Contributions
- © 2026 Kimün Games
- All rights reserved **only** for original contributions authored by Kimün
  Games (code, assets, branding, documentation, and editorial content)
- See:
  - `NOTICE.md`
  - `CREDITS.md`
  - `KIMUN_LICENSE.md`

Moral rights of original authors are fully respected.

---

## Community

Community channels will be announced as the project stabilizes.

For upstream historical discussion, see the original OpenDuelyst community.

---

**Kimün Tactics Engine**  
A foundation for tactical card games — rebuilt, offline, and open at its core.
