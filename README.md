# bee525-lab2-task1

## Target

- Texas Instruments Tiva C Series LaunchPad TM4C123G

## Dependencies

- [Keil uVision 4](https://www.keil.com/demo/eval/armv4.htm)
- [TivaWare 2.1.4.178](http://www.ti.com/tool/SW-TM4C) installed to `C:\ti\TivaWare_C_Series-2.1.4.178`

## Based On

- [ADCSWTrigger_4C123 project by Dr. Valvano](http://users.ece.utexas.edu/~valvano/arm/) - [Direct Link](http://users.ece.utexas.edu/~valvano/arm/ADCSWTrigger_4C123.zip)

## Modifications

- Added TivaWare path for includes
- Added missing NVIC_EN0_INT19 define
- Changed `Use` setting on project options Debug tab from Simulator to `Stellaris ICDI`