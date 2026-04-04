---
layout: page
title: About
---

I build production-grade systems across B2B SaaS, real-time communications, and AI infrastructure.

I joined [FreJun](https://frejun.com){:target="_blank"} in 2022 and spent nearly 4 years as part of the founding team, initially as a full-stack engineer and later as tech lead. During this time, I helped build the voice platform from the ground up, growing it to process 500K+ calls daily with global reach and high availability.

In 2025, I led the development of [FreJun Teler](https://frejun.ai){:target="_blank"}, building voice infrastructure designed for the AI era.

Following this, I operated independently, working closely with startups to ship end-to-end systems, including voice AI infrastructure at [BotSpace](https://www.bot.space/){:target="_blank"} and a fully local, [enterprise RAG system](/blog/rag){:target="_blank"}.

Recently, I joined [Glacis](https://glacis.com){:target="_blank"} as a founding engineer, where I'm building at the intersection of supply chains and Agentic AI.

Reach out to me at [hello@robinsharma.me](mailto:hello@robinsharma.me)

## Projects

### [Teler](https://frejun.ai){:target="_blank"}
Voice Infrastructure for AI Agents.

Built on a distributed microservice architecture, Teler delivers advanced capabilities including SIP trunking, bidirectional media streaming, and real-time STT/TTS. Apart from building Teler's core VoIP infrastructure, I also wrote the [Python SDK](https://pypi.org/project/teler/){:target="_blank"}, many [reference implementations](https://github.com/frejun-tech){:target="_blank"}, and the Docusaurus-based [developer documentation](https://frejun.ai/docs/){:target="_blank"}.

### [Enterprise RAG](/blog/rag){:target="_blank"}
A fully offline, advanced RAG system designed for secure, enterprise deployments. 

Integrates hybrid retrieval combining BM25 ranking with Dense vector search, leverages high-throughput vLLM inference for scalable LLM and embedding workloads, and employs advanced chunking strategies to preserve semantic and structural fidelity. It further supports asynchronous, distributed file indexing with robust status tracking, and provides native ingestion for a broad spectrum of enterprise document formats including *PDF, DOCX, PPTX, XLSX, CSV, and Markdown*.

This project inspired my recent blog post [Enterprise RAG: Production-grade RAG goes offline](/blog/rag){:target="_blank"}.

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