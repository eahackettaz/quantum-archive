# A Syndrome-Extraction Framework for Distributed Lattice Surgery on Arbitrary Rotated Surface-Code Layouts

| | |
|---|---|
| Authors | Pritesh Thakur, Daniel Dilley, Zain Saleem |
| Published | 2026-09-22 |
| Source | [arxiv:2609.26736](https://arxiv.org/abs/2609.26736) |
| DOI | [10.48550/arXiv.2609.26736](https://doi.org/10.48550/arXiv.2609.26736) |
| License | http://creativecommons.org/licenses/by/4.0/ |
| Categories | quant-ph |
| PDF SHA-256 | `049a01c4fe20f37c32b361587c7fc46bfbfc0fcb59682475217f34a394abf6a5` (of v1) |

## Abstract

Modular quantum computing is a leading candidate for scalable fault tolerant quantum computation. Performing lattice surgery using surface code patches in different modules requires the use of inter-module gates that are noisier than the local gates. Furthermore, the merged layouts during lattice surgery expose multiple directions in which hook errors can propagate to reduce the fault distance. Existing hook-avoiding schedules either increase the syndrome extraction circuit depth, or let link faults propagate into the bulk. We introduce a seam construction that allows splitting arbitrary merged rotated surface code layout into smaller patches with uniform boundaries that could keep their own hook-avoiding N/Z shaped schedule. At the seam we split weight-4 stabilizers into pairs of weight-2 stabilizers that are mediated through a Bell pair and measured within a CNOT depth of 4. We also employ the use of three-qubit $\texttt{CXX}$ gates for parity measurements at the seam to maintain the minimum CNOT depth. Through this seam construction, we confine the elevated link error at the seam, protecting the bulk from higher error rate. We also give a custom detector annotator for such seams that can find the detector space, annotate detectors in the Stim circuits, and ensure that they are suitable to use by matching decoders. We implement our construction for the logical Pauli-$XX$ measurement lattice surgery and a cross-shaped spatial junction and sweep the link error rate from $10$ times to $100$ times a fixed bulk error rate, and show that our construction gives the lowest and most stable logical error rate than the other frameworks compared here.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
