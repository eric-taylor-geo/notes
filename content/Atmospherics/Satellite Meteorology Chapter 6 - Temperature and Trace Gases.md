[[Kidder and Vonder Haar, 1995]]

## 6.1 Sounding Theory

- Two basic types of atmospheric sounding:
	- Vertical sounding - sounding instrument senses radiation coming from the atmosphere and the Earth's surface
		- Sensor detects radiation from the Earth's surface and atmosphere
	- Limb sounding - only the limb of the atmosphere is sensed.
		- Sensor detects radiation only from the Earth's atmosphere
- Both methods use Shwarzchild's equation.
- Active atmospheric sounding includes both lidar and radar.

## 6.2 Retrieval methods:

- What temperature and trace gas concentrations could have produced a set of observed spectral radiances?
- This question is an inverse or retrieval problem. The forward problem is to calculate the outgoing radiances given known temperature and trace-gas profiles
- Given clear-column radiances, the forward problem is easy to solve. However, the inverse problem does not have a unique solution.
- When a finite number of wavelengths are observed and contaminated with noise, an infinite number of solutions are possible
- Retrieval problem becomes one of finding temperature profiles that satisfy the radiative transfer equation *and* approximate the true profiles as closely as possible.
- Approaches to the problem are classified into three general areas:
	- Physical retrievals
	- Statistical retrievals
	- Hybrid retrievals

### 6.2.1 Physical Retrievals

- Iterative process:
1. A first guess of the temperature profile is made
2. The weighting functions are calculated
3. The forward problem is solved using physical equations 
4. If the computed radiances match the observed radiances within the noise level of the radiometer, the current profile is accepted as a solution.
5. If not, the current profile is adjusted
6. Repeated until a solution is found

**Advantages:**
- Physical processes are clearly evident at each stage of the retrieval
- No large database of coincident radiosonde data is necessary
**Disadvantages:**
- Method is computationally intensive
- It requires accurate knowledge of transmittances
- Except for information contained in the first gues, it does not utilise known statistical properties of the atmosphere
### 6.2.2. Statistical retrievals

- The radiative transfer equation is not directly used
- Methods assume that the radiometer has been designed so that its channels will vertically sample the atmosphere.
- A training data set is used to calculate a statistical relationship between observed radiances and atmospheric temperatures.
- Data sets must be:
	- Large enough to ensure statistical significance
	- Must be updated frequently
	- Must be divided temporally and spatially
**Advantages:**
- Actual retrieval is computationally easy once training is done
- Requires no knowledge of the transmittances or use of radiative transfer equation
- Utlises statistical properties of the atmosphere
**Disadvantages**
- A large training data set of radiosonde and satellite data is necessary 
- Physical processes aren't taken into account yet these are embedded in the statistics

### 6.2.3 Hybrid Retrievals

- They appear much like statistical methods, but they do not require a large training data set. 
- Rather, they use weighting functions like physical retrievals but they do not directly involve integration of the radiative transfer equation
- 
