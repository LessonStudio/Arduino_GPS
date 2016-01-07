# Arduino_GPS
This ties into the youtube video explaining how to connect a GPS unit to an Arduino

This might be one of the simplest and most satisfying Arduino projects around. All that is needed are four wires, a cheap GPS unit, and an Arduino. 


In this particular example I use the SoftwareSerial library. This then moves the RX, TX off the RX, TX pins on the Arduino. The benefit of this is that the GPS unit can interfere with programming the Arduino via the USB as the TX, RX pins are the same as what is used while uploading a sketch. By moving to different pins this problem goes away. 

Not all pins can be used for SoftwareSerial and it does impose a slight overhead. If memory is tight it is not necessary. 

The accompanying YouTube video is:

https://www.youtube.com/watch?v=09sNLmoJ3HI

Feel free to contact me with any questions or suggestions.