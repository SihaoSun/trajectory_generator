# trajectory_generator
This program generates payload trajectories leveraging differential-flatness of quadrotors. The users need to provide algebratic equations of quadrotor flat outputs (px,py,pz,psi). Then the trajectories including pos, vel, acc, omega, alpha are generated and stored in a csv file.

# Dependencies
Matlab R2023b (tested version, others may work)

CasADi toolbox (https://web.casadi.org/get/)

Robotics systems toolbox, for the `rotm2quat` function. Other toolboxes such as UAV toolbox may also work.

# Run
1. Define parameters in main.m
2. Define algebraic equations of trajectories in main.m
3. Run main.m

