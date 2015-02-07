# OpenCV-Laser-Tracker
Track a laser pointer with OpenCV in Python 
Optionally send laser pointer coordinates via serial to Arduino, to control servos etc.

* Python 2.7.5```(python-2.7.5.msi)```
* OpenCV 2.4.5```(OpenCV-2.4.5.exe)```
* pySerial 2.7```(pyserial-2.7.win32.exe)```- Optional

## Quick Start
Must have USB or laptop webcam connecte
```python track_laser.py```

## Use with Arduino
* Remove comments from lines ```10``` and ```180```
* Replace ```COM16``` with your Arduino device port
* Upload ```ArduinoParser.ino``` sketch to Arduino and keep cable connected to computer
* Run ```python track_laser.py```
