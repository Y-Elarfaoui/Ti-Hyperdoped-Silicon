Computational Input Files
The complete Quantum ESPRESSO input files optimized atomic structures, pseudopotentials, and post-processing scripts used in this work are publicly available in the accompanying GitHub repository (link to be added upon publication). The repository contains all files required to reproduce the calculations reported in this study.
S1. Self-consistent field (SCF) calculations
Self-consistent DFT calculations were performed for all investigated Ti defect configurations in silicon, including:
	Interstitial Ti (Tii) 
	Substitutional Ti (TiSi) 
	Interstitial–substitutional Ti complex (TiSiTiiSi64) 
The corresponding SCF input files include the optimized supercell structures, computational parameters, pseudopotential definitions, Brillouin-zone sampling, and convergence criteria used throughout this work.
GitHub files
	SCF_Tii.in 
	SCF_TiSi.in 
	SCF_TiSiTiiSi64.in 

S2. Band structure calculations
Band structure calculations were performed using the converged SCF charge density along the high-symmetry path
Γ-X-M-Γ-R-X-M-R

The complete band structure input files, including the selected k-point path, are available in the GitHub repository.
GitHub file
	bands_TiSi.in 

S3. Optical calculations
The frequency-dependent dielectric function and optical absorption spectra were calculated using the Quantum ESPRESSO epsilon.x post-processing code. The input file specifies the energy grid, Gaussian broadening, and spectral sampling used to obtain the optical properties presented in the manuscript.
GitHub file
	epsilon.in 

S4. Optimized structures
The fully relaxed atomic coordinates for all Ti defect configurations used in this work are provided in the GitHub repository.
The structures include
	Ti interstitial (Tii) 
	Ti substitutional (TiSi) 
	Ti interstitial–substitutional complex (TiSiTiiSi64) 
in standard Quantum ESPRESSO input format.

S5. Repository
The complete computational dataset required to reproduce this work is available at
GitHub Repository
https://github.com/Y-Elarfaoui/Ti-Hyperdoped-Silicon
The repository contains:
	Complete SCF input files 
	Band structure input files 
	Optical-property (epsilon.x) input files 
	Relaxed atomic structures 
	K-point paths 
	Pseudopotential information 

