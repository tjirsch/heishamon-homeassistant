# heishamon-homeassistant

An integration for heatpumps handled by [heishamon](https://github.com/Egyras/HeishaMon).

## Installation

ssh into homassistant instance
clone into /root/config/custom_components/aquaera

## Configuration

Just make sure you have an MQTT integration configured. Heishamon mqtt messages should quickly lead to auto-discovery. There is no way to configure one manually.
ℹ This integration supports any heishamon MQTT topic prefix (defaults to `hp01`) and a setup of on heatpump with Heating and DHW.
⚠ Only the sensors related to this setup are enabled by default. They can easily enabled when looking at the "Aquarea HeatPump Indoor Unit" device under "entities not shown".

