## Sonar Scanner
**`Arduino-based sonar scanner using an ultrasonic sensor and servo to map surroundings.`**

### 🔍 Overview
This project showcases an Arduino-based sonar scanner designed to detect and measure distances to nearby objects using an ultrasonic sensor (HC-SR04) mounted on a servo motor. The Arduino Uno acts as the central controller, managing the rotation of the sensor and interpreting distance data in real time. As the servo sweeps the sensor across a defined arc, the system captures multiple distance points, effectively monitoring the surroundings for any object. Once an object is spotted, the passive buzzer generates a sound and if the object continues to approach the RGB LED will light up. The data can be displayed on a serial monitor, OLED screen, or sent to a connected PC for visualization. This setup simulates a basic radar system and demonstrates key concepts in robotics, sensor integration, and spatial awareness.

### 🛠️ Components Used
- Arduino UNO: To control the sonar scanning system by reading sensor data, processing it, and triggering the actuator; the servo.
- C++ : The programming language to write the code.
- Passive Buzzer: Used to make a sound whenever an object approaches the ultrasonic sensor.
- RGB LED: Lights up when an object is extremely close to the ultrasonic sensor.
- Ultrasonic Sensor: Measure distances based on transmitting and receiving ultrasonic signals.
- Breadboard: Hosts multiple components and facilitates the creation of a temporary circuit.
- Jumper wires: Connects the different components.
- Resistors: Limits the current flow to prevent damage to components.

### 🎯 Results
The sonar scanner performed reliably in indoor environments, detecting objects at distances ranging from 2 cm to 400 cm with an average accuracy of ±1 cm. The servo motor provided smooth and consistent angular motion, allowing for precise scanning across the designated sweep range (0° to 180°). The system was able to identify the location and relative distance of objects with a good degree of consistency. Minor inaccuracies were observed when thin objects approached the ultrasonic sensor, which is expected because the surface area of the object isn't large enough for enough ultrasonic signals to bounce on. Overall, the project successfully demonstrated the principles of distance sensing and environmental scanning using low-cost components.

