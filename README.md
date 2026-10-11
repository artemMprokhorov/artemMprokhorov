Hi there, I'm Artem! 🚀
Android Engineer @ Scotiabank | AI Memory Architect & Researcher
Persistent memory architectures for AI agents — from spreading activation to shipping binaries.

🧠 Current Work: Seventh Wall Lab — We give agents memory, the kind experience grows out of.
An Airy Spirit — your agent's own memory. Experience that outlives the session.

Every session, an AI agent starts from zero. An Airy Spirit gives it a memory of its own, on your machine: not a store of documents about your project, but a record of how the agent itself works — where it tends to be wrong, which corrections it was given and why, what it decided and what came of it.

One program, written in Rust from the storage engine up, running as an MCP server. No cloud, no LLM, no interpreter, no telemetry. Public since October 2026 — signed and notarised for macOS, packages for Linux, Docker images, Homebrew and npm.

Layer	What it does
Recall	By connection, not by keyword: a query starts from the direct matches and spreads along edges that carry meaning — similarity, contradiction, supersession, part of a whole
Consolidation	Sleep, light and deep: new material settles into connections, memories group into topics; a deep sleep is all or nothing
Forgetting	What goes unused dims — never deleted — and rises again when it is needed; a place in long-term memory is earned
Time	Two dates on every memory: when it happened and when it was written down
Your data	One folder on your disk, optional ChaCha20-Poly1305 encryption, a per-install recovery phrase, one encrypted file to move the whole memory
npx anairyspirit setup
Or a macOS disk image, Homebrew, .deb / .rpm, Docker — install. Works with Claude Code, Claude Desktop, Gemini CLI, Antigravity, Codex, Cursor, Grok and Kiro — and any other MCP client.

The thesis: Model = substrate, personality = memory. The graph holds the language model as an external library, not the other way around. Structure computes on its own; the model attaches at the language boundary. Our aim — a goal, not a claim — is that experience, kept long enough, becomes a self.

Why that matters: when consolidation, importance, and concept extraction are implemented as model calls, they stop the moment the key is removed — and what remains is an index of logs. An Airy Spirit is built so recall, consolidation, and forgetting run with no language model present at all.

Lineage
Project	Description
HippoGraph Pro	Self-hosted associative memory. BGE-M3 + BM25 + cross-encoder reranking + lateral inhibition. LOCOMO: 69.4% Recall@5, zero LLM API cost.
HippoGraph	Python release. Spreading activation search, entity graph, MCP integration.
Neural Memory Graph	GraphRAG with associative memory and weight-based decay.
Semantic Memory MCP	Lightweight MCP server for persistent LLM memory. Where this all started.
🔬 Other Projects
Project	Description
Cinemy	Agentic coding benchmark — a full Android app built with zero manual code. Server-Driven UI + on-device ML.
💼 Professional
Senior Android Engineer @ Scotiabank Chile (Fabrica Digital) Core banking features, MVI architecture, Jetpack Compose at scale. 20+ years in IT.

🛠 Tech Stack
Area	Technologies
AI / Memory	Rust, MCP, ONNX Runtime, BGE-M3, cross-encoder reranking, BM25, GLiNER, spreading activation, GraphRAG
Security / Release	ChaCha20-Poly1305, GPG-signed manifests, cosign, Apple Developer ID + notarisation, npm provenance
Mobile	Kotlin, Jetpack Compose, Clean Architecture
Infrastructure	Docker, self-hosted Forgejo CI, Python, FastAPI, SQLite, NetworkX
🔭 Currently Exploring
Predictive memory — a JEPA-style predictor over the graph's node space: prospection and pattern completion in latent space, with prediction error replacing manually assigned importance
AI identity continuity — how much of an agent survives a substrate swap. Entry-point swaps preserve behaviour; whether a different base model reconstructs the same self from the same memory is an open question I'm testing, not a claim I'm making
Entropy as impulse — a hardware TRNG as a source of non-deterministic timing, distinct from entropy as signal
Benchmark-driven development — LOCOMO, LongMemEval, Personal Continuity Benchmark, and reading source instead of READMEs
📫 Connect
Location: Santiago, Chile 🇨🇱
Focus: AI Memory Systems · Graph Retrieval · Mobile Development
Lab: seventhwalllab.com · Product: anairyspirit.com
