

# Firebase Core

The `com.google.firebase.core` extension contains the core Firebase components that are required by all Firebase related extensions. 

We have separated this library and made it a common dependency as there are several extensions that rely on these libraries and require a common location in order to avoid conflicts. 

Any extension that uses Firebase will require this extension, in particular:

- [com.distriqt.Firebase collection](http://airnativeextensions.com/extension/com.distriqt.Firebase)
- [com.distriqt.PushNotifications](http://airnativeextensions.com/extension/com.distriqt.PushNotifications)


# Play Core

The `com.google.android.core` extension contains the Google Play Core library which contains libraries to interface with the Google Play Store. Some of the things you can do with Play Core include the following:

- Download additional language resources 
- Manage delivery of feature modules
- Manage delivery of asset packs
- Trigger in-app updates
- Request in-app reviews ()
    - [com.distriqt.ApplicationRater](http://airnativeextensions.com/extension/com.distriqt.ApplicationRater)




# Google Play Services 



The following summarises the functionality in each of the extensions. This is not an exhaustive list but just an indication of where these extensions are used.

Most are directly related to one extension however several are shared amongst multiple extensions and may be in used in more the future. 

You should follow the documentation in the individual extensions to see which depenencies are required.



## Ads

Google Mobile Ads services, 
- [com.distriqt.Adverts](http://airnativeextensions.com/extension/com.distriqt.Adverts)


## Analytics

Google Analytics services:
- [com.distriqt.GoogleAnalytics](http://airnativeextensions.com/extension/com.distriqt.GoogleAnalytics)
- [com.distriqt.GoogleTagManager](http://airnativeextensions.com/extension/com.distriqt.GoogleTagManager)


## Auth

Google Authentication services:
- [com.distriqt.GoogleIdentity](http://airnativeextensions.com/extension/com.distriqt.GoogleIdentity)
- [com.distriqt.GooglePlus](http://airnativeextensions.com/extension/com.distriqt.GooglePlus)
- [com.distriqt.GameServices](http://airnativeextensions.com/extension/com.distriqt.GameServices)
- [com.distriqt.firebase.Auth](http://airnativeextensions.com/extension/com.distriqt.Firebase)


## Base

Base services required by all ANEs using the Google Play Services client library.

This extension provides the Availability API to determine if the Google Play Services are installed on a device:

- [Google API Availability Helper](https://github.com/distriqt/ANE-GooglePlayServices/wiki/API-Availability)




## Drive

Google Drive, used for data saving such as saved games etc:
- [com.distriqt.GameServices](http://airnativeextensions.com/extension/com.distriqt.GameServices)


## Games

Google Play Games:
- [com.distriqt.GameServices](http://airnativeextensions.com/extension/com.distriqt.GameServices)


## GCM

Google Cloud Messaging services:
- [com.distriqt.PushNotifications](http://airnativeextensions.com/extension/com.distriqt.PushNotifications)


## Identity

Google Sign In and Identity services:
- [com.distriqt.GoogleIdentity](http://airnativeextensions.com/extension/com.distriqt.GoogleIdentity)
- [com.distriqt.GooglePlus](http://airnativeextensions.com/extension/com.distriqt.GooglePlus)


## Location

Location services, using GPS and network locations:
- [com.distriqt.Location](http://airnativeextensions.com/extension/com.distriqt.Location)


## Maps

Google Maps services, used to display maps:
- [com.distriqt.NativeMaps](http://airnativeextensions.com/extension/com.distriqt.NativeMaps)


## Plus

Google Plus services:
- [com.distriqt.GooglePlus](http://airnativeextensions.com/extension/com.distriqt.GooglePlus)



## TagManager

Google Tag Manager services:
- [com.distriqt.GoogleTagManager](http://airnativeextensions.com/extension/com.distriqt.GoogleTagManager)


## Licensing 

Google Play Licensing library provides ability to query a trusted Google Play licensing server to determine whether the application is licensed to the current device user.

It is used by the following extensions:

- [com.distriqt.ExpansionFiles](http://airnativeextensions.com/extension/com.distriqt.ExpansionFiles)

It provides licensing functionality:

- [Licensing](https://github.com/distriqt/ANE-GooglePlayServices/wiki/Licensing)

