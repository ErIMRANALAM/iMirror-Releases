# Install iMirror

1. Download the universal DMG from the [latest GitHub release](https://github.com/ErIMRANALAM/iMirror-Releases/releases/latest).
2. Open the DMG and drag `iMirror.app` into `Applications`.
3. Open iMirror. If ADB is missing, review and accept Google's Android SDK terms, then choose **Download and Set Up**.
4. Connect an Android device over USB with USB debugging enabled, or use the Wi-Fi setup panel. For Android 11 and later, pair through Wireless debugging. For older Android versions, connect by USB once and choose **USB setup** to enable ADB over Wi-Fi.

Requires macOS 14 or later. The DMG includes the iMirror Android agent; it does not include Google's Platform-Tools.

## Verify the download

Compare the DMG's SHA-256 digest with the value shown in the GitHub release notes. On macOS, run:

```sh
shasum -a 256 iMirror-*-macos-universal.dmg
```

## macOS security

Install only a release whose GitHub release notes state that it is signed and notarized. macOS may block an unnotarized download. Do not disable Gatekeeper or use an unnotarized build for general distribution.
