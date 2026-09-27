# Soft decoding for quantum LDPC codes with experimental validation

| | |
|---|---|
| Authors | Arda Aydin, Edwin Tham, Nicolas Delfosse, Min Ye |
| Published | 2026-09-22 |
| Source | [arxiv:2609.26958](https://arxiv.org/abs/2609.26958) |
| DOI | [10.48550/arXiv.2609.26958](https://doi.org/10.48550/arXiv.2609.26958) |
| License | http://creativecommons.org/licenses/by/4.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `fc28f632584e011ab624cfd1ae17cf73cb1219c21e97dc21b6ea8c6c11318b45` (of v1) |

## Abstract

The decoder is a critical component of a fault-tolerant quantum computer, computing corrections based on parity-check measurements performed throughout the computation. A soft decoder supplements its output with a confidence score which, when used alongside post-selection, can substantially improve logical performance. We introduce a soft beam search decoder for quantum low-density parity-check codes that uses internal decoder data as a confidence metric, removing the need for extra computation. We perform circuit-level simulations of five quantum LDPC codes relevant for superconducting and trapped ion architectures equipped with our global soft decoder and we obtain up to $580\times$ logical-error suppression at a physical error rate of $10^{-3}$ while rejecting only $0.1\%$ of shots. Then, we simulate an error detected measurement, which is a core logical operation of the walking cat architecture, using a streaming version of soft beam decoder and we achieve up to $210\times$ error suppression while increasing the rejection probability by only $0.5$ percentage points. Finally, we revisit recent quantum LDPC code memory experiments on trapped ions, demonstrating that our soft decoder doubles the logical qubit lifetimes at the price of a mean rejection rate of $2.6\%$--$5.6\%$ per syndrome round, bringing all five codes into the beyond-breakeven regime.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
