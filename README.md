Arduino-slotcars
================

Arduino slotcars

Using a Noepixel string as a virtual slotcar set.

Requirements

- Arduino Uno or similar
- Neopixel string 
- 5V PSU capable of running the entire string.
- A Neopixel start finish line.

Objectives:

Allow Arduino to dynamically create a track that is different each time the arduino is booted.

Have the track areas to be denoted in different colors ( low illumination - based upon speed of vehicle)

Have the program run a test lap based upon "Schumacher" mode that is capable of lapping the track in the best
time based upon the spee limits of the dynamic track layout. - will vary depending upon the state of the dynamic track created 
This ensures that no 2 tracks are the same or lap times will be the same.

 