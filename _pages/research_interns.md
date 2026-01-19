---
permalink: /research_interns/  # Matches your navigation URL
title: "Research & Internship Experience"
author_profile: true
layout: single
---

## Research Experience  
### Northeastern University (Advisor: Qing Zhou)  
**Role**: Research Assistant | **Duration**: Jul. 2024 – Present  
**Focus Area**: Balanced Minimum Sum-of-Squares Clustering Problem (under the project "Research on Resource Scheduling in Cloud Data Centers for Complex Tasks")  

**Responsibilities & Achievements**:  
- Overview: Balanced MSSC (capacity/balance); Java + reproducible eval; beats K-means++.
- Designed and developed balanced MSSC algorithms under capacity/balance constraints to address poor initialization and local optima issues, delivering ~1.8× faster per iteration neighbor scoring and 9–13% lower objectives (up to ~17%) than K means++ (50 restarts) across six synthetic/real datasets (n≤100k, k=10–50).
- Engineered a Java codebase with pluggable initializers, amortized O(1) exchange cost updates via statistics, and tabu search operators (one move/swap), augmented by a population based diversification mechanism to avoid premature convergence.
- Established a reproducible evaluation protocol (fixed balance tolerance and restart budgets, 5 seeds, wall clock timing)
and ran ablations to isolate gains from the fast cost updater, swap moves, and diversification.  


## Internship Experience  
### 1. Midea Group (Shanghai) | Algorithm Intern (Human-Computer Interaction)   Midea_Midea Group_Professional Platform_AI Research Institute_AI Algorithms_Human-Computer Interaction
**Duration**: Jul. 2025 – Present | **Tech Stack**: Python, Streamlit, Mem0, Multi-Agent Systems, Prompt Engineering, sft/rl  
**Responsibilities & Achievements**:  
- Overview: Teachable smart‑home AI across Chat & Memory Agents, focusing on memory architecture and evaluation.
- Built user profiles and device‑preference memory using custom prompt‑based dialog summarization on reset in a Chat Agent
predemo with Streamlit UI, Redis for chat history, and GPT-4o streaming, to enable cross‑session personalization.
- Evaluated memory store options and selected Mem0 on‑prem using a Redis vector store with GPT-4o and bge-m3, optimizing
labeled memory extraction and update prompts to stabilize persistence and reduce integration issues.
- Curated an evaluation dataset from online logs using time‑ordering and showroom filtering, while mining logs via a Linux bastion
and Python to detect bad cases and build confusion matrices, resulting in processing ~27,698 sessions into 2,309 scenario samples
across 167 families and actionable defect buckets routed to owners.
- Delivered the Chat Agent MVP with multi‑turn dialog, correction/clarification/rejection, and memory using a single GPT-4o
pipeline with legacy fallback and few‑shot integrated into the control screen, reducing p50 latency to ~6 s.
- Improved speed and cost with two‑stage SFT using LoRA on Qwen 8B and token reduction, deploying an optimized on‑prem
model for inference and improving the internal benchmark from 10/22 → 12.5/22.
- Set up an LLM‑for‑judge loop for fine‑tuned Qwen variants (dense and MoE, 3B–22B+), using GPT‑OSS and Gemini as judges
with GPT‑5 as arbiter, to adjust prompts based on judgments and improve decision quality.

### 2. Henan Shuqing Data Technology Co., Ltd. | AI Data Training Intern (Remote)  
**Duration**: Jun. 2024 – Nov. 2025 | **Tech Stack**: Python, Pandas, Matplotlib, scikit-learn, LightGBM, XGBoost, Jupyter Notebook  
**Responsibilities & Achievements**:  
- Overview: Tianchi (Bank Customer Product Subscription Prediction); end‑to‑end modelling pipeline.
- Built a data preparation and feature engineering pipeline using Jupyter/Pandas with data integrity validation,
LabelEncoder for categorical features, and Matplotlib correlation heatmaps, resulting in cleaner training data and clearer
insights for targeted marketing.
- Trained and compared logistic regression, random forest, XGBoost, and LightGBM with scikit‑learn using 5 fold cross
validation and targeted hyperparameter tuning (n_estimators, learning_rate), achieving AUC 0.87, F1 0.51, and accuracy
90% (LightGBM best).  

### 3. Migu Music Co., Ltd. | Data Algorithm Intern  
**Duration**: Dec. 2024 – Mar. 2025 | **Tech Stack**: Python, Stable Diffusion, LLM Prompt Engineering, Data Labeling  
**Responsibilities & Achievements**:  
- Overview: Spring Festival content agent (LLM + Stable Diffusion); prompts/templates and QC datasets.
- Developed and tuned prompts for LLMs and Stable Diffusion (text to image/video) using batch templates and negative
prompts for Spring Festival assets, resulting in ~35–40% reduction in post editing workload
- Performed structured labeling for audio/video/images and built datasets with QC checks using Python scripts to validate
metadata and file integrity, achieving ~25% increase in annotation throughput.


### 4. Shenzhen Bairen Biotechnology Co., Ltd. | Full-Stack Development Engineer  
**Duration**: Oct. 2024 – Dec. 2024 | **Tech Stack**: Python, Docker, Linux, GPT-4o, JSON Schema Validation  
**Responsibilities & Achievements**:  
- Overview: Bioinformatics platform; pipeline automation & containerization for Linux workloads.
- Automated Python analysis of pipeline outputs using Dockerized services on Linux, resulting in −35% runtime, −50% setup
time, and +15% success rate.
- Designed GPT‑4o prompts for JSON extraction with schema validation and retry, achieving 90% valid parses and −30%
manual review.


### 5. Chengdu Xiaoduo Technology Co., Ltd. | R&D Intern (Prompt Engineer)  Digital Experience Innovation Team
**Duration**: Jul. 2024 – Sep. 2024 | **Tech Stack**: Python, GPT-4o, Elasticsearch, BM25, HNSW, bge-m3, Cross-Encoder, Streamlit  
**Responsibilities & Achievements**:  
- Overview: Owned the customer‑service RAG initiative for online product support, focusing on query routing, retrieval
relevance, and prompt orchestration from prototype to demo.
- Built a RAG routing agent using GPT 4o and prompt orchestration to rewrite/classify queries into four workflows (KB Q&A,
product Q&A, recommendation, comparison) with confidence based fallback, resulting in +24% routing precision and −31%
misroutes on internal eval.
- Implemented hybrid retrieval in Elasticsearch using BM25 + dense vector HNSW with bge-m3 embeddings, with a cross
encoder re‑ranker and rule‑based filters, achieving +18% top 5 recall and −27% hallucination rate in offline QA tests.
- Shipped a Streamlit demo with streaming responses to validate end‑to‑end RAG, delivering p50 latency ~6 s and −42%
feedback cycle time through faster stakeholder reviews.


### Access Full Documentation   
- [Download Standard CV (PDF)](/files/CV.pdf) – Standard CV
- [Download Europass CV (PDF)](/files/Europass.pdf) – Europass format CV
- [Download Academic Transcript (PDF)](/files/Transcript.pdf) – Complete academic records with GPA conversion statement
- [Download Portfolio (PDF)](/files/portfolio.pdf) – Visual summaries of technical work
- [Download Course Descriptions (PDF)](/files/课程描述.pdf) – Detailed course content and learning outcomes
