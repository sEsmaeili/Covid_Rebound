# Covid_Rebound
This repository contains supporting files for the results reported in "A unifying model to explain nirmatrelvir / ritonavir's high efficacy during early treatment and low efficacy as post-exposure prophylaxis, and to predict viral rebound"

Shadisadat Esmaeili (1), Katherine Owens (1), Jessica Wagoner (2), Stephen J. Polyak (2), Judith M. White (3), and Joshua T. Schiffer (1,2)

1. Fred Hutchinson Cancer Center, Vaccine and Infectious Diseases Division
2. University of Washington, Department of Medicine
3. Department of Cell Biology, University of Virginia; Charlottesville, VA, USA.


Content includes:
   - Python notebooks for figures 2-8 and S1-S16
   - AllFunctions supporting Python notebook
   - individual VL parameters
   - population VL parameters
   - Nirmatrelvir individual PK parameteres
   - Nirmatrelvir population PK parameters
   - VL Data file for NBA cohort with variant information
   - Nirmatrelvir PD data
### System's Requirements

Codes are written in Python 3.9.12 and can be run on Jupyter notebook on any standard Mac or Windows computer.

### Instruction for use

Jupyter notebook "All_Functions.ipynb" contains all the necessary functions and needs to be in the same directory as the other notebooks for all the other notebooks to run successfully.
Path names for the files should be updated. 

### Demo
a demo file is provided to run the simulation for the 400 sample individuals in the NBA cohort with Omicron infection (Demo_file.cvs). 

Run time on a standard Mac OS: under 4 minutes

Output: rebound probablity of control and different treatment arms with different treatment timings (PEP, early, intermediate, late)

minor change to the exact rebound percentages is expected in each run due to the stochastic nature of incubation period, Pk, and PD parameters.

