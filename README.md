# Weather Application

This is a simple weather application that displays current weather information for your current location. It shows the latitude, longitude, address, system time and weather information including temperature, humidity, and weather description.

## ✨ Features

- Displays current latitude and longitude.
- Reverse geo-coded address.
- Current system time.
- Weather information including temperature, humidity, and weather description.

## ⚙️ Installation
1. Clone the repository:

- git clone https://github.com/Dulara-Kavindu/WeatherApp

2. Open the project through Android Studio.

3. Configure API Key:

- Open MainActivity.java.
- Find the line where the API key is required: Call<WeatherResponse> call = service.getCurrentWeather(latitude, longitude, "YOUR_API_KEY");
- Replace "YOUR_API_KEY" with your actual OpenWeatherMap API key.

4.Sync Project with Gradle Files:

- Go to File > Sync Project with Gradle Files.
- Run the Application

5.The application requires the following permissions:

ACCESS_FINE_LOCATION: To get the current location of the device.
INTERNET: To fetch weather data from the OpenWeatherMap API.
ACCESS_NETWORK_STATE: To check network connectivity.

## 🚀 Usage

Open the app on your device.
Press the "Refresh" button to get the current weather information for your location.
The app will display the latitude, longitude, address, system time, and weather information.
