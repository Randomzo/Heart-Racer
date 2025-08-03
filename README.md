# Heart-Racer
TLDR: Arduino heart rate monitor that displays a message on an I2C screen if the heart rate changes quickly

Aim: Display a prewritten message on a screen for 10 seconds based on how much the heart rate changes over a 10-second period.

Materials Used:
-FREENOVE I2C IIC LCD 1602 Module (ESP32 ESP8266)
-Arduino Uno
-Hailege 5V Heartbeat Detect Sensor Heart Rate (KY-039 )

Procedure: 
Connect all GND to GND
VCC/VDD pins to 5V power
Connect A0 to the sensor’s output.
Connect the Arduino's SDA and SCL pins to the SDA and SCL pins on the I2C screen.
