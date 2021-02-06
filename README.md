# Dual-AGN-Detectability
## This code is used for generating 2D detectability of dual AGNs with ~kpc separations. The detailed description of this project is published on Astrophysical Journal: 
Li, K., Bogdanović, T., & Ballantyne, D. R. 2020, ApJ 896 113
(https://ui.adsabs.harvard.edu/abs/2020ApJ...896..113L/abstract)

## Background 
> Observational searches for dual active galactic nuclei (dAGNs) at kiloparsec separations are crucial for understanding the role of galaxy mergers in the evolution of galaxies. In addition, kpc-scale dAGNs may serve as the parent population of massive black hole binaries, an important potential source of gravitational waves. Using a semi-analytic model to describe the orbital evolution of a massive black hole (MBH) under the influence of stellar and gaseous dynamical friction in post-merger galaxies, we investigate how the detectability of approximately 40, 000 kpc-scale dAGNs depends on the structure of the host galaxy and the orbital properties of the secondary MBH. The detectability of each dAGN system is defined as the product of the most likely separation of the two MBHs, the most likely luminosity ratio of the individual AGNs, and the decay timescale of the orbit of the secondary MBH. Assuming Bondi accretion onto the central, fixed primary MBH and Bondi- Hoyle-Lyttleton accretion onto the moving secondary MBH, kpc-scale dAGNs will be most easily detectable in rapidly rotating galaxies with gas rich disks and a bulge mass of 4E+9 M_sun. However, radiation feedback effects could strongly suppress the detectability in gas-rich galaxies. Any detected kpc-scale dAGNs are most likely to be high mass-ratio MBH pairs with secondary MBHs on low-eccentricity, prograde orbits within the post-merger galaxies.

> Each MBH evolution model produces a detailed description of the dAGN
position and luminosity throughout its evolution time (the
time required for the separation to reach 1 pc. Observationally
identifying a kpc-scale dAGN candidate will depend on both the
separation (d), and luminosity ratio (L_2/L_1), of a dAGN with
larger values of both properties increasing the chances of detectability. 
It is crucial, therefore, to determine the types of
galaxies and orbits that could increase the chances of finding dAGNs.

## Definition of Detectability Plot
> In order to determine how the structure of the galaxy and
properties of the orbits affect d and L_2/L_1, we compute the
fraction of evolution time that a particular model dAGN spends at different
values of d and L_2/L_1.

> We follow the evolution of the sMBH in dAGN
simulations from beginning to end summing the elapsed time whenever
the system is at a specific dAGN separation and luminosity ratio. The range of separation is evenly divided into nine bins with a size of 0.1 kpc, while the logarithm of luminosity ratio (ranging from -3 to 3) is divided into six bins with a size of 1. 

> Thus, for each model we produce a
two-dimensional probability distribution that shows the likelihood a
dAGN is observed at different points in the (L_2/L_1,d) plane. The
maximum of the distribution is where the dAGN spends the largest
fraction of its evolution time, and is identified as the most-likely
combination of luminosity ratio and separation at which the dAGN would
be observed. 

# Getting Start
### 1. Download the python code and the data zip file.
### 2. Unzip the data file, and put the python code into the same directory.
### 3. Run the code and generates the 2D detectability plots. Here is an example of the 2 plots generated using the unmodified code and the 18 data files which you can download from this repositery:

![Image of 2d plot](https://github.com/kli356/Dual-AGN-Detectability/blob/Detectability/dl_pro_small.png)
![Image of 2d plot](https://github.com/kli356/Dual-AGN-Detectability/blob/Detectability/dl_retro_small.png)

**Figure.1** The two-dimensional probability distribution of dual AGNs in prograde oribts, embedded in galaxies with M_bin = 3E+6 M_sun, q = 1/9, and vg = 0.2vc. The distributions are summed over all values of n_gd0 and f_gd. The top panel shows the plot for sMBHs on prograde orbits, while the results for retrograde orbits are plotted in the bottom panel. For either type of orbit, The most likely dual AGN luminosity ratio in these types of galaxies is L2/L1 ∼ 1E-2, although prograde orbits have the potential to produce higher ratios. In contrast, sMBHs on retrograde orbits are most likely to be found at separations of 0.5–0.9 kpc, while those on prograde orbits will likely be found at 0.3–0.4 kpc. The difference in the most-likely separations is due to how the eccentricity of the orbits evolve in the two cases (see Sect. 3.1 of https://ui.adsabs.harvard.edu/abs/2020ApJ...896..113L/abstract).


