2025-05-23 19:49


Paper: [[II - Atmospherics]]

# Understanding flow

The change in flow over time is dependent on:
1. The advection of flow by flow itself
	- The transport itself depends on the wind and thus the transport term is described by the product of the wind speed itself. Thus, this term is non-linear and mainly responsible for the chaotic behaviour of the atmosphere. It allows for the fast evolution of flow even with a small perturbation.
2. Coriolis force
	 - Deflection due to the Earth's rotation.
3. Pressure gradient force
	- PGF is responsible for the generation of a flow, and it is the only force that leads to an acceleration and an increase in horizontal wind speed.
	- Since the PGF is determined by pressure, we need information about the pressure and temperature fields
4. Gravitational force
	- In the vertical, the PGF is largely balanced by the gravitational force, giving rise to buoyancy forces.
5. Frictional force
	- Responsible for the generation of turbulence in the atmosphere and is mainly felt in the lowest kilometre of the atmosphere. It reduces the wind speed, thereby converting kinetic energy into heat.

The geostrophic flow is recovered from this equation by ignoring friction and advection and by assuming a balanced flow, meaning that the change of the flow with time is zero. Thus, a flow in geostrophic balance has no development.

When friction is considered, the wind speed is reduced, thereby decreasing the Coriolis force. Consequently, the Coriolis force and pressure gradient force are no longer in balance, and the flow is no longer geostrophic. Assuming, temporarily, that the pressure field does not change with time, a new balance between the Coriolis, pressure gradient, and frictional forces will be reached. In this new balance, there is a flow component from the high to the low pressure. The movement of air from high to low pressure decreases the pressure gradient, thereby changing the pressure field and producing a further development of the flow. Thus, the presence of friction not only changes the wind speed but. It also changes the wind direction. Friction will always destroy flow but can never create flow.

## Cyclostrophic balance

Cyclostrophic balance considers the centrifugal force in addition to the pressure gradient and the Coriolis forces. Such a wind is called a *gradient wind* ([[Lynch and Cassano, 2006]]). In this balance, these three forces will add to zero, so that there is no longer a net force acting on the flow (we are ignoring friction here). The centrifugal force always acts radially away from the centre of curvature and is a function of the wind speed and radius of curvature. Depending on the flow direction, the Coriolis force and centrifugal force can act in the same or opposite directions. This results in an asymmetry between high- and low-pressure systems. 

**High Pressure System**

In a high-pressure system, the pressure gradient force acts outward, the centrifugal force acts outward, and the Coriolis force acts inward. Therefore, the Coriolis force must oppose both the pressure gradient and centrifugal forces.
$$
\text{PGF + Centrifugal = Coriolis}
$$
Thus, relative to geostrophic flow, where only $\text{PGF = Coriolis}$, the Coriolis force must increase, which requires flow to be faster than geostrophic flow. However, the Coriolis force is not the only force in this balance which is affected by velocity. The Coriolis force increases linearly with velocity:
$$
F_c \propto v
$$
But the centrifugal force increases quadratically:
$$
F_{\text{Centrifugal}} \propto \frac{v^2}{r}
$$
Consequently, increasing the velocity increases the Coriolis force but also increases the centrifugal force more rapidly, meaning eventually, the Coriolis force cannot grow fast enough to counterbalance the rapidly increasing centrifugal force, causing the force equilibrium to collapse. Thus, there will be a point where the Coriolis force will not be able to balance both the pressure gradient and centrifugal forces through an increase in flow velocity. This leads to an unstable situation, thereby placing a limit on how strong an anti-cyclone can get.

For a given pressure field, this dynamic limit sets a maximum wind speed beyond which the force balance cannot be maintained, placing an upper bound on anticyclone strength. To stay within stable parameters, anticyclones must exhibit larger radii and lower velocities, making them broad and weak compared to cyclones

**Low Pressure System**

Meanwhile for a low-pressure system, the pressure gradient force acts inward, and both the centrifugal and Coriolis forces act outward:
$$
\text{PGF = Coriolis + Centrifugal}
$$
Therefore, the differing rates of increase between the Coriolis and centrifugal forces do not compete with eachother, and for a given PGF, there is always a solution for the wind velocity. This permits smaller radii with higher wind speeds which can be maintained for stronger pressure gradient forces, thereby enabling low-pressure systems to be compact and intense.

# Circulation

Circulation describes atmospheric flow that involves rotation or curvature. It is defined as the line integral of the wind around a closed curve anywhere in the atmosphere:
$$
\text{C} = \oint \vec{V} \cdot d\vec{s}
$$
Unlike angular velocity, circulation does not require the definition of a centre of rotation. Circulation is positive for a counterclockwise flow.

According to Kelvin's circulation theorem, circulation is conserved in barotropic, inviscid, adiabatic flow.

For quantifying rotation in atmospheric dynamics, because it is not a local property. Thus it captures the aggregate rotational effect over an area, rather than the rotation at a single point in space, which is more relevant for understanding local atmospheric dynamics. 

# Vorticity

Vorticity is another way of describing the curved motion of fluid parcels without reference to a centre of rotation. It is defined as the circulation per unit area:

$$
\zeta = \frac{\partial C}{\partial A}
$$
Local vorticity is obtained in the limit as the circulation contour shrinks to a point. This allows analysis of fine-scale rotation without needing to define a full loop.
We can also compare how the zonal wind speed changes in the meridional direction and how the meridional wind speed changes in the zonal direction:
$$
\zeta = \frac{\partial v}{\partial x} - \frac{\partial u}{\partial y}
$$
Relative vorticity will be positive for counterclockwise rotation and negative for clockwise rotation. Therefore, rotation around low pressure in the NH will have positive relative vorticity and in the SH it will have negative relative vorticity.

Because the Earth is also rotating, we must define planetary vorticity (vorticity imparted to an air parcel by Earth's rotation) and relative vorticity (vorticity relative to the Earth's surface), which together comprise absolute vorticity:
$$
\eta = \zeta + f,
$$
where $f$ is the Coriolis parameter, $2 \Omega \sin(\phi)$.

## Vorticity Equation

$$
\frac{d}{dt}(\zeta + f) + (\zeta + f)\delta = 0,
$$
where $\delta$ is the horizontal divergence:
$$
\delta = \frac{\partial u}{\partial x} + \frac{\partial v}{\partial y},
$$
which is a measure of how much the zonal wind changes in the zonal direction and how much the meridional wind changes in the meridional direction.

This equation shows that even absolute vorticity is not conserved if there is horizontal divergence (i.e., stretching or compression of air columns). Absolute vorticity is conserved in inviscid, barotropic, non-divergent flow. This is because $\delta = 0$ and thus provides the barotropic vorticity equation:
$$
\frac{d}{dt}(\zeta + f) = 0
$$
Inviscid, barotropic, non-divergent flow is rarely found in the atmosphere. However, the 500 hPa lies in a quasi-barotropic region of the atmosphere, where the flow is close to geostrophic due to low friction, and horizontal divergence is week. This makes this pressure level ideal for applying the barotropic vorticity equation, where absolute vorticity is conserved.

In divergent or stratified flow, this conservation breaks down because $\delta \neq 0$, and potential vorticity must be used. It motivates the need for potential vorticity, which remains conserved under divergent, adiabatic flow.
### What can the 500 hPa level show us?

#### Vertical movement

In geostrophic conditions, the wind flows parallel to contour lines in the 500 hPa geopotential height field. Troughs, which exhibit cyclonic curvature correspond to regions of high relative vorticity. Ridges which exhibit anticyclonic curvature correspond to regions of low vorticity have low vorticity. The geostrophic wind can be used to trace where vorticity is being advected.

When air flows into a region of higher or lower absolute vorticity, it creates a local imbalance because it cannot immediately adjust its spin. The atmosphere responds by inducing vertical motion. When there is positive vorticity advection, air ascends, stretching the column and increasing vorticity. When there is negative vorticity advection, air descends, compressing the column and decreasing vorticity. Therefore, convergent and divergent flow (ascending and descending movement, respectively) redistribute air vertically, and absolute vorticity is not conserved.

Thus, from the 500 hPa geopotential, regions or rising or descending air can be inferred, providing insights into rainfall patterns (associated with rising air) or clear skies (descending air).


___

## Potential Vorticity

The disadvantage of relative vorticity compared to circulation is that divergence changes vorticity but conserves circulation. This can be remedied by including a layer thickness into the definition of vorticity, which leads us to the concept of potential vorticity. Potential vorticity (PV) is the absolute vorticity divided by the air column depth:
$$
\text{PV} = \frac{\zeta + f}{H}
$$
PV is conserved under frictionless, adiabatic conditions. PV is also conserved in divergent flow because in divergent flow, columns stretch (H increases), and η decreases proportionally to conserve PV. Conversely, convergence compresses the column (H decreases), and η increases.

The main issue is defining a useful layer thickness. A sensible finite number will strongly depend on the specific atmospheric conditions. Rather, a more general approach is to focus on thin atmospheric layers and use the local vertical properties of the atmosphere.

## Isentropic Potential Vorticity

Isentropic potential vorticity (IPV) is the PV along isentropic surfaces (surfaces of constant potential temperature $\theta$ - potential temperature is the temperature of an air parcel when moved adiabatically to a reference pressure, typically sea level). It combines dynamics (rotation) with thermodynamics (stratification). It considers atmospheric motion as an adiabatic process.
$$
\text{IPV} = \frac{\delta \theta}{\rho \delta z}(\zeta + f)\tag{1}
$$
Lynch and Cassano ([[Lynch and Cassano, 2006|2006]]) present IPV as:
$$
\text{IPV} = -g\frac{\delta \theta}{\delta p}\left(\zeta + f\right)\tag{2}
$$
Where the change in pressure due to elevation is rearranged to solve for $\rho$ and substituted into $(1)$
$$
\frac{\delta p}{\delta z} = -\rho g \tag{3}
$$
As for any other potential vorticity, isentropic potential vorticity is conserved in a barotropic, frictionless atmosphere. Whilst this is conserved, it does not mean that the rotation of the air does not change. Three things can provide changes in relative vorticity:
1. A change in the potential temperature difference.
2. A change in the pressure difference.
3. A change in the Coriolis parameter.

The thermodynamic element of the IPV equation is measured by $d \theta / d P$ which is a measure of the static stability of the atmosphere since it measures how fast potential temperature increases with altitude that is with decreasing pressure.

A stable atmosphere's  $d \theta / d P$ will have a large magnitude, and hence, have a large PV. Stratospheric air is very stable because it is heated from above by ozone absorption of UV radiation, which produces a temperature inversion, whereby temperature increases with height, in contrast to the troposphere. Thus, the potential temperature increases even more steeply with height, causing a very stable atmosphere. Thus, stratospheric air has much larger IPV that tropospheric air 

## Applications / implications

### Deflection over a topographic barrier

The conservation of isentropic potential vorticity (IPV) governs the meridional deflection of air as it flows over a topographic barrier, resulting in the formation of a stationary Rossby wave. In a stratified, adiabatic, inviscid atmosphere, an air column bounded by two isentropic surfaces conserves IPV as it moves. Although the isentropic surfaces themselves remain fixed for a given parcel, the vertical spacing between them (represented by $\delta \theta / \delta p$) varies as the lower isentrope conforms more tightly to the terrain than the upper. This induces changes in the static stability of the column as it ascends or descends the mountain.
$$
\text{IPV} = -g\frac{\delta \theta}{\delta p}\left(\zeta + f\right) = \text{Constant}\tag{2} 
$$

As the column of air approaches a mountain, the upper isentropic surface rises, causing the column to stretch. This causes a decrease in $\delta \theta / \delta p$. IPV is conserved because we are assuming an baratropic, inviscid atmosphere. Therefore, the absolute vorticity must increase to balance the decrease in $\delta \theta / \delta p$. Consequently, rotation is induced, increasing counter-calockwise rotation and relative vorticity. The air column also moves north, increasing its planetary vorticity. Thus, when $\delta \theta / \delta p$ is decreasing, the air column is deflected northwards and counter-clockwise rotation increases. Conversely, when $\delta \theta / \delta p$ is increasing, the air column is deflected southwards and counter-clockwise rotation decreases. This occurs when the air column impedes on the slope of the topographic barrier, causing the air column to be compressed significantly, increasing $\delta \theta / \delta p$. This causes significant southward displacement. 

Upon surpassing the crest of the topographic barrier, the air column stretches, decreasing $\delta \theta / \delta p$, thereby deflecting it back northwards, decreasing its counter-clockwise rotation. Because the air mass has momentum, when it returns back to its original line of latitude, despite having 0 vorticity (relative to its original vorticity before going over the topographic barrier), the air mass overshoots, and keeps moving northwards, thereby increasing its planetary vorticity. Because the air mass has passed the topographic barrier, we can assume that the two bounding isentropic surfaces are now at constant pressures apart, thus $\delta \theta / \delta p$ is constant. Therefore, for IPV to remain constant, the relative vorticity must decrease, inducing clockwise flow, which diverts to the air column back south. The same process occurs, but this time with an increasing relative vorticity to account for a decreasing planetary vorticity. This processes repeats, and consequently, a Rossy wave is formed. 

![[Pasted image 20250524213147.png]]

### Meridional movement of cyclones

The barotropic vorticity equation:
$$
\frac{d}{dt}(\zeta + f) = 0,
$$
describes the conservation of absolute vorticity in a barotropic, inviscid, non-divergent atmosphere. It explains why cyclones weaken when moving poleward and intensify when moving equatorward.

As a cyclone moves poleward, the planetary vorticity increases in magnitude (it becomes more positive in the NH and more negative in the SH). To conserve absolute vorticity, the relative vorticity must adjust in the opposite direction to the change in planetary vorticity. For a cyclone this means a reduction in cyclonic vorticity, whereby relative vorticity becomes less positive in the NH or less negative in the SH, resulting in cyclone weakening. Conversely, as a cyclone moves equatorward, the planetary vorticity decreases in magnitude, thus the relative vorticity must become more cyclonic (more positive in the NH, more negative in the SH), strengthening the cyclone.

The opposite occurs for anti-cyclones, which through the same principles of the conservation of absolute vorticity strengthen when they move poleward, and weaken when they move equatorward.

### Vorticity generation in baroclinic conditions

The atmosphere is baroclinic where density is not solely a function of pressure:

$$
\rho \neq \rho(P)
$$
Under baroclinic conditions, temperature is not constant along surfaces of constant pressure. Thus, temperature gradients exist along constant pressure surfaces, which create potential energy in the atmosphere. This potential energy can be converted into kinetic energy upon perturbation, which manifests itself as circulation and vorticity.

This is captured in the baroclinic term in the vorticity equation:
$$
\frac{1}{\rho^2}\nabla \rho \times \nabla p,
$$
which is non-zero in baroclinic conditions - the cross product of non-parallel vectors is non-zero. In barotropic conditions where isobars and isopyncals are parallel, the term vanishes, hence its omission in the other vorticity equations above.

**Mid-latitudes**

This configuration predisposes the mid-latitude atmosphere to baroclinic instability, where wave disturbances amplify, converting potential energy into kinetic energy and generating vertical vorticity and hence, cyclogenesis.

**Land-sea**

Differential heating between the land and sea also produce horizontal temperature gradients, resulting in baroclinic conditions.

### Vorticity generation from latent heat release

As moist air rises and condenses, latent heat is released into the air column. Latent heat warms the air column, lowing its local density and causing expansion aloft. This causes divergence in the upper troposphere. In the vorticity equation:
$$
\frac{d}{dt}(\zeta + f) + (\zeta + f)\delta = 0,
$$
divergent flow means that $\delta$ is positive, thereby causing a decrease in absolute vorticity. This equation cannot be explicitly used because it assumes adiabatic flow - the release of latent heat violates this assumption - however, it still qualitatively describes how divergence reduces vorticity aloft. Toward the surface, increased divergent flow aloft due to latent heat release results in more convergent flow near the surface in order to maintain mass continuity. Using the same principles, this causes an increase in absolute vorticity, thereby strengthening cyclonic motion around a low pressure system. This aids with cyclogenesis by intensifying cyclonic vorticity at the surface.



