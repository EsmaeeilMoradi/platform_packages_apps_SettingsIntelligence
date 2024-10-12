## Clone AOSP platform_packages_apps_SettingsIntelligence
This is the repository to build LineageOS SettingsIntelligence app outside the AOSP source tree using gradle.

To build,

* clone this repo and use Android studio 

## Notes

* I'm not sure if this application will actually run without crashes, I don't want to replace my system SettingsIntelligence with this app. Need to fork SettingsIntelligence and change package names etc.. to make it installable as a separate app.
* Other AOSP based SettingsIntelligence apps might compile with these build scripts too with minimal modifications.
* Bundled lib packages are needed to build the app. `AOSP-android.jar` is the `android.jar` for api 28 with hidden apis bundled, it's extracted from a LineageOS build tree. `aosp-sdk.jar` .
