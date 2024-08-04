# HA-Airco-HVAC-Control

This blueprint is for using the air conditioner automatically, based on a start and end temperature.

Presence detection and weekday selector are available.

I remain open to feedback and any ideas to make this blueprint more usable for everyone.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Shiard/HA-Airco-HVAC-Control/blob/main/HVAC-Airco-Control.yaml)

See also: https://community.home-assistant.io/t/hvac-airco-control-blueprint/650943 for the original

Made the following changes:
* Streamlined Triggers: Combined above and below triggers for temperature into one.
* Simplified Conditions: Reduced complexity in action conditions for better readability and maintainability.
* Additional Safety Checks: Ensured the automation respects the specified start and stop times more clearly.
