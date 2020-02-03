# ASW-28-Simulator
This is a non-linear 6 degree of freedom simulator of power glider ASW-28 built by Simulink.

The simulator contains plant, actuators, sensors and controller module. Dimension of ASW-28 was written in matlab function aeroSurface. Dynamics of the aircraft including lift and drag equations were also in aeroSurface. Dimension can be changed to other aircrafts. Restriction may be applied since this simulator is for fixed wing power glider with only one propeller. 

To use this simulator, simply download the asw_28_simulator.slx file. To run simulation, you need to have access to Aerospace Blockset library in Simulink. This simulator also achieves visualization by passing position and attitude values to FlightGear flight simulator. 
