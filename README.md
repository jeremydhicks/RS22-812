# RS22-812
This is a simple port of rs22812.py, by Don Peterson, to a platform that someone in the 2020s would be developing on.  It allows for simple remote readings from a Radio Shack 22-812 Digital Multimeter to the computer running this script via the RS-232 port.

# How to run
This is a standalone file.  Running the script will launch an infinite loop of readings.  To use it in another script, import the RS22812 class.  All that is required is Python 3 and PySerial.  The environment I used to test the script was Python 3.11.5 with PySerial 3.5.0 on a Windows 11 system.