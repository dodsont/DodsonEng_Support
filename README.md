DodsonEng_Support
=================

Android library for common tasks


THe purpose of thise library is to provide you with one line calls for common android tasks.  See the information below about the functionality available.


This library has 3 classes

AppRater
DodsonEng
JSONParser



AppRater:
AppRater will create a prompt to ask the user to rate the app.  AppRater will wait until the app has been launched 4 times before it asks the user.  This is done so that they the changes of a good rating are more likely if the user has gone back to the app.

This function will also determine if the app has been installed from Google Play or from the Amazon App Store.  It will direct them to the proper one automatically.



DodsonEng:
DodsonEng is a class with general use functions.  This class is designed to help make it easier to  do common Android things such as:

printff() - Print a toast with one line

debugPrintff() - Debug specific toast with one line

GetRandomNumber() - Get a random number passing in the max

isNetworkAvailable() - Check network availability

AppInstalledorNot() - Check if an app is installed on the device



JASONParser:
JSONParser is used to parse JSON into your android app.  This makes an HTTP Call to a back-end server to receive
the JSON data.
