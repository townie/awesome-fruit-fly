# GitHub-latest cool (3–16 Oct 2026)

Research date: **2026-10-16** (UTC). Scope: MaleCNS / FlyWire / fruit-fly-connectome **demo** repos created or pushed after the 2 Oct hunt (PR #10, merged 3 Oct), through today. [OrigoZero](https://origozero.ai/world/lumi/fruit-fly) is already on the README (PR #11, merged 14 Oct) and is not re-added. Ranked by novelty versus [README](../README.md) and [`discoveries/*.md`](.).

Stars are GitHub API `stargazers_count` from this pass. Missing stars are omitted, not guessed. No invented URLs. Live pages below were HTTP-checked **200** on 16 Oct 2026 unless marked otherwise. READMEs were read; the games and flight sims were not re-run.

**Compared against:** `README.md` at `a047a45` (OrigoZero), every `discoveries/*.md` file, and [`cobanov/awesome-fly`](https://github.com/cobanov/awesome-fly) (**705★**, content pushes **13–15 Oct**: Barfly, Katamari, FlyGateDemo, ENSOphilia, fault-lines, price-of-thought, plus a Fly-NAF wording update).

These remain wiring-diagram simulations. A live page, a PAM pulse, or a trained readout is an interface, not proof a fly learned pinball, maths, El Niño, or a Cessna.

## Search volume

GitHub Search API, 16 Oct 2026 UTC. Created-date queries did not overflow 100. `fly-brain pushed:>=2026-10-03` and one hyphenated connectome query hit the 100-row page cap; the unique pool below is the union of the pages that were fetched, not a claim that every pushed repo on GitHub was opened.

| Query | Total (`created:>=2026-10-03` unless noted) |
|---|---:|
| `MaleCNS` | 36 (pushed: 71) |
| `malecns` | 36 (pushed: 71) |
| `flywire` / `FlyWire` | 50 (pushed: 93) |
| `flybrain` | 38 (pushed: 56) |
| `fly-brain` | 91 |
| `"fruit fly" brain` | 52 |
| `"fruit-fly" connectome` | 55 |
| `"fruit fly" connectome` | 51 |
| `"drosophila connectome"` (phrase) | 13 |
| `"male cns"` | 5 |
| `"166,700"` | 7 |
| `"165,122"` / `PAM11` / `PPL101` created | 0 (`PPL101` pushed: 1) |

**192** unique repositories with `createdAt` on or after 3 Oct 2026 across those queries, before the relevance filter. None of those full names were already in this list. A further set of older repos was still being pushed; anything already named in a shard was skipped. Two keyword misses were opened because a web catalog named them: [abstractionthief/duth-x-stepmania](https://github.com/abstractionthief/duth-x-stepmania) (created 6 Oct; description does not say MaleCNS) and the [znatgost → gexhaw](https://github.com/gexhaw/chessfly) move of ChessFly.

## Ranked: folded this pass

Taste + substance (new I/O, a control table, a live page, or an honest null). Not star order.

| # | Project | Stars | Dopamine/RL? | Live | One-liner |
|---|---|---:|---|---|---|
| 1 | [TheJustas228/connectocopter](https://github.com/TheJustas228/connectocopter) | 1 | no (frozen Shiu LIF) | [replay](https://thejustas228.github.io/connectocopter/) | Whole FlyWire **138,639 / 15.1M** on a simulated quad that can also drive. Rewire fails flights **0/16**. Giant fibre silenced: looming escape **0/15**. Thrust is a conventional controller. Created 8 Oct. |
| 2 | [aryawidjaja/flight-test-the-fly](https://github.com/aryawidjaja/flight-test-the-fly) | 1 | no | [fly.aryawijaya.com](https://fly.aryawijaya.com) · [Zenodo](https://doi.org/10.5281/zenodo.23156035) | FlyWire subgraph **20,556** neurons as a Cessna yaw damper. Real wiring ranks first vs degree-preserving shuffles and cuts yaw RMS **14–19%** vs the bare airframe; a classical damper cuts **52–57%**. Created 4 Oct. |
| 3 | [omeruk/synaptera](https://github.com/omeruk/synaptera) | 4 | no | local | Pre-registered whole FlyWire on NeuroMechFly. Only feeding (MN9) met the brain-decision bar, and the sugar input is a hand-made foot shortcut. DNp15 steering failed. Tower criterion failed. Created 7 Oct. |
| 4 | [dorywoof/BioGrid](https://github.com/dorywoof/BioGrid) | 4 | no | Windows release page **200**; game not run | Whole FlyWire screen of **140** paired sensory types. Humidity and cooling reach DNb05 via **16** projection neurons; heating mostly does not. Untested in a real fly. Created 15 Oct. |
| 5 | [0Sakura721/flyaim](https://github.com/0Sakura721/flyaim) | — | readout / plasticity arms, all failed | local | Full MaleCNS aiming. Pre-registered: wiring vs shuffle **412.5 vs 430.9 px**, p = 0.66; both worse than random **251.7 px**. Five learning regimes miss. The compound-eye servo that holds the target bypasses the graph. Created 3 Oct. |
| 6 | [castor639/fly-tennis](https://github.com/castor639/fly-tennis) | 0 | no | [fly.warpfield.me](https://fly.warpfield.me) | Two MaleCNS copies (**163,903** neurons, ≥5 synapses). Medulla bump steers; the swing is code. Intact **54/54** hits; shuffle **10**; parked at center **14**. Created 5 Oct. |
| 7 | [SEKY443/3DPinball-DrosophilaCadet](https://github.com/SEKY443/3DPinball-DrosophilaCadet) | 1 | no | [Pages](https://seky443.github.io/3DPinball-DrosophilaCadet/) | **373**-neuron LC4/LPLC2→DNp01 circuit flips Space Cadet. Real wiring beats six shuffles; a hand reflex still wins a little. Comparison framed after the fact. Created 3 Oct. |
| 8 | [krezio/fly-arithmetic](https://github.com/krezio/fly-arithmetic) | 1 | **RL readout** | [Pages](https://krezio.github.io/fly-arithmetic/) | ~**2,000** FlyWire neurons. Held-out addition: real wiring **48±6%**, same-size random net **98±2%**. Created 9 Oct. |
| 9 | [nicpittman/ENSOphilia](https://github.com/nicpittman/ENSOphilia) | 0 | trained readout; reservoir fixed | local | **80**-neuron MaleCNS circuit forecasts Niño 3.4. RMSE **0.807 °C** vs median rewire **0.742**; **85/100** scrambles match or beat it. Cobanov 15 Oct. Created 14 Oct. |
| 10 | [ProfTAlent/FlyGateDemo](https://github.com/ProfTAlent/FlyGateDemo) | 0 | **yes** — PPL101 / PAM on KC→MBON | local | Blog requests as odors. Cosine-on-text still beats one dopamine punishment. Wiring ≈ shuffle. Cobanov 13 Oct. Created 3 Oct. |
| 11 | [rustyorb/barfly](https://github.com/rustyorb/barfly) | 1 | dopamine drive tried; reported dead end | local `npm run dev` | Whole FlyWire at a bar on the Doodle Fly engine. Sugar and looming are injected current. Buzz meter and dialogue are invented. Cobanov 13 Oct. Created 11 Oct. |
| 12 | [PedroKeita/katamari-connectome](https://github.com/PedroKeita/katamari-connectome) | 2 | PAM/PPL runners; no training claimed | [Vercel](https://katamari-connectome.vercel.app) | ~**75k** FlyWire neurons (~54%), not the whole brain. Bias **−0.70** zeroed by hand. One 181 s session, **4.6**/min, no baseline. Created **19 Sep**; cobanov added it 13 Oct. |
| 13 | [Maksym-Lazirko/Drosophila-melanogaster](https://github.com/Maksym-Lazirko/Drosophila-melanogaster) | 0 | no | local VST | **731** FlyWire auditory neurons filter audio. Missing JO synapses are not invented. Created 4 Oct. |
| 14 | [abstractionthief/duth-x-stepmania](https://github.com/abstractionthief/duth-x-stepmania) | 0 | no | local viewer | **766**-neuron looming circuit. Arrows injected, timing calibrated. Edit chart **97%** vs three rewires **~40%**. OutFox play still in progress. Created 6 Oct. |

Also updated, not new projects:

- [ChessFly](https://github.com/gexhaw/chessfly) moved off `znatgost` (Shaduf noted the move on 13 Oct; GitHub redirects the old repo URL). Old Pages `znatgost.github.io/chessfly/` **404**; [gexhaw.github.io/chessfly/](https://gexhaw.github.io/chessfly/) **200**. README link updated. `gexhaw/fly67` is the same move of a project that stayed in the 2 Oct shard.
- [ArtyMend07/Fly-NAF](https://github.com/ArtyMend07/Fly-NAF) best published run is now **5 AM on night 3** (was 4 AM on night 2). [YouTube](https://www.youtube.com/watch?v=R4Ogbf33Gfo) **200**. A full Linux night has not been run.

## Nearby: real wiring, not folded

Inspected READMEs. Left out because the loop repeats something already listed, the host is local and the claim is thinner than the rows above, or the project was created before 3 Oct and was only still being pushed.

| Repo | Why it stays in the shard |
|---|---|
| [asiluzunoglu1216-gif/FlyBrainGame](https://github.com/asiluzunoglu1216-gif/FlyBrainGame) | Full MaleCNS ecosystem. Pages **200**. README says “100% pure connectome” and “zero heuristic creep”; no shuffle table was in the opening. Created 9 Oct. |
| [victory-c/fly-brain](https://github.com/victory-c/fly-brain) | Rewritten bike simulator behind already-listed flybrain-play. [fly-brain-bike.vercel.app](https://fly-brain-bike.vercel.app) and [flybrain-play.vercel.app](https://flybrain-play.vercel.app) both **200**. Not a second entry. |
| [LakoMoor/FlyWireGBA](https://github.com/LakoMoor/FlyWireGBA) | **10★.** GBA ROM, **128** FlyWire neurons including sugar IDs and one MN9. Care meters are the game. Created 4 Oct. |
| [Libra-missing/Fruit-fly-light-pursuit-by-Fruit-fly-brain-modeling-](https://github.com/Libra-missing/Fruit-fly-light-pursuit-by-Fruit-fly-brain-modeling-) | **7★.** ~127k snnTorch brain; light is mapped onto sugar GRNs, which the README says is not vision. Created 13 Oct. |
| [guneysol/flytrader](https://github.com/guneysol/flytrader) | Whole FlyWire paper-trades memecoins. Lost **2.0%** on a historical window; learning “has not been shown to help.” Another tape loop. Created 9 Oct. |
| [devsolux/oandafly](https://github.com/devsolux/oandafly) | Full MaleCNS forex workspace. Trading section is already crowded. Created 13 Oct. |
| [FelipeJackFox/Flomb](https://github.com/FelipeJackFox/Flomb) | Mushroom-body minesweeper. [overfitters.space](https://overfitters.space/proyectos/moscas/buscaminas) **200**. Minesweeper was already a nearby game in earlier shards. Created 4 Oct. |
| [programmingWTF/FlyBrain](https://github.com/programmingWTF/FlyBrain) / [CROmartin/flappy-fly](https://github.com/CROmartin/flappy-fly) | More Flappy. Escape reflex, or a trained readout the README says is not the fly learning. |
| [mpvasilis/flywire-playground](https://github.com/mpvasilis/flywire-playground) | Whole FlyWire in the browser. Pages **200**. Name-collides with already-listed `hills-dong/flywire-playground`. Created 7 Oct. |
| [GiuseppeBellamacina/let-it-flyppen](https://github.com/GiuseppeBellamacina/let-it-flyppen) | Five FlyWire copies, frozen graph, linear readout learns a transcription of *Let It Happen*. ~1,700 neurons actually driven. Created 6 Oct. |
| [Resnais-Beefhair/brain-concert](https://github.com/Resnais-Beefhair/brain-concert) | Whole FlyWire WebGPU sonification. Honest: no rewire control yet. Public link is the upstream artwork [koodio.fi](https://koodio.fi/demot/aivokonsertti/) **200**, not a host of this checkout. Created 11 Oct. |
| [thepuneeth/Flycraft](https://github.com/thepuneeth/Flycraft) | Frozen MaleCNS nerve-cord hexapod, IEEE BIBM draft. Overlaps already-listed fly-cord-robots and Walking in the wiring. Created 14 Oct. |
| [wenlibo90/jumper-connectome](https://github.com/wenlibo90/jumper-connectome) | Crab robot, FlyWire+MANC rate net. README: gait and MuJoCo-WASM still in progress. |
| [lvmengstruggle-a11y/FruitFly-CrabRobot](https://github.com/lvmengstruggle-a11y/FruitFly-CrabRobot) | Claims full MaleCNS in the browser driving Jumper; readout learns; robot assets live next door. |
| [ArcadiaE/fly-brain](https://github.com/ArcadiaE/fly-brain) | FastBrain backend on already-listed `eonsystemspbc/fly-brain`. [Pages](https://arcadiae.github.io/fly-brain/) **200**. Tooling. |
| [fogfish/microfly](https://github.com/fogfish/microfly) | MaleCNS slices in the browser. Local server. Created 5 Oct. |
| [pr4yhk6zt6-wq/flybrain-ios](https://github.com/pr4yhk6zt6-wq/flybrain-ios) | README says the old iPhone whole-brain app is being rebuilt from the nervous system out. |
| [IrohAmca/NeuroPest](https://github.com/IrohAmca/NeuroPest) / [GhostInTheBus/buzzkill](https://github.com/GhostInTheBus/buzzkill) / [TZY114514/fly-colony](https://github.com/TZY114514/fly-colony) | More desktop pets. Buzzkill is a 668-neuron DesktopFly-family pest. |
| [arpanguria68-ui/fly-ears](https://github.com/arpanguria68-ui/fly-ears) / [arpanguria68-ui/fly-plays-nes](https://github.com/arpanguria68-ui/fly-plays-nes) | Full MaleCNS watches video or plays NES. Pages **200**. Overlaps the TV fly and fly-mario. |
| [zonzujiro/flywire-pong](https://github.com/zonzujiro/flywire-pong) | Trained FlyWire paddle. Pages **200**. Another small-readout Pong. |
| [Zaib111/fly-clash-royale](https://github.com/Zaib111/fly-clash-royale) | Self-play Clash clone. Hugging Face space named in the README; no committed result table in the opening. |
| [EvanGruhlkey/fly-poker](https://github.com/EvanGruhlkey/fly-poker) | Another poker. [pokerwithafly.vercel.app](https://pokerwithafly.vercel.app/) **200**. |
| [wangshen310-hub/fly-brain](https://github.com/wangshen310-hub/fly-brain) | Snake. README: has not learned ordinary Snake (0 food in 24 games). |
| [ORI-Muchim/flydrive](https://github.com/ORI-Muchim/flydrive) / [supat-roong/fly-racer](https://github.com/supat-roong/fly-racer) / [jaskirat1616/telotaxis](https://github.com/jaskirat1616/telotaxis) / [Riccardozono/male-cns-circuit-lab](https://github.com/Riccardozono/male-cns-circuit-lab) | More driving. Circuit Lab is explicit that dynamics and the decoder are artificial. |
| [m-de-graaff/valley-intercept](https://github.com/m-de-graaff/valley-intercept) | Jet dogfight. Overlaps Flybrain FPV / Connectocopter. |
| [H29-crypto/biobug-rescue](https://github.com/H29-crypto/biobug-rescue) | Rescue sim. Pages **200**. Hackathon pitch energy. |
| [jayis1/glados](https://github.com/jayis1/glados) / [Patternity/LiquidAion-Neural-Observatory](https://github.com/Patternity/LiquidAion-Neural-Observatory) / [ShiminLee/ChatFlyPT](https://github.com/ShiminLee/ChatFlyPT) / [Mcking1983/flybrain](https://github.com/Mcking1983/flybrain) | Language models with a fly graph beside them. Overlaps FLM. LiquidAion is a **512**-neuron subset. |
| [taehojo/adfly-connectome](https://github.com/taehojo/adfly-connectome) | Amyloid-like pathology on MaleCNS. [jolab.ai/adfly](https://www.jolab.ai/adfly/) **200**. Paper code, not a game. |
| [dhruvin-sarkar/price-of-thought](https://github.com/dhruvin-sarkar/price-of-thought) | Wiring-cost essay. [Pages](https://dhruvin-sarkar.github.io/price-of-thought/) **200**. Cobanov 5 Oct. Sibling of fault-lines, already in the 17 Sep shard. Analysis, not a demo. |
| [LordKarV/flyscore](https://github.com/LordKarV/flyscore) | Benchmark asking whether a sim behaves like a fly because of its wiring. Tooling. |
| [PPWPW/MaleCNS](https://github.com/PPWPW/MaleCNS) | Rubik distance on a **2,048**-node subgraph. Overlaps the X-only cube clips and `lntegrals/flycube-public`. Created 16 Oct. |
| [yifanQQMC/FlyBrainPlayer](https://github.com/yifanQQMC/FlyBrainPlayer) / [someone405-ship-it/fruitfly-roblox-agent](https://github.com/someone405-ship-it/fruitfly-roblox-agent) | Another Minecraft mod; a **1,024**-unit Roblox agent, not the 166k graph. |
| [adventure-gpt/flyguy](https://github.com/adventure-gpt/flyguy) | Rocket League bot. Name-collides with already-listed `Cem-Bas/flyguy`. |
| [sadiqkhzn/fly-vnc-walking-sim](https://github.com/sadiqkhzn/fly-vnc-walking-sim) / [SekWaf/fly-re-embodiment](https://github.com/SekWaf/fly-re-embodiment) / [koishiSaikou/embodied-fly-lab](https://github.com/koishiSaikou/embodied-fly-lab) | More VNC / FlyGym bodies. Embodied stack already listed. |
| [hsilvosa/fruit-fly-rl](https://github.com/hsilvosa/fruit-fly-rl) / [Kxnar/fly-jumpshot](https://github.com/Kxnar/fly-jumpshot) | Navigation RL; jumpshot README is one line (“ts fly ballin”). |
| [two35s/flybrain-pentest](https://github.com/two35s/flybrain-pentest) | Isolated-lab decision experiment. Not a public game, and not promoted here. Created 5 Oct. |
| [Pr1nted/Open-Fly-Doctrines](https://github.com/Pr1nted/Open-Fly-Doctrines) | Whole FlyWire as one country in a strategy game. Repo size is tiny next to the claim; not re-played. |
| [azuyaturing-creator/Automatic-2048-Based-on-the-Fruit-Fly-Brain](https://github.com/azuyaturing-creator/Automatic-2048-Based-on-the-Fruit-Fly-Brain) | **1,452**-neuron subgraph plus a learned readout. 20fly8 already covers 2048 with controls. |
| [shuhaibNC/neuroFly](https://github.com/ShuhaibNC/neuroFly) | 3D fly explorer. Pages **200**. Pulses with flight phases; not a new loop. |
| [OrneyKraken/fastfly](https://github.com/OrneyKraken/fastfly) / [Paradoxsmile/flybrain](https://github.com/Paradoxsmile/flybrain) / [yad-qasim/Fly-Brain-Lab](https://github.com/yad-qasim/Fly-Brain-Lab) | Graph analysis, cell-type GNN, BANC viewer (**188,508** cells). Viewers. |
| [bookseal/virtual-fly-brain](https://github.com/bookseal/virtual-fly-brain) | Classroom pages. [Pages](https://bookseal.github.io/virtual-fly-brain/) **200**. Lessons, not a connectome runtime. |
| [AUW160150/flybrain](https://github.com/AUW160150/flybrain) / [prove-ai/flybrain](https://github.com/prove-ai/flybrain) | Same seven-experiment portfolio. [Render](https://flybrain-q2h5.onrender.com/) **200**. Not opened past the README. |
| [jvermaa/jam-with-a-fly](https://github.com/jvermaa/jam-with-a-fly) / [kishanrajeev/AeroMind-Music-Player](https://github.com/kishanrajeev/AeroMind-Music-Player) / [MyWestLord/claude-skirt](https://github.com/MyWestLord/claude-skirt) | Beat playback; a mushroom-body music ranker; a bee ballerina. [claude-skirt Pages](https://mywestlord.github.io/claude-skirt/) **200**. |
| [snownmouse/cyber-fly](https://github.com/snownmouse/cyber-fly) / [glimmercharger/flycursor](https://github.com/glimmercharger/flycursor) | ESP32 body; mouse/keyboard via already-listed fly.ai. |
| [FarhanAhmed67/FLY-001](https://github.com/FarhanAhmed67/FLY-001) | Interactive nervous-system page. Advertised `fly001chat.duckdns.org` was not re-checked past the README. |
| [heyziq05/VirFly](https://github.com/heyziq05/VirFly) | Browser pet. Pages **200**. Short README. |
| [fruitflyworld/onefly](https://github.com/fruitflyworld/onefly) | Daily fly whose brain is **50 NAND gates**. [onefly-nu.vercel.app](https://onefly-nu.vercel.app) **200**. Metaphor. |
| [IffatIqbal/compass-rescue](https://github.com/IffatIqbal/compass-rescue) | **106**-neuron hemibrain heading circuit. Not MaleCNS / FlyWire whole brain. |
| [michelangeloromerochisco/fly-distill](https://github.com/michelangeloromerochisco/fly-distill) | Larval connectome as a frozen language-model substrate. Paper code. |
| [dean750/mushroom-body-dopamine-learning](https://github.com/dean750/mushroom-body-dopamine-learning) | Small mushroom-body teaching-signal note. Not a demo. |
| [OpenUploading/cnskit](https://github.com/OpenUploading/cnskit) / [Lulzx/molecular-compiler](https://github.com/Lulzx/molecular-compiler) | Training tooling. |
| [dsbaha/flybrain](https://github.com/dsbaha/flybrain) | WebGPU LIF “sized like” FlyWire, plus an arena. Not established as the measured graph from the opening. |

### Created before 3 Oct, still pushing, not in prior shards

Not folded. They missed earlier keyword windows or were still growing. Recorded so the next hunt does not treat them as new.

| Repo | Note |
|---|---|
| [Vortitron/HouseFly](https://github.com/Vortitron/HouseFly) | Home Assistant rate model, **4,724** neurons (hemibrain + FlyWire), PAM/PPL1, with written failures (compass does not integrate; escape has no real threshold). [housefly.vome.io](https://housefly.vome.io) **200**. Created **17 Sep**, pushed 14 Oct. |
| [JonnasFigueiredo/mosca-qa](https://github.com/JonnasFigueiredo/mosca-qa) | Full MaleCNS learns software-defect “odors.” Pre-registered; body arena does **not** find the first bug faster. Local. Created **25 Sep**. |
| [silascroe/melanogaster](https://github.com/silascroe/melanogaster) | Godot reactions on MaleCNS subsets. The headline count **211,577** is not the retained 166,700 graph; senses run separate subset copies. [fly.clankclub.site](https://fly.clankclub.site/) **200**. Created **28 Sep**. |
| [uguryildirim24/flyonenomics](https://github.com/uguryildirim24/flyonenomics) | Dopamine perturbation checks; README says findings are non-significant after correction. Created 27 Sep, pushed 9 Oct. |

## Thin, metaphor, stub, or mislabeled

| Repo | Why it looks thin |
|---|---|
| [arthen97/drawfly](https://github.com/arthen97/drawfly) | README: “MaleCNS / connectome code is not part of this project.” The description overclaims. |
| [fruitflyworld/onefly](https://github.com/fruitflyworld/onefly) | 50 NAND gates and a date function. |
| [Kxnar/fly-jumpshot](https://github.com/Kxnar/fly-jumpshot) | README is “ts fly ballin”. |
| [RandomGuy-nobody/fly-brain-api](https://github.com/RandomGuy-nobody/fly-brain-api) | 3 KB. Description says it is not a game. |
| [VISMAY2005/FlyBrain-Dino1.1-Dino-Game--RL-NN-](https://github.com/VISMAY2005/FlyBrain-Dino1.1-Dino-Game--RL-NN-) | Another Dino hybrid. Fly Dino already covers the game. Size ~21 KB. |
| [valleebo/FlyBrainLab](https://github.com/valleebo/FlyBrainLab) / [valleebo/FlyBrainLabOwn](https://github.com/valleebo/FlyBrainLabOwn) | Mirror of FlyBrainLab. Viewer, not a new demo. |
| [clawclawson-ctrl/jumper-local-sim](https://github.com/clawclawson-ctrl/jumper-local-sim) | Local Jumper apps. README: vision brains are concepts. |
| [MyWestLord/claude-skirt](https://github.com/MyWestLord/claude-skirt) | Page-load ballerina. Connectome claim is the costume. |
| Empty / no-README / course-dump cluster | `Kyoto-Designs/Fly-brain`, `CharlieZhang1999/flybrain`, `Eltan1n/flybrain`, `yoyore1/flybrain`, `sutharson-k/MALECNS`, `wohazu676-eng/flybrain-project`, `izzatjonibrakhimov-bot/fly-brain-lab`, `AmitAgrawal-AI/AmitAgrawal-AI`, and other 0–few KB description-only repos in the 192. |

## Search notes

- Cobanov commits since 2 Oct that add entries: `516c40e` (fly-cartpole, already listed), `5f0ef45` (Doodle Fly and 20fly8, already listed), `35a2841` (fault-lines, price-of-thought), `6a2954d` (Fly-NAF v0.3 wording), `bb3910c` (Barfly), `88d1f95` (Katamari), `29f5b2e` (FlyGateDemo), `4209692` (ENSOphilia).
- `nftechie` public fly repos were not re-listed. A web catalog’s 15 Oct note still has DOOMFLY’s last default-branch commit in September.
- Live HTTP GET on 16 Oct 2026: pinball Pages, fly.aryawijaya.com, Zenodo 10.5281/zenodo.23156035, fly-arithmetic Pages, fly.warpfield.me, connectocopter Pages, FlyBrainGame Pages, both bike Vercel URLs, katamari Vercel, housefly.vome.io, fly.clankclub.site, Flomb, fly-ears, fly-plays-nes, mpvasilis Pages, VirFly, koodio.fi artwork, claude-skirt, bookseal Pages, ArcadiaE Pages, flybrain Render, jolab.ai/adfly, biobug-rescue, neuroFly, flywire-pong, fly-draw, price-of-thought, fault-lines, onefly, pokerwithafly, BioGrid releases page, Fly-NAF YouTube, gexhaw chessfly Pages — **200**. `znatgost.github.io/chessfly/` and `znatgost.github.io/fly67/` — **404**. Preprints.org manuscript `202610.1232` — **403** to this client, so it is not cited.
- X/Twitter was not used for new status IDs. No `x.com/*/status/` URLs appeared in the fetched READMEs. See [`x-latest-cool-2026-10-16.md`](x-latest-cool-2026-10-16.md).
- Star counts are not copied into the README. FlyAim’s star field was absent from the search payload; it is omitted, not guessed.

*End of shard. Folded this pass: Connectocopter, Flight-test the fly, Synaptera, BioGrid, FlyAim, fly-tennis, 3D Pinball, fly-arithmetic, ENSOphilia, FlyGateDemo, Barfly, Katamari, Lazirko auditory VST, StepMania, plus the ChessFly URL move and the Fly-NAF night-3 line. Left in this file: another whole-brain browser, another Flappy / Pong / poker / Dino / desktop pet, crab and driving overlaps, language-model couplings, analysis sites, pre-3 Oct misses (HouseFly, Mosca QA, melanogaster), and metaphor or stub repos.*
