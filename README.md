# Heep Hardware

Welcome to Heep hardware. This part of the Repo contains the Eagle Schematic and Layout files for the circuit board hardware that makes our system tick. The hardware you'll find in here is described below.

## Manufacturing Files

### [Seeed Design Files](Seeed Design Files/)

This section contains the CAM and DRC scripts required to prepare a circuit board under Seeed Studio's Fusion PCB Service. 

## Circuit Board Designs

### [Heep 32u4 Board](Heep32u4Board/)

This circuit runs an ATMega32u4 microprocessor along with a Microchip ENC28J60 ethernet controller to give its relays access to the Heep system. This is a potential candidate for the board behind a Heep Home smart plug or receptacle.

### [Heep Teensy Board](HeepTeensyBoard/)

This is a simple circuit that gives inexpensive network access to a Teensy. It simply holds a Teensy, breaks its pins out, and gives internet access to the Teensy.

### [Heep Teensy Board With Relays](HeepTeensyBoardWithRelays/) 

The same circuit as the Heep Teensy Board, but with 3 relays to allow smart plug and smart receptacle control. It also opens the doors to controlling any other high voltage or high current devices with Heep.

### [Heep Teensy Board With Relays Rev 2](HeepTeensyBoardWithRelaysRev2/) 

A more refined revision of the Teensy Relay board. This board more intelligently runs traces, and organizes the circuit components and connectors in a more accessible way.