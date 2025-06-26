# EngineAI Firmware Package

## Introduction
This repository contains the firmware packages for the EngineAI robot.

## Installation
1. Set the robot into idle or passive mode
2. Use scp command to copy the firmware package to the robot
3. SSH login to the robot ```ssh user@192.168.0.163```
4. Use sudo dpkg -i command to install the firmware package ```sudo dpkg -i robotics-engineai-pm01_1.0.4_amd64.deb```
5. Restart the robot for the changes to take effect

## Firmware Package List
| Name | Description |
|------|-------------|
| robotics-engineai-pm01 | EngineAI motion control software package |