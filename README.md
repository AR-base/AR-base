## Sai Anish Pinninti

MSc student in Cybersecurity and Data Science at ESAIP, Angers (2026–2028), with a B.Tech in Data Science. I build AI applications (retrieval-augmented generation, tool-using agents, assistants) and the security around them, and I ship them: most of the projects below are live.

---

### Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[Atlas](https://github.com/AR-base/atlas)** · [live](https://atlas.anish-pinninti.workers.dev) | Enterprise knowledge agent: one question, and it queries the database, searches internal documents and reads the code, then answers with every query and source it used. Read-only SQL enforced twice. | Claude tool use · SQLite (WebAssembly) · Cloudflare Workers |
| **[Verity](https://github.com/AR-base/verity)** · [live](https://verity.anish-pinninti.workers.dev) | Measurable RAG engine: BM25 + multilingual embeddings, rank fusion, cross-encoder reranking, a citation on every sentence, and a built-in evaluation (hit@k, MRR) of four retrieval methods. | Workers AI (bge-m3, bge-reranker) · Claude · Cloudflare Workers |
| **[Bastion](https://github.com/AR-base/bastion)** · [live](https://bastion.anish-pinninti.workers.dev) | Passive website security scanner: grades headers, HTTPS, cookies and exposure from A to F, with plain-language fixes. Scores A (100/100) on itself. | Cloudflare Workers · Claude · vanilla JS |
| **[ESAIP AI Assistant](https://github.com/AR-base/esaip-ai-assistant)** · [live](https://esaip-ai-assistant.vercel.app) | Bilingual French/English assistant for ESAIP students: arrival steps, visa renewal, housing, alumni. Streaming, file upload, server-side keys. | Vercel Edge · Claude · vanilla JS |
| **[Trim](https://github.com/AR-base/TRIM)** *(team project)* | Least-privilege access control for enterprise AI agents: removes unused permissions and flags agents that behave unlike themselves. | FastAPI · PostgreSQL · React · scikit-learn · Docker · Azure |
| **[PhishLens](https://github.com/AR-base/phishlens)** *(team project)* | Phishing-awareness training: email simulator, AI tutor and URL inspector. | Vercel Functions · Claude · vanilla JS |

Each project has a security section in its README, keeps secrets on the server, validates its inputs and runs its tests in CI.

---

### How I work

- **Measure, don't assume.** Cost per request, test suites, retrieval metrics.
- **Defense in depth.** Strict headers and CSP, size caps, rate limits, least privilege.
- **Honest scope.** Each README states what the project does not do yet.

---

### Contact

psaianish2001@gmail.com · [LinkedIn](https://www.linkedin.com/in/pinninti-sai-anish-2b7125278/) · English (professional), French (intermediate)
