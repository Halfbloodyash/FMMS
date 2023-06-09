# FMMS
Fish Monitoring System
This project is designed to monitor the temperature and pH level of water in a fish tank and track the movement of fish using a camera and an AI-trained model using TensorFlow Lite. The project is implemented on a Raspberry Pi 3 Model B and uses a DS18B20 temperature sensor and a pH sensor for monitoring the water parameters.

Requirements
Raspberry Pi 3 Model B
DS18B20 temperature sensor
pH sensor
Pi camera module
TensorFlow Lite library
Python 3

Installation
Clone this repository to your Raspberry Pi:
git clone https://github.com/Halfbloodyash/FMMS

Install the required packages:
Copy code
pip install tensorflow-lite
pip install RPi.GPIO

Connect the DS18B20 temperature sensor to the Raspberry Pi as per the circuit diagram .
Connect the pH sensor to the Raspberry Pi as per the circuit diagram provided .
Connect the Pi camera module to the Raspberry Pi.

Troubleshooting
If the temperature or pH readings are not accurate, check the connections of the sensors and ensure that they are calibrated properly.
If the camera feed is not displaying properly or the fish detection is not working, check the connections of the Pi camera module and ensure that the TensorFlow Lite model is properly installed.


License
This project is licensed under the MIT License - see the LICENSE file for details.




