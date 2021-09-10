# SIMULATION AND INVESTIGATION OF AUTOMATIC COORDINATION IN MULTILANE MOTORWAY

![N|Solid](https://th.bing.com/th/id/OIP.EVYtEYwaWrmaP9DzUZhdawHaFj?pid=ImgDet&rs=1)

The primary goal of this research is to develop a simulation for a highway with automatic coordinated motorway. This simulation is performed using SimPy V.4 package in Python. This simulation is to minimize the traffic overflow, with a motorway of totally three kilometers which is around 2kilometers for the three lanes and that decreased into two lanes of about 1 Kilometer. With the support of vehicle’s 
parameters includes such as vehicle length, acceleration, deceleration, and human driver’s actions such as speed, lane change, yielding for other vehicles and some other assumptions like inter-arrival time distribution and speed limits for each lane, will simulate the model to find highest number of vehicles can be accommodated in the motorway. The vehicles such as electric cars, autonomous cars and heavy goods vehicles are the types of vehicles used in the simulation. The average travel timing is also estimated in the model simulation.

## Research Questions:
1. How much vehicle can be accommodated in the three to two merge multi lane highway?
2. What will be the average time travelling, average speed, maximum overflow, and maximum throughput, that depends on the speed?

![N|Solid](https://th.bing.com/th/id/OIP.m4SgdkNz52SDhpkfXWiTCwHaEK?pid=ImgDet&rs=1)

The primary objective is to find the traffic flow and how much vehicles can be fitted into the highway. The object-oriented characteristics such as inheritance and encapsulation in the Python programming is used to establish the methodology of the simulation. The process starts by creating objects and classes for different types 
of entities.

The Class Recorder is used to run all the events such as crashing, overtaking, braking, changeLane occurs during simulation. After the running, the process of simulation is stored in the separate pandas dataframe. The various events 
occurring in the class Recorder are mentioned below.

#### A. Emergency Braking:
It is the situation of braking when it happens during the simulation, it will be recorded.

#### B. Crash:
Crashing is recorded when any vehicles crash during the run in the simulation.

#### C. Enter: 
Enter is the event when vehicle enters the lane, it will be recorded.

#### D. Leave:
Leave is the event which happened when a vehicle leaves the lane, this will be recorded during the simulation run.

#### E. End:
End is recorded when the simulation has come to end.

The Simulation is the replication of the real-world events in virtual technology. This project is self-organizing vehicles created by using simulation process. It runs for various times to estimate the optimal simulation result. In this research, Throughput will be estimated along with traffic flow (volume), traffic density, average speed and average total travelling time. An environment is created using simPy.environment. The classes and functions are combined all together in a single 
environment using env.process. The simulation runs using env.run, all the events runs from the declared start and stop time. No events will run after the stop time, it will be ended.

#### A. Traffic flow or traffic volume:
Traffic flow is the flow of the vehicles in the motorway, which is calculated by taking difference between the vehicle that enters the lane and which leaves the lane in the highway.

#### B. Throughput:
Throughput is the aggregation volume between one direction lanes and the time. In this scenario, throughput is calculated by the difference between the last vehicle which leaves the lane and the first vehicle that leaves the lane.

#### C. Average speed:
Average Speed is the calculation of the ratio of total lane length and total travelling time of the vehicle. After that, average will be taken by using the number of cars selected.

#### D. Traffic density:
Traffic density is the ratio of throughput and the average total travelling time taken for the highway.

#### E. Average Total Travelling time:
Average total travelling time is the mean of the total time travelled by the vehicles all through the motorway. In this scenario, all the vehicles total time which passes 
through the highway from the enter lane to the leave lane is being calculated. Then, the average time will be estimated according to the total number of vehicles selected while simulation.

# SIMULATION RESULTS
![N|Solid](https://github.com/IswaryaYogeashwaran/Modelling-Simulation-and-Optimization/blob/main/MSOPICTURE1.png?raw=true)
