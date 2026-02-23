## Experiment No: 3
DIFFERENTIATOR USING OP-AMP (μA741)
## Aim
To design and simulate a Differentiator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the rate of change of input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Capacitor C = 0.01 µF
•	Resistor Rf = 10 kΩ
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1043" height="784" alt="image" src="https://github.com/user-attachments/assets/593b45af-3c3f-4a30-8242-610af7c91b20" />

## Connection Details:
•	Input signal → Capacitor (C) → Inverting terminal (Pin 2)
•	Feedback resistor (Rf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Differentiator circuit produces an output voltage proportional to the rate of change of input voltage.
## Working Principle:
•	When input changes rapidly → output amplitude increases
•	When input is constant → output is zero
•	Output is inverted
## Procedure
1.	Open Proteus software.
2.	Select μA741, capacitor, resistor, signal generator, and CRO.
3.	Connect circuit in differentiator configuration.
4.	Apply ±15V power supply.
5.	Set input sine wave (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No 	         Input Signal	              Frequency	            Expected  Output	            Practical Observation
<img width="727" height="421" alt="image" src="https://github.com/user-attachments/assets/0d09f6d2-f41a-440d-8038-8185b0b00225" />

## Waveforms
•	Sine input → Cosine output (90° phase shift)
•	Square input → Positive & negative spikes
•	Triangular input → Square wave
<img width="1368" height="884" alt="image" src="https://github.com/user-attachments/assets/0d7d36f9-d577-46ca-9d43-fab3ef4adcca" />

## Result
The Differentiator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the rate of change of input voltage.
The circuit behaves as a differentiator.
## Conclusion
•	Output depends on frequency.
•	Output leads input by 90° (for sine input).
•	Higher frequency → Higher output amplitude.
•	Used in wave shaping and signal processing applications.
## Viva Questions
1.	What is a differentiator?
  
	A differentiator is an op-amp circuit that produces output proportional to the rate of change of input voltage.


2.	Write the output equation of differentiator.

	Vout = -Rf × C × (dVin/dt)
Where:  
Rf = Feedback resistor  
C = Capacitor  
dVin/dt = Rate of change of input voltage  

3.	Why is output leading input?

The output leads the input by 90° because differentiation of a sine wave produces a cosine wave.

4.	What happens at very high frequency?

At very high frequency, the output voltage increases and the circuit may become unstable and produce noise.

5.	What is practical differentiator?

A practical differentiator is a modified circuit that includes additional components to improve stability and reduce noise.

