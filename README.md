# SmartHomeApp
SmartHomeApp is a full-stack smart home automation project, consisting of:

Android Mobile App:
Allows users to control and monitor smart home devices (lights, curtains, garage door, sensors, etc.), receive real-time notifications, and manage household members. Features include:
User authentication (login, signup, password reset)
Room and device control via a modern UI
Real-time sensor data (temperature, gas, etc.)
Push notifications (e.g., for gas leaks or security alerts)
Face recognition for secure access

Python Backend API:
Provides RESTful endpoints for device control, sensor data management, and user notifications. 

Key features:
Handles commands and sensor updates from the app
Integrates with Firebase for notifications and data storage
Includes a face recognition module for security
Modular structure for easy extension

How it works:
The Android app communicates with the backend API to send commands and receive sensor updates. The backend processes these requests, interacts with smart devices, and sends notifications to users as needed.
