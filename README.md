# BetterRadio

## Hardware ##
[Pirate Radio Kit](https://shop.pimoroni.com/products/pirate-radio-pi-zero-w-project-kit) from [Pimoroni](https://shop.pimoroni.com/)

## Config Files ##

### Setup Raspberry Pi Zero W ###
* ssh
* wpa_supplicant.conf

While the SD card is in another computer copy the ssh file to the {Drive letter:}/boot/ directory. This will enable SSH for the Raspberry Pi Zero W.

Open the wpa_supplicant.conf and edit the SSID and PSK with your WiFi network name and password. Then add this file the same way as the SSH file.

### Playlist for Stations ###
Add the default.m3u file to the following directory: /etc/vlcd/
Each line should be a separate station link.


