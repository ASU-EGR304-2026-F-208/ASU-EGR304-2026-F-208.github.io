---
title: Software Proposal
---
# Software Proposal
#### Inertial Measurement Board -

`SPI`: Inertial Measurement Unit requires SPI to communicate the MCU<br>
`UART`: Display Angular Measurement Data to a PuTTY Terminal using UART from Nano Debugger for verification

#### Distance Sensor Board -

`ADC`: Distance sensor will require amplification of an Analog Signal, so an ADC will be used to read the values and estimate angle from
them

#### Motor Actuation Board -

`PWM`: To change the direction and speed of the DC motor, we will need to use PWM from the MCU.

#### Inter-board Communication

`GPIO`: GPIO pins will be used to send binary values that represent the different states of motor direction.
There will be states for rotating Clockwise, Counter-Clockwise, and no rotation.
