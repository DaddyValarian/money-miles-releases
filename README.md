# Money Miles — Official Android Releases

This public repository hosts official, permanently signed Android APK releases and release notes. The application source and signing credentials remain private.

No public APK has been published yet. Do not install unofficial copies.

## Publishing updates

1. Build the APK using the private permanently signed workflow and verify its certificate.
2. Publish a GitHub Release here with a signed APK asset named `Money-Miles-vX.Y.Z.apk`.
3. Verify that the APK downloads publicly and installs over the previous app without uninstalling.
4. Only then update `version.json` on `main` with `versionCode`, `versionName`, `downloadUrl`, and `notes` pointing to the verified release asset.

Update manifest URL: `https://raw.githubusercontent.com/DaddyValarian/money-miles-releases/main/version.json`

Never publish the private keystore, signing passwords, source code, or debug APKs. Android requires customer approval to install updates.
