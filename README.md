# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



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
![20251203_215924](https://github.com/user-attachments/assets/3f037fb3-6cbd-41bf-ba89-b0497d4bf9a4)

## SIMULATION CIRCUIT DIAGRAM
![20251203_215950](https://github.com/user-attachments/assets/bf1f0b45-c288-4025-9997-4e4bbaedb648)

## MODEL GRAPH
![20251203_220051](https://github.com/user-attachments/assets/13ec216b-63ce-4d18-ae47-94605769dc4f)

---

## DESIGN
![20251203_220106](https://github.com/user-attachments/assets/54416e36-29e1-4cda-b14a-0e2e5191c15d)

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![20251203_220202](https://github.com/user-attachments/assets/3e6e6553-a12e-4422-b613-13fa9056f3cb)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_221346](https://github.com/user-attachments/assets/b5950d47-a0f9-4507-bc84-00e2807c7ce9)
![20251203_220027](https://github.com/user-attachments/assets/1da8deea-e23a-46ce-9717-002c908c164f)
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/a81e3638-f04d-4d58-b334-ffb7764fc4fd" />

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
![20251203_220252](https://github.com/user-attachments/assets/8eb5148f-bf9c-4e2b-b625-6a2094f4bd43)

## SIMULATION CIRCUIT DIAGRAM
![20251203_220401](https://github.com/user-attachments/assets/3164f398-22be-45ab-9f4e-a9b2367745f1)

## MODEL GRAPH
![20251203_220433](https://github.com/user-attachments/assets/3de01663-7bcf-4846-80e9-a591dc991290)

---

## DESIGN
![20251203_221607](https://github.com/user-attachments/assets/a35a784d-81f3-4461-a564-9c676650628c)

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![20251203_221753](https://github.com/user-attachments/assets/e723989c-39c6-4949-9991-da9198364516)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_221726](https://github.com/user-attachments/assets/7b0ef294-7b67-45ed-abef-9461317cc528)
![20251203_220418](https://github.com/user-attachments/assets/941ced96-f12f-4488-b409-dfa86b5d07bc)
<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/44786273-4e9f-4d1f-9ba6-5be8faf0283a" />

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
![20251203_221922](https://github.com/user-attachments/assets/a0551f25-9d26-429b-986e-1cb0c644e005)

## MODEL GRAPH
![20251203_221931](https://github.com/user-attachments/assets/c53d47be-5ec2-4a93-a4f6-f1dec4b949d9)

---

## DESIGN
![20251203_222051](https://github.com/user-attachments/assets/89c66e08-5aa9-42ed-b7e9-9a65895eab31)

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![20251203_222114](https://github.com/user-attachments/assets/efc4f6ee-7c1c-4c8e-bd03-0d2f5b9147f7)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![BPF](https://github.com/user-attachments/assets/432467e9-9f4c-49bb-bc2e-9f792a324d00)
![20251203_221854](https://github.com/user-attachments/assets/b3ba1e59-c9ed-4371-bab4-1a776d61df6b)
<img width="784" height="339" alt="image" src="https://github.com/user-attachments/assets/8725f923-55a9-4d38-b8e5-003eade23ff9" />

---
##RESULT:
![20251203_222135](https://github.com/user-attachments/assets/1e479007-5d5f-4ab8-ba2a-5f7451983446)
![20251203_222226](https://github.com/user-attachments/assets/b4451c15-1b04-46d2-9030-e018b78cdc3b)

	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
