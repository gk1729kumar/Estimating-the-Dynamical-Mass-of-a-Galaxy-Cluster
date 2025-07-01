
## 📌 Project Overview
This project estimates the **dynamical** and **luminous mass** of a galaxy cluster using real astronomical data from the **Sloan Digital Sky Survey (SDSS)**. We select cluster members using redshift and velocity dispersion, calculate the cluster’s physical size, and apply the **Virial Theorem** to derive the total mass.

## 🎯 Objectives
- Select cluster galaxies using redshift and velocity filtering (±3σ).
- Calculate the velocity dispersion and redshift of the cluster.
- Determine the cluster’s physical radius using angular separation.
- Estimate the **dynamical mass** via the Virial Theorem.
- Estimate the **luminous mass** using g-band magnitudes and M/L ratio.
- Compare both mass estimates and evaluate the presence of dark matter.

## 📊 Tools & Libraries
- `pandas` — data handling  
- `numpy` — numerical operations  
- `matplotlib` — plotting and visualization  
- `astropy` — cosmological calculations and constants  

## 📁 File Structure
```

📦 galaxy-cluster-mass-estimation
┣ 📄 README.md
┣ 📄 LICENSE (MIT)
┣ 📄 Skyserver\_SQL6\_30\_2025.csv
┣ 📄 cluster\_mass\_analysis.ipynb
┗ 📊 output\_graphs/
┣ 📈 velocity\_histogram.png
┣ 📈 ra\_dec\_plot.png
┗ 📈 angular\_separation\_hist.png

```

## 🖼 Sample Output Graphs
- Velocity Distribution Histogram  
- RA vs Dec Plot of Galaxy Positions  
- Angular Separation Histogram

## 📈 Key Results
- **Mean Redshift (z):** 0.0808  
- **Velocity Dispersion:** ~1317 km/s  
- **Cluster Radius:** ~0.03 Mpc  
- **Dynamical Mass:** ~1.62 × 10¹⁴ M☉  
- **Luminous Mass:** ~1.52 × 10¹⁴ M☉  
- **Mass Ratio (Dyn/Lum):** ≈ 1.06  

## 🔗 References
- SDSS Sky Server: https://skyserver.sdss.org  
- Binney & Tremaine (1987), *Galactic Dynamics*  
- Mo, van den Bosch & White, *Galaxy Formation and Evolution*  
- Hogg (1999), *Distance Measures in Cosmology*

## 📝 License
This project is licensed under the [MIT License](./LICENSE). You are free to use, modify, and distribute this work with attribution.
