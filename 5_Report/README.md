# **INTRODUCTION**

A windscreen wiper or windshield wiper is a device used to remove rain, snow, ice and debris from a windscreen or windshield. Almost all motor vehicles, including cars, trucks, train locomotives, watercraft with a cabin and some aircraft, are equipped with such wipers, which are usually a legal requirement.
A wiper generally consists of a metal arm, pivoting at one end and with a long rubber blade attached to the other. The arm is powered by a motor, often an electric motor, although pneumatic power is also used in some vehicles. The blade is swung back and forth over the glass, pushing water or other precipitation from its surface.  The speed is normally adjustable, with several continuous speeds and often one or more "intermittent" settings. Most automobiles use two synchronized radial type arms, while many commercial vehicles use one or more pantograph arms.
The project is about the implementing of the car wiper control system. In this project by using STM32F407 IDE software , we have to use one switch button, resisters, power supply and 4 different LEDs,those four leds are red,green,blue and orange. In this we have to use ignition also so then only wiper will move.
A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. Firstly when we press on the button and hold it for two seconds then the red ignition will be on at the acc,then after sometime we have to again press the button for the desired sec,the it should on ble led,then so on like green and orange. And at the last the ignition should be turned off.
The advantage is that  it is quite easy for use it,less energy is consumed. But sometimes when water falls squarely on the rain sensor, the mechanism activates.

# **LITERATURE REVIEW**

**STM32F407VG**

It is a high-performance ARM cortex-M4 thirty-two bit controller it is based on RISC architecture and works at one sixty eight megahertz frequency. The Cortex-M4 core of this module provides unique and accurate FPU or floating-point units that incorporates with all types of ARM data commands.
The STM32F407 belongs to the family of microcontrollers and has a core of ARM cortex-M4 which is based on the RISC (Reduced-instruction-set Computing) structure.
This module comprises of large operating speed embedded memory units such as flash memory having a storage capacity of one megabyte, static random access memory of one ninety kilobytes, with that has four-kilo bytes Static ram as back up memory unit.
It printing and scanning machines this device is used. Heat ventilation AC system, security systems, also used this device. In different types of devices used in homes comprises of this module.

 **Features of STM32F407**
  
It comprises of thirty two-bit central processing unit having a core of Cortex M4.

It has a flash memory of one megabytes.

It contains one ninety-two kilobytes static ram with the sixty-four-kilo byte core coupled memory.

There are some additional memories units exits in it which are compact flash, NAND, NOR, SRAM.

There is a voltage range of operating volts is 1.8 to 3.6 volts.

Crystal oscillator having frequency four to twenty-six megahertz is used in it.

It uses a thirty two-kilo hertz oscillator to calibrate the RTC module.

**WORKING PRINCIPLE**
  
 Firstly we have to assume that the automobile is microcontroller.In this there is only one button(switch) and four LED'S those are red, green, blue, yellow, orange. When we press the button, first red led should turn ON,if the user button is pressed and held for 2 secs,then the wiper will start. Then the wiper will turn off,On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.Then the wiper is turned off. then switching the wiper the LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2.then the last step is that when we press on the button the Ignition Key Position at Lock,the Red LED is OFF, if the user button is pressed and held for 2 secs.
  
  **ABOUT STM32F407 DISCOVERY BOARD**
  
  ![stm32f4_discovery_1](https://user-images.githubusercontent.com/101978434/168297101-4180baaa-cef0-4d20-a20a-df23bb9d43df.jpg)
  
  This project gives almost all the basic information needed to get started with STM32F407 Discovery Board and also development of driver code.

Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE

Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY

For installation of STM32CubeIDE refer Youtube

**Overview of STM32F407VGT6 Microcontroller:**

![OVERVIEW](https://user-images.githubusercontent.com/101978434/168297385-80614e28-cbd7-44a8-839c-cdcff1f587e6.png)

The STM32F4DISCOVERY Discovery kit leverages the capabilities of the STM32F407 high-performance microcontrollers, to allow users to develop audio applications easily. It includes an ST-LINK/V2-A embedded debug tool, one ST-MEMS digital accelerometer, one digital microphone, one audio DAC with integrated class D speaker driver, LEDs, push-buttons, and a USB OTG Micro-AB connector.Specialized add-on boards can be connected by means of the extension header connectors.


# **OUTPUTS AND RESULTS**

![board](https://user-images.githubusercontent.com/101978434/168326738-0758ef4a-c016-4aed-bce2-4bd9143f95a5.png)

![green Led on](https://user-images.githubusercontent.com/101978434/168326820-bc4b44c0-4007-44ef-a02e-e35efd54ca97.png)

![orange led on](https://user-images.githubusercontent.com/101978434/168326872-05c1b8d8-0f91-46a9-b852-99e75dbdd08d.png)

![red Led on](https://user-images.githubusercontent.com/101978434/168326912-db65dd9f-b568-47b2-a748-445425773a6a.png)

![car_wiper_control_system](https://user-images.githubusercontent.com/101978434/168327099-d771ea7f-c923-40b7-a86d-53678226b8d1.png)





# **CONCLUSION**

As almost everything described already for this design, we would like to say there are still numerous kinds of enhancements one can implement on this project to make it even more convenient. The project I have made and presented is quite efficient and it is cost effective also. It has great advantage of over the optical sensor covering all the design specifications together with the requirements of common man. The speed controlling mechanism can be added in this project which will make it work according to the intensity and speed of water coming on the sensor. The basic maneuvering is done only to make it cost effective and reliable.
