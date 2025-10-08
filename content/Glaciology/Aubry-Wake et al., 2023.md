2024-09-21 12:45

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology|Glaciology]]

DOI:

URL: https://www.cambridge.org/core/journals/journal-of-glaciology/article/using-groundbased-thermal-imagery-to-estimate-debris-thickness-over-glacial-ice-fieldwork-considerations-to-improve-the-effectiveness/1995C93BE7A6C18DBE4A0586D6E09AEC

Tags: [[Glaciology - Debris]] [[Glaciology - Energy Balance Model]]

Status: #unread 
# Using ground-based thermal imagery to estimate debris thickness over glacial ice: fieldwork considerations to improve the effectiveness

## Abstract

- Paper examines the potential to estimate debris thickness through using ground based thermal infrared radiometry (TIR)
- 4 day measurement period in August 2019
- 44 manual excavations of debris thickness - varies between 10 and 110 cm
- Regression models for inferred debris thickness from surface temperature - optimal performance had an R^2 of 0.7 and a root mean square error of 10.3cm
- Optimal performance when the model was applied to measurements taken on clear nights before sunrise - model still performs well under complete cloud cover when an exponential model is used

## Introduction

- Rock debris on 44% of world's glaciers [[Herreid and Pellicciotti, 2020]]
- Modulating sub-debris ice melt … bla bla [[Østrem, 1959]] [[Nicholson and Benn, 2006]]
- Thickness generally increases towards terminus [[Anderson and Anderson, 2018]] (also [[Nicholson and Benn, 2013]])
- However, strong scale variability [[Nicholson and Benn, 2013]] [[Nicholson et al., 2018]]
- Manual excavations to capture small scale variability are time and labor intensive - can result in a risk of bias in results 

- Due to the difficulties in gathering field-based thicknesses, different methods have been employed to estimate thickness from remotely sensed observations (e.g., satellite-derived surface temperatures) (e.g. [[Rounce and McKinney, 2014]])
- Two methods in deriving thickness from surface temperatures

**Empirical**

- Uncertainties remain regarding the best form of empirical relationship - linear or exponential 
- Linear papers: [[Mihalcea et al., 2008a]]
- Exponential: [[Mihalcea et al., 2008b]] [[Tarca and Guglielmin, 2022]]
- Appeals due to its simplicity and ow amount of required data
- However limited because performance is strongly dependent upon the availability of well-distributed input data that that represents the full range of debris thicknesses and surface temperature [[Boxall et al., 2021]]

**Physically-based Energy-Balance Model**

- Examples: [[Foster et al, 2012]] [[Rounce and McKinney, 2014]] [[Schauwecker et al., 2015]] [[Rounce et al., 2018]] [[Stewart et al., 2021]]
- Challenge is to obtain reliable metertological data to accurately quantify the energy fluxes at the debris surface [[Foster et al, 2012]] [[Rounce and McKinney, 2014]] [[Rounce et al., 2015]]
- Difficulties in obtaining other variables such as debris properties, albedo, thermal resistance, roughness, etc. have to be estimated across the glacier area and add further uncertainty to the methods

- Both methods only provide accurate debris-thickness estimates for debris less than 0.5 m in thickness
- Beyond this threshold, a decoupling of surface temperature and debris thickness occurs
	- [[Mihalcea et al., 2008a]] [[Foster et al, 2012]] [[Tarca and Guglielmin, 2022]]
- [[Rounce et al., 2018]] and [[Rounce et al., 2021]] address this limitation and managed to obtain robust estimates for debris greater than 0.5 m thick by combining an inverted sub-debris melt model with calculations of elevation change and flux divergence
	- *Diss* maybe can try this for my diss?
	- Requires a series of digital elevation models and surface velocity data as well as meteorological data and debris parameters
	- Thus is still hampered by the same limitations with data and parameter availability and uncertainty 

- Satellite derived surface temperature is limited by its poor spatial resolution (usually 60 - 100 m) [[Rounce et al., 2013]]
	- Local slope and aspect variations are lost as well as debris, ice cliffs, supraglacial ponds
	- Debris is known to vary significantly over 10s of meters [[Nicholson and Benn, 2013]]
	- Can result in an underestimation of debris thickness [[Rounce et al., 2018]] [[Herreid, 2021]]
	- This underestimation when inputted into melt models can underestimate ablation by 11-30% [[Nicholson et al., 2018]]
		- *But if underestimating debris thickness, surely this overestimates melt predications ? - need to read paper*

- Instead, near-surface remote sensing can be employed to gather high spatial resolution thermal imagery
- Plane or uncrewed arial vehicles: [[Kraaijenbring et al., 2018]]
- Ground-based oblique imagery: [[Hopkinson et al., 2010]] [[Aurby-Wake et al., 2015]] [[Herreid, 2021]] [[Tarca and Guglielmin, 2022]]
- The increased flexibility of measurements (no longer reliant upon photos taken once per orbital cycle) allows for assessments of when and how surface temperature should be measured to optimise debris thickness estimates
- [[Herreid, 2021]] suggests that weather conditions play a key role 
	- Clear days are the least suitable and cloud cover provides optimal conditions
	- ***Thus, eliminating satellite-based remote sensing methods due to not being able to measure ground temperature through cloud cover*** - we can only see clear days - but these are said to be bad :((

 Paper investigates:
 
> - Empirical regression type
> - Time of day of TIR image acquisition
> - Weather conditions
> - Number and depth distribution of manual debris thickness measurments
> - Spatial resolution of images
> - Distance between ROI and the TIR camera

…

## Results and Discussion

![[Pasted image 20240925161325.png]]
![[Pasted image 20240925161420.png]]
## Conclusions

- 1478 thermal-infrared images between 5-9 August 2019
- 44 moraine excavations
- "Using 44 debris thickness measurements ranging from five to 110 cm, a linear and exponential regression model between debris thickness and surface temperature was generated for each image. A pattern emerged, where an exponential model provided better performance than the linear model throughout the day, but the linear model performed better than the exponential model for a short period in late-night conditions, reaching _R_ 2 values of 0.71 and nRMSE of 0.13 cm. Based on these results, the most reliable times to obtain surface temperatures that correlate well to debris thickness are from late at night to just before sunrise under clear conditions or any time of the day or night under cloudy conditions."