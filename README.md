# Drone-Tracking-Trajectories-Simulation




![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Traectory%20Flight%20Controller.png)
# Flight Controller with Trajectory Planner



>From the above block diagram, the inputs for the Flight Controller Algorithm are desired positions their velocities and accelerations. 

>The position controller takes the desired inputs and feed backs of position and velocities from the onboard sensors of quadcopter. Then it generates’ u1 ‘as control output for controlling the Altitude of drone. Also, the commanded Euler angles.

>These commanded Euler angles along with actual Euler angles and their rates from the sensors are taken as input for the Attitude controller which yields ‘u2 ‘as a control output of Moments.

>These Moments and Thrust acts on the Quadcopter a s rigid body and responses accordingly based on rigid body dynamics.

>Flight Controller Algorithm the input for the Position Controller is the desired positions , desired velocities and their acceleratons.
>
>In Trajectory planner we generate the desired positions so that the quadcopter will follow the desired trajectory.



*****************************************************************
Minimum Jerk Trajectory Simulation
![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Trajectory1_Simulink.gif)

**************************************************************************************
Helical Trajectory Simulation

![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Trajectory2_Simulink.gif)

*****************************************************************

For Project Codes :- 

Go To This Link :

For Password Ping me :
*****************************************
