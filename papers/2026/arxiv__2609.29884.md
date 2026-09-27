# Efficient Synthesis of Multi-Controlled Toffoli Gates with Ternary Clifford$+P_9$ Gates

| | |
|---|---|
| Authors | Amit Saha, Francesco Arzani |
| Published | 2026-09-24 |
| Source | [arxiv:2609.29884](https://arxiv.org/abs/2609.29884) |
| DOI | [10.48550/arXiv.2609.29884](https://doi.org/10.48550/arXiv.2609.29884) |
| License | http://creativecommons.org/licenses/by/4.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `8857c2b4441c118b75ea02eae075d5dbf09d935b0bd21cc6fa6352224c85a87c` (of v1) |

## Abstract

Temporary occupation of qutrit levels can reduce the width and depth required for binary circuit logic in quantum computing. We introduce an efficient intermediate-qutrit decomposition of multi-controlled Toffoli gates with binary-subspace inputs and outputs. For balanced control widths $n=2^h-1$, the proposed decomposition is evaluated hierarchically through a tree, allowing independent subtree computations to proceed in parallel and reducing the depth from linear to logarithmic. The balanced low-depth construction requires $6n+3$ logical $P_9$ injections and $\frac{n-3}{4}$ clean ancillary qutrits. It matches the direct $P_9$ count of a recursively extended Clifford+$P_9$ baseline derived from the state-of-the-art work while using asymptotically one-quarter as many clean ancillas and replacing linear depth with logarithmic depth. For arbitrary control widths, a sequential extension preserves the $6n+3$ $P_9$ count but has depth $O(\log m+n-m)$ for a balanced core $m=2^h-1\leq n$, which is linear in the worst case over $n$. By reducing the resource overhead of a widely used reversible primitive, the proposed decomposition provides a practical building block for the design and compilation of more resource-efficient quantum algorithms in the fault-tolerant regime.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
