# AR488 Bluetooth Mega 2560
 Source code and KiCad PCB design files for AR488 with Arduino Mega 2560

Firmware is in folder `AR488-firmware`. The Schematic and PCB files are edited with KiCad 6. Gerber Files are compressed in `AR488-Gerber.zip`.

You can find the chips here: [SN75160BN](https://www.mouser.co.uk/ProductDetail/Texas-Instruments/SN75160BN?qs=Dqy2GfToSoSUifmRVz6Aqg%3D%3D) and [SN75161BN](https://www.mouser.co.uk/ProductDetail/Texas-Instruments/SN75161BN?qs=Dqy2GfToSoS%252BO4WL2FUX5A%3D%3D).

The GPIB connector I use: [112-024-213R001](https://www.mouser.co.uk/ProductDetail/NorComp/112-024-213R001?qs=IGgAdOvCTsR9oVdHJ26vTQ%3D%3D). Please note that this is a *female* connector, so you will need a GPIB male-male cable.

Connect JP2, "0" side of JP3 and JP4 as the origin setup. You can change that accordingly with the `AR488_config.h`.

PCB images in KiCad 3D Viewer:
![top](images/AR488-Bluetooth-top.png)

![bottom](images/AR488-Bluetooth-bottom.png)
