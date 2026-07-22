Cloud-Controlled IoT Rover using AtumX Subo Super Board
Control your robot from anywhere in the world using MQTT and a web browser.

Features
🌍 Control from anywhere using the Internet
☁️ MQTT Cloud Communication
🚗 Real-time WASD Controls
⚡ Adjustable Speed
🌈 RGB LED Matrix Feedback
🔒 Secure TLS Connection
💻 Browser-Based Dashboard
📱 Mobile Friendly
Hardware
AtumX Subo Super Board (ESP32-S3)
2 × BTS7960 Motor Drivers
2 × DC Gear Motors
Robot Chassis
Li-ion Battery

Software
Trix app by AtumX
Arduino IDE
PubSubClient
WiFi
WiFiClientSecure
Subo Library
Folder Structure
Arduino_Code/ Web_Dashboard/ Images/ Documentation/

Wiring
Left Driver
RPWM → GPIO 4

LPWM → GPIO 39

Right Driver
RPWM → GPIO 13

LPWM → GPIO 38
MQTT Topics
Movement

car/control
Commands

F = Forward
B = Reverse
L = Left
R = Right
S = Stop
Speed

V150
Lights

H
Horn

P = Horn ON
O = Horn OFF
Keyboard Controls
W → Forward
A → Left
S → Reverse
D → Right
Space → Stop
H → Headlights
P → Horn
Future Improvements
FPV Camera
Robotic Arm
AI Object Detection
GPS Navigation
Voice Control
Gesture Control
