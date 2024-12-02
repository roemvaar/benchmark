---
layout: default
title: Example Usage
nav_order: 3
has_children: true
permalink: /docs/examples
---

# Example Usage

## AGL - Send CAN to the dashboard

Host machine:

```
$ canplayer -I <logfilename>.log can1=can0
```


## Target Platforms

Target platforms characteristics:

| **Industry**  | **Target**    | **Communication Protocol** |
|---------------|---------------|----------------------------|
| Aerospace     | Drone         | MAVLink                    |
| Automotive    | AGL Dashboard | CAN                        |
| Smart Sensors | Camera        | UART                       |
