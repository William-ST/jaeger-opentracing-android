# jaeger-opentracing-android

## About jaeger-opentracing-android

This app will instantiate a tracer when the button displayed on screen is pressed 
The app then creates a span logs the details of the span generated,
using jaeger-tracer ,the logs for the app displays the working status of span creation
REMARK: This project is under progress.
 

## Getting Started

### Clone the Repository

As usual, you get started by cloning the project to your local machine:

```
$ git@github.com:dexter816/jaeger-opentracing-android.git
```

## Prerequisites
Having gradle 4.0.0 version and android studio latest version with kotlin support

### Open and Run Project in android studio

Now that you have cloned the repo:

1. open the project up in Android Studio .

2. Go to the project and link it with the gradle build the project , and then click on the run app option present on the navigation bar 

3.click on the view option --> Tool Window --> Logcat 

4. press on the click button in the emulator or the android device connected to , the logs will be updated with the span trace creation message and desiably backend jaeger can connect and trace the same 

## Android Version Targeting

App is currently built to work with Android API 24(Nougat).

### Screenshots 
![screenshot logcat](https://github.com/dexter816/jaeger-opentracing-android/blob/master/logxcat.png)

### TODO's

- [ ] fix the connection to jaeger-backend 
- [ ] get a modified version of the HOTROD app that has been implemented in GO to port it in KOTLIN
- [ ] error handling and child span creation 


Please feel free to submit any suggestions or review :) 
