# sMC (Scaling Monte Carlo)

Optical diagnostic techniques
1. Monitor physiological parameters by using optical methods
2. Analyze spectral features that give diagnostic information
3. detect disease (cancer and/or precancer)

## Spectroscopy
Measuring the wavelength dependent changes of light after interaction with matters can give us some information about the matter of interest.

## Algorithm Steps
* Simulation with a Large Number
> Use a large number of photons to solve the photon propagation problem (simulate how photons propagate in tissue.)
* Random Walk
> Track the “random walk” of photons in a medium with both absorption and scattering.
* Pros
> Flexible and accurate. It can handle any source and detector geometry, tissue geometry and tissue optical properties.
* Cons
> Very time-consuming!!! Large numbers (107~108)of photons are needed!!!

## Scaling Monte Carlo (sMC)
* sMC has higher accuarcy.
* Competible speed-up ratio (Relative acceleration to standard MC is around 200).
* sMC is practical and flexible to model light transport in inhomogeneous layered tissue.
* We can get the results of different wavelength in only one time simulation.
However, there are no available open source software based on sMC yet.
