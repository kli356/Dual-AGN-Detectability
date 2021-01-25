# Dual-AGN-Detectability
## This code is used for generating 2D detectability of dual AGNs with ~kpc separations. The detailed description of this project is published on Astrophysical Journal: 
Li, K., Bogdanović, T., & Ballantyne, D. R. 2020, ApJ 896 113
(https://ui.adsabs.harvard.edu/abs/2020ApJ...896..113L/abstract)

# Getting Start
### 1. Download the python code and the data zip file.
### 2. Unzip the data file, and put the python code into the same directory.
### 3. Edit the input files' name according to your need.
Data file name has the format of : "dl_orbit. a, b, c, d, e.txt"

- orbit= l2, lr2, h2, hr2 for prograde+low e_0, retrograde+low e_0, prograde+high e_0, retrograde+high e_0 
- a= 0, 1, 2 for v_g= 0.2, 0.5, 0.8 v_c
- b= 0, 1, 2 for f_dg= 0.3, 0.5, 0.9
- c= 0, 1, 2 for M_bin= 3E+6, 1.0E+7, 1.0E+8 M_sun
- d= 0, 1, 2 for n_gd0= 100, 200, 300 /cm^3
- e= 0, 1, 2 for q= 1/4, 1/8, 1/10 
### 4. Run the code and generates the 2D detectability plots. Here is an example of the 4 plots generated:
()
