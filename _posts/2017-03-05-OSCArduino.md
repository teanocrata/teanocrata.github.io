---
layout: post
title: OSCArduino - Arduino weather and soil station
category: projects
image: /images/OSCArduino.png
link: https://github.com/ilice/OSCArduino
---

Estación controlada por arduino con varios sensores, alimentada luz solar y baterías que envía cada cierto tiempo datos gracias a una conexión 2G.

Está compuesto a su vez por varios subproyectos para trabajar por separado con el GPRS (conexión a internet gracias a una tarjeta SIM mediante conexión 2G), los sensores o el WIFI en el caso de usar una placa [Arduino Yún](https://www.arduino.cc/en/Main/ArduinoBoardYun)

## Code

Todo el código del proyecto está disponible en [el repositorio de Github ilice/OSCArduino](https://github.com/ilice/OSCArduino)

## Goal

El objetivo es contruir una estación que se mantenga sola gracias a la luz solar y que cada cierto tiempo envie los datos que recoja de los sensores mediante una tarjeta SIM con el mínimo gasto de datos. Inicialmente la carcasa de la estació es MrPotato ;P

Básicamente envía datos a un endpoint, he probado con varias opciones desde una DynamoBD en AWS hasta Web Service con Google Apps Script o simplemente un endpoint de php, dependiendo del momento de otros proyectos :)

## Using...

* [Arduino Languaje](https://www.arduino.cc/en/Reference/HomePage)
* Un poquito de C/C++ y [Processing](https://processing.org/)
* [fritzing](http://fritzing.org/home/) para los esquemas
* [Arduino Uno](https://www.arduino.cc/en/main/arduinoBoardUno) y [Arduino Yun](https://www.arduino.cc/en/Main/ArduinoBoardYun)
* Baterías LiIon
* Placas solares
* Módulo [SIM800L](http://simcomm2m.com/UploadFile/TechnicalFile/SIM800%20Series_AT%20Command%20Manual_V1.09.pdf)
* [Comandos AT para modems gsm](http://simcomm2m.com/UploadFile/TechnicalFile/SIM800%20Series_AT%20Command%20Manual_V1.09.pdf)
* Fotoresistencia, sensor de temperatura, presion, sensor de humedad, etc
* Sodador, estaño, cables y muchas ganas de cacharrear
