PDPi-11
=======

PDPi-11 - PDP-11 on the Raspberry Pi

PiDP-11 is a software bundle containing a PDP-11 simulator and various operating
systems from the hugely popular (in it's time) minicomputer.

## Why?
I recently read that a nuclear power plant in Canada was planning on keeping
their PDP-11 that controls plant robotic systems in service until 2050! With
that in mind someone at GE is looking to recruit PDP-11 assembly programmers
to maintain their systems[1].

The Raspberry Pi is aimed at getting people closer to the computer, so why
no get them closer one of the other most influential systems in computing
history.

## What?
The PDP-11 simulator comes courtesy of Bob Supnik's SIMH[2][3], a collection
of simulators for bygone computing platforms. The aim is to put together
pre-built simulator binaries along with config and OS disk images, all
wrapped with neat startup scripts to make getting started simple.

## Supported PDP-11 Operating Systems
Currently the following operating systems are provided with PiDP-11. To start
an OS you just need to run the appropriate shell script.

dosbatch-11 - DOS/Batch-11 V10
pdp-11-unixv6 - PDP-11 UNIX V6
pdp-11-unixv7 - PDP-11 UNIX V7
rt-11-v53 - RT-11 v5.3
rt-11-v53-ethernet - RT-11 v5.3 with an ethernet card configured

## References
[1] http://www.vintage-computer.com/vcforum/showthread.php?37827-Greetings-from-GE-Canada
[2] http://simh.trailing-edge.com/
[3] https://github.com/simh/simh
