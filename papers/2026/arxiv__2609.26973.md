# Near-optimal high-rate surgery from linear PCPPs

| | |
|---|---|
| Authors | Alexander Cowtan, Benjamin Ide |
| Published | 2026-09-22 |
| Source | [arxiv:2609.26973](https://arxiv.org/abs/2609.26973) |
| DOI | [10.48550/arXiv.2609.26973](https://doi.org/10.48550/arXiv.2609.26973) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `70a42563784a4c49fcdb4fe2588e92104e8e9217dec78e80209a1138cec3dff6` (of v1) |

## Abstract

A central problem for surgery with quantum Low-Density Parity Check (LDPC) codes is the design of auxiliary systems which measure large sets of logical operators in parallel, while preserving sparsity and fault distance. We introduce a very general method for designing surgery gadgets which are 'high rate', meaning that the number of operators measured in parallel is large in comparison to the size of the auxiliary system. Given an arbitrary initial $[[ n, k, d ]]$ quantum LDPC Calderbank-Shor-Steane (CSS) code, and an arbitrary subcode of size $μ\leq n$ that contains $t \leq k$ logical qubits, the method produces a sparse high-rate surgery gadget with size $μ(\logμ)^{O(\log\log μ)}=μ^{1+o(1)}$ which measures all $t$ logicals in the subcode. The space overhead is asymptotically optimal up to subpolynomial factors, as the lower bound is $Ω(μ)$. This gadget is produced in time polynomial in $μ$. When logical measurement is performed using these surgery gadgets, the phenomenological fault distance is at least $d$ when performed for $d$ rounds. Our main result comes from relating surgery gadgets with relative cosystolic expansion to linear Probabilistically Checkable Proofs of Proximity (PCPPs), which allow a randomised verifier to probabilistically verify the input to a linear circuit, using only oracle access to the input and a claimed proof.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
