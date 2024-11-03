# Automatic Night-Light with Motion Sensor

## Required Products:
* Zigbee Motion Sensor (e.g., Aqara Motion Sensor)
* Zigbee 3.0 Light Bulb

## How to Use:
1. Import the blueprint.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhtml-css-js23%2Fhomeassistant-blueprints%2Fblob%2Fmain%2F01_night_light_motion_sensor%2Fnight-motion-light.ymal)
Or import by link:

https://github.com/html-css-js23/homeassistant-blueprints/blob/main/01_night_light_motion_sensor/night-motion-light.ymal

2. Enter the motion sensor entity and the light bulb entity.

The setup will automatically configure the night light to turn on under these conditions:
* Monday to Thursday and Sunday: Activates if motion is detected between 9:00 PM and 5:30 AM.
* Friday and Saturday: Activates if motion is detected between 11:00 PM and 5:30 AM.

## Recommended Placement:
Install the motion sensor under your bed, so the night light activates when you get up.
