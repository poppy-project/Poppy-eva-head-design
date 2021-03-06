# Poppy-eva-head-design

Raspberry Pi 4-based head design for Poppy Torso and Humanoid ; embedding a screen: the work was done by 3 students of the ENSAM Bachelor of technology at Bordeaux, France: Damien MARTY, Clément GEA and Éléa CHARPNTIER, under the supervison of Jean-Luc CHARLES and Cécile DELARUE, professors at ENSAM Bordeaux.

<img src="doc/img/Eva_head_with_students.png" width="200" /> <img src="doc/img/eva_head.png" width="200" /> 

This repository contains:

* `doc` contains the documentation files on the Poppy Eva head:
  * `Eva_head_design.pdf` gives the design history of the head Eva.
  * `Eva_head_assemby_procedure.md` is the assembly guide to make the Eva head for the Poppy Torso or Humanoid.
* `hardware`
  * `STL` : contains the STL files to print the four parts that make the Eva head.
  * `BOM.md`: the bill of material.
* `software`: contains the instructions to customize the file `config.txt` in the `boot` partition of the SD card in order to use the DSI connector of the RPI4 to connect the display screen. A full example of `config.txt` is also given.
