# Games / media / art shard

Fruit-fly connectome demos in games, VR, music, art, social, and entertainment (MaleCNS / FlyWire / Drosophila connectome controlling something fun).

Research date: 2026-09-13. Links below were HTTP-checked or fetched as live GitHub/Hugging Face/demo pages. Tweet URLs are omitted unless a public page was retrieved; news citations are evidence notes only.

## Known

Listed for completeness. Not treated as new finds.

- **DOOMFLY** / Alex Wormuth (`@nftechie_`) — MaleCNS frames → sensory neurons → Doom controls; damage stims PPL101 dopamine. Repo: https://github.com/nftechie/doomfly — Dopamine/RL? yes — Evidence: fetched README (PPL101 + KC→MBON plasticity); Gizmodo / Tom's Hardware / GIGAZINE cover the X post.
- **Mario 64 / Fly64** / Jessica Paquette (`@barrelshifter`; repo `ornata/fly`) — MaleCNS hooked to Super Mario 64. Repo: https://github.com/ornata/fly — Dopamine/RL? unclear — Evidence: GitHub API `ornata/fly` description “malecns fly hooked up to mario”; Gizmodo/Tom's Hardware name Paquette.
- **NeuroCraft Fly** / Evan Sinclair Smith (`evnsnclr`) — Minecraft fly driven by retained MaleCNS activity. Repo: https://github.com/evnsnclr/neurocraft-fly-public — Dopamine/RL? unclear — Evidence: fetched public-home README; IBTimes UK.
- **Beat Saber** / Lyra (`@_lyraaaa_`) — Viral “the fly brain can play Beat Saber” clip. No public repo found in this pass. — Dopamine/RL? no (later caveat: motor replay / not yet autonomous) — Evidence: IBTimes UK + Know Your Meme name `@_lyraaaa_`; no tweet URL retrieved here.
- **Bad Apple** / Kevin Lin (`kevinlinxc`; news also cites `@linguinelabs`) — Bad Apple frames through a fly connectome. Repo: https://github.com/kevinlinxc/badapple-fly — Dopamine/RL? no — Evidence: GitHub API + repo description.
- **Fly social network** / `@nftechie_` — Known social demo; not re-verified as a separate repo in this pass.
- **Fly Hero** / `actuallyrizzn` — Frozen fly-connectome reservoir plays Clone Hero from the note highway. Repo: https://github.com/actuallyrizzn/fly-hero — Dopamine/RL? unclear (readout trains; wiring frozen) — Evidence: fetched README.
- **FLYBOARD** / `sukoji` — Music chart voted by a full MaleCNS GPU sim (84 songs). Repo: https://github.com/sukoji/flyboard — Demo: https://sukoji.github.io/flyboard/ — Dopamine/RL? no — Evidence: fetched README + GitHub Pages mentioned there.
- **fly_chess** / `tolatolatop` (and in-progress `xenonbomin54/flyChess`) — FlyWire LIF chess in-browser. Repo: https://github.com/tolatolatop/fly-chess — Demo: https://tolatolatop.github.io/fly-chess/ — Dopamine/RL? no (fixed untrained readout) — Evidence: fetched README.
- **Infinite Sugar** / `cnqso` — Browser terrarium artwork. Repo: https://github.com/cnqso/infinite-sugar — Demo: https://infinitesugar.cnqso.com — Dopamine/RL? unclear — Evidence: GitHub API homepage + cobanov list.
- **flydoom** / `mutkuoz` — FlyWire/FAFB-v783 brain playing Doom. Repo: https://github.com/mutkuoz/flydoom — Dopamine/RL? unclear — Evidence: GitHub API description.

## New

### Games

- **Aimbug** / SlickDomi (`slickdomi`; news: domi on Bluesky)
  - Browser FPS aim trainer: full MaleCNS (166,700 neurons) steers/pitches via DNa02/DNp53 and fires one shot per pIP10 courtship-song bout while LC10 “sight” is open; targets are photos of female flies.
  - Repo: https://github.com/slickdomi/aimbug — Live: https://aimbug.domi.zip/ (also https://slickdomi.github.io/aimbug/)
  - Dopamine/RL? no
  - Evidence: fetched live site and GitHub README (“no trained readout and no aim logic”); HTTP 200 on both URLs. Tweaktown/Gaming ProMax describe the same project (courtship song → shoot).

- **Swat** / `hrook1`
  - Browser arcade: swat a fly whose evasive turns/bursts are influenced by a 6,000-neuron MaleCNS LC16→MDN retreat circuit.
  - Repo: https://github.com/hrook1/Swat — Play: https://fruitfly-tiny-brain.vercel.app/
  - Dopamine/RL? no
  - Evidence: fetched README; HTTP 200 on play URL.

- **Kick the Fly** / `legendarylolo318-cloud`
  - Kick-the-buddy toy: live 166,700-neuron MaleCNS; tools hit real sensory neurons; sugar lights PAM dopamine and heals.
  - Repo: https://github.com/legendarylolo318-cloud/kick-the-fly
  - Dopamine/RL? yes (PAM reward on sugar; not a trained game policy)
  - Evidence: fetched README (PAM dopamine, descending-neuron reactions).

- **Fly Poker** / `HappyAny`
  - Two-player 13-card shedding game vs a full-connectome fly sim in the browser (WebGPU/CPU).
  - Repo: https://github.com/HappyAny/fly-poker — Play: https://fly-poker.piphipsi.com/
  - Dopamine/RL? unclear
  - Evidence: fetched README; HTTP 200 on demo.

- **fly-brain-poker** / `ItayParienty`
  - FlyWire mushroom-body LIF sat at Texas Hold’em; innate wiring discriminates hands; outcome-driven dopamine did not teach cards.
  - Repo: https://github.com/ItayParienty/fly-brain-poker
  - Dopamine/RL? yes (dopamine plasticity tested; learning result negative)
  - Evidence: fetched README tables (conditioning vs poker reward).

- **Flyhard** / `MarkUnthank`
  - MaleCNS model learns to turn a physical steering wheel with fly legs and drive CARLA (stock Mini Cooper; “Flyat” Panda planned).
  - Repo: https://github.com/MarkUnthank/flyhard
  - Dopamine/RL? yes (optimizer / training updates; documented hold-out steering)
  - Evidence: fetched README (100/100 held-out after training). Tweaktown’s “fly-controlled driving simulation” matches this repo.

- **Fly-Brain-Minesweeper** / `Kaos599`
  - 80-neuron MaleCNS subgraph plays Minesweeper with a Three.js neural HUD; CEM-trained readout (96.4% safe reveals on beginner boards, per README).
  - Repo: https://github.com/Kaos599/fly-brain-minesweeper
  - Dopamine/RL? yes (cross-entropy method on readout)
  - Evidence: fetched README; HTTP 200 on GitHub.

- **FlyTris** / `rothilion26`
  - MaleCNS mushroom body (KC→MBON, PAM/PPL1) learns Tetris as odor-gradient navigation with dopamine-gated plasticity.
  - Repo: https://github.com/rothilion26/flytris
  - Dopamine/RL? yes
  - Evidence: fetched README (DAN compartments, APL ablation results).

- **MaleCNS Tetris** / `on7jya`
  - Tetris + connectome viz on a MaleCNS visuo-motor circuit (R1–R6 → LoVP92 → VES200m → DNg13), with FAFB/BANC switches.
  - Repo: https://github.com/on7jya/brain_fly
  - Dopamine/RL? unclear
  - Evidence: fetched README.

- **Help the Fly Escape** / `dzhng`
  - 3D browser house-escape: place furniture, release flies whose MaleCNS LIF circuits drive movement.
  - Repo: https://github.com/dzhng/fly-escape — Play: https://fly-escape.vercel.app/
  - Dopamine/RL? no
  - Evidence: fetched README; HTTP 200 on play URL. Likely the “escape room” mentioned in Tweaktown.

- **FlyPong** / `jonatasperaza`
  - Pong paddle from a MaleCNS subgraph; ball position → LIF → motor readout. Dopamine plasticity variants failed to learn.
  - Repo: https://github.com/jonatasperaza/FlyPong
  - Dopamine/RL? yes (tested; negative result)
  - Evidence: fetched README validation section.

- **Connectome Fighter** / `Unjuno`
  - MaleCNS LIF mapped into FightingICE; project-defined RL/plasticity kept separate from wiring.
  - Repo: https://github.com/Unjuno/connectome-fighter — Ledger: https://unjuno.github.io/connectome-fighter/ — homepage also lists https://connectome-fighter.vercel.app
  - Dopamine/RL? yes (project-defined reinforcement)
  - Evidence: fetched README + GitHub API homepage.

- **Fly Dino** / Mert Cobanov (`cobanov`)
  - Original Chromium Dino jumped by an 80-cell MaleCNS circuit + 243-parameter CEM-trained readout (99/100 held-out courses in published checkpoint).
  - Repo: https://github.com/cobanov/flyjump — Play: https://flydino.cobanov.dev/
  - Dopamine/RL? yes (CEM neuroevolution of readout only)
  - Evidence: fetched README; HTTP 200 on play URL.

- **FLYFEAR** / `furkancak1r`
  - Godot first-person horror: a MaleCNS-derived sim flies in the room and an external reward-updated layer picks scare events.
  - Repo: https://github.com/furkancak1r/flyfear — Play: https://furkancakir.dev/flyfear/
  - Dopamine/RL? yes (external decision layer, pretraining reported)
  - Evidence: fetched README (play URL in README).

- **FlyBrain (boss)** / `Jhongdlp`
  - Video-game boss driven in real time by a MaleCNS LIF engine (Rust/WASM + Three.js), not a behavior tree.
  - Repo: https://github.com/Jhongdlp/FlyBrain
  - Dopamine/RL? no (README: not a DRL policy)
  - Evidence: fetched README.

- **flypv / fly-fpv** / `joey-david`
  - MaleCNS adjacency-masked sparse controller trained (BC then PPO) to fly a 3D hoop course.
  - Repo: https://github.com/joey-david/fly-fpv
  - Dopamine/RL? yes (PPO; weights learned, topology constrained)
  - Evidence: fetched README.

- **Fly Brain Minecraft** / `blendi-remade`
  - Fabric 1.21.1 mod: each fly mob runs a MaleCNS LIF brain; world → real sensory cells; DNs/motors → mob actions; live brain HUD.
  - Repo: https://github.com/blendi-remade/fly-brain-minecraft
  - Dopamine/RL? unclear
  - Evidence: fetched README. Distinct from NeuroCraft (`evnsnclr`).

- **ruby-project** / `wavendis`
  - Minecraft NeoForge mod giving a mob a FlyWire brain with dopamine-gated KC→MBON learning.
  - Repo: https://github.com/wavendis/ruby-project
  - Dopamine/RL? yes
  - Evidence: fetched README (“What's real vs fabricated” table). Distinct from NeuroCraft (FlyWire vs MaleCNS, earlier August 2026 date).

- **fly-craftax** / `liuzihe02`
  - FlyWire/MaleCNS agent in Craftax with PPO on a descending-neuron readout (research prototype).
  - Repo: https://github.com/liuzihe02/fly-craftax
  - Dopamine/RL? yes
  - Evidence: GitHub API description + cobanov list; repo exists (2026-09-09).

### VR / AR

- **CyberFly** / Pavlo Tkachenko (`PtPavloTkachenko`)
  - Hologram flies on Snap Spectacles (2024); each runs full MaleCNS on a Mac Metal GPU; glasses stream room senses, DNs move wings/legs/head.
  - Repo: https://github.com/PtPavloTkachenko/fly-brain-spectacles — Blog cited in README: https://pavlo-stijn.dev/blog/posts/a-real-fly-brain-on-spectacles.html
  - Dopamine/RL? no
  - Evidence: fetched README (demo mp4 path + architecture).

### Desktop / toys

- **DesktopFly** / Denis Shiryaev (`DenisSergeevitch`)
  - 3D fly living on a macOS (and Electron) desktop; FlyWire looming/escape circuit plus MaleCNS motor extract; cursor looming can trigger Giant Fiber takeoff.
  - Repo: https://github.com/DenisSergeevitch/desktop-fly
  - Dopamine/RL? no
  - Evidence: fetched README (v1.1.0 MaleCNS motor extract).

### Music

- **Fly Lab** / `Apolotary`
  - Ableton Live: fly motor-circuit activity → small trainable musical readout (“More/Less like this”); also Fly Tombola / ambient garden modes.
  - Repo: https://github.com/Apolotary/fly-lab
  - Dopamine/RL? yes (70 musical weights; wiring frozen)
  - Evidence: fetched README.

### Art

- **Neural Canvas / Fruit Fly Simulation** / Joshua Lochner (`Xenova`)
  - Browser WebGPU demo: paint/stimulate 166,700 MaleCNS neurons and watch a Three.js NeuroMechFly body walk/turn/fly (illustrative kinematics).
  - Space: https://huggingface.co/spaces/Xenova/fruit-fly-simulation
  - Dopamine/RL? no
  - Evidence: fetched Hugging Face README; HTTP 200 on the Space.

- **Fruit Fly Fashion** / `jtc268`
  - Full MaleCNS LIF (via DOOMFLY proxy) spike vectors place/rotate/scale prints for a six-shirt drop; proof videos on YouTube.
  - Repo: https://github.com/jtc268/fruit-fly-fashion — Shop cited: fruitfly.fashion — Videos: https://youtu.be/PsyYCbb3VdU (and five more listed in README)
  - Dopamine/RL? no
  - Evidence: fetched README.

- **Faiku** / `xyzzyapps`
  - MaleCNS mushroom-body RL writes Japanese/English haiku as a fly-font ink trail (PAM/PPL1 dopamine on glyph match).
  - Repo: https://github.com/xyzzyapps/faiku
  - Dopamine/RL? yes
  - Evidence: fetched README (generated 5–7–5 example).

### Social / entertainment feeds

- **FlyScroll** / `ranagwho`
  - MaleCNS “doomscroller”: photoreceptors watch short-form video; novelty-MBON habituation advances the clip.
  - Repo: https://github.com/ranagwho/Fruitfly-Doomscroller
  - Dopamine/RL? unclear (KC→MBON depression / homeostasis, not a reward trainer)
  - Evidence: fetched README.

- **Fly / Wirehead** / `mattyhempstead`
  - Full MaleCNS watches endless insect Shorts on a virtual phone; pixels → network → body + dopamine-neuron overlay.
  - Repo: https://github.com/mattyhempstead/fly-wirehead
  - Dopamine/RL? unclear (overlay shows dopamine cells; no claimed RL loop in README excerpt)
  - Evidence: fetched README.

## Mentioned, not verified as standalone new demos

Skipped as new entries (no first-party URL retrieved, or already Known):

- **Fruit fly heaven** — IBTimes UK / Gaming ProMax quote a peaceful grass/fruit sandbox (handle given as Macroblock / `@sainim` in one article). No repo or tweet retrieved.
- **Ro0oney Minecraft YouTube** (“I Put A Fly's Conscious Brain into Minecraft”) — Know Your Meme / ixbt; no stable YouTube URL fetched here. Separate from NeuroCraft and `blendi-remade`.
- **Aimbug-as-Beat-Saber** — Tweaktown says Aimbug started as Beat Saber; the live site/README now describe an FPS trainer only.
- **FLYHARD Studio** (`rjrobinson/flyhard-studio`) — Meme-video generator; README states it is *not* a connectome simulation.
- Trading bots (Stonkfly, OpenFly, FlyDegen, meme coins) — out of this shard’s games/media/art focus unless they are social toys; Stonkfly is nftechie-adjacent and not duplicated here.

## Search notes

GitHub code/repo search (`MaleCNS`, fruit-fly connectome + game names), cobanov/awesome-fly games/art sections, Hugging Face Spaces (`Xenova/fruit-fly-simulation`), GIGAZINE / Tom's Hardware / Gizmodo / Tweaktown / IBTimes UK (Sep 2026). X itself was not reachable as a first-party API in this environment.
