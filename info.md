# Ecobee Lovelace Card

A card developed for Lovelace to mimic the look of the ecobee thermostat.

Note: All credit to [jknoflook's](https://github.com/jknoflook/homeassistant/tree/master/Ecobee%20Card) Ecobee Card, this is just reformatted for use in HACS.

![ecobee](https://raw.githubusercontent.com/notmayo/ecobee-card/main/ecobee.png)

**Options**

| Name | Type | Default | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | 'custom:ecobee-card'
| entity | string | **Required** | 'climate.home' This is your ecobee climate entity

**To Use:**

In ui-lovelace.yaml:

    resources:
      - url: /local/custom_ui/ecobee-card.js
        type: js

**Example Configuration:**

    - type: custom:ecobee-card
      entity: climate.home
