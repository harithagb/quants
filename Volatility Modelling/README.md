# Create a new README.md and .txt file for the volatility smile modeling project

readme_content = """# Volatility Smile Modeling and Implied Volatility Surface Fitting

This project demonstrates how to model and fit volatility smiles using option market data. The goal is to build a robust implied volatility surface and assess the quality of the fit using public or synthetic data.

## Objective
To explore techniques for modeling implied volatility smiles across strikes and maturities, using a combination of analytical models and numerical optimization.

## Methodology
- **Data**: Synthetic or publicly available options data across different strikes and maturities.
- **Smile Modeling**:
  - Fit implied volatility curves using quadratic and cubic splines.
  - Regularize fits to reduce overfitting and ensure smoothness.
- **Surface Construction**: Extend across maturities to build a vol surface.
- **Diagnostics**:
  - Visual plots of fitted vs market IVs
  - Residual error metrics
  - Commentary on extrapolation behavior

## Highlights
- Clean illustration of volatility smile behavior
- Robust fitting techniques with interpretability
- Framework adaptable to real-world option surfaces

## Files
- `HarithaGB_VolModels.ipynb`: Main analysis notebook
- `data/`: Assumed directory for public/simulated data

## Dependencies
- Python 3.9+
- `pandas`, `numpy`, `matplotlib`, `scipy`, `statsmodels`
"""

txt_content = """GitHub repo for code sample: 
https://github.com/harithagb/quants/blob/main/Volatility%20Modelling/HarithaGB_VolModels.ipynb

Project: Volatility Smile Modeling and Implied Volatility Surface Fitting
Description: Demonstrates volatility smile modeling using splines and surface fitting techniques. Based on public or synthetic data.
"""

readme_path = "/mnt/data/README_vol_smile.md"
txt_path = "/mnt/data/BestWork_VolSmile.txt"

with open(readme_path, "w") as f:
    f.write(readme_content)

with open(txt_path, "w") as f:
    f.write(txt_content)

readme_path, txt_path
