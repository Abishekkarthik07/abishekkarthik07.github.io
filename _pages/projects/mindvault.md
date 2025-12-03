---
layout: single
title: "MindVault"
permalink: /projects/mindvault/
author_profile: true
---

## MindVault

An AI-Powered Personal Knowledge Assistant

MindVault is a project I built to solve a problem I kept running into: I often take notes, collect PDFs, save research articles, and write summaries—but when I need a specific piece of information later, finding it is surprisingly difficult. Scrolling through hundreds of pages or manually searching isn’t efficient, especially when the information is distributed across multiple documents and formats.

I wanted an assistant that could ingest all of my notes and allow me to query them naturally, almost like talking to someone who has read everything I’ve ever written or saved. That idea became MindVault.

## Motivation

Most search tools rely on keyword matching, which only works if you remember the exact words you used. I wanted something more flexible—a system that understands meaning, retrieves the most relevant pieces of text, and then uses an LLM to produce a clear, contextual answer.

## What MindVault Does

MindVault allows the user to upload documents in various formats (PDF, DOCX, TXT, Markdown). After a file is uploaded, the system:

- Extracts and cleans the text
- Splits the text into semantic chunks using LangChain
- Generates embeddings for each chunk with `all-mpnet-base-v2`
- Stores vectors in a FAISS index for fast retrieval

When the user asks a question, MindVault retrieves relevant chunks and uses an LLM to produce a grounded answer. The system also maintains conversational context across queries.

## How It Works

1. Document Parsing — extract text reliably using format-specific parsers
2. Chunking & Embedding — semantic chunking and vectorization
3. Vector Storage — FAISS index for similarity search
4. Answer Generation — retrieve context and generate answers via LLM

## Technologies Used

- Python, Streamlit
- LangChain, FAISS
- HuggingFace sentence-transformers
- Groq API (LLaMA-3 70B)

## What I Learned

- Vector databases and retrieval strategies
- Document parsing and chunking
- Integrating LLMs with retrieval pipelines

<p style="margin-top:1rem;"><a href="https://github.com/Abishekkarthik07/MindVault" style="text-decoration:none;"><strong>[View code]</strong></a></p>

<p style="margin-top:1rem;"><a href="/projects/" style="text-decoration:none;color:#1a73e8;">← Back to Projects</a></p>
