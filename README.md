# Tanmay Dixit

Applied AI / ML systems engineer focused on reliable retrieval, agents, evaluation, model serving, and realtime voice AI.

Based in Miami, Florida. I build systems that expose evidence, preserve provenance, respect authorization boundaries, and fail in ways an engineering team can diagnose.

## Flagship: AtlasRAG v0.2.0

[AtlasRAG](https://github.com/tandixit95/AtlasRAG) is a permission-aware retrieval core with deterministic source identity, chunk provenance, BM25, exact dense retrieval, Reciprocal Rank Fusion, and fail-closed tenant/group filtering.

Verified public evidence:

- 63 tests, GitHub Actions on Python 3.11-3.13, and clean wheel/source-distribution install gates.
- SciFact Recall@10 across 300 judged queries: BM25 `0.7816`, exact dense `0.7833`, hybrid RRF `0.8212`.
- Exact A/B reproduction of every reported quality metric and raw top-10 ranking.
- Nine synthetic authorization/provenance checks with zero unauthorized returns.
- Checksummed release assets, machine-readable results, methodology, limitations, and claim boundaries.

[Release](https://github.com/tandixit95/AtlasRAG/releases/tag/v0.2.0) | [Results](https://github.com/tandixit95/AtlasRAG/blob/main/benchmarks/RESULTS.md) | [Methodology](https://github.com/tandixit95/AtlasRAG/blob/main/benchmarks/METHODOLOGY.md) | [Evidence package](https://github.com/tandixit95/AtlasRAG/tree/main/benchmarks)

The benchmark evidence is local and reproducible; it is not a production SLO, peer-review claim, or claim of external adoption.

## Selected open-source work

- [vLLM #50462](https://github.com/vllm-project/vllm/pull/50462): align KV-cache capacity and concurrency observability with resolved scheduler state.
- [DSPy #10107](https://github.com/stanfordnlp/dspy/pull/10107): support population-level metrics in MIPROv2 evaluation while preserving per-example output semantics.
- [Hugging Face TRL #6587](https://github.com/huggingface/trl/pull/6587): support bracketed IPv6 communicator hosts.
- [LlamaIndex #22509](https://github.com/run-llama/llama_index/pull/22509): serialize fact-memory tool history correctly.
- [Ragas #2900](https://github.com/vibrantlabsai/ragas/pull/2900): preserve repeated prompt invocations in traces.
- [Hermes carrier #69298](https://github.com/NousResearch/hermes-agent/pull/69298): merged upstream carrier explicitly credits my original active-turn notification-scoping fix in [#63450](https://github.com/NousResearch/hermes-agent/pull/63450).

Pull-request states can change; the linked upstream records are the source of truth.

## Systems I build

- Retrieval and grounding: ingestion, chunking, embeddings, BM25, dense retrieval, RRF, reranking, citations, provenance, and ACL-aware retrieval.
- Agent reliability: structured state, tool routing, verification, retries, human approval, permission checks, and traceable outcomes.
- Evaluation: Recall@K, MRR, nDCG, groundedness, citation quality, task success, latency, cost, and release gates.
- Product integration: Python, PyTorch, FastAPI, C#/.NET, SQL, Azure OpenAI/OpenAI APIs, streaming interfaces, and realtime voice systems.

## Connect

- [LinkedIn](https://www.linkedin.com/in/dixittanmay)
- Email: `dixit.tanmay1995@gmail.com`
