# Plot-orbit-of-two-body-using-rk4
This program simulates the orbit of an orbiting mass around a central mass (e.g., a satellite orbiting the Earth) using the Runge-Kutta 4th Order numerical method. The initial conditions of the satellite are set for a geostationary orbit. The satellite's initial position is 35,786 kilometers above the Earth's surface, and its initial velocity is 3.07 kilometers per second, resulting in a circular orbit. Modifying the initial speed slightly changes the orbit's eccentricity, making it more elliptical as the value deviates from 3.07 km/s.

The period of the simulation can be adjusted, but it is currently set for one day, which corresponds to the approximate time a geostationary satellite takes to complete a single orbit. The entire animation is rendered using the tkinter module, with customizable options such as color, canvas dimensions, and additional graphical features like tracer and radial lines.
## Simulation Results

Below are images showing the satellite's orbit with different initial velocities.

- The image on the left shows a circular orbit with an initial velocity of 3.07 km/s.
- The image on the right demonstrates an elliptical orbit with an initial velocity of 2.07 km/s.

Increasing the velocity further can result in a hyperbolic trajectory, where the satellite does not return.

![Satellite Orbit Simulation](Orbits.png)
