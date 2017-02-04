# Home Assistant configuration

My Home Assistant (https://home-assistant.io) configuration files and screenshots.


## Table of contents

* [Controlled devices](#controlled-devices)
* [What's special?](#whats-special)
* [Screenshots](#screenshots)


## Controlled devices

* [Max Hauri maxSMART Power Station](http://www.maxsmart.ch/de/produkte-de/power-station-de.html)
* [Philips Hue lamps](http://www2.meethue.com/de-ch/productdetail/philips-hue-white-and-color-ambiance-starter-kit-a19)
* [Philips 47PFL6007](http://www.mea.philips.com/c-p/47PFL6007H_12/6000-series-smart-led-tv-with-ambilight-spectra-2-and-pixel-precise-hd#see-all-benefits)
* [Linn Majik DSM](https://linn.co.uk/hifi-separates/network-music-players/majik)
* [Kodi media player](https://kodi.tv/) (running on a Raspberry Pi)
* Game consoles and other devices


## What's special?

### Automation based on power consumption

The Max Hauri maxSMART Power Station can be used to read power consumption and to control socket states. This allows to automatically turn off power for devices that are in standby and which Home Assistant knows are not in use anymore. This is determined by the state of binary switches ('Music', 'TV' etc.).

Another possibility is to automatically switch the source of the amplifier to 'Phono' if the turntable is using energy.


## Screenshots

![Screenshot 1](images/ha01.png)

