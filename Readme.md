<div align="center">

# Hi, I'm Aditya Raj 👋

**AI Engineer · Agentic Systems · RAG · LLM Fine-Tuning**

B.Tech @ NIT Rourkela (Minor in CSE, 2028) · Lead AI Engineer @ Atlas AI Labs · Secretary, ML4E Club

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aditya%20Raj-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-raj-2766621b5/)
[![Email](https://img.shields.io/badge/Email-adityaraj.adi365%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adityaraj.adi365@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-400%2B%20solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nv7l0ciCal/)

</div>

---

## 🧭 About me

I build AI systems that run like production services, not notebook demos: agents that plan and use tools, retrieval pipelines that check their own sources, and fine-tuned models that ship behind an API.

- 🤖 **Agents:** LangGraph state machines, MCP servers and clients, tool use, self-review loops
- 🔎 **Retrieval:** hybrid BM25 + vector search, rank fusion, reranking, corrective RAG, retrieval evals
- 🧪 **Models:** QLoRA fine-tuning, CNNs, gradient-boosted models, evaluation and guardrails
- 🚀 **Shipping:** FastAPI, Docker, CI/CD, cloud deploys on Azure, AWS, Vercel and Hugging Face
- 🎯 Currently looking for **AI Engineering / SDE internships for Summer 2027**

---

## ⭐ Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [🛰️ Atlas — Autonomous AI Agent](https://github.com/Aditya365x/atlas-agent)
An agent that plans a task, searches the web, reads pages and PDFs, runs Python in a locked-down sandbox, searches your documents, reviews its own answer and streams every step live. Also an **MCP server and client**.

- LangGraph plan → act → reflect loop, multi-provider routing with fallbacks
- Hybrid pgvector + BM25 retrieval with RRF, measured by recall@k / MRR / nDCG
- Guardrails, budgets, Prometheus metrics, **53 tests + 2 eval suites in CI**
- [**Live demo**](https://atlas-web.graymeadow-875698b7.centralindia.azurecontainerapps.io) on Azure Container Apps

`LangGraph` `FastAPI` `LiteLLM` `pgvector` `Redis` `MCP` `Next.js` `Docker`

</td>
<td width="50%" valign="top">

### [🧠 CRAG — Corrective RAG: Ask Any PDF](https://github.com/Aditya365x/CRAG)
Upload a PDF and ask questions. CRAG grades every retrieved passage and falls back to web search when the document can't answer, with `[p.N]` / `[web N]` citations on every sentence.

- Hybrid BM25 + MiniLM retrieval fused with reciprocal rank fusion
- LLM relevance grading → CORRECT / AMBIGUOUS / INCORRECT routing
- Sentence-level filtering and a transparent pipeline trace per answer
- [**Live demo**](https://crag-app-tawny.vercel.app) on Vercel

`LangGraph` `FAISS` `BM25` `FastAPI` `Tavily` `Llama 3.3 70B`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🌾 AgriSutra — AI Platform for Oilseed Farmers](https://github.com/Aditya365x/AgriSutra)
Full-stack farm assistant: yield prediction, leaf-disease detection with RAG-based treatment advice, a multilingual agronomy chatbot grounded in oilseed research, and live IoT sensor dashboards.

- CatBoost yield model, Keras fertilizer recommender, CNN disease classifier
- "Krishi Saathi" history-aware RAG chatbot over a library of oilseed research PDFs (FAISS)
- FastAPI + JWT backend, Next.js web app, Flutter mobile app

`FastAPI` `CatBoost` `TensorFlow` `LangChain` `FAISS` `Next.js` `Flutter`

</td>
<td width="50%" valign="top">

### [🧾 Text-to-SQL — Fine-Tuned LLM](https://github.com/Aditya365x/Text-to-SQL-Generator_LLM_Fine_tuned)
Turns plain-English questions into SQL with a fine-tuned 1B-parameter Gemma model.

- QLoRA (4-bit NF4, LoRA rank 8) on `gemma-3-1b-it`, ~15 MB adapter
- Trained on the schema-aware `sql-create-context` corpus
- Two-tier deploy: FastAPI backend → Hugging Face inference Space

`PyTorch` `QLoRA` `PEFT` `Hugging Face` `FastAPI` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [🚨 SETU — Disaster Early-Warning & Coordination](https://github.com/Aditya365x/setu2.0)
The allocation layer between a disaster alert and the teams on the ground: incident clustering, shelter and supply allocation, routing and live dashboards for district control rooms.

- Ingests reports over SMS, IVR and a citizen PWA
- [Operations dashboard](https://setu2-dashboard.vercel.app/) + [Citizen PWA](https://setu2-citizen.vercel.app/)

`FastAPI` `PostgreSQL` `WebSockets` `Docker` `Optimization`

</td>
<td width="50%" valign="top">

### [🤝 Multi-Agent Research System](https://github.com/Aditya365x/multi-agent-collaboration-system)
Three specialized agents (Researcher → Analyst → Writer) collaborate through shared LangGraph state to produce structured research reports.

`LangGraph` `LangChain` `FastAPI` `Docker`

</td>
</tr>
</table>

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Languages** | Python · C++ · SQL · TypeScript |
| **GenAI & Agents** | LangChain · LangGraph · MCP · LiteLLM · Hugging Face · OpenAI · CrewAI |
| **ML / DL** | PyTorch · TensorFlow/Keras · scikit-learn · CatBoost · QLoRA/PEFT · MLflow |
| **Retrieval & Data** | PostgreSQL + pgvector · ChromaDB · FAISS · BM25 · Redis |
| **Backend & DevOps** | FastAPI · Docker · GitHub Actions · Azure Container Apps · AWS · Vercel |
| **Frontend** | Next.js · React · Tailwind CSS |

---

## 🏆 Highlights

- 🥉 **Smart India Hackathon 2025 — National 2nd Runner-Up:** crop-yield prediction model (R² 0.93) on 70K+ samples and a CNN leaf-disease classifier
- 💻 **400+ LeetCode problems** solved, focused on dynamic programming and graphs
- 📜 **IBM Agentic AI & Workflows Specialization** (Coursera): LangGraph, CrewAI, AutoGen
- 👥 **Secretary, ML4E (Machine Learning for Everyone), NIT Rourkela:** run hands-on LLM and agent workshops for a 60+ member community and co-organize inter-club hackathons

---

<div align="center">

📫 Open to **AI Engineering / SDE internships** and collaborations. Reach me at **adityaraj.adi365@gmail.com**

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Aditya365x&show_icons=true&hide_border=true&count_private=true)

</div>
