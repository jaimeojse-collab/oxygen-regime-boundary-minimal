# Oxygen Regime Boundary — Minimal Model
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19069266.svg)](https://doi.org/10.5281/zenodo.19069266)

This repository explores whether oxygen-related systems may be structured by regimes rather than continuous transitions.

We investigate two complementary perspectives:

	•	A descriptor-based boundary (PCA on oxygen species)
	•	A dynamical boundary (finite-time recovery behavior)

## Approach

1. Descriptor space (oxygen species)
A minimal descriptor set is used:

	•	Molecular weight
	•	Electron affinity
	•	Ionization energy
	•	Number of oxygen atoms

Principal Component Analysis (PCA) projects species into a low-dimensional space.

A boundary appears to emerge separating:

	•	O–H dominated species
	•	O–O dominated species
  
2. Dynamical system (minimal model)
A minimal recovery-limited dynamical system is constructed to test whether failure depends on:

	•	total load
	•	vs. rate of application (rise time)  
  

## Key Observation

A boundary appears to emerge separating regimes with distinct recovery behavior.

	•	At matched load, recovery depends on rise time
	•	A region exists where recovery becomes dynamically inaccessible within finite time
	•	A sharp transition appears in (load, rise_time) space

## Results

	•	Critical load increases with rise time (r ≈ 0.98)
	•	Recovery time shows nonlinear scaling with load
	•	A temporal boundary emerges in the system
	•	Boundary structure is reproducible under minimal assumptions

## Interpretation

These results suggest that regime structure may depend not only on system state, but on transition dynamics.

This minimal model was originally motivated by structural trajectories observed in oxygen redox systems.  

## Limitations

	•	Very small dataset (descriptor model)
	•	Minimal dynamical abstraction (not system-specific)
	•	No direct comparison with experimental data yet
	•	Results are hypothesis-generating  

## Reproducibility

Run:
finite_time_recovery_boundary.ipynb
and
oxygen_regime_boundary_.ipynb

## DOI

https://doi.org/10.5281/zenodo.19069266

## Citation

If you use this work, please cite:

Ojeda, J. (2026).  
Oxygen Regime Boundary — Minimal Model.  
Zenodo. https://doi.org/10.5281/zenodo.19069266
