Paper: [[II - Atmospherics]]

# Properties of Waves

Wavelength $\lambda$: Distance between repeating features
Amplitude $A$: Maximum displacement from equilibrium
Frequency $\nu$: Number of oscillations per unit time
Angular frequency $\omega$: $2 \pi \nu$
Wave number $k$: Spatial frequency ($2 \pi / \lambda$)
Phase speed $c$: Speed at which an individual wave structure moves:
$$
c = \frac{\omega}{k}
$$
Group velocity $c_g$: Speed and direction of energy propagation:
$$
c_g = \frac{\partial\omega}{\partial k}
$$

Waves can be dispersive or non-dispersive. In dispersive waves, different wavelengths travel at different speeds. In non-dispersive waves, all wavelengths travel at the same speed.

# Gravity Waves

## Mechanism

Gravity waves are oscillations generated when an air parcel in a stable atmosphere is displaced vertically. Gravity (via buoyancy) acts as the restoring force. Upon vertical displacement, the air parcel rises, expands, and cools by the dry adiabatic lapse rate. In stable conditions, the environmental lapse rate is smaller than the dry adiabatic. Therefore, the vertically displaced air parcel will be colder, denser, and less buoyant than its environment. The buoyancy force will accelerate the air parcel downward until it reaches its original position where it is neutrally buoyant.

However, the parcel overshoots this, because it has its maximum velocity, and it will continue to be displaced downward. As it is displaced downward, it warms with the dry adiabatic lapse rate. Again, in stable conditions the environment cools slower with decreasing altitude than the dry adiabatic. Consequently, the air parcel is warmer and less dense than its surroundings, becoming increasingly positively buoyant, decelerating it and eventually resulting in upward acceleration. This time, the parcel has its maximum upward velocity at the neutral buoyancy height, and overshoots again. In a frictionless setting, the parcel will reach its original point of displacement, and oscillate around its neutral buoyancy height with this amplitude.
## Propagation

Gravity waves propagate both vertically and horizontally. Vertical propagation is clear - the oscillating parcel will displace air above and below.  Parcels can also oscillate at slanted angles, permitting their horizontal propagation. Consequently, gravity waves have two wavelengths - one in the vertical, and one in the horizontal.

The frequency of a gravity wave is dependent on the environmental lapse rate, because the environmental lapse rate determines the stability of the atmosphere, which determines the buoyancy force. The more stable the atmosphere, the stronger the restoring buoyancy force becomes. Hence, its acceleration / deceleration is greater ($a = F/m$), which increases the frequency of the gravity wave because the air parcel is oscillating between its maximum displacements at a faster speed. The frequency of a gravity wave is given by the Brunt-Väisälä frequency:
$$
\nu = \sqrt{g \frac{1}{\Theta}\frac{\partial \Theta}{\partial z}}\cos{\alpha},
$$
where the root term is the buoyancy force, given by the relative change of the potential temperature with altitude times gravity, and $\alpha$ is the angle between the perturbation and the vertical direction.

From this equation two key principles can be analytically inferred. First, the more slanted the path, the lower the oscillation frequency. If the perturbation is horizontal, then $\cos{90} = 0$, and there is no oscillation. Secondly, gravity waves only occur in a stable atmosphere. In an unstable atmosphere $\partial \Theta / \partial z$ is negative, which does not have any real solutions when rooted.

The phase speed of a gravity wave is:
$$
c = \nu \lambda.
$$
Because the frequency is independent of wavelength, gravity waves are dispersive, and longer waves travel faster than shorter waves. The group velocity of gravity waves is perpendicular to the phase speed (*which is left as an exercise to the reader !!!*) ([[Fritts and Alexander, 2003]]). Consequently, energy and momentum of gravity waves is transported perpendicular to the direction of individual gravity waves. This allows the upward deposition of momentum which changes wind velocity and the deposition of energy which heats the air when waves break.
## Sources (from [[Fritts and Alexander, 2003]])

Gravity waves require an initial vertical displacement of air for their generation. This can develop from:
- Changes in topography
- Atmospheric convection can result in overshooting in updrafts or horizontal flow in the background is forced over areas of convection.
- Frontal systems cause the vertical rearrangement of air masses.

**Topography**

Gravity waves formed from uplift due to topography, mountain waves, have dominant scales (in terms of momentum fluxes) of 10-100 km, phase speeds near zero (near-stationary) and vertical wavelengths dictated by the local static stability and mean wind in the plane of wave propagation.

**Convective generation**

Waves generated by convection are not characterised by a single prominent phase speed or frequency unlike topographic waves. Low-frequency waves (which have long wavelengths) are observed in the atmosphere at large horizontal distances from convective sources, making correlation with clouds or other indicators of convection difficult.




## Breaking

Gravity waves break through two mechanisms. First, vertically propagating waves will eventually become convectively unstable. The density of air decreases with altitude. To conserve wave energy, the amplitude of gravity waves must grow when the density is lower so that the same mass is oscillating. Consequently, waves aloft have a greater amplitude than those below, meaning that temporally, parcels will surpass eachother.  Density generally decreases exponentially with altitude, therefore the ampltitude increases rapidly,  and the overlapping effect is stronger at higher altitudes. This creates atmospheric instability, which causes the gravity wave to break for gravity wave require a stable atmosphere.

Secondly, when horizontal wind speed changes with altitude, the angle of the oscillating air parcel with respect to the vertical changes. If the wind speed is sufficient to cause the vertical wavelength to approach zero, gravity waves lose their vertical component and thus also break.

The breaking of gravity waves in the stratosphere is important for transferring energy and momentum from the troposphere to the stratosphere.
![[Pasted image 20250526203933.png|425]]


# Rossby Waves

## Mechanism

Rossby waves arise due to the latitudinal variation in the Coriolis parameter. For small latitude changes, the Coriolis parameter is approximated to vary linearly with latitude using a Beta-plane approximation where:
$$
f = f_0 + \beta y \quad,\quad \beta = \frac{2\Omega\cos{\varphi_0}}{R} \quad,\quad y = R(\varphi - \varphi_0) \quad,\quad \beta = \frac{\partial f}{\partial y},
$$
where $f_0$ is the planetary vorticity prior to perturbation, $\beta$ is the linear approximation for the variation in the Coriolis parameter, and y is the meridional displacement. This assumption is valid for small meridional amplitudes. For greater pertubations, spherical geometry is required.

Consider a parcel of air with zero relative vorticity in the Northern Hemisphere. If it is displaced polewards, it gains planetary vorticity. Under the assumption of the conservation of absolute vorticity in non-divergent, barotropic flow (sufficient understanding for this course), which is approximately accurate at the 500 hPa quasi-barotropic level:
$$
\frac{d}{dt}(\zeta + f)=0
$$
the relative vorticity must decrease in order to conserve absolute vorticity.  Consequently, anti-cyclonic (clockwise) rotation is induced which curves the air parcel's trajectory, causing it to turn equatorward. As it moves equatorward, its planetary vorticity decreases, resulting in an increase in relative vorticity. Upon reaching its original latitude of zero relative vorticity, $\varphi_0$, the air parcel retains meridional momentum, and continues equatorward. Continued equatorward movement continues to decrease the planetary vorticity, and hence, absolute vorticity increases, resulting in cyclonic (anticlockwise) rotation equatorward of $\varphi_0$, which curves the air parcel back poleward, reducing its relative vorticity. The air parcel will pass $\varphi_0$, gaining planetary vorticity and reducing its absolute vorticity. It will reach the latitude of its original displacement. Hence, an oscillatory pattern is established, with oscillation in the meridional direction.

## Sources

Topographic barriers which cause deflection.
Baroclinic conditions which generate vorticity

## Propagation

Rossby waves propagate westwards, which is explained by the meridional change in planetary vorticity. Air parcels which are north of $\varphi_0$ will have negative relative vorticity, creating anti-cyclonic motion which moves parcels that are to the east of the maximum displacement to the South, back to $\varphi_0$. Likewise, air parcels which are south of $\varphi_0$ will have positive relative vorticity, creating cyclonic motion which moves parcels that are to the west of the maximum displacement to the North, back to $\varphi_0$. Therefore, the wave will propagate westwards relative to the mean flow.

The phase speed of a Rossby wave is:
$$
c = \bar{U}-\frac{\beta}{k^2} = \bar{U}-\frac{\beta\lambda^2}{4\pi^2},
$$
where $\bar{U}$ is the mean flow and $k$ is the wave number, respectively. The latter term is always positive (the cosine term in $\beta$ is positive between -90 and 90 degrees), and thus analytically it can be seen that propagation is always negative (west) with respect to the mean flow.  Depending on the speed of the mean flow, the phase speed can be westward ($\beta/k^2>\bar{U}$), stationary ($\beta/k^2=\bar{U}$), or eastward ($\beta/k^2<\bar{U}$). In eastward flow, the wave is considered prograde.

Because $k = 2\pi/\lambda$, it can also be seen that longer wave lengths will have a greater phase speed, with the phase speed increasing quadratically with wavelength. Therefore, Rossby waves are dispersive waves. Their group velocity can be in either zonal direction, thereby transporting energy and momentum in either zonal direction.

**Vertical Propagation**

Rossby waves can only propagate vertically into a westerly mean flow that is not too strong ([[Charney and Drazin, 1961]]). Analytically, vertical propagation can only occur when:
$$
0 < U - c < U_{\text{Crit}},
$$
is satisfied. Where $U$ is the zonal wind velocity of the atmosphere above, and $c$ is the phase velocity of the Rossby wave. Rossby waves typically move with the mean flow in a the eastward direction, thus $c > 0$. Thus, if the flow is easterly, $U$ is negative, and no vertical propagation can occur. Therefore, $U$ must be westerly. It must also be westerly *relative to the the wave*, else $U -c$ will still be negative. The difference in velocities must also be less than a critical velocity, else propagation cannot occur. The critical velocity is proportional to the vorticity gradient and roughly inversely proportional to the square of the wavenumber:
$$
U_{\text{crit}}=\frac{\beta}{(k^2 + l^2) + \frac{f_0^2}{4N^2H^2}}\propto \beta.
$$
Therefore, $U_{\text{Crit}}$ is lower at higher latitudes, and is higher for longer wavelengths. Therefore, Rossby waves most easily propagate vertically when they have long wavelengths (hence, lower wavenumbers) and at the low-latitudes.

Under barotropic conditions, absolute vorticity is conserved (when inviscid), Rossby waves are stable and perturbations don't grow, meaning there is no cyclone development. 

## Importance

**Critical Velocity - Stratospheric Coupling**

The vertical propagation is important for the coupling of the troposphere and stratosphere. Rossby waves that propagate into the stratosphere will deposit their energy and momentum, heating the stratosphere and reducing westerly winds through depositing westward momentum.
In the winter hemisphere, stratospheric westerlies define the stratospheric polar vortex due to a cold pole and warm equator. Thus, Rossby waves can propagate vertically into the stratosphere during winter when wind speeds are are below the critical speed. Conversely, in the summer hemisphere, there are weak easterlies due to a warm pole and equator, which prevents upward propagation and hence, decouples the stratosphere from the troposphere.

The Northern hemisphere generates more Rossby waves due to topography, thereby explaining the hemispherical different in the strength of the stratospheric polar vortex. There are not enough Rossby waves to perturb and weaken the stratospheric polar vortex in the Southern hemisphere, thereby enabling it to strengthen quickly and in southern autumn where velocities become too greater for Rossby wave propagation. Conversely, the northern stratospheric polar vortex is perturbed by Rossby waves, slowing its development through weakening. However, similarly, upon becoming sufficiently strong, it can no longer be weakened by Rossby waves from the troposphere.

**ENSO**

Oceanic Rossby waves play a role ENSO - see below in Kelvin waves (delayed oscilator theory)

**Heat waves**

Stationary waves can produce persistent conditions, resulting in heat wave. Both the infamous 2003 and the 2019 European heatwaves were fuelled by a persistent planetary-scale Rossby wave which became stationary, becoming an omega block ([[Mitchell et al., 2019]]). Temperatures in France rose to 45.9 degrees C.



# Kelvin Waves

## Mechanism

Kelvin waves are [[Atmospheric Waves#Gravity Waves|Gravity Waves]] which are affected by the Coriolis force and are trapped against a boundary where a geostrophic balance is not possible. They exist in two forms: topographic boundary and equatorial Kelvin waves, and their amplitude decays exponentially away from the boundary.

Equatorial Kelvin waves are trapped along the equator by the change in sign of the Coriolis force at the equator, which acts as a restoring force. The direction of propagation along the equator is only eastward. When moving eastward slightly north of the equator, the Coriolis force acts southward, trapping the perturbation to the equator. Similarly, when moving eastward slightly south of the equator, the Coriolis force acts northward, thereby balancing its northward counterpart, and trapping a perturbation to the equator. In westward flow, the change in sign of the Coriolis force either side of the equator would result in divergence, and thus, dissipation of the perturbation. Thus, Kelvin waves only propagate eastward. The change in sign of the Coriolis parameter at the equator affects both air and water. Therefore, equatorial Kelvin waves are present in both.

Meanwhile, topographic boundary waves predominantly occur in water. Coastlines prevent water from being deflected by the Coriolis force when in the correct orientation, thereby trapping a perturbation along the coast. Therefore, in the Northern hemisphere and Southern hemisphere, the coast must be to the right and left, respectively, relative to the flow direction.

The phase speed of Kelvin waves is independent of the wavelength. Therefore, the group velocity of Kelvin waves is the same as the phase velocity. Kelvin waves are thus non-divergent.

$$
c = \sqrt{gH}
$$
Kelvin waves, a type of gravity wave, can propagate vertically. However, they can only propagate eastward, into regions with a westerly zonal flow.

## Importance

'Atmospheric Kelvin waves play an important role in the adjustment of the tropical atmosphere to convective latent heat release, in the stratospheric quasi-biennial oscillation, and in the generation and maintenance of the Madden–Julian Oscillation. Oceanic Kelvin waves play a critical role in tidal motion, in the adjustment of the tropical ocean to wind stress forcing, and in generating and sustaining the El Niño Southern Oscillation' ([[Wang 2003]]).

**ENSO:**

Equatorial Kelvin waves play a critical role in ENSO. Westerly wind anomalies in the western Pacific create a local rise in sea surface height in the central/eastern Pacific. This causes an adjustment in the water column, pushing the thermocline down. The thermocline marks the transition between warm surface water and cold deep water. The deeper thermocline results in an increase in sea surface temperatures. This anomaly propagates into the eastern Pacific as a downwelling Kelvin wave, raising eastern Pacific sea surface temperatures. Kelvin waves take approximately 2-3 months to propagate across the Pacific. Upon reaching the coast of South America, the equatorial Kelvin waves are diverted meridionally and travel as coastal Kelvin waves. These Kelvin waves are reflected and return as upwelling westward propagating Rossby waves which propagate westward at half the speed of eastward propagating Kelvin waves. Upwelling waves raise the thermocline, resulting in lowered sea surface temperatures. Upon propagating into the western Pacific, the Rossby waves are reflected as upwelling equatorial Kelvin waves, which propagate into the central and eastern Pacific, offsetting the warming anomaly, thereby providing a negative feedback mechanism to shift El Niño conditions into La Niña conditions. A new El Niño cycle can begin once sufficient ocean heat content has built up in the West Pacific. Thus, the West Pacific must recharge. These events make up the recharge oscillator theory ([[Jin, 1997]]).










https://www.desmos.com/calculator/4xzwylhyqg