# Everything Presence One

The Everything Presence One is a presence sensor for the smart home. It combines a mmWave sensor, motion sensor, light illuminance sensor, temperature and humidity sensor and integrates directly with [Home Assistant](https://www.home-assistant.io/) through [ESPHome](https://esphome.io/).

The official user guide for the EP1 is located [here](https://everythingsmarthome.github.io/everything-presence-one/)!

![Everything Presence One](static/images/assembly-insert-pir-sensor-3.jpg)

This repo borrows the mmWave sensor part of the YAML file so that it can be used with an ESP8266 (I am using Lolin/Wemos D1 Mini Pro) for ESPhome.  I have not adapted the smart things version or the beta.

I use the !secret keywords to hide sensitive information.  Input your own information into your secrets.yaml file as described in the [ESPhome FAQ](https://esphome.io/guides/faq.html).
