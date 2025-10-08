# Useful stats:

### Greenland:

-  Total sea level potential of the Greenland Ice Sheet is 7.42 ± 0.05 m ([[Morlighem et al., 2017]])
-  Between **1992** and **2018**, the Greenland Ice Sheet lost more ice through ablation than it gained through accumulation, losing **3.9 trillion tonnes** of ice in total at an average rate of **150 Gt** per year ([[IMBIE, 2020]])
- During this period, the rate of ice loss from the Greenland Ice Sheet increased **7-fold**, rising from **34 Gt per year** in the 1990s to **234 Gt** per year in the 2010s ([[IMBIE, 2020]]).
- During 2011–2014, Greenland mass loss averaged 269 ± 51 Gt yr-1, contributing 0.74 ± 0.14 mm/yr to SLR ([[McMillan et al., 2016]])
- Mass loss shows high inter-annual variation - melt events in 2012 and 2019 were >400 Gt, whilst 2024 the net mass loss was the lowest since 2013 - 55 ± 35 Gt ([[Poinar et al., 2024]])

### Antarctica:

- East Antarctic Ice Sheet holds 52 m of SLR equivalent ([[Fretwell et al., 2013]])
- West Antarctic Ice Sheet holds 5.4 m of SLR equivalent ([[Fretwell et al., 2013]])
- Total is 58 m ([[Pritchard et al., 2025]])
- West Antarctic Ice Sheet currently dominates mass loss, with a net mass loss at a rate of 159 ± 26 Gt a-1 ([[Shepherd et al., 2018]]) between 2005-2010
- Lost 2,720 ± 1,390 billion tonnes of ice between 1992 and 2017 ([[Shepherd et al., 2018]])
- East Antarctica covers 73% of Antarctica's land mass - 10.2 million km2
- Total Antarctic Ice Sheet is losing mass at 109 ± 56 Gt yr-1
- Future simulations for Antarctic mass balance project mass losses of up to 150 cm sea level equivalent per year by 2100 (IPCC, 2021)

- Divide by 361 to get Gt to SLR in mm

# Ice Sheet Mass Balance

- The mass balance is the net difference between ice gains through snowfall, and ice losses through melting at its surface or underneath its floating ice tongues, and through the calving of icebergs from glaciers flowing into the ocean.
	- We can consider two separate components which contribute to total mass balance: surface mass balance, and ice dynamics

**Greenland:**
- Present mass loss from the Greenland Ice Sheet is roughly equally distributed between increased summer surface melt and an accelerated flux to the ocean from marine-terminating glaciers ([[van den Broeke et al., 2017]])
- Ice discharge from marine-terminating glaciers has increased ([[Enderlin et al., 2014]]). However, the acceleration in ice losses has been primarily driven by increased runoff due to atmospheric warming ([[Hanna et al., 2012]]).
- Atmospheric warming is intensifying surface melt and causing it to expand spatially to higher elevations ([[Gagliardini and Werder, 2018]]).
- Mass balance deviated from its natural range of variability during the 1980s and has remained persistently negative since the early 1990s ([[IMBIE, 2020]]).

**Antaractica:**
- Mass loss is dominated by discharge, and surface melt is low.
- Mass loss is dominated by dynamic losses in the WAIS - 159 ± 26 Gt yr-1 ([[Shepherd et al., 2018]])
### Assessing mass balance

- Remote sensing methods are the only plausible methods of measuring ice sheet's mass balance.
- Satellites provide repeat observations and full coverage over the polar ice sheets.
- Satellites launched by the European Space Agency and NASA have continuously monitored the ice sheets since the 1990s and allow scientists to measure mass balance.
- Three main methods are used: (categorised according to lecture notes and previous exam questions):
1. **Mass-budget accounting**: compares mass gain (snowfall) with mass losses (sublimation / evaporation, meltwater runoff, ice flux to the ocean)
2. **Altimetry**: reveals changes in ice sheet volume through measuring the height of the surface, which can be related to mass through the density of the ice lost or gained ([[Simonsen et al., 2021]])
3. **Gravitimetry**: measures changes in ice mass through changes in Earth's gravitational field ([[Velicogna et al., 2020]])

#### *In situ* validation data

- *In situ* measurements are required to validate model outputs.
- Bales et al. ([[Bales et al., 2009|2009]]) presented the first unified measurements across Greenland between 1950 and 2000, using 300 shallow ice cores and snow pits, as well as data from 20 coastal weather stations.
- Van de Wal et al. ([[Van de Wal et al., 2012|2012]]) measure annual accumulation, melt, and runoff along a transect near Kangerlussuaq (K-transect) - 21 year record along 67 degrees N, spanning elevations from 390-1850 m asl.
	- Mean mass balance gradient over elevations: **3.8 mm w.e. yr-1 m−1**
	- Over the study period, the surface mass balance became more negative and the mean mass balance gradient became steeper.
#### Mass-budget (input / output) accounting

- Quantifies the difference between the surface mass balance and ice discharge at the grounding line ([[van den Broeke et al., 2009]]).
$$
\text{MB} = \frac{\partial M}{\partial t} = \text{SMB} - \text{D}
$$
- Method provides estimates of SMB and discharge separately at individual glacier drainage basins ([[van den Broeke et al., 2009]]).
##### Mass balance modelling

- Use Global Climate Model (GCM) outputs as an input into a surface energy balance model.
- GCM's resolution is typically hundreds of km. These are typically statistically downscaled to a finer resolution (10-30 km2; [[Khan et al., 2015]]) using various physical assumptions, for example, environmental lapse rates and precipitation gradients.
- GCMs then force a regional climate model which is then used to calculate the surface mass balance using energy balance models.

######  Study examples:

**[[Hanna et al., 2011]] Greenland:**
- Use reanalysis climate data to force a degree day model for Greenland between 1870 and 2010 and find a steady decline in mass balance.

**[[Enderlin et al., 2014]] - An improved mass budget for the Greenland ice sheet**:

- Findings provide observational support to recent model predictions that SMB, not discharge, is the primary driver of Greenland Ice Sheet mass loss on decadal and greater time scales
- Why:
	- Outlet glacier acceleration (which increases discharge) has not been sustained over large regions, and their accelerations are short-lived and uneven.
	- Dynamic ice thinning due to surface melt acts to reduce discharge, and this effect becomes substantial over time periods of several years; thus, a sustained increase in discharge is only possible if glaciers continue to accelerate.
		- A more negative SMB acts to reduce discharge by removing more ice before it reaches the margin ([[Goelzer et al., 2013]])
- The acceleration in SMB loss is greater than that of ice sheet discharge.
-  The relative contribution of ice discharge to total loss decreased from 58% before 2005 to 32% between 2009 and 2012. As such, 84% of the increase in mass loss after 2009 was due to increased surface runoff.


##### Ice discharge modelling

- Ice velocity and ice thickness are required to estimate ice discharge.
- However, often no measurment of ice thickness at the glacier grounding line is available, and therefore it is estimated using the closest known ice flux ([[Khan et al., 2015]]; [[Enderlin et al., 2014]])
- Ice velocity can be derived from using Interferometric Synthetic Aperture Radar (InSAR) imagery from satellites, which has good agreement with GPS data ([[Joughin, 2002]])
- Feature tracking using optical satellite imagery is also possible.
- Out of the two components, the greatest uncertainty in ice discharge modelling stems from uncertainty in ice thickness.
	- Ice thickness is derived using airborne radio echo sounding ([[Morlighem et al., 2017]])
	- Ice thickness is estimated for the entire ice sheet from ice-penetrating radar measurements - West/North-West Greenland coast is best covered. Less coverage in the interior. 
	- High uncertainty remains in areas with few measurements.
	- The uncertainty in ice thickness has implications for assessing the rate of surface thinning - whilst many glaciers along the coast have been thinning, the cumulative amount of thinning remains less than the uncertainty in radar-derived ice thickness measurement (∼50 m) except in coastal regions that experience strong thinning ([[Morlighem et al., 2017]]).
	- Morlighem et al. (2017) has improved upon previous estimates of ice thickness by using a mass conservation scheme which incorporates surface velocity measurements and radar measurements of the bed ([[Morlighem et al., 2014]])
- Rignot and Kanagaratnam ([[Rignot and Kanagaratnam, 2006|2006]]) find that ice discharge is accelerating and expanding further north.

- It's important to constrain the geothermal heat flux, which controls basal melting and thus, sliding.
- The uncertainty of ice discharge from the Northeast Greenland Ice Stream to the ocean due to uncertainties in the geothermal heat flux is estimated at 2.10 Gt yr-1 ([[Smith-Johnsen et al., 2019]])
- This is important because paleogeological data from ice cores show that the Northeast Greenland Ice Stream played a significant role in the thinning of the Greenland Ice Sheet during the early Holocene ([[Tabone et al., 2024]]).
- Models show that fast ice stream flow caused by transiently imposed reduced basal shear stress following northeast retreat explains 55 ± 18% of Greenland's estimated ice thinning ([[Tabone et al., 2024]]).

#### Altimetry

- Surface elevation changes are calculated from both satellite and airborne altimetry measurements.
- Geoscience Laser Altimeter System (GLAS) instrument on ICESat
- ICESat provided measurements between 2003 and 2009. ICESat-2 was launched in 2018.
- Elevation changes will not solely be due to melt - but are also controlled by: (expanded upon below)
	- Firn Compaction
	- Elastic uplift of the bedrock
	- Glacial isostatic adjustment

##### Study examples:

**[[McMillan et al., 2016]] - A high-resolution record of Greenland mass balance:**

- Use high spatial (5km) and temporal resolution (monthly) CryoSat-2 altimetry
- During 2011–2014, Greenland mass loss averaged 269 ± 51 Gt/yr. Atmospherically driven losses were widespread, with surface melt variability driving large fluctuations in the annual mass deficit
- Consider the July 2012 unprecedented surface melt event. The melt event changed the snowpack's radar scattering properties, affecting its radar-derived surface elevation which has to be corrected for.
- The melt event is the single largest annual ice deficit of 432 ± 62 Gt - accounting for more than 40% of the total mass loss during the 4-year study - highlights how brief but intense melt events can dominate multi-year mass balance trends and the vulnerability of ice sheets to short-lived climate anomalies.
- Terminus regions of five dynamically thinning glaciers, which constitute less than 1% of Greenland's area, contributed more than 12% of the net ice loss.
- Glaciers are:
	- **Kangerdlugssuaq Glacier** (southeast Greenland)
	- **Jacobshavn Isbræ** (west Greenland)
	- **Upernavik Isstrøm** (northwest Greenland)
	- **Steenstrup Glacier** (west Greenland)
	- **Zachariae Isstrøm** (northeast Greenland)
- These glaciers have accelerated significantly in recent decade, increasing ice discharge and thus, mass loss from their termini - thus mass is being lost through through ice dynamics, not surface melting.
- This high-resolution record demonstrates that mass deficits extending over small spatial and temporal scales have made a relatively large contribution to recent ice sheet imbalance.

**[[Zwally et al., 2015]] - Antarctica:**

- Data from ICESat shows that mass gains from snow accumulation on the Antarctic ice sheet exceed discharge losses by 82 ± 25 Gt year-1 , resulting in a reduction in global sea-level rise by 0.22 mm year-1
- Mass loss from West Antarctic Ice Sheet and Antarctic Peninsula
- Finds that East Antarctica's snow depth is increasing at a rate of 1.59 cm year

Disagreement:

- Zwally et al. ([[Zwally et al., 2015|2015]]) is "clearly an outlier among recent studies of Antarctic mass balance" ([[Scambos and Shuman, 2016]])
- Argue that the declining energy of the GLAS on the ICESat satellite has caused brighter surfaces to appear to have an increased elevation under the same albedo and atmospheric conditions, thus resulting in an overestimate of surface elevation increases.
- Even after correction algorithms were put in place, over the mission life span, an apparent increase of 1 cm yr-1 is still observed - whilst the error is small, extrapolated of the 10 million square km of the East Antarctic Ice Sheet, this results in an overestimation of accumulation by 45 Gt year-1 ([[Scambos and Shuman, 2016]])
- This highlights the sensitivity of mass balance estimates over the entire ice sheet to small uncertainties in measurements, whether they stem from assumptions about firn density, estimates of accumulation from regional climate models, or the calibration of satellite sensors.
- Accumulation rates in Antarctica are one of the largest sources of uncertainty regarding mass balance estimates due to the lack of *in situ* measurements ([[Shepherd et al., 2018]])
- Indeed, for East Antarctica, the mass balance is 5 ± 46 Gt year-1 ([[Shepherd et al., 2018]]).

##### Firn Compaction
- Firn compaction will result in overestimates of mass loss if calculated purely from elevation changes.
- Correcting for firn compaction requires subtracting a volume from the total estimated volume change. This volume is calculated using models which are forced by annual temperature, accumulation, melt, and refreezing (e.g., BOX, RACMO2) [[(Khan et al., 2014)]].
- Converting the change in ice volume (surface area * measured height change) requires assumptions about the ice's density - a spatial density model is used to convert the volume change to mass change, according to a known distribution of surface mass balance and ice dynamic processes, including the modelling of firn density

##### Elastic uplift
- Elastic uplift of the bedrock due to present-day mass changes will result in underestimates in mass loss if calculated purely from elevation changes. Models of vertical bedrock deformation are used (e.g, [[Dziewondski and Anderson, 1981]]).
- The rates of the correction due to elastic uplift converted to ice volume have increased from 3.6 km3 yr-1 between 2003-2006 to 9.9 km3 yr-1 between 2009-2012 ([[Khan et al., 2015]]) - likely due to increased mass loss resulting in more elastic uplift.

##### GIA

- Ice surface elevation changes must be corrected for the viscous response of the lithosphere to past glacial history - rates of uplift are slow, and Khan et al. ([[Khan et al., 2015|2015]]) obtain an ice-sheet-wide GIA correction, converted to ice volume, of -0.1 km3 yr-1.
- However, this correction is spatially heterogeneous. Indeed, not all areas of Greenland are uplifting in response to deglaciation ([[Wake et al., 2016]]).

From [[Wake et al., 2016]]: Glacial Isostatic Adjustment (GIA) in Greenland: a Review

- Uncertainties between models not only stem from their models of the Earth's crustal dynamics, but also from their differences in the timing and magnitude of early Holocene deglaciation. 
- The contribution of GIA to GRACE estimates of mass imbalance is becoming increasingly insignificant for large areas of Greenland as it enters a period of extreme warmth, and in total represents <5 % contribution (−6 to +10 Gt/year) to the observed Greenland-wide mass trends over the last decade - although small, it still remains an important quantity to constrain further in specific areas of Greenland.

- Three highlight areas useful for essays:
	1. South-west Greenland: discrepancies due to uncertainty in the timing and magnitude of early Holocene deglaciation. 
	2. north-West Greenland: is in fact, subsiding rather than sinking
	3. north-East Greenland: total mass loss is relatively small, therefore, even modest errors in GIA can contribute to a large percentage of the inferred signal

- **South-west Greenland** has a large discrepancy between different models (e.g., Huy3, ICE_6G_C; [[Lecavalier et al., 2014]]; [[Peltier et al., 2015]]), where estimates of uplift vary by ~6mm per year due to their different constraints on ice sheet retreat - Huy3 uses a large quantify of geological observations to constrain its deglacial history in the region and predicts a lingering ice margin between 7 and 4 kya. Reviews of lake sediments agree with this assessment ([[Larsen et al., 2015]]).
- **North-west Greenland**, between AASI and THU2, is subsiding because during the LGM, the Laurentide Ice Sheet's immense mass depressed the crust beneath it causing the surrounding area to forebulge. Since the loss of the Laurentide Ice Sheet, the forebulge is collapsing, causing subsidence at rates between 0-2 mm yr-1 ([[Wake et al., 2016]]).
- **North-east Greenland**'s net mass loss is relatively low, due to its cold and dry climate and many land-terminating glaciers, which are unaffected by changes in ocean dynamics. Here, mass loss is ~10 Gt year-1 ([[Barletta et al., 2013]]). GIA corrections for this region reach up to ± 4 Gt year-1, representing 40% of the estimated mass loss, and indeed, GIA is the greatest contributor to observed mass trends ([[Wake et al., 2016]]). (*though do note that these mass trends are obtained from Gravitimetry rather than Altimetry*)

- Assessing the rate of GIA is not only important for constraining past and present estimates of mass loss, but also future rates of mass loss.
- GIA affects the gradient of ice sheet beds, which has implications for marine ice sheet instability, where ice sheets on retrograde slopes are hypothesised to be vulnerable to instability and irreversible collapse upon the retreat of the grounding lines ([[Schoof, 2007b]])
- Thus, quantifying GIA is especially important in areas which are deemed vulnerable to marine ice sheet instability, for example, Thwaites Glacier in West Antarctica ([[Joughin et al., 2014]]).
- More recent geodetic investigations of crustal motions in the Amundsen Sea sector show that the upper mantle's viscosity beneath the region is significantly lower than expected ([[Barletta et al., 2018|2018]]), causing GIA to occur at a much faster rate, occuring at a temporal scale fast enough (41 mm a-1; [[Barletta et al., 2018]]) to be able to reduce the steepness of retrograde beds in time to limit the vulnerability to MISI.
- Incorporating GIA into high spatiotemporal resolution models has demonstrated a 26.8% reduction in Thwaites Glacier's contribution to SLR over the next 350 years, showing that its vulnerability to MISI is less than originally thought ([[Larour et al., 2019]]).

#### Gravimetry:

- GRACE and GRACE Follow-on missions allow for direct estimates of ice-sheet-wide mass variability by determining the effects of mass changes on the Earth's gravitational field.
- GRACE mission constructs monthly solutions for the gravity field at the Earth's surface
- The resolution is a few hundred km, therefore, gravimetry methods can resolve ice-sheet wide changes in mass but not the variability of individual glaciers ([[Khan et al., 2015]])
- Gravimetric measurements of ice sheet mass change are the only remote method of assessing mass changes which measure mass directly. Other techniques solve an inverse problem to infer mass changes from other measurements
- However, despite this, GRACE measures the total gravity variability from all geophysical sources, including mass variation from continental ice/water storage outside Greenland, ocean water, atmospheric mass, and glacial isostatic adjustment, as well as changes in ice mass.
- Thus, these additional sources must be removed from the GRACE signal to isolate changes in mass due to ice sheet mass changes.
- GIA's contribution to observed mass changes in Greenland is small - contributing to <5% of the total observed mass change ([[Wake et al., 2016]]).
- However, this correction is spatially heterogeneous. Indeed, not all areas of Greenland are uplifting in response to deglaciation ([[Wake et al., 2016]]) -> see [[_Part II Glaciology#GIA|GIA]]

##### Study Examples:

[[Velicogna et al., 2020]]: Greenland and Antarctica

- Use GRACE and GRACE Follow-on data
- Use SMB estimates to bridge the 11 month gap between missions - fits well.

**Antarctica**
- In Antarctica, ongoing high mass losses in the Amundsen Sea Embayment of West Antarctica, the Antarctic Peninsula, and Wilkes Land in East Antarctica cumulate to 2130, 560, and 370 Gt, respectively, since 2002. 
- A cumulative mass gain of 980 Gt in Queen Maud Land since 2009, however, led to a pause in the acceleration in mass loss from Antarctica after 2016.
- - Snow fall in Dronning Maud Land has been 25% higher than during the pre-industrial period ([[Medley et al., 2017]])

| Region                                   | Mass Change (Gt) | Time Period |
| ---------------------------------------- | ---------------- | ----------- |
| Amundsen Sea Embayment (West Antarctica) | -2130            | Since 2002  |
| Antarctic Peninsula                      | -560             | Since 2002  |
| Wilkes Land (East Antarctica)            | -370             | Since 2002  |
| Queen Maud Land                          | +980             | Since 2009  |

**Greenland**
- Finds an acceleration in the mass loss in Greenland, however this is insignificant.
- 2019 was another exceptionally warm year, with mass loss being similar to the 2012 melt event, seeing a 600 Gt loss - 142% higher than what would be needed to maintain the ice sheet in mass balance.
	- Persistent anticyclonic conditions over the summer promote high snow and ice melt, coupled with low precipitation of snow in the previous winter + low cloud cover ([[Tedesco and Fettweis, 2019]])

**[[Velicogna et al., 2014]]: Greenland and Antarctica**

- Comparing GRACE results to SMB estimates highlights the dominant processes driving ice mass change across regions.
- Mass loss in the Amundsen Sea sector is accelerating (13 ± 2 Gt yr-2)

**Greenland**
- SW: GRACE and SMB agree closely, indicating that mass loss is almost entirely due to SMB, specifically increased runoff - thus dynamic ice discharge plays a minimal role in this region
	- Indeed, most glaciers in SW Greenland are land-terminating -> hence their choice for monitoring seasonal changes in glacier velocity which are unaffected by changes in ocean dynamics ([[Van de Wal et al., 2008]]; [[Zwally et al., 2002]]; [[Tedstone et al., 2015]]; [[Sole et al., 2013]]; [[Sundal et al., 2011]])
- SE and NW: GRACE detects more mass loss than SMB can account for, indicating that ice dynamics dominate in these areas - more marine terminating glaciers allowing for more discharge over grounding lines (**INSERT citations once reading complete**)

**Antarctica**

- The Amundsen Sea sector has a very large discrepancy: SMB changes are only able to explain <10% of the 110 ± 6 Gt yr-1 of mass loss, indicating that almost all loss here is driven by dynamic thinning and glacier acceleration rather than surface processes.
- Dronning Maud Land shows strong agreement in the mass gain due to increased snowfall - 63 ± 6 Gt yr-1.
	- Also accelerating in increase - 15 ± 1 Gt yr-2


# Greenland Hydrology

## Surface Hydrology

- Accumulation, melt, refreezing, and runoff have all increased on the Greenland Ice Sheet ([[Box et al., 2013]])
- 40-50% of meltwater runs off the ice surface directly, and the rest enters the subglacial drainage system ([[Arnold et al., 2013]])
- Meltwater impacts ice sheet mass balance directly by removing mass via drainage and runoff. It also indirectly impacts ice sheet mass balance by influencing ice sheet dynamics, modulating ice flow and hence, discharge across grounding lines.

### Supraglacial Streams

**[[Smith et al., 2015]] - Supraglial drainage through streams and rivers**

- Thermally incised meltwater channels flow each summer across melt-prone surfaces of the Greenland Ice Sheet
- 2012 melt event saw the formation of 523 high-order stream/river channel networks, of of which terminated in moulins before reaching the ice edge.
### Supraglacial Lakes

- Occur over multiple years, often in the same location due to local topographic depressions in the bed topography which is expressed on the ice surface ([[Leeson et al., 2012]]). They are fed by surface meltwater transported via supraglacial channels and provide a significant temporary meltwater store.
- Lakes form and increase in size and elevation in early summer. In mid-to-late summer, they start to shrink or disappear.
- Lakes are forming at progressively higher elevations ([[Tedstone and Muchguth, 2022]])
- **[ DO MORE READING ON DETECTION ]**

- Categories of lake behaviour: ([[Dunmire et al., 2025]]):
	- Refreeze
	- Buried
	- Rapid drain
	- Slow drainage

### Moulins / Crevasses

- Elevation of moulins / crevasses predicted to increase with warming ([[Gagliardini and Werder, 2018]]). 
- Modelling by Gagliardini and Werder ([[Gagliardini and Werder, 2018|2018]]) find that the activation of moulins requires crevassing, but does not necessarily require the presence of supraglacial lakes (they do not consider supraglacial lakes, and yet, moulin activation still spreads up-stream). This disagrees with studies which suggest that the expansion of supraglacial lakes upstream and at higher elevations is the cause of crevassing ([[Christoffersen et al., 2018]] [[Hoffman et al., 2018]])
- Their results contrast with previous studies (e.g., [[Poinar et al., 2015]]) who suggest that crevassing will not extend inland.
- Marine-terminating glaciers, which have been accelerating recently (2016-2021) show a significant increase in crevasse volume (+25.3 ± 10.1% in the SE) ([[Chudley et al., 2025]]).
- However, increases in the SE have been offset by a reduction in crevasse volue in the central west sector (-14.2 ± 3.4%), in particular at Jakobshavn Isbræ, due to slowdown and thickening over the study period, reducing its crevasse volume.
- Thus, changes in crevasse volume are correlated strongly with antecedent discharge changes.

### Firn aquifers

- Firn holds meltwater within its air space, either as liquid water or refrozen into ice ([[Amory et al., 2024]])
- 45% of meltwater in Greenland and almost all Antarctic meltwater refreezes in firn ([[Amory et al., 2024]]; [[Brils et al., 2024]]), preventing it from contributing to sea level rise.
- Firn air content is important to assessing whether firn can hold meltwater. Firn air content can be approximated using a liquid-to-solid ratio defined by the amount of surface melt (and rain, technically, albeit rare) divided by snowfall ([[Stokes et al., 2022]]).


- Many firn aquifers are found in the South-east of Greenland, where accumulation is high enough summer melt to produce water but also enough accumulation to maintain firn air content ([[Miège et al., 2016]]).
- Firn complicates the role of meltwater in the Greenland Ice Sheet by storing water ([[Forster et al., 2014]]), which can:
	- Delay the delivery of water to the bed.
	- Release water to the bed at times beyond e.g., the onset of the melt season or warm days.
	- Collate melt water sufficiently to allow for large hydrofracture ([[Poinar et al., 2017]]).
	- All of which can modulate glacier dynamics.
	
- Miège et al. ([[Miège et al., 2016|2016]]) document the existence of widespread firn aquifers in the elevation range of 1200-2000 m in the high snow-accumulation region of South-east Greenland using GPR.
- Firn aquifers in SE Greenland range in depth from 5-50 m from the ice sheet surface, cover up to 70,000 km2, and store up to 140 km3 of water, acting as a significant store of meltwater ([[Forster et al., 2014]]).

- Requires firn to be accessible - firn beneath low-permeability horizons is less accessible ([[Culberg et al., 2021]])
- 2012 extreme melt season formed a near-surface melt layer - ice slab - restricting vertical percolation. This slab was still present in 2017, though had been buried by around 5 m of new snow/ice ([[Culberg et al., 2021]]; [[Jullien et al., 2023]])
- Frequency of extreme melt seasons relative to the rate at which pore space regenerates is a key determinant of firn's multi-year response to surface melt ([[Jullien et al., 2023]]).
- Extreme melt events (e.g., 2019) in the future are more likely under climate change (IPCC), meaning that ice slabs will play a greater role in modulating Greenland's surface hydrology. Indeed, ice slabs are expanding in surface area and reaching higher elevations ([[Jullien et al., 2023]]) -> maybe link to atmospheric rivers

## Subglacial hydrology

- Much is explained in [[_Part II Glaciology#Influence on dynamics|Influence on Dynamics]].
- Greenland also has subglacial lakes ([[Palmer et al., 2013]] [[Palmer et al., 2015|2015]]), which have been observed to drain.
- There are 64 known subglacial lakes in Greenland ([[Livingstone et al., 2022]])
- Lakes are much smaller than Antarctic lakes and are found nearer the margins. The interior of the Greenland Ice Sheet is not thick enough to produce melt in the interior ([[Bowling et al., 2019]])

**[[Palmer et al., 2015]] - Subglacial lake drainage in Greenland**

- Subglacial lake drainage detected in central west Greenland, using altimetry data.
- Behaviour differs from Antarctic subglacial lakes, which are fed by meltwater generated at the ice sheet base.
- Rather, the proximity of the inferred subglacial lake to a moulin suggests that the lake may have been storing surface-derived meltwater.
- Inferring why the lake formed here is not possible from the low resolution of the ice thickness dataset ([[Morlighem et al., 2017]]).
- Authors suggest that the lake is dammed behind a topographic ridge too small to be resolved, which forms a hydropotential dam.
## Influence on dynamics

- Summer surface melt accounts for half of the mass loss from the Greenland Ice Sheet ([[Van den Broeke et al., 2017]]). Therefore, understanding the control that surface hydrological processes have on the dynamics of the Greenland Ice Sheet is essential for understanding the ice sheet's response to warming.
- We can define glacier dynamics as the resulting ice flow processes caused by the balance of the driving and resistive forces ([[Singh et al., 2011]]). These are primarily driven by processes occurring towards the base, involving the deformation of ice and basal till and basal sliding.
- Various factors influence these processes:
	- Surface mass balance's control on ice thickness
	- Bed topography
	- Temperature changes
- These factors evolve slowly ([[Zwally et al., 2002]]).
- Surface hydrological processes are able to modulate ice dynamics on much shorter time scales which makes them important in the context of a changing climate ([[Zwally et al., 2002]]).
### Land terminating

- Changes to basal conditions are the only processes which are able to modulate the dynamics of land-terminating glaciers over short time periods ([[Gagliardini and Werder, 2018]]).
- Perturbations in basal water pressure affect glacier dynamics through the effective pressure's influence on both glacier sliding and ice deformation.
- Increased water pressure in cavities on the glacier bed enhances sliding, causing cavity growth ([[Kamb, 1987]]).
- This process in turn reduces the apparent rugosity of the bed, thereby weakening ice-bed mechanical coupling ([[Lliboutry, 1983]]), and in doing so, the weight of the glacier ice is supported by a lower surface area at the bed.
- Stress is equal to force divided by area. Therefore, the increase in stress enhances ice deformation ([[Glen, 1955]]; [[Willis, 1995]]).
- If surface meltwater is able to penetrate the ice sheet's bed, it suggests that the Greenland Ice Sheet may exhibit similar dynamics to valley glaciers where an initial speed up in surface velocities at the onset of the melt season is observed, driven by the influx of meltwater into an inefficient, distributed subglacial hydrological system (e.g., [[Nienow et al., 1998]]).

- The thickness of the Greenland Ice Sheet and sub-freezing temperatures over much of its thermal profile mean that any drainage connections between the surface and bed must establish themselves and develop at a fast enough rate before meltwater is able to refreeze ([[Van der Veen, 2007]]).
- When the water pressure in surface crevasses exceeds the local ice overburden pressure, hydrofracture can occur, allowing meltwater to propagate through the full thickness of the ice and reach the bed. This process is facilitated by sufficient accumulation of meltwater to sustain the pressure required for fracture propagation ([[Alley et al., 2005]]; [[Van der Veen, 2007]]).
- Liquid water in the subglacial hydrological system also results in cryo-hydrologic warming, which reduces ice viscosity, thereby contributing to localised faster ice flow ([[Philips et al., 2010]]).
- The refreezing of ice within a crevasse also warms englacial ice through the release of latent heat, aiding fracturing mechanisms ([[Boon and Sharp, 2003]]).

- The rate of water delivery to the bed is fundamental to its effect on basal hydrology ([[Schoof, 2010]]). High water fluxes to the bed can channelise the basal system over the course of a melt season ([[Bartholomew et al., 2011]]). However, channelisation may not occur during short lived periods of high flux or when water flux is too low.

#### Annual influence of melt

- GPS tracking of ice reveals a correlation between changes in ice velocity and the intensity and timing of surface melting during the ablation season (e.g., [[Van de Wal et al., 2008]]; [[Zwally et al., 2002]]).
- The correlation between surface melt, surface uplift, and enhanced horizontal velocities, is indicative of the rapid delivery of surface meltwater to the ice sheet bed via efficient hydraulic connections such as crevasses or moulins, resulting in the hydraulic jacking of ice and enhanced sliding ([[Bartholomew et al., 2010]]) - Russel Everet Glacier.
- When melt first reaches the bed, the acceleration in surface velocities and uplift is indicative of an inefficient, distributed subglacial hydrological system which is highly sensitive to changes in water fluxes at the bed ([[Bartholomew et al., 2010]]).
- The initial acceleration in surface velocities was an initial cause for concern for the Greenland Ice Sheet's response to future climate warming ([[Zwally et al., 2002]]). Enhanced ice velocities would result in more ice being advected into the ablation zone, accelerating surface melt and ice discharge ([[Zwally et al., 2002]]).
- However, later studies have observed a gradual surface lowering and slowdown of land-terminating glaciers over the melt season, indicative of the evolution of the subglacial hydrological system to a more efficient, channelised network where basal water pressures are lower ([[Schoof, 2010]]; [[Bartholomew et al., 2010]]).
- This development of a more efficient subglacial hydrological system preconditions the system for lower velocities in the winter period, thereby offsetting any enhanced glacier flow in the summer period, the net result being an annual slowdown in glacier velocities ([[Sundal et al., 2011]]; [[Sole et al., 2013]]).
- Indeed, when monitored on a decadal time scale, despite a 50% increase in meltwater production in 2007-2014, compared to 1985-1994, annual ice motion on land-terminating glaciers in West Greenland was 12% slower ([[Tedstone et al., 2015]]).

- The englacial storage time of meltwater is important for controlling its temporal influence on ice dynamics ([[Ran et al., 2024]]).
- Ran et al. (2024) use GNSS to monitor the elastic deformation of bedrock due to its response to changes in meltwater mass on the Greenland Ice Sheet.
- SMB models typically only account for local, shallow meltwater storage by capillary action and refreezing in seasonal snow and firn; further meltwater is assumed to reach the ocean instantly. However, in reality, water storage causes a runoff delay.
- The average storage time of meltwater is 8 weeks, though this is spatially variable.
- NE and W regions it is around 9 weeks, whilst in SE it is only a few weeks, likely due to the SE being characterised by high accumulation rates, steep topographic relief, and a narrower ablation zone with shorter distances from surface melt locations to the ocean.
- This understanding aids in the understanding of hydrology on dynamics and also the response of bedrock to melt, which helps to constrain 

**Some nuance: [[Doyle et al., 2014]]: Persistent flow acceleration within the interior of the Greenland ice sheet**

- Speed up / slow down effect is spatially variable. Doyle et al. ([[Doyle et al., 2014|2014]]) measure GPS velocities at a high elevation above the ELA, 50 km into the accumulation area. They find that summer velocities increase in response to surface melt, but the flux of meltwater is insufficient to develop efficient channels.
- Their study, therefore, is contrary to Sundal et al. ([[Sundal et al., 2011|2011]]) where summer velocities in the ablation area decrease in warmer summer, indicative of the development channelised system.
- Also disagrees with Sole et al. ([[Sole et al., 2013|2013]]) and Tedstone et al. ([[Tedstone et al., 2015|2015]]) where summer speed up is offset by winter slowdown due to the preconditioning of the hydrological system to channelized flow, reducing basal water pressure in winter - reduced annual velocity.
- Doyle et al. find an increase in annual velocity.

#### Diurnal influence of melt

- Shorter diurnal changes in horizontal velocity variations have also been correlated with daily melt and positive degree days ([[Shepherd et al., 2009]])
- Similar mechanism whereby subglacial water pressures are increased, enhancing sliding and resulting in the hydraulic jacking of the ice sheet.
- Short diurnal changes are not necessarily always correlated with daily melt, the drainage of supraglacial lakes also affects dynamics.

#### Drainage of supraglacial lakes

- The drainage of supraglacial lakes have been associated with short-lived ice uplift and increase ice velocities due to meltwater perturbing the bed.
- Das et al. ([[Das et al., 2008|2008]]) provide the first known evidence of this, where the draining of North Lake in 2 hours at a rate of 8700 m3 s-1 resulted in local uplift and ice velocity increases within 24 hours.
- Similar behaviour from Lake F on Russell Glacier - Lake F drained initially slowly through oversplilling, then drained rapidly via hydrofracture ([[Doyle et al., 2013]])
- Tedesco et al. ([[Tedesco et al., 2013|2013]]) observe the slow drainage of Lake Half Moon via overspill into pre-existing channel and moulin 700 m downstream. This spill caused a 5-fold increase in velocity. Meanwhile Lake Ponting drained rapidly via hydrofracture in a short time after another lake overspilled into Ponting. A 600 m fracture opened along the lakebed with multiple new moulins. This event triggered a 15-fold velocity increase.
	- Each drainage was associated with uplift and increased ice velocity.
	- Thus, the impact of the surface lake drainage on ice dynamics is dependent on the drainage mechanism.

- The influence of supraglacial lake drainages are not necessarily confined to the region immediately surrounding the supraglacial lake.
- Lakes often drain in clusters, where an initial event may trigger cascading draining events through various mechanisms including the draining of a lake directly into another through overtopping and slow drainage, altering its depth, or the draining into the subglacial hydrological system which perturbs the glaciological setting of lakes through changes in their stress regime ([[Christoffersen et al., 2018]]; [[Stevens et al., 2024]]; [[Stevens et al., 2015]]).
- See surface hydrology notes for more on drainage.
- The spatial impact of lakes is obviously determined by the presence of lakes in the first place

#### Drainage of firn aquifers

- Firn complicates the role of meltwater in the Greenland Ice Sheet by storing water ([[Forster et al., 2014]]), which can:
	- Delay the delivery of water to the bed
	- Release water to the bed at times beyond e.g., the onset of the melt season or warm days
	- Collate melt water sufficiently to allow for large hydrofracture ([[Poinar et al., 2017]])

**[[Poinar et al., 2017]] - Drainage of Southeast Greenland Firn Aquifer Water through Crevasses to the Bed**
- Firn aquifer in the Helheim Glacier catchment of SE Greenland
- 3.5 km long segment lost a large volume of water (26,000 - 65,000 m2 in cross section) between spring 2012 and spring 2013.
- Water is thought to have entered crevasses downstream.
- Using a model, the study shows that the crevasses receiving firn-aquifer water hydrofracture to the bed, 1000 m below, in 10-40 days. The englacial refreezing of firn-aquifer water raises the local ice temperature by 4 degrees over a 10 year period, enhancing deformational ice motion by 50 m yr-1, 25% of the total observed surface velocity (200 m yr-1)
- Model finds that if the firn aquifer was not present to concentrate surface meltwater into crevasses, then surface meltwater would simply refreeze anually in the crevasses at depths of less than 500 m. 
- Thus, the presence of the firn aquifer acts in a way to concentrate water into crevasses, enabling water which would otherwise have refrozen to reach the bed and modulate glacier dynamics.
- This system may uniquely affect ice-sheet dynamics by routing a large volume of water to the bed outside of the typical runoff period in summer and at a relatively high elevation (1500 m).

### Marine terminating

- 87% of Greenland's glacierised area terminates in the ocean ([[Kochtitzky et al., 2023]]).
- Ice discharge accounts for 90% of frontal ablation ([[Kochtitzky et al., 2023]])
- Moon et al. ([[Moon et al., 2014|2014]]) classify three types of glacier behavior for 55 marine-terminating glaciers over a 5-year record of seasonal velocity measurements: (which vary in space and time)
	- Type 1: Seasonal speed variations are driven by the position of the terminus
	- Type 2: Seasonal changes are correlated to the volume of meltwater runoff in the catchment
	- Type 3: Seasonal speeds relate to runoff volumes, but their speeds show an initial maxima in the early melt season and then decline due to the adaptation of the subglacial hydrological system to high runoff.
- Type 1 is terminus-driven, type 2 is runoff-driven, and type 3 is runoff-adapting.
- Most (27/55) are runoff-driven/adapting, 6 are Type 1, and the rest have no dominant type over the 5-year period.
- **DO LATER**
- Because changes in these factors can be superimposed on, and interact with, one another, it is often difficult to attribute an observed glacier dynamic change to a particular forcing factor ([[Catania et al., 2021]]).
- The relative contribution of external factors (oceanic and climatic) vs. localized glacier-specific factors (most notably fjord geometry and basal topography) remains poorly understood and identifying their respective influence on outlet glacier retreat is of paramount importance for estimating future glacier response to climate change and sea level rise ([[Hill et al., 2017]]).


**[[Sommers et al. 2024]] - Helheim Glacier**

- Terminus effects dominate seasonal velocity patterns at Helheim Glacier in the near-terminus region.
- Seasonal runoff is responsible for less than 10% of the velocity variability near the terminus
- Beyond 15 km inland, meltwater reaching the bed is the main driver of velocity variations.
- Steady year-round meltwater drainage from the firn aquifer causes higher inland velocities, and seasonal variations in the firn aquifer drainage result in altered seasonal patterns of the interior velocity.
- Model-based finding of terminus control within 15 km is consistent with observational studies (e.g., [[Moon et al., 2014]]; [[Poinar et al., 2023]]).
- Incorporating terminus forcing is required in order to reproduce the observed velocity pattern near the terminus.
- However, the finding of hydrological control further upstream is difficult to validate with observations because the magnitude of the simulated variations of inland velocity is below the noise level in observations at these locations.
- However, it is clear that inland locations do not necessarily follow a seasonal pattern reflecting the terminus - two separate controls.

**[[Amundson et al., 2010]] - Mélange dynamics Jakobshavn Isbræ**

- Mélange plays a role on terminus dynamics and stability.
- During winter, sea ice growth stiffens the mélange matrix by binding icebergasts together, ultimately preventing the calving of full-glacier-thickness icebergs, enabling terminus advance in the magnitude of several kilometres.
- The breakup of melange in summer results in terminus retreat.
- A realistic model of terminus behavior must be able to predict seasonal variations in calving rate
- Therefore, Jakobshavn Isbræ, these variations are presently controlled by variations in sea ice cover and ice mélange strength and by dynamic thinning of grounded ice in summer
- Calving events can cause short-lived, rapid movements of mélange away from the calving front.

- Thinning rates slowed from 2014 and the glacier thickened and readvanced between 2016-2019 ([[Khazendar et al., 2019]]).
- Joughin et al. ([[Joughin et al., 2020|2020]]) suggest that ocean-induced mélange changes control dynamics rather than through submarine melting. 
- Therefore, projections of glacier contributions to future SLR based solely on glacier geometry are insufficient, and accounting for external forcing is crucial.

# Antarctic Hydrology

- Antarctic hydrology contrasts with Greenland's. The majority of ice loss is through discharge and calving at the margins.
- 55% of the Antarctic Ice Sheet bed is at the pressure melting point, raised there by geothermal heating and friction with the bed ([[Pattyn, 2010]]).

## Subglacial hydrology

- There are **675** known lakes beneath the Antarctic Ice Sheet ([[Livingstone et al., 2022]]).
- Water collects in sinks in the subglacial hydraulic potential, as governed by Shreve's theory ([[Shreve, 1972]]). Subglacial hydraulic potential is calculated using the bedrock height and estimates of ice thickness (e.g., Bedmap2, 3, [[Fretwell et al., 2013]]; [[Pritchard et al., 2025]]).
- Willis et al. ([[Willis et al., 2016|2016]]) utilise Bedmap2 (Fretwell et al., 2013) to predict the locations of subglacial lakes by identifying hydraulic potential sinks. Not all predicted lakes align with real lakes, although real lakes often align well with the predicted ones.
- Lakes are detected using Radio Echo Sounding and Altimetry - they are sufficiently large that the ice's topography above is affected by them and is typically flat. Rises and falls in the topography over some lakes, detected by altimetry, indicate the filling and draining of lakes. They appear as bright sub-horizontal reflectors, contrasting with adjacent areas of the bed ([[Carter et al., 2007]])
- Seigert et al. ([[Seigert et al., 2005|2005]]) identify two types of lakes:
1. Interior lakes
	- often close to subglacial margins and near slow-flowing ice divides.
	- on the stoss sides of hills and mountains.
2. Lakes close to the onset of enhanced ice flow
	- Hundreds of km from ice-sheet divides.
	- Close to the beginning of ice streams (though not all fast flow onset areas are necessarily near lakes).

### Active lakes

- Many lakes detected by repeat satellite altimetry using ICESat and InSAR showing changes in height of ice sheet surface.
- More than 130 active lakes ([[Siegfried and Fricker, 2021]])
- Lakes are small and transient, filling and draining on an annual or multi-annual basis.
- The location of subglacial lakes is important, because the presence of meltwater and saturated subglacial sediments facilitates rapid ice velocity.
- Water-saturated sediments reduce basal shear stress, allowing basal sliding at low driving stresses ([[Rignot et al., 2011]]; [[Kamb, 2001]]).
- Changes in the subglacial hydraulic system can result in rapid changes in glacier velocities.

- Several lakes, which together have a similar size to Lake Vostok, have been found in the onset region of the Recovery Glacier Ice Stream in EA ([[Bell et al., 2007]]).
- These lakes initiate and maintain the rapid ice flow in the downstream ice streams by changing the basal thermal regime and lubrication ([[Bell et al., 2007]]).
- Enhanced flow from lubrication then contributes to more friction, raising basal temperatures, generating more melt, which further promotes subglacial lake growth.

- Lakes are hydraulically connected, inferred from the near-simultaneous drainage of nearby lakes and modeled subglacial water flow pathways using Shreve's theory ([[Smith et al., 2017a]]).
- The sensitivity of a glacier is dependent on the spatial extent to which water is distributed across the ice-bed interface, and the nature of the ice-bed interface itself ([[Smith et al., 2009]]).
- Case studies below have different spatial and temporal impacts, causing different responses.
- Shows that internal variation affects flow speeds.

**Example of acceleration in response to lake drainage [[Stearns et al., 2008]]: Increased flow speed on a large East Antarctic outlet glacier caused by subglacial floods**

- Observed acceleration of ice velocity on Byrd Glacier, EA, of about 10% of the original speed between December 2005 and February 2007
- Acceleration extended along the entire 75 km glacier trunk and its onset coincided with the discharge of 1.7 km3 of water from two large subglacial lakes 200 km upstream of the grounding line.
- Deceleration coincided with the termination of the flood.

- Track velocities using satellite feature tracking.
- Speed up coincides with rapid changes in surface elevations at two locations 200 km upstream of the grounding line, detecting using ICESat altimetry data.
- Velocities reached 900 m yr- at the grounding line.
- Elevation changes vary by up to 12 m over the study period, and are thus beyond the range of observed elevation changes detected in most parts of Antarctica. Thus, they are interpreted as the filling and draining of subglacial lakes.

- Byrd Glacier has several regions of high basal drag - 'sticky spots' ([[Whillans et al., 1989]])
- The distributed drainage network beneath Byrd Glacier is unable to discharge incoming drainage water, submerging stick spots, thereby reducing basal friction and promoting faster ice velocities.

**More recent example of acceleration [[Siegfried et al., 2016]] - Episodic ice velocity fluctuations triggered by a subglacial flood in West Antarctica**

- Use 5 years of continuous GPS measurements, between 2010 and 2015, on Whillans and Mercer ice streams. 
- GPS-derived height change capture two distinct phases of the subglacial hydrologic system. 2010-2011 saw the slow filling of lakes, and 2012-2014 saw the draining of the lakes.
- Draining of subglacial lake Mercer occurred in two phases in late 2012 and 2014 and had differing impacts on ice dynamics. The first drainage was positively correlated with velocity, the second was negatively correlated, suggesting the evolution of the subglacial hydrological system between each episode.
- The first event even negated a decelerating trend in the glacier's velocity, causing a temporary acceleration. 
- Overall, basal conditions of ice streams can rapidly evolve on annual to sub-annual timescales, meaning that short-term observations in glacier velocities may not be representative of long-term ice sheet dynamics.


**Example of cascading drainage: [[Smith et al., 2017a]] - Connected subglacial lake drainage beneath Thwaites Glacier, West Antarctica**

- Use CryoSat-2 altimetry data to observe the near-simultaneous drainage of 4 lakes in 2013-2014 on Thwaites glacier over 6 months, 70-170 m from the grounding line.
- Hydraulic potential mapping shows that subglacial water flow beneath the area is organised into circuitous paths which are often perpendicular to the large-scale flow gradient.
- This method is not perfect as it assumes that the water pressure equals the overburden (zero effective pressure), but in reality, some regions' water pressure must be lower to maintain basal traction; otherwise, according to sliding laws, the basal resistance becomes zero.

- Draining can be initially slow and inefficient, occurring once a lake overtops its local hydro-potential barrier.  
- A low-pressure gradient channel may then develop due to melting, which leads to more rapid drainage. Upon drainage, the water flux is not high enough to maintain the tunnel, causing it to reclose due to ice deformation, which reseals the lake, allowing it to recharge.

- Using this, we could then expect an upstream's drainage into a downstream lake to cause the downstream lake to then overflow, causing a cascading drainage nature.
- However, Lake Thw124, which is the second most downstream lake, spills first, with the remaining three lakes' drainage occurring concurrently after, thereby disagreeing with the above hypothesis.
- Smith et al. (2017) suggest that the drainage of a downstream lake would lower its own potential, forcing more water flow toward the lake which could alter pressure gradients sufficiently to allow water from the adjacent catchments to spill over, inducing spills from upstream lakes.

- The sudden injection of a large volume of water under the trunk of an active glacier has in some cases led to a short-term acceleration in flow and discharge ([[Stearns et al., 2008]]).
- For this study, however, the extra water from lake drainage seems to have had little or no influence on the speed of the lower glacier. 
- Modelling of basal shear stresses of TWG by Joughin et al. ([[Joughin et al., 2009|2009]]) suggests that basal drag is concentrated in narrow bands oriented perpendicular to flow.
- The glacier speed is largely controlled by the drag in these high-stress regions, which provides a more global control on glacier velocity, even in regions of low basal stresses due to high basal water pressure. Thus if the change isn't in these areas, lake drainage is unlikely to have a large impact on the larger glacier velocity.
- Furthermore, if the drainage of water between lakes moved through narrow channels, it would only occupy a small area of the bed, resulting in only a small impact on basal shear stresses and any sliding.
- In addition, the development of low-pressure water channels would further draw in more water from any surrounding higher-pressure distributed systems, acting to decrease speeds, rather than accelerating them.
- The lack of elevation increases downstream, implying that the discharge water was not stored subglacially but discharged to the ocean. See Gourmelen et al. ([[Gourmelen et al., 2025|2025]]) for the influence of a short-term but high-volume discharge into the ocean.

**[[Gourmelen et al., 2025]] - Lake discharge influence on Thwaites**

- Study analyses the influence of the 2014 (± a few years of other lake activity) lake drainage event ([[Smith et al., 2017a]]) on Thwaites Glacier.
- Lake drainage lasted about a year and discharged a total volume of 7.22 ± 0.26 km3, about four times the predicted annual meltwater production in this catchment, and the largest connected lake activity in the recent record under the AIS.
- Found that the buoyant plume from the subglacial discharge in 2013 temporarily doubled the rate of ocean melting under Thwaites, thinning the ice shelf.
- A polynya started forming 20 km offshore from Thwaites' grounding line in early September 2013.
- Authors suggest that the formation is a consequence of the buoyant plume created by subglacial discharge and meltwater, which entrains deep ocean heat, delivers it to the ocean surface, and melts sea ice.

**[[Hager et al., 2022]] - Persistent Channelised Network beneath Thwaites**

- Model outputs suggest that a persistent, extensive channelised network lies beneath Thwaites Glacier.
- Slightly contrasts with Smith et al. ([[Smith et al., 2017a|2017a]]) because they suggest that channels are ephemeral, only forming during subglacial lake drainage events.
- Lake formation can be explained by portions of the bed being hydraulically disconnected, which is observed in alpine and Greenland glaciers ([[Rada Giacaman and Schoof, 2023]]).
- Without the presence of a seasonal melt cycle forcing a reconfiguration of the hydrological system ([[Schoof, 2010]]), disconnected regions can remain disconnected year-round, permitting disconnected water to pool into lakes, which drain when they periodically exceed their hydropotential seals ([[Fowler, 1999]]; [[Smith et al., 2017a]]).
- Such drainage events could act as similar catalysts for drainage network reconfigurations as the seasonal melt cycles of alpine and Greenland glaciers.
- Indeed, Siegfried et al. ([[Siegfried et al., 2016|2016]]) noted two draining events of Lake Mercer beneath Mercer Ice Stream in late 2012 and late 2014 had differing impacts on ice dynamics, suggestive of the change in the subglacial hydrological system between drainage events.
- An already efficient channelised network could accommodate the additional flux from lake drainage events, which may explain why Smith et al. ([[Smith et al., 2017a|2017]]) only observed a minor increase (<10%) in Thwaites Glacier's velocity during drainage - though this would require the previously disconnected lake to efficiently connect to the main channelised network efficiently.
### Groundwater contribution

- Magnetotelluric and seismic data of the sediment beneath Whillans Ice Stream suggest that a deep groundwater system beneath the ice stream holds an order of magnitude more water than the shallow hydrological system above it ([[Gustafson et al., 2022]]).
- The groundwater is saline, and thus of marine origin, inferred to have developed during a period when the West Antarctic Ice Sheet's extent was less than the present day during deglaciation prior to re-advance ([[Kingslake et al., 2018]]).
- There is a gradient in the salinity, indicating mixing between meltwater and the groundwater ([[Gustafson et al., 2022]]).
- Thus, the groundwater can both contribute water to the subglacial hydrological system and remove water, affecting basal sliding in a complex way.
- Solutes can also affect local melting points of ice, further affecting basal sliding.

## Seasonal variation

- Recent satellite-remote sensing studies have documented the multi-decadal acceleration of the Antarctic Ice Sheet in response to rapid rates of ice-sheet retreat and thinning. Unlike the Greenland Ice Sheet, where historical, high-temporal-resolution satellite and in situ observations have revealed distinct changes in land-ice flow within intra-annual timescales, observations of similar seasonal signals are limited in Antarctica ([[Boxall et al., 2022]]).
- Recent observations of seasonal ice acceleration on the Antarctic Peninsula ([[Boxall et al., 2022]], [[Boxall et al., 2024|2024]]; [[Wallis et al., 2023]]) emulate the observations from Greenland and valley glaciers, thereby implying they may be driven by similar surface meltwater-related processes, or oceanic forcing mechanisms.
- Assessing the degree of seasonal ice-flow variability at such locations is important for accurately quantifying Antarctica's future contribution to global sea-level rise ([[Boxall et al., 2022]]). Variable ice flow on intra-annual timescales has not been considered within discharge-based calculations of ice sheet mass balance ([[Rignot et al., 2011]]), meaning ice discharge may be over- or under-estimated ([[Boxall et al., 2024]])

**[[Boxall et al., 2022]], [[Boxall et al., 2024|2024]] - Seasonal variation in George VI Ice Shelf**

- Use high-spatial- and high-temporal-resolution Copernicus Sentinel-1A/B synthetic aperture radar observations acquired between 2014 and 2020 to provide the first evidence for seasonal flow variability of the land ice feeding George VI Ice Shelf
- Distinct summertime (DJF) speed up of 22 ± 1.8 m yr-1 (15% of baseline rates).
- Authors suggest that meltwater and ocean variability from the intrusion of cirumpolar deepwater can cause speedups in velocity.
- Indeed, Boxall et al. ([[Boxall et al., 2024|2024]]) finds statistically significant correlations between surface meltwater and ice velocity, with a 0-1 month lag across all 16 studied glaciers.
- Short-lived velocity maxima followed by sharp deceleration lend evidence to this interpretation, resembling a "Greenland-style" late-to-post-summertime switch 
- However, they are unable to directly observe any mechanism which allows for the near-instantaneous routing of meltwater to the bed.
- However, despite this correspondence between seasonal signals, supraglacial meltwater presence and persistence are limited inland of Antarctica's grounding zone, and surface ponding is absent, offering no mechanism for hydrofracture.
- Firn aquifers are present near the northern ice front of George VI ice shelf ([[Miller et al., 2022]]), and Boxall et al. suggest that if these features are close to the hydrofracture threshold, seasonal surface melt accumulation could rapidly result in hydrofracture, presenting a mechanism for the rapid delivery of meltwater to the bed and near-instantaneous acceleration in glacier velocities.

**[[Wallis et al., 2023]] - Widespread seasonal speed-up of west Antarctic Peninsula glaciers from 2014 to 2021**

- Use Sentinel-1 observations between 2014 and 2021 of 105 glaciers across the AP, finding an average summer speed up of 12.4 ± 4.2%.
-  Glaciers response to seasonal forcing in the ice-ocean-atmosphere system, indicating sensitivity to changes in terminus position, surface melt plus rainfall flux, and ocean temperature.
- Seasonal speed variations must be accounted for when measuring the mass balance and sea level contribution of the Antarctic Peninsula, and studies must establish the future evolution of this previously undocumented signal under climate warming scenarios.

Little bit different: **[[Murray et al., 2007]] - Ice flow modulated by tides at up to annual periods at Rutford Ice Stream, West Antarctica**

- Use 2 years of GPS data 40 km upstream of Rutford Ice Stream's grounding line.
- They find a clear modulation of ice flow at semi-diurnal, diurnal, two-weekly, semi-annual, and annual ocean tidal frequencies.
# Ice Sheet Instability and ice sheet futures

## Antarctica

- Of the 58 m of sea level rise equivalent stored in the Antarctic Ice Sheets, 19 m is from ice grounded below present sea level ([[Fretwell et al., 2013]]).
	- Split 1:2 between West and East ([[Fretwell et al., 2013]])
- Marine-based ice sheets are susceptible to positive feedback mechanisms which cause instability ([[Edwards et al., 2019]]).
- Three main mechanisms which have been modelled/observed / inferred from palaeogeolocial evidence:
	- Marine Ice Sheet Instability (MISI) ([[Joughin et al., 2014]])
	- Marine Ice Cliff Instability (MICI) ([[Wise et al., 2017]])
	- Ice sheet reaching full buoyancy ([[Batchelor et al., 2023]])
- Constraining the bed topography is crucial for assessing vulnerability and potential instability ([[Morlighem et al., 2020]])

### Marine Instability
#### Marine Ice Sheet Instability

- MISI is the hypothesis that marine-based ice sheets lying on retrograde beds are inherently unstable and vulnerable to rapid retreat ([[Schoof, 2007b]]; [[Weertman, 1974]])
- The ice flux through any point is the ice velocity multiplied by the cross-sectional area perpendicular to the flow direction.
- Thus, on a retrograde bed, any retreat in the grounding line position, whether due to internal or external forcing, will result in an increase in ice thickness at the grounding line.
- Consequently, ice discharge over the grounding line increases, which results in further thinning, calving, and reduced buttressing if an ice shelf is present.
- The grounding line further retreats in response to this, resulting in a positive feedback loop.
- Much of our understanding of MISI is from models, which suggest that MISI may be underway in response to the increased presence of modified circumpolar deepwater on Antarctica's continental shelves.

- Causes of initial retreat:
	- Thinning of ice shelves reduces buttressing, resulting in enhanced discharge over the grounding line, enhancing disequilibrium, causing initial grounding line retreat. Indeed, Antarctica's outlet streams have accelerated in recent decades ([[Shepherd et al., 2018]]).
	- Intrusion of modified Circumpolar Deepwater beneath ice shelves ([[Stokes et al., 2022]]).

**[[Schoof, 2007b]] [[Schoof, 2012|2012]] - Simple MISI Model**

- Schoof ([[Schoof, 2007b|2007b]]) demonstrates the MISI hypothesis using a depth-integrated model for the flow of a rapidly sliding, two-dimensional marine ice sheet.
- Schoof demonstrates that ice flux is always an increasing function of ice thickness and longitudinal stress.
- Within two dimensions, Schoof further demonstrates that longitudinal stress is always an increasing function of thickness.
- Thus, ice flux can be represented as purely an increasing function of thickness.
- Using this model, it follows that if an ice sheet’s grounding line lies upon a retrograde bed, a slight retreat in its grounding line position in response to external or internal mechanisms will lead to an increase in grounding-line ice thickness, thereby increasing the ice flux at the grounding line.
- Therefore, viable stead-state profiles of ice sheets must have their grounding line on prograde beds ([[Schoof, 2007b]]; [[Schoof, 2012|2012]]).

##### West Antarctic Ice Sheet MISI

- The West Antarctic Ice Sheet has been identified as being especially vulnerable to MISI, particularly the glaciers which feed the Amundsen Sea Sector, due to their beds lying on a retrograde bed which deepens inland ([[Mercer, 1978]]; [[Hughes, 1981]]; [[Joughin and Alley, 2011]]).
- This is of concern due to the West Antarctic Ice Sheet's current dominance within Antarctica's mass loss, contributing to 159 ± 25 Gt yr-1 from the total loss of 109 ± 56 Gt yr-1 ([[Shepherd et al., 2018]]) (*Note that the total mass loss is actually lower due to being a net mass loss, which includes gains from the East Antarctic Ice Sheet*).
- Models suggest that MISI is underway in response to the increased presence and intrusion of warm modified circumpolar deepwater on Antarctica's continental shelves ([[Favier et al., 2014]]; [[Jacobs et al., 2011]]; [[Joughin et al., 2014]]).
- Warm water is thinning the ice shelves due to increased melt at the ice-water interface, which reduces their buttressing capabilities, resulting in the acceleration of ice flow from the ice sheet's interior ([[Joughin et al., 2014]]).

- However, with only a few decades’ worth of satellite data and no direct observations of grounding-line retreat for PIG during the twentieth century, it remains difficult to assess fully the relative importance of the various drivers, especially whether the recent changes are indeed a response to past perturbations ([[Smith et al., 2017b]]).

**[[Joughin et al., 2014]] - Marine Ice Sheet Collapse Potentially Under Way for the Thwaites Glacier Basin, West Antarctica**

- Study uses a 'prognostic, finite-element, depth-averaged, shallow-shelf model' (*good luck remembering that*) model* to investigate Thwaites Glacier’s stability and find that unstable retreat is underway in all basal melt scenarios except for model runs where there is no coupling between the grounding line position and glacier response - an unrealistic scenario.
- Thwaites Glacier’s grounding line is already on a retrograde bed, and a further 60-80km inland, its bed rapidly gives way to a deep basin, further increasing its vulnerability if retreat extends sufficiently far, which is almost inevitable owing to the positive feedback nature of MISI.
- Study does not consider ocean-driven melt on ungrounded ice. This would cause further thinning, reducing buttressing, and accelerating ice discharge, contributing to further grounding line retreat - thus study may underestimate retreat.
- The main uncertainties in their model regard the timescale of collapse, rather than whether MISI is occurring or not.

**[[Favier et al., 2014]] - Retreat of Pine Island Glacier controlled by marine ice-sheet instability**

- The retreat of Pine Island Glacier is attributed to the acceleration of the glacier in response to sub-ice-shelf melting, controlled by MISI.
- No model scenarios produce a steady grounding line on the retrograde slope, and perhaps most concerningly, the rate of grounding-line retreat was independent of the original trigger and continued despite its later removal.
- This highlights the vulnerability to irreversible retreat even if mitigation measures are implemented.

**[[Smith et al., 2017b]] - Observations of grounding line retreat on Pine Island Glacier**

- Use sediment cores to observe grounding line retreat on Pine Island Glacier
- Warm El Niño conditions in 1940s caused the development of a cavity behind a ridge which Pine Island Glacier was grounded upon.
- Ridge became ungrounded post-1973, which corroborates with satellite imagery.
- A retrograde bed lies behind the ridge, which is conducive to the MISI hypothesis, and grounding-line retreat has occurred down the bed.
- Even with the return to normal conditions in ensuing decades, retreat continued, suggesting that ice-sheet retreat can continue even when the forcing reverts to its earlier state.

**[[Rosier et al., 2021]] - Tipping points for Pine Island Glacier** 

- Ocean warming of 1.2 degrees results in a complete collapse of Pine Island Glacier
- Requires reducing the control parameter further beyond its initial state to recover the system
- Thus, removing the original forcing does not result in stabilisation, corroborated by past observational evidence ([[Smith et al., 2017b]]).


##### East Antarctic Ice Sheet MISI

- Recent attention in the literature has turned to East Antarctica, where research was previously sparse due to the concentration on West Antarctica.
- Historically, the EAIS has been under-monitored compared to the WAIS because it was thought to be in mass balance and, therefore, contributing minimally to net Antarctic mass loss ([[Stokes et al., 2022]]).
- East Antarctica holds 2/3rds of Antarctica's below-sea-level grounded ice ([[Shepherd et al., 2018]]).
- Parts of East Antarctica have the same characteristics, which are driving current instability in the WAIS and have historically been vulnerable to rapid retreat during previous interglacial periods ([[Jones et al., 2015]]; [[Pelle et al., 2020]]).
- Jones et al. ([[Jones et al., 2015|2015]]) use exposure estimates and a model on an East Antarctic outlet glacier, finding that Mackay Glacier’s rapid thinning and retreat in the early Holocene was driven by MISI.
- Retrograde beds are present under some basins within East Antarctica - **Recovery, Wilkes, and Aurora Subglacial Basins** ([[Diez et al., 2018]]).

- mCDW intrusion has been detected on continental shelves proximal to EA's marine-terminating glaciers and ice shelves ([[Hirano et al., 2020]]), caused by the weakening of Southern Hemisphere Easterlies, reducing onshore Ekman transport of cold, fresh Antarctic Surface Water, which typically displaces mCDW away from the continental shelf ([[Guo et al., 2023]]; [[Stokes et al., 2022]]).
- Thus, parts of EA display both the physical disposition - a retrograde bed - and the forcing required to initiate MISI - mCDW intrusion.

- Not only does this highlight the vulnerability to MISI, but increased melt also affects the stratification of East Antarctica's coastal waters ([[Guo et al., 2019]]; [[Guo et al., 2023|2023]]) which are a primary region for the formation of Antarctic Dense Shelf Water, and hence, Antarctic Bottom Water ([[Ribeiro et al., 2021]]; [[Williams et al., 2016]]).
- Thus, rapid grounding line retreat and its associated melt has implications on the wider global ocean overturning circulation ([[Ribeiro et al., 2021]]),. increasing the potential spatial impact of East Antarctica's melt.
- Looking ahead into the next century, it is predicted that mCDW will continue to pool on East Antarctica’s continental shelves because of persisting weakened easterlies, threatening the future stability of ice shelves, sea ice, and AABW formation ([[Guo et al., 2023]]).
- Due to a lack of observational records, it is difficult to attribute mCDW intrusion to natural variability or anthropogenic activity ([[Stokes et al., 2022]]). However, as demonstrated by models and observational evidence, retreat can continue even if the original forcing is removed ([[Favier et al., 2014]], [[Smith et al., 2017b]]). Thus, even if mCDW intrusion is part of natural variability, if present intrusion initiates MISI-like grounding line retreat, then even if intrusion decreases due to natural variability, MISI may continue regardless.the present intrusion initiates MISI-like grounding line retreat, then even if the intrusion decreases due to natural variability, MISI may continue nonethe

##### Model Assessment

- Schoof's ([[Schoof, 2007b|2007b]]) original model is limited due to only being a two-dimensional model, where ice flux is always an increasing function of ice thickness, which asserts that ice sheets cannot be stable on retrograde beds.
- However, models such as full Stokes models, which allow for the consideration of a three-dimensional ice sheet, find that it is possible to have stable ice configurations on a retrograde bed ([[Gudmundsson et al., 2012]]).
- Simulations of historic ice-stream retreat in Antarctica since the last glacial maximum find that the retreat of the Marguerite Bay Ice Stream, AP, was highly non-linear and displayed periods of stabilisation despite lying on a retrograde bed, which previous theory would otherwise predict a rapid retreat ([[Jamieson et al., 2012]]).
- Transient stabilisations in retreat were a result of periods of enhanced lateral drag as the ice stream narrowed ([[Jamieson et al., 2012]]).
- Thus, the vulnerability of ice sheets to MISI is more complex than simply assessing the gradient of their beds.
- Glacier regimes with low driving and basal stresses due to shallow surface slopes, such as on the Siple Coast, do not conform exactly to the MISI hypothesis and their (in)stability of the grounding line is determined by a combination of drag, basal stress regime, snow accumulation rate, and the bed slope ([[Sergienko and Wingham, 2019]]).
- The combination of multiple factors that affect grounding line stability highlights the importance of accurate models that consider the aforementioned factors and have reliable initial conditions and geophysical data to constrain models. Else, the AIS’s vulnerability to MISI may be overestimated, resulting in overestimates of projected changes in global mean sea level ([[Ritz et al., 2015]]).
##### Stability mechanisms

- There are several mechanisms which could stabilise ice sheets from MISI:
	- Glacial isostatic adjustment reduces the gradient of retrograde beds.
	- The formation of ice rises produces pinning points beneath ice shelves, reducing their velocity and thus increasing backstress, reducing discharge over the grounding line.
###### GIA / Ice Rises

**Evidence**
- There is evidence that the grounding line of the West Antarctic Ice Sheet during the early Holocene retreated hundreds of kilometres inland of today's grounding line, before re-advancing ([[Kingslake et al., 2018]]).
- Glacial isostatic rebound has sufficiently stabilised processes, allowing retreat to half and reversing climate-initiated loss ([[Kingslake et al., 2018]]).

- Glacial isostatic rebound also results in the formation of ice rises, where localised ridges come into contact with ice shelves, providing a buttressing effect, causing a slowdown in glacier velocities and thickening ([[Wearing and Kingslake, 2019]]).
- The formation of Henry Ice Rise, West Antarctica, 6 kyr BP (± 2 kyr) increased buttressing from the Ronne Ice Shelf, enabling ice-sheet advance in the Weddell Sea Sector ([[Wearing and Kingslake, 2019]]).

**Future models**
- More recent geodetic investigations of crustal motions in the Amundsen Sea sector show that the upper mantle's viscosity beneath the region is significantly lower than expected ([[Barletta et al., 2018]]), causing GIA to occur at a much faster rate, occuring at a temporal scale fast enough (41 mm a-1; [[Barletta et al., 2018]]) to be able to reduce the steepness of retrograde beds in time to limit the vulnerability to MISI.
- Incorporating GIA into high spatiotemporal resolution models has demonstrated a 26.8% reduction in Thwaites Glacier's contribution to SLR over the next 350 years, showing that its vulnerability to MISI is less than originally thought ([[Larour et al., 2019]]).
###### Local SLR

- Whilst the melting of grounded ice contributes to increases in the global mean sea level, which at face value would increase the vulnerability of ice by placing more ice in contact with water, changes in sea level are heterogeneous.
- The loss of mass from ice sheets reduces the gravitational pull of the ice sheet, resulting in localised decreases in sea level ([[Kurtze, 2022]]). 
- Thus, assessing localised changes in sea level around ice sheets requires an in-depth understanding of where mass loss is occurring in order to accurately assess the gravitational pull of the ice sheet on sea levels.
- *Currently unconstrained in ice sheet models? Can't find anything else on this*?

#### Palaeogeological evidence for instability

- A lack of observational records limits the ability of numerical models to be validated over decadal to centennial time scales, which affects the assessment of the AIS’ vulnerability to MISI over these time scales.
- Therefore, longer-term dynamics of the Antarctic Ice Sheet associated with past periods of significant retreat must be assessed ([[Bart and Krarochvil, 2022]]).

- Exposure estimates used to constrain a numerical model of Mackay Glacier, EA, find that its rapid thinning and retreat in the early Holocene were driven by MISI ([[Jones et al., 2015]]).
- Palaeogeological evidence suggests that grounding lines have retreated much more rapidly than what is currently observed, indicating other processes may be at play ([[Bassis et al., 2024]]).

#### Marine Ice Cliff Instability

- "MICI is built on the premise that cliff-calving rates scale with ice thickness—if climate forcing drives ice margin retreat into the thicker ice found in the interior basins of West Antarctica, calving rates will increase (a positive feedback inherent to the geometry of the system), reinforcing retreat. In theory, this process could be arrested by exogenous changes in the terminal stress state that inhibit cliff failure (like the development of mélange or sea ice, or retreat into a narrowing fjord) or by compensating negative feedbacks in the system, such as acceleration and thinning, which could re-establish marginal ice shelves with thinner terminal ice cliffs" ([[Needell and Holschuh, 2023]]).
- Evidence is largely indirect and based from palaeogeological evidence and the noted lack of ice cliffs greater than 100 m in height ([[Edwards et al., 2019]]).
- The only potential evidence for MICI behaviour in the satellite record is Crane Glacier's response to the collapse of the Larsen B Ice Shelf in 2003 ([[Oppenheimer, 2019]]; [[Needell and Holschuh, 2023]]).
- Ice sheet models struggle to replicate the rates of historic SLR without the incorporation of MICI ([[Pollard et al., 2015]];[[DeConto and Pollard, 2016]]).

**[[Needell and Holschuh, 2023]] - Potential observations at Crane Glacier**

- Satellite remote sensing cannot provide direct evidence of ice cliff failure, however it can be used to record retreat and determine if behaviour is consistent with the critical requirements of the MICI hypothesis:
	- Terminus failed by cliff calving
	- Unforced acceleration of the calving rate associated with a taller terminal ice cliff (not compensated for by simultaneous terminal acceleration and thinning)
- Crane Glacier saw a rapid retreat following the collapse of the Larsen B Ice Shelf in 2002.
- Retreat stabilised in 2004 after a 10 km rapid retreat which reached rates of 8 km yr-1.
- The cliff height at its stable point was higher than its initial terminus height, indicating that if MICI was involved, there are other processes which resulted in stability, where MICI would otherwise hypothesise further retreat.
- Stabilised in the narrowest section of the fjord, suggesting that increased lateral drag from narrower margins reduced the calving rate to allow it to balance with discharge, permitting a stable terminus.
	- Stabilisation can also occur from changing bed conditions (e.g., prograde bed) (e.g., [[Wise et al., 2017]]) or retreat into ice whiche is not preconditioned for weaknesses
- Development of thicker sea ice reduced the calving rate, resulting in an advance and the development of an ice shelf.
- The ice shelf broke up after significant ponding in 2021, and the terminus retreated back to its more stable position in land.
- The maximum terminal cliff height was 111 m - under current models, terminal stresses at this height are below the failure threshold of ice.
- Thus, this implies that the ice was damaged, highlighting the importance of assessing ice damage in projecting future ice sheet behaviour.

**[[Wise et al., 2017]] - Palaeogeological evidence of Pine Island Glacier**

- Runaway calving due to MICI would be expected to produce a large number of relatively small icebergs which is in contrast with a low frequency (also seen in [[Kirkham et al., 2025]]).
- Analysis of iceberg-keel plough marks indicates many small icebergs and the absence of large tabular icebergs during ice retreat from a large grounding zone wedge between 12.3 and 11.2 kyr BP.
- Rapid retreat between 12.3 to 11.2 kyr BP until the grounding line stabilised on a prominent across-trough bathymetric ridge.

**Contrast: [[Morlighem et al., 2024]] - West Antarctic Ice Sheet may not be vulnerable to MICI in the 21st Century**

- Models worse case scenarios of MICI: no butressing, maximum calving
- A quick retreat does occur due to a cliff collapse, but it is quickly arrested.
- The acceleration of ice flow due to a retreat of the grounding line causes considerable thinning.
- Thus, whilst the ice may be thick upstream of the grounding line presently, making it vulnerable to MICI if the cliff reaches this ice immediately, by the time sufficient retreat of the terminus has occurred, this ice has thinned considerably, reducing its height to below the MICi thresholds.
- Thus, the processes of acceleration following ice shelf collapse and subsequent thinning act as negative feedback, which is able to stop retreat due to cliff failure - thus, the glacier does not retreat immediately further upstream in an uncontrollable manner, contrary to what would be expected under MICI.
- However, although these results suggest that the West Antarctic Ice Sheet is not vulnerable to MICI, it does not suggest that the West Antarctic Ice Sheet is as a whole stable. Thwaites Glacier is potentially subject to another positive feedback mechanism, MISI, owing to lying on a retrograde bed ([[Joughin et al., 2014]]). These results do not preclude the West Antarctic Ice Sheet from MISI.

#### Full buoyancy

- The grounding line of the former Norwegian Ice Sheet became ungrounded near-instantaneously upon approaching full buoyancy over a shallow-gradient region, resulting in grounding line retreat rates upwards of 600 m d-1  ([[Batchelor et al., 2023]]).
- Rates of retreat were calculated by measuring the distances between corrugation ridges.
- Corrugation ridges are formed when the ice sheet's retreating margin moves up and down with the tides, pushing seafloor sediments into a ridge for every low tide - ridges are thus produced twice a day.
- This style of retreat only occurs across relatively flat beds, where less melting is required to thin the overlying ice to the point where it starts to float.
	- *Prograde beds too then?*
- This has implications for the current AIS because Thwaite Glacier’s bed has a very shallow gradient only 4 km upstream of its current grounding line position

### Ice Shelf Collapse - case study overview

#### Larsen B

- Collapsed in March 2002, following widespread surface ponding and hydrofracture ([[Scambos et al., 2003]])
- >2,750 supraglacial lakes developed during the decade prior to break up ([[Scambos et al., 2000]]; [[Scambos et al., 2003|2003]]; [[Scambos et al., 2009|2009]]).
- Caused a 6 times speed up of glaciers feeding it following its collapse ([[Scambos et al., 2004]]).
- Broke-up rapidly through a chain-reaction of lake drainages. Lake-drainaged-induce stresses set the fracture spacing small enough to allow for sufficiently small icebergs relative to their height, which enables capsize-driven breakup ([[Banwell et al., 2013]]).
- More in [[_Part II Glaciology#Case Studies|Atmospheric Rivers Case Studies.]]
#### Conger Ice Shelf 

**From [[Walker et al., 2024]]:**

- First observed ice shelf to have collapsed in East Antarctica.
- Collapse in March 2022 was the culmination of 25 years of thinning.
- Did not collapse due to widespread surface melt causing disintegration, unlike the Larsen B ice sheet ([[Scambos et al., 2004]]). The different mechanism of ice shelf collapse highlights the need to reconsider ice shelf collapse in model scenarioss - existing models parameterize collapse as a function of surface melt ([[Seroussi et al., 2020]]).
- L-band brightness temperatures suggest temporal variability deeper in the ice shelf, suggesting deep-sea water infiltration, which became more pronounced in the months preceding collapse.
- Suggests the degradation of the structural integrity of the ice shelf via both surface and basal structures that became seawater-filled.
- Basal thinning means the base of the ice sheet sits in higher water, causing it to come into contact with increased ocean heat in the upper water column, further enhancing basal melt, causing further thinning which makes the ice shelf more vulnerable to collapse.
-  [[_Part II Glaciology#Case Studies|Atmospheric Rivers Case Studies]].

## Ice Shelf (in)Stability

- Governed by the pooling of meltwater, which can drive hydrofracture and ice shelf collapse.
- The 'Greenlandification' ([[Rodehacke et al., 2020]]; [[Bell et al., 2018]]) of Antarctica refers to Antarctica's response to climate change, in particular, it ice shelves, where the surface hydrology is beginning to resemble that of Greenland's present day ablation and percolation zones.

**[[Davison et al., 2023]]**
- Present mass budget of all Antarctic ice shelves between 1997 and 2021.
- Out of 162 ice shelves, 71 lost mass, 29 gained mass, and 62 did not change mass significantly. Of the shelves that lost mass, 68 had statistically significant negative mass trends, 48 lost more than 30% of their initial mass, and basal melting was the dominant contributor to that mass loss at a majority (68%). 
- Quantifying the components of the mass budget enables the understanding of the changes of mass loss (/gain)
- Mass loss is primarily through basal melting rather than calving.


**[[Lai et al., 2020]]**
- The ice shelves that will control the ice sheet's response to atmospheric warming are those that are at in the intersection of:
	- Provide active buttressing to the ice sheet
	- Are vulnerable to meltwater driven collapse via hydrofracture
	- Have meltwater present
- Ice will hydrofracture if local stresses allow - higher tensile stresses promote hydrofracture. Regions actively buttressing have lower tensile stresses due to the backstress from buttressing. Therefore, the areas most vulnerable to hydrofracture do not necessarily provide the most butressing.
- Fractures are identified using a deep convolutional neural network
- Access the stability of fractures using linear elastic fracture mechanics
	- Vertical propagation of a stable fracture stops when it is too energetically costly to break the ice further. By contrast, unstable fractures propagate through the entire ice thickness
- Fractures can form on both the surface and base of ice shelves and their stability depends on the tensile resistive stress
- Upon theoretical inundation of all ice shelves with meltwater filling fractures, the study finds that 60 ± 10% of the total area of Antarctica's ice shelves would be vulnerable to hydrofracture.
- When assessing regions where melt is currently observed in supraglacial lakes ([[Stokes et al., 2019]]), only 0.6% of East Antarctic ice shelves fit all three criteria - provide active buttressing, experience meltwater ponding, and are vulnerable to hydrofracture.
	- *I would consider this an example of survivorship bias, which is not discussed by Lai et al. (2020). It would be expected that only a very small proportion of ice shelves are found to be be vulnerable to all three due to retrospective observational sampling. If all three characteristics are present, it is likely that hydrofracture has occurred previously, either draining surface meltwater, or resulting in ice shelf collapse (e.g., Larsen B), thereby excluding it from the dataset. This methodological limitation therefore likely underrepresents the true risk of meltwater-induced collapse. Increased firn air content depletion and the expansion of melt is likely to spread to other vulnerable regions important to buttressing.
- Presence of lakes does not necessarily indicate vulnerability - indeed large meltwater ponds have persisted in numerous locations for decades, for example on George VI ice shelf ([[Kingslake et al., 2017]]). They can persist in regions of low tensile resistive stresses which are resilient to hydrofracture.
- Future warming will expand the region of meltwater ponding, especially considering depleted firn air content, indicating that meltwater ponding could spread to many of the buttressing and vulnerable regions.

### Instability mechanisms:

**[[Dunmire et al., 2020]] - Evidence for hydrofracture draining in land**
- Buried lake first discovered by a Belgian field team in February 2016 near the grounding line - 1 km inland of the Roi Baudouin Ice Shelf
- Upon returning in 2017, they found that the lake had drained causing an ice surface lowering and the formation of a series of ice ridges and blocks on the surface, evidence of a rapid drainage event - similar to seen in Greenland ([[Tedesco et al., 2013]])
- Use GPR transects to show that the buried lake drained via vertical fractures, providing the first direct evidence of hydrofracturing on the Antarctic Ice Sheet.
- Fracture are reactivated by meltwater and are advected onto the ice shelf, providing structural weaknesses in the ice-shelf surface (*which can precondition it to being vulnerable to future melt events*)

- Satellite-derived DEM differencing agrees with field GPS observations
- Hydrofracturing in land of the grounding line provides evidence of a possible link between the supraglacial, englacial, and even potentially the subglacial hydrologic network, for which limited evidence exists ([[Bell et al., 2018]])
- If connections exist, supraglacial hydrology will be able to have an impact on subglacial dynamics ([[Tuckett et al., 2019]])
- Lake forms annually within the same topographic depression.
- The Greenland Ice Sheet is a self-regulated system, whereby surface melt volume is not correlated with annual ice flow velocity in marginal regions where melt is sufficient ([[Tedstone et al., 2015]]) - thus, surface lake drainage events have less of an impact on basal lubrication and ice flow ([[Poinar et al., 2017]]).
- However, Antarctic ice shelves are much more vulnerable to meltwater-induced flexure and fracture, threatening ice shelf stabiliy ([[Banwell et al., 2013]]) and mass loss from the Antarctic Ice Sheet as a whole.

**[[Alley et al., 2016]] - basal channels**:
- Use satellite imagery, airborne ice-penetrating radar and satellite laser altimetry between 2002 and 2014 to map basal channels in the ice shelves surrounding Antarctica.
- Methods only detect large channels which are sufficient in size to cause detectable depressions on the ice shelf surface - channels are typically 1-5 km across and incised 50=250 m into the ice shelf base.
- Study catagorises three channel types:
	- Ocean-sourced which do not intersect the grounding line 
	- Subglacially-sourced which begin immediately at the grounding line at a location where subglacial meltwater is predicted - subglacial meltwater forms buoyant plumes which carves channels
	- Grounding-line-sourced which intersect the grounding line but do not necessarily correspond to a modelled subglacial outflow point 
- Find a significant positive correlation between basal channel density and basal-melt rate, suggesting that warm water plays an important role in their formation. 
- West Antarctic Ice Sheet, and in particular the Amundsen Sea Sector, has the highest basal channel density
- Also a positive correlation between channel density and maximum grounding line depth (using Bedmap2), implying that CDW is responsible for creating these basal channels due to it mainly affected ice shelves with deep ice drafts.
- 93% of basal channels in the Amundsen Sea Sector are ocean-sourced.
- Basal channels appear to lead to structural weakening by concentrating basal melt. The margin of the Roi Baudouin Ice Shelf has split along a basal channel. 
- Also, crevasses have formed at the tip of the Scott Peninsula along the shear margin of the Getz Ice Shelf.

### Stability mechanisms:

**[[Trusel et al., 2022]] - Lake drainage controlled by tidal variations rather than reaching a threshold**:
- Document repeated, abrupt drainages of a supraglacial lake at the grounding zone of Amery Ice Shelf, East Antarctica between 2014 and 2020.
- Find that lake drainage occurs near peaks in tidal amplitude and therefore hypothesize that hydrofracture is assisted by tidal flexure of the ice shelf.
- Surface depressions inherent to grounding zones provide basins for water accumulation. Melt is also enhanced here due to wind-albedo feedbacks ([[Lenaerts et al., 2017]])
- Their drainage could represent a mechanism which potentially safeguards ice shelves from enhanced meltwater production.
- Provides a mechanism for runoff to reach the sub-ice shelf ocean cavity
- High tides induce strong tensile stresses at the base, promoting basal fracture. Low tides transfers strong tensile stresses to the surface, potentially supporting hydrofracture.

**[[Bell et al., 2017]] - Surface river evacuating surface melt:**
- The presence of a river on the Nansen Ice Shelf has been documented since Ernest Shackleton's Nimrod expedition in 1909
- Documented 15 m deep and 50 m wide channel
- Surface meltwater is able to be evacuated off an ice shelf through a supraglacial hydrologic system which evolves as melt increases.
- Therefore, this decreases the capacity for meltwater to pond, reducing the vulnerability to meltwater induced hydrofracture.
- Rivers form when the ice-surface slope is sufficiently steep and the storage capacity in firn aquifers, ponds, and crevasses is limited. The slope of ice shelves are strongly controlled by the thickness of incoming ice and the basal melt rate (also where basal melt is concentrated).
- A key question is establishing whether Nansen-esque rivers could form on other ice shelves.
- Rivers could also be possible inland on Amery, FIlchner-Ronne, Larsen C, and Ross ice shelves which are otherwise thought to disintegrate quickly within the next century ([[DeConto and Pollard, 2016]]).
- An accurate assessment of ice shelf drainage is required for accurately projecting the future of ice sheets and their potential contribution to changes in Antarctic discharge.
- Similar rivers are on Petermann Glacier, Greenland ([[Boghosian et al., 2021]])
- Other citation: ([[Kingslake et al., 2017]])

### Firn Processes

- Ocean-driven processes have previously dominated Antarctic mass loss, whilst mass loss due to meltwater runoff has been largely negligible ([[Lenaerts et al., 2019]]; [[Rignot et al., 2019]])
- With rising temperatures, surface processes will play a larger role in mass loss.
- Increased surface runoff poses a significant risk to ice sheets and shelves, as surface water pools, making ice vulnerable to hydrofracture ([[Scambos et al., 2004]]; [[Stokes et al., 2019]]).
- Thus, it is important to assess the capability of Antarctica's firn to store meltwater, which can be assessed by the melt-over-accumulation ratio ([[van Wessem et al., 2023]]).
- If accumulation is greater than melt, then firn, which becomes saturated by meltwater, is replenished by freshly fallen snow. If the rate of melt is greater, then firn air content becomes depleted, reducing its capacity to hold meltwater, which can result in saturation, and thus, ponding.
- Theoretical considerations imply that an MOA exceeding 0.7 would result in the pore space within firn no longer being maintained, and meltwater runoff and/or ponding is initiated ([[Pfeffer et al., 1991]]).
- The MAO threshold is spatially variable and is linked to temperature through temperature's impact on snowfall and subsequent melt.
- Very dry areas of Antarctica, which have low accumulation rates, have their firn replenished at a very slow rate, making them vulnerable to surpassing their MAO thresholds at lower temperatures than typically thought, as a lower volume of meltwater is required to result in saturation ([[van Wessem et al., 2023]]).
- Antarctica's dry ice shelves, e.g., Amery, Ross, and Filcher-Ronne, can reach their thresholds at a -15 degree C annual 2 m air temperature, whilst original estimates were -5 degrees ([[van Wessem et al., 2023]]).
- Due to their lower thresholds, less warming is required to reach the MAO threshold, making dry areas vulnerable to even the lowest of warming scenarios.
- For instance, Amery Ice Shelf's MAO threshold is reached at ~-19 degrees C, which is only 0-1 degrees warmer than current temperatures ([[van Wessem et al., 2023]]).
- Suggests that Amery Ice Shelf is close to 80% MOA ([[Stokes et al., 2022]])

#### Ice Slabs

- Not only does firn need to be present, but it needs to be accessible beneath permeable horizons ([[Culberg et al., 2021]]).
- Extreme melt events can result in the formation of impermeable ice lenses and slabs, which act as a barrier to percolation, preventing meltwater from reaching the firn beneath ([[Culberg et al., 2021]]).
- 2012 extreme melt season in Greenland, which caused 97% of the ice sheet surface to melt, formed a near-surface melt layer - ice slab - restricting vertical percolation. This slab was still present in 2017, though had been buried by around 5 m of new snow/ice ([[Culberg et al., 2021]]; [[Jullien et al., 2023]])
- Frequency of extreme melt seasons relative to the rate at which pore space regenerates is a key determinant of firn's multi-year response to surface melt ([[Jullien et al., 2023]]).
- Extreme melt events (e.g., 2019) in the future are more likely under climate change (IPCC), meaning that ice slabs will play a greater role in modulating Greenland's surface hydrology. Indeed, ice slabs are expanding in surface area and reaching higher elevations ([[Jullien et al., 2023]]).
- Extreme melt events expand the spatial area of melt, thereby preconditioning the ice surface for ponding in areas that would otherwise not have approached firn saturation ([[Siegert et al., 2023]]; [[Wille et al., 2019]]).

#### Observations

- Remote sensing has revealed the presence of meltwater slush and ponding on Antarctic ice shelves and further inland of the grounding line in East Antarctica, indicative of the absence of sufficient firn porosity to absorb surface melt ([[Dell et al., 2024]]. [[Stokes et al., 2019]]).
- The presence of slush decreases the surface albedo of ice, and when included in models of snowmelt, forced by climate models (e.g., RACMO), surface melt is on average 2.8 times higher ([[Dell et al., 2024]])
- Thus, it is important for slush to be incorporated into model estimates of melt.
### Atmospheric Rivers

- Atmospheric rivers are narrow, elongated corridors of intense moisture transport that facilitate up to 90% of the total poleward water vapour flux from the lower latitudes ([[Wille et al., 2022]]; [[Nash et al., 2018]]).
- The delivery of warm, moist air contributes both to increased accumulation and ablation, contributing either positively or negatively to surface mass balance ([[Wille et al., 2022]]).
- Atmospheric rivers only occur 1% of the time at a given location along the Antarctic coastline, yet they are associated with 13% of the annual total precipitation and 35% of the interannual variability in precipitation over Antarctica ([[Wille et al., 2021]]).
- ~12 events per year ([[Wille et al., 2019]])
- In some cases, a single event can deliver nearly 10% of a region's annual snowfall in a matter of days ([[Bozhurt et al., 2024]]).
- Foën winds can flow down Antarctic Peninsula onto the Larsen Ice Shelves ([[Wille et al., 2019]]).
- Increased water vapour results in increased cloud cover, which on the one hand reduces the shortwave solar radiation flux, but increases the longwave radiative flux through clouds' enhancement of the greenhouse effect. Mixed-phase clouds act to reduce radiative cooling during the night-time by increasing the downward longwave radiation when the incoming shortwave radiation is small, which has been shown to decrease meltwater refreezing ([[Wille et al., 2019]]).

#### Impacts on ice shelves

- Atmospheric rivers result in extreme temperatures, melt, runoff, and swell events, all of which are detrimental to ice-shelf stability.
- Strong ARs were precursors for more than 60% of the major calving events of the Larsen A and Larsen B ice shelves since 2000 and precluded their main collapses ([[Wille et al., 2022]]).
- The Larsen C is the most sensitive to ice shelf on the Antarctic Peninsula to AR-induced temperature changes, having the greatest regional warming during an AR, owing to the region's topography.
- Wilkins Ice Shelf may more less sensitive to ARs due to lying on, typically, the windward side of the Antarctic Peninsula, meaning it is less conducive to AR-triggered foën events.
#### Case Studies

**[[Bozhurt et al., 2024]] - July 2023**

- Temperatures on the northern Antarctic Peninsula rose to 2.7 degrees in July 2023 (austral winter), resulting in rainfall rather than snowfall.

**[[Wille et al., 2022]] - January 2008**

- Caused a disintegration and fragmentation of nearly all land-fast ice in the Larsen A and B embayments, generating 6.3 Gt of runoff, which was followed by a calving event 6 days later.
- The calving event resulted in a 11 km retreat of the eastern region of the remnant Larsen B ice shelf.

**[[Wille et al., 2022]] - July 2017**

-  A winter AR occurred 5 days before the calving of the A68 iceberg on July 10-12, 2017 from the Larsen C ice shelf.
- It is possible that the AR applied a wind stress before calving; however, the impacts of winter ARs on ice-shelf stability are unclear, as they generally produce lower melt values compared to the summer melt season.

**[[Wille et al., 2024a]], [[Wille et al., 2024b|2024b]]; [[Walker et al., 2024]] - Conger Ice Shelf Collapse March 2022**

- The Conger Ice Shelf collapsed on March 16, 2024, coinciding with a record-breaking heat wave caused by an atmospheric river, thereby raising questions on whether the two events were linked.
- Temperatures anomalies were between 30-40 degrees C, resulting in recorded temperatures of -9.4 degrees at Concordia Station, which rivals even summer maximums ([[Wille et al., 2024a]])
- Sentinel-1 backscatter measurements do not show meltwater presence until after its collapse, indicating that the ice shelf did not break up via hydrofracture ([[Wille et al., 2024b]]).
- Calving events between 5-7th March caused the shelf to lose its pinning point on Bowman Island.
- Record-low sea ice ([[Turner et al., 2022]]) meant that the shelf front was a) not buttressed by sea ice and b) was exposed to swells, which destabilise ice shelf fronts ([[Wille et al., 2022]]).
- Thinning at its base, due to deep-sea water intrusion, degraded the structural integrity of the ice shelf ([[Walker et al., 2024]]), a process that occurred over a 25-year period.
- Thus, collapse was not specifically caused by high levels of coastal melt and rainfall brought by the AR, but cyclonic conditions which are typically associated with ARs, coupled with a steady thinning at its base and surface from surface and basal melt, brought about calving, dislodging the shelf from Bowman Island, causing collapse.
- Despite record-high temperatures, the autumn occurrence delivered a significant amount of snowfall, which caused the Antarctic Ice Sheet to experience a record positive mass balance of +296 Gt, equivalent to mitigating 0.81 mm of SLR.

**[[Nicholas et al., 2017]] - January 2016**

- Enhanced surface melt due to residual clouds and precipitation water following an AR in January 2016 over Ross Ice Shelf and Marie Byrd Land.

#### Future impact

- Determining the future impact of ARs is strongly sensitive to the thresholds used for AR detection.
- Wille et al. ([[Wille et al., 2021|2021]]) identify ARs as those where the polar integrated vapour transport is at or above the 98th percentile from 1980 to 2018.
- Air's moisture capacity increases exponentially with air temperature due to the Clausius-Clapeyron effect ([[Zhang et al., 2024b]]). Consequently, with climate warming, the frequency of ARs will increase relative to current thresholds, as the 1980-2018 98th percentile will be more likely to be surpassed.
- Indeed, Maclennan et al. ([[Maclennan et al., 2025|2025]]), using CESM2, find that the frequency of ARs over the Antarctic Ice Sheet doubles when applying present-day thresholds, occurring for 6 days per year at a given location.
- However, when the threshold is appropriately scaled to account for the increased capacity to hold water vapour, future AR frequencies are similar to those of the present day ([[Maclennan et al., 2025]]).
- Given that their definition requires settting a threshold, their future frequency (and thus impacts) is sensitive to the threshold chosen ([[Maclennan et al., 2025]]).

- Using present-day vIVT thresholds for future AR detection, AR precipitation increases 2.5 times over Antarctica over 2066-2100, rising to 1012 ± 138 Gt yr-1 (2.8 mm SLR equiv) ([[Maclennan et al., 2025]]).
- Increases in AR precipitation outpace increases in total precipitation, causing the relative contribution of ARs to total precipitation to rise to 24 ± 2% (from 13 ± 0.6%) ([[Maclennan et al., 2025]]).
- Though, when using adjusted thresholds, the relative contribution of ARs remains the same.
- Despite no change in the relative contribution of ARs when using adjusted thresholds, they do contribute to more rainfall (up to 40 mm w.e. yr-1) ([[Maclennan et al., 2025]]).
- Given the compounding impacts of rainfall in Antarctica, including the raising of firn temperatures through refreezing of liquid water, reduction of surface albedo, firn air depletion, and ice erosion – all of which precondition the surface for widespread melting ([[Amory et al., 2024]]).
- Ultimately, how we detect Antarctic ARs and attribute precipitation in the present-day, and how we adapt these methodologies to future climate states, will determine how we describe the importance of ARs in the Antarctic climate system.


## Greenland

**[[Wood et al., 2021]] - Ocean forcing drives glacier retreat in Greenland**

 - Study of the retreat of 226 marine-terminating glaciers between 1992 and 2017 using a combination of in situ, remote sensing, and modelling methods, and classify 139.
 - Glaciers terminating in deep, warm water (53%) accounted for 49% of mass loss
 - Glaciers terminating in shallow, cold polar water (17%) accounted for 3% of mass loss
 - Glaciers terminating on shallow ridges (19%) accounted for 9% of mass loss
 - Glacier with long floating ice tongues which terminate in deep fjords (7%) accounted for 22% of grounded ice retreat and 15% of mass loss.
 - Ocean warming paused between 2008 and 2017; however, despite a reversion to the initial ocean state, ice fronts kept retreating, suggesting that sustained dynamic thinning at glacier margins, induced by an initial ocean warming, led to an unstable configuration of the glaciers, which could not reach a new equilibrium state.

**[[Hill et al., 2021]] - Petermann Glacier Future**

 - Petermann drains 4% of the Greenland Ice Sheet ([[Münchow et al., 2014]]).
- Catchment holds 0.41 m of SLR equivalent. 
- Modelling shows that under several future scenarios of ice shelf thinning and retreat, the removal of the ice shelf will not contribute substantially to SLR (< 1 mm)
- The initial retreat of the grounding line is over a shallow retrograde slope, 8 km inland.
- Bed slope is known to impact the stability of the glacier grounding line ([[Schoof, 2007b]])
- The grounding line stabilises at a topographic high ~12 km inland of Petermann's current grounding line position.

**[[Millan et al., 2022]].- Petermann Glacier Observations**

- Calculate the grounding line retreat rate as a simple function of ice thickness ([[Rignot et al., 1998]]) down a retrograde bed.
- The majority of retreat in the central sector grounding line took place between 2017 and 2021 where is receded more than 5 km along a retrograde bed, grounded 500 m below sea level.
- Warm water erosion/melt of the base through a thermal forcing of 0.3 degrees C due to the intrusion of Atlantic water, results in a modelled grounding line which aligns more closely with observed grounding line retreat rates (1.6 km yr-1), which are unable to be driven from dynamic thinning.
- Thus, retreat is caused more by rising ocean temperatures enhancing melt at the base rather than dynamic thinning due to increased surface melt.

**[[Catania et al., 2018]] - Western Greenland Geometric Controls**

- Retreat of tidewater glaciers between 1999 and 2016 is coincident with the northward movement of warm Atlantic Water, due to climate modes operating in the North Atlantic
- Study finds that the amount of retreat is very strongly related to the length of the overdeepening behind the terminus at retreat onset.
- Basal geometry is not the only geometry controlling grounding line retreat. Narrow points in the fjord's width are able to pin the grounding line by enhancing lateral drag, seen on Kangilerngata Sermia Glacier, which stabilised on a retrograde bed, which would otherwise be predicted to have resulted in unstable retreat ([[Schoof, 2007b]])
- Furthermore, enhanced ice flux during Kangilerngata Sermia's retreat exceeded the melt rate, perhaps also contributing to stabilisation ([[Rignot et al., 2016]]).
- Runoff and ocean temperatures pushed glaciers into a new state, but fjord topography is largely responsible for modulating the response to external forcings.

**[[Amundson et al., 2010]] - Ice Mélange at Jakobshavn Isbræ**

- Mélange plays a role in terminus dynamics and stability by providing a buttressing effect.
- The growth of sea ice stiffens the mélange matrix by binding iceberg clasts together, preventing the calving of full-glacier-thickness icebergs, enabling several km of terminus advance.
- Break-up of mélange in the summer results in terminus retreat. Thus, models of terminus behaviour require the accurate seasonal variations in the calving rate.

- Thinning rates slowed from 2014 and the glacier thickened and readvanced between 2016-2019 ([[Khazendar et al., 2019]]).
- Joughin et al. ([[Joughin et al., 2020|2020]]) suggest that ocean-induced mélange changes control dynamics rather than through submarine melting. 
- Therefore, projections of glacier contributions to future SLR based solely on glacier geometry are insufficient, and accounting for external forcing is crucial.

**[[Rignot et al., 2021]] - Humboldt Gletscher**

- Between 1972-2019, Humboldt Gletscher lost 161 Gt of ice, the fourth largest contribution from Greenland's outlet glaciers
- Humboldt is the widest glacier in Greenland at 100 km wide, moves slowly (<100 m yr-1), and has a minimal ice tongue (25 km2 - compared to 100 km wide front, this is minuscule) - its original ice tongue disappeared between 1996 and 2017.
- Find that increased undercutting due to warm water (1.7 degrees C increase since 1948) explains 70% of retreat.
- A posteriori observations suggest that the calving of grounded ice blocks does not significantly impact the retreat of Humboldt Glacier, as thinning at both the base and surface explains 100% of the modelled retreat, which aligns well with observations.
- Finds that the fjord is 200 m than previous estimates ([[Morlighem et al., 2017]]), permitting the intrusion of more warm water (Type 1, [[Wood et al., 2021]]). Highlights the need for an accurate assessment of the bed topography.

**[[Zhao et al., 2025]] - Jakobshavn Isbræ future modelling**

- Evaluate the effectiveness of geoengineering by adding a barrier to deep water intrusion by raising the elevation of Jakobshavn Isbræ's inlet.
- Regardless of the barrier height or climate forcing scenario (even setting the forcing back to pre-2000 levels), the results indicate retreat along a retrograde bed that extends 40 km inland.
- The inability to reach a stable state under any future climate forcing indicates that the glacier has surpassed the tipping point of MISI.
- Other fjords have potential: Zacharia Glacier, northeast Greenland, has been in disequilibrium since 2003 ([[Mouginot et al., 2015]]) and is one of two glaciers draining the northeast Greenland ice stream, which drains 12% of the ice sheet.
- Observations at nearby 79 N Glacier suggest the intrusion of warm water.

# Concluding statements

- Antarctic Ice Sheet will contribute 0.28 m by 2100 - greatest uncertainty is in the type of model followed by future scenario ([[Seroussi et al., 2024]])
- Even with limiting warming to 1.5 m, thermal lock in will result in several meters of sea level rise in the next few centuries ([[Stokes et al., 2025]])
- Temperatures will have to be cooled to +1 degree relative to the pre-industrial average in order to protect low-lying coastal communities ([[Stokes et al., 2025]])

# Revision Lecture Notes

## Section 2:

- Stresses in ice sheets
- How are stresses estimated
- How are stresses incorporated into models
- Processes that affect ice sheet thermal strcture
- Hw can these processes influence ice flow
  How can these processes be incorporated into ice flow models 
- Idea of hydrology as a control on ice flow - how is this incorperated into models
- How geomoetrphic data, model reconstturctions and knowledhe of erosions and ddeposition processes to reconstruct palaeo water flow and landform development

- Knowledge of erosion and sedimentation comes from temperature valley glaciers
- Limit of high resolution shallow level data in offshore locations because industry is mostly concerned with deeper down.
- Though, wind farm geological surveys have presented a new opportunity for higher resolution data closer to the surface
- Slow aquifer freeze in winter releases latent heat \- can be detectedish by sentinel SAR
- 90s saw increase in outlet glaciers, but nvm just [[Enderlin et al., 2014]] stuf
- Slabs as perched acuitards

- Don't need to explain 1B processes in detail
- 