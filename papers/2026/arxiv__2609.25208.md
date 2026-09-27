# Adaptive thresholding for scalable measurement-based qubit reset

| | |
|---|---|
| Authors | Qian Cao, Unnati Akhouri, Samuel Vizvary, Nissim Ofek, Wei Dai, Kater W. Murch |
| Published | 2026-09-21 |
| Source | [arxiv:2609.25208](https://arxiv.org/abs/2609.25208) |
| DOI | [10.48550/arXiv.2609.25208](https://doi.org/10.48550/arXiv.2609.25208) |
| License | http://arxiv.org/licenses/nonexclusive-distrib/1.0/ |
| Categories | quant-ph, cond-mat.stat-mech |
| PDF SHA-256 | `6c77e889cfd354098a08b7c54ba06406ff42fcbf4481d60a63d4be3e40e5da11` (of v1) |

## Abstract

Fast, high-fidelity qubit initialization is a key primitive for scalable quantum information processing, but conventional reset protocols either require long relaxation times or discard information contained in continuous measurement records. We demonstrate an adaptive measurement-based reset protocol for superconducting qubits that uses Bayesian inference to update the qubit-state estimate after each readout and dynamically adjust the feedback threshold. Unlike fixed-threshold or repeat-until-success (RUS) protocols, the method utilizes the full analog measurement history, enabling the reset decision to become progressively more conservative as confidence in ground-state preparation increases. Implemented with real-time FPGA-based feedback on a dispersively readout transmon qubit, the protocol achieves a ground-state initialization fidelity of $99.44\pm0.04\%$ after a small number of reset rounds. We further compare adaptive reset with RUS strategies in multi-qubit experiments and show that adaptive thresholding provides deterministic reset duration while maintaining a five-qubit simultaneous-reset fidelity of $98.78 \pm 0.19\%$. These results establish Bayesian adaptive thresholding as a practical and scalable route to fast qubit reset in superconducting quantum processors.

---

This is an index entry, not a copy of the paper. Follow the source link for the paper itself. The SHA-256 identifies the exact PDF that was read when this entry was made, so anyone holding the same file can verify it.
