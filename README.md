# Cordova AdMob Mediation Plugin

This mediation plugin is compatible with `cordova-plugin-admob-free` and `admob-plus`.

## Installation

```sh
cordova plugin add cordova-plugin-admob-mediation --save
```

### If you encounter Build Error  ':app:checkDebugDuplicateClasses'

To bypass this error make changes to 'Platform > Android > Project.properties' file and use latest version of play-services

``
cordova.system.library.1=com.google.android.gms:play-services-base:17.0.0
cordova.system.library.2=com.google.android.gms:play-services-ads:17.0.0
``
