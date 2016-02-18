OpenNoteScanner
===============

This little application provides a way on scanning handwritten notes and printed documents.

It automatically detect the edge of the paper over a contrastant surface.

If you have RocketBook Wave notebook or home printed pages it automatically detects the qrcode printed on the bottom right corner and scans the page immediately.

After the page is detected, it compensates any perspective from the image adjusting it to a 90 degree top view and saves it on a folder on the device.

It is also possible to launch the application from any other application that asks for a picture, just make sure that there is no default application associated with this action.

**TODO:** place some screenshots here

How to Install
--------------

It is possible to install it directly from Google Play Store through [this link](https://play.google.com/store/apps/details?id=com.todobom.opennotescanner).

Binary APK file is available in the [releases section](https://github.com/ctodobom/OpenNoteScanner/releases) of the project. If you install the binary manually you will need also the OpenCV Manager. The best way on doing this manually is downloading the [OpenCV SDK for Android](http://sourceforge.net/projects/opencvlibrary/files/opencv-android/3.1.0/OpenCV-3.1.0-android-sdk.zip/download) on a computer, unzip it and pick the correct APK for your device in the ```apk``` folder. Normally for phone devices, the armeabi-v7a is the correct one. If you have Play Store access, Open Note Scanner will direct you to it in order to download OpenCV Manager if it is not found in the device.


Instructions for building
-------------------------

For building is needed to import the OpenCV library on the project.

**TODO:** place better instructions here.

History
-------

I've started this app on a brazilian holyday "extended weekend" based on the fact that I was unable to find any open source application that does this job. I was mainly inspired on the RocketBook Wave closed source application.

I really do not know if I will extend more the application, but I am writing bellow some objectives to make it better.

Roadmap
-------

* enhance the image gallery of scanned documents
* register a share action in order to obtain documents already pictured through standard camera apps
* implement automatic action based on the RocketBook Wave marking of the page

License
-------

Copyright 2016 - Claudemir Todo Bom

Software licensed under the GPL version 2 available in GPLv2.TXT and
online on http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt.

Use parts from other developers, sometimes with small changes,
references on autorship and specific licenses are on individual
source files.
