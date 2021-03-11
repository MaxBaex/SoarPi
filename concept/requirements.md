# SoarPi

Soarpi is a navigation system based on the well-known XCSoar software. The also well known [Openvario project](https://www.openvario.org/) follows a similar approach. The motivation to design SoarPi has basically two roots: On the one hand, the Linux hardware of OpenVario is now quite outdated and on the other hand, we would like to add more features.

SoarPi is being developed openly so that anyone interested can contribute or use the results. The goal of this project is to show an inexpensive possibility to equip gliders with adequate navigation systems.

# Connectors

This section describes which connection options SoarPi provides electrically or wirelessly.

## Power Supply

The device is supplied with power via this connector. The device is usually supplied from the board battery and must cope with the usual fluctuations in the supply.

Connector: Power
* Connector: __Todo: to be defined__
* Voltage range: 8 .. 16 V DC

## IGC/Flarm Compatible Interfaces

A connected Flarm device is supplied with power. XCSoar receives the NMEA data from the Flarm. It should also be possible to connect a Flarm remote display directly.

Specifications, see [Flarm Spec](https://flarm.com/wp-content/uploads/man/FLARM_InstallationManual_E.pdf) and [IGC SPec](https://www.fai.org/document-compression/25026).

XCSoar is able to control radios via RS232 interface. SoarPi supports this by a corresponding interface.

Connector: Flarm
* Connector Type: Rj45 (__Todo: to be decided__)
* Signals: 12V Power, Ground, RX, TX, 

Connector: Flarm Indicator
* Connector Type: Rj45 (__Todo: to be decided__)
* Signals: 12V Power, Ground, RX, TX

Connector: Radio
* Connector Type: __Todo: to be defined__
* Signals: Rx, Tx, Ground

## Can bus
__ToDo: describe connector type, standards and applications__

## Speaker
__ToDo: is speaker included or just connected?__

## USB Interfaces

The Remote Stick is a ergonomical method for controlling the XCSoar based glide computer in flight. Details see [this site](https://www.stefly.aero/openvario/). 

It can be added with the help of a USB interface. Other useful devices can also be connected.

Conncector: USB 1
* Connector Type: USB 2 type A port

Conncector: USB 2
* Connector Type: USB 2 type A port

Conncector: USB 3
* Connector Type: USB 2 type A port

Conncector: USB 4
* Connector Type: USB 2 type A port

## µSD Card

The firmware including XCSoar is stored on a µ SD card. The memory card can be replaced without opening the device. 

__ToDo: Alternative would be to work with inernal SD card and trade updates via USB-STick: to be defined__

Connector: Firmware
* Connector Type: µSD Card Holder

# Operation
# Electronics
# Mechanics
