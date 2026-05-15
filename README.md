# Madhu Marga

**Precision Beekeeping Management for Android**

Alternative line: **Smarter paths for healthier hives.**

Madhu Marga is now scaffolded as a native Android app written in Kotlin with Jetpack Compose. It helps beekeepers track hive health, inspections, honey harvests, and local flora from a mobile-first field interface.

## What Is Included

- Native Kotlin Android project
- Jetpack Compose UI
- Dashboard with hive stats, alerts, recommendations, and watchlist
- Hive management screen with health badges and frame-fill meters
- Inspection log screen with queen, pest, and activity details
- Harvest tracking screen with seasonal goal progress
- Flora calendar screen with bloom and nectar guidance
- App icon, Material 3 theme, Gradle wrapper, and local Android SDK config

## Project Structure

```text
.
├── app/
│   ├── build.gradle.kts
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── java/com/madhumarga/app/
│       │   ├── MainActivity.kt
│       │   ├── data/
│       │   │   ├── Models.kt
│       │   │   └── SampleRepository.kt
│       │   └── ui/theme/Theme.kt
│       └── res/
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── gradlew
└── gradlew.bat
```

## Run The App

Open this folder in Android Studio, let Gradle sync, then run the `app` configuration on an emulator or Android device.

Command line build:

```powershell
.\gradlew.bat :app:assembleDebug
```

Debug APK output:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## Tech Stack

- Kotlin
- Jetpack Compose
- Material 3
- Android Gradle Plugin

## Next Steps

- Connect the sample repository to Room or a backend API.
- Add real authentication.
- Add offline sync for field inspections.
- Add camera-based pest and brood image records.
