2024-09-06 09:32

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology]]

DOI:

URL:

Tags: [[Glaciology - Energy Balance Model]] [[Glaciology - Debris]] [[Glaciology - Model]]

Status: #read-detailed 
# Using climate reanalysis data in conjunction with multi-temporal satellite thermal imagery to derive supraglacial debris thickness changes from energy-balance modelling

Supraglacial debris thickness has a direct impact on mass balance ([[Østrem, 1959]]; [[Nicholson and Benn, 2006]]). Debris layers range from a non-continuous layer, millimetres in thickness, to a blanket-like continuous cover that can reach several metres in thickness. As debris thickness increases from zero on a clean-ice surface, the sub-debris melt rate will increase until the critical thickness is reached, representing the maximum ablation rate. The maximum ablation rate is typically higher than for a climatologically equivalent clean-ice surface (Østrem, 1959; Mattson and others, (1993); [[Evatt et al., 2015]]). As a debris layer thickens, its ability to efficiently transfer thermal energy to the ice surface beneath decreases, and sub-debris melt decreases as debris insulates the ice surface (Østrem, 1959; [[Mattson et al, 1993]]).

Generally, debris thickness increases towards a glacier terminus and over time (e.g. Anderson, 2000; Gibson and others, 2017), transitioning from convex to concave in profile due to a decline in surface velocity and the conveyor belt-like nature of debris-covered glaciers (Anderson and Anderson, 2018).

Knowledge of the thickness of supraglacial debris remains unknown for most glaciers on Earth ([[Scherler et al., 2018]]; [[Herreid and Pellicciotti, 2020]]) and changes in thickness even more so.

Field measurements of debris thickness are difficult to collect.

Manual excavations, extrapolations from ice-cliff surveying are ground-penetrating radar measurements are the most commonly sued methods for measuring / estimating debris thickness.

Recent work to derive debris thickness from satellite thermal images using:

- Empirical relationships between debris thickness and surface temperature (Mihalcea and others, 2008a, 2008b)
- Limited by not being spatially or temporally transferable
- Surface energy-balance modelling which using debris thickness as the only unknown in the energy balance model.
- Can provide debris thickness at any point in space or time given that all the other input data is available.
- First attempt to reconstruct debris thickness from satellite thermal imagery was by [[Mihalcea et al., 2008a]] – derived elevation-dependent empirical relationship between debris surface temperature and debris thickness for Miage Glacier, Italy.
- Predicted to within +- 0.05m for thicknesses up to 0.4 ,.
- Primary limitation is that these relationships are only valid for the time and place they were derived -> cannot be transferred or used to detect change in thickness over time.

Study aims to test whether:

- A) reanalysis data can be used to estimate spatially distributed supra glacial debris thickness in a remote-sensing-driven energy-balance modelling framework
- B) determine whether these estimates of debris thickness can enable a multi-temporal analysis of debris thickness change.

Study uses model from [[Rounce and McKinney, 2014]]

- Rounce DR and McKinney DC (2014) Debris thickness of glaciers in the Everest area (Nepal Himalaya) derived from satellite imagery using a nonlinear energy balance model. Cryosphere 8(4), 1317–1329. doi: 10.5194/ tc-8-1317-2014.

Uses renalaysis data to force the model and reconstruct historical debris thickness and debris thickness change over time.

Data from NCEP/NCAR Reanalysis (Kalnay _et al_., 1996) and ERA-5 (Copernicus Climate Change Service, 2017).

In line with aim 2 – study applies the model to 44 time series images to obtain spatially distributed estimates of debris hickness at 3 glaciers: Miage, Khumbu, Haut Gladier d’Arolla

**Data:**

Use freely available remotely sensed data of debris surface temperature, DEMs, reanalysis data, and in situ measurements of meteorological variables and debris thickness

**Remotely sensed data:**

Used Landsat 7 Enhanced Thematic Mapper (ETM+) thermal imagery

Landsat 7 images suffer from a striping effect causing a loss of 22% of data from each image (Scaramuzza and Barsi, 2005)

Band 6 (thermal band) images were used to derive surface temperature by converting spectral radiance to surface temperature (Rounce and McKinney, 2014; NASA, 2020)

Uncertainty of +- 1 K

The Landsat 7 band 6 product has a 60 × 60 m grid spacing and was automatically resampled to 30 × 30 m.

ASTER Global Digital Elevation Model (G-DEM 2) (30x30m spacing) was used as a DEM input for model simulations.

Uncertainty of 10m and horizontal geolocation accuracy better than 50m

Therefore, final debris thickness maps have a spatial resolution of 30m.

**Reanalysis Data**

ERA-5 reanalysis data spans 137 pressure levels and has a horizontal resolution of ~0.5 degrees (55km x55km) at the equator.

Data acquired within 1 hour of landsat imagery

**Methods**

Energy-balance model seeks to solve equations of the energy balance at the debris surface and heat conduction into the debris and can be used to solve for debris thickness if the surface temperature is known.

Requires knowledge of metrological data and debris surface properties.

**Energy-balance model:**

![[Pasted image 20240906093300.png]]
Workflow for a given time step (tx):

1. Image acquisition from Landsat 7, ASTER G-DEM
2. GIS pre-processing of slope, aspect and hillshade products
3. Execution of the model

Following Rounce _et al_. (2018), authors define a series of 500m long contiguous boxes using the glacier centreline to form ‘flux boxes’

Does not use wind speed from reanalysis due to it being inaccurate at estimating local-scale surface wind speeds (Betts _et al_., 2019) – the model is sensitive to wind speed.

Therefore, wind speed was gathered from taking the mean AWS wind speed.

Fixed value of 1.41 ms-1 should be used for Himalayan settings.

**Model sensitivity and uncertainty**

Used a Monte Carlo framework to identify sensitivity to key parameters affecting debris thickness estimation.

Each parameter was varied randomly over 1000 model runs within a sensible range.

High sensitivity to surface roughness, incoming longwave radiation, and wind speed.

Minimal sensitivity to albedo, incoming shortwave radiation, and surface temperature.

Same Monte Carlo framework used to determine uncertainties into estimates of debris thickness.

There are several assumptions made in the model:

- Debris properties are assumed to be constant in time and uniform in space (despite being known to be highly heterogenous (e.g., Nicholson and Benn, 2013))
- Meteorological variables are also either assumed to be uniform in space or extrapolated to the glacier scale with relatively simple assumptions despite the potential for their variability to be high (e.g., Steiner and Pellicciotti, 2016)
- Calculates the uncertainty for each pixel by conducting 1000 Monte Carlo simulations varying each variable uniformly within a range of sensible values (Table 5)

Compared in situ measurements with debris thickness estimates -> disslink: same as what I've obvserved
	"Such comparison highlights an important methodological result and how debris thickness studies should be wary of describing debris thickness and debris thickness change using single images that might both have high errors and be affected by localised, timespecific thickness changes."
	we suggest that for the detection of debris thickness changes, trends from multiple estimates should be used

Author acknowledges that differencing different maps results in very different trends 

**Conclusions:**

Quantifying supraglacial debris thickness is essential for accurately calculating ablation from debris covered glaciers.

Debris thickness estimates using energy balance and ERA-5 surface-level reanalysis data were within 0.02m of in situ AWS-derived estimates.

AWS = automatic weather station

Advances are needed in energy-balance modelling, meteorological forcing, and debris properties.

Models should be improved by including transient simulations that are not limited to the instantaneous energy fluxes calculations at the time of the images, as these cannot capture changes in debris heat content and thus reproduce the correct temperature gradients within the debris

Furthermore, assumptions of a surface energy balance and a latent heat flux of zero at the top of the debris layer ([[Rounce and McKinney, 2014]]) need to be tested further and constrained with field observations

Future research should also seek to improve the downscaling of reanalysis data, and wind speed data in particular, to glacier surfaces