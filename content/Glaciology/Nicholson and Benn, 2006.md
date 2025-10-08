2024-09-24 17:04

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology|Glaciology]]

DOI:

URL: https://www.cambridge.org/core/journals/journal-of-glaciology/article/calculating-ice-melt-beneath-a-debris-layer-using-meteorological-data/D1B92BB2343D00A47624864454748B5F

Tags:  [[Glaciology - Debris]] 

Status:
# Calculating ice melt beneath a debris layer using meteorological data

## Abstract

- Numerical models of sub-debris ice ablation are generally preferable to empirical approaches to predicting runoff
- Model presents a modified surface energy-balance model to calculate melt beneath a surface debris-layer from daily mean meteorological variables
- Performs well and modelled melt rates match well to observed melt rates
- Builds on previous models which were inappropriate for thick debris cover

Ostrem curves:

![[Pasted image 20240924171508.png]]

## Previous Work

- Melt rate can be calculated as:
$$
M = \frac{Q_m}{ρ_iL_f}
$$
>Q is the energy flux at the base of the layer
>L is the latent heat of fusion

- Energy flux is dominated by vertical temperature gradient (rather than horizontal) - Q is given by:
$$
Q_c = k\frac{dT}{dZ}
$$
- Assuming the gradient between the upper and lower surfaces is linear, this can be written as:
$$
Q_c = k\frac{(T_s-T_i)}{h_d}
$$
>K is the thermal conductivity ($W m^{-1} K^{-1}$)

- The simplification rests on the assumption that the debris layer is in thermal equilibrium - the heat stored in the layer is constant over time and that Q at the debris surface is the same as at the ice interface (is linear)
- Solution of above equation requires knowledge of the surface temperature which can be difficult to obtain
- E.g., [[Kayastha et al., 2000]] measured ablation below 7 sites on Khumbu Glacier bur only had a single site where surface temperature was measured *(surely just add this to the methodology now you know this in hindsight ?*
	- The use of thermal bands from satellite data has been proposed [[Nakawo and Rana, 1999]] - however this is limited for it only yields instantaneous temperatures which cannot be applied over long timescales [[Conway and Rasmussen, 2000]]
		- *I don't understand this; surely a single measurement from in situ would be the same?* - *but I guess satellites will measure once every e.g., 16 days (landsat 7) whilst in situ could take various over a single day - I think that's the point they're making*
- [[Nakawo and Young, 1981]] calculate daytime and night-time ablation using meteorological data and assuming a steady state was attained over these timescales
	- Using meteorological data also allowed for the circumvention of knowing the surface temperature by using the data to solve an equilibrium surface-energy balance equation
	- However, data from vertical temperature profiles through supraglacial debris show that this assumption is not valid [[Nicholson, 2004]]
	- Nakawo and Young's results over predict night melt rates and under predict day melt rates
	- Over prediction of melt because the assumption of an instantaneous linear temperature gradient does not account for the inversion in the temperature gradient (at least in the near subsurface) which results in a heat flux towards the debris surface rather than downwards towards the ice [[Kayastha et al., 2000]]
	- Thus, authors recommend a timescale using a timescale of at least 24 hours over which to employ the heat-flux model (above equation)

![[Pasted image 20240924173430.png]]
## Modelling ablation beneath a debris layer

- Method for calculating sub-debris melt using diurnally averaged meteorological data
… article  …

- All independent variables are 24 hour means
- **Temperature at the ice-debris interface is assumed constant at 0ºC**

## Discussion

- Model provides a good match to published Østrem curves from empirical measurements, displaying an asymptotic decline in melt with increasing debris thickness
- However the model does not mimic the rising limb up until the critical thickness - rather it predicts falling melt rates from an infinitesimally thin debris layer
- In reality, light debris consists of scattered particles of debris [[Adhikari et al., 2000]] - in this case, the surface albedo is a function of the proportion of the surface that is debris-covered and may account for the observed rising limb up until a critical threshold is reached.
	- Within the model this can be simulated by varying surface albedo up until a specified minimum thickness for continuous cover

- At Ghiacciao del Belvedere, the energy fluxes over bare ice are all positive with the largest flux being sensible heat.
- Where there is debris cover, the largest flux is shortwave radiation which occurs in response to lower albedo and higher debris-surface temperatures
- Longwave radiation also becomes negative when there is debris cover (even thin)
- Under wet debris conditions, longwave flux is less negative - debris surface is cooled by latent-heat losses

- 1 cm debris cover reduces the energy flux available for melt by 33% if the debris is dry, and by 11% if the debris is wet
- while at Larsbreen the same debris thickness reduces the energy flux available for melt by only 17% where debris is dry, and increases the energy flux by 2% where wet, in comparison to clean ice
- **These contrasts are more strongly controlled by differences in the meteorological conditions than contrasting debris properties at the two glaciers**

## Conclusions

- Model assumes that the daily mean temperature gradient is linear and that there is a negligible net change in heat storage on diurnal scales
	- These assumptions are valid for summer conditions at the study sites
- **The assumption that the underlying ice is at the melting point is valid for temperate glaciers in summer, but may yield erroneous results for polythermal glaciers or on all glaciers in early spring before the near-surface ice cooled during the winter is raised to the melting point**

