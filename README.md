# Recoverability Boundary — Minimal Dynamical Model

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19069266.svg)](https://doi.org/10.5281/zenodo.19069266)

This repository contains code and simulations supporting the paper:

**A recoverability boundary in a minimal rate-limited dynamical system**  
Jaime Ojeda (2026)

---

## Overview

We study a minimal recovery-limited dynamical system under transient forcing.

The system is designed to test whether failure depends only on total input (AUC), or also on the **rate of application (forcing timescale)**.

Results suggest that system behavior may separate into recoverable and non-recoverable regimes, defined by a boundary in the joint space of load and timescale.

---

## Model

The system follows a minimal recovery–damage dynamic:

dv/dt = (1 - v)/τ_r − E₀·u(t) + ξ(t)

Where:

- `v` = system state (normalized)
- `tau_r` = recovery timescale
- `u(t)` = transient forcing (fixed AUC, variable duration)
- `E0` = coupling strength

The forcing is implemented as a pulse with constant area (AUC) and varying rise time.

---

## Key findings

- A **recoverability boundary** emerges in (AUC, timescale) space  
- Minimum state reached depends primarily on total input (AUC)  
- Recoverability depends jointly on load and forcing timescale  
- Recovery time appears primarily controlled by forcing duration  
- Prior subcritical exposure can shift the system into a non-recoverable regime (history dependence)

---

## Repository structure

- `recoverability_boundary_model.ipynb` — main simulation notebook  
- `figures/` — figures used in the manuscript  
- `paper/` — manuscript PDF  

---

## Reproducibility

All figures in the manuscript can be reproduced directly from the notebook.

---
## Interpretation

This is a minimal model intended to isolate a structural hypothesis:

> Failure may arise from a mismatch between input rate and recovery capacity, rather than absolute load alone.

These results are consistent with a rate-limited failure mechanism, where system collapse may occur when input dynamics exceed recovery capacity over finite time.

The model does not aim to represent a specific biological system, but to test a general dynamical mechanism under minimal assumptions.

---

## License

MIT License
