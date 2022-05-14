## M3_Wiper-Control-System
## Abstract
Wiper is an essential component that is used to wipe raindrops or any water from the vehicle’s windscreen. The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems. In spite of removing water from windscreen, this system also will be upgraded to an automatic control system by using a Peripheral Interface Controller and water sensor. The wiper system functions well according to the water condition from the outside of a car. This project showed a contribution on the design of the automatic wiper system for the future research in this same field. In this project we will build manually controlled wiper control system. We built a wiper control system using STM32F4 Discovery board. Here we use builtin button and LEDs to operate or visualize the project. We will control onboard four LEDs of STM32F4 discovery board with a push button.
## Requirements
### INTRODUCTION
The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.     
### SOFTWARE REQUIREMENTS

STM32 CUBE IDE

COMPONENTS

STM32F4O7VG MICROCONTROLLER BOARD
## 4W's & 1H
### What
Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
### When
The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
### Where 
It can be incorporated in car, trucks, etc
### Why 
To keep the windscreen clean enough to give adequate view at all times.
### How 
By using STM32F407VG microprocessor       
### Swot Analysis
![Swot Analysis](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/d7640b7406c72c18fbeee72a3aeb75494aec78aa/1_Requirements/Swot%20Analysis.png)
## Detail requirements
## High Level Requirements
| ID | Description | Requirement | Status | 
| ----- | ----- | ------- | ---------|
| HR001 | SSD or HARD DRIVE  | 1GB TO 20 GB | IMPLEMENTED | 
| HR002 | OPERATING SYSTEM  | WINDOWS |  IMPLEMENTED  |
| HR003 | PROGRAMMING LANGUAGE | EMBEDDED C |  IMPLEMENTED  |
| HR004 | ARM BASED MICROCONTROLLER | STM32F407VGT6 BOARD  |  IMPLEMENTED  |
## Low Level Requirements
| ID | Description | REQUIREMENT | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR001 | WIPER COMES TO INITIAL POSITION AFTER HIS WORK | LED USED FOR THIS |  IMPLEMENTED  |
| LR002 | PROPER SUPPLY TO PINS AND BOARD | DONE |  IMPLEMENTED |
| LR003 | ON AND OFF SWITCH MECHANISM FOR ACTIVATION AND DEACTIVATION OF WIPER BLADES  | DONE  | IMPLEMENTED |
## FlowChart
![Flowchart](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/8fe6ad44abe125e0f7e78a252d74f2465d0a2c9e/2_Design/Flow%20Chart.jpeg)
## Block Diagram
![BlockDiagram](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/073d6a966e2bb7c525ba195461891583a46bdde2/2_Design/BlockDiagram.png)
### Low Level Test Case
![Low Level Test Case](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/90c681d061b6463fe9d72664e046f4e84708d7ee/4_TestCases/Low%20Level%20Test%20Case.png)
## High Level Test Case
![High Level Test Case](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/fb5609794dd6a19df82e57a8a770868df4fbb27f/4_TestCases/High%20Level%20Test%20Case.png)
# On State
![On State](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/2671bd6bba8dc99f1381f37c9a6a82e0f237b786/6_Output/On%20State.png)
## Lower Wiper Speed
![Lower Speed Speed](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/a602d050ed7659e928604437e30e28b9959d6097/6_Output/Lower%20Wiper%20Speed.png)
## Wiper Speed Is Moderate
![Wiper Speed is moderate](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/bc54915c934b551af1f396d4b73b0b2975124531/6_Output/Lower%20Wiper%20Speed.png)
## High Wiper Speed
![High Wiper Speed](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/27af16f59cda60621ee7dfd78e60020691509b1a/6_Output/High%20Wiper%20Speed.png)
## Off State
![Off State](https://github.com/BhargavaRaj/M3_Wiper-Control-System/blob/34ccd75e9ebad71d777c5cde2c020706b7962101/6_Output/Off%20State.png)





