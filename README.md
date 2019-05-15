# Ultra Orienteering Printer

Ultra Orienteering Printer is based on OTIMCON and it is adapted to work with Ultra Orienteering Software.

At the end of race, the participant can get a journal with the route and the timing.

### Description
Hardware consists of:
1. Arduino UNO  ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/Arduino-UNO.jpg">see the image</a> )
2. RFID RC522 ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/rfid-rc522.jpg">see the image</a>  )
3. Pololu Step-Up/Step-Down S18V20F5 ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/sursa-pololu-step-upstep-down.jpg">see the image</a> )
4. Thermal Printer SparkFun ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/Thermal-Printer-SparkFun.jpg">see the image</a> )
5. Battery 12v 5a lead acid ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/Battery-12v-5a-lead-acid.jpg">see the image</a> )
6. Box 265X185X95
7. Vipow BAT1132 Charger for the Battery ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/vipow-bat1132.jpg">see the image</a> )
8. DC 2,1mm DC SOCKET WITH PIPE ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/PRIZA-DC-2-1-MM-5-5-MM-PANOU.jpg">see the image</a> )
9. SWITCH 1x16A ON-OFF ( <a href="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/INTRERUPATOR-1X16A-ON-OFF.jpg">see the image</a> )

It is based on popular orienteering systems, and it's best used for orienteering, trekking, and other sports in which timing on several controls are needed.

### Printer Scheme

<p align="center"><img width=100% src="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/ultraorienteering-printer.jpg"></p>
 
### How to compile
1. Install Arduino IDE from https://www.arduino.cc/en/Main/Software
2. Install the drivers CH341SER for Arduino from Requirements\CH341SER\CH341SER\SETUP.exe
3. Copy the Libraries from Requirements\Libraries to your Documents\Ardiuno folder
4. Open src/otimcon0_2/optimcon0_2.io
5. From Tools select Board: Arduino Nano; Port: select the COM port; verify the code and Upload it.


### How to configure the Printer

<b>IMPORTANT: When you compile, please unplug the  RX / TX pins.</b>

To configure those Check Points use Orientare.exe from CheckPointSoftware\Orientare\bin\Release

Open Orientare.exe and configure your station with MODE > READOUT and press SET to apply.

Remember to select where you want to Save the files on your computer using "File" button or the software will stop running.


### How we made it

<p align="center"><img width=100% src="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/ultraorienteering-printer-1.jpg"></p>

<p align="center"><img width=100% src="https://www.ultra-orienteering.drumetiimontane.ro/download/imagini/ultraorienteering-printer-inside.jpg"></p>