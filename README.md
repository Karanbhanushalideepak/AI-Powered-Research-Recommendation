# 🔬 AI-Powered Research Recommendation System

An intelligent research assistant platform designed to parse academic papers, extract key domain contexts, and deliver personalized research recommendations leveraging advanced NLP techniques and large language models (LLMs).

---

## 🛠️ Tech Stack:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-886FBF?style=for-the-badge&logo=googlegemini&logoColor=fff)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 🖼️ Interface & Dashboard

Below are previews of the system interface. To display your actual images, name your images `dashboard.png` and `recommendation.png`, upload them to your repository folder, and they will display automatically here.

### Main Dashboard UI
<!-- This acts as a center-aligned image container -->
<p align="center">
  <img src="dashboard.png" alt="System Dashboard UI View" width="100%" />
</p>

### Personalized Recommendation Flow
<p align="center">
  <img src="recommendation.png" alt="Recommendation Logic Interface" width="100%" />
</p>

---

## 🌟 Key Features

* **📄 Academic Document Parsing:** Automatically ingests and parses PDF research papers to build comprehensive vector knowledge stores.
* **🧠 Semantic Recommendation Engine:** Analyzes user research history and reading preferences to recommend contextually relevant papers rather than simple keyword matches.
* **📈 Trend Matrix Graph:** Extracts trending research keywords and groups interconnected academic subjects.
* **⚡ Vector Similarity Search:** Employs high-speed vector embeddings to scan millions of text vectors instantly.

---

## 🚀 Getting Started

### 1. Vector Database Setup
1. Open your terminal environment and launch your local vector instance database (e.g., ChromaDB, Milvus, or FAISS backend).
2. Configure your pipeline parameters in your secure environment layout setup.

### 2. Environment Verification
1. Create a secure local environmental storage configuration file named `.env`:
```text
   GEMINI_API_KEY=your_gemini_api_key_here
   VECTOR_DB_URL=http://localhost:8000
