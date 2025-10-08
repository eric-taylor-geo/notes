2025-01-24 12:19


Paper: [[II - Atmospherics]]

DOI:

URL: https://www.ecmwf.int/sites/default/files/elibrary/2015/11061-impact-satellite-data-nwp.pdf?utm_source=chatgpt.com

Tags: [[Atmospherics - Sattelites]]

Status:
# The impact of satellite data on NWP

## Introduction

- Modern data assimilation systems are highly complex and can extract atmospheric information from a wide variety of different observations.
- Important to regularly assess and understand the relative contribution of each component because:
	- Impact of observations may change over time depending on the model / data assimilation evolution and the availability of new data
	- Important to explore the resilence and redundancy to optimise the use of resources
	- Useful for the long term planning of the global observing system.
- Quantification of the observation impact has become a necessity to justify the enormous costs of developing, building, and launching satellite instruments

## Factors influencing forecast impact

**Measurement quality:**

- Satellites observe radiation at the top of the atmosphere - poor (noisy) detectors, poor radiometric calibration, and spectral calibration result in bad data
- Poor data can still have a limited positive impact on data assimilation if assimilation accurately characterises its error characteristics

**Measured quantity**

- Even if an instrument accurately measures radiation at the TOA, it may still be difficult to extract useful atmospheric information from these data.
- A radiance observation that is sensitive to various atmospheric phenomena requires intense retrieval mechanisms (e.g., discussed in [[Satellite Meteorology Chapter 6 - Temperature and Trace Gases]] ) 
- A more simpler observation may be more useful here.
- E.g., extracting temperature information from infrared radiances (that are highly sensitive to clouds and atmospheric composition) is significantly harder than extracting the same information from microwave radiances (which are much less sensitive to interfering phenomena)

**Spatial coverage and time**

- The observing system has limited spatial coverage due to:
	- Orbit cycle / scanning instrument type
	- Unuseable data (e..g, due to cloud cover)
- Affects the impact on the forecasting system
- NWP centres now employ four-dimensional assimilation schemes where the time that the observations are made may have a strong influence on their impact
- E.g., observations made nearer the end of the observation window may have a stronger influence on the output than those near the beginning
- Forecast model can evolve numerous atmospheric variables over time to fit the data at the end of the window

**Tuning of assimilation system:**

- The weighing of variables affects their contribution to the model.

## Evaluating forecast impact

- Observing System Experiments (OSE) used where forecasts using all available observations are compared against those with the observation of interest deliberately withheld
- Computationally expensive to run

## Assessment of current satellite impact on NWP forecasts

- The study uses OSE using the latest version of ECMWF in a period over spring 2014
- Satellite data is crucial for NWP in the Southern Hemisphere, where in situ observations are sparse - indeed, removing in situ observations from the model results in a negligible difference.
- In situ data is more influential in the Northern Hemisphere, especially in the short range. But overall, forecast skill is still dominated by the collective impact of satellites.

## Conclusions

- Many factors influence the impact of a particular satellite observation on reducing forecast errors
- Clear findings:
	- The simultaneous loss of all satellite data results in a catastrophic loss of forecast skill in both hemispheres and is much more damaging than the removal of all in situ (conventional) observations.
	- However, there is high degree of resilience in the satellite network such that when just one component is removed the others compensate and there is only a modest loss of forecast skill (compared to removing all satellites).
	- Individual OSE denials indicate that microwave and infrared sounding radiances are the main drivers of headline forecast skill, but other sensors (GEO and MWI) have impacts on specific parameters (wind and boundary layer humidity respectively) in the short range (but reliable verification is an issue). However, in the medium range MW and IR sounding dominate the forecasting of even these parameters presumably by constraining the larger scales.
		- GEO: mainly used for constraining wind field through atmospheric motion vectors or by dynamical tracing of humidity sensitive radiances in the upper troposphere
	- GPS-RO observations have a strong constraining effect limiting the growth of systematic temperature errors in the lower stratosphere. They are the only observations assimilated with no bias correction and thus represent a crucial anchor on mean errors.


