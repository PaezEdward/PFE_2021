	*** OLIMEX demo project for the STM32-P207 and STM32-P407 ***

1. Requirements
	- STM32-P207 or STM32-P407 demo board by Olimex
	- Compatible debugger, for example ARM-JTAG-EW
	- IAR EW v6.30.7

2. Description
	The program demonstrates the functionality of the Samsung E700 camera, the external 512kB SRAM chip and the colour LCD display. The program acts as a very simple and crude video capture device that streams its output to the LCD display. The SRAM is used as a buffer for both the capture and processed image data from the camera.
	
3. How to use this demo
	+ Open the workspace file: ".\STM32-P207_P407_IAR_6.30.7_DEMO_V4_1\STM32-P207_P407_DEMOS.eww" and select the configuration for your processor
	+ Press F7 to compile the project.
	+ Connect the debugger to the PC and to the target board. Supply the board as needed.
	+ Press Ctrl+D to download the executable to the target.
	+ Start debugging (F5)
		
4. Support
	http://www.iar.com/
	http://www.olimex.com/dev/
