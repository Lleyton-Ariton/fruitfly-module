# Fruitfly Module

## Overview
This repository contains hardware for the *Fruitfly*.

The Fruitfly is intended to be a small but powerful LoRa capable embedded module. The design is currently implemented as an M.2 Key B for simple usage and extendability.

All files are intended for KiCad 6.

## Features 

Micro Controller Unit (MCU):
 
 - The Fruitfly is build around the STM32H723 MCU with an Arm® Cortex®-M7 core operating at 550MHz

Memory and Storage:

- 32MB of on-board SDRAM
- 32MB of NOR FLASH
- MicroSD card interface

Communication:

- Semtec SX1276 LoRa Transciever

## TODO
This is not an exhaustive list but is marked in order of priority:

- Complete first draft of schematic
	- Add bus aliases where missing 
	- Change power supply line selection circuitry
	- Add TVS diodes to microSD card
	- Potentially include SD card translator IC
	- Final schematic review
- Complete PCB layout and design
