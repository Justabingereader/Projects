Weather App 🌦️:

A PyQt5-based desktop application that provides weather information for any city using the OpenWeatherMap API.
This app displays the temperature, weather condition, and a corresponding emoji to visually represent the weather.

Features:

🌡️ Displays current temperature in Celsius.
🌦️ Shows weather condition with a descriptive label.
😎 Includes emojis to represent weather conditions.
🖥️ Intuitive GUI with sleek styling.

Requirements:

Before running the app, make sure the following dependencies are installed:
Python (version 3.7 or later)

Required Python libraries:

PyQt5 (for building the GUI)
requests (for making API calls)

Installation
Clone the repository:

git clone https://github.com/yourusername/weather-app.git
cd weather-app
Or you can alternatively navigate to the dist directory and click on the main.exe file to get a one time access to the interface.

Install dependencies:
Run the following command in your terminal to install the required packages:

pip install -r requirements.txt

Alternatively, install them individually:

pip install PyQt5 requests

API Key:

Obtain your API key from OpenWeatherMap and replace the placeholder api_key in the script with your actual key:
api_key = "your_api_key_here"

Usage:

Run the application:

python main.py
Enter a city name in the input box and click the Get Weather button.

The app will display:

The temperature in Celsius.
An emoji representation of the weather.
A short description of the weather condition.
Error Handling

This app gracefully handles various errors, including:

Invalid API key.
Network connection issues.
Non-existent city names.
Server-side issues.
Error messages are displayed in the app's interface to guide the user.

Example:

Input: London

Output:
Temperature: 15.0°C
Emoji: ☁️
Description: overcast clouds

Contributing:

Feel free to contribute by:
Improving the GUI design.
Adding new features like forecast display.
Reporting bugs or suggesting enhancements.


Acknowledgments
OpenWeatherMap: For providing the weather data.
PyQt5 Documentation: For GUI development resources.
