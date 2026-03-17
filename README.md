# Oxygen Regime Boundary — Minimal Model

This repository explores whether oxygen chemistry may be structured by regimes (O–O vs O–H dominated species) rather than a continuum.

## Approach

A minimal descriptor set is used:

- Molecular weight  
- Electron affinity  
- Ionization energy  
- Number of oxygen atoms  

Principal Component Analysis (PCA) is applied to project species into a low-dimensional descriptor space.

## Key Observation

A linear boundary appears to emerge separating:

- O–H dominated species  
- O–O dominated species  

A held-out species (O3) is then projected to test whether it falls on the expected side.

## Results

- Linear separability in minimal descriptor space  
- Leave-one-out accuracy: 1.0 (very small dataset; result not yet generalizable) 
- O3 classified consistently with O–O regime  
- Boundary score correlates with physical descriptors  

## Limitations

- Very small dataset  
- Boundary orientation not stable under bootstrap  
- Results are preliminary and hypothesis-generating  

## Reproducibility

Run:
