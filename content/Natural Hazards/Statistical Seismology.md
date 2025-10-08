### Guttenberg-Richter law

The Gutenberg-Richter law ([[Gutenberg and Richter, 1944]]) expresses the relationship between the magnitude and total number of earthquakes of at least that magnitude. It is expressed as:
$$
\log_{10}N = a - bM
$$
or
$$
N = 10^{a-bM}
$$
where
- $N$ is the number of events having a magnitude $≥ M$,
- $a$ and $b$ are constants.
- Can calculate from data using a maximum likelihood method.

$b$ is typically close to unity globally ([[Lay and Wallace, 1995]]), making that for every unit increase in earthquake magnitude, there are 10 times fewer earthquakes at or above this magnitude.

It is important to note that the observed logarithmic-linear relationship does not hold at lower earthquake magnitudes. This is due to the incomplete detection of small earthquakes, causing the distribution curve to flatten below what is labeled as the Magnitude of Completeness ([[Mignan et al., 2012]]) ([[Weimer and Wyss, 2000]])

Observations of the b-value show that it is not constant in space or time due to differences in regional geological structures and the earthquake data used. Early work by [[Smith, 1981]] observed that regions near the epicenter of $M ≥ 6$ earthquakes in New Zealand displayed an increase in the b-value, which then returned to normal before an earthquake, and therefore Smith suggested the b-value could be used as a precursor index for earthquakes. Conversely, different studies have shown that the b-value decreases in the years before $M ≥ 6$ earthquakes (e.g., [[Imoto, 1991]]). A lower b-value indicates that there are fewer small earthquakes relative to large ones, indicating increasing stress on a fault - thereby suggesting the increased likelihood of a major macro-failure.

More recent studies corroborate a lower b-value as a precursor for earthquakes. For instance, [[Chan et al., 2024]] examine b-value variations prior to $M ≥ 6$ earthquakes in Taiwan between 1999 and 2021, finding that many large earthquakes occurred in areas with low b-values in the year prior. Taiwan upgraded its seismic network in 2012, enhancing its ability to record smaller earthquakes and providing a more precise earthquake catalog, enhancing the quality of precursor research ([[Chan et al., 2024]]). Increased detection of smaller earthquakes would increase the b-value and therefore require calibration of the magnitude of completeness. [[Chan et al., 2024]] found that after the upgrade in Taiwan's seismic network in 2012, there was a noticeable decrease in calculated values of the magnitude of completeness, indicating that the quality of observations improved after the integration of the seismic network. However, despite noting lower b-values a year prior to earthquakes, they found no significant temporal changes near the epicenters of earthquakes, thus making the monitoring of the b-value an inconsistent precursor for earthquakes. Indeed, earthquakes are not always associated with a prior drop in the b-value, nor is a drop in the b-value always associated with an earthquake. 

Earthquakes are typically followed by an increase in the b-value by 20-30% following a large shock ([[Gulia et al., 2005]]), which has implications for real-time monitoring of predicting whether an earthquake is the main earthquake or a foreshock ([[Gulia and Weimer, 2019]]). B-values which do not increase following a large shock are indicative of a more significant main shock still to come ([[Gulia and Weimer, 2019]]). Gulia and Weimer (2019) assessed a sequence of b-values during earthquake sequences during the Norcia and Amatrice earthquakes in 2016, which both had M6 foreshocks before the main shocks - two months and 28 hours prior, respectively. Both sequences did not show an increase in the b-value until the mainshocks, suggesting its possible usage as a real-time indicator of future short-term earthquake activity. Though there are questions of the reliability of this assessment ([[Dascher-Cousineau et al., 2020]],  [[Dascher-Cousineau et al., 2021|2021]]; [[Gulia et al., 2020]]; [[Gulia and Wiemer, 2021]]). The discrepancies in results between studies highlight the complexity of forecasting seismic activity.

### Omori-Utsu Decay

The frequency of aftershocks decreases roughly with the reciprocal of time after the main shock. An empirical relationship was first proposed by [[Omori, 1894]] and modified by [[Utsu, 1961]]:

$$
n(t) = \frac{k}{(c+t)^p}
$$
 The rate of aftershocks is proportional to the inverse of time since the mainshock and this relationship can be used to estimate the probability of future aftershock occurrence. Further events modify the curve.
![[Pasted image 20250508204820.png]]
Modelled using Epidemic-Type Aftershock Sequence (ETAS) modelling: [[Mizrahi et al., 2021]]
![[Pasted image 20250508204858.png]]

### Frequency of the Largest Earthquake

Knowing from [[Gutenberg and Richter, 1944]] that:
$$
\log_{10}N = a - bM_w
$$
And from [[Hanks and Kanamori, 1979]]:
$$
M_0 = \mu AD \quad,\quad \log_{10}M_0 = cM_w + d = 1.5M_w + 9.05
$$
Thus:
$$
\log_{10}N = a + \frac{bd}{c}-\frac{b}{c}\log_{10}M_0
$$
$$
N(M_0) = 10^{a + \frac{bd}{c}}M_0^{-\frac{b}{c}}
$$
$$
N(M_0) = αM_0^{-β}
$$
$N(M_0)$ is the number of earthquakes greater than $M_0$ [[Molnar, 1979]]

We can then set a cut-off using a known maximum earthquake seismic moment calculated from geological evidence using a heaviside function:
$$
\displaystyle \text{H}(x) = \begin{cases} 
0 & \text{if $x < 0$} \\  
1 & \text{if $x \geq 0$} \\  
\end{cases}
$$
$$
N(M_0) = αM_0^{-β} \left[\text{H}\left(M_0^{\text{max}}-M_0\right)\right]
$$
ngl idk what's going on with this integration but this can be related back to the Guttenberg-Richter law using the rate of $M_0$, $\dot{M}_0^\sum$

![[Pasted image 20250509105746.png]]
Then, understanding the predicted rate of earthquakes, allows for the development of risk mitigation strategies based on a physical understanding of risk.


![[Pasted image 20250509104043.png]]
### Velocity Fields and Coupling Maps

- Use GPS sensors to monitor the surface velocity
- Plate velocoties are then calculated in a reference frame fixed to one plate, allowing relative motion to be interpreted.
- The surface velocity has a physical relationship with slip along the fault. Thus, solving this inverse problem using a backslip model and knowledge of the fault's geometry allows the slip along the fault to be estimated.
- The velocity deficit is the loading rate (equal to the convergence rate of the two plates, assuming there is only elastic deformation taking place) minus the estimated inversion along the fault. The deficit reflects how much motion is being stored - i.e., the strain accumulation.
- We can thus define coupling as the ratio between the deficit and the loading.
- Value of 1: fully locked - no stress is being released
- Value of 0: freely slipping
- [[Métois et al., 2016]] compare coupling map with locations of seismic activity in Chile. Areas with high coupling exhibit more earthquakes. Thus, whilst we are unable to predict *when* an earthquake may happen, we can predict *where* earthquakes are most likely to occur along a fault.

### Seismic Gap - Coseismic approach

- Can use satellite radar to monitor which parts of the fault plane have moved and by what magnitude. Can then insert into models to see which parts of the fault did not release their energy - seismic gap.
- Thus, energy was not released here during the earthquake, making it a likely location for future earthquales.
- Seismic gap in Türkiye 2023 earthquakes [[Barbot et al., 2023]]
- Was a location of a later earthquake in 2024
- Thus, detailed modelling can help us understand where energy was released, but most importantly, where it was *not*, which can inform future earthquake planning
### Intersiemic approach

- Analyse plate movement between earthquakes.
- Can then measure how much energy is getting stored on faults that will eventually released in an earthquake.
- [[Weiss et al., 2020]] for Turkey using Sentinel-1 data 2014-2020
- [[Hussain et al., 2018]] found that the strain accumulation rate is constant across the North Anatolian Fault and over time.