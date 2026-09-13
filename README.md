# 7.-Design-and-Implement-Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillator-using-Op-amp
**Aim:**
To design and implement Sine-wave-Generator-RC-Phase-shift-Wein-bridge-Oscillato-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,3.3K,1.5K,33K,15K,1MΩ	2
7.	Capacitor	0.1 µF	3
8.	Connecting wires and probes	As required	


**THEORY:**

**RC PHASE SHIFT OSCILLATOR**

RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .

**WIEN BRIDGE**

A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
 

**DESIGN:**

**RC PHASE SHIFT OSCILLATOR**

fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1  > 10 R
R1 =10 R = 33 k.
Rf = 29R1=1MΩ


**WIEN BRIDGE OSCILLATOR**

Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ


**PROCEDURE:**

1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.


  **CIRCUIT DIAGRAM**
<img width="1600" height="1425" alt="image" src="https://github.com/user-attachments/assets/0ef34c84-820c-4b11-a669-b8d0b61f9720" />


  **MODEL GRAPH:**
<img width="1600" height="804" alt="image" src="https://github.com/user-attachments/assets/b91014bc-0d15-45a0-b1aa-8bd178aef030" />


  **TABULATION:**
 
<img width="1600" height="687" alt="image" src="https://github.com/user-attachments/assets/5cfb462d-c51f-4c4f-b65c-0a303a4c9981" />

<img width="1600" height="807" alt="image" src="https://github.com/user-attachments/assets/16cca1c4-1bcb-427d-b89d-2c172353c634" />

WIEN BRIDGE OSCILLATOR

CIRCUIT DIAGRAM
<img width="1600" height="1241" alt="image" src="https://github.com/user-attachments/assets/28779c1f-40e0-43ba-b221-f8ce43b2f273" />

MODEL GRAPH:
<img width="1600" height="1046" alt="image" src="https://github.com/user-attachments/assets/614b3978-6188-496f-977c-01c5baf16bf8" />
TABULATION:
<img width="1600" height="720" alt="image" src="https://github.com/user-attachments/assets/e2e9de72-3e69-464c-9b8a-3975b59c4df1" />
<img width="1600" height="778" alt="image" src="https://github.com/user-attachments/assets/6a5b1199-625a-4981-b3a0-4e61905f91c7" />

**RESULT:**
Thus a RC Phase Shift and Wien Bridge oscillators designed and tested using op-amp IC 741.
 

