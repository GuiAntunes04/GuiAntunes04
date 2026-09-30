<div align="center">

# Hi, I'm Guilherme Antunes

**Back-End Developer** · Information Management student at **Federal University of Uberlândia (UFU)**

Building REST APIs, data-driven systems and applied AI solutions with Python, Java and TypeScript.

[![GitHub](https://img.shields.io/badge/GitHub-GuiAntunes04-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GuiAntunes04)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-antunes04)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guilherme.hrq.antunes@gmail.com)

</div>

---

## About Me

I'm a back-end developer focused on designing clean, well-documented APIs and integrating them with databases, third-party services and AI models. My work ranges from machine learning classifiers to full-stack platforms deployed in production.

- Building back-end services with **Java / Spring Boot**, **Python / FastAPI** and **Node.js / Express**
- Working with relational and NoSQL databases: **PostgreSQL**, **MySQL**, **MongoDB** and **Supabase**
- Applying **machine learning** and **LLMs** (Google Gemini) to solve real-world problems
- Currently pursuing a Bachelor's degree in Information Management at **UFU**, combining business insight with software engineering

---

## Tech Stack

| Area | Technologies |
|------|--------------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white) |
| **Back-End** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) |
| **AI & ML** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-017CEE?style=flat-square) ![Optuna](https://img.shields.io/badge/Optuna-2C5BB4?style=flat-square) ![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) |
| **Front-End** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |
| **Tools & Cloud** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) |

---

## Featured Projects

### [ENEM Prep AI](https://github.com/GuiAntunes04/guilherme-antunes-enem-ai-challenge)
Full-stack study platform for Brazil's national university entrance exam (ENEM). Features timed mock exams with ~4,800 real questions, an AI tutor, automated essay grading across the five official ENEM competencies, and a performance dashboard.

- Question bank synced from the EnemHub API and cached in Supabase to bypass external rate limits
- LLM-powered tutoring, essay topic generation, grading and OCR import (photo/PDF/DOCX) with Google Gemini
- API key and model fallback strategy to handle quota limits and model overload

**Stack:** React · TypeScript · Node.js · Express · Supabase (PostgreSQL, Auth, RLS) · Google Gemini · Vercel · Render
**Live:** [enem-prep-ai.vercel.app](https://enem-prep-ai.vercel.app/)

### [Exoplanet Classifier](https://github.com/GuiAntunes04/exoplanet-classifier)
Machine learning system that distinguishes confirmed exoplanets from false positives using 24+ astronomical features from the Kepler, TESS (TOI) and K2 missions. Built for the NASA Space Apps Challenge.

- XGBoost binary classifier with one-hot encoding and missing-value imputation
- Web interface for single-object classification and batch processing via CSV/Excel

**Stack:** Python · XGBoost · Streamlit
**Live:** [exoplanet-classifier.streamlit.app](https://exoplanet-classifier-spaceappschallenge.streamlit.app/)

### [Cryptonit API](https://github.com/GuiAntunes04/cryptonit-api)
Crypto portfolio management API with hybrid persistence and live market data from Binance.

**Stack:** Java · Spring Boot · PostgreSQL · MongoDB · Binance API

### [Crypto Buying System](https://github.com/GuiAntunes04/Crypto-Buying-System)
REST API for tracking crypto buy/sell transactions, calculating average cost, unrealized profit/loss and per-asset analytics with real-time prices.

- MongoDB Atlas with aggregation pipelines and indexing for query optimization
- Modular architecture (routes, services, connections, models)

**Stack:** Python · FastAPI · MongoDB Atlas · Streamlit · Binance API
**Live:** [crypto-buying-system.streamlit.app](https://crypto-buying-system.streamlit.app/)

### [AINET Coffee](https://github.com/GuiAntunes04/ainet-coffee)
Computer vision pipeline for the [Kaggle AINET Coffee](https://www.kaggle.com/competitions/ainet-coffee/overview) competition, classifying coffee beans into five ripeness classes.

- Custom CNN and MobileNetV2 transfer learning
- Automated hyperparameter tuning with Optuna and stratified k-fold validation
- Reproducible experiment tracking with YAML configs and per-run metadata

**Stack:** Python · TensorFlow · Keras · Optuna

### Other Projects

| Project | Description |
|---------|-------------|
| [Projeto_Lstm](https://github.com/GuiAntunes04/Projeto_Lstm) | Bitcoin price forecasting with LSTM neural networks |
| [java-spring-api](https://github.com/GuiAntunes04/java-spring-api) | REST API built with Java and Spring Boot |
| [chess-java](https://github.com/GuiAntunes04/chess-java) | Console chess game applying object-oriented design in Java |

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=GuiAntunes04&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GuiAntunes04&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

</div>

---

## Get in Touch

I'm open to internship and junior back-end opportunities, as well as collaborations on projects involving APIs, data and AI. Feel free to reach out.

- **LinkedIn:** [linkedin.com/in/guilherme-antunes04](https://www.linkedin.com/in/guilherme-antunes04)
- **Email:** guilherme.hrq.antunes@gmail.com
