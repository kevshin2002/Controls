# Voltage Follower Circuit Analysis
In this lab, we focused on using an op-amp as a voltage follower and optimized it by adding a compensation resistor to minimize ringing.

## Voltage Follower Circuit Topology
![Voltage Follower Circuit](./imgs/topology.png)

## Correlation of DC gain with Bandwidth
We can trade off DC for bandwidth or vice versa depending on our design needs. 

![DC and Bandwidth Correlation](./imgs/simulation_dc.png)
![DC and Bandwidth Correlation 1](./imgs/simulation_dc1.png)

## Adding a Capacitative Load to our Voltage Follwoer Circuit
![Simulation with Capacitative Load](./imgs/capacitive_load.png)

## Adding a Compenstation Resistor
![Simulation with Compensation Resistor and Capacitative Load](./imgs/capacitive_load+comp.png)

## Optimized Compensation Resistor
![Simulation of Optimized Compensation Resistor with Capacitative Load](./imgs/11_overshoot.png)

## Fastest Rise Time Simulation
![Simulation of Fastest Rise Time](./imgs/fastest_rise_time.png)

## DC and Bandwidth in Real Life Settings
### 10 DB Bandwidth
![10 DB Bandwidth](./imgs/10db.png)
### 30 DB Bandwidth
![30 DB Bandwidth](./imgs/30db.png)

## Simulations of LF411C Capacitor with different values in Real Life Settings
### 100pF
![100 pF Simulation](./imgs/simulation_100pf.png)
### 300pF
![300 pF Simulation](./imgs/simulation_300pf.png)
### 1nF
![1 nF Simulation](./imgs/simulation_1nf.png)
### 2nF
![2 nF Simulation](./imgs/simulation_2nf.png)
### 4nF
![4 nF Simulation](./imgs/simulation_4nf.png)
### 10nF
![10 nF Simulation](./imgs/simulation_10nf.png)

## Simulation of LF411C with Optimized Values in Real Life Settings
This optimization was for an overshoot less than 11%.

![Simulation of Optimized LF411C](./imgs/optimized_simulation.png)

## Rise Time in Real Life Settings
![Rise Time](./imgs/risetime_sim.png)

## Conclusion
We see that ideal op-amps have characteristics that are both ideal and non-ideal. By trading gain, we can gain more bandwidth and vice versa. We also saw that by adding a capacitor load, we get ringing, whic hwe can reduce by adding a compensation resistor. By having specific impedance dividers and circuit elements, we can manipulate our feedback ratio such that we transform our transfer function into a second order filter. This allows us to tailor it such that it meets our design specifications using metrics such as overshoot, rise time, and settling time.