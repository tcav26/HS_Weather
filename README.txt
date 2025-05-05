# Weather Finder Application

A simple front-end web application that fetches and displays the current weather for a user-specified **US zip code** using the OpenWeatherMap API.

Link to Application: https://tcav26.github.io/HS_Weather/

## Features

* Fetches current weather data (temperature, conditions, icon, humidity, wind speed, etc.).
* User-friendly interface to input **US zip codes** (e.g., 90210).
* Displays weather information in a clean, responsive card (including the city name associated with the zip code).
* Includes loading and error states for better user experience.
* Basic validation for 5-digit US zip code format.
* Uses Tailwind CSS for styling.

## How to Run Locally

1.  Clone this repository or download the `index.html` file.
2.  Open the `index.html` file directly in your web browser.
3.  The application will prompt you for an OpenWeatherMap API key upon the first search attempt in a browser session.

## API Key Setup (Important!)

This application requires an API key from OpenWeatherMap to function.

**How to Obtain Your API Key:**

1.  Go to the [OpenWeatherMap website](https://openweathermap.org/).
2.  **Sign Up** for a free account or **Sign In** if you already have one.
3.  Navigate to the **"API keys"** tab in your user dashboard.
4.  You will likely see a default key generated for you. You can use this key, or generate a new one (giving it a descriptive name like "My Weather Project" is recommended).
5.  **Copy** the generated API key (it's a long string of letters and numbers).

**How the Application Uses the Key:**

* The application **does not store your API key in the source code**.
* When you perform your first weather search in a new browser session, the application will **prompt** you to enter the API key you obtained above.
* The key is then stored temporarily in your browser's **`sessionStorage`**. This means the key is kept only for the current browser tab/session and is cleared when the tab is closed. You will need to re-enter it if you close the tab and open the app again.
* **Activation Delay:** Please note that newly generated OpenWeatherMap API keys can sometimes take **a few minutes up to an hour or two** to become active. If you get an "invalid key" error immediately after generating it, please wait a while before trying again.

## Technologies Used

* HTML5
* CSS3 (via Tailwind CSS CDN)
* JavaScript (Vanilla JS)
* [OpenWeatherMap API](https://openweathermap.org/api)

## Project Structure

* `index.html`: Contains the HTML structure, CSS (within `<style>` tags and Tailwind classes), and JavaScript logic.
* `README.md`: This file.

## Group Members

* Tim Cavanagh
* TJ Hanzsche
* Jacob Matthew

