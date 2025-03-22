Hand2Text is a wearable device that translates American Sign Language (ASL) gestures into readable text displayed on an OLED screen. It is designed to assist deaf or hard-of-hearing individuals in communicating more easily with those unfamiliar with sign language.

🧠 How It Works
Uses 5 flex sensors to detect finger bends.
Uses an MPU6050 accelerometer/gyroscope to detect hand orientation.
Processes sensor data with an STM32F401 microcontroller.
Recognized gestures are translated into characters and displayed on a 0.96" OLED screen via I2C.
⚙️ Hardware Components
STM32F401 Microcontroller
5x Flex Sensors
1x MPU6050 Accelerometer + Gyroscope
1x OLED Display (I2C, 3.3V)
LiPo Battery + Buck-Boost Converter
Custom glove for mounting sensors
🛠️ Features
Real-time letter recognition from hand gestures
OLED display shows detected characters
Modular code structure for adding more gestures
Power-efficient wearable design
📦 Folder Structure
css
Copy
Edit
/Core                  → STM32 source code  
/Drivers               → Device drivers for sensors  
/Docs                  → Diagrams, block diagrams, visuals  
/main.c                → Main application file  
/README.md             → This file  
🧪 Current Status
✅ Prototype assembled
✅ Initial gestures (A, B, C, P) working
🔧 Final testing and expansion of gesture set in progress
📅 Course Info
UC Davis — EEC 136AB Winter 2025
