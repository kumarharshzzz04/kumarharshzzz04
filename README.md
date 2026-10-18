<h1 align="center">Kumar Harsh</h1>

<p align="center">
  <b>I build AI systems end to end — data, training, retrieval, evaluation, and the product around them.</b><br/>
  <sub>Comfortable from the tokenizer up: a transformer trained from scratch, RAG that cites where an answer came from, and both shipped behind interfaces people use.</sub>
</p>

<p align="center">
  <a href="https://github.com/kumarharshzzz04/haiku-zero"><b>HAIKU ZERO</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/HadeS">HadeS</a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/jane">Jane</a> &nbsp;·&nbsp;
  <a href="https://github.com/kumarharshzzz04/qml-disease-prediction">Quantum ML</a>
</p>

---

## What I do

**Models and training.** A 15.8M-parameter transformer written from scratch — BPE tokenizer, two-stage pretraining, constrained decoding — plus the probes and gates that keep every claim honest.

**Retrieval and applied LLM systems.** RAG over lecture video and data files, vector search, reranking, grounded answers with sources you can open. Local models where the data cannot move, hosted ones where it can.

**Evaluation, not vibes.** Quality floors, filters-off probes, leakage-free validation. I keep a written record of the experiments that failed, because those are the ones that teach.

**Full-stack delivery.** Python and FastAPI services, React and TypeScript interfaces, SQL, DuckDB, packaging and launchers — everything between a notebook and something a person can actually use.

**Data foundations.** Before the models: 13M rows of transaction data, churn analysis and Tableau. That background is why the AI work arrives with numbers and a way to check them.

---

## Selected work

### [HAIKU ZERO](https://github.com/kumarharshzzz04/haiku-zero) — a language model trained from scratch on one laptop

15.8M parameters, its own 4,096-token BPE, two training stages: 54.35M tokens of public-domain poetry, then 39,697 haiku. The decoder enforces 5-7-5 **while writing** instead of retrying afterwards.

**100% exact 5-7-5 · 0% repeated words · 0% invented words · 0.9 s per poem** on a 6 GB laptop GPU, behind a React desk UI and a stdlib HTTP server.

`PyTorch` · `CUDA` · `tokenizers` · `React 19` · `MIT`

### [HadeS](https://github.com/kumarharshzzz04/HadeS) — an AI tutor for 18 hours of lecture video

Turns a lecture series into a searchable tutor. Answers stream with the exact lesson and minute they came from, the video plays in the answer card at that timestamp, and retrieval was validated at **11/11** on a fixed question set. Whisper transcription, FAISS retrieval and a local LLM, with no API keys to leak.

`Python` · `FAISS` · `faster-whisper` · `Ollama llama3:8b` · `FastAPI` · `React 19` · `MIT`

### [Jane](https://github.com/kumarharshzzz04/jane) — an AI data analyst you can audit

Ask a CSV, Excel, JSON or Parquet file a question and get an answer with the evidence attached: Jane writes **read-only DuckDB SQL** you can inspect and shows the rows behind every conclusion.

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

`Python` · `PyTorch` · `tokenizers` · `CUDA` · `FAISS` · `Ollama` · `faster-whisper` · `FastAPI` · `DuckDB` · `SQL` · `scikit-learn` · `PennyLane` · `pandas` · `React 19` · `TypeScript` · `Tailwind v4` · `Tableau`

---

## Currently

Working across applied ML — small models, retrieval systems, and the evaluation that keeps them honest. Building in public, including the experiments that do not work out.

Open to **AI/ML engineering and builder roles**, and to freelance work on AI or data products. I care about education tools; HadeS is where that started.

---

## Contact

- **Email** — kumar.harshzzz04@gmail.com
- **LinkedIn** — [linkedin.com/in/kumar-harsh](https://linkedin.com/in/kumar-harsh)
