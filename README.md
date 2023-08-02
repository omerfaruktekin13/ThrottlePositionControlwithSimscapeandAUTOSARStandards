# ThrottlePositionControlwithSimscapeandAUTOSARStandards
Throttle Position Control with Simscape and AUTOSAR ISO26262 Standards
# Throttle Position Control with Simscape and AUTOSAR Standards

## Project Media
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/VehicleDesign.png "Deneme ")
|:--:|
| *Vehicle Model* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/Architecture.png "Deneme ")
| *Overall System* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/Composition.png "Deneme ")
| *Software Architecture* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/LookUpTable.png "Deneme ")
| *LookUp Table* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/PIDControl.png "Deneme ")
| *Function-Call Subsystem* |
![Dxxxxx](https://github.com/omerfaruktekin13/ThrottlePositionControlwithSimscapeandAUTOSARStandards/blob/main/Media/function-call.png "Deneme ")
| *PID Control Unit* |

## Description
I've created a CAN (Controller Area Network) bus system to simulate transmitter and receiver signals between the powertrain and ECU (Electric Control Unit) of the vehicles. To create virtual channels and CAN Pack/ CAN Unpack connections, I used Simulink Vehicle Network Toolbox. Furthermore, I decided to add a Sensor Fusion algorithm to my project in order to observe signal characteristics between IMU sensors and vehicle dynamics. Figure 1 represents the CAN Network. Figures 2 and 3 are showing the wheel and IMU sensor respectively. The last image depicts the comparison of the transmitter and receiver signals. According to the plot, CAN bus can be implemented to create a connection between ECU and the wheels.

## Tools and Languages
<a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a>
<p> * MATLAB 2023a </p>
<p> * Simulink </p>
<p> * Simulink Powertrain Blockset </p>
<p> * Simulink Desktop Real-Time </p>
<p> * Simulink Vehicle Network Toolbox </p>

## Installation
> 1. Download WheelsCanCommunication.slx and CANCommunicationPlot.m files.
> 2. Open the Simulink Model. You can use the .m file to plot and compare receiver and transmitter CAN Signals.
> 3. You can create your C code using Code Generator to implement it to your hardware.

## Open to Development
Please share your comments and ideas about the project with me. Thank you for your time.
