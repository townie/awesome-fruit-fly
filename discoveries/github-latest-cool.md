# GitHub-latest cool (Sep 2026 fan-out)

Research date: **2026-09-14**. Scope: brand-new or heavily updated MaleCNS / FlyWire / fruit-fly-connectome **demo** repos, ranked by novelty vs the existing [README](../README.md) plus [`discoveries/*.md`](.).

Stars are GitHub API counts from this pass. Missing stars are omitted, not guessed. No invented URLs. Live demos were HTTP-checked (200) unless marked otherwise.

**Compared against:** `README.md`, `discoveries/games-media-art.md` (2026-09-13), `discoveries/trading-dopamine-wirehead.md` (2026-09-13), `discoveries/science-embodied-rl.md`. **New** means the repo URL is not already cited there. Cobanov’s parallel list [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) (243★, still being updated today) is a competitor index, not a demo; several of its game/desktop entries are still missing from this repo and are folded in below.

## Ranked: coolest new

Genuine misses that are cooler, newer, or a different loop than what the README already canonizes (DOOMFLY, Stonkfly, Fly64, Fly/Wirehead, DesktopFly, fly-escape, etc.). Rank is taste + substance (unique loop, honesty, live page, or a star signal), not a claim that any of these beat biology.

| # | Project | Stars | Dopamine/RL? | Live demo | One-liner |
|---|---|---:|---|---|---|
| 1 | [jerryjliu/fly_ocr](https://github.com/jerryjliu/fly_ocr) | 68 | RL readout (tiny decoder; wiring frozen) | local Vite viewer in-repo; [teaser mp4](https://github.com/jerryjliu/fly_ocr/releases/download/teaser-v1/fly-ocr-teaser.mp4) | Frozen MaleCNS (166,700 / 25.6M) as a character reservoir; 87.6% on a 1,632-glyph benchmark, 5.7% CER on selected PDF lines. Honest that a 3° tilt breaks it. |
| 2 | [nftechie/flm](https://github.com/nftechie/flm) | 65 | no (adapter trains; graph frozen; **no** PAM/PPL) | none (local chat after train) | Same author as DOOMFLY / Stonkfly: token embeddings drive the full retained MaleCNS; a 278k adapter nudges Liquid LFM2.5 logits. Matched direct-input control **slightly won**. |
| 3 | [nicodunks/fruitless](https://github.com/nicodunks/fruitless) | 32 | no | local Three.js (`npm start`) | mAL-block courtship assay on 166,606 classified MaleCNS cells with a recorded-activity fly viz. Result: male-cue responses rise after the block, **not** a male preference. |
| 4 | [TailsProwerWorks/PersonConnectome](https://github.com/TailsProwerWorks/PersonConnectome) | 1 | no (weights frozen) | People Playground mod (spawn **Person Connectome (Active)**) | Heavily updated **today**: MaleCNS-derived 176,422-neuron / 6.3M-edge graph drives a PPG Human. Huge mapping docs; DNp01 escape is gated by injury/looming, not a raw spike→run cheat. |
| 5 | [charbelkassab/flybrain-intransitive](https://github.com/charbelkassab/flybrain-intransitive) | 2 | no (zero training) | in-repo `media/fly_plays_intransitive.mp4` | Full MaleCNS plays [Intransitive](https://meaf.us/rps2/) (RPS-chess) by mapping good moves to small-object chase and bad moves to looming. 100–0 vs random; scrambled wiring 0 vs greedy. Sister of already-listed `flybrain-snake`. |
| 6 | [KakaoXI/fly-brain-billiards](https://github.com/KakaoXI/fly-brain-billiards) | 0 | **yes** — PAM reward current + KC→MBON; learning **not** shown to win pool | local browser eight-ball | Created **today**. Full retained 166,700 LIF sees the table, shoots stripes through an artificial cue, pulses PAM on useful outcomes. Italian UI (`biliardo`). |
| 7 | [oskarmalmwiklund/swat-or-buy](https://github.com/oskarmalmwiklund/swat-or-buy) | 0 | no | [swat-or-buy.vercel.app](https://swat-or-buy.vercel.app) (200) | Ad creative judged by MaleCNS optic-lobe salience (29k retina/lamina in-browser). Duel or bracket; the fly cannot read. Multiply Labs experiment. |
| 8 | [VaheOfficial/FLY](https://github.com/VaheOfficial/FLY) | 1 | no | local `flypet` (Rust / wgpu) | Full 166,700 / 25.6M GPU desktop pet. Keyboard/mouse/windows are senses; sugar stim of LB3b/c → MN9 is the lab check. Distinct from macOS DesktopFly. |
| 9 | [Decentricity/mindmeld-with-fly](https://github.com/Decentricity/mindmeld-with-fly) | 13 | no | local libcaca + Muse | Live Muse EEG (δ–γ) sparsely drives one MaleCNS reservoir; fly “EEG” is reservoir spectra, not insect electrophysiology. |
| 10 | [ZeroXClem/closed-loop-fly](https://github.com/ZeroXClem/closed-loop-fly) | 3 | no | in-repo `loop.html` + cruise GIF/mp4 | Closes the loop the README still lists as two pieces: AbijahKaj optic-lobe WebGPU **plus** Xenova whole-CNS LIF, images → wings → next pose. |
| 11 | [andrewevmiller/flybeats](https://github.com/andrewevmiller/flybeats) | 0 | RL (gains learned on frozen topology; **not** PAM11) | local `realtime.py` bundle | Updated **today**. MaleCNS-constrained drummer from audio. Pipeline now beats a constant predictor on a tiny CPU run; author says that is **not** a connectome result. |
| 12 | [eganeganegan/flydoom](https://github.com/eganeganegan/flydoom) | 3 | **yes** — PPO + optional three-factor / KC→MBON | local VizDoom + PyVista | **Not** a DOOMFLY fork. Asks whether MaleCNS topology is a useful RL inductive bias vs rewired / MLP / GRU / LSTM controls. Pushed today. Distinct from `nftechie/doomfly` and `mutkuoz/flydoom`. |
| 13 | [pratik90908/fly-doom](https://github.com/pratik90908/fly-doom) | 0 | **yes** — tabular Q-learning motor readout (FlyWire weights frozen) | [pratik90908.github.io/fly-doom](https://pratik90908.github.io/fly-doom/) (200) | Browser Doom + full FlyWire v783 viz. Every visitor trains their own readout in localStorage. |
| 14 | [jackspiece/flappy-fly](https://github.com/jackspiece/flappy-fly) | 0 | RL decoder pilots | [jackspiece.github.io/flappy-fly](https://jackspiece.github.io/flappy-fly/) (200) | 166,700-neuron arcade, distinct from already-listed `arjunkshah12345-hash/fly-flappy-bird`. |
| 15 | [pikabell/fly-tictactoe](https://github.com/pikabell/fly-tictactoe) | 0 | RL readout in-browser | [pikabell.github.io/fly-tictactoe](https://pikabell.github.io/fly-tictactoe/) (200) | 98 measured MaleCNS cells, 1,494 edges; silencing/rewiring controls in the UI. The honest small-circuit version of today’s tic-tac-toe wave. |

**Nearby, same coolness band (not ranked separately):**

- [seanphan/flyt3](https://github.com/seanphan/flyt3) (1★, created today) — tic-tac-toe / README also says Connect Four; **PPL101 aversive pulse + REINFORCE** on a linear motor readout; k3s GPU worker. Cites flychess-hq.
- [flychess-hq.vercel.app](https://flychess-hq.vercel.app) (200) — “Chess vs. a Fruit Fly Connectome.” **No public GitHub repo found** in `gh search`; cited by `seanphan/flyt3` and `Aananda-giri/fly-chess`.
- [Aananda-giri/fly-chess](https://github.com/Aananda-giri/fly-chess) (0★, created today) — trainable “cortex” grafted on frozen MaleCNS chess vs the flychess-hq linear-readout design. Split from [`Aananda-giri/fly-haven`](https://github.com/Aananda-giri/fly-haven) (0★).
- [ykakade/flappy-fly-connectome](https://github.com/ykakade/flappy-fly-connectome) (0★) — 96-cell MaleCNS neighborhood + **PPO**; 0→16.88 gates on held-out seeds; shuffled graph and MLP scored **higher**. Demo: [flappy-fly-connectome.pox.chatgpt.site](https://flappy-fly-connectome.pox.chatgpt.site) (200).
- [powerOFMAX/fly-parking-lab](https://github.com/powerOFMAX/fly-parking-lab) (0★) — Carla the fly parks a Mini Cooper in-browser (NeuroMechFly v2 + MuJoCo WASM). Live: [fly-parking-lab-teal.vercel.app](https://fly-parking-lab-teal.vercel.app) (200). Concept-adjacent to already-listed [Flyhard](https://github.com/MarkUnthank/flyhard) (physical wheel + CARLA); this one is a WebGL/WASM toy with a very marketing README.
- [hotocoo/malecns](https://github.com/hotocoo/malecns) (0★, today) — full MaleCNS wired to an F1 car on Monaco; ES-trained interface + neuron viewer.
- [tom2824/fly-survivors](https://github.com/tom2824/fly-survivors) (0★) — FlyWire v783 LIF on GPU plays Vampire Survivors.
- [hcsolakoglu/fruit-fly-plays-fruit-ninja](https://github.com/hcsolakoglu/fruit-fly-plays-fruit-ninja) (0★) — closed-loop MaleCNS Fruit Ninja with orbitable fly-at-PC scene and trace-backed videos.
- [mukndd/flyweight](https://github.com/mukndd/flyweight) (0★, pushed today) — 2D fighter with a FlyWire recurrent controller (distinct from already-listed Connectome Fighter).
- [realgauravvyas/flykick](https://github.com/realgauravvyas/flykick) (0★) — two teams of circuit-flies play football; possess any fly. [realgauravvyas.github.io/flykick](https://realgauravvyas.github.io/flykick/) (200). Same-day sibling pages `drosomind` / `afterwing` look like a vibe-coded cluster — playable, treat claims lightly.
- [vikas1188/fruitfly-darts](https://github.com/vikas1188/fruitfly-darts) (0★) — connectome learns darts + MuJoCo exoskeleton. [flydarts-arena.vercel.app](https://flydarts-arena.vercel.app) (200).
- [RupertDodkins/crud-fly](https://github.com/RupertDodkins/crud-fly) (0★) — 1,072 MaleCNS neurons nudge crud aim and still lose to a scripted bot. [rupertdodkins.github.io/crud-fly](https://rupertdodkins.github.io/crud-fly/) (200).
- [shivareddy42/flyway-surfer](https://github.com/shivareddy42/flyway-surfer) (0★) — 1,072-neuron endless runner. Homepage `flyway-surfer.lightningshiva1.chatgpt.site`.
- [Ziyang-Bai/nFly](https://github.com/Ziyang-Bai/nFly) (0★) — FlyBrain LIF on a **TI-Nspire CX** via Ndless. Weird hardware, real C.

## New: dopamine / trading / wirehead

Not already in `trading-dopamine-wirehead.md` or the README dopamine/trading sections.

- [davidmcarati/chonchurik](https://github.com/davidmcarati/chonchurik) (1★, created yesterday, pushed today) — **Johnny Silverfly, “son of Stonkfly.”** MaleCNS 166,700 / 25.6M; Coinbase Advanced via a custom AgentKit provider. Gains → **15 PAM11**, losses → **2 PPL101**, candidate KC→MBON. Kernel adapted from DOOMFLY; package still named `stonkfly`. **Not a thin fork:** README is a measurement dump (visual pathway saturated; 1.9 inhibitory ratio; readout SNR &lt; 1; **nothing traded at a profit**).
- [KakaoXI/fly-brain-billiards](https://github.com/KakaoXI/fly-brain-billiards) — see rank #6 (PAM + KC→MBON pool).
- [seanphan/flyt3](https://github.com/seanphan/flyt3) — PPL101 + REINFORCE (games, but dopamine-tagged).
- [ML-Chen/fruit-fly-utopia](https://github.com/ML-Chen/fruit-fly-utopia) (1★) — “a fruit fly given only things it wants.” MaleCNS somata, live hedonic index, motor programs from the **real reward circuit**. Wirehead art, sibling energy to Infinite Sugar / Fly-Wirehead.
- [funcreator2030/flylab](https://github.com/funcreator2030/flylab) (0★) — MaleCNS mushroom-body associative conditioning. Learns CS+/CS−; degree-matched null says **KC→MBON structure is not why**, ALPN→KC is. Built as a Stonkfly-stack alternative.
- [Flyextractor/extractor](https://github.com/Flyextractor/extractor) (0★, today) — MaleCNS vs scrambled wiring on U.S. stocks. Live: [flyextractor.online](https://flyextractor.online) (200). Expects a null.
- [Synapse-Fly/synapsefly](https://github.com/Synapse-Fly/synapsefly) (1★) — connectome paints price on a Win95 Paint canvas and tweets brain state. [synapsefly.com](https://www.synapsefly.com) (200).
- [Air-crypto/Stonkfly-Trading](https://github.com/Air-crypto/Stonkfly-Trading) (0★) — paper Solana lab: full Stonkfly net + 802-param Q head (earlier PPO). No real-order endpoint. Derivative of Stonkfly, more than a rename.
- [abigubi/fruit-fly-options-lab](https://github.com/abigubi/fruit-fly-options-lab) (0★, today) — MaleCNS reservoir for dividend-aware call-option experiments. Fresh; not audited beyond the GitHub description.
- [Rob-bio4/degeneretfly](https://github.com/Rob-bio4/degeneretfly) (0★) — MaleCNS LIF visualizer driven by live Polymarket CLOB depth. Homepage [kick.com/degenaratefly](https://kick.com/degenaratefly). Distinct from already-listed Polyfly (no GitHub).
- [InstarCage/instar](https://github.com/InstarCage/instar) (0★, today) — persistent MaleCNS flies as Solana NFTs. [instarcage.com](https://instarcage.com) (200). “The fly is the asset.” Crypto-cage; README is unusually careful about what is real.
- [primemeridiem/flyvape](https://github.com/primemeridiem/flyvape) (0★) — **thin conceptual fork** of `fruitflydev/flycoinrh` (author says so): nicotine rig, puff → dopamine, neurons die in 3D. [primemeridiem.github.io/flyvape](https://primemeridiem.github.io/flyvape/) (200).
- [rectinajh/counterfly](https://github.com/rectinajh/counterfly) (0★) — “cyber fruit-fly connectome” RWA counterfactuals. [counterfly.vercel.app](https://counterfly.vercel.app) (200). Markets-adjacent; treat as a branded dashboard until the connectome loop is re-read.

## New: desktop pets, EEG, phones, hardware

README already has DesktopFly (macOS) and CyberFly (Spectacles). These ports/new shells were missing.

- [VaheOfficial/FLY](https://github.com/VaheOfficial/FLY) — rank #8, full-CNS GPU pet.
- [So2K/musca-desktop-fly](https://github.com/So2K/musca-desktop-fly) (0★) — Windows desktop fly; sees, clicks, eats, live activity.
- [fengruochen8/cyberfly](https://github.com/fengruochen8/cyberfly) (0★) — MaleCNS-constrained autonomous macOS desktop fly (name collision with Spectacles CyberFly).
- [somsom10/desktop-fly-linux](https://github.com/somsom10/desktop-fly-linux) (3★, Aug 2026; still absent from this list) — GNOME/X11 port of DesktopFly, GTK3, no Electron.
- [lubabs770/gnat](https://github.com/lubabs770/gnat) (9★, Aug 2026) — Hyprland/Wayland DesktopFly port in Rust; 668-neuron circuit, `--flies 8`.
- [tegnike/fly-typist](https://github.com/tegnike/fly-typist) (0★, today) — Swift “virtual fly typing” based on DesktopFly; Japanese input + MP4 recording.
- [fortunto2/flykeeper](https://github.com/fortunto2/flykeeper) (0★, **created today**) — iOS/Swift FlyWire pet, 138,584 LIF neurons, offline. GitHub `size` still 0 at fetch (very new); tree has `Sources/`, `Resources/`, `Package.swift`. Engine claimed as a separate xcframework.
- [MindExtendAI/mindfly](https://github.com/MindExtendAI/mindfly) (0★) — Muse 2 EEG → MaleCNS walking circuit in the browser. [mindextend.com/mindfly](https://mindextend.com/mindfly) (200). Complementary to mindmeld (walk vs reservoir cinema).
- [mhdsilva/flywire-arduino](https://github.com/mhdsilva/flywire-arduino) (0★) — FlyWire on a laptop CPU driving an Arduino; escape/flight from wiring.
- [Ziyang-Bai/nFly](https://github.com/Ziyang-Bai/nFly) — TI-Nspire, above.

## New: language, art, science-as-demo

- [nftechie/flm](https://github.com/nftechie/flm) / [jerryjliu/fly_ocr](https://github.com/jerryjliu/fly_ocr) / [nicodunks/fruitless](https://github.com/nicodunks/fruitless) — ranks 1–3.
- [alexbuildstech/fly-connectome-lm](https://github.com/alexbuildstech/fly-connectome-lm) (0★, 252 MB, pushed today) — full MaleCNS as token-in/token-out LM vs a compute-matched transformer. Short answer: beats bigram, loses to transformer; wiring ties a shuffled copy. v3 unfreezes synapses with BPTT.
- [leetae9yu/fly-as-a-lm](https://github.com/leetae9yu/fly-as-a-lm) (0★) — character LM on a connectome, Colab T4. Smaller sibling of FLM / fly-connectome-lm.
- [nisbenz/flybrain-learns-english](https://github.com/nisbenz/flybrain-learns-english) (3★) — semantics probe.
- [mohvahedi/flylingo](https://github.com/mohvahedi/flylingo) (1★) — Spanish Q&A through 166,700 neurons + wiring control.
- [water-bear86/flytown](https://github.com/water-bear86/flytown) (2★) — connectome as planner for an LLM-worker swarm vs shuffled nulls; **results so far null**. [flytown-sigma.vercel.app](https://flytown-sigma.vercel.app) (200).
- [CakeCrusher/fly-adjudicator](https://github.com/CakeCrusher/fly-adjudicator) (0★) — fly “juror” on X posts; also a takedown of descending-neuron readouts. Homepage field is just male-cns.janelia.org.
- [Roxx0x/wetware](https://github.com/Roxx0x/wetware) (9★) — full connectome as reservoir; claimed 94% handwriting. Wiring frozen, readout only. Rust port: [awdemos/wetware-rs](https://github.com/awdemos/wetware-rs).
- [PixelML/firefly](https://github.com/PixelML/firefly) (0★, today) — frozen MaleCNS as wildfire-damage feature extractor; decoder-only; majority-class trap documented.
- [ashemag/fly-brain-atlas](https://github.com/ashemag/fly-brain-atlas) (7★) — interactive MaleCNS atlas. [fly-brain-atlas.vercel.app](https://fly-brain-atlas.vercel.app) (200). Tooling, not a game.
- [brandoncho369/flybench](https://github.com/brandoncho369/flybench) (1★) — reflex benchmark (sugar→MN9, looming→GF, …) so Doom/Minecraft gain knobs can be scored. Companion to already-listed fly-explorer. [fly-bench.com/bench](https://www.fly-bench.com/bench) (200).
- [cobanov/fly-connectome-template](https://github.com/cobanov/fly-connectome-template) (27★) — MaleCNS soma atlas + flybody mesh + React/Three workbench. Custom license requires UI+README attribution. Starter, not a pretrained brain.
- [anzal1/samesmell](https://github.com/anzal1/samesmell) (0★) — MaleCNS + FlyWire male/female react oppositely to the same pheromone in-browser.
- [5p00kyy/neuroterrarium](https://github.com/5p00kyy/neuroterrarium) (2★) — inspectable terrarium; default 48-cell graph is **synthetic**; MaleCNS GF microcircuit path reports a **negative** topology result. [neuroterrarium.5p00ky.dev](https://neuroterrarium.5p00ky.dev) (200).
- [vaibhavkedarisetti/fruit-fly-lab](https://github.com/vaibhavkedarisetti/fruit-fly-lab) (13★, Aug 2026) — Shiu 2024 LIF on full FlyWire; looming → LC4/LPLC2 → GF. Advertised Vercel host 404 at re-check; use the repo.
- [abgnydn/webgpu-fly](https://github.com/abgnydn/webgpu-fly) (5★, May 2026, still missing) — FlyWire + MANC + flybody in WebGPU/WASM. [webgpu-fly.pages.dev](https://webgpu-fly.pages.dev) (200).
- [lvl13icewizard/studiofly](https://github.com/lvl13icewizard/studiofly) (0★, 227k KB) — FlyWire on the DAW master bus. Distinct from already-listed Fly Lab (Ableton readout).
- [radiotedu/radiotedu-djfly](https://github.com/radiotedu/radiotedu-djfly) (0★, today) / [anloren/fly-dj-malecns](https://github.com/anloren/fly-dj-malecns) (0★) — DJ flies; overlap DJ Drosophila already in README. Inspect before promoting.
- [JacobEGarcia/fruit-fly-purgatory](https://github.com/JacobEGarcia/fruit-fly-purgatory) / [JacobEGarcia/fruit-fly-hell](https://github.com/JacobEGarcia/fruit-fly-hell) — waiting-room / suffering-sim art.
- [afterflydev/afterfly](https://github.com/afterflydev/afterfly) (0★) — paired neural-response leftover-signal experiments. [afterfly.fun](https://afterfly.fun) (200).
- [NullLabTests/flybrain](https://github.com/NullLabTests/flybrain) (1★) — 166,700-neuron current-injection arcade; glow is the voltage field. Listed on cobanov, missing here.
- [astelmach20/smallfly](https://github.com/astelmach20/smallfly) (0★) — town of 30k-neuron MaleCNS slices as generative agents. [smallfly.vercel.app](https://smallfly.vercel.app) (200).
- [RaphaelSR/fly-vial](https://github.com/RaphaelSR/fly-vial) (0★) — keep a FlyWire fly 50 days and teach tricks, 138,639 neurons in-browser. Same author as already-listed fly-brain-bench.
- [AntonioCoppe/flyciv](https://github.com/AntonioCoppe/flyciv) (0★) — colony sim; frozen brains, evolving adapters.
- [Pizzawookiee/catch_the_fly](https://github.com/Pizzawookiee/catch_the_fly) (0★) — you are a frog hunting a MaleCNS fly (MIT Green Building).
- [tibzejoker/ecrase-la-mouche](https://github.com/tibzejoker/ecrase-la-mouche) (0★) — swat game on FlyWire looming/GF (26,580 neurons in a worker). French sibling of already-listed Swat.
- [Yi-111-a/FlyCraft](https://github.com/Yi-111-a/FlyCraft) (1★, today) — MaleCNS → Minecraft fight/flee NPC. Fourth Minecraft fly after NeuroCraft / blendi-remade / ruby-project.
- [5RoD/FruitFly](https://github.com/5RoD/FruitFly) (0★, today) — Fabric 1.21.1 horror creature with FlyWire modulation + opt-in voice mimicry.
- [Jadog1122/fly-with-a-real-brain](https://github.com/Jadog1122/fly-with-a-real-brain) (0★) — 45,808 FlyWire neurons, browser 3D pet.
- [Poisson48/fruity_fly_triops](https://github.com/Poisson48/fruity_fly_triops) (0★) — Godot: Triops bodies driven by a FlyWire brain.
- [Jerry090215/eon-systems](https://github.com/Jerry090215/eon-systems) (0★, today) — 7,497 FlyWire neurons, LIF+STDP, macOS desktop. Name-collides Eon Systems’ already-listed fly-brain.
- [skulitom/haltere](https://github.com/skulitom/haltere) (0★) — 30k MaleCNS neurons trained to fly Liftoff FPV. Distinct from already-listed `joey-david/fly-fpv`.
- [Lak106/flybrain-pilot](https://github.com/Lak106/flybrain-pilot) (0★) — MaleCNS → flight-sim controls. Language field empty at fetch (thin-ish).
- [zhengxuyu/nfly](https://github.com/zhengxuyu/nfly) (0★, today) — MaleCNS as RNN for **any Gymnasium game**.
- [timfromhcs/FlyBrain](https://github.com/timfromhcs/FlyBrain) (0★, today) — Vulkan-first “artificial organism” framework on MaleCNS. Name-collides `Jhongdlp/FlyBrain`.
- [artem-x-meta/fly-arena](https://github.com/artem-x-meta/fly-arena) (4★) — FlyGym/MuJoCo + MaleCNS, two-fly food competition.
- [Sylviali-Maker/flybrain-sim](https://github.com/Sylviali-Maker/flybrain-sim) (5★) — Brian2 + FlyGym teaching bench (food/predator, 166-neuron raster — **not** the 166k graph despite the name).
- [Doga0/flycns-sim](https://github.com/Doga0/flycns-sim) / [dohun1214/flybrain](https://github.com/dohun1214/flybrain) / [2510034127qq-wq/malecns](https://github.com/2510034127qq-wq/malecns) — more MaleCNS+FlyGym/Arbor/MuJoCo benches; overlap Virtual-Embodied-Fly / Fly-Brain-AI.
- [monomyth/fly-brain-codex](https://github.com/monomyth/fly-brain-codex) / [monomyth/fly-brain-grok](https://github.com/monomyth/fly-brain-grok) — MaleCNS as robot-arm controller (HF weights on grok).
- [TomkeMonke/fly-brain-olympiad](https://github.com/TomkeMonke/fly-brain-olympiad) (0★) — full FlyWire on a Polish Informatics Olympiad task. [tomkemonke.github.io/fly-brain-olympiad](https://tomkemonke.github.io/fly-brain-olympiad/).
- [lntegrals/flycube-public](https://github.com/lntegrals/flycube-public) (0★) — MaleCNS in a Rubik’s cube solver loop.
- [michaelpersonal/flytype](https://github.com/michaelpersonal/flytype) (1★) — MaleCNS plays breakout **and** types, from pixels.
- [shovon/malecns-v1-dinosaur-game](https://github.com/shovon/malecns-v1-dinosaur-game) (0★, today) — Chrome dino. Overlaps already-listed cobanov/flyjump.
- [roymina/Fly_Gomoku](https://github.com/roymina/Fly_Gomoku) (0★) — MaleCNS + FlyWire gomoku.
- [meerzulee/palovbek](https://github.com/meerzulee/palovbek) (0★) — 166,700 neurons cook Uzbek plov in the browser.
- [onehappymonk/fly-orders-kfc](https://github.com/onehappymonk/fly-orders-kfc) (0★) — FlyWire sample makes a KFC order. Joke demo; real-ish sample, silly readout.
- [jtwolfe/flysune-miku](https://github.com/jtwolfe/flysune-miku) (0★) — “Flysune Miku” mushroom-body G2P TTS. Self-described meme science.
- [connorslab/hashfly](https://github.com/connorslab/hashfly) (0★, today) — Hashfly/BLAKE2b miner viz “adaptation.” Mining skin on a connectome; flag as novelty wrapper.
- [testinganything/accurate-fly-brain](https://github.com/testinganything/accurate-fly-brain) (0★) — Shiu-params whole-CNS LIF with a video pipeline that **explicitly includes adult content**. Skip for the public awesome list unless someone wants that framing.

## Already catalogued (not New)

Confirmed still live in search hits; **do not re-add**. Includes the Sep 6–13 canon plus shards:

DOOMFLY, Stonkfly, StonkFlyRH, stonkfly-lab, Fly/Wirehead, Scrollfly, FlyScroll, Infinite Sugar, Faiku, fly-mario, FlyTris, kick-the-fly, Aimbug, Swat, Fly Poker, fly-brain-poker, Flyhard, fly-brain-minesweeper, FlyPong, connectome-fighter, flyfear, fly-fpv, fly-craftax, fly-escape, DesktopFly, CyberFly/Spectacles, fly-hero, flyboard, flydoom (`mutkuoz`), NeuroCraft, Fly Brain Minecraft, ruby-project, fruit-fly-fashion, OpenFly, Richy, TraderFly, flycoinrh, flybrain-female, flywire-live, fruit-fly-fund, fruitfly.trade, Gregor, quantum-fly, YannickBeck/stonkfly (plan), fly-explorer, fly-brain-bench, fly-flappy-bird, flybrain-snake, FlyBrain boss, FlyBrain-HalfLife, flyputer, FLYBRAIN-BAD_APPLE_X_DOOM, FLYWATT, DJ Drosophila, FLYcasso, flyverse, fly-self-driving, fly.ai, eonsystemspbc/fly-brain, etc.

Cobanov-only science/tooling (datasets, navis, neuPrint, FlyBrainLab) still belongs on [watthem/awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome), not this demos list.

## Thin meme forks / stubs

Flagged so later README editors do not promote them as brand-new brains.

| Repo | Why it looks thin |
|---|---|
| [WeiserFox/FlyBrainGmod](https://github.com/WeiserFox/FlyBrainGmod) | Two-line README, GitHub size 0, no addon files. |
| [Thespaceblade/flappy-fly](https://github.com/Thespaceblade/flappy-fly) | README sketch + `NOTES.md` only (size 3). Name-collides jackspiece/ykakade. |
| [kankan-veda/FlyWire-NeuroArena](https://github.com/kankan-veda/FlyWire-NeuroArena) | Empty repo (“果蝇大脑和超级玛丽”). |
| [piyushdotcomm/flydynasty](https://github.com/piyushdotcomm/flydynasty) | Empty repo; description overclaims “zero assumptions.” |
| [guilhermemigra05-sys/FlyWire](https://github.com/guilhermemigra05-sys/FlyWire) | README-only, no description. |
| [Gary-XC/flywire-rl-engine](https://github.com/Gary-XC/flywire-rl-engine) | README + `requirements.txt` (size 12). |
| [Griff1018/MaleCNS-snake-game-training](https://github.com/Griff1018/MaleCNS-snake-game-training) | Author: “GA and brain setting is not completed… just a framework.” |
| [SlabyLol/fly-torture](https://github.com/SlabyLol/fly-torture) / [SlabyLol/flybrain-real](https://github.com/SlabyLol/flybrain-real) | Tiny HTML “torture chamber”; FlyWire-inspired, not a connectome runtime. |
| [Frankweb33/flybrain-robot-bridge](https://github.com/Frankweb33/flybrain-robot-bridge) | **33★ the day it was created.** README: default backend is eight hand-designed LIF groups; **MaleCNS is planned**. CI badge points at `Himas1211/flybrain-robot-bridge`. Star count is not evidence of a fly brain. |
| [torronen/stonkfly](https://github.com/torronen/stonkfly), [jonleach323/stonkfly](https://github.com/jonleach323/stonkfly), [fr303388/stonkfly](https://github.com/fr303388/stonkfly), [royaldynamo128-gif/stonkfly-bybit](https://github.com/royaldynamo128-gif/stonkfly-bybit) | Stonkfly copies / Bybit reskins. Dashboard-only: [Bgihe/stonkfly-dashboard](https://github.com/Bgihe/stonkfly-dashboard) (already in the trading shard’s “not added”). |
| [YannickBeck/stonkfly](https://github.com/YannickBeck/stonkfly) | Still a plan (`PLAN.md`), already noted. |
| [primemeridiem/flyvape](https://github.com/primemeridiem/flyvape) | Author: started as a copy of flycoinrh; new files are the vape overlay. |
| [bubbezhue/galaxybrain](https://github.com/bubbezhue/galaxybrain) | `$FLYBRAIN` token landing clone. |
| [makeitdouble/real-doomfly-sd15-loop](https://github.com/makeitdouble/real-doomfly-sd15-loop) | SD1.5 loop “real brain” installer scripts; not a new arena. |
| [putra10/flywire](https://github.com/putra10/flywire) | Generic Vercel page named FlyWire. |
| [ChihHsiangChien/maleCNS](https://github.com/ChihHsiangChien/maleCNS) / [as7ar/malecns-test](https://github.com/as7ar/malecns-test) / [wadamczewski/malecns-simulator](https://github.com/wadamczewski/malecns-simulator) | Empty or undescribed MaleCNS-named dumps. |
| [JangYeongSil69420/fly-wirehead-kaggle-version](https://github.com/JangYeongSil69420/fly-wirehead-kaggle-version) | Notebook rehost of Fly/Wirehead (already excluded in the trading shard). |
| [eganeganegan/flydoom](https://github.com/eganeganegan/flydoom) vs [nftechie/doomfly](https://github.com/nftechie/doomfly) vs [mutkuoz/flydoom](https://github.com/mutkuoz/flydoom) vs [pratik90908/fly-doom](https://github.com/pratik90908/fly-doom) | Four Doom flies. Only `eganeganegan` and `pratik90908` are new; do not merge them. |
| Same-day Flappy cluster | `jackspiece/flappy-fly` (has a live arcade), `ykakade/flappy-fly-connectome` (PPO, honest null on topology), `Thespaceblade/flappy-fly` (stub), plus already-listed `arjunkshah12345-hash/fly-flappy-bird`. |
| `realgauravvyas/{flykick,drosomind,afterwing,connectomics}` | Four same-day GitHub Pages toys. `flykick` is the one with a clear playable loop. |

## Search notes

- `gh search repos MaleCNS --sort updated` → **131** hits (API total_count). Pages saved under this pass; ~100 were absent from this repo’s README/shards.
- Also searched: `FlyWire` created `>=2026-09-01`; `fruit fly connectome` created `>=2026-09-01`; `stonkfly`; `doomfly`; `fly-wirehead`; `"166,700"`; `flybrain` created `>=2026-09-01`. Quoted `166700` (no comma) returned nothing useful. Repo search for `PAM11` is polluted by Java class homework; the PAM11 hits that matter (`chonchurik`, billiards, flyt3) came from MaleCNS / `166,700` descriptions.
- `gh search` `--sort created` is not supported; recency used `--created >=2026-09-01` and `--sort updated`.
- Cobanov [`awesome-fly`](https://github.com/cobanov/awesome-fly) (243★) is ahead of this list on desktop ports (`gnat`, `desktop-fly-linux`), FLM, fruitless, flyt3, NullLabTests/flybrain, mindmeld. Worth diffing again after README freeze.
- X/Twitter was not used as a source. Hugging Face Spaces were not re-crawled (Xenova already listed).
- Star outliers that are **not** cooler demos: `fruitflydev/flycoinrh` 174★ (already listed), `nftechie/stonkfly` 635★ / `doomfly` 261★ / `fly-wirehead` 118★ (canon), `dzhng/fly-escape` 41★, `ornata/fly` 38★, `Frankweb33/flybrain-robot-bridge` 33★ (see thin table).

*End of shard. Fold only the strongest verified items into README; do not dump this file wholesale.*
