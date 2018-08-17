# auto-logistics-service-android-package

An Android library package for enabling routing last-mile deliveries to dispatch riders in traffic by sending OpenCellID data via Pull USSD.

## Online Resources (Read Up)

- [Telephony API for sending and intecepting USSD Android 8.0](https://stackoverflow.com/questions/5477597/how-is-it-possible-to-do-ussd-requests-on-android)
- [Intent for intercepting and receiving USSD calls text results in Android 2.3 - 4.1](https://github.com/alaasalman/ussdinterceptor)

Prior to Android 4.2 (KitKat), intercepting USSD requests was possible. It was removed for security concerns and now has reappeared in Android 8.0 (Oreo). However, Android 8.0 (Oreo) is still in very small distribution in the market. Pull USSD is seemingly the cheapest option to implement a completely offline mobile app that can send location information to a coordinating web server which uses [this package](https://github.com/isocroft/auto-logistics-service-router). This library targets only Anroid 4.0 and 4.1 only. Mobile phones using Android 4.0,4.1 are already rediculously cheap and accessible unlike mobile phones using Android 8.0. Furthermore, Android 8.0 will be targeted by this library in the future. Here is a **Stack Overflow** brief discussion on how to extract LAC/CID data from a mobile phone SIM card using the [Android Native Telephony API on Android_4.1](https://stackoverflow.com/questions/4152373/how-to-know-location-area-code-and-cell-id-in-android-phone/).
