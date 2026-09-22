# GitHub-latest cool (15–18 Sep 2026)

Research date: **2026-09-18** (UTC). Scope: brand-new or heavily updated MaleCNS / FlyWire / fruit-fly-connectome **demo** repos since ~**2026-09-15**, ranked by novelty versus the existing [README](../README.md) plus [`discoveries/*.md`](.).

Stars are GitHub API `stargazers_count` from this pass. Missing stars are omitted, not guessed. No invented URLs. Live demos were HTTP-checked (200) unless marked otherwise.

**Compared against:** `README.md` (last updated 15 Sep 2026), `discoveries/github-latest-cool-2026-09-15.md` (research 16 Sep), `discoveries/x-latest-cool-2026-09-15.md`, `discoveries/github-latest-cool.md`, `discoveries/x-latest-cool-2026-09-14.md`, `discoveries/games-media-art.md`, `discoveries/trading-dopamine-wirehead.md`, `discoveries/science-embodied-rl.md`. **New** means the repo URL is not already cited there. Cobanov [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) last *content* commit is still **14 Sep** (`8cb2ea6`); GitHub `updated_at` on 18 Sep is issue/star churn, not a new index dump. It had not absorbed the 16–18 Sep drops below.

These remain wiring-diagram simulations. A live page, a PAM pulse, or a trained readout is an interface, not proof a fly learned Balatro, Asteroids, LinkedIn, RuneScape, or courtship song.

## Ranked: coolest new

Genuine misses that are cooler or a different loop than what the README / 15 Sep shards already canonize. Rank is taste + substance (unique I/O, honesty, live page, or a control table), not star count. `EvolutionDeep/murmur` is the star outlier among *new* fly-named demos (15★); it is a ~1,080-cell FlyWire **downsample**, not #1.

| # | Project | Stars | Dopamine/RL? | Live demo | One-liner |
|---|---|---:|---|---|---|
| 1 | [bennjordan/fruitflysynth](https://github.com/bennjordan/fruitflysynth) | 10 | no (conductance-based courtship circuit + physical-model DSP) | [bennjordan.github.io/fruitflysynth](https://bennjordan.github.io/fruitflysynth/) (200). Repo homepage field empty; Pages works. | Benn Jordan: MANC thoracic courtship circuit sings pulse/sine song in-browser. Drag the female closer → ticks become a hum. Unique *audio* I/O. Created 16 Sep. |
| 2 | [fkfkfk0406/fly-chan](https://github.com/fkfkfk0406/fly-chan) | 0 | no (gauges are authored; DNs/MNs pick feed / startle / groom) | [fkfkfk0406.github.io/fly-chan](https://fkfkfk0406.github.io/fly-chan/) (200) | FlyWire v783 (138,639 LIF) as a 3D tamagotchi girl / anatomical fly. ~100 MB first load. Relationship meter is the game; spikes are the body. Created 15 Sep, still pushing 18 Sep. |
| 3 | [Franz23/brainrot](https://github.com/Franz23/brainrot) | 0 | no (sugar GRN → MN9; bait is the sugar) | [brainrotposts.com](https://brainrotposts.com) (200); `brainrot-posts.vercel.app` redirects there | FlyWire v783 rates a LinkedIn post. Engagement bait → sugar Hz → Shiu whole-brain lookup → MN9 verdict. 404 Media (15 Sep) named “write LinkedIn posts” with **no URL**; this is the inspectable one. Created 15 Sep. |
| 4 | [suifei/flywire-fly-lab](https://github.com/suifei/flywire-fly-lab) | 7 | no (knockout screen, not a trainer) | [suifei.github.io/flywire-fly-lab/game.html](https://suifei.github.io/flywire-fly-lab/game.html) (200) | 138,639 / 15.1M on a 16 GB laptop; **17,628** virtual knockouts; browser game is 4,599 cells. κ 0.59 sugar / 0.87 water / 0.91 grooming vs opto. Redundancy ≠ graph path (r ≈ 0). Created 15 Sep. |
| 5 | [dohun1214/malecns-asteroids](https://github.com/dohun1214/malecns-asteroids) | 0 | no (untrained DN decode; **silence two cells**) | local `localhost:8766`; Triton 7.3× realtime claimed | Full 166,700 plays Asteroids. Flee = LC4→DNp02/11; chase = LC10a→AOTU→DNa. Double dissociation in the README. Created 16 Sep. |
| 6 | [FalinX/fly-brain](https://github.com/FalinX/fly-brain) | 0 | no (**zero** trained weights) | local `127.0.0.1:8770` | MaleCNS 166,700 / 25.6M plays Boxhead 2Play. Survival-to-death table: v13 kiter-legs + connectome-eyes **197 s** median vs 216 s scripted ceiling / 104 s 3-rule. Created 16 Sep. |
| 7 | [AbhiPoluri/fly-balatro](https://github.com/AbhiPoluri/fly-balatro) | 0 | **yes** — learning fly vs frozen reservoir; controls in `RESULTS.md` | local overlay of a real Balatro window | MaleCNS as a frozen spiking reservoir on Balatro, with the controls the genre usually skips. Created 15 Sep. Huge tree (193 MB). |
| 8 | [rperissi/iigs-fly](https://github.com/rperissi/iigs-fly) | 1 | no (viewer; PPL101 is a packed cell type, not a reward loop) | local MAME / real IIgs + CoGS TLS card | Apple IIgs 40th (15 Sep): 18 MaleCNS skeletons (GF, DNa, MBON, LC10a/LC4, **PPL101**, aMe12) rotate on a 65C816. Created 16 Sep. |
| 9 | [hwkim3330/flyworker](https://github.com/hwkim3330/flyworker) | 0 | no (policy is one of four; **fly loses to noise**) | [hwkim3330.github.io/flyworker](https://hwkim3330.github.io/flyworker/) (200); [HF Space](https://huggingface.co/spaces/kimhyunwoo/flyworker) (200) | Browser-game QA fuzzer. One policy is FlyWire 138,639; it loses to smooth random. Product is the harness + repro HTML, not fly IQ. Created 15 Sep. |
| 10 | [wetware-labs/nandfly](https://github.com/wetware-labs/nandfly) | 0 | no | [wetware-labs.github.io/nandfly](https://wetware-labs.github.io/nandfly/) (200) | Giant Fiber (12/311 LC4/LPLC2, 661 NAND/LATCH) as an ownerless BSC contract. 98.9% vs LIF on all 4096 patterns. Not whole-CNS; derivation is unusually honest. Created 16 Sep. |
| 11 | [MarlonSteiner/fruitfly-9tofly](https://github.com/MarlonSteiner/fruitfly-9tofly) | 0 | no | [marlonsteiner.github.io/fruitfly-9tofly](https://marlonsteiner.github.io/fruitfly-9tofly/) (200) | Flybody at a sales desk; phone ring → 809-cell DNp01 neighborhood (seeded, ≥5 synapses) → Giant Fiber leaves the chair. Ablation table in the README. Created 17 Sep. |
| 12 | [rahilmavani/fly-hears](https://github.com/rahilmavani/fly-hears) | 2 | trained reader only; 30k-cell frozen graph | local `localhost:8001` | Speak a digit; watch spikes; a tiny reader guesses 0–9. “You’re asking a fruit fly to do speech recognition. Manage your expectations.” Created 17 Sep. |
| 13 | [SimonSaysGiveMeSmile/gfly](https://github.com/SimonSaysGiveMeSmile/gfly) | 0 | no | [gfly.site](https://gfly.site) (200) | Whole MaleCNS in a worker: 163,997 neurons / 6.2M edges (≥5 synapses, 21.7 MB), no server. Field-guide + embodied loop. Created 17 Sep. |
| 14 | [gitwub5/FlyOhtani](https://github.com/gitwub5/FlyOhtani) | 0 | reward on contact/distance; **swing is still scripted** | local Vite `127.0.0.1:5173` | Life-sized NeuroMechFly at the plate. LC4/LPLC2 (311) → 12 DNs → right foreleg + bat. Author flags the scripted swing in the hero GIF caption. Created 17 Sep. |
| 15 | [Moeinich/malecns-OSRS](https://github.com/Moeinich/malecns-OSRS) | 0 | no (lesion + degree-preserving shuffle every score) | local LostCity / rs-sdk socket | MaleCNS plays 2004scape. Sensory/motor import firewall; shuffle control is the deliverable. Created 15 Sep. |

**Nearby, same coolness band (not ranked separately):**

- [aravpanwar/amfly](https://github.com/aravpanwar/amfly) (10★, created **14 Sep**, pushed 17 Sep) — six copies of 166,700 on electric pins; operator fly gets dopamine if a victim hits 100%, burns below 50%. Wirehead art the 15 Sep shard missed. Local CUDA; no public host.
- [Franz23/brainrot](https://github.com/Franz23/brainrot) is #3; sibling energy: [oskarmalmwiklund/land-or-bounce](https://github.com/oskarmalmwiklund/land-or-bounce) (0★, 13 Sep created / 16 Sep push) — same MaleCNS retina/lamina as already-listed swat-or-buy, now scoring a landing page 0–100. [land-or-bounce.vercel.app](https://land-or-bounce.vercel.app) (200). Created before the 15 Sep cut; **URL not cited**. Fold as a Multiply Labs sibling, not a new eye.
- [person55/ommatid](https://github.com/person55/ommatid) (0★, 15 Sep) — FlyVis optic lobe + MaleCNS 165,122 on a Hiwonder RoSpider. Phase 1 pre-registered reflexes **failed** (looming was an input artefact). Advertised `ommatid.org` is **NXDOMAIN** here.
- [emiliano-go/neurafly](https://github.com/emiliano-go/neurafly) (2★, 17 Sep) — FlyWire v783 as a terminal braille visualizer of *whatever the PC is playing* (PulseAudio/PipeWire). Linux-only.
- [tirukovelamanoj/unswattable](https://github.com/tirukovelamanoj/unswattable) (0★, 16 Sep) — 1,984-cell FlyWire looming/GF dodge; learns strike direction. [fly.manojtirukovela.com](https://fly.manojtirukovela.com) (200). Overlaps Swat / ecrase-la-mouche / FlyWireSwat.
- [Batushn/FlyWireSwat](https://github.com/Batushn/FlyWireSwat) (1★, 17 Sep) — Unity 6 kitchen: 1,517-cell FlyWire escape vs swatter / racket / cat / RPG-7; 150-trial kill table. Local Unity, not a web host.
- [zgbrenner/thelegalfly](https://github.com/zgbrenner/thelegalfly) (2★, created 12 Sep, pushed 16 Sep) — MaleCNS as village-charter counsel. Held-out: connectome 13/16, shuffle 11/16, facts-only **14/16**. [legalfly-web.onrender.com](https://legalfly-web.onrender.com) (200).
- [fernando-neto-ai/fly-wordbrain](https://github.com/fernando-neto-ai/fly-wordbrain) (0★, 15 Sep / push 17 Sep) — 49,393-cell frozen recurrent LM; deleting 92.5% of the readout **helped**; shuffled wiring −0.010 nats. Live recital: [huggingface.co/spaces/fernandofernandes/fly-recital](https://huggingface.co/spaces/fernandofernandes/fly-recital) (200). FLM-adjacent with the rare “wiring did almost nothing” table.
- [lyutvs/flymon](https://github.com/lyutvs/flymon) (0★, 17 Sep) — MaleCNS LIF picks attacks in restricted gen-1 OU. M0/M1 measurement dump; **PPL101 is constitutively ~119 Hz** (unusable as a phasic teacher). Local Showdown.
- [rison1337/droffel-isaac-brain](https://github.com/rison1337/droffel-isaac-brain) (0★, 15 Sep) — MaleCNS 165,122 plays Binding of Isaac via a local mod + 3D brain view. New game; not live-hosted.
- [jawaadjariwala/fly-brain-gladiators](https://github.com/jawaadjariwala/fly-brain-gladiators) (0★, 43 kb, 17 Sep) — two untrained 166,700 fighters; octopamine vs loom-gain vs lesioned optics. Thin-ish tree; idea is the octopamine knob.
- [nsfm/fly-afterlife](https://github.com/nsfm/fly-afterlife) (0★, 17 Sep) — MaleCNS LIF + flyvis seam onto real T4/T5 geometry; a FlyWire female shares the room. Lab notebook (`docs/SEAM.md`), not a toy.
- [ak7660/fly-brain-escape](https://github.com/ak7660/fly-brain-escape) (1★, created 18 Sep, GitHub `size` 0 at search, README + 4.4 MB circuit bundle) — 4,296-cell looming→GF rate net, 60 fps. `ak7660.github.io/fly-brain-escape` **404**; use `./run_demo.sh`.
- [Euraxluo/fly-brain-drone](https://github.com/Euraxluo/fly-brain-drone) (0★, 17 Sep) — 5,145-cell looming/escape in-browser. [euraxluo.github.io/fly-brain-drone](https://euraxluo.github.io/fly-brain-drone/) (200). Name says drone; the hosted loop is a swat reflex.
- [ReapeRAlan/fly-operator-lab](https://github.com/ReapeRAlan/fly-operator-lab) (0★, 17 Sep) — full MaleCNS as a Door Kickers 2 operator (native MinHook bridge). v3.2 imitation `move` 100%; PPO collapsed; internal plasticity no measurable effect.
- [tryfontheo/fruit-fly-dota](https://github.com/tryfontheo/fruit-fly-dota) (1★, created 13 Sep, pushed 17 Sep) — 176,422-node MaleCNS + GRU/PPO on real Dota Workshop last-hit. Still a weak prototype. Distinct from planning-only `Draganoider/dota-fly`.
- [frsswq/flygo](https://github.com/frsswq/flygo) (0★, 17 Sep) — MaleCNS frozen structure for Go vs randomized controls. Distinct from already-listed `roymina/Fly_Gomoku` / `BOHUYESHAN-APB/flygo`.
- [NileshArnaiya/flybrain-cricket](https://github.com/NileshArnaiya/flybrain-cricket) (0★, 16 Sep) — shot selection. [flybrain-cricket.vercel.app](https://flybrain-cricket.vercel.app) (200). Inspect before promoting; cricket I/O is new, connectome depth unverified beyond the blurb.
- [klmtseng/fly-explorer](https://github.com/klmtseng/fly-explorer) (0★, 16 Sep) — kids 3D MaleCNS (140,024 positioned somata) replaying escape. [fly-brain-explorer.vercel.app](https://fly-brain-explorer.vercel.app) (200). **Name-collides** already-listed `brandoncho369/fly-explorer`.
- [vijethmd/poke-a-fly-brain](https://github.com/vijethmd/poke-a-fly-brain) (0★, 16 Sep) — stimulate 176,422 MaleCNS cells. [vijethmd.github.io/poke-a-fly-brain](https://vijethmd.github.io/poke-a-fly-brain/) (200). Kitchen-table poke, overlaps HEREISCB / flyverse.
- [matsuo-koya/music-on-the-fly](https://github.com/matsuo-koya/music-on-the-fly) (0★) / [matsuo-koya/music-in-the-body](https://github.com/matsuo-koya/music-in-the-body) (0★, both 17 Sep) — endless instruments on FlyWire v783 / MaleCNS. Pages **200**. Overlaps Fly Lab / DJ Drosophila / lofly-claim.
- [jeffory/lofly](https://github.com/jeffory/lofly) (0★, 23 MB, 17 Sep) — GitHub **description** is courtship-song lo-fi; the README is still cobanov `fly-connectome-template`. Treat as a template clone until the song loop is in-tree. Not ranked.
- [leo-bone/fruitfly-life](https://github.com/leo-bone/fruitfly-life) (1★, 17 Sep) — cinematic egg→death. [fruitfly-life.app.workbuddy.host](https://fruitfly-life.app.workbuddy.host) (200). Brain is **9 functional roles + 42 microcircuits**, not 166k. Empathy toy.
- [AgoraExchange/HiFlyGuy](https://github.com/AgoraExchange/HiFlyGuy) (0★, 17 Sep) — life-cycle observer. [agoraexchange.github.io/HiFlyGuy](https://agoraexchange.github.io/HiFlyGuy/) (200).
- [cpduncan/fly-simulator](https://github.com/cpduncan/fly-simulator) (0★, 41 kb, 15 Sep) — ~138k piloting a virtual body. [cpduncan.github.io/fly-simulator](https://cpduncan.github.io/fly-simulator/) (200). Thin tree; watch the hosted loop before a README fold-in.
- [WilliamJones/pet-fly](https://github.com/WilliamJones/pet-fly) (0★, 15 Sep) — complete MaleCNS web pet, PAM sugar / PPL1 poke, hunger over wall-clock. `williamjones.github.io/pet-fly` **404**; local `index.html`.
- [goldengrape/FPGA-FlyBrain](https://github.com/goldengrape/FPGA-FlyBrain) (0★, 16 Sep) — teaching path from LIF math to FPGA, MaleCNS-constrained. Course, not a game.
- [rickenator/VybFly](https://github.com/rickenator/VybFly) (0★, created 18 Sep, size 0 at search) — “can FlyWire be enlarged 10× and still behave?” Paper/plan energy; README exists. Flag as early.
- [Draganoider/dota-fly](https://github.com/Draganoider/dota-fly) (0★, 18 Sep) — README: **planning only**. Do not promote as a running Dota fly.
- [NakliTechie/flymate](https://github.com/NakliTechie/flymate) (0★, 18 Sep, size 0) / [saintiron82/beat-the-fly](https://github.com/saintiron82/beat-the-fly) (0★, 17 Sep) / [MCSDWVL/WordsWithFlies](https://github.com/MCSDWVL/WordsWithFlies) (0★, 120-byte README) — chess / jigsaw / word-game claims; too new or too thin to rank.
- [hwkim3330/nogeneration](https://github.com/hwkim3330/nogeneration) (0★, 17 Sep) — browser LM-at-logits + a fly connectome. Same author as flyworker; FLM-adjacent.
- [al0cam/flyview](https://github.com/al0cam/flyview) (0★, 17 Sep) — reconstruct the fly’s view from MaleCNS geometry.
- [dhruvin-sarkar/fault-lines](https://github.com/dhruvin-sarkar/fault-lines) (0★, 15 Sep / push 17 Sep) — MaleCNS attack-tolerance. [dhruvin-sarkar.github.io/fault-lines](https://dhruvin-sarkar.github.io/fault-lines/) (200). Science demo; same author as already-listed ConnectomeLens.
- [opifor/femaleflybrain](https://github.com/opifor/femaleflybrain) (0★, 16 Sep) — pre-registered female+male whole-brain bench. Separate from already-listed `opifor/flybrain-female` ($HER token).
- [cosmmoo/RocketFly](https://github.com/cosmmoo/RocketFly) (0★, 16 Sep) — MaleCNS booster landing. Overlaps already-listed Fly Space Program; do not merge.
- [seruyvodoley/flyswarm-connectome](https://github.com/seruyvodoley/flyswarm-connectome) (1★, 16 Sep) — multi-agent tanks on MaleCNS copies.
- [abbosaliboev/fly-brain-drone](https://github.com/abbosaliboev/fly-brain-drone) (0★, 17 Sep) / [HaroldHormaechea/drone-fly](https://github.com/HaroldHormaechea/drone-fly) (0★, 16 Sep) / [CC834/flywire-drone-brain](https://github.com/CC834/flywire-drone-brain) (0★, 185 MB, 17 Sep) — more drone/FPV. Overlaps FlyDrones / fly-fpv / drosophiladrone.
- [Incarntor/fly-hero](https://github.com/Incarntor/fly-hero) (0★, 15 Sep) — FlyWire 14,664 LIF Guitar Hero. **Third** fly-hero after `actuallyrizzn` and `bsgelman`.
- [pulka2014/fly-checkers](https://github.com/pulka2014/fly-checkers) (0★, 15 Sep) — FlyWire Russian checkers.
- [Estevao260/flybrain-pong](https://github.com/Estevao260/flybrain-pong) (0★, 15 Sep) — another Pong (after FlyPong / flywire-pong).
- [realjustadev/FLYBRAIN](https://github.com/realjustadev/FLYBRAIN) (0★, 15 Sep) — Flappy-ish. [realjustadev.github.io/FLYBRAIN](https://realjustadev.github.io/FLYBRAIN/) (200). Flappy cluster continues.
- [FuChen1649/fly-mario](https://github.com/FuChen1649/fly-mario) (0★, 64 kb, 17 Sep) — name-collides already-listed `ksanjeev284/fly-mario`.
- [polatbulut/hello-fly](https://github.com/polatbulut/hello-fly) (0★, 15 Sep) — 139k FlyWire + FlyGym odor walk. Embodied bench.
- [comfuture/flylab](https://github.com/comfuture/flylab) (0★, 17 Sep) — whole-brain + body in-browser. Name-collides `funcreator2030/flylab`.
- [Gnelfling/fruit-fly-neural-addon-gnelfling](https://github.com/Gnelfling/fruit-fly-neural-addon-gnelfling) (0★, 16 Sep, 112-byte README) — GMod FlyWire claim; empty-ish.
- [jjedwards2081/FlyCraft](https://github.com/jjedwards2081/FlyCraft) (0★, 14 Sep / push 16 Sep) — FlyWire via fly-brain in Minecraft Education. Sixth Minecraft fly.
- [Rayato159/minecraft-auto-mining](https://github.com/Rayato159/minecraft-auto-mining) (0★, 17 Sep) — Forge miner + experimental FlyWire. Not a full-brain demo.
- [hjkornn-phys/malecns-operator](https://github.com/hjkornn-phys/malecns-operator) (0★, 16 Sep) — memory-game on 8 GB; rules committed before each run.
- [JaronKBragg7337/fly-school](https://github.com/JaronKBragg7337/fly-school) (0★, 17 Sep) — Morse timing on school hours with the fly’s own learning rule.
- [liudicsu/3dfly](https://github.com/liudicsu/3dfly) (0★, 16 Sep) — MaleCNS visual pathway → MuJoCo flight → stereo point cloud.
- [Demianyuen/flysound-lab](https://github.com/Demianyuen/flysound-lab) (0★, 17 Sep) — JO–AMMC–WED hearing schematic. [flysound-lab.vercel.app](https://flysound-lab.vercel.app) (200). Educational cartoon, not whole-CNS.
- [ankitkapooor/Flycast](https://github.com/ankitkapooor/Flycast) (0★, 16 Sep) — MaleCNS as a fixed reservoir. [flycast.ankitkapoor.me](https://flycast.ankitkapoor.me) (200).
- [acnlabs/fly-harness](https://github.com/acnlabs/fly-harness) (1★, 15 Sep) — model-agnostic deploy harness. [pypi.org/project/fly-harness](https://pypi.org/project/fly-harness/) (200). Tooling.
- [sphere-homotopy/flytegral](https://github.com/sphere-homotopy/flytegral) (0★, created 11 Sep, pushed 18 Sep) — MaleCNS “autonomous math agent.” Heavily updated; not a 15 Sep drop.

## New: dopamine / trading / wirehead

Not already in `trading-dopamine-wirehead.md` or the 15 Sep GitHub shard.

- [franBec/fly-mcp](https://github.com/franBec/fly-mcp) (0★, 16 Sep) — Stonkfly kernel as remote MCP. `reward_fly` / `punish_fly` queue **15 PAM11 / 2 PPL101**. Default backend is a **mock** unless `FLYBRAIN_BASE_URL` is set. Comedy oracle; HOLD is an honest result. Same author as already-listed flywalker.
- [sykeriin/fly-drums](https://github.com/sykeriin/fly-drums) (0★, 15 Sep) — 165,122-cell MaleCNS; six motor pools as kit voices; **dopamine-gated KC→MBON** toward Groove MIDI. Reward is invented (a fly has no snare). Local `real-brain.html`.
- [jaylendilkhush2028/flypoker](https://github.com/jaylendilkhush2028/flypoker) (0★, 17 Sep) / [jaylendilkhush2028/flygambler](https://github.com/jaylendilkhush2028/flygambler) (1★, 16 Sep) — win→dopamine / lose→pain poker and FlyWire-MB gambling. Overlaps fly-brain-poker / Fly Poker; the gambler names FlyWire mushroom body.
- [EvolutionDeep/murmur](https://github.com/EvolutionDeep/murmur) (15★, 17 Sep) — 24 agents, each a **~1,080-neuron laminar downsample of FlyWire**, settle real USDC on Arc via x402. [muros.live](https://www.muros.live/) and [api.muros.live](https://api.muros.live/) **200**. Star count is not evidence of MaleCNS. Keep next to astrafly in the “named fly, not 166k” bucket unless an editor wants the on-chain settlement angle.
- [maumcrez-svg/flyfam](https://github.com/maumcrez-svg/flyfam) (1★, 17 Sep) — connectome paper-trades Pons; holders vote. [flyfam.xyz](https://flyfam.xyz) (200).
- [SotoAlt/flychain](https://github.com/SotoAlt/flychain) (0★, 18 Sep) — PoW is eight gustatory flies; MN9 swallows a tx. Same author as already-listed TraderFly. Local `:5311`.
- [fruitflydev/flyonardo-da-vinci](https://github.com/fruitflydev/flyonardo-da-vinci) (0★, 17 Sep) — 165,122-cell pen driven by Robinhood Chain; canvas claimed by burning $FLYBRAIN. [flybrain.online/flyonardo](https://flybrain.online/flyonardo) (200). Art wrapper on already-listed flycoinrh.
- [wetware-labs/nandfly](https://github.com/wetware-labs/nandfly) — rank #10 (on-chain GF, no token yield).
- [tsukiema1/FLYWHEEL](https://github.com/tsukiema1/FLYWHEEL) (1★, 15 Sep) — connectome-gated RH-chain paper trader. Advertised Pages URL **404** this pass.
- [DocMorphic/tradefly](https://github.com/DocMorphic/tradefly) (0★, created 13 Sep, pushed 17 Sep) — two paper-trading flies. [papertradefly.vercel.app](https://papertradefly.vercel.app/) (200).
- [tyun122189/dopamine-trading-fly](https://github.com/tyun122189/dopamine-trading-fly) (0★, 19 kb, 16 Sep) — FlyWire 138,639 paper-BTC 50×. Toy README.
- [whoboy2/FlyStocks](https://github.com/whoboy2/FlyStocks) (1★, 1 kb, 16 Sep) — empty “training a fruit fly to trade stocks.”
- [aravpanwar/amfly](https://github.com/aravpanwar/amfly) — dopamine on the operator fly (nearby above).
- `gh search repos PAM11 created:>=2026-09-15` returned **0**. The PAM/PPL loop that matters this window is `fly-mcp` (explicit 15/2 Stonkfly set), fly-drums (KC→MBON), and flymon’s negative PPL101-as-teacher note.

## New: desktop, phones, hardware

README already has DesktopFly (macOS) and CyberFly (Spectacles). The 15 Sep shard added Go/OpenGL, HarmonyOS, MLX, PSP, Garmin-thin.

- [MMGGAAS3-git/desktop-vibe-fly-4win](https://github.com/MMGGAAS3-git/desktop-vibe-fly-4win) (7★, created **22 Aug**, pushed 16 Sep) — from-scratch Win32/D3D11 port of desktop-vibe-fly / DesktopFly. Not a 15 Sep drop; **URL not cited**. Best missing Windows pet.
- [SuperCatCraze/FlyBuddy](https://github.com/SuperCatCraze/FlyBuddy) (0★, 17 Sep) — macOS pet, “real fruit fly connectome.”
- [alejandroacho/miga](https://github.com/alejandroacho/miga) (0★, 16 Sep) — native macOS FlyWire circuits + bait.
- [ThomasLin070217/FlyGift](https://github.com/ThomasLin070217/FlyGift) (0★, 54 MB, 17 Sep) — “mysterious macOS gift” on complete FlyWire.
- [nilsonpmjr/OmaFly](https://github.com/nilsonpmjr/OmaFly) (0★, 15 Sep) — FlyWire companion for Omarchy (Arch Hyprland).
- [cj5pvj4vjt-ux/flybrain-deploy](https://github.com/cj5pvj4vjt-ux/flybrain-deploy) (0★, 16 Sep) — macOS pet on a **9-neuron** circuit plus optional offline FlyWire LIF. Desktop-cool, connectome-thin unless the offline path is on.
- [rperissi/iigs-fly](https://github.com/rperissi/iigs-fly) — rank #8.
- [goldengrape/FPGA-FlyBrain](https://github.com/goldengrape/FPGA-FlyBrain) — FPGA course (nearby).
- [person55/ommatid](https://github.com/person55/ommatid) — physical hexapod (nearby).

## New: language, art, science-as-demo

- [bennjordan/fruitflysynth](https://github.com/bennjordan/fruitflysynth) / [Franz23/brainrot](https://github.com/Franz23/brainrot) / [fernando-neto-ai/fly-wordbrain](https://github.com/fernando-neto-ai/fly-wordbrain) / [franBec/fly-mcp](https://github.com/franBec/fly-mcp) / [fruitflydev/flyonardo-da-vinci](https://github.com/fruitflydev/flyonardo-da-vinci) — ranks / nearby above.
- [flybook-git/flm](https://github.com/flybook-git/flm) (71★, created 15 Sep, **pushed 11 Sep**) — **not new work.** README still `git clone https://github.com/nftechie/flm.git`. Same pattern as already-flagged `FLModel/flm`. Mirror / import.
- [nfttechie/flm](https://github.com/nfttechie/flm) (0★, 15 Sep) — one-letter typo squat of `nftechie/flm`; same README clone line.
- [phattar4phan/flylm](https://github.com/phattar4phan/flylm) (0★, 3 kb, 16 Sep) — “FlyWire Language Model”; advertised `chat.flywire.dev` is **NXDOMAIN**.
- [allgoodnow/fruit_fly_torment_nexus](https://github.com/allgoodnow/fruit_fly_torment_nexus) (2★, created 9 Sep, pushed 17 Sep) — torment-nexus art; heavily updated, not a 15 Sep create.
- [suifei/flywire-fly-lab](https://github.com/suifei/flywire-fly-lab) / [dhruvin-sarkar/fault-lines](https://github.com/dhruvin-sarkar/fault-lines) / [opifor/femaleflybrain](https://github.com/opifor/femaleflybrain) — science benches (above).
- nftechie public fly repos this pass are still **doomfly / stonkfly / flm** plus a 15 Sep `homebrew-tap` (not a demo). doomfly **345★**, flm **81★** (API `users/nftechie/repos`).

## Already catalogued (not New)

Confirmed still live in search hits; **do not re-add**. Includes the Sep 6–16 canon plus shards:

DOOMFLY, Stonkfly, StonkFlyRH, stonkfly-lab, FLM (`nftechie/flm`), Fly/Wirehead, Scrollfly, FlyScroll, Infinite Sugar, Faiku, fly-mario, FlyTris (`rothilion26`), kick-the-fly, Aimbug, Swat, Fly Poker, fly-brain-poker, Flyhard, fly-brain-minesweeper, FlyPong, connectome-fighter, flyfear, fly-fpv, fly-craftax, fly-escape, DesktopFly, CyberFly/Spectacles, fly-hero (`actuallyrizzn` / `bsgelman`), flyboard, flydoom (`mutkuoz` / `eganeganegan` / `pratik90908`), NeuroCraft, Fly Brain Minecraft, ruby-project, fruit-fly-fashion, OpenFly, Richy, TraderFly, flycoinrh, flybrain-female, flywire-live, fruit-fly-fund, fruitfly.trade, Gregor, quantum-fly, fly-explorer (`brandoncho369`), fly-brain-bench, fly-flappy-bird, flybrain-snake (`charbelkassab`), FlyBrain boss, FlyBrain-HalfLife, flyputer, FLYBRAIN-BAD_APPLE_X_DOOM, FLYWATT, DJ Drosophila, FLYcasso, flyverse, fly-self-driving, fly.ai, eonsystemspbc/fly-brain, PersonConnectome, flybrain-intransitive, swat-or-buy, Same Smell, Fruit Ninja, fruit-fly-utopia, pikabell tic-tac-toe, jerryjliu/fly_ocr, nicodunks/fruitless, KakaoXI billiards, VaheOfficial/FLY, chonchurik, Fly Space Program, Fly Marksman, FlyDrones, fly-xiangqi, flywalker, fly-flappy (`ns2250225`), fly-habitat, FlyCoder, fly-megacode, Open-Fly (`Pr1nted`), DOOM-x-Fly, etc.

`land-or-bounce` / `thelegalfly` / `amfly` / `desktop-vibe-fly-4win` / `fruit-fly-dota` were created on or before 14 Sep and missed the 15 Sep GitHub shard; they are listed as New *to this repo*, not as 16–18 Sep births.

## Thin meme forks / stubs

Flagged so later README editors do not promote them as brand-new brains.

| Repo | Why it looks thin |
|---|---|
| [flybook-git/flm](https://github.com/flybook-git/flm) | 71★ mirror of `nftechie/flm`. Created 15 Sep; last push 11 Sep; clone instructions still point at nftechie. Same class as `FLModel/flm`. |
| [nfttechie/flm](https://github.com/nfttechie/flm) | Typo-squat of nftechie; identical README clone line. |
| [EvolutionDeep/murmur](https://github.com/EvolutionDeep/murmur) | 15★ / ~1,080-cell FlyWire downsample. Real USDC is cool; do not caption as 166,700. |
| [jeffory/lofly](https://github.com/jeffory/lofly) | Description claims courtship lo-fi; README is still the cobanov template. |
| [leo-bone/fruitfly-life](https://github.com/leo-bone/fruitfly-life) | Live cinematic; 9-role cartoon, not whole-CNS. |
| [cj5pvj4vjt-ux/flybrain-deploy](https://github.com/cj5pvj4vjt-ux/flybrain-deploy) | Default desktop loop is **9 synthetic** neurons. |
| [phattar4phan/flylm](https://github.com/phattar4phan/flylm) | 3 kb; `chat.flywire.dev` NXDOMAIN. |
| [tsukiema1/FLYWHEEL](https://github.com/tsukiema1/FLYWHEEL) | Pages 404 this pass. |
| [Draganoider/dota-fly](https://github.com/Draganoider/dota-fly) | Author: planning only. |
| [whoboy2/FlyStocks](https://github.com/whoboy2/FlyStocks) | 1 kb, no README. |
| [arkibo-lab/sisyphus-fly](https://github.com/arkibo-lab/sisyphus-fly) | No README. |
| [heavyrain39/ffrep](https://github.com/heavyrain39/ffrep) | 159-byte FAQ stub. |
| [MCSDWVL/WordsWithFlies](https://github.com/MCSDWVL/WordsWithFlies) | 120-byte README. |
| [Gnelfling/fruit-fly-neural-addon-gnelfling](https://github.com/Gnelfling/fruit-fly-neural-addon-gnelfling) | 112-byte README. |
| Empty / 0-size namesakes created 16–18 Sep | `tharun-1365/Fruit-fly-brain-porject`, `Savinup21/FlyWireRing`, `ashishsengupta/FruitFly`, `kissy24/ex-malecns`, `creatorarno/assassin_fruit_fly`, `swademcmiller/FruitFlyMinecraft`, `DivyaRaval1909/flybrain-x`, `burkun/FlyBrain`, `Neuroscencer/flybrain`, plus invoice/FLM-named dumps (`repo-7flmnfmw`, `Payment-Receipt-flmn6hna`, …). |
| Stonkfly copies this window (size ~1388 kb, upstream description) | `danielhmills/stonkfly`, `Pendia/Stonkfly-MaleCNS-Coinbase-AI`, `Ma-Dan/stonkfly`, `edacul/stonkfly`, `kernelentropy/stonkfly`, `VirtualAgentics/stonkfly`, `tolliss/stonkfly`, `deecalov/stonkfly`, `JamesOnion0727/stonkfly`, `hzdlive/stonkfly-nftechie`, `GoldRush520/stonkfly`, `0xffar0Oq/stonkfly`, `chenosaurus/stonkfly`, `Bartok9/stonkfly`, `luzobyi-cyber/stonkfly`, plus already-flagged `lawjar` / `yev9en` / `linkpark0929` / `PtPPPPP` / `marekbujko` / `Baroni7777`. `WaromiV/stonkfly` and `twindragon97/stonkfly` are forks with extra bytes; still Stonkfly. |
| Doomfly copies (size ~16451 kb) | `RimuruDev/doomfly`, `Ma-Dan/doomfly`, `ncagle/doomfly`, `8raind/doomfly`, `lesliebinbin/doomfly`, `sunnyark/doomfly`, `vikasvardhanv/doomfly`, plus already-flagged `yeager620` / `dan668673-web` / `marekbujko` / `vitorgamer58`. [GetAGripGal/doomfly-with-interact-and-real-doomwad](https://github.com/GetAGripGal/doomfly-with-interact-and-real-doomwad) is a **renamed doomfly fork** (110 MB). |
| FLM copies | `flybook-git/flm` (71★ mirror), classroom `flm` clones already listed 15 Sep, plus this window’s `MohamedEmad300/flm` and the `*flm*` invoice squat cluster. |
| Same-day Flappy / Pong / Hero cluster | `realjustadev/FLYBRAIN`, `treewalkr/flybrain-flap`, `Estevao260/flybrain-pong`, `Incarntor/fly-hero` (third Guitar Hero). |

## Search notes

- `gh search repos MaleCNS --created >=2026-09-15` → **78** hits. `malecns` same window → **78**. `FlyWire --created >=2026-09-15` → **54**. `"166,700" --created >=2026-09-15` → **9**. `flybrain --created >=2026-09-15` → **54**. `fruit fly connectome --created >=2026-09-15` → **37**. `fruit-fly --created >=2026-09-15` → **100** (API page cap). `stonkfly --include-forks --created >=2026-09-15` → **27**. `doomfly` same → **13**. `flm --include-forks --created >=2026-09-15` → **46**. `PAM11 --created >=2026-09-15` → **0**. `PPL101` same → **0**. Quoted `166700` (no comma) → **0**. `"Male CNS" --created >=2026-09-15` → **7**.
- Also: `MaleCNS --sort updated --updated >=2026-09-16` (85), `FlyWire` same (63), `flybrain` (48), `"166,700"` (12), `fruit-fly` (100, cap), `drosophila connectome` (18). Search API rate-limited further queries this pass; core REST (README/metadata/HTTP) continued.
- `gh search --sort created` is still unsupported; recency used `--created` / `--updated` plus `--sort updated`.
- Ingested **403** unique repo records this pass; **333** unknown-to-this-repo before a relevance/size filter. Ranked / New above are the ones with a fetched README (or an honest empty-tree flag), not the raw dump. Forks API: `nftechie/stonkfly` **131**, `doomfly` **56**, `flm` **13**.
- Live HTTP GET on 18 Sep 2026: fruitflysynth Pages, fly-chan Pages, brainrotposts.com, flywire-fly-lab game.html, nandfly Pages, 9tofly Pages, gfly.site, flyworker Pages + HF, unswattable, flyonardo, muros.live, land-or-bounce, legalfly Render, flyfam.xyz, fly-recital HF, fruitfly-life host, poke-a-fly-brain Pages, fly-brain-explorer Vercel, music-on-the-fly / music-in-the-body Pages, HiFlyGuy Pages, flybrain-cricket Vercel, fly-simulator Pages, flysound-lab Vercel, fault-lines Pages, FLYBRAIN Pages, papertradefly Vercel, pypi fly-harness — **200**. `ommatid.org` **NXDOMAIN**; `chat.flywire.dev` **NXDOMAIN**; `tsukiema1.github.io/FLYWHEEL/` **404**; `williamjones.github.io/pet-fly` **404**; `ak7660.github.io/fly-brain-escape` **404**.
- X/Twitter was not used. Hugging Face Spaces were not re-crawled except flyworker + fly-recital.
- Star outliers that are **not** cooler new whole-brain demos: `nftechie/doomfly` 345★ / `flm` 81★ (canon); `flybook-git/flm` 71★ (mirror); `EvolutionDeep/murmur` 15★ (1,080-cell downsample); `bennjordan/fruitflysynth` 10★ (real, MANC song — ranked #1 on coolness); `aravpanwar/amfly` 10★ (real, created 14 Sep); `suifei/flywire-fly-lab` 7★ (real); `MMGGAAS3-git/desktop-vibe-fly-4win` 7★ (Windows port of an older pet).

*End of shard. Fold only the strongest verified items into README; do not dump this file wholesale. Suggested high-bar fold-ins if the list thaws: Fruitflysynth, Fly-chan, Brain Rot (LinkedIn), flywire-fly-lab (knockout honesty), malecns-asteroids, Boxhead Fly Brain, fly-balatro (with the control caveat), GS FLY (IIgs), Fly Worker (fly loses), NANDFLY (on-chain GF), 9 to Fly. Leave murmur out of the 166k table.*
