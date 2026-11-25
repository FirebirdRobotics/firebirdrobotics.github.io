# Coprocessors

## Overview

The vision system runs off of coprocessor(s) attached to a camera each.  The coprocessors we use are OrangePi 5's running a Debian-based PhotonVision Linux distro.

If necessary, the coprocessors can be accessed over SSH with the username "pi" and the password "raspberry".  Normally they should be accessed at [photonvision.local:5800](https://photonvision.local:5800), however.

## Installation

All installation requires is flashing the OS onto the SD card.  This should be done with the [Raspberry Pi Imager](https://www.raspberrypi.com/software/) version 2.0.0 or Balena Etcher (deprecated).  The image should be the latest version from the [PhotonVision releases page](https://github.com/PhotonVision/photonvision/releases/latest) of the form "photonvision-{version}-linuxarm64_orangepi5.img.xz".

## Configuration

### Networking Setup

The IP address can be set through the web interface.  It is important to set the team number to 3019, and set a static IP address.  The first Pi should be at 10.30.19.11, and subsequent Pi's count up from 12.

If there are multiple Pi's, their hostnames should be changed to something descriptive (e.g., photonvision-back.local).

### Adding Cameras

Cameras should be plugged into the USB ports, and activated in the "Cameras" tab.  Change the names and follow the calibration instructions under the [vision parent page](index.rst).

## Common Problems
