# PhoneGap Developer App

> Available in an app store near you!

## Overview

The PhoneGap Developer app is a testing utility for web developers and designers
using the PhoneGap framework. After installing the PhoneGap Developer app you
can connect to your PhoneGap desktop app to instantly view and test your project
on the device.

For more information, see [app.phonegap.com][3].

## Download

- [Android Google Play][1]
- [Apple AppStore][2]
- [Windows Phone store][7]

## Development

### Compile the Application

    $ npm install -g phonegap@3.4.0-0.19.21
    $ phonegap run ios
    $ phonegap run android
    $ phonegap run wp8

For developers wishing to use the platform SDKs (Xcode, Eclipse, Visual Studio),
please build once with the CLI to correctly populate the platform assets:

    $ phonegap build <platform>

### Compiling LESS / CSS

When making changes to the CSS styling, remember to compile the LESS files:

    $ npm install
    $ npm run less

### Commits, Tags, and Releases

See the [CONTRIBUTING.md][6] file for details.

[1]: https://play.google.com/store/apps/details?id=com.adobe.phonegap.app
[2]: https://itunes.apple.com/app/id843536693
[3]: http://app.phonegap.com
[4]: http://github.com/phonegap/connect-phonegap
[5]: http://github.com/phonegap/phonegap-cli
[6]: https://github.com/phonegap/phonegap-app-developer/blob/master/CONTRIBUTING.md
[7]: http://www.windowsphone.com/en-us/store/app/phonegap-developer/5c6a2d1e-4fad-4bf8-aaf7-71380cc84fe3

