# Ashes Born

**TypeScript / Agent engineer.** I build retrieval and agent systems in TypeScript — graph-based RAG, MCP servers, and the engines and interfaces around them.

Ex-frontend architect at JD (京东) and Compass Inc. (NYSE: COMP), last at Yellow (Web3 trading). Now full-time on [graphrag-ts](#-graphrag-ts--typescript-graphrag-with-evidence) and looking for **Agent / frontend engineering** roles (remote).

📧 [justlikeashes@gmail.com](mailto:justlikeashes@gmail.com) · ✍️ [blog.ashesborn.cloud](https://blog.ashesborn.cloud/) · 💼 [graphrag-ts](https://github.com/sadofriod/graphrag-ts)

---

## 🔭 graphrag-ts — TypeScript GraphRAG with evidence

A reference GraphRAG implementation for Markdown corpora: build a knowledge graph in PostgreSQL, detect communities, and answer with evidence-backed hybrid retrieval — **without a Python runtime**.

- **Build pipeline** — markdown-aware ingestion, entity / relationship / claim extraction, Leiden community detection, full + incremental builds that reuse unchanged community summaries.
- **Retrieval** — vector + keyword + graph hybrid, plus corpus-wide Map-Reduce (global) queries; every answer is grounded in retrieved source chunks.
- **MCP server** — isolated workspaces, Docker Compose deployment, connectable from any MCP client.
- **Benchmark** — 10/12 strict hits and 95.8% combined lexical recall on a 12-question in-corpus set (5 chapters, self-run; small-scope, not a cross-project comparison).

Writing on how it works: [index pipeline & incremental update](https://blog.ashesborn.cloud/blog/article-48439fbce06b) · [retrieval](https://blog.ashesborn.cloud/blog/article-41f472d98d25) · [incremental builds](https://blog.ashesborn.cloud/blog/article-e98105d779d1) · [global Map-Reduce queries](https://blog.ashesborn.cloud/blog/article-9b49bb9ddfb1)

## 🛠 What I'm building now

- **Research intelligence over graph RAG** — turning research reports (PDF → structured Markdown, tables preserved) into evidence-traced relationship intelligence, with confidence-weighted graph edges and multi-tier verification.
- **Incremental topology stability** — local community recomputation, stable IDs, versioned snapshots, so a small input change doesn't drift the whole community structure.
- **MCP distribution** — making graphrag-ts installable and discoverable from MCP clients (Registry, awesome-mcp-servers, mcp.so, LobeHub, Glama).
- **Long-form fiction agent** — solving the "forgetting" and hallucination problems of million-word serialized writing.

## 🧩 Selected earlier work

- **京东视界 (jdv.jd.com)** — low-code data-visualization platform behind JD 11.11 / 6.18 campaigns and internal dashboards: state management, layered-cache history, component grouping, three.js / D3 visualization components, drag-and-realtime performance.
- **Salesforce rule & UI engine (Compass)** — migrated auth for every Compass user by rendering Salesforce rules as a finite state machine, translating the Salesforce dialect to AST with PEG.js and executing it in a self-built sandbox.
- **Incremental E2E testing (Compass)** — Git-diff + AST-based two-level test-to-code tracing to cut CI E2E runtime; React partial HMR in a MonoRepo via a shared React instance.
- Patent: *React-based Turing-complete form rendering system* (ID 202110043108.9).

## 🧰 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?logo=bun&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-6E56CF)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?logo=d3&logoColor=white)

## 📊 GitHub stats

![](https://github-readme-stats.vercel.app/api?username=sadofriod)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=sadofriod)

<details>
<summary><b>中文简介</b></summary>

TypeScript / Agent 工程师。8 年前端与架构经验：京东低代码可视化平台（京东视界 jdv.jd.com）→ Compass Inc.（NYSE: COMP，微前端 / Salesforce 规则与 UI 引擎 / E2E 增量测试）→ Yellow 欧洲 Web3 交易平台。持专利「基于 React 的图灵完备表单渲染系统」。

目前全职开发 [graphrag-ts](https://github.com/sadofriod/graphrag-ts)：TypeScript + PostgreSQL/pgvector 的 GraphRAG 引擎，覆盖 Markdown 摄取、实体/关系抽取、Leiden 社区检测、增量构建、向量+关键词+图结构混合检索、Map-Reduce 全局查询与 MCP 服务端。

技术文章：[索引管道与增量更新](https://blog.ashesborn.cloud/blog/article-48439fbce06b) · [检索实现](https://blog.ashesborn.cloud/blog/article-41f472d98d25) · [增量构建](https://blog.ashesborn.cloud/blog/article-e98105d779d1) · [Global Map-Reduce 查询](https://blog.ashesborn.cloud/blog/article-9b49bb9ddfb1)

求职方向：Agent 开发 / 前端开发（远程）。邮箱 justlikeashes@gmail.com

</details>

---

<sub>Open to Agent engineering and frontend architecture roles — remote, English or Chinese.</sub>