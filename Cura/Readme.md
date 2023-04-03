1. Add a new Printer in Cura:

![](AddPrinter.png)

2. With following Printer Settings:

![](PrinterSettings.png)

Use as start GCODE:

> START_PRINT BED={material_bed_temperature_layer_0} HOTEND={material_print_temperature_layer_0}

3. and following Extruder Settings:

![](ExtruderSettings.png)

4. Import profiles at **Preferences->Configure Cura->Profiles** by pressing the Import button
5. Install the Moonraker plugin to communicate with the printer through WIFI. You have to add the Ip Address of the printer in the Moonraker Settings.
