# GRBL-Mega_FE_2560_V1.1f
Updated GRBL files for Futurashop CNC with ATmega2560 micro.
The GRBL-Mega original firmware version is v1.1f.

The procedure is to cut and paste the 3 files (config.h, cpu_map.h and defaults.h) inside the root of original GRBL-Mega project. After that compile and flash the firmware inside the USB board (https://www.futurashop.it/scheda-usb-controller-cnc-ft1290m).

Please after bord flash, restore EEPROM default value with --> $RST=$
If need to invert axis directions, use --> $3=7
...and that's all!!


Change log:
- Default microstep set to 16
- Probe on PF6 port
- No Homing enabled
- and other minor changes!!

For any questions, please refer to www.vincenzogermano.com

