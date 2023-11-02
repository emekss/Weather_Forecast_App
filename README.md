# Weather Forecast App

Welcome to the Weather Forecast App, a Flutter-based application that provides you with up-to-date weather information using a weather data API. With support for both dark mode and light mode themes, this app ensures a pleasant user experience in any lighting condition.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Themes](#themes)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time weather data display.
- Dark mode and light mode themes.
- Current weather conditions (temperature, humidity, wind speed, etc.).
- Five-day weather forecast.
- Location-based weather information (requires location permission).
- Search for weather information by city name or ZIP code.

## Screenshots



https://github.com/emekss/Weather_Forecast_App/assets/110977719/6f930e9b-4f50-4de9-ba35-148dd0ad7e38



## Installation

To run this app, follow these steps:

1. Ensure you have Flutter installed on your system. If not, you can [install Flutter](https://flutter.dev/docs/get-started/install) from the official Flutter website.
2. Clone or download this repository to your local machine.
3. Open a terminal/command prompt and navigate to the project directory.
4. Run the following command to get the required dependencies:
   flutter pub get
5. Connect your mobile device or emulator.
6. Run the app using the following command:

   ```bash
   flutter run
   ```

## Usage

Once the app is installed and running, you can use it to:

- View the current weather conditions for your location.
- Search for weather information in other cities by entering the city name or ZIP code.
- Toggle between light mode and dark mode by accessing the app's settings.
- Access a five-day weather forecast for any location.

## API Integration

This app uses a weather data API to fetch weather information. To integrate your own API, follow these steps:

1. Sign up for a weather API service and obtain an API key.
2. Replace the placeholder in the `lib/config/api_config.dart` file with your API key.

```dart
class ApiConfig {
  static const String apiKey = 'YOUR_API_KEY_HERE';
}
```

3. Ensure that your API provides the necessary endpoints for fetching weather data, including current conditions and five-day forecasts.

## Themes

The app supports both dark mode and light mode. You can switch between these themes by accessing the app's settings.

## Contributing

We welcome contributions to improve this Weather Forecast App. If you have any bug fixes, feature enhancements, or other improvements to suggest, please feel free to submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This Weather Forecast App is open-source and available under the [MIT License](LICENSE).

Thank you for using our Weather Forecast App! We hope you find it helpful and enjoy using it in any lighting condition. If you have any questions or encounter any issues, please don't hesitate to reach out to us.
