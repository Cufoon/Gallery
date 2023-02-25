# Gallery

A tool to test the privacy of your phone, just install the apps in release folder:

- app-release-28.apk
  - this apk is target api 28, which is known as Android 9
- app-release-29-legacy.apk
  - this apk is target api 29, which is known as Android 10
  - but with requestLegacyExternalStorage, scoped storage is disabled
- app-release-29.apk
  - this apk is target api 29, which is known as Android 10
  - scoped storage is enabled
- app-release-33.apk
  - this apk is target api 33, which is known as Android 13
  - the newest offical version of scoped storage
  - but in some bands, photo privacy is not realized
 
 As I know:
 
 - android app target lower than api level 29(not include 29), most of the phone bands had do a good job to protect your photos.
 - android app target higher than api level 29(not include 29), must use scoped storage, but without phone's protect, all of your photos will read by an app with just one permission you granted.
 - android app target api 29, with requestLegacyExternalStorage acts like the first former, otherwise the second former.
 - most phone system look audio, photos and videos permission as one(even contain files of other types).
