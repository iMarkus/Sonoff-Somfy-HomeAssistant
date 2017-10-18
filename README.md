# Sonoff-Somfy-HomeAssistant

This project describes a simple way on how to use a [Somfy](https://www.somfy.com) remote control with a Sonoff 4CH Pro.

## Somfy Telis 1

For this project the Somfy Telis 1 Pure RTS, 1 Channel remote control was used.

### Soldering
<p>
3 switches - UP / MY / DOWN
</p>
<img src="https://github.com/iMarkus/Sonoff-Somfy-HomeAssistant/blob/master/media/SomfyTelis.jpg" width="15%">
<p>
This is how it looks like after putting some shrink-on tube on it. 
</p>
<img src="https://github.com/iMarkus/Sonoff-Somfy-HomeAssistant/blob/master/media/SomfyTelisShrinkOnTube.jpg" width="15%">

## Sonoff 4CH Pro

The Sonoff 4CH Pro has been flashed with Tasmota firmware using [SonOTA](https://github.com/mirko/SonOTA).

Please see the [wiki](https://github.com/mirko/SonOTA/wiki) for known working configurations.

The Somfy remote fits exactly into the Sonoff case and there is still enough space for the cables.

<img src="https://github.com/iMarkus/Sonoff-Somfy-HomeAssistant/blob/master/media/Sonoff4chPro.jpg" width="50%">

<ul>
<li>R1 - unused</li>
<li>R2 - UP</li>
<li>R3 - MY</li>
<li>R4 - DOWN</li>
</ul>

## MQTT

After flashing Sonoff with Tasmota firmware it is possible to control it using MQTT and therefore easily integrate it into HomeAssistant. There is also a Mosquito broker add-on available for [hass.io](https://home-assistant.io/hassio/).

## HomeAssistant
