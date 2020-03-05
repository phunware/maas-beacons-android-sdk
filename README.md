
MaaS Engagement Beacons Library for Android
==============

Version 3.5.7

## Overview 
This is Phunware's Android SDK for the Beacons module. Visit http://maas.phunware.com/ for more details and to sign up.

This library is used along with Phunware Mobile Engagement library. 
https://github.com/phunware/maas-engagement-android-sdk


### Build requirements  
* Android SDK 4.3+ (API level 19) or above 
* Android Support Library 28.0.0

Prerequisites
-------------

Add the following to your `repositories` tag in your top level `build.gradle` file.

 ```XML
 projects {
   repositories {
     ...
     maven {
         url "https://nexus.phunware.com/content/groups/public/"
     }
     ...
   }
 }
 ```

The beacon library can be imported by adding the following to your app's `build.gradle` file
 ```
 implementation('com.phunware.engagement:beacon-location-manager:3.5.7') {
     exclude group: 'com.phunware.engagement', module: 'mobile-engagement'
 }
 ```


Privacy  
-----------  
You understand and consent to Phunware’s Privacy Policy located at www.phunware.com/privacy. If your use of Phunware’s software requires a Privacy Policy of your own, you also agree to include the terms of Phunware’s Privacy Policy in your Privacy Policy to your end users.  
  
Terms  
-----------  
Use of this software requires review and acceptance of our terms and conditions for developer use located at http://www.phunware.com/terms/

