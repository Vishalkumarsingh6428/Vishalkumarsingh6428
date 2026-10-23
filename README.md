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

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/financial-filings-copilot"><b>financial-filings-copilot</b></a><br>
Evidence-grounded agentic RAG for SEC 10-K/10-Q filings · Recall@5 58% → 75% · <a href="https://financial-filings-copilot.streamlit.app">Live app</a><br>
<img src="https://img.shields.io/badge/FOCUS-RAG_%7C_LANGGRAPH_%7C_AGENTS-0d1117?style=for-the-badge&labelColor=3b9be0"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/financial-filings-copilot?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/financial-filings-copilot?style=flat-square">
</td>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/ALNM-detection-multimodal"><b>ALNM-detection-multimodal</b></a><br>
Lymph node metastasis detection from ultrasound + clinical data · AUC 0.8344 · Grad-CAM<br>
<img src="https://img.shields.io/badge/FOCUS-MULTIMODAL_%7C_MEDICAL_AI-0d1117?style=for-the-badge&labelColor=2ea44f"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/ALNM-detection-multimodal?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/ALNM-detection-multimodal?style=flat-square">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/ocr-rag-llm-pipeline"><b>ocr-rag-llm-pipeline</b></a><br>
Self-hosted OCR + RAG + LLM pipeline: upload documents and chat with them<br>
<img src="https://img.shields.io/badge/FOCUS-RAG_%7C_OCR_%7C_AUTOMATION-0d1117?style=for-the-badge&labelColor=e0943b"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/ocr-rag-llm-pipeline?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/ocr-rag-llm-pipeline?style=flat-square">
</td>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/Personal_Finance_Environment"><b>Personal_Finance_Environment</b></a><br>
Personal finance environment for decision-making under uncertainty (OpenEnv compliant)<br>
<img src="https://img.shields.io/badge/FOCUS-RL_%7C_ENVIRONMENTS-0d1117?style=for-the-badge&labelColor=8a4fe0"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/Personal_Finance_Environment?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/Personal_Finance_Environment?style=flat-square">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/reliable-dpo-finetuning"><b>reliable-dpo-finetuning</b></a><br>
Direct Preference Optimization fine-tuning experiments<br>
<img src="https://img.shields.io/badge/FOCUS-LLM_%7C_FINE--TUNING-0d1117?style=for-the-badge&labelColor=8a4fe0"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/reliable-dpo-finetuning?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/reliable-dpo-finetuning?style=flat-square">
</td>
<td width="50%" valign="top">
<a href="https://github.com/Vishalkumarsingh6428/ipl-ai-predictor"><b>ipl-ai-predictor</b></a><br>
IPL match prediction project<br>
<img src="https://img.shields.io/badge/FOCUS-ML_%7C_PREDICTION-0d1117?style=for-the-badge&labelColor=e0504a"><br>
<img src="https://img.shields.io/github/stars/Vishalkumarsingh6428/ipl-ai-predictor?style=flat-square"> <img src="https://img.shields.io/github/forks/Vishalkumarsingh6428/ipl-ai-predictor?style=flat-square">
</td>
</tr>
</table>

<!-- Replace the ipl-ai-predictor and reliable-dpo-finetuning descriptions with what they really do, and fix the focus badges to match. -->

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
