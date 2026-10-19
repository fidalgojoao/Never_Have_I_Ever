# Never Have I Ever — Kotlin Android app

The Kotlin rewrite of the Never Have I Ever Android app.

## Requirements

- JDK 17
- Android SDK with API 36
- Gradle 8.13+

## Build

```bash
gradle assembleDebug
```

For a signed release, set `NHI_KEYSTORE_PATH` to the upload-key file and `NHI_STORE_PASSWORD` to its password before running `gradle assembleRelease` or `gradle bundleRelease`.

The app source is in `src/main/kotlin/game/neverhaveiever/MainActivity.kt`. English and Spanish prompt decks are in `src/main/assets/never_have_i_ever_prompts_english.json` and `src/main/assets/never_have_i_ever_prompts_spanish.json`.
