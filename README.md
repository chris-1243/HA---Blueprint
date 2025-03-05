Small collection of Home Assistant blueprints for the PTM215Z/ZE and PTM216Z. Those blueprints shall be used with Zigbee2MQTT.

In the **deprecated** folder, you will find blueprints based on the deprecated `sensor.action` and they shall not be used with Zigbee2MQTT v2.x.x or later (unless the option below is set to true). This folder will not receive any update.
```shell
homeassistant:
  legacy_action_sensor: true
``` 

There are some sporadic updates for the new `event` action even if this feature is still in experimental mode. A **test** folder is now available to test first iterations based on the new `event trigger`.

...**_v2**: This version has now the `mode: restart` enabled. This is intended to ease the dimming when using HA commands. It adds the possibility to repeat the same command.

For any questions or improvement, feel free to open an issue or to post in the Home Assistant forum directly via the links provided below.

  - [PTM215Z/ZE](https://community.home-assistant.io/t/zigbee2mqtt-ptm215z-ze/827944)

  - [PTM216Z](https://community.home-assistant.io/t/zigbee2mqtt-ptm216z/732003)
