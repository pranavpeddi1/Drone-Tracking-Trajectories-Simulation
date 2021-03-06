# Drone-Tracking-Trajectories-Simulation




![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Traectory%20Flight%20Controller.png)

                    Fig :- Flight Controller with Trajectory Planner



>From the above block diagram, the inputs for the Flight Controller Algorithm are desired positions their velocities and accelerations. 

>The position controller takes the desired inputs and feed backs of position and velocities from the onboard sensors of quadcopter. Then it generatesβ u1 βas control output for controlling the Altitude of drone. Also, the commanded Euler angles.

>These commanded Euler angles along with actual Euler angles and their rates from the sensors are taken as input for the Attitude controller which yields βu2 βas a control output of Moments.

>These Moments and Thrust acts on the Quadcopter a s rigid body and responses accordingly based on rigid body dynamics.


>In Trajectory planner we generate the desired positions so that the quadcopter will follow the desired trajectory.



*****************************************************************
# Minimum Jerk Trajectory Simulation

 >> Minimum Jerk Trajectory has 5th degree polynomial equation. 
 >> 
 >> s(t)=ππ‘5+ππ‘4+ππ‘3+ππ‘2+ππ‘+π 
 >> 
 >> We can extend the same trajectory to other dimensions as well.
 >>  
 >> Following are the Boundary conditions to solve the coefficients 
 >> 
 >> At t = 0: - s(t) = 0, v(t) = 0, a(t) = 0.
 >> 
 >> At t = 5: - s(t) = 20, v(t) = 0, a(t) = 0. 
 >> 
 >> The minimum Trajectory curve is used with the above boundary conditions for simulation in simscape multibody dynamics and obtained following simulation.
 
![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Trajectory1_Simulink.gif)

**************************************************************************************
# Helical Trajectory Simulation

>>Helical equations are implemented in Trajectory planner. 
>>
>>The equations used are shown below. 
>>
>>Desired Positions: - π₯=πβsin(π‘) , π¦=πβcos(π‘) , π§=β2βππβπ‘ . 
>>
>>Desired Velocities: - Vπ₯=πβcos(π‘) , ππ¦=βπβsin(π‘), ππ§=β2βππ . 
>>
>>Desired Accelerations: - Aπ₯=βπβsin(π‘) , π΄π¦=βπβcos(π‘) , π΄π§=0 .
>>
>>Desired Yaw and Yaw Rates: - ππ π=sin(π‘) , ππ ππππ‘= cos (π‘) .

>>Above Equatons are used in Trajectory Planner and simulated using the simscape multibody dynamics and obtained following simulation.


![alt text](https://github.com/pranavpeddi1/Drone-Tracking-Trajectories-Simulation/blob/main/Trajectory2_Simulink.gif)

*****************************************************************

For Project Codes :- 

Go To This Link : https://drive.google.com/file/d/1awzVzoaZSvMMn1iH_7c7_Z1aNhDfYMHr/view?usp=sharing

For Password Ping me 
*****************************************
