# DJI Mobile SDK for Android



## What Is This?

The DJI Mobile SDK enables you to automate your DJI Product. You can control flight, and many subsystems of the product including the camera and gimbal. Using the Mobile SDK, create a customized mobile app to unlock the full potential of your DJI aerial platform.

 ## Register as a DJI Developer
Register for a DJI Developer account here: http://developer.dji.com/register.

During the registration process, email information and a credit card or phone number will need to be supplied to verify registration. Any credit card information given will only be used for verification and will not be charged.

This guide assumes above Android Studio version 3.1.1.

## Generate an App Key
Every application needs a unique App Key to initialize the SDK.

To create an App Key for an application:

1. Go to the DJI developer Developer Center

2. Select the "Apps" tab on the left.

3. Select the "Create App" button on the right.

4. Enter the name, platform, package identifier, category and description of the application.

5. The package identifier is the Package Name(You can find it in the AndroidManifest.xml file in sample code).

6. An application activation email will be sent to complete App Key generation.

7. The App Key will appear in the developer center, and can be copied and pasted into the application.

Download or clone the Android Sample Github Project from above:

Open the project in Android Studio and paste the generated App Key string into android:value in the "com.dji.sdk.API_KEY" meda-data element in the "AndroidManifest.xml" file.

## Run the Sample App
Compile the sample application to the Android or iOS Mobile Device. Then the Mobile Device can be connected to the DJI product to run the Sample App.

For Aircraft that use Lightbridge as the wireless link between the Remote Controller and the Aircraft, the Mobile Device is connected to the product by USB.

For Aircraft or products that use WiFi as a wireless link, the Mobile Device is connected to the product by WiFi.

## USB Connection Procedure
Mavic Pro, Phantom 4, Phantom 4 Professional, Inspire series, Phantom 3 Professional, Phantom 3 Advanced, M100, M600, M600 Pro:

Turn on the Remote Controller.

Turn on the Aircraft and wait until the Remote Controller has connected with the Aircraft.
Connect iOS/Android Mobile Device to the Remote Controller using a Lightning (iOS) or USB (Android) cable.
Run Sample App on the Mobile Device.

## WiFi Connection Procedure
Phantom 3 Standard, Phantom 3 4K, Spark:

Turn on the Remote Controller.

Connect Mobile Device to the WiFi network created by the Remote Controller.
Turn on the Aircraft and wait until the Remote Controller has connected with the Aircraft.
Run Sample App on the Mobile Device.
Osmo Series, Mavic Pro, Spark:

Turn on the product (Osmo or aircraft).

Connect Mobile Device to the WiFi network created by the product.
Run Sample App on Mobile Device.