# ResearchLens

**A Trustworthy Academic Research Assistant Powered by Hybrid Information Retrieval and RAG.**

ResearchLens is an AI-powered academic research assistant designed to help users
discover, retrieve, understand, and verify information from scientific literature
in Computer Science, Artificial Intelligence, and Information Technology.

The system combines traditional Information Retrieval methods, semantic search,
Retrieval-Augmented Generation (RAG), and claim-level verification to provide
evidence-grounded answers with traceable academic citations.

## Key Features

- Academic paper collection and processing.
- Boolean Retrieval, TF-IDF, and BM25.
- Dense Semantic Retrieval.
- Hybrid Retrieval with Reciprocal Rank Fusion.
- Cross-Encoder Reranking.
- Retrieval-Augmented Generation.
- Evidence-grounded citations.
- Claim-level verification inspired by Truth Reader.
- Retrieval and RAG evaluation.

## System Architecture

```text
Academic Papers
      |
      v
Data Ingestion & Processing
      |
      v
Information Retrieval
  |       |       |
 BM25   Dense   Hybrid
      |
      v
    Reranking
      |
      v
  RAG Generation
      |
      v
 Truth Verification
      |
      v
 Evidence-Grounded Answer