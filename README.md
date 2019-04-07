# falldetection
# abstract
Falling is an external aspect that can lead to death for the elderly. With so many activities they can do will increase the likelihood of falling. A fall detection device is designed to minimize post-fall risk. An MPU6050 sensor with 3 axis accelerometer and 3 gyroscope axis is used to detect the activities of the elderly. This research is expected to recognize the falling forward movement, falling aside, falling backward, sitting, sleeping, squatting, upstairs, down stairs and praying. This project module is a combined integration of NodeMCU ESP8266 and MPU6050 for gyroscope and accelerometer for retrieving the fall detection details.

HARDWARE REQUIRED :
* NodeMCU ESP8266
* MPU6050
* Female-Female Jumper wires.

SOFTWARE REQUIRED :
* Arduino IDE
* ESP8266 Library
* Cayenne MQTT Library
* MPU6050 Library

MISCELLANEOUS :
* Wifi Internet connection
* Soldering tool and wires
* Micro USB Cable

TOTAL COST OF COMPONENTS :- RS.1000- RS.1500

# System Overview
The main component of the setup is the Nodemcu ESP8266 module. All the other hardware components are connected to the Nodemcu. The board is programmed in Arduino IDE and uses the ESP8266, MPU6050, Cayenne MQTT libraries. These libraries have been added to the Arduino IDE. The MPU6050 module with gyroscope and accelerometer is directly connected to the Nodemcu using a micro USB cable. This MPU6050 is used to detect the fall achieved when hits the condition and is signalled by the programmed NodeMCU ESP8266 with a trigger as an Email using Cayenne support.

# Programming NodeMCU and Setting Up Cayenne Dashboard
* Import MPU6050 Library to the Arduino IDE
* Fill your cayenne token, ssid, and wifi password to the code.
* Upload falldetection code to your NodeMCU

* Setup your cayenne dashboard, add a custom widget, choose two state widget and give it name, choose virtual pin V8 for connectivity, and press add widget.
* Now press the trigger, give trigger's name, on if add the widget added befor, on then fill email with your email, and press save.

# Links to Github and Youtube

Github : https://github.com/sarnaam/falldetection
Youtube : https://www.youtube.com/watch?v=-hb-8XGw5ZU
