# Data from a TARA Oceans study

### Description

This dataset comes [this study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4851848):

> Guidi, L., Chaffron, S., Bittner, L., Eveillard, D., Larhlimi, A., Roux, S., ... & Coelho, L. P. (2016). Plankton networks driving carbon export in the oligotrophic ocean. Nature, 532(7600), 465-470.

The `data` subdirectory contains:

* `SI4_environmental_data.tsv`: Supplementary Table 4 containing environmental data for each sample:
  + `Sample`:	Sample ID
  + `Latitude`:	Latitude 
  + `Longitude`:	Longitude
  + `Salinity`:	Salinity 
  + `NO2 (umol/L)`:	NO2 concentration
  + `PO4 (umol/L)`:	PO4 concentration
  + `NO2NO3 (umol/L)`:	NO2NO3 concentration
  + `Mean Chloro HPLC adjusted (mg Chl/m3)`:	Chlorophyll concentration
  + `Mean Temperature deg C`:	Temperature in degree Celsius
  + `Mean Oxygen adjusted (umol/Kg)`:	Oxygen concentration
  + `Mean Flux at 150m`:	Carbon flux at 150m
  + `NPP 8d VGPM (mgC/m2/day)`:	NPP weekly average (VGPM model)

* `SI5_eukaryotic_lineages.tsv`: Supplementary Table 5 containing eukaryotic lineages and their correlations as computed using sparse PLS regression (sPLS)

* Normalised abundance tables

### How did we create these files?

* We **downloaded Supplementary Tables** as Excel sheets (`SI.tables.xlsx`) from http://www.raeslab.org/companion/ocean-carbon-export.html

* For the sheets containing **Table S4** and **S5**, we saved them in the Tab Separated Values (`.tsv`) format.

* **Normalised abundance tables** have just been extracted from the `norm.abundance.matrices.zip` archive and remained unchanged.