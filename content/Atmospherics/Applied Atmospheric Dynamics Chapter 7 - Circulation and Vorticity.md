[[Lynch and Cassano, 2006]]

# 7.1 Circulation

- Circulation describes atmospheric flow that involves rotation or curvature - defined as the line integral of the wind around a closed curve anywhere in the atmosphere
$$
\begin{equation}
C = \oint \overrightarrow{u} \cdot d\overrightarrow{s}
\end{equation}
$$
- Dot product to find the tangential velocity component
- Whilst angular velocity requires the definition of a center of rotation, circulation does not and therefore is a convenient measure when a single axis of rotation is difficult to identify
- Circulation is positive for a counterclockwise flow


## 7.1.1 Kelvin's Circulation Theorem

- Circulation around a closed curve is a function of time and space.
- Therefore, the rate of change of circulation is:
$$
\begin{equation}
\frac{DC}{Dt} = \oint \frac{D\overrightarrow{u}}{Dt} \cdot d\overrightarrow{s}
\end{equation}
$$

$$
= \oint -\frac{1}{\rho} \frac{\partial p}{\partial s} ds + \oint \frac{\partial \Phi}{\partial s} ds + \oint \text{friction}
$$
- in Navier stokes form ^
- Gravity term integrates to 0 around a closed circuit - makes sense since gravity force isn't involved in the generation of rotating motion - gravity acts through the center of mass
- Additionally, if the flow is baratropic, density is a function of pressure and therefore in a closed circuit, the pressure term is also 0
- If we assume a inviscid liquid (frictionless) - Kelvin's theorem therefore: circulation is constant in a baratropic, inviscid fluid.

##  7.1.2 Bjerknes' circulation theorem

- Conditions for Kelvin's circulation rarely hold - changes in circulation can arise from viscous forces and baroclinicity (Bjerknes, 1937)
- Baraclinic: surface of constant pressure has a temperature gradient
- I don't understand ! :D

## 7.1.4 Relative Circulation

- Considering a rotating frame of reference, a component of the circulation around any circuit will be due to the rotating frame:

$$
C_{\text{absolute}} = C_{\text{earth}} + C_{\text{relative}}
$$
- The circulation due to the rotation of the Earth - loop is taken around a loop of latitude
- Therefore, Earth's component is dependent on latitude - therefore, a meridional flow of air will experience an induced relative circulation to compensation for changes in the absolute circulation due to the rotation of the Earth

# 7.2 Vorticity

- Vorticity is another way of describing the curved motion of fluid parcels without reference to a centre of rotation
- Vorticity is the circulation per unit area:
$$
\zeta = \frac{\partial C}{\partial A}
$$
- Vorticity simplifies analysis because we no longer need to define a specific closed circuit in our flow of interest.
- Circulation represents the flux of vorticity
- Solid body vorticity for an infinitesimally small disk:
$$
\zeta = \frac{\partial C}{\partial A} = \frac{2\pi \delta rV}{\pi \delta r^2} = \frac{2V}{\delta r} = 2 \omega
$$
- Vorticity also has a component due to the rotation of the Earth.
- Earth's $\omega$ is $\Omega \sin{\phi}$ and hence it's vorticity is:
$$
\zeta_{\text{Earth}} = 2 \Omega \sin{\phi}
$$
- and is therefore positive in the NH and negative in the SH
- Relative vorticity is:
$$
\zeta = \frac{\partial v}{\partial x} - \frac{\partial u}{\partial y}
$$
	- How much X velocity changes in the Y direction and how much Y velocity changes in the X direction
- Relative vorticity will be positive for counterclockwise rotation and negative for clockwise rotation
	- Therefore, rotation around low pressure in the NH will be positive and in the SH it will be negative
- Typically, moderate to strong circulations on Earth have a relative vorticity one or two orders of magnitude larger than the absolute vorticity.
- Vorticity will change in time and space - temporal changes inform us about cyclonic system development whilst spatial changes indicate the influence of topography or temperature gradients
- The concept of *potential vorticity* can be used to address the variation in vorticity - potential vorticity is conserved in time

## 7.3 Conservation of potential vorticity

First: difference between barotropic and baroclinic:

![[Pasted image 20250508132821.png]]
From: https://www.youtube.com/watch?v=slZKmmjkiac

- In real cases, changes due to baroclinicity or friction mean that Kelvin's circulation theorem is invalid.
- However, we can simplify situations through two assumptions:
	- Far from the surface (therefore minimal frictional effects)
	- Motion is adiabatic (potential temperature is constant)
	- This is a '*potentiotropic*' situation
- Adiabatic flow is more closely approximated in the real atmosphere than barotropic flow - therefore, on a constant potential temperature surface, the pressure gradient term disappears and the fluid satisfies Kelvin's circulation theory. Therefore:
$$
\frac{D C_{\text{absolute}}}{D t} \Big|_{\theta} = 0
$$
- Assuming the constant potential surface is roughly horizontal (so we can integrate over a horizontal 2D surface, x and y):

$$
\zeta = \frac{\partial C}{\partial A} \\ \\
$$
$$
C_{absolute} = \int \int_{A} \zeta_{absolute} dA
$$
$$
C_{absolute} = \int \int_{A} (\zeta_{relative} + f) dA
$$
- Finding vorticity as we take the limit dA -> 0:
$$
\zeta_{relative} + f=\lim_{\delta A \rightarrow0}\frac{C_{absolute}}{\delta A}
$$
$$
\delta A(\zeta_{relative} + f) = C_{absolute}
$$
- Because $C_{absolute}$ is constant under Kelvin's Circulation Theorem (circulation is conserved in an inviscid, baraclonic liquid):
$$
\delta A(\zeta_{relative} + f) = \text{Constant}
$$

- Propose an air parcel confined between two potential surfaces: $\theta$ and $\theta + \delta \theta$, separated by pressure interval $\delta p$.
- Because under our assumption we are confining the parcel to a potential temperature, the motion is by assumption, adiabatic.

- The parcel's mass is given by:
$$
\delta M = \rho\delta z\delta A
$$
- Because pressure changes with elevation by the hydrostatic equation:
$$
\frac{dp}{dz} = -\rho g
$$
- Rearranged to:
$$
\rho = -\frac{dp}{gdz}
$$
- Substituted into $\delta M = \rho\delta z\delta A$:
$$
\delta M = -\left(\frac{\delta p}{g}\right)\delta A
$$
$$
\delta A = -\frac{\delta M g}{\delta p} = -\frac{\delta M g}{\delta p} \times \frac{\delta \theta}{\delta \theta} 
$$
- Fucking chain rule magic
$$
\delta A = -\frac{\delta Mg}{\delta \theta} \times \left(\frac{\delta \theta}{\delta p}\right)
$$
- Because we are assuming a constant potential temperature $\theta$ (mass is also constant):
$$
\delta A = -\text{Constant} \times g\frac{\delta \theta}{\delta p}
$$
- Combining with Constant equation from above:
$$
\left(\text{Constant}\times -g\frac{\delta \theta}{\delta p}\right)\left(\zeta_{\theta} + f\right) = \text{constant}
$$
$$
\text{Isten Potential Vorticity, P} = -g\frac{\delta \theta}{\delta p}\left(\zeta_{\theta} + f\right)
$$

- As a column of air approaches a mountain, the upper potential temperature surface rises, causing the column to increase in depth which causes a decrease in $\delta \theta / \delta p$ ($\theta$ (potential temperature) is constant and pressure decreases with height)
- From supo: potential vorticity is absolute vorticity divided by the depth of the air column
	- Has the disadvantage that it is defined for a particular layer and defining a layer is rather arbitary in the atmosphere
	- A few obvious choices: boundary layer, tropopause
	- Isentropic potential vorticity is conserved on an isentropic surface in a baratropic, inviscid atmosphere.
	- Isentropic surface -> surfaces of constant potential temperature 
		- Constant potential temperature is indicative of a neutral atmosphere
		- Potential temperature increases with altitude in a stable atmosphere
		- $g\frac{\delta \theta}{\delta p}\left(\zeta_{\theta} + f\right)$ -> looking at the difference between pressures means that the thickness is removed - thickness will increase as we increase altitude
		- In a stable atmosphere, as we rise, potential temperature increases, and pressure decreases.
		- dtheta constant in istentropic surface
- Because potential vorticity is constant (above), $\left(\zeta_{\theta} + f\right)$ must increase, inducing rotation
- $\zeta_{\theta}$ can increase, increasing counter-clockwise rotation
- $f$ can increase, moving the air mass northward
- QUESTION FOR MICHAEL: does $f$ increase *because* it moves poleward, or does it move poleward in order to increase $f$ to balance it all

- Once the flow impinges on the rising slopes of the mountain, the air column decreases in depth, increasing $\delta \theta / \delta p$. Therefore, vorticity must decrease, generating a strong anticyclonic rotation - source of high pressure on the windward side of a long mountain range.
- In turn, results in southward flow, reducing planetary vorticity.
- Returns to a point more northwards (WHY MICHAEL WHY) -> larger $f$ than initially, causing clockwise rotation and equatorward motion - can generate a lee side wave

![[Pasted image 20250227154158.png]]

![[Pasted image 20250301180456.png]]
## An introduction to the vorticity equation

- Even where potential vorticity is conserved, relative vorticity is not (interplay between relative and planetary)
- Interplay between relative and planetary vorticity is an important aspect of the generation of atmospheric circulations
- Vorticity equation is used to predict the change in time and space of the vorticity
- Can be derived from first principles using the Navier-Stokes equations

$$
\frac{D_h}{Dt}\left(\zeta + f\right) = -f\left(\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y}\right)
$$
- Synoptically scaled vorticity equation tells us that changes in time of relative vorticity are generated by the advection of relative and planetary vorticity, and by the convergence of planetary vorticity carrying air.
- For a Rossby wave, divergence can be said to be 0.
- Meanwhile, if we wish to understand the temporal evolution of a mid-latitude cyclone we should use a theoretical model that allows for convergence and divergence
	- $\left(\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y}\right)$ is the divergence / convergence term which tells us how air is spreading out or converging
- In geostrophic flow we assume Continuity equation:
$$
\nabla \cdot \textbf{V} = 0
$$
$$
\frac{\partial u}{\partial x} + \frac{\partial v}{\partial y} + \frac{\partial w}{\partial z} = 0
$$
- Therefore:
$$
\frac{D_h}{Dt}\left(\zeta + f\right) = f\left(\frac{\partial w}{\partial z}\right)
$$
- Changes in vorticity are linked to vertical motion
- Quasi-geostrophic flow: divergence in the horizontal is balanced by convergence in the vertical and vice versa
- Therefore, relative vorticity in a quasi-geostrophic situation will be generated by the advection of relative vorticity.

Summaryish
- Vorticity changes are modified by:
	- Advection of vorticity
	- Stretching / compression of air columns
- Important for the development of mid-latitude storms

I genuinely have no clue what is going on
