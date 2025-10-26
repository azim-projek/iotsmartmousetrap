🧠 Smart Tikus Trap System

IoT-based automatic rat (tikus) detection and trap activation system using ESP32, ultrasonic sensor, and dual servos.

📘 Description

This project uses an ESP32 microcontroller to detect the presence of a rat using an ultrasonic sensor (HC-SR04).
When the rat is detected within a preset distance, two servos rotate in opposite directions (one clockwise, one counter-clockwise) to activate a mechanical trap.

At the same time, the system sends real-time notifications to Telegram with the exact timestamp using NTP time synchronization.
If the Wi-Fi disconnects, it automatically tries to reconnect and updates the user via Telegram once reconnected.

🧩 Features

✅ Ultrasonic sensor for tikus detection
✅ Dual servo control (CW & CCW rotation)
✅ Automatic Telegram notifications
✅ Time-stamped alerts using NTP server
✅ Auto Wi-Fi reconnection
✅ Compact and fully automated design
