# GARBAGE-COLLECTING-MOBILE-ROBOT

**ABSTRACT**

Twenty-first century has endorsed for remarkable growth in technical as well as economic sectors, yet there remains the lack of proper waste management techniques in most countries. This project focuses on implementation of a autonomous robotic machine which can be controlled by software that will give commands to the robotic jaw to collect the stationary waste as part of the initial stage to ensure a hygienic environment for us to live in. The main idea was to design and implement a robotic device that collects garbage lying on corridors, large halls, or even a house, by picking up using a Robotic arm. The device embodies a tough chassis, Arduino, ESP32, a motor driver and a precise robotic arm with actuators.This robot has one robotic arm in which it can pick the garbage and dispense it in main basket attached to the robot. The prototype has an electronic mechanism by which the robot can dispense it collected garbage to the dispensing point. This robot has installed batteries in which there is no fuel or electricity required to complete the operation

**SYSTEM WORKING**

The project is based on a low-cost solution; the system is completely userfriendly. The project consists of semi-autonomous button control. We have used one Bluetooth module for wireless links between the robot and the mobile for below base and also an ESP32 module for above ARM control through mobile. The mobile generates the command and sends it to the Arduino microcontroller and ESP32 module via Bluetooth and WIFI network and the microcontroller read the command and performs the respective action. There is one robotic hand placed on the robot which will pick up the garbage and dispense it in the basket which is placed on robot. servo motors are used in robotic hand which move the robotic hand in 6degrees of freedom.

We have used Arduino based microcontroller in this project in which it has 54 digital input/output pins (of which 14 can be used as PWM outputs), 16 analog inputs, 4 UARTs (hardware serial ports), a 16 MHz crystal oscillator, a USB connection, a power jack, an ICSP header, and a reset button.

The motor driver which we have used is L293D, L293D designed to provide bidirectional drive currents of up to 600-mA at voltages from 4.5 V to 36 V. Both devices are designed to drive inductive loads such as relays, solenoids, DC and bipolar stepping motors, as well as other highcurrent/high-voltage loads in positive-supply applications.

We have used one buck converter to convert 12V to 5V for microcontroller operation. We are controlling our Robotic Arm through ESP32.

**APPLICATION USED**

1. Arduino IDE - The Arduino Integrated Development Environmentcontains a text editor for writing code, a message area, a text console, a toolbar with buttons for common functions and a series of menus. It connects to the Arduino hardware to upload programs and communicate with them.
2. BLYNK App – We have used this application to control our robotic arm through ESP32. Blynk is an IoT platform for iOS or Android smartphones that is used to control Arduino, Raspberry Pi and NodeMCU via the Internet. This application is used to create a graphical interface or human machine interface (HMI) by compiling and providing the appropriate address on the available widgets

![image](https://github.com/AnjaliDolas/GARBAGE-COLLECTING-MOBILE-ROBOT/assets/104906262/47f8a7ae-a58e-457f-874d-8eb4e761a3dd)

3. Bluetooth RC Controller – We have used this application for controlling base of the robot. Forward and backward movements are controlled by the direction of power flow from the battery. Turning operations to the right and the left are performed by logic like turning to left side involves power flow form battery only to right side wheels, right side wheels do get power flow.


![image](https://github.com/AnjaliDolas/GARBAGE-COLLECTING-MOBILE-ROBOT/assets/104906262/8e29de0c-feae-492c-a880-55262d255990)

**CIRCUIT DIAGRAM**


![image](https://github.com/AnjaliDolas/GARBAGE-COLLECTING-MOBILE-ROBOT/assets/104906262/a7bf597c-fc2a-4c52-a9d8-fd6bfb78a272)

Fig. Circuit diagram of Arm


![image](https://github.com/AnjaliDolas/GARBAGE-COLLECTING-MOBILE-ROBOT/assets/104906262/3fa84e22-4dc4-4c11-8de8-020cff121c9c)


