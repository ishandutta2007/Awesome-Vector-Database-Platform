# Awesome-Vector-Database-Platform

# Top Vector Database Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Vector Similarity Search, Embeddings Storage, RAG, Semantic Search & AI Retrieval Infrastructure*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vector Databases**. These tools store, index, and query high-dimensional vector embeddings for semantic search, retrieval-augmented generation (RAG), recommendation systems, and other AI applications requiring fast approximate nearest-neighbor search.

**Examples** include Pinecone, Weaviate, Qdrant, Milvus, Chroma, LanceDB, Vespa, Redis Vector, Elastic Vector Search, Astra DB, Zilliz Cloud, Astra DB Vector, and pgvector Cloud (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for vector search engines, embedding stores, and related libraries — ideal for AI engineers, RAG developers, and teams seeking high-performance, self-hosted, or fully controllable vector infrastructure without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pinecone](https://www.pinecone.io/)**  
  Fully managed, serverless vector database optimized for low-latency similarity search, hybrid retrieval, and production RAG workloads with minimal operational overhead.

- **[Weaviate Cloud](https://weaviate.io/)**  
  Managed cloud offering of the open-source Weaviate vector database, supporting hybrid search, GraphQL, and modular embedding pipelines.

- **[Qdrant Cloud](https://qdrant.tech/)**  
  Managed service for the high-performance Qdrant vector database, emphasizing fast filtering, low latency, and easy scaling.

- **[Zilliz Cloud (Milvus)](https://zilliz.com/)**  
  Fully managed cloud service for Milvus, designed for billion-scale vector search with distributed architecture and enterprise features.

- **[Chroma Cloud](https://www.trychroma.com/)**  
  Hosted version of the popular open-source Chroma embedding database, geared toward rapid prototyping and production RAG applications.

- **[LanceDB Cloud](https://lancedb.com/)**  
  Managed offering of the LanceDB multimodal vector database built on the Lance columnar format.

- **[Vespa Cloud](https://cloud.vespa.ai/)**  
  Managed platform for Vespa, a large-scale search and recommendation engine with native vector and hybrid ranking capabilities.

- **[Redis Cloud (Vector Search)](https://redis.io/)**  
  Managed Redis with vector similarity search (RediSearch / VSS) for ultra-low-latency retrieval combined with caching and operational data.

- **[Elastic Cloud (Vector Search)](https://www.elastic.co/)**  
  Managed Elasticsearch/OpenSearch with dense vector (kNN) support for hybrid full-text + semantic search.

- **[Astra DB / Astra DB Vector (DataStax)](https://www.datastax.com/products/datastax-astra)**  
  Serverless database built on Apache Cassandra with native vector search capabilities for generative AI workloads.

- **[pgvector Cloud offerings](https://github.com/pgvector/pgvector)**  
  Managed PostgreSQL services (from various cloud providers) that include the pgvector extension for vector similarity search inside Postgres.

## Open-Source GitHub Projects

- **[Milvus](https://github.com/milvus-io/milvus)**  
  Leading open-source, cloud-native vector database designed for billion-scale similarity search, with distributed architecture, multiple index types, and strong ecosystem support (LF AI & Data project).

- **[Qdrant](https://github.com/qdrant/qdrant)**  
  High-performance open-source vector database written in Rust, known for excellent filtering, low latency, and production-ready features for RAG and semantic search.

- **[Weaviate](https://github.com/weaviate/weaviate)**  
  Open-source vector database with native hybrid search (BM25 + vector), GraphQL API, modular vectorization, and flexible deployment options.

- **[Chroma](https://github.com/chroma-core/chroma)**  
  Popular open-source embedding database designed for simplicity, developer experience, and rapid development of LLM/RAG applications.

- **[LanceDB](https://github.com/lancedb/lancedb)**  
  Open-source, developer-friendly vector database built on the Lance columnar format, optimized for multimodal data and large-scale analytics.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open-source big data serving engine with powerful vector search, hybrid ranking, and real-time computation capabilities at massive scale.

- **[pgvector](https://github.com/pgvector/pgvector)**  
  Open-source PostgreSQL extension that adds vector similarity search (HNSW, IVFFlat) directly inside Postgres, ideal for teams already using relational databases.

- **[Faiss (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)**  
  Foundational open-source library for efficient similarity search and clustering of dense vectors, widely used as a building block in other systems.

- **[Vald](https://github.com/vdaas/vald)**  
  Kubernetes-native distributed vector search engine focused on high scalability and cloud-native operations.

- **[Marqo](https://github.com/marqo-ai/marqo)**  
  Open-source tensor search engine that simplifies multimodal and hybrid search with built-in vectorization.

- **[Txtai](https://github.com/neuml/txtai)**  
  Open-source embeddings database and semantic search framework for building AI-powered applications.

- **[Annoy / Hnswlib / other ANN libraries](https://github.com/spotify/annoy)**  
  Lightweight open-source approximate nearest neighbor libraries frequently used for custom vector search implementations.

### Additional Strong Open-Source Options

- **Database extensions**: pgvector, pgvectorscale, Redis Stack / RediSearch, Elasticsearch/OpenSearch kNN, ClickHouse vector functions, DuckDB vector support.
- **Embedded & lightweight**: Chroma, LanceDB, and similar tools ideal for local development and single-node deployments.
- **Distributed & cloud-native**: Milvus, Qdrant, Weaviate, Vald, and Vespa for production-scale workloads.
- **Libraries**: Faiss, Hnswlib, ScaNN, and other high-performance ANN implementations.
- Many research and specialized **vector indexing** projects continuing to advance the state of the art on GitHub.

**Frameworks for building custom systems**: Combine **Milvus, Qdrant, or Weaviate** as the core vector store, **pgvector** when staying inside PostgreSQL, embedding models (open-source or API), and orchestration frameworks (LangChain, LlamaIndex, Haystack) to create complete open-source RAG and semantic search pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vector databases often store sensitive embeddings derived from proprietary or personal data; proper access controls, encryption, and compliance measures are essential.
- Self-hosted open-source solutions require attention to indexing performance, memory/disk management, and backup strategies at scale.

---

**Made for AI engineers, RAG developers, search teams, and infrastructure builders.**  
Let's make vector search more open, performant, and accessible.
