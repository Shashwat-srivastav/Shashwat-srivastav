# Shashwat Srivastava

### Quantitative ML Researcher

**Systematic Trading · Scientific ML · Peer-Reviewed Research**

21 accepted alphas → Top 10 Global (1,171 participants) → IEEE ICIP 2026 → ITU Innovation Award

---

## Evidence Grid

| 🏆 TOP 10 GLOBAL | 📈 21 ALPHAS | 📊 2.5 PEAK SHARPE | 📄 IEEE ICIP | 🛰️ ITU AWARD |
|:---:|:---:|:---:|:---:|:---:|
| Avenir × HKU | WorldQuant BRAIN | Live Trading | Workshops 2026 | Innovation Award |
| 1,171 participants | Gold tier | +4.3% net return | Accepted paper | 6 of 27 finalists |
| 200+ universities | | | | |

**Verification:** [Avenir × HKU](https://www.hkubs.hku.hk/media/school-news/web3-competition-brought-by-hku-business-school-and-avenirgroup/) · [ITU Results](https://aiforgood.itu.int/from-orbit-to-impact-celebrating-the-winners-of-the-ai-and-space-computing-challenge/) · [Portfolio](https://shashwat-srivastav.github.io/portfolio/)

---

## What I Research

I build models for **decisions where the data is noisy, the environment shifts, and the model is probably wrong about something.**

```
Alpha research ──────► Systematic trading
       │
       ▼
Physics-informed ML ──► Scientific computing
       │
       ▼
Robust validation ────► Out-of-sample evidence
```

The question isn't:

> *"Did the backtest make money?"*

It's:

> *"Why did it work, when does it stop working, and what breaks when I try hard to break it?"*

---

## Selected Work

### 📈 Systematic Trading — Avenir × HKU Web3.0 Quant Trading Challenge 2025

**Top 10 Global · Final Round · 1,171 participants · 200+ universities · 15 countries**

**Sole quant contributor.** Built and traded the strategy that placed Top 10 globally in Asia's first institution-grade digital asset quantitative trading competition.

**Hosts:** HKU Business School · Avenir Group · HKU Web3 Research Centre · Standard Chartered Foundation FinTech Academy

**Competition structure:**
- Six months, three rounds
- Round 1: Kaggle ranking challenge (weighted Spearman correlation)
- Final Round: Live trading, Grand Final at HKU

**Results:**

| Metric | Value |
|---|---|
| Net Return | **+4.3%** |
| Peak Sharpe | **2.5** |
| P&L | **+540 USDT** |
| Rank | **Top 10 / 1,171** |
| Prize Pool | US$50,000 |

**Strategy Lifecycle:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    STRATEGY LIFECYCLE                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  SIGNAL GENERATION        VALIDATION            EXECUTION      │
│  ┌──────────┐            ┌──────────┐          ┌──────────┐   │
│  │ Momentum │──┐         │ Walk-    │          │ Position │   │
│  │ Mean Rev │  │         │ Forward  │          │ Sizing   │   │
│  │ Volatility│ ├────────►│ OOS      │─────────►│ Costs    │   │
│  │ Fundamental│ │         │ Regime   │          │ Risk     │   │
│  │ Technical │──┘         │ Decay    │          │ Limits   │   │
│  └──────────┘            └──────────┘          └──────────┘   │
│                                                                 │
│  Methodology: Walk-forward ✓ · OOS ✓ · Costs ✓ · Drawdown ✓   │
└─────────────────────────────────────────────────────────────────┘
```

**Verification:** [HKU Business School](https://www.hkubs.hku.hk/media/school-news/web3-competition-brought-by-hku-business-school-and-avenirgroup/) · [Kaggle](https://www.kaggle.com/competitions/avenir-hku-web) · [Finalists](https://phemex.com/news/article/finalists-announced-for-avenirhkuweb30-quant-trading-challenge-38180)

---

### 🧮 Alpha Research — WorldQuant BRAIN

**21 Accepted Alphas · Gold Tier · Peak Sharpe 2.10**

Systematic alpha construction and factor research across multiple market regimes.

**Alpha Research Pipeline:**

```
┌──────────────────────────────────────────────────────────────┐
│                    ALPHA PIPELINE                            │
│                                                              │
│  HYPOTHESIS ──► FORMULATION ──► TESTING ──► ACCEPTANCE      │
│                                                              │
│  "Momentum      Signal         In-sample      Sharpe ≥ 1.5  │
│   persists in    expression     OOS            Turnover OK  │
│   energy                        Decay          Correlation  │
│   sector"                       Capacity       low          │
│                                                              │
│  21 survived this process. Hundreds didn't.                 │
│  The graveyard is the methodology.                          │
└──────────────────────────────────────────────────────────────┘
```

**Signal types explored:**
- Cross-sectional momentum
- Mean reversion
- Volatility-based signals
- Fundamental factors
- Technical indicators

---

### 🛰️ S2WISH — Physics-Informed Water Quality Intelligence

**🏆 Innovation Award — ITU AI & Space Computing Challenge 2026**

**Track 2 · Space Intelligence for Water Quality**

**Named among six Track 2 Innovation Award recipients** in ITU's official results announcement, 7 July 2026.

**Field:**

| Metric | Value |
|---|---|
| Entrant teams | 258 teams, 36 countries |
| Final round | 106 teams, 13 countries |
| Awarded teams | 41 teams, 12 countries |
| Track 2 Awarded | 9 of 27 finalists |
| Innovation Award recipients | **6 of 27** |

**System Architecture:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    S2WISH ARCHITECTURE                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  SENTINEL-2          DOMAIN              ML MODEL              │
│  IMAGERY             CONSTRAINTS         (Physics-Informed)    │
│  ┌─────────┐        ┌─────────┐         ┌─────────┐           │
│  │ Bands   │        │ Water   │         │ Spectral│           │
│  │ B2-B8A  │───────►│ Optics  │────────►│ Features│           │
│  │ Angles  │        │ CDOM    │         │ + Domain│──┐        │
│  │ Metadata│        │ Physics │         │ Priors  │  │        │
│  └─────────┘        └─────────┘         └─────────┘  │        │
│                                                        ▼        │
│                                              ┌──────────────┐  │
│                                              │  PREDICTIONS │  │
│                                              │  Turbidity   │  │
│                                              │  Suspended   │  │
│                                              │  Sediment    │  │
│                                              │  CDOM        │  │
│                                              └──────────────┘  │
│                                                                 │
│  Methodology: Domain-informed ✓ · Baselines ✓ · Ablations ✓   │
└─────────────────────────────────────────────────────────────────┘
```

**Research output:** Manuscript under review at **ITU Journal on Future and Evolving Technologies** (Manuscript ID ITUJ-2026-0045).

**Verification:** [ITU Results](https://aiforgood.itu.int/from-orbit-to-impact-celebrating-the-winners-of-the-ai-and-space-computing-challenge/) · [Challenge Rules](https://aiforgood.itu.int/ai-and-space-computing-challenge/) · [Entrant Pool](https://www.ecns.cn/cns-wire/2026-07-10/detail-ihfhemcv3618490.shtml)

---

### 📡 Sentinel-1 RFI Detection — IEEE ICIP Workshops 2026

**Physics-Constrained Dual-Architecture Ensemble**

**Accepted paper.** Gaur & Srivastava (second author).

**Why this matters:** Standard image classification treats satellite data as arbitrary images. This fails when the physics of the sensor matters.

**Model Architecture:**

```
┌─────────────────────────────────────────────────────────────────┐
│              DUAL-ARCHITECTURE ENSEMBLE                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  SAR QUICKLOOK                                                  │
│       │                                                         │
│       ├──────────────┬──────────────────────┐                   │
│       ▼              ▼                      ▼                   │
│  ┌─────────┐   ┌───────────┐        ┌──────────────┐           │
│  │ CNN     │   │ Physics   │        │ Transformer  │           │
│  │ Branch  │   │ Features  │        │ Branch       │           │
│  │         │   │ (Domain)  │        │              │           │
│  └────┬────┘   └─────┬─────┘        └──────┬───────┘           │
│       │              │                     │                   │
│       └──────────────┼─────────────────────┘                   │
│                      ▼                                         │
│               ┌─────────────┐                                  │
│               │  ENSEMBLE   │                                  │
│               │  FUSION     │                                  │
│               └──────┬──────┘                                  │
│                      ▼                                         │
│               ┌─────────────┐                                  │
│               │ RFI / CLEAN │                                  │
│               └─────────────┘                                  │
│                                                                 │
│  Ablations ✓ · Baselines ✓ · Physics constraints ✓            │
└─────────────────────────────────────────────────────────────────┘
```

**Status:** Copyright transferred; to appear.

---

### 📰 NarrativeX — Multilingual Disinformation Dataset

**DISARM-TTP-Annotated · Hindi / Urdu / English**

Content-level disinformation research dataset with threat-vector annotations.

**Status:** In progress. Target: ICWSM deadline 15 January 2027.

The goal isn't another:

> *"AI detects fake news"*

demo.

The goal is to make the underlying **data and threat representation** useful for actual research.

---

### 🧮 RealPDE — Scientific ML for Partial Differential Equations

Exploring machine-learning approaches to scientific computing and PDE problems.

```
Can a learned approximation respect the structure of the problem it is trying to solve?
```

**Status:** Live competition.

---

## Research Methodology

Every project I publish includes:

| Component | Why It Matters |
|---|---|
| **Baseline comparison** | Without a baseline, "good" is meaningless |
| **Out-of-sample testing** | In-sample results are optimistic |
| **Failure analysis** | Understanding when the model breaks |
| **Reproducible code** | Research should be verifiable |
| **Ablation studies** | Which components actually matter? |

---

## Things I Don't Trust Easily

- Suspiciously beautiful backtests
- Models without serious baselines
- "SOTA" without checking the comparison
- Metrics nobody can explain
- Results that disappear when the data split changes
- My own hypothesis before the experiment attacks it

> *If I can't define how a claim could fail, I probably haven't defined the claim properly.*

---

## Trajectory

```
2023: ML Engineering (MLH Fellowship, OWASP, Backend)
       │
       ▼
2024: Scientific ML (RIC Presentation, S2WISH begins)
       │
       ▼
2025: Quantitative Research (WorldQuant BRAIN, Avenir × HKU)
       │
       ▼
2026: Peer-Reviewed Research (IEEE ICIP, ITU Award, J-FET under review)
```

The throughline: **building models that survive contact with reality.**

---

## Technical Stack

```
Python · NumPy · Pandas · SciPy · PyTorch · scikit-learn
Docker · FastAPI · PostgreSQL · Redis · AWS · GCP
Matplotlib · Plotly · LaTeX · Git
```

Mostly Python. Occasionally Docker gets involved. Nobody is happy.

---

## Additional Evidence

| Category | Result |
|---|---|
| HackVSIT 5.0 | 1st Runner-Up, 150+ teams (RouteCraft) |
| MLH Hacky New Year | Most Innovative Hack (ColabWorks) |
| Meta Hacker Cup 2025 | Global rank 4,042 / 20,000+ |
| MLH Fellowship | Advanced to project-matching stage |
| RIC 2024, IIT Guwahati | Oral presentation (Dyslexia subtype classification) |

---

## Contact

[LinkedIn](https://www.linkedin.com/in/shashwat-srivastava-08394a225/) · [X](https://x.com/shashwat1322) · [Email](mailto:shashwat1322001@gmail.com) · [Portfolio](https://shashwat-srivastav.github.io/portfolio/)

---

**If you have a good problem, a questionable hypothesis, or a dataset that looks innocent but clearly isn't — I'm interested.**

*Currently reading: market microstructure papers, satellite physics documentation, and my own backtest results with increasing suspicion.*

---
