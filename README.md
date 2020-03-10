# Background
This repository accompanies the publication XYZ. 

# Inventory 
**[Notebook 1: Classical Electrostatic Analysis](https://github.com/FaradayInstitution/redox_descriptors/blob/master/Notebooks/Notebook_1-madelung_analysis.ipynb)** 

- Crystal structure analysis to calculate Madelung site potentials for Oxygen.
- Comparison of LiMO2 and Li2MO3 model systems. 
- Comparison of local oxygen coordination environments in disordered 128 atom supercells of LiMO2 compounds.
- Calculation of "hole localization energy" on oxygen vs. transition metal.

**[Notebook 2: Quantum Electronic Structure](https://github.com/FaradayInstitution/redox_descriptors/blob/master/Notebooks/Notebook_2-DOS_analysis.ipynb)**

- Calculation of contributions of different states to the upper valence band of electronic density of states.


# Data
- `relaxed_structures.json`  - Relaxed LiMO2 and Li2MO3 crystal structures used as input for Notebook 1. 
- `ionisation_potentials_TM.csv` - Ionization potentials used in the calcualtion of hole localization energy in Notebook 1.
- `electronic_structure_data/`
	- VASP output (`vasprun.xml`) and crystal structure (`CONTCAR`) for each compound used as input for Notebook 2.
	- DOS data and plots produced by [sumo](https://github.com/SMTG-UCL/sumo) (`*dos.dat`,`dos.pdf`). 
	- config files for sumo DOS plotting code (`custom_colors.conf`, `custom.mplstyle`). 
- `matplotlibrc` - Matplotlib config file used to generate plots (set `text.usetex: False` if LaTeX not installed).

