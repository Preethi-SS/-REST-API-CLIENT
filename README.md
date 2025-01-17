# REST API CLIENT
# WeatherApp

WeatherApp is a simple Java-based application that fetches and displays the current weather information for a specified city using the OpenWeatherMap API.

## Features
- Fetches real-time weather data for a specified city.
- Displays the following weather details:
  - Temperature (in °C)
  - Feels Like temperature (in °C)
  - Humidity (in %)
  - Weather description (e.g., clear sky, overcast clouds).

## Requirements
- Java Development Kit (JDK) 8 or higher
- OpenWeatherMap API Key
- Internet connection

## How to Run the Project
1. **Clone or Download the Repository**  
   Clone this repository or download the source code into your local environment.

2. **Get an OpenWeatherMap API Key**  
   - Visit [OpenWeatherMap](https://openweathermap.org/).
   - Sign up or log in to your account.
   - Generate an API key.

3. **Set Up the Project**  
   - Open the source file `WeatherApp.java`.
   - Replace the `API_KEY` constant with your OpenWeatherMap API key:
     ```java
     private static final String API_KEY = "your_api_key_here";
     ```

4. **Compile and Run**  
   - Open a terminal or your IDE (e.g., Eclipse, IntelliJ).
   - Compile the program:
     ```bash
     javac WeatherApp.java
     ```
   - Run the program:
     ```bash
     java WeatherApp
     ```

5. **View the Output**  
   The application will display the current weather information for the specified city (default: London) in the console.

## Code Overview
The program consists of the following components:
- **fetchWeatherData(city)**: Sends an HTTP GET request to the OpenWeatherMap API and retrieves weather data in JSON format.
- **displayWeatherData(jsonResponse)**: Parses the JSON response to extract and display weather details.
- **Main Method**: Handles execution flow, error handling, and user interaction.

## Example Output
![image](https://github.com/user-attachments/assets/1ef2017c-4815-4de8-ab37-dda473b554fb)
