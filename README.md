# INEX Arduino AVR core addon for INEX's AVR products

INEX Arduino AVR core addon
(Not release, during development still tested!)

[Board support]
ATX-2
POP-X2
POP-7
i-Duino R3B (atmega328pb)
Unicon boatd
POP-XT
POP-168 (RBX-168 robot)
IPST-SE
Uno R3 (atmega328)

[Instruction]
(Remark: Fast intenet connection and lagre files transfer required for this procedure)
Open Arduino, menu File -> Preferences
lookon bottom of page, Addition Boards Manager URL then copy below on field

https://raw.githubusercontent.com/INEXdev/ArduinoAVR/main/package_inex_avr_index.json

click OK, then goto menu Tools -> Board -> Boards Manager
wait for Ardduino check addition URL, then scroll down and looking for "INEX AVR" then click "Install"
sitting back and wait for get files from internet and Installing...

If all Okay, you will get all need file for working witl INEX AVR core products.. Have Fun..

Note for i-Duino R3B
---------------------
After install INEX AVR Board manager , user need to download "iom328pb.h" (above) and copy to Arduino package location,

[for PC Windows]   
%LocalAppData%\Arduino15\packages\arduino\tools\avr-gcc\7.3.0-atmel3.6.1-arduino7\avr\include\avr\

or download https://github.com/INEXdev/ArduinoAVR/raw/main/iom328pb.exe and running patch after Install Board Manager.

[for MacOSX]
... (will be add Later)


