# Design Principles for Ultra-High-Rate Quantum Codes

| | |
|---|---|
| Authors | Jong Yeon Lee, Koki Okada, Nishad Maskara, Kenta Kasai, Hengyun Zhou |
| Published | 2026-09-24 |
| Source | [arxiv:2609.30069](https://arxiv.org/abs/2609.30069) |
| DOI | [10.48550/arXiv.2609.30069](https://doi.org/10.48550/arXiv.2609.30069) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `071e9291dcf691ea12dc78870e3afad6a91ccac38590b37fbe6937d867309c1c` (of v1) |

## Abstract

Reducing the qubit overhead of quantum error correction is a central challenge for scalable fault-tolerant quantum computing. Recent ultra-high-rate quantum codes offer a promising route toward this goal, with some constructions requiring as few as two physical data qubits per logical qubit. However, systematic principles for navigating the tradeoffs among encoding rate, distance, check weight, and blocklength remain lacking. Here, we develop and analyze principles for exploring this design space, and use them to design compact code constructions with improved performance. We develop code templates based on a pair-partition construction and a halving transformation that further reduces blocklength. Motivated by ensemble analysis of the degree distributions, we identify column weight as a key design parameter: increasing the column weight enables larger distances at compact blocklengths, at the cost of heavier checks. We find that at physical error rates of 0.1%, the benefits of increased distance often outweigh the penalty associated with heavier checks. Applying this framework, we identify numerous compact codes with favorable parameters, including [[90,21,11]], [[140,31,15]], and [[200,43,20]] non-CSS codes with check weight 10. Moreover, we develop symmetry-informed strategies for identifying low-weight logical bases. These results provide systematic strategies for designing ultra-high-rate quantum codes and navigating their Pareto frontier.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
