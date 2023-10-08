# Climatex
A beautiful and dynamic weather app built using Flutter that fetches real-time weather data from an API and provides a user-friendly interface to display the weather information.
Creating a weather app using Flutter with a dynamic UI involves fetching weather data from an API and presenting it in a visually appealing and interactive manner.

# Weather App with Dynamic UI using Flutter

[![Flutter](https://img.shields.io/badge/Flutter-2.2.3-blue.svg?style=flat)](https://flutter.dev/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A beautiful and dynamic weather app built using Flutter that fetches real-time weather data from an API and provides a user-friendly interface to display the weather information.

## Features

- **Real-time Weather Data**: Get accurate and up-to-date weather data from a reliable API to ensure users get the most recent weather information.

- **Dynamic UI**: The app include Google's Material Design which gives device native UI feature and  adapting to weather conditions, such as sunny, rainy, cloudy, and more.

- **Location-based Forecast**: Fetch weather data based on the user's location, providing hyper-local weather updates.

- **Weather Details**: View detailed weather information such as temperature, humidity and more for the current location.

- **Hourly Forecast**: Provide an hourly weather forecast to keep users informed throughout the day.

- **Weather Icons**: Utilize weather icons to visually represent different weather conditions, improving the user experience.

- **Responsive Design**: Ensure a seamless experience on various devices, including smartphones and tablets.

- **User-friendly Interface**: Create an intuitive and easy-to-use interface for a positive user experience.

## Screenshots
<p float="left">
  <img src="![climateX 1](https://github.com/vikneshsrv24/Climatex-App/assets/97838319/f5a9fe80-29e6-4ebe-bc6a-9a1afd0da884)" width="33%" />
  <img src="![climateX 2](https://github.com/vikneshsrv24/Climatex-App/assets/97838319/81d8e2dc-7640-4f43-b8c4-92bd224fd779)" width="33%" />
  <img src="![climateX 3](https://github.com/vikneshsrv24/Climatex-App/assets/97838319/b35471fc-d9ac-4bfb-89ed-58411971ea4c)" width="33%" />
</p>
## Getting Started

To run this app locally on your machine, follow these steps:

1. Make sure you have [Flutter](https://flutter.dev/) installed on your system.

2. Clone this repository using the following command:

```
git clone https://github.com/vikneshsrv24/ClimateX-app.git
```

3. Navigate to the project directory and fetch the dependencies:

```
cd weather-app
flutter pub get
```

4. Obtain an API key from a weather data provider like OpenWeatherMap,Accuweather and replace `YOUR_API_KEY` in `lib/ui/testing.dart`.

5. Run the app on your preferred device:

```
flutter run
```

## API Used

This app fetches weather data from [OpenWeatherMap API](https://openweathermap.org/api)/[AccuWeather](https://developer.accuweather.com/).

## Libraries Used

- [http](https://pub.dev/packages/http): For making API requests.
- [geolocator](https://pub.dev/packages/geolocator): For obtaining user location.
- [flutter_svg](https://pub.dev/packages/flutter_svg): For displaying SVG weather icons.
- [intl](https://pub.dev/packages/intl): For formatting date and time.
- dynamic_color, flutter_animate, free_place_search, google_nav_bar, home_widget, http, lottie, and sleek_circular_slider

## Contributions

Contributions to this project are welcome! If you find any issues or want to add new features, feel free to open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to use this GitHub description as a starting point for your weather app project using Flutter and a dynamic UI. Adjust the features, APIs, and libraries used to suit your specific implementation. Happy coding!
