# cordova

## Build Commands

https://github.com/hamdifourati/cordova-android-builder.git

### Check dependencies are installed and configured.
```docker run -v D:\code_data\cordova\cordovaapp:/opt/src --rm hamdifourati/cordova-android-builder cordova requirements```

### Build Android apk
```docker run -v D:\code_data\cordova\cordovaapp:/opt/src --rm hamdifourati/cordova-android-builder cordova build```

## TODO

- Deactivate `HTTP` support and enforce `HTTPS`. See `config.xml`: 
    ``` <application android:usesCleartextTraffic="true" />```