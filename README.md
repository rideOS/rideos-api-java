# rideOS Java API Bindings

This repository builds the Java API bindings for interacting with our various services.

## Building

This project uses gradle to build. There are two build variants for this repository: one for general Java clients and
one for Android clients. The standard Java bindings depend on `protobuf-java`, whereas the Android bindings depend on
`protobuf-lite`.

To build the Java bindings, run:
```
./gradlew -b build-java.gradle build
```
To build the Android bindings, run:
```
./gradlew -b build-android.gradle build
```

## Running

To use rideOS APIs, you'll first need to create an account on [app.rideos.ai](https://app.rideos.ai/login#lockScreen=signUp).
Once you have an account, you can view your API key on your [profile](https://app.rideos.ai/profile) page. 
The example `curl` commands in this repo assume that you've exported your API key into the `RIDEOS_API_KEY`
environment variable: `export RIDEOS_API_KEY="YOUR_API_KEY"`.


