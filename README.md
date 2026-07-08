# BlueShip AI

Systematic research engineering: autonomous alpha research pipelines and fixed-income analytics.

## Flagship: The Anomaly Graveyard
**[blueship-ai.github.io/anomaly-graveyard](https://blueship-ai.github.io/anomaly-graveyard/)** — a live, nightly-updated public record of published trading strategies tested with institutional rigor by an autonomous six-stage research pipeline (idea extraction from new arXiv papers → feature engineering → 20-year costed backtests → Newey-West / 10,000-draw bootstrap / out-of-sample validation → HMM regime audit → six-factor decomposition). Every verdict ships with the rejection reason and the dollars-honest outcome versus an index benchmark. The pipeline runs autonomously every night; verdicts publish on a 3-day lag.

Design principles baked into the pipeline:
- **Maker–checker separation** — the agent that generates a hypothesis never judges it.
- **Deterministic statistics** — LLM agents do language (paper reading, critique); all numbers come from code.
- **Self-verifying runs** — z-score canaries, look-ahead canaries, dollar-neutrality identities checked before any result is trusted.
- **Documented bias** — the equity universe is survivorship-biased and every report says so.

## Fixed-income analytics
Single-file, dependency-free HTML dashboards demonstrating institutional fixed-income methodology — bond math (YTM, duration, convexity, DV01, key-rate durations), multi-strategy stress testing with regime-conditional correlations, cross-capital-structure analysis, and probability-distribution-based signal integration. **All dashboard market data is simulated for demonstration.**

## Interests
OTC credit market microstructure, probabilistic pricing (full-distribution signals over point estimates), prediction-market calibration, and event-driven research on SEC EDGAR data.
