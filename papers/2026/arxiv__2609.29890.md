# Syndrome measurements enable deterministic fault-tolerant $T$ gates

| | |
|---|---|
| Authors | Kishor Bharti, Tobias Haug, Andrew Tanggara |
| Published | 2026-09-24 |
| Source | [arxiv:2609.29890](https://arxiv.org/abs/2609.29890) |
| DOI | [10.48550/arXiv.2609.29890](https://doi.org/10.48550/arXiv.2609.29890) |
| License | http://creativecommons.org/licenses/by/4.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `b2f117159ee6af6bbaa5175754e008bfb93ea814755e8f0448ab4d039ccea155` (of v1) |

## Abstract

Non-Clifford gates are essential for universal quantum computation, yet implementing them fault-tolerantly remains a central challenge for stabilizer codes. Here, we show how a syndrome degree of freedom can mediate a logical non-Clifford gate. Releasing one stabilizer check makes an additional logical qubit available within the encoded data block. Two Pauli rotations, followed by syndrome measurement and Clifford feed-forward, then implement a deterministic logical $T$ gate on every stabilizer code of distance at least two, in a suitable logical basis. During the ideal rotations, the state remains in an intermediate stabilizer code whose distance we determine exactly. For pure codes with a balanced factorization, this distance grows with the original code distance, whereas the maximum weight of the stabilizer generators bounds the intermediate distance from above. We realize the mechanism in two circuits that tolerate a single fault under local stochastic circuit noise: a fixed 22-qubit construction admitting recursive error suppression and a direct Golay-code gate protected by measuring a stabilizer check transported through the non-Clifford rotation, which can recover the unknown encoded state even after rejection. Serial implementations with ancilla reuse, reset, and flexible two-qubit connectivity require at most 33 and 32 physical qubits, respectively. These results establish a general mechanism for logical non-Clifford gates and demonstrate how syndrome measurements and recovery can protect the intermediate evolution of encoded information.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
