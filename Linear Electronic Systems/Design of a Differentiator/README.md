# Differentiator Circuit
In this circuit, we try to create a differentiator circuit. We also add a compensator to improve our phase margin which we do by adding either a resistor in series or a capacitor in parallel. We show that these two essentially do the same.

## Differentiator Circuit Topology
![Differentiator Circuit Topology](./imgs/differentiator_circuit.png)

### Frequency Response of Differentiator
![Frequency Response of Differentiator](./imgs/diff_freq.png)
### Step Response of Differentiator
![Step Response of Differentiator](./imgs/diff_step.png)
### MATLAB Data Specification of Differentiator
![MATLAB Data Specs of Differentiator](./imgs/diff_data.png)
### Overshoot of Differentiator
![Overshoot of Differentiator](./imgs/diff_overshoot.png)
### Risetime of Differentiator
![Risetime of Differentiator](./imgs/diff_risetime.png)
### Real Simulation of Differentiator
![Practical Simulation of Differentiator](./imgs/diff_real.png)

## Differentiator Circuit with Compensation Resistor Topology
![Differentiator Circuit Topology](./imgs/differentiator_compensator.png)
### Frequency Response of Differentiator with Compensation Resistor
![Frequency Response of Differentiator with Compensation Resistor](./imgs//diff_comp_freq.png)
### Step Response of Differentiator with Compensation Resistor
![Step Response of Differentiator with Compensation Resistor](./imgs/diff_comp_step.png)
### MATLAB Data Specification of Differentiator with Compensation Resistor
![MATLAB Data Specs of Differentiator with Compensation Resistor](./imgs/diff_comp_data.png)
### Overshoot of Differentiator with Compensation Resistor
![Overshoot of Differentiator with Compensation Resistor](./imgs/diff_comp_overshoot.png)
### Risetime of Differentiator with Compensation Resistor
![Risetime of Differentiator with Compensation Resistor](./imgs/diff_comp_risetime.png)
### Real Simulation of Differentiator with Compensation Resistor
![Practical Simulation of Differentiator with Compensation Resistor](./imgs/diff_comp_real.png)

### Frequency Response of Differentiator with Optimized Compensation Resistor
![Frequency Response of Differentiator with Optimized Compensation Resistor](./imgs/diff_optimized_freq.png)
### Step Response of Differentiator with Optimized Compensation Resistor
![Step Response of Differentiator with Optimized Compensation Behavior](./imgs/diff_optimized_step.png)
### MATLAB Data Specification of Differentiator with Optimized Compensation Resistor
![MATLAB Data Specs of Differentiator with Optimized Compensation Resistor](./imgs/diff_optimized_data.png)
### Overshoot of Differentiator with Optimized Compensation Resistor
![Overshoot of Differentiator with Optimized Compensation Resistor](./imgs/diff_optimized_overshoot.png)
### Risetime of Differentiator with Optimized Compensation Resistor
![Risetime of Differentiator with Optimized Compensation Resistor](./imgs/diff_optimized_risetime.png)
### Real Simulation of Differentiator with Optimized Compensation Resistor
![Practical Simulation of Differentiator with Optimized Compensation Resistor](./imgs/diff_optimized_real.png)

## Differentiator Circuit with Parallel Capacitor Topology
![Differentiator Circuit Topology](./imgs/differentiator_compensator_parallel.png)
### Overshoot of Differentiator with Parallel Capacitor
![Overshoot of Differentiator with Parallel Capacitor](./imgs/diff_parallel_overshoot.png)
### Risetime of Differentiator with Parallel Capacitor
![Risetime of Differentiator with Parallel Capacitor](./imgs/diff_parallel_risetime.png)
### Real Simulation of Differentiator with Parallel Capacitor
![Practical Simulation of Differentiator with Parallel Capacitor](./imgs//diff_parallel_real.png)

## Conclusion
We see that op-amps have characteristics that are both ideal and non ideal. The non-ideal characteristics interfere with our circuits that we are designing and cause ringing as a result of an extra pole. This illustrates the marginal stability of the circuit and how the gain and phase margins are related to the stability. By adding a compensation resistor, we can design our circuit to meet our design specifications by trading off overshoot for risetime.