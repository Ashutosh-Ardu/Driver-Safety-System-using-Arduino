# Driver-Safety-System-using-Arduino
* System's Overview: [`Overview`](./PrjtOverview.png)

* System's Flowchart:
<p align = "center">
  <img src="./Flowchart.png" width = 50%>
</p>

* [VehicleModule](./VehicleModule/) has code related to the our car simulator part with various sensors
-> All pin connections are mentioned in the code<br/>
-> Install LiquidCrystal_I2C library from Arduino IDE for interfacing the LCD<br/>

* [HeadKitModule](./HeadKitModule/) has code related to the wearable head kit designed by us.
-> All pin connections are mentioned in the code.<br/>
-> Install TMRpcm,SD,SPI,SoftwareSerial library from Arduino IDE or from github for interfacing with SD card module for audio messages, for Text Messaging/Calling using SIM800L V2 module.<br/>

* [Circuit Photo](./Circuit%20Photo/)
-> Contains demo circuit diagram, the extact pin connections are not used in the project and in the code.<br/>
-> Its aim is just to show the hardware connection layout for our project.<br/>

* Alert message is the audio message used to alert the driver
* DHT_Library is for interfacing with the Temperature sensor
* [`driverSafetySystem`](./driverSafetySystem.pdf) is the final report of my system.
* Live Project Demonstration: https://youtu.be/lGitoWjo3aw