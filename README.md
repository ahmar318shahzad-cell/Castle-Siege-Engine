![preview](https://raw.githubusercontent.com/ahmar318shahzad-cell/Castle-Siege-Engine/main/view_dd31.svg)

# Verdant Siege: The Castle Alchemist's Trial

![Verdant Siege Banner](https://img.shields.io/badge/Status-Active-2ea44f?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web%2FCross--Device-6f42c1?style=for-the-badge)
![Engine](https://img.shields.io/badge/Engine-Three.js-r75?style=for-the-badge)
![Language](https://img.shields.io/badge/UI-English%20%26%20German-ff69b4?style=for-the-badge)

An interactive, living-fortress strategy experience that reimagines medieval siege warfare through the lens of botanical alchemy and living architecture. Developed by a young prodigy aged 12, this fully browser-native project invites players to grow, nurture, and command a sentient castle that defends itself using organic projectiles and regenerative stonework.

Rather than commanding dormant, lifeless battlements, you cultivate a fortress that breathes, adapts, and retaliates. Every wall segment remembers the impact of enemy trebuchets. Every tower blooms with defensive flora that launches volatile seed-pods at invading forces. This is not a game where you simply build defenses—it is a living relationship between architect, botanist, and wartime strategist.

---

## 🌿 Overview

Verdant Siege: The Castle Alchemist's Trial bridges the gap between medieval engineering and modern ecological fantasy. It is an single-player, browser-embedded experience leveraging Three.js to render a fully explorable, procedurally-grown castle environment. The core loop revolves around nurturing your fortress's "Verdant Core"—a mystical heartwood that fuels both structural regeneration and offensive plant-life.

What began as a child's curiosity for medieval fortifications has blossomed into a sophisticated sandbox where every stone can sprout, every courtyard can become a thorny labyrinth, and every siege becomes an opportunity to witness the symbiosis between human ingenuity and nature's resilience.

The project is designed for touch-friendly interfaces, making it equally at home on tablets, laptops, and desktop monitors. With a bilingual interface (English and German), it welcomes players from both linguistic backgrounds to experience the unique fusion of history and horticulture.

---

## 🏰 Core Gameplay Pillars

| Pillar | Description |
|--------|-------------|
| **Living Fortifications** | Walls, towers, and gates are composed of "Heartwood Stone"—a material that slowly regenerates when fed by the Verdant Core. Structural damage is visible, with cracks that vine over and heal. |
| **Botanical Siege Weaponry** | Instead of cannonballs or boulders, your defenses fire "Galthorn Seeds"—fast-growing, spike-covered pods that burst upon impact, creating temporary thorn barriers on enemy pathways. |
| **The Trial System** | Each of the game's 7 levels presents a unique "Alchemist's Trial"—a puzzle-like siege scenario. For example, one level may restrict you to defensive-only seeds, requiring clever placement of thorn walls rather than direct attacks. |
| **Seasonal Cycle** | Your castle experiences a day/night cycle that affects plant growth. Seeds planted during dawn grow faster, while those planted during dusk become denser and more resistant to fire attacks. |

---

## 🚀 Getting Started

[![Download](https://raw.githubusercontent.com/ahmar318shahzad-cell/Castle-Siege-Engine/main/start_9127cf.svg)](https://ahmar318shahzad-cell.github.io/Castle-Siege-Engine/)

The most direct path to entering your own living fortress begins with acquiring the latest build. The download bundle includes all required assets, shaders, and the optimized Three.js runtime—no additional configuration is necessary for standard browsers.

### Browser Requirements

- **Chrome 88+** or **Firefox 90+** for full WebGL 2.0 compatibility for advanced foliage rendering.
- **Safari 15+** with "WebGL 2.0" enabled in experimental features.
- Minimum 4GB RAM recommended for expansive castle gardens without frame-rate drops.
- Touch screen or traditional mouse input—both are supported natively.

### Initial Castle Blessing (First Launch)

Upon the first boot, you will be guided through a short "Awakening Ritual"—a tutorial that teaches you how to channel the Verdant Core's energy into your first seed. You will learn to:

1. **Grow a Foundation Turret** by clicking and holding on a designated soil spot. A small sapling will rise, and within a few seconds, it will form a hardened stone tower.
2. **Direct the Root Network** by drawing paths with your cursor to route defensive vines to specific wall sections.
3. **Unlock your first Galthorn Seed** by completing a simple matching puzzle involving the properties of different soil types.

---

## 🧪 The Alchemist's Laboratory

This section details the unique mechanics that set Verdant Siege apart from static tower-defense games.

### The Verdant Core

At the center of your castle lies the Verdant Core—a pulsating, glowing mass of intertwined roots and crystals. This is your primary resource manager. It has two distinct bars:

- **Sap Energy**: The fuel for growing new structures and repairing damaged ones. Sap regenerates slowly but can be accelerated by placing "Sap Crystals" (found after successful defenses) near the core.
- **Bloom Charge**: The offensive resource. This is consumed when firing Galthorn Seeds. Bloom Charge is replenished by the natural "flowering" of your castle's gardens—so planting purely decorative flowers is not just aesthetic; it's a strategic imperative.

### Adaptive Stonework

Each segment of your castle wall has an "Integrity Score." When an enemy projectile strikes, the score drops, and the wall visually crumbles. However, the Heartwood properties create a unique feedback loop: the damage causes the wall to expose its inner root structure, which then accelerates Sap regeneration for that segment. Creating a "damage farming" strategy where you let certain walls take minor hits to fuel rapid expansion elsewhere.

### The Thorn Maze Generator

When you fire a Galthorn Seed, it doesn't just explode on impact. If the seed lands on soil (rather than stone), it triggers a "Thorn Maze Generation" algorithm. This algorithm rapidly grows a labyrinth of thorny vines that slows enemy troops, redirects them into kill zones, and eventually withers back into the soil after 30 seconds. The shape of the maze is procedurally generated based on the surrounding terrain and the angle of the shot, meaning no two sieges ever play out the same.

---

## 🎮 Feature Deep-Dive

### Responsive Living Interface

![Responsive UI](https://img.shields.io/badge/UI-Responsive%20%26%20Adaptive-brightgreen)

The HUD is not a static overlay—it is itself a part of the living castle. The resource bars are represented as "Crystal Vines" that grow along the edges of your screen. When your Sap Energy is high, the vines appear lush and green. When it is low, they become thin and brown. This ensures that you never have to look away from the battlefield to check your resources; the screen's periphery tells you everything at a glance. On mobile devices, the interface compresses into a single "pocket garden" panel at the bottom, ensuring full gameplay without a mouse.

### Multilingual Castle Charters

The game supports a seamless toggle between English (EN) and German (DE) by pressing the `L` key. This is not just a translation of text; the game's lore and tutorial dialogues are fully re-voiced by an in-game narrator, "The Stone Bard," who tells the story of your castle in either language. The Stone Bard's voice also adapts to the in-game season—more melancholic during autumn, more energetic during spring.

### 24/7 Castle Warden (Support)

![Always-On Support](https://img.shields.io/badge/Support-24%2F7%20Warden%20Assistance-blue)

Should you encounter any issue with your castle's growth—be it a graphical anomaly with the WebGL rendering or a balance issue with the Thorn Maze algorithm—the game features a built-in "Warden's Request" system. This is not a traditional chatbot; it is a contextual help system that examines your current game state (your castle's health, your active seeds, your recent actions) and provides a targeted, story-flavored solution. If the internal system cannot resolve the issue, it compiles an anonymous diagnostic report that you can send directly to the developer through the main menu. The Warden is available around the clock, ensuring that no aspiring castle alchemist is ever left without guidance.

---

## 🛠️ Technical Architecture

The project is built with a modular, seed-based system that mirrors the in-game botanical theme.

- **Core Runtime**: Three.js (r150+) for all rendering, specifically utilizing the `InstancedMesh` feature to render thousands of individual leaves and thorns without performance degradation.
- **Logic Engine**: A custom "Root Network" state machine that manages the connections between the Verdant Core, each wall segment, and every planted seed.
- **Procedural Growth Algorithm**: The Thorn Maze Generator uses a modified `Recursive Subdivision` algorithm that treats each segment of the maze as a "branch" that can bifurcate based on the Perlinson soil moisture data.
- **Asset Pipeline**: All 3D models are generated in-engine using signed distance functions (SDFs). This means there are no external model files for the castle itself—only a seed string that defines the default layout. This significantly reduces the download size and allows for the infinite procedural castle layouts in the bonus "Garden Chaos" mode.

---

## 🧩 Benefits of the Living Fortress Approach

Why choose a castle that grows over a castle that is built?

- **Dynamic Difficulty**: Because walls regenerate, a poorly-played early game is not instantly fatal. Your castle can heal its wounds over time, allowing for a "comeback" mechanic that is rare in siege games.
- **Visual Feedback Loop**: The game's visual narrative is inherently tied to its mechanics. A well-fed castle looks majestic and verdant. A neglected castle looks withered and hollow. This gives the player a constant, emotional connection to their structure.
- **Unique Strategy Space**: The combination of "damage farming" for Sap and "Thorn Maze" redirects creates a dual-layer strategy that is rarely explored in the genre. Are you a defensive planner who focuses on wall integrity, or an aggressive botanist who wants to flood the battlefield with organic traps?

---

## 📜 Roadmap 2026

| Quarter | Milestone |
|---------|-----------|
| Q1 2026 | Release of "The Winter Siege" expansion, adding frost-resistant plants and enemy ice-mages. |
| Q2 2026 | Introduction of "Castle Duels"—an asynchronous multiplayer mode where you share your castle layout and challenge friends to siege it. |
| Q3 2026 | Native WebGPU support for enhanced leaf-physics and dynamic particle effects for seed explosions. |
| Q4 2026 | "Alchemist's Workshop"—an in-browser level editor that allows players to design custom Trial scenarios and share them via URL. |

---

## 🤝 Contributing to the Garden

We encourage the community to help this living project grow. Rather than forking the repository in a traditional manner, we utilize a "Grafting" process. A contributor is referred to as a "Gardener." To propose a change:

1.  **Culture a Cutting**: Write your code in a separate branch. This is your "cutting" from the main tree.
2.  **Grafting Request**: Submit a Pull Request, but describe it as a "Grafting Request"—explaining how your code "hybridizes" with the existing architecture.
3.  **The Arborist Review**: A senior contributor (the "Arborist") will review your code for compatibility, ensuring it doesn't "cross-pollinate" with existing features in an unwanted way.

All contributions are crediting in the in-game "Wall of Patrons" on the castle's keep.

---

## 📄 License

This project is open-sourced under the MIT License. This license permits you to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the Software.

The Software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement.

You are free to use this as a learning resource, a base for your own botanical siege games, or to support a young developer's journey.

[View the Full License Text](https://opensource.org/licenses/MIT)

---

## ⚠️ Disclaimer

Verdant Siege is an independent, community-supported project. It is inspired by the architectural concepts of medieval castles and the ecological theories of permaculture, but it is not a historical simulation nor a real-world architectural guide. The behavior of "alchemical seeds" and "sentient stone" are pure fantasy constructs designed for entertainment.

The game collects no personal data. The "Warden's Request" system only sends anonymized game-state data if you explicitly choose to submit a diagnostic report. No cookies are used for tracking; the only persistent storage is a single local save file within your browser's storage for your castle's current state.

The project is developed in an open environment, and community feedback is always welcomed. Please note that the developer, being a young and growing individual (age 12), reserves the right to take "artistic naps" and may occasionally delay updates. We appreciate your patience as the castle, and its builder, continue to grow.

---

**Begin your alchemical journey today. The stones are waiting to sprout.**

[![Download](https://raw.githubusercontent.com/ahmar318shahzad-cell/Castle-Siege-Engine/main/start_9127cf.svg)](https://ahmar318shahzad-cell.github.io/Castle-Siege-Engine/)