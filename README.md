# THIS REPOSITORY IS DEPRECATED

This repository has been deprecated in favor of official ARM version of [Tini](https://github.com/krallin/tini)
* Use  __tini-armhf__ for ARMv7 (RPi2)
* Use  __tini-arm64__ for ARMv8 (RPi3)

## About this repository

This is a forked [krallin's Tini repository](https://github.com/krallin/tini) where the aim is compile Tini to work in RPi2 (ARMv7).

Tini is described as a tiny but valid init for containers. All Tini does is spawn a single child (Tini is meant to be run in a container), and wait for it to exit all the while reaping zombies and performing signal forwarding.

For more information of how to use it, go to [krallin's Tini repository](https://github.com/krallin/tini).