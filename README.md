# Differential Amplifier

### This Repositery shows the design of a basic Differential Amplifier
1. [Abstract](#Abstract)

2. [Circuit Details](#Circuit-Details)

3. [Circuit Design](#Cicuit-Design)

4. [Waveforms](#Waveforms)

5. [References](#References)

### Abstract
This paper proposes the implementation of a differential amplifier using CMOS Technology. The reference CMOS differential amplifier has been implemented using 180nm technology, with a supply voltage of 1.8v.  A differential amplifier is a circuit that can accept two input signals and amplify the difference between the two input signals by removing the common noise . This reference circuit will be implemented in the eSim EDA tool.



### Circuit Details

  A Differential Amplifier is a device that is used to amplify the difference in voltage of the two input signals. A differential amplifier is an important building block in integrated circuits of analog systems.The important advantage of differential operation over single ended operation is higher immunity to noise, the other advantage in differential amplifiers is the voltage swing.<br>
  
  Differential amplifiers can operate in two modes which are differential mode and common mode. Common mode type gives the result of zero output while differential mode gives a result of high output, hence this amplifier has high common mode rejection ratio. If two input voltages are equal, then the differential amplifier gives an output voltage of almost zero volt and if the two input voltages are not equal the differential amplifier gives high output voltage.
  
  Used the below design equations from reference paper[1]:<br>
   ![des](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/design_eq.png)
   
   ![des2](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/image.png)
 

### Circuit Design


![design](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/Circuit.png)

### Waveforms


1. magnitude plot as per the design with sky130 technology file.
![waveform1](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/magnitude.png)

2. phase plot as per the design with sky130 technology file.
![wavefprm2](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/phase.png)

### References
[1] Bangadkar, M.B., Scholar, P.G., Lamba, M.A. and Bhure, M.V., 2015. Study of Differential Amplifiers using CMOS..

[2] [CMOS differential amplifier design and types of amplifiers](https://silo.tips/download/chapter-3-cmos-differential-amplifiers)

[3] [Differential amplifier - types and design equations](https://www.electronics-tutorial.net/Analog-CMOS-Design/CMOS-Differential-Amplifier/Differential-Amplifier)
