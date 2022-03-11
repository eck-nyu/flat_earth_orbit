# flat_earth_orbit
## Exercise from Chapter 1 of Statistical Orbit Determination by Tapley, Schutz, and Born (2004)
### We are given an initial guess for a satellite's orbital state vector state_0 = {X_0, Y_0, dX_0/dt, dY_0/dt, g}, with tracking station coordinates {X_s, Y_s}.
### Furthermore we are given a set of observations, in this case 5 range (rho, see figure below) measurements at specified times, and the true state vector state_true for checking convergence. 
### Use Newton-Raphson method to calculate a better estimate of the orbital state vector given the set of observations. 

![orbit_fig1](https://user-images.githubusercontent.com/22056545/157787827-3999dc73-6f7d-426c-b400-4ecacc2a1c37.jpg)
