# Precision and resource scaling of real-time flux distortion compensation for superconducting quantum control

| | |
|---|---|
| Authors | Qi Zhou, Zi-Hao Mei, Peng Duan, Peng Wang, Liang-Liang Guo, Hao-Ran Tao, Wei-Cheng Kong, Hui Yang, Guo-Ping Guo, Zhao-Yun Chen |
| Published | 2026-09-23 |
| Source | [arxiv:2609.27456](https://arxiv.org/abs/2609.27456) |
| DOI | [10.48550/arXiv.2609.27456](https://doi.org/10.48550/arXiv.2609.27456) |
| License | http://creativecommons.org/licenses/by-nc-sa/4.0/ |
| Categories | quant-ph, cs.AR |
| PDF SHA-256 | `9f089078a1c60f0bfff785cc45d66c5f9368913aeac0dbca300626044399b1d7` (of v1) |

## Abstract

Real-time waveform generation supports dynamic quantum circuits without pre-storing complete waveforms for every execution path. However, long-lived distortions in flux-control lines degrade gate fidelity, requiring compensation to account for the actual pulse history. A frequency-domain inversion and time-domain fitting method is proposed for resource-efficient real-time flux distortion compensation. The method fits the reconstructed compensation impulse response with a compact hybrid infinite impulse response (IIR) and finite impulse response (FIR) filter. Look-ahead parallelization enables this filter to process synthesized waveforms at 1.2GSa/s on a field-programmable gate array (FPGA). Two-qubit cross-entropy benchmarking shows that real-time IIR filtering achieves a median controlled-Z Pauli fidelity close to the software-reference value of 99.57%. Numerical analysis and FPGA synthesis indicate approximately logarithmic growth in hardware resource use with compensation timescale. Extending compensation from microsecond to hundred-microsecond timescales increases look-up table (LUT) and digital signal processing (DSP) resource use by only about 14% and 4%, respectively, while maintaining a relative arithmetic error below $10^{-4}$. This work provides a scalable hardware foundation for high-fidelity flux control in dynamic superconducting quantum circuits.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
