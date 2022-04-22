# M2_Temperature_Control_System
## Theory
The primary function of the heat control system is to regulate the temperature of a car seat. The button sensor is engaged when a user or driver of the car sits in the vehicle. The user then has the ability to turn on the heating. The temperature sensor continuously measures the temperature and transmits the analogue value to the microcontroller. The temperature sensor's analogue input is processed by the microcontroller, which then produces a temperature reading via serial connection. The control system's whole operation is controlled by an Atmega328 microprocessor.

![image](https://user-images.githubusercontent.com/101788713/164622576-7396f5e4-f367-47d7-9220-f0456599e752.png)
## Components used
### Atmega328
Atmel's megaAVR series includes the ATmega328, a single-chip microcontroller. It has an 8-bit RISC processing core based on Harvard architecture.
![image](https://user-images.githubusercontent.com/101788713/164686576-02998a51-1f62-451f-b9e6-4a67d537a019.png)

### Communication Protocol 
The Universal Asynchronous Receiver Transmitter, or UART, is a serial communication device that converts parallel to serial data at the transmitter and serial to parallel data at the receiver. It is ubiquitous because it has changeable settings such as transfer speed, data speed, and so on.
![image](https://user-images.githubusercontent.com/101788713/164687543-7fed6daf-3a0d-4b42-bead-b9ca370c657b.png)
### Software Used
* SimulIde
SimulIDE is an electronic circuit simulator that runs in real time. It's a straightforward tool for advanced learning that also allows you to enjoy the process. SimulIDE is a simple electronics simulator that is supposed to be quick and easy to use. AVR, Arduino, and PIC microcontrollers are available in SimulIDE and can be accessed in the same way as other components. Gpsim and simavr are features that allow you to use PIC and AVR microcontrollers, respectively.
![image](https://user-images.githubusercontent.com/101788713/164699506-12d66296-01d6-4959-8b1e-64d22e8559fd.png)
* Winavr 
WinAVR is a collection of open-source software development tools for the Atmel AVR series of RISC microprocessors running on Windows. It comes with the GNU GCC C and C++ compiler.
![image](https://user-images.githubusercontent.com/101788713/164700002-75b59da8-a8d8-421d-a9d3-7086ead4d7c1.png)




## SWOT Analysis
S Strength | W Weakness
------------- | -------------
Circuit Knowledge |Complex Flows
Platform Independent | Requires Vs code or Winavr

O Opportunity | T Threats
------------- | -------------
 requirement in every car for a better driving experience | Hardware dependency
Better Sequential Flow | Changing User Attitude
Rising Need in automobile industry | Daily need
## 4W's and 1'H
### Who:
* End Users will be in any sort of vehicles

### What:
* It will monitor the analog value of temperature and we can also control the temperature as per the users need.
### Where:
* This will be particularly useful in  main focus is automobile industry.
### How:
* The button sensor is turned on. The user then has the ability to turn on the heating. The temperature sensor continuously measures the temperature and transmits the analogue value to the microcontroller.





