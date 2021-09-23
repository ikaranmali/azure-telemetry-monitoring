# Description 
* A Python utility that show how a device that uses the IoT Plug and Play conventions interacts with either Azure IoT Hub or IoT Central.
* This utility demonstrate how a device that follows the IoT Plug and Play conventions interacts with Azure IoT Hub or IoT Central, to:

  * Send telemetry.
  * Update read-only and read-write properties.
  * Respond to command invocation.

* languages:
  * python
* azure services:
  * azure-iot-hub
  * azure-iot-pnp

## Screens

![0 screen](/screenshots/4.ico)

![1 screen](/screenshots/1.ico) 

![2 screen](/screenshots/3.ico) 

## Configuring the utility

utility use environment variables to retrieve configuration.

* If you are using a connection string to authenticate:
  * set IOTHUB_DEVICE_SECURITY_TYPE="connectionString"
  * set IOTHUB_DEVICE_CONNECTION_STRING="\<connection string of your device\>"

## Installing Requirements
* pip install -r requirements.txt

## Running the instance
* python3 temperature.py

[![Helper Documentation](../../doc/images/docs-link-buttons/azure-documentation.svg)](https://docs.microsoft.com/azure/iot-develop/)

