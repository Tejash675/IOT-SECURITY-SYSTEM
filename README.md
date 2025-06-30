# IOT-SECURITY-SYSTEM
COMPANY : CODTECH IT SOLUTIONS

NAME : SINGAMPALLI TEJASH VARDHAN 

INTERN ID : CT04DF1943

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH KUMAR

The **IoT Security System** is a basic Arduino-based project designed to detect changes in light intensity and provide visual alerts using LEDs. This project was built and tested using **Tinkercad**, a free online tool that allows users to simulate electronic circuits and write Arduino code without needing real components. Tinkercad helps beginners understand the working of sensors, microcontrollers, and simple electronic systems in a safe and interactive environment.

This system mainly uses a **Light Dependent Resistor (LDR)** as the sensor. The LDR detects light levels in the surrounding environment. When there is enough light, the system assumes everything is normal. However, when the light level drops (for example, when someone passes in front of the sensor or enters a room), the system identifies it as a possible intrusion or alert condition.

The circuit is built using the following components:

* **Arduino Uno** (main controller)
* **Breadboard** (for connections)
* **LDR** (light sensor)
* **Two LEDs** (Red and Orange)
* **Resistors** (220 ohm for LEDs, 10k ohm for LDR voltage divider)
* **Jumper Wires**

In this setup:

* The LDR is connected between the **5V supply** and **analog pin A0** of the Arduino. A **10k ohm resistor** connects the junction of the LDR and A0 to **GND**, forming a voltage divider.
* The **Red LED** is connected to **Digital Pin 7** through a 220-ohm resistor.
* The **Orange LED** is connected to **Digital Pin 8** through a 220-ohm resistor.
* Power (5V) and GND from the Arduino are connected to the breadboard rails.

The Arduino reads the analog value from the LDR. If the light level is above a certain threshold, it turns on the **orange LED**, indicating normal conditions. If the light level falls below the threshold, the **red LED** turns on, acting as a warning or alert.

This project is a simple example of how IoT systems can monitor environments and respond to changes. It shows how basic sensors and microcontrollers can create useful security systems. The use of Tinkercad makes the development and testing process easier and accessible to students and beginners. This system can be further enhanced by adding Wi-Fi modules or alarms for real-time alerts.
