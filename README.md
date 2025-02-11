Small collection of Home Assistant blueprints for the PTM215Z/ZE and PTM216Z. Those blueprints shall be used with Zigbee2MQTT.

...**(HA)** version are based on the deprecated `sensor.action` and shall not be used with Zigbee2MQTT v2.x.x or later (unless the old `Home Assistant legacy action sensors` is set to `true`. Those files have been moved to the **deprecated** folder and they will not receive any update.

There will be an update for the new `event` action when this feature will move from the experimental mode. A **test** folder is now available to test first iterations based on the new `event trigger`.

... _v2.yaml: This version has now the `mode: restart` enabled. This is intended to ease the dimming when using HA commands. It adds the possibility to repeat the same command.

For any questions or improvement, feel free to open an issue or to post in the Home Assistant forum directly via the links provided below.

  - [PTM215Z/ZE](https://community.home-assistant.io/t/zigbee2mqtt-ptm215z-ze/827944)

  - [PTM216Z](https://community.home-assistant.io/t/zigbee2mqtt-ptm216z/732003)
