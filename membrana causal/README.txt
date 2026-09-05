Resonant Hunter v13 Paper Package - English

Contents:
- validation_script.py : Final validation script v12 Spritz Fix v2 - reads X,Y,Z -> A,E,T, cleans NaN gaps (10080/146160), bandpass 0.005-0.045 Hz, F_eff corrected, Hilbert DeltaPhi avoids N_A*N_E, UAT sub-Higgs drift 0.046 mHz/day
- scientific_methodology.pdf : Full methodology from v10 Welch to v13 VGB 365d secular, steps to reach final script, explanation of console output (NaN gaps, resample, mean/std)
- field_equations.pdf : Field equations - TDI conversion, F_eff orbital modulation, bandpass Hilbert, UAT sub-Higgs f(t)=f0+alpha_si*t*k_early*(1-R_sub), overdrive ratio 5.32>4.5 energy 3531.7x, Lambda ground truth we do NOT use
- supplementary.zip : All graphics (46 png) and CSVs from runs - combined 4 residues, VGB secular, sub-Higgs, integrated LDC etc.

Dataset: LISA Spritz LDC2b Zenodo Open DOI 10.5281/zenodo.7436568 - Published 14 Dec 2022 - Files: mbhb1 85.8 MB, mbhb2 85.8 MB, vgb 1.0 GB, orbits.h5 618 kB - No registration needed (LDC portal autoregistration disabled until 15 Sept)

How to run in Colab:
1. Download files via wget -c https://zenodo.org/records/7436568/files/LDC2_spritz_mbhb1_training_v2.h5 etc to /content/
2. Run python validation_script.py
3. Outputs: hunter_v12_fix2_*.png and csv with residuo mean -10.70 mHz std 15.27 etc

Console output explained in methodology PDF.

DOIs: Resonant Hunter 10.5281/zenodo.18446712, UAT 10.5281/zenodo.17729221, UPC 10.5281/zenodo.18210808
