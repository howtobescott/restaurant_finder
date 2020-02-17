# restaurant_finder

***************************************************************************************************

SCOTT CHU #1570524
SIMON CHEN #1574384
CMPUT275 Wi2020
Major Assignment 1 Part 2

***************************************************************************************************

Included Files:
-a1part1.cpp
-lcd_image.cpp
-lcd_image.h
-Makefile
-README

Setup:
A8 -> JoyStick VRy
A9 -> JoyStick VRx
52 -> JoyStick SW
5V -> JoyStick +5V
GND -> JoyStick GND

Running:
1. Navigate into the directory with all of the included files
2. <make upload>

Description: 
An Arduino program that uses a joystick to navigate around a map of Edmonton. When the joystick is pressed the screen changes to the 20 closeset restaurants to where the cursor was located on the map. User can the select a restaurant and will return to that restaurant on the map. Tapping the screen will then show all of the restaurants that are located near (Blue dots). 

Two buttons are implemented to let the user select which rating (1-5 stars) restaurants they want to see, and also a button to decide which sorting algorithm they want to run (insertion or quick).
Running time for the algorithms are printed in the serial monitor.


