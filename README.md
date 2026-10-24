# Roger Le

**AI Agent Systems · Quantitative Research · Workflow Automation**

I build AI systems that run unattended in production — research agents, RAG pipelines, and quantitative trading infrastructure — and I publish the proof.

## Featured work

- **[rag-with-receipts](https://github.com/lechangxu/rag-with-receipts)** — a RAG service where every answer must show its source, sentence by sentence, or get flagged. Runtime citation verification + an eval harness that ships in the repo. Runs keyless in 5 minutes; 15 tests, CI-green.
- **[finnews-extractor](https://github.com/lechangxu/finnews-extractor)** — Chinese financial news → structured events, with source grounding verified independently of the model: every extraction span and attribute value is re-located in the original text, or flagged as a hallucination. Golden fixture from a real LLM run; 16 tests, CI-green, keyless.
- **[llm-data-warehouse-demo](https://github.com/lechangxu/llm-data-warehouse-demo)** — a miniature modern data warehouse done properly: Delta Lake ODS→DWD→DWS→ADS layering, executable quality gates (incl. a raw-vs-clean reconciliation gate), an SFT dataset pipeline, and a metric dictionary whose definitions are pinned by tests. PySpark 4 / Delta 4, CI-green.
- **[quant-research-portfolio](https://github.com/lechangxu/quant-research-portfolio)** — methodology from production systematic trading: a live-vs-backtest divergence audit (including a risk overlay that silently locked 86.8% of out-of-sample paths), a four-threshold factor acceptance gate, and a negative-results log — plus a tested mini-framework implementing the gate.
- **[Query-Web3](https://github.com/Query-Web3)** — **Product manager** for a Polkadot-ecosystem BI + AI data platform funded by the Web3 Foundation: 0→1 across requirements, PRD, UI prototypes and milestone acceptance checklists. Milestone 1 — data indexer, data model and admin backend — passed the foundation's review, and the team's shipped code is public under the org.

## Production systems (demo on request)

- **Market-intelligence data service for AI agents** — a production MCP service that answers agent queries over a continuously collected market dataset. Source is private. Demo available on request.
- **ReadLeap** — an AI-graded English reading product: adaptive vocabulary assessment, leveled generation, and spaced review. The PRD went through many revisions and the product runs in closed beta. Source is private. Demo available on request.

## What I work on

- **AI Agent Orchestration** — multi-agent systems, LLM/RAG pipelines, MCP tool integration, confidence-gated automation
- **Quantitative Systems** — multi-factor models, backtesting engines, live trading pipelines (A-share & crypto)
- **Workflow Automation** — n8n / Dify based business automation, document extraction with source grounding

## Experience

- **Query-Web3** — product manager; AI-powered information service platform in the Polkadot ecosystem
- 20 years across software engineering, product management, enterprise consulting (insurance, banking, and large-scale BI transformation programmes), and quantitative finance
- MBA (ECUST) · Master's degree in Economic Philosophy (SUFE)

## Currently

Building autonomous research & trading infrastructure. Most of my active work lives in private repositories — the pinned projects above are the public, runnable evidence of how I build, and where a system cannot be public I am glad to show it live instead.
