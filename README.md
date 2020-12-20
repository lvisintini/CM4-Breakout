# CM4-Breakout (project discontinued)

A simple 2 layer PCB board for the Raspberry pi CM4 designed on KiCad.

##  Objectives

- Ceate a PCB board with all the CM4 pins exposed so that it can be used for prototyping as part of a breadboard.
- Learn how to layout a board in KiCad
- Learn how to design for the CM4

## Outcomes and conclusions

While it was certainly educational to attempt to design this board, I wont be finishing this project.

There are many reasons, but the main problem is that it is just not very practical:
- Most projects wont need to use everything and creating a breakout board that only uses the required features is simpler.
- Exposing some pins as anything other that the ports/jacks they are designed for is nonsensical.
- There is already an [abundance](https://github.com/geerlingguy/raspberry-pi-pcie-devices) of open-hardware projects with desing breakout boards for the CM4. There is probably no need for a new one with a narrow use case such as this one..
- Trying to fit all the traces using only 2 layers is too much of a constraint (the CM4IO uses 4)

However, this was not a waste of time:
- Learned a lot about the CM4 module
- Learned a lot about KiCad 6 (pre-release nightly versions)
- Learned a lot about PCB design in general

## Screenshot

![Screenshot](https://github.com/lvisintini/CM4-Breakout/raw/master/Progress.png)
