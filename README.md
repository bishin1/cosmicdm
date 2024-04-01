# COSMICDM

This is a Mathematica code for proving the possible existence of dark matter within our galaxy using cosmic-ray data. Dark matter constitutes 24% of the energy density of our universe and is abundant within our galaxy as well. To indirectly prove the existence of dark matter, I calculated the amount of anti-protons produced by dark matter and compared this with actual data.


# Dark Matter Distribution
The distribution of dark matter was calculated using PPPC4DMID (http://www.marcocirelli.net/PPPC4DMID.html). PPPC4DMID is a Mathematica package that calculates the quantity of standard model particles produced during the annihilation/decay processes of dark matter within our galaxy. Specifically, I used ProtonFluxELDRAnn.m to calculate the quantity of protons with the characteristics of Energy Losses including tertiaries and Diffusive Reacceleration generated from dark matter.

The mass of dark matter is specified in the range of 0.1 GeV to 1000 GeV.

To explore various characteristics of dark matter, distributions were obtained in multiple ways.

Propagation function: MIN, MED, MAX

Halo profile: NFW, BURKERT, EINASTO

Distribution based on characteristics during dark matter annihilation: MASS, CHARGE, DEMOCRACY

# ERROR BAR
Actual observational data was obtained from AMS-02 data(https://ams02.space/publications/201601), and an error bar plot was produced using Mathematica code.
To check the data and calculate the error bars, refer to the nb files in the Error-bar folder.
