# Weather App

A simple and clean web application that displays the current weather for a specified city using the OpenWeatherMap API.

## Features

-   Search for weather conditions in any city.
-   Displays current temperature in Celsius.
-   Shows humidity percentage and wind speed.
-   Dynamically updates the weather icon based on the conditions (e.g., clouds, rain, clear sky).
-   Provides user-friendly error messages for invalid city names.
-   Responsive design that works on both desktop and mobile browsers.

## Technologies Used

-   **HTML5:** For the structure of the web page.
-   **CSS3:** For styling the application, including the card layout and responsive design.
-   **JavaScript:** For fetching data from the API and dynamically updating the DOM.
-   **OpenWeatherMap API:** To get the weather data.

## Setup and Usage

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Weather-App.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Weather-App
    ```

3.  **Get an API Key:**
    -   Go to [OpenWeatherMap](https://openweathermap.org/api) and create a free account.
    -   Navigate to the 'API keys' tab and get your API key.

4.  **Add the API Key to your code:**
    -   In the `weather.js` file, replace the placeholder for the `apiKey` with your actual API key.

5.  **Open the application:**
    -   Simply open the `index.html` file in your favorite web browser.

## How It Works

The user enters a city name in the search bar and clicks the search button. JavaScript then sends a request to the OpenWeatherMap API with the city name and your API key. The received JSON data is then parsed and used to update the temperature, city name, humidity, wind speed, and the weather icon on the page. If the city is not found, an error message is displayed.

