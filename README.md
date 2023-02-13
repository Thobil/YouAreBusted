<center>

# ”YOU ARE BUSTED”
# Arduino Alarm via Blynk
</center>

## Project Description

In the overall project, we are going to create a movement monitoring system or alarm system. This monitor system can be used for example as a “anti-thef system”. Our Device A will be controlling the proximity sensor and measure the distance of the objects that can go in front of it. 

Device A will be serving as a monitoring system which will raise an alarm if some obstacle is detected closer than 20cm. Alarm message will be sent to the second Device B and lamp will be switched on. At the same time a mobile notification message will be sent to the user and email message.

As a messaging platform will be used Blynk system: (https://blynk.io)

![alt text](./Assets/Blynk.jpg?raw=true)

## How Blynk Works

Blynk was designed for the Internet of Things. It can control hardware remotely, it can display sensor data, it can store data, visualize it and do many other cool things.

There are three major components in the platform:

•	Blynk App - Allows to you create amazing interfaces for your projects using various widgets we provide.

•	Blynk Server - Responsible for all the communications between the smartphone and hardware. You can use our Blynk Cloud or run your private Blynk server locally. It’s open source, could easily handle thousands of devices and can even be launched on a Raspberry Pi.

•	Blynk Libraries - For all the popular hardware platforms - enable communication with the server and process all the incoming and outcoming commands.

Now imagine: every time you press a Button in the Blynk app, the message travels to space the Blynk Cloud, where it magically finds its way to your hardware. It works the same in the opposite direction and everything happens in a blynk of an eye.

![alt text](./Assets/BlynkConnection.png?raw=true)

Here, you can find all the needed information with more detail: https://docs.blynk.cc/

## Components

| Hardware  | Quantity | Description | Image |
|:---------------|:---------------:|:-----|:---:|
|Arduino UNO Wifi Rev 2|2|Device A is the distance monitor and device B is the alarm|![alt text](./Assets/Rev2.png?raw=true)|
|Ultrasonic Distance Sensor - HC-SR04|1|Used for measuring the distance|![alt text](./Assets/Sensor.png?raw=true)|
|Breadboard Generic|2|Generic breadboard for building the circuits|![alt text](./Assets/board.png?raw=true)|
|LED Light|1|Any color (we use red)|![alt text](./Assets/LED.jpg?raw=true)|
|Resistor|1|220 oΩ|![alt text](./Assets/Resistor.png?raw=true)|
|Cable MINI USB for Arduino|1|Used for uploading code to the Arduinos. It is used only during development. Then power supply can be used.|![alt text](./Assets/usbCable.png?raw=true)|
|Jumper Wires (generic) Male to Male|9|Different length|![alt text](./Assets/wires.png?raw=true)|
|9V Power Adapter|2|Use power adapter to locate your Arduino in any location without need connecting to your computer. Alternatively  battery based power supply can be used.|![alt text](./Assets/power.png?raw=true)|

## 	APPS and Online Services

| Application  | Comment |
|:--------------:|:---------------|
|<img src="./Assets/arduino_logo.png"  width="200" height="100" />|Used for developing code for Arduino devices. Arduino IDE will be used to fully control the flow of execution. Note that an alternative solution is to use the web editor but due to issues with librairies it will not be done here.|
|<img src="./Assets/Blynk_logo.png"  width="150" height="50" />|Blynk is a hardware-agnostic IoT platform with white-label mobile apps, private clouds, device management, data analytics, and machine learning. Mobile App installation is strongly recommended.|
|<img src="./Assets/tinkercad.png"  width="150" height="120" />|Plan your circuit online|
|<img src="./Assets/fritzing.png"  width="200" height="50" />|Alternative to Tinkercad for circuit virtual planning and testing. Plan your circuit offline.|

## Blynk Installation

Download **Blynk IoT** NEW App in Appstore or Google Play

 			 

Create New Account in Blynk app.

Blynk app for iOS and Android is the easiest way to build your own mobile app that work with the hardware of your choice. 

Account is needed to save your projects and provide access from any smartphone you have.

☝️Use a valid email address as it will be later used often.

☝️After account creation you will receive an email with very useful links to start with.

☝️Blynk user guides for beginners can be found here: https://docs.blynk.cc/#getting-started
