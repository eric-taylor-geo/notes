2024-10-11 09:16

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology|Glaciology]]

DOI:

URL: https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020GL091311

Tags: [[Glaciology - Debris]] [[Glaciology - Energy Balance Model]] [[Glaciology - Meta Scale]]

Status:
# Distributed Global Debris Thickness Estimates Reveal Debris Significantly Impacts Glacier Mass Balance
[[ed et al., 2012]]

## Abstract

Supraglacial debris affects glacier mass balance as a thin layer enhances surface melting, while a thick layer reduces it. While many glaciers are debris-covered, global glacier models do not account for debris because its thickness is unknown. **We provide the first globally distributed debris thickness estimates using a novel approach combining sub-debris melt and surface temperature inversion methods**. Results are evaluated against observations from 22 glaciers. We find the median global debris thickness is ∼0.15 ± 0.06 m. In all regions, the net effect of accounting for debris is a reduction in sub-debris melt, on average, by 37%, which can impact regional mass balance by up to 0.40 m water equivalent (w.e.) yr-1. We also find recent observations of similar thinning rates over debris-covered and clean ice glacier tongues is primarily due to differences in ice dynamics. Our results demonstrate the importance of accounting for debris in glacier modeling efforts.

Produces the first global debris thickness estimate for the 92,033 debris-covered glaciers in the RGI - excluding ice sheets and Antarctic periphery
Uses estimates to determine the cause of the debris-cover anomaly (see below) and to quantify the the impact of debris on sub-debris melt and mass balance on various spatial scales

… does this just make my diss irrelevant…

## Introduction

- Ostrem …
- Effect is known well at the point scale
- 'Debris-cover anomaly' [[Pellicciotti et al., 2015]] - refers to similar change rates for both debris-covered and clean-ice glaciers in HMA [[Gardelle et al., 2013]] [[Kääb et al., 2012]]
	- Explanations: enhanced melt at ice cliffs and ponds, lower emergence velocities [[Brun et al., 2018]]
- Cites [[Herreid and Pellicciotti, 2020]] [[Scherler et al., 2018]] - debris cover must be accurately measured to quantify the impact of debris on glacier mass balance from local to global scales
- In situ measurements of debris thickness are scarce a limited to glaciers in Europe and HMA - however, these are still typically spatially and/or temporally limited.
- In situ measurements used for:
	- Empirical relationships: [[Kraaijenbrink et al., 2017]] [[Mihalcea et al., 2008a]]
	- Validation of physically-based surface temperature inversion [[Foster et al, 2012]] [[Rounce and McKinney, 2014]]
	- Validation of sub-debris melt inversion [[Rounce et al., 2018]]
- Sub-debris melt inversion method is the only physically-based method that can accurately estimate debris-thicknesses >0.5 m
	- But limitations due to requiring accurate estimates of climatic mass balance which must be derived from in-situ measurements or remotely-sensed elevation change data (difficult - [[Rounce et al., 2018]])
- Surface temperature inversion methods have no spatial limitations but cannot estimate thick debris cover and requires accurately resolving surface energy balance fluxes at the time of image acquisition

## Methods

- Uses sub-debris melt inversion method [[Rounce et al., 2015]] [[Rounce et al., 2018]] to estimate debris thickness over binned near-stagnant debris-covered area
- Surface temperature inversion method then estimates distributed debris thickness over a glacier's entire debris-covered portion using binned debris thickness estimates for calibration
- Extrapolates debris debris coefficients from the nearest calibrated glacier to estimate debris thickness on remaining glaciers

**Sub-debris melt inversion model**

- Debris is located in the ablation area, thus the sub-debris melt can be assumed to be equivalent to the annual climatic mass balance - estimated by elevation change and flux divergence

**Surface temperature inversion method**

- Uses Landsat-8 surface temperature data
- Uses [[Rounce et al., 2015]]

**Modeled Regional Mass Balance**

- Uses Python Glacier Evolution Model (PyGEM) [[Rounce et al., 2020]] to quantify the regional mass balance.
	- Estimates the climatic mass balance using 10 m elevation bins and a monthly time step forced by ERA5 air temperature and precipitation data
	- Glacier melt computed using degree-day model

## Results

- Debris thickness increases towards the termini of glaciers - agrees with [[Anderson and Anderson, 2018]]
- Debris thickness also increases towards the lateral margins, where valley walls provide sources of debris
- Glaciers with medial moraines may have thicker debris in the center of the glacier -> disslink
- Evaluates debris thickness estimates by comparing in situ measurements with the nearest pixel
- Debris thickness uncertainty estimates are comparable to those of in situ vs modelled uncertainty - lends confidence
- Can reproduce thicknesses exceeding 1 m
- Also well estimates thicknesses less than 0.2m, approaching critical thickness
- Global debris volume is 7.3 km3 (4.3 - 12.8)
- Mean debris thickness of 0.35 m (0.21-0.62)
- This is higher than the median since debris thickness is right skewed
![[Pasted image 20241011112840.png]]
**Impact on sub-debris melt**

- Debris enhancement factor: ratio between sub-debris melt and clean-ice melt.
- Spatial variation in debris cover on individual glaciers results in enhanced melt in the uppermost debris-covered portions and limited melting downglacier
- In all regions, the net effect of debris is a reduction in sub-debris melt

**Impact on regional mass balance**

- Net impact depends on the spatial distribution of debris thickness, relative amount of debris-covered ara to total glacier area, and mass balance gradient.
- The latter is essential because glacier termini are where ablation is greatest on clean-ice glaciers

**Debris Cover Anomaly**

- Mixed pixel effect reduce thickness estimates [[Rounce et al., 2018]] and increase enhancement factors
- Enhancements for cliffs and ponds vary from 0.81 to 1.85 - comparable to the factors for thin debris
- "In High Mountain Asia, the mean enhancement factor of 0.64 indicates melt beneath debris-covered areas is, on average, reduced by 36% compared to clean ice. If we assume ice cliffs and ponds have enhancement factors of 0.81–1.85 and comprise 6%–14% of the debris-covered areas (Brun et al., 2018; Herreid & Pellicciotti, 2018; Miles et al., 2018), then enhancement factors for the remaining debris-covered area are 0.44–0.63. We can therefore estimate that enhanced melting due to cliffs and ponds accounts for 3%–35% (0.01–0.20 of the 0.37–0.56 reduction) of the debris cover anomaly and attribute the remaining 65%–97% to reduced emergence velocities over debris-covered areas compared to clean ice. Hence, less ice flux into the slow-moving, debris-covered portion of the glacier is the dominant cause of the debris cover anomaly in High Mountain Asia."

## Conclusions

- First global assessment for debris thickness
- Debris thickness variation causes glacier tongues to have an inverted ablation gradient - consistent with previous studies - greatest ablation near the ELA
- Causes glaciers to stagnate and develop supra/pro glacial lakes - hazard
- 
