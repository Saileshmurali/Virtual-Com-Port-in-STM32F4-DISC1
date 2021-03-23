# Virtual-Com-Port-in-STM32F4-DISC1
This code is for using virtual com port with the discovery board. The program has been configured in a way that everytime the timer overflow occurs, inside the interrupt subroutine, the data is sent via usb cable. Only characters/string can be sent via this mode.
