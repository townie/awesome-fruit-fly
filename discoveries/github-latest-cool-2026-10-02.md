# GitHub-latest cool (23 Sep–2 Oct 2026)

Research date: **2026-10-02** (UTC). Scope: MaleCNS / FlyWire / fruit-fly-connectome **demo** repos created or pushed after the 22 Sep hunt (PR #9), plus one same-day miss that hunt never cited (`igdigitallab/bioreservoir`, created 22 Sep 06:03 UTC). Ranked by novelty versus [README](../README.md) and [`discoveries/*.md`](.).

Stars are GitHub API `stargazers_count` from this pass. Missing stars are omitted, not guessed. No invented URLs. Live pages below were HTTP-checked **200** on 2 Oct 2026 unless marked otherwise.

**Compared against:** `README.md` at `da3cd79` (22 Sep cool-hunt), every `discoveries/*.md` file, and [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) (**656★**, content push **30 Sep**: Banana Quest, BioReservoir, Fly Self Driving). Fly Self Driving was already on this README. The other two were not.

These remain wiring-diagram simulations. A live page, a PAM pulse, or a trained readout is an interface, not proof a fly learned 2048, chess, osu!, or the midterms.

## Search volume

GitHub Search API, 2 Oct 2026 UTC, `created:>=2026-09-23` (first page, up to 100, none of these queries overflowed 100):

| Query | Total |
|---|---:|
| `MaleCNS` | 50 |
| `FlyWire` / `flywire` | 75 |
| `flybrain` | 48 |
| `malecns` | 50 |
| `"male cns"` | 14 |
| `"fruit fly" connectome` | 66 |
| `drosophila connectome` | 66 |
| `"fruit-fly" brain` | 52 |
| `"166,700"` | 7 |
| `doomfly` | 1 |
| `stonkfly` / `PAM11` / `PPL101` / `"165,122"` | 0 |

**215** unique repositories across those queries before the relevance filter. Almost all were absent from this list. `nftechie` public fly repos are still **doomfly / stonkfly / flm** (no new demo; latest unrelated push `misalignment` 21 Sep). `fruitflydev` has no repo pushed after 18 Sep.

## Ranked: folded this pass

Taste + substance (new I/O, a control table, a live page). Not star order. `Shirtep/fly-mania` is the star outlier of the *new* set (**5★**) and is not #1.

| # | Project | Stars | Dopamine/RL? | Live | One-liner |
|---|---|---:|---|---|---|
| 1 | [professorwang/flybrain-banana-quest](https://github.com/professorwang/flybrain-banana-quest) | 2 | no (frozen LIF; maps authored) | [Pages](https://professorwang.github.io/flybrain-banana-quest/) | FlyWire **139,255** foraging game; optional MaleCNS+VNC mode (Zenodo: **176,422**). Technical note: a glutamate-sign flip is synaptic-mass balance, not glutamate. Cobanov 25–30 Sep. Created 25 Sep. |
| 2 | [dtecx/doodle-fly](https://github.com/dtecx/doodle-fly) | 0 | no | [Pages](https://dtecx.github.io/doodle-fly/) | Whole FlyWire **138,639** LIF, no training, Doodle-Jump-style. Intact falls 0–1× / 2 min (~12,500); swapped eyes 41–44×; blind hops. Created 29 Sep. |
| 3 | [dtecx/20fly8](https://github.com/dtecx/20fly8) | 0 | **yes** — PAM / PPL1 on FlyWire KC→MBON | [Pages](https://dtecx.github.io/20fly8/) | 5,177 Kenyon cells learn 2048. 3,000 games → score 6,986; rewired nose 925; shuffled learned synapses 1,287. TD error is computed outside the circuit. Created 1 Oct. |
| 4 | [igdigitallab/bioreservoir](https://github.com/igdigitallab/bioreservoir) | 3 | no (fixed reservoir) | [fly.igdigi.com](https://fly.igdigi.com) | 165,122 MaleCNS LIF answers yes/no. Pre-registered midterm batch: real-brain mean p(yes) **0.5001** (range 0.4930–0.5053) on 33 questions. Outcomes **not scored** yet. Controls: no-brain, degree-preserving rewire, ER, seeded coin. Created **22 Sep** (missed). |
| 5 | [slickdomi/flybrain-fpv](https://github.com/slickdomi/flybrain-fpv) | 0 | no (frozen; `learn` arm was the worst) | [flybrain-fpv.domi.zip](https://flybrain-fpv.domi.zip) | Full **166,700** MaleCNS on WebGPU flies an FPV drone (Aimbug author). Yaw DNa02, climb DNp53, escape DNp01. Painting / lock / dive assist are game code; no target drive collapses hits. Created 23 Sep. |
| 6 | [vib2810/fly-brain-zero-shot](https://github.com/vib2810/fly-brain-zero-shot) | 1 | tuned gains, weights frozen | local | FlyWire 138,639 + flyvis eyes on NeuroMechFly. Intact ~2.96 poles/10 s vs scramble ~0.34; two-leg cut does not wipe the real-wiring arm. Leg rhythm is a hand-built CPG. Created 29 Sep. |
| 7 | [znatgost/chessfly](https://github.com/znatgost/chessfly) | 0 | **yes** — MB dopamine; look-ahead is engine code | [Pages](https://znatgost.github.io/chessfly/) | 5,177 FlyWire Kenyon cells self-play chess. Real wiring ≈ shuffled claws. Created 30 Sep. |
| 8 | [Curt-Park/fly-cartpole](https://github.com/Curt-Park/fly-cartpole) | 0 | sensor-gain search; synapses frozen (earlier MB dopamine arm 392.5) | [Pages](https://curt-park.github.io/fly-cartpole/) | 5,459-neuron MaleCNS flight circuit on CartPole. Untuned 275.6/500 (pole never falls); five tuned gains hit 500. Created 29 Sep. |
| 9 | [RootVandal/subject-783](https://github.com/RootVandal/subject-783) | 0 | no | [Pages](https://rootvandal.github.io/subject-783/) | Horror lab on whole FlyWire Shiu LIF. Block neurons; loud sound into JO can fire the giant fiber. Created 2 Oct. |
| 10 | [SpikeCalls/grey-leno-fly-brain](https://github.com/SpikeCalls/grey-leno-fly-brain) | 0 | PAM / PPL1 term in the loop; learning not claimed | [flyleno.viosarcade.xyz](https://flyleno.viosarcade.xyz/) and [Pages](https://spikecalls.github.io/grey-leno-fly-brain/) | 138,639 / 15.1M puppets Grey Leno. Stage events hit identified sensory cells. Created 30 Sep. |
| 11 | [turlockmike/alpha-fly](https://github.com/turlockmike/alpha-fly) | 0 | **yes** — one gain per synapse; topology frozen | [Pages](https://turlockmike.github.io/alpha-fly/) | Full MaleCNS chess self-play. README: wiring probably **not** special vs a same-degree, same-sign shuffle. Beats Stockfish only while Stockfish plays mostly at random. Created 23 Sep. |
| 12 | [victory-c/flybrain-play](https://github.com/victory-c/flybrain-play) | 0 | **RL readout** (71-parameter CEM decoder; graph frozen) | [Vercel](https://flybrain-play.vercel.app) | Whole MaleCNS tastes drinks and rides a bike. Walking-command neurons do not track lean; flight-steering DNs do. 16 riders, mean 14.1 s / 15 s. Created 28 Sep. |
| 13 | [Jeremiah-Sakuda/fly-applicant](https://github.com/Jeremiah-Sakuda/fly-applicant) | 0 | no | [fly-office.vercel.app](https://fly-office.vercel.app) | 166,700 / 25.6M MaleCNS applies to scripted jobs. The market is authored comedy. Created 26 Sep. |
| 14 | [KapilSareen/flytown](https://github.com/KapilSareen/flytown) | 1 | no | [Pages](https://kapilsareen.github.io/flytown/) | Town of citizens, each an **8,000-neuron** MaleCNS prune. Goals (café, brawl) are hand-made. Created 29 Sep. |
| 15 | [Pacsy1/MaleCNSBee](https://github.com/Pacsy1/MaleCNSBee) | 0 | no | local Paper server | Minecraft bee on 165,733 MaleCNS neurons. Author: fly nervous system, not a bee’s, and no trained motivation. Created 27 Sep. |
| 16 | [Shirtep/fly-mania](https://github.com/Shirtep/fly-mania) | 5 | **RL readout** (DAgger, 352,971 params; no reward) | local | Frozen 3,418-neuron MaleCNS subgraph plays osu!mania 4K. Created 29 Sep. |
| 17 | [kenprosi/PFPG---fruit-fly-playground](https://github.com/kenprosi/PFPG---fruit-fly-playground) | 3 | **yes** — PAM / PPL1 weaken KC→MBON; body motion is code | local `Play.bat` | Browser ragdolls can wear all 139,255 FlyWire neurons. Distinct from PersonConnectome. Created 26 Sep. |
| 18 | [Chawakorn111/PoopyFly](https://github.com/Chawakorn111/PoopyFly) | 1 | **yes** — homeostatic three-factor rule | local | MaleCNS core **165,650** decides when to defecate. Assumptions file limits the claim. Created 27 Sep. |
| 19 | [UniversidadCamiloJoseCela/drosophila-lang](https://github.com/UniversidadCamiloJoseCela/drosophila-lang) | 0 | PAM / PPL1 write KC→MBON “variables” | local | Esoteric language on FlyWire ≥5-synapse graph (138,639 / 2,700,513). Program ends when the giant fiber fires. Created 28 Sep. |
| 20 | [kosmoKwan/fly-connectome-wiring](https://github.com/kosmoKwan/fly-connectome-wiring) | 0 | no | local | Leg motor rate models, MaleCNS + MANC, six rewire families. Manuscript code, not a game. Created 30 Sep. |

Also folded from the still-unmerged branch `x/add-connectome-host-954c` (cherry-picked, not a new biology find): [anima-research/connectome-host](https://github.com/anima-research/connectome-host) with the **Not biology** caveat. Shard: [`connectome-host-2026-09-25.md`](connectome-host-2026-09-25.md).

## Nearby: real wiring, not folded

Inspected READMEs. Left out because the loop repeats something already listed, the host is local and the claim is thin, or the honesty bar is softer than the rows above.

| Repo | Why it stays in the shard |
|---|---|
| [znatgost/fly67](https://github.com/znatgost/fly67) | Whole FlyWire in a tab (Brian2-checked, “six seven”). Live Pages **200**. Overlaps flybrain.app / fly-explorer / fly-brain-bench. Created 29 Sep. |
| [znatgost/designfly](https://github.com/znatgost/designfly) | Browser design studio. Project text says a **121-neuron** brain, not a published whole-CNS graph. Pages **200**. Created 1 Oct. |
| [shushuzn/fruitfly-tetris](https://github.com/shushuzn/fruitfly-tetris) | Full MaleCNS Tetris. Honest “runs, plays badly.” FlyTris already covers this game. Created 23 Sep. |
| [rmz-24/fruitfly-blackjack](https://github.com/rmz-24/fruitfly-blackjack) | FlyWire whole-brain blackjack + MB dopamine. The Fly’s Table is the measured MaleCNS MB table. Created 26 Sep. |
| [Olh2012ooo/fluesjakk](https://github.com/Olh2012ooo/fluesjakk) | Norwegian chess on a ~134k FlyWire-scale net. Chess already has honest-null labs (fly_chess, ChessFly, alpha-fly). Created 23 Sep. |
| [S1MS4/fly-chess](https://github.com/S1MS4/fly-chess) / [GrzegorzOle/flybrain-tictactoe](https://github.com/GrzegorzOle/flybrain-tictactoe) / [50RISHU/FlyCNS-TicTacToe](https://github.com/50RISHU/FlyCNS-TicTacToe) | More chess / tic-tac-toe. FlyCNS-TicTacToe is explicit that **minimax decides** and the fly only breaks ties ([DEV write-up](https://dev.to/asyncinnovator/i-connected-a-fruit-fly-connectome-to-tic-tac-toe-with-a-minimax-safety-net-5bc0)). |
| [EmirMuhammetARAN/doom-flywire](https://github.com/EmirMuhammetARAN/doom-flywire) | Another FlyWire Doom. DOOMFLY and mutkuoz/flydoom already cover the genre. Created 23 Sep. |
| [baltap/FlappyFly](https://github.com/baltap/FlappyFly) | Another Flappy (~80k, dopamine-on-crash). Several Flappies already nearby. Created 25 Sep. |
| [pasangimhana/fly-x-jev](https://github.com/pasangimhana/fly-x-jev) (5★) / [aryap1804/fly-x-jev](https://github.com/aryap1804/fly-x-jev) | Near-duplicate browser robots: MaleCNS eye columns + MB PAM/PPL + Jev action pick. Model Kombat already is the versus-Jev fight. |
| [padmanabhan-r/Spikecast](https://github.com/padmanabhan-r/Spikecast) | Fly on a road, Jev chooses actions. [spikecast.vercel.app](https://spikecast.vercel.app) **200**. Overlaps the Jev cluster. |
| [AwesomeZun/FDDD](https://github.com/AwesomeZun/FDDD) | Browser swarm learns from **already-computed** docking scores. [flybrain.kr/en](https://flybrain.kr/en) **200**. Author: not a drug experiment. Created 27 Sep. |
| [AwesomeZun/Project-FlyGate](https://github.com/AwesomeZun/Project-FlyGate) | Hackathon pharmacovigilance agent; MaleCNS is a router next to an LLM. [Vercel](https://project-flygate.vercel.app) **200**. |
| [merfijang/inufly](https://github.com/merfijang/inufly) | MaleCNS Shiba on a runner track; attempts are paid by token fees. Meme-economy wrapper. Created 29 Sep. |
| [solonlend/fly-engine](https://github.com/solonlend/fly-engine) | Evolved connectomes on candles. README: work in progress. Created 23 Sep. |
| [youn-sm/fly-trading](https://github.com/youn-sm/fly-trading) | README: the live page is a club-room reel with **no stock UI**; the NVDA pipeline is an older script. |
| [Sametergucc/FlyNads](https://github.com/Sametergucc/FlyNads) | BTC prediction game on a **699-neuron** visual. Not whole-brain. |
| [8002panch/his-royal-flyness](https://github.com/8002panch/his-royal-flyness) | hackUMBC courtship: four phones, one MaleCNS. Hackathon scope; not re-played here. Created 26 Sep. |
| [CodeMan1729/flybrain-arena](https://github.com/CodeMan1729/flybrain-arena) | Godot combat fork of already-nearby FLYFEAR. Escape via LC4/LPLC2→DNp01/DNp03. Created 24 Sep. |
| [owenautosport/flyspeare](https://github.com/owenautosport/flyspeare) | FlyWire mushroom body types Shakespeare. Local. Created 26 Sep. |
| [izntariq/fly-with-me](https://github.com/izntariq/fly-with-me) | Whole FlyWire DJ. Overlaps DJ Drosophila / fruitflysynth. Created 29 Sep. |
| [thepixelabs/flyer](https://github.com/thepixelabs/flyer) | Whole FlyWire picks a flavour; response drawn as an ink plate. Art-adjacent, local. Created 29 Sep. |
| [xiangyangssss-del/fly-explore](https://github.com/xiangyangssss-del/fly-explore) | Phone foraging PWA. [Pages](https://xiangyangssss-del.github.io/fly-explore/) **200**. Honesty panel in-app; not re-audited past the short README. |
| [snuri00/fruit-fly-connectome](https://github.com/snuri00/fruit-fly-connectome) | FlyWire lab console + swat game. Swat / Hand-loom GF already cover the reflex arcade. |
| [ameerul-muminin/fly-tamagotchi](https://github.com/ameerul-muminin/fly-tamagotchi) / [leath0r/flydesk](https://github.com/leath0r/flydesk) / [spicypunch/neurofly](https://github.com/spicypunch/neurofly) / [BakonZHOU/FlyPet-MaleCNS](https://github.com/BakonZHOU/FlyPet-MaleCNS) / [lan450/desktop-roach](https://github.com/lan450/desktop-roach) | More desktop pets. Fly-chan, Flyguy, DesktopFly, FlyCNS Desktop Pet already span this. Roach is a DesktopFly fork with a cockroach mesh. |
| [klasinlapaprechar/fly-muaythai](https://github.com/klasinlapaprechar/fly-muaythai) | 6,170 MaleCNS neurons, PPO, MuJoCo ring. Wiring frozen. Overlaps embodied PPO demos (fly-fpv, fly-garden). |
| [ZENinjaneer/flykart](https://github.com/ZENinjaneer/flykart) | 165,122-neuron go-kart. Overlaps fly-self-driving / flybrain-play. Created 28 Sep. |
| [WKDev/flykski](https://github.com/WKDev/flykski) | flybody + MaleCNS ski research. Status table says walking plates exist; infinite slope not started. Created 23 Sep. |
| [hldrnwnv/fly-drone](https://github.com/hldrnwnv/fly-drone) | Virtual FPV via fly.ai. No physical drone. Overlaps Flybrain FPV / fly-fpv. |
| [silas1011/pilotfly](https://github.com/silas1011/pilotfly) | FlyWire + flyvis into Uncrashed. README: **not finished**. |
| [Ryans-sS/malecns-embodied-fly](https://github.com/Ryans-sS/malecns-embodied-fly) | Codex fork plus MaleCNS→NeuroMechFly. Embodied stack already listed (fly.ai, eonsystemspbc, FlyGym). |
| [fsantibanezleal/CAOS_RES_Destello](https://github.com/fsantibanezleal/CAOS_RES_Destello) / [fsantibanezleal/CAOS_FlyCNS](https://github.com/fsantibanezleal/CAOS_FlyCNS) | Whole-CNS compiler + two-eye viewer (PyPI `flycns`). Tooling. |
| [LengQingSnow/CNS2FPGA](https://github.com/LengQingSnow/CNS2FPGA) | FPGA graph images; Ethernet load claimed board-verified. Tooling, not a playable demo. |
| [joonghui0926/drosophila-connectome-cognitive-tasks](https://github.com/joonghui0926/drosophila-connectome-cognitive-tasks) | Paper code: one trainable scalar per MaleCNS edge. Not a demo. |
| [xiangdoz/fly-connectome-attractor](https://github.com/xiangdoz/fly-connectome-attractor) | Shiu-model attractor / neurotransmitter-annotation screen. Science note. |
| [vichienFF/flybrain-connectome-benchmark](https://github.com/vichienFF/flybrain-connectome-benchmark) | Zenodo preprint on knockout-prediction failures. Sibling of flybench, not a game. |
| [zapret-digital/fly-brainloss](https://github.com/zapret-digital/fly-brainloss) | Random cell deletion vs sugar / loom / touch. Lesion toy; flybench is the pre-registered version. |
| [neuroflyapp/neurofly](https://github.com/neuroflyapp/neurofly) | “NeuroCause” experiment host. [neuro-cause.com](https://neuro-cause.com) **200**. Platform, not one demo. |
| [abstractionthief/drosophila-under-the-hood](https://github.com/abstractionthief/drosophila-under-the-hood) | MaleCNS path explorer. [duth.abstraction.engineer](https://duth.abstraction.engineer) **200**. Viewer. |
| [jasonfye2015/fly-brain-dungeon](https://github.com/jasonfye2015/fly-brain-dungeon) | 4,501 MB neurons as a dungeon monster. Subgraph; Windows exe. |
| [jasonfye2015/fly-mind](https://github.com/jasonfye2015/fly-mind) | Local LLM plus a 5,191-neuron MB “limbic system.” Language is the LLM. |
| [pragyaangaur/Fly-Brain-LeetCode](https://github.com/pragyaangaur/Fly-Brain-LeetCode) | FlyWire answers LeetCode. Overlaps FLM / BioReservoir as a reservoir party trick; no control table pulled this pass. |
| [prshnttw/Fly-Flirt](https://github.com/prshnttw/Fly-Flirt) | Groq scores chat into a 1,350-cell MaleCNS subgraph. Profiles `x.com/prshnttw` and `x.com/Shriyasai1` with **no status IDs**. |
| [musefly-ai/game](https://github.com/musefly-ai/game) | fruitfly.world survival dish. [fruitfly.world/play](https://fruitfly.world/play) **200**. Brain is a pluggable slot; sim core is the LC4/LPLC2 giant-fiber contract (`musefly-ai/sim`). |
| [s31fdev/fly-terrarium](https://github.com/s31fdev/fly-terrarium) | **Name collision** with already-listed `jonathancomergit-ai/fly-terrarium`. This one is NeuroMechFly route walking. [Pages](https://s31fdev.github.io/fly-terrarium/) **200**. |
| [NewYorkImperialist/fly-simulator](https://github.com/NewYorkImperialist/fly-simulator) | Swat a physically simulated fly. Overlaps Fly Terrarium / Swat. |
| [icybb0903-sketch/flygo](https://github.com/icybb0903-sketch/flygo) | 9×9 Go. README: wiring is real; dynamics, encoding, and the trained head are engineered. |
| [grishahq/fly-vs-fly](https://github.com/grishahq/fly-vs-fly) | Two FlyWire agents play Gomoku with supervised + PPO readouts. One recorded 37-move game. |
| [cook-cxb/flybrain-dodge](https://github.com/cook-cxb/flybrain-dodge) | Rate-model dodge from MaleCNS synapse counts. Subgraph arcade. Created 2 Oct. |
| [treewalkr/flybrain](https://github.com/treewalkr/flybrain) | Pong-catch, CEM readout, frozen MaleCNS. Another small-readout Pong. |
| [valerypetrov/fly-admin](https://github.com/valerypetrov/fly-admin) | FlyWire administers a local ClickHouse. Joke ops loop. |
| [imrizwan/flywire-cortex](https://github.com/imrizwan/flywire-cortex) | Pip package mapping FlyWire rates to coding-agent drives. Not a watchable demo. |
| [neomorrison/malecns-test](https://github.com/neomorrison/malecns-test) | MaleCNS decides; a **trained** humanoid walks. Body skill is PPO, not the connectome. |
| [WerG0D/FlyBG3](https://github.com/WerG0D/FlyBG3) | BG3 NPC bridge. Experimental; game and net are separate processes. Not re-run. |
| [solomonshalom/flycraft](https://github.com/solomonshalom/flycraft) | Minecraft body + smell-centre edits. Short research note. |
| [amthedev/cerebro-mosca](https://github.com/amthedev/cerebro-mosca) | FlyWire + BANC laptop LIF, Zenodo. Runtime/tooling. |
| [joshuabradley012/brainfly](https://github.com/joshuabradley012/brainfly) | Large “close the loop” MaleCNS attempt. Not a single finished demo this pass. |
| [gyujeongion/flyconnectome-nulls](https://github.com/gyujeongion/flyconnectome-nulls) | **Already on the README.** Still pushing (search created-date 23 Sep). Do not re-add. |

## Thin, metaphor, stub, or gone

| Repo | Why it looks thin |
|---|---|
| [zehantan6970/LeLampFlyBrainSimulation](https://github.com/zehantan6970/LeLampFlyBrainSimulation) | Desk lamp on a **Drosophila-inspired** SNN. Not a published connectome. |
| [GinyuSpecialForce/FlyPhysicsC](https://github.com/GinyuSpecialForce/FlyPhysicsC) | AP Physics C via a symbolic solver dressed as optic lobe / MB. |
| [Adelalbasm-stack/fruit-fly-hogwarts-connectome](https://github.com/Adelalbasm-stack/fruit-fly-hogwarts-connectome) | Creative Hogwarts sensory script. |
| [Dudleycatalectic7176/dudleycatalectic7176.github.io](https://github.com/Dudleycatalectic7176/dudleycatalectic7176.github.io) | README is **GetMyCv**, a CV-order site. Description mentioned a drone pilot; the fetched README does not. |
| [bastionextras/fly-brain1v1-arena](https://github.com/bastionextras/fly-brain1v1-arena) | 246-byte README plus a Google Drive link. |
| [roanbrasil/fly-brain-lab](https://github.com/roanbrasil/fly-brain-lab) | 0 kb. Description only. |
| [MANGOCURLY/fly-hangul](https://github.com/MANGOCURLY/fly-hangul) / [owertonguedes/fly-connectome-learning](https://github.com/owertonguedes/fly-connectome-learning) | Search hits; GitHub README API **404** this pass. |
| [Charan-2004/Flying-Jev](https://github.com/Charan-2004/Flying-Jev) / [Lexovian/WerrSoma](https://github.com/Lexovian/WerrSoma) / [reacherwu/giant-fiber](https://github.com/reacherwu/giant-fiber) | Marketing-heavy “139k + Jev + swords / sub-5 ms coprocessor” pages. Not promoted over inspectable games. |
| [IT-EXPRESS-Bayern/Fliege](https://github.com/IT-EXPRESS-Bayern/Fliege) | “GPT-6” reconstruction pitch. |
| Empty / no-README cluster | `MatiasDelera/flybrain`, `burakayy7/flybrain-experiments`, `hulehe/malecns-control`, `AryaGpt05/Fruit-Fly-Brain-Connectome`, and other 0–1 kb description-only repos in the 215. |

## Search notes

- Also checked cobanov commits since 22 Sep: `03356c1` / `9e8092d` (BioReservoir, 22 Sep), `2df0698` (Banana Quest, 25 Sep), `ed5e006` (Fly Self Driving, already listed, 30 Sep).
- Live HTTP GET on 2 Oct 2026: fly.igdigi.com, Banana Quest Pages, flyleno.viosarcade.xyz, grey-leno Pages, subject-783 Pages, doodle-fly Pages, 20fly8 Pages, flybrain-fpv.domi.zip, flybrain-play Vercel (+ `/ride/`), fly-office.vercel.app, fly-cartpole Pages, flytown Pages, chessfly / fly67 / designfly Pages, alpha-fly Pages, flybrain.kr/en, fly-explore Pages, fly-brain-agent Pages, s31fdev fly-terrarium Pages, spikecast.vercel.app, fruitfly.world/play, flyrace Pages, project-flygate Vercel, duth.abstraction.engineer, neuro-cause.com, IBM Doom recap, Zenodo 10.5281/zenodo.22998484 — **200**.
- X/Twitter was not used for new status IDs. No `x.com/*/status/` URLs appeared in the fetched READMEs. See [`x-latest-cool-2026-10-02.md`](x-latest-cool-2026-10-02.md).
- Star counts are not copied into the README.

*End of shard. Folded this pass: Banana Quest, Doodle Fly, 20fly8, BioReservoir, Flybrain FPV, fly-brain-zero-shot, ChessFly, fly-cartpole, Subject 783, Grey Leno, alpha-fly, flybrain-play, Fly Applicant, Flytown, MaleCNS Bee, fly-mania, ragdoll playground, PoopFly, Drosophila-Lang, Walking in the wiring, plus the cherry-picked connectome-host **Not biology** line. Left in this file: another whole-brain browser, another Doom/Flappy/Tetris/blackjack/chess, Jev duplicates, meme traders, desktop-pet forks, and metaphor/stub repos.*
