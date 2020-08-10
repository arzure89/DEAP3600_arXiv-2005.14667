====================================================================================================
The dataset provided was used for the paper: 
"Constraints on dark matter-nucleon effective couplings in the presence 
of kinematically distinct halo substructures using the DEAP-3600 detector"
on behalf of DEAP-3600 collaboration.
----------------------------------------------------------------------------------------------------
arXiv:2005.14667 [astro-ph.CO]
for Physical Review D
----------------------------------------------------------------------------------------------------
Four directories are included:

1. limits
 
Exclusion curves organized according to the subtructures. Inside each subtructure's directory, there are subdirectories corresponding to each isospin scenario: isoscalar (IS), isovector (IV), and xenonphobic (XP). Exclusion curves are formatted as text files with two columns: DM mass [GeV/c^2] and DM-proton cross section [cm^2]. File names encode the models used for each curve, including the relative substructure density. For example, lim_G6_IS_O3_etasub30.txt refers to an isoscalar interaction using the O3 operator with the G6 group of substructures at a relative density of eta_sub = 30%. These files contain exclusion curves shown in Figures 7, 8, 9, 10, 11, and 12.

2. recoil_energy_spectra

Recoil energy spectra computed for a DM mass of 100 GeV/c^2. These spectra correspond to those shown in Figures 3, 4, 5, and 6, and they are sorted into subdirectories corresponding to each figure. Spectra are drawn for DM-nucleon cross sections that give similar numbers of events within the region of interest, to make comparisons of their shapes more clear. Spectra are provided as text files with two columns: recoil energy [keV] and differential scattering rate [keV kg day]^-1. More details are given in the captions for each figure, which are reproduced in the Caption.txt files in each subdirecory.

3. specific_intercations

Exclusion curves for anapole, magnetic dipole, electric dipole, and millicharge DM-nucleon interactions. Inside this directory, there are subdirectories corresponding to each interaction type, which contain files corresponding to each velocity distribution function considered in this analysis. For example, cou_G5_milli_etasub30.txt contains limits for the G5 group of substructures at a relative density of eta_sub = 30% for millicharge interactions. Limits for the SHM correspond to those shown in Figure 13 of the paper. Exclusion curves are formatted as text files with two columns: DM mass [GeV^-1] and coupling strength. Coupling strengths are given for each interaction type as follows,
 - anapole: coupling constant [GeV^-2]
 - magnetic dipole: magnetic dipole moment [GeV^-1]
 - electric dipole: electric dipole moment [GeV^-1]
 - millicharge: fractional elementary charge [e]

4. vdf

This directory contains the group representatives for the velocity distribution functions (VDFs), as listed in Table II of the paper and shown in Figure 2. VDFs are sorted into subdirectories named after the corresponding group, and are formatted as as text and ROOT files. Each VDF formatted as a text file has two columns: DM speed [km/s] and probability [km/s]^-1. File names denote the substructure being added to the SHM and the substructure's relative density. For example, vdf_G6_etasub30.txt shows the VDF for the SHM plus the G6 group representative substructure with a relative density of eta_sub = 30%, and vdf_shm.txt contains the pure SHM.

