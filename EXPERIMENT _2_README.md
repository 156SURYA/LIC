# DIFFERENTIAL AMPLIFIER 

### ABOUT DIFFERENTIAL AMPLIFIERS :-

A differential amplifer amplifies the difference between two input voltage also by rejecting thr common voltage shared by the input

### WORKNG :
Basically it has 2 input terminals v1 and v2
from the output terminal we can get  Vout = gain(v1-v2)
                                      Vout = gain (vd)
                     where , vd= v1-v2

Question : Design and analyse the different amplifier forthe given  specification

Vpp= 2.2V ; P <= 2.2mw ; Vincm =1.2V ; Vocm = 1.25V Vp = 0.4V simulate the following also extract DC , transient , frequency respinse parameter

### calculation and circuit diagram  :

![WhatsApp Image 2025-03-06 at 21 16 43_98d5892c](https://github.com/user-attachments/assets/2774419c-a383-47bb-8b7a-99dd61b316f2)


### circuit diagram : -

Now , from the calculated value design the circuit

![Screenshot (443)](https://github.com/user-attachments/assets/6f286604-06c1-4360-8e09-cdc494a0561b)


### DC analysis : -

1) To get the exact value of the drain current we are supposed to vary the length and width of the mosfet
2) practically to get the exact output voltage we can also change the value of the Rd value
3) with the calculated values this is the DC output which we get with Rd = 1.9 k ohm ; and Rss = 400 ohms  

![Screenshot (444)](https://github.com/user-attachments/assets/773bbb98-3bdb-4c19-8fb5-ade8f1b8a135)

Mosfet to work as an Amplifier it should we working in the saturation region 
from the obtained output => 

Vgs = 0.8 V
Vds = 0.85 V
Vth = 0.366 V


### Transient analysis :-

steps :
1) to change the input  DC voltage to AC singnal with the DC offset voltage
2) with 100 mV as peak to peak voltage and DC offset voltage as 1.2 Volts
3) from the output we can observe a phase shift of 180 degrees

![Screenshot (437)](https://github.com/user-attachments/assets/9f43e477-2011-443e-b455-6180471c59f6)



###  AC analysis :-
![Screenshot (458)](https://github.com/user-attachments/assets/672ee74c-b659-4c91-94e3-86aa9a15285a)


## Replacing the resistor With current source 

### Circuit Diagram :-

### DC analysis : -

![Screenshot (460)](https://github.com/user-attachments/assets/ad475f1f-cdca-487c-83ab-f77ba6c48299)

### TRansient Analysis :-

![Screenshot (464)](https://github.com/user-attachments/assets/0ed2b0ab-57b3-4d36-9d5e-1a89684348eb)



### AC Analysis :-

## replacing the resisitor with mosfet 

### circuit Diagram :-


###  DC Analysis :-

### Transient Analysis :-

### AC Analysis :-

###



















