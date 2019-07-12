# rideOS API

This repository stores the proto interface files for interacting with our various services.

## Building

This project uses gradle to build. You can use the command

```
./gradlew build
```

## Running

To use rideOS APIs, you'll first need to create an account on [app.rideos.ai](https://app.rideos.ai/login#lockScreen=signUp).
Once you have an account, you can view your API key on your [profile](https://app.rideos.ai/profile) page. 
The example `curl` commands in this repo assume that you've exported your API key into the `RIDEOS_API_KEY`
environment variable: `export RIDEOS_API_KEY="YOUR_API_KEY"`.


