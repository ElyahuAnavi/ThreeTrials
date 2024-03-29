# ThreeTrials 🎮

Welcome to the ThreeTrials repository! This project is an Android application that combines three exciting games: Guess the Number, 7 Boom, and Snake, providing a diverse gaming experience.

## Table of Contents 📚

- [Screenshots](#screenshots-)
- [Overview](#overview-)
- [Installation](#installation-)
- [Getting Started](#getting-started-)
- [Contribution](#contribution-)
- [License](#license-)

## Screenshots 📸

<table>
  <tr>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/d1c975b0-c635-4a05-9fd1-b7ed54249d82" width="300" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/7c5f8bf4-8779-47a9-8886-eaef86c60dc8" width="300" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/678a0918-9b78-44b5-b42b-afe03da772f9" width="300" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/3e87ccdc-681c-4808-b90a-bcafa6da5fdb" width="300" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/acaf9aa8-90eb-4f61-99d4-c5b67b82daf2" width="300" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ThreeTrials/assets/137146370/ed5cff04-f9e5-43ab-b7c4-04889ed4dd89" width="300" /></td>
  </tr>
</table>


## Overview 🌟

ThreeTrials is an Android app that bundles together three engaging games, each offering its own unique set of challenges:

1. **Guess the Number** 🧐: Put your logic to the test and guess the secret number within limited tries.
2. **7 Boom** 💥: A game of quick thinking and faster reactions. Identify numbers related to 7 under pressure.
3. **Snake** 🐍: The classic game reimagined. Guide the snake, grow its length, and navigate through increasing difficulty.

## Installation 🛠️

To get started with ThreeTrials, clone this repository and set it up in your Android development environment. Here's a quick setup guide:

- **Compile SDK**: 32
- **Min SDK**: 27
- **Target SDK**: 32

Dependencies are crucial to ensure the smooth running of the app:

```gradle
dependencies {
    // Essential libraries
    implementation 'androidx.appcompat:appcompat:1.4.1'
    implementation 'com.google.android.material:material:1.5.0'
    
    // UI and layout
    implementation 'androidx.constraintlayout:constraintlayout:2.1.3'
    
    // Firebase for authentication and real-time database
    implementation 'com.google.firebase:firebase-auth:21.0.2'
    implementation 'com.google.firebase:firebase-database:20.1.0'
    
    // Testing and debugging
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
    
    // For an appealing splash screen
    implementation 'androidx.core:core-splashscreen:1.0.0'
}
```

## Getting Started 🚀

Download the app on an Android emulator or device to begin exploring the trio of games. Select from the main menu to start your adventure in any of the three games.

## Contribution 🤝

Your contributions can help make ThreeTrials even better! If you have ideas, enhancements, or bug fixes, fork this repository, implement your changes, and submit a pull request. Your input is invaluable.


Jump into the world of ThreeTrials and enjoy a diverse gaming experience!
