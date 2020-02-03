# ASW-28-Simulator
This is a non-linear 6 degree of freedom simulator of power glider ASW-28 built by Simulink.

The simulator contains plant, actuators, sensors and controller module. Dimension and mass property of ASW-28 were written in matlab function asw28MassnGeometry. Dynamics of the aircraft including lift and drag equations were witten in matlab function aeroSurface. Dimension can be changed to other aircrafts. Restriction may be applied since this simulator is for fixed wing power glider with only one propeller. 

To use this simulator, simply download the asw_28_simulator.slx file. To run simulation, you need to have access to Aerospace Blockset library in Simulink. This simulator also achieves visualization by passing position and attitude values to FlightGear flight simulator. 

PS: There are three methods for building rotation kinematics, which are Euler kinematics, Poisson kinematics and Quaternion Kinematics. The block diagram for these three methods are all put in rot_kin.slx file, which are interchangeable. Note that when using Quternions, there will be one more state for linear analysis. 
