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
   

   DC ANALYSIS :
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

  Let RD = 100 kohms 

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




 TRANSIENT ANALYSIS :

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
 vout = 1.745 V ; vin = 900 mV
 
 Gain = 1.745/900m

  gain = 1.938

AC ANALYSIS :
this analysis is done to get the output at different frequencies
INPUT :
 DC offset : 0.9V
 ampltitude = 50mV
 frequency = 1 k Hz
 AC amplitude = 1

  CIRCUIT :
  ![Screenshot (407)](https://github.com/user-attachments/assets/32d81c44-c647-4a11-ba2b-c5294f1a9ffc)

  OUTPUT WAVEFORM :
  ![Screenshot (408)](https://github.com/user-attachments/assets/773b9e0a-58f5-44ab-a19f-2369b1693ee6)

## Result :

DC operating point ,for 1 k ohm >> 
  


  


  


    

   
   
