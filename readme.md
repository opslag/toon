<div align="center">
  <img src="https://raw.githubusercontent.com/opslag/toon/master/.github/logo.png" title="Logo" style="max-width:100%;" width="256" />
</div>

# Toon Integration for Home Assistant

This integration adds a climate device for your Toon thermostat, some switches allowing you to control the program and holiday mode of the thermostats as well.

Sensors for energy, power and gas consumption, sensors for solar production and several binary sensors for things like boiler burner on/off, hot tap water and boiler health status.

For the Toon integration to work, you’ll need an active Toon subscription and a Toon API developer account.

Supported devices:

  - Eneco Toon
  - Engie Electrabel Boxx
  - Viesgo Toon

# Installation

## Manual

1. Clone the repository to your machine and copy the contents of custom_components/ to your config directory
2. Restart Home Assistant
3. Setup integration via the integration page.

## HACS

1. Add the integration through this link:
   [![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=opslag&repository=toon&category=integration)
2. Restart Home Assistant
3. Setup integration via the integration page.
