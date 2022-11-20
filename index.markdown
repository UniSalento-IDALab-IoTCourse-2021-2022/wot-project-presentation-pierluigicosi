---
layout: default
title:IoT project
---

# About

The work performed allows obtaining and managing real-time data from IoT systems, in this case an indoor **real time locating system**,
integrating an intermediate layer for streaming and saving purposes. 
In addition to this, it gives the end user the ability to view such data in a **WebApp** created through a **Building Information Modelling System**, while ensuring access only to authorized parties.

* * *

# Architecture
The architecture developed for the project is shown in the following figure:

<img src="./images/architecture.png" class="centro" alt="" />

## Back-end 
The back-end is composed by:
1. A **locating system** in which data are simulated and sent via MQTT.
2. A **streaming system** in which data are saved in a Kafka cluster accessible through a REST proxy.

The code regarding the backend can be found at:
[Github repo](https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part1-MQTT_Kafka-Cosi).

## Front-end
The front-end is composed by a WebApp with two plugins:
1. **User localization** in the 2d viewer of the building.
2. **RSSI measurements** to see data regarding the BLE Beacons calibration.

The code regarding the frontend can be found at:
[Github repo](https://github.com/UniSalento-IDALab-IoTCourse-2021-2022/wot-project-part2-BIMdata-Cosi).

* * *

# Demo
This is a video that shows how the WebApp works: