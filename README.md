# Power Distribution Controller

## Introduction
Power Distribution Controller is an electronic system that manage the power distribution of a system. It is controlled by a microcontroller where on this system a STM32F103C8T6 is used. The systems is divided into 2 sub-systems which are a power distributor systems, and monitoring and protection systems. This system is adapted from Formula SAE Power Distribution Controller by Daniel Baron with a lot of modifications
<p align="center">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Power%20Distribution%20Controller%20Top%20Side.png" width="100%" height="auto">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Power%20Distribution%20Controller%20Bottom%20Side.png" width="100%" height="auto">

## Power Distributor Systems
The Power Distribution Systems is divided into 4 kinds which are High Current Regulated Output, High Current Output, Low Current Regulated Output, and Low Current Output. The specifications of the systems is:
1. High Current Regulated Output:
   - Input Voltage: 16 - 12.5 V
   - Output Voltage: 12 V
   - Maximum Output Current (Continuous): 6.67 A
   - Maximum Output Voltage at maximum load: 11.4 V
   - Working temperature: 40 - 50 <sup>0</sup>C
   - Efficiency at maximum load (V<sub>IN</sub>: 12.5 V): 87.8%
   <p align="center">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/High%20Current%20Regulated%20Output%20Top%20Side.png" width="45%" height="auto">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/High%20Current%20Regulated%20Output%20Bottom%20Side.png" width="45%" height="auto">
   </p>
2. High Current Output:
   - Input Voltage: 16 - 12.5 V
   - Output Voltage: Input Voltage
   - Maximum Output Current (Continuous): 10 A
   - Working temperature: 30 - 40 <sup>0</sup>C
   - Efficiency at maximum load (V<sub>IN</sub>: 12.5 V): 86.9%
   <p align="center">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/High%20Current%20Output%20Top%20Side.png" width="45%" height="auto">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/High%20Current%20Output%20Bottom%20Side.png" width="45%" height="auto">
   </p>
3. Low Current Regulated Output:
   - Input Voltage: 16 - 12.5 V
   - Output Voltage: 12 V
   - Maximum Output Current (Continuous): 4 A
   - Maximum Output Voltage at maximum load: 11.3 V
   - Working temperature: 40 - 55 <sup>0</sup>C
   - Efficiency at maximum load (V<sub>IN</sub>: 12.5 V): 89.8%
   <p align="center">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Low%20Current%20Regulated%20Output%20Top%20Side.png" width="45%" height="auto">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Low%20Current%20Regulated%20Output%20Bottom%20Side.png" width="45%" height="auto">
   </p>
4. Low Current Output:
   - Input Voltage: 16 - 12.5 V
   - Output Voltage: Input Voltage
   - Maximum Output Current (Continuous): 5 A
   - Working temperature: 30 - 40 <sup>0</sup>C
   - Efficiency at maximum load (V<sub>IN</sub>: 12.5 V): 91.8%
   <p align="center">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Low%20Current%20Output%20Top%20Side.png" width="45%" height="auto">
   <img src="https://github.com/tangguhbayuw/Power-Distribution-Controller/blob/main/img/Low%20Current%20Output%20Bottom%20Side.png" width="45%" height="auto">
   </p>
