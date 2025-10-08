2025-03-06 13:57


Paper: [[II - Atmospherics]]

URL: https://www.youtube.com/watch?v=aSSI8cg8ljU

## Kelvin Waves

- Kelvin waves are trapped gravity waves
- Trapped waves decay exponentially in some direction
- Kelvin waves need a boundary to exist
- Observed in the ocean and atmosphere
	- Equatorial kelvin waves in the ocean and atmosphere
	- Coastal kelvin waves
- Start from shallow water equations:
	- X-momentum equation
	- Y-momentum equation
	- Continuity equation (mass conservation)
![[Pasted image 20250306140032.png]]
### Equatorial Kelvin Waves
- Wave propagation for equatorial Kelvin waves is always eastwards
- Coriolis parameter is approximated by the equatorial β-plane:
$$
f = f_0 + \beta y, \quad f_0 = 0, \quad \beta=\frac{2\Omega \cos{\Phi}}{a}
$$
- At the equator, therefore $\Phi$ is 0
- Kelvin waves are trapped along the equator and therefore have no meridional component (v = 0)
- Therefore, shallow water equations simply become:
- ![[Pasted image 20250306141257.png]]
- Linearise shallow water equations about a state at rest with mean height H and some small perturbations:
	- u -> u'
	- v = 0
	- h -> H + h'
![[Pasted image 20250306141605.png]]
- Eliminate terms which are products of two perturbations
- Wave equation is a closed form equation for u' as a function of time and zonal coordinate, x
- In fact, the wave equation describes a wave that propagates away from a central location with a fixed phase speed which is:
$$
c = \omega/k = \sqrt{gH}
$$
- Solving of differential equations (in video but not made notes on this) yields the amplitude in the y direction:
$$
\hat{u}(y) = u_0\exp{\left(-\frac{\beta y^2}{2c}\right)}
$$
- Because $c = \sqrt{gH}$, negative solutions to the phase speed would mean that the amplitude increases exponentially moving away from the equator which is clearly an unphysical solution (βy^2 is always positive)
- Therefore, the only physically valid branch of the Kelvin wave solution is the eastward propagating branch. Therefore, equatorial Kelvin waves only propagate eastward (phase speed is positivie)
- **Equatorial Rossby Radius of Deformation**: the radius at which rotational effects become important for equatorial waves. In particular the radius at which the wave has decayed by a certain amplitude
$$
R_{eq} = \sqrt{\frac{c}{\beta}}
$$
- ![[Pasted image 20250306145140.png]]
### Coastal Kelvin waves

- Assume:
	- Flat bottom topography
	- Constant coriolis parameter, f_0
	- Coastline is parallel to the y-axis
	- Zonal velocity (normal to the coast) is 0
- ![[Pasted image 20250306151317.png]]
- Finds that only northward propagating kelvin waves are allowed on the eastward side of a coast (e.g., west coast of North America) 
- Equally shows exponential decay away from the coast - only two possible solutions
- Example:
	- English channel
	- North Atlantic tide enters the channel from the west and assumes the character of a kelvin wave which is trapped against france leading to higher tides along the french side of the channel








