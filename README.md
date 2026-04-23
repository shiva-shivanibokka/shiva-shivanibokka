# Shivani Bokka

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shivani-bokka)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivani.bokka93@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/shiva-shivanibokka)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://public.tableau.com/app/profile/shivani.bokka)

---

## About Me

I am a **Graduate Student in Data Science & Artificial Intelligence** at **San Francisco State University** (GPA: 3.93 / 4.0), building intelligent systems at the intersection of machine learning, large language models, and software engineering.

My work spans the full AI development lifecycle — from classical ML pipelines on clinical genomics data, to production-grade agentic systems with multi-provider LLM orchestration, RAG/CAG architectures, and MLOps tooling. I have a strong foundation in deep learning (Transformers, LSTMs, attention mechanisms) and hands-on experience deploying full-stack AI applications on cloud infrastructure.

**Currently seeking** roles in AI/ML Engineering, Data Science, and Software Engineering where I can build systems that create measurable real-world impact.

---

## Skills & Expertise

### Programming Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

### Machine Learning

![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-003366?style=for-the-badge&logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logo=python&logoColor=black)

**Supervised Learning:** Linear & Logistic Regression (L1/L2 regularization), Ridge, Lasso, ElasticNet, Polynomial Regression, Bayesian Linear Regression, SVM (RBF + linear kernels), K-Nearest Neighbors, Random Forest, Gradient Boosting, XGBoost, CatBoost, LDA, QDA, Gaussian Naive Bayes

**Unsupervised Learning:** K-Means, PCA, TruncatedSVD, feature selection (VarianceThreshold, RFE)

**Model Selection & Evaluation:** K-Fold CV, Stratified K-Fold, Time Series Split, Grid Search, Random Search, Bayesian Optimization (scikit-optimize, Optuna), Walk-Forward CV; metrics across regression (MAE, RMSE, R²), binary/multiclass classification (Accuracy, Precision, Recall, F1, ROC-AUC, Log Loss, Confusion Matrix), and ranking

**Feature Engineering:** Statistical aggregation of time-series, interaction terms, binning, target encoding, ColumnTransformer pipelines, sklearn Pipeline with data leakage prevention

**Class Imbalance:** SMOTE, `class_weight='balanced'`, `scale_pos_weight`, decision threshold calibration, stratified sampling

**Bioinformatics / Domain ML:** High-dimensional genomics (scRNA-seq, microarray — 22,000+ features), label harmonization across datasets, rare class handling in multiclass settings

---

### Deep Learning & Neural Networks

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

**Architectures:** Transformer (Encoder-only, Decoder-only, Encoder-Decoder), LSTM, RNN, CNN, PatchTST, Temporal Fusion Transformer (TFT), Holistic Attention Network (HAN), Mixture of Experts (MoE)

**Attention Mechanisms:** Multi-Head Self-Attention, Channel Attention, Spatial Attention, Layer Attention, Residual Channel Attention Blocks (RCAB), Group Query Attention; KV cache optimization

**Training Techniques:** Backpropagation from scratch (custom autograd engine), AMP (Automatic Mixed Precision), gradient clipping, gradient accumulation, early stopping, cosine annealing, weight decay, dropout, batch/layer normalization, pinball/quantile loss, pixel shuffle upscaling

**Time Series:** Temporal Fusion Transformer with static categoricals, known future covariates, variable selection networks, quantile (P10/P50/P90) prediction; LSTM/RNN with walk-forward validation; 36+ technical indicator feature engineering (MACD, RSI, ATR, Bollinger Bands, OBV, VIX)

**Computer Vision:** Single-image super-resolution (HAN), hierarchical residual attention, SSIM and PSNR evaluation, custom data augmentation pipelines on large patch datasets

---

### Large Language Models & Generative AI

![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**LLM Providers:** Anthropic Claude, OpenAI GPT-4o, Google Gemini, Groq (LLaMA), Mistral, Ollama — multi-provider abstraction and hot-swapping at runtime

**Agentic Systems:** ReAct reasoning loop, LangGraph multi-node stateful agents (conditional edges, error short-circuiting), Model Context Protocol (MCP) with 50-tool typed registry, sliding window memory compression, tool result TTL caching

**RAG & CAG:** Full RAG pipeline (chunking strategies, sentence-transformer embeddings, FAISS/ChromaDB vector retrieval, LLM generation); Context Augmented Generation (full corpus in context window, KV cache exploitation); CAG vs RAG benchmarking (latency, token cost, LLM-as-judge quality scoring)

**NLI & Hallucination Detection:** DeBERTa-v3-large for sentence-level entailment/contradiction/neutral classification; sentence-level hallucination scoring (GROUNDED / UNGROUNDED / CONTRADICTED); multi-source document ingestion (PDF, URL, plain text) with Playwright fallback

**Prompt Engineering:** Zero-shot, few-shot, Chain-of-Thought, structured JSON extraction, system prompt design, LLM-as-judge evaluation, Constitutional AI principles

**Embeddings:** `all-MiniLM-L6-v2`, `text-embedding-ada-002`; cosine similarity, FAISS ANN indexing (IVFFlat, IndexFlatIP), ChromaDB

**Structured Output:** Pydantic v2 schema validation for LLM responses, provider-agnostic wrapper design

---

### MLOps & Deployment

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**MLflow:** Experiment tracking, hyperparameter logging, model artifact registry, Staging → Production promotion workflows, prediction logging, drift detection (MAE + calibration score)

**Deployment:** FastAPI + uvicorn REST APIs, Gradio web apps on Hugging Face Spaces, Streamlit dashboards, Flask + Next.js full-stack, Docker + docker-compose containerization, AWS EC2 deployment

**CI/CD:** GitHub Actions for automated weekly model retraining; model hot-reload endpoints; rate-limited production APIs

---

### Data Analytics & Visualization

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

EDA, data wrangling, statistical analysis, hypothesis testing, interactive dashboard development (18-chart Plotly dashboards, Tableau public dashboards)

---

### Web Scraping & Data Ingestion

`BeautifulSoup4`, `requests`, `Playwright` (JS-rendered pages), `pypdf`, `yfinance`, Tavily API (real-time web search), SerpAPI / DuckDuckGo, `nbformat` (Jupyter notebook parsing), async MySQL + PostgreSQL (`aiomysql`, `asyncpg`)

---

### Frameworks & Tools

**Backend:** FastAPI, Flask, Django  
**Frontend:** React, Next.js, Gradio, Streamlit  
**Version Control:** Git, GitHub  
**Notebooks:** Jupyter, Google Colab  
**Cloud:** AWS (EC2, S3, SageMaker), Google Cloud (AI Platform, BigQuery)

---

### Computer Science Fundamentals

Two Pointers, Sliding Window, Fast & Slow Pointers, Binary Search, Merge Intervals, Linked List patterns, Binary Tree DFS/BFS, Graph DFS/BFS, Topological Sort, Heaps / Priority Queues, Backtracking, Dynamic Programming (memoization + tabulation)

---

### Languages Spoken

- **English** — Fluent
- **Hindi** — Fluent
- **Telugu** — Fluent

---

## Professional Experience

### Teaching Assistant — Data Science & Machine Learning / PINC Program, SFSU
**Aug 2025 – Present**

Supporting 20+ students in mastering Python, data analysis, and ML model development through lectures, code reviews, and project guidance.

- Conducted 10 weekly discussion sessions and office hours on Python, data preprocessing, and ML algorithms
- Guided students in applying PyTorch, TensorFlow, and scikit-learn to real-world projects
- Designed 2+ coding examples, datasets, and exercises weekly to reinforce learning
- Provided one-on-one debugging assistance, improving assignment completion rates

---

### Vice President Finance — Associated Students, SFSU
**Jun 2025 – Present**

Managing a $100,000+ budget for student organizations and leading financial planning initiatives.

- Oversaw $100,000+ budget allocation across multiple campus organizations
- Chaired weekly Finance Committee meetings, approving funding proposals
- Developed fundraising strategy securing $50,000 for the Gator Groceries initiative

---

### Teaching Assistant / Grader — Pattern Analysis & Machine Intelligence, SFSU
**Feb 2025 – May 2025**

- Led weekly sessions simplifying pattern recognition algorithms in MATLAB and Python
- Supported 40+ students in applying classification, clustering, and feature extraction
- Graded 200+ assignments and projects with rubric-based feedback

---

### Teaching Assistant / Grader — Probability and Statistics I, SFSU
**Feb 2025 – May 2025**

- Led weekly problem-solving sessions on statistical methods and probability theory
- Provided academic support to 40+ students via one-on-one and group guidance
- Graded 400+ assignments with detailed written feedback

---

### Manager (Marketing & New Technologies) — Stagecraft Pvt Ltd, New Delhi, India
**Aug 2022 – Mar 2024**

Led cross-functional teams delivering multimedia production projects and integrating technology-driven workflow improvements.

- Managed 15+ multimedia projects, bridging marketing and technical teams
- Delivered client presentations increasing engagement by 10% and retention by 15%
- Improved team workflows by 15% through technology integration initiatives

---

## Let's Connect

Open to discussing AI/ML engineering, research collaborations, and full-time opportunities.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shivani-bokka)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivani.bokka93@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/shiva-shivanibokka)

---

<p align="center"><em>"Engineering Intelligence, One Model at a Time."</em></p>


<p align="center">
  <em>"Engineering Intelligence, One Model at a Time."</em>
</p>


