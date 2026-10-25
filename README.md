# HackClub Week 3: MIDI Keypad

A custom-designed MIDI input device featuring tactile mechanical switches, analog sliders, rotary encoders, and capacitive touch pads.

---

## Overview

This project is a custom MIDI controller built around the waveshare ESP32-S3-ZERO microcontroller. It integrates multiple types of user input: push buttons, sliders, a rotary encoder, and capacitive touch channels which allows for real-time control over music production.

---

## Schematics & Layout

### Schematic
The complete schematic details the wiring for the ESP32-S3-ZERO, rotary encoders (`SW4`), slide potentiometers (`RV1`, `RV2`), mechanical push switches (`SW1`–`SW3`), and capacitive touch headers.

![Schematic](./images/f_schematic.png "Schematic")

### PCB Layout
The custom 2-layer printed circuit board layout designed in KiCad, routing signals across the front (`F.Cu`) and back (`B.Cu`) copper layers along with some cool art I created a while ago.

![PCB](./images/f_pcb.png "PCB")

### 3D Model
A 3D render preview showcasing the physical layout and placement of components on the hardware.

![3D Model](./images/f_3d_model.png "3D Model")

---

## Features & Hardware Components

- **Microcontroller:** ESP32-S3-ZERO
- **Inputs:**
	- 3x Mechanical Push Switches (`SW1`–`SW3`)
	- 2x Slide Potentiometers / Sliders (`RV1`, `RV2`)
	- 1x Rotary Encoder with Push Switch (`SW4`)
	- Capacitive Touch Button Header (`J1`)

---

> The [Journal](./JOURNAL.md) file details my experience this week

---

## Onshape Case for storing the MIDI Keypad

[Onshape Link](https://cad.onshape.com/documents/9c3e4e1773f598a6c621c8e7/w/239b4c5f4313af9012ed1455/e/c954f826d795d710e863c1da)

> Just a box to store the midi without damaging it. Made it with my MIDI's dimension in sight