# Hi, I'm Vishal Kumar Singh 👋

**AI Engineer** · LLMs • RAG • Multimodal AI · IIT Madras

I build practical AI systems: document-chat pipelines, medical imaging models, fine-tuning experiments and decision-making environments. I like taking an idea from a notebook to something people can actually run, and I contribute to open source along the way.

📫 vishalkumarsingh6428@gmail.com · 🇮🇳 India
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vishal_Kumar_Singh-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishal-kumar-singh-6b3873326)

---

## What I'm working on now

- 🔧 Open-source contributions to **Soup** (merged PR #2064) and **SoupTeam/SoupZero** (October 2026)
- 🧠 Fine-tuning experiments (DPO) and RAG pipelines
- 📈 Improving [Financial Filings Copilot](https://github.com/Vishalkumarsingh6428/financial-filings-copilot) (multi-turn questions, claim-level citations) and RL environments

---

## Open source contributions

### [MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup)
Contributing through my fork ([Vishalkumarsingh6428/Soup](https://github.com/Vishalkumarsingh6428/Soup)).

| PR | What I changed |
|---|---|
| ✅ [#2064](https://github.com/MakazhanAlpamys/Soup/pull/2064) `fix(config): refuse vision row formats on preference tasks, drop pixtral-dpo recipe` (merged) | Fixed [#1867](https://github.com/MakazhanAlpamys/Soup/issues/1867): the `pixtral-dpo` recipe passed config validation and `--dry-run`, then failed after the model loaded because Soup has no vision-preference row path. Config load now refuses `dpo`, `ipo`, `simpo`, `orpo`, `bco` and `preference` combined with `llava` or `sharegpt4v`, with an error that names the task and format. Dropped the broken recipe (170 → 169) and updated the docs. Added 12 refusal tests, text-format controls and a catalog test. Mutation-checked: removing the validator fails all 12 refusal cases. |

I proposed the plan on the issue first, then implemented it and addressed review feedback (recipe-count floor, tighter test assertions, clearer changelog). The maintainer's review is on the PR. This also led to follow-up issue [#2078](https://github.com/MakazhanAlpamys/Soup/issues/2078) (`kto` and `reward_model` accept vision formats too).

### [SoupTeam/SoupZero](https://github.com/SoupTeam/SoupZero)
Started contributing in October 2026. My first pull request was opened on Oct 7.

| PR | What I changed |
|---|---|
| `fix(form): reject wrong-type values in form reads` | Validates `soup.yaml` values when projecting them into the form: rejects non-string `base` and `training.quantization`, and invalid `training.batch_size`. +59 −3, 10 review comments |
| `feat: one-command developer setup` | Added `scripts/setup.ps1` and clearer setup docs so new contributors can get started in one command |
| `fix(identity): raw module docstring` | Made the docstring raw so Windows path examples survive intact |

<!-- Once your PRs are merged, add "✅ merged" next to them. -->

---

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**financial-filings-copilot**](https://github.com/Vishalkumarsingh6428/financial-filings-copilot) · [🔗 Live app](https://financial-filings-copilot.streamlit.app) | Evidence-grounded agentic RAG for SEC 10-K/10-Q filings (15 companies, 75 filings). Hybrid retrieval (dense + BM25 + RRF) with cross-encoder reranking, a LangGraph workflow that grades evidence, retries weak retrieval (max 2) and verifies citations. Recall@5 improved from 58.3% → 66.7% → 75.0% across vector-only, hybrid and reranked setups. FastAPI backend and Streamlit UI | LangGraph, Pinecone, Groq, FastAPI, Streamlit |
| [**ALNM-detection-multimodal**](https://github.com/Vishalkumarsingh6428/ALNM-detection-multimodal) | Detects axillary lymph node metastasis by combining ultrasound images with clinical data (ER, PR, HER2). Test AUC 0.8344, 5-fold CV AUC 0.7997, Grad-CAM explainability | PyTorch, EfficientNet-B0 |
| [**ocr-rag-llm-pipeline**](https://github.com/Vishalkumarsingh6428/ocr-rag-llm-pipeline) | Free, self-hosted pipeline: upload documents, extract text with OCR, chat with them | n8n, Gemini, Supabase |
| [**Personal_Finance_Environment**](https://github.com/Vishalkumarsingh6428/Personal_Finance_Environment) | AI-powered finance environment for decision-making under uncertainty (OpenEnv compliant) | Python |
| [**ipl-ai-predictor**](https://github.com/Vishalkumarsingh6428/ipl-ai-predictor) | IPL prediction project (my most active repo, 20 commits in June 2026) | Python |
| [**reliable-dpo-finetuning**](https://github.com/Vishalkumarsingh6428/reliable-dpo-finetuning) | Direct Preference Optimization fine-tuning experiments | Jupyter, LLMs |
| [**binance-futures-testnet-bot**](https://github.com/Vishalkumarsingh6428/binance-futures-testnet-bot) | Modular CLI for MARKET, LIMIT and STOP-LIMIT orders on Binance Futures Testnet, with validation, logging and unit tests | Python |

<!-- Fill in the ipl-ai-predictor and reliable-dpo-finetuning descriptions with what they actually do and any results. -->

---

## More projects

- [cyber-fraud-detection](https://github.com/Vishalkumarsingh6428/cyber-fraud-detection): fraud detection (Jupyter)
- [heart_disease_prediction](https://github.com/Vishalkumarsingh6428/heart_disease_prediction): classification on health data (Jupyter)
- [loan-Default-pridiction](https://github.com/Vishalkumarsingh6428/loan-Default-pridiction): loan default prediction (rename the repo to fix the spelling)
- [chatbot](https://github.com/Vishalkumarsingh6428/chatbot): my first chatbot (Jupyter)
- Time-Series-Asset project: add the link here with the full repo name

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Focus areas:** LLMs · RAG · Fine-tuning (DPO) · Multimodal learning · Medical imaging · Explainable AI · Time series · Reinforcement learning environments

---

## GitHub stats

![Vishal's GitHub stats](https://github-readme-stats.vercel.app/api?username=Vishalkumarsingh6428&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Vishalkumarsingh6428&layout=compact&hide_border=true)

---

*Open to AI engineering internships and collaborations. Feel free to reach out!*
