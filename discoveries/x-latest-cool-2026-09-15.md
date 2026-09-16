# X / web latest-cool shard (2026-09-15)

Search window: ~14–16 Sep 2026 plus viral items the [14 Sep shard](x-latest-cool-2026-09-14.md) and current README still missed. Ranked by wow-factor (live I/O, new games, dopamine/RL, clever interfaces) and novelty versus README + `discoveries/*.md`. Tweet URLs appear only when an unroll/news/KYM page confirmed a status ID. Direct `x.com` fetches from this environment hit login/edge walls; **do not treat missing IDs as non-existence, and do not invent them**.

GitHub `MaleCNS created:>=2026-09-14` returned **51** repos on 16 Sep 2026; `FlyWire created:>=2026-09-14` returned **44**. This file is not that dump. Quality bar: working link, honest wiring-vs-adapter split, and something a person can watch or play.

**These remain wiring-diagram simulations.** A live site or a shuffled-wiring control is evidence of an interface, not that a fly learned Doom, language, ads, Smash, Deadlock, or chess.

## Hottest new

Ranked by coolness + novelty. “Handle” is the GitHub owner or the X handle when that is the primary source.

### 1. FlyDrones — `SpikeCalls`

- **What:** Webcam / keyboard gestures become optic-flow illusions on fly visual neurons; descending neurons (DNg02 climb/turn, LPLC2/LC4 → giant-fiber DNp01 escape) steer a 3D drone. Open palm climbs, fist holds, rush-the-camera escapes. Browser loop is MiniFly (~850 spiking cells) plus a safety governor; the Python path can load the full MaleCNS graph onto real drone stacks.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/SpikeCalls/FlyDrones · https://spikecalls.github.io/FlyDrones/
- **Dopamine/RL?** no.
- **Why it's cool:** Best new *closed-loop body* I/O since Flyhard. Your hand is the visual world. README is explicit that the browser demo is MiniFly, not 166k cells, and that this is not a living fly.
- **Evidence:** fetched README (gesture table + “the honest part”); live HTTP 200 (16 Sep 2026). Created 15 Sep 2026.

### 2. Fly OCR — `jerryjliu`

- **What:** Frozen MaleCNS (166,700 / 25.6M) as a printed-character reservoir. A 266,628-parameter decoder reads 1,024 downstream cells after a 100 ms presentation. 87.6% on a 1,632-glyph / 68-class benchmark; 5.7% CER on eight selected PDF lines; 21/21 and 44/45 exact cells on two numeric table crops. A 3° tilt breaks segmentation.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/jerryjliu/fly_ocr (local Vite replay viewer; teaser mp4 in Releases). No public host found.
- **Dopamine/RL?** no (supervised decoder only; wiring frozen).
- **Why it's cool:** New interface (reading, not a game). Same honesty pattern as FLM: the fly graph is a reservoir; skill is the tiny readout. Quantum Zeitgeist recap **14 Sep 2026**.
- **Evidence:** fetched README + report table; GitHub API created 13 Sep 2026; 79★ on 16 Sep. Listed in [`github-latest-cool.md`](github-latest-cool.md) #1 but **not** in the 14 Sep X shard or the README. News: https://quantumzeitgeist.com/fruit-fly-ocr/

### 3. Fly Marksman / fruitfly-lab — `webergithub`

- **What:** 3,963-neuron FlyWire LC10a → AOTU019/025 → DNa02 pursuit circuit aims and fires in the browser with **no training**. Same circuit on ViZDoom *defend_the_center*: real wiring 10.2 kills/episode vs scrambled-wiring 0.7 (degree- and sign-preserving shuffle; n=10).
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/webergithub/fruitfly-lab · https://opcstudio.cc/fly-aim/ · 3D soma view `?focus=brain`
- **Dopamine/RL?** no (fixed calibrated readout).
- **Why it's cool:** Rare published **scrambled-wiring Doom** control on a real visual pathway, plus a one-click live aim trainer. Bearing→LC10a Poisson drive is engineered; the author says so.
- **Evidence:** fetched README scoreboard; live HTTP 200. Created 15 Sep 2026.

### 4. Fly Space Program — `steph4n-gh`

- **What:** Full retained MaleCNS (166,700 / 25.6M) sees 32×24 eyes + body/odor channels; a learned ten-command readout flies a simulated booster. Release claim: **60/80** safe landings on unseen starts; covering both eyes or killing flight indicators → **0/80**. Orbital missions: no stable orbit. Physical “Fly Cube” is concept art, not hardware.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/steph4n-gh/fly-space-program · https://fly.steph4n.dev/
- **Dopamine/RL?** yes (trained motor readout / complete-flight reward; wiring frozen).
- **Why it's cool:** Kerbal-class I/O nobody else shipped. Failure tables are in the README. Distinct from already-listed [fly-fpv](https://github.com/joey-david/fly-fpv) (hoop course) and [fly-self-driving](https://github.com/suanmiao/fly-self-driving) (street).
- **Evidence:** fetched README evidence table; live HTTP 200. Created 14 Sep 2026.

### 5. flywalker — `franBec`

- **What:** Stonkfly’s unmodified MaleCNS kernel walks real Lisbon Mapillary streets looking for pastel de nata. FLY vs COIN (random) vs GREEDY (crow-flies). Progress → 15 PAM11; regression → 2 PPL101. v1: FLY ≈ COIN, nobody arrived. v2 adds an engineered **goal-meter column** on each candidate frame because raw visual salience carried no navigation signal (meter vs live brain: per-junction correlation −0.07).
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/franBec/flywalker (local walker + oracle; no public host).
- **Dopamine/RL?** yes (Stonkfly PAM11 / PPL101 pulses; KC→MBON “may or may not accumulate anything useful”).
- **Why it's cool:** Dopamine street-navigation with baselines and an honest “we had to paint the answer on the frame” note. Treat arrival claims as unproven; v2 results were still `pending` in the README on 16 Sep.
- **Evidence:** fetched README honesty + v1 table. Created 15 Sep 2026.

### 6. Fruitless — `nicodunks`

- **What:** Block modeled mAL output on 166,606 classified MaleCNS cells and ask whether male-associated cues activate P1-related candidates. Local Three.js replay. Result: male-cue responses rise after the block; **female cues still win**. “Increased responsiveness, not male preference.”
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/nicodunks/fruitless (local `npm start`; no public host).
- **Dopamine/RL?** no.
- **Why it's cool:** The only inspectable courtship-intervention demo. 404 Media (15 Sep) names a Nico Christie “bi fly”; **that is not this repo** (Christie’s public GitHub has no MaleCNS project). Do not merge the two.
- **Evidence:** fetched README; 33★; created 10 Sep 2026. Already in [`github-latest-cool.md`](github-latest-cool.md); still missing from README.

### 7. Super Smash Bros + Rubik’s cube — [@nickwalton00](https://x.com/nickwalton00) — **X-only**

- **What:** “i just spent the last day training a real fly brain to play super smash brothers wins against the bots 2/3 matches” and “i trained the fly to solve rubiks cube.”
- **Tweet URL:** Smash https://x.com/nickwalton00/status/2098537903110652087 · Rubik’s https://x.com/nickwalton00/status/2098301053372621070 (both IDs from [unrollnow Smash](https://www.unrollnow.com/status/2098537903110652087) and [unrollnow Rubik’s](https://www.unrollnow.com/status/2098301053372621070)). Dated 13 Sep 2026 in the archive chrome.
- **Repo / live:** none found (`gh search` smash/rubik + MaleCNS empty). Do not equate with [lntegrals/flycube-public](https://github.com/lntegrals/flycube-public) (a different Rubik’s *decision-loop* repo, 0★, no author link).
- **Dopamine/RL?** unknown (“trained” in the tweets; methods not inspectable).
- **Why it's cool:** New games the 14 Sep shard never logged, with archived status IDs. Treat 2/3 Smash wins as an unverified clip, not a published control table.
- **Evidence:** unrollnow HTTP 200 for both IDs (16 Sep 2026).

### 8. Deadlock — [@jetsetworm](https://x.com/jetsetworm) — **X-only**

- **What:** KYM card (updated 13 Sep): “the fly can play deadlock… trained the MaleCNS v1.0… using YOLOv5 and video pretraining data… most success on Graves.”
- **Tweet URL:** **not listed as a numeric status ID** on the [KYM video page](https://knowyourmeme.com/videos/440448-fruit-fly-brain-simulations) fetched here — so no `status/` URL in this file.
- **Repo / live:** none found.
- **Dopamine/RL?** claimed video pretraining / attention aiming; not inspectable. YOLO in the loop is a computer-vision front-end, not a fly retina.
- **Why it's cool:** Viral miss (Valve hero shooter). Methods are a red flag for “the fly learned Deadlock.”
- **Evidence:** KYM video page HTTP 200 with that caption.

### 9. fly-flappy — `ns2250225`

- **What:** Full MaleCNS in a Web Worker plays Flappy Bird. `PURE BRAIN` (raw DNp01 decode) vs `ONLINE TRAIN` / `FAST TRAIN` logistic readout. Live: https://8cef51e4.pinme.dev/
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/ns2250225/fly-flappy · https://8cef51e4.pinme.dev/
- **Dopamine/RL?** yes (online / fast-train readout; wiring frozen). Safety rails forbid flap-when-above-pipe.
- **Why it's cool:** Cleanest *new* full-graph Flappy with a public host (9★ by 16 Sep). Still a Flappy — overlaps already-listed `arjunkshah12345-hash/fly-flappy-bird`, `jackspiece/flappy-fly`, `ykakade/flappy-fly-connectome`.
- **Evidence:** fetched README; live HTTP 200. Created 15 Sep 2026.

### 10. Fly Habitat — `vasu-devs`

- **What:** FlyWire v783 on WebGPU + anatomical flybody in MuJoCo, in a 3D house. Food/water/rest/nursery/eggs; inherited steering and goal readouts across generations. Extends already-listed [webgpu-fly](https://github.com/abgnydn/webgpu-fly).
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/vasu-devs/fly-habitat · https://fly.siddhvasudev.com/
- **Dopamine/RL?** yes (browser learners + optional reinforcement; wiring measured, learners authored). More generations “do not guarantee improvement.”
- **Why it's cool:** Best *life-cycle* live site of this window. Credit the upstream WebGPU fly.
- **Evidence:** fetched README; live HTTP 200. Created 15 Sep 2026.

### 11. Fast-weight navigation clip — [@BrainsAndTennis](https://x.com/BrainsAndTennis) + [@nicochristie](https://x.com/nicochristie) — **X-only**

- **What:** 404 Media (15 Sep) embeds: “I and @nicochristie ran the fly connectome and found the group of neurons (hΔH, hΔA, hΔI and hΔG) that could allow the fly to navigate using fast synaptic weight updates, not neural activations. This is fast-weight continual learning in a fly, something current LLMs don't do!”
- **Tweet URL:** **no numeric status ID** on the fetched 404 Media page — so none listed here.
- **Repo / live:** none found. Nico Christie’s public GitHub has no MaleCNS repo.
- **Dopamine/RL?** claimed fast synaptic updates; not inspectable.
- **Why it's cool / why skepticism:** Highest-ambition *learning* claim of the window. hΔ cells are real FlyWire/MaleCNS types; “continual learning LLMs can't do” is a slogan until there is a protocol, shuffled control, and code. Same article’s “bi fly” (Christie programmed the fly to be attracted to other males) also has **no first-party URL**.
- **Evidence:** https://www.404media.co/a-digital-fly-brain-has-taken-over-the-internet/ HTTP 200 (15 Sep byline).

### 12. 404 Media kebab / LinkedIn (unverified color)

- **What:** 15 Sep recap headline: the fly has been “cutting doner kebab” and “write LinkedIn posts.” Body never names a kebab or LinkedIn-writing repo. LinkedIn hits in search are Xenova’s already-listed WebGPU canvas and the MaleCNS paper posts.
- **Tweet URL:** none for kebab / LinkedIn-writer.
- **Repo / live:** none found (`gh search` kebab + MaleCNS empty).
- **Dopamine/RL?** n/a.
- **Why it's here:** So later editors do not hunt a ghost “kebab fly.” Treat as journalism flavor around known clips (Andrei Apanasik Doom screenshot, evnsnclr Minecraft, Stonkfly, heaven).
- **Evidence:** fetched 404 Media article.

### Other verified 14–16 Sep notables (not ranked into the top)

| Name | Pointers | Dopamine/RL? | Note |
|---|---|---|---|
| **fly-xiangqi** | https://github.com/tomzlabs/fly-xiangqi · https://fly-xiangqi.vercel.app/ | no (fixed untrained readout) | Chinese-chess fork of already-listed `tolatolatop/fly-chess`. Live HTTP 200. Created 15 Sep. |
| **flywire-pong** | https://github.com/buhuia1/flywire-pong · https://buhuia1.github.io/flywire-pong/ | unknown | FlyWire Pong; live HTTP 200. Overlaps cobanov’s FlyPong. |
| **flydurak** | https://github.com/KremlevLev/flydurak | yes (batched RL + GRU on the graph) | Durak; 165k/10.5M. Local `python run.py`. Baseline vs GRU/LSTM unfinished. |
| **FlyCoder** | https://github.com/tolga-ileri/FlyCoder | no | 166,700 neurons “trying to center a div.” Joke I/O; demo mp4 in-repo. |
| **fly-shogi** | https://github.com/nyoki-mtl/fly-shogi | unknown | Shogi + MaleCNS. Created 15 Sep; not audited beyond API description. |
| **flybrain-dogfight** | https://github.com/Mihir717/flybrain-dogfight | yes (dopamine / hit rewards, evolutionary readout) | JSBSim dogfight. Created 15 Sep; local. |
| **MaleCNS-Driving-Robot** | https://github.com/AlexNoyanov/MaleCNS-Driving-Robot | no | Physical 2WD: Arduino + Pi + Mac LIF on an **AL(R) ~4,057-cell subset**. Not whole-CNS. |
| **drosophila-brain-mlx** | https://github.com/Kisame76/drosophila-brain-mlx | no | Apple-Silicon MLX port of Shiu LIF; sugar→MN9 vs degree-preserving shuffle (MN9 silent). Tooling, not a game. |
| **HEREISCB/flybrain** | https://github.com/HEREISCB/flybrain | no | Kitchen-table 3D fly, local browser. Overlaps flyverse / virtual-fly-lab. |
| **flybrain-playground** | https://github.com/mingdianliu/flybrain-playground · https://flybrain-theater.ming1001.chatgpt.site/en.html | no | Stimuli + 3D activity. Live HTTP 200. Created 16 Sep. |
| **Fruitfly-reviewer** | https://github.com/pbomaster/Fruitfly-reviewer | trained extractive head | FLM-adjacent paper reviewer “without a pretrained LLM backbone.” Fresh; not audited. |
| **FLModel/flm** | https://github.com/FLModel/flm | no | Org created 11 Sep; repo created 15 Sep. README still `git clone nftechie/flm`. **Rehost, not a new model.** Live chat remains https://fly-language-model.vercel.app/ |
| **train-your-fly** | https://github.com/eudald-seeslab/train-your-fly | trained gains + KC readout | FlyWire-constrained vision toolkit (created 2025). Cobanov added it **14 Sep**; not a Sep-wave toy. |
| **nftechie Doom tweet ID** | https://x.com/nftechie_/status/2097711063135383642 | PPL101 (already listed) | Previously “status ID not independently archived.” Now confirmed via [unrollnow](https://unrollnow.com/status/2097711063135383642). |

Thin / skip-as-new-brain (same-day stubs, forks, empty): `Thespaceblade/flappy-fly` (still a sketch), `fr303388/stonkfly` and `royaldynamo128-gif/stonkfly-bybit` (Stonkfly copies), `hznameai-cmyk/FlyWire` (empty-ish name squat), `Quillotaku/fly-away-from-security` (meme + “seguridad”), `ChihHsiangChien/maleCNS` (already flagged).

## Already known (skip-list)

Do not re-list as discoveries. Confirmed still in README or prior shards.

**Canonical viral / nftechie / games:** DOOMFLY (`nftechie/doomfly`, **297★** on 16 Sep; tweet `2097711063135383642` now archived), Stonkfly (`nftechie/stonkfly`, **690★**; tweet `2098012107652391357`), FLM (`nftechie/flm`, **74★**; live chat still up; no new nftechie fly repo — GitHub is still doomfly / stonkfly / flm), Fly / Wirehead, Fly64 / Mario 64 (`ornata/fly`, tweet `2097004115826200898`), NeuroCraft Fly (`evnsnclr`, 135★, still landing-page), Beat Saber (`@_lyraaaa_`, tweet `2097527368919470162`), Aimbug, Bad Apple, Fly social network / TheFlybook (tweet `2098371978612924425`, **still no public repo**), Fly Dino, Swat, Kick the Fly, Fly Poker, fly-brain-poker, Flyhard, FlyTris, fly-escape, CyberFly, DesktopFly, Fly Brain Minecraft, Ruby Project, Same Smell, swat-or-buy, Fly Tic-Tac-Toe, Fruit Ninja, Fruit fly utopia, flybrain-intransitive, PersonConnectome, fly-hero, flybrain-snake, fly-flappy-bird, FlyBrain-HalfLife, flybrain.app, flydoom (`mutkuoz`), FLYWATT, Faiku, FLYcasso, Infinite Sugar, Xenova fruit-fly-simulation, FlyScroll, Scrollfly, OpenFly, StonkFlyRH, Richy, TraderFly, FlyTV, Polyfly, fruitfly.trade, flycoinrh, fruit-fly-fund.

**14 Sep shard already ranked:** Fly Parking Lab, FLY desktop pet (`VaheOfficial`), ConnectomeFly / realflybrain.com, parallel parking (`@alright_mark`), Strandbeest (`Frankweb33` / mock backend), fly-brain-atlas, cobanov/awesome-fly, FLYT3, firefly, flybeats, fly-connectome-lm, Johnny Silverfly / chonchurik, InstarCage, fly_ocr (GitHub shard only), fly-brain-billiards, mindmeld, closed-loop-fly, eganeganegan/flydoom.

**Science / bodies:** FlyGM, FlyGym / NeuroMechFly, flybody, flyvis, Shiu LIF model, FLYNN, fly-fpv, fly-self-driving, flyverse, webgpu-fly, train-your-fly (now that cobanov listed it).

**TheFlybook follow-up:** unrollnow for `2098371978612924425` still has no URL in the archive text. nftechie GitHub (16 Sep) is still doomfly, stonkfly, flm.

**Fruit fly heaven (news):** 404 Media + GoogleAI unroll still have no first-party heaven URL. Closest repo remains `ML-Chen/fruit-fly-utopia`.

**“Bi fly” (404 Media / Christie):** no repo. Closest *inspectable* courtship intervention is `nicodunks/fruitless`, which is **not** a preference flip.

## Viral / news recap (14–16 Sep)

- [404 Media — “A Digital Fly Brain Has Taken Over the Internet”](https://www.404media.co/a-digital-fly-brain-has-taken-over-the-internet/) — **15 Sep 2026**. Recap of Minecraft, Doom, Beat Saber, Stonkfly, parking, heaven; names kebab / LinkedIn / bi fly / Peter Wang clip without first-party URLs for those four.
- [Quantum Zeitgeist — Fly OCR](https://quantumzeitgeist.com/fruit-fly-ocr/) — **14 Sep 2026**.
- [DailyCoin — Stonkfly](https://dailycoin.com/stonkfly-simulated-fly-brain-cryptocurrency-trading/) — **15 Sep 2026**. Recap only; no new method.
- GIGAZINE / Gizmodo / Tom’s Hardware / TechSpot / PC Gamer / KYM: still the 6–12 Sep Doom + Mario + Beat Saber + Stonkfly wave. No new GIGAZINE follow-on found after the 9 Sep piece.
- KYM video cards still circulating: Deadlock (13 Sep update), Strandbeest (14 Sep). No kebab / guitar / drone / shogi cards found.
- Cobanov [`awesome-fly`](https://github.com/cobanov/awesome-fly) last content push **14 Sep 10:50Z** (FLYT3 + train-your-fly). Not yet listing FlyDrones / Marksman / Space Program / fly_ocr.

## Handle check

| Handle | 14–16 Sep status |
|---|---|
| [@nftechie_](https://x.com/nftechie_) | No new public fly repo. Doom status ID now archived (`2097711063135383642`). FLM chat still 200. Stars up (doomfly 297 / stonkfly 690 / flm 74). |
| [@barrelshifter](https://x.com/barrelshifter) | `ornata/fly` last push 8 Sep; no new repo. |
| [@evnsnclr](https://x.com/evnsnclr) | NeuroCraft still the public landing page (135★). 404 Media interview; no new GitHub demo. |
| [@_lyraaaa_](https://x.com/_lyraaaa_) | No new public repo. Beat Saber remains X-only. |
| [@stonkfly](https://x.com/stonkfly) | Still unresolved beyond StonkFlyRH ads. |
| New this pass | `@jetsetworm` (Deadlock), `@nickwalton00` (Smash / Rubik’s), `@BrainsAndTennis` + `@nicochristie` (fast-weight / bi-fly claims). |

## Search notes / method

- GitHub Search API (16 Sep 2026): `MaleCNS created:>=2026-09-14` **51**; `FlyWire created:>=2026-09-14` **44**; `MaleCNS created:>=2026-09-01` **152** (was 126 on 14 Sep). Extra queries: kebab, deadlock, PAM11, wirehead, smash, rubik — kebab/deadlock/smash/rubik + MaleCNS returned **0** repos.
- News/web: 404 Media, Quantum Zeitgeist, DailyCoin, GIGAZINE (no new piece), Know Your Meme video cards, unrollnow, cobanov README, MarkTechPost / Artificial Scientific (FLM, already known).
- X/nitter: first-party X HTML not usable. Status IDs only from unrollnow / KYM / 404 Media text. New archived IDs: `2097711063135383642` (Doom), `2098301053372621070` (Rubik’s), `2098537903110652087` (Smash). Deadlock and Peter Wang clips have **no** archived numeric ID here.
- HTTP GET of live URLs on 16 Sep 2026: FlyDrones Pages, opcstudio.cc/fly-aim, pinme fly-flappy, fly.siddhvasudev.com, fly.steph4n.dev, fly-xiangqi.vercel.app, flywire-pong Pages, flybrain-theater, FLM Vercel, 404 Media, Quantum Zeitgeist, KYM Deadlock card, unrollnow Doom/Smash/Rubik’s — all **200**.
- Star counts from the GitHub API were used only as a ranking hint and **are not copied into the README**.

## Suggested README fold-ins (high bar)

Promoted in the accompanying README edit: **FlyDrones**, **Fly OCR**, **Fly Marksman**, **Fly Space Program**, **Fruitless**, **Smash / Rubik’s X-only** (archived IDs), **Deadlock X-only** (KYM, no status ID), the **nftechie Doom status ID** on the existing article line, and **404 Media**. Left out of the list: flywalker (v2 pending, painted goal meter), fly-flappy (third Flappy), habitat (webgpu-fly extension), xiangqi (chess fork), FLModel/flm (rehost), fast-weight / bi-fly / kebab (no inspectable artifact).
