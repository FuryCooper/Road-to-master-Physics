 This is the reading notebook of A First Course in String Theory. The author is Barton Zwiebach.

### Chapter4 Nonrelativistic String

The nonrelativistic string Lagarangian:
$$
S=\int_{t_i}^{t_f}L(t)dt=\int_{t_i}^{t_f}dt\int_0^adx\left[\frac12\mu_0\left(\frac{\partial y}{\partial t}^2\right)-\frac12T_0\left(\frac{\partial y}{\partial x}^2\right)\right]
$$

### Chapter6 Relativistic String

The line traced out by the particle in spacetime is called the world-line. The two-dimensional surface traced out by a string in spacetime will be called the World-sheet.

The proper time is the Lorentz invariant “proper length” of the world-line. For Strings we will define the Lorentz invariant “proper area” of a world-sheet. The action is called Nambu-Goto action.

reparameterization invariance: it means the value of the action is independent of the parameterization chosen to calculate it.
$$
ds^2=g_{ij}(\xi)d\xi^id\xi^j\\
g_{ij}(\xi)\equiv\frac{\partial\vec{x}}{\partial\xi^i}\cdot\frac{\partial\vec{x}}{\partial\xi^j}\\
Then\ A=\int d\xi^1d\xi^2\sqrt g
$$
Given usual spacetime coordinates $x^\mu(\tau,\sigma)$, we denote the mapping functions with capitalized symbols without changing the meaning of the functions: $X^\mu(\tau,\sigma)$.(String coordinates)

The Nambu-Goto string action:
$$
S=-\frac{T_0}{c}\int _{\tau_i}^{\tau_f}d\tau\int _{0}^{\sigma_f}d\sigma\sqrt{(\dot{X}\cdot X^{\prime})^2-(\dot{X})^2(X^{\prime})^2}\\
\delta S=\int _{\tau_i}^{\tau_f}d\tau\int _{0}^{\sigma_f}d\sigma\left[\frac{\partial}{\partial\tau}(\delta X^{\mu}P^\tau_\mu)+\frac{\partial}{\partial\sigma}(\delta X^\mu P^\sigma_\mu)-\delta X^\mu\left(\frac{\partial P^\tau_\mu}{\tau}+\frac{\partial P^\sigma_\mu}{\sigma}\right)\right]\\
P^\tau_\mu\equiv\frac{\partial L}{\partial \dot{X^\mu}},\ P^\sigma_{\mu}\equiv\frac{\partial L}{\partial X^{\mu\prime}}\\
$$
The second term has to do with string endpoints,equation of motion for the relativistic string:
$$
\frac{\partial P^\tau_\mu}{\partial\tau}+\frac{\partial P^\sigma_\mu}{\sigma}=0
$$
For boundary conditions of endpoints, two possible condition:
$$
Dirichlet\ B.C.:\ \frac{\part X^\mu}{\part\tau}(\tau,\sigma_*)=0,\\
free\ endpoint\ condition:\ P^\sigma_\mu(\tau,\sigma_*)=0
$$
The objects on which open string endpoints must lie are characterized by their dimensionality, more precisely, by the number of spatial dimensions that they have. They are called $D$-branes. A D$p$-branes is an object with $p$ spatial dimensions.