# lsFusion Capacitor

## How to run for the first time
    ```bash
    npm init -y
    npm install @capacitor/core @capacitor/cli
    npx cap init capacitor-browser org.lsfusion.capacitor
    npm install @capacitor/android
    npx cap add android
    ```
    
    Open `AndroidManifest.xml` and add inside `<application>`:
    ```xml
    android:usesCleartextTraffic="true"
    ```

    ```bash
    npx cap sync
    npx cap open android
    ```

    Project will be opened in Android Studio

---

## How to apply changes
    ```bash
    npx cap sync
    npx cap open android
    ```

## How to generate APK

    ```bash
    npx cap sync
    npx cap open android
    ```

    In Android Studio:
    ```
    Build → Generate App Bundles or APKs → Generate APKs
    ```

    APK will be generated in:
    ```
    \android\app\build\outputs\apk\debug\
    ```