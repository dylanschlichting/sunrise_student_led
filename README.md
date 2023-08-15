# sunrise_student_led
```sunrise_student_led``` is a repository for analysis of TXLA model output used for the 2022 SUNRISE student cruise manuscript. All analysis is done in Python via Jupyter notebooks. To run the notebooks in this repository, an environment can be installed by running 

        conda install --file copano.txt
## Analysis notebooks (work in progress)
> There are several notebooks to
> - Make an overview figure that contains snapshots of ESA Sentinal data for Chlorophyll and sediment concentration on Jul 3, 2022. Likewise, TXLA model salinity, vorticity, and then zoomed in locations of the cruise are provided. Pointwise time series of wind stress and surface currents may also be included. Due to the different aspect ratios, we construct the figure offline using a third party software such as powerpoint. 
> - Computes a volume-integrated heat budget with diagnostic and average files from 2010 to assess their accuracy.
> - Compute a volume-integrated heat budget with average files during the 2022 cruise and the associated Ekman buoyancy flux.  
> - Make TS diagrams with model and observational data to qualitatively assess model skill. Also coded TS diagrams by vertical momentum mixing, or the dissipation of total kinetic energy. 
