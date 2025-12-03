---
layout: single
author_profile: true
title: "Projects"
permalink: /projects/
---

# 📂 Projects

A collection of my end-to-end AI, geospatial, NLP, and multi-agent systems projects.  
Each project showcases practical problem-solving, systems design, and scalable AI engineering.

---

## 🗺️ **GeoExpert-QA**  
A **zero-shot geospatial question-answering agent** capable of complex spatial reasoning, code generation, and dynamic map visualization.  
Built using Python, PyTorch, GeoPandas, Folium, Streamlit, and a multi-expert architecture.

### 🔥 Key Features
- Zero-shot reasoning over **real geospatial data**  
- Retrieves shapes, boundaries, coordinates, environmental parameters  
- Generates **executable Python code** to answer queries  
- Supports spatial analytics, geometric reasoning, adjacency matrices, area comparison, environmental queries  
- Dynamic map output via custom GeoPatch objects  

### 🧠 Example Abilities
- Compare areas of countries (Russia vs Greenland)  
- Get air quality of any region  
- Check if geographical points form geometric shapes  
- Generate adjacency matrices of US states  
- Solve spatial-temporal queries using multiple expert modules  

### 🔗 View Code  
https://github.com/Abishekkarthik07/GeoExpert-QA

<p style="margin-top:0.5rem;"><a href="/projects/geoexpert-qa/" style="background:#1a73e8;color:#fff;padding:8px 12px;border-radius:6px;text-decoration:none;">Learn more</a></p>

---

## 🧠 **MindVault – AI Personal Knowledge Chatbot**  
An AI-powered personal knowledge assistant that lets you **upload PDFs, DOCX, TXT, or MD files** and instantly query them using vector search + LLMs.

### 🔥 Key Features
- Upload documents → extract + chunk text via LangChain  
- Embeddings using *sentence-transformers/all-mpnet-base-v2*  
- Semantic search using **FAISS**  
- LLaMA-3 70B (via Groq API) for rich, contextual answers  
- Maintains conversational memory  
- Simple Streamlit UI for real-time Q&A  
- Fully local embedding + vector search pipeline  

### 🔧 Tech Stack
Python, Streamlit, LangChain, FAISS, HuggingFace, Groq API  

### 🔗 View Code  
https://github.com/Abishekkarthik07/MindVault

<p style="margin-top:0.5rem;"><a href="/projects/mindvault/" style="background:#1a73e8;color:#fff;padding:8px 12px;border-radius:6px;text-decoration:none;">Learn more</a></p>

---

## 🎥 **StoryFromVideo-AI (Vid2Story Generator)**  
A fully offline, open-source tool that turns short videos into **coherent AI-generated stories**.

### 🔥 Features
- Upload any short video  
- Whisper → speech transcription  
- BLIP → image captioning from video frames  
- OpenCV → frame extraction  
- Offline story generator  
- Choose genres (horror, comedy, sci-fi, etc.)  
- Download story as `.txt`  
- Runs 100% locally — **no paid APIs**  

### 🧰 Tech Stack
Streamlit, Whisper, BLIP, OpenCV, GPT-3.5 equivalent via open-source models  

### 🔗 View Code  
https://github.com/Abishekkarthik07/StoryFromVideo-AI

<p style="margin-top:0.5rem;"><a href="/projects/storyfromvideo-ai/" style="background:#1a73e8;color:#fff;padding:8px 12px;border-radius:6px;text-decoration:none;">Learn more</a></p>

---

## 📈 **MultiAgent-Stock-Advisor**  
A **multi-agent financial portfolio manager** combining LLM reasoning with quantitative investing models.

### 🔥 System Highlights
#### 8-Agent Architecture  
**AI Agents inspired by legendary investors:**  
- Warren Buffett Agent  
- Charlie Munger Agent  
- Peter Lynch Agent  
- Ben Graham Agent  

**Non-AI Agents:**  
- Fundamentals Agent  
- Valuation Agent  
- Technicals Agent  
- Sentiment Agent  

**Plus:**  
- Risk Manager  
- Portfolio Manager (final decision synthesis)

#### 📊 What It Does
- Pulls financial metrics, insider trades, and news  
- AI agents generate human-like reasoning  
- Non-AI agents compute ratios, DCFs, valuations  
- Portfolio Manager aggregates signals into buy/sell/hold  
- Includes simulation engine and portfolio logs  

### 🧰 Tech Stack
Python, LLM reasoning, quantitative finance models, API-based financial data, modular agents  

### 🔗 View Code  
https://github.com/Abishekkarthik07/MultiAgent-Stock-Advisor

<p style="margin-top:0.5rem;"><a href="/projects/multiagent-stock-advisor/" style="background:#1a73e8;color:#fff;padding:8px 12px;border-radius:6px;text-decoration:none;">Learn more</a></p>

