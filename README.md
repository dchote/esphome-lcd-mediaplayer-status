# esphome-lcd-mediaplayer-status
![Example of code running](images/running_on_panel.jpg)

Homeassistant Media Player Status on waveshare-esp32-s3-touch-lcd-7 hardware.

This code was almost entirely created using ChatGPT and many iterations to get something that actually works and looks good. 
It was initially based on the clock example from https://github.com/inytar/waveshare-esp32-s3-touch-lcd-7-esphome

It is entirely self-contained and will display album art, track, artist, and album information.  

I havent been able to get this to cleanly restart after OTAs, you will need to power cycle. This may be related to the waveshare library I'm using... Not sure

## Install Dependencies
You will need to have the relevant fonts available for ESPHome to use. You will need to use the Advanced SSH & Web Terminal addon to do this.

- Download the NotoSans font from Google and place `NotoSans-VariableFont_wdth,wght.ttf` into `/config/esphome/fonts`.
- Find and download `fa-solid-900.ttf` into `/config/esphome/fonts`.
- Land a jpeg at `/config/www/placeholder.jpg` to become the placeholder album art image.




