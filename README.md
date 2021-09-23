---

description: "A Python utility that show how a device that uses the IoT Plug and Play conventions interacts with either Azure IoT Hub or IoT Central."
languages:
- python
products:
- azure-iot-hub
- azure-iot-central
- azure-iot-pnp
---

# Using IoT Plug And Play device 

[![Documentation](../../doc/images/docs-link-buttons/azure-documentation.svg)](https://docs.microsoft.com/azure/iot-develop/)

These samples demonstrate how a device that follows the IoT Plug and Play conventions interacts with Azure IoT Hub or IoT Central, to:

- Send telemetry.
- Update read-only and read-write properties.
- Respond to command invocation.

## Screens

![1 screen](/screenshots/1.ico) 

![2 screen](/screenshots/3.ico) 

## Configuring the samples

Both samples use environment variables to retrieve configuration.

* If you are using a connection string to authenticate:
  * set IOTHUB_DEVICE_SECURITY_TYPE="connectionString"
  * set IOTHUB_DEVICE_CONNECTION_STRING="\<connection string of your device\>"

## Installing Requirements
* pip install -r requirements.txt

## Running the instance
* python3 temperature.py
