# medicinereminder

An Android medicine-reminder app (Kotlin). **Status: incomplete.** Only the Gradle project skeleton is committed so far.

## What is in the repository

- `settings.gradle.kts` includes an `:app` module, but there is **no `app/` directory with source code** in this repo yet.
- `build.gradle.kts` in the root contains the *app-module* configuration (application id `com.example.medicinereminder`, minSdk 24, compileSdk 34, view/data binding). It looks like it was uploaded to the root instead of `app/`.
- `proguard-rules.pro` and the Gradle wrapper (`gradlew`, `gradlew.bat`).

Because of this the project cannot be built as it stands.

## Tech stack

Kotlin, Android (minSdk 24, compileSdk 34), Gradle Kotlin DSL.

## Getting started

Not possible yet: the app source (`app/src/...`) and the app-level `build.gradle.kts` need to be added first. Once they are, open the folder in Android Studio and run the `app` configuration.

## Roadmap

- [ ] Add the `app/` module (source, manifest, resources) and move the app build file into it
- [ ] Reminder scheduling and notifications
- [ ] Screenshots

## Author

Mrittunjay Dubey, GitHub [@JayD108](https://github.com/JayD108)

## License

No license file is included yet, so all rights are reserved by default.