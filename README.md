# Arduino IoT Sensor Data Logger

This Arduino project is designed to read temperature and electrical conductivity (EC) values from sensors,
displays them on an OLED screen, and sends the data to ThingSpeak for logging and analysis.

## Hardware Requirements

- Arduino board (ESP32)
- Temperature sensor (Dallas Temperature sensor)
- EC sensor module (DFRobot ESP EC)
- OLED display module (SSD1306)

## Dependencies

- Adafruit SSD1306 library
- DallasTemperature library
- DFRobot_ESP_EC library
- Adafruit ADS1X15 library
- WiFi library

## Installation

1. Install the required libraries using the Library Manager in Arduino IDE.
2. Connect the sensors and OLED display to the appropriate pins on your Arduino board.
3. Modify the `apiKey`, `ssid`, and `pass` variables with your ThingSpeak API key and Wi-Fi credentials.
4. Upload the code to your Arduino board.

## Usage

1. Power on your Arduino board.
2. Real-time temperature and EC values will be displayed on the OLED screen.
3. Data will be sent to ThingSpeak for logging and analysis.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
