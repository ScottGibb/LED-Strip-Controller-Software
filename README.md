# LED Strip Controller Software

<center>
<img src="docs/Languages_And_Tools.png">
</center>
# Summary

As discussed throughout this project the LED Strip Controller is a microcontroller-based device running its firmware which can be communicated with using USB Serial. For anyone to interact with the hardware they must either abide by the serial control interface or use one of the following software approaches.

<center>
<img src ="docs/High_Level_System_Diagram.png">
</center>
# Software Interactions
A variety of different software applications were created/used to interact with the hardware.

## Python Command Interface
At the simplest, a Python Control Interface was developed which would connect to the hardware and ask the user a series of questions as to what they wanted each channel to do.

## Node-Red 
The next application was Node-Red which was responsible for interacting with Alexa and acting as a gateway between Alexa and the hardware control system.

## C# Application
As for the final application, a C# Graphical user interface was chosen, to allow for easier control of the Lights Controller and allow the user to control the device and effectively leave it after "uploading" the selected colours and fade patterns.

# Improvements

