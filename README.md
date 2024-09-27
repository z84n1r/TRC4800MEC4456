java c
Department of Mechanical and Aerospace Engineering 
TRC4800/MEC4456 Robotics 
PC 9: Multi-Variable   ControlProblem 1. Derive the   computed-torque-control   (CTC)   scheme   and write the   control   law   for the robot in Figure   1. Assume point masses.   The dynamics of   the system   is   given by: Figure   1: An RP manipulator
Problem 2. Specify the feedforward and feedback components of   the   CTC   law   derived   in   problem   1 and explain their roles.
Problem 3. Consider a linear control law (PD   controller) based   on   linearization   of   the   system   about an equilibrium point is directly used for a robotic manipulator.

Where Kv and Kp are positive definite matrices and   e    =   θ − θd.
Prove   that   if θ̇d      =   0, the control law applied to the system renders the equilibrium point   θd =   0   globally asymptotically stable.
The Lypunov function is defined   as:

Where P is the potential energy.
Problem 4. Suppose a PID computed torque controller law代 写TRC4800/MEC4456 Robotics PC 9: Multi-Variable Control
代做程序编程语言 is   applied to   eliminate nonzero   steady-state error, and the error   is   defined   as:
e   =      qd      −   q 
The error dynamics is   given by:

Draw the block diagram of   the proposed PID-CTC law and derive the   system dynamics equation with PID-CTC law, using the parameters below:
m1      =   m2    =    1kg                           l1    =   l2       =   1m  
The dynamics of   the system (Figure   2)   is   given by: 

Figure 2: An RR manipulator
Problem 5. Since we have proved that the   PD control law is asymptotically   stable   at the equilibrium point θ    =   0, when θ̇d      =   0. Now let’s consider a modified version of   the PD   control   law:

We call it augmented PD control law. Prove that   the   control   law   applied to   the   system   is asymptotically stable if, kv >   0, kp >   0, and explain how you would choose E. The   Lyapunov   function candidate is chosen   as:










         
加QQ：99515681  WX：codinghelp
