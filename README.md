# INEX Arduino AVR core addon for INEX's AVR products

Last update :

23 Oct 2022
 : Re-package INEXavr-1.8.5.tar.bz2 for Arduino 2.0.1 support
 
 ** Note for previous user who install old version
 
    You need to Uninstall older 1.8.5 and remove JSON address from Arduino->Preferences first,
    then Close program and Open Arduino then replace new JSON address and OpenBoard Manager again
    
    -> You must see [INEX_AVR by INEX] instead of old [INEX AVR by INEX AVR core boards].
    
    Install again, and it will be OK.
    

17 Jul 2022  
 : update avr-1.8.5.tar.bz2

27 Jan 2022  
 : Add & Fix examples file inside package  
 : move avr-1.8.4.tar.bz2 store location.  

24 Jan 2022  
 : (no need to patch iom328pb.h anymore!)  

INEX Arduino AVR core addon  
work on Arduino IDE 1.8.x https://www.arduino.cc/en/software  
for 64bit Windows user can try new Arduino IDE 2.0 RC
(In development, testing, If any error please inform me at dev[at]inex.co.th)  

# Board support
ATX-2  
POP-X2  
POP-7  
i-Duino R3B (atmega328pb)  
Unicon boatd  
POP-XT  
POP-168 (RBX-168 robot)  
IPST-SE  
Uno R3 (atmega328)  

# USB Driver
for ATX-2, POP-X2, POP-7 and IPST-SE using FTDI chip get driver from https://ftdichip.com/drivers/vcp-drivers  
for i-Duino R3B, Uno R3 using built-in Arduino Uno driver  
for Unicon board, POP-XT using built-in Arduino Leonardo driver

# Instruction
(Remark: Fast internet connection and large files transfer required for this procedure)  
Open Arduino, menu File -> Preferences  
look at the bottom > Addition Boards Manager URL then copy below address on field  

https://github.com/INEXdev/ArduinoAVR/raw/main/package_inex_avr_index.json  

and IMPORTANT! "REMOVE Checkbox "Verify code after upload"
and also disable "Check for updates on startup" keep working on this version.
![alt text](https://github.com/INEXdev/ArduinoAVR/raw/main/EditPreference.png)

click OK, then goto menu Tools -> Board -> Boards Manager  
wait for Arduino check addition URL, then scroll down and looking for "INEX AVR" then click "Install"  
sitting back and wait for get files from internet and Installing...  

If all Okay, you will get all needed file for working with INEX AVR core products.. Have Fun..  
