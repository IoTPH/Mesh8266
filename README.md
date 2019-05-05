<p align="center"> 
<img src="https://github.com/OpenBuildProject/OpenBuild_IoT-Mesh8266/blob/master/logo.png">
</p>

## Open Build IoT - Mesh 8266
**An open source mesh network integration using ESP8266 based on painlessMesh library.**

## Table Of Contents

## Mission
## General
## Development Principles
## Get Started
### Microcontroller Setup and Code Upload <a name="setup"></a>
1. Download Arduino IDE: https://www.arduino.cc/en/Main/Software
2. Open the IDE and click: File -> Preferences -> Additional Boards Manager --> Paste this link: http://arduino.esp8266.com/stable/package_esp8266com_index.json
3. Then click: Tools -> Board -> Board Manager -> search ESP8266 Community, then click install
4. Then click again the Tools -> Board -> NodeMCU 1.0 (ESP12E Module)
5. Then click again the Tools -> PORT -> USB0 (or anything that works)
6. The click Sketch -> Upload | Note: This procedure uploads the bare minimum code and checks whether there are potential errors. There are two common errors. The first one is on the PORT setting. Go back to Tools -> PORT then choose the right one. The second one is the admin permission error. For linux users, run this command in your terminal to change the permission: $ sudo chown user path. Where "user" is your machine's username and path is the location of the permission denied folder. 
7. At this point, you can now start and upload the sample code / sketch. 
### Dependencies
1. ArduinoJson (6.10.0)
2. ArduLibraries
3. PainlessMesh
4. ESPAsyncTCP
5. TaskScheduler
### How It Works

