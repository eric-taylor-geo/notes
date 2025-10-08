2025-04-07 20:08

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology|Glaciology]]

DOI:

URL: https://onlinelibrary.wiley.com/doi/10.1002/esp.4973

Tags: [[Glaciology - Debris]]

Status:
# Geomorphological evolution of a debris-covered glacier surface

"There exists a need to advance our understanding of debris-covered glacier surfaces over relatively short timescales due to rapid, climatically induced areal expansion of debris cover at the global scale, and the impact debris has on mass balance."

Use UAVs and DEM differencing with debris thickness and stability modelling to understand the evolution of Miage Glacier's debris cover between 2015 and 2018

Differencing maps provides insights into the patterns and mechanisms of debris redistribution -> *disslink* for discusison

# Introduction

- "The advection of supraglacial debris is classically regarded as a ‘passive’ form of glacial sediment transport, in so far as it relates to the evolution of clast morphologies (Boulton, 1978). However, this classification masks the geomorphological dynamism of debris-covered glacier surfaces, which, topographically and sedimentologically, are continuously evolving due to the interplay of ablative (e.g. Immerzeel et al., 2014; Buri et al., 2016; Miles et al., 2018), mass movement (Benn and Owen, 2002; Moore, 2018), and weathering processes (Owen et al., 2003), as well as ice flow and dynamics (e.g. Kraaijenbrink et al., 2016; Mölg et al., 2019)"
- "The various gravitational, often meltwater-aided, processes which redistribute debris locally across glacier surfaces (so-called ‘secondary dispersal’) have been observed (e.g. Thompson et al., 2016) and quantified (Moore, 2018; Nicholson et al., 2018) to a limited degree."
- ‘Primary dispersal’ relates to the mechanism by which debris is spread across a melting ice surface as the result of its emergence from migrating outcrops of septa ([[Kirkbride and Deline, 2013]]). Debris may emerge from such septa where adjacent glacier flow units converge and elevate sediment to the supraglacial zone to form medial moraines (e.g. Small and Clark, 1974; Eyles and Rogerson, 1978; Anderson, 2000; [[Mölg et al., 2020]]), and from numerous discontinuous debris bands associated with rockfall delivery to the glacier surface in the accumulation zone. Debris may also emerge from flow-transverse debris septa hypothesized to form as the result of the elevation of subglacial sediment or crevasse-fill (Kirkbride and Deline, 2013). However, the most likely origin for much of the emerging debris is via passive melt-out of englacial, foliation-parallel debris septums, rather than thrusting. For glaciers with a negative mass balance, an imbalance exists between rates of debris supply to the glacier and the glacier's ability to evacuate this debris at its margins (Kirkbride, 2000). In turn, a debris cover may develop and expand
- ![[Pasted image 20250407201632.png]]

**Corrections for glacier flow**

- "To arrive at a set of DEMs which can be differenced to yield vertical surface change on an actively flowing glacier it is necessary to isolate and account for the components of glacier flow and their uncertainties, namely horizontal surface movement, u, and vertical displacement due to valley slope, ɑ, and flux divergence, w_e"
- "These data represent surface change, which is the product of net ablation, englacial debris emergence and surface debris layer thickening, and surface debris redistribution, which can manifest as either debris thickening or thinning"
- ![[Pasted image 20250407201855.png]]
**Distributed debris thickness mapping**

- use [[Rounce et al., 2018]] [[Rounce et al., 2015]] sub-debris ablation model
- Also uses Monte Carlo simulations to quantify uncertainty -> *disslink*
- Use AWS and ERA5 reanalysis to force model
**Differencing:**

- Use quadrative sum same as [[Stewart et al., 2021]] to determine significant changes
- " Thresholded debris thickness change data (_∆h_) were analysed as a proxy for tracking spatio-temporal patterns of debris redistribution. Our debris thickness change detection threshold is non-linear; because we find increasing uncertainty with decreasing debris layer thickness estimates, we require a larger relative change in debris thickness in areas of thinner debris for this change to register as significant; for instance, for a debris layer thickness of 0.05 m, change must exceed 0.03 m (i.e. 62% of the initial debris thickness) to be deemed significant. For thicker debris, the relative threshold is lower; i.e. for an initial debris thickness of 0.5 m, the relative change threshold is 25%, or 0.12 m, but larger in absolute terms."

**Limitations:**

- "Gridded debris thicknesses represent mean debris thickness for a given differencing period and are not therefore specific to a given date"
- "Accordingly, we have the most confidence in our debris thickness estimates in areas where debris cover has remained relatively stable and experienced no significant debris redistribution during the differencing period." -> *disslink: not very useful for detecting changes in debris thickness.*

## Results

![[Pasted image 20250407204058.png]]
- *disslink -> I really like this image -> I think it's important to clarify the difference between snow and non-significant delta h in images as rn you can't tell in mine*
![[Pasted image 20250407205818.png]]
- okay that's a really cool picture

## Discussion

- Our surface lowering results show that patterns of ablation vary over space and time and can vary by over an order of magnitude over relatively short spatial scales (Figure [6](https://onlinelibrary.wiley.com/doi/10.1002/esp.4973#esp4973-fig-0006)), primarily due to variations in debris thickness (Figure [7](https://onlinelibrary.wiley.com/doi/10.1002/esp.4973#esp4973-fig-0007)). Overall year-to-year variations in ablation for a given location are determined firstly by annual variations in meteorological forcing, and debris thickness, and secondly by more localized effects, such as proximity to patches of snow cover (which can exert a net cooling effect), topographic shadowing, and other various meso- and micro-scale controls on the surface energy balance, which we do not consider due to computational limitations, and a lack of empirical knowledge of these effects.
- We found the thinnest debris cover on steep, western-facing slopes, and the thickest on slopes with a northerly aspect, which broadly mirror the findings of [[Nicholson et al., 2018]] who found that debris tended to be thicker on slopes with a north-westerly aspect on Khumbu Glacier
- Ice cliff evolution serves as an efficient mechanism for debris remobilization [[Nicholson and Mertes, 2017]]
- Mass conservation suggests that rates of loss and gain should cancel each other, however, re-sorting of material as it cascades down the cliff face may go some way to ‘undoing’ the compaction that debris cover may experience over time by reducing layer density ([[Anderson and Anderson, 2018]]), and may account for the thicker mean debris thicknesses at ice cliff toes compared to their crest source areas
- We discovered that: (i) debris thickness generally increases with slope-distance (i.e. distance from a slope crest along the path of steepest descent; Figure [14C](https://onlinelibrary.wiley.com/doi/10.1002/esp.4973#esp4973-fig-0014)) and (ii) the rate at which the debris layer thickens also increases with slope-distance (Figure [14D](https://onlinelibrary.wiley.com/doi/10.1002/esp.4973#esp4973-fig-0014)).
- ![[Pasted image 20250408005804.png]]
- Based on the spatiotemporal patterns of topographic evolution in our data, such estimates appear sound; over a three-year period, we clearly observe the progression of various mechanisms that contribute to topographic inversion.
- These findings conform with those of [[Mölg et al., 2020]] who found that high relief areas on a debris-covered glacier surface can develop from an initially smooth glacier surface over a period of two decade

Also uses ERA5 for one period due to no AWS data