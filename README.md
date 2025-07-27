This Arduino project is a sonar scanner that uses a servo motor and an ultrasonic sensor (HC-SR04) to detect objects and measure distances in a wide area, as well as displaying the object it scans with a red dot.

How it works:
- The servo motor rotates from left to right (e.g., 0° to 180°)

- At each angle, the ultrasonic sensor measures the distance to the nearest object.

- The distances are then either:
    - Sent to the Serial Monitor for viewing, or
    - Mapped out for a simple radar-style display (if connected to Processing or another visual tool).
 
Hardware Used:
- Arduino Uno (or compatible)

- SG90 Servo Motor

- HC-SR04 Ultrasonic Sensor

- Jumper wires

- Breadboard or sensor mount

Notes:
- You can use Processing to visualize the data like a radar screen
