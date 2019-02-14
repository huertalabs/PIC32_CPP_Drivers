# PIC32_CPP_Driver UART example
Basic demo that demonstrates how to use a UART driver. 
Board uses Curiosity PIC32MZ EF. Which contains the PIC32MZ2048EFM100 microprocessor
Open as a project in MPLAB and compile

This demo will tranmit a string in the TX port RPD15 port at baud rate of 115200.
The same string will simultaniously also transmit in port RB3. This uses the U1TX register
After the above mention string gets sent a different string gets transmitted 
in TX port RPC2 at baud rate of 57600. This uses the U2TX register
