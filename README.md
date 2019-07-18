## Understanding Energy Transfer in Plasma Turbulence

Welcome to my virtual gallery! 
Please enjoy these fun visualizations that illustrate what's happening in plasma turbulence simulations.

### What do these visuals show?

To simulate plasma turbulence, we computationally simulate stirring fluid inside a 3D box. The **forcing amplitude** tells us how quickly we spin the stir sticks. Varying the forcing amplitude allows us to simulate turbulent systems with different levels of compressibility (different sonic Mach numbers). In these simulations, we include forcing amplitudes of 0.25, 1, 4, 16, and 64. The multipanel animations follow this order from left to right and top to bottom.
 
The features illustrated include density, velocity, acceleration, and cell-centered magnetic field magnitudes (though we could have plotted other features as well). Each plot illustrates how one of these features evolves from the beginning of the simulation to the end. Remember: these are sliceplots, so they are only giving us a two dimensional view of what is really a 3D simulation. The sliceplots shown here are all perpendicular to the x axis, but we could just as easily have chosen to look from the y or z direction.

## Hydrodynamic simulations

These visuals come from hydrodynamic situations. They show plasma turbulence with no magenetic fields present.

#### Density
![](hydro_density_x_movie.gif)

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
