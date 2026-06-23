# Hi, I'm Likhil Dahal 👋

**`AI Engineer | Building AI-Native Systems for the Physical World`**

I'm a BSc (Hons) Computing graduate and AI Engineer working at the intersection of **AI, systems architecture, and applied deep learning**. I think in ecosystems, not isolated products — my work spans backend AI infrastructure, multi-agent systems, and the long-term goal of building software that funds increasingly ambitious deep-tech R&D.

Currently building **CADAI** — an AI-native CAD platform that compiles natural language into manufacturable hardware designs.

---

## 🚀 Flagship Project

### [CADAI](https://github.com/docxbox) — AI-Native CAD Platform *("Lovable for Hardware")*
**Status:** Private / in active development — reach out for a walkthrough or demo access.

CADAI lets engineers describe a part in natural language and generates a manufacturable, parametric CAD design through a deterministic pipeline:

```
prompt → intent → design graph → compiler contract → CadQuery/OpenCASCADE → artifacts
```

**Architecture highlights:**
- **195 REST endpoints** across 37 routers, **46 tool-registry functions**, sole-architect build
- Hard LLM/deterministic boundary — the LLM proposes design graph diffs only; geometry is fully deterministic and reproducible
- 6-agent swarm system with multi-round debate, causal memory graphs, and hypothesis scoring
- Physics-grade simulation: 2D/3D FEM (frame & hex), 1D/2D thermal, 2D Navier–Stokes CFD, topology optimization (SIMP)
- Digital twin synthesis, live telemetry ingestion, GitHub PR auto-review, voice & multimodal input
- Semantic memory (pgvector LSA + FTS), cross-project org memory, automated hypothesis validation

**Tech:** Python, FastAPI, PostgreSQL, Redis, CadQuery/OpenCASCADE, Gmsh, scipy, React (in progress)

---

## 📂 Other Highlighted Projects

### [ScholarAI Graph-RAG](https://github.com/docxbox/ScholarAI_Graph_Rag)
AI research assistant combining **Graph-RAG + LLMs** to query scientific papers and visualize entity relationships.
**Tech:** Python, FastAPI, Neo4j, PySpark, React, Tailwind, OpenRouter/Ollama
- Graph-RAG pipeline: vector search + graph expansion over arXiv papers
- Conversational AI with streaming chat and interactive knowledge graph visualization
- Scalable architecture: offline Spark indexing + online FastAPI serving

### [Transcription Factor Binding Prediction](https://github.com/docxbox/Transcription-Factor-Prediction-Using-ML)
Comparative ML study predicting transcription factor binding sites from ENCODE ChIP-seq data (55K+ samples, 31 TF classes).
**Tech:** TensorFlow/Keras, XGBoost, scikit-learn
- Built a custom **Hybrid CNN + Multi-Head Attention** architecture on raw DNA sequence
- Benchmarked against XGBoost, Random Forest, and MLP baselines with stratified k-fold CV
- Diagnosed overfitting via train/validation curve analysis — best baseline (XGBoost) reached 0.871 ROC-AUC

### [NerdyGeek](https://github.com/docxbox/NerdyGeek)
MCP server that grounds AI coding agents in live, up-to-date documentation instead of stale training data.
**Tech:** TypeScript

### [Spotify Dataset ETL Pipeline](https://github.com/docxbox/SPOTIFY-DATASET-ETL-PIPELINE-PYSPARK)
End-to-end ETL pipeline processing Spotify dataset at scale.
**Tech:** Python, PySpark

### [Motion-Synced Robotic Arm](https://github.com/docxbox/Motion-Syned-Robotic-Arm)
Real-time hand-gesture-controlled robotic arm.
**Tech:** Python, OpenCV, MediaPipe, Arduino
- Real-time gesture tracking mapped to motor control signals

### [NYC 311 Complaints Data Analysis](https://github.com/docxbox/NYC_311_Complaints_DATA_ANALYSIS)
Exploratory data analysis on 300K+ NYC 311 service requests across 53 features.
**Tech:** Python, Pandas, Matplotlib, Seaborn

<details>
<summary>More projects</summary>

- [Store Management System](https://github.com/docxbox/Store-Management-System) — Java inventory system with CRUD operations
- [Inventory Management System CLI](https://github.com/docxbox/Inventory-Management-System-CLI) — Python CLI inventory tool
- [GrabGo E-Commerce Site](https://github.com/docxbox/GrabGo-Ecommerce-Site) — Responsive grocery e-commerce front end

</details>

---

## 🔬 Current Focus
- Building **CADAI** toward a usable frontend and first real users
- AI/backend roles — Python, FastAPI, RAG, and multi-agent LLM systems
- Applying core engineering principles (deterministic pipelines, simulation, evaluation rigor) across domains — from hardware design to computational genomics

## ⚡ Research Philosophy
I'm interested in how **biology and evolution** can inspire more robust AI architectures — not just smarter models, but smarter systems. I care about building tools that compress the distance between an idea and a manufactured, working thing.

---

## 💻 Tech Stack

### **Languages**
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### **Backend & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![REST API](https://img.shields.io/badge/REST-008000?style=for-the-badge)

### **Databases & Data Systems**
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black)

### **AI / ML / Data Science**
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

### **DevOps & Cloud**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

### **Frontend**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

### **Hardware**
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry_Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![nVIDIA CUDA](https://img.shields.io/badge/cuda-000000.svg?style=for-the-badge&logo=nVIDIA&logoColor=green)

---

## 🌐 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/likhil-dahal-72477928b)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:likhildahal@outlook.com)

---

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=docxbox&theme=dark&include_all_commits=true&count_private=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=docxbox&theme=dark&layout=compact)

[![](https://visitcount.itsvg.in/api?id=docxbox&icon=0&color=0)](https://visitcount.itsvg.in)
