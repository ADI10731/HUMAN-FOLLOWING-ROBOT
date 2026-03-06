🤖 Human Following & Bluetooth Controlled Robot








An Arduino-based intelligent mobile robot that can automatically follow a human using sensors and can also be manually controlled using a smartphone via Bluetooth.

This project demonstrates sensor integration, embedded programming, motor control, and wireless communication.

📌 Project Overview

The Human Following Robot is designed to detect and follow a person while maintaining a safe distance. It uses an ultrasonic sensor to measure distance and IR sensors to detect direction. The robot also supports manual control via Bluetooth, allowing the user to control movement through a mobile application.

The system operates in two modes:

🔹 Auto Mode

The robot automatically follows a person using sensor data.

🔹 Manual Mode

The robot is controlled using a smartphone via Bluetooth commands.

⚙️ Features

✔ Human following functionality
✔ Bluetooth mobile control
✔ Ultrasonic distance detection
✔ IR direction tracking
✔ Reverse buzzer alert system
✔ Mode switching button
✔ PWM motor speed control

🧰 Hardware Components
Component	Description
Arduino Uno	Main microcontroller
HC-SR04 Ultrasonic Sensor	Distance measurement
IR Sensors (2)	Direction detection
L298N Motor Driver	Motor control
HC-05 Bluetooth Module	Wireless communication
DC Motors	Robot movement
Robot Chassis	Mechanical structure
Buzzer	Alerts and signals
Push Button	Mode switching
Battery Pack	Power supply
🔌 Circuit Connections
Component	Arduino Pin
Ultrasonic TRIG	Pin 11
Ultrasonic ECHO	Pin 12
IR Right	Pin 2
IR Left	Pin 3
Bluetooth RX	Pin 13
Bluetooth TX	Pin 4
Motor Driver ENA	Pin 5
Motor Driver ENB	Pin 6
Motor Driver IN1	Pin 7
Motor Driver IN2	Pin 8
Motor Driver IN3	Pin 9
Motor Driver IN4	Pin 10
Mode Button	A0
Buzzer	A1
📱 Bluetooth Commands
Command	Action
F	Move Forward
B	Move Backward
L	Turn Left
R	Turn Right
S	Stop
Y	Horn
🧠 Working Principle

Robot checks whether it is in Auto Mode or Manual Mode.

In Auto Mode, ultrasonic sensor measures distance from the human.

IR sensors detect the direction of movement.

Arduino processes sensor data and sends signals to the motor driver.

Motors move the robot to follow the person.

In Manual Mode, commands from a smartphone via Bluetooth control the robot.

📊 Applications

Smart luggage robots

Warehouse automation

Security patrol robots

Hospital assistance robots

Educational robotics systems

🚀 Future Improvements

🔹 AI-based human tracking using camera
🔹 Obstacle avoidance system
🔹 WiFi / IoT control
🔹 Voice control system
🔹 GPS tracking system

💻 Technologies Used

Arduino IDE

Embedded C++

Sensor Interfacing

PWM Motor Control

Bluetooth Communication

👨‍💻 Author

Adithya
Diploma in Electronics and Communication Engineering
R.N. Shetty Polytechnic, Sirsi
Karnataka, India
