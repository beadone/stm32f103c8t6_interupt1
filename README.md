# stm32f103c8t6_interupt1
An eclipse project for a STM32f103c8t6 arm system.

sets up two timers to blink pins pb8 and pb9
it is built on the blink and uart1 programs so it will also
initialise the uart1 pins (PB9 and PB10) on an stm32f103c8t6 development board 
and send a message in a continuous loop.
you can use this to help debug your programs 
It also blinks pa13 so you know all is working
this project is built on the PC13 blink program.
 It is the default program when creating a basic "hello world" for the stm32f103.

You can download the whole project and import it into eclipse.
The binary and debug files are also available if you want just 
load a working file to test your device
