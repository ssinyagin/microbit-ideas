# Automatic aimer with a radar

The Microbit controller is connected to two servo motors and a distance meter, such as VL53L0X time-of-flight infrared sensor.

The bottom servo motor is turning the distance meter, scanning the area. 

The upper servo is controlling the aimer, which can hold a small web camera, or a cannon. 

The sensor is constantly scanning the area, and pointing the aimer to the closest object.

Experiment with various timers and steps. Try adding a small pause after setting a new angle on the sensor servo, and see the effect. 

Additional task: make the scanning speed variable: the sensor moves rapidly across the whole range if it doesn't see anything, and slows down and narrows down the search area as soon as it detects an object.
