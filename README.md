# ODEs for Simple Classical Mechanics

Assignment 1: In the free_fall.ipybn Jupyter notebook or in a separate Python program, verify the behavior of the Euler and RK2 algorithms as a function of the timestep. 
* In particular, plot the error on the final height of the ball as a function of dt for the Euler algorithm. Repeat the calculation for the RK2 algorithm to show that there are no truncation errors in this case.
* In the free_fall.ipybn Jupyter notebook or in a separate Python program, implement and run a fourth-order Runge-Kutta algorithm (e.g. following the Program 2.4 of the textbook). Verify that the free fall problem is still described exactly.

Assignment 2: (based off P2.2 of the textbook) In the projectile_motion.ipynb Jupyter notebook or in a seperate Python program, implement and run a free fall in two dimension, that is, projectile motion. The array of degrees of freedom will now have two coordinates and two velocities.  
* Write the function that plays the role of the generic diffeq() function and computes the derivatives of the different degrees of freedom (see equations in P2.2 of the textbook)
* Assume initial conditions as $x(0)=y(0)=0m$, launching speed and angle at $v_0(0)=10m/s$ and $\theta=30\degree$, respectively.
Follow the motion until the projectile hits the ground. Plot the $x(t)$ and $y(t)$ curves and compare with analytic results. 
* Optional: visualize the trajectory with VPython