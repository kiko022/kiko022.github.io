---
permalink: /research_interns/  # 必须与导航 url 完全匹配
title: "Research & Internship Experience"
author_profile: true
layout: single
---

## Research Experience  
### National Natural Science Foundation of China (Youth Fund Project)  
**Role**: Research Assistant | **Duration**: Jul. 2024 – Present  
**Focus Area**: Balanced Minimum Sum-of-Squares Clustering Problem  

**Key Contributions**:  
1. Implemented the core clustering algorithm using **Java**，with two-step optimization to improve solution quality:  
   - First, repeated **K-means** runs to secure stable initial solutions (avoid randomness in single K-means results);  
   - Then, designed a tabu search algorithm to calculate "exchange costs" between data points，reducing redundant computations by 30% (vs. brute-force search).  
2. Integrated **population algorithm** to solve local optima:  
   - Enabled information sharing among "search individuals" to explore multiple optimization paths;  
   - Guided algorithm evolution when stuck in local minima，enhancing final clustering accuracy by 15% (tested on public datasets).  


## Internship Experience  
### 1. Midea Group (Shanghai) | Algorithm Intern (Human-Computer Interaction)  
**Duration**: Jul. 2025 – Present | **Tech Stack**: Python, Streamlit, Mem0, Multi-Agent Systems  
**Responsibilities & Achievements**:  
- Developed a **Master Agent system** to coordinate sub-agents (data analysis/device control)，using Streamlit for interactive interface design;  
- Integrated Mem0 dynamic memory module to support **long-context conversation persistence** (solved the problem of "forgetting" historical interactions);  
- Optimized prompt templates for memory extraction/update，improving context coherence in 80+ user test scenarios (e.g., continuous device control commands).  


### 2. Migu Music Co., Ltd. | Data Algorithm Intern  
**Duration**: Dec. 2024 – Mar. 2025 | **Tech Stack**: Python, StableDiffusion, Prompt Engineering  
**Responsibilities & Achievements**:  
- Optimized prompts for LLMs (text understanding)、text-to-image (StableDiffusion) and text-to-video models;  
- Generated 500+ Spring Festival-themed images via StableDiffusion，supporting the development of holiday-specific AI music agents;  
- Conducted structured label recognition for audio/video/image data (e.g., music genre tagging)，laying the foundation for model training data.  


### 3. Shenzhen Bairen Biotechnology Co., Ltd. | Platform Development Intern  
**Duration**: Oct. 2024 – Dec. 2024 | **Tech Stack**: Python, Docker, Linux, GPT-4o  
**Responsibilities & Achievements**:  
- Wrote Python automation scripts to optimize bioinformatics data processing workflows (e.g., gene sequence alignment)，reducing manual operation time by ~30%;  
- Used Docker to build and manage application environments，ensuring consistency across development/testing teams;  
- Developed GPT-4o-based prompts to extract key information from bioinformatics source code/manuscripts，outputting structured JSON for downstream data integration.  


### 4. Chengdu Xiaoduo Technology Co., Ltd. | R&D Intern (Prompt Engineer)  
**Duration**: Jul. 2024 – Sep. 2024 | **Tech Stack**: Python, Elasticsearch, Streamlit, RAG Framework  
**Responsibilities & Achievements**:  
- Built a **routing-style intelligent Agent** based on RAG: used LLMs to classify user queries and route them to 4 workflows (knowledge base Q&A, product Q&A, recommendation, comparison);  
- Established a vector database with Elasticsearch，completing lightweight vector storage of knowledge base content via manually defined semantic features (e.g., product keyword weights);  
- Created interactive demos with Streamlit to showcase RAG-based AI interaction，supporting internal product testing.  


### Quick Access to My Work  
- [Download My CV (PDF)](/files/CV.pdf) – View detailed research/internship documentation  
- [View 6-Page Portfolio (PDF)](/files/portfolio.pdf) – See visual summaries of key projects
