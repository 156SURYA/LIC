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

           
    
    
