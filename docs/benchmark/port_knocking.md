---
layout: default
title: Port Knocking
parent: Benchmark Overview
nav_order: 4
---

# Port Knocking

Port knocking is a security mechanism where firewall ports are externally opened
through a sequence of connection attempts on a predefined set of closed ports.

After receiving a valid series of connection attempts, the firewall rules are
dynamically updated to enable the host that sent the knocks to connect to a given
port.

## Types of Port Knocking

* Static knocks
* Covert knocks
* Dynamic knocks
* One-time knocks
* *Sequence based*
* *Single packet authorization*
