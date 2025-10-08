2025-05-08 14:42
2025-05-08 14:42

Paper: [[_II - Natural Hazards]]

DOI:

URL: https://www.nature.com/articles/s41586-019-1606-4

Tags: [[Natural Hazards - Earthquakes]]

Status:
# Real-time discrimination of earthquake foreshocks and aftershocks

- After large earthquakes, there are questions of whether it was the main shock or a foreshock to an even stronger earthquake yet to come.
- This affects the public and decision-makers with respect to the recovery from an earthquake

## Main

- crustal moderate-to-large earthquakes are followed by a decaying aftershock sequence which typically lasts for years.
- In some cases, this decaying sequence is interrupted by an even larger, and often more destructive, subsequent mainshock. One of the biggest unknowns in real-time seismic hazard assessment during an ongoing seismic sequence is whether the largest event—the mainshock—has already happened or is still to come
- From a statistical perspective, the probability that after a moderate earthquake event an even larger event occurs within 5 days and 10 km is typically 5% [[Roeloffs and Goltz, 2017]][^1] - understanding this provides the short term earthquake probability (STEP), and algorithms such as epidemic type aftershock sequences (ETAS) can be used for operational earthquake forecasting
- From a physics perspective, the probability of a subsequent larger mainshock depends on the stress conditions established by previous events and the long-term tectonic stress conditions, which are typically unknown [[Parsons et al., 2014]][^2]
	- Attempts at physical models have not provided any advancement from statistical models

- Authors exploit the fact that the time after a moderate or larger mainshock is the most data-rich period during the earthquake cycle, with thousands of aftershocks or potential foreshocks occuring witin hours - allows for the observation of spatial and temporal changs at resoluiotns 1-10,000 times higher than normal conditions.
- B-values from the Gutenberg-Richter law ([[Gutenberg and Richter, 1944]]) typically increase by 20% following a mainshock ([[Gulia et al., 2005]]).
- Authors thus propose that b-value sequences which divert from this typical increase are of a high concern and are indicative of a subsequent larger event still to occur.
- Thus, real-time monitoring of the _b_ value in aftershock sequences can be used for real-time discrimination between foreshocks and aftershocks, allowing us to use a posteriori awareness for a priori alerts.
- Authors use evidence from a time series of Norcia and Kumamoto earthquakes in 2016 which were both preceded by identified foreshocks reaching M6.
![[Pasted image 20250508194313.png]]
- Amatrice-Norcia, Italy:
	- 24/08/2016: M6.2, 300 deaths and severe damage to towns
	- 30/10/2016: M6.6 earthquake, 20 km north-west, revealing a posteriori that the M6.2 event and its 'aftershock' sequence had in fact been a foreshock
- Kumamoto, Japan:
	- 15/04/2016: M6.5, followed by a M7.3 28 hours later

- Lower b-value following events increases the probability of a larger event - Norcia saw a 20% drop in the b-value following the first event, using a background b-value of 1.3, estimated from past data, this is indicative of the probability of a subsequent M6.6 earthquake increasing by 1,000 over the background probability. 

## Possible physical mechanism

- Presently two schools of thought regarding foreshock mechanisms and prognostic value ([[Gomber, 2018]])[^3]
	1. Deterministic PoV: Foreshocks represent a precursory process. For example, a precursory slip on the fault.
	2. Stochastic PoV: foreshocks are an indistinguishable part of earthquake clustering - according to epidemic type aftershock sequence models, there is no difference between foreshocks, mainshocks, and aftershocks; all foreshocks are simply mainshocks with aftershocks that happen to be bigger. The rupture process is not cyclic but epidemic.
- Authors interpret conditions which favour a drop in b-value after a moderate shock as the presence of critically pre-stressed faults and overall high stress levels coupled with a suitable orientation of source and receiver faults.
- However, assessing this is not currently possible even a posteriori.
- Real-time modelling for warning purposes would be even more challenging.
- However, empirical observations of b-value changes remain useful to improve earthquake risk mitigation.

## Towards real-time risk mitigation

- The evolution of b-values can be used as a proxy for the average stress conditions of faults.
- Authors propose a simple traffic light system - a traffic light system is useful for when decisions must be made in real time during or following a disaster.
- Green: b-value during aftershock sequences increases by >10%.
- Yellow: b-value during aftershock sequences changes by ± 10%
- Red: b-value during aftershock sequences falls by >10%
	- In such cases, decision-makers should be prepared to consider actions to continue evacuations.
- Traffic light system can be redefined using additional data, risk-cost-benefit analysis and by considering the uncertainty in b-values.
- Spatially mapping relative changes in the b-value can help with probabilistic assessment of the area most likely to be the epicenter of a subsequent larger event.
	- In the case of Norica, the mainshock occured in the areas with strongest decrease in the b-values.
![[Pasted image 20250508201827.png]]
- Testing their foreshock traffic light system on 58 more sequences (from [[Gulia et al., 2005]]), the authors have a 95% accuracy.
- One false-positive red alter was from Morgan Hull in 1984 - attributed to poor data.
- Further difficult to assess because M>6 earthquakes are rare in areas with excellent network coverage.
- Therefore, using the b-value as an assessor of a mainshock still to come is relient on excellent network coverage which is able to detect and process many smaller earthquakes (<M2) consistently and in real-time in order to compute a rolling b-value.

- **BUT THERE ARE LIMITATIONS ** -> [[Dascher-Cousineau et al., 2020]] 
- *ffs of course there are*
- 

[^1]: https://doi.org/10.1785%2F0220160183

[^2]: https://doi.org/10.1002%2F2014GL062379

[^3]: https://doi.org/10.1038%2Fs41561-018-0149-x
