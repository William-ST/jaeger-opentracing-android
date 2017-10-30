# jaeger-opentracing-android
To run the app :
clone this repository and spin it up in android studio preferably,dow
This app will instantiante a tracer when the button displayed on screen is pressed 
The app then creates a span logs the details of the span generated,
using jaeger-tracer ,the logs for the app displays the working status of span creation
This project is under progress : 

TODO:


# Egg &mdash; the Applicasa Sample App for 	Android

This is a sample app provided to show developers what Applicasa looks like in action, and help them see a real example of integrating Applicasa into their applications.

## About jaeger-opentracing-android

This app will instantiante a tracer when the button displayed on screen is pressed 
The app then creates a span logs the details of the span generated,
using jaeger-tracer ,the logs for the app displays the working status of span creation
This project is under progress : 
 
## Raise Custom events:
```
Sample app Introduces the variety of Ad networks, All you need to do is:

A. Go to MainActivity.

B. Set the value of the parameter "customEvent" from the list stated in the activity.

C. Build & Run, and press on the "Raise Promotions" button
```

### What New:
1. Implementation of Android's New In app Billing (ver 3)

### What You Will Find in Egg:
1. Integrating the Applicasa SDK and frameworks for Android
2. Implementing Applicasa's extensive In-App Purchasing support
  * Virtual Currency support &mdash; whereby users use IAP to purchase in-game currency
  * Virtual Goods support &mdash; whereby users use in-game currency to buy virtual items
  * User Inventory &mdash; whereby users can see the virtual items they've purchased
3. Implementing User handling via Applicasa's SDK and Facebook
  * Register new users
  * Login/Logout via Applicasa
  * Login/Logout via Facebook
4. Implementing Promotion handling via Applicasa's Promotion framework
  * Easy-to-use promotions that are triggered by events that happen inside your game
5. Implementing Push Messages 
  * Send user to users push message
  - [] fix the connection to jaeger-backend 
- [] get a modified version of the HOTROD app that has been implemented in GO to port it in KOTLIN
- [] error handling and child span creation 

## Getting Started

### Clone the Repository

As usual, you get started by cloning the project to your local machine:

```
$ git@github.com:dexter816/jaeger-opentracing-android.git
```

## Prerequisites
Have gradle 4.0.0 version and android studio latest version with kotlin support

### Open and Run Project in android studio

Now that you have cloned the repo:

1. open the project up in Android Studio .

2. Go to the project and link it with the gradle build the project , and then click on the run app option present on the navigation bar 

3.click on the view option --> Tool Window --> Logcat 

4. press on the click button in the emulator or the android device connected to , the logs will be updated with the span trace creation message and desiably backend jaeger can connect and trace the same 

## Android Version Targeting

App is currently built to work with Android API 24(Noughat).

### Screenshots 

### TODO's

- [] fix the connection to jaeger-backend 
- [] get a modified version of the HOTROD app that has been implemented in GO to port it in KOTLIN
- [] error handling and child span creation 


Please feel free to submit any suggestions for now 
