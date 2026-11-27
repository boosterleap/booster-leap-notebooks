# Booster LEAP notebooks

Jupyter notebooks that go with the Booster LEAP courses. Each notebook opens in Google Colab from the lesson page; it needs no GPU unless it says so.

- `computer-vision/notebook-augmentation-e2e.ipynb`: does data augmentation help, and when?
- `computer-vision/notebook-cnn-from-scratch-e2e.ipynb`: a CNN from scratch, end to end
- `diffusion-models/notebook-environment-and-first-generation.ipynb`: environment check, memory arithmetic and a first tiny diffusion model on your machine (CPU or Colab GPU)
- `diffusion-models/notebook-train-tiny-ddpm.ipynb`: train a tiny DDPM end to end on 8 x 8 digits and on photo crops, sample with DDIM and DDPM, and measure the result
- `diffusion-models/notebook-latent-inference-e2e.ipynb`: a latent text-to-image pipeline end to end: a photo autoencoder, then a toy tokenizer, text encoder, autoencoder, U-Net, scheduler and guidance on digits, with measurements and a scheduler comparison
- `diffusion-models/notebook-cfg-sweep.ipynb`: a guidance-scale sweep on digits: a class-conditional model trained on a CPU, fidelity, diversity and out-of-range values per scale, three seeds, label dropout, editing strength and inpainting
- `diffusion-models/notebook-lora-e2e.ipynb`: LoRA end to end on a digit diffusion model: a base trained on the digits 0 to 6, a LoRA written by hand, ranks, merge scale, forgetting and replay with three seeds, and a few-patch photo denoiser adapted with full update against LoRA
- `rag-advanced-engineering/capstone-enterprise-and-research-qa-notebook.ipynb`: Capstone: enterprise and research question answering: the real-library code of the lessons
- `rag-advanced-engineering/cost-latency-and-caching-notebook.ipynb`: Cost, latency and caching: the real-library code of the lessons
- `rag-advanced-engineering/debugging-rag-failures-notebook.ipynb`: Debugging RAG failures: the real-library code of the lessons
- `rag-advanced-engineering/evaluation-frameworks-ragas-notebook.ipynb`: Evaluation frameworks: RAGAS: the real-library code of the lessons
- `rag-advanced-engineering/hybrid-search-bm25-and-vector-notebook.ipynb`: Hybrid search: BM25 and vector: the real-library code of the lessons
- `rag-advanced-engineering/metadata-filtering-and-acl-patterns-notebook.ipynb`: Metadata filtering and access-control patterns: the real-library code of the lessons
- `rag-advanced-engineering/multi-document-reasoning-notebook.ipynb`: Multi-document reasoning: the real-library code of the lessons
- `rag-advanced-engineering/query-rewriting-and-expansion-notebook.ipynb`: Query rewriting and expansion: the real-library code of the lessons
- `rag-advanced-engineering/reranking-cross-encoders-notebook.ipynb`: Reranking with cross-encoders: the real-library code of the lessons
- `rag-advanced-engineering/retrieval-metrics-and-baselines-notebook.ipynb`: Retrieval metrics and baselines: the real-library code of the lessons
- `rag-production-and-agentic-systems/agentic-rag-with-langgraph.ipynb`: Agentic RAG with LangGraph and MCP
- `rag-production-and-agentic-systems/caching-with-real-libraries.ipynb`: Caching with real libraries
- `rag-production-and-agentic-systems/graph-rag-with-networkx.ipynb`: A small graph RAG with networkx
- `rag-production-and-agentic-systems/health-and-smoke-checks.ipynb`: Health, readiness and smoke checks
- `rag-production-and-agentic-systems/multimodal-pdf-extraction.ipynb`: What a PDF text extractor really gets
- `rag-production-and-agentic-systems/rag-api-skeleton.ipynb`: A RAG API skeleton, end to end
- `rag-production-and-agentic-systems/rag-streaming.ipynb`: A streaming RAG endpoint, end to end
- `rag-production-and-agentic-systems/streaming-ingest-with-sqlite.ipynb`: Capturing changes with triggers, and consuming them
