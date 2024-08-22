# Mobile Weather Station Project

## Overview

This project involves the development of a portable weather station that can be easily transported to different locations to collect environmental data. The station is designed to measure various atmospheric parameters including temperature, humidity, wind speed, wind direction, light intensity, and barometric pressure. The system is powered by a solar panel and utilizes an Arduino Mega microcontroller to interface with the sensors and output devices like a micro-SD card and GSM module. The data collected is stored locally and can be transmitted to a remote server for further analysis.

## Table of Contents

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Components](#components)
- [Methodology](#methodology)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [License](#license)

## Introduction

The mobile weather station is designed to monitor environmental conditions in real-time. It is equipped with a variety of sensors to measure key weather parameters:
- **Temperature**
- **Humidity**
- **Barometric Pressure**
- **Wind Speed**
- **Wind Direction**
- **Light Intensity**
- **Rainfall**

The data is logged to an SD card and can also be transmitted to an online server via a GSM module, making it suitable for deployment in remote locations.

## Objectives

The primary objectives of this project are:
- To build a low-cost, portable weather station.
- To enable data acquisition and storage for further environmental analysis.

## Components

The project uses the following components:
- **Arduino Mega 2560**
- **RTC Module**
- **DHT22 Sensor (Temperature and Humidity)**
- **BMP180 Sensor (Barometric Pressure)**
- **BH1750FVI Sensor (Light Intensity)**
- **Anemometer (Wind Speed)**
- **Wind Vane (Wind Direction)**
- **Rain Gauge**
- **Micro-SD Card Module**
- **GSM Module**
- **Solar Panel**
- **Rechargeable Battery**

## Methodology

The project was developed in several phases:
1. **Sensor Setup**: Each sensor was individually configured and tested.
2. **Integration**: The sensors were integrated into a single system controlled by the Arduino Mega.
3. **Power Supply**: The system is powered by a rechargeable battery that is charged using a solar panel.
4. **Data Handling**: Data is stored on an SD card and can be transmitted to a remote server for monitoring.

### System Diagram

Not provided for confidentiality.

### Assembly

The sensors and components are housed in a weatherproof enclosure mounted on a portable stand. The solar panel is positioned to ensure optimal energy capture. The entire setup is designed to be easily transportable and deployable in various locations.

## Results

The weather station successfully captures and logs data on temperature, humidity, pressure, light intensity, rainfall, wind direction, and wind speed. The data is stored in CSV format on an SD card and can also be sent to an online server for remote access.

## Future Enhancements

Potential future improvements include:
- Utilizing separate microcontrollers for different tasks to reduce data logging delays.
- Implementing a radiation shield for the temperature and humidity sensors.
- Developing a dedicated server for secure data storage.
- Designing a custom PCB for the circuit to enhance reliability.

## Installation

To set up the weather station:
1. **Set Up the Arduino IDE**: Download and install the Arduino IDE.
2. **Install Required Libraries**: Install necessary libraries (`RTClib`, `DHT`, `Adafruit_Sensor`, `Adafruit_BMP085`, `BH1750`, `SD`, `SPI`).
3. **Upload Code**: Load the provided Arduino sketch onto the Arduino Mega.
4. **Connect Components**: Assemble the components as per the connection diagram.
5. **Deploy the Station**: Set up the weather station at the desired location.

## Usage

1. **Start Data Logging**: Power on the station to begin data logging.
2. **Access Data**: Retrieve data from the SD card or monitor it remotely via the server.
3. **Monitor Remotely**: Use the GSM module to send data to the online server for real-time monitoring.

## Contribution

Contributions are welcome! If you want to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your branch.
5. Open a pull request for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
