# cordova-banner-notifications
This plugin was created to support showing banner notifications at the top of the application in cordova. This is meant for iOS to show notifications while the app is in the foreground. The notification structure is easy to use and able to support function callbacks on clicking the banner.

## Supported Features:
- Scrolling text
- Banner colour customization
- Text colour customization
- In/Out Animation customization
- Adding / removing onclick functions
- Duration customization
- Banner size: big + small

## Sample

Here is an example of the 'big' style banner notification:

<img src="https://github.com/DavidBriglio/cordova-banner-notification/blob/master/sample/LargeNotificationSample.png" width="50%"/>

```javascript
//Big Banner
cordova.plugins.notification.banner.show({
  message:"New Notification",
  //style: "big",
  backcolor:{
    red: 255,
    blue: 50
  }
});
```



Here is an example of the 'small' style banner notification:

<img src="https://github.com/DavidBriglio/cordova-banner-notification/blob/master/sample/SmallNotificationSample.png" width="50%"/>

```javascript
//Small Banner
cordova.plugins.notification.banner.show({
  message:"New Notification",
  style: "small",
  backcolor:{
    red: 255,
    blue: 50
  }
});
```



## Supported Platforms:
- iOS (Tested on iOS 9)

## Installation:
This plugin can be installed from CLI:

```bash
cordova plugins add https://github.com/DavidBriglio/cordova-banner-notification
```

## Questions?
Please see the wiki for how to use the plugin.

Feel free to send me a message, open an issue, or make pull requests!


## License

This software is released under the MIT License.

David Briglio 2016.

