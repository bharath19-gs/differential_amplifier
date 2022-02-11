# Differential Amplifier

### This Repositery shows the design of a basic Differential Amplifier
1. [Abstract](#Abstract)

2. [eSim Tool Details](#eSim-Tool-Details)

3. [Circuit Details](#Circuit-Details)

4. [Google SkyWater PDK](#Google-SkyWater-PDK) 

4. [Circuit Design](#Circuit-Design)

5. [Waveforms](#Waveforms)

6. [References](#References)

### Abstract
This paper proposes the implementation of a differential amplifier using CMOS Technology. The reference CMOS differential amplifier has been implemented using 180nm technology, with a supply voltage of 1.8v.  A differential amplifier is a circuit that can accept two input signals and amplify the difference between the two input signals by removing the common noise . This reference circuit will be implemented in the eSim EDA tool.


### eSim Tool Details
eSim is an open source EDA tool for circuit design, simulation, analysis and PCB design, developed by FOSSEE Team at IIT Bombay. It is an integrated tool build using open source softwares such as KiCad, Ngspice and GHDL.
![tool_image](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/eSim_tool.png)

#### Features of the [eSim](https://github.com/FOSSEE/eSim) EDA tool 
- An open-source EDA tool.
- Perform Circuit Design.
- Perform Simulation.
- Perform Layout Design.
- Model builder and Subcircuit builder.
- Support for Mixed-Signal Simulations including Microcontrollers.
- eSim has been successfully ported to low cost FOSSEE laptop.

### Google Skywater PDK 
The [SkyWater Open Source PDK](https://github.com/google/skywater-pdk) is a collaboration between Google and SkyWater Technology Foundry to provide a fully open source Process Design Kit and related resources, which can be used to create manufacturable designs at SkyWater’s facility.



### Circuit Details

  A **Differential Amplifier** is a device that is used to amplify the difference in voltage of the two input signals. A differential amplifier is an important building block in integrated circuits of analog systems.The important advantage of differential operation over single ended operation is higher immunity to noise, the other advantage in differential amplifiers is the voltage swing.<br>
  
  Differential amplifiers can operate in two modes which are differential mode and common mode. Common mode type gives the result of zero output while differential mode gives a result of high output, hence this amplifier has high common mode rejection ratio. If two input voltages are equal, then the differential amplifier gives an output voltage of almost zero volt and if the two input voltages are not equal the differential amplifier gives high output voltage.
  
  Used the below _**design equations**_ from reference paper[1]:<br>
   ![des](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/design_eq.png)
   
   ![des2](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/image.png)
 

### Circuit Design


![design](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/Circuit.png)

### Waveforms


1. magnitude plot as per the design with sky130 technology file.
![waveform1](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/magnitude.png)

2. phase plot as per the design with sky130 technology file.
![wavefprm2](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/phase.png)

3. Input plot for transient analysis.
![inputs](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/transient_analysis.png)

4. transient analysis output for the circuit. 
![output](https://github.com/bharath19-gs/differential_amplifier/blob/main/Implementaion%20and%20ouptuts/transient_analysis_output.png)

### References
[1] Bangadkar, M.B., Scholar, P.G., Lamba, M.A. and Bhure, M.V., 2015. Study of Differential Amplifiers using CMOS..

[2] [CMOS differential amplifier design and types of amplifiers](https://silo.tips/download/chapter-3-cmos-differential-amplifiers)

[3] [Differential amplifier - types and design equations](https://www.electronics-tutorial.net/Analog-CMOS-Design/CMOS-Differential-Amplifier/Differential-Amplifier)
