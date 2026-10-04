# 📜 The Story of FastFlowLM (FLM)

From a 2025 university research project to the NPU-first runtime for AMD Ryzen™ AI — now part of AMD.

---

## 🎓 2025 — A University Project

Modern AMD Ryzen™ AI laptops all shipped with a capable, power-efficient NPU. Almost nobody could run an LLM on it with good performance and long context length.

FastFlowLM started as an **NSF-funded university research project** aimed squarely at that gap. The bet: closing it required co-designing kernels around the NPU's dataflow architecture from the ground up — not porting an existing runtime onto it.

What began as federally funded lab work became **FastFlowLM, Inc.** in 2025, and the runtime was released publicly as open source that June.

### Founders

- **Tao Wei** — Professor of ECE, Clemson University; directs the NEXT Lab (domain-specific accelerators, reconfigurable computing, applied ML). Leads FLM kernel strategy.
- **Ken Qing Yang** — Distinguished Engineering Professor, University of Rhode Island. 30+ years in computer architecture; serial entrepreneur behind four deep-tech startups, including VeloBit (acquired by Western Digital) and DapuStor.
- **Zhenyu (Alfred) Xu** — Research Assistant Professor, Clemson University. Accelerator design and on-device AI inference, with hardware–software co-optimization across FPGA, CGRA, and AI accelerators.

## 🚀 2025–2026 — Building in the Open

First public commit landed June 16, 2025; v0.1.0 nine days later. The design principle was borrowed from tools developers already liked — "Think Ollama, but deeply optimized for NPUs." Install in seconds, `flm run <model>`, done.

FLM was MIT-licensed and open source from the start, built on IRON, the open-source NPU compiler technology developed and released by AMD's Research and Advanced Development (RAD) Group. That open foundation, plus close alignment with Lemonade (AMD's open-source inference initiative), drove adoption across developers and ISVs.

(See the project for a full timeline and references.)
