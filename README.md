# Data analysis for &ldquo;Substantial Oxygen Loss and Chemical Expansion in Lithium-Rich Layered Oxides at Moderate Delithiation &rdquo;
[![DOI](https://zenodo.org/badge/??.??)](https://zenodo.org/doi/1??)

Scripts to analyse and plot data supporting:
Substantial Oxygen Loss and Chemical Expansion in Lithium-Rich Layered Oxides at Moderate Delithiation
([ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/65c93d6b66c13817296bf3fc)).

Authors:
- Peter M. Csernica (orcid: [0000-0003-4259-1614](https://orcid.org/0000-0003-4259-1614))
- Kit McColl (orcid: [0000-0002-7794-8276](https://orcid.org/0000-0002-7794-8276))
- Grace M. Busse
- Kipil Lim
- Diego F. Rivera
- David A. Shapiro
- M. Saiful Islam (orcid: [0000-0002-3056-8233](https://orcid.org/0000-0003-0373-116X))
- William C. Chueh

## Summary
This repository contains the analysis and figure-plotting workflow for the manuscript &ldquo;Substantial Oxygen Loss and Chemical Expansion in Lithium-Rich Layered Oxides at Moderate Delithiation &rdquo; (([ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/65c93d6b66c13817296bf3fc)).

The workflow here contains three main components: 
- `Kinetics` (Kinetically possible rearrangements: AIMD)
- `Thermodynamics` (Thermodynamically favoured structures: cluster expansion & Monte Carlo)
- `Fluid_O2` (Nanconfined fluid O<sub>2</sub>)

which analyse and plot key data in Figure 2, 3 and 4 in the manuscript. The repositories will also cover all the analysis of DFT calculations, ab initio molecular dynamics simulations and cluster expansion and Monte Carlo simulations presented in the main paper, as well as the preparatory calculations peformed in to obtain structures with which to train the cluster expansion. Each section consits of annotated Jupyter notebooks that show how the computational analysis in the paper was conducted from calculation data.

Rerunning this workflow requires the raw calculation data files for several hundred DFT claculations, and AIMD trajectory files, which are not included in this repository due to a lack of space; data to generate key figures in the manuscript has been collated into `.json` files in the `./Data/` folder. 
