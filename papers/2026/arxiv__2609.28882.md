# Efficient Record-and-Replay Arithmetic for Quantum Elliptic-Curve Point Addition

| | |
|---|---|
| Authors | Jieyi Long, Theodore Pender, Zhao Huang, Manuel B. Santos, Samrendra Kumar Singh, Bartosz Naskręcki, BitWonka, Pierre-Luc Dallaire-Demers, Francesco Giannicola, Ruben M. L. Paschoarelli, Oli Freuler, Jackie Chia-Hsun Lee, Vasily Gnuchev, Gopi Kannappan, John Boyer, Xavier Butler, Akash Balasubramani, Jordan Newman, Bereket Dereje, Alexander Hertlein, Robert Kodra, Lucas Levy, Shaan Patel, JT Rose, Matt Zweil, Okechukwu Wisdom, Tarek El-Eter, Edison Lee, Michael Dong, Alan Li, Anto Joseph, Duy Nguyen, Gajesh Naik, Gautham Anant, Soubhik Deb, Justin Drake |
| Published | 2026-09-24 |
| Source | [arxiv:2609.28882](https://arxiv.org/abs/2609.28882) |
| DOI | [10.48550/arXiv.2609.28882](https://doi.org/10.48550/arXiv.2609.28882) |
| License | http://creativecommons.org/licenses/by/4.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `a82133bcf4d42fe8bb8cd0ddfd223c29a820bbe685eb2e318ce073f58e04465a` (of v1) |

## Abstract

We study reversible secp256k1 point-addition circuits developed through ECDSA.Fail for Shor's elliptic-curve discrete-logarithm algorithm. Two complementary constructions improve record-and-replay GCD arithmetic: Jump-2 groups binary-GCD steps and compresses their decisions using base-5 encoding, while ping-pong uses fixed register alternation and one-bit decisions to avoid full-width comparisons and data-dependent swaps. Fused replay combines doubling and signed addition into one modular correction. Both constructions support quantum-addressed window selection with measurement-based lookup cleanup. We compare three circuits on 100,000 fresh inputs across nine lookup-table configurations. A separately tested repair uses 1,419 qubits and 1.356 million mean executed Toffolis, with no detected failures on another 100,000 inputs. Structured supported-input counterexamples remain, so these tests do not establish all-input correctness. We also provide conditional coherent-error analysis and reversible safegcd comparisons. Under the stated window allowance, repaired-circuit resources lie below Google's low-gate caps and Schrottenloher's low-gate estimates, but differing accounting and correctness evidence preclude formal dominance. The results concern individual window-selected additions, not complete Shor computations.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
