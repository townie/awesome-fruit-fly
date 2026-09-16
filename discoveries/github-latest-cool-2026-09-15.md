# GitHub-latest cool (15–16 Sep 2026)

Research date: **2026-09-16** (UTC). Scope: brand-new or heavily updated MaleCNS / FlyWire / fruit-fly-connectome **demo** repos since ~**2026-09-14**, ranked by novelty versus the existing [README](../README.md) plus [`discoveries/*.md`](.).

Stars are GitHub API `stargazers_count` from this pass. Missing stars are omitted, not guessed. No invented URLs. Live demos were HTTP-checked (200) unless marked otherwise.

**Compared against:** `README.md` (last updated 14 Sep 2026), `discoveries/github-latest-cool.md` (2026-09-14), `discoveries/x-latest-cool-2026-09-14.md`, `discoveries/games-media-art.md`, `discoveries/trading-dopamine-wirehead.md`, `discoveries/science-embodied-rl.md`. **New** means the repo URL is not already cited there. Cobanov [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) (326★ this pass; last push 14 Sep) is a competitor index, not a demo; it had not absorbed the 15 Sep drops below.

These remain wiring-diagram simulations. A live page, a PAM pulse, or a trained readout is an interface, not proof a fly learned Doom, ACLS, CSS, or memecoins.

## Ranked: coolest new

Genuine misses that are cooler or a different loop than what the README already canonizes. Rank is taste + substance (unique I/O, honesty, live page, or a control table), not star count. `ns2250225/fly-flappy` is the star outlier among *new* demos; it is not #1.

| # | Project | Stars | Dopamine/RL? | Live demo | One-liner |
|---|---|---:|---|---|---|
| 1 | [steph4n-gh/fly-space-program](https://github.com/steph4n-gh/fly-space-program) | 1 | RL readout on frozen 166,700-node graph (not PAM11) | [fly.steph4n.dev](https://fly.steph4n.dev/) (200) | MaleCNS as a booster pilot: 60/80 held-out safe landings; covering both eyes → 0/80. Orbit still fails. Fly Cube hardware is concept art. Created 14 Sep. |
| 2 | [webergithub/fruitfly-lab](https://github.com/webergithub/fruitfly-lab) | 0 | no (fixed LC10a→DNa02 readout; **no** training) | [opcstudio.cc/fly-aim](https://opcstudio.cc/fly-aim/) (200) | FlyWire LC10a pursuit circuit (3,963 LIF neurons) aims a gun in-browser. Same graph on ViZDoom *defend_the_center*: 10.2 kills vs 0.7 scrambled. Created 15 Sep. |
| 3 | [Jimmy110101013/fly-megacode](https://github.com/Jimmy110101013/fly-megacode) | 0 | **yes** — PAM if right, PPL1 if wrong; only KC→MBON plastic | [jimmy110101013.github.io/fly-megacode](https://jimmy110101013.github.io/fly-megacode/) (200) | FlyWire mushroom body learns AHA 2025 ACLS by trial-and-error (76.8% on unseen megacodes vs 12.5% chance). Not a clinical tool. Created 15 Sep. |
| 4 | [Pr1nted/Open-Fly](https://github.com/Pr1nted/Open-Fly) | 1 | no (untrained DN groups) | [pr1nted.itch.io/open-fly](https://pr1nted.itch.io/open-fly) (200); advertised `open-fly.pages.dev` **NXDOMAIN** here | Whole FlyWire LIF (138,639; Shiu spike-for-spike) plays the *Open Doctrines* strategy game from sugar/bitter/water/JO encodings. Preregistered; not good at it. Created 13 Sep, still pushing 15 Sep. |
| 5 | [Aur1ety/DOOM-x-Fly](https://github.com/Aur1ety/DOOM-x-Fly) | 3 | RL readout (imitation + DAgger-ish; wiring frozen) | local ViZDoom + `docs/RESULTS.md`; videos “links coming” | MaleCNS subgraph (138,968 / 4.6M) finishes shareware E1M1 **57%** vs 0% random / 6% blind replay. Author flags an earlier test where random wiring carried as much signal. Created 15 Sep. **Not** a nftechie/doomfly fork. |
| 6 | [tolga-ileri/FlyCoder](https://github.com/tolga-ileri/FlyCoder) | 2 | experimental Q / idle-commit **outside** the graph | in-repo `docs/media/flycoder-demo.mp4` | “166,700 fruit fly neurons trying to center a div.” Frozen fly.ai `FlyBrain`; CSS error → LC10a/LPLC2; DNs → LEFT/RIGHT/COMMIT. Created 15 Sep. |
| 7 | [dogluk/fly-fruit-buffet](https://github.com/dogluk/fly-fruit-buffet) | 1 | **yes** — PAM vs PPL1 compartments on measured KC→MBON (no invented innate-valence table) | local 3D odor toy | FlyWire PN→KC + DoOR 2.0 receptors: fermenting fruit vs citrus valence *falls out of* measured wiring. Created 13 Sep; previous shards missed it. |
| 8 | [SpikeCalls/FlyDrones](https://github.com/SpikeCalls/FlyDrones) | 0 | no (optic-flow → identified DNs; safety governor is engineered) | [spikecalls.github.io/FlyDrones](https://spikecalls.github.io/FlyDrones/) (200) | Webcam / palm-looming flies a browser MiniFly (**850** spiking cells in the hosted loop; local path loads MaleCNS). Giant Fiber escape on a rush at the camera. Created 15 Sep. |
| 9 | [bsgelman/fly-hero](https://github.com/bsgelman/fly-hero) | 0 | **yes** — dopamine inside a 6,900-cell MaleCNS subgraph; shuffled wiring stays ~22% | [bsgelman.github.io/fly-hero](https://bsgelman.github.io/fly-hero/) (200) | Three-lane Guitar Hero: 33% → 99.3% after 30 songs; dopamine-blocked stays ~33%. **Name-collides** already-listed `actuallyrizzn/fly-hero` (Clone Hero reservoir). Created 15 Sep. |
| 10 | [KremlevLev/flydurak](https://github.com/KremlevLev/flydurak) | 1 | **yes** — batched RL on MaleCNS recurrent policy + GRU heads | local `python run.py` → localhost:8765 | 165,122-neuron Durak with a playable activity viz. Checkpoint can beat humans; GRU/LSTM multi-seed bake-off unfinished. Created 15 Sep. |
| 11 | [ns2250225/fly-flappy](https://github.com/ns2250225/fly-flappy) | 9 | RL readout (`ONLINE TRAIN` / logistic; `PURE BRAIN` DNp01 path has no learning) | [8cef51e4.pinme.dev](https://8cef51e4.pinme.dev/) (200) | Full retained MaleCNS in a Web Worker playing Flappy Bird. Highest-star *new* demo this window; still another flappy after jackspiece / ykakade / arjunkshah. Created 15 Sep. |
| 12 | [Palak11245/fly-guitar](https://github.com/Palak11245/fly-guitar) | 0 | **yes** — measured KC→MBON depression; **reward is invented** (a fly has no key) | local `http://127.0.0.1:4661/` | 165,122-neuron MaleCNS hears a backing track via Johnston’s Organ and plays guitar. Walking DNs were dead to sound; motor neurons were not. Created 14 Sep. |
| 13 | [freewangfei/digitalfly](https://github.com/freewangfei/digitalfly) | 4 | no (closed-loop body; transmitter-signed graph) | local `cli.py web` | MaleCNS + flybody + FlyGym kinematics: 185,348 nodes / 26.0M edges, split-screen soma spikes vs MuJoCo. Created 13 Sep; still missing from this list. |
| 14 | [HEREISCB/flybrain](https://github.com/HEREISCB/flybrain) | 1 | no | local installer → `localhost:8765` | Kitchen-table poke lab: 167,106 MaleCNS neurons, sugar/fruit/fan/loom tools, Metal/CUDA/CPU. Name-collides `snedea/flybrain` / `Jhongdlp/FlyBrain`. Created 15 Sep. |
| 15 | [tomzlabs/fly-xiangqi](https://github.com/tomzlabs/fly-xiangqi) | 0 | no (forked from already-listed `tolatolatop/fly-chess`) | [fly-xiangqi.vercel.app](https://fly-xiangqi.vercel.app) (200) | Same FlyWire LIF chess engine, Chinese chess instead of international. Created 15 Sep. |

**Nearby, same coolness band (not ranked separately):**

- [AndresChacon00/fly-connectome-mujoco](https://github.com/AndresChacon00/fly-connectome-mujoco) (1★, 14 Sep) — 166,700 LIF + MuJoCo forage / eat / Giant Fiber escape / land. Scrambled wiring: TTMn 0 spikes vs 38 real. In-repo `vida_de_mosca.mp4`.
- [ChenYvhang/cyberfly-explorer](https://github.com/ChenYvhang/cyberfly-explorer) (2★, 14 Sep) — Three.js habitat; **hosted page is a lightweight controller**, full 166,700 is local-only. [chenyvhang.github.io/cyberfly-explorer](https://chenyvhang.github.io/cyberfly-explorer/) (200).
- [vasu-devs/fly-habitat](https://github.com/vasu-devs/fly-habitat) (0★, 15 Sep) — FlyWire WebGPU + flybody MuJoCo lineage. [fly.siddhvasudev.com](https://fly.siddhvasudev.com) (200).
- [empire/fruit-fly](https://github.com/empire/fruit-fly) (1★, 14 Sep) — Go MaleCNS reservoir vs tic-tac-toe / hexapawn / Othello; only the linear readout is REINFORCE-trained; asks whether the brain helps.
- [nyoki-mtl/fly-shogi](https://github.com/nyoki-mtl/fly-shogi) (0★, 15 Sep) — MaleCNS shogi (“Fly Meijin”); L-BFGS-B MBON fit **or** dopamine-like KC→MBON updates.
- [radekvechet/FlyTris](https://github.com/radekvechet/FlyTris) (0★, 14 Sep) — **Not** already-listed `rothilion26/flytris`. 256-cell FlyWire circuit, human-vs-fly, [flytris.net](https://www.flytris.net) (200). Output weights only.
- [AlexNoyanov/MaleCNS-Driving-Robot](https://github.com/AlexNoyanov/MaleCNS-Driving-Robot) (1★, 15 Sep) — Arduino 2WD + Pi camera + Mac MaleCNS subset (~4,057 AL neurons). Physical robot, not CARLA/Flyhard.
- [saruar-ryskaliyev/psp-fly](https://github.com/saruar-ryskaliyev/psp-fly) (0★, 15 Sep) — PSP-2000 arena: FlyWire sugar net (2,774) is real; walking “noise brain,” heading ring, and path integrator are **hand-wired** and documented as such.
- [freaker2k7/desktop-fly](https://github.com/freaker2k7/desktop-fly) (2★, 14 Sep) — Go/OpenGL desktop fly on a **few** MaleCNS types (DNge104, KC, HBeyelet, TTMn), not whole-CNS. Distinct from `DenisSergeevitch/desktop-fly`.
- [annel0/flybrain](https://github.com/annel0/flybrain) (2★, created 13 Sep, pushed 14 Sep) — Triton GPU LIF plus an honest “what if we *add* neurons to this brain?” failure log.
- [Kisame76/drosophila-brain-mlx](https://github.com/Kisame76/drosophila-brain-mlx) (0★, 14 Sep) — Shiu LIF on Apple MLX (FlyWire v630 + MaleCNS), Brian2-checked, shuffled-connectome control.
- [zhuhaozoo/FlyBrain-HarmonyOS](https://github.com/zhuhaozoo/FlyBrain-HarmonyOS) (0★, 15 Sep) — Full FlyWire v783 LIF on a HarmonyOS phone (ArkTS / ArkGraphics 3D).
- [Reaper404-wag/drosophila-1c](https://github.com/Reaper404-wag/drosophila-1c) (0★, 14 Sep) — FlyWire closes 1C:Enterprise lab assignments (PDF → real infobase). Joke I/O with an honest “what actually decides” section.
- [pbomaster/Fruitfly-reviewer](https://github.com/pbomaster/Fruitfly-reviewer) (0★, 15 Sep) — MaleCNS extractive paper reviewer with **no** pretrained LM backbone (contrast already-listed FLM).
- [yub4-arema/flymerge](https://github.com/yub4-arema/flymerge) (1★, 14 Sep) — Diff → LIF → approve/reject/hold. Self-described PR-judge joke.
- [lorcanorourkeai/flykeys](https://github.com/lorcanorourkeai/flykeys) (0★, 14 Sep) — Connectome types into Claude Code to build a Clay workflow; learning is cued key-targeting only.
- [Mihir717/flybrain-dogfight](https://github.com/Mihir717/flybrain-dogfight) (0★, 22 kb, 15 Sep) — MaleCNS reservoir + evolutionary readout dogfights F-16s in JSBSim. Thin-ish tree; dopamine/hit rewards claimed in the description.
- [theajmalrazaq/drosophiladrone](https://github.com/theajmalrazaq/drosophiladrone) (0★, 14 Sep) — ROS 2 + PX4 SITL + Google 3D tiles. Overlaps already-listed `joey-david/fly-fpv` / new FlyDrones.
- [buhuia1/flywire-pong](https://github.com/buhuia1/flywire-pong) (0★, 15 Sep) — FlyWire Pong. [buhuia1.github.io/flywire-pong](https://buhuia1.github.io/flywire-pong/) (200). Distinct from already-listed FlyPong (MaleCNS subgraph).
- [BOHUYESHAN-APB/flygo](https://github.com/BOHUYESHAN-APB/flygo) (0★, 15 Sep) — Two MaleCNS brains play Gomoku. Distinct from already-listed `roymina/Fly_Gomoku`.
- [InvaderSquibs/LoFly](https://github.com/InvaderSquibs/LoFly) (1★, 15 Sep) — “Lord of Fly” console: shared MaleCNS pathways drive several Bug activities including courtship.
- [Nuu-maan/flappyfly](https://github.com/Nuu-maan/flappyfly) (1★, 13 Sep) / [naginagiyev/flappy-fly](https://github.com/naginagiyev/flappy-fly) (2★, 13 Sep) — more Flappy; evolutionary / small-circuit variants. Fold only if README wants a Flappy cluster note.
- [bugrax/flybrain-snake](https://github.com/bugrax/flybrain-snake) (0★, 14 Sep) — 3,189 neurons, zero policy training. Name-collides `charbelkassab/flybrain-snake`.
- [kristianbonnici/fruit-fly-brain-snake](https://github.com/kristianbonnici/fruit-fly-brain-snake) (0★, 15 Sep) — recorded Snake + 3D replay. [fruitfly-brain-snake.dynv6.net](https://fruitfly-brain-snake.dynv6.net/) (200).
- [artifyr/NeuroFly](https://github.com/artifyr/NeuroFly) (0★, 14 Sep) — FlyWire SNN embodied in Minecraft. Fifth Minecraft fly after NeuroCraft / blendi-remade / ruby-project / Yi-111-a/FlyCraft.
- [tiredbooy/Fruit-Fly](https://github.com/tiredbooy/Fruit-Fly) (1★, 13 Sep) — inspectable MaleCNS lab + Three.js/WebGPU observatory.
- [mertozbas/fruitfly-hashtag](https://github.com/mertozbas/fruitfly-hashtag) (3★, 13 Sep) — Hashtag Neural Lab: **7,075-neuron** orientation net, not whole-brain. `labs.hashtagworldcompany.com` redirected to [labs.hashtagrobotics.tr](https://labs.hashtagrobotics.tr/) (200).
- [alipyth/fly_brain_studio](https://github.com/alipyth/fly_brain_studio) (3★, 15 Sep) — Persian FlyWire/FAFB explorer + imitation-learning controller. Homepage is a Telegram channel, not a demo.
- [CornyBirdy/flybrainSDK](https://github.com/CornyBirdy/flybrainSDK) (1★, 14 Sep) — WIP SDK “add this to a prompt.” Unvalidated ports.
- [Pronexsteam/brainlab](https://github.com/Pronexsteam/brainlab) (1★, 15 Sep) — one-GPU whole-brain LIF (FlyWire / BANC / MaleCNS), Shiu-validated.
- [PouyanJay/drosophila-lab](https://github.com/PouyanJay/drosophila-lab) (1★, 15 Sep) — 3D MaleCNS atlas + NAS experiments. Tooling more than a game.
- [dhruvin-sarkar/ConnectomeLens](https://github.com/dhruvin-sarkar/ConnectomeLens) (0★, 14 Sep) — predict sexually dimorphic cell types from wiring vs degree-preserving nulls. [dhruvin-sarkar.github.io/ConnectomeLens](https://dhruvin-sarkar.github.io/ConnectomeLens/) (200). Science demo, not a toy.
- [KoichiHiraoka/fly-brain-lab](https://github.com/KoichiHiraoka/fly-brain-lab) (0★, 14 Sep) — FlyWire sensory/MB/reward with calibrated APL compartments (0.903 → 0.150 MAE on held-out conditions).
- [hwkim3330/micro-cat-fly](https://github.com/hwkim3330/micro-cat-fly) (0★, 15 Sep) — frozen FlyWire steering a robot command; readout-only; noncommercial sibling of `micro-cat`.
- [AcastaPaloma/neuroframe](https://github.com/AcastaPaloma/neuroframe) (0★, 15 Sep) — full FlyWire + Freedoom RGB-from-spikes + MuJoCo body.
- [whiteram/fly-man-bci](https://github.com/whiteram/fly-man-bci) (0★, 15 Sep) — MaleCNS inside a human sphere-head EEG forward model.
- [fruitflyworld/fruit-fly-world](https://github.com/fruitflyworld/fruit-fly-world) (0★, 15 Sep) — hourly forage map; humans vs agents. [fruitfly.world](https://fruitfly.world) (200). Connectome loop not re-audited beyond the README.
- [binivin/drosophila-connectome-odor-navigation](https://github.com/binivin/drosophila-connectome-odor-navigation) (0★, 14 Sep) — MaleCNS-derived recurrent odor-source navigation.
- [osesantos/flycraft](https://github.com/osesantos/flycraft) (0★, 18 kb, 14 Sep) — Rust “can a connectome fly a drone?” skeleton. Flag as early.
- [juancristobalgd1/flybrain-lab](https://github.com/juancristobalgd1/flybrain-lab) (0★, 14 Sep) — warehouse drone twin. Live [juancristobalgd1.github.io/flybrain-lab](https://juancristobalgd1.github.io/flybrain-lab/) (200). README: **512-neuron proxy**, not 166,700.
- [s192275/Fruit-Fly-RL-Okey-101](https://github.com/s192275/Fruit-Fly-RL-Okey-101) (1★, 14 Sep) — Okey 101 via a **neuropil-inspired MLP** (ACH→ELU, GABA→LeakyReLU…), not the published graph. Treat as biomimetic, not a connectome runtime.
- [bekhruzmd/dj-fruit-fly](https://github.com/bekhruzmd/dj-fruit-fly) (0★, 14 Sep) — two-deck house mixer; “connectome-inspired” small circuit. Overlaps already-listed DJ Drosophila / Fly Lab.
- [ayuuXploits/fruitfly-chess](https://github.com/ayuuXploits/fruitfly-chess) (0★, 14 Sep) — 3D chess vs “connectome GNN & Stockfish.” Inspect before promoting; Stockfish in the blurb is a tell.

## New: dopamine / trading / wirehead

Not already in `trading-dopamine-wirehead.md` or the README dopamine/trading sections.

- [Jimmy110101013/fly-megacode](https://github.com/Jimmy110101013/fly-megacode) — rank #3 (PAM / PPL1 on KC→MBON).
- [dogluk/fly-fruit-buffet](https://github.com/dogluk/fly-fruit-buffet) — rank #7 (compartment identity, not a P&L pulse).
- [bsgelman/fly-hero](https://github.com/bsgelman/fly-hero) — rank #9 (hits → dopamine; blocked DA control).
- [Palak11245/fly-guitar](https://github.com/Palak11245/fly-guitar) — rank #12 (measured depression rule, invented musical reward).
- [nyoki-mtl/fly-shogi](https://github.com/nyoki-mtl/fly-shogi) — optional dopamine-like KC→MBON arm.
- [bryceweiner/fly-trader](https://github.com/bryceweiner/fly-trader) (0★, created 14 Sep) — FlyWire **central brain** (41,756 / 1.04M) distilled to copy a gradient-boosted PumpSwap selector. Paper book default; live is deny-by-default. Site [fly-trader.app](https://fly-trader.app) (200). No PAM11/PPL101 named.
- [sevenup27/astrafly](https://github.com/sevenup27/astrafly) (8★, 35 kb, 14 Sep) — “10 GPT-6 ASTRA agents + a digital fruit-fly brain” paper-trading Robinhood Chain. **Not a published connectome runtime** (see thin table). Star count is not evidence of MaleCNS.
- [MidTermDev/immortal-fruit-fly](https://github.com/MidTermDev/immortal-fruit-fly) (2★, 15 Sep) — FlyWire circuit as BNB `$FLY`. [immortal-fruit-fly.vercel.app](https://immortal-fruit-fly.vercel.app) (200). Meme-economy; treat like flycoinrh.
- [KoichiHiraoka/fly-brain-lab](https://github.com/KoichiHiraoka/fly-brain-lab) — calibrated APL on a real reward circuit (science, not a trader).
- `gh search repos PAM11 created:>=2026-09-13` returned **0** connectome hits (the qualifier is polluted by Java “Pertemuan 11” homework). The PAM/PPL loops that matter this window (`fly-megacode`, fruit-buffet, fly-hero, fly-guitar, fly-shogi) came from MaleCNS / FlyWire / `166,700` descriptions, not the PAM11 name search.

## New: desktop, phones, hardware

README already has DesktopFly (macOS) and CyberFly (Spectacles). These shells were missing.

- [freaker2k7/desktop-fly](https://github.com/freaker2k7/desktop-fly) — Go/OpenGL subset pet (above).
- [AlexNoyanov/MaleCNS-Driving-Robot](https://github.com/AlexNoyanov/MaleCNS-Driving-Robot) — physical 2WD (above).
- [saruar-ryskaliyev/psp-fly](https://github.com/saruar-ryskaliyev/psp-fly) — PSP-2000 (above).
- [zhuhaozoo/FlyBrain-HarmonyOS](https://github.com/zhuhaozoo/FlyBrain-HarmonyOS) — HarmonyOS phone (above).
- [Kisame76/drosophila-brain-mlx](https://github.com/Kisame76/drosophila-brain-mlx) — Apple MLX (above).
- [Furina-star/mkdir-fly-companion](https://github.com/Furina-star/mkdir-fly-companion) (1★, **2 kb**, 15 Sep) — desktop companion claim; empty README / stub size. See thin table.
- [zgbrenner/flywatchos](https://github.com/zgbrenner/flywatchos) (0★, 15 Sep) — Garmin Forerunner 245 overlay. **64 synthetic neurons**, not MaleCNS/FlyWire. Hardware-cool, connectome-thin.
- [CircuitGhost/drosophila-connectome-esp32](https://github.com/CircuitGhost/drosophila-connectome-esp32) (0★, 18 kb, 14 Sep) — undescribed ESP32 dump.

## New: language, art, science-as-demo

- [tolga-ileri/FlyCoder](https://github.com/tolga-ileri/FlyCoder) / [pbomaster/Fruitfly-reviewer](https://github.com/pbomaster/Fruitfly-reviewer) / [yub4-arema/flymerge](https://github.com/yub4-arema/flymerge) / [lorcanorourkeai/flykeys](https://github.com/lorcanorourkeai/flykeys) — ranks / nearby above.
- [FLModel/flm](https://github.com/FLModel/flm) (68★, created 15 Sep, **pushed 11 Sep**) — **not new work.** Identical commit SHAs to already-listed [nftechie/flm](https://github.com/nftechie/flm) (74★ this pass). README still says `git clone https://github.com/nftechie/flm.git`. Mirror / import; do not promote as a second Fly Language Model.
- [dhruvin-sarkar/ConnectomeLens](https://github.com/dhruvin-sarkar/ConnectomeLens) / [Pronexsteam/brainlab](https://github.com/Pronexsteam/brainlab) / [annel0/flybrain](https://github.com/annel0/flybrain) — science benches (above).
- [iamnih4l/NeuroFLY](https://github.com/iamnih4l/NeuroFLY) (0★, 14 Sep) — MaleCNS + real-world media → modeled brain states (“what happens when a fly watches the world?”). Overlaps Fly/Wirehead / Scrollfly energy.
- [whiteram/fly-man-bci](https://github.com/whiteram/fly-man-bci) — EEG forward-model art (above).

Cobanov still lists older science/demo misses this repo never folded (`pusulamkendim/flywire-neuro`, `seven-monarchs/NeuroFly`, `lixiang1076/fly-brain`, `eonfathom/FastFly`, `ruvnet/Connectome-OS`, `seohyunjun/mps-malecns-model`, `dhakalnirajan/axonweave`, `eudald-seeslab/train-your-fly`). They are **not** Sep 14–15 drops (most last-pushed Feb–Jul 2026) and belong on a tooling pass / [awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome), not this shard’s “new” table.

## Already catalogued (not New)

Confirmed still live in search hits; **do not re-add**. Includes the Sep 6–14 canon plus shards:

DOOMFLY, Stonkfly, StonkFlyRH, stonkfly-lab, FLM (`nftechie/flm`), Fly/Wirehead, Scrollfly, FlyScroll, Infinite Sugar, Faiku, fly-mario, FlyTris (`rothilion26`), kick-the-fly, Aimbug, Swat, Fly Poker, fly-brain-poker, Flyhard, fly-brain-minesweeper, FlyPong, connectome-fighter, flyfear, fly-fpv, fly-craftax, fly-escape, DesktopFly, CyberFly/Spectacles, fly-hero (`actuallyrizzn`), flyboard, flydoom (`mutkuoz` / `eganeganegan` / `pratik90908`), NeuroCraft, Fly Brain Minecraft, ruby-project, fruit-fly-fashion, OpenFly, Richy, TraderFly, flycoinrh, flybrain-female, flywire-live, fruit-fly-fund, fruitfly.trade, Gregor, quantum-fly, fly-explorer, fly-brain-bench, fly-flappy-bird, flybrain-snake (`charbelkassab`), FlyBrain boss, FlyBrain-HalfLife, flyputer, FLYBRAIN-BAD_APPLE_X_DOOM, FLYWATT, DJ Drosophila, FLYcasso, flyverse, fly-self-driving, fly.ai, eonsystemspbc/fly-brain, PersonConnectome, flybrain-intransitive, swat-or-buy, Same Smell, Fruit Ninja, fruit-fly-utopia, pikabell tic-tac-toe, jerryjliu/fly_ocr, nicodunks/fruitless, KakaoXI billiards, VaheOfficial/FLY, chonchurik, etc.

`xenonbomin54/flyChess` (1★, created 13 Sep) was already named as in-progress in `games-media-art.md`; it is a real chess experiment now, but not a surprise URL.

## Thin meme forks / stubs

Flagged so later README editors do not promote them as brand-new brains.

| Repo | Why it looks thin |
|---|---|
| [FLModel/flm](https://github.com/FLModel/flm) | 68★ mirror of `nftechie/flm` (same SHAs `d60610ff6a` / `7251a8921d`). Created after upstream; clone instructions still point at nftechie. |
| [sevenup27/astrafly](https://github.com/sevenup27/astrafly) | 8★ / 35 kb. GPT-agent desk with a “Fly Brain” coordinator; not MaleCNS/FlyWire LIF. |
| [Furina-star/mkdir-fly-companion](https://github.com/Furina-star/mkdir-fly-companion) | 2 kb, empty README, companion claim. |
| [zgbrenner/flywatchos](https://github.com/zgbrenner/flywatchos) | Garmin overlay; **64 synthetic** neurons. |
| [s192275/Fruit-Fly-RL-Okey-101](https://github.com/s192275/Fruit-Fly-RL-Okey-101) | Neuropil-named MLP activations, not the connectome graph. |
| [juancristobalgd1/flybrain-lab](https://github.com/juancristobalgd1/flybrain-lab) | Live warehouse toy; author says 512-neuron **proxy**. |
| [osesantos/flycraft](https://github.com/osesantos/flycraft) | 18 kb drone-brain sketch. |
| Empty / 0-size namesakes created 14–16 Sep | `davidko0616/Fruit_Fly_CS2`, `DeveloperKubilay/fruit-fly-plays-mc`, `Willa-media/fruit-fly-brain-3d`, `hesong0222-dev/FruitFlyRobot`, `lajoiete11-cyber/Fly-brain`, `JonusNattapong/FlyBrain`, `singleolives/FlyBrainBot`, `mingdianliu/flybrain-playground`, `pedro-anthony/fruit-fly-experiments`, `lordlol13/fruitfly-drosophila-` (“making a fruit fly's brain suffer”). |
| [omar21136-creator/synapsespeak-connectome](https://github.com/omar21136-creator/synapsespeak-connectome) | 3 kb “Bio-LLM translation engine.” |
| [ArtyomITA/flytollm](https://github.com/ArtyomITA/flytollm) | 16 kb “uncut 166,700 as the spi…” stub. |
| Stonkfly copies (size ~1388 kb, upstream description) | `Baroni7777/stonkfly`, `marekbujko/stonkfly`, `yaniscrimsonzhang-gif/stonkfly`, `linkpark0929/stonkfly`, `yev9en/stonkfly`, `PtPPPPP/stonkfly`, `lawjar/stonkfly`, `zxcv1234aa/stonkfly`, `bitcoinagree/stonkfly`, `lupin4/stonkfly`, `wecoinweb3/stonkfly`, `thegreatesthoneybee/stonkfly`, `trezero/stonkfly`, plus the 13 Sep wave (`flipyou`, `FSOPP`, `instigator24`, `webclinic017`, …). Same cluster as the 14 Sep shard’s torronen/jonleach/fr303388 list. |
| [chmiela11-cyber/stonkfly-fork](https://github.com/chmiela11-cyber/stonkfly-fork) / [DrivenIdeaLab/stonkfly](https://github.com/DrivenIdeaLab/stonkfly) | Forks with extra files; still Stonkfly reskins, not new loops. |
| [sagistiki/stonkfly-3d](https://github.com/sagistiki/stonkfly-3d) | 6.5 MB **3D spectator** of Stonkfly BUY/HOLD/SELL. Derivative viewer, not a new trader. |
| Doomfly copies (size ~16451 kb) | `marekbujko/doomfly`, `dan668673-web/doomfly`, `yeager620/doomfly`, `vitorgamer58/doomfly`, `yuejunzhang/doomfly`, `ccc-ai0/doomfly`, `hzdlive/doomfly`, `goldenbbang/doomfly`, `isztldav/doomfly`, … plus 13 Sep `Onikore/doomfly`. [PolloXDDD/LLMfly](https://github.com/PolloXDDD/LLMfly) is a **renamed doomfly fork** (1★). |
| FLM copies (size 119 kb) | `marilynrichardson/flm`, `mMohammed52/flm`, `Mehta590/flm`, `jmorel9650/flm`, `yenkruger/flm`, `pedrobennett62/flm`, `StefanFlores09175/flm`, `eUnal607/flm`, `MiguelGupta57/flm`, `talhamartinez56115/flm`, `ngoc60393/flm`, `gomes6903/flm`, `tyler59532/flm`, `MODLICENSE/flm`, `hzdlive/flm`, `zhanshuo-art/flm`, `alrapine/flm`. Same-day star-farm / classroom clones. |
| [msh-bbk/flm-industrie40](https://github.com/msh-bbk/flm-industrie40) / [satishkokkirala/FLM_one](https://github.com/satishkokkirala/FLM_one) / [tejaswibaggam/FLM-system-design](https://github.com/tejaswibaggam/FLM-system-design) | FLM-named class/system-design dumps, not MaleCNS chat. |
| [Justsomebuddy/chonchurik](https://github.com/Justsomebuddy/chonchurik) | Fork of already-listed Johnny Silverfly. |
| [MidTermDev/immortal-fruit-fly](https://github.com/MidTermDev/immortal-fruit-fly) | Token wrapper on a FlyWire circuit; keep in trading-adjacent, not science. |
| Same-day Flappy cluster | `ns2250225/fly-flappy` (has a live Worker + pinme host), `Nuu-maan/flappyfly`, `naginagiyev/flappy-fly`, plus already-listed jackspiece / ykakade / arjunkshah / Thespaceblade stub. |
| Four Doom flies remain distinct | `nftechie/doomfly`, `mutkuoz/flydoom`, `eganeganegan/flydoom`, `pratik90908/fly-doom`, **plus new** `Aur1ety/DOOM-x-Fly` and `webergithub/fruitfly-lab` (pursuit subgraph on *defend_the_center*). Do not merge them. |

## Search notes

- `gh search repos MaleCNS --created >=2026-09-13` → **83** hits. `malecns` same window → **83**. `FlyWire --created >=2026-09-13` → **63**. `"166,700" --created >=2026-09-13` → **15**. `flybrain --created >=2026-09-13` → **53**. `fruit fly connectome --created >=2026-09-13` → **36**. `stonkfly --include-forks --created >=2026-09-13` → **54**. `doomfly` same → **22**. `flm --include-forks --created >=2026-09-13` → **49** (almost all classroom clones). `PAM11 --created >=2026-09-13` → **0**. Quoted `166700` (no comma) → **0**.
- Also: `MaleCNS --sort updated --updated >=2026-09-13` (100, API cap), `FlyWire` same, `drosophila connectome`, `fruit-fly`, `PPL101` (0), `fly-wirehead` (2), `Male CNS`. Forks API: `nftechie/stonkfly` **100** (page cap), `doomfly` **46**, `flm` **12**.
- `gh search --sort created` is still unsupported; recency used `--created` / `--updated` plus `--sort updated`.
- Ingested **558** unique repo records this pass; **307** unknown-to-this-repo after a relevance filter. Ranked / New above are the ones with a fetched README (or an honest empty-tree flag), not the raw dump.
- Live HTTP GET on 16 Sep 2026: fly.steph4n.dev, opcstudio.cc/fly-aim, jimmy megacode Pages, itch.io/open-fly, pinme flappy, fly-xiangqi, FlyDrones Pages, fly.siddhvasudev.com, flytris.net, cyberfly-explorer Pages, immortal-fruit-fly, fruitfly.world, flywire-pong Pages, ConnectomeLens Pages, bsgelman fly-hero Pages, fly-trader.app, juancristobal flybrain-lab Pages — **200**. `open-fly.pages.dev` **NXDOMAIN** from this agent (use itch).
- X/Twitter was not used. Hugging Face Spaces were not re-crawled.
- Star outliers that are **not** cooler new demos: `nftechie/stonkfly` 690★ / `doomfly` 297★ / `flm` 74★ (canon); `FLModel/flm` 68★ (mirror); `sevenup27/astrafly` 8★ (agent desk); `ns2250225/fly-flappy` 9★ (real, but Flappy).

*End of shard. Fold only the strongest verified items into README; do not dump this file wholesale. Suggested high-bar fold-ins if the list thaws: Fly Space Program, Fly Marksman, Fly Megacode, Open Fly, DOOM-x-Fly (with the random-wiring caveat), FlyCoder, fruit buffet, FlyDrones (MiniFly honesty), bsgelman Fly Hero (disambiguate the name).*
