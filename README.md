# serial2keyboard
Python script that listens to serial data and pushes virtual keyboard keys. Baudrate is hardcoded to 115200 right now.. deal with it... Thank you to CalPolyUROV for the nifty serial list function [from here](https://github.com/CalPolyUROV/UROV2019/blob/master/raspi/snr/comms/serial/serial_finder.py) 

# requirements if you want to run it with python:
```
pip3 install pynput pyserial
```

# how to run it
Easiest way if you have python installed is to just "python3 serial2keyboard.py [port]"

There's also a binary compiled with pyinstaller for linux, hoping to add more soonish.

The precompiled binaries shouldn't have any extra requirements [TODO: TEST IF THIS IS A LIE].
[This link tells me that i might have a bad time](https://pynput.readthedocs.io/en/latest/limitations.html)
