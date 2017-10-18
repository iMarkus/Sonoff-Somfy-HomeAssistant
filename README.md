# Sonoff-Somfy-HomeAssistant

This project describes a simple way on how to use a [Somfy](https://www.somfy.com) remote control with a Sonoff 4CH Pro.

## Somfy Telis 1

For this project the Somfy Telis 1 Pure RTS, 1 Channel remote control was used.

## Sonoff 4CH Pro

The Sonoff 4CH Pro has beend flashed with Tasmota firmware using [SonOTA](https://github.com/mirko/SonOTA).

Please see the [wiki](https://github.com/mirko/SonOTA/wiki) for known working configurations.

## MQTT

After flashing Sonoff with Tasmota firmware it is possible to control it using MQTT and therefore easily integrate it into HomeAssistant. There is also a Mosquito broker add-on available for [hass.io](https://home-assistant.io/hassio/).

## HomeAssistant