# Discoveries: science / embodied / RL / locomotion

Search shard for scientific, embodied, reinforcement-learning, robotics, and locomotion projects that use fruit-fly connectomes (FlyWire, MaleCNS, BANC, VNC) or connectome-constrained controllers. Sources checked: arXiv, Nature/Nature Methods/eLife/bioRxiv landing pages, and live GitHub repositories. No citations below were invented.

## Already known

These were in scope before this shard. Citations are pinned only so later shards can reuse them.

- **FlyGM** — whole-brain FlyWire graph policy for flybody locomotion (walking, turning, gait initiation, flight). Paper: [arXiv:2602.17997](https://arxiv.org/abs/2602.17997). Code linked from [lnsgroup.cc/research/FlyGM](https://lnsgroup.cc/research/FlyGM) and [sites.google.com/view/flygm](https://sites.google.com/view/flygm). Method: imitation init + PPO / PyTorch Geometric / MuJoCo flybody.
- **[neilt93/Fly-Brain-AI](https://github.com/neilt93/Fly-Brain-AI)** — FlyWire LIF brain (Brian2) closed-loop with FlyGym/MuJoCo; also a BANC VNC firing-rate walking experiment.
- **[TheFlyExperiment/Virtual-Embodied-Fly](https://github.com/TheFlyExperiment/Virtual-Embodied-Fly)** — Shiu-style whole-brain emulation driving NeuroMechFly.
- **[AbijahKaj/fruit-fly-brain-research](https://github.com/AbijahKaj/fruit-fly-brain-research)** — MaleCNS optic-lobe rate model in-browser; image → wing commands.
- **[Kartha-33/BioDrone_RL](https://github.com/Kartha-33/BioDrone_RL)** — fly-connectome RL stack aimed at small-drone autopilot.
- **BANC / VNC walking models** — now pinned as Pugliese et al. (see Foundational). Independent embodied demos (Fly-Brain-AI, Virtual-Embodied-Fly) already reuse those VNC CPG results.

## Foundational datasets (brief)

Wiring maps, not controllers. Cited because almost every embodied project below consumes them.

- **FlyWire female adult brain (FAFB v783)** — Dorkenwald et al., *Nature* (2024). [DOI 10.1038/s41586-024-07558-y](https://doi.org/10.1038/s41586-024-07558-y). Companion cell-type atlas: Schlegel et al., *Nature* (2024), [DOI 10.1038/s41586-024-07686-5](https://doi.org/10.1038/s41586-024-07686-5). Portal: [codex.flywire.ai](https://codex.flywire.ai/).
- **MaleCNS v1.0** — complete male CNS (brain + VNC). Preprint: “Sexual dimorphism in the complete connectome of the Drosophila male central nervous system,” [bioRxiv 10.1101/2025.10.09.680999](https://doi.org/10.1101/2025.10.09.680999). Data: [male-cns.janelia.org](https://male-cns.janelia.org/). Access package: [flyconnectome/malecns](https://github.com/flyconnectome/malecns/).
- **BANC (brain + nerve cord)** — Bates, Phelps, Kim, Yang et al., *Nature* (2026), [DOI 10.1038/s41586-026-10735-w](https://doi.org/10.1038/s41586-026-10735-w). Code: [htem/BANC-project](https://github.com/htem/BANC-project/). Preprint: [bioRxiv 10.1101/2025.07.31.667571](https://doi.org/10.1101/2025.07.31.667571).
- **Male VNC (MANC)** — Takemura et al., *eLife* (2024), “A connectome of the male Drosophila ventral nerve cord,” [DOI 10.7554/eLife.97769](https://doi.org/10.7554/eLife.97769).
- **VNC walking CPG simulations** — Pugliese et al., “Connectome simulations identify a central pattern generator circuit for fly walking,” [bioRxiv 10.1101/2025.09.12.675944](https://doi.org/10.1101/2025.09.12.675944). Code: [smpuglie/Pugliese_cpg_2025](https://github.com/smpuglie/Pugliese_cpg_2025) (JAX/JIT firing-rate VNC; DNg100 / DNb08 descending screens).

## New finds

### FlyGym / NeuroMechFly v2 — [NeLy-EPFL/flygym](https://github.com/NeLy-EPFL/flygym)

Gymnasium/MuJoCo digital twin of adult *Drosophila* for hierarchical sensorimotor control, terrain walking, vision, olfaction, and RL.

- **Paper:** Wang-Chen et al., “NeuroMechFly v2: simulating embodied sensorimotor control in adult Drosophila,” *Nature Methods* 21, 2353–2362 (2024). [DOI 10.1038/s41592-024-02497-y](https://doi.org/10.1038/s41592-024-02497-y). Preprint: [bioRxiv 10.1101/2023.09.18.556649](https://doi.org/10.1101/2023.09.18.556649). Data: [Harvard Dataverse 10.7910/DVN/3MCEYR](https://doi.org/10.7910/DVN/3MCEYR). Docs: [neuromechfly.org](https://neuromechfly.org/).
- **Code:** https://github.com/NeLy-EPFL/flygym (legacy Gymnasium snapshot: [NeLy-EPFL/flygym-gymnasium](https://github.com/NeLy-EPFL/flygym-gymnasium)).
- **Method:** MuJoCo + Gymnasium POMDP; CPG / hybrid locomotion controllers; hierarchical brain–VNC interface; **SAC** via Stable-Baselines3 for multimodal obstacle-avoid + odor-taxis; **FlyVision** connectome-constrained vision for fly-following.
- **Evidence:** Nature Methods page and EPFL postprint name FlyGym, SAC, and FlyVision; GitHub README matches the paper title and MuJoCo/NeuroMechFly v2 description.

### NeuroMechFly v1 — [NeLy-EPFL/NeuroMechFly](https://github.com/NeLy-EPFL/NeuroMechFly)

Original neuromechanical adult-fly body used to replay walking/grooming kinematics and optimize gaits (now archived; use FlyGym for new work).

- **Paper:** Lobato-Rios et al., “NeuroMechFly, a neuromechanical model of adult Drosophila melanogaster,” *Nature Methods* 19, 620–627 (2022). [DOI 10.1038/s41592-022-01466-7](https://doi.org/10.1038/s41592-022-01466-7).
- **Code:** https://github.com/NeLy-EPFL/NeuroMechFly (archived; site notes successor at neuromechfly.org).
- **Method:** PyBullet / FARMS neuromechanics; CPG / neuromuscular controllers; evolutionary gait optimization (not connectome-structured policy).
- **Evidence:** Repo README cites the 2022 Nature Methods paper and marks itself as legacy relative to FlyGym.

### flybody — [TuragaLab/flybody](https://github.com/TuragaLab/flybody)

Anatomically detailed MuJoCo whole-body fly with walking, flight, and vision-guided flight RL tasks (DeepMind + Janelia). Controllers are MLPs, not connectome graphs; this is the body FlyGM later wraps.

- **Paper:** Vaxenburg et al., “Whole-body physics simulation of fruit fly locomotion,” *Nature* 643, 1312–1320 (2025). [DOI 10.1038/s41586-025-09029-4](https://doi.org/10.1038/s41586-025-09029-4). Preprint: [bioRxiv 10.1101/2024.03.11.584515](https://doi.org/10.1101/2024.03.11.584515).
- **Code:** https://github.com/TuragaLab/flybody (DMPO training script: `flybody/train_dmpo_ray.py`).
- **Method:** MuJoCo + dm_control; **imitation learning** of real walking/flight trajectories; **DMPO** (Acme) with Ray-distributed actors; hierarchical vision-guided flight that reuses a frozen low-level policy.
- **Evidence:** Nature article and repo README/bibtex agree on title, DOI, DMPO/Ray, and task set. Paper explicitly flags future connectome-constrained controllers (Lappalainen / FlyWire / VNC).

### flyvis — [TuragaLab/flyvis](https://github.com/TuragaLab/flyvis)

Connectome-constrained deep mechanistic network of the fly optic lobe; the visual prior reused by NeuroMechFly v2 fly-following and cited by flybody/FlyGM as the connectome-policy template.

- **Paper:** Lappalainen et al., “Connectome-constrained networks predict neural activity across the fly visual system,” *Nature* (2024). [DOI 10.1038/s41586-024-07939-3](https://doi.org/10.1038/s41586-024-07939-3).
- **Code:** https://github.com/TuragaLab/flyvis — docs: [turagalab.github.io/flyvis](https://turagalab.github.io/flyvis/).
- **Method:** PyTorch connectome-constrained DMN (64 visual cell types; FIB19/FIB25 filters); task-optimized optic-flow training (not PPO/locomotion).
- **Evidence:** Nature paper and GitHub README both name this repo as the official implementation. NeuroMechFly v2 methods credit FlyVision commit `056e4aa` for closed-loop fly-following.

### Whole-brain LIF model — [philshiu/Drosophila_brain_model](https://github.com/philshiu/Drosophila_brain_model)

Brian2 leaky-integrate-and-fire model of the entire adult FlyWire brain; the sensorimotor substrate later embodied by Virtual-Embodied-Fly / Fly-Brain-AI.

- **Paper:** Shiu et al., “A Drosophila computational brain model reveals sensorimotor processing,” *Nature* (2024). [DOI 10.1038/s41586-024-07763-9](https://doi.org/10.1038/s41586-024-07763-9). Preprint title on the repo: [bioRxiv 10.1101/2023.05.02.539144](https://doi.org/10.1101/2023.05.02.539144). Model output archive: [DOI 10.17617/3.CZODIW](https://doi.org/10.17617/3.CZODIW).
- **Code:** https://github.com/philshiu/Drosophila_brain_model
- **Method:** **Brian2** LIF; FlyWire synapse counts + predicted transmitters; open-loop activation of gustatory/mechanosensory circuits (feeding, grooming) — not a physics body.
- **Evidence:** Nature article states “The brain model is available at https://github.com/philshiu/Drosophila_brain_model.” Repo README matches.

### FLYNN — [ben-gitdev/fly-gym](https://github.com/ben-gitdev/fly-gym)

Connectome-topology RNN trained to navigate a wheeled MuJoCo robot; robustness study of FlyWire wiring vs. small-world / CNN baselines.

- **Paper:** Wang & Chen, “FLYNN: Robust Neural Network for Robot Navigation using Fly Brain Topology,” [arXiv:2607.00025](https://arxiv.org/abs/2607.00025) (cs.RO; v2 13 Jul 2026). [DOI 10.48550/arXiv.2607.00025](https://doi.org/10.48550/arXiv.2607.00025).
- **Code:** https://github.com/ben-gitdev/fly-gym
- **Method:** FlyWire FAFB v783 sparse RNN (~139k units); virtual retina (L1/L2/L3); **DAgger** imitation vs. VFH*+PID teacher; MuJoCo differential-drive (not a fly body).
- **Evidence:** arXiv abstract and HTML PDF describe DAgger / MuJoCo / FlyWire; repo README is titled as the FLYNN companion and cites arXiv:2607.00025.

### Antennal-grooming connectome + body replay — [NeLy-EPFL/antennal-grooming](https://github.com/NeLy-EPFL/antennal-grooming)

Connectome-derived antennal-grooming network plus kinematic replay in a MuJoCo/FARMS fly body; FlyVis-style networks trained to emulate coordination.

- **Paper:** Özdil et al., “Centralized brain networks controlling antennal grooming coordination,” *Nature Communications* (2026). [DOI 10.1038/s41467-026-72152-x](https://doi.org/10.1038/s41467-026-72152-x). Preprint: [bioRxiv 10.1101/2024.12.17.628844](https://doi.org/10.1101/2024.12.17.628844).
- **Code:** https://github.com/NeLy-EPFL/antennal-grooming (depends on SeqIKPy, FARMS/MuJoCo, and a FlyVis fork).
- **Method:** 3D kinematics → inverse kinematics → MuJoCo contact replay; connectome activation/silencing screen; FlyVis-trained ANNs for perturbation experiments.
- **Evidence:** Nature Communications page and repo README both point at the same title/DOI; repo lists FARMS and FlyVis as runtime dependencies.

## Search notes / negatives

- `magicmayonaise/Fruit-Fly-Foraging` appeared in web-index snippets (hemibrain/FlyWire GCN + PPO/REINFORCE) but the GitHub URL returned **404** at verification time, so it is not listed as a find.
- FlyBrainLab ([FlyBrainLab/FlyBrainLab](https://github.com/FlyBrainLab/FlyBrainLab); Lazar et al., *eLife* 2021, [DOI 10.7554/eLife.62362](https://doi.org/10.7554/eLife.62362)) is a general executable-circuit workbench, not a locomotion/RL embodiment, so it is omitted from New.
- No additional peer-reviewed whole-brain **connectome-structured locomotion policy** beyond FlyGM (already known) was found on arXiv at search time.
