# PIC32_CPP_Driver
C++ based peripheral drivers for the PIC32 microprocessor. Baremetal Examples

For the example a PIC32MZ2048EFM100 is being used. This CPU is running at 200MHz.
If you want to use this in your project, and are using a different CPU. Then you 
need to edit line 28 of serial.h and enter your CPU clock speed.

For the PIC32MZ the UART peripheral address starts at 0xBF822000. Check the datasheep
of your microprocessor Usually chapter 22 (universal asynchronous Receiver transmitter) 
for PIC datahseets. Edit line 49 and enter your microprocessors UART address for the first
instance UART1.
