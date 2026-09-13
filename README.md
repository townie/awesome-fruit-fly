# Awesome Fruit Fly [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Interactive demos, games, trading loops, art, and dopamine / RL experiments that run a reconstructed *Drosophila* (fruit fly) connectome — especially **MaleCNS v1.0** (Sep 2026) and **FlyWire**.

The September 2026 MaleCNS release (~166,700 neurons spanning brain, optic lobes, and ventral nerve cord) set off a wave of community “fly brain” simulations: Doom, Mario 64, Beat Saber, Minecraft, BTC trading, browser pets, and closed-loop locomotion. This list is a curated index of those **applications**, not a catalogue of every dataset or analysis library.

For datasets, viewers, and analysis tools see the companion list **[awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome)**. We still keep a short [Datasets & tools](#datasets--tools) section so demos have context.

**These are wiring-diagram simulations.** Published connectomes give who connects to whom. Sensory maps, leaky-integrate-and-fire dynamics, dopamine pulses, and button bindings are almost always engineered. A listed project is not a living fly, and “learning” in a README is not proof of biological memory unless the authors publish controls that hold up.

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
- [Fly / Wirehead](https://github.com/mattyhempstead/fly-wirehead) - Endless insect Shorts on a phone in front of the same retained MaleCNS graph. Every accepted frame injects current into 15 PAM11 cells — artificial “wirehead” dopamine, inspired by Stonkfly. Preference and addiction are not established.
- [fly-mario](https://github.com/ksanjeev284/fly-mario) - Full MaleCNS v1.0 playing NES Super Mario Bros with CUDA LIF dynamics, dopaminergic learning, and a live 3D web dashboard.
- [flywire-playground](https://github.com/hills-dong/flywire-playground) - FlyWire sub-circuits as spiking networks that play games using the fly’s own dopamine update rule.
- [Ruby Project](https://github.com/wavendis/ruby-project) - NeoForge Minecraft 1.21.1 mod that gives a mob a FlyWire-derived LIF brain (photoreceptors, descending neurons, Kenyon cells, MBON, DAN) with dopamine-gated KC→MBON learning. Real wiring plus a few synthetic Minecraft entry neurons; the author documents what is fabricated.
- [Stonkfly](https://github.com/nftechie/stonkfly) - BTC-USDC candlestick pixels into MaleCNS; a fixed readout proposes buy / sell / hold via Coinbase AgentKit. Portfolio gains pulse 15 PAM11 cells, losses pulse two PPL101 cells. Profitable learning has not been demonstrated. X: [@nftechie_](https://x.com/nftechie_/status/2098012107652391357). [ [stonkfly.com](https://stonkfly.com) · [live dashboard](https://stonkfly-three.vercel.app/) ]
- [stonkfly-lab](https://github.com/paappraiser/stonkfly-lab) - Smaller mushroom-body trading lab with odor inputs, delayed dopamine, two-fly agreement, paper BTC, and a dashboard. Inspired by Stonkfly; not the full MaleCNS graph.

## Games & interactive

Connectome activity mapped onto game controls or a playable / inspectable agent. Prefer repos and live pages; X-only clips are marked.

- [Beat Saber (Lyra)](https://x.com/_lyraaaa_/status/2097527368919470162) - **X-only.** [@\_lyraaaa\_](https://x.com/_lyraaaa_) (“the fly brain can play beat saber,” 8 Sep 2026). Author notes motor patterns were overfit to a replay with teacher-forced input while visual reactivity / RL training continued — not fully reactive play from pixels alone.
- [Fly64 / Super Mario 64](https://github.com/ornata/fly) - Jessica Paquette ([@barrelshifter](https://x.com/barrelshifter)) hooks MaleCNS to a decompiled SM64 build: six hidden cameras, LIF dynamics, DNg100 / DNa02 / DNp01 readouts. No training or reward in the published loop; Mario can walk into a wall and stay there. [ [announcement](https://x.com/barrelshifter/status/2097004115826200898) ]
- [fly_chess](https://github.com/martialsystems/fly_chess) - Chess via a connectome LIF ply plus search. The README reports that one LIF ply on the real graph is silent and `wiring_helped` is false — an honest negative result.
- [fly-explorer](https://github.com/brandoncho369/fly-explorer) - FlyWire (~139k neurons) as a live browser spiking network. Press sugar, watch a proboscis motor neuron fire. [ [demo](https://www.fly-bench.com) ]
- [fly-flappy-bird](https://github.com/arjunkshah12345-hash/fly-flappy-bird) - MaleCNS wired to Flappy Bird with engineered adapters and recorded gameplay.
- [fly-hero](https://github.com/actuallyrizzn/fly-hero) - Frozen fly-connectome reservoir that plays Clone Hero by seeing the highway.
- [fly-brain-bench](https://github.com/RaphaelSR/fly-brain-bench) - Browser LIF over FlyWire (138,639 neurons, ~2.7M connections) at 60 fps with no extra dependencies.
- [FlyBrain (boss)](https://github.com/Jhongdlp/FlyBrain) - Video-game boss driven by MaleCNS (~165k neurons): Rust engine, vectorized Python VecEnv, Three.js visualizer.
- [FlyBrain-HalfLife](https://github.com/Yusuftmle/FlyBrain-HalfLife) - MaleCNS / FlyWire agent playing Half-Life via LIF dynamics, a 60×60 retina, and DirectInput.
- [flybrain.app](https://flybrain.app) - Browser FlyWire FAFB v783 simulation (139,255 LIF neurons) forked from worm-sim. [ [repo](https://github.com/snedea/flybrain) ]
- [flybrain-snake](https://github.com/charbelkassab/flybrain-snake) - Live MaleCNS (~165k neurons) playing Snake, with the control mapping documented instead of hidden.
- [flydoom](https://github.com/mutkuoz/flydoom) - Alternate Doom fly on Princeton’s FAFB-v783 (FlyWire) dataset rather than MaleCNS.
- [FLYBRAIN-BAD_APPLE_X_DOOM](https://github.com/fazchile17/FLYBRAIN-BAD_APPLE_X_DOOM) - Local 3D FlyWire v783 viewer (139,255 neurons) with optional Bad Apple!! and Doom overlays on the neurons.
- [flyputer](https://github.com/migkapa/flyputer) - Local Gemma agent queries FlyWire, runs small LIF subcircuits, and includes a playable Giant Fiber swatter game against the real LPLC2/LC4 escape reflex.
- [Fruit Fly Simulation (Xenova)](https://huggingface.co/spaces/Xenova/fruit-fly-simulation) - Joshua Lochner’s WebGPU MaleCNS demo: paint / stimulate 166,700 neurons and watch an articulated Three.js fly. Connectivity is biological; movements are programmed. Verified Hugging Face Space (not a GitHub repo).
- [NeuroCraft Fly](https://github.com/evnsnclr/neurocraft-fly-public) - Evan Sinclair Smith’s Minecraft MaleCNS fly (166,700 neurons). In-game events (food, light, nearby creatures, attacks) drive the network; activity selects scripted body programs. Public landing page and recorded demo; the Fabric mod itself was still being prepared as of the Sep 2026 landing-page README.
- [Optic-lobe steering](https://github.com/AbijahKaj/fruit-fly-brain-research) - MaleCNS optic lobe (65.8k neurons) as a WebGPU rate model: the fly renders 1,771 column directions and the wiring becomes wing commands. [ [browser demo](https://fruit-fly-research.vercel.app/) ]

### X-only or thinly documented game clips

- [Bad Apple!! (@linguinelabs)](https://x.com/linguinelabs) - **X-only.** Kevin / [@linguinelabs](https://x.com/linguinelabs) fed the Bad Apple!! video into a fly-brain simulator and showed neuron activity driving a 3D fly body. Widely credited in coverage; no public repo or stable status URL was verified here. See also the open-source [FLYBRAIN-BAD_APPLE_X_DOOM](https://github.com/fazchile17/FLYBRAIN-BAD_APPLE_X_DOOM) viewer above.
- [Fly social network](https://x.com/nftechie_/status/2098371978612924425) - [@nftechie_](https://x.com/nftechie_) (13 Sep 2026): three male and three female connectomes with separate states; presenting flies stimulates sensory neurons and activity decides whether another fly responds (“TheFlybook”). No public repo was found at write-up.
- [Mario 64 follow-ups](https://x.com/barrelshifter) - After the [7 Sep 2026 clip](https://x.com/barrelshifter/status/2097004115826200898), [@barrelshifter](https://x.com/barrelshifter) posted further SM64 training experiments (including a “teaching to Kill” follow-up circulated in community notes). Those later clips were not independently archived with a verified status ID here.

## Trading & markets

Same caveat as the dopamine section: a chart-in / trade-out loop is an interface, not a proven alpha.

- [the_buzz](https://github.com/TropiFloAI/the_buzz) - Bitcoin prediction bake-off: random forest vs a fruit-fly-connectome network.
- [flycoinrh](https://github.com/fruitflydev/flycoinrh) - MaleCNS-scale connectome (165,122 neurons) used to launch tokens on Robinhood Chain. Meme-token experiment; treat as entertainment, not a model organism.
- [flybrain-female](https://github.com/opifor/flybrain-female) - FlyWire FAFB v783 “sister” token experiment on Robinhood Chain. [ [site](https://femaleflybrain.com) ]
- [fruit-fly-fund](https://github.com/armanbabazadeh6/fruit-fly-fund) - Two MaleCNS v1.0 flies race the same paper market; one applies experimental memory updates and one does not. No real orders. [ [demo](https://armanbabazadeh6.github.io/fruit-fly-fund/) ]
- [fruitfly.trade](https://github.com/fruitflytrader/fruitfly.trade) - Simulated connectome whose spikes choose memecoin trades. [ [site](https://fruitfly.trade) ]
- [Gregor](https://github.com/PunzRH/gregor) - “A real fruit-fly connectome kept alive by its coin.”
- [openfly](https://github.com/marketcalls/openfly) - MaleCNS v1.0 trading an intraday NIFTY straddle through OpenAlgo.
- [Stonkfly](https://github.com/nftechie/stonkfly) - See [Reinforcement & dopamine](#reinforcement--dopamine). The canonical dopamine-gated trading demo.

## Art & media

- [DJ Drosophila](https://github.com/MRsagi/dj-drosophila) - MaleCNS-inspired fly DJ and shared 24/7 CC0 live radio.
- [FLYcasso](https://github.com/gustavz/FLYcasso) - Connectome-conditioned image diffusion and simulated fly painting on MaleCNS wiring.
- [flyboard](https://github.com/sukoji/flyboard) - Music chart voted by a GPU simulation of MaleCNS v1.0 (~165k neurons) after 84 songs. [ [viewer](https://sukoji.github.io/flyboard/viewer.html) ]
- [FLYWATT](https://github.com/flywatt-live/watt-the-fly) - Browser MaleCNS subset (38,178 neurons, 5.1M synapses); every spike is converted to power and lights a bulb (~6.5 µW).
- [Infinite Sugar](https://github.com/cnqso/infinite-sugar) - Browser fruit-fly connectome artwork. [ [demo](https://infinitesugar.cnqso.com) ]
- [Xenova fruit-fly-simulation](https://huggingface.co/spaces/Xenova/fruit-fly-simulation) - See [Games & interactive](#games--interactive). The cleanest in-browser MaleCNS canvas.

## Embodied / scientific RL

Closed-loop bodies, locomotion policies, and research-grade simulators. Several predate the Sep 2026 meme wave and are included because later demos stand on them.

- [BioDrone_RL](https://github.com/Kartha-33/BioDrone_RL) - PPO drone in a 3D obstacle course with a fly-inspired compound-eye sensor and sparse / small-world policy. Inspired by Drosophila motion circuits; a “real connectome data” phase was still planned in the Mar 2026 README.
- [Drosophila_brain_model](https://github.com/philshiu/Drosophila_brain_model) - Shiu et al. whole-brain FlyWire LIF model (*Nature* 2024). The sensorimotor reference most MaleCNS game kernels cite.
- [eonsystemspbc/fly-brain](https://github.com/eonsystemspbc/fly-brain) - Eon Systems whole-brain FlyWire v783 LIF emulation across Brian2, PyTorch, NEST GPU, and GeNN backends.
- [erojasoficial-byte/fly-brain](https://github.com/erojasoficial-byte/fly-brain) - FlyWire v783 (138,639 neurons) in a NeuroMechFly v2 / MuJoCo body with vision, olfaction, flight, and Hebbian plasticity. [ [pages](https://erojasoficial-byte.github.io/fly-brain/) ]
- [fly.ai / flybrain](https://github.com/alextitonis/fly.ai) - Runnable MaleCNS v1.0 spiking network on CPU (Numba) or GPU (CuPy), with a neuron model following [Fly64](https://github.com/ornata/fly). [ [PyPI](https://pypi.org/project/flybrain/) ]
- [Fly-Brain-AI / plastic-fly](https://github.com/neilt93/Fly-Brain-AI) - Closed-loop FlyWire (139k LIF neurons in Brian2) + FlyGym / MuJoCo. The `plastic-fly/` package is the brain–body bridge, ablation / odor / looming experiments, and analysis — not a separate GitHub repo.
- [fly-brain (browser WASM)](https://github.com/Lulzx/fly-brain) - Embodied whole-CNS MaleCNS LIF in the browser (WASM) plus MuJoCo flybody and flyvis vision.
- [fly-self-driving](https://github.com/suanmiao/fly-self-driving) - MaleCNS-scale connectome (165k neurons, 25.6M synapses) trained to drive a simulated street from pixels. [ [demo](https://fly-self-driving.kylon.app) ]
- [flyverse](https://github.com/djmango/flyverse) - Native Rust MaleCNS v1.0 sim embodied in a virtual room, with a browser visualizer. See also [flyverse-core](https://github.com/tel-0s/flyverse-core) (transmitter-aware core).
- [FlyGM](https://arxiv.org/abs/2602.17997) - Jin, Zhu, Zhang, Sui. *Whole-Brain Connectomic Graph Model Enables Whole-Body Locomotion Control in Fruit Fly* (arXiv:2602.17997). Instantiates the adult whole-brain connectome as a directed message-passing graph and trains it with RL (imitation + PPO) on a biomechanical fly for walking, turning, and flight. No official code repo was found at write-up.
- [FlyGym / NeuroMechFly v2](https://github.com/NeLy-EPFL/flygym) - Physics digital twin of adult *Drosophila* (vision, olfaction, terrain). The body most embodied demos attach a connectome to. [ [NeuroMechFly](https://github.com/NeLy-EPFL/NeuroMechFly) · [docs](https://neuromechfly.org/) ]
- [flyvis](https://github.com/TuragaLab/flyvis) - Connectome-constrained deep mechanistic model of the fly visual system in PyTorch.
- [Descending-neuron atlas](https://github.com/shreyansatvik/fly-brain-to-body-drosophila-descending-neurons) - Interactive map of 481 MaleCNS descending-neuron types onto the body parts they excite or inhibit.
- [Virtual Embodied Fly](https://github.com/TheFlyExperiment/Virtual-Embodied-Fly) - Documentation landing page for a closed-loop FlyWire + NeuroMechFly “virtual embodied fly” announcement (Eon Systems / Shiu lineage). Marketing-heavy README; runnable code lives in [eonsystemspbc/fly-brain](https://github.com/eonsystemspbc/fly-brain).
- [virtual-fly-lab](https://github.com/Leon-Av/virtual-fly-lab) - Full-CNS MaleCNS fly living in a Godot 4 sandbox.

## Datasets & tools

Short orientation only. Deeper coverage lives on [watthem/awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome).

- [MaleCNS v1.0](https://male-cns.janelia.org/) - Complete adult male CNS (brain + optic lobes + VNC, intact neck connective): ~166,700 neurons, ~125 million synapses. FlyEM / Janelia, Cambridge, MRC LMB, and Google Research. Data **CC BY 4.0**. Primary paper: Berg, Beckett, et al., *Sexual dimorphism in the complete Drosophila male central nervous system connectome*, [*Cell* (3 Sep 2026)](https://doi.org/10.1016/j.cell.2026.08.015). [ [Google Research blog](https://research.google/blog/a-connectomics-milestone-mapping-the-complete-male-fruit-fly-brain/) · [downloads](https://male-cns.janelia.org/download/) · [neuPrint](https://neuprint.janelia.org) · [Cell Type Explorer](https://reiserlab.github.io/celltype-explorer-drosophila-male-cns/) ]
- [FlyWire / FAFB](https://flywire.ai) - Complete adult female brain (~139,255 neurons, ~50 million synapses), 2024. Data **CC BY-NC 4.0**. Primary paper: Dorkenwald et al., *Neuronal wiring diagram of an adult brain*, [*Nature*](https://doi.org/10.1038/s41586-024-07558-y). [ [Codex](https://codex.flywire.ai) ]
- [malecns (natverse)](https://github.com/natverse/malecns) - R access to `male-cns:v1.0` via neuPrint.
- [flybrain SDK](https://github.com/freeman-1984-coder/flybrain-sdk) - CPU LIF runtime, game APIs, and on-demand MaleCNS / FlyWire data (no CUDA required).

## Related lists

- [awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome) - Datasets, papers, viewers, analysis libraries, and a shorter viral-experiments section. Complementary: they curate the science stack; this list curates demos and dopamine / RL use cases.

## Articles & threads

Verified reporting and primary posts. Tweet IDs appear only when an archive or news embed confirmed them.

- [A connectomics milestone: Mapping the complete male fruit fly brain](https://research.google/blog/a-connectomics-milestone-mapping-the-complete-male-fruit-fly-brain/) - Google Research, 3 Sep 2026.
- [Sexual dimorphism in the complete Drosophila male central nervous system connectome](https://doi.org/10.1016/j.cell.2026.08.015) - Berg, Beckett, Costa, Schlegel, Januszewski, Marin, et al., *Cell* 189(18), 3 Sep 2026. [ [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.10.09.680999) ]
- [Neuronal wiring diagram of an adult brain](https://doi.org/10.1038/s41586-024-07558-y) - Dorkenwald et al. / FlyWire Consortium, *Nature*, 2024.
- [A Drosophila computational brain model reveals sensorimotor processing](https://doi.org/10.1038/s41586-024-07763-9) - Shiu et al., *Nature*, 2024. The LIF kernel many demos copy.
- [Whole-Brain Connectomic Graph Model Enables Whole-Body Locomotion Control in Fruit Fly](https://arxiv.org/abs/2602.17997) - FlyGM, arXiv:2602.17997.
- [@nftechie_ — Doom training](https://x.com/nftechie_) - 6 Sep 2026 announcement (quoted across TechSpot, Gizmodo, Tom’s Hardware): frames → sensory neurons; damage → two PPL101 cells. Status ID not independently archived here.
- [@nftechie_ — Stonkfly](https://x.com/nftechie_/status/2098012107652391357) - “I gave the fly brain $100 to trade bitcoin.”
- [@nftechie_ — fly social network](https://x.com/nftechie_/status/2098371978612924425) - Three male + three female connectomes.
- [@barrelshifter — Mario 64](https://x.com/barrelshifter/status/2097004115826200898) - “playing mario 64 using a fly's brain.”
- [@_lyraaaa_ — Beat Saber](https://x.com/_lyraaaa_/status/2097527368919470162) - “the fly brain can play beat saber.”
- [Gizmodo](https://gizmodo.com/google-mapped-a-fruit-flys-brain-now-its-playing-doom-and-super-mario-64-2000808616) - Doom + Mario 64 recap with embedded posts.
- [TechSpot](https://www.techspot.com/news/113780-google-mapped-fly-nervous-system-developers-using-play.html) - Confirms the barrelshifter status URL and the PPL101 Doom loop.
- [PC Gamer](https://www.pcgamer.com/hardware/after-google-mapped-an-adult-male-fruit-flys-brain-software-engineers-made-it-play-doom-mario64-and-beat-saber/) - Doom, Mario 64, and Beat Saber wave.
- [Know Your Meme — Fly Brain Simulations](https://knowyourmeme.com/memes/fly-brain-simulations-fruit-fly-brain-mapped) - Spread timeline (Beat Saber, Stonkfly, parallel-parking clips). Treat as a meme log, not a methods paper.

## Contributing

New demo? Open a PR. The bar is a working link, a one-line factual description, and honesty about what is simulated. Details in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

List text is [CC0 1.0](LICENSE) (public domain dedication), the usual license for awesome lists.

Linked projects and datasets keep their own terms. **MaleCNS data is CC BY 4.0** (attribution required; commercial use allowed). **FlyWire / FAFB data is CC BY-NC 4.0** (non-commercial). Check each source before you ship a fork.

*Last updated September 2026, during the MaleCNS demo wave. Fly on. 🪰*
