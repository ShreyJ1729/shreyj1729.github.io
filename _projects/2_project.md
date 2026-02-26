---
layout: page
title: "LeelaFAQuantum"
description: "FAQ engine and RAG backend for LeelaQ — semantic search over YouTube transcriptions."
img: assets/img/2.jpg
importance: 2
category: work
---

**Frontend:** [github.com/ShreyJ1729/leelafaquantum](https://github.com/ShreyJ1729/leelafaquantum) &nbsp;/&nbsp; **Backend:** [github.com/ShreyJ1729/leelafaquantum-backend](https://github.com/ShreyJ1729/leelafaquantum-backend)

A full-stack FAQ engine for LeelaQ. The Next.js frontend lets users ask questions and receive answers sourced directly from LeelaQ YouTube video content.

The backend scrapes YouTube channels, downloads and transcribes videos, stores embeddings in ChromaDB, and exposes a FastAPI endpoint for semantic search via OpenAI embeddings. Built as a RAG (Retrieval-Augmented Generation) pipeline.

**Stack:** Next.js, FastAPI, ChromaDB, OpenAI embeddings, Whisper
