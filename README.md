# Akaki Jvarsheishvili

Computer science student at Caldwell University (B.S., minor in Mathematics, expected May 2027). I build machine learning systems and test them with pre-specified, reproducible evaluations.

[Portfolio](https://akok3.github.io/) | [LinkedIn](https://www.linkedin.com/in/akaki-jvarsheishvili-891b40359/)

## Research

**Is SPY an Intraday Tripwire? Detecting Volatility Regime Shifts and Testing Their Cross-Market Reach.** Preprint with Dr. Cagla Yildirim: [doi.org/10.5281/zenodo.24512827](https://doi.org/10.5281/zenodo.24512827).

Four intraday regime detectors on SPY, evaluated under a protocol fixed in advance with 43 logged amendments. A separately written implementation reproduced all 344 Gaussian HMM runs of the final evaluation. The paper reports its negative results: simple volatility rules matched or beat the detectors, and no market showed a consistent move after SPY switches.

Code, protocol, amendments and results: [spy-regime-research](https://github.com/akoK3/spy-regime-research)

## Projects

- **MarketLens** is a live SPY regime detection engine and market intelligence app on Google Cloud. [Live site](https://marketlens-k1k1.duckdns.org)
- **CampusFix** is a completed team capstone: a FastAPI and PostgreSQL ticketing backend with a local AI classifier and a fine-tuned Qwen3-8B model, evaluated on frozen datasets. [Repository](https://github.com/akoK3/CRUD-campus-fix)
- **MarketRegimeAI** is a supervised ML pipeline for SPY regime classification, benchmarked across four model families with walk-forward validation. [Repository](https://github.com/akoK3/MarketRegimeAI)
