
I2C meteorological break-out board
==================================

Introduction
------------
This an I2C board with selected sensors for selected within the RC3 part
of WIMEA project. WIMEA-ICT Research Component 3 Automated Weather Station 
(AWS) development and network densification in Africa. This work is funded
by the Norad. 

The idea is challenge existing technologies in price performance aspect
by using the latest research and products and combining expertise in
various fields.

The work herein describes a break-out board with selected sensors to be
used as an first approximation for prototyping, verification and testing.
The results are open and can be used in various project as well as being 
a starting point for other. Work includes:

* Senors selection and testing.
* PCB design.
* Some comparison.

The selection
-------------

SHT25 (Sensiron)  Temp, RH and via calculation AH, temp dew-point, heat index.
http://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/Humidity/Sensirion_Humidity_SHT25_Datasheet_V3.pdf

MS5611 (Measurements Specialists) Atmospheric Pressure
http://www.meas-spec.com/downloads/MS5611-01BA03.pdf

MCP3424 (4 channel. Hi-Res 18-bit ΔΣ ADC with Differential Input)
http://ww1.microchip.com/downloads/en/DeviceDoc/22088b.pdf

The selected sensors are proposed by Joachim Reuder, Björn Pehrson, 
Robert Olsson also very useful information has come form the paparazzi
project. Special thanks to Martin Mueller for testing pressure sensors.


The board
---------
The break-out board was designed with the gEDA PCB toolchain. Major componetsntsgschem and pcb.



References
-----------
http://129.177.63.214/
