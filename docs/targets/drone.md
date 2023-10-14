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
* Main System-on-Chip: STM32F427VIT6 rev.3
	* CPU: 180 MHz ARM Cortex® M4 with single-precision FPU
	* RAM: 256 KB SRAM (L1)

## Source Code (Firmware)

* [PX4 Drone Autopilot](https://github.com/PX4/PX4-Autopilot): Source code for the whole project,
including bootloader, RTOS, flight mode code
* The RTOS running the drone code is NuttX
* [NuttX Applications](https://github.com/PX4/NuttX-apps/tree/a489381b49835ecba6f3b873b5071d882a18152f)

## Build

```
$ git clone https://github.com/roemvaar/PX4-Autopilot
$ cd PX4-Autopilot
$ make px4_fmu-v4
```

* You can add a version of the firmware at the end, e.g., ``make px4_fmu-v4``

## Load Firmware

Make sure that the drone is plugged into the dev machine using a serial ttl
to USB adapter.

Two options:

* Recommended:

```
$ make px4_fmu-v4 upload
```

* Using ![QGroundControl](https://docs.px4.io/main/en/config/firmware.html)

## Firmware Versions

* [Get specific release](https://docs.px4.io/main/en/contribute/git_examples.html#get-a-specific-release)

* Stable firmware version: v1.13.2

46a12a09bf (HEAD, tag: v1.13.2, powerfuzzer/v1.13.2-stable, origin/stable, v1.13.2-stable) fmu-v2: make optional sensor startup quiet

The lab drone is known to boot correctly using this firmware.

* PX4 GitHub fork with custom firmware (branches):

	* main - mirrors PX4 main repo
	* waterloo - custom commands
