# Changelog
1. Added network permission for Android build
2. Change App label for Android build
3. Automatic wake-on-lan on startup
4. Added saving of MAC address, IP address and token
5. Custom layout
6. Hardware volume button support (overlay permission required)
7. Theming, transparent notification bar, white notification icons, for both iOS and Android; matching colored splash screen for Android

# Notes
1. The "Connect" button at center top will be hidden once it is connected.
2. It will save the IP, Wifi MAC and token of the first connected TV. If your TV changed IP, you will need to remove app data.
3. Hardware volume button on iOS will not work once your iOS device reached maximum or minimum. See [hardware_buttons](https://pub.dev/packages/hardware_buttons) for more information.


# Flutter remote controller for Smart TVs models (2016 and up)

A dart implementation for [samsungtv](https://github.com/christian-bromann/samsungtv) by [Christian Bromann](https://github.com/christian-bromann)

Inspired from [Universal Remote](https://apps.apple.com/us/app/universal-remote-tv-smart/id1401880138)

You can discover Samsung Smart TVs in your network using the discover button. It uses the UPNP protocol to lookup services.

<img src="screens/screen.png" width="400" />
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
