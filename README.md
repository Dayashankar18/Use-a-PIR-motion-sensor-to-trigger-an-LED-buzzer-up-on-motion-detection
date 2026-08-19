# Use-a-PIR-motion-sensor-to-trigger-an-LED-buzzer-up-on-motion-detection
**Exp3: Use a PIR motion sensor to trigger an LED/buzzer up on motion detection**

**Aim**
To interface a PIR (Passive Infrared) motion sensor with Arduino UNO and control an LED and buzzer when motion is detected
**Components Required**
•	Arduino UNO 
•	PIR motion sensor (HC-SR501) 
•	LED 
•	220 Ω resistor 
•	Buzzer 
•	Breadboard 
•	Connecting wires 
•	USB cable 
•	Computer with Arduino IDE 

**Circuit Diagram:**

**Procedure**
1.	Connect the PIR sensor to the Arduino UNO: VCC to 5V, OUT to D2, and GND to GND.
2.	Connect the LED to digital pin D13 through a 220 Ω resistor and connect its other terminal to GND.
3.	Connect the buzzer positive terminal to D8 and its negative terminal to GND.
4.	Connect the Arduino UNO to the computer using the USB cable.
5.	Open Arduino IDE, select the Arduino UNO board and the appropriate COM port, and upload the program.
6. Observe the LED and buzzer when movement is made in front of the PIR sensor.

**Arduino IDE Code:**



**Working principle:** 
The PIR sensor detects changes in infrared radiation caused by movement of a person or object. Its output becomes HIGH when motion is detected. Arduino UNO reads this signal through digital pin D2 and turns ON the LED and buzzer.

**Output:**



**Result**
The PIR motion sensor was successfully interfaced with Arduino UNO. The LED and buzzer turned ON when motion was detected and remained OFF when no motion was detected.






