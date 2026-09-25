# Awesome Fruit Fly [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Interactive demos, games, trading loops, art, and dopamine / RL experiments that run a reconstructed *Drosophila* (fruit fly) connectome — especially **MaleCNS v1.0** (Sep 2026) and **FlyWire**.

The September 2026 MaleCNS release (~166,700 neurons spanning brain, optic lobes, and ventral nerve cord) set off a wave of community “fly brain” simulations: Doom, Mario 64, Beat Saber, Minecraft, BTC trading, browser pets, and closed-loop locomotion. This list is a curated index of those **applications**, not a catalogue of every dataset or analysis library.

For datasets, viewers, and analysis tools see the companion list **[awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome)**. We still keep a short [Datasets & tools](#datasets--tools) section so demos have context. Raw search notes from the Sep 2026 shards live in [`discoveries/`](discoveries/).

**These are wiring-diagram simulations.** Published connectomes give who connects to whom. Sensory maps, leaky-integrate-and-fire dynamics, dopamine pulses, and button bindings are almost always engineered. A listed project is not a living fly, and “learning” in a README is not proof of biological memory unless the authors publish controls that hold up.

Items whose point is a reward loop are collected under [Reinforcement & dopamine](#reinforcement--dopamine). Elsewhere, **Dopamine/RL** in the description means the same thing: identified PAM / PPL cells, a mushroom-body three-factor rule, or a trained readout / PPO policy on connectome topology.

Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Reinforcement & dopamine](#reinforcement--dopamine)
- [Games & interactive](#games--interactive)
- [Trading & markets](#trading--markets)
- [Art & media](#art--media)
- [Embodied / scientific RL](#embodied--scientific-rl)
- [Datasets & tools](#datasets--tools)
- [Related lists](#related-lists)
- [Articles & threads](#articles--threads)
- [Contributing](#contributing)
- [License](#license)

## Reinforcement & dopamine

Experiments that inject reward or aversion into identified dopamine cells (PAM11 appetitive, PPL101 aversive, mushroom-body three-factor rules) or treat the connectome as a plastic RL substrate.

- [DOOMFLY](https://github.com/nftechie/doomfly) - MaleCNS v1.0 (166,700 neurons) plays a live Doom arena; frames drive R1–R6 / R8 inputs, damage pulses two PPL101 cells, and an experimental rule updates KC→MBON11 synapses. Announced by [@nftechie_](https://x.com/nftechie_) on 6 Sep 2026. Open source; the repo is explicit that learned survival has not been demonstrated. [ [live spectator](https://fly-brain-doom.awormuth.chatgpt.site/) ]
- [Faiku](https://github.com/xyzzyapps/faiku) - MaleCNS mushroom-body RL writes Japanese/English haiku as a fly-font ink trail, with PAM / PPL1 dopamine on glyph match.
- [Fly / Wirehead](https://github.com/mattyhempstead/fly-wirehead) - Endless insect Shorts on a phone in front of the same retained MaleCNS graph. Every accepted frame injects current into 15 PAM11 cells — artificial “wirehead” dopamine, inspired by Stonkfly. Preference and addiction are not established.
- [fly-brain-poker](https://github.com/ItayParienty/fly-brain-poker) - FlyWire mushroom-body LIF sat at Texas Hold’em. Innate wiring can discriminate hands; outcome-driven dopamine did **not** teach cards. Honest negative result.
- [fly-mario](https://github.com/ksanjeev284/fly-mario) - Full MaleCNS v1.0 playing NES Super Mario Bros with CUDA LIF dynamics, dopaminergic learning, and a live 3D web dashboard.
- [Fly School](https://github.com/JaronKBragg7337/fly-school) - MaleCNS mushroom-body depression (PAM / PPL1 onto KC→MBON) drilled on Morse timing during “school hours.” Held-out `.-` barely moves; `-.` stays 0 — an honest mostly-null. [ [live](https://www.heartbeatobservatory.com/school/) ]
- [FlySoul](https://github.com/heyobi/flysoul) - MaleCNS LIF vs Iudex Gundyr in SoulsGym. Damage pulses PPL101 (LTD); a boss hit pulses PAM (LTP). The biological loop wins once in ~600 fights and does not learn to; a synthetic readout on the same senses wins about one in three. [ [write-up](https://heyobi.github.io/flysoul/) ]
- [FlyScroll](https://github.com/ranagwho/Fruitfly-Doomscroller) - MaleCNS “doomscroller”: short-form video into R1–R8; the feed advances when novelty-compartment KC→MBON synapses habituate. Habituation / prediction-error, not a PAM11 profit pulse.
- [FlyTris](https://github.com/rothilion26/flytris) - MaleCNS mushroom body (KC→MBON, PAM / PPL1) learns Tetris as odor-gradient navigation with the fly’s own dopamine-gated plasticity rule.
- [flywire-playground](https://github.com/hills-dong/flywire-playground) - FlyWire sub-circuits as spiking networks that play games using the fly’s own dopamine update rule.
- [Fruit fly utopia](https://github.com/ML-Chen/fruit-fly-utopia) - MaleCNS soma cloud plus a reduced PAM / PPL1 / PER rate model. Worlds include sugar, cocaine, doomscroll, and a printed “utopia” welfare mix that is **not** “max PAM”; cocaine loses. Wanting / reinforcement, not a trained policy.
- [Kick the Fly](https://github.com/legendarylolo318-cloud/kick-the-fly) - Kick-the-buddy toy on a live 166,700-neuron MaleCNS. Tools hit real sensory cells; sugar lights PAM dopamine and heals. Reward is the sugar pulse, not a trained game policy.
- [Pokefly](https://github.com/Reldnahc/pokefly) - Pixel-driven Pokémon Red (PyBoy) on MaleCNS via fly.ai: fixed spatial adapter, internal synaptic plasticity kept across whole-game attempts, and a live neural dashboard. Reaching the battle is part of the task. Distinct from `blackicon-eth/fly-plays-games` (frozen weights).
- [Ruby Project](https://github.com/wavendis/ruby-project) - NeoForge Minecraft 1.21.1 mod that gives a mob a FlyWire-derived LIF brain (photoreceptors, descending neurons, Kenyon cells, MBON, DAN) with dopamine-gated KC→MBON learning. Real wiring plus a few synthetic Minecraft entry neurons; the author documents what is fabricated.
- [Scrollfly](https://github.com/sebastian-stapf/scrollfly) - MaleCNS watches Shorts, predicts watch time, “likes,” and scrolls. Frozen graph + trained readout; does not beat a constant baseline. Credits Stonkfly and Fly / Wirehead. [ [demo](https://sebastian-stapf.github.io/scrollfly/) ]
- [Stonkfly](https://github.com/nftechie/stonkfly) - BTC-USDC candlestick pixels into MaleCNS; a fixed readout proposes buy / sell / hold via Coinbase AgentKit. Portfolio gains pulse 15 PAM11 cells, losses pulse two PPL101 cells. Profitable learning has not been demonstrated. X: [@nftechie_](https://x.com/nftechie_/status/2098012107652391357). [ [stonkfly.com](https://stonkfly.com) · [live dashboard](https://stonkfly-three.vercel.app/) ]
- [StonkFlyRH](https://github.com/CryptoGatsu/StonkFlyRH) - Stonkfly fork on Robinhood Chain memecoins. Gains → 15 PAM11, losses → 2 PPL101; a rug it bought doubles the aversive pulse. Advertised X: [@StonkFlyRH](https://x.com/StonkFlyRH).
- [stonkfly-lab](https://github.com/paappraiser/stonkfly-lab) - Smaller mushroom-body trading lab with odor inputs, delayed dopamine, two-fly agreement, paper BTC, and a dashboard. Inspired by Stonkfly; not the full MaleCNS graph.
- [The Fly’s Table](https://github.com/WilliamJones/fly-blackjack) - Heads-up blackjack against a measured MaleCNS mushroom body (682 PN, 1,200 KC, 97 MBON, 332 PAM / PPL1). 30k solo hands move winrate from −45% to −16% with 52% basic-strategy agreement; cutting dopamine wipes the gain. Circuit subset. [ [play](https://fly-blackjack.vercel.app/) ]

## Games & interactive

Connectome activity mapped onto game controls or a playable / inspectable agent. Prefer repos and live pages; X-only clips are marked.

- [Aimbug](https://github.com/slickdomi/aimbug) - Browser FPS: full MaleCNS steers via DNa02 / DNp53 and fires one shot per pIP10 courtship-song bout while LC10 “sight” is open. No trained readout. [ [play](https://aimbug.domi.zip/) ]
- [Beat Saber (Lyra)](https://x.com/_lyraaaa_/status/2097527368919470162) - **X-only.** [@\_lyraaaa\_](https://x.com/_lyraaaa_) (“the fly brain can play beat saber,” 8 Sep 2026). Author notes motor patterns were overfit to a replay with teacher-forced input while visual reactivity / RL training continued — not fully reactive play from pixels alone.
- [Beat the Fly](https://github.com/saintiron82/beat-the-fly) - Jigsaw race vs a 7,858-cell MaleCNS photoreceptor→L1 graph in one tab. Shuffle-wiring solves as well; the fly visual system is a motion system, not a jigsaw solver. [ [play](https://saintiron82.github.io/beat-the-fly/) ]
- [Brain Rot](https://github.com/Franz23/brainrot) - FlyWire v783 rates a LinkedIn post: engagement bait → sugar GRN Hz → Shiu whole-brain lookup → MN9 verdict. The inspectable “write LinkedIn posts” 404 Media named without a URL. [ [rate](https://brainrotposts.com) ]
- [CyberFly](https://github.com/PtPavloTkachenko/fly-brain-spectacles) - Hologram flies on Snap Spectacles; each runs full MaleCNS on a Mac Metal GPU while the glasses stream room senses. [ [blog](https://pavlo-stijn.dev/blog/posts/a-real-fly-brain-on-spectacles.html) ]
- [DesktopFly](https://github.com/DenisSergeevitch/desktop-fly) - 3D fly on a macOS / Electron desktop. FlyWire looming / escape plus a MaleCNS motor extract; cursor looming can trigger Giant Fiber takeoff.
- [FlyCNS Desktop Pet](https://github.com/Teafox113/FlyCNS-Desktop-Pet) - Windows always-on-top 2D pet: 3,335 R1–R6 plus an engineering-cruise vs “pure BCI” control. MaleCNS-derived; neuromod / sugar telemetry are optional and documented as unverified.
- [Flyguy](https://github.com/Cem-Bas/flyguy) - macOS Tamagotchi: ScreenCaptureKit vision through 165,122 / 10.5M MaleCNS plus a live soma cloud. Gentle hue/app affinities, not a PAM11 loop. Distinct from DesktopFly.
- [Fly Terrarium](https://github.com/jonathancomergit-ai/fly-terrarium) - Local GPU LIF of 165,122 / 23.8M MaleCNS in a tank: sugar, bitter, fan, courtship song, and a swat, plus a flyvis webcam optic-lobe page. Honesty table (cartoon body vs real wiring); lab bench can silence the giant fiber. No public host.
- [Fly64 / Super Mario 64](https://github.com/ornata/fly) - Jessica Paquette ([@barrelshifter](https://x.com/barrelshifter)) hooks MaleCNS to a decompiled SM64 build: six hidden cameras, LIF dynamics, DNg100 / DNa02 / DNp01 readouts. No training or reward in the published loop; Mario can walk into a wall and stay there. [ [announcement](https://x.com/barrelshifter/status/2097004115826200898) ]
- [Fly Brain (Boxhead)](https://github.com/FalinX/fly-brain) - Frozen MaleCNS (166,700 / 25.6M) plays Boxhead-style zombie survival. v13 kiter-legs + connectome eyes: ~197 s median survival vs a no-brain kiter ~216 s (statistically level). Local Python; no public host.
- [Fly Brain Minecraft](https://github.com/blendi-remade/fly-brain-minecraft) - Fabric 1.21.1 mod: each fly mob runs a MaleCNS LIF brain with a live HUD. Distinct from NeuroCraft (runnable mod vs landing page) and from [Ruby Project](https://github.com/wavendis/ruby-project) (FlyWire + dopamine).
- [Fly-chan](https://github.com/fkfkfk0406/fly-chan) - FlyWire v783 (138,639 LIF) as a 3D tamagotchi girl / anatomical fly. Relationship gauges are authored; DNs/MNs pick feed / startle / groom. ~100 MB first load. [ [play](https://fkfkfk0406.github.io/fly-chan/) ]
- [FlyBreak](https://github.com/Shriya-sai/FlyBreak) - 30-second neural heist: cut or jam MaleCNS nodes so LC4 cannot reach DNg108 while sparing protected DNa13. The fly reroutes every four seconds. [ [play](https://flybreak-neural-heist.shriyasai8.chatgpt.site) ]
- [fly_chess](https://github.com/martialsystems/fly_chess) - Chess via a connectome LIF ply plus search. The README reports that one LIF ply on the real graph is silent and `wiring_helped` is false — an honest negative result.
- [fly-chess (WASM)](https://github.com/tolatolatop/fly-chess) - Separate FlyWire LIF chess experiment in the browser (Rust / WASM) with spike traces and causal controls. [ [demo](https://tolatolatop.github.io/fly-chess/) ]
- [Fly Dino](https://github.com/cobanov/flyjump) - **RL readout.** Chromium Dino jumped by an 80-cell MaleCNS circuit plus a CEM-trained 243-parameter readout (99/100 held-out courses in the published checkpoint). Wiring is frozen. [ [play](https://flydino.cobanov.dev/) ]
- [Fly Falafel King](https://github.com/Eli-HarShefer/fly-brain-falafel) - FlyWire subgraph (4,798 LIF / 116,960 synapses) plays an original Falafel King: LC10a→AOTU→DNa02 locks onto trays; LPLC2→DNp01 slaps flies off the food. Order-reading is authored game logic; the fly does not learn. Circuit subset. [ [play](https://eli-harshefer.github.io/fly-brain-falafel/) ]
- [FlyDrones](https://github.com/SpikeCalls/FlyDrones) - Webcam / keyboard optic-flow illusions (open palm climb, fist hold, rush-the-camera giant-fiber escape) steer a 3D drone via DNg02 / DNp01. Browser demo is MiniFly (~850 cells) plus a safety governor, not the full 166k graph. [ [play](https://spikecalls.github.io/FlyDrones/) ]
- [Fly Marksman](https://github.com/webergithub/fruitfly-lab) - 3,963-neuron FlyWire LC10a→AOTU→DNa02 pursuit circuit aims in the browser with no training. Same circuit on ViZDoom *defend_the_center*: real wiring 10.2 kills/episode vs a degree-preserving scramble 0.7. Bearing→LC10a drive is engineered. [ [play](https://opcstudio.cc/fly-aim/) ]
- [Fly-NAF](https://github.com/ArtyMend07/Fly-NAF) - Whole FlyWire v783 (138,639 LIF, frozen weights) plays Five Nights at Freddy's 1. DNp01 slams doors; DNp09 raises the tablet; camera-up blinds the fly via GABAergic inhibitors. Best published run: 4 AM on night 2. Windows only.
- [fly-swing](https://github.com/JHC56/fly-swing) - MuJoCo fly web-swings a random obstacle course. Escape is LC4/LPLC2 → DNp01 Giant Fiber (no dodge code); the full 165,122-neuron graph is a live HUD. A kNN threat memory picks web direction (20/20 published courses).
- [Fly Tic-Tac-Toe](https://github.com/pikabell/fly-tictactoe) - **RL readout.** 98-cell MaleCNS circuit + a 425-parameter readout in the browser, with silence / rewire controls. Imitation of minimax uses the circuit; a degree-preserving rewired graph scores about the same — topology is not the skill. [ [play](https://pikabell.github.io/fly-tictactoe/) ]
- [fly-escape](https://github.com/dzhng/fly-escape) - 3D browser house-escape: place furniture, release flies whose MaleCNS LIF circuits drive movement. [ [play](https://fly-escape.vercel.app/) ]
- [fly-explorer](https://github.com/brandoncho369/fly-explorer) - FlyWire (~139k neurons) as a live browser spiking network. Press sugar, watch a proboscis motor neuron fire. Companion benchmark: [flybench](#datasets--tools). [ [demo](https://www.fly-bench.com) ]
- [flywire-fly-lab](https://github.com/suifei/flywire-fly-lab) - FlyWire v783 (138,639 / 15.1M) on a 16 GB laptop with **17,628** virtual knockouts; the browser game is 4,599 cells. κ 0.59 sugar / 0.87 water / 0.91 grooming vs opto. [ [play](https://suifei.github.io/flywire-fly-lab/game.html) ]
- [MaleCNS Asteroids](https://github.com/dohun1214/malecns-asteroids) - Full 166,700-neuron LIF plays Atari Asteroids. Escape (LC4→DNp02/11) vs pursuit (LC10a→DNa02) readouts; silencing two DNp11 cells flips steering while a random 2,000-cell lesion does not. Local CUDA; no public host.
- [fly-flappy-bird](https://github.com/arjunkshah12345-hash/fly-flappy-bird) - MaleCNS wired to Flappy Bird with engineered adapters and recorded gameplay.
- [Hand-loom Giant Fiber](https://github.com/Euraxluo/fly-brain-drone) - Browser 5,145-neuron MaleCNS LPLC2/LC4→DNp01 looming loop: drag toward the fly; slow hands miss the spike and swat it. Not the full 166k graph. Distinct from already-listed [Swat](https://github.com/hrook1/Swat) (LC16→MDN) and from `abbosaliboev/fly-brain-drone` (MuJoCo apple-finding WIP). [ [play](https://euraxluo.github.io/fly-brain-drone/) ]
- [fly-hero](https://github.com/actuallyrizzn/fly-hero) - Frozen fly-connectome reservoir that plays Clone Hero by seeing the highway.
- [Fly Poker](https://github.com/HappyAny/fly-poker) - Two-player 13-card shedding game vs a full-connectome fly sim in the browser. [ [play](https://fly-poker.piphipsi.com/) ]
- [fly-brain-bench](https://github.com/RaphaelSR/fly-brain-bench) - Browser LIF over FlyWire (138,639 neurons, ~2.7M connections) at 60 fps with no extra dependencies.
- [FlyBrain (boss)](https://github.com/Jhongdlp/FlyBrain) - Video-game boss driven by MaleCNS (~165k neurons): Rust engine, vectorized Python VecEnv, Three.js visualizer. Not a DRL policy.
- [FlyBrain-HalfLife](https://github.com/Yusuftmle/FlyBrain-HalfLife) - MaleCNS / FlyWire agent playing Half-Life via LIF dynamics, a 60×60 retina, and DirectInput.
- [flybrain.app](https://flybrain.app) - Browser FlyWire FAFB v783 simulation (139,255 LIF neurons) forked from worm-sim. [ [repo](https://github.com/snedea/flybrain) ]
- [flybrain-intransitive](https://github.com/charbelkassab/flybrain-intransitive) - Full MaleCNS LIF plays rock-paper-scissors chess with no training: captures as small-object chase, threats as looming / giant-fiber escape. Scrambled wiring collapses; a learned descending readout played *worse* than the biological approach/escape pair. Feature→neuron map is still hand-designed.
- [flybrain-snake](https://github.com/charbelkassab/flybrain-snake) - Live MaleCNS (~165k neurons) playing Snake, with the control mapping documented instead of hidden.
- [flydoom](https://github.com/mutkuoz/flydoom) - Alternate Doom fly on Princeton’s FAFB-v783 (FlyWire) dataset rather than MaleCNS.
- [FLYBRAIN-BAD_APPLE_X_DOOM](https://github.com/fazchile17/FLYBRAIN-BAD_APPLE_X_DOOM) - Local 3D FlyWire v783 viewer (139,255 neurons) with optional Bad Apple!! and Doom overlays on the neurons.
- [flyputer](https://github.com/migkapa/flyputer) - Local Gemma agent queries FlyWire, runs small LIF subcircuits, and includes a playable Giant Fiber swatter game against the real LPLC2/LC4 escape reflex.
- [Fruit Fly Plays Fruit Ninja](https://github.com/hcsolakoglu/fruit-fly-plays-fruit-ninja) - 4,386-neuron MaleCNS visuo-motor circuit slices fruit via a fitted descending readout. Local 3D “fly at a PC” spectator plus measured / rewired / cut / blinded controls. Not whole-brain; connectome weights stay frozen.
- [Fruit Fly Simulation (Xenova)](https://huggingface.co/spaces/Xenova/fruit-fly-simulation) - Joshua Lochner’s WebGPU MaleCNS demo: paint / stimulate 166,700 neurons and watch an articulated Three.js fly. Connectivity is biological; movements are programmed. Verified Hugging Face Space (not a GitHub repo).
- [NANDFLY](https://github.com/wetware-labs/nandfly) - Giant Fiber escape compiled to 661 NAND/LATCH gates on BNB Chain. The site lets you swat the netlist; 98.9% jump agreement vs a LIF reference on all 4,096 input patterns. Top-12 of 311 LC4/LPLC2 cells, not the full fan-in. [ [swat](https://wetware-labs.github.io/nandfly/) ]
- [Model Kombat](https://github.com/lavallee/mk-jev-fly-brain) - 12,000-neuron MaleCNS subgraph (LPLC2/LC4/LC10a/P1 → DNp09/MDN/TTMn) fights a language model in mk.js. A dopamine-like rule updates during the fight; controls say what each side contributes. Not whole-CNS. [ [play](https://lavallee.github.io/mk-jev-fly-brain/) ]
- [NeuroCraft Fly](https://github.com/evnsnclr/neurocraft-fly-public) - Evan Sinclair Smith’s Minecraft MaleCNS fly (166,700 neurons). In-game events (food, light, nearby creatures, attacks) drive the network; activity selects scripted body programs. Public landing page and recorded demo; the Fabric mod itself was still being prepared as of the Sep 2026 landing-page README.
- [Optic-lobe steering](https://github.com/AbijahKaj/fruit-fly-brain-research) - MaleCNS optic lobe (65.8k neurons) as a WebGPU rate model: the fly renders 1,771 column directions and the wiring becomes wing commands. [ [browser demo](https://fruit-fly-research.vercel.app/) ]
- [PersonConnectome](https://github.com/TailsProwerWorks/PersonConnectome) - People Playground Human driven by a thresholded MaleCNS-derived LIF graph. Game senses (injury, looming, audio, liquids as telemetry) map to a frozen decoder; it does not learn from staying alive.
- [pianist-fly](https://github.com/Noir-infini/pianist-fly) - Full MaleCNS LIF (166,700 / 25.58M) hunts a sugar plume over a piano and strikes keys with Damped Least Squares IK on a MuJoCo body. Frozen graph; local only.
- [Same Smell](https://github.com/anzal1/samesmell) - One cVA puff into MaleCNS (he) and FlyWire (she) at once: he lunges, she pauses. Extra modes play Pong between the two brains and let both courtship circuits swipe dating profiles. LIF timing is stretched; bodies are puppets on real descending output. [ [play](https://anzal1.github.io/samesmell/) ]
- [Swat](https://github.com/hrook1/Swat) - Browser arcade: swat a fly whose evasive turns are influenced by a 6,000-neuron MaleCNS LC16→MDN retreat circuit. [ [play](https://fruitfly-tiny-brain.vercel.app/) ]

### X-only or thinly documented game clips

- [Bad Apple!!](https://github.com/kevinlinxc/badapple-fly) - Kevin Lin ([@linguinelabs](https://x.com/linguinelabs) in news write-ups) pipes Bad Apple!! through MaleCNS v1.0 and shows a NeuroMechFly body. Open-source; LIF parameters and movement programs are illustrative. Coverage also used the X handle; the repo is the verified source.
- [Deadlock](https://knowyourmeme.com/videos/440448-fruit-fly-brain-simulations) - **X-only.** [@jetsetworm](https://x.com/jetsetworm) (11 Sep 2026): “the fly can play deadlock” with YOLOv5 + video pretraining, “most success on Graves.” No numeric status ID archived here; no public repo. YOLO is a vision front-end, not a fly retina.
- [Fly social network](https://x.com/nftechie_/status/2098371978612924425) - [@nftechie_](https://x.com/nftechie_) (13 Sep 2026): three male and three female connectomes with separate states; presenting flies stimulates sensory neurons and activity decides whether another fly responds (“TheFlybook”). No public repo was found at write-up.
- [Mario 64 follow-ups](https://x.com/barrelshifter) - After the [7 Sep 2026 clip](https://x.com/barrelshifter/status/2097004115826200898), [@barrelshifter](https://x.com/barrelshifter) posted further SM64 training experiments (including a “teaching to Kill” follow-up circulated in community notes). Those later clips were not independently archived with a verified status ID here.
- [Parallel parking](https://x.com/alright_mark/status/2098085928489177142) - **X-only.** [@alright_mark](https://x.com/alright_mark) (10 Sep 2026): “the fly has completed* the ultimate test: parallel parking.” Status ID from public unroll/news embeds. No first-party repo tied to this handle; not the same as [Flyhard](https://github.com/MarkUnthank/flyhard).
- [Super Smash Bros / Rubik’s cube](https://x.com/nickwalton00/status/2098537903110652087) - **X-only.** [@nickwalton00](https://x.com/nickwalton00) (13 Sep 2026): Smash “wins against the bots 2/3 matches” and a [Rubik’s](https://x.com/nickwalton00/status/2098301053372621070) follow-up. Status IDs from unrollnow. No public repo; not the same as [lntegrals/flycube-public](https://github.com/lntegrals/flycube-public). Methods not inspectable.

## Trading & markets

Same caveat as the dopamine section: a chart-in / trade-out loop is an interface, not a proven alpha. **Dopamine/RL** tags mark PAM / PPL pulses or KC→MBON updates.

- [The Dartboard](https://flybrain.online/dartboard) - **Dopamine/RL.** fruitflydev 165,122-neuron MaleCNS walks a dark room of nine identical stock cards (smell = ticker; DNp09 ≥ 200 Hz while slow commits). Paper only — no GitHub in the 22 Sep clip. Live page: learning ±0.04 vs look noise, **no claimed edge**; Fly vs Random vs Hold. Does not name PAM11 / PPL101. X: [@fruitflydev](https://x.com/fruitflydev/status/2102092842537734496).
- [the_buzz](https://github.com/TropiFloAI/the_buzz) - Bitcoin prediction bake-off: random forest vs a fruit-fly-connectome network.
- [flycoinrh](https://github.com/fruitflydev/flycoinrh) - MaleCNS-scale connectome (165,122 neurons) used to launch tokens on Robinhood Chain. Meme-token experiment; treat as entertainment, not a model organism. X: [@fruitflydev](https://x.com/fruitflydev/status/2100964182028099993) (Flyonardo airdrop, 18 Sep) · [stock-room trader](https://x.com/fruitflydev/status/2101298482002927874) (19 Sep).
- [flybrain-female](https://github.com/opifor/flybrain-female) - FlyWire FAFB v783 “sister” token experiment on Robinhood Chain. Launch-form / cursor demo; no P&L dopamine loop in this README. [ [site](https://femaleflybrain.com) ]
- [flywire-live](https://github.com/iyz2013/flywire-live) - Robinhood Chain *spectator*: other people’s swaps become sensory current in a MaleCNS LIF. The fly never signs a tx. Advertised site `flywire.live` failed TLS / 404 at re-check; use the repo.
- [fruit-fly-fund](https://github.com/armanbabazadeh6/fruit-fly-fund) - Two MaleCNS v1.0 flies race the same paper market; one applies experimental memory updates and one does not. No real orders. [ [demo](https://armanbabazadeh6.github.io/fruit-fly-fund/) ]
- [fruitfly.trade](https://github.com/fruitflytrader/fruitfly.trade) - Simulated connectome whose spikes choose memecoin trades. [ [site](https://fruitfly.trade) ]
- [FlyTV](https://www.tradingview.com/script/nmnHkA02-FlyTV-a-real-fruit-fly-connectome-trading-on-your-chart/) - **Dopamine/RL.** TradingView Pine: 995-neuron MaleCNS distillation. Looming (LC4 / LPLC2 → DNp01) flattens a selloff; realized P&L drives PAM / PPL1 onto KC→MBON. Includes a shuffled-weight control. Does not beat buy-and-hold after fees.
- [Gregor](https://github.com/PunzRH/gregor) - “A real fruit-fly connectome kept alive by its coin.” Separate from Richy.
- [FlyDegen](https://flydegen.fun/docs) - **Offline.** FlyWire FAFB v783 LIF that maps tape to sugar / bitter / antennal rates (MN9 = BUY). Docs say no RL / P&L fine-tune. Host returned HTTP 402 (`DEPLOYMENT_DISABLED`) at re-check; no public GitHub found.
- [OpenFly](https://github.com/marketcalls/openfly) - **Dopamine/RL (learning arm).** MaleCNS v1.0 paper-trades an intraday NIFTY straddle through OpenAlgo. Default path is a fitted decoder; the learning arm pulses 15 PAM11 / 2 PPL101. No profitable edge claimed.
- [Polyfly](https://polyfly.higgsfield.app/) - Live neural trader on one Polymarket Fed-funds contract. MaleCNS-scale model; marked P&L becomes “reward or aversive stimulation.” Does not name PAM11 / PPL101. No public GitHub found.
- [Richy The Fly](https://github.com/PunzRH/richythefly) - **Dopamine/RL.** Full MaleCNS v1.0 trades Pons coins on Robinhood Chain from its own wallet; Δequity pulses 15 PAM11 or 2 PPL101. Advertised site returned 404 at re-check; repo + [@RichyTheFly](https://x.com/RichyTheFly) remain the pointers. Profitable learning not claimed.
- [Stonkfly](https://github.com/nftechie/stonkfly) - See [Reinforcement & dopamine](#reinforcement--dopamine). The canonical dopamine-gated trading demo.
- [StonkFlyRH](https://github.com/CryptoGatsu/StonkFlyRH) - See [Reinforcement & dopamine](#reinforcement--dopamine). Robinhood Chain fork.
- [TraderFly](https://github.com/SotoAlt/traderfly-brain) - Male CNS LIF maps sugar GRNs → BUY, looming LC4 / LPLC2 → ESCAPE sell. No PAM11 / PPL101 P&L pulse. [ [live](https://traderfly.xyz) ]

## Art & media

- [9 to Fly](https://github.com/MarlonSteiner/fruitfly-9tofly) - 809-neuron DNp01 Giant Fiber slice at a sales desk: the phone rings, the fly leaves the chair. Looming vs receding vs flat inputs are 1.00× — selectivity is upstream of this slice. Movement is keyframed. [ [demo](https://marlonsteiner.github.io/fruitfly-9tofly/) ]
- [DJ Drosophila](https://github.com/MRsagi/dj-drosophila) - MaleCNS-inspired fly DJ and shared 24/7 CC0 live radio.
- [The Drosophila Critic](https://github.com/Synthetic-Humanities-Lab/drosophila-critic) - Spoken Blake *The Fly* into Johnston’s organ cells on a frozen MaleCNS; the published reading never sees the poem text. [ [Blake edition](https://synthetic-humanities-lab.github.io/drosophila-critic/) ]
- [Faiku](https://github.com/xyzzyapps/faiku) - See [Reinforcement & dopamine](#reinforcement--dopamine). Haiku as a dopamine-gated ink trail.
- [FLM](https://github.com/nftechie/flm) - **Trained readout, not dopamine.** Frozen Liquid AI 1.2B LM whose logits are nudged by a 278k-parameter adapter on the full retained MaleCNS graph. Language comes from the backbone; a no-graph control does slightly better. [ [chat](https://fly-language-model.vercel.app/) · [paper](https://artificialscientific.com/papers/flies-are-all-you-need) ]
- [Fly Lab](https://github.com/Apolotary/fly-lab) - **RL readout.** Ableton Live: fly motor-circuit activity → a small trainable musical “More / Less like this” readout. Wiring frozen.
- [Fly OCR](https://github.com/jerryjliu/fly_ocr) - Frozen MaleCNS as a printed-character reservoir; a 266k-parameter decoder scores 87.6% on a 1,632-glyph benchmark and 5.7% CER on selected PDF lines. A 3° tilt breaks it. Local replay viewer; not a claim that flies read.
- [The Fly Hears](https://github.com/rahilmavani/fly-hears) - Spoken digits through a 30k-cell MaleCNS auditory slice; a logistic reader scores 70.0% vs scrambled wiring 69.7%. Local demo; wiring frozen.
- [FLYcasso](https://github.com/gustavz/FLYcasso) - Connectome-conditioned image diffusion and simulated fly painting on MaleCNS wiring.
- [flyboard](https://github.com/sukoji/flyboard) - Music chart voted by a GPU simulation of MaleCNS v1.0 (~165k neurons) after 84 songs. [ [viewer](https://sukoji.github.io/flyboard/) ]
- [Fruitflysynth](https://github.com/bennjordan/fruitflysynth) - In-browser MANC thoracic courtship circuit plus physical-model DSP: drag the female closer and pulse song becomes sine song. Not MaleCNS whole-CNS. [ [play](https://bennjordan.github.io/fruitflysynth/) ]
- [Fruit fly utopia](https://github.com/ML-Chen/fruit-fly-utopia) - See [Reinforcement & dopamine](#reinforcement--dopamine). Sugar / cocaine / doomscroll / utopia as motor programs on a PAM–PPL1 cartoon.
- [FLYWATT](https://github.com/flywatt-live/watt-the-fly) - Browser MaleCNS subset (38,178 neurons, 5.1M synapses); every spike is converted to power and lights a bulb (~6.5 µW).
- [Infinite Sugar](https://github.com/cnqso/infinite-sugar) - Browser FlyWire terrarium with continuous sweet-GRN stimulation — a wirehead / “pleasant life” metaphor. No learning, so it cannot get bored. Displayed PAM rates are telemetry, not a trading reward. [ [demo](https://infinitesugar.cnqso.com) ]
- [Муха смотрит телевизор](https://github.com/georgesher/fly24-public) - Full MaleCNS LIF (Stonkfly C++ kernel) watches live IPTV and changes channels from Kenyon-cell / Giant Fiber telemetry. Pixels only; “boredom” is an authored label. Local FastAPI; created 22 Sep 2026.
- [Music in the Body](https://github.com/matsuo-koya/music-in-the-body) - Endless browser instrument on a ≥5-synapse MaleCNS graph (163,997 bodies) in a Web Worker. Harmony and timbre mapping are authored; includes a rewired comparison. [ [instrument](https://matsuo-koya.github.io/music-in-the-body/) ]
- [swat-or-buy](https://github.com/oskarmalmwiklund/swat-or-buy) - Ad creatives scored by a MaleCNS retina/lamina running in the browser. You pick first; the fly “BUYs” glance salience and swats the rest. Deep `buy`/`swat` cells are silent under LIF (graded optic lobe); the live show uses honest glance/boredom. [ [play](https://swat-or-buy.vercel.app/) ]
- [Xenova fruit-fly-simulation](https://huggingface.co/spaces/Xenova/fruit-fly-simulation) - See [Games & interactive](#games--interactive). The cleanest in-browser MaleCNS canvas.

## Embodied / scientific RL

Closed-loop bodies, locomotion policies, and research-grade simulators. Several predate the Sep 2026 meme wave and are included because later demos stand on them.

- [Antennal grooming](https://github.com/NeLy-EPFL/antennal-grooming) - Connectome-derived grooming network plus kinematic replay in a MuJoCo / FARMS fly body (Özdil et al., *Nature Communications* 2026). [ [DOI](https://doi.org/10.1038/s41467-026-72152-x) ]
- [BioDrone_RL](https://github.com/Kartha-33/BioDrone_RL) - PPO drone in a 3D obstacle course with a fly-inspired compound-eye sensor and sparse / small-world policy. Inspired by Drosophila motion circuits; a “real connectome data” phase was still planned in the Mar 2026 README.
- [boltzmann-fly](https://github.com/jniimi/boltzmann-fly) - Purchase-World Deep Boltzmann Machine whose couplings are masked to right-hemisphere MaleCNS PN→KC→MBON. Visit AUC matches the dense original; a free-energy clamp test **flips sign** vs a degree-preserving rewire. Magnitudes are learned; the mask is the wiring.
- [Drosophila_brain_model](https://github.com/philshiu/Drosophila_brain_model) - Shiu et al. whole-brain FlyWire LIF model (*Nature* 2024). The sensorimotor reference most MaleCNS game kernels cite.
- [flyconnectome-nulls](https://github.com/gyujeongion/flyconnectome-nulls) - Compressed FlyWire v783 agents evolve next to randomised wiring. Standard shuffles beat the connectome because they invent olfactory→motor shortcuts the compressed graph lacks; boundary-preserving nulls wipe the gap. Pre-registered; one registered prediction failed and is reported as failed. [ [Zenodo](https://doi.org/10.5281/zenodo.22871090) ]
- [eonsystemspbc/fly-brain](https://github.com/eonsystemspbc/fly-brain) - Eon Systems whole-brain FlyWire v783 LIF emulation across Brian2, PyTorch, NEST GPU, and GeNN backends.
- [erojasoficial-byte/fly-brain](https://github.com/erojasoficial-byte/fly-brain) - FlyWire v783 (138,639 neurons) in a NeuroMechFly v2 / MuJoCo body with vision, olfaction, flight, and Hebbian plasticity. [ [pages](https://erojasoficial-byte.github.io/fly-brain/) ]
- [fly.ai / flybrain](https://github.com/alextitonis/fly.ai) - Runnable MaleCNS v1.0 spiking network on CPU (Numba) or GPU (CuPy), with a neuron model following [Fly64](https://github.com/ornata/fly). [ [PyPI](https://pypi.org/project/flybrain/) ]
- [fly-afterlife](https://github.com/nsfm/fly-afterlife) - Whole MaleCNS LIF with a flyvis optic-lobe seam on true compound-eye geometry, plus a FlyWire female sharing a room. Timestamped `docs/SEAM.md` lab notebook; local only.
- [fly-cord-robots](https://github.com/SakshayMahna/fly-cord-robots) - MANC / MaleCNS ventral nerve cord as a walking CPG on a simulated hexapod, then an “amputated” quadruped. Spinal-cord I/O, not a whole-brain game kernel.
- [fly-garden](https://github.com/hama-jp/fly-garden) - **RL readout.** Full MaleCNS LIF (166,700 / 25.6M) sees a Three.js garden; a Double DQN layer picks seven locomotor actions. Connectome weights stay frozen.
- [Fly-Brain-AI / plastic-fly](https://github.com/neilt93/Fly-Brain-AI) - Closed-loop FlyWire (139k LIF neurons in Brian2) + FlyGym / MuJoCo. The `plastic-fly/` package is the brain–body bridge, ablation / odor / looming experiments, and analysis — not a separate GitHub repo.
- [fly-brain (browser WASM)](https://github.com/Lulzx/fly-brain) - Embodied whole-CNS MaleCNS LIF in the browser (WASM) plus MuJoCo flybody and flyvis vision.
- [flybody](https://github.com/TuragaLab/flybody) - Anatomically detailed MuJoCo whole-body fly (DeepMind + Janelia). Controllers are MLPs, not connectome graphs — this is the body FlyGM later wraps. Vaxenburg et al., *Nature* 2025. [ [DOI](https://doi.org/10.1038/s41586-025-09029-4) ]
- [fly-fpv](https://github.com/joey-david/fly-fpv) - **RL.** MaleCNS adjacency-masked sparse controller trained (behavior cloning, then PPO) to fly a 3D hoop course. Weights learned; topology constrained.
- [Flybrain (gate course)](https://github.com/YYK2007/flybrain) - **RL readout.** Full 166,700 / 25.6M *rate* model on a 3D gate course; a logistic decoder on 64 population averages flaps. Trained 6/6 held-out courses; silenced 0; **presynaptic shuffle also 3/3** — the README does not claim topology is the skill. Distinct from [fly.ai / flybrain](https://github.com/alextitonis/fly.ai) (LIF runtime). Local `127.0.0.1:8765`.
- [Flyhard](https://github.com/MarkUnthank/flyhard) - **RL.** MaleCNS model learns to turn a physical steering wheel with fly legs and drive CARLA (stock Mini Cooper). Documented hold-out steering.
- [Haltere Pilot](https://github.com/Ameerkhanjk/haltere-pilot) - Simulated quadrotor whose gyro enters **haltere afferents** and whose motors are real wing MNs. Tuned gains reach 93% of a teacher; silencing 204 haltere cells crashes every second, while 204 random cells do almost nothing.
- [therealfly](https://github.com/fruitflydev/therealfly) - Full MaleCNS LIF (165,122 / 10.2M) coupled to flybody with **no written controller**. Preregistered stage 1 (DNa01+DNa02 cord rhythm) **FAIL**: left–right anti-phase 0/3; a degree-preserving scramble makes the same 11 Hz peak. Stages 2–3 not run on that evidence. Offline science; no wallet.
- [fly-self-driving](https://github.com/suanmiao/fly-self-driving) - MaleCNS-scale connectome (165k neurons, 25.6M synapses) trained to drive a simulated street from pixels. [ [demo](https://fly-self-driving.kylon.app) ]
- [flyverse](https://github.com/djmango/flyverse) - Native Rust MaleCNS v1.0 sim embodied in a virtual room, with a browser visualizer. See also [flyverse-core](https://github.com/tel-0s/flyverse-core) (transmitter-aware core).
- [FLYNN](https://github.com/ben-gitdev/fly-gym) - **RL / imitation.** FlyWire FAFB v783 as a ~139k-unit sparse RNN trained with DAgger to drive a wheeled MuJoCo robot, vs small-world and CNN baselines. Wang & Chen, arXiv:2607.00025.
- [Fly Space Program](https://github.com/steph4n-gh/fly-space-program) - **RL readout.** Full retained MaleCNS plus a learned ten-command readout flies a simulated booster (60/80 unseen landings in the published release; covering the eyes → 0/80). Orbital missions and the physical “Fly Cube” are not demonstrated. [ [sim](https://fly.steph4n.dev/) ]
- [Fruitless](https://github.com/nicodunks/fruitless) - MaleCNS mAL-block courtship assay with a recorded-activity Three.js fly. Male-cue responses rise after the block; female cues still win — increased responsiveness, not male preference.
- [FlyGM](https://arxiv.org/abs/2602.17997) - Jin, Zhu, Zhang, Sui. *Whole-Brain Connectomic Graph Model Enables Whole-Body Locomotion Control in Fruit Fly*. Instantiates the adult whole-brain connectome as a directed message-passing graph and trains it with RL (imitation + PPO) on flybody for walking, turning, and flight. [ [project](https://lnsgroup.cc/research/FlyGM) · [site](https://sites.google.com/view/flygm) ]
- [FlyGym / NeuroMechFly v2](https://github.com/NeLy-EPFL/flygym) - Physics digital twin of adult *Drosophila* (vision, olfaction, terrain, SAC obstacle-avoid). The body most embodied demos attach a connectome to. Wang-Chen et al., *Nature Methods* 2024. [ [DOI](https://doi.org/10.1038/s41592-024-02497-y) · [NeuroMechFly v1](https://github.com/NeLy-EPFL/NeuroMechFly) · [docs](https://neuromechfly.org/) ]
- [flyvis](https://github.com/TuragaLab/flyvis) - Connectome-constrained deep mechanistic model of the fly visual system in PyTorch (Lappalainen et al., *Nature* 2024). The visual prior reused by NeuroMechFly v2 fly-following. [ [DOI](https://doi.org/10.1038/s41586-024-07939-3) · [docs](https://turagalab.github.io/flyvis/) ]
- [Descending-neuron atlas](https://github.com/shreyansatvik/fly-brain-to-body-drosophila-descending-neurons) - Interactive map of 481 MaleCNS descending-neuron types onto the body parts they excite or inhibit.
- [VNC walking CPG](https://github.com/smpuglie/Pugliese_2026) - Pugliese et al. firing-rate VNC simulations that identify a walking CPG (DNg100 / DNb08 screens). [ [bioRxiv](https://doi.org/10.1101/2025.09.12.675944) ]
- [Virtual Embodied Fly](https://github.com/TheFlyExperiment/Virtual-Embodied-Fly) - Documentation landing page for a closed-loop FlyWire + NeuroMechFly “virtual embodied fly” announcement (Eon Systems / Shiu lineage). Marketing-heavy README; runnable code lives in [eonsystemspbc/fly-brain](https://github.com/eonsystemspbc/fly-brain).
- [virtual-fly-lab](https://github.com/Leon-Av/virtual-fly-lab) - Full-CNS MaleCNS fly living in a Godot 4 sandbox.

## Datasets & tools

Short orientation only. Deeper coverage lives on [watthem/awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome).

- [MaleCNS v1.0](https://male-cns.janelia.org/) - Complete adult male CNS (brain + optic lobes + VNC, intact neck connective): ~166,700 neurons, ~125 million synapses. FlyEM / Janelia, Cambridge, MRC LMB, and Google Research. Data **CC BY 4.0**. Primary paper: Berg, Beckett, et al., *Sexual dimorphism in the complete Drosophila male central nervous system connectome*, [*Cell* (3 Sep 2026)](https://doi.org/10.1016/j.cell.2026.08.015). [ [Google Research blog](https://research.google/blog/a-connectomics-milestone-mapping-the-complete-male-fruit-fly-brain/) · [downloads](https://male-cns.janelia.org/download/) · [neuPrint](https://neuprint.janelia.org) · [Cell Type Explorer](https://reiserlab.github.io/celltype-explorer-drosophila-male-cns/) ]
- [FlyWire / FAFB](https://flywire.ai) - Complete adult female brain (~139,255 neurons, ~50 million synapses), 2024. Data **CC BY-NC 4.0**. Primary paper: Dorkenwald et al., *Neuronal wiring diagram of an adult brain*, [*Nature*](https://doi.org/10.1038/s41586-024-07558-y). Companion atlas: Schlegel et al., [*Nature*](https://doi.org/10.1038/s41586-024-07686-5). [ [Codex](https://codex.flywire.ai) ]
- [BANC](https://github.com/htem/BANC-project) - Brain And Nerve Cord, female whole-CNS. Bates, Phelps, Kim, Yang et al., *Nature* (2026). [ [DOI](https://doi.org/10.1038/s41586-026-10735-w) · [bioRxiv](https://doi.org/10.1101/2025.07.31.667571) ]
- [MANC](https://doi.org/10.7554/eLife.97769) - Male Adult Nerve Cord. Takemura et al., *eLife* (2024).
- [malecns (natverse)](https://github.com/natverse/malecns) - R access to `male-cns:v1.0` via neuPrint.
- [flybench](https://github.com/brandoncho369/flybench) - 36 pre-registered reflex tasks on FlyWire v783 and MaleCNS (shuffled-wiring controls, flyvis eye, FlyGym body). Working gain ~0.45, not published 1.0; spike-frequency adaptation beats the reference LIF. Companion to [fly-explorer](#games--interactive). [ [leaderboard](https://www.fly-bench.com/bench) ]
- [flybrain SDK](https://github.com/freeman-1984-coder/flybrain-sdk) - CPU LIF runtime, game APIs, and on-demand MaleCNS / FlyWire data (no CUDA required).
- [connectome-host](https://github.com/anima-research/connectome-host) - **Not biology.** Anima Research’s recipe-driven agent host (web UI / TUI / headless fleet) on their “Connectome” software stack (agent-framework, context-manager, chronicle, membrane). Name collision with MaleCNS / FlyWire wiring diagrams; no *Drosophila* graph.
- [connectome-kernels](https://github.com/QuixiAI/connectome-kernels) - Fused CUDA kernels for training a recurrent net on a fixed sparse graph (built for FlyGPT / MaleCNS Shakespeare). Tooling, not a demo.

## Related lists

- [awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome) - Datasets, papers, viewers, analysis libraries, and a shorter viral-experiments section. Complementary: they curate the science stack; this list curates demos and dopamine / RL use cases.
- [awesome-fly](https://github.com/cobanov/awesome-fly) - Parallel community index (games, desktop flies, language/art, research tools) by the Fly Dino author, with a [fly-connectome-template](https://github.com/cobanov/fly-connectome-template) starter. Overlaps this list; last content push 20 Sep 2026 (The Fly’s Table, Fly-NAF, fly-swing, boltzmann-fly). Useful as a second pass.
- [`discoveries/`](discoveries/) - Uncurated search shards (games / media / art, science / embodied RL, trading / dopamine / wirehead, the 14–22 Sep 2026 X/web and GitHub cool-hunts, and a 25 Sep 2026 name-collision note for [anima-research/connectome-host](https://github.com/anima-research/connectome-host)). Stronger items are folded into the sections above; the shards keep rejected and “mentioned, not verified” notes.

## Articles & threads

Verified reporting and primary posts. Tweet IDs appear only when an archive or news embed confirmed them.

- [A connectomics milestone: Mapping the complete male fruit fly brain](https://research.google/blog/a-connectomics-milestone-mapping-the-complete-male-fruit-fly-brain/) - Google Research, 3 Sep 2026.
- [Sexual dimorphism in the complete Drosophila male central nervous system connectome](https://doi.org/10.1016/j.cell.2026.08.015) - Berg, Beckett, Costa, Schlegel, Januszewski, Marin, et al., *Cell* 189(18), 3 Sep 2026. [ [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.10.09.680999) ]
- [Neuronal wiring diagram of an adult brain](https://doi.org/10.1038/s41586-024-07558-y) - Dorkenwald et al. / FlyWire Consortium, *Nature*, 2024.
- [A Drosophila computational brain model reveals sensorimotor processing](https://doi.org/10.1038/s41586-024-07763-9) - Shiu et al., *Nature*, 2024. The LIF kernel many demos copy.
- [Whole-body physics simulation of fruit fly locomotion](https://doi.org/10.1038/s41586-025-09029-4) - Vaxenburg et al., *Nature* 2025 (flybody).
- [Connectome-constrained networks predict neural activity across the fly visual system](https://doi.org/10.1038/s41586-024-07939-3) - Lappalainen et al., *Nature* 2024 (flyvis).
- [Whole-Brain Connectomic Graph Model Enables Whole-Body Locomotion Control in Fruit Fly](https://arxiv.org/abs/2602.17997) - FlyGM, arXiv:2602.17997.
- [FLYNN: Robust Neural Network for Robot Navigation using Fly Brain Topology](https://arxiv.org/abs/2607.00025) - Wang & Chen, arXiv:2607.00025.
- [@nftechie_ — Doom training](https://x.com/nftechie_/status/2097711063135383642) - “the fly brain can play doom” (6 Sep 2026). Frames → sensory neurons; damage → two PPL101 cells. Status ID from unrollnow.
- [@nftechie_ — Stonkfly](https://x.com/nftechie_/status/2098012107652391357) - “I gave the fly brain $100 to trade bitcoin.”
- [@nftechie_ — fly social network](https://x.com/nftechie_/status/2098371978612924425) - Three male + three female connectomes.
- [@fruitflydev — Flyonardo airdrop](https://x.com/fruitflydev/status/2100964182028099993) - 18 Sep 2026. NFT canvases claimed by burning $FLYBRAIN. Status ID from unrollnow. Repo: [flyonardo-da-vinci](https://github.com/fruitflydev/flyonardo-da-vinci) (already in the 17 Sep shard; token wrapper).
- [@fruitflydev — stock-room trader](https://x.com/fruitflydev/status/2101298482002927874) - 19 Sep 2026. “gave the fly $10,000 to trade stocks.” Live paper build is [The Dartboard](#trading--markets); that page is more conservative than the tweet (no edge claimed).
- [@fruitflydev — dartboard clip](https://x.com/fruitflydev/status/2102092842537734496) - Clip-only; no GitHub in the post. [flybrain.online/dartboard](https://flybrain.online/dartboard) (200).
- [Flies Are All You Need](https://artificialscientific.com/papers/flies-are-all-you-need) - FLM methods note: full retained MaleCNS reservoir on a frozen 1.2B LM. Direct-input control slightly beats the fly graph. Conversational recipe is [nftechie/flm](https://github.com/nftechie/flm); study artifacts stay private.
- [@barrelshifter — Mario 64](https://x.com/barrelshifter/status/2097004115826200898) - “playing mario 64 using a fly's brain.”
- [@_lyraaaa_ — Beat Saber](https://x.com/_lyraaaa_/status/2097527368919470162) - “the fly brain can play beat saber.”
- [@alright_mark — parallel parking](https://x.com/alright_mark/status/2098085928489177142) - “the fly has completed* the ultimate test: parallel parking.”
- [@nickwalton00 — Smash / Rubik’s](https://x.com/nickwalton00/status/2098537903110652087) - Super Smash Bros clip; [Rubik’s](https://x.com/nickwalton00/status/2098301053372621070). X-only; no public repo found.
- [404 Media](https://www.404media.co/a-digital-fly-brain-has-taken-over-the-internet/) - 15 Sep 2026 recap (Minecraft, Doom, Beat Saber, Stonkfly, parking). Names kebab / LinkedIn / “bi fly” without first-party URLs for those.
- [Inquirer / NYT — “Is there anything a fruit fly brain can't do?”](https://www.inquirer.com/news/nation-world/fruit-fly-brain-map-simulation-video-games-parking-dancing-research-20260917.html) - 17 Sep 2026 recap (Rubik’s, YMCA four-tone dance, poker/blackjack, kebab). Names Unthank blinkers on Flyhard; no first-party URLs for YMCA / kebab. Blackjack now has [The Fly’s Table](#reinforcement--dopamine).
- [SuperTruth — Intelligence Is Structure, Not Scale](https://supertruth.ai/research/connectome) - Frozen MaleCNS (166,700 / 6.24M ≥5-synapse edges) trained to copy a health-record trust index vs LLM baselines. Pre-registered reservoir experiment, not a clinician. [ [paper](https://doi.org/10.5281/zenodo.22865214) · [repo](https://github.com/evil-robot/supertruth-connectome-public) ]
- [Quantum Zeitgeist — Fly OCR](https://quantumzeitgeist.com/fruit-fly-ocr/) - 14 Sep 2026 write-up of jerryjliu/fly_ocr.
- [Gizmodo](https://gizmodo.com/google-mapped-a-fruit-flys-brain-now-its-playing-doom-and-super-mario-64-2000808616) - Doom + Mario 64 recap with embedded posts.
- [TechSpot](https://www.techspot.com/news/113780-google-mapped-fly-nervous-system-developers-using-play.html) - Confirms the barrelshifter status URL and the PPL101 Doom loop.
- [PC Gamer](https://www.pcgamer.com/hardware/after-google-mapped-an-adult-male-fruit-flys-brain-software-engineers-made-it-play-doom-mario64-and-beat-saber/) - Doom, Mario 64, and Beat Saber wave.
- [Know Your Meme — Fly Brain Simulations](https://knowyourmeme.com/memes/fly-brain-simulations-fruit-fly-brain-mapped) - Spread timeline (Beat Saber, Stonkfly, parallel-parking clips). Treat as a meme log, not a methods paper.

## Contributing

New demo? Open a PR. The bar is a working link, a one-line factual description, and honesty about what is simulated. Details in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

List text is [CC0 1.0](LICENSE) (public domain dedication), the usual license for awesome lists.

Linked projects and datasets keep their own terms. **MaleCNS data is CC BY 4.0** (attribution required; commercial use allowed). **FlyWire / FAFB data is CC BY-NC 4.0** (non-commercial). Check each source before you ship a fork.

*Last updated 25 September 2026, during the MaleCNS demo wave. Fly on. 🪰*
