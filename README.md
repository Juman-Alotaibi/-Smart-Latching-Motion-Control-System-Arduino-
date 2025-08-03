# -Smart-Latching-Motion-Control-System-Arduino-
This Arduino project combines a PIR motion sensor and a pushbutton to control a load (via a transistor). The system starts only when the user presses the button, and it stays on as long as motion is detected. If no motion is detected for 30 seconds, the system shuts down automatically.

🔩 Components Used
Arduino Uno
PIR Motion Sensor
Pushbutton
NPN Transistor (e.g., 2N2222 or similar)
2× Resistors (one for button, one for transistor base)
LED (indicator)
Breadboard and jumper wires

⚙️ Functionality
User presses the pushbutton to activate the system.

The transistor is enabled (activating the connected load).

The indicator LED turns on to show system is active.

The PIR sensor continuously monitors for motion.

If motion is detected, the system timer resets.

If no motion is detected for 30 seconds, the system powers down automatically.

🔧 Applications
Energy-saving lighting system

Motion-activated fans or devices

DIY security or monitoring systems

Smart room automation


