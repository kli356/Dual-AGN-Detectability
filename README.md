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
- e= 0, 1, 2 for q= 1/3, 1/7, 1/9 
### 4. Run the code and generates the 2D detectability plots. Here is an example of the 4 plots generated:

![Image of 2d plot](https://github.com/kli356/Dual-AGN-Detectability/blob/Detectability/dl_pro_small.png)

**Figure.1** The two-dimensional probability distribution of dual AGNs in prograde oribts, embedded in galaxies with M_bin = 3E+6 M_sun, q = 1/9, and vg = 0.2vc. The distributions are summed over all values of n_gd0 and f_gd. The most likely dual AGN luminosity ratio in these types of galaxies is L2/L1 ∼ 1E-2, although prograde orbits have the potential to produce higher ratios. 


![Image of 2d plot 2](https://github.com/kli356/Dual-AGN-Detectability/blob/Detectability/dl_pro_large.png)

**Figure.2** The two-dimensional probability distribution of dual AGNs in prograde oribts, embedded in galaxies with M_bin = 1E+8 M_sun, q = 1/3, and vg = 0.8vc. The distributions are summed over all values of n_gd0 and f_gd. Here, the decrease in relative velocity between the sMBH and the galaxy increases the accretion rate onto the sMBH, boosting the most likely observed value of L2/L1 to ∼ 1 for prograde orbits. In addition, as the characteristic scales of the bulge and disks are proportional to M1 there will be a larger gas density at a given separation, further enhancing L2 compared to the situation in Fig. 1.
