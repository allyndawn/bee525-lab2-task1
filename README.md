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

## Running

- Connect your Tiva C Series LaunchPad device to your computer with the Device/Debug switch set to Debug
- Open the ADCSWTrigger.uvproj file in Keil uVision
- From the Project menu, click on Rebuild all target files
- From the Flash menu, click on Download
- From the Debug menu, click on Start/Stop Debug Session
- Dismiss the Evaluation Mode dialog, if you get one, by clicking OK
- From the Debug menu, click on Run
- Observe the ADCValue changing every few seconds in the Watch1 panel
- Observe the rapidly flashing (10 Hz) blue LED on the Tiva LaunchPad (near the RESET button)
- When done, from the Debug menu, click on Stop and then Start/Stop Debug Session

