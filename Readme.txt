# DJI Mobile SDK for Android

## What Is This?

The DJI Mobile SDK enables you to automate your DJI Product. You can control flight, and many subsystems of the product including the camera and gimbal. Using the Mobile SDK, create a customized mobile app to unlock the full potential of your DJI aerial platform.

Application Activation
Now, let's create a new project in Android Studio, open Android Studio and select File -> New -> New Project to create a new project, named 'ActivationDemo'. Enter the company domain and package name (Here we use "com.dji.activationDemo") you want and press Next. Set the minimum SDK version as API 18: Android 4.3 (Jelly Bean) for "Phone and Tablet" and press Next. Then select "Empty Activity" and press Next. Lastly, leave the Activity Name as "MainActivity", and the Layout Name as "activity_main", press "Finish" to create the project.

Registering the Application
This demo is build based on the ImportSDKDemo Github Sample, you can check the Integrate SDK into Application tutorial to learn how to import the Android SDK Maven Dependency and register the application using DJI Mobile SDK.

Implementing the UI of Application
Working on the MApplication, DemoApplication and ConnectionActivity