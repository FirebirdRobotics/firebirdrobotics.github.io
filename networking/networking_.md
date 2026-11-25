## Overview

![Network Diagram](networkdiagram.jpg "On-Robot Network Diagram")

The robot has an onboard network mediated by the [robot radio](radio.md), which includes the [RoboRIO](../operations/roborio.md) and the [coprocessors](../vision/coprocessors.md).  The [driver station](../operations/driverstation.md) connects to these devices over the wifi access point provided by the radio, called "FRC 3019".  For [vision](../vision/index.rst) to work properly, the network should be configured with static IP's as shown in the above network diagram.

## Configuration

The [radio](radio.md), [RIO](../operations/roborio.md), and [coprocessor(s)](../vision/coprocessors.md) should be configured with network settings per their individual pages.

### Static IP Configuration

We use static IPs on the robot to avoid the complications of reconfiguring the DHCP setup regularly.  The IP settings on each device should be:

 * VH-109 radio - static 10.30.19.1
 * roboRIO - static 10.30.19.2 / subnet mask 255.255.255.0
 * VH-109 access point radio - static 10.30.19.4
 * Driver Station - static 10.30.19.5 / subnet mask 255.0.0.0
 * Other devices - static 10.30.19.6-.19 / subnet mask 255.255.255.0

## Radio

See: [Radio](radio.md)

## Common Problems
