# GitHub profile — github.com/rd51

## Scope

**Required** — these appear on your profile page itself:

1. The README (`publish/README.md`)
2. Bio + location in your profile sidebar — both currently empty
3. Which six repos are pinned
4. Descriptions for those six — pinned cards show name, description and language, and
   yours currently show a blank where the description goes

**Optional, whenever** — everything below the pinned six. Descriptions on the other
21 repos only show on the Repositories tab, not the profile. The empty repos and the
RescueBot typo are housekeeping I noticed in passing, not part of the profile job.

No renames.

## Proposed pins — replacing the current six

Current pins: `Banking-Fraud-Detection`, `customer-retention-intelligence-platform-`, `E-commerce-Business-Intelligence-Dashboard`, `esars-stimulator`, `MLOps`, `NovaMart`

Three of those are weak: `esars-stimulator` is 65 KB, `NovaMart` is 554 KB with no README, and `MLOps` has no README at all.

| # | Repo | Why it earns a pin |
|---|---|---|
| 1 | `Strait-Disruption-DL` | Your most ambitious project. Multimodal deep learning, validated against a real 2026 event. 13.5 MB — the most substantial thing on the account. |
| 2 | `wafa` | Multilingual NLP, fairness audit, and you caught your own leakage bug. The honesty is a feature. |
| 3 | `Banking-Fraud-Detection` | Sequence modelling + attention + stacked ensemble at 6.36M rows. Clean README. |
| 4 | `SDAIM-MLops` | The **only** repo with a live CI badge, Docker, and a deployed Space. This is what proves MLOps rather than claiming it. |
| 5 | `TechNova-Workforce-Optimizer` | Algorithmic bias and ethics. Directly on-theme for Anthropic Fellows and the AI Societal Impact Fellowship. |
| 6 | `RescueBot-POMDP` | POMDPs and Bayesian belief updating — shows reasoning under uncertainty, not just supervised learning. |

## Descriptions — ready to paste

Verified against each repo's actual README.

| Repo | Description |
|---|---|
| `Strait-Disruption-DL` | Supply-chain disruption early-warning system for the Strait of Hormuz, fusing satellite imagery, price signals and geopolitical text into an explainable chokepoint risk index. |
| `wafa` | Multilingual customer retention platform — BiLSTM + DistilmBERT over code-switched Arabic/English/Hindi/Tagalog, churn scoring, and LLM outreach drafts behind human approval. |
| `Banking-Fraud-Detection` | Transaction-sequence fraud and AML detection on 6.36M PaySim records: Conv1D → LSTM → self-attention, stacked under XGBoost, routing to CLEAR / REVIEW / FREEZE. |
| `SDAIM-MLops` | Credit card default risk scorer with a reproducibility-gated GitHub Actions pipeline, Docker packaging and a deployed Gradio service. |
| `TechNova-Workforce-Optimizer` | Ethics-in-AI dashboard exposing algorithmic bias in performance-metric-driven layoffs, over a synthetic 2,400-employee dataset. |
| `RescueBot-POMDP` | POMDP rescue-robot simulator with live Bayesian belief updating over noisy sensor readings, served as a Flask web console. |
| `smartgrid` | Stochastic energy dispatch optimiser balancing renewables, conventional generation and battery storage under demand uncertainty, framed as an MDP. |
| `Stock-Market-Research` | AI-driven study of non-linear interactions between equity markets, VIX and labour indicators, using LSTM and tree ensembles in a Streamlit dashboard. |
| `waselx` | Last-mile delivery network optimisation — graph algorithms, tree and linear structures, sorting benchmarks, with Flask API and Streamlit frontend. |
| `E-commerce-Business-Intelligence-Dashboard` | Streamlit BI dashboard for e-commerce analytics with predictive models, SHAP explainability, knowledge graphs and real-time reporting. |
| `Bank-Data-Linux` | Bank customer classification project. |
| `e-commerce` | *(already has one — current text is 3 lines; suggest trimming to)* Automated e-commerce churn prediction pipeline built on Hugging Face to replace a manual ML workflow. |

## Needs a decision

**1. ~~Wafa — solo or group?~~ Resolved: solo. Both repos stay — your call, nothing breaks.**

The README links to `/wafa`, which exists, so the duplicate costs nothing.

One optional one-line edit: `customer-retention-intelligence-platform-`'s README says
**"MAIB AI 115 · Final Group Project"** on work you built solo. Worth correcting whenever
you're next in that repo. Not urgent, not blocking.

**2. Three repos are empty and currently public:**
- `AI-Credit-Risk-Scoring-` — 0 KB, no files at all
- `SDAIM-2` — 0 KB
- `ai-safety-work-` — 10 KB, no README

An empty public repo named after a project reads worse than no repo. Make them private, delete them, or push the work.

> I told you earlier to pin `AI-Credit-Risk-Scoring-`. That was wrong — I was going off your project record before I checked the repo. It's empty. The credit-risk work that *is* on GitHub is `SDAIM-MLops`.

**3. `RescueBot-POMDP` names the wrong institution.**
Its README says *"S.P. Jain Institute of Management and Research"* — that's SPJIMR in Mumbai, a different school from SP Jain School of Global Management, Dubai, where you actually study. Worth fixing.

**4. Repos with no README — deferred, revisit later.**
`MLOps`, `UAE-Dashboard-DVA`, `esars-stimulator`, `Optimisation-ecologistics`, `insurance`, `Universal-Bank`, `ProjectB`, `Mini-Project-Lab-Work`, `NovaMart`, `lulu-repository`, `luludashboard`

Several look like coursework. When you come back to these, the options are: describe them, archive them, or make them private. Archiving greys them out and signals "finished coursework" rather than "abandoned". Nothing here blocks the profile README.
