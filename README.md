# Azure IoT Hub client for .NET Micro Framework using a SIM800H

These are sample .NET Micro Framework projects to connect to Azure Iot Hub using a SIM800H module.
They use the SIM800 driver developed by Eclo Solutions and the related Microsoft.Devices.Client port that uses the SIM800H for Internet connection.

The application structure is very straightforward: 
1. setup the SIM800H module
2. setup the client connection to an Azure IoT Hub
3. update RTC from time server
4. send messages to an Azure IoT device (D2C)
5. waits for messages for a device (C2D) 

## Features

* Send and receives data to/from Azure IoT Hub
* HTTPS connection (for HTTP client)
* Same API as the official Microsoft.Devices.Client (we maintain a port compatible with SIM800H)
* 'Standard' Azure IoT connection string

## Folder structure

There are sample projects for:
- HTTP client
- AMQP client (comming soon)

   



Your comments and pull requests are most welcome!