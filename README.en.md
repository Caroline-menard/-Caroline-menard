# Caroline-menard
<p align="right">
  <img src="https://github.com/Caroline-menard/-Caroline-menard/blob/main/logo_blanc.png?raw=true" alt="Logo Caroline Ménard" width="160">
</p>

👉🇫🇷 [Version Francaise](https://github.com/Caroline-menard/-Caroline-menard/blob/main/README.md)

---

### 👋 Hi, I'm Caroline

I started out teaching mathematics before diving into the fascinating world of data.

Naturally curious and passionate about language, I now work as a data scientist specializing in NLP at the startup **U change**.
I design tools that listen, sort, and explain — all from vast amounts of messy text data.

My projects blend analytical rigor, language processing, and a keen eye for detail.
### 🧪 This portfolio showcases my personal projects.

Because personal projects fuel professional growth — and vice versa.
Exploring, learning, failing, succeeding: here, everything is a reason to grow.

  > *“Once you stop learning, you start dying.”*
  >  — Albert Einstein

Welcome to my world — part algorithm, part poetry...

---

# 1- Amazon Review Classifier & Dashboard

👉 [Check out the project on GitHub](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard)

Language:

➡️ 🇬🇧 [README English version](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard/blob/main/README.en.md)  
➡️ 🇫🇷 [README Version française](https://github.com/Caroline-menard/amazon_review_classifier_and_Dashboard/blob/main/README.md)

**Automatic customer review classification and interactive visualization via Streamlit.**

This NLP project identifies various issue types in Amazon reviews (damaged product, non-compliance, etc.) using a pipeline that combines TF-IDF, semantic features, and XGBoost.

Results can be explored through a dashboard with filters, charts, and data export options.

## Skills Applied in This Project

*Natural Language Processing (NLP):*

  > - Text cleaning and preprocessing, TfidfVectorizer, dimensionality reduction with TruncatedSVD.

*Multi-label Machine Learning:*

  > - Modular pipeline built with scikit-learn.<br>

  > - Training and cross-validation using GridSearchCV.

*Feature Engineering:*

  > - Feature creation using FunctionTransformer.<br>

  > - Custom preprocessing and post-processing classes.

*Data Manipulation:*

  > - Using pandas, numpy.<br>

  > - Optimized storage with .parquet files.

*Light Data Engineering:*

  > - Interaction with a PostgreSQL database hosted on Supabase.<br>

  > - ETL scripts for inserting and updating predictions.

*Interactive Visualization & Presentation:*

  > - Creation of an interactive Streamlit dashboard.<br>

  > - Results visualization, dynamic filters, data export.

*Deployment:*

  > - Dashboard hosted on Streamlit Cloud.<br>

  > - Optimization of requirements.txt for server compatibility.

*Project Organization / Best Practices:*

  > - Script modularization (prediction, ETL, orchestration).<br>

  > - Clean .gitignore, detailed README, architecture visualization.<br>

  > - Clear dependency management and reproducible workflow.<br>

  > - 🧘 Patience and perseverance — essential to tame Streamlit Cloud’s quirks at 2 a.m.

___

# 2. Customer Insight Dashboard (synthetic data)

👉 [Check out the project on GitHub](https://github.com/Caroline-menard/Customer-insight-dashboard)

Language:

➡️ 🇬🇧 [README English version](https://github.com/Caroline-menard/Customer-insight-dashboard/blob/main/README.en.md)  
➡️ 🇫🇷 [README Version française](https://github.com/Caroline-menard/Customer-insight-dashboard/blob/main/README.md)

A lightweight Streamlit dashboard designed to simulate a **client activity analysis tool**, inspired by a real-world use case in a B2B environment.  
The data has been **synthetically generated**, and the code **heavily modified** for confidentiality reasons — yet the app accurately reflects real usage scenarios:  
activity tracking, early signal detection, data export, and automated PDF report generation for client teams.

Targeted at **Customer Success Managers**, **Account Managers**, and **Onboarding Specialists**, this project illustrates how minimal log data can be used to better understand user needs — while preserving their privacy.

## Skills & Key Challenges Addressed

> - Designing an interface tailored for **non-technical users**, with a dashboard that is clear, ergonomic, and business-focused  
> - Optimizing **API connections** using a manual refresh system and local caching of data in `.parquet` format  
> - Analyzing client behavior while ensuring **data confidentiality**, through minimalistic logging and an ethical data-handling approach  
> - Generating a **synthetic dataset** that simulates team structures and diverse user profiles to realistically test the dashboard

