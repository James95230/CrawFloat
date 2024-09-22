# CrawFloat 

CrawFloat is a device designed for crawfish farmers to monitor environmental factors such as water temperature, depth, and other vital metrics. This floating sensor device allows farmers to easily access real-time data, ensuring optimal conditions for crawfish farming.

## Project Overview
This project involves the use of an ESP32 to collect sensor data and publish it to a GitHub-hosted website. The data collected includes:
- Water Temperature
- Depth Measurements
- pH Level
- O2 Level
- TDS

This repository hosts the code for both the ESP32 device and the static website that displays the sensor data.

## Features
- **Real-Time Monitoring**: Live updates on water temperature, depth, and other metrics.
- **Remote Access**: View data from the farm from anywhere via a web interface.
- **Cost-Effective**: Uses affordable and easy-to-source components.

## How It Works
1. The ESP32 collects data from connected sensors such as temperature, depth, pH, O2, and TDS sensors.
2. The collected data is sent to a cloud database (e.g., Firebase) or directly to the website.
3. The GitHub Pages website fetches the data and displays it for easy monitoring.

## Setup Instructions

### Hardware
1. Set up your ESP32 and connect it to the sensors (temperature, depth, pH, O2, TDS).
2. Power the device and ensure that it is connected to a Wi-Fi network.

### Software
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
2.	ESP32 Code:
Upload the provided ESP32 code to your device using the Arduino IDE or another compatible IDE. Ensure the correct libraries for Firebase and sensor handling are installed.
3.	Website:
o	This repository hosts the static files for the website.
o	Make sure the index.html file correctly points to the Firebase database (or other data source) for fetching the sensor data.
o	Customize the display to suit your needs.
4.	Deploy to GitHub Pages:
o	Push changes to the main branch.
o	Go to your repository settings, and under the "Pages" section, ensure the site is correctly published from the root of the main branch.
Future Enhancements
•	Add additional sensors to monitor other factors like pH levels.
•	Integrate a mobile app for easier access.
•	Expand the project to include other farming-related data.
License
This project is licensed under the MIT License. (To be changed)
