# Projected climate change scenarios spatially decouple desert EFN-ant mutualisms.
Storage for derived data files and analyses 

![image](https://github.com/user-attachments/assets/0aea01fe-3f6b-4343-af7a-42b2e3216b2a)



## Getting Started

These instructions describe the contents of this repository and will get you a copy of the project up and running on your local machine. 

See https://jennabraun.github.io/prey_item_survey for final work up 

### Folder descriptions

* data folder - watershed boundary file and phylogenetic tree files
    * output folder
	* predictions - consensus species prediction rasters
		* Future - consensus species prediction rasters for future scenarios
	* vi - Variable Importance for Plant Models
	* viants - Variable Importance for Ant Models
* predictions - csv files holding the results of cross-validation for plant species SDM (40 runs per species)
	* antcontrasts - csv holding CV results for ant species SDM with EFN and only EFN
	* ants - csv holding CV results for climate-based ant species SDM
* sdmscripts - scripts used to create the SDMs, note: These scripts require large external datasets to run

envs.grd - raster derived from PCA applied to worldclim data clipped to study extent
na_rasters - worldclim data raster clipped to study extent
ssp245, ssp370 - raster derived from PCA applied to worldclim


Index.Rmd is the main document for analysis
