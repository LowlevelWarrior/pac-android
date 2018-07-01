Welcome to _$PAC Wallet_, a standalone $PAC payment app for your Android device!

This project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __native-scrypt__:
     Native code implementation for Scrypt. The C files are copied from the
     Java Scrypt project at [GitHub](https://github.com/wg/scrypt).
 * __market__:
     App description and promo material for the Google Play app store.
 * __integration-android__:
     A tiny library for integrating $PAC payments into your own Android app
     (e.g. donations, in-app purchases).
 * __sample-integration-android__:
     A minimal example app to demonstrate integration of digital payments into
     your Android app.

You can build all sub-projects at once using Gradle:

`gradle clean build -x test`

Full Guide for building the APK:

`$ git clone https://github.com/PACCommunity/pacj.git `

`$ cd pacj`

`$ git checkout release-0.14`

`$ mvn clean install -DskipTests`

`$ cd ..`

`$ git clone https://github.com/PACCommunity/pac-android.git `

`$ cd pac-android`

`$ git checkout release-4`

`$ gradle clean build -x test`


