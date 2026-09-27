# Reconfigurable bus-based quantum router for modular superconducting processors

| | |
|---|---|
| Authors | Benzheng Yuan, chaojie Zhang, Yangyang Fei, Chuanbing Han, Haoran He, Huihui Sun, Bo Zhao, Fudong Liu, Weilong Wang, Zheng Shan |
| Published | 2026-09-24 |
| Source | [arxiv:2609.28881](https://arxiv.org/abs/2609.28881) |
| DOI | [10.48550/arXiv.2609.28881](https://doi.org/10.48550/arXiv.2609.28881) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `715e9e7f079bfbf22fa7d3d06c82e8be7c980341d0f055d0c30af5d92e30f9a8` (of v1) |

## Abstract

Scaling superconducting quantum processors requires interconnects that provide both non-local connectivity and parallel entangling operations. Nearest-neighbour couplings require distant interactions to be routed through SWAP networks, increasing the native two-qubit-gate count and potentially extending the circuit critical path. Here we introduce a bus-based reconfigurable quantum router for modular superconducting processors. Flux-tunable SQUID couplers selectively connect interface qubits to two shared buses, allowing destructive interference to suppress idle interactions while supporting two disjoint controlled-$Z$ (CZ) gates in parallel. Full-system Hamiltonian simulations yield parallel-gate errors at the level of $10^{-3}$, and open-system analysis identifies the coherence requirements for high-fidelity operation. We further assess the circuit-level consequences using hardware-aware compilation and resource-constrained scheduling. For 36-qubit quantum Fourier transform (QFT), QAOA-MaxCut and random-pairing circuits, the router reduces the median SWAP count by up to $34\%$ and the native CZ count by up to $20\%$ relative to a matched two-dimensional grid. End-to-end depth reduction is circuit dependent, reaching $20\%$ for QAOA-MaxCut but remaining negligible for the QFT despite its lower gate count. These results show that enhanced connectivity and schedulable parallelism provide distinct benefits, establishing the router as a compiler-visible hardware resource for modular superconducting quantum processors.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
