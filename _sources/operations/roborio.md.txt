# RoboRIO (Deprecated)

## Overview

The RoboRIO is a real-time microcontroller designed specifically for FIRST.  It runs the robot code and controls everything that happens on the robot.

## Configuration

### Network Settings

By default, the RIO is configured for DHCP, but it needs to be configured to a static IP at 10.30.19.2 in order to interoperate with the [vision system](../vision/index.rst).

## Common Problems

### The Driver Station cannot find the RoboRIO.

Double check the network settings of the RIO in the web dashboard (it can reset itself under the right circumstances).