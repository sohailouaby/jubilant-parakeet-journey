# jubilant-parakeet-journey

**Skills demonstrated**
Here is what ive learned so u know what ive learned before reading the story

- KiCad
- PCB Layout
- ESP32
- USB-C
- CH340C
- Voltage Regulation
- Power Supply Design
- Schematic Design

## first kicad projet OMG

## Overview

This project documents my journey learning PCB design in KiCad. And it is abt how i built my first ocb and what did i learn from it.

---

## Version 1

### Goal

Learn how to use the software and built my first ever PCB in Kicad

### Components

- 2 THT leds
- 2 THT resistors
- Arduino Nano footprint

### What I learned

- How to read schematics and use them
- How to route the components togther.
- How to assign footprints based on the component that i wanted based on size.

---

## Version 2

### Goal

Go deeper on PCb design and work with an Esp32 wroom

### Challenges

When routing, i couldnt figure out how to route all header pins into the esp32 GPIO pins bcs the traces were interfeering each other.

### Features

- ESP32-WROOM
- Header pins

### Result

After changing the header pins to individual ones, I managed to route all header pins to all GPIO pins and leanred how to work with the software confortably. Now it isnt heck intimidating as it used to be

# Practice PCBs

## Overview

This project documents my journey learning PCB design in KiCad. Instead of building a finished project immediatly after project 1, i worked my way into building my own custom Esp32 dev kit board

---

## Version 1

### Goal

Learn how USB power and capacitors work.

### Components

- USB-A power connector footprint
- LED
- Push button
- 10 µF capacitor

### What I learned

- USB can directly power simple circuits.
- Capacitors help stabilize the power supply.
- Basic PCB routing.

---

## Version 2

### Goal

Learn how to design a custom ESP32 development board from scratch and the components used.


### Challenges

I redesigned both the schematic and PCB six times because design logic was off and wasnt adding up. Each revision taught me how to organize my projects and learn how to distribute power to all of my components

### Features

- ESP32-WROOM
- USB-C power input
- CH340C USB-to-UART
- 3.3 V voltage regulator
- Decoupling capacitors
- USB-C configuration resistors

### Result

After six redesigns, I have finally manged to build a Esp32 dev kit board that is almost like the commercial one and ive learned a lot like pcb routing, voltage regulators, capacitors, and more. Now, i can stop looking at a board like magic and see it like blocks to a funcioning PCB
