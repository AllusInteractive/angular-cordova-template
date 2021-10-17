# AngularCordovaTemplate

This project is a template project built with [Angular](https://github.com/angular/angular-cli) and [Cordova](https://cordova.apache.org/).

## Prerequisites

* Angular CLI `npm install @Angular/cli`
* Cordova `npm install cordova`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build --prod --aot` to build the angular project. Then to compile the app, run `cordova build` with the correct platform flag. 
E.g. to build for Android, run `cordova build android`.

## Useful Commands

* `cordova platform add` adds the platform of your choice to the project. For example, running `cordova platform add android` adds the Android platform to your project.
* `cordova platform rm` removes any unneeded platforms from your project. For example, running `cordova platform rm android` removes the Android platform.
* `export ANDROID_SDK_ROOT=/home/<USERNAME>/Android/Sdk` If building for android, this sets the ANDROID_SDK_ROOT path for your project. Note, this path shoulkd be where you installed the Android SDK.
* `export JAVA_HOME=/usr/lib/jvm/java-1.11.0-openjdk-amd64` sets the JAVA_HOME path for your project. Note, yours may differ depending where you installed the JDK.
