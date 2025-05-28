# INSTRUMENTATION AMPLIFIER

### AIM :
To design and analyze instrumentation amplifier using 741 IC op-amp in LT spice

### Design Question :
Design an instrumentation amplifier using 3 op-amp configuration with the following constraints,
a) R1 = R2 = R3 = R4 = R5 =R6 = 100k ohm.

  Vcc= 13.5 V
b) difference gain ADM = 20 v/v
find Acm (common mode gain) and calculate CMRR for ADM = 20 and 50 v/vuse LT spice simulator


### About Instrumentation Amplifiers :-

An instrumentation amplifier (IA) is a specialized type of differential amplifier designed for precise signal amplification, particularly where accuracy, noise immunity, and impedance matching are critical. These amplifiers are commonly used in applications requiring the reliable extraction of small signals in electrically noisy environments.

### Main Characteristics:

 • Three-Op-Amp Architecture: Typically composed of three operational amplifiers—two serve as input buffers 
    to provide high impedance, and the third performs the differential amplification.

•  High Input Impedance: Minimizes the loading effect on the source, allowing accurate signal acquisition.

•  Low Output Impedance: Facilitates easy interfacing with subsequent circuitry or loads.

•  Easily Configurable Gain: Gain can be precisely adjusted using a single external resistor, offering 
   flexibility and simplicity in circuit design.

• Superior Common-Mode Rejection Ratio (CMRR): Efficiently filters out common-mode noise and interference 
  present on both input lines, ensuring signal integrity in electrically noisy conditions.

### Common Use Cases:

• Monitoring biological signals such as electrocardiograms (ECG) and electroencephalograms (EEG)

• Amplifying signals from sensors like thermocouples and strain gauges

• Controlling processes in industrial environments

Instrumentation amplifiers are the go-to solution when it’s essential to amplify weak differential signals while minimizing the impact of ambient electrical noise.


### Circuit  :-
![image](https://github.com/user-attachments/assets/c9c70acb-480a-4f0c-bdf2-858912a7485d)

### CALCULATION :-


### CIRCUIT DIAGRAM :-
![image](https://github.com/user-attachments/assets/c344233d-c671-46a5-a885-f267162fa844)



