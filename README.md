# HOD_in_TNG300

Brief code for HOD in TNG300:

- HOD1_proyect_cen_sat_all.ipynb is the script for the first HOD, separating the sample into centrals, satellites, and the entire population (with a stellar mass cut).

- HOD2_proyect_color.ipynb is the script for the HOD, but it separates galaxies based on a color threshold (g-r = 0.64 [mag]). Be careful, as there are galaxies classified as red or blue for which the fits do not work.

- HOD3_proyect_sfr.ipynb is the script for the HOD, but it separates star-forming and quiescent galaxies (using sSFR = 10^(-10.5) as the threshold).

- HOD4_proyect_fit.ipynb is the script used to fit our HOD with the five-parameter model (M_min, sigma_logM, M_cut, M_1, alpha). The fitting process is a bit challenging, but you can try to improve it.
  
- HOD5_proyect_CF.ipynb is the script to compute correlation function (for a clustering measurement) of our sample, you can try connecting it with the five-parameters HOD model.
