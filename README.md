# edgehog-buildroot-rpi-images

## A Raspberry Pi 4 64-OS image based on Buildroot with Rauc and Edgehog.

------------

## Installation.

- Get a 4 GB SD-card which will hold the image.
- Download the image BR2-RAUC-EDGEHOG-date.zip from release page
- Extract the image
- Flash the image on the SD-card with bmap-tools
``` shell
    bmaptool copy images/sdcard.img.xz /dev/sda
```
- Insert the SD-card in your Raspberry Pi 4.
