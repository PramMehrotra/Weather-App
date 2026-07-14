# Weather Application

This is a simple weather application that fetches real-time weather data for a given city using the OpenWeatherMap API (not)

## Features
- Retrieves current weather conditions
- Displays temperature in Fahrenheit
- Handles invalid city names gracefully

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install dependencies (requires Python 3.x):
   ```bash
   pip install requests
   ```

3. Obtain an API key from OpenWeatherMap:
   - Sign up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up)
   - Get your API key from [API keys section](https://home.openweathermap.org/api_keys)

4. Replace `api_key` in the script with your actual API key:
   ```python
   api_key = 'your_api_key_here'
   ```

## Usage
1. Run the script:
   ```bash
   python weather.py
   ```
2. Enter a city name when prompted.
3. The application will display the current weather and temperature.

## Example Output
```
Enter city: London
The weather in London is: Clear
The temperature in London is: 70ºF
```

## Notes
- Ensure you have an active internet connection.
- The script uses OpenWeatherMap's free API tier, which has rate limits.

## License
This project is licensed under the MIT License.

