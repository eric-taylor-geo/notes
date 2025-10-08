2024-09-06 09:24

Paper: [[II - Dissertation|II - Dissertation]] [[3 - Tags/Glaciology]]

DOI:

URL:

Tags: [[Glaciology - Debris]] [[Glaciology - Meta Scale]]

Status: #read-detailed
# Notes

Using GGE Landsat 8 and Sentinel-2 satellite imagery, Scherler _et al_. (2018) find that 4.4% of glacier areas (bar GIS and AIS) are covered in debris.

Debris distribution is heterogenous.

Largest debris-covered areas are located in high-mountain ranges

At a global scale, there is a negative relationship with glacier size and its percentage debris cover – this is owing to the increased melt-out of englacially entrained debris which emerges upon melt.

Thus, as glaciers continue to reduce in size in a warming climate **(CITATION)**, the role of debris cover on their mass balances is expected to increase.

Evaluates results by contrasting with recently published datasets

## Methods

Combines glacier extents with remote-sensing based ice and snow identification.

Glacier extents were defined by the Randolph Glacier Inventory (RGI Consortium, 2017)

RGI Consortium (2017). Randolph Glacier Inventory (RGI)—A dataset of global glacier outlines: Version 6.0, Technical Report, Global Land Ice Measurements from Space, Boulder, Colorado, USA, Digital Media. [https://doi.org/10.7265/N5-RGI-60](https://doi.org/10.7265/N5-RGI-60)

Glacier outlines however, are difficult to draw owing to the similar reflectance of debris in satellite imagary to the surrounding rocky terrain (e.g., Paul _et al_,, 2004). Thus, manual editing is used for glacier inventory outlines (e.g., Nuimura _et al_, 2015).

Scherler _et al_. (2018) do not attempt to modify glacier outlines further.

The date of glacier outlines in glacier inventories is important. Older glacier outlines are likely to result in the overestimation of debris cover owing to the retreat of ice and exposure of valley sides due to the shrinking of global glaciers (Scherler _et al_., 2018).

![[Pasted image 20240906092906.png]]

**Issues with ice-cover mapping:**

Shadows and cloud and snow cover.

Manual approaches to classifying debris cover rely upon obtaining and selecting suitable images, however this is time consuming (Paul _et al_, 2017).

Scherler _et al_.’s (2018) automatic approach uses a pixel-based approach where various satellite images available from a given time period are used to best classify debris / ice / snow cover.

These were defined based on the RATIO, NSDI and FDC images.

RATIO: red to short-wavelength infrared band ratio (Hall _et al_., 1987)

NDSI: Normalized difference snow index (Dozier, 1989)

FDC: Linear spectral unmixing-derived fractional debris cover (e.g., Keshava and Mustard, 2002)

## Results

Mapping of debris extent is most accurate for glaciers > km2. For smaller glaciers, the proportion of debris cover is more sensitive to changes in thresholds.

![[Pasted image 20240906092923.png]]
-              Sufficient image coverage

-              E.g., cloud cover – especially in the equatorial regions during the melting season

-              Suitable algorithms and threshold values- smaller glaciers are more sensitive to thresholds

-              NDSI thresholds vary in space and time and deviate from the commonly used value of 0.4 (Härer _et al_, 2018). Predicting their variation at a global scale is a challenge.

-              Scherler _et al_. suggest using a range of threshold values and assigning probabilities to debris cover.

These challenges result in gaps in the data and misclassifications.

Previous studies have attempted to minimize such misclassifications through applying additional rules to debris classification based on the relative elevation or size of debris-cover patches (read Mölg _et al_., 2018 and Herreid _et al_., 2015) – however, these methods require a priori knowledge which is not typically available. _Further research ?_

Snow buries debris quickly – thought: _so can this therefore result in multiple layers of alternating debris and snow ? How does this affect energy balance?_

RGI regions closer to the equator tend to have higher proportions of their area being debris-covered than regions closer to the poles. This is likely owing to glaciers closer to the equator being found exclusively in high altitude mountain ranges which typically feature steep rock walls, a major source of debris.

Whilst, closer to the poles, ice is less constrained to high-altitude regions and can even bury the existing topography, being no longer constrained by it – thus, removing sources of debris.