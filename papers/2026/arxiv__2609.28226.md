# Pinpointing Super-Quadratic Quantum Enumeration Speedups: Exact and Certified Evaluation of the Guessing-Moment Exponent under Product-Distribution Advice

| | |
|---|---|
| Authors | Carsten Schubert, Niklas Paskarbeit, Maximilian J. Kramer, Jean-Pierre Seifert, Marian Margraf |
| Published | 2026-09-23 |
| Source | [arxiv:2609.28226](https://arxiv.org/abs/2609.28226) |
| DOI | [10.48550/arXiv.2609.28226](https://doi.org/10.48550/arXiv.2609.28226) |
| License | http://creativecommons.org/licenses/by-nc-nd/4.0/ |
| Categories | cs.CR |
| PDF SHA-256 | `818cc30fde704bd38d201c750a9f12dd491ef5afa7d8f9ffe145227d6c43e777` (of v1) |

## Abstract

Grover's algorithm gives an optimal quadratic query advantage for black-box search. In cryptanalysis, however, the search often comes with additional probabilistic advice over the candidates, frequently of product form, e.g. from side-channel leakage on independent key coordinates. Classically, guessing in likelihood order is optimal in expectation. In the quantum setting, Montanaro showed how to achieve an optimal expected query complexity, beating plain Grover on every non-uniform advice distribution (up to a constant overhead factor). What has been missing so far is a finite-size method for evaluating the quantum-classical guessing-moment separation induced by a given advice distribution. We provide such a method for product-distribution advice, thereby sharpening the previous entropy-based estimate of Bashiri et al. We reduce the classical and quantum guessing moments to functionals of the one-dimensional surprisal distribution, obtained for product advice by convolving the per-coordinate surprisal laws. When the surprisals lie on a common arithmetic grid (the commensurate case), the logarithmic moments and hence the speedup exponent can be evaluated as finite sums without discretization error; exponential tilting makes this computation numerically stable. For general product advice, we discretize the surprisals onto a common grid and derive an a-posteriori bound on the resulting binning error. We apply the framework to cold-boot leakage on seeds and block-cipher keys, to template-attack posteriors, and to synthetic i.i.d. Bernoulli posteriors calibrated to residual ranks reported for Keccak side-channel attacks on ML-KEM and ML-DSA. The resulting exponents substantially exceed 2 in several skewed-advice settings, reaching up to 3.97 in these synthetic models, and include cases where the previous entropy-based bound did not establish an exponent above 2.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
