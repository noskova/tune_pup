# TunePup

TunePup is a Flutter application that allows users to download MP3 music from YouTube video links. The app uses `flutter_bloc` for state management and `youtube_explode_dart` for extracting audio streams from YouTube.

## Features

- Download MP3 from YouTube links
- Simple and intuitive user interface
- State management with `flutter_bloc`
- Custom themes and UI components

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: Included with Flutter
- Android Studio or Visual Studio Code: Recommended for development

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/tunepup.git
   cd tunepup
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the app:**
   ```bash
   flutter run
   ```

## Usage

1. Open the YouTube app and find the music you like.
2. Click the three dots and select "Share".
3. Copy the link and paste it into the app's input field.
4. Click "Get the Beat 🎧🐾" to download the MP3.

## Project Structure

- `lib/`: Contains the main application code.
  - `main.dart`: Entry point of the application.
  - `features/downloader/`: Contains the logic for downloading YouTube videos.
  - `app_theme.dart`: Defines the app's theme.

- `android/`: Contains Android-specific files.
- `ios/`: Contains iOS-specific files (if applicable).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Flutter](https://flutter.dev/)
- [youtube_explode_dart](https://pub.dev/packages/youtube_explode_dart)
- [flutter_bloc](https://pub.dev/packages/flutter_bloc)
