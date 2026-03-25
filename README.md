# Weather App (CLI - API Integration)

## Overview
This project is a command-line application built in Python that retrieves real-time weather data from an external API. It demonstrates how to work with APIs, handle HTTP requests, and process JSON data.

## Features
- Get real-time weather information by city
- Displays temperature and weather conditions
- Handles invalid input and API errors

## Technologies
- Python 3
- Requests library
- OpenWeatherMap API
- Visual Studio Code

## Project Structure
- main.py → application logic

## How It Works
The application sends an HTTP request to the OpenWeatherMap API using the city name provided by the user. It then parses the JSON response and displays relevant weather information.

## Setup
1. Get a free API key from OpenWeatherMap
2. Replace `your_api_key_here` in the code
3. Run the script

## Skills Demonstrated
- API integration
- HTTP requests handling
- JSON parsing
- Error handling
- Clean CLI design

## Future Improvements
- Add forecast (next 5 days)
- Support multiple units (Celsius/Fahrenheit)
- Save search history
