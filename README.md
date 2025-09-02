# adflowtptu
adflow&amp;topon_thinkup
AdFlow Ad SDK Integration Documentation

Overview

AdFlow Advertising SDK is an advertising mediation platform that provides an integrated solution for rewarded video and interstitial ads for mobile app developers. This SDK needs to be used in conjunction with the TOPON platform. It only requires the initialization and loading/displaying of ads using topon, and no additional operations are required. This SDK does not contain any gambling, adult or other illegal advertising content and is fully compliant with all app store policies.

Features:


1.Supports Rewarded Video Ads

﻿
2.Supports Interstitial Ads

﻿
3.Smart optimization

﻿
4.High performance with low latency

﻿
5.Strict ad content review mechanism

﻿
6.Supports both Android platforms


Integration Requirements

1.Minimum Android API level: 26 (Android 8.0)


2.Requires internet permission


Important Notes:

1.Load ads at appropriate times to avoid unnecessary traffic consumption


2.Handle reward callbacks properly after showing rewarded video ads


3.Show interstitial ads at natural breakpoints in your app


4.Avoid frequent calls to ad loading APIs


How to Use:

This SDK is similar to admob and is directly integrated into the TOPON platform. Therefore, only TOPON initialization and loading of advertising code are required, and no additional operations are needed to use it


INSTALLATION


Adflow SDKs are published to jitpack as independent modules. To utilize a feature listed above include the appropriate dependency (or dependencies) listed below in your app/build.gradle file.


dependencies {

    implementation("com.github.adflowsdk:adflowtptu:3.1.04")
    
}
Note: 'com.github.adflowsdk:adflowtp:2.2.12' is based on the TopOn version library: com.anythink.sdk:core-tpn:6.4.87
Please use the corresponding version. If the version is different, please contact customer service.

You may also need to add the following to your project/build.gradle file.



buildscript {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
