## Theoretical Challenges for Ocean Dynamics
### Ice-ocean interactions jupyter notebook

This is the public repository for the coding/hands-on session on ice-ocean interactions of the Theoretical Challenges for Ocean Dynamics graduate school week, which will take place at ENS de Lyon from Nov 17 to 21st 2025. The notebook explores the validity of the 3-equation parameterization for ice-ocean boundary layers using data from Ronne ice shelf (site 5).

A big thank you to Keith Nicholls and Pete Davis (British Antarctic Survey), former colleagues, who made the data available and helped me make sense of it.

The files are:
- Depths5c.mat : the deployment depths of the instruments that went down at site 5
- s5cInterpAll.mat : time series for all variables of interest derived from the instrument measurements
- iceocean-tcod2025_intro.pdf : a short intro to ice-ocean boundary layers
- iceocean-tcod2025_starter.ipynb : the problem set
- iceocean-tcod2025_solutions.ipynb : the problem set with solutions, available at the end of the session
- teaching.yml : the environment file (modules required) to create a suitable conda environment

### Getting started

- Install Miniconda : https://www.anaconda.com/docs/getting-started/miniconda/main
- Create the environment using teaching.yml : https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

### Related references

- Rosevear, M. G., Gayen, B., Vreugdenhil, C. A., & Galton-Fenzi, B. K. (2025). How does the ocean melt Antarctic ice shelves?. Annual Review of Marine Science, 17(1), 325-353.
- Hattermann, T., Nicholls, K. W., Hellmer, H. H., Davis, P. E., Janout, M. A., Østerhus, S., ... & Kanzow, T. (2021). Observed interannual changes beneath Filchner-Ronne Ice Shelf linked to large-scale atmospheric circulation. Nature Communications, 12(1), 2961.
