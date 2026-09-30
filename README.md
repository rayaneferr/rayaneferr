# Rayane Ferrat

**AI Engineer · Machine Learning, LLM & Data Science**

Telecommunications engineer ([ENSEIRB-MATMECA](https://enseirb-matmeca.bordeaux-inp.fr/), Bordeaux INP, 2026), working across machine learning, statistics and software engineering.
I care about measuring things properly before trusting a result.

Looking for a first full-time role in Paris.

## Latest experience

**AI Engineer (intern) · [Lucca](https://www.lucca-software.com/)**, expense reports team · Mar – Sep 2026

Designed, built and used an evaluation bench for LLM-based data extraction from expense receipts (merchant, date, amount, VAT), integrated into the product stack: C#/.NET back end, Angular front end, Python for datasets.

- Deterministic, field-by-field scoring against ground truth (11 weighted fields), persistent and resumable campaigns, full history re-scored when the metric changes
- Latency and cost measured per call, with input tokens split between text and image so cost can be attributed to its cause
- Noise characterised before claiming any gain: log-normal latency fit over ~3,700 calls (R² = 0.98) giving significance thresholds and required sample sizes; ~5 % residual divergence even at temperature 0, traced to provider infrastructure
- 8 configurations compared on accuracy, latency and cost; the selected one is in production
- ~500 campaigns run, ~33k lines of C#, TypeScript and Python, 4 use cases plugged into the generic core

The code is proprietary; a public summary is available as a [poster (PDF, in French)](https://cv-rayane.vercel.app/docs/rapports/poster-lucca.pdf).

## Selected projects

| Project | What it is |
| --- | --- |
| [fr-power-forecast](https://github.com/rayaneferr/fr-power-forecast) | Do time series foundation models beat market-specific models on French day-ahead electricity prices? Accuracy, calibration and cost. |
| [info-reg-bench](https://github.com/rayaneferr/info-reg-bench) | Information-theoretic regularization for LLM fine-tuning: VIB vs label smoothing vs confidence penalty, Qwen2.5 + LoRA, MNLI → HANS. |
| [agora-rag](https://github.com/rayaneferr/agora-rag) | Local semantic search MCP servers over French parliamentary debates and film synopses (bge-m3 + LanceDB, no API key). |
| [letterboxd-film-clustering](https://github.com/rayaneferr/letterboxd-film-clustering) | Unsupervised clustering of my Letterboxd films from synopsis embeddings (sentence-transformers, UMAP, HDBSCAN). |

## Stack

**Main Languages & Tools**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />

**Other Languages**
<br/>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />

**Data Science & ML**
<br/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />

## Contact

[cv-rayane.vercel.app](https://cv-rayane.vercel.app) · [LinkedIn](https://www.linkedin.com/in/rayaneferrat)

[![wakatime](https://wakatime.com/badge/user/ecac6c61-855f-4ef1-bc8f-e01eabfb1a8a.svg)](https://wakatime.com/@ecac6c61-855f-4ef1-bc8f-e01eabfb1a8a)
