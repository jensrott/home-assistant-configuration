# Home Assistant Configuration

## Jens Rottiers - New Media Development

## About

### What I did

I created a system based on [Home-Assistant](https://www.home-assistant.io/) which demonstrates the capabilities of all possible extensions and personalisations you can use in a home automation system.
The system can be seen as prototype which can be later replaced/used as a real home automation system in your house.

### What you need

- A [Raspberry Pi](https://www.kiwi-electronics.nl/raspberry-pi-3-model-b-plus-basic-pack-red-white?search=raspberry%20pi&description=true)
  with [Hass.io](https://www.home-assistant.io/hassio/) installed.
- A physical demonstrator board with all the elements
- My repository with all the files

### Integrations

- Weather forecast (buienrader.nl)
- Weather forecast (Norwegian Meteorological Institute)
- Weather forecast ([Windy](https://www.windy.com))
- Ip Camera generic platform (used for Hikvision camera)
- Z-Wave ([USB Vision Z-Wave Dongle](https://www.robbshop.nl/vision-usb-stick-z-wave))
- Z-Wave (AEON Labs multisensor)
- Google Assistant (Home Assistant Cloud - Nabu Casa)
- Philips Hue
- Waze (travel time calculation)
- Sun integration
- Sonos
- Bose
- Sagem Internet Gateway Device (UPnP)
- RPi GPIO (Raspberry Pi GPIO integration for switches)

### Lovelace UI Personalisation/Customizations

- 4 Views (Light control, Monitoring, Systemservices, Automatisations)

- Light control:

  - Dedicated cards for individual lightcontrol
  - Badges for sensor status
  - Dedicated card for video streaming
  - Control widgets for Sonos and Base
  - Picture-elements card for mood control (Including dedicated )

- Monitoring:

  - Global view on all sensor data
  - Dedicated cards for each sensor

- Systemservices:

  - Dedicated for each system service integration (Weather forecast, traffic control...)

- Automatisations:

  - Switching on/off each automatisation individually

### Automatisations

I created some example automatisations using scripts:

- Turn off all the lights at 2 am (all of)
- Switch on lights at movement detection
- Switch off lights when no movement detected for more than one minute
- Presence simulation
- Alarm (led flashes)

## Images

![front_board](https://i.imgur.com/lzN17mf.jpg)
![back_board](https://i.imgur.com/9nXjVIX.jpg)

## Demonstrator site

I documented all the components of the board on the following [website]().
Here you can also find videos which demonstrate the control of the board.

The site requires a login:

Username: **TestGebruiker**
Password: **Test123**

## Special thanks to

I would like to thank [Niko](https://www.niko.eu/nl-be) for letting me use all the components.
Thank you!
