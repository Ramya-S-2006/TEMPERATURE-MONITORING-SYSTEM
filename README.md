# TEMPERATURE-MONITORING-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: RAMYA S

INTERN ID:

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

DESCRIPTION:
This project represents a temperature monitoring system using an Arduino Uno, an LM35 temperature sensor, and a 16x2 LCD display. The LM35 sensor detects the ambient temperature and provides an analog voltage output proportional to the temperature in degrees Celsius. This voltage is read by the Arduino through the analog input pin and then converted into a temperature value. The temperature is displayed in real time on the LCD screen. A potentiometer is used to control the contrast of the LCD display, and appropriate wiring is done to connect all the components through a breadboard.
The Arduino code initializes the LCD display using the LiquidCrystal library, specifying the appropriate digital pins connected to the LCD. In the setup function, the LCD is configured to 16 columns and 2 rows, and a welcome message "Temp Monitor" is displayed for two seconds before clearing the screen. In the loop function, the analog signal from the LM35 sensor is read using analogRead. This raw analog value is converted into voltage using the formula voltage = analogValue * (5.0 / 1023.0), considering the 10-bit ADC resolution and 5V reference. Since the LM35 outputs 10 mV per degree Celsius, the voltage is then multiplied by 100 to obtain the temperature in degrees Celsius. The temperature value is then printed on the LCD along with a degree symbol and the unit "C". The process repeats every second, creating a real-time temperature monitoring system.
This system has several real-life applications. It can be used in home automation to monitor room temperature and activate fans or air conditioning systems accordingly. It is useful in greenhouses and agricultural fields for monitoring environmental conditions that affect plant growth. In industrial applications, this system can be adapted to ensure that machines or equipment do not exceed safe operating temperatures. Additionally, it can be employed in medical refrigerators to ensure vaccines and medications are stored at the correct temperature. This project is a fundamental example of how sensors and microcontrollers can be integrated for real-time environmental monitoring.

#OUTPUT: 
