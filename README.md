# Tello-control-with-arduino-nano-33-ble-sense
Controlling dji Tello drone with Arduino nano 33 ble Sense.
Using microcontroller's gesture sensor we are able to fly the drone in 4 directions: UP, DOWN, LEFT, RIGHT.
Python and Arduino code is available.
# Important!
Using the serial port in Python means that we cannot have two programs opened at the same port.
While running the .py program, the serial monitor of Arduino should be closed.
# Files
- the .ino file is the code of detecting gestures from microcontroller
- the gestures_Tello.py file is the python script of controlling the drone from the detected gestures
- the gestures_Tello_v1.1.py is an updated version with UP and DOWN gestures to move the drone up and down
and land after a certain time
