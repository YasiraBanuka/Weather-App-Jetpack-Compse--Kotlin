# Weather App

A simple weather application built with Kotlin, Jetpack Compose, and Material3. This app fetches weather data from an API and displays it in a user-friendly interface.

## Features

- Fetches weather data for a specified city
- Displays city name, temperature, humidity, and weather description
- Supports dynamic theming based on system settings

## Screenshots

![Purple Modern App Instagram Ad](https://github.com/user-attachments/assets/6ff9e772-7654-4268-9fbe-fe613884207c)


## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/YasiraBanuka/weather_app.git
    ```
2. Open the project in Android Studio.
3. Build the project to download all dependencies.

## Usage

1. Run the app on an emulator or a physical device.
2. Enter the name of a city in the text field.
3. Click the "Check Weather" button to fetch and display the weather data.

## Project Structure

- `app/src/main/AndroidManifest.xml`: Contains the app's manifest file.
- `app/src/main/java/com/example/weather_app/`: Contains the main Kotlin source files.
- `app/src/main/java/com/example/weather_app/ui/theme/`: Contains the theme-related files.
- `app/src/main/res/`: Contains the resource files like layouts, drawables, and values.

## Dependencies

- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [Material3](https://developer.android.com/jetpack/androidx/releases/compose-material3)
- [Kotlin](https://kotlinlang.org/)

## API

This app uses the OpenWeatherMap API to fetch weather data. You need to provide your own API key in the `MainActivity.kt` file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
