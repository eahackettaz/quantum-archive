# MagiCFirm: A Runtime for Magic-State Cultivation with Algorithm-Hardware Co-Design

| | |
|---|---|
| Authors | Jubo Xu, Abbas B. Ziad, Prakash Murali, Hongxiang Fan |
| Published | 2026-09-24 |
| Source | [arxiv:2609.29267](https://arxiv.org/abs/2609.29267) |
| DOI | [10.48550/arXiv.2609.29267](https://doi.org/10.48550/arXiv.2609.29267) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph, cs.AR, cs.DC |
| PDF SHA-256 | `873708d2d3e4fe5a1b4ac78f8a60031fea22f06cd0b4bf91bd37f2cfbb63d96b` (of v1) |

## Abstract

Magic-state cultivation offers a promising alternative for lowering the cost of non-Clifford operations in fault-tolerant quantum computing (FTQC). However, realizing cultivation in practice exposes two challenges: (i) the lack of an open-source classical runtime layer between logical software and physical control, and (ii) the latency constraints on protocol-specific decisions that determine magic-state readiness. To address these challenges, we adopt an algorithm--hardware co-design approach. At the algorithm level, we develop a two-stage early-escape scheme that identifies an informative subset of detectors offline, constructs a compact decoding problem, and performs partial decoding in parallel with complete decoding at runtime, allowing high-confidence attempts to advance before full decoding completes. At the hardware level, we present MagiCFirm, a configurable runtime that combines offline-compiled microprograms with dedicated datapaths for detector construction, event processing, and protocol control, enabling end-to-end execution of magic-state cultivation. Across evaluated configurations, MagiCFirm reduces wall-clock magic-state preparation time by up to 39.3% at matched logical error rate. For a representative magic-state-bound workload, this translates to an estimated 11% reduction in overall application runtime.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
