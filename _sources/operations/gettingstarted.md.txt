# Getting Started

## Overview

By the end of this guide you will be set up to start programming our robot.

## Setup

### Necessary Software

These are the core tools required to work on the robot.  WPILib will provide a customized VSCode installation and the build tools required to write and deploy the robot code.  FRC Game Tools allows you to remotely control the robot.

 - [FRC Game Tools](https://www.ni.com/en/support/downloads/drivers/download.frc-game-tools.html)
 - [WPILib](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html?authuser=0)

Note: FRC software is currently only available for Windows.  This will likely not change.  It is important to reinstall these software suites every season, as differing versions are strictly incompatible.

### Acquiring the Code

The Firebird Robotics code is [hosted on GitHub](https://github.com/FirebirdRobotics).  You can download a local copy by opening the appropriate version of WPILib VSCode, clicking on the Git panel on the left toolbar (it looks like 3 branches), and cloning the appropriate repository by URL.

### Building and Simulating the Code

To build and simulate the robot code in one go, open the command search in WPILib VSCode (by pressing control-shift-P), and locating "WPILib: Simulate Robot Code", selecting "Use Real DriverStation".  It will only work if you open DriverStation first.  If you plug in an XBox controller, you will be able to simulate driving the robot.  If you add some publication of the robot's position into the code, you can view the robot's movement in real time on SmartDashboard.

## Common Problems
