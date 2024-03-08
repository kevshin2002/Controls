# Linear Control Systems
These systems were solved as part of homework assignments in ECE 171B at UCSD taught by Professor YuanYuan Shi for Fall 2023.

Due to academic integrity, I can not post my full lab report on here. All analytical work can not be shown as well as it includes derivations. As such, only simulations and results will be shown. For the full lab report, please inquire at kevshin2002@gmail.com

## Breakdown
- Pendulum Systems
- Cruise Control 
- Nutrient System
- Op-Amp Voltage Follower Circuit
- GPS System
- Control Vehicle Steering

## Pendulum Systems
We work with the trivial pendulum example, where we analyze the stability and try to stabilize it via adding a controller. Anayltical works include computing the state trajectory without any controls, the phase portraits of linearized and original system, computing reachability matrix for controller design, and trajectory after controller design.

## Crusie Control
We try to understand how we can implement a cruise controller using just a PI controller. 

## Nutrient System
In this scenario, we try to design a state feedback controller to regulate the balance of our body nutrient system. A simplified two-compartment model is adopted where we only look at the gastrointestinal (digestive) system and the blood circulatory system.

## Op-Amp Voltage Follower Circuit
In this assignment, we try to stabilize the output of an Op-Amp by creating a controller and observer which combines to create an output feedback controller.

## GPS System
This trivial system uses a 1st order example to illustrate a Kalman Filter for noisy systems. This example assumes that the car is moving in a straight line.

## Control Vehicle Steering
For this assignment, we implement a output feedback controller and compare and contrast the cost of different controllers. 