# HA-Airco-HVAC-Control ![version](https://img.shields.io/badge/version-0.4-blue)

This blueprint is for using the air conditioner automatically, based on a start and end temperature.
Based of: https://community.home-assistant.io/t/hvac-airco-control-blueprint/650943 for the original
https://github.com/OoM-JaN/Airco-HVAC-control/blob/main/HVAC%20airco%20control.yaml ![version](https://img.shields.io/badge/version-0.3-blue)

*Core Features*:
* Climate control based on a scheduler
* Minumum startup temperature and maximum shutdown
* Weekday selector
* Presense group selection

*Made the following changes*:
* Streamlined Triggers: Combined above and below triggers for temperature into one.
* Simplified Conditions: Reduced complexity in action conditions for better readability and maintainability.
* Additional Safety Checks: Ensured the automation respects the specified start and stop times more clearly.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Shiard/HA-Airco-HVAC-Control/blob/main/HVAC-Airco-Control.yaml)
