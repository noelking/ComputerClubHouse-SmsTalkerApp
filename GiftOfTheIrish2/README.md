CoderDojo @ Computer Club House Conference Dublin 2012
======================================================

The Sms Talker app, was an easy to build application we presented to the delegates showing how with a few lines of code a cool and fun application can be built. To get this application up and running you will need to 

1. Setup your development environment (eclipse and Android SDK) as we did not the day
2. Create a new Android project inside eclipse called GiftOfTheIrish2
3. Set your top level package to be "org.coderdojo.giftoftheirish" (remove the double quotes)
4. Once the project is created unzip the source code into your project making sure you override the existing code.

Setup your development environment (eclipse and Android SDK) as we did not the day
To play, understand and extend this application you should download this code and get it running inside eclipse, the following instructions should help you get started with eclipse and Android development
http://developer.android.com/sdk/installing.html

Create a new Android project inside eclipse called GiftOfTheIrish2
Once you have opened eclipse you can select the File > New > Android Project

The application has simple interface build via the Android Interface builder, this can be accessed and changed by selecting 
res/layouts/main.xml

The text for the application is stored in the
res/values/strings.xml

The project is managed by 4 Java classess all with their own goal
* GiftOfTheIrish2Activity.java - Provides the user interface support, like managing the clicking of the button to turn Sms talking on or off
* SmsWatcher.java - Lisens for the Sms messages to land on your phone
* TalkActivity.java - Does all the talking
* GiftOfTheIrishApplication.java - Handles the full application state enabling a gobal setting for talking turned on or off.