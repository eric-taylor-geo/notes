2024-10-02 11:07

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology|Glaciology]]

DOI:

URL: onlinelibrary.wiley.com/doi/full/10.1029/2017JF004395

Tags: [[Glaciology - Debris]] [[Glaciology - Energy Balance Model]]

Status:
# Quantifying Debris Thickness of Debris-Covered Glaciers in the Everest Region of Nepal Through Inversion of a Subdebris Melt Model


- Novel method for estimating debris thickness using DEM, surface velocity, ice thickness estimates, and a debris-covered energy balance model.
- Method able to estimate debris thicker than 0.5 m - a limitation of [[Rounce and McKinney, 2014]]

## Measuring Thickness

Disslink: useful for Lit review

[[Rounce et al., 2018]]

 **In situ**:
 
 - Manual excavation [[Patel et al., 2016]] [[Reid et al., 2012]] [[Rounce and McKinney, 2014]] [[Soncini et al., 2016]]
 - Surveying debris above exposed ice faces [[Nicholson and Benn, 2012]]
 - Terrestrial Photography [[Nicholson and Mertes, 2017]]
 - Ground penetrating radar [[McCarthy et al., 2017]] [[Nicholson and Mertes, 2017]] [[Wu and Liu, 2012]]
 - Difficult to apply at glacier scale and above due to time and labor constraints
 - Available measurements tend to be focused on localised sections of debris-cover and therefore may not be representative of the whole glacier

**Empirical relationships:**

- [[Mihalcea et al., 2008a]]
- [[Soncini et al., 2016]]

**Inverse Ostrem Curve**:

- [[Regettli et al., 2015]] - using an energy balance model and surface lowering measurements
- Promising results but limited validation.

**Energy balance models:**

- [[Rounce and McKinney, 2014]] [[Foster et al, 2012]] [[Schauwecker et al., 2015]]

- Uncertainties in meteorological data, debris properties, and components of the surface energy balance model are obstacles to these approaches.
- Energy balance models above have been unable to accurately estimate debris thicker than 0.5 m
- In addition, the low resolution of thermal imagery can cause a 'mixed pixel' effect where a single pixel can contain debris, ice cliffs, and supraglacial ponds
	- This reduces the surface temperature, thereby underestimating the thickness of debris
- Validation of model results is a general issue for remote sensing approaches in HMA due to the lack of in situ measurements against which to compare estimates.
![[Pasted image 20241006193953.png]]
## Methods

**Flux Divergence and Vertical Velocity**

[[Cogley et al., 2011]]: 
>Negative Flux divergence: box is gaining mass and is called the emergence velocity
>Positive Flux divergence: box is losing mass and is called the submergence velocity


- Study uses a forward model of subdebris melting [[Rounce et al., 2015]] in an inverse approach - debris thickness is iteratively adjusted until modeled subdebris melt agrees with the observed subdebris melt rate
	- *Okay I am confused - Rounce et al, 2015 uses manual measurements of debris thickness to calculate the ablation rate - soooooo …. ?*
- Subdebris melt model is driven by meteorological data from a weather station
- Shading effect not included due to low resolution of DEM
- Temperature extrapolated spatially using lapse rate of 6.5
- Other meteorological data assumed to be constant over the glacier

**Debris thickness estimates:**

- The continuity equation shows the relationship between the rate of change of glacier thickness (_ḣ_), climatic-basal mass balance (_ḃ_>), and flux divergence ( ![urn:x-wiley:21699003:media:jgrf20837:jgrf20837-math-0006](https://agupubs.onlinelibrary.wiley.com/cms/asset/9afc59f8-0de5-4758-b6c7-91e489ae80a2/jgrf20837-math-0006.png)) [[Cogley et al., 2011]]
![[Pasted image 20241008111505.png]]
 - Study assumes that $ḣ$ is equal to the rate of elevation change
 - Iterally solves for debris thickness by inverting the Ostrem curve until the modelled subdebris melt (determined by the iteratively changing debris thickness) agrees with the observed subdebris melt rate based on the elevation change and flux divergence
 - Similar method to [[Ragettli et al., 2015]] - however this study also includes ice flux divergence, accounts for topography, and also quantifies uncertainty.
 - Method deemed the 'Monte-Carlo Østrem inversion method'

![[Pasted image 20241010102220.png]]
- Thickness estimates were compared to two sets of previously conducted field measurments:
	- Debris above exposed ice cliffs [[Nicholson and Benn, 2012]]
	- Ground Penetrating Radar [[Nicholson and Mertes, 2017]]

## Results

**Velocity**:

- Maximum velocity occurs near the transition from clean ice to debris cover.
- Velocity deceases then onwards toward the glacier terminus
	- Ngozumpa Glacier becomes relatively stagnant (<5m/a) ~6.3km from the terminus
	- Khumbu Glacier is 3.7 km
	- Lhtose Shar Glacier is active
	- Imja GLacier 0.75-1.5 km 
- Clusters of higher velocities on the tongues of Ngozumpa and Khumbu Glaciers coincident with ice cliffs and supraglacial ponds

**Flux Divergence and Vertical Velocity**

- Flux divergence for 600-m boxes was calculated using horizontal surface velocity and ice thickness estimates
- Negative flux divergence for all but one box on the debris-coverded portion of the glacier.
- Single positive divergence caused by a bottleneck in the surface velocity

**Debris Thickness**

**Ngozumpa Glacier:**

- Inverse ablation gradient clearly evident - increase in surface lowering upglacier where debris thickness is thinner
- Local maxima in surface lowering are evident over the stagnant part of the tongue where ice cliffs and supraglacial ponds are present
- Debris thickness varies by an order of magnitude and shows a general trend of increasing thickness down-glacier
- 