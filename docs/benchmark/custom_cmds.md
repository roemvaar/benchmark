---
layout: default
title: Custom Commands
parent: Benchmark Overview
nav_order: 2
---

# Custom Commands

## General

## Drone Specific

## Drone Firmware - "Undocumented" Commands

| **Command** |   **Type**  | **No. of Instructions*** |                     **Name**                     |
|:-----------:|:-----------:|--------------------------|:------------------------------------------------:|
|     591     |    Proxy    | X                        |   VEHICLE_CMD_COMPONENT_CUSTOM_RECEIVE_HANDLER   |
|      27     |    Proxy    | X                        |  VEHICLE_CMD_COMPONENT_CUSTOM_RECEIVE_HANDLER_2  |
|     602     |    Proxy    | X                        |  VEHICLE_CMD_COMPONENT_CUSTOM_RECEIVE_HANDLER_3  |
|      35     |   Non-mem   | 1                        |   VEHICLE_CMD_COMPONENT_CUSTOM_NON_MEMORY_ADD_1  |
|     363     |   Non-mem   | 5                        |   VEHICLE_CMD_COMPONENT_CUSTOM_NON_MEMORY_ADD_5  |
|     702     |   Non-mem   | 10                       |  VEHICLE_CMD_COMPONENT_CUSTOM_NON_MEMORY_ADD_10  |
|      68     |   Non-mem   | 100                      |  VEHICLE_CMD_COMPONENT_CUSTOM_NON_MEMORY_ADD_100 |
|     379     |   Non-mem   | 1000                     | VEHICLE_CMD_COMPONENT_CUSTOM_NON_MEMORY_ADD_1000 |
|     253     |     Mem     | 1                        |   VEHICLE_CMD_COMPONENT_CUSTOM_MEMORY_ACCESS_1   |
|      45     |     Mem     | 5                        |   VEHICLE_CMD_COMPONENT_CUSTOM_MEMORY_ACCESS_5   |
|     481     |     Mem     | 10                       |   VEHICLE_CMD_COMPONENT_CUSTOM_MEMORY_ACCESS_10  |
|      49     |     Mem     | 100                      |  VEHICLE_CMD_COMPONENT_CUSTOM_MEMORY_ACCESS_100  |
|     399     |     Mem     | 1000                     |  VEHICLE_CMD_COMPONENT_CUSTOM_MEMORY_ACCESS_1000 |
|     562     |    Flash    | 1                        |    VEHICLE_CMD_COMPONENT_CUSTOM_FLASH_ACCESS_1   |
|     257     |    Flash    | 5                        |    VEHICLE_CMD_COMPONENT_CUSTOM_FLASH_ACCESS_5   |
|     161     |    Flash    | 10                       |   VEHICLE_CMD_COMPONENT_CUSTOM_FLASH_ACCESS_10   |
|      72     |    Flash    | 100                      |   VEHICLE_CMD_COMPONENT_CUSTOM_FLASH_ACCESS_100  |
|      48     |    Flash    | 1000                     |  VEHICLE_CMD_COMPONENT_CUSTOM_FLASH_ACCESS_1000  |
|      39     | Conditional | X                        |    VEHICLE_CMD_COMPONENT_KILL_SWITCH_KNOCK_ONE   |
|     389     | Conditional | X                        |    VEHICLE_CMD_COMPONENT_KILL_SWITCH_KNOCK_TWO   |
|      51     | Conditional | X                        |   VEHICLE_CMD_COMPONENT_KILL_SWITCH_KNOCK_THREE  |
|     409     | Kill-Switch | X                        |   VEHICLE_CMD_COMPONENT_KILL_SWITCH_ARM_DISARM   |

* X is don't care value