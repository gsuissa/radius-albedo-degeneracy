# radius-albedo-degeneracy
Inferring the Size of Directly-Imaged Exoplanets Using Solar System Phase Curves. \
Suissa et al. (in prep)

Includes Solar system phase curve data and solar system-derived $A_g\Phi(\alpha)$ prior to help break the radius-albedo degeneracy in direct imaging.

- [Solar System Phase Curves](solarsystem_agphi_suissa.dat): Interpolated phase curves in units of AgPhi collected by Suissa et al (in prep). Values are interpolated but not extrapolated.
- [Gas Giants Phase Curves](giantplanets_agphi_suissa.dat): Interpolated phase curves in units of AgPhi of just the giant planets. Values are interpolated but not extrapolated.
- [AgPhi Prior](agphi_prior_suissa.dat): Table of mean and sigma of lognormal distribution that describes solar system AgPhi at a specified phase angle
- [Monte Carlo Example](Cahoy-MC-Example.ipynb): Monte Carlo routine to infer radius distribution using AgPhi prior, using [Cahoy et al. 2010](https://ui.adsabs.harvard.edu/abs/2010ApJ...724..189C)  synthetic reflectance [spectra](cahoy_et_al_2010_models) as an example
