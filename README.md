<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />

Distance Based Insult Generator 🎯💀
Basic Details
Team Name: Distance Based Insult Generator
Team Members
Team Lead: ARUN M V – THEJUS ENGINEERING COLLEGE
Member 2: ATHUL KRISHNAN M P – THEJUS ENGINEERING COLLEGE
Project Description
The Distance Based Insult Generator is a funny hardware project that measures how close a person is using an Ultrasonic Sensor. Based on the measured distance, the system generates different funny insults.
The closer you come, the more personal the insult gets. 💀
The project uses an Arduino UNO to process the distance measured by the ultrasonic sensor. Different distance ranges are programmed with different funny messages. The insults can easily be changed by modifying the Arduino code.
It is a completely unnecessary but entertaining combination of Arduino + Ultrasonic Sensor + random insults.
The Problem (that doesn't exist) 🤡
People are getting way too close to us.
There was no existing technology to properly tell someone:
"Bro, why are you standing this close?"
Therefore, we identified a critical problem in society: lack of distance-based insults.
The Solution (that nobody asked for) 🎯
Our system continuously measures the distance between the ultrasonic sensor and a person.
Depending on the distance:
Far away: The system politely ignores you.
Getting closer: It starts questioning your life choices.
Very close: The insults become stronger.
Extremely close: Congratulations, you have entered the danger zone. 💀
The Arduino calculates the distance and sends the corresponding funny message to the computer.
Technical Details
Technologies/Components Used
For Software
Programming Language: C/C++
Microcontroller Programming: Arduino
IDE/Tools: Arduino IDE
Serial Communication: Arduino Serial Monitor
Logic: Distance-based conditional statements (if/else)
For Hardware
Arduino UNO
HC-SR04 Ultrasonic Sensor
Breadboard
Jumper Wires
USB Cable
Computer/Laptop for displaying the generated insults
Hardware Specifications
Arduino UNO
ATmega328P microcontroller
5V operating voltage
Digital input/output pins
USB programming and serial communication
HC-SR04 Ultrasonic Sensor
Ultrasonic distance measurement
Trigger and Echo pins
Approximate measuring range: 2 cm – 400 cm
Breadboard
Used for connecting the ultrasonic sensor to the Arduino without soldering.
Implementation
For Software
The Arduino program:
Sends an ultrasonic pulse using the HC-SR04.
Receives the reflected signal.
Calculates the distance.
Checks the distance against predefined ranges.
Selects an appropriate insult.
Sends the message through the Arduino's Serial connection.
The message can be viewed on a computer through the Serial Monitor.
Example Distance Logic
Distance
System Response
More than 150 cm
"You're finally keeping a safe distance."
100–150 cm
"Why are you coming closer?"
50–100 cm
"Personal space has left the chat."
20–50 cm
"Bro, back up!"
Less than 20 cm
"🚨 TOO CLOSE! Please uninstall yourself."
Installation
Required Software
Install Arduino IDE and connect the Arduino UNO to the computer using a USB cable.
Then:
Open Arduino IDE.
Connect Arduino UNO.
Select Arduino UNO under Board.
Select the correct COM/serial port.
Paste the project code.
Upload the code to the Arduino.
Run
Connect the HC-SR04 to the Arduino UNO through the breadboard.
Connect the Arduino UNO to the computer.
Upload the program.
Open the Serial Monitor.
Set the appropriate baud rate.
Place your hand/person at different distances from the sensor.
Watch the insults change according to the distance. 💀
Project Documentation
For Software
Screenshots
Screenshot 1 – Arduino Code
Shows the Arduino program containing the ultrasonic sensor calculations and distance-based insult conditions.
Screenshot 2 – Serial Monitor
Shows the distance measured by the ultrasonic sensor along with the corresponding funny insult.
Screenshot 3 – Different Distance Responses
Shows how the generated messages change when the distance between the person and the sensor changes.
Diagrams
Workflow
Person/Object → HC-SR04 Ultrasonic Sensor → Arduino UNO → Distance Calculation → Distance Range → Insult Selection → Serial Monitor
This workflow shows how the system measures distance and generates the corresponding insult.
For Hardware
Schematic & Circuit
HC-SR04 → Arduino UNO
HC-SR04 Pin
Arduino UNO
VCC
5V
GND
GND
TRIG
Digital Pin 9
ECHO
Digital Pin 10
The ultrasonic sensor is connected to the Arduino UNO through the breadboard.
Circuit Description
The HC-SR04 ultrasonic sensor sends ultrasonic waves and receives their echo after bouncing off an object. The Arduino UNO calculates the distance using the time taken for the echo to return.
Based on this distance, the Arduino selects an appropriate insult.
Build Photos
Components Shown
Arduino UNO
HC-SR04 Ultrasonic Sensor
Breadboard
Jumper Wires
USB Cable
Computer/Laptop
Build Steps
Place the Arduino UNO and breadboard.
Connect the HC-SR04 ultrasonic sensor to the breadboard.
Connect VCC and GND.
Connect the TRIG pin to Arduino digital pin 9.
Connect the ECHO pin to Arduino digital pin 10.
Connect the Arduino UNO to the computer using USB.
Upload the Arduino program.
Open Serial Monitor.
Test the system by moving closer to and farther from the sensor.
Final Build
The final prototype is a simple distance-detection system that converts physical distance into completely unnecessary insults. 😂
Project Demo
Video
[Add your demo video link here]
What the Video Demonstrates
The video demonstrates the complete working of the Distance Based Insult Generator.
A person approaches the ultrasonic sensor from different distances. The Arduino measures the distance and generates different insults depending on how close the person gets.
Additional Demos
Arduino source code
Circuit diagram
Serial Monitor demonstration
Live hardware demonstration
Team Contributions
ARUN M V – Team Lead
Hardware circuit setup
Arduino UNO and ultrasonic sensor integration
Distance measurement implementation
Testing and debugging
Project demonstration
ATHUL KRISHNAN M P – Member
Arduino programming
Distance-based insult logic
Creating funny insult messages
Software testing
Project documentation and presentation
🎯 One-Line Project Pitch
“The closer you get, the more you get insulted.” 💀
