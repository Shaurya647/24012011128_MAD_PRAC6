# 24012011128_MAD_PRAC6

## MAD Animation Practical

An Android application developed using Kotlin and XML to demonstrate different types of animations and animation resources.

## Features

- Animated splash screen
- UVPCE logo animation
- Fade transition from splash screen to main screen
- Animated alarm illustration
- Animated heart icon
- Digital clock displaying current time and date
- Alarm button interface
- Material CardView based UI
- ConstraintLayout based screen design

## Technologies Used

- Kotlin
- XML
- Android Studio
- Android SDK
- Material Components
- ConstraintLayout
- AnimationDrawable
- Android Animation API

## Screenshots

### Splash Screen

![Splash Screen](screenshots/splash_screen.png)

### Main Screen

![Main Screen](screenshots/main_screen.png)

## Project Structure

```text
24012011128_MAD_PRAC6/
│
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── com/example/a24012011128_MAD_PR6/
│           │       ├── MainActivity.kt
│           │       └── SplashActivity.kt
│           │
│           └── res/
│               ├── anim/
│               │   └── twin_animation.xml
│               │
│               ├── drawable/
│               │   ├── alarm_animation_list.xml
│               │   ├── heart_animation_list.xml
│               │   ├── uvpce_animation_list.xml
│               │   ├── uvpce_logo.png
│               │   └── animation frame resources
│               │
│               ├── layout/
│               │   ├── activity_main.xml
│               │   └── activity_splash.xml
│               │
│               ├── values/
│               │   ├── colors.xml
│               │   ├── strings.xml
│               │   └── themes.xml
│               │
│               └── xml/
│                   ├── backup_rules.xml
│                   └── data_extraction_rules.xml
│
├── screenshots/
│   ├── splash_screen.png
│   └── main_screen.png
│
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
└── README.md
```

## Animation Details

### Splash Animation

The splash screen uses an animated UVPCE logo with multiple drawable frames. The logo animation is defined using `AnimationDrawable` and the animation resource.

### Main Screen Animations

The main screen contains frame-by-frame animations for:

- Alarm illustration
- Heart icon

The animations are controlled according to the activity lifecycle.

## Digital Clock

The main screen displays a digital clock showing the current:

- Time
- AM/PM
- Day
- Month
- Year

## How to Run

1. Open the project in Android Studio.
2. Wait for Gradle synchronization to complete.
3. Connect an Android device or start an Android emulator.
4. Click the **Run** button.
5. The application will start with the animated splash screen.
6. After the splash animation, the main screen will be displayed.

## Requirements

- Android Studio
- Android SDK
- JDK
- Android device or emulator
- Minimum SDK: Android 7.0 (API 24)

## Author

**Shaurya Patel**

**Enrollment No.: 24012011128**
