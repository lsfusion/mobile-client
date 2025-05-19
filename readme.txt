How to run first time:
npm init -y
npm install @capacitor/core @capacitor/cli
npx cap init capacitor-browser org.lsfusion.capacitor
    www
npm install @capacitor/android
npx cap add android
AndroidManifest.xml: add android:usesCleartextTraffic="true"
npx cap sync
npx cap open android
Адчыняецца ў android studio


How to generate apk:

1. In Intellij Idea:
npx cap sync
npx cap open android
It will open android studio

2. In Android Studio:
Build → Generate App Bundles or APKs → Generate APKs
apk is generated in "\android\app\build\outputs\apk\debug\"