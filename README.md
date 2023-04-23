# somfy-remote
ESP32 (NODEMCU32-S + Ebyte CC1101 Dev. Board) Somfy Remote PCB and Code

![pcb layout](https://github.com/maltezacharias/somfy-remote/blob/main/pcb.png)


    kicad/ - hardware
    esphome/ - esphome files

## PCB

The PCB is double sided and will accept the nodemcu module on one side and the cc1101 module on the other side. 4 Holes are also included for alignment and mounting of the device in a to be desiged 3D printed case.

## Sources

Blog entry explaining the concept
https://www.die-welt.net/2021/06/controlling-somfy-roller-shutters-using-an-esp32-and-esphome/

Somfy ESP-Remote library 
https://github.com/Legion2/Somfy_Remote_Lib

Disclosure of Somfy RTS Protocol
https://pushstack.wordpress.com/somfy-rts-protocol/

Library to drive the CC1101 from ESP32 (includes connection diagrams)
https://github.com/LSatan/SmartRC-CC1101-Driver-Lib
