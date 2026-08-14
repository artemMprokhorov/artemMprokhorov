# Hi there, I'm Artem! 🚀

### AI-native Android Engineer | AI Memory Architect & Researcher

*Persistent memory architectures for AI agents — from spreading activation to shipping binaries.*

---

## 🧠 Current Work: Seventh Wall Lab — We give agents memory, the kind experience grows out of.

*Local-first, brain-inspired associative memory for AI agents. Your data stays on your machine.*

**Mehengram** — a memory graph written in Rust, running as an MCP server, shipping as a signed single binary with no external database. Currently in pre-release.

| Layer | What it does |
| --- | --- |
| **Retrieval** | Spreading activation over an engram graph — convergent evidence accumulates rather than being ranked path by path |
| **Consolidation** | Sleep cycles, light and deep: dedup, edge re-weighting, relation extraction, topic derivation — deterministic, no model in the loop |
| **Forgetting** | Edge decay with anchor policies, so chosen categories resist aging instead of everything fading uniformly |
| **Isolation** | Peripheral namespaces — domain subgraphs that consolidate independently and can be cherry-picked across |
| **Writeback** | A short-term capture tier with agent-side hooks, feeding consolidation without manual bookkeeping |

**The thesis:** *Model = substrate, personality = memory.* The graph holds the language model as an external library, not the other way around. Structure computes on its own; the model attaches at the language boundary.

**Why that matters:** when consolidation, importance, and concept extraction are implemented as model calls, they stop the moment the key is removed — and what remains is an index of logs. Mehengram is built so activation, consolidation, and decay run with no model present at all.

### Lineage

| Project | Description |
| --- | --- |
| **[HippoGraph Pro](https://github.com/artemMprokhorov/hippograph-pro)** | Self-hosted associative memory. BGE-M3 + BM25 + cross-encoder reranking + lateral inhibition. LOCOMO: **69.4% Recall@5**, zero LLM API cost. |
| **[HippoGraph](https://github.com/artemMprokhorov/hippograph)** | Python release. Spreading activation search, entity graph, MCP integration. |
| **[Neural Memory Graph](https://github.com/artemMprokhorov/neural-memory-graph)** | GraphRAG with associative memory and weight-based decay. |
| **[Semantic Memory MCP](https://github.com/artemMprokhorov/semantic-memory-mcp)** | Lightweight MCP server for persistent LLM memory. Where this all started. |

---

## 🔬 Other Projects

| Project | Description |
| --- | --- |
| **[Cinemy](https://github.com/artemMprokhorov/cinemy)** | Agentic coding benchmark — a full Android app built with zero manual code. Server-Driven UI + on-device ML. |

---

## 💼 Professional

**Senior Android Engineer @ Scotiabank Chile (Fabrica Digital)**
Core banking features, MVI architecture, Jetpack Compose at scale. 20+ years in IT.

---

## 🛠 Tech Stack

| Area | Technologies |
| --- | --- |
| **AI / Memory** | Rust, Spreading Activation, MCP, HNSW, BGE-M3, GraphRAG, BM25, GLiNER2 |
| **Mobile** | Kotlin, Jetpack Compose, Clean Architecture |
| **Infrastructure** | Docker, Python, FastAPI, SQLite, NetworkX |

---

## 🔭 Currently Exploring

- **Predictive memory** — a JEPA-style predictor over the graph's node space: prospection and pattern completion in latent space, with prediction error replacing manually assigned importance
- **AI identity continuity** — how much of an agent survives a substrate swap. Entry-point swaps preserve behaviour; whether a different base model reconstructs the same self from the same memory is an open question I'm testing, not a claim I'm making
- **Entropy as impulse** — a hardware TRNG as a source of non-deterministic timing, distinct from entropy as signal
- **Benchmark-driven development** — LOCOMO, Personal Continuity Benchmark, and reading source instead of READMEs

---

### 📫 Connect

- **Location:** Santiago, Chile 🇨🇱
- **Focus:** AI Memory Systems · Graph Retrieval · Mobile Development
- **Lab:** [seventhwalllab.com](https://seventhwalllab.com)
