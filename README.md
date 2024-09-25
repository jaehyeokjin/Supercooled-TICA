# Supercooled-TICA
## tICA Projection Analysis of Supercooled Water MD Simulations

<img src="https://github.com/jaehyeokjin/Supercooled-TICA/blob/main/TOC_figure.png" alt="STICA Art" width="300"/>

This repository contains the analysis scripts and results for projecting time-lagged Independent Component Analysis (tICA) onto Molecular Dynamics (MD) simulations of supercooled water. 

The current analysis scripts and results are based on the preprint:  
*"Reactive Water Unravels the Quiescent Nature of Supercooled Water"* (available upon request) from 2016.  
For further inquiries, please contact me via email: [jj3296@columbia.edu](mailto:jj3296@columbia.edu).

### Prerequisites
To run the provided Python code, the following packages are required:
- **MSMBUILDER** (for `msmbuilder.dataset`)
- **MATPLOTLIB**

You can install MSMBUILDER from [here](http://msmbuilder.org/).

### Usage Instructions
Once MSMBUILDER is installed:
1. Load the processed h5 format trajectory from each folder.
2. Run the `plot_tica.py` script to perform the tICA projection analysis.

### Note on Data Availability
Due to the large size of the trajectories (over 50 ns), the full trajectory files have been omitted from this repository. Instead, we have uploaded the processed h5 trajectory files.

If you need access to the full trajectory data, please reach out to me at the email provided above.
