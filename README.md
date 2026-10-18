<h1 align="center">Kumar Harsh</h1>

<p align="center">
  <b>I build complete AI systems — the data pipeline, the model, the decoder, and the interface people actually use.</b><br/>
  <sub>Local-first by default: no API keys, no cloud, nothing leaving your machine unless it has to.</sub>
</p>

<p align="center">
  <a href="https://github.com/kumarharshzzz04/haiku-zero"><b>HAIKU ZERO</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/HadeS">HadeS</a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/jane">Jane</a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/qml-disease-prediction">Quantum ML</a>
</p>

---

## What I do

**Train models, don't just call them.** A 15.8M-parameter transformer with its own tokenizer, written and trained from scratch — because the interesting problems are in the details a library hides.

**Build retrieval that cites.** Every answer in HadeS points at the minute of the lecture it came from, and the decoder refuses to invent the rest. A citation you can click beats a confident paragraph.

**Ship local-first tools.** Files, audio and questions stay on the machine that owns them. No API keys, no telemetry, no per-request cost — the model is the product.

**Analyse data that has to survive scrutiny.** Before the models, there was 13M rows of transaction data, churn analysis and Tableau work. That background is why the AI systems come with numbers and a way to check them.

---

## Selected work

### [HAIKU ZERO](https://github.com/kumarharshzzz04/haiku-zero) — a language model trained from scratch on one laptop

15.8M parameters, its own 4,096-token BPE, two training stages: 54.35M tokens of public-domain poetry, then 39,697 haiku. The decoder enforces 5-7-5 **while writing** instead of retrying afterwards.

**100% exact 5-7-5 · 0% repeated words · 0% invented words · 0.9 s per poem** on a 6 GB laptop GPU, behind a React desk UI and a stdlib HTTP server.

`PyTorch` · `CUDA` · `tokenizers` · `React 19` · `MIT`

### [HadeS](https://github.com/kumarharshzzz04/HadeS) — an offline tutor for 18 hours of lecture video

Turns a lecture series into a searchable tutor. Answers stream with the exact lesson and minute they came from, the video plays in the answer card at that timestamp, and retrieval was validated at **11/11** on a fixed question set.

`Python` · `FAISS` · `faster-whisper` · `Ollama llama3:8b` · `FastAPI` · `React 19` · `MIT`

### [Jane](https://github.com/kumarharshzzz04/jane) — a local-first AI data analyst

Ask a CSV, Excel, JSON or Parquet file a question and get an answer you can audit: Jane runs a local model over your data, writes **read-only DuckDB SQL** you can inspect, and shows the rows behind every conclusion. Nothing is uploaded.

`Python` · `DuckDB` · `Ollama` · `React 19` · `Vite` · `Tailwind v4`

### [Hybrid quantum-classical disease predictor](https://github.com/kumarharshzzz04/qml-disease-prediction) — quantum and classical models, measured honestly

A stacked committee: quantum kernel SVM, bagged variational circuits, a single VQC, and tuned classical baselines combined by an out-of-fold meta-learner. **86.89% on Cleveland (53/61)**, validated with a leakage-free protocol that refits the feature selector inside every fold — plus a 918-patient combined set for scale checks.

`PennyLane` · `scikit-learn` · `FastAPI` · `Python`

---

## Also on the shelf

| Project | What it does | Stack |
|---|---|---|
| [transaction-risk-analysis](https://github.com/kumarharshzzz04/transaction-risk-analysis) | Risk signals across 13M credit-card transactions — channel, amount, merchant and velocity as compounding factors | Python, pandas |
| [telecom-churn-eda](https://github.com/kumarharshzzz04/telecom-churn-eda) | Who churns and why, across 7,000+ customer records | Jupyter, pandas |
| [steam-games-analysis-tableau](https://github.com/kumarharshzzz04/steam-games-analysis-tableau) | Pricing, reviews and release trends across 9,994 Steam titles | Tableau |

---

## Stack

`Python` · `PyTorch` · `tokenizers` · `FastAPI` · `DuckDB` · `SQL` · `scikit-learn` · `PennyLane` · `pandas` · `React 19` · `TypeScript` · `Tailwind v4` · `Tableau`

---

## Currently

Building small models and tools that run on one machine, and writing down what the measurements say — including the experiments that fail.

Open to **AI/ML engineering and builder roles**, and to freelance work on local-first AI or data products. I care about education tools; HadeS is where that started.

---

## Contact

- **Email** — kumar.harshzzz04@gmail.com
- **LinkedIn** — [linkedin.com/in/kumar-harsh](https://linkedin.com/in/kumar-harsh)
