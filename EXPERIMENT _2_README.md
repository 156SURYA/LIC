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

![Screenshot (474)](https://github.com/user-attachments/assets/88eb075c-fca9-41e4-b654-d7e184085a46)


### DC analysis : -

1) To get the exact value of the drain current we are supposed to vary the length and width of the mosfet
2) practically to get the exact output voltage we can also change the value of the Rd value
3) with the calculated values this is the DC output which we get with Rd = 1.9 k ohm ; and Rss = 400 ohms  

![Screenshot (444)](https://github.com/user-attachments/assets/773bbb98-3bdb-4c19-8fb5-ade8f1b8a135)

Mosfet to work as an Amplifier it should we working in the saturation region 
from the obtained output => 
![Screenshot (471)](https://github.com/user-attachments/assets/51d5bf17-2efd-4213-876d-28710bb25e56)

Vgs = 0.8 V
Vds = 0.85 V
Vth = 0.366 V
 As Vgs >Vth and Vds > Vov we can conclude that the mosfet is operating in the saturation region

 therefore the Qpoint is ( 0.85V,0.5mA) .

 ### Calculating the minmum and the maximum values :
  Vincm (min) = Vth + vp => 0.366 + 0.399 = 0.765 V
  Vincm(max) = Vdd - (Id*Rd) +Vth => 1.616 V
  Vout (min) = Vov1 + Vp => 0.824 V
  Vout(max) = Vdd - (Id*Rd) => 1.25 V

### Transient analysis :-
From this simulation we can calculate the gain

Valculated Value :
Gain = Av = - Gm*Rd 
Gm = 2Id/Vov = 2 ( 0.5 *10^-3 ) / 0.434 * 10 ^3 = 2.30 v/v

steps :
1) to change the input  DC voltage to AC singnal with the DC offset voltage
2) with 100 mV as peak to peak voltage and DC offset voltage as 1.2 Volts
3) from the output we can observe a phase shift of 180 degrees

### output :

![Screenshot (437)](https://github.com/user-attachments/assets/9f43e477-2011-443e-b455-6180471c59f6)



###  AC analysis :-

![image](https://github.com/user-attachments/assets/75cd60dc-b60f-4d8c-829e-77d3b743faaa)



## Replacing the resistor With current source 

### Circuit Diagram :-

![Screenshot (473)](https://github.com/user-attachments/assets/6c6156b9-1c5d-4051-9f61-825235e60fe2)


### DC analysis : -

![Screenshot (460)](https://github.com/user-attachments/assets/ad475f1f-cdca-487c-83ab-f77ba6c48299)

### TRansient Analysis :-

![Screenshot (464)](https://github.com/user-attachments/assets/0ed2b0ab-57b3-4d36-9d5e-1a89684348eb)



### AC Analysis :-
![image](https://github.com/user-attachments/assets/5ae1824c-f774-4377-9bdd-754c1bf9fd04)




## replacing the resisitor with mosfet 

### circuit Diagram :-

![image](https://github.com/user-attachments/assets/5258e817-82dd-4dc1-a65d-a5abb93101f7)



###  DC Analysis :-


![image](https://github.com/user-attachments/assets/57fc3195-8968-482b-b1e3-b38c94dadeea)

Now , Vds = Vgs -Vt
    0.85 + 0.366 = 1.216 volts
     therefore Vg = 1.216 V ; souurce is grounded 

### Transient Analysis :-

![image](https://github.com/user-attachments/assets/34d4d457-d8d4-484e-857a-b0d858ee6546)


### AC Analysis :-

![image](https://github.com/user-attachments/assets/a83905cc-0e50-4799-85b2-42cffdb10f29)




##Result :-
1) From the DC analysis of the 1st circuit where the differential amplifier is connected with the resistor Rss we can get to know the  mosfet is working in saturation region or not

![image](https://github.com/user-attachments/assets/f18e2b71-7409-4d03-a787-a058d02a26ad)

also we can get the exact values of all paramters

2) also we can see that by replacing the Rss in the circuit there is a stable output current





## Inference :-

### Circuit Comparision :

![image](https://github.com/user-attachments/assets/0cd53549-b280-4a63-9d01-0a84b36f282a)























