# Setup Kotlin and Standard Jetpack Libraries

The project has Kotlin source files but is missing the Kotlin Gradle plugin configuration. This plan will set up the Kotlin plugin and add common Jetpack libraries for a robust XML-based Android app.

## Proposed Changes

### [Gradle Configuration]

#### [MODIFY] [libs.versions.toml](file:///C:/Users/devra/AndroidStudioProjects/Demo/gradle/libs.versions.toml)
- Add Kotlin version and plugin definition.
- Add `androidx.lifecycle` dependencies.
- Update existing libraries to stable versions.

#### [MODIFY] [build.gradle.kts (root)](file:///C:/Users/devra/AndroidStudioProjects/Demo/build.gradle.kts)
- Add the Kotlin Android plugin to the top-level plugins block.

#### [MODIFY] [app/build.gradle.kts](file:///C:/Users/devra/AndroidStudioProjects/Demo/app/build.gradle.kts)
- Apply the Kotlin Android plugin.
- Fix `compileSdk` and `targetSdk` to standard stable values (35).
- Add `lifecycle` dependencies to the dependencies block.

## Verification Plan

### Automated Tests
- Run `./gradlew assembleDebug` to verify the project builds successfully.

### Manual Verification
- Check that `MainActivity.kt` no longer shows syntax errors related to missing Kotlin stdlib or plugin.
