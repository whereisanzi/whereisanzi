# Anderson Anzileiro

**Senior / Staff Software Engineer · Backend · Fintech & Distributed Systems**

I build backend systems for fintech, payments, and regulated platforms. Occasionally with LLMs in them, but the craft is the systems.

## What I'm building

I build **[Maracatu](https://maracatu.org)** ([github.com/maracatu-org](https://github.com/maracatu-org)), a personal civic-tech project that uses AI to make Brazilian public spending accessible to any citizen: ask in plain Portuguese, get answers grounded in official sources. It started from my curiosity about LLMs and public data, and I keep building it to learn. Some pieces are open (the models and the systems tooling below); the platform itself is a live product.

### LLMs & open weights
- **[maracatu-llm](https://github.com/maracatu-org/maracatu-llm)**, Open-weight Brazilian-Portuguese foundation models trained from scratch (Maracatu-20M / 80M). Llama-style decoder-only transformers; open weights on [Hugging Face](https://huggingface.co/maracatu-labs) and Ollama. Apache 2.0.

### Systems & performance
- **[catraca](https://github.com/maracatu-org/catraca)**, Single-host L4 TCP connection dispatcher in Rust (MIT). `io_uring` multishot accept + `SCM_RIGHTS` zero-copy fd hand-off. ~300 lines, no async runtime.

### Architecture & backend
- **[tag](https://github.com/whereisanzi/tag)**, *The Architecture of Gateways*. Opinionated Python platform pattern combining DDD, hexagonal architecture, and functional programming (MIT).

## What I specialize in

- **Backend & distributed systems**, Python, TypeScript, Node.js, AWS
- **Fintech & RegTech**, payments, AML/compliance, regulated platforms
- **Microservices, event-driven, observability, reliability**, production scale, instrumentation, graceful recovery
- **Platform engineering**, architecture standards, internal SDKs, engineering practices
- **AI-fluent**, LLM, RAG, AI agents when the problem earns it

## Currently

Open to **Senior or Staff Software Engineer** roles in backend, distributed systems, and fintech. Brazil-remote or LATAM-remote. EN/PT fluent.

## Get in touch

[LinkedIn](https://linkedin.com/in/whereisanzi) · [X](https://x.com/whereisanzi) · [Hugging Face](https://huggingface.co/whereisanzi) · [Kaggle](https://kaggle.com/whereisanzi)
