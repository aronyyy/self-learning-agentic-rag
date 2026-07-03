# Self-Learning Agentic RAG

This repository implements a **production-grade RAG system**, starting with a
strong Phase-1 retrieval core and evolving into an **agentic, self-improving RAG**.

## Phase 1 (Current)
- PDF-only ingestion
- Semantic chunking with metadata
- FAISS-based vector recall
- Metadata-aware reranking
- Retrieval logging (SQLite)

## Tech Stacks
- Python
- LangChain
- FAISS
- SQLite

## Roadmap
- Phase 2: Agentic planner–executor
- Phase 3: Multi-modal RAG
- Phase 4: Self-learning via feedback
