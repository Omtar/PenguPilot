     ___________________________________________________
    |  _____                       _____ _ _       _    |
    | |  __ \                     |  __ (_) |     | |   |
    | | |__) |__ _ __   __ _ _   _| |__) || | ___ | |_  |
    | |  ___/ _ \ '_ \ / _` | | | |  ___/ | |/ _ \| __| |
    | | |  |  __/ | | | (_| | |_| | |   | | | (_) | |_  |
    | |_|   \___|_| |_|\__, |\__,_|_|   |_|_|\___/ \__| |
    |                   __/ |                           |
    |  GNU/Linux based |___/  Multi-Rotor UAV Autopilot |
    |___________________________________________________|


Overview
--------
PenguPilot is a Free and Open Source Multi-Rotor UAV autopilot
for Linux-based computer modules.
The whole state estimation and control system runs as a Linux
user-space task, which is ideal for prototyping and experimentation.
PenguPilot's architecture allows to distribute the control code
among several processes (e.g. high-level control and low-level control).

Contents
--------
Flight Infrastructure:
- autopilot: autopilot software
- blackbox: black box writer
- powerman: power management daemon
- gps: gps sensor, similar to gpsd
- icarus: high-level control and complex commands

Supporting Infrastructures:
- scl: signaling and communication link
- opcd: online parameter configuration daemon
- svctrl: service management and control utility
- shared: shared Libraries
- config: system architecture and parameter config files
- setup: config file creation scripts (EXPERIMENTAL)
- remote: remote control reader service (EXPERIMENTAL)

Build System and Environment:
- site\_scons: related to build system
- SConstruct: scons build file
- scripts: various scripts

![Build Status](https://travis-ci.org/PenguPilot/PenguPilot.png)
