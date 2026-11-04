# WeatherWear

An incomplete Android project scaffold. The repository currently contains top-level Gradle configuration and launcher scripts, but not the application module.

## Current contents

- Android Gradle Plugin 7.2.1 configuration.
- Gradle repository settings and an `include ':app'` declaration.
- Gradle launcher scripts and project properties.

## Build status

**This checkout cannot currently build or run an Android application.** The `app/` module, Android manifest, application source/resources and `gradle/wrapper/` files are missing. No weather or clothing recommendation functionality can be verified from the files committed here.

## To restore the project

1. Restore the original `app/` module, including its build file, manifest, source and resources.
2. Restore Gradle wrapper files compatible with the declared Android Gradle Plugin.
3. Configure the Android SDK locally through Android Studio.
4. Build the restored application and document its actual features and setup requirements.

`local.properties` contains machine-specific SDK settings and should be generated locally rather than committed.
