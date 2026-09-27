# Error Suppression in Distributed Quantum Computing with Heterogeneous-Distance Lattice Surgery

| | |
|---|---|
| Authors | Daniel Dilley, Anastashia Jebraeilli, Rayat Roy, Shobhit Gupta, Alvin Gonzales, Zain Saleem |
| Published | 2026-09-22 |
| Source | [arxiv:2609.26784](https://arxiv.org/abs/2609.26784) |
| DOI | [10.48550/arXiv.2609.26784](https://doi.org/10.48550/arXiv.2609.26784) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `d55199399f46a371383b44ef2ef2436db365dc193f598459034e0b2c12d82864` (of v1) |

## Abstract

Distributed quantum computing requires fault-tolerant operations across inter-QPU links that can be substantially noisier than local gates. Uniformly increasing code distance provides additional protection but also enlarges data patches used for local storage and computation. Here, we introduce distributed heterogeneous-distance lattice surgery using an eight-data-patch ancilla-mediated (8-DAM) architecture, which will be useful for near-term quantum devices with less qubit overhead. In this architecture, the central ancilla spanning the inter-QPU boundary is enlarged while the data patches retain distance $d$. The protocol uses traveling stabilizers to suppress hook errors during merge and split operations between these unequal-distance patches. Circuit-level simulations of rotated surface codes at fixed local depolarizing noise show that logical-readout error rates depend only weakly on link noise. The resulting advantage over conventional lattice surgery grows as link errors increase. Comparisons with uniform distance implementations demonstrate comparable logical error suppression with reduced physical-qubit overhead. We also demonstrate how 8-DAM layouts support two simultaneous distributed logical CNOT operations between four logical data qubits using a single enlarged ancilla. At higher link noise, this construction yields lower logical error rates and more stability than two independent distributed logical CNOTs. These results support selective ancilla enlargement as a resource-efficient approach to fault-tolerant distributed quantum computing.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
