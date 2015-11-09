
I2C meteorological break-out board
==================================

Introduction
------------
This I2C board uses selected sensors by the WIMEA project. WIMEA-ICT 
Research Component 3 has focus on Automated Weather Station  (AWS) 
development and network densification in Africa. The work is funded 
by Norad. 

The idea is challenge existing technologies in price performance aspect
by using the latest research and products and combining expertise in
various fields.

The work herein describes a break-out board with selected sensors to be
used as an first approximation for prototyping, verification and testing.
The results are open and can be used in various project as well as being 
a starting point for other. The work includes:

* Sensor selection and testing
* PCB design
* Some comparison

The sensor selection
--------------------

* SHT25 (Sensiron)  Temp, RH and via calculation AH, temp dew-point, heat index.
http://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/Humidity/Sensirion_Humidity_SHT25_Datasheet_V3.pdf

* MS5611 (Measurements Specialists) Atmospheric Pressure
http://www.meas-spec.com/downloads/MS5611-01BA03.pdf

* MCP3424 (4 channel. Hi-Res 18-bit ΔΣ ADC with Differential Input)
http://ww1.microchip.com/downloads/en/DeviceDoc/22088b.pdf

The selected sensors are proposed by Joachim Reuder, Björn Pehrson, Robert 
Olsson. Very useful information has come form the paparazzi project and special thanks to Martin Mueller for testing the pressure sensors.


The PCB
--------
The break-out board was designed with the gEDA PCB toolchain. Major components
gschem and pcb. I2C bus is available on many platforms, Arduino, Raspberry Pi and is available on most microcontrollers. Included:

* gEDA schematics and resource files
* gerber files for fabrication
* various pictures

![Component side] (./pictures/board-back.png)


Schematics
-----------
![Component side] (./pictures/dboard-1-schematics.png)


Manufactured & Assembled
------------------------
![Component side] (./pictures/WIMEA-I2C-edited.jpg)


References & Project Site
--------------------------
http://gfi063214.klientdrift.uib.no
