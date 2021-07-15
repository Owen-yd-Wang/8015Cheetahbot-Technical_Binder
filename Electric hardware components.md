# Electric hardware components

***Before you start:*** Read carefully through this [document](https://docs.wpilib.org/en/stable/docs/controls-overviews/control-system-hardware.html)

<h2 id ='1'>RoboRIO</h2>

As the "brain" of the robot, roboRIO is the only command processor in the robot. 

1. CAN port: NI RoboRIO has only one pair of CAN ports, which means that RIO has to be either the start or the end of the CAN string
2. RSL port: RSL stands for Robot Signal Light. In competitions, if RSL stop flashing, the connection will be automatically shut down. When wiring RSL, remember to use electrical adhesive tape to fix the wire. 
3. Only one intertnet port, remember to connect it to the router. There're two USB ports, they can be connected to the cameras. 
4. If the connection to the robot is broken, rebase roboRIO via [Driver Station](https://docs.wpilib.org/en/stable/docs/software/driverstation/driver-station.html#frc-driver-station-powered-by-ni-labview) (this will be further explained in coding part). 
5. Before each session, remember to update firmware by [roboRIO Imaging Tool](https://docs.wpilib.org/en/stable/docs/controls-overviews/control-system-software.html) (this will be further explained in coding part). 

## Power Distribution Panel (PDP)

PDP is the center power distribution place on the robot. It directly connects to the battery and distributs power to the applicances. On PDP, there're 8 output pairs of 40A continuous current and 8 pairs of 30A continuous current with both 12V DC. There're also 3 pairs of jumpers, which applies for [roboRIO](#1), VRM and PCM (jumpers are indicated). 




