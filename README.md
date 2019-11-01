# count-my-heat

IR-Lese-Sensor erfasst die Impulse, schickt sie über einen ESP (esp8266 oder esp32) per MQTT an mosquitto, am mqtt-server können die Events dann z.B. per NodeRed in eine InfluxDB gesteckt und per Grafana visualisiert werden.
Alternativ können die Werte über den esp32 als WiFi-AP mit Captive Portal angezeigt.
