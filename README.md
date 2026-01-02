ESP32 Fan & Heater Control

This project uses an ESP32 to control a 12V DC fan and heater using PWM and MOSFET switching. A push button is used to switch between fan and heater modes, and a potentiometer controls the PWM duty cycle for speed or power control. A MOSFET (with transistor driver) allows the low-voltage ESP32 to safely control high-power loads.

Hardware: ESP32, N-channel MOSFET, BC547 transistor, 12V DC fan, heater load, SMPS power supply, potentiometer, push button.
Software: Arduino IDE, ESP32 hardware PWM (LEDC).