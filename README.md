# Home Assistant Blueprints

A small collection of Home Assistant automation blueprints.

## Available blueprints

### Motion - Light

Turns on a light when motion is detected in low illumination and turns it off after motion clears. It uses a helper entity to track whether the automation activated the light.

[![Import the Motion - Light blueprint into your Home Assistant instance](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fpanther7%2Fhomeassistant%2Fblob%2Fmain%2Fblueprints%2Fautomation%2Fpir_light.yaml)

### Zigbee2MQTT - Tuya TS0043 3 button remote

Connects a Tuya TS0043 three-button remote through Zigbee2MQTT. It supports single press, double press, and long press actions for all three buttons.

[![Import the Tuya TS0043 blueprint into your Home Assistant instance](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fpanther7%2Fhomeassistant%2Fblob%2Fmain%2Fblueprints%2Fautomation%2FTS0043.yaml)

## Usage

1. Click an import button above.
2. Confirm the blueprint import in Home Assistant.
3. Create an automation from the imported blueprint and configure its inputs.

Blueprint files are stored in [`blueprints/automation`](blueprints/automation).
