# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
<img width="687" height="481" alt="Screenshot 2025-12-04 223919" src="https://github.com/user-attachments/assets/f2256caf-b7b7-4791-8208-cca9b6e01ec4" />

## HIGH-PASS
<img width="708" height="532" alt="Screenshot 2025-12-04 223946" src="https://github.com/user-attachments/assets/7aad646d-9cad-430b-afb0-e7a920491875" />

## BAND-PASS
<img width="690" height="578" alt="Screenshot 2025-12-04 224021" src="https://github.com/user-attachments/assets/302f14eb-81fd-4793-a9a8-4380157f4218" />


## MODEL GRAPH:
## LOW_PASS
<img width="690" height="565" alt="Screenshot 2025-12-04 224316" src="https://github.com/user-attachments/assets/9cf6ba49-6854-424f-88ef-206198547fc5" />

## HIGH-PASS
<img width="600" height="532" alt="Screenshot 2025-12-04 224348" src="https://github.com/user-attachments/assets/0ebddfad-a05c-406b-8b6c-5d3513a697a9" />

## BAND-PASS
<img width="706" height="636" alt="Screenshot 2025-12-04 224413" src="https://github.com/user-attachments/assets/ebe439ea-1865-46f5-83d9-822437c5bbc9" />


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
<img width="706" height="706" alt="Screenshot 2025-12-04 224648" src="https://github.com/user-attachments/assets/efc64dcc-8b79-4e67-8a2f-c8e713fd9175" />

## HIGH-PASS
<img width="584" height="649" alt="Screenshot 2025-12-04 224711" src="https://github.com/user-attachments/assets/76c0bc55-beb2-4d10-8eb7-01384d024175" />

## BAND-PASS
<img width="680" height="880" alt="Screenshot 2025-12-04 224744" src="https://github.com/user-attachments/assets/33db69de-36a5-4f10-b69c-4b2b1bea91de" />

## CALCULATIONS:
## LOW_PASS
<img width="705" height="347" alt="Screenshot 2025-12-04 224932" src="https://github.com/user-attachments/assets/47940b67-fe8a-4365-99b2-bacbf7d93cbb" />
<img width="724" height="306" alt="Screenshot 2025-12-04 224951" src="https://github.com/user-attachments/assets/ff38497a-3673-438e-85af-0dff93fecea7" />


## HIGH-PASS
<img width="705" height="347" alt="Screenshot 2025-12-04 224932" src="https://github.com/user-attachments/assets/21217de5-c808-4050-b357-955c563e5136" />
<img width="724" height="306" alt="Screenshot 2025-12-04 224951" src="https://github.com/user-attachments/assets/0c0ef76a-196c-4977-84c2-c53ca6245b18" />


## BAND-PASS

<img width="518" height="631" alt="Screenshot 2025-12-04 225014" src="https://github.com/user-attachments/assets/43266252-732e-4d62-ad48-e1235c73d2c6" />

## GRAPH:
## LOW_PASS

<img width="1025" height="785" alt="Screenshot 2025-12-04 225255" src="https://github.com/user-attachments/assets/390db646-e9f8-40ec-b0e3-26feeb77d350" />

## HIGH-PASS

<img width="989" height="795" alt="Screenshot 2025-12-04 225228" src="https://github.com/user-attachments/assets/b33b6bd9-85b8-414b-9124-73515247e0b2" />

## BAND-PASS

<img width="1020" height="789" alt="Screenshot 2025-12-04 225150" src="https://github.com/user-attachments/assets/d44425db-f02d-45eb-ad76-a33110ebc512" />

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

