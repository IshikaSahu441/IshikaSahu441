# Ishika Sahu

[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=20&duration=3000&color=FFFFFF&lines=AI+Engineer+%40+xCaliber+Health;Clinical+AI+infrastructure;HDLQL+%7C+Multi-agent+systems+%7C+Voice+AI;Published+in+Applied+AI+%26+Neural+Networks)](https://git.io/typing-svg)

AI Engineer at [xCaliber Health](https://www.xcaliberhealth.ai), building production infrastructure for clinical AI — from a typed healthcare query language and distributed data pipelines to multi-agent memory systems and the real-time voice backbone for [Merlin](https://www.xcaliberhealth.ai/merlin).

[![Resume](https://img.shields.io/badge/Resume-View-blue?logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1tbjbOtayNJDYPNlMZXENfJcenM9gjLmq/view?usp=sharing)

---

## Currently Building @ xCaliber Health

- **Merlin voice backbone** — real-time clinical voice assistant with decoupled STT, LLM reasoning, and TTS; ~4s end-to-end latency over HTTP and WebSocket, alongside a composable role synthesis layer that provisions typed Merlin assistants on demand
- **Risk and quality analytics workflows** — configuration-driven YAML templates with two-layer validation, orchestrated via Temporal across 6 activity workflows; 92% test coverage across 99 tests integrated into CI/CD
- **HDLQL** — in-house typed analytical query language for healthcare data lakes; AWS Glue Catalog as the single schema source of truth with auto-generated .pyi stubs, DAFT as the execution engine, YAML-defined pipelines scaling to Ray cluster distribution
- **Multi-agent session memory** — shared session memory system powering and coordinating Merlin's role-based agents; Redis-backed short-term state with per-agent write isolation, TTL-controlled promotion to KuzuDB for long-term graph storage

---

## Projects

#### [Reflection — AI Interview Preparation Platform](https://github.com/yashrustagi2004/Reflection)
End-to-end RAG pipeline with resume-driven question generation using sentence-transformer embeddings, Pinecone, LangChain, and Gemini, with metadata-filtered retrieval per candidate. Architected 6 independent microservices on Kubernetes with OAuth 2.0 + JWT auth and a Jenkins CI/CD pipeline with git-diff-based change detection.

`Python` `Flask` `LangChain` `Gemini` `Pinecone` `MongoDB` `Kubernetes` `Jenkins`

#### [Anomaly Detection in Human Behaviour](https://colab.research.google.com/drive/1JZookAGvND_-lqOw7-g_I9xD_jSp5icK?usp=sharing)
Hybrid spatial-temporal feature extraction combining LBP-TOP across XY, XT, and YT planes with volumetric LBP, fed into an autoencoder trained on normal behaviour videos. MSE reconstruction error drives anomaly scoring; a fuzzy inference system with percentile-calibrated membership functions produces interpretable severity labels. 90% accuracy on held-out test data.

`Python` `OpenCV` `TensorFlow` `scikit-fuzzy`

#### [Medical Chatbot — RAG-Powered AI Medical Query Assistant](https://github.com/IshikaSahu441/Medical_Chatbot.git)
Flask-based RAG chatbot using LangChain, Pinecone, and Google Gemini to answer medical queries with context-aware retrieval.

`Python` `Flask` `LangChain` `Pinecone` `Gemini`

#### [Phishing Email Detection Extension](https://github.com/yashrustagi2004/Kingfisher.git)
Browser extension for phishing detection combining email header inspection, URL pattern analysis, and NLP-based contextual classification. [NLP Model](https://colab.research.google.com/drive/1nbZ5-bnbRk9NsZTylJRUnHSwPXi3OBaG?usp=sharing)

`Python` `JavaScript` `NLP`

#### [Solar Power Generation Predictor](https://github.com/IshikaSahu441/SKAI.git)
Machine learning model predicting whether future weather conditions are optimal for high solar power generation.

`Python` `Scikit-learn`

---

## Publication

**Anomaly Detection in Human Behaviour Using Computer Vision: A Review**
*Journal of Advanced Research in Applied AI and Neural Network*, Vol. 10, Issue 1, 2026
[View](https://drive.google.com/file/d/1FpE2P6Y0lcMM1n9RAfo1auju0bTAwzOS/view?usp=sharing)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Data & Databases**

![Apache Iceberg](https://img.shields.io/badge/Apache_Iceberg-0070C0?logo=apache&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?logo=temporal&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)

**ML / AI**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)

---

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/ishika-sahu-900a5924a" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:ishika.sahu1942@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>
