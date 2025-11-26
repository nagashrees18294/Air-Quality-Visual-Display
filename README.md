AQI Monitoring System with OLED Display

This project is an Air Quality Monitoring System using the MQ-135 gas sensor and SSD1306 OLED display. 
It measures air quality and shows the AQI value along with a category label on the OLED display and Serial Monitor.


🛠️ Components Needed

Arduino Uno / Nano / Mega
MQ-135 Gas Sensor
SSD1306 OLED Display (128x64)
Jumper wires
Breadboard (optional)


📌 Features

Measures air quality (CO₂, smoke, NH₃, etc.)
Converts sensor readings to AQI value (0–500)
Displays Sensor Value, AQI, and Category on OLED
Prints data to Serial Monitor …and Serial Plotter
Categorizes AQI as:
Good (0–50)
Moderate (51–100)
Poor (101–500)


⚡ Circuit Connections

Component	Arduino Pin
MQ-135 Analog Out	A0
OLED VCC	5V
OLED GND	GND
OLED SCL	A5 (Uno)
OLED SDA	A4 (Uno)


> Adjust pins if using a different Arduino board.


🔧 How to Run

1. Connect components as per the circuit table above
2. Open Arduino IDE
3. Install required libraries:
Adafruit_SSD1306
Adafruit_GFX
4. Upload the AQI_OLED.ino code
5. Open Serial Monitor at 9600 baud
6. Observe AQI readings on OLED and Serial Monitor


💡 Future Improvements

Integrate Wi-Fi module (ESP8266/ESP32) to log data online
Add mobile notifications for poor air quality
Include temperature and humidity sensor for better AQI accuracy





