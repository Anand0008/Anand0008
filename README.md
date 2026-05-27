<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&duration=4000&pause=1000&color=38BDF8&center=true&vCenter=true&random=false&width=750&lines=AI+Engineer+%7C+Multi-Model+Systems;Building+Consensus+Intelligence;Cost-Aware+%7C+Production-Grade" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://wankhade.me"><img src="https://img.shields.io/badge/-Portfolio-38bdf8?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="https://linkedin.com/in/anand-wankhade-791089174/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anandwankhade0007@gmail.com"><img src="https://img.shields.io/badge/-anandwankhade0007%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### 👨‍💻 About Me

> **"An Independent Researcher & Production-Grade Builder."**

I am an **AI/ML Engineer** who builds intelligent systems with measurable impact. My work sits at the intersection of complex data, advanced algorithms, and unforgiving real-world constraints—transforming theoretical problems into highly scalable, production-ready solutions. 

I specialize in designing end-to-end machine learning pipelines from the ground up: encompassing rigorous data ingestion, feature engineering, model deployment, continuous monitoring, and automated improvement. I bring a deep foundation in statistical learning, deep learning, and mathematical optimization. 

Crucially, I pair this theoretical rigor with battle-tested experience in delivering infrastructure that survives under extreme operational pressure—a discipline I honed extensively during my tenure in **Production Management at J.P. Morgan Chase** (a non-AI role that taught me how to operate flawless mission-critical systems). I care deeply about the engineering craft: reproducibility, model interpretability, and robust evaluation are never afterthoughts; they are my core principles. I understand fundamentally that the greatest algorithms only matter if they integrate flawlessly with existing systems, empower teams, and drive concrete business objectives.

**In short: I don't just train models; I engineer intelligence.** Bridging the gap between academic rigor and production reliability is my specialty.

When I'm not optimizing data pipelines or researching novel architectures, you'll find me singing 🎤, travelling to new corners of the globe 🌍, or dissecting anime lore. I'm also an avid reader 📚 and a passionate chess player ♟️—always exploring new worlds, whether in code or in reality.

```text
📍 India  •  🎓 B.E. Information Technology (9.59/10)  •  🏢 Ex-J.P. Morgan Chase (Production Management)
```

---

### 🏗️ What I Build

> Three flagships: two production agentic systems shipping today, one published research pipeline behind them.

---

#### 🤖 IDRE Reports Bot
**Telomere** · Agentic AI Reporting Platform · *production, current role*

A **14-agent LangGraph state machine** that converts natural-language operator queries into safe, audited SQL over the IDRE dispute-resolution platform. Custom **MCP tool-use layer** with 7 typed function-calling tools and a mandatory pre-execution **EXPLAIN gate**, XML-injected business rules, and a 14-pattern self-debugging retry loop. Productionized on **AWS via CDK** (EC2 + RDS + Secrets Manager + IAM) with TLS-only read-only DB access, fully-reproducible JSONL audit trails, and **260+ unit tests** gating every deploy.

> 🎯 **97% query-execution accuracy** &nbsp;·&nbsp; ⚡ **sub-second p95 latency** &nbsp;·&nbsp; 🧪 **260+ unit tests**

---

#### ⚙️ Artoo — Agentic SDLC Assistant
**Telomere** · JIRA → Draft GitHub PRs · *production*

An **18-node LangGraph pipeline** that autonomously converts JIRA tickets into Draft Pull Requests (implementation plan + per-file code + AAA tests). Powered by a deterministic Knowledge Retrieval layer (~1,700 git co-change pairs, LLM-summarized file index, scope baselines) and an **Explorer agent** that deep-reads source files via GitHub MCP before code generation. Four quality gates with self-correcting revision loops, **MCP-integrated JIRA + Confluence + GitHub**, SecretStr vaulting + PII sanitization. Deployed on **Streamlit + FastAPI** on AWS.

> 🎯 **~70% file-overlap with dev PRs** &nbsp;·&nbsp; ⏱️ **time-to-first-commit: hours → <15 min** &nbsp;·&nbsp; 🔐 **MCP + secret vaulting**

---

#### 🧠 FLSS — Cost-Aware Multi-Model Consensus
**Independent Research** · *2 papers under Springer review*

A **14-stage Generative AI pipeline** that shifts consensus aggregation from whole-response voting to **atomic schema validation** via Field-Level Structural Synthesis. Verifies individual fields against heterogeneous model outputs — significantly outperforming RAG baselines. **Adaptive Compute Allocation** routes by semantic complexity, filtering 52% of traffic away from flagship reasoners. High-performance backend with **Hybrid Retrieval (Dense + Sparse) + Reciprocal Rank Fusion**, parallel async inference, and **Semantic Caching (Redis)**. Productionized as **Serverless Microservices** on FastAPI + AWS Lambda + RDS.

> 🎯 **93.93% precision** &nbsp;·&nbsp; 💰 **50.4% cost reduction** ($0.30 → $0.14/query) &nbsp;·&nbsp; 🏆 **91.8% win rate** (Cohen's h=1.74)

---

#### 🔧 Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Agentic AI & LLM Stack**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP Servers](https://img.shields.io/badge/MCP_Servers-6E56CF?style=flat-square&logo=anthropic&logoColor=white)
![Vector DBs](https://img.shields.io/badge/Vector_DBs-3F8EFC?style=flat-square&logo=databricks&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Qdrant](https://img.shields.io/badge/Qdrant-FE4155?style=flat-square&logo=qdrant&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Machine Learning & Vision**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Web & Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**Cloud, DevOps & Observability**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### 📚 Publications

> Three peer-reviewed papers. The two recent works formalize the **FLSS + Cost-Aware Structured Generation + Knowledge Graph Induction** pipeline behind my current research; the earlier paper documents forensic-ML work from my internship.

**🆕 Recent — both under Springer review**

[![FLSS Paper](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18643835-1C3C3C?style=flat-square&logo=doi&logoColor=white)](https://doi.org/10.5281/zenodo.18643835)
&nbsp; **Field-Level Structural Synthesis: A Schema-Aware Multi-Model Consensus Framework for High-Fidelity Structured Generation and Knowledge Graph Induction**

[![Cost-Aware Paper](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18270482-1C3C3C?style=flat-square&logo=doi&logoColor=white)](https://doi.org/10.5281/zenodo.18270482)
&nbsp; **Cost-Aware Structured Generation: High-Fidelity Synthesis via Hybrid RAG**

**📜 Earlier**

[![DeepFake Paper](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.18279368-1C3C3C?style=flat-square&logo=doi&logoColor=white)](https://doi.org/10.5281/zenodo.18279368)
&nbsp; **DeepFake Detection Using Inception-ResNet-v2**

---

### 📌 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### [🔬 Cost-Aware Structured Generation](https://github.com/Anand0008/cost-aware-structured-generation)
Production-grade **14-stage pipeline** for structured content generation with adaptive conditional compute. Processes 1,270 aerospace engineering queries with 93.5% precision via Hybrid RAG and multi-model consensus.

`Python` `LLM` `RAG` `FastAPI` `AWS Lambda`

</td>
<td width="50%" valign="top">

#### [🌐 Automated Knowledge Graph Induction](https://github.com/Anand0008/Knowledge_Graph_Induction)
Downstream application of the **FLSS consensus pipeline**. Automatically induced a curriculum-aligned ontology with 37,970 nodes and 55,153 edges directly from synthesized question metadata. Achieved **94.95% connectivity** without manual curation, enabling bidirectional navigation (Questions ↔ Concepts) and exposing hidden semantic relationships (prerequisites, common mistakes).

`Data Mining` `Ontology Learning` `Three.js` `Data Viz`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [🛡️ Video Source Authenticator](https://github.com/Anand0008/Video_Source_Authenticator)
DeepFake detection system using **Inception-ResNet-v2** with Swish/Mish activation optimization. Metadata extraction for forensic video origin verification. 5% accuracy improvement over ReLU baselines.

`Python` `Deep Learning` `Computer Vision` `Forensics`

</td>
<td width="50%" valign="top">

#### [🤖 Rasa Hotel Bot](https://github.com/Anand0008/Rasa_Hotel_Bot)
Conversational AI assistant for hotel booking built with the **Rasa framework**. Natural language understanding with intent classification and entity extraction for hospitality domain.

`Python` `Rasa` `NLP` `Conversational AI`

</td>
</tr>
</table>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Anand0008&color=38bdf8&style=flat-square&label=Profile+Views&base=257" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Anand0008/Anand0008/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Anand0008/Anand0008/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Anand0008/Anand0008/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</p>
