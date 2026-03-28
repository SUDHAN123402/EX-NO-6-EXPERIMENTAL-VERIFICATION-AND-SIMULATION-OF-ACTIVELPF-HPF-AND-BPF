# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF

         
---         


## AIM 
Obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

## 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
<img width="836" height="455" alt="image" src="https://github.com/user-attachments/assets/e5181151-836f-4f80-8f56-53b23ff05c74" />


## MODEL GRAPH
<img width="913" height="559" alt="image" src="https://github.com/user-attachments/assets/c8d28c41-6f3e-44a6-a9da-2b798cf07346" />

---

## DESIGN

<img width="1080" height="1433" alt="image" src="https://github.com/user-attachments/assets/a7efda9b-7175-4a1c-bbd8-398557d194ff" />



## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

<img width="1446" height="1600" alt="image" src="https://github.com/user-attachments/assets/e142fe7c-5955-4be1-831c-7442bc20a2b5" />

## GRAPH
<img width="1080" height="1350" alt="image" src="https://github.com/user-attachments/assets/ea68c80d-7d0e-4a5d-a49c-a3335079aa4e" />


## OUT PUT WAVEFORM 
<img width="1917" height="884" alt="image" src="https://github.com/user-attachments/assets/5a9f2964-b6d2-4e70-9e4e-4698b8af878e" />

---

 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="887" height="486" alt="image" src="https://github.com/user-attachments/assets/907a1395-28d4-406f-ac09-96c4e060587e" />


## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN
<img width="1600" height="1499" alt="image" src="https://github.com/user-attachments/assets/7346c49d-9bc4-4817-a8a8-def71718b0c1" />



## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
<img width="1095" height="1600" alt="image" src="https://github.com/user-attachments/assets/5ed9c6a5-0581-433a-9452-b7d263bc4041" />


---
## GRAPH
<img width="1080" height="1489" alt="image" src="https://github.com/user-attachments/assets/770eb58c-0900-4c75-80e0-26b6ffad9a57" />


## OUT PUT WAVEFORM 
<img width="1919" height="870" alt="image" src="https://github.com/user-attachments/assets/fe71097a-a331-4c75-bc25-c6d00f4388ed" />

---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="1068" height="446" alt="image" src="https://github.com/user-attachments/assets/ee37b95a-05ea-448c-9102-111e071e41e8" />

## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

DESIGN: BAND PASS FILTER

<img width="979" height="1600" alt="image" src="https://github.com/user-attachments/assets/582cdeab-d948-42c8-b68f-32cd4e007b9d" />
<img width="1080" height="1398" alt="image" src="https://github.com/user-attachments/assets/78af8f39-fdc7-4367-a1db-9e799dd4ad68" />



## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
<img width="1536" height="1600" alt="image" src="https://github.com/user-attachments/assets/4c4981f3-e11a-47ab-bc95-e45c86fe2f64" />


---
## GRAPH
<img width="1021" height="1600" alt="image" src="https://github.com/user-attachments/assets/99996e44-c2f6-4810-8951-58c680db8e02" />


## OUT PUT WAVEFORM 
<img width="1919" height="884" alt="image" src="https://github.com/user-attachments/assets/22329b32-5fcb-4512-9571-5daf866c3d4a" />


---
## RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
