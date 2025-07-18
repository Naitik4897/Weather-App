# Weather App

A responsive weather application built with HTML, CSS, and JavaScript that allows users to check current weather conditions for their location or search for weather in any city.

## Features

- **Current Location Weather**: Get weather information for your current location
- **City Search**: Search for weather information in any city worldwide
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Data**: Fetches live weather data from OpenWeatherMap API

## Demo

[Live Demo](https://weather-app-naitik.vercel.app/) - Check out the live application!

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap API
- Geolocation API

## Getting Started

### Prerequisites

- A modern web browser
- OpenWeatherMap API key (get one from [OpenWeatherMap](https://openweathermap.org/api))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Naitik4897/Weather-App.git
   cd Weather-App
   ```

2. Open `index.html` in your web browser or serve it using a local server.

3. The app will request location access for current weather or you can search for any city.

## API Configuration

The app uses the OpenWeatherMap API. The API key is currently hardcoded in `script.js`. For production use, consider:

- Using environment variables
- Implementing a backend proxy to hide the API key
- Using a secure key management system

## Usage

1. **Your Weather Tab**: Click "Grant Access" to allow location access and get current weather
2. **Search Weather Tab**: Enter a city name to get weather information for that location
3. View detailed weather information including temperature, humidity, wind speed, and cloudiness

## Project Structure

```
weather-app/
├── index.html          # Main HTML file
├── style.css           # Styling
├── script.js           # JavaScript functionality
├── Images/            # Image assets
│   ├── cloud.png
│   ├── favicon.ico
│   ├── humidity.png
│   ├── loading.gif
│   ├── location.png
│   ├── not-found.png
│   ├── search.png
│   └── wind.png
└── README.md          # Project documentation
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Naitik4897 - [GitHub Profile](https://github.com/Naitik4897)

Project Link: [https://github.com/Naitik4897/Weather-App](https://github.com/Naitik4897/Weather-Ap)
