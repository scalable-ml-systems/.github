# Nancy Bethala-Frounjian
### AI Systems Engineer | Multi-Vendor Systems (CUDA & ROCm)

Building end-to-end AI systems—from GPU memory execution up to ontology-driven knowledge graphs for complex domain reasoning.

[![StackBytes](https://img.shields.io/badge/Writing-StackBytes-orange?style=flat-square&logo=beehiiv)](https://stackbytes.beehiiv.com/)
[![GitHub](https://img.shields.io/badge/Labs-nbethala-181717?style=flat-square&logo=github)](https://github.com/nbethala)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/your-profile)

---

## Systems Methodology: Full-Stack Integration

I approach AI engineering through a systems-thinking lens:

1. **Deterministic Domain Modeling (Ontology/Graph):** Structuring complex biomedical domain knowledge into typed entity-relationship graphs (Palantir-style object models) so LLM reasoning is grounded in deterministic truth, strict schema boundaries, and auditable lineage.
2. **High-Throughput Runtime Infrastructure:** Optimizing serving engines (vLLM, Triton) for low-latency batching, state machine enforcement, and KV-cache efficiency under heavy request concurrency.
3. **Hardware & Silicon Efficiency:** Profiling and tuning workloads across multi-vendor accelerator hardware (NVIDIA CUDA & AMD ROCm).

---

## Featured Repositories

| Repository | System Layer | Key Focus Area | Stack |
| :--- | :--- | :--- | :--- |
| **[`biomedical-ai-infra-lab`](https://github.com/scalable-ml-systems/biomedical-ai-infra-lab)** | Domain & Runtime | Ontology-grounded Graph RAG for biomedical reasoning, long-context window management, and schema-constrained inference execution. | Neo4j/NetworkX, vLLM, Python, Triton, Ray |
| **[`amd-rocm-platform-engineering`](https://github.com/scalable-ml-systems/amd-rocm-platform-engineering)** | Silicon & Accelerator | Cross-vendor GPU performance profiling, ROCm/HIP kernel optimization, memory bandwidth triage, and multi-GPU benchmarking. | ROCm, HIP, CUDA, C++, PyTorch, Docker |

---

## ⚡ Open-Source Contributions

* **[vLLM](https://github.com/vllm-project/vllm)** — **[PR #34978](https://github.com/vllm-project/vllm/pull/34978)**: Resolved high-concurrency state machine divergence during structured output parsing under heavy load.

---

## 📝 Technical Write-ups

* **[StackBytes](https://stackbytes.beehiiv.com/)**: Technical deep-dives on ontology modeling for enterprise RAG, vLLM state machines, and bare-metal GPU performance triage.
