# Weather Detection Project using Django

## Overview

This project is a weather detection web application built using Django, a high-level Python web framework. It allows users to input a city name and retrieve current weather information such as temperature, humidity, wind speed, and weather condition. The application utilizes the OpenWeatherMap API to fetch real-time weather data.

## Features

- User-friendly interface for entering city names and viewing weather information.
- Real-time weather data retrieval using the OpenWeatherMap API.
- Display of temperature, humidity, wind speed, and weather condition for the specified city.
- User authentication system to allow registered users to save their search history and view it later.
- Responsive design to ensure compatibility across various devices.

## Technologies Used

- **Django**: Python web framework used for backend development.
- **HTML/CSS**: Frontend styling and structure.
- **Bootstrap**: Frontend framework for responsive design and UI components.
- **OpenWeatherMap API**: Used to fetch real-time weather data for specified locations.
- **SQLite**: Default database system provided by Django for storing user data and search history.

## Getting Started

### Prerequisites

- Python 3.12
- Django

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/swayam02072001/weather-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-detection
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Django server:

    ```bash
    python manage.py runserver
    ```

5. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the application.

## Usage

1. Enter the name of a city in the input field on the homepage.
2. Click on the "Search" or "Confirm" button to retrieve weather information.
3. View the current temperature, humidity, wind speed, and weather condition for the specified city.
4. Register and login to save your search history and access it later.

## How to Obtain OpenWeatherMap API Key

To use the OpenWeatherMap API for fetching weather data, you need to obtain an API key. Here's how to get it:

1. Go to the [OpenWeatherMap website](https://home.openweathermap.org/users/sign_up) and sign up for an account if you haven't already.
2. After signing in, go to your [API keys](https://home.openweathermap.org/api_keys) section.
3. Generate a new API key by providing a name for it and clicking on the "Generate" button.
4. Copy the generated API key and paste it into your Django project where you make API requests.

## Acknowledgments

- Special thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- This project was inspired by the desire to create a simple and intuitive weather detection tool using Django.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with any improvements or additional features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
---
