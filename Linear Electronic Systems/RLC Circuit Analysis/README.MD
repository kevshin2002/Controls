# RLC Circuit Analysis
The lab focused on four simple filters composed made up of only RLCs:
- Highpass
- Lowpass
- Bandpass
- Mystery (Bandstop)

## MATLAB Plots
### Highpass Filter
#### Circuit
![Highpass Filter Circut](./imgs/highpass_circuit.png)
#### Bode Plot (linear)
![Highpass Bode Plot (linear)](./imgs/highpass_bode_linear.png)
#### Bode Plot (Logarithmic)
![Highpass Bode Plot (Logarithmic)](./imgs/highpass_bode_log.png)
#### Phase Plot
![Highpass Phase Plot](./imgs/highpass_phase.png)

### Lowpass Filter
#### Circuit
![Lowpass Filter Circut](./imgs/lowpass_circuit.png)
#### Bode Plot (linear)
![Lowpass Bode Plot (linear)](./imgs/lowpass_bode_linear.png)
#### Bode Plot (Logarithmic)
![Lowpass Bode Plot (Logarithmic)](./imgs/lowpass_bode_log.png)
#### Phase Plot
![Lowpass Phase Plot](./imgs/lowpass_phase.png)

### Bandpass Filter
#### Circuit
![Bandpass Filter Circut](./imgs/bandpass_circuit.png)
#### Bode Plot (linear)
![Bandpass Bode Plot (linear)](./imgs/bandpass_bode_linear.png)
#### Bode Plot (Logarithmic)
![Bandpass Bode Plot (Logarithmic)](./imgs/bandpass_bode_log.png)
#### Phase Plot
![Bandpass Phase Plot](./imgs/bandpass_phase.png)

### Mystery Filter
#### Circuit
![Mystery Filter Circut](./imgs/mystery_circuit.png)
#### Bode Plot (linear)
![Mystery Bode Plot (linear)](./imgs/mystery_bode_linear.png)
#### Bode Plot (Logarithmic)
![Mystery Bode Plot (Logarithmic)](./imgs/mystery_bode_log.png)
#### Phase Plot
![Mystery Phase Plot](./imgs/mystery_phase.png)

### Influence of Zeta on Overshoot
Zeta values = [0.1, 0.3, 0.707, 1.0, 3.0, 10.0]

![Influence of Zeta on Overshoot Graph](./imgs/overshoot.png)
### Influence of Zeta on Step Response
![Influence of Zeta on Step Response Graph](./imgs/stepresponse.png)

## Conclusion
As displayed in the simulations, the mystery filter is the bandstop filter. This can be seen from the plots where only certain frequencies are attenuated and all other frequencies are not. All second-order RLC transfer functions shared the same denominator and the numerator changed depending on which element we were voltage dividing against. Depending on which element was on the numerator determined if it was a lowpass, highpass, bandpass, or a bandstop. The bandstop was done by having both the capacitor and inductor on the numerator. 

In terms of the zeta, it can be seen that the lower our zeta, the higher our overshoot, and the more oscillations we have. The higher the zeta, the more damping there will be and less oscillation. The critical value for the damping factor is 0.707 where the frequency response will cause a maximally flat transition. 