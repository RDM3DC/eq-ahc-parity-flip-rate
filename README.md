# AHC Parity Flip-Rate (locking observable)

**ID:** `eq-ahc-parity-flip-rate`  
**Tier:** derived  
**Score:** 87  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
r_b=\frac{\#\{k:\ b_k\neq b_{k-1}\}}{K-1}
$$

## Description

The key AHC observable: fraction of consecutive steps where parity flips. AHC prediction: r_b drops when α_π/μ_π is high enough ('parity locking'). This is the primary testable quantity for the qubit Berry-loop experiment.

## Assumptions

- K is large enough for the ratio to be statistically meaningful.
- Parity flips are detected correctly (no double-counting at coincident singularities).

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
