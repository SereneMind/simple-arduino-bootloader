# simple-arduino-bootloader
simple arduino bootloader
TO BURN BOOTLOADER IN AVR ATMEGA328P FOLLOW THE PROCEDURE :
THINGS NEED:
1. Two 22pf capacitors
2. one 16mhz crystal
3. atmega328p/atmega328(p dinotes the picopower 328p use in simple arduino for power saving)

PROCEDURE:
1. first of all just connect the arduino to the pc 
2. now open the examples in arduino IDE and open arduinoISP
3.upload it to the arduino
4. disconnect the arduino from the pc
5. make the following circuit as shown in the image "atmegabootloader"
6. now copy the "avrdude.txt" file in the following loacation(dont connect arduino to the pc)
   C:\Program Files (x86)\Arduino\hardware\tools\avr\etc
   and replace the file(make sure that your arduino ide is closed)
7. now open the arduino IDE and connect the arduino to the pc
8. now make the following settings in the arduino IDE
    -tools/boards/arduinomini(atmega328)
    -programmer/arduino as ISP
9. now click the tools/burn bootloader
   and wait 30 seconds...........
Now its done now you can use new atmega328 as normal arduino

TO UPLOAD PROGRAMM TO THE NEW ATMEGA328  FOLLOW THE INSTRUCTIONS :
1. Dettach the older atmega328p from the arduino and attach the new one
2. now write the programm and upload it to the arduino
3.then dettach the new atmega328 from the arduino and place it on the breadboard
4. now see the "atmega328pinout" and connect the pins according to the programm (also connect the crystal and capacitors to the atmega328p
   as shown in figure "crystal and capacitors")
NOW YOU SEE WORKING ATMEGA328 WITHOUT ANY ARDUINO BOARD..................:) :) :)
