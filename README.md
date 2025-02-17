#  EXPERIMENT -01



# Aim :
   a) to simulate the circuit to get DC operating point also by varying it's RD value
   
   b) to the the transient and AC analysis of the same circuit 



  ## components used :-
   DC power supply of 1.8v and 0.9 volt
   resistor of 1k ohms
   NMOS4
   Gate voltage :0.9 V
   
   also for this eperiment we have used netlist called 'spice netlist ' and the library file which 
   we have used is 'tsmc018.lib'
   

  ## DC ANALYSIS :
   
   the DC operating point of the mosfet can be obtained int the following way the power rating is given as 100 micro watt

   RD = 1k ohm
   VDD = 1.8v
   
   to calculate ID :

  P=V*I
    by substituting the given values of power and voltage ID = P/V
    100 µ /1.8
    ID = 55.55 µA

  So,we can get this drain current by varying either length or width of the mosfet,
  first we supposed to connect the mosfet as per the circuit with the DC supply as 1.8V and 0.9V for the gate terminal

  ![image](https://github.com/user-attachments/assets/d7b66808-1316-45f9-a10f-f14fc84986ba)


  with W = 1.981um and L = 1um
  we can get the output  ID = as 55.5 µA and voltage of 1.74 V
  therfore the Q point will be ( 1.74 V, 55.5µA)

  ![image](https://github.com/user-attachments/assets/a4f2f196-baea-4a9d-aede-0e876b9e905e)

  OUTPUT Will be :
  ![image](https://github.com/user-attachments/assets/83d4ea3d-6e34-46b0-89ab-c5ad17e2d3bd)

  for the same circuit by variying the value of the drain resistance 

  Let RD = 100k ohms 

circuit diagram

  ![Screenshot (395)](https://github.com/user-attachments/assets/7794c20c-02ee-41ca-b716-38e52cde9a27)

  the output will be 
  
  ![Screenshot (396)](https://github.com/user-attachments/assets/288d5fb7-dd85-41b3-b882-f57934094c28)

by changing the length and the width of the mosfet the output drain current and volatge will be varied 

let W = 2 µm
    L = 1.5 µm

  CIRCUIT :

 ![Screenshot (402)](https://github.com/user-attachments/assets/171046c7-ac62-4464-a024-77a6de6e1f3d)


 the output will be :

 ![Screenshot (403)](https://github.com/user-attachments/assets/6c1a31de-ac1f-4d34-b49c-64eb027d8684)




 ## TRANSIENT ANALYSIS :

 this analysis is done to know the output both voltage and the current with respect to time 

 for the same circuit transient analysis can be done by changing the input voltage to time dependent sine wave with the offset value = 0.9v ;amplitude = 50 mV ; frequency = 1k Hz ;

 circuit :
 
 ![Screenshot (404)](https://github.com/user-attachments/assets/26f8df12-5773-429a-99c0-2dfd67f0743d)

 input wave :
 
 ![Screenshot (405)](https://github.com/user-attachments/assets/4f32055f-d7b7-41d8-9ddb-38191a9e9b72)

 output wave :
 
 ![Screenshot (406)](https://github.com/user-attachments/assets/c5d072fe-08b9-4c3d-8a64-267fea13a82d)

 from the above input and the output waves we can calculate the gain 

 Av = Vout/Vin
 vout = 1.755 V ; vin = 950 mV
 
 Gain = 1.755/950m

  gain = 1.84

## AC ANALYSIS :

this analysis is done to get the output at different frequencies

INPUT :
 DC offset : 0.9V
 
 ampltitude = 50mV
 
 frequency = 1 k Hz
 
 AC amplitude = 1
 for simulation of AC analysis select sweep to decade ;number of points to 20 and operating frequency range from 0.1 to 1T Hz.

  CIRCUIT :
  
  ![Screenshot (407)](https://github.com/user-attachments/assets/32d81c44-c647-4a11-ba2b-c5294f1a9ffc)

  ![Screenshot (412)](https://github.com/user-attachments/assets/eebd6183-2bc1-4fe0-acc4-40f4d8ab7005)


  OUTPUT WAVEFORM :
  ![Screenshot (408)](https://github.com/user-attachments/assets/773b9e0a-58f5-44ab-a19f-2369b1693ee6)

## Result :

DC operating point 
1) for 1 k ohm >> (1.7444 V,55.5µA) with W = 1.981µm and L = 1µm
2) for 100 k ohm >> (0.068 V,17.31 5µA) with W = 1.981 µm and L =1µm
3) the gain of the circuit is 1.84

## Inference :
 1) from the above  analysis we can conclude that ID depends on both the length and width of the mosfet , where width is directly propotional and length is inversely propotional to the drain current
 2)  


 # Simulation of CMOS Amplifier

 ## Aim
 To simulate DC Analysis ; transient Analysis and AC Analysis of a CMOS amplifier

 ## DC ANALYSIS :

 for this DC Analysis we have to replace the resistor with a mosfet with the same supply and the gate voltage
 let ID value be same = 55 µA

 ## Circuit 
 ![Screenshot (421)](https://github.com/user-attachments/assets/fb44f6f9-1976-48ae-99e8-df90c125fc54)
 
 ## DC OPERATING POINT :

 
the Qpoint is (1.55V,55 µA)
 ![Screenshot (422)](https://github.com/user-attachments/assets/7de8a3e8-37f1-4761-914e-379e94570a05)


 ## TRANSIENT ALAYSIS :

to get the transient output we have replace the DC gate voltage with a sine wave 

 DC offset = 0.9v
 Amplitude = 50 mV
 Frequency = 1 k Hz
 CIRCUIT DIAGRAM :
 
![Screenshot (426)](https://github.com/user-attachments/assets/fde08bfd-5902-49bf-95cc-92c622b6c8f7)



 OUTPUT WAVEFORM :
 
 ![Screenshot (425)](https://github.com/user-attachments/assets/f0216bac-531d-4a43-9bb4-920b1d1588a6)

 from the above waveform we can conclude that there is 180 degree phase shift between input and output wave

 ## AC ANALYSIS :

 OUTPUT WAVEFORM:

 ![image](https://github.com/user-attachments/assets/f211b851-7281-4292-b91d-a722fe27aed3)

 Gain =5.5 dB

 ## Inference 
 1)therefore from the above analysis we can conclude that the output wave is about 5.5 times grater than the input wave
 2) the transient analysis output shows how the amplifier responds to a time varying gignal
 

 
 



 
  


  


  


    

   
   
