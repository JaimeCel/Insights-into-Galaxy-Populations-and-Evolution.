# Insights into Galaxy Populations and Evolution.


## Overview  
This notebook analyzes mock galaxy catalogues from the Euclid mission, combining simulated and observational data to study galaxy distributions, luminosities,evolution and large-scale structure.

---

## Workflow  
1. **Load & preprocess** mock catalogue (RA, Dec, redshift, magnitude, color).  
2. **Visualize** sky distribution and clustering using **HEALPix maps**.  
3. Compute luminosity function and compare to Schechter model.  
4. Compare results across galaxy populations and redshift bins.

---

## Key Findings  
- Galaxy distribution traces realistic **cosmic web structures**.  
- The **luminosity function** fits the Schechter form well.  
- Evidence of **color bimodality** (red vs. blue galaxies).  

---

## Tools  
`numpy`, `pandas`, `matplotlib`, `healpy`, `astropy`, `scipy`

---

## Run it  
```bash
pip install numpy pandas matplotlib healpy astropy scipy
jupyter notebook "Insights into Galaxy Populations and Evolution..ipynb"
