# Smart BinX – Intelligent Waste Management System

## About
Smart BinX is an AI and IoT-based smart waste segregation system designed 
to automate waste classification at the source level. It uses a webcam to 
capture waste images, classifies them using a Machine Learning model, and 
automatically opens the correct bin compartment using servo motors controlled 
by an ESP32 microcontroller.

## Tech Stack
- **Language:** Python
- **Libraries:** OpenCV, TensorFlow, NumPy
- **Hardware:** ESP32 Microcontroller, Servo Motors, Webcam
- **IDE:** Arduino IDE
- **Communication:** USB Serial / Wi-Fi / Bluetooth

## Waste Categories Detected
- Biodegradable (food scraps, fruit peels, garden waste)
- Recyclable (plastic bottles, aluminum cans, glass, paper)
- Non-Biodegradable (plastic wrappers, thermocol, synthetic packaging)

## How It Works
1. Webcam captures real-time image of waste
2. Python ML model classifies the waste type
3. Result is sent to ESP32 via serial/Wi-Fi
4. ESP32 activates servo motor to open correct bin lid
5. Bin closes automatically after disposal

## Features
- Real-time waste detection using webcam
- ML-based image classification
- Automatic bin lid opening via servo motors
- Supports Wi-Fi and Bluetooth communication
- Reduces manual waste sorting and health risks for sanitation workers

## Project Documentation
[View Full Documentation]https://github.com/joshnachallagali/SmartBinx-Intellligent-Waste-Management/blob/e1c00a04cabd29bc8685490fb765ec494ab2e9db/FINAL%20PROJECT%20DOCUMENTATION-1.pdf)
## Developer
Challagalli Reddy Joshna
B.Tech Computer Science | Aditya College of Engineering
