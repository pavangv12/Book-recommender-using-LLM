#Semantic Book Recommender using LLMs

Welcome! This project is a **Semantic Book Recommender System** built using the power of **Large Language Models (LLMs)** and **Vector Search**. It combines modern NLP techniques with interactive visualization to deliver meaningful book recommendations based on natural language queries.

> This project reflects my learning journey and practical application of LLMs in semantic search, classification, sentiment analysis, and web-based recommendation systems.

---

## Overview

This project aims to build an intelligent book recommender that understands the context and semantics of your input, rather than relying on keyword matching. The system is built in five major stages:

1. **Data Cleaning & Exploration** – Preprocess and understand the book dataset.
2. **Semantic Search with Vector Databases** – Use embeddings to find books matching a user's query semantically.
3. **Zero-Shot Text Classification** – Classify books into categories like *Fiction* or *Non-Fiction* using LLMs.
4. **Sentiment & Emotion Analysis** – Analyze emotional tones (e.g., joyful, suspenseful) to improve recommendations.
5. **Interactive Dashboard** – A user-friendly Gradio interface for real-time book recommendations.

---

## Tech Stack

- **Python 3.11**
- **LangChain**
- **Gradio**
- **Hugging Face Transformers**
- **Pandas, Matplotlib, Seaborn**
- **OpenAI API for LLM tasks**
- **Chroma for vector storage**
- **Jupyter Notebooks for development and experimentation**

---

## Project Structure

| File / Folder             | Description                                      |
|--------------------------|--------------------------------------------------|
| `data-exploration.ipynb` | Cleaning and analyzing the raw dataset           |
| `vector-search.ipynb`    | Generating embeddings and implementing vector search |
| `text-classification.ipynb` | Zero-shot classification using LLMs         |
| `sentiment-analysis.ipynb` | Sentiment and emotion extraction              |
| `gradio-dashboard.py`    | Web app for interactive book recommendations     |
| `requirements.txt`       | Project dependencies                             |

---

