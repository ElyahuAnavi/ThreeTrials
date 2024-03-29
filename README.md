# ThreeTrials README 🎮

Welcome to the ThreeTrials repository! This project is an Android application that combines three exciting games: Guess the Number, 7 Boom, and Snake, providing a diverse gaming experience.

## Table of Contents 📚

- [Overview](#overview-)
- [Installation](#installation-)
- [Getting Started](#getting-started-)
- [Contribution](#contribution-)
- [License](#license-)

## Overview 🌟

ThreeTrials is an Android app that includes three different games, each offering unique challenges:

1. **Guess the Number** 🧐: A classic game where players deduce a hidden number.
2. **7 Boom** 💥: Navigate through numbers, marking or avoiding those associated with 7.
3. **Snake** 🐍: Control a growing snake, avoiding obstacles and gaining points.

## Installation 🛠️

Clone this repository and open it in your Android development environment. Here are the main configuration details:

- **Compile SDK**: 32
- **Min SDK**: 27
- **Target SDK**: 32

Dependencies:

```gradle
dependencies {
    // Core and material design
    implementation 'androidx.appcompat:appcompat:1.4.1'
    implementation 'com.google.android.material:material:1.5.0'
    
    // Layout and Firebase
    implementation 'androidx.constraintlayout:constraintlayout:2.1.3'
    implementation 'com.google.firebase:firebase-auth:21.0.2'
    implementation 'com.google.firebase:firebase-database:20.1.0'
    
    // Testing
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
    
    // Splash screen
    implementation 'androidx.core:core-splashscreen:1.0.0'
}
```

## Getting Started 🚀

Run the app on an emulator or device. The main screen lets you choose and play any of the games.

## Contribution 🤝

Feel free to contribute! Fork this repo, make changes, and submit a PR.

Enjoy and feel free to enhance ThreeTrials!
