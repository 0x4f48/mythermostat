# mythermostat

This project is aiming the followings.

* Getting ESP32 development experiences. What it can do? How easy to develop?
* Learning basics of web application development with node.js.
* Collecting environment data (temperature and humidity) while using the system in my real life.
* Use collected data for learning and exercising ML (machine learning) later.


## Design Concept

* The system is consist of two parts, which are ESP32 based temperature controller (thermostat) and web application running on a host system like RaspberryPi.

[high level design diagram]

### Thermostat

* Measure current temperature and control relays for heater and AC control.
* Once Wi-Fi network is available, it will report environment data to a server.
* The system takes control messages from a server and manages temperature.


### Host Application

* Provide web based control interface to users.
* Collect and store environment data.
* Bridge the data between thermostat and users.


![Device front](https://github.com/0x4f48/mythermostat/blob/main/misc/device-front.jpg)

![Device inside](https://github.com/0x4f48/mythermostat/blob/main/misc/device-inside01.jpg)

![Device inside, level shifter](https://github.com/0x4f48/mythermostat/blob/main/misc/device-inside02.jpg)

![ACDC module](https://github.com/0x4f48/mythermostat/blob/main/misc/ac24-dc5.jpg)


![App login](https://github.com/0x4f48/mythermostat/blob/main/misc/app-login.jpg)

![App main control](https://github.com/0x4f48/mythermostat/blob/main/misc/app-main.jpg)

![App graph](https://github.com/0x4f48/mythermostat/blob/main/misc/app-graph.jpg)


