This is the source code for MKS Base V1.5 on Anet A8. Small modification has to made on the wiring in order for the product to work with this microcontroler. Please refer to the picture

The original source code was obtained from OSOYOO's Website. However, small modification were made to ensure that the code works for Anet A8 3D Printer

Name of Product:
OSOYOO 2017 Super 3D Printer kit for RepRap Prusa I3 with MKS Base V1.5 Controller Board + 2.8" TFT LCD Touch Screen
 
Link to item
https://www.amazon.com/OSOYOO-MKS-3D-printer-kit/dp/B01J9ZVPZU?th=1

Origianl Source Code
http://osoyoo.com/driver/Marlin-mks12864.rar

Before we begin:
1. This code is for MKS Base V1.5 with 2.8" TFT

Hardware Modification Made:
0. Please follow the instruction given in wiring_diagram.jpg
1. X, Y, and Z MinStop negative pin (black) has to be removed and placed at the middle port
2. PLA fan (Fan 1) wire pin has to be cut off and screw in the PLA Fan slot
* Make sure that you plug in the display to the correct port
** Sample picture of the Anet A8 is included in the source folder (sample_1.jpg, sample_2.jpg)

Software Modification:
1. Plug in the cable to Arduino IDE
2. Select Arduino Mega 2560 Board
3. Download the source code here unzip it
4. In Arduino IDE, File Open > Marlin.ino
5. Compile and upload the code
6. Power cycle the entire unit 
7. Turn it back on and calibrate your machine