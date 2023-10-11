---
layout: default
title: Drone
parent: Target Platforms
nav_order: 3
---

# Drone Firmware

## Flight Controller (Autopilot) Hardware

* https://docs.px4.io/main/en/flight_controller/
* ![mRo Pixracer (FMUv4)](https://docs.px4.io/main/en/flight_controller/pixracer.html)
* Main System-on-Chip: STM32F427VIT6 rev.3 (opens new window)
	* CPU: 180 MHz ARM Cortex® M4 with single-precision FPU
	* RAM: 256 KB SRAM (L1)

## Source Files (Firmware)

* [PX4 Drone Autopilot](https://github.com/PX4/PX4-Autopilot): Source code for the whole project,
including bootloader, rtos, flight mode code
* The RTOS running the drone code is NuttX
* [NuttX Applications](https://github.com/PX4/NuttX-apps/tree/a489381b49835ecba6f3b873b5071d882a18152f)

## Build

* make px4_fmu-v4
* You can add a version of the firmware at the end, e.g., ``make px4_fmu-v4``

## Load Firmware

Two options:

* Using ![QGroundControl](https://docs.px4.io/main/en/config/firmware.html)
* Recommended: make px4_fmu-v4 upload


## Firmware Versions (Experiments)

* [Get specific release](https://docs.px4.io/main/en/contribute/git_examples.html#get-a-specific-release)

* Stable firmware version: v1.13.2

46a12a09bf (HEAD, tag: v1.13.2, powerfuzzer/v1.13.2-stable, origin/stable, v1.13.2-stable) fmu-v2: make optional sensor startup quiet


1. normal - precompiled downloaded from official page
2. normal - downloaded source code and compiled "manually"
3. low battery - 10V
4. boot fail - 0 division at the bootloader
5. boot fail - 0 division at the battery subsystem
6. secret v1 - /platforms/nuttx/NuttX/apps/secret_v1/secret_v1.c
7. secret v2


# Drone

## Build

```
$ git clone https://github.com/roemvaar/PX4-Autopilot
$ cd PX4-Autopilot
```
