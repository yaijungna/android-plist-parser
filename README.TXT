Android PList parser is a SAX-based implementation of a XML PList parser
for Android.  XML PList is a format developed by Apple Inc.  PLists are commonly used in Apple application development on Cocoa and the iPhone SDK, and the XML format is especially used for iPhone applications.

License
-------
Licensed under Creative Commons Attribution 3.0 Unported license.
http://creativecommons.org/licenses/by/3.0/

You are free to copy, distribute and transmit the work, and to adapt the work. You must attribute android-plist-parser to Free Beachler (http://www.freebeachler.com).

The Android PList parser (android-plist-parser) is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Project
-------
The project has two modules: android-plist-parser-app and android-plist-parser-test.  The Android unit tests can be run from Eclipse (you must have ADT installed) or with the Maven.

If you use maven to run the tests, you'll need to install android-maven-plugin.  Instructions can be found at http://code.google.com/p/maven-android-plugin/wiki/GettingStarted.

Source
------
The main objective of the project is to provide you with consumable source code for your application.  You may also want to consider using a maven build to generate a JAR for use in your application (and comment out the test module for this).

Known Issues
------------
Base64 support completely untested.  If you implement, please contribute back to the project.

PList - Copyright 2010 Apple Inc. All Rights Reserved.