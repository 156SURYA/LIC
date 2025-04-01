# CURRENT MIRROR EXPERIMENT 

### Introduction to Current Mirroring Circuits in Linear Integrated Circuits :-

A current mirror circuit is a crucial building block in linear integrated circuits (LICs) used to copy or replicate a reference current from one branch of a circuit to another. It ensures that the mirrored current remains stable and independent of variations in voltage or temperature, making it highly useful in analog circuit design.
Current mirrors are widely used in applications such as biasing, active loads, current amplification, voltage regulators, and analog signal processing. These circuits utilize transistors (BJTs or MOSFETs) to produce an output current that is either equal to or a scaled version of the reference current.

![image](https://github.com/user-attachments/assets/b8572d36-d26d-483f-b319-328aa84e06d5)

### AIM OF THE EXPERIMENT :
 to Design and anlyze current mirror circuit  as load in amplifier circuit 
 
 1) to design the circuit
 2) for the specification , Av >= -10 v/v ; Vdd = 1.8 v , P <=1 mW
 3) Analyze the DC analysis of current mirror curcuit
    
 4) differetn cases with the constant W/L ratio :
           a) Lmin = 180 nm
           b) L = 500 nm
           c) L = 1 um
           d) transient and AC analysis for the circuits


### Circuit design :-

GIVEN:
VDD = 1.8V
P <= 1mW
AV > -10v/v

ITotal = P/VDD
ITotal <= 1x10^-3 /1.8
ITotal <= 0.555mA

ITotal = IREF + IX
For 1:1 Current mirror ratio. IREF = 0.277mA & IX = 0.277mA
For 1:2 Current mirror ratio IREF is 0.185mA & IX = 0.365mA

the aspect ratio (w/l) of both mosfets is 16.66

the aspect ratios of mosfet for 1:1 current mirror should be identical,the width-to-length (w/l) ratio of both transistors must be the same to ensure accurate current replication.

M1 = 3um/180nm
M2 = 3um/180nm
M3 = 3um/180nm VGS = 0.838V
The aspect  ratio's of mosfet for 1:2 current mirror:

M1 = 3um/180nm
M2 = 6um/180nm
M3 = 6um/180nm VGS = 0.763V

## SIMULATION :

### 1.DC ANALYSIS :

 CIRCUIT :
![image](https://github.com/user-attachments/assets/adcb6ef1-9358-44f9-b3a2-aa0f2dbdea2b)


 Mosfet aspect Ratio :
![image](https://github.com/user-attachments/assets/d26910a0-ac31-45a0-be82-619a1f00a692)



 DC OUPUT :
 For length = 180 nm
 
![image](https://github.com/user-attachments/assets/a2f69d2d-25d5-4ba3-88ef-f71f9b7b81db)

For length = 500 nm 

![image](https://github.com/user-attachments/assets/02d2a362-4d28-4794-a061-20cfe9d7f2e9)

For length = 1 micrometer

![image](https://github.com/user-attachments/assets/6b4c211e-f8fe-44f1-8267-fc1f6ffa44c0)






 ### Transient Analysis :
 
For L = 180 nm
 ![image](https://github.com/user-attachments/assets/2a032825-1ca5-4ead-a54b-ea9023c7ad05)


 For L =500nm


 For length = 1 micrometer :

 ![image](https://github.com/user-attachments/assets/d3e6be63-173d-4281-9a15-b6f736d68ac2)



 

 ### AC Analysis :
 
 ![image](https://github.com/user-attachments/assets/786f5669-5235-41e0-bf18-cca80d00d707)


 





           
    
    
