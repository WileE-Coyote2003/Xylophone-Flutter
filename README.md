🎵 Xylophone App

A Flutter application that simulates a colorful xylophone instrument. Users can tap different keys to play musical notes and explore basic sound playback functionality.

✨ Features

* Play seven musical notes
* Interactive and colorful user interface
* Real-time audio playback
* Responsive layout
* Beginner-friendly Flutter project

🛠️ Technologies Used

* Flutter
* Dart
* audioplayers ^6.0.0

📦 Dependencies

dependencies:
  flutter:
    sdk: flutter
  audioplayers: ^6.0.0

📂 Project Structure

lib/
└── main.dart
assets/
└── sounds/
    ├── note1.wav
    ├── note2.wav
    ├── note3.wav
    ├── note4.wav
    ├── note5.wav
    ├── note6.wav
    └── note7.wav

🚀 Getting Started

Prerequisites

* Flutter SDK
* Dart SDK
* Android Studio or VS Code

Installation

1. Clone the repository

git clone https://github.com/your-username/flutter-xylophone.git

2. Navigate to the project directory

cd flutter-xylophone

3. Install dependencies

flutter pub get

4. Run the application

flutter run

🔊 Audio Playback

The app uses the audioplayers package to load and play local audio assets.

Example:

final player = AudioPlayer();
await player.play(AssetSource('sounds/note1.wav'));


Developed as a Flutter learning project to explore audio integration and interactive mobile UI development.
