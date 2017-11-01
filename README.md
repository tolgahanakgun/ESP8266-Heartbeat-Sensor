# ESP8266_Heartbeat_Sensor
A wearable IoT project with ESP8266

This project aims to track patients heartbeat rate in a day and record the data. The provided code was written in Arduino IDE. ESP8266 chip connected with heartbeat sensor connected with analog pin reads the data from finger and sends to a web service within a POST request over WiFi network. The web service address and WiFi credentials are hard coded therefore without compiling the code these credentials and web service address cannot be changed. If you use a NodeMcu the led on the chip will blink simultaneously with hearbeat pulse.
