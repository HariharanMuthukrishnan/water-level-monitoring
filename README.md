**💧 Water Level Monitoring System**

This project is a simple Water Level Monitoring System using an Arduino Uno, Ultrasonic Sensor (HC-SR04), and LED indicators. It measures the water level in a tank and lights up corresponding LEDs (Red, Yellow, Green) based on the current level.


**🔧 Components Used**


**Component	Quantity**
Arduino Uno	1
Ultrasonic Sensor (HC-SR04)	1
Red LED	1
Yellow LED	1
Green LED	1
Resistors (220Ω)	3
Breadboard & Jumper Wires	As required

**⚙️ Working Principle**
The ultrasonic sensor continuously measures the distance between itself and the water surface.

Based on the measured distance:

Red LED turns on if the water level is low.

Yellow LED turns on if the water level is medium.

Green LED turns on if the tank is full.

You can customize the distance thresholds based on your tank size.


**🔌 Circuit Connections**

Ultrasonic Sensor (HC-SR04)

VCC → 5V (Arduino)

GND → GND

Trig → Pin 9

Echo → Pin 10

LEDs
Green LED → Pin 2 (with 220Ω resistor)

Yellow LED → Pin 3 (with 220Ω resistor)

Red LED → Pin 4 (with 220Ω resistor)


**🖥️ Arduino Code**
The Arduino sketch measures water level and switches LEDs accordingly.


**📷 Future Add-ons**
Buzzer for sound alert on low water

LCD Display to show distance in cm

Relay Module for automatic motor control


**📌 Applications**
Overhead tank monitoring

Sump tank water level alerts

Smart irrigation systems

**Simulator link :** https://hariharanmuthukrishnan.github.io/water-level-monitor-simulator/
