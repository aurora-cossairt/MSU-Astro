## Understanding Energy Transfer in Plasma Turbulence

Welcome to my virtual gallery! 
Please enjoy these visualizations that illustrate my **plasma turbulence simulations**

<p align="center">
  <img src="MHD_a-64.00_density_z.gif">
</p>

### What do these visuals show?

*Plasma turbulence* is irregular motion of plasma fluids. It plays an important role in star formation, galaxy formation, and other interesting phenomena, but **turbulence is not well understood.**

To **simulate plasma turbulence**, we computationally simulate stirring fluid inside a 3D box. The visuals here are *sliceplots* which let us *peer through one side of the box* to see what is happening inside. 

This example (from a hydrodynamic simulation) looks along the x-axis to see the *density of the fluid* inside:

<p align="center">
  <img src="a-64.00_density_x.gif">
</p>

Here's the same simulation viewed along the z-axis:

<p align="center">
  <img src="a-64.00_density_z.gif">
</p>

The **forcing amplitude** tells us how quickly we spin the stir sticks that drive the turbulence. Varying the forcing amplitude allows us to simulate turbulent systems with **different sonic Mach numbers** (different levels of compressibility). 

Here is a look at 5 different simulations (all viewed along the x-axis) with Mach numbers of 0.4, 0.8, 1.6, 2.9, and 5.6 (from upper left to bottom right). 

<p align="center">
  <img src="hydro_density_x_movie.gif">
</p>

We can see **shock waves** developing in the bottom two panels (and a bit of the upper right). This is because these simulations had Mach numbers greater than 1, so the plasma particles are moving **faster than the speed of sound**.

*Notice* that all these visuals have their own colorscale. This is because there is significantly more variation in the density of simulations with higher Mach numbers than in those with low Mach numbers. If we used the same colorscale for all, we wouldn't detect any turbulence in the simulations with low Mach numbers.

We can also examine **velocity** and **acceleration** for these simulations.

**Velocity**
<p align="center">
  <img src="hydro_velocity_x_x_movie.gif">
</p>

**Acceleration**
<p align="center">
  <img src="hydro_acceleration_x_x_movie.gif">
</p>

The acceleration sliceplots barely seem to change. Why is that? Here, *acceleration* refers to the acceleration of the **driving** (the "stirring"). We have set the parameters of the simulations so that the forcing amplitude is constant, so the acceleration associated with the driving force should remain the same.

### Magnetized Turbulence

The previous examples were all from **hydrodynamic** simulations (meaning there were no magnetic fields). *Without magnetic fields, plasma behaves just like any other fluid.* For this reason, we are interested in **magnetohydrodynamics** (MHD)--how plasma fluid moves in the presence of magnetic fields.

Let's look again at one of the density sliceplots. The streamlines here illustrate the magnetic field lines (which begin all pointing the same direction).

<p align="center">
  <img src="MHD_a-64.00_density_z.gif">
</p>

Notice how the features of these simulations seem to be shaped by the magnetic field lines! This is due to **flux-freezing**, a phenomenon in which magnetic field lines are "frozen in" to the plasma fluid. If the fluid moves, so do the magnetic fields. This creates **magnetic tension** which can, in turn, **impose structure** on the fluid.

*Look what happens* to the velocity in an MHD simulation!

<p align="center">
  <img src="a-64.00-256-MHD_velocity_y_y.gif">
</p>

Again, we can vary the **forcing amplitude** to see how this plays out for simulations with different **sonic Mach numbers** (upper left to bottom right: Ms = 0.4, Ms = 0.8, Ms = 1.6, Ms = 2.9, Ms = 5.6)

**Density**

<p align="center">
  <img src="MHD_density_y.gif">
</p>

**Velocity**

<p align="center">
  <img src="MHD_velocity_y_y_movie.gif">
</p>

**Acceleration**

<p align="center">
  <img src="MHD_acceleration_y_y_movie.gif">
</p>

### Energy Transport

All of these simulations can help us understand **how energy is transported** is turbulent systems. We are interested in how energy gets converted from *kinetic* to *magnetic* (and vice-versa) and how energy is carried from *large scales* to *small scales* (and vice-versa)

A **Kolmogorov Power Spectra** illustrates how much energy is contained in different scales in the simulation. This animation shows how the *Kinetic Energy Power Spectrum* changes over the course of the simulation

![](rhoU_Full_power_spectra.gif)

Creating this kind of power spectrum is one way that we can *analyze energy transport* in the simulations. As part of the ICER-ACRES program at Michigan State University, I helped develop *a new way to analyze energy transport*. To learn more about what we learned, please refer to my poster (presented at the 9th annual Mid-Michigan Symposium for Undergraduate Research Experiences (Mid-SURE))

## Acknowledgements
Thanks to my mentors, Dr. Philipp Grete and Dr. Brian O'Shea of Michigan State University.

We run our plasma turbulence simulations using Athena, which was developed at Princeton (https://github.com/PrincetonUniversity/Athena-Cversion)

Citation: J. M. Stone, et. al. (2008). Astrophys. J. Suppl. Ser. 178, 137
