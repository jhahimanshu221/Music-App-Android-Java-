# Music Player App

This Android app is a simple yet functional music player designed to play audio files stored locally on the device. It retrieves audio data from the device's storage and offers basic playback functionality, allowing users to enjoy their music collection effortlessly.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Features

- Allows users to browse and play audio files from their device storage.
- Provides a clean user interface for easy navigation and playback control.
- Supports permissions for accessing audio files and external storage.

## Requirements

- Android device with version 4.1 (Jelly Bean) or higher.
- Permissions required:
  - `android.permission.READ_MEDIA_AUDIO`
  - `android.permission.READ_EXTERNAL_STORAGE`

## Installation

1. Clone or download the repository to your local machine.
2. Open the project in Android Studio.
3. Build and run the app on your Android device or emulator.

## File Structure

- **`AndroidManifest.xml`**: Contains the app's manifest file with permissions and activity declarations.
- **`activity_main.xml`**: Layout file for the main activity.
- **`activity_music_player.xml`**: Layout file for the music player activity.
- **`recycler_item.xml`**: Layout file for each item in the RecyclerView.
- **`AudioModel`**: Class representing the audio model.
- **`MainActivity`**: Java class for the main activity.
- **`MusicListAdapter`**: Adapter class for the RecyclerView.
- **`MusicPlayerActivity`**: Java class for the music player activity.
- **`MyMediaPlayer`**: Custom media player class for managing media player instance and current index.
- **`build.gradle`**: Contains the project's build configuration.

## Dependencies

- `implementation 'androidx.appcompat:appcompat:latest_version'`
- `implementation 'com.google.android.material:material:latest_version'`
- `implementation 'androidx.activity:activity:latest_version'`
- `implementation 'androidx.constraintlayout:constraintlayout:latest_version'`
- `testImplementation 'junit:junit:latest_version'`
- `androidTestImplementation 'androidx.test.ext:junit:latest_version'`

## Usage

- `MyMediaPlayer`: Singleton class for managing the media player instance and the current index of the playing song.





## Screenshots

<div style="display: flex;">
    <img src="Music%20App/1.jpg" width="200" style="margin-right: 20px;">
    <img src="Music%20App/2.jpg" width="200" style="margin-right: 20px;">
    <img src="Music%20App/3.jpg" width="200" style="margin-right: 20px;">
    <img src="Music%20App/4.jpg" width="200">
</div>









