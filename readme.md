# Anet A8 MKS Base V1.5 Mod

This is the source code for MKS Base V1.5 with 2.8" Touch LCD on Anet A8. Small modification has to made on the Anet A8's wiring in order for the printer to work with the microcontroller. Please refer to hardware and software modifications instructions below. I suggest everyone that are new to programming purchase and use the same type and size of LCD display for their modification instead of opting in for different size and technology.

## Product Information

| Info | Description |
|-|-|
| Product Name | OSOYOO 2017 Super 3D Printer kit for RepRap Prusa I3 with MKS Base V1.5 Controller Board + 2.8" TFT LCD Touch Screen |
| Link on Amazon | https://www.amazon.com/OSOYOO-MKS-3D-printer-kit/dp/B01J9ZVPZU?th=1 |
| Link to Original Source Code | http://osoyoo.com/driver/Marlin-mks12864.rar |

### Hardware Modification
Please follow the instruction given in wiring diagram below to wire up your 3D printer to the microcontroller. Make sure that you plug in the display to the correct port and double check the wiring before turning on the printer. X, Y, and Z MinStop negative pin (black) has to be removed from the plastic header and placed at the middle port. PLA fan (Fan 1) wire pin has to be cut off (removed the header) and screw it onto the PLA Fan slot

![](/wiring_diagram.jpg)

### Software Modification
0. Obtain a copy of Arduino 1.5.4 IDE. The latest version of Arduino IDE will not work with the source code. This is how to source code is written by the manufacturer. Old releases of Arduino can be obtained from their website: https://www.arduino.cc/en/Main/OldSoftwareReleases
1. Connect your printer with your computer via USB cable
2. Start your Arduino IDE
3. Select Arduino Mega 2560 Board
4. Download the source code from the repository and unzip it
5. In Arduino IDE, File Open > Marlin.ino
6. Compile and upload the code
7. Power cycle the entire unit 
8. Calibrate your machine

### After Modifications are Completed, perform the steps below
1. Check/Adjust your stepper driver current to .410 volts. You may obtain more information from: http://reprap.org/wiki/Calibration#Motor_Calibration or watch the sample sample adjustment video: https://youtu.be/GNfKZ7o_7PI

### Finished Product
The finished product can be found in the pictures below. The pictures were taken on the moment where I completed my modifications and before I modified my printer to fit those parts.

![](/sample_1.jpg)
![](/sample_2.jpg)