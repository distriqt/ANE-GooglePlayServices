###### 2026.02.20 [v32.1.2]

```
fix(fir-adidsupport): correct ios library name
```

###### 2026.02.19 [v32.1.1]

```
fix(fir-core): correct ios framework packaging (resolves https://github.com/distriqt/ANE-Firebase/issues/519) 
```

###### 2026.02.17 [v32.1.0]

```
Update Firebase dependencies to the latest versions (iOS SDK v12.9.0 and Android SDK BOM v34.9.0).
Several other dependencies have also been updated to their latest versions, 
including AdMob SDK v24.9.0, Ads Identifier SDK v19.3.0, Auth SDK v22.3.0, Base SDK v19.2.0, Cronet SDK v19.0.3, and Fitness SDK v22.1.0.

### Updates

feat(fir-core,fir-messaging,fir-adidsupport,fir-ondeviceconversion): update firebase ios sdk v12.9.0
feat(fir-core,fir-messaging,fir-adidsupport,fir-ondeviceconversion): update firebase android sdk bom v34.9.0
feat(ads): update admob sdk v24.9.0
feat(adsidentifier): update sdk v19.3.0
feat(auth): update sdk v22.3.0
feat(base): update sdk v19.2.0
feat(cronet): update sdk v19.0.3
feat(fitness): update sdk v22.1.0
```

###### 2025.09.24 [v32.0.1]

```
feat(ads): update admob sdk v24.6.0
```

###### 2025.08.26 [v32.0.0]

```
feat(fir-adidsupport): update firebase sdk: android v34.1.0 ios v12.1.0
feat(fir-core): update firebase core sdk: android v34.1.0 ios v12.1.0
feat(fir-messaging): update firebase messaging sdk: android v25.0.0 ios v12.1.0
feat(fir-ondeviceconversion): update firebase messaging sdk: android v34.1.0 ios v12.1.0
feat(ads): update admob sdk v24.5.0
feat(adsidentifier): rollback adsidentifier sdk v18.1.0 (resolves https://github.com/distriqt/ANE-Adverts-Mediation/issues/89)
feat(auth): update auth sdk v21.4.0
feat(gamesv2): update games v2 sdk v21.0.0
feat(maps): update maps sdk v19.2.0
```

###### 2025.04.30 [v31.1.0]

```
feat: update gradle build - NOTE: requires using gradle version 8.9
feat(ads): update admob sdk v24.2.0
feat(ads-identifier): update ads identifier sdk v18.2.0
feat(auth): update auth sdk v21.3.0
feat(location): update location sdk v21.3.0
feat(recaptcha): update recaptcha sdk v17.1.0
feat(tagmanager): update tag manager sdk v18.3.0
```

###### 2025.03.21 [v31.0.3]

```
fix(playservices-base): remove dependency causing incorrect addition of AD_ID permission
```

###### 2025.01.20 [v31.0.2]

```
feat(fir-ondeviceconversion): new dependency for the Firebase On-Device Measurement library (https://github.com/distriqt/ANE-Firebase/issues/505)
```

###### 2025.01.20 [v31.0.1]

```
fix(fir-core): add additional ios frameworks that were causing conflicts from multiple extensions (https://github.com/airsdk/Adobe-Runtime-Support/issues/3644)
```

###### 2024.12.05 [v31.0.0]

```
Major update - move to new gradle build process

In this update we have moved all the extensions to use the newer gradle dependencies process. 

feat: move to gradle dependencies
feat(fir-core,fir-messaging,fir-adidsupport): update firebase ios sdk v11.5.0
```

###### 2024.10.16 [v30.3.0]

```
feat(playservices-ads): update ads sdk to v23.4.0
feat(playservices-base): update base sdk to v18.5.0
feat(playservices-analytics): update analytics sdk to v18.1.0
```

###### 2024.09.19 [v30.2.0]

```
fix(fir-core): fix build issue that caused missing dependecnies (resolves https://github.com/distriqt/ANE-Firebase/issues/499)
feat(adsidentifier): update play-services-adsidentifier v18.1.0
feat(appset): update play-services-appset v16.1.0
feat(auth): update play-services-auth v21.2.0
feat(cloudmessaging): update play-services-cloud-messaging v17.3.0
feat(cronet): update play-services-cronet v18.1.0
feat(fitness): update play-services-fitness v21.2.0
feat(games): update play-services-games v23.2.0
feat(identity): update play-services-identity v18.1.0
```

###### 2024.08.27 [v30.1.0]

```
feat(playservices-ads): update ads sdk to v23.3.0
```

###### 2024.08.19 [v30.0.0]

```
feat(gamesv2): add playservices games-v2 dependency
```

###### 2024.05.21 [v29.0.2]

```
feat(playservices-base): remove min sdk 24 requirement in preparation of AIR update
```

###### 2024.05.16 [v29.0.1]

```
feat(playservices-ads): update ads sdk v23.1.0
```

###### 2024.05.16 [v29.0.0]

```
feat(fir-core): update firebase sdk: android bom v33.0.0 ios v10.25.0
feat(fir-adidsupport): update firebase sdk: android bom v33.0.0 ios v10.25.0
feat(fir-messaging): update firebase messaging sdk v24.0.0
feat(playservices-auth): update auth to v21.1.1
feat(playservices-base): update base to v18.4.0 (and compatible dependencies)
feat(playservices-cloudmessaging): update cloudmessaging to v17.2.0
```

###### 2024.04.17 [v28.3.2]

```
feat(playservices-cronet): add new cronet dependency v18.0.1
```

###### 2024.04.03 [v28.3.1]

```
feat(android-play): update to v2.0.3 of the Google Play Core library
```

###### 2024.03.28 [v28.3.0]

```
feat(playservices-ads): update to v23.0.0
```

###### 2023.10.04 [v28.2.2]

```
feat(fir-core): update firebase datatransport and installations dependencies 
feat(fir-messaging): update firebase inapp messaging to v20.3.5
fix(fir-core): resolved duplicate definition (resolves #30)
```

###### 2023.09.22 [v28.2.1]

```
fix(fir-core): correct swift flags used for ios packaging
```

###### 2023.08.18 [v28.2.0]

```
feat(playservices-ads): update to v22.2.0
```

###### 2023.08.15 [v28.1.0]

```
fix(fir-messaging): critical fix for incorrectly packaged ios build 
```

###### 2023.08.11 [v28.1.0]

```
feat(fir-messaging): add firebase messaging sdk v23.1.0 as separated dependency
```

###### 2023.07.13 [v28.0.1]

```
feat(airpackage): add platforms to extensions to allow apm to selectively deploy the extensions
```

###### 2023.07.04 [v28.0.0]

```
Updates to latest GPS versions and firebase bom 32.1.1

feat(firebase): update firebase, android bom v32.1.1, ios v10.11.0
feat(fitness): add fitness sdk v21.1.0
feat(ads): update ads sdk v22.1.0
feat(analytics): update analytics sdk v18.0.3
feat(auth): update auth sdk v20.5.0
feat(base): update base sdk v18.2.0
feat(games): update games sdk v23.1.0
feat(location): update location sdk v21.0.1
feat(maps): update maps sdk v18.1.0
feat(tagmanager): update tagmanager sdk v18.0.3
```

###### 2023.01.12 [v27.3.2]

```
feat(appset): update air package dependencies
```

###### 2023.01.11 [v27.3.1]

```
feat(android-play): update sdk to v1.10.3
feat(fir-core): remove bitcode and add no-objc-msgsend-selector-stubs compiler flag 
```

###### 2022.11.18 [v27.3.0]

```
feat(playservices-ads): update ads library to v21.3.0
```

###### 2022.06.24 [v27.2.0]

```
feat(playservices-ads): update to v21.0.0
feat(playservices-base): update some of the base libs for ads v21.0.0 support 
```

###### 2022.06.23 [v27.1.0]

```
feat(fir-adidsupport): add new firebase sdk dependency for adding ad id support to ios
feat(fir-core): update ios firebase sdk to v8.15.0
feat(appset): add new extension library and example for playservices appset library
```

###### 2022.03.15 [v27.0.2]

```
Correct firebase core dependency
```

###### 2022.03.08 [v27.0.1]

```
Update cloud messaging to v17.0.2
```

###### 2022.03.08 [v27.0.0]

```
Updates to latest GPS versions and for firebase bom 29.0.4
Add recaptcha extension
Removed excessive resources from extensions and cleaned up versioning
```

###### 2021.09.09 [v26.7.1]

```
Updated com.google.android.play to v1.10.1
```

###### 2021.08.20 [v26.7.0]

```
AIR packages for Google Play dependency libraries and some minor build updates
```

###### 2021.07.13 [v26.6.0]

```
Updated AdMob Ads SDK to v20.2.0, changed resource references in Base extension
```

###### 2021.06.04 [v26.5.0]

```
Updated AdMob Ads SDK to v20.1.0
```

###### 2021.05.11 [v26.4.0]

```
Updated to latest Google Play Services and Firebase SDKs
 - Ads v20.0.0

Corrected issue with Games dependency
Added Provider Installer functionality (resolves #20)
```

###### 2021.04.27 [v26.3.2]

```
Corrected build issue with Games dependency
```

###### 2021.04.14 [v26.3.1]

```
Updated play services ads to v19.8.0
```

###### 2021.01.20 [v26.3.0]

```
Updated to latest Google Play Services and Firebase SDKs
```

###### 2020.10.12 [v20.5.1]

```
Corrected builds
```

###### 2020.10.04 [v20.5.0]

```
Updated Ads to v19.4.0
```

###### 2020.09.01 [v20.4.0]

```
Updated to latest Google Play Services and Firebase SDKs
```

###### 2020.08.25 [v20.3.0]

```
Added the Play Core library com.google.android.play
```

###### 2020.08.14 [v20.2.1]

```
Added Licensing to provide access to Google Play Licensing
Separated AdsIdentifier to avoid Ads SDK warning from Google
Added SWCs
```

###### 2020.05.25 [v20.2.0]

```
Updated firebase core iOS v6.11.0
```

###### 2020.05.04 [v20.1.1]

```
Updated to latest Google Play Services
```

###### 2020.03.20 [v20.1.0]

```
Android X migration (resolves #9)
```

###### 2019.09.30 [v16.0.5]

```
Fixed issue with ApiAvailablity checks
```

###### 2019.08.12 [v16.0.5]

```
Android 64bit support (resolves #6)
```

###### 2019.03.02 [v16.0.5]

```
Removed unused iOS implementations
Added version information (resolves distriqt/ANE-Firebase#190)
```

###### 2019.02.26 [v16.0.5]

```
Updated minimum iOS version to 8.0
```

###### 2019.02.26 [v16.0.5]

```
Updated minimum iOS version to 8.0
```

###### 2018.12.12 [v16.0.5]

```
Updated Ads to 17.1.2
```

###### 2018.11.27 [v16.0.5]

```
Updated to Google Play Services v16.0.5
```

###### 2018.06.01 [v15.0.1]

```
Updated to Google Play Services v15.0.1
```

###### 2018.02.22 [v11.8.0]

```
Updated to Google Play Services v11.8.0
```

###### 2017.11.24 [v11.0.4]

```
Added AppInvite client library extension
```

###### 2017.08.09 [v11.0.4]

```
Added GoogleApiAvailability functionality
```

###### 2017.08.04 [v11.0.4]

```
Updated to Google Play Services v11.0.4
```

###### 2017.07.10 [v11.0.2]

```
Updated to Google Play Services v11.0.2
```

###### 2017.06.10 [v11.0.0]

```
Updated to Google Play Services v11.0.0
```

###### 2017.05.30 [v10.2.6]

```
Updated to Google Play Services v10.2.6
```

###### 2017.03.01 [v10.2.0]

```
Updated to Google Play Services v10.2.0
```

###### 2017.02.02 [v10.0.1]

```
Release v10.0.1
```

###### 2017.01.30 [v10.0.1]

```
Updated to Google Play Services v10.0.1
```

###### 2016.11.22 [v9.8.0]

```
Updated to Google Play Services v9.8.0
```

###### 2016.10.27 [v9.6.1]

```
Updated to Google Play Services v9.6.1
```

###### 2016.08.10 [v9.4.0]

```
Updated to Google Play Services v9.4.0
```

###### 2016.08.10 [v..]

```
Updated to Google Play Services v9.4.0
```

###### v9.2.1 2016.07.26

```
Updated to v9.2.1
```

###### 2016.07.16

```
Updated to be compatible with latest Core ANE
```

###### 2016.03.02

```
Updated to v8487000
```

###### 2015.11.18

```
Update to latest Google Services lib
```

###### 2015.11.18

```
Update to latest Google Services lib
```

###### 2015.11.05

```
Updated to latest SDK
```

###### 2015.06.15

```
Removed debug code from AS lib
iOS: Updated to latest common lib
Android: Windows: Fix for bug in AIR packager resulting in missing resources
```

###### 2015.04.27

```
Android: Updated to version 7095000
```

###### 2015.02.23

```
Android: Added the android support v4 library
```
