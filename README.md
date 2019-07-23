## Understanding Energy Transfer in Plasma Turbulence

Welcome to my virtual gallery! 
Please enjoy these fun visualizations that illustrate what's happening in plasma turbulence simulations

<iframe width="560" height="315" src="https://www.youtube.com/embed/U0Cxs1h-4Dc" frameborder="0" allow="autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### **Turbulence is Beautiful**

<p align="center">
  <img width="690" height="450" src="MHD_a-64.00_density_z.gif">
</p>

![](MHD_a-64.00_density_z.gif)
<iframe width="560" height="315" src="https://www.youtube.com/embed/U0Cxs1h-4Dc" frameborder="0" allow="autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

*Plasma turbulence* is irregular motion of plasma fluids. It plays an important role in star formation, galaxy formation, and other interesting phenomena, but **turbulence is not well understood.**

**Large scale computer simulations** allow us to *visualize* turbulence and *analyze* what is happening.

Another attempt:

<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/U0Cxs1h-4Dc" frameborder="0" allow="autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

### What do these visuals show?

To simulate plasma turbulence, we computationally simulate stirring fluid inside a 3D box. The **forcing amplitude** tells us how quickly we spin the stir sticks. Varying the forcing amplitude allows us to simulate turbulent systems with **different levels of compressibility** (different sonic Mach numbers). Our simulations have Mach numbers of Ms=0.4, Ms=0.8, Ms=1.6, Ms=2.9, and Ms=5.6. 
 
These animatations illustrate *density, velocity, acceleration, and cell-centered magnetic field magnitudes*. They allow us to visualize how these features change over the course of the simulation (start at Turb.0001, end at Turb.0100). 

Remember: **these are sliceplots**, so they are only giving us a two dimensional view of what is really a 3D simulation. Most of the sliceplots shown here are oriented perpendicular to the x axis, but we could just as easily have chosen to look from the y or z direction.

![](hydro_a-64.00_density_z.gif)
## Hydrodynamic simulations

These visuals come from hydrodynamic situations. They show plasma turbulence with no magenetic fields present.

#### Density
<p align="center">
  <img width="460" height="300" src=hydro_density_x_movie.gif>
</p>

*Noteable features*: notice that all these visuals have their own colorscale. This is because there is significantly more variation in the density of simulations with high forcing amplitudes than in those with low forcing amplitudes. Using independent scales for each simulation allows us to detect the turbulence present in all of them, rather than only those with large forcing amplitudes.

In the last three panels, we see shock waves developing. This indicates that the sonic Mach number is greater than or equal to 1 (the speed of the average particle is greater than the speed of sound).

#### Velocity
![](hydro_velocity_x_x_movie.gif)

### Magnetohydrodynamic (MHD) Simulations
These visuals illustrate plasma turbulence in the presence of magnetic fields. The streamlines here illustrate the magnetic field lines in the two directions perpendicular to the viewing direction. I've also changed the colorscheme so it's easier to see the streamlines. Notice how the features of these simulations seem to be shaped by the magnetic field lines.

#### Density
![](MHD-256.gif)

### Velocity
![](MHD_velocity_x_x_movie.gif)

### Acceleration
![](MHD_acceleration_x_x_movie.gif)

### Cell-centered magnetic field magnitudes
![](MHD_cell_centered_B_x_x_movie.gif)

### Power Spectra

![](rhoU_Full_power_spectra.gif)

## Acknowledgements
We run our plasma turbulence simulations using Athena, which was developed at Princeton (https://github.com/PrincetonUniversity/Athena-Cversion)

## Image experimentation

<img src='https://youtu.be/U0Cxs1h-4Dc' title='MHD sim' width='' alt='MHD sim' />
