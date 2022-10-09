# Introduction

There are a lots of weather application available in Google Play Store. 
But you may want to develop your own weather application in Android Studio. 
Oh, don’t worry, you don’t need to setup a weather station in each city on each country to get weather information in your app. 
There are free APIs available in the market to use them to get weather informations like Temperature, Pressure, Humidity, Weather status, Time of Sunrise and Sunset etc. 
Today in this tutorial I’ll walk you through creating an android weather app using Kotlin in Android Studio.

* That’s my AndroidManifest.xml with the above permission:
  * uses-permission android:name="android.permission.INTERNET" .
  * I have added android:screenOrientation="portrait" .
  * Also I disabled the default Action Bar .
  * We can use Theme.AppCompat.Light.NoActionBar to implement these theme .
