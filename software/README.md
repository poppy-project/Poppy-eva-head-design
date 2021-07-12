# File config.txt in the /boot partition of the SD card

In order to get the display on the DSI bus, you must customize the file `config.txt` in the `/boot` partition of the SD card:

- All the lines setting HDMI parameters are commented out with the character `#` at the beginning of the line.

- the section `[pi4]` must contain the lines

```
dtoverlay=vc4-fkms-v3d
max_framebuffers=2
```
As an example you can find a full`config.txt` file in the `software` directory.
