# Automatic-room-temperature-maintenance
chip programming to work with heater and cooler

electricity consumption:
Microprocessor 2.5W
Socket 50W
LED Display 50W (Optional)
Computer 200 W (But it can be turned off and you don't need to keep it on all the time)
Heater 5 - 1000 W (it all depends on the load)
Gas air cooler 100W

- d0 - This is a sensor
- d1 - This is a heater
- d2 is a gas air cooler
- d3 - This is a display
These things need to be selected on the socket

Line 23 - number 20 - indicates the temperature when the heater should turn on
Line 24 - number 30 - indicates the temperature when cooling should turn on
Line 25 - number 23 - indicates when everything should be turned off
Important! In this case, the temperatures are in degrees Celsius! The code already contains the conversion formula from Kelvin to Celsius
