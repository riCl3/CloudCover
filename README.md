# 🌦️📰 CloudCover: Get News of World and Clouds

A sleek and modern Flutter app that gives you **real-time weather updates** and **breaking news headlines**, all in one place. Designed with clean architecture and API integrations, this project is ideal for demonstrating Flutter development, API consumption, and UI structuring.

## 🚀 Features

### 🌤️ Weather Section
- Live weather data fetched using **OpenWeatherMap API**
- Location-based temperature, humidity, wind speed, and status
- Clean and user-friendly UI

### 📰 News Section
- Latest news fetched via **NewsAPI**
- Multiple filters like:
  - Apple (by popularity)
  - Tesla (recent)
  - Business in the US
  - TechCrunch headlines
  - Wall Street Journal coverage
- Clickable news cards with titles, images, and links
- Opens news in the browser via `url_launcher`

### 🧭 Navigation
- Integrated **bottom navigation bar** to toggle between:
  - Weather
  - News

## 🛠️ Tech Stack

- **Flutter** (Latest Stable)
- **Dart** Language
- **OpenWeatherMap API** for weather data
- **NewsAPI.org** for news headlines
- **Provider / Riverpod** (optional for state management)
- **Dio or http** for API calls
- **flutter_dotenv** for API key management
- **url_launcher** to open news links in the browser

# Register your .env in pubspec.yaml:
```bash
flutter:
  assets:
    - .env
```

# Load it in main.dart:
```
await dotenv.load(fileName: ".env");
```
# Getting Started
## Clone the repository:
```
git clone https://github.com/your-username/weather-news-app.git
cd weather-news-app
```

## Install dependencies:
```
flutter pub get
```

## Run the app:
```
flutter run
```
