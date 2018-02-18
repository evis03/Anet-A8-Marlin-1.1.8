# Anet-A8-Marlin-1.1.8
Marlin firmare Configuration.h for Anet A8 3D Printer with auto levelling

As above. The Anet A8 board doesn't have enough memory to run Marlin with bileniar bed levelling. This config file simply disables eeprom feedback to the host to free up enough memory for bileniar bed levelling. Extruder steps per mm has also been upped to 105.

#**IMPORTANT**

The Z sensor offsets are not compatible with the default sensor mount! To correct this, before using the file open it in your preferred text editor and adjust the following values:

X_PROBE_OFFSET_FROM_EXTRUDER

Y_PROBE_OFFSET_FROM_EXTRUDER

Instructions on how to enter these values correctly are directly above their #define instruction.
