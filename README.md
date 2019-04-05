# Kotlin Multiplatform

### Android

`./gradlew android-app:installDebug`

### iOS

`./gradlew build`, then run from XCode targetting a simulator in the Debug Configuration

### Web

npm install required as workaround for issue: https://github.com/JetBrains/kotlin-wrappers/issues/36

```
npm install core-js@2.6.3
./gradlew js-app:run
```

### Desktop

`./gradlew javafx-app:run`

### Server

`./gradlew spring-boot-app:bootRun`
