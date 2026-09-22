# GitHub-latest cool (18–22 Sep 2026)

Research date: **2026-09-22** (UTC). Scope: brand-new or heavily updated MaleCNS / FlyWire / fruit-fly-connectome **demo** repos since ~**2026-09-17**, plus high-priority misses that the 15–17 Sep shards never cited. Ranked by novelty versus the existing [README](../README.md) plus [`discoveries/*.md`](.).

Stars are GitHub API `stargazers_count` from this pass. Missing stars are omitted, not guessed. No invented URLs. Live demos were HTTP-checked (200) unless marked otherwise.

**Compared against:** `README.md` after folding the unmerged 17 Sep X/GitHub shards onto main (this branch), `discoveries/github-latest-cool-2026-09-17.md`, `discoveries/x-latest-cool-2026-09-17.md`, and earlier shards. **New** means the repo URL is not already cited there. Cobanov [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) (**575★** this pass) last *content* commits are **19–20 Sep** (blackjack, boltzmann-fly, fly-swing, Fly-NAF, fly-flappy). It still has not absorbed most 18–22 Sep drops below.

These remain wiring-diagram simulations. A live page, a PAM pulse, or a trained readout is an interface, not proof a fly learned Dark Souls, Pokémon, piano, or health-record scoring.

## Ranked: coolest new

Genuine misses that are cooler or a different loop than what the README / 17 Sep shards already canonize. Rank is taste + substance (unique I/O, honesty, live page, or a control table), not star count. `SpikeCalls/FlyDrones` is the star outlier of this window (**216★**, was 0★ on 16 Sep) but is **already on the README** — not #1, not New.

| # | Project | Stars | Dopamine/RL? | Live demo | One-liner |
|---|---|---:|---|---|---|
| 1 | [heyobi/flysoul](https://github.com/heyobi/flysoul) | 0 | **yes** — damage → PPL101 LTD; boss hit → PAM LTP | [heyobi.github.io/flysoul](https://heyobi.github.io/flysoul/) (200) | MaleCNS LIF vs Iudex Gundyr in SoulsGym. Biological loop wins **once in ~600** fights and does not learn to; a synthetic readout on the same senses wins ~1/3. Created 19 Sep. |
| 2 | [lavallee/mk-jev-fly-brain](https://github.com/lavallee/mk-jev-fly-brain) | 2 | **yes** — dopamine-like rule *during* the fight, not a pretrained policy | [lavallee.github.io/mk-jev-fly-brain](https://lavallee.github.io/mk-jev-fly-brain/) (200) | 12,000-neuron MaleCNS subgraph (LPLC2/LC4/LC10a/P1 → DNp09/MDN/TTMn) fights TypeSafe’s Jev LM in mk.js. Controls say what each side contributes. Created 18 Sep. |
| 3 | [Reldnahc/pokefly](https://github.com/Reldnahc/pokefly) | 0 | **yes** — internal synaptic plasticity kept across whole-game attempts | local `127.0.0.1:8777` | Pixel-driven Pokémon Red (PyBoy) on MaleCNS via fly.ai; fixed seven-button decoder; live neural dashboard. Learning to *reach* battles is part of the task. Created 18 Sep. Distinct from `blackicon-eth/fly-plays-games` (frozen weights). |
| 4 | [Noir-infini/pianist-fly](https://github.com/Noir-infini/pianist-fly) | 3 | no (frozen LIF; sugar plume → T1 leg IK) | in-repo mp4s; local MuJoCo | Full 166,700 / 25.58M LIF hunts a sugar plume over a piano and strikes keys with Damped Least Squares IK. Highest-star *new* demo this window. Created 20 Sep. |
| 5 | [WilliamJones/fly-blackjack](https://github.com/WilliamJones/fly-blackjack) | 1 | **yes** — PAM + PPL1 (332 DANs) onto measured KC→MBON | [fly-blackjack.vercel.app](https://fly-blackjack.vercel.app/) (200) | “The Fly’s Table”: 682 PN / 1,200 KC / 97 MBON heads-up blackjack. 30k solo hands −45% → −16% winrate, 52% basic-strategy agreement; dopamine-cut wipes the gain. Created **14 Sep**; cobanov folded 19 Sep; this list missed it. |
| 6 | [ArtyMend07/Fly-NAF](https://github.com/ArtyMend07/Fly-NAF) | 1 | no (frozen FlyWire v783; DNp01 doors, DNp09 tablet) | local Windows; [YouTube recording](https://www.youtube.com/watch?v=4UNPlA-YJtw) | Whole 138,639 LIF plays FNAF 1. Best run 4 AM night 2. Camera-up blinds the fly via GABAergic inhibitors. Created 1 Sep; cobanov #11 on 20 Sep. |
| 7 | [Shriya-sai/FlyBreak](https://github.com/Shriya-sai/FlyBreak) | 1 | no | [flybreak-neural-heist.shriyasai8.chatgpt.site](https://flybreak-neural-heist.shriyasai8.chatgpt.site) (200) | 30-second neural heist: cut/jam MaleCNS nodes so LC4 cannot reach DNg108 while sparing protected DNa13. The fly reroutes every 4 s. Created 21 Sep. |
| 8 | [JHC56/fly-swing](https://github.com/JHC56/fly-swing) | 0 | no (GF reflex + kNN threat memory; wiring frozen) | local MuJoCo | Spider-Man webs through a random obstacle course. **No dodge code** — LC4/LPLC2 → DNp01 Giant Fiber; whole 165,122 graph is live display. 20/20 courses in the published run. Created 15 Sep; cobanov #9 on 19 Sep. |
| 9 | [Ameerkhanjk/haltere-pilot](https://github.com/Ameerkhanjk/haltere-pilot) | 0 | trained gains on frozen graph (teacher 93%) | local `127.0.0.1:8765` | Quadrotor whose gyro enters **haltere afferents** and whose motors are real wing MNs. Silencing 204 haltere cells crashes every second; 204 random cells do almost nothing. Created 21 Sep. |
| 10 | [SakshayMahna/fly-cord-robots](https://github.com/SakshayMahna/fly-cord-robots) | 0 | no (VNC CPG, not PAM) | local robots | MANC / MaleCNS **nerve cord** walks a hexapod, then an “amputated” quadruped. Spinal-cord I/O nobody else shipped. Created 18 Sep; still pushing 22 Sep. |
| 11 | [Cem-Bas/flyguy](https://github.com/Cem-Bas/flyguy) | 0 | gentle hue/app affinities (not PAM11) | macOS local | Desktop Tamagotchi: ScreenCaptureKit vision through **165,122 / 10.5M** MaleCNS plus a live soma cloud. Distinct from DesktopFly (subset + Electron). Created 18 Sep. |
| 12 | [georgesher/fly24-public](https://github.com/georgesher/fly24-public) | 1 | no (KC “interest” / GF “fear” are authored labels) | local `127.0.0.1:8001` | 166,700 LIF (Stonkfly C++ kernel) watches live Russian IPTV and changes channels. Pixels only; boredom is Kenyon-cell telemetry. Created **22 Sep**. |
| 13 | [Synthetic-Humanities-Lab/drosophila-critic](https://github.com/Synthetic-Humanities-Lab/drosophila-critic) | 0 | no (frozen graph; reading is text-blind) | [synthetic-humanities-lab.github.io/drosophila-critic](https://synthetic-humanities-lab.github.io/drosophila-critic/) (200) | Spoken Blake *The Fly* → JO-A/B → full frozen MaleCNS → recorded spikes → a critic that never sees the poem. Created 20 Sep. |
| 14 | [hama-jp/fly-garden](https://github.com/hama-jp/fly-garden) | 0 | **yes** — Double DQN *controller*; connectome weights frozen | local `127.0.0.1:18741`; [YouTube](https://www.youtube.com/watch?v=3BSv3TqA-yY) | 166,700 / 25.6M LIF sees a Three.js garden (192×96); learned layer picks 7 locomotor actions. Created 16 Sep; 17 Sep shards missed it. |
| 15 | [Teafox113/FlyCNS-Desktop-Pet](https://github.com/Teafox113/FlyCNS-Desktop-Pet) | 0 | optional neuromod / sugar reward telemetry | Windows local | 2D always-on-top pet; 3,335 R1–R6 plus a “pure BCI” control. Engineering cruise vs neural readout is documented. Created 18 Sep. |

## Box X follow-up (same day, later)

Verified 22 Sep 2026 after a login-walled X scan named six GitHub URLs plus three `@fruitflydev` status IDs. Stars from GitHub API this pass. Live hosts HTTP **200**. Tweet IDs confirmed via unrollnow (200); first-party `x.com` still 404 here.

| Project | Stars | Fold? | One-liner |
|---|---:|---|---|
| [Eli-HarShefer/fly-brain-falafel](https://github.com/Eli-HarShefer/fly-brain-falafel) | 0 | **README** (games) | FlyWire subgraph **4,798 / 116,960** LIF in-browser Falafel King. LC10a→AOTU→DNa02 trays; LPLC2→DNp01 slaps. Order-reading is authored. Created 21 Sep; still pushing 22 Sep. [Pages](https://eli-harshefer.github.io/fly-brain-falafel/) (200). |
| [fruitflydev/therealfly](https://github.com/fruitflydev/therealfly) | 6 | **README** (embodied) | Full MaleCNS LIF (165,122 / 10.2M) → flybody with **no written controller**. Preregistered DNa01+DNa02 cord rhythm **FAIL** (anti-phase 0/3; scramble makes the same 11 Hz peak). Created 12 Sep / last push 13 Sep; 6★ by 18 Sep. Offline; no wallet. |
| [gyujeongion/flyconnectome-nulls](https://github.com/gyujeongion/flyconnectome-nulls) | 0 | **README** (embodied) | Compressed FlyWire v783 evolution vs nulls. Standard shuffles invent olfactory→motor shortcuts; boundary-preserving nulls wipe the gap. Pre-registered; one registered prediction **failed** and is reported. Created 21 Sep. [Zenodo](https://doi.org/10.5281/zenodo.22871090) (200). |
| [brandoncho369/flybench](https://github.com/brandoncho369/flybench) | 2 | **README** (tools) | 36 pre-registered reflex tasks, FlyWire + MaleCNS, shuffled controls. Was in `github-latest-cool.md` (1★) as a fly-explorer companion; never on README. Heavily updated 22 Sep. [fly-bench.com/bench](https://www.fly-bench.com/bench) (200). |
| [flybrain.online/dartboard](https://flybrain.online/dartboard) | — | **README** (trading) | Paper stock room on the same 165,122 MaleCNS. **No GitHub repo** (clip-only tweet). Live page: no edge vs Random; sugar/shock MB lessons. HTTP 200. |
| [fruitflydev/flycoinrh](https://github.com/fruitflydev/flycoinrh) | 190 | already README | Confirmed still listed. Tweets folded into the existing row + Articles. |
| [HaroldHormaechea/drone-fly](https://github.com/HaroldHormaechea/drone-fly) | 0 | **shard only** | Real MaleCNS **slice** + PPO racing drone. README: **not** a biophysical LIF — weights are learned. Overlaps already-listed [fly-fpv](https://github.com/joey-david/fly-fpv). Created 16 Sep; still pushing 22 Sep. Already nearby in the 17 Sep GitHub shard. |
| [seeton/fly](https://github.com/seeton/fly) | 0 | **shard only** | MaleCNS / hemibrain / FlyWire desktop lab (navis + flygym). Escape takeoff is **hand-translated** DNp01→TTMn; flight is a CMA-ES `flight_policy.json`, not a LIF graph. Brain lighting is sensory-input mapping. Created 19 Sep. Tooling/viewer, not a wiring-diagram sim. |

**fruitflydev tweets (unrollnow 200; do not invent others):**

- https://x.com/fruitflydev/status/2100964182028099993 (18 Sep) — Flyonardo NFT airdrop / $FLYBRAIN burn. Repo already in 17 Sep shard: `fruitflydev/flyonardo-da-vinci`.
- https://x.com/fruitflydev/status/2101298482002927874 (19 Sep) — “gave the fly $10,000 to trade stocks” (five-card room). Tweet claims outperform random/hold; the live Dartboard page is more conservative.
- https://x.com/fruitflydev/status/2102092842537734496 — clip-only; no GitHub in the post. Points at `flybrain.online/dartboard`.

**Nearby, same coolness band (not ranked separately):**

- [jonathancomergit-ai/fly-terrarium](https://github.com/jonathancomergit-ai/fly-terrarium) (0★, 16 Sep) — 165,122 GPU LIF in a tank (sugar/bitter/fan/song/swat) plus a flyvis webcam optic-lobe page. Local `8793`. Folded this pass (must-include). Overlaps Infinite Sugar / flyverse energy.
- [YYK2007/flybrain](https://github.com/YYK2007/flybrain) (0★, 18 Sep) — 166,700 rate model + trained flap decoder on a 3D course. Shuffle control also completes; README does not claim topology is the skill. Folded this pass (must-include). Distinct from `alextitonis/fly.ai`.
- [jniimi/boltzmann-fly](https://github.com/jniimi/boltzmann-fly) (0★, 16 Sep) — Purchase-World DBM whose couplings are **masked to right-hemisphere PN→KC→MBON**. Visit AUC 0.712 vs dense 0.711; clamp test **flips sign** vs degree-preserving control. Cobanov listed 19 Sep.
- [suifei/flywire-fly-lab](https://github.com/suifei/flywire-fly-lab) (13★, 15 Sep) — already #4 in the 17 Sep GitHub shard; **folded this pass**. [game.html](https://suifei.github.io/flywire-fly-lab/game.html) (200). 17,628 virtual knockouts.
- [bennjordan/fruitflysynth](https://github.com/bennjordan/fruitflysynth) (15★, 16 Sep) — already #1 in the 17 Sep GitHub shard; **folded this pass**. [Pages](https://bennjordan.github.io/fruitflysynth/) (200).
- [fkfkfk0406/fly-chan](https://github.com/fkfkfk0406/fly-chan) (0★) / [Franz23/brainrot](https://github.com/Franz23/brainrot) (0★) — already #2/#3 on 17 Sep; **folded this pass**. Both live **200**.
- [blackicon-eth/fly-plays-games](https://github.com/blackicon-eth/fly-plays-games) (0★, 19 Sep) — frozen-weight Pokémon Red sibling of pokefly. Honest “not a player” README.
- [GeorgeCanon/FlyBrain-Worldle](https://github.com/GeorgeCanon/FlyBrain-Worldle) (0★, 18 Sep) — frozen flyvis eyes + MaleCNS central-complex RNN, REINFORCE on country silhouettes.
- [lo2003058/flymj](https://github.com/lo2003058/flymj) (0★, 19 Sep) — MB topology as a mahjong hidden layer, vs random wiring, Streamlit play.
- [Ro0tk1t/fly-fight](https://github.com/Ro0tk1t/fly-fight) (1★, 21 Sep) — 94-cell / 621-synapse subgraph fighting game. Live [qoder.zone](https://fly-fight-i5p1cjup8mn.qoder.zone) (200). MiniFly, not 166k.
- [jamesbiederbeck/flappy-haltere](https://github.com/jamesbiederbeck/flappy-haltere) (0★, 19 Sep) — another Flappy plus a **haltere inverse-dynamics** oracle thread.
- [jamesbiederbeck/flybody-connectome](https://github.com/jamesbiederbeck/flybody-connectome) (0★, 19 Sep) — closed MuJoCo loop, **explicitly no visual information yet** (empty arena).
- [immanuel-lam/flyscope](https://github.com/immanuel-lam/flyscope) (0★, 19 Sep) — anatomy + NeuroMechFly walk + 512-cell “flygpt”. [flyscope.vercel.app](https://flyscope.vercel.app) (200).
- [almera-vs/malecns-pong-lab](https://github.com/almera-vs/malecns-pong-lab) (0★, 19 Sep) — inspectable Pong plant. Advertised [pages.dev](https://malecns-pong-lab.pages.dev/) (200).
- [merolaagi/malecns-lab](https://github.com/merolaagi/malecns-lab) (1★, 21 Sep) — 807 identified cells / 21k directed edges; “assumed dynamics,” not whole-CNS.
- [Seed123-psy/male-cns-neural-field](https://github.com/Seed123-psy/male-cns-neural-field) (0★, 20 Sep) — CPU 166,700 forage + online Double DQN readout.
- [crystalleeo/MaleCNS_Experiment_Platform-demo](https://github.com/crystalleeo/MaleCNS_Experiment_Platform-demo) (1★, 20 Sep) — Three.js viewer plumbing; producer is a **non-scientific demo stream**.
- [8S8642/FlyFace](https://github.com/8S8642/FlyFace) (0★, 21 Sep) — face images → MaleCNS/Stonkfly pipeline; DNa02 readout marked unvalidated; no attractiveness ranking.
- [karacurt/polyfly-ui](https://github.com/karacurt/polyfly-ui) (0★, 19 Sep) — Next.js spectator for already-listed Polyfly. [polyfly-ui.vercel.app](https://polyfly-ui.vercel.app) (200). Paper fly vs Polygon DEX wallet; no keys in-repo.
- [xtensionlabs/anima-zero](https://github.com/xtensionlabs/anima-zero) (0★, 19 Sep) — FLM-adjacent LM + MaleCNS thesis lab.
- [tsungyumr/malecns_LoL](https://github.com/tsungyumr/malecns_LoL) (0★, 21 Sep) — MuMu screen → cached MaleCNS V2 → Garen keys. Default is **dry-run**; private/custom only.
- [evil-robot/supertruth-connectome-public](https://github.com/evil-robot/supertruth-connectome-public) (0★, 20 Sep) — frozen 166,700 / 6.24M (≥5 synapses) trained to copy a health-record trust index vs LLM baselines. Pre-registered. [supertruth.ai/research/connectome](https://supertruth.ai/research/connectome) (200). Treat as a scored reservoir, not a clinician.
- [kkokosa/dotFly](https://github.com/kkokosa/dotFly) (0★, 21 Sep) — native .NET 11 LIF engine (MaleCNS + FlyWire), Brian2-checked, Godot loop. [docs](https://kkokosa.github.io/dotFly/) (200). Tooling.
- [sksat/kobae](https://github.com/sksat/kobae) (0★, 21 Sep) — whole 166,700 on Vulkan/wgpu (AMD BC-250), bit-identical fixed-point. Tooling + viewer.
- [QuixiAI/connectome-kernels](https://github.com/QuixiAI/connectome-kernels) (1★, 14 Sep) — fused CUDA sparse recurrence for FlyGPT. Not a demo.
- [Zidanski/matrix-das-moscas](https://github.com/Zidanski/matrix-das-moscas) (0★, 21 Sep) — 3♂ MaleCNS + 3♀ FlyWire in a fake 3D world; world code never moves a fly.
- [PestvsPest/PestvsPest](https://github.com/PestvsPest/PestvsPest) (0★, 21 Sep) — MaleCNS vs experimental *C. elegans* paper-trading the same book.
- [huilo1/FlyRun](https://github.com/huilo1/FlyRun) (0★, 19 Sep) — Xenova MaleCNS graph in a random room. [flyrun.runningdog.org](https://flyrun.runningdog.org) (200).
- [gianlucamazza/flymsg](https://github.com/gianlucamazza/flymsg) (0★, 21 Sep) — whole-CNS 3D Shiu viewer, created today-ish.
- [maximusmaximus/flyphilospher](https://github.com/maximusmaximus/flyphilospher) (0★, 21 Sep) — subgraph on a pedestal + mirror; tiny README.
- [rev4n7/fly-world](https://github.com/rev4n7/fly-world) / [rev4n7/fly-pacman](https://github.com/rev4n7/fly-pacman) (0★, 18 Sep) — Pac-Man + sandbox + 3D flight cluster.
- [bedchem/fruit-fly-slot-machine](https://github.com/bedchem/fruit-fly-slot-machine) (0★, 18 Sep) — [fly.pokyh.com](https://fly.pokyh.com/) (200).
- [shantanugoel/fly-games](https://github.com/shantanugoel/fly-games) (0★, 19 Sep) — frozen MaleCNS → Mario / Kung Fu / Doom via typed VPNs. Another multi-game harness.
- [mingdianliu/flybrain-drive](https://github.com/mingdianliu/flybrain-drive) (1★, 18 Sep) — 3D driving + live brain. Overlaps fly-self-driving.
- [zhongpei/fly-pet](https://github.com/zhongpei/fly-pet) (0★, 20 Sep) — another 166k desktop pet.
- [Vaseto108/fly_rotten](https://github.com/Vaseto108/fly_rotten) (0★, 18 Sep) — notebook: frozen MaleCNS features vs ResNet-18 on fresh/rotten fruit.
- [AdilSiddiquiHQ/fly-connectome-chess](https://github.com/AdilSiddiquiHQ/fly-connectome-chess) (3★, 18 Sep) — “164k” + dopamine RL chess. Marketing-heavy; inspect before promoting over already-listed honest-negative chess labs.
- [Umair-JM/fly-eeg](https://github.com/Umair-JM/fly-eeg) (0★, 22 Sep) — MaleCNS as EEG-denoise reservoir. **No README** this pass.
- [HaroldHormaechea/drone-fly](https://github.com/HaroldHormaechea/drone-fly) (0★, 16 Sep / push 22 Sep) — see Box X follow-up. Not biophysical LIF; overlaps fly-fpv.
- [seeton/fly](https://github.com/seeton/fly) (0★, 19 Sep) — see Box X follow-up. Viewer + flygym; takeoff is hand-mapped.

## New: dopamine / trading / wirehead

Not already in `trading-dopamine-wirehead.md` or the README dopamine/trading sections.

- [heyobi/flysoul](https://github.com/heyobi/flysoul) — rank #1 (named PAM / PPL101 on a Souls boss).
- [Reldnahc/pokefly](https://github.com/Reldnahc/pokefly) — rank #3 (internal synapses persist across whole-game attempts).
- [lavallee/mk-jev-fly-brain](https://github.com/lavallee/mk-jev-fly-brain) — rank #2 (in-fight dopamine-like rule).
- [WilliamJones/fly-blackjack](https://github.com/WilliamJones/fly-blackjack) — rank #5 (measured MB + dopamine-cut table).
- [hama-jp/fly-garden](https://github.com/hama-jp/fly-garden) — rank #14 (DQN layer, frozen graph).
- [karacurt/polyfly-ui](https://github.com/karacurt/polyfly-ui) — UI only for already-listed Polyfly.
- [PestvsPest/PestvsPest](https://github.com/PestvsPest/PestvsPest) — fly vs worm paper book.
- [Jammore1203/flybrain-trader](https://github.com/Jammore1203/flybrain-trader) (0★, **22 Sep**, 190 kb) — FlyWire GPU + “evolved and taught to trade BTC with dopamine.” Too fresh/thin to promote.
- [flybrain.online/dartboard](https://flybrain.online/dartboard) — paper stock room (Box X follow-up). No GitHub. Live 200.

`PAM11 created:>=2026-09-17` is still polluted; named PAM/PPL loops this window came from README text, not the qualifier search.

## New: desktop, phones, hardware

- [Cem-Bas/flyguy](https://github.com/Cem-Bas/flyguy) / [Teafox113/FlyCNS-Desktop-Pet](https://github.com/Teafox113/FlyCNS-Desktop-Pet) / [zhongpei/fly-pet](https://github.com/zhongpei/fly-pet) — desktop pets (above).
- [SakshayMahna/fly-cord-robots](https://github.com/SakshayMahna/fly-cord-robots) — physical/sim robots from VNC (above).
- [Ameerkhanjk/haltere-pilot](https://github.com/Ameerkhanjk/haltere-pilot) — quadrotor (above).
- [sksat/kobae](https://github.com/sksat/kobae) — AMD BC-250 Vulkan (above).
- [kkokosa/dotFly](https://github.com/kkokosa/dotFly) — .NET / Godot (above).

## New: language, art, science-as-demo

- [georgesher/fly24-public](https://github.com/georgesher/fly24-public) / [Synthetic-Humanities-Lab/drosophila-critic](https://github.com/Synthetic-Humanities-Lab/drosophila-critic) / [Noir-infini/pianist-fly](https://github.com/Noir-infini/pianist-fly) — ranks above.
- [jniimi/boltzmann-fly](https://github.com/jniimi/boltzmann-fly) / [evil-robot/supertruth-connectome-public](https://github.com/evil-robot/supertruth-connectome-public) / [QuixiAI/connectome-kernels](https://github.com/QuixiAI/connectome-kernels) — science / kernels (above).
- nftechie public fly repos this pass are still **doomfly / stonkfly / flm** (385★ / 802★ / 90★). No new nftechie demo.

## Already catalogued (not New)

Do not re-add. Includes the Sep 6–17 canon plus shards:

DOOMFLY, Stonkfly, StonkFlyRH, stonkfly-lab, FLM (`nftechie/flm`), Fly/Wirehead, Scrollfly, FlyScroll, Infinite Sugar, Faiku, fly-mario, FlyTris, kick-the-fly, Aimbug, Swat, Fly Poker, fly-brain-poker, Flyhard, FlyDrones (**216★**, already in README), Fly Marksman, Fly Space Program, Fly OCR, Fruitless, NANDFLY, Beat the Fly, 9 to Fly, Fly School, Boxhead (`FalinX/fly-brain`), MaleCNS Asteroids, Hand-loom GF (`Euraxluo`), fly-afterlife, Music in the Body, The Fly Hears, Fly-chan / Brain Rot / fruitflysynth / flywire-fly-lab / iigs-fly / fly-balatro / flyworker (17 Sep GitHub shard), NeuroCraft, Fly Brain Minecraft, ruby-project, Xenova canvas, etc.

## Thin meme forks / stubs / metaphor-only skips

| Repo | Why it looks thin |
|---|---|
| [DWJStraat/FlyWall](https://github.com/DWJStraat/FlyWall) | **142-byte** README: cyber-defense claim, no code. |
| [nikolasandwich/fly-sudoku-expert](https://github.com/nikolasandwich/fly-sudoku-expert) | Classical Sudoku solver + an **~800-synapse toy reservoir**. “MaleCNS-inspired,” not the published graph. |
| [h100envy/nerve](https://github.com/h100envy/nerve) | Memecoin trading protocol (“seven typed agents”). **No connectome runtime.** |
| [paonxeth/flyswatter-detector](https://github.com/paonxeth/flyswatter-detector) | Webcam motion/shape heuristics. Mentions 166,700 in a tagline; detector is CV, not LIF. |
| [wwtlitee/fly-chaser](https://github.com/wwtlitee/fly-chaser) | PySide6 desktop fly-swat game. No connectome. |
| [Frankweb33/flybrain-robot-bridge](https://github.com/Frankweb33/flybrain-robot-bridge) | **Mock backend**: eight hand-designed groups. README: MaleCNS is a planned integration only. |
| [Umair-JM/fly-eeg](https://github.com/Umair-JM/fly-eeg) | Description-only; no README this pass. |
| [Jammore1203/flybrain-trader](https://github.com/Jammore1203/flybrain-trader) | 190 kb, created today. |
| Empty / invoice / `flm*` squat cluster 18–22 Sep | `Drui-Hardmanx/flmnahk`, `nikshamompandio/flmqw`, `Payment-flm4helu`, classroom `flm_docker_*`, … |
| Stonkfly / doomfly copies this window | `ysazhao439-wq/stonkfly`, `coderwpf/stonkfly`, `krazykitty2503/stonkfly`, `runingdog2025/stonkfly`, `kuishou68/stonkfly`, `ssun3/stonkfly`, `smclw/stonkfly`, `ringoapple816/doomfly`, `Ace1928/doomfly`, `sass3r/doomfly`, … Same upstream descriptions. |
| [shreyash-sharma/doomFly](https://github.com/shreyash-sharma/doomFly) | Namesake Doom fly created 18 Sep; treat as fork-adjacent until audited. |
| [Injae-Yun/fly-poker](https://github.com/Injae-Yun/fly-poker) / [aroo-stack/connectome-chess](https://github.com/aroo-stack/connectome-chess) / [thebakedbeangunslingerdev/freeman-flybrain](https://github.com/thebakedbeangunslingerdev/freeman-flybrain) | No README this pass. |

## Search notes

- GitHub Search API (22 Sep 2026 UTC): `MaleCNS created:>=2026-09-17` **80**; `MaleCNS created:>=2026-09-18` **55**; `FlyWire created:>=2026-09-17` **52**; `FlyWire created:>=2026-09-18` **37**; `"166,700" created:>=2026-09-17` **11**; `flybrain created:>=2026-09-17` **53**; `fruit fly connectome created:>=2026-09-17` **74**; `MaleCNS created:>=2026-09-01` **270** (was 212 on 18 Sep). `stonkfly created:>=2026-09-17` **2** without forks / **23** with `--include-forks true`. `doomfly` same window **4** / **15** with forks.
- Also ingested FlyWire / flybrain / fruit-fly dumps (262 unique records across queries before the relevance filter). Ranked / New above are fetched-README items, not the raw dump.
- Forks API this pass: `nftechie/stonkfly` stars **802**, `doomfly` **385**, `flm` **90**. FlyDrones **216★** / 51 forks.
- Live HTTP GET on 22 Sep 2026: mk-jev Pages, FlyDrones Pages, fruitflysynth Pages, fly-chan Pages, brainrotposts.com, flywire-fly-lab game.html, nandfly, beat-the-fly, 9tofly, Fly School, Euraxluo, music-in-the-body, polyfly-ui, flyscope, malecns-pong-lab Pages, fly-blackjack, FlyBreak chatgpt.site, flysoul Pages, drosophila-critic Pages, flyrun.runningdog.org, dotFly docs, supertruth research, fly.pokyh.com, fly-fight qoder.zone, FLM Vercel, Aimbug, Marksman, Space Program, Inquirer, falafel Pages, fly-bench.com/bench, flybrain.online/dartboard, flybrain.online/flyonardo, unrollnow 2100964182028099993 / 2101298482002927874 / 2102092842537734496, Zenodo 22871090 — **200**. `stonkfly.com` **TLS hostname mismatch** from this agent (dashboard `stonkfly-three.vercel.app` still 200). First-party `x.com` HTML **404** (login wall).
- X/Twitter was not used for new status IDs. Hugging Face Spaces were not re-crawled except URLs already in READMEs.
- Star outliers that are **not** cooler new whole-brain demos: FlyDrones 216★ (already listed; MiniFly in the browser); cobanov 575★ (index); nftechie canon; fruitflysynth 15★ (already ranked 17 Sep); flywire-fly-lab 13★ (already ranked 17 Sep); pianist-fly 3★ (real, ranked #4).

*End of shard. Fold only the strongest verified items into README; do not dump this file wholesale. Folded this pass: FlySoul, Model Kombat, Pokefly, pianist-fly, The Fly’s Table, Fly-NAF, FlyBreak, fly-swing, Haltere Pilot, fly-cord-robots, Flyguy, Fly Terrarium, Flybrain (gate course), fruitflysynth / Brain Rot / fly-chan / flywire-fly-lab (17 Sep GitHub shard), fly24, Drosophila Critic, fly-garden, boltzmann-fly, connectome-kernels (tools). Box X follow-up folded: Fly Falafel King, therealfly, flyconnectome-nulls, flybench, The Dartboard. Leave FlyWall / sudoku-expert / metaphor-only / LoL dry-run / fly_rotten (notebook) / drone-fly (overlaps fly-fpv; not LIF) / seeton/fly (viewer, not LIF) out of the list.*
