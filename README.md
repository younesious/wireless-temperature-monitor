# Temperature Monitoring System using MLX90614 Infrared Thermometer

This project utilizes an MLX90614 infrared thermometer sensor to measure temperature and display it on a serial monitor. The system is designed to be implemented on a microcontroller platform, providing a simple and efficient solution for temperature monitoring applications.

## Overview

The project consists of the following components:

1. **MLX90614 Infrared Thermometer:** A non-contact temperature sensor that measures the temperature of objects by detecting infrared radiation emitted from them.

2. **Microcontroller Platform:** Utilizes a microcontroller board (e.g., Arduino) to interface with the MLX90614 sensor and process temperature readings.

3. **Serial Communication:** Communicates temperature readings from the microcontroller to a serial monitor for real-time monitoring and data logging.

## Features

- **Temperature Measurement:** Measures and displays object temperatures in both Celsius and Fahrenheit scales.
- **Non-Contact Sensing:** Enables temperature measurement without physical contact with the object, suitable for various applications.
- **Real-Time Monitoring:** Provides continuous temperature monitoring through serial communication with a computer or display device.

## Hardware Requirements

- Microcontroller board (e.g., Arduino Uno, ESP32)
- MLX90614 infrared thermometer sensor
- Connecting wires
- Power source (e.g., USB cable, battery)

## Software Requirements

- Arduino IDE
- Adafruit MLX90614 library

## Setup Instructions

1. **Connect Hardware:** Wire the MLX90614 sensor to the microcontroller according to the pinout specifications. Ensure proper power supply and connections.

2. **Install Libraries:** Install the Adafruit MLX90614 library in the Arduino IDE to enable communication with the sensor. You can install the library through the Arduino Library Manager.

3. **Upload Code:** Copy the provided code (`temperature_monitoring.ino`) to your Arduino IDE and upload it to the microcontroller board.

4. **Monitor Temperature:** Open the serial monitor in the Arduino IDE to view real-time temperature readings in Celsius and Fahrenheit scales.

## Usage

- Ensure that the microcontroller is powered on and properly connected to the MLX90614 sensor.
- Open the serial monitor in the Arduino IDE or any serial communication terminal to view temperature readings.
- Place objects in front of the MLX90614 sensor to measure their temperatures non-invasively.

## Contributing

Contributions to this project are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
