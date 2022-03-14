# Child-Tracking-System-2
It's another blended version of the first uploaded tracking system but using only Nodemcu v3 and Gps module

The materials needed for this:
New Nodemcu V3 - Esp 8266 Wifi.
Gps module with antenna - Neo6mv2
Jumper wires.
The software package - Arduino IDE.


Connection:

VCC of Gps Module ---> 3V of Nodemcu

GND of Gps Module ---> G of the Nodemcu

RX of the Gps Module  ---> D1 on the Nodemcu

TX of the GPS module ---> D2 on the Nodemcu.

Done!!

Upload code to the IDE

Install the necessary libraries and set the baud rate to 11500 and upload code via the dedicated usb port.

Libraries.

TinyGPS++.h

ESP8266WiFi.h

BlynkSimpleEsp8266.h
