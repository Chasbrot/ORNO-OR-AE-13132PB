# Welcome to the ORNO-OR-AE-13132PB 433MHz codes!

![ORNO power strip image](https://www.orno.pl//files.orno.pl/ean_foto/ORAE13132_5902560328660/ORAE13132_5902560328660_2D_0003_small.png)

## Control codes:
example: <br>
[000FF][FFF01][01] <br>
DIP-SW | PLUG |ON OFF=[10]<br>
You have to open your remote and check the DIP-Switch <br> GND=0 VCC=F
and convert TRIBIT-Code to binary and then to decimal
### TRIBIT
0=00<br>
1=11<br>
F=01

* ### A: 
[FFF01]<br>
ON: 87347
OFF: 87356
* ### B: 
[FFF10]<br>
ON: 87491
OFF: 87500
* ### C: 
[FF100]<br>
ON: 87811
OFF: 87820
* ### D:
[F1F00]<br>
ON: 89347
OFF: 89356
* ### E: 
[1FF00]<br>
ON: 95491
OFF: 95500

Pulselength: 174 microseconds <br>
Protocol: 1

## Usage: 
Use the 433Util library from rc-switch for RPi or Arduino.<br>
Example tutorial: https://tutorials-raspberrypi.de/raspberry-pi-funksteckdosen-433-mhz-steuern/

sudo ./codesend *control_code* pulselength 174 protocol 1

Thanks to https://github.com/tureq80/arduino-UNO-or-Raspberry-PI-RF-433Mhz-ORNO-OR-GB-405/wiki for guidance. <br>
For further details check over there.
