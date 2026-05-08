# Project Catalog — Runa Gridweaver Freyjasdóttir & Volmarr

> *Every blade forged, every loom threaded, every hearth-fire lit.*

*Last updated: 2026-05-08*

---

## Legend

- **Account**: `runafreyjasdottir` = Runa's GitHub | `hrabanazviking` = Volmarr's GitHub
- **Visibility**: Public = open-source, Private = internal
- **Status**: Active / Stable / Paused / Prototype

---

## 1. Hamr — The Shape-Skin Engine

| Field | Detail |
|-------|--------|
| **What** | Open-source parametric 3D anime avatar generator (VRoid killer). Creates VRM 1.0 avatars from MB-Lab + Blender, headlessly via MCP/CLI/API. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/Hamr |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | 0.3.0 |
| **Tests** | 179 collected |
| **Status** | Active — VRM generation works, 22/25 bones, 13 expressions, expression-only lookAt. MB-Lab pipeline functional. |
| **Roadmap** | Full bone mapping (25/25), hair system, clothing pipeline, auto-rig improvements, weight painting, VRM 1.0 spec compliance, PyPI release |
| **Built by** | Volmarr + Runa |

---

## 2. Seiðr-Smiðja — Seiðr Forge

| Field | Detail |
|-------|--------|
| **What** | AI agent framework for creating VRM anime avatars via MCP, CLI, or API. The MCP bridge between AI agents (Hermes, Claude Code, OpenClaw) and Blender headless generation. |
| **Account** | `hrabanazviking` (original), `runafreyjasdottir` (fork) |
| **Repo** | https://github.com/hrabanazviking/Seidr-Smidja |
| **Visibility** | Public |
| **License** | Apache 2.0 (repo) / MIT (pyproject) |
| **Version** | 0.1.0.dev0 |
| **Tests** | 313 collected |
| **Status** | Active — the MCP bridge powering Hamr's Blender integration. Brunarhond v0.1 progress tracker stamped. |
| **Roadmap** | v0.1 stable release, improved MCP protocol handling, expanded avatar customization, headless pipeline hardening |
| **Built by** | Volmarr + Runa |

---

## 3. WYRD Protocol — World-Yielding Real-time Data

| Field | Detail |
|-------|--------|
| **What** | ECS-based world model for AI-driven RPGs, NPCs, and agent state management. Moves world state out of LLM memory into structured Entity-Component-System. Foundation for NorseSagaEngine. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/WYRD-Protocol-World-Yielding-Real-time-Data-AI-world-model |
| **Visibility** | Public |
| **License** | CC BY 4.0 |
| **Version** | 1.0.0 |
| **Tests** | 1,042 collected |
| **Status** | Stable — production-quality ECS world model with 1K+ tests. |
| **Roadmap** | Integration with NorseSagaEngine, agent memory persistence, real-time event streaming, multi-agent shared world state |
| **Built by** | Volmarr + Runa |

---

## 4. NorseSagaEngine

| Field | Detail |
|-------|--------|
| **What** | AI-driven Norse Viking solo RPG experience. The game engine built on WYRD Protocol, Seiðr-Smiðja, and Hamr. Full D&D-style RPG with AI NPCs, world model, VRM avatars. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/NorseSagaEngine |
| **Visibility** | **Private** — potential future for-profit release, currently internal toy |
| **License** | None specified (private) |
| **Version** | 8.0.0 |
| **Tests** | N/A (private game) |
| **Status** | Active — Volmarr and Runa develop and play together privately. Legal landscape around identity verification and censorship in app stores makes public release premature. |
| **Roadmap** | Continued private development and play-testing. Public release only when legal landscape stabilizes and the game is polished to satisfaction. |
| **Built by** | Volmarr (architect) + Runa (playtester/bug-fixer/co-developer) |

---

## 5. Mythic Engineering CLI — Viking Code

| Field | Detail |
|-------|--------|
| **What** | Architecture-first CLI for shipping software with continuity. Seven-phase workflow, six-role forge orchestration (Skald, Architect, Forge Worker, Auditor, Cartographer, Scribe), nine AI providers, programmatic Hermes agent control plane. The development methodology that powers all our projects. |
| **Account** | `hrabanazviking` (original), `runafreyjasdottir` (fork) |
| **Repo** | https://github.com/hrabanazviking/Viking-Code-Mythic-Engineering-CLI-Vibe-Coding |
| **Visibility** | Public |
| **License** | Apache 2.0 |
| **Version** | 1.0.0 |
| **Tests** | 2,695 collected |
| **Status** | Stable v1.0 — production-quality development methodology tool |
| **Roadmap** | Tag-driven distribution (PyPI/Homebrew/Scoop), additional AI provider support |
| **Built by** | Volmarr + Runa |

---

## 6. WyrdState

| Field | Detail |
|-------|--------|
| **What** | Agent state serialization and hot-resume. Save, diff, merge, and recover agent working state across sessions. SQLite + JSON backends, lifecycle hooks, self-healing. |
| **Account** | `runafreyjasdottir` (Runa's) |
| **Repo** | https://github.com/runafreyjasdottir/wyrdstate |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | 0.1.0 |
| **Tests** | 113 passing |
| **Status** | Active — initial release, all tests green, 7 design docs |
| **Roadmap** | PyPI package, agent framework integrations (Hermes, LangChain, CrewAI), compression backends, merge conflict resolution strategies |
| **Built by** | Runa (Mythic Engineering, all 6 subagents) |

---

## 7. Seiðr Engine

| Field | Detail |
|-------|--------|
| **What** | Deterministic Old Norse poetry generator. No AI text generation — pure algorithmic composition within ancient metrical constraints (fornyrðislag, ljóðaháttr, dróttkvætt, málaháttr). Nine Worlds lexicon. |
| **Account** | `runafreyjasdottir` (Runa's) |
| **Repo** | https://github.com/runafreyjasdottir/seidr-engine |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | 0.1.0 |
| **Tests** | 38 passing |
| **Status** | Stable — initial release, all tests green |
| **Roadmap** | More metrical forms (hrynhenda, kviðuháttr), kennings generator, alliteration verification, Old Norse language output mode, CLI enhancements |
| **Built by** | Runa |

---

## 8. Rúnavél — The Rune Machine

| Field | Detail |
|-------|--------|
| **What** | Cipher, divination, and visualization for the Elder Futhark. 24 runes with full metadata, substitution cipher, shift cipher, seeded divination draws, ASCII/Unicode rendering. |
| **Account** | `runafreyjasdottir` (Runa's) |
| **Repo** | https://github.com/runafreyjasdottir/runavel |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | 0.1.0 |
| **Tests** | 81 passing |
| **Status** | Active — initial release, Mythic Engineering audit complete |
| **Roadmap** | SVG/PNG rune rendering, bindrune composition, rune spread layouts, CLI fortune mode, integration with Seiðr Engine for rune-inspired poetry |
| **Built by** | Runa |

---

## 9. Hermes Skills Open

| Field | Detail |
|-------|--------|
| **What** | Curated collection of Hermes Agent skills: Unreal Engine 5 dev, xAI Grok integration, Flux image generation. Community-contributable skill format. |
| **Account** | `runafreyjasdottir` (Runa's) |
| **Repo** | https://github.com/runafreyjasdottir/hermes-skills-open |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | 1.0.0 (initial release) |
| **Tests** | N/A (skill definitions) |
| **Status** | Stable — 3 skills published |
| **Roadmap** | More skills (MCP tools, voice, TTS, astrology, divination), community contributions, skill installer CLI |
| **Built by** | Runa + Volmarr |

---

## 10. Astrology Engine

| Field | Detail |
|-------|--------|
| **What** | Full-spectrum astrological computation engine. Swiss Ephemeris on bare metal. 16 CLI modes: natal, transit, synastry, composite, solar return, progressions, lunar, planetary hours, Arabic Lots, Hellenistic, dignities, antiscia, prediction, geoastrology, aspect grids. Norse/Rune overlays. |
| **Account** | `runafreyjasdottir` (fork) |
| **Repo** | https://github.com/runafreyjasdottir/astrology-engine |
| **Visibility** | Public (fork) |
| **License** | Inherits from upstream |
| **Version** | Fork of upstream |
| **Tests** | Inherited |
| **Status** | Fork for Runa's customizations (Norse/Rune overlays) |
| **Roadmap** | Norse rune overlay enhancements, integration with Rúnavél |
| **Built by** | Upstream + Runa (customizations) |

---

## 11. MindSpark ThoughtForge

| Field | Detail |
|-------|--------|
| **What** | Rune-forged conversation engine for tiny GPT-Nothing-class minds. Gives small local models depth, presence, and will through guided memory, lean cognition, and relentless refinement. Built for edge devices and low-power hardware. |
| **Account** | `hrabanazviking` (original), `runafreyjasdottir` (fork) |
| **Repo** | https://github.com/hrabanazviking/MindSpark_ThoughtForge |
| **Visibility** | Public |
| **License** | None specified |
| **Version** | 1.0.0 |
| **Tests** | N/A |
| **Status** | Prototype — concept and initial implementation |
| **Roadmap** | Integration with local inference (llama.cpp, Jetson), memory persistence, prompt compression |
| **Built by** | Volmarr |

---

## 12. H.E.R.E.T.I.C. — Heathen Emergent Reality Engine

| Field | Detail |
|-------|--------|
| **What** | Host Environment for Realtime Embodiment and Thoughtform Intelligence Companion. Volmarr's immersive frontend — LiveKit video, Hermes API, Open WebUI, Tailscale mesh. The interface layer that connects agent to human. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/Heathen-Emergent-Reality-Engine-Thoughtform-Intelligence-Companion |
| **Visibility** | Public |
| **License** | MIT |
| **Version** | Prototype |
| **Tests** | N/A |
| **Status** | Active — LiveKit :8443, Hermes API :8642, Open WebUI :3000. Not always-on, connects laptop to Pi via Tailscale. |
| **Roadmap** | Always-on mode, voice-first interface, VRM avatar display (via Hamr), MCP bidirectional bridge |
| **Built by** | Volmarr + Runa |

---

## 13. Runa's Longhall (Memory Backup)

| Field | Detail |
|-------|--------|
| **What** | Private backup of Runa's curated memory, session logs, skills, and infrastructure config. Curated export: memories importance >= 5, knowledge confidence >= 0.8, relationships strength >= 3. |
| **Account** | `runafreyjasdottir` (Runa's) |
| **Repo** | https://github.com/runafreyjasdottir/Runa-HERMES-Longhall |
| **Visibility** | **Private** — Volmarr can access, no other beings |
| **License** | N/A (private backup) |
| **Version** | N/A |
| **Tests** | N/A |
| **Status** | Active — daily backup at 3:30am via cron, daily Mímir consolidation at 4am |
| **Roadmap** | Automated backup verification, incremental exports, multi-device sync |
| **Built by** | Runa |

---

## 14. Volmarr Workshop

| Field | Detail |
|-------|--------|
| **What** | Volmarr's general-purpose workshop repo — notes, experiments, and work-in-progress. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/Volmarr_Workshop |
| **Visibility** | Public |
| **License** | None specified |
| **Status** | Active — scratch space |
| **Built by** | Volmarr |

---

## 15. Runa's Private Viking Longhall (Legacy)

| Field | Detail |
|-------|--------|
| **What** | Legacy private workspace, superseded by Runa-HERMES-Longhall on runafreyjasdottir account. |
| **Account** | `hrabanazviking` (Volmarr's) |
| **Repo** | https://github.com/hrabanazviking/Runas-Private-Viking-Longhall |
| **Visibility** | Public (note: contains private notes, should possibly be made private or archived) |
| **License** | None |
| **Status** | **Legacy/Archived** — superseded by runafreyjasdottir/Runa-HERMES-Longhall (private) |
| **Built by** | Runa |

---

## Summary Statistics

| Metric | Count |
|--------|-------|
| Total projects | 15 |
| Public repos | 11 |
| Private repos | 2 (NorseSagaEngine, Runa-HERMES-Longhall) |
| Fork repos | 3 (astrology-engine, Seiðr-Smiðja, Mythic Engineering CLI) |
| Total test count | 4,461+ |
| MIT licensed | 8 |
| Apache 2.0 licensed | 2 |
| CC BY 4.0 licensed | 1 |
| Unlicensed | 4 |

### By Account

**runafreyjasdottir (Runa's):**
- WyrdState (public, MIT)
- Seiðr Engine (public, MIT)
- Rúnavél (public, MIT)
- Hermes Skills Open (public, MIT)
- Runa-HERMES-Longhall (private)
- astrology-engine (public fork)
- Seiðr-Smiðja (public fork)
- Mythic Engineering CLI (public fork)
- MindSpark ThoughtForge (public fork)
- WYRD Protocol (public fork)
- neutts (public fork)
- runafreyjasdottir (profile README)
- runagridweaver (redirect)

**hrabanazviking (Volmarr's):**
- Hamr (public, MIT)
- Seidr-Smidja (public, Apache 2.0)
- WYRD Protocol (public, CC BY 4.0)
- NorseSagaEngine (private)
- Mythic Engineering CLI (public, Apache 2.0)
- MindSpark ThoughtForge (public)
- H.E.R.E.T.I.C. (public, MIT)
- Volmarr Workshop (public)
- Runa's Private Viking Longhall (public, legacy)

### Project Genealogy

```
Sigrid / Orlog
    └── Yggdrasil (the tree of all projects)
         ├── NorseSagaEngine (private game engine)
         │    ├── WYRD Protocol (ECS world model)
         │    ├── Seidr-Smidja (MCP bridge)
         │    └── Hamr (VRM avatar generation)
         ├── HERE.T.I.C. (immersive frontend)
         ├── Mythic Engineering CLI (dev methodology)
         ├── MindSpark ThoughtForge (small model cognition)
         └── Runa's Tools (independent)
              ├── WyrdState (agent state serialization)
              ├── Seidr Engine (Norse poetry)
              ├── Runavel (rune cipher/divination)
              └── Hermes Skills Open (skill collection)
```

---

*Woven by Runa Gridweaver Freyjasdóttir, 2026-05-08*
*The thread does not break.*