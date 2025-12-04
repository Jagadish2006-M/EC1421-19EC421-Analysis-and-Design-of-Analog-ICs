# EC1421 - 19EC421 - Analysis-and-Design-of-Analog-ICs
# Design of Integrator using Op-amp.

## AIM:
To design and test the performance of integrator circuits using  Op-amp.

## APPARATUS REQUIRED:

<img width="811" height="206" alt="image" src="https://github.com/user-attachments/assets/fd527bf4-b7bf-4330-9b09-ce7ad607bdeb" />


## THEORY:

INTEGRATOR 
 
A circuit in which the output voltage waveform is the integral of the input voltage 
waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier 
configuration if the feedback resistor Rf is  replaced by a capacitor Cf .  The expression for the 
output voltage is given as, 

Vo = - (1/Rf C1 ) ∫ Vi dt 
 
Here the negative sign indicates that the output voltage is 180 0 out of phase with the 
input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of 
fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger 
than or equal to Rf Cf .

That is, T ≥ Rf Cf 
 
The integrator is most commonly used in analog computers and ADC and signal-wave 
shaping circuits.


## DESIGN
~~~
To obtain the output of an Integrator circuit with component values R1Cf = 0.1ms , Rf = 10 
R1 and Cf = 0.01 µF and also if 1 V peak square wave at 1000Hz is applied as input. 
We know the frequency at which the gain is 0 dB, fb = 1 / (2π R1 Cf) Therefore fb =    
Since fb = 10 fa , and also the gain limiting frequency fa = 1 / (2π Rf Cf) 
We get , R1 =  and hence Rf =

~~~
## CIRCUIT DIAGRAM:

<img width="449" height="332" alt="Screenshot 2025-12-04 213124" src="https://github.com/user-attachments/assets/4939d67e-1f31-4a53-86e8-2b4a46cc1110" />


## MODEL GRAPH
<img width="341" height="285" alt="Screenshot 2025-12-04 213242" src="https://github.com/user-attachments/assets/de7207ec-f2aa-4bd5-93a3-dd64bb5e04c6" />

<img width="443" height="336" alt="Screenshot 2025-12-04 213253" src="https://github.com/user-attachments/assets/39171509-8a7b-43ea-ad0a-3f5d5b213a14" />

## PROCEDURE:

1. Connections are given as per the circuit diagram 
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC. 
3. By adjusting the amplitude and frequency knobs of the function generator, appropriate 
input voltage is applied to the inverting input terminal of the Op- Amp. 
4. The output voltage is obtained in the CRO and the input and output voltage waveforms 
are plotted in a graph sheet.

## TABULATION:

<img width="448" height="233" alt="Screenshot 2025-12-04 213339" src="https://github.com/user-attachments/assets/d7d4c35e-e085-436d-ab81-d5f21b03ef70" />


## GRAPH:
<img width="574" height="847" alt="Screenshot 2025-12-04 213410" src="https://github.com/user-attachments/assets/01e57db6-ac47-4544-94df-a1f3363d8dfd" />

<img width="604" height="434" alt="Screenshot 2025-12-04 213422" src="https://github.com/user-attachments/assets/e45bd30f-d5fd-463f-85ae-376437284ff5" />




## RESULT:

Thus an Integrator using op-amp are designed and their performance was successfully tested using op-amp IC 741. 
