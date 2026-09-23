# Hi, I'm Liheng Ye

**Agent application development** · Python, LangGraph & TypeScript · 叶立恒

Building AI applications and submitting patches to [Tencent/WeKnora](https://github.com/Tencent/WeKnora) and [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) · Open to Agent / LLM application development opportunities

> I build agent workflows with explicit state, traceable evidence, and clear failure handling.

## What I work on

- **Agent workflows** — interview planning, question generation, validation and repair, with a separate workflow for answer evaluation. Built with LangGraph and structured intermediate state. ([project](https://github.com/yeliheng-010/ai-interview-studio) · [write-up](https://blog.miansu.eu.cc/posts/langgraph-interview-workflow/))
- **Code retrieval & tools** — combine keyword and vector search with symbol graphs, graph expansion and call-path tools; expose citations and execution traces in the UI. ([project](https://github.com/yeliheng-010/CodeRag) · [write-up](https://blog.miansu.eu.cc/posts/agentic-graphrag-learning-notes/))
- **Integration reliability** — investigate HTTP failures, incomplete resource discovery and inconsistent UI state; turn reproducible bugs into small patches and regression tests. ([upstream PRs](https://github.com/search?q=is%3Apr+author%3Ayeliheng-010+-user%3Ayeliheng-010&type=pullrequests))

## Projects

- **[AI Interview Studio](https://github.com/yeliheng-010/ai-interview-studio)** — an interview practice application that turns a resume and job description into tailored questions, supports regeneration, and evaluates written answers. LangGraph + FastAPI + PostgreSQL + Next.js.
- **[CodeRag](https://github.com/yeliheng-010/CodeRag)** — an Agentic GraphRAG application for code repositories, with symbol-aware retrieval, call-path exploration and evidence-backed answers. Tree-sitter + KuzuDB + Chroma + LangGraph.

## Open-source work

Selected submitted patches — **all four PRs are open, not yet merged, as of September 23, 2026**. Links below show their latest status.

- **LightRAG: model API errors** — reject unsuccessful HTTP responses before consuming generated text, streams or embeddings; add regression coverage and fix a CI mock compatibility issue. ([#4057](https://github.com/HKUDS/LightRAG/pull/4057) · [write-up](https://blog.miansu.eu.cc/posts/lightrag-lollms-http-errors/))
- **WeKnora: resource discovery** — follow GitLab pagination headers so project discovery returns more than the first 100 resources; test later-page failures. ([#3624](https://github.com/Tencent/WeKnora/pull/3624) · [write-up](https://blog.miansu.eu.cc/posts/weknora-gitlab-pagination/))
- **WeKnora: multimodal inspection** — add OCR and image-description chunk filters, preserving the selected type across reloads and resetting it when returning to full-text view. ([#3548](https://github.com/Tencent/WeKnora/pull/3548) · [write-up](https://blog.miansu.eu.cc/posts/weknora-chunk-type-filter/))
- **WeKnora: developer docs** — clarify Swagger access under Docker Compose, including backend ports, runtime mode and container recreation. ([#3620](https://github.com/Tencent/WeKnora/pull/3620) · [write-up](https://blog.miansu.eu.cc/posts/weknora-swagger-docker/))

Reproduction steps, validation scope and AI-assisted development details are documented in the linked PRs and write-ups.

📫 [yeliheng3@gmail.com](mailto:yeliheng3@gmail.com) · [Blog / 中文技术笔记](https://blog.miansu.eu.cc)
