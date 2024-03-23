# Linear Electronic Systems
These were the labs part of the ECE 100 course at UCSD taught by Professor Drew Hall for Spring 2023.

Due to academic integrity, I can not post my full lab report on here. All analytical work can not be shown as well as it includes derivations. As such, only simulations and results will be shown. For the full lab report, please inquire at kevshin2002@gmail.com

## Breakdown
- RLC Circuit
- Sallen Key Filter 
- Voltage Follower Circuit
- Design of a Differentiator
- Op Amps and Wien-Bridge Oscillator

## RLC Circuit
This lab aimed to analyze and understand 2nd order RLC systems and the effects of different zeta values which represent damping ratio. By using MATLAB and plotting 2nd order highpass, lowpass, bandpass, and bandstop filters, a higher zeta meant a longer rise time in exchange for a lower overshoot percentage. A lower zeta characterized more oscillations as a result of less damping.


## Sallen Key Filter
This lab aimed to analyze a low pass Sallen Key Filter and its design aspect of it. In this lab, we constructed and simulated the filter to explore the discrepancies between ideal and real-world performance. In addition, we evaluated the economic considerations that can be made when implementing the filter, as well as analyzing the impact of modifying the circuit's zeta values.

## Op-Amp Voltage Follower Circuit
This lab aimed to analyze the behavior of an op-amp as a voltage follower circuit. We saw how the impedances of the input and output can be modeled as a capacitor and an inductor. More specifically though, we looked at how tradeoffs can occur using the bandwidth and DC gain and the effect of a capacitive load on the overall closed-loop transfer function. We sought to reduce the effects caused by the capacitive load using a compensation resistor. Using these two elements, we then saw how we can implement certain design specifications using overshoot and rise time.

## Design of a Differentiator
This lab aimed to analyze the behavior of an op amp as a differentiator. We see the non-ideal behavior of an op amp influence the differentiator to cause ringing in the output and how adding a compensation resistor allows us to trade off overshoot for rise time to meet our design specification. The lab also demonstrates how we can use gain and phase margin to stabilize our circuits.

## Op Amps and Wien-Bridge Oscillator
This lab aimed to analyze how we can use the Nyquist plots of loop gains in order to determine the stability of the circuit as encirclements represent zeros which then turns the denominator into a zero and causes the transfer function to become infinity. Furthermore, we explored positive feedback using the Wien-Bridge Oscillator and how we can utilize positive feedback with noise to create an oscillator. In addition to that, we learned that op amps have practical limitations. By adding diodes, we learned one method to soft clip the sine wave. In terms of op amps non-ideality, we saw that op-amps are powered by current sources which means that the slew rate is capped and causes a bandwidth limit of frequency.