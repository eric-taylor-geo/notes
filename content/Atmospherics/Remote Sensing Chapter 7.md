![[Pasted image 20250122144420.png]]

## 7.2.5 Low Earth Orbits

- Defined as an orbit altitude of 2,000 km or less.
- Orbital decay due to atmospheric drag is substantial below about 200 km
- Therefore, most LEO orbits are between 160 and 2,000 km
- LEO satellites are advantaged due to their closeness to the Earth's surface which allows for a better resolution of surface features and also the signal of reflected and emitted signals is strongest - signal falls off proportional to inverse square law
- The resolution is also consistent across the entire Earth's surface.
- Due to sensor swath overlap, polar-orbiting satellites see an improvement in satellite coverage due to more swath overlap at the higher latitudes

### Sun Synchronous Orbits

- Many weather and Earth mapping satellites are in a Sun-synchronous orbit which provides a consistent illumination of the Earth-scan view.
- Satellite passes over the equator and each line of latitude at about the same time each day [[Kidder and Vonder Haar, 1995]]
	- Kidder, S. Q., and T. H. Vonder Haar, 1995: Satellite Meteorology: An Introduction. Academic Press, 466 pp.
- The orbital plane of a sun-synchronous orbit must precess at ~1 degree each day (1/365º) to take into account the Earth's revolution around the sun
- The separation between consecutive ground-tracks must take into account the field of view of most sensors.
- Ratio of the number of orbits to days to repeat the first ground track:
	- n:m
	- E.g., 14:3 means the satellite will orbit exactly the the first ground track on the 15th orbit after 3 cays
	- Landsat 1 and 2 used a 251:18 orbit
- The separation between ground tracks on consecutive orbits is: (I'm assuming this is at the equator)
$$
d = \frac{2\pi}{n}\dot{}R_E
$$
- Typically weather satellites fly in pairs with one satellite having a morning crossing time where clouds are typically at a minimum before diurnal solar heating is able to generate cloud cover
- The second satellite in the constellation has a mid-afternoon flyover to sample the impact of the solar max on land surface vegetation - however, this is limited by increased cloud coverage in the afternoon

### Non-Sun-Synchronous orbits

- Satellites which are non sun-sychronous typically have a much lower orbital inclination and are designed to cover the tropical to mid-latitude bands

### Tracking

- numerous LEO communication satellites to provide coverage to polar orbiting satellites 
- Gives equal communications potential at all latitudes unlike GEO which have limited resolution toward the poles

## Geostationary Earth Orbits

- Goal of GEO is to have the satellite constantly pointing at the same location on the Earth 
- This is only possible at 35,786 km above the equator with an inclination of 0 degrees
- Ideal for communication satellites and for weather satellites 
- Orbit antennas also do not need to track the satellite's motion but rather they can remain fixed, orientated toward the satellite of interest
- First theorised in 1928 by Herman Potocnik and popularised by science-fiction Arthur Clark in 1945 
- US operates two Geostationary Operation Environmental Satellites (GOES) - one to sense the pacific and the gulf of alaska and the other to sense the atlantic

## Highly Elliptical Orbits

- HEO has a low altitude (~1,000km) at perigee and a very high altidue (>35,786km) at apogee
- These elliptical orbits are benefited for they dwell for a long time around the apogee permitting a similar standard of coverage as a GEO whilst this occurs.
- Indeed, bodies moving through the long apogee can appear almost stationary to the ground when the orbit is in the right inclination and the angular velocity of the orbit in the equatorial plane is close to the rotation of the Earth's surface.
- The longitude at which the satellites dwell remains fairly constant as the Earth rotates

- Lagrange points -> relevant for essay ?