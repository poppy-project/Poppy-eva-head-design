# Poppy-eve-head-design

Raspberry Pi 4-based head design for Poppy Torso and Humanoid ; embedding a screen:

<img src="doc/img/eve_head.png" width="200" />

This repository contains:

* `doc` contains the documentation files on the Poppy Eve head:
  * `Eve_head_design.pdf` gives the design history of the head Eve, made by 3 students of the ENSAM Bachelor of technology at Bordeaux, France.
  * `Eve_head_assemby_procedure.md` is the assembly guide to make the Eve head for the Poppy Torso or Humanoid.
* `hardware`
  * `STL` : contains the STL files to print the four parts that make the Eve head.
  * `BOM.md`: the bill of material.
* `software`
  * `RPi_config`: contains the instructions to add at the end of file `config.txt` in the `boot` partition of the SD card in order to use the DSI connector of the RPI4 to connect the display screen.
