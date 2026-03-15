## Overview
One of my earliest projects during college where I integrated a Raspberry Pi with Laravel to create a smart parking simulation. 
The system utilized CNY-70 sensors to monitor real-time slot occupancy and controlled a servomotor to manage gate access based on current availability.
Unfortunately, I couldn't find a photo of the circuit, just this source code an good memories remains.

## Fun fact
In the testing phase, we had to connect the circuit twice, b/c the servomotor didn't open. Connection issues are very common and we never thought it was a software issue.
It turned out to be a section in the code commented. Actually you can still see it in the python/app/parking.py file in **63**. I guess I didn't care to update this repo after the project finished :P
