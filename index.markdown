---
layout: page
title: About
---

#### Hi :wave:

I'm a software developer with 4+ years of experience building scalable systems across SaaS, real-time communications, and AI.

I joined [FreJun](https://frejun.com){:target="_blank"} in 2022 as a founding engineer and helped build and scale the platform from the ground up, growing it to process 500K+ calls daily with global reach and high availability. In 2025, I built and launched [Teler](https://frejun.ai){:target="_blank"}, a voice infrastructure platform for AI Agents. Since November 2025, I've been working independently as a contractor, primarily building solutions in the Enterprise and Voice AI space. 

Being an obsessive learner and problem solver, I'm always on the lookout for exciting problems to work on. Please feel free to get in touch with me at [hello@robinsharma.me](mailto:hello@robinsharma.me)

## Projects

### [Enterprise RAG](/blog/rag){:target="_blank"}
A fully offline, advanced RAG system designed for secure, enterprise deployments. 

Integrates hybrid retrieval combining BM25 ranking with Dense vector search, leverages high-throughput vLLM inference for scalable LLM and embedding workloads, and employs advanced chunking strategies to preserve semantic and structural fidelity. It further supports asynchronous, distributed file indexing with robust status tracking, and provides native ingestion for a broad spectrum of enterprise document formats including *PDF, DOCX, PPTX, XLSX, CSV, and Markdown*.

This project inspired my recent blog post [Enterprise RAG: Production-grade RAG goes offline](/blog/rag){:target="_blank"}.

### [Teler](https://frejun.ai){:target="_blank"}
Voice Infrastructure for AI Agents.

Built on a distributed microservice architecture, Teler delivers advanced capabilities including SIP trunking, bidirectional media streaming, and real-time STT/TTS. Apart from building Teler's core VoIP infrastructure, I also wrote the [Python SDK](https://pypi.org/project/teler/){:target="_blank"}, many [reference implementations](https://github.com/frejun-tech){:target="_blank"}, and the Docusaurus-based [developer documentation](https://frejun.ai/docs/){:target="_blank"}.

### [Kinto (Open-source)](https://github.com/Kinto/kinto){:target="_blank"}
A generic JSON document store with sharing and synchronisation capabilities. Used at [Mozilla](https://www.mozilla.org/){:target="_blank"}.

My contributions include implementing metrics for [cache](https://github.com/Kinto/kinto/pull/3566){:target="_blank"} and [failed authentications](https://github.com/Kinto/kinto/pull/3577){:target="_blank"}.

### [Conduit](https://rhythmiqcx.com/){:target="_blank"}
Real-time messaging backend powering [RhythmiqCX](https://rhythmiqcx.com/){:target="_blank"}.

I've written more about Conduit in this [blog post](/blog/conduit){:target="_blank"}.

### [Local Voice](https://github.com/Robin-07/local-voice){:target="_blank"}
Locally running AI voice assistant for low-latency conversations, powered by OpenAI Whisper, Ollama, and Piper TTS.

Delivers < 1s round-trip latency on consumer hardware owing to a hybrid design combining multiprocessing and asyncio.

### [VoIP Dialer](https://chromewebstore.google.com/detail/frejun-chrome-dialler-plu/eninbjdhgaccikhclpomppfcclammnoc?hl=en){:target="_blank"}
A chrome extension which allows users to make/receive calls directly from the browser.

Currently serves 5000+ daily active users. Powered by WebRTC and SIP.js.