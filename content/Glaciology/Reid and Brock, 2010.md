2024-09-06 10:21

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology]]

DOI:

URL:

Tags: [[Glaciology - Energy Balance Model]] [[Glaciology - Debris]] [[Glaciology - Model]]

Status: #read-detailed 
#  An energy-balance model for debris-covered glaciers including heat conduction through the debris layer

Paper presents a physically based energy-balance model for the surface of a debris-covered glacier  - developed using data collected at Miage glacier, Italy, during the ablation seasons of 2005, 2006, and 2007.

Essential to assess exactly how debris cover affects glacier melt rates.

Debris surface temperature is estimated by considering the balance of heat fluxes at the air/debris interface, and heat conduction through the debris is calculated in order to estimate melt rates at the debris/ice interface.

Model can be used to reproduce observed changes in melt rates below debris layers of varying types and thicknesses – an important consideration for the overall mass balance of debris-covered glaciers.

**Introduction:**

Glacier ablation zones are covered in near-continuous blankets of rock debris
Debris-covered glaciers are important components of the water cycle in many mountain regions (e.g., headwaters of the Ganges and Indus rivers)

-              Debris layers have significant impact on glacier thermodynamics ([[Brock et al., 2010]]) -> therefore, crucial to be able to accurately assess how debris presence affects glacial responses to atmospheric changes.

-              Lots of studies investigating surface energy balance on clean glaciers, there is a lack of models (in 2010) that analyse the processes that influence debris-covered snow and ice.

-              Paper presents a one-dimensional melt-model – Debris Energy-Balance Model (DEB) for a debris covered glaciers.

-              How:

-              Calculates surface temperatures and melt rates similar to measurements taken at the rock-debris-covered Miage glacier, Italy, and a tephra-covered glacier on Villarrica volcano Chile, for various values of debris thickness.

-              Uses meteorological variables and specified debris thermal properties.

-              Presents theoretical discussion on how this model can replicate the ‘Østrem curve” (Østrem, 1959) – thin debris enhances melt, whilst thicker debris reduces melt – relationship between albedo and insulation.

**Data used for modelling:**

-              Variables used are:


-              Data collected for these variables from Miage glacier, Italy in the ablation seasons in 2005, 2006, and 2007.

**Energy balance models:**

-              Energy-Balance Models (EMBs) have been developed for:

-              Debris-covered glacers (e.g., Nakawo and Youg, 1981; Nicholson and Benn, 2006)

-              Clean glaciers (e.g., Hay and Fitzharris, 1988; Arnold _et al_., 1996; Brock and Arnold, 2000; Klok and Oerlemans, 2002; Pelliciotti _et al_., 2008) using a general form determined by the sum of fluxes at the atmosphere/glacier boundary

![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image003.png)

-              M: energy available for melt

-              S: solar shortwave radiation

-              L: Net longwave radiation

-              H: sensible heat transfer

-              LE: Latent heat transfer

-              P: heat flux due to preciptation

-              G: conductive heat flux below the surface

-              Limits:

-              flux calculations depend on quantities such as surface temperature, surface humidity, and internal debris temperatures which are not regularly measured on or neat glacier sites.

-              Such variables are not predicted to sufficiently high resolution by global or regional-scale climate models to infer future projections of glacial activity.

-              Due to these limitations, many models have used degree day models (e.g., Mihalcea _et al_., 2006) that rely upon simple empirical correlations between air temperature and melt.

-              Other studies use enhanced temperature index (ETI) models that use a regression of melt rate with air temperature and solar radiation (Pellicciotti _et al_., 2005)

-              But -> Pellicciotti _et al_. (2008) identify that ETI models are limited by being calibrated from specific climatic and topographic conditions that cannot necessarily be applied to different glacial regions – this limitation becomes exacerbated when considering debris-covered glaciers due to further variations in thickness, structure, lithology.

-              _Link to Ostrem (1959)_

-              Model accuracy can be further tested by comparing short-term performance with high-resolution data using  ‘models that are as generalizable as an EBM but require fewer input variables and parameters’

-              Paper identifies:

-              Debris surface temperature Ts

-              Internal debris temperatures Td

-              As useful variables (_duh?_)

-              They are treated as unknowns that are calculated alongside heat fluxes -> presents a circularity problems as Ts and Td not only depend on the surface fluxes, but are also required for the calculation of surface fluxes -> solved using numerical algorithms.

![A diagram of a heat wave
Description automatically generated](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image004.png)

**Debris surface temperature:**

-              Air/debris interface temperature Ts is considered to change on every time-step to a temperature which will cause the sum of the heat fuxes at the deris surface to be zero – to obey laws of conservation of energy.

-              Given that some fluxes are functions of Ts, and some are not, the energy balance can be expressed as:

![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image006.png)

Or simply:

![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image008.png)

-              To calculate the next time step, authors use the Newton-Raphson method: **WHY**

![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image010.png)

-              Where, F’(Ts) is the derivative of the total surface flux with respect to Ts.

-              An initial guess of Ts(n=0) must be made – for the first step it was set to air temperature.

-              Iterative formular is repeated until |Ts(n+1) – Ts(n)|< 0.01

**Debris internal temperatures**

-              Flux of subsurface heat conduction is can be significant when there is a non-zero gradient of temperature with depth, or when solar shortwave flux penetrates into the snow/ice.

-              Conduction can be calculated from a heat-conservation equation:

![A mathematical equation with numbers and symbols
Description automatically generated](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image011.png)

-              ρi,s, c i,s and k bs are, respectively, the density, specific heat capacity and thermal conductivity of the ice or snow.

-              First right-hand term represents heat conduction, second term accounts for radiative fluxes, Q, penetrating into an ice or snow layer from above.

-              Making the assumption that no radiative fluxes penetrate through rock, ∂Q/∂z can be ignored.

![A mathematical equation with numbers and symbols
Description automatically generated](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image012.png)

-              Equation is solved by dividing the debris layer into several calculation layers and applying a numerical algorithm with boundary conditions defined by the surface temperature and the temperature at the debris base which is assumed to remain at the melting point of ice – justified by measurements.

-              The number of calculation layers, N, is chosen so that the model calculates temperatures are 1 cm layers.

-              See appendix for full method

**Surface heat fluxes**

-              Brock _et al_., (2010) present equations for the heat fluxes on the surface of Miage glacier.

-              Paper uses the same equations with some modifications.

-              Convention that positive fluxes are directed towards the debris surface.

![A table of numbers and symbols
Description automatically generated](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image013.gif)

‘Constants’ used in the DEB model, which are well known and should not change significantly across different sites, and ‘parameters’, which may vary across different sites. Default parameter values are given for Miage glacier and Villarrica. All parameter values are based on values given by Brock and others (2007, 2010), unless otherwise stated in the text

**Solar shortwave radiation:**

-              Can either use S in – S our S = (1-albedo)S.

**Longwave radiation:**

-              Incoming supplied to the DEB model from data – but can be simulated for future applications

-              Upwelling longwave radiation is calculated from the Stefan-Boltzmann law:

![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image015.png)

-       Where ![](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image017.png) is the debris surface emissivity,

…. Read if usefl

**Overall model structure:**

![A flowchart of a algorithm
Description automatically generated](file:////Users/erictaylor/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image018.gif)

**Bare Ice model:**

-              To quantify the effects of debris on ablation, a bare-ice model was developed for comparison with the DEB model.