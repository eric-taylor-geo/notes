# 2.4 Meteorological satellite orbits

**2.4.1 Sunsynchronous orbits**

- The Earth's oblateness allows polar orbits to be sun-synchronous
- Precession at 1/365 degrees per day will mean the satellite will be synchronised with the sun
- Requires an inclination of 98.8 degrees
- Sun-synchronous orbits are classified by their equator crossing time 
- The highest latitude reached by the subsatellite point is equal to the inclination angle (or the suppliment)
- Therefore, sun-synchronous orbits are unable to observe the poles - orbits are referred to as near-polar orbits

**2.4.2 Geostationary Orbits**

- Geosynchronous: orbits with the same angular velocity as the Earth
- Geostationary: is geosynchronous but also has no inclination or eccentricity
- Irrespectively of their subtle difference, both are typically referred to interchangeably
- Second-order perturbations in the Earth's gravitational field cause geostationary satellites to drift from their desired orbit, requiring periodic maneuvers. 

**2.4.3 Other Orbits**

- Highly elliptical orbits: used by the Soviet Union (Molniya communications satellites). Suggested that this orbit would be useful for meteorological observations of the high latitudes:
	- Kepler's laws

## 2.5 Satellite positioning, tracking, and navigation

- calculating the position of satellites is important to allow for communications with them.
- geometry to find satellite … 
- Navigation - knowing where a satellite is in its orbit, is fundamental for knowing the scene the satellite is viewing.
- Satellite data usually comes in the form of scan lines, each divided into elements or samples - pixels/scan spots
- Scanning means each pixel is not acquired at the same time 
- Instruments on many LOE orbit satellites are mounted under the satellite, scanning perpendicularly to the velocity vector - nadir  - using the satellite pitch, yaw, and roll, the scan geometry can be calculated
- some more maths :) 

# 2.6 Space-time sampling

- Examining how different orbits affect a satellite's ability to sample the atmosphere is a matter of the following questions:2
	- What areas will the orbit and scan pattern allow the instrument to observe?
	- How often will an area be observed
	- At what local times will the observations be made?
	- At what viewing zenith and azimuth angles will the observations be made?
	- These questions are aspects of what is called space-time sampling
- Geostationary satellites view a fixed area - roughly 42% of the globe
	- Therefore, any point within this area can be observed as frequently as their instruments will allow
	- Therefore, an area can be observed in local time
	- However, each point has a fixed geometric relationship to the satellite, meaning it is only viewed at one zenith and azimuth angle
- Most LEO meteorological satellites have their swath overlapping with a previous or successive orbit.
- Owing to the satellite's movement, each point can be viewed from a wide range of zenith and azimuth angles
- Sun-synchronous near-polar orbits are not useful for diurnal variation studies, because their overpass time is the same each day.
- Earth Radiation Budget Satellite (ERBS) has a 57º inclination at an altitude of 600 km. The angle between the sun and the ascending node changes 4.94º each day. Because the satellite makes observations both as it ascends and as it descends, all local times are sampled in ~36 days.


