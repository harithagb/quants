# Volatility Modeling in the Two-Factor Bergomi Framework

This project explores volatility surface modeling for SPX and VIX derivatives using the two-factor Bergomi stochastic volatility model. Implemented under the guidance of Prof. Julien Guyon, it emphasizes both theoretical understanding and practical implementation of smile dynamics and derivative pricing.

## Objective
To simulate and understand the behavior of SPX and VIX smiles under the two-factor Bergomi model, and to analyze the effects of various model parameters such as volatility-of-volatility, mean reversion, and correlation.

## Methodology
- **Model**: Two-factor Bergomi stochastic volatility model.
- **Simulation**: 
  - Generate SPX volatility smiles across strikes using Monte Carlo.
  - Vary correlation matrices, VoV, and mean reversion speed to examine smile sensitivity.
- **Techniques**:
  - Cholesky decomposition for simulating correlated Brownian motions.
  - Gauss-Hermite quadrature applied to VIX option pricing.
  - Parameter stress testing for smile shape dynamics.

## Additional Work
- A separate notebook in this directory explores **particle-based calibration methods** for the two-factor Bergomi model. This is currently in progress.

## Files
- `0c7fd819-e561-4771-8c69-a7b7afb74736.ipynb`: Main notebook for SPX and VIX smile simulations.
- `particle_calibration.ipynb` (WIP): Work-in-progress notebook for particle filter–based calibration.

## Dependencies
- Python 3.9+
- `numpy`, `pandas`, `matplotlib`, `scipy`

## Credits
This project was developed under the supervision of Prof. Julien Guyon as part of advanced volatility modeling coursework.

---

This project uses simulated data and does not rely on any proprietary datasets.
