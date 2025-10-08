# Insights into Galaxy Populations and Evolution.


## Overview  
This notebook analyzes mock galaxy catalogues from the Euclid mission, combining simulated and observational data to study galaxy distributions, luminosities,evolution and large-scale structure.

---

## Workflow  
1. Load and preprocess mock catalogue (Position, redshift, magnitude, color).  
2. Visualize sky distribution and clustering using Healpix maps.  
3. Compute luminosity density function and compare to Schechter model.  
4. Visualize evolution of magniude with redshift.
5. Galaxy color distribution fitted with a 3-component Gaussian Mixture Model, representing blue, green, and red galaxy populations.

---

## Key Findings  
- Galaxy distribution traces realistic structures.  
- The luminosity defnsity function fits the Schechter form well.  
- Evidence of color bimodality (red vs. blue galaxies).  

---

## Tools  
`numpy`, `numpy`, `matplotlib`, `healpy`, `astropy`, `scipy`
Tools I used in this project.
-`numpy`
-`pandas`
-`matplotlib`
-`healpy`
-`scipy`

---

## Run it  
```bash
pip install numpy pandas matplotlib healpy astropy scipy
jupyter notebook "Insights into Galaxy Populations and Evolution..ipynb"
