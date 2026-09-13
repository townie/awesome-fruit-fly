# Trading / dopamine / wirehead shard

Research date: 2026-09-13  
Repo: [townie/awesome-fruit-fly](https://github.com/townie/awesome-fruit-fly)

Scope: fruit-fly connectome demos involving **trading, markets, wireheading, dopamine/reward, scrolling feeds, addiction metaphors, crypto/memecoins**. Links below were fetched or confirmed via GitHub/HTTP; none are invented.

## New

### OpenFly — marketcalls

- **What it does:** MaleCNS v1.0 (166,700 neurons) watches painted NIFTY / INDIAVIX / straddle-premium bars and paper-trades an intraday short NIFTY straddle through OpenAlgo. Default readout is a fitted statistical decoder; a separate learning arm uses fly dopamine. Paper/analyzer mode is default; live is opt-in. No profitable edge claimed.
- **Repo and/or X URL:** https://github.com/marketcalls/openfly
- **Reward scheme:** PAM11, PPL101 (learning arm only). Default path has no reward. Learning arm: +reward → 15 PAM11; −reward → 2 PPL101, then KC→MBON updates. Reward is “how far NIFTY moved vs what the straddle priced,” not cash P&L.
- **Evidence note:** README describes both arms, dopamine-pulse sanity checks, and “no profitable learning.” Homepage field points at OpenAlgo docs, not a public fly dashboard.

### StonkFlyRH — CryptoGatsu / @StonkFlyRH

- **What it does:** Stonkfly fork that hunts Robinhood Chain memecoins as Uniswap v3 pools appear, screens rugs, and swaps USDG via `exactInputSingle`. Chart pixels → MaleCNS photoreceptors → buy/sell/hold. Posts fills as @StonkFlyRH. Also launches its own Pons coin (paired with GOOGL).
- **Repo and/or X URL:** https://github.com/CryptoGatsu/StonkFlyRH · https://x.com/StonkFlyRH
- **Reward scheme:** PAM11, PPL101. Gains → 15 PAM11; losses → 2 PPL101; a rug it bought doubles aversive pulse length. Candidate KC→MBON memory. Engineered signals, not modeled pain.
- **Evidence note:** README + contract/wallet addresses. X handle is advertised in-repo (HTTP fetch of x.com returned 503 from Twitter’s edge, typical for bots). Distinct from nftechie/stonkfly (Coinbase spot).

### Richy The Fly — PunzRH / @RichyTheFly

- **What it does:** Separate PunzRH project from Gregor. Full MaleCNS v1.0 “smells” Pons coins on Robinhood Chain, renders a chosen chart onto 3,335 photoreceptors, and reads DNp20 L/R for buy/sell/hold from its own wallet. $RICHY pool fees (80%) fund the fly. Uses a stonkfly/DOOMFLY kernel plus RH-chain brokers.
- **Repo and/or X URL:** https://github.com/PunzRH/richythefly · https://x.com/RichyTheFly
- **Reward scheme:** PAM11, PPL101. Δequity → 200 ms into 15 PAM11 or 2 PPL101 → KC→MBON depression; second memory books realized P&L by “smell bucket.”
- **Evidence note:** README documents on-chain addresses and the PAM11/PPL101 loop. Advertised site https://richythefly.com returned **404** on 2026-09-13; GitHub + X remain the verified pointers. Author says the fly was rugged on its second coin; profitable learning not claimed.

### TraderFly — SotoAlt

- **What it does:** Male CNS LIF (repo: 176,422 neurons / 6.3M synapses from neuPrint) tastes token 24h-return/volatility. Sugar GRNs → MN9 = BUY; looming LC4/LPLC2 → giant fiber = ESCAPE sell; wind/grooming → aDN = TAKE PROFIT. Live site lets anyone feed a token; $TFLY on Robinhood Chain. Exit thresholds are kept private.
- **Repo and/or X URL:** https://github.com/SotoAlt/traderfly-brain · https://traderfly.xyz
- **Reward scheme:** none. No PAM11/PPL101 P&L pulse. Market state is encoded as sugar / bitter / looming / grooming Poisson drive. App/wallet code is not in this repo.
- **Evidence note:** Live page on 2026-09-13 showed a stash (TFLY, GOOGL, AI, PONS, …) and a public decision log (BUY / ESCAPE / TAKE PROFIT / REJECT / IGNORE) with tx links. Validate suite checks sugar→MN9 and looming→giant fiber.

### FlyTV — gsoloviev

- **What it does:** TradingView Pine strategy: 995-neuron / 17k-connection distillation of a MaleCNS subgraph. Looming (LC4/LPLC2 → DNp01 giant fiber) treats a selloff as an approaching object (flatten). Command-neuron map: DNp09 long, MDN exit, DNa01/02 flip, DNg11 wait. Mushroom bodies learn from realized P&L. Tested on BTCUSDT H1; does **not** beat buy & hold; fees wipe the print.
- **Repo and/or X URL:** https://www.tradingview.com/script/nmnHkA02-FlyTV-a-real-fruit-fly-connectome-trading-on-your-chart/
- **Reward scheme:** other (PAM / PPL1 families). Realized P&L drives dopaminergic PAM and PPL1 onto KC→MBON (4,934 plastic synapses in this build). Not the 15-cell PAM11 / 2-cell PPL101 Stonkfly set.
- **Evidence note:** Open-source TradingView publication. Includes shuffled-weight control (real wiring produces giant-fiber spikes; shuffled does not). FlyWire deliberately unused (non-commercial license).

### Polyfly — Higgsfield (no public GitHub found)

- **What it does:** Live neural trader on **one** Polymarket contract (Fed +25 bps Sept 2026). Order-book bid/ask/spread/history → photoreceptor-style streams → 166,700-neuron / ~25.6M-connection model → BUY/SELL/HOLD, then hard $100 / $10 / −$20 / 24-order/day gates. Public ledger of settled fills.
- **Repo and/or X URL:** https://polyfly.higgsfield.app/
- **Reward scheme:** other. Page says marked P&L becomes “reward or aversive stimulation” and updates plastic edges. Does **not** name PAM11 or PPL101.
- **Evidence note:** Fetched 2026-09-13: live telemetry, YES position, and a dated fill table. No GitHub repo turned up under polyfly + connectome. Architecture text matches MaleCNS scale, not FlyWire FAFB.

### FlyDegen — flydegen.fun (deployment disabled)

- **What it does:** Closed-loop FlyWire FAFB v783 LIF (~138,639 neurons). Market tape (paper FLYDGEN bonding curve, or armed pump.fun / DexScreener mint) encoded as sugar/bitter/antennal Poisson rates. MN9 = BUY, DN1/DN2 = SELL, aBN1 = GROOM, else HOLD. Explicitly **no** backprop / RL / PnL fine-tune. Public visitors see paper only.
- **Repo and/or X URL:** https://flydegen.fun/docs (Vercel host; see evidence)
- **Reward scheme:** none. Docs state there is no reinforcement learning and no PnL fine-tuning. Sensory analogy only (green candle = sugar, dump = bitter).
- **Evidence note:** Web-search index of `/docs` quotes the MN9/DN/aBN1 table, FAFB v783 counts, and paper-vs-live rules. Direct fetch on 2026-09-13 returned **HTTP 402** (`x-vercel-error: DEPLOYMENT_DISABLED`). No public GitHub owner found. Treat as a documented demo whose hosted UI is currently off. Unrelated: flydegen.neocities.org is a generic Solana meme page, not this connectome lab.

### Scrollfly — sebastian-stapf

- **What it does:** MaleCNS watch-time demo: fly watches ShortVideo clips (and an optional live TikTok “For You” companion), predicts watch time, “likes” mid-prediction, and scrolls at the predicted time with a Fly/Wirehead-style 3D replay. Readout trained on 500 videos, evaluated on 50; **does not beat a constant baseline**. Connectome stays frozen.
- **Repo and/or X URL:** https://github.com/sebastian-stapf/scrollfly · https://sebastian-stapf.github.io/scrollfly/ · live companion: https://sebastian-stapf.github.io/scrollfly/live/
- **Reward scheme:** none. Frozen graph + trained watch-time readout. Credits Stonkfly and Fly/Wirehead; no PAM11/PPL101 trading loop.
- **Evidence note:** README + GitHub Pages 200. Live TikTok path says frames stay in a local Chrome companion; GitHub Pages never receives the personal feed. Prediction accuracy “unvalidated.”

### FlyScroll — ranagwho

- **What it does:** MaleCNS “doomscroller”: short-form reels (local MP4s or live YouTube Shorts via Playwright) into R1–R8. Stays on a clip while novelty-compartment MBON activity stays high; scrolls when KC→novelty-MBON synapses habituate (or max-watch timeout). Spectator shows a neon MaleCNS wiring plate.
- **Repo and/or X URL:** https://github.com/ranagwho/Fruitfly-Doomscroller
- **Reward scheme:** other. Habituation / prediction-error novelty on mushroom-body synapses, not PAM11 profit pulses. README: does **not** inject frame-difference current into KCs or directly stimulate T4/T5/LC detectors.
- **Evidence note:** README + demo GIF. `--scale visual` (~70k) vs `--scale full` (~166k). Listed in cobanov/awesome-fly as FlyScroll.

### Infinite Sugar — cnqso

- **What it does:** Browser artwork: FlyWire whole-brain LIF (139,255 neurons) in a terrarium with **continuous sweet-GRN stimulation**. Motor output mostly disconnected; no visual input from the cage — a wirehead / “pleasant life” metaphor (inspired by *Infinite Pain*). No learning or habituation, so it cannot get bored.
- **Repo and/or X URL:** https://github.com/cnqso/infinite-sugar · https://infinitesugar.cnqso.com/
- **Reward scheme:** other. Constant sugar-GRN drive, not P&L. Site telemetry table includes a **PAM (DA)** row among motor/sensory rates; that is displayed activity, not a trading reward rule.
- **Evidence note:** Live page fetched 2026-09-13 (premise + PAM row). Also listed in cobanov/awesome-fly.

### Female Flybrain ($HER) — opifor

- **What it does:** Sister of fruitflydev/flycoinrh using **FlyWire FAFB v783** (139,255 neurons) instead of MaleCNS. Headless Chromium on the Pons launchpad; hex-column retina → L1/L2; DNa02/DNa01/MDN/DNp09 (+ proboscis MNs for click) fill the form. README: launched **$HER** from her wallet at block 60,428,098. Site: femaleflybrain.com.
- **Repo and/or X URL:** https://github.com/opifor/flybrain-female · https://femaleflybrain.com
- **Reward scheme:** none documented for P&L. This fork is a launch-form / cursor demo, not a PAM11 trader. Any mushroom-body “reward” language lives in the upstream flycoinrh writeup, not in the portions of this README that describe her loop.
- **Evidence note:** femaleflybrain.com returned HTTP 200. Distinct sex/dataset from already-known flycoinrh / $FLYBRAIN.

### flywire.live — iyz2013 / @FlyWireLive

- **What it does:** Robinhood Chain **market visualizer**, not a trader. Confirmed Pons/DEX swaps become buy (green) / sell (red) sensory current in a MaleCNS LIF; the 3D fly rises on buys and drops on sells. Token rooms by contract; `/colony` shows many migrated coins. Fly never signs a tx.
- **Repo and/or X URL:** https://github.com/iyz2013/flywire-live · https://flywire.live · https://x.com/FlyWireLive
- **Reward scheme:** none. Authored sensory mapping of other people’s swaps. Pink reserved for fee inputs (live feed does not decode fees).
- **Evidence note:** README is explicit that trade mappings are application behavior. Fits the memecoin/markets cluster as a spectator, not an agent.

### Stonkfly Lab — paappraiser

- **What it does:** Laptop-sized **mushroom-body** paper-BTC lab inspired by Stonkfly, **not** the 166k graph. Market factors become an odor alphabet (return, vol, inventory, partner vote) → 800 KCs → buy/sell MBON pools. Optional two-fly agreement. Dashboard at localhost:7474.
- **Repo and/or X URL:** https://github.com/paappraiser/stonkfly-lab
- **Reward scheme:** other (PAM / PPL1 motif). Delayed dopamine on the KC snapshot of the last action (three-factor KC→MBON). Not identified 15 PAM11 / 2 PPL101 cells.
- **Evidence note:** README argues Stonkfly’s chart-on-retina + turning-neuron decoder is the wrong organ for learning, and that Stage 0 planted odors should learn while live BTC may sit on HOLD.

### Quantum Fly — stancsz

- **What it does:** Research skeleton: bounded MaleCNS subgraph (4,096 segments / 160k edges in the published snapshot) as a sparse prior, optional 4-qubit PennyLane score, vs no-graph controls on cached FRED S&P 500 features. Offline only. “Weird brain. Boring controls. No magical returns.”
- **Repo and/or X URL:** https://github.com/stancsz/quantum-fly
- **Reward scheme:** none. No PAM11/PPL101. Connectome is a structural reservoir/prior, not a dopamine trader.
- **Evidence note:** README + verification doc. Historical gate passed; forward edge unproven. In-scope as a markets experiment, not a live demo.

### YannickBeck / stonkfly (Gold / OANDA) — plan only

- **What it does:** **No implementation yet.** Written plan for a full FlyWire FAFB v783 LIF that trades **XAU_USD** on OANDA Practice (€1000 fictional, never live). Market as odor; gain as sugar; loss as bitter; energy budget; 8-fly GeNN batch; plasticity only at KC→MBON.
- **Repo and/or X URL:** https://github.com/YannickBeck/stonkfly
- **Reward scheme:** other (planned). Sugar/bitter for mark-to-market on the open position; not PAM11/PPL101. CLAUDE.md: “Reward ist Mark-to-Market auf der aktuellen Position.”
- **Evidence note:** Repo contains CLAUDE.md, `docs/PLAN.md`, and `ops/preflight.sh` only. Included so the gold-market variant is not lost; it is not a running demo.

## Already known (excluded from New)

These were given as already catalogued. Confirmed they still exist; not re-listed as discoveries.

| Name / handle | Pointers | Reward scheme | Note |
|---|---|---|---|
| **Stonkfly** — nftechie / @nftechie_ / @stonkfly | https://github.com/nftechie/stonkfly · https://stonkfly-three.vercel.app/ | PAM11, PPL101 | Coinbase engineer Alex Wormuth; BTC-USDC chart pixels; paper $100 default. Wide news coverage Sep 2026. |
| **Fly / Wirehead** — mattyhempstead | https://github.com/mattyhempstead/fly-wirehead | PAM11 (artificial video drive) | “Born to fly. Forced to scroll.” Insect Shorts every 3s; 20 mV-equivalent current to 15 PAM11 while video plays. Addiction/pleasure not established. |
| **Doomfly** — nftechie | https://github.com/nftechie/doomfly | PPL101 | Damage → 2 PPL101 aversive cells. Survival learning not demonstrated. |
| **fruitfly.trade** — fruitflytrader | https://github.com/fruitflytrader/fruitfly.trade · https://fruitfly.trade | none (MB learning failed) | MaleCNS LIF; Fdg=BUY, MDN=SELL on Axiom Pulse / RH chain. Sugar validation works; odor code / conditioning does not. |
| **Gregor** — PunzRH | https://github.com/PunzRH/gregor | (not re-audited; empty README via API) | “A real fruit-fly connectome kept alive by its coin.” Separate from Richy. |
| **flycoinrh / FLYBRAIN** — fruitflydev | https://github.com/fruitflydev/flycoinrh · https://flybrain.online | other (invented MB reward, per third-party writeups) | 165,122-neuron LIF fills Pons launch form; $FLYBRAIN on Robinhood Chain. |
| **the_buzz** — TropiFloAI | https://github.com/TropiFloAI/the_buzz | none | 7,500-neuron FlyWire reservoir ESN vs Random Forest on BTC; backtest comparison, not a closed-loop dopamine trader. |
| **ruby-project** dopamine Minecraft | (given; not re-hunted as new) | — | Left in Known. Nearby Minecraft/dopamine work exists (NeuroCraft Fly, flyproject.io) but was not treated as this shard’s job to rename. |

## Not added

- **Forks / viewers of known projects:** `torronen/stonkfly`, `jonleach323/stonkfly`, `Bgihe/stonkfly-dashboard` (read-only Stonkfly UI), `JangYeongSil69420/fly-wirehead-kaggle-version`, extra `flycoinrh` forks.
- **Wallet-index repos** (`kane-rox/wallets-`, `flybook-git/wallets`) — no connectome demo.
- **zebralink/zebralink** — zebrafish, not fruit fly.
- **lixiang1076/fly-brain** — dopamine-modulated MB chat; no market / feed / wirehead framing.
- **Generic $FLYDegen meme pages** (flydegen.neocities.org) — no connectome.

## Search notes

GitHub repo search (`MaleCNS`, `fruit fly connectome`, `stonkfly`, `flycoinrh`, `doomfly`, `fly-wirehead`) plus news (The Register, Tom’s Hardware, PANews, Protos) and live pages. TCMB “fly sets rates” mention in PANews had no verifiable repo/demo. No invented URLs.
