# Hi, I'm Vishal Kumar Singh 👋

**AI Engineer** · LLMs • RAG • Multimodal AI · IIT Madras

I build practical AI systems: agentic RAG, medical imaging models, voice-agent ML and fine-tuning experiments. I like taking an idea from a notebook to something people can actually run, and I contribute to open source along the way.

📫 vishalkumarsingh6428@gmail.com · 🇮🇳 India
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vishal_Kumar_Singh-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishal-kumar-singh-6b3873326)

---

## Now

- 🔧 Open source: merged PR in **Soup**, contributing to **SoupZero**
- 🧠 Fine-tuning experiments (DPO) and agentic RAG
- 📈 Improving [Financial Filings Copilot](https://github.com/Vishalkumarsingh6428/financial-filings-copilot) (multi-turn questions, claim-level citations)
- 🎙️ Exploring voice-agent latency and turn-taking

---

## Open Source

<table>
<tr>
<td width="50%" valign="top">

**[Soup](https://github.com/MakazhanAlpamys/Soup)**
Fine-tuning toolkit · ✅ PR [#2064](https://github.com/MakazhanAlpamys/Soup/pull/2064) merged<br>
![focus](https://img.shields.io/badge/FOCUS-CONFIG%20VALIDATION%20%7C%20VLM%20%7C%20DPO-0f172a?style=flat-square&labelColor=3b82f6)<br>
![stars](https://img.shields.io/github/stars/MakazhanAlpamys/Soup?style=flat-square&labelColor=374151&color=f59e0b)
![forks](https://img.shields.io/github/forks/MakazhanAlpamys/Soup?style=flat-square&labelColor=374151&color=60a5fa)

</td>
<td width="50%" valign="top">

**SoupTeam/SoupZero**
3 PRs · form validation, one-command dev setup, Windows docstring fix<br>
![focus](https://img.shields.io/badge/FOCUS-VALIDATION%20%7C%20DEV%20EXPERIENCE-0f172a?style=flat-square&labelColor=8b5cf6)

</td>
</tr>
</table>

**Soup #2064** · [`fix(config): refuse vision row formats on preference tasks, drop pixtral-dpo recipe`](https://github.com/MakazhanAlpamys/Soup/pull/2064)
Fixed [#1867](https://github.com/MakazhanAlpamys/Soup/issues/1867): a recipe passed validation and `--dry-run`, then failed after the model loaded. Config load now refuses `dpo`, `ipo`, `simpo`, `orpo`, `bco` and `preference` with `llava` / `sharegpt4v`, with an error naming the task and format. Added 12 refusal tests, text-format controls and a catalog test; removing the validator fails all 12 refusal cases. I posted the plan on the issue first, fixed the review feedback in one commit, and all 17 CI checks passed. It led to follow-up issue [#2078](https://github.com/MakazhanAlpamys/Soup/issues/2078).

**SoupZero PRs**

| PR | What I changed |
|---|---|
| `fix(form): reject wrong-type values in form reads` | Rejects non-string `base` and `training.quantization`, and invalid `training.batch_size`, when projecting `soup.yaml` into the form (+59 −3, 10 review comments) |
| `feat: one-command developer setup` | Added `scripts/setup.ps1` and clearer setup docs |
| `fix(identity): raw module docstring` | Made the docstring raw so Windows path examples survive |

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[financial-filings-copilot](https://github.com/Vishalkumarsingh6428/financial-filings-copilot)** · [Live app](https://financial-filings-copilot.streamlit.app)
Agentic RAG for SEC 10-K/10-Q filings · Recall@5 58.3% → 75.0%<br>
![focus](https://img.shields.io/badge/FOCUS-AGENTIC%20RAG%20%7C%20LANGGRAPH-0f172a?style=flat-square&labelColor=3b82f6)<br>
![stars](https://img.shields.io/github/stars/Vishalkumarsingh6428/financial-filings-copilot?style=flat-square&labelColor=374151&color=f59e0b)
![forks](https://img.shields.io/github/forks/Vishalkumarsingh6428/financial-filings-copilot?style=flat-square&labelColor=374151&color=60a5fa)

</td>
<td width="50%" valign="top">

**[ALNM-detection-multimodal](https://github.com/Vishalkumarsingh6428/ALNM-detection-multimodal)**
Ultrasound + clinical data · AUC 0.8344, 5-fold CV 0.7997 · Grad-CAM<br>
![focus](https://img.shields.io/badge/FOCUS-MULTIMODAL%20%7C%20MEDICAL%20AI-0f172a?style=flat-square&labelColor=22c55e)<br>
![stars](https://img.shields.io/github/stars/Vishalkumarsingh6428/ALNM-detection-multimodal?style=flat-square&labelColor=374151&color=f59e0b)
![forks](https://img.shields.io/github/forks/Vishalkumarsingh6428/ALNM-detection-multimodal?style=flat-square&labelColor=374151&color=60a5fa)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[plivo-ml-md24b031-](https://github.com/Vishalkumarsingh6428/plivo-ml-md24b031-)** (end-of-turn detection)
Audio-only turn-taking for voice agents · ~15% lower response delay (English)<br>
![focus](https://img.shields.io/badge/FOCUS-VOICE%20AI%20%7C%20TURN--TAKING-0f172a?style=flat-square&labelColor=f97316)<br>
![stars](https://img.shields.io/github/stars/Vishalkumarsingh6428/plivo-ml-md24b031-?style=flat-square&labelColor=374151&color=f59e0b)
![forks](https://img.shields.io/github/forks/Vishalkumarsingh6428/plivo-ml-md24b031-?style=flat-square&labelColor=374151&color=60a5fa)

</td>
<td width="50%" valign="top">

**[ocr-rag-llm-pipeline](https://github.com/Vishalkumarsingh6428/ocr-rag-llm-pipeline)**
Self-hosted OCR + RAG + LLM with n8n, Gemini and Supabase<br>
![focus](https://img.shields.io/badge/FOCUS-OCR%20%7C%20RAG%20%7C%20AUTOMATION-0f172a?style=flat-square&labelColor=ec4899)<br>
![stars](https://img.shields.io/github/stars/Vishalkumarsingh6428/ocr-rag-llm-pipeline?style=flat-square&labelColor=374151&color=f59e0b)
![forks](https://img.shields.io/github/forks/Vishalkumarsingh6428/ocr-rag-llm-pipeline?style=flat-square&labelColor=374151&color=60a5fa)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Personal_Finance_Environment](https://github.com/Vishalkumarsingh6428/Personal_Finance_Environment)**
Finance environment for decisions under uncertainty (OpenEnv compliant)<br>
![focus](https://img.shields.io/badge/FOCUS-RL%20ENVIRONMENT%20%7C%20FINANCE-0f172a?style=flat-square&labelColor=8b5cf6)

</td>
<td width="50%" valign="top">

**[reliable-dpo-finetuning](https://github.com/Vishalkumarsingh6428/reliable-dpo-finetuning)**
Direct Preference Optimization fine-tuning experiments<br>
![focus](https://img.shields.io/badge/FOCUS-LLM%20FINE--TUNING%20%7C%20DPO-0f172a?style=flat-square&labelColor=ef4444)

</td>
</tr>
</table>

**More:** [ipl-ai-predictor](https://github.com/Vishalkumarsingh6428/ipl-ai-predictor) · [binance-futures-testnet-bot](https://github.com/Vishalkumarsingh6428/binance-futures-testnet-bot) · [cyber-fraud-detection](https://github.com/Vishalkumarsingh6428/cyber-fraud-detection) · [heart_disease_prediction](https://github.com/Vishalkumarsingh6428/heart_disease_prediction) · [loan-Default-pridiction](https://github.com/Vishalkumarsingh6428/loan-Default-pridiction) · [chatbot](https://github.com/Vishalkumarsingh6428/chatbot)

---

## Highlights

| Highlight | Detail |
|---|---|
| **Merged open-source PR** | Fixed a validation gap in [Soup](https://github.com/MakazhanAlpamys/Soup) (#2064): planned on the issue, mutation-tested the fix, passed all 17 CI checks, and the maintainer filed a follow-up issue from it |
| **Agentic RAG, deployed** | [Financial Filings Copilot](https://financial-filings-copilot.streamlit.app): hybrid retrieval + reranking + LangGraph + citation verification over 75 SEC filings; Recall@5 improved 58.3% → 66.7% → 75.0%, with failures documented |
| **Multimodal medical AI** | ALNM detection from ultrasound + clinical data: AUC 0.8344, 5-fold CV AUC 0.7997, with Grad-CAM explainability |
| **Voice-agent ML** | End-of-turn detection from audio before the pause only (strict causality): ~15% lower response delay on English at 5% interrupted turns; Hindi AUC 0.516 → 0.703 |
| **Education** | IIT Madras |

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Focus areas:** LLMs · RAG · LangGraph · Fine-tuning (DPO) · Multimodal learning · Medical imaging · Speech and turn-taking · Explainable AI · Reinforcement learning environments

---

## GitHub stats

![Vishal's GitHub stats](https://github-readme-stats.vercel.app/api?username=Vishalkumarsingh6428&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Vishalkumarsingh6428&layout=compact&hide_border=true)

---

*Open to AI engineering internships and collaborations. Feel free to reach out!*
