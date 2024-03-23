# Wien Bridge Oscillator and Nyquist Plot
In this lab, we utilize nyquist plot to realize the stability of our previous lab circuits. We also use the Nyquist plot on the Wien Bridge while seeing that diodes in different regions give the same output.

### Bode and Phase Plot of Differentiator
![Bode and Phase Plot of Differentiator](./imgs/bode+phase_diff.png)
### Nyquist Plot of Loop Gain of Differentiator
![Nyquist Plot of Loop Gain of Differentiator](./imgs/nyquist_loop_diff.png)

### Bode and Phase Plot of Differentiator with Compensation Resistor
![Bode and Phase Plot of Differentiator with Compensation Resistor](./imgs/bode+phase_diff+resistor.png)
### Nyquist and Phase Plot of Differentiator with Compensation Resistor
![Nyquist Plot of Differentiator with Compensation Resistor](./imgs/nyquist_loop_diff_resistor.png)

### Bode and Phase Plot of Voltage Follower Circuit
![Bode and Phase Plot of Voltage Follower Circuit](./imgs/bode+phase_voltage.png)
### Nyquist Plot of Loop Gain of Voltage Follower Circuit
![Nyquist Plot of Loop Gain of Voltage Follower Circuit](./imgs/nyquist_loop_voltage.png)

### Bode and Phase Plot of Voltage Follower Circuit with Capacitative Load
![Bode and Phase Plot of Voltage Follower Circuit with Capacitative Load](./imgs/bode+phase_voltage+capc.png)
### Nyquist Plot of Loop Gain of Voltage Follower Circuit with Capacitative Load
![Nyquist Plot of Loop Gain of Voltage Follower Circuit with Capacitative Load](./imgs/nyquist_loop_voltage+capc.png)

### Bode and Phase Plot of Voltage Follower Circuit with Optimized Capcitative Load
![Bode and Phase Plot of Voltage Follower Circuit with Optimized Capcitative Load](./imgs/bode+phase_voltage_optimized.png)
### Nyquist Plot of Loop Gain of Voltage Follower Circuit with Optimized Capacitative Load
![Nyquist Plot of Loop Gain of Voltage Follower Circuit with Optimized Capacitative Load](./imgs/nyquist_loop_voltage_optimized.png)

### Topology of Wien Bridge Circuitry
![Topology of Wien Bridge Circuitry](./imgs/wien_bridge_circuit.png)
### Simulation Model of Wien Bridge Oscillator
![Simulation Model of Wien Bridge Oscillator](./imgs/simulation_model_wien.png)
### Nyquist Plot of Wien Bridge Oscillator
![Bode and Phase Plot of Wien Bridge Oscillator](./imgs/nyquist_loop_wien.png)
### Simulation of Wien Bridge Oscillator using Simulink
![Simulation of Wien Bridge Oscillator](./imgs/simulation_wien.png)
### Simulation of Wien Bridge Oscillator
![Simulation of Wien Bridge Oscillator](./imgs/wien_bridge_simulation.png)
### Fast Fourier Transform of Wien Bridge Oscillator
![FFT of Wien Bridge Oscillator](./imgs/wien_bridge_FFT.png)
### Minimum Frequency of Wien Bridge Oscillator
![Min Freq of Wien Bridge Graph](./imgs/wien_bridge_minimumfreq.png)
### Maximum Frequency of Wien Bridge Oscillator
![Max Freq of Wien Bridge Graph](./imgs/wien_bridge_maxfreq.png)
### Soft Clipping of Wien Bridge Oscillator
![Soft Clipping of Wien Bridge](./imgs/wien_bridge_softclipped.png)
### Real Clipping of Wien Bridge Oscillator
![Real Clipping of Wien Bridge](./imgs/wien_bridge_real_clipping.png)
### Output of Wien Bridge Oscillator
![Output of Wien Bridge Oscillator](./imgs/wien_bridge_real.png)
### Soft Clipping of Wien Bridge Oscillator at 301 kHz
![Soft Clipping at 301 kHz](./imgs/wien_bridge_softclipping_301kHZ.png)

### Topology of Wien Bridge Circuitry with Parallel Diodes
![Topology with Parallel Diodes](./imgs/wien_bridge_parallel.png)
### Simulation of Wien Bridge Oscillator with Parallel Diodes
![Simulation of Parallel Diodes](./imgs/wien_bridge_parallel_simulation.png)
### Fast Fourier Transform of Wien Bridge Oscillator with Parallel Diodes
![FFT of Parallel Diodes](./imgs/wien_bridge_parallel_FFT.png)
### Soft Clipping of Parallel Diodes at 6k Resistance
![6k Resistance Soft Clipping](./imgs/wien_bridge_parallel_softclipping_6k.png)
### Output of Wien Bridge Oscillator at 6k Resistance
![Output of Wien Bridge Parallel Diodes with 6k Resistance](./imgs/wien_bridge_parallel_6k.png)
### Soft Clipping of Parallel Diodes at 15k Resistance
![15k Resistance Soft Clipping](./imgs/wien_bridge_parallel_softclipping_15k.png)
### Output of Wien Bridge Oscillator at 15k Resistance
![Output of Wien Bridge Parallel Diodes with 15k Resistance](./imgs/wien_bridge_parallel_15k.png)
### Maximum Frequency of Wien Bridge Oscillator at 15k Resistance
![Maximum Frequency of Wien Bridge Oscillator at 15k Resistance](./imgs/wien_bridge_max_freq_15k.png)

## Conclusion
We see how the Nyquist plot is a powerful tool in determining the stability as it allows us to look at the open-loop circuit and understand if the closed-loop system is stable. In addition, we understand how positive feedback is utilized such as in the Wien-Bridge Oscillator where we can take advantage of noise caused by resistors. By setting our gain to be greater than 3, we cause our system to become unstable, which allows our noise to be increased and formed into a sine wave due to the frequency being on the imaginary axis with no real part. 

We learned that these outputs are clipped but can be deferred by implementing strategies such as hard clipping or soft clipping with zener diodes, a result of their non-linaer IV models. In addition, we got a more in-depth understanding of the non-ideal characteristics of op-amps where it has a finite bandwidth as a result of a hard-set current source.