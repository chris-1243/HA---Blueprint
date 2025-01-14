Small collection of Home Assistant blueprints for the PTM215Z/ZE and PTM216Z. Those blueprints shall be used with Zigbee2MQTT.

...**(HA)** version are based on the deprecated sensor and should not be used with Zigbee2MQTT v2.x.x or later.
There will be an update for the new `event` action when this feature will move from the experimental mode. A **test** folder is now available to test first iterations based on the new `event trigger`.

**UPDATE**

**2025.01.14 :**
Before updating, please read carefully this note. This will apply to all version from 2025.01.14 or later

There are some syntax changes which impact the `button_x_and_y_***` action. Your automation based on this function will have to be updated according to the next sentence: 

`button_x_and_y_***` becomes **buttons_x_and_y_*****.

The easiest way to proceed is to open your automation based on this blueprint and select `edit in YAML`. Then, just add the **s** missing.
