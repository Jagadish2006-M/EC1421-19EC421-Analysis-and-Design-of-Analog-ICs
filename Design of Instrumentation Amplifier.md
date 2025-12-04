# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
#  INSTRUMENTATION AMPLIFIER

## AIM: 

To construct and test the CMRR of an instrumentation amplifier using op-amp  
IC741.
 
## APPARATUS REQUIRED

<img width="634" height="166" alt="image" src="https://github.com/user-attachments/assets/e7f51b72-b143-4728-9c65-6b9d447201cf" />


## THEORY
## INSTRUMENTATION AMPLIFIER

An instrumentation amplifier is the intermediate stage of a instrumentation system. The 
signal source of the instrumentation amplifier is the output of the transducer. Many 
transducers output do not have the ability or sufficient strength to drive the next following 
stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of 
the transducer so that it can drive the following stages such as indicator or displays. 
 
The major requirements of a instrumentation amplifier are precise, low-level 
signal amplification where low-noise, low thermal and time drifts, high input resistance & 
accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior 
performance. 
 
 The output of Instumentation amplifier is given by 
                                                         
Vo = RF/R1[1+ 2R’/R][V2-V1] 
## CIRCUIT DIAGRAM: 
<img width="684" height="509" alt="Screenshot 2025-12-04 212808" src="https://github.com/user-attachments/assets/ecaddbca-dc41-4980-b4d4-e5a99228fb38" />

## MODEL GRAPH:
<img width="482" height="430" alt="Screenshot 2025-12-04 212848" src="https://github.com/user-attachments/assets/1fd9affd-0ad0-41c1-a02c-b06da308d7ca" />

## PROCEDURE:  
1. Select the entire resistor with the same value. Let R be the gain varying resistor with 
different values of resistance for simplicity let R be a constant value. 
2. Connect the circuit as shown in the circuit diagram.  
3. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC. 
4. Give the input V1 and V2 to the non-inverting terminals of first & second op-amp 
respectively.  
5. By varying the value of RG, measure the output voltage for common mode and 
differential mode operation. Since RG is selected as constant value, provide different 
input value of V1 and V2. 
6. Check the theoretical value with the experimental value. 
7. The output voltage is obtained in the Multimeter and the input and output voltage 
waveforms are plotted in a graph sheet.

## TABULATION:
<img width="691" height="341" alt="Screenshot 2025-12-04 212915" src="https://github.com/user-attachments/assets/2becda52-e51f-4dff-8f26-6ee62789d9f0" />

## CALCULATIONS:
 <img width="681" height="820" alt="Screenshot 2025-12-04 212948" src="https://github.com/user-attachments/assets/ec242b18-7e90-466c-9005-4344a229c034" />

## GRAPH:
<img width="303" height="430" alt="Screenshot 2025-12-04 213022" src="https://github.com/user-attachments/assets/8a8f03d2-2d21-4502-a64e-be1a22647f98" />

 ## RESULTS:
 Thus an instrumentation amplifier was constructed and  tested using op
amp IC 741. 
 
