
# Simple Weather App

A simple weather application that fetches and displays real-time weather data using the OpenWeatherMap API. The app allows users to search for weather conditions in any city and displays the temperature, weather description, and high/low temperatures for the day.

 ![Screenshot (63)](https://github.com/user-attachments/assets/f2dbe9b2-c058-43ce-b99a-05a31973556d)


## Features

- Fetches weather data for any city worldwide.
- Displays:
  - Current temperature
  - Weather conditions (e.g., sunny, cloudy)
  - Minimum and maximum temperatures for the day
  - Date and location details
- Fetches weather for a default city on page load (e.g., New York).
- Optionally fetches weather based on user's current location using geolocation.

## Tech Stack

- **HTML5**: For structure and content.
- **CSS3**: For styling and layout.
- **JavaScript**: For dynamic functionality and API integration.
- **OpenWeatherMap API**: For real-time weather data.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/UnknownLoop11/Simple-Weather-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Simple-Weather-App
   ```
3. Open `index.html` in your browser to view the app.

## Project Structure

```
Simple-Weather-App/
├── index.html         # Main HTML file
├── style.css          # Stylesheet for the app
├── main.js          # JavaScript for dynamic functionality
└── README.md          # Project documentation
```

## Setup Instructions

1. Replace the `api.key` in `script.js` with your OpenWeatherMap API key:
   ```javascript
   const api = {
     key: "your-api-key-here",
     base: "https://api.openweathermap.org/data/2.5/"
   };
   ```
2. Open the app in your browser and start searching for weather data!

## Future Enhancements

- Add a responsive design for better mobile compatibility.
- Implement hourly and weekly forecasts.
- Display weather icons alongside descriptions.
- Provide more detailed information, such as humidity and wind speed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Replace `path-to-screenshot.png` with the actual path to your app's screenshots if you have any. Let me know if you want to include additional details!
