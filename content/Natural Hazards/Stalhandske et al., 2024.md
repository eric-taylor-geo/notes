2025-06-01 11:51

Paper: [[_II - Natural Hazards]]

DOI:

URL: https://www.nature.com/articles/s41598-024-55775-2

Tags: [[Natural Hazards - Multi-Hazard]]

Status:
# Global multi-hazard risk assessment in a changing climate


Natural hazards pose significant risks to people and assets in many regions of the world. Quantifying associated risks is crucial for many applications such as adaptation option appraisal and insurance pricing

However, traditional risk assessment approaches have focused on the impacts of single hazards, ignoring the effects of multi-hazard risks and potentially leading to underestimations or overestimations of risks

Present a framework for modelling multi-hazard risks globally in a consistent way, considering hazards, exposures, vulnerabilities, and assumptions on recovery

Illustrate using river floods and tropical cyclones and their impacts on people and physical assets on a global scale in a changing climate

Combine single-hazard models driven by climate model realisations and show that incorporating common physical drivers and recovery considerably alters the multi-hazard risk.

## Intro

- Combining risks from multiple single hazards by assuming them to be independent is a first step towards a more comprehensive risk assessment. This type of risk assessment is defined by the European Commission as multi-layer single-hazard risk assessment ([[Zschau, 2017]])
- This allows the computation of a shared exceedance probability of losses ([[Flemming et al., 2016]])
- Interactions ([[Gill and Malamud, 2016]])
- Based on these hazard interactions, the resulting risk assessment is considered as multi-hazard risk. When including dynamic vulnerability, it becomes a multi-risk assessment ([[Gill et al., 2021]])
- When transitioning from analyzing single hazards to multiple hazards, it is necessary to establish a common timescale to consider how these hazards interact ([[Tilloy et al., 2019]])
- When assessing compound risks of multiple hazards, it is essential to consider the assumptions made about the recovery of the exposures and changes in their vulnerabilities ([[Zschau, 2017]]; [[de Ruiter et al., 2020]])
	- A house cannot be destroyed twice in a week
- Cyclones and foods affect the largest number of people globally and cause the highest damage to physical assets (EM-DAT, n.d.)

- An impact return period curve represents an additional valuable risk metric, which describes the probabilistic cumulative distribution of impacts. From this curve, one can for example read the 100-year impact, which is a useful metric that provides a standardized way of comparing the potential impact of natural hazards for a defined geographical area. It helps to guide risk management and mitigation strategies, and is used as a benchmark for determining insurance premiums and other financial policies related to natural hazards.
- Find that impact increases under warmer climate scenarios

## Case Study: Vietnam

- Often affected by compounding storms and flooding
- Also consider heat stress as a hazard
- Recovery assumptions affect the total impact over time.
- For recovery times faster than the return period of hazards, assets are recovered and the level of preparedness for a next hazard 
- *This study assumes that vulnerability remains constant in time - however, this is a limitation because if a population is still recovering when another hazard occurs, their vulnerability is likely to be altered. Whether their vulnerability is greater or lower is context-specific. For instance, if a population is living in temporary structures such as tents, then the vulnerability to building collapse during earthquakes is low…*
- However, when recovery times are slower than the return period of hazards, then the impacts of hazards become compounded
- *Which then raises the question.. when does a hazard cascade end?*

## Discussion

- Total reserves needed to buffer the sum of both risks are likely to overestimate the actual need if single-hazard approaches are used -> a house may be destroyed independently by an earthquake or a cyclone. Thus, initially under single-hazard frameworks, it is destroyed twice in both scenarios, thereby requiring twice the rebuild cost for recovery under mult-layer single-hazard assessments.
- However, if both occur within a week, the house is only destroyed once (the destroyed house is not destroyed again), and thus recovery costs from simply summing multi-layer single-hazard assessments are likely to be overestimated.
- Thus, this is highly relevant for developing insurance products for different hazards.
- For independent hazards, the estimation of the 100-year spatially compounding impacts can be improved by computing the shared exceedance probability of losses by considering the impacts of all events of both hazards, ignoring which one caused the impact
- However, this changes when hazards are strongly correlated due to common physical drivers.

- Considering recovery time does not necessarily increase the total impacts for a given event, however, it affects the proportion of assets damaged at any specific moment in time. A one year recovery period would quickly reduce the percentage of impaired assets, while a five year recovery period would mean a part of the assets remains dysfunctional for a longer duration, thereby intensifying secondary associaed economic and social impacts ([[Sauer et al., 2023]])
- 