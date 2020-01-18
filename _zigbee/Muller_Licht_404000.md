---
model: 404000 
vendor: Müller Licht 
title: Tint A60 806lm E27 RGBCCT Bulb
category: light
supports: on/off, brightness, colortemp, colorxy
image: /assets/images/devices/404000.jpg
zigbeemodel: ['ZBT-ExtendedColor']
compatible: [z2m,conbee]
mlink: https://www.mueller-licht.de/produktinformationen/artikel/404000/
link: https://www.amazon.de/dp/B07XDNCGR5
link2: 
link3: https://www.amazon.co.uk/M%C3%BCller-Licht-E27-White-Compatible-Controllable-Dimmable/dp/B07CSFNJQP 
---
### Pairing
Turn the light bulb five times on and off. After turning it on the sixth time,
it will indicate with colors that the bulb is pairing.


### Device type specific configuration
*[How to use device type specific configuration](https://www.zigbee2mqtt.io/information/configuration)*


`transition`   
Controls the transition time (in seconds) of brightness,
colortemp (if applicable) and color (if applicable) changes. Defaults to `0` (no transition).
Note that this value is overridden if a `transition` value is present in the MQTT command payload. 