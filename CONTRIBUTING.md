# Contributing

Thanks for helping keep this list useful. It follows the usual [awesome-list conventions](https://github.com/sindresorhus/awesome/blob/main/awesome.md).

## What belongs here

Prefer **interactive demos, applications, and dopamine / RL experiments** that run a fruit-fly connectome (MaleCNS, FlyWire, MANC/FANC, BANC) or a clearly documented subset of one.

Good additions:

- Live browser / Hugging Face / hosted demos
- Open-source games, trading loops, art pieces, or embodied sims
- Experiments that stimulate identified dopamine cells (PAM11, PPL101, etc.) or use a connectome as an RL policy
- Short, high-signal papers or threads that explain a listed demo

Usually a better fit for [awesome-fruit-fly-connectome](https://github.com/watthem/awesome-fruit-fly-connectome):

- Dataset portals, viewers, and analysis libraries with no demo
- Generic neuroscience tools that happen to mention *Drosophila*

## Style

- Search the README first so we do not duplicate an entry.
- Add one line in the right section:

  `- [Name](canonical-url) - Short factual description.`

  The description starts with a capital letter and ends with a period.
- Link the repo, live demo, and a verified X/Twitter status when those exist. Do not invent tweet IDs, star counts, or ownership.
- Mark **X-only** items when there is no public repo or demo to inspect.
- Say what is engineered (readouts, reward pulses, teacher forcing) versus what comes from the published wiring.
- Note dataset license when it matters: **MaleCNS is CC BY 4.0**; **FlyWire / FAFB is CC BY-NC 4.0**.
- Quality over volume. A clear live demo beats a same-day stub with no README.
- Uncurated search notes live in [`discoveries/`](discoveries/). Fold only the strongest verified items into `README.md`; do not dump a shard wholesale.

## Pull requests

Open one PR per addition or a small batch of closely related items. Please include a sentence on why the project is interesting and how you verified the links.

By contributing you agree that list text is dedicated to the public domain under [CC0 1.0](LICENSE). Linked projects keep their own licenses.
