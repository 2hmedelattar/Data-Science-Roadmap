# 🧠 Complete Data Science Roadmap

> A structured, end-to-end roadmap covering every skill you need — from zero to job-ready Data Scientist.
> Includes tasks, topics, resources, and specialization tracks.

---

## 📋 Table of Contents

- [Phase 0 — Entry Level](#phase-0--entry-level)
- [Phase 1 — Beginner](#phase-1--beginner)
- [Phase 2 — Intermediate](#phase-2--intermediate)
- [Phase 3 — Advanced](#phase-3--advanced)
- [Phase 4 — Professional Specializations](#phase-4--professional-specializations)
- [Soft Skills](#soft-skills)

---

## Phase 0 — Entry Level

> Before writing a single line of code, understand the landscape, the market, and set up your environment.

### 🗺️ Understanding the Field

#### Task 1: Data Science vs AI vs ML vs DL
**Time:** 1 day

**Topics:**
- Difference between Data Science, AI, Machine Learning, and Deep Learning
- Venn diagram of how they overlap
- Real-world examples for each field
- Who does what inside companies

**Resources:**
- [IBM — What is Data Science?](https://www.ibm.com/topics/data-science)
- [Towards Data Science — DS vs ML vs AI](https://towardsdatascience.com/data-science-vs-machine-learning-whats-the-difference-a8da-c4e16dad6b2c)

---

#### Task 2: Job Titles & Specializations in the Market
**Time:** 2 days

**Topics:**
- Data Analyst
- Data Scientist
- Machine Learning Engineer
- Data Engineer
- AI Researcher
- MLOps Engineer
- Business Intelligence Analyst

**Resources:**
- [DataCamp — Data Science Job Titles Explained](https://www.datacamp.com/blog/data-science-job-titles)
- [Towards Data Science — Job Titles Explained](https://towardsdatascience.com/data-science-jobs-explained-c47f54bf7b67)

---

### 📊 Job Market & Demand

#### Task 3: Most In-Demand Skills in 2025
**Time:** 2 days

**Topics:**
- Top 10 most requested skills
- Python vs R in the job market
- Cloud Skills (AWS / GCP / Azure)
- MLOps & Deployment
- LLMs & Generative AI Skills
- Salary benchmarks (global & regional)

**Resources:**
- [Kaggle State of Data Science Survey 2024](https://www.kaggle.com/competitions/kaggle-survey-2024)
- [LinkedIn Jobs — Data Science Trends](https://www.linkedin.com/jobs/data-scientist-jobs/)

---

#### Task 4: Build Your Personal Learning Plan
**Time:** 1 day

**Topics:**
- Choosing your niche (Generalist vs Specialist)
- Setting short-term and long-term goals
- Building a personal roadmap
- Tracking your progress

**Resources:**
- [fast.ai — How to Learn ML](https://www.fast.ai/posts/2020-01-16-fast_template.html)
- [Towards Data Science — Learning Path 2024](https://towardsdatascience.com/how-to-learn-data-science-in-2024-2b02fb1f0e5c)

---

### ⚙️ Setup Your Environment

#### Task 5: Dev Environment Setup
**Time:** 1 day

**Topics:**
- Install Python via Anaconda / Miniconda
- VS Code + essential extensions
- Jupyter Notebook vs JupyterLab vs Google Colab
- Create your first virtual environment
- Create accounts: GitHub, Kaggle, Hugging Face

**Resources:**
- [Anaconda Installation Guide](https://docs.anaconda.com/anaconda/install/)
- [Google Colab — Getting Started](https://colab.research.google.com/)

---

## Phase 1 — Beginner

> Build the foundational tools. Every task here must be practiced, not just read.

### 🐍 Python

#### Task 1: Python Fundamentals
**Time:** 3 weeks

**Topics:**
- Variables, Data Types, Type Casting
- Lists, Tuples, Sets, Dictionaries
- Loops (`for` / `while`) & Conditionals
- Functions & Scope
- String Methods
- File I/O
- Error Handling (`try` / `except`)

**Resources:**
- [CS50P — Harvard (Free)](https://cs50.harvard.edu/python/)
- [Python.org Official Tutorial](https://docs.python.org/3/tutorial/)
- [Kaggle Python Course (Free)](https://www.kaggle.com/learn/python)

---

#### Task 2: Python for Data
**Time:** 2 weeks

**Topics:**
- NumPy Arrays & Broadcasting
- Pandas — Series & DataFrame
- DataFrame Operations (filter, sort, `groupby`)
- Merging & Joining DataFrames
- Reading CSV / Excel / JSON
- Matplotlib Basics

**Resources:**
- [Pandas Documentation](https://pandas.pydata.org/docs/getting_started/)
- [NumPy Documentation](https://numpy.org/doc/stable/)

---

### 📐 Mathematics

#### Task 3: Statistics Fundamentals
**Time:** 3 weeks

**Topics:**
- Mean, Median, Mode, Range
- Variance & Standard Deviation
- Probability Basics
- Normal Distribution
- Correlation Coefficient
- Intro to Hypothesis Testing

**Resources:**
- [Khan Academy — Statistics & Probability](https://www.khanacademy.org/math/statistics-probability)
- [StatQuest YouTube Channel](https://www.youtube.com/@statquest)

---

#### Task 4: Linear Algebra Fundamentals
**Time:** 2 weeks

**Topics:**
- Vectors & Scalars
- Matrix Addition & Multiplication
- Transpose & Inverse
- Dot Product
- Identity Matrix

**Resources:**
- [3Blue1Brown — Essence of Linear Algebra (Free)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2ZVjFEMk97OoTL)
- [Khan Academy — Linear Algebra](https://www.khanacademy.org/math/linear-algebra)

---

### 🔧 Git & GitHub

#### Task 5: Git Basics
**Time:** 1 week

**Topics:**
- `init`, `add`, `commit`, `log`, `status`
- Branching & Merging
- GitHub Remote Repos (`push` / `pull`)
- Writing a good `README.md`
- `.gitignore`

**Resources:**
- [Learn Git Branching (Interactive)](https://learngitbranching.js.org/)
- [GitHub Skills](https://skills.github.com/)
- [Pro Git Book (Free)](https://git-scm.com/book/en/v2)

---

## Phase 2 — Intermediate

> Work with real data and build your first real models.

### 📊 Data Analysis

#### Task 1: Exploratory Data Analysis (EDA)
**Time:** 3 weeks

**Topics:**
- Univariate & Bivariate Analysis
- Missing Values Deep Dive
- Outlier Detection (IQR, Z-score)
- Correlation Matrix & Heatmaps
- Categorical vs Numerical Analysis
- `ydata-profiling` (automated EDA)

**Resources:**
- [Kaggle — Titanic EDA Notebooks](https://www.kaggle.com/c/titanic)
- [Towards Data Science — EDA Guide](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15)

---

#### Task 2: Data Cleaning
**Time:** 3 weeks

**Topics:**
- Imputation Strategies (Mean / Median / KNN / MICE)
- Handling Outliers (Capping, Winsorization)
- Encoding (One-Hot, Label, Ordinal, Target Encoding)
- Regex for String Cleaning
- DateTime Parsing
- Duplicate Handling

**Resources:**
- [Kaggle Data Cleaning Course (Free)](https://www.kaggle.com/learn/data-cleaning)
- [Sklearn Preprocessing Docs](https://scikit-learn.org/stable/modules/preprocessing.html)

---

#### Task 3: Data Visualization
**Time:** 3 weeks

**Topics:**
- Chart Selection Framework
- Seaborn — Statistical Plots
- Plotly — Interactive Charts
- Storytelling with Data Principles
- Building Dashboards with Streamlit
- Color Theory for Data Visualization

**Resources:**
- [Fundamentals of Data Visualization — Claus Wilke (Free)](https://clauswilke.com/dataviz/)
- [Plotly Python Documentation](https://plotly.com/python/)
- [Streamlit Documentation](https://docs.streamlit.io/)

---

### 🤖 Machine Learning (Intro)

#### Task 4: Feature Engineering
**Time:** 3 weeks

**Topics:**
- Scaling (StandardScaler, MinMaxScaler, RobustScaler)
- Polynomial & Interaction Features
- Time-based Feature Extraction
- Target Encoding
- Feature Selection (Correlation, RFE)
- Building Sklearn Pipelines

**Resources:**
- [Kaggle Feature Engineering Course (Free)](https://www.kaggle.com/learn/feature-engineering)
- [Sklearn Pipeline Documentation](https://scikit-learn.org/stable/modules/pipeline.html)

---

#### Task 5: Supervised ML Fundamentals
**Time:** 4 weeks

**Topics:**
- Linear & Logistic Regression
- Decision Trees
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Train / Validation / Test Split
- Cross-Validation (k-fold, Stratified)
- Evaluation Metrics (Accuracy, F1, AUC-ROC, RMSE)
- Overfitting & Regularization (L1 / L2)

**Resources:**
- [Andrew Ng ML Specialization — Coursera](https://www.coursera.org/specializations/machine-learning-introduction)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)

---

## Phase 3 — Advanced

> Master advanced models, deployment, and intro to deep learning.

### 🚀 Advanced Machine Learning

#### Task 1: Ensemble Methods
**Time:** 3 weeks

**Topics:**
- Random Forest (Deep Dive)
- Gradient Boosting Theory
- XGBoost (Full Mastery)
- LightGBM & CatBoost
- Stacking & Blending
- Voting Classifiers

**Resources:**
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)
- [Hands-On ML — Aurélien Géron (Chapter 7)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)

---

#### Task 2: Unsupervised Learning
**Time:** 2 weeks

**Topics:**
- K-Means Clustering (Elbow Method, Silhouette Score)
- Hierarchical Clustering
- DBSCAN
- PCA (Deep Dive)
- t-SNE & UMAP
- Anomaly Detection

**Resources:**
- [Sklearn Clustering Guide](https://scikit-learn.org/stable/modules/clustering.html)
- [UMAP Documentation](https://umap-learn.readthedocs.io/en/latest/)

---

#### Task 3: Hyperparameter Tuning
**Time:** 2 weeks

**Topics:**
- `GridSearchCV` & `RandomizedSearchCV`
- Optuna (Bayesian Optimization)
- Early Stopping
- Learning Curves
- Model Calibration
- SHAP Values for Model Interpretation

**Resources:**
- [Optuna Documentation](https://optuna.org/)
- [SHAP Documentation](https://shap.readthedocs.io/en/latest/)

---

### 🚢 ML Deployment & MLOps

#### Task 4: Deployment Pipeline
**Time:** 3 weeks

**Topics:**
- FastAPI — Serving a model as a REST API
- Docker Containerization
- Docker Compose
- Streamlit App Deployment
- Deploying to Heroku / Render
- Hugging Face Spaces

**Resources:**
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Docker Getting Started](https://docs.docker.com/get-started/)

---

#### Task 5: MLOps Basics
**Time:** 3 weeks

**Topics:**
- MLflow — Experiment Tracking & Model Registry
- DVC — Data Version Control
- GitHub Actions (CI/CD)
- Model Monitoring with Evidently AI
- Data Drift Detection
- A/B Testing in Production

**Resources:**
- [Made With ML — MLOps (Free)](https://madewithml.com/)
- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)

---

### 🧠 Deep Learning (Foundations)

#### Task 6: Neural Networks Foundations
**Time:** 4 weeks

**Topics:**
- Forward Pass & Backpropagation
- Activation Functions (ReLU, Sigmoid, Softmax)
- Loss Functions & Optimizers (SGD, Adam, AdamW)
- Batch Normalization & Dropout
- PyTorch Fundamentals
- Writing a Training Loop from Scratch
- GPU Acceleration

**Resources:**
- [fast.ai — Practical Deep Learning (Free)](https://course.fast.ai/)
- [PyTorch Official Tutorials](https://pytorch.org/tutorials/)
- [Deep Learning Specialization — Andrew Ng, Coursera](https://www.coursera.org/specializations/deep-learning)

---

## Phase 4 — Professional Specializations

> Pick one track and go deep. Once you finish a specialization, you're ready to work in it.

---

### 👁️ Computer Vision

**Topics:**
- CNNs Deep Dive (ResNet, VGG, EfficientNet)
- Object Detection (YOLOv8/v9, DETR)
- Image Segmentation (SAM, Mask R-CNN)
- Image Generation (Diffusion Models, ControlNet)
- Video Understanding
- Classical CV with OpenCV
- Hugging Face Vision Models
- Deployment: TensorRT, ONNX

**Resources:**
- [CS231n — Stanford (Free)](http://cs231n.stanford.edu/)
- [Hugging Face Computer Vision Course](https://huggingface.co/learn/computer-vision-course)
- [Ultralytics YOLO Documentation](https://docs.ultralytics.com/)

---

### 💬 Natural Language Processing (NLP)

**Topics:**
- Text Preprocessing & Tokenization
- Word Embeddings (Word2Vec, GloVe, FastText)
- Transformer Architecture (Deep Dive)
- BERT Fine-Tuning
- GPT & Causal Language Modeling
- Named Entity Recognition (NER)
- Question Answering & Summarization
- RAG (Retrieval Augmented Generation)
- LLM Fine-Tuning (LoRA, QLoRA)
- LangChain & LlamaIndex

**Resources:**
- [Hugging Face NLP Course (Free)](https://huggingface.co/learn/nlp-course)
- [The Annotated Transformer — Harvard](https://nlp.seas.harvard.edu/annotated-transformer/)
- [fast.ai NLP Course](https://course.fast.ai/)

---

### 📈 Time Series

**Topics:**
- Time Series EDA (Trend, Seasonality, Noise)
- Classical Methods (ARIMA, SARIMA, Exponential Smoothing)
- Prophet (by Meta)
- LSTM & GRU for Time Series
- Temporal Fusion Transformer (TFT)
- Feature Engineering for Time Series
- Cross-Validation with `TimeSeriesSplit`
- Deployment for TS Models

**Resources:**
- [Forecasting: Principles and Practice (Free)](https://otexts.com/fpp3/)
- [Nixtla — StatsForecast & TimeGPT](https://nixtlaverse.nixtla.io/)

---

### 🎯 Recommender Systems

**Topics:**
- Collaborative Filtering (User-based, Item-based)
- Matrix Factorization (SVD, ALS)
- Content-Based Filtering
- Hybrid Recommendation Systems
- Deep Learning for RecSys (NCF, Wide & Deep)
- LLM-powered Recommendations
- A/B Testing Recommender Systems
- Deployment at Scale

**Resources:**
- [Google Recommendation Systems Course (Free)](https://developers.google.com/machine-learning/recommendation)
- [Microsoft Recommenders Toolkit](https://github.com/microsoft/recommenders)

---

### ⚙️ MLOps Engineer

**Topics:**
- Advanced Docker & Kubernetes
- Kubeflow & MLflow (Advanced)
- Feature Stores (Feast)
- Model Registry & Governance
- Continuous Training Pipelines
- Model Monitoring & Alerting
- Cloud ML Platforms (SageMaker, Vertex AI)
- Infrastructure as Code (Terraform)
- Data Pipelines (Airflow, Prefect)

**Resources:**
- [Made With ML — MLOps (Free)](https://madewithml.com/)
- [Full Stack Deep Learning (Free)](https://fullstackdeeplearning.com/)

---

### 🤖 Generative AI / LLM Engineer

**Topics:**
- LLM Architecture Deep Dive (GPT, LLaMA, Mistral)
- Advanced Prompt Engineering
- RAG Systems (Advanced)
- Fine-Tuning LLMs (LoRA / QLoRA / RLHF)
- LangChain & LlamaIndex (Advanced)
- AI Agents & Tool Use
- Vector Databases (Pinecone, Chroma, Weaviate)
- LLM Evaluation Frameworks
- Production LLM APIs & Cost Optimization

**Resources:**
- [DeepLearning.AI Short Courses (Free)](https://www.deeplearning.ai/short-courses/)
- [LangChain Documentation](https://python.langchain.com/)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)

---

## Soft Skills

> Technical skills get you the interview. Soft skills get you the job — and grow your career.

---

### 🎤 Communication & Presentation

#### Storytelling with Data
**Time:** 3 weeks

**Topics:**
- Data Narrative Framework
- From Insight to Story
- The Pyramid Principle
- Writing Executive Summaries
- Presenting Business Recommendations

**Resources:**
- [Storytelling with Data — Cole Nussbaumer (Book)](https://www.storytellingwithdata.com/)
- [Coursera — Data Visualization with Storytelling](https://www.coursera.org/learn/dataviz-design)

---

#### Public Speaking & Presentations
**Time:** 3 weeks

**Topics:**
- Toastmasters Techniques
- TED Talk Structure
- Slide Design Principles (Less is More)
- Presenting to Technical vs Non-Technical Audiences
- Handling Q&A

**Resources:**
- [Toastmasters International](https://www.toastmasters.org/)
- [Coursera — Dynamic Public Speaking Specialization](https://www.coursera.org/specializations/public-speaking)

---

### 🌐 Personal Branding

#### LinkedIn & Portfolio Building
**Time:** 2 weeks

**Topics:**
- LinkedIn Profile Optimization for DS/ML
- GitHub Portfolio Strategy
- Kaggle Rankings & Competitions
- Writing Technical Articles (Medium / Substack)
- Personal Website / CV Website
- Professional Project Documentation

**Resources:**
- [Towards Data Science — Portfolio Guide](https://towardsdatascience.com/how-to-build-a-data-science-portfolio-5f566517c79c)
- [StatQuest — Career Advice for Data Scientists](https://www.youtube.com/@statquest)

---

#### Networking & Community
**Time:** Ongoing

**Topics:**
- Meetups & Conferences (local & online)
- Data Science community on Twitter/X
- Discord Servers (Hugging Face, fast.ai)
- Contributing to Open Source
- Kaggle Discussions & Notebooks
- LinkedIn Outreach Strategy

**Resources:**
- [Kaggle Community](https://www.kaggle.com/discussion)
- [Hugging Face Community](https://discuss.huggingface.co/)

---

### 💼 Freelancing & Business

#### Freelancing as a Data Scientist
**Time:** 3 weeks

**Topics:**
- Setting up Upwork / Toptal Profiles
- Writing Winning Client Proposals
- Project Scoping & Time Estimation
- Contracts, Payments & Deliverables
- Building Reviews & Reputation
- Rate Setting Strategies

**Resources:**
- [Upwork — Freelance Data Science Guide](https://www.upwork.com/resources/how-to-become-a-freelance-data-scientist)
- [Toptal — Data Science Network](https://www.toptal.com/data-science)

---

#### Job Search Strategy
**Time:** 1 month

**Topics:**
- Writing a Professional DS Resume / CV
- Cover Letter for DS Roles
- Technical Interview Preparation
- ML System Design Interviews
- Behavioral Interviews (STAR Method)
- Salary Negotiation
- Evaluating Job Offers

**Resources:**
- [Glassdoor — Data Scientist Interview Questions](https://www.glassdoor.com/Interview/data-scientist-interview-questions-SRCH_KO0,14.htm)
- [Interview Query — DS Interview Prep](https://www.interviewquery.com/)

---

### 🧩 Work & Productivity

#### Project Management for Data Science
**Time:** 2 weeks

**Topics:**
- CRISP-DM Methodology
- Agile for Data Science Teams
- Jira / Notion / Linear for DS Projects
- Research Documentation & Experiment Tracking
- Code Review Best Practices
- Managing Technical Debt

**Resources:**
- [CRISP-DM Guide](https://www.datascience-pm.com/crisp-dm-2/)
- [Chip Huyen — ML Best Practices](https://huyenchip.com/)

---

## ⏱️ Estimated Timeline

| Phase | Duration |
|---|---|
| 0 — Entry Level | 1–2 weeks |
| 1 — Beginner | 2–3 months |
| 2 — Intermediate | 3–4 months |
| 3 — Advanced | 4–5 months |
| 4 — Professional (1 specialization) | 3–5 months |
| Soft Skills | Ongoing throughout |
| **Total** | **~14–19 months** |

---

## 💡 Tips

- **Don't skip Phase 0.** Understanding the field before coding saves you months of confusion.
- **Build projects at every phase.** A GitHub full of real projects > a list of certificates.
- **Pick one specialization.** Going deep beats going wide when you're job hunting.
- **Soft Skills are not optional.** They separate candidates with the same technical level.
- **Use Kaggle.** Competitions, datasets, and notebooks are your best free gym.

---

## 📌 Quick Reference — Core Resources

| Topic | Best Free Resource |
|---|---|
| Python | [CS50P — Harvard](https://cs50.harvard.edu/python/) |
| Statistics | [StatQuest](https://www.youtube.com/@statquest) |
| Linear Algebra | [3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2ZVjFEMk97OoTL) |
| ML | [Andrew Ng — Coursera](https://www.coursera.org/specializations/machine-learning-introduction) |
| Deep Learning | [fast.ai](https://course.fast.ai/) |
| NLP / LLMs | [Hugging Face Courses](https://huggingface.co/learn) |
| MLOps | [Made With ML](https://madewithml.com/) |
| Computer Vision | [CS231n — Stanford](http://cs231n.stanford.edu/) |

---

*Feel free to fork, star ⭐, and share this roadmap. Contributions and suggestions are welcome via Issues and Pull Requests.*
