# Automatic Night-Light with Motion Sensor

## Required Products:
* Zigbee Motion Sensor (e.g., Aqara Motion Sensor)
* Zigbee 3.0 Light Bulb

## How to Use:
1. Import the blueprint.
2. Enter the motion sensor entity and the light bulb entity.

The setup will automatically configure the night light to turn on under these conditions:
* Monday to Thursday and Sunday: Activates if motion is detected between 9:00 PM and 5:30 AM.
* Friday and Saturday: Activates if motion is detected between 11:00 PM and 5:30 AM.

## Recommended Placement:
Install the motion sensor under your bed, so the night light activates when you get up.
