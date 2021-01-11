---
permalink: /matlab/odeRK
title: "Runge-Kutta solver"
---

The function [`odeRK.m`](https://github.com/uwglacier/uwglacier.github.io/blob/main/code/matlab/odeRK.m) is an ODE integrator that uses an explicit fourth-order Runge-Kutta method. This is very similar to the built-in `ode45` function but without the adaptive timestep. This function is useful for prototyping models since it takes predictable timesteps. The syntax is described in the function header, and is nearly identical to the built-in Matlab integrators, except that you also have to provide the timestep.

