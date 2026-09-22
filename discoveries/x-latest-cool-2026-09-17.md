# X / web latest-cool shard (2026-09-17)

Search window: ~16–18 Sep 2026 (UTC fetch 18 Sep) plus viral items the [15 Sep shard](x-latest-cool-2026-09-15.md), [GitHub 15–16 Sep shard](github-latest-cool-2026-09-15.md), and current README still missed. Ranked by wow-factor (live I/O, new games, dopamine/RL, clever interfaces) and novelty versus README + `discoveries/*.md`. Tweet URLs appear only when an unroll/news/KYM page confirmed a status ID. Direct `x.com` fetches from this environment hit login/edge walls; **do not treat missing IDs as non-existence, and do not invent them**.

GitHub `MaleCNS created:>=2026-09-16` returned **51** repos on 18 Sep 2026; `FlyWire created:>=2026-09-16` returned **30**. `MaleCNS created:>=2026-09-01` is now **212** (was 152 on 16 Sep). This file is not that dump. Quality bar: working link, honest wiring-vs-adapter split, and something a person can watch or play.

**These remain wiring-diagram simulations.** A live site or a silenced-cell control is evidence of an interface, not that a fly learned Asteroids, Morse, sales, jigsaws, or shawarma.

## Hottest new

Ranked by coolness + novelty. “Handle” is the GitHub owner or the X handle when that is the primary source.

### 1. MaleCNS Asteroids — `dohun1214`

- **What:** Full MaleCNS v1.0 (166,700 LIF / 10.5M synapses) plays Atari Asteroids in real time. Two modes on the same graph: **flee** (LC4 → DNp02/DNp11 → 507 VNC cells, turn *away*) and **chase** (LC10a → AOTU019/025 → DNa02/13/15 → 1,076 cells; ipsilateral AOTU025 excitation / contralateral AOTU019 inhibition is the steering sign, not a chosen scalar). Silencing **two DNp11 cells** drops action match to 57.4% and **flips** the turn channel; a random 2- or 20-cell lesion is 100% match; a random 2,000-cell lesion is still 86.7%. Degree-/sign-/weight-preserving LC4 shuffle sends avoidance error from 43.6° to 105°.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/dohun1214/malecns-asteroids (local CUDA/Triton; no public host).
- **Dopamine/RL?** no (fixed biological readouts).
- **Why it's cool:** Best *causal* game demo of this window — the “toggle two identified cells” answer to “how is this not an if-statement?” Distinct from already-listed Fly Marksman (3,963-cell FlyWire aim) and DOOMFLY.
- **Evidence:** fetched README evidence tables (Korean + English). Created 16 Sep 2026. Size 6.4 MB.

### 2. Beat the Fly — `saintiron82`

- **What:** Side-by-side jigsaw race in one tab (209 KB, no server). 7,858 MaleCNS photoreceptor + L1 cells, 7,107 signed edges in `brain.bin`. The fly is shown every one-swap-away board and reports L1 distance to the finished picture; enumerating swaps is the wrapper, not the fly. Unthrottled it finishes 12 pieces in under a second, so the UI gives it **one candidate per 18 ms** (photoreceptor→lamina latency). Shuffle-wiring (same counts, same E/I split, random targets) **solves just as well**; raw pixel difference scores 96.2% of teacher.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/saintiron82/beat-the-fly · https://saintiron82.github.io/beat-the-fly/
- **Dopamine/RL?** no.
- **Why it's cool:** Instant playable “are you smarter than a fly?” with the rare published **negative topology result** on a static spatial task (the fly visual system is a motion system). Korean title: 설마 초파리한테 지겠어?
- **Evidence:** fetched README; live HTTP **200** (18 Sep 2026). Created 17 Sep 2026.

### 3. 9 to Fly — `MarlonSteiner`

- **What:** A fruit fly works in sales. 809 neurons seeded from DNp01 (Giant Fiber) plus every cell with ≥5 synapses onto it (21,086 connections). Phone ring / looming current; the jump is when excitation outruns leak. Live MuJoCo flybody stills. Honest experiment: looming vs receding vs flat peak GF response is **1.00×** — this slice cannot tell expansion from recession; looming computation is upstream (optic lobe). Movement is **keyframed**, not physics. Same author as the 403-walled Medium shawarma essay (no first-party kebab repo on this GitHub).
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/MarlonSteiner/fruitfly-9tofly · https://marlonsteiner.github.io/fruitfly-9tofly/
- **Dopamine/RL?** no.
- **Why it's cool:** New *office-gag* I/O plus a measured failure, not a fake “the fly got startled by Excel.” Distinct from already-listed DesktopFly / Swat GF toys.
- **Evidence:** fetched README (loom/recede table); live HTTP **200**. Created 17 Sep 2026.

### 4. NANDFLY — `wetware-labs`

- **What:** Giant Fiber escape (DNp01 ← top-K LC4/LPLC2 → TTMn) quantized to **661 gates (659 NAND + 2 LATCH)** and deployed as an ownerless BNB Chain contract. Site: call `swat(stimulus)` against the netlist. Keeps **12 of 311** LC4/LPLC2 cells (3.9% of the pathway). Exhaustive 4,096-pattern check vs a LIF reference: **98.9%** jump/no-jump agreement; every miss is a missed jump, zero false jumps. Credits independent convergent work at `BruceLanLan/c3s-reflex-circuits`.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/wetware-labs/nandfly · https://wetware-labs.github.io/nandfly/ · methods https://wetware-labs.github.io/nandfly/methods.html . Advertised BscScan page returned **403** from this agent (do not treat as down).
- **Dopamine/RL?** no.
- **Why it's cool:** Weirdest inspectable artifact of the window — a fly reflex that “earns nothing. It just refuses to die.” Not a token (README is explicit any NANDFLY token is unaffiliated).
- **Evidence:** fetched README + derivation claims; Pages HTTP **200**. Created 16 Sep 2026.

### 5. Fly School — `JaronKBragg7337`

- **What:** Full-ish MaleCNS LIF (165,122 / 10.2M, flycoinrh runtime) taught Morse timing with the fly’s own KC→MBON **depression** rule (PAM reward / PPL1 punish; Hige/Cohn). Input: 50 typed JO-A Johnston’s organ cells. Output: two DNa01 cells. School hours, exams, forgetting half-life. Report card: pooled `.-` 1/90 → 7/90; **`-.` stays 0**; wide-gap `.-` appears *untrained* (output bias). Leg-drive control wipes the exam.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/JaronKBragg7337/fly-school · https://www.heartbeatobservatory.com/school/
- **Dopamine/RL?** yes (measured PAM/PPL1 → KC→MBON depression; learning is weak / mostly null).
- **Why it's cool:** Dopamine + a *school* frame nobody else shipped, with CHOSEN vs MEASURED constants and a public gradebook. Not a claim the fly learned Morse.
- **Evidence:** fetched README table; live HTTP **200**. Created 17 Sep 2026.

### 6. Fly Brain (Boxhead) — `FalinX`

- **What:** Frozen MaleCNS (166,700 / 25.6M, **zero trained weights**) plays a Boxhead-style zombie shooter. Encoder → visual projection neurons; 1,314 descending neurons → keys. Survival-to-death (24 arenas): hand-written kiter 216 s; **v13 kiter-legs + connectome eyes 197 s** (t = −0.96, statistically level) at 42.7% vs 63.2% hit rate; 3-rule script 104 s; kiter that never shoots stuck on wave 1 at 115 s.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/FalinX/fly-brain (local Python + browser 3D brain; no public host).
- **Dopamine/RL?** no (frozen graph; engineered encoder/decoder).
- **Why it's cool:** New *game* (twin-stick zombie survival) with a published ceiling (no-brain kiter) instead of a vibes clip. Name-collides many `fly-brain` repos.
- **Evidence:** fetched README survival table. Created 16 Sep 2026. Size 43 MB.

### 7. The Fly Hears — `rahilmavani`

- **What:** Speak a digit 0–9. 32 bands → engineered JO drive → **30,000** MaleCNS cells / 1.35M signed edges → logistic reader. Speaker-separated: fly+reader **70.0%** vs scrambled **69.7%** vs audio-features **66.9%** (n = 3,000, six speakers). Local `localhost:8001`; ~6 MB demo bundle; no GPU.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/rahilmavani/fly-hears (local; no public host).
- **Dopamine/RL?** no (supervised reader; wiring frozen).
- **Why it's cool:** New interface (hearing, after Fly OCR’s reading). Same honesty: topology is not the skill.
- **Evidence:** fetched README + results table. Created 17 Sep 2026. 2★ this pass.

### 8. Hand-loom Giant Fiber — `Euraxluo`

- **What:** Browser 5,145-neuron / 687,542-edge MaleCNS LPLC2+LC4 → DNp01/DNp03 loop at 1 kHz. Drag toward the fly: slow (≲0.2 m/s) → GF silent → you swat it; mid/fast → GF spikes → it jumps. In-page speed scan (9 points) and channel ablation (3 conditions) recompute live. Python↔JS engines checked pointwise. Full 166k graph is a *optional* 20 Hz guidance layer, not the hosted toy.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/Euraxluo/fly-brain-drone · https://euraxluo.github.io/fly-brain-drone/
- **Dopamine/RL?** no.
- **Why it's cool:** Best new *one-click GF physics* since Swat. Distinct circuit (LPLC2/LC4 looming, not already-listed Swat’s LC16→MDN) and distinct from `abbosaliboev/fly-brain-drone` (MuJoCo apple-finding WIP).
- **Evidence:** fetched README; live HTTP **200**. Created 17 Sep 2026.

### 9. fly-afterlife — `nsfm`

- **What:** Whole-CNS MaleCNS LIF (162,517 in this build) with a **flyvis** graded optic lobe seamed onto the brain’s own T4/T5 cells on true compound-eye geometry. A FlyWire female shares the room. Timestamped `docs/SEAM.md` notebook: synapse-strength correction for FIB-SEM vs ssTEM, DNp09 walking via 373 real leg MNs, bristle-wall bursts, five meetings in five minutes. Thermotaxis-by-walking is **not** in the model (warmth hits wing MNs first). Local `world/pair.py` + HTML viewer export.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/nsfm/fly-afterlife (local; no public host).
- **Dopamine/RL?** no (closed-loop physiology, not a trainer).
- **Why it's cool:** Highest-ambition *senses-one-at-a-time* lab of the window. Not a game.
- **Evidence:** fetched README status paragraph. Created 17 Sep 2026.

### 10. Music in the Body — `matsuo-koya`

- **What:** Endless Satie/ambient browser instrument. Web Worker on MaleCNS bodies with synapse weight ≥5 (163,997 / 6.2M directed edges). First-person soma flight; authored harmony/timbre (`body-pulse`). Real vs rewired vs no-recurrence comparison in the UI. Positions are a performance layout, not anatomy.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/matsuo-koya/music-in-the-body · https://matsuo-koya.github.io/music-in-the-body/
- **Dopamine/RL?** no.
- **Why it's cool:** Live art nobody else shipped this week (DJ Drosophila / Fly Lab are different I/O). Honest about authored readout.
- **Evidence:** fetched README; live HTTP **200**. Created 17 Sep 2026.

### 11. FlyGambler — `jaylendilkhush2028`

- **What:** FlyWire mushroom body at a betting terminal. Wins → dopamine (PAM), losses → “pain” (PPL1), KC→MBON stores value. Learnable book: climbs $25→$100. Rigged book: variable-ratio hook to $0. Intervention table (n=40): blocking win-driven reinforcement takes ruin ~32%→0%. Advertised live is a Claude artifact URL (HTTP **403** here) — treat as **repo-only**.
- **Tweet URL:** none verified.
- **Repo / live:** https://github.com/jaylendilkhush2028/flygambler (local scripts + pngs). Claude artifact not verified.
- **Dopamine/RL?** yes (PAM / PPL1 on measured KC→MBON).
- **Why it's cool:** Cleanest *addiction-metaphor* MB loop since Infinite Sugar / Fly/Wirehead, with a willpower-doesn’t-help control. Left out of README because the hosted viewer was not reachable.
- **Evidence:** fetched README figures/table. Created 16 Sep 2026. 1★.

### 12. YMCA / kebab / blackjack (news color, still no artifact)

- **What:** [Inquirer / NYT, 17 Sep 2026](https://www.inquirer.com/news/nation-world/fruit-fly-brain-map-simulation-video-games-parking-dancing-research-20260917.html) (Michael Levenson): a fly “dances to the Village People’s ‘Y.M.C.A.’ in response to four tones”; others “playing poker and blackjack and slicing a doner kebab.” Interviews Unthank (Flyhard blinkers) and Wormuth (Doomfly / Stonkfly). 404 Media (15 Sep) already named kebab without a URL. Medium “shawarma” essay by Marlon Steiner HTTP **403**; Steiner’s only MaleCNS repo is 9 to Fly, not a kebab stall.
- **Tweet URL:** none for YMCA / kebab / blackjack (do not invent).
- **Repo / live:** **none found.** `gh search` kebab / YMCA / blackjack / shawarma + MaleCNS → **0** this pass. Poker is already listed (`HappyAny/fly-poker`, `ItayParienty/fly-brain-poker`). Rubik’s remains X-only `@nickwalton00`.
- **Dopamine/RL?** n/a.
- **Why it's here:** So later editors do not hunt a ghost “YMCA fly.” Journalism flavor around known clips.
- **Evidence:** Inquirer HTTP **200**; GitHub name search empty.

### Other verified 16–18 Sep notables (not ranked into the top)

| Name | Pointers | Dopamine/RL? | Note |
|---|---|---|---|
| **GFly** | https://github.com/SimonSaysGiveMeSmile/gfly · https://gfly.site | no | Whole MaleCNS ≥5-synapse graph in-browser (163,997 / 6.2M). Live HTTP 200. Overlaps Xenova / flybrain.app canvases. Created 17 Sep. |
| **fly-operator-lab** | https://github.com/ReapeRAlan/fly-operator-lab | PPO adapter **collapsed** (23→0 overnight); imitation `move` 5/5 | Door Kickers 2 native bridge + 166,700 LIF. Needs a legit Steam copy. Unique game; not README-promoted (binary hook + unproven learning). |
| **abbosaliboev/fly-brain-drone** | https://github.com/abbosaliboev/fly-brain-drone · [DEV 17 Sep](https://dev.to/abbos_aliboev/could-a-real-fly-brain-control-a-drone-70c) | no | MuJoCo apple-finding; FlyVis + authored control. README: **not finished**. Overlaps FlyDrones / fly-fpv. DEV HTTP 200. |
| **FlyOhtani** | https://github.com/gitwub5/FlyOhtani | planned reward on LC4/LPLC2 | Life-sized NeuroMechFly at the plate. **Swing is still scripted**; “아직 어떤 뉴런도 시뮬레이션하지 않는다.” Too early. |
| **Gladiators** | https://github.com/jawaadjariwala/fly-brain-gladiators | no (octopamine gain knobs) | 166,700, two swords, GF dodge. README CLI is still `TODO`; 43 KB. Concept-cool, not runnable here. |
| **fruitfly-life** | https://github.com/leo-bone/fruitfly-life · https://fruitfly-life.app.workbuddy.host | no | Cinematic egg→death; 5,396-type rate cartoon. Live HTTP 200. Empathy art, not a LIF runtime. |
| **flygo** | https://github.com/frsswq/flygo | trained encoder/readout planned | Frozen MaleCNS rate model vs Go 5×5–9×9. Viewer play is **intentionally untrained**. Protocol exists; bake-off not done. |
| **drone-fly** | https://github.com/HaroldHormaechea/drone-fly | PPO on connectome-seeded sparse layer | Racing-drone overlap with fly-fpv / FlyDrones. Not biophysical LIF. |
| **ak7660/fly-brain-escape** | https://github.com/ak7660/fly-brain-escape | type-level gains on frozen 4,296-cell loom path | Created 18 Sep; GitHub `size` 0 at fetch (tree may still be landing). Claimed 99.9% vs shuffled 97.9% (task is easy; linear eye classifier 100%). Do not promote until the bundle is re-checked. |
| **flyonardo-da-vinci** | https://github.com/fruitflydev/flyonardo-da-vinci · https://flybrain.online/flyonardo | no | 165k LIF pen driven by Robinhood Chain; NFT claim. Live HTTP 200. Token wrapper on already-listed flycoinrh lineage. |
| **flyfam** | https://github.com/maumcrez-svg/flyfam · https://flyfam.xyz | unknown | Paper Pons memecoins + token-holder votes. Live HTTP 200. Trading-adjacent. |
| **klmtseng/fly-explorer** | https://github.com/klmtseng/fly-explorer · https://fly-brain-explorer.vercel.app | no | Kids 3D escape-reflex replay (140,024 positioned cells). Name-collides already-listed `brandoncho369/fly-explorer`. Live HTTP 200. |
| **fly-brain-explainer** | https://github.com/cosmiksoul/fly-brain-explainer · Pages 200 | no | Russian explainer + toy sandbox. Pedagogy, not a new loop. |
| **NileshArnaiya/flybrain-cricket** | https://flybrain-cricket.vercel.app | unknown | Shot-selection toy. Live HTTP 200. Not audited beyond description. |
| **hwkim3330/nogeneration** | https://github.com/hwkim3330/nogeneration | no | LM logits + connectome, no text generation. FLM-adjacent. |
| **al0cam/flyview** | https://github.com/al0cam/flyview | no | Recreate the fly’s view from MaleCNS. Thin/new. |
| **greatAlexandria-sys/FlyDecider** | https://github.com/greatAlexandria-sys/FlyDecider | no | Frozen MaleCNS binary email agent. |
| **win10ogod/LFM2-JSpace-Memory** | https://github.com/win10ogod/LFM2-JSpace-Memory | no | LFM2.5-VL + MaleCNS-Titans memory. FLM-adjacent, not a demo. |
| **NeuroCraft copy** | https://github.com/Sinkingfundgaliellarufa9675/neurocraft-fly-public | no | Description clones already-listed evnsnclr landing page. |

Thin / skip-as-new-brain (same-day stubs, empty names, token skins): many untitled `flybrain` dumps (`RofehTattoo`, `Aeronleelucero`, `Sethuram2003`, `Neurosciencer`, `burkun`, …), `mlngaxri/flybraindoom` (untitled Doom namesake), `treewalkr/flybrain-flap` (another Flappy), `zmdo/malecns-learn`, `kissy24/ex-malecns`, `skellywelly/freddy-fruit-fly` (one-line env), `JoeyTrribbiani/fly-buddy` (headless token pet), `SuperCatCraze/FlyBuddy` (Mac pet claim, 9 KB), `Furina-star`-class companions. Stonkfly/doomfly/FLM classroom clones continue; not re-listed.

## Already known (skip-list)

Do not re-list as discoveries. Confirmed still in README or prior shards.

**Canonical viral / nftechie / games:** DOOMFLY (`nftechie/doomfly`, **345★** this pass; last push 9 Sep), Stonkfly (`nftechie/stonkfly`, **744★**), FLM (`nftechie/flm`, **81★**; live chat still the Vercel from the 14 Sep shard), Fly / Wirehead, Fly64 / Mario 64, NeuroCraft Fly, Beat Saber (`@_lyraaaa_`), Aimbug, Bad Apple, TheFlybook (still no public repo on nftechie GitHub — new repo this window is a Homebrew tap, not a fly), Fly Dino, Swat, Kick the Fly, Fly Poker, fly-brain-poker, Flyhard, FlyTris, fly-escape, CyberFly, DesktopFly, Fly Brain Minecraft, Ruby Project, Same Smell, swat-or-buy, Fly Tic-Tac-Toe, Fruit Ninja, Fruit fly utopia, flybrain-intransitive, PersonConnectome, fly-hero, flybrain-snake, fly-flappy-bird, FlyBrain-HalfLife, flybrain.app, flydoom, FLYWATT, Faiku, FLYcasso, Infinite Sugar, Xenova fruit-fly-simulation, FlyScroll, Scrollfly, OpenFly, StonkFlyRH, Richy, TraderFly, FlyTV, Polyfly, fruitfly.trade, flycoinrh, fruit-fly-fund.

**15 Sep shard already ranked:** FlyDrones, Fly OCR, Fly Marksman, Fly Space Program, flywalker, Fruitless, Smash / Rubik’s X-only, Deadlock X-only, ns2250225/fly-flappy, Fly Habitat, 404 Media kebab/LinkedIn/fast-weight/bi-fly (still no first-party URLs), fly-xiangqi, flywire-pong, flydurak, FlyCoder, fly-shogi, flybrain-dogfight, MaleCNS-Driving-Robot, drosophila-brain-mlx, HEREISCB/flybrain, flybrain-playground, Fruitfly-reviewer, FLModel/flm rehost.

**GitHub 15–16 Sep shard already ranked:** Fly Megacode, Open-Fly, DOOM-x-Fly, fruit buffet, bsgelman Fly Hero, Palak fly-guitar, digitalfly, etc. Do not re-add.

**Science / bodies:** FlyGM, FlyGym / NeuroMechFly, flybody, flyvis, Shiu LIF, FLYNN, fly-fpv, fly-self-driving, flyverse, webgpu-fly.

**Cobanov [`awesome-fly`](https://github.com/cobanov/awesome-fly):** still last **content** push 14 Sep 10:50Z (FLYT3 + train-your-fly). Stars 462 this pass (was 326 on 16 Sep). Has not absorbed 16–17 Sep drops.

**YMCA / kebab / blackjack / shawarma / LinkedIn-writer / fruit-fly heaven / bi fly:** still **no inspectable first-party artifact**. Closest courtship intervention remains `nicodunks/fruitless`. Closest heaven remains `ML-Chen/fruit-fly-utopia`. Closest kebab-adjacent *author* is Steiner’s 9 to Fly (sales desk), not a shawarma stall.

## Viral / news recap (16–18 Sep)

- [Inquirer (NYT syndication) — “Is there anything a fruit fly brain can’t do?”](https://www.inquirer.com/news/nation-world/fruit-fly-brain-map-simulation-video-games-parking-dancing-research-20260917.html) — **17 Sep 2026**. Recap + Unthank / Wormuth / Spruston / Matsliah quotes. Names Rubik’s, YMCA four-tone dance, poker, blackjack, kebab **without URLs**.
- [DEV — Abbos Aliboev, “Could a real fly brain control a drone?”](https://dev.to/abbos_aliboev/could-a-real-fly-brain-control-a-drone-70c) — **17 Sep 2026**. First-party write-up of `abbosaliboev/fly-brain-drone` (WIP; FlyVis + authored control).
- [Shelly Palmer — “166,700 Simulated Neurons Are Playing Doom”](https://shellypalmer.com/2026/09/166700-simulated-neurons-are-playing-doom/) — recap of the 4–15 Sep wave (Minecraft, Doom, Beat Saber, Stonkfly, parking, kebab, heaven). No new method.
- 404 Media (15 Sep), Gizmodo / PC Gamer / TechSpot / KYM: unchanged. KYM entry still **updated 12 Sep**; Deadlock card 13 Sep; Strandbeest 14 Sep. **No new KYM video cards** for Asteroids / jigsaw / YMCA / NANDFLY found.
- Medium “How the Viral Fruit Fly Learned to Make Shawarma” (Marlon Steiner): search hit; fetch **403**. No GitHub kebab repo under that user.

## Handle check

| Handle | 16–18 Sep status |
|---|---|
| [@nftechie_](https://x.com/nftechie_) | No new public fly repo (doomfly / stonkfly / flm only). Stars up (doomfly 345 / stonkfly 744 / flm 81). Homebrew tap is unrelated. |
| [@barrelshifter](https://x.com/barrelshifter) | No new repo checked in. |
| [@evnsnclr](https://x.com/evnsnclr) | NeuroCraft still the public landing page. One GitHub *copy* (`Sinkingfundgaliellarufa9675/neurocraft-fly-public`) appeared 17 Sep. |
| [@_lyraaaa_](https://x.com/_lyraaaa_) | Beat Saber remains X-only. |
| New this pass (GitHub, not X IDs) | `dohun1214`, `saintiron82`, `MarlonSteiner`, `wetware-labs`, `JaronKBragg7337`, `FalinX`, `rahilmavani`, `Euraxluo`, `nsfm`, `matsuo-koya`, `abbosaliboev` (DEV 17 Sep). |

No **new archived numeric tweet IDs** this pass. Unrollnow still surfaces the GoogleAI recap thread `2098109357624095155` (already in the 6–12 Sep wave). Do not invent YMCA / kebab status URLs.

## Search notes / method

- GitHub Search API (18 Sep 2026 UTC): `MaleCNS created:>=2026-09-16` **51**; `FlyWire created:>=2026-09-16` **30**; `MaleCNS created:>=2026-09-01` **212**. Quoted `166,700 created:>=2026-09-16` and `fruit fly connectome` / `flybrain` same window used to catch description-only repos (`abbosaliboev`, `ak7660`, `jaylendilkhush2028`). kebab / YMCA / blackjack / shawarma + MaleCNS → **0**.
- News/web: Inquirer 17 Sep, DEV 17 Sep, Shelly Palmer recap, 404 Media, KYM (no post-14 Sep cards), cobanov README (frozen 14 Sep), unrollnow (no new demo IDs).
- X/nitter: first-party X HTML not usable. **Zero new status IDs** archived this hunt.
- HTTP GET on 18 Sep 2026: beat-the-fly Pages, 9tofly Pages, heartbeatobservatory.com/school, Euraxluo Pages, music-in-the-body Pages, nandfly Pages + methods, gfly.site, fruitfly-life host, fly-brain-explorer.vercel.app, cosmiksoul Pages, flybrain-cricket, flyfam.xyz, flyonardo, DEV post, Inquirer — all **200**. Claude FlyGambler artifact **403**. Medium shawarma **403**. BscScan NANDFLY **403** from this IP (Pages still 200).
- Star counts from the GitHub API were used only as a ranking hint and **are not copied into the README**.

## Suggested README fold-ins (high bar)

Promoted in the accompanying README edit: **MaleCNS Asteroids**, **Beat the Fly**, **9 to Fly**, **NANDFLY**, **Fly School**, **Fly Brain (Boxhead)**, **The Fly Hears**, **Hand-loom Giant Fiber (Euraxluo)**, **fly-afterlife**, **Music in the Body**, and the **17 Sep Inquirer/NYT recap** (with the YMCA/kebab/blackjack no-URL caveat). Left out of the list: FlyGambler (hosted artifact 403), GFly (another whole-brain canvas), operator-lab (Steam binary + collapsed PPO), Abbos drone (WIP overlap), FlyOhtani (scripted swing), Gladiators (CLI TODO), fruitfly-life (rate cartoon), flygo (untrained), flyonardo (token), YMCA/kebab/blackjack (no inspectable artifact).
