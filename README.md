<div align="center">

# Ujjawal Maurya

**Software Engineer &nbsp;·&nbsp; AI/GenAI &nbsp;·&nbsp; Backend &nbsp;·&nbsp; Mobile**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ujjawalmauryaum)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ujjawalmauryaum@gmail.com)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-F58025?style=flat-square&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/12053457/ujjawal-maurya)

</div>

---

Building AI-integrated applications and backend systems. I work across the full product stack — from FastAPI services and RAG pipelines to mobile apps and local inference runtimes.

B.Tech CS &nbsp;·&nbsp; 2+ years of Flutter/mobile experience &nbsp;·&nbsp; currently focused on applied GenAI and backend engineering.

---

## 🎯 Current Focus

Building systems where LLMs are an engineering component rather than the product itself — RAG pipelines with source attribution and chunk-level citation, LLM orchestration across multiple providers (Gemini, OpenAI, local Ollama models), and AI agents that interact with real tools and APIs.

On the backend side: FastAPI services, PostgreSQL/Supabase, vector stores (Chroma, FAISS, Qdrant), and Docker-based deployment. On the application side: Flutter for mobile and React for web interfaces.

The common thread is keeping inference grounded — avoiding hallucination through retrieval, proper context management, and memory-safe design.

---

## 📌 Selected Work

### [HackSquad-YUKTI — AI Scout](https://github.com/Ujjawalmaurya/HackSquad-YUKTI) &nbsp;·&nbsp; 🥇 1st Prize, HyperSpace Hackathon 2026

Precision agriculture platform combining YOLOv8 anomaly detection with NDVI computation over aerial drone imagery. Farmers upload drone footage; the backend processes multispectral image channels to compute vegetation health indices and flags disease regions using object detection.

Key engineering: FastAPI inference service + YOLOv8 + NDVI pipeline + GIS visualisation layer + role-based access control. Docker Compose for the full stack.

`Python` · `FastAPI` · `YOLOv8` · `Computer Vision` · `Node.js` · `Docker`

---

### [HyperBrain](https://github.com/Ujjawalmaurya/HyperBrain)

The backend AI service extracted from the agriculture platform. A standalone FastAPI service exposing REST endpoints for NDVI calculation and YOLOv8-based agricultural anomaly detection. Built to be independently deployable and usable by any frontend.

`Python` · `FastAPI` · `YOLOv8` · `REST API`

---

### [Off-Grid-Chat](https://github.com/Ujjawalmaurya/Off-Grid-Chat)

Offline Android AI chat app built with Flutter + llama.cpp via FFI. Runs quantised GGUF models (SmolLM2, Qwen 2.5, Llama 3.2, Phi-3) directly on device with Vulkan GPU acceleration. No internet, no API keys, no telemetry.

Key engineering: runtime Vulkan capability detection with graceful CPU fallback, a sliding-window context buffer (6 turns / 2,048 tokens) to prevent OOM on 4–6 GB devices, and tuned sampling parameters specifically for small-model stability.

`Flutter` · `Dart` · `llama.cpp` · `FFI` · `Vulkan` · `Local Inference`

---

### [WebLLM](https://github.com/Ujjawalmaurya/WebLLM)

Web application that runs LLMs locally inside the browser via WebGPU — no server, no API key, no data leaving the device. Model weights are downloaded and cached in browser storage on first run. Inference runs in a Web Worker to keep the UI responsive, with real-time token streaming into the chat.

Supports Llama 3.2, Gemma 3, Qwen 2.5, Phi 3.5, SmolLM2, Ministral, OLMo 2 — small variants optimised for WebGPU memory limits.

`JavaScript` · `WebGPU` · `Web Workers` · `Local Inference`

---

### [LeagalAI](https://github.com/Ujjawalmaurya/LeagalAI) &nbsp;·&nbsp; [live ↗](https://leagal.streamlit.app/)

RAG application for legal document analysis. Upload any contract or agreement; it extracts risky clauses (auto-renewal, silent data sharing, fee escalations) and answers questions in plain language with page and section citations.

Stack: LangGraph for the RAG workflow, Gemini for embeddings and generation, Chroma as the vector store, Streamlit for the interface. Deployed and live.

`Python` · `LangGraph` · `Gemini` · `Chroma` · `RAG` · `Streamlit`

---

### [smaran](https://github.com/Ujjawalmaurya/smaran)

Flutter library/SDK for bringing RAG capabilities into mobile apps. On-device retrieval pipelines for mobile — a Flutter application queries a local vector store and feeds relevant context to an LLM without a server round-trip.

`Flutter` · `Dart` · `RAG` · `Mobile AI`

---

### [PeerRide + CabContract](https://github.com/Ujjawalmaurya/PeerRide)

P2P cab system with a blockchain escrow backend (Hardhat/Solidity) and a Flutter mobile client for both rider and driver flows. Covers on-chain wallet balance, ride acceptance, and payment settlement.

`Flutter` · `Solidity` · `Hardhat` · `Blockchain` · `Dart`

---

## ⚙️ Engineering Areas

| Domain | Technologies |
| :--- | :--- |
| **AI / GenAI** | LLMs · RAG · LangGraph · LangChain · Ollama · local inference (llama.cpp, WebGPU) · Chroma · FAISS · Qdrant · Gemini · OpenAI |
| **Computer Vision** | YOLOv8 · NDVI computation · multispectral image analysis |
| **Backend** | Python · FastAPI · Node.js · Go · REST · WebSockets |
| **Data** | PostgreSQL · Supabase · MongoDB · vector databases |
| **Mobile / Frontend** | Flutter · Dart · React · JavaScript · TypeScript |
| **Infrastructure** | Docker · Linux (daily driver) · Git |
