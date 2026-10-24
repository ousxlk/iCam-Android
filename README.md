# iCam Android APK

This repository contains the GitHub Actions workflow for building the original iCam Android project without editing its application source.

## Build the APK

1. Upload the original project archive as **`iCam-native.zip`** at the repository root (the archive should contain the `iCam/` folder).
2. Commit the upload to the `main` branch.
3. Open the **Actions** tab and select **Build iCam APK**.
4. When the workflow succeeds, open the completed run and download the **iCam-debug-apk** artifact. Extract the artifact ZIP to get the APK.

The workflow uses Java 17 and Gradle 8.9. It does not modify the application source.
