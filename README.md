# AIQuizMaster

AIQuizMaster is a complete Kotlin Android app that generates multiple-choice quizzes with the Gemini API. 

**#LANGUAGES**
basically i used kotlin in this project and alsos used google ai studio 

## Add Gemini API Key

Open `local.properties` in the project root and add:

```properties
GEMINI_API_KEY=your_real_gemini_api_key
```

The key is read by Gradle into `BuildConfig.GEMINI_API_KEY` and is not hardcoded in source files.

## Run

1. Open this folder in Android Studio.
2. Let Gradle sync finish.
3. Select an emulator or Android device.
4. Run the `app` configuration.

## Build APK

From Android Studio:

1. Open **Build**.
2. Select **Build Bundle(s) / APK(s)**.
3. Select **Build APK(s)**.

From terminal with JDK 17 available:

```bash
./gradlew :app:assembleDebug
```

The debug APK is generated at `app/build/outputs/apk/debug/app-debug.apk`.
