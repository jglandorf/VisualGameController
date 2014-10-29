# VisualGameController

The Visual Game Controller app is designed to run on an Android TV device and displays visual feedback for the buttons of an attached game controller.

This sample is originally from https://github.com/googlesamples/androidtv-VisualGameController

It has been modified as follows:

* Set up as an Android Studio project, with one module, named 'tv'
* tv/.../ControllerView.java - look for devices with SOURCE_GAMEPAD _and_ (instead of _or_)SOURCE_JOYSTICK bits set to avoid conflicts with USB keyboards.
* tv/.../res\values\attrs.xml - removed tag <attr name="showText" format="boolean"/> to avoid duplicate attribute error
* tv/build.gradle - updated the SDK and libraries to 21

## Dependencies
* Android SDK v7 appcompat library
* Android SDK v4 support library

## Setup Instructions
* Compile and deploy to your Android TV device.
* If using gradle, make sure you update build.gradle and settings.gradle to reflect the name you gave your VisualGameController project when you cloned it.

## References and How to report bugs
* [Developer Documentation](http://developers.google.com/)

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE

## Google+
Google Developers Page on Google+ [https://plus.google.com/+GoogleDevelopers/posts](https://plus.google.com/+GoogleDevelopers/posts)

## Change List
