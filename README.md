# ESP32_SW
Files for the ESP32 board with a switching regulator.

The ESP32_Sw has a switching regulator to allow operation from 7V to 36V.  The switching regulator regulates the high voltage to 5V that is used to power the LDO that regulates the 3.3V rail for the ESP32.  The 5V output of the switching regulator is available on a pin to power external devices suce as displays or sensors.  The 5V can supply at least 200mA but the maximum current depends on the application and the startup behavior of the external devices.

There are no demonstration programs specific to this module.

Please note that the high voltage input is labeled Vhi.  Applying the high voltage to the Vin pins will destroy the module.  The Vin pins are connected to the input of the LDO, the same as the other ESP32 modules.

The schematic should be used as the master reference for the pinout of the module.
