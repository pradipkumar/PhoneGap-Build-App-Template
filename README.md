# PhoneGap Build App Template

_Copyright (c) 2012 Daniele Veneroni. Released under MIT License._

PhoneGap Build App Template is a template (a ready-to-use project) to create web apps and it's formatted to be easily wrapped on a stand-alone application using PhoneGap Build to build apps for iOS, Android, Windows Phone, BlackBerry, WebOS and Symbian.

You can easily replace or modify the resources of the project to create your own app.

## Project Structure:

### index.html
Your main page, that's the first page that the app will show when loaded.

### config.xml
The configurations file. See [Using config.xml](https://build.phonegap.com/docs/config-xml) to learn how to personalize yours. It's already formatted with the most common settings.

### icon.png, splash.png
The essential icon and splash screen. These are used only if the app runs on a device that doesn't support any of the provided icons or splash screens.

### icons folder
Contains all formats of icons required for the various operating systems.

### splash folder
Contains all formats of splash screens required for the various operating systems.

### lib folder
Contains all the libraries, frameworks, CSS and images needed for the app. Provided frameworks:
* **add2home** - it shows a message to allow the user to create a web app container on iOS from the browser version
