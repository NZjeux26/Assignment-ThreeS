# Assignment-ThreeS
Submitted Assignment Three for 159236.

My Goal was to create a CHIP8 emulator with a BT keyboard for input using Dr Martin Johnson's graphics library, but i had real issues getting anything to work, constant crashing and linbrary issues with BT meant i had to sideline it for another option which was to make a MQTT based Alarm clock. It is under netwoking-alarm, connect to the wifi and then using MQTT explorer subscribe to 159236/alarm and feed the message as YYYY-MM-DD HH:MM the screen will display the current time, received time from MQTT and a countdown timer. Whent he alarm goes off, the screen flashes red and green, and if connected to PIN27 and GND a Buzzer or LEF will flash/sound off.
